BSD in France - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in France.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/France/Desktop/README.md) and [notebooks](/Location/France/Notebook/README.md).

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

Total: 624

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Deciso        | NetBoard-A20                | Notebook    | [33ca458105](https://bsd-hardware.info/?probe=33ca458105) | Mar 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [9696e7d17f](https://bsd-hardware.info/?probe=9696e7d17f) | Mar 29, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [7945f26073](https://bsd-hardware.info/?probe=7945f26073) | Mar 25, 2023 |
| Intel         | H81U                        | Notebook    | [af9a6469c9](https://bsd-hardware.info/?probe=af9a6469c9) | Mar 24, 2023 |
| Acer          | Revo 70                     | Desktop     | [50d93bea69](https://bsd-hardware.info/?probe=50d93bea69) | Mar 23, 2023 |
| MSI           | H81I                        | Desktop     | [4983a6a077](https://bsd-hardware.info/?probe=4983a6a077) | Mar 22, 2023 |
| HP            | 805A                        | Desktop     | [d90c74af40](https://bsd-hardware.info/?probe=d90c74af40) | Mar 21, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [55dc82af1c](https://bsd-hardware.info/?probe=55dc82af1c) | Mar 20, 2023 |
| MSI           | H81I                        | Desktop     | [a1981bf557](https://bsd-hardware.info/?probe=a1981bf557) | Mar 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [03cf8c47dc](https://bsd-hardware.info/?probe=03cf8c47dc) | Mar 17, 2023 |
| YENTEK        | R250                        | Desktop     | [fc42406b39](https://bsd-hardware.info/?probe=fc42406b39) | Mar 15, 2023 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [864a4017cb](https://bsd-hardware.info/?probe=864a4017cb) | Mar 15, 2023 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [25256b1698](https://bsd-hardware.info/?probe=25256b1698) | Mar 14, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [bc21ae472e](https://bsd-hardware.info/?probe=bc21ae472e) | Mar 13, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [d210b12607](https://bsd-hardware.info/?probe=d210b12607) | Mar 13, 2023 |
| Sony          | VGN-FZ19VN                  | Notebook    | [73809d943a](https://bsd-hardware.info/?probe=73809d943a) | Mar 13, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ad6f854637](https://bsd-hardware.info/?probe=ad6f854637) | Mar 12, 2023 |
| Supermicro    | X11SSL-F                    | Server      | [c9ddd32406](https://bsd-hardware.info/?probe=c9ddd32406) | Mar 12, 2023 |
| Dell          | 07WP95 A02                  | Desktop     | [f45a92348a](https://bsd-hardware.info/?probe=f45a92348a) | Mar 12, 2023 |
| Dell          | Precision 7720              | Notebook    | [01f5f21b76](https://bsd-hardware.info/?probe=01f5f21b76) | Mar 12, 2023 |
| HP            | 3398                        | Desktop     | [20bcb682d8](https://bsd-hardware.info/?probe=20bcb682d8) | Mar 11, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3548f4efa2](https://bsd-hardware.info/?probe=3548f4efa2) | Mar 11, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [88de48013c](https://bsd-hardware.info/?probe=88de48013c) | Mar 10, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495 20NKS0HN1N    | Notebook    | [af190c38e9](https://bsd-hardware.info/?probe=af190c38e9) | Mar 10, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [223879138d](https://bsd-hardware.info/?probe=223879138d) | Mar 10, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [e70d97f7d6](https://bsd-hardware.info/?probe=e70d97f7d6) | Mar 09, 2023 |
| Dell          | Latitude D620               | Notebook    | [8b3ad4e8b9](https://bsd-hardware.info/?probe=8b3ad4e8b9) | Mar 09, 2023 |
| Dell          | Latitude D620               | Notebook    | [d42a8ee079](https://bsd-hardware.info/?probe=d42a8ee079) | Mar 09, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | Desktop     | [98fe8cc428](https://bsd-hardware.info/?probe=98fe8cc428) | Mar 09, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [3c5f826544](https://bsd-hardware.info/?probe=3c5f826544) | Mar 07, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [2a6207fb45](https://bsd-hardware.info/?probe=2a6207fb45) | Mar 07, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [8d052cbf4c](https://bsd-hardware.info/?probe=8d052cbf4c) | Mar 06, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8e9e9d3ce2](https://bsd-hardware.info/?probe=8e9e9d3ce2) | Mar 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c93a7e552](https://bsd-hardware.info/?probe=8c93a7e552) | Mar 04, 2023 |
| Intel         | D510MO AAE76523-403         | Desktop     | [0da634580f](https://bsd-hardware.info/?probe=0da634580f) | Mar 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [85fdc49ec4](https://bsd-hardware.info/?probe=85fdc49ec4) | Mar 03, 2023 |
| HP            | 1496                        | Desktop     | [f2acf09862](https://bsd-hardware.info/?probe=f2acf09862) | Mar 02, 2023 |
| HP            | 212B                        | Desktop     | [185934706d](https://bsd-hardware.info/?probe=185934706d) | Mar 02, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [9fa1054078](https://bsd-hardware.info/?probe=9fa1054078) | Mar 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6d1d3ded0d](https://bsd-hardware.info/?probe=6d1d3ded0d) | Feb 28, 2023 |
| HP            | 8055                        | Desktop     | [faadcd3e41](https://bsd-hardware.info/?probe=faadcd3e41) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [2ab690000c](https://bsd-hardware.info/?probe=2ab690000c) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [ae0dc68ba6](https://bsd-hardware.info/?probe=ae0dc68ba6) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [aef791947c](https://bsd-hardware.info/?probe=aef791947c) | Feb 23, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [3dae7e3ebb](https://bsd-hardware.info/?probe=3dae7e3ebb) | Feb 23, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [6669622646](https://bsd-hardware.info/?probe=6669622646) | Feb 23, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [d23ae47425](https://bsd-hardware.info/?probe=d23ae47425) | Feb 23, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [fb908ee344](https://bsd-hardware.info/?probe=fb908ee344) | Feb 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [3e1b050969](https://bsd-hardware.info/?probe=3e1b050969) | Feb 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d23b2cfe5a](https://bsd-hardware.info/?probe=d23b2cfe5a) | Feb 17, 2023 |
| HP            | 198E                        | Desktop     | [1f9a7e4f9b](https://bsd-hardware.info/?probe=1f9a7e4f9b) | Feb 17, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [0f589ba9bf](https://bsd-hardware.info/?probe=0f589ba9bf) | Feb 16, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [95a8784d4a](https://bsd-hardware.info/?probe=95a8784d4a) | Feb 16, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [ffc9e123b4](https://bsd-hardware.info/?probe=ffc9e123b4) | Feb 14, 2023 |
| Dell          | OptiPlex 9020               | Desktop     | [0c8a5f8dfa](https://bsd-hardware.info/?probe=0c8a5f8dfa) | Feb 13, 2023 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [ba1b9f0010](https://bsd-hardware.info/?probe=ba1b9f0010) | Feb 12, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [4c4e675427](https://bsd-hardware.info/?probe=4c4e675427) | Feb 10, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [e376971bd6](https://bsd-hardware.info/?probe=e376971bd6) | Feb 09, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [78a978a8d4](https://bsd-hardware.info/?probe=78a978a8d4) | Feb 06, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [5462140da0](https://bsd-hardware.info/?probe=5462140da0) | Feb 05, 2023 |
| HP            | 8350                        | Desktop     | [9ec1605295](https://bsd-hardware.info/?probe=9ec1605295) | Feb 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [6096b00a0c](https://bsd-hardware.info/?probe=6096b00a0c) | Jan 29, 2023 |
| AMD           | Larne CRB                   | Desktop     | [8b9a301b47](https://bsd-hardware.info/?probe=8b9a301b47) | Jan 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [d36217b166](https://bsd-hardware.info/?probe=d36217b166) | Jan 26, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [0c75494953](https://bsd-hardware.info/?probe=0c75494953) | Jan 25, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [081d22fbe2](https://bsd-hardware.info/?probe=081d22fbe2) | Jan 24, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [a35053ad38](https://bsd-hardware.info/?probe=a35053ad38) | Jan 24, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [476203ee86](https://bsd-hardware.info/?probe=476203ee86) | Jan 23, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [4af2cc1909](https://bsd-hardware.info/?probe=4af2cc1909) | Jan 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| Dell          | Precision 5540              | Notebook    | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| Dell          | PowerEdge R710              | Desktop     | [720e99b25e](https://bsd-hardware.info/?probe=720e99b25e) | Jan 17, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [7cbcb5b513](https://bsd-hardware.info/?probe=7cbcb5b513) | Jan 12, 2023 |
| Lenovo        | 3138                        | Desktop     | [14876c7561](https://bsd-hardware.info/?probe=14876c7561) | Jan 12, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [4014cc42ed](https://bsd-hardware.info/?probe=4014cc42ed) | Jan 08, 2023 |
| Lenovo        | ThinkStation D20 415575G    | Desktop     | [0a15d989e3](https://bsd-hardware.info/?probe=0a15d989e3) | Jan 08, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [0d13116822](https://bsd-hardware.info/?probe=0d13116822) | Jan 06, 2023 |
| Deciso        | Netboard A20                | Notebook    | [3ff47d2ce0](https://bsd-hardware.info/?probe=3ff47d2ce0) | Jan 06, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [334575b738](https://bsd-hardware.info/?probe=334575b738) | Dec 31, 2022 |
| Unknown       | Unknown                     | Firewall    | [72eaa7a90f](https://bsd-hardware.info/?probe=72eaa7a90f) | Dec 30, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [41094c24b2](https://bsd-hardware.info/?probe=41094c24b2) | Dec 27, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d62deb9883](https://bsd-hardware.info/?probe=d62deb9883) | Dec 26, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [33c59c687d](https://bsd-hardware.info/?probe=33c59c687d) | Dec 24, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [7bd99b62ab](https://bsd-hardware.info/?probe=7bd99b62ab) | Dec 19, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [c233fa7d25](https://bsd-hardware.info/?probe=c233fa7d25) | Dec 18, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [abe21b9c9e](https://bsd-hardware.info/?probe=abe21b9c9e) | Dec 18, 2022 |
| MSI           | MS-98C8                     | Desktop     | [a6e45c8e5f](https://bsd-hardware.info/?probe=a6e45c8e5f) | Dec 17, 2022 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [11d5b82cdd](https://bsd-hardware.info/?probe=11d5b82cdd) | Dec 17, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [342c99d07d](https://bsd-hardware.info/?probe=342c99d07d) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [dbbdd023e9](https://bsd-hardware.info/?probe=dbbdd023e9) | Dec 08, 2022 |
| ASUSTek       | G11CD                       | Desktop     | [7bc1746333](https://bsd-hardware.info/?probe=7bc1746333) | Dec 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c953c78309](https://bsd-hardware.info/?probe=c953c78309) | Dec 07, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [7f6194b56e](https://bsd-hardware.info/?probe=7f6194b56e) | Dec 07, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [218e00e7ea](https://bsd-hardware.info/?probe=218e00e7ea) | Dec 05, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [90279b62b7](https://bsd-hardware.info/?probe=90279b62b7) | Dec 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [54e89ef90b](https://bsd-hardware.info/?probe=54e89ef90b) | Dec 04, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [9497657cb2](https://bsd-hardware.info/?probe=9497657cb2) | Dec 04, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6a1a5865cb](https://bsd-hardware.info/?probe=6a1a5865cb) | Nov 30, 2022 |
| Panasonic     | CF-31-5                     | Notebook    | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| Supermicro    | X10SRG-F                    | Desktop     | [66b7819b2a](https://bsd-hardware.info/?probe=66b7819b2a) | Nov 27, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [787a2db2cd](https://bsd-hardware.info/?probe=787a2db2cd) | Nov 26, 2022 |
| Dell          | 0W13NR A07                  | Server      | [c5b09b219b](https://bsd-hardware.info/?probe=c5b09b219b) | Nov 24, 2022 |
| Medion        | E15415                      | Notebook    | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| Shuttle       | FS35V5                      | Mini pc     | [8b634987b4](https://bsd-hardware.info/?probe=8b634987b4) | Nov 13, 2022 |
| HP            | 806A                        | Desktop     | [9567b6949c](https://bsd-hardware.info/?probe=9567b6949c) | Nov 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [4adc5f7629](https://bsd-hardware.info/?probe=4adc5f7629) | Nov 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [47efa8b4bc](https://bsd-hardware.info/?probe=47efa8b4bc) | Nov 06, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [0312c464c4](https://bsd-hardware.info/?probe=0312c464c4) | Nov 05, 2022 |
| Dell          | 0G7WYD A01                  | Server      | [655a9e7af2](https://bsd-hardware.info/?probe=655a9e7af2) | Nov 04, 2022 |
| Dell          | Precision M4500             | Notebook    | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [9c133326c9](https://bsd-hardware.info/?probe=9c133326c9) | Nov 03, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [14f174bd7c](https://bsd-hardware.info/?probe=14f174bd7c) | Oct 26, 2022 |
| Intel         | H81U                        | Notebook    | [b0e1f80338](https://bsd-hardware.info/?probe=b0e1f80338) | Oct 24, 2022 |
| Dell          | Precision M4500             | Notebook    | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| ASUSTek       | E35M1-I DELUXE              | Desktop     | [2fdf1c6db6](https://bsd-hardware.info/?probe=2fdf1c6db6) | Oct 18, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e67cb3a0c5](https://bsd-hardware.info/?probe=e67cb3a0c5) | Oct 14, 2022 |
| HP            | 260 G3 DM                   | Desktop     | [3ad5292d71](https://bsd-hardware.info/?probe=3ad5292d71) | Oct 13, 2022 |
| HP            | Compaq nw8440 (RND39ET)     | Desktop     | [55bef385e3](https://bsd-hardware.info/?probe=55bef385e3) | Oct 13, 2022 |
| Intel         | H81U                        | Notebook    | [9b212d2264](https://bsd-hardware.info/?probe=9b212d2264) | Oct 13, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [5f271a82bf](https://bsd-hardware.info/?probe=5f271a82bf) | Oct 11, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [0f87a99ca7](https://bsd-hardware.info/?probe=0f87a99ca7) | Oct 11, 2022 |
| Lenovo        | 316E NOK                    | Mini pc     | [2a7c8f55cb](https://bsd-hardware.info/?probe=2a7c8f55cb) | Oct 10, 2022 |
| Clevo         | R130T                       | Desktop     | [6f8a6bf77c](https://bsd-hardware.info/?probe=6f8a6bf77c) | Oct 10, 2022 |
| Soekris En... | net6501                     | Desktop     | [1cb23f6bda](https://bsd-hardware.info/?probe=1cb23f6bda) | Oct 08, 2022 |
| Soekris En... | net6501                     | Desktop     | [03ee772b1f](https://bsd-hardware.info/?probe=03ee772b1f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [31ce3d5e46](https://bsd-hardware.info/?probe=31ce3d5e46) | Oct 07, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [36fb81bec0](https://bsd-hardware.info/?probe=36fb81bec0) | Oct 07, 2022 |
| PC Engines    | apu1                        | Desktop     | [1a8ff34d31](https://bsd-hardware.info/?probe=1a8ff34d31) | Oct 06, 2022 |
| Toshiba       | NB300                       | Notebook    | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell          | Precision M4500             | Notebook    | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [d3c50c8d60](https://bsd-hardware.info/?probe=d3c50c8d60) | Oct 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [16f6784862](https://bsd-hardware.info/?probe=16f6784862) | Sep 27, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [b8db4655e5](https://bsd-hardware.info/?probe=b8db4655e5) | Sep 26, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [ae535b0b49](https://bsd-hardware.info/?probe=ae535b0b49) | Sep 25, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8f4900d0e6](https://bsd-hardware.info/?probe=8f4900d0e6) | Sep 25, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [59886931c5](https://bsd-hardware.info/?probe=59886931c5) | Sep 24, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5029142d61](https://bsd-hardware.info/?probe=5029142d61) | Sep 22, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [1a754b2a9e](https://bsd-hardware.info/?probe=1a754b2a9e) | Sep 21, 2022 |
| HP            | 21D0                        | Desktop     | [43fa46655e](https://bsd-hardware.info/?probe=43fa46655e) | Sep 21, 2022 |
| HP            | 21D0                        | Desktop     | [463e2563d7](https://bsd-hardware.info/?probe=463e2563d7) | Sep 19, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [77727b5832](https://bsd-hardware.info/?probe=77727b5832) | Sep 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [95ae240b55](https://bsd-hardware.info/?probe=95ae240b55) | Sep 13, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [130de630ad](https://bsd-hardware.info/?probe=130de630ad) | Sep 10, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [4db37ff154](https://bsd-hardware.info/?probe=4db37ff154) | Sep 07, 2022 |
| AMD           | Larne CRB                   | Desktop     | [787a51fa78](https://bsd-hardware.info/?probe=787a51fa78) | Sep 03, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [11ac5a7932](https://bsd-hardware.info/?probe=11ac5a7932) | Sep 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [525631a32f](https://bsd-hardware.info/?probe=525631a32f) | Aug 28, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [d346cf971a](https://bsd-hardware.info/?probe=d346cf971a) | Aug 15, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [ab6603e750](https://bsd-hardware.info/?probe=ab6603e750) | Aug 13, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [649021e20c](https://bsd-hardware.info/?probe=649021e20c) | Aug 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [870dface68](https://bsd-hardware.info/?probe=870dface68) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [5e2f93a960](https://bsd-hardware.info/?probe=5e2f93a960) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [66fefba790](https://bsd-hardware.info/?probe=66fefba790) | Aug 06, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [81441a97b2](https://bsd-hardware.info/?probe=81441a97b2) | Aug 06, 2022 |
| HP            | 3397                        | Desktop     | [6111a627d6](https://bsd-hardware.info/?probe=6111a627d6) | Aug 05, 2022 |
| AMD           | Larne CRB                   | Desktop     | [db094f95af](https://bsd-hardware.info/?probe=db094f95af) | Aug 04, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [ac69a3ecef](https://bsd-hardware.info/?probe=ac69a3ecef) | Aug 03, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [1b794b3563](https://bsd-hardware.info/?probe=1b794b3563) | Aug 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [5ac2fc150b](https://bsd-hardware.info/?probe=5ac2fc150b) | Aug 02, 2022 |
| HP            | 3397                        | Desktop     | [dac75fec6e](https://bsd-hardware.info/?probe=dac75fec6e) | Jul 31, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [0eaaa31106](https://bsd-hardware.info/?probe=0eaaa31106) | Jul 31, 2022 |
| Dell          | 0RH817 A00                  | Server      | [7d7740d447](https://bsd-hardware.info/?probe=7d7740d447) | Jul 30, 2022 |
| Gigabyte      | GB-BSi3-1115G4              | Desktop     | [4cd0769d75](https://bsd-hardware.info/?probe=4cd0769d75) | Jul 30, 2022 |
| AMD           | Larne CRB                   | Desktop     | [794541e833](https://bsd-hardware.info/?probe=794541e833) | Jul 29, 2022 |
| Dell          | 0M877N A02                  | Server      | [c1623d6f23](https://bsd-hardware.info/?probe=c1623d6f23) | Jul 26, 2022 |
| Dell          | 0G7WYD A01                  | Server      | [81586f6d39](https://bsd-hardware.info/?probe=81586f6d39) | Jul 22, 2022 |
| Dell          | 0G7WYD A01                  | Server      | [ce43e9f067](https://bsd-hardware.info/?probe=ce43e9f067) | Jul 22, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [59c576a4ba](https://bsd-hardware.info/?probe=59c576a4ba) | Jul 22, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [3fe3a46a7a](https://bsd-hardware.info/?probe=3fe3a46a7a) | Jul 21, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [bbca74a96f](https://bsd-hardware.info/?probe=bbca74a96f) | Jul 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [070ccc68f8](https://bsd-hardware.info/?probe=070ccc68f8) | Jul 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [9e54e446ef](https://bsd-hardware.info/?probe=9e54e446ef) | Jul 14, 2022 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [d43e397f02](https://bsd-hardware.info/?probe=d43e397f02) | Jul 10, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [b57457834e](https://bsd-hardware.info/?probe=b57457834e) | Jul 04, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [dca437b993](https://bsd-hardware.info/?probe=dca437b993) | Jul 01, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [6ce39c5e61](https://bsd-hardware.info/?probe=6ce39c5e61) | Jun 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ab2f42b567](https://bsd-hardware.info/?probe=ab2f42b567) | Jun 26, 2022 |
| Dell          | 0M877N A02                  | Server      | [c6f1ccfe6d](https://bsd-hardware.info/?probe=c6f1ccfe6d) | Jun 22, 2022 |
| Intel         | D945GCLF2 AAE46416-104      | Desktop     | [84f2afeff4](https://bsd-hardware.info/?probe=84f2afeff4) | Jun 21, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [25d5a77b59](https://bsd-hardware.info/?probe=25d5a77b59) | Jun 17, 2022 |
| HP            | 86E9 A                      | Desktop     | [1d1ac2dd90](https://bsd-hardware.info/?probe=1d1ac2dd90) | Jun 16, 2022 |
| Alienware     | M18xR2                      | Notebook    | [6d55881f6a](https://bsd-hardware.info/?probe=6d55881f6a) | Jun 15, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [8ba77d7208](https://bsd-hardware.info/?probe=8ba77d7208) | Jun 13, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [4be2393c8d](https://bsd-hardware.info/?probe=4be2393c8d) | Jun 11, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4e0a906acb](https://bsd-hardware.info/?probe=4e0a906acb) | Jun 11, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [776a4892d0](https://bsd-hardware.info/?probe=776a4892d0) | Jun 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Dell          | Latitude 7490               | Notebook    | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [f3ad761457](https://bsd-hardware.info/?probe=f3ad761457) | Jun 04, 2022 |
| Dell          | Latitude 7490               | Notebook    | [22224f46f4](https://bsd-hardware.info/?probe=22224f46f4) | Jun 02, 2022 |
| Acer          | Aspire E5-576               | Notebook    | [138e9fdeb4](https://bsd-hardware.info/?probe=138e9fdeb4) | May 31, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [9bacfc2b0e](https://bsd-hardware.info/?probe=9bacfc2b0e) | May 29, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [20814a930a](https://bsd-hardware.info/?probe=20814a930a) | May 18, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [115de395dd](https://bsd-hardware.info/?probe=115de395dd) | May 17, 2022 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [e8d2744812](https://bsd-hardware.info/?probe=e8d2744812) | May 12, 2022 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [0419c52079](https://bsd-hardware.info/?probe=0419c52079) | May 11, 2022 |
| ASRock        | A320M Pro4-F                | Desktop     | [f307756ddf](https://bsd-hardware.info/?probe=f307756ddf) | May 11, 2022 |
| Intel         | H81U                        | Notebook    | [550699602e](https://bsd-hardware.info/?probe=550699602e) | May 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [6cf944b0ef](https://bsd-hardware.info/?probe=6cf944b0ef) | May 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cf58c679ef](https://bsd-hardware.info/?probe=cf58c679ef) | May 08, 2022 |
| Intel         | H81U                        | Notebook    | [04646d1cc7](https://bsd-hardware.info/?probe=04646d1cc7) | May 05, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [5f9e266167](https://bsd-hardware.info/?probe=5f9e266167) | May 04, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [7d4dd8ba29](https://bsd-hardware.info/?probe=7d4dd8ba29) | May 04, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [3481513b0f](https://bsd-hardware.info/?probe=3481513b0f) | May 03, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0d5b872ec1](https://bsd-hardware.info/?probe=0d5b872ec1) | May 02, 2022 |
| Dell          | Latitude 7490               | Notebook    | [03c97fe4d9](https://bsd-hardware.info/?probe=03c97fe4d9) | May 02, 2022 |
| Dell          | Precision 7730              | Notebook    | [bdb3e3d4ce](https://bsd-hardware.info/?probe=bdb3e3d4ce) | Apr 30, 2022 |
| Dell          | Latitude 7490               | Notebook    | [1586880dd7](https://bsd-hardware.info/?probe=1586880dd7) | Apr 30, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [86ade7ce4b](https://bsd-hardware.info/?probe=86ade7ce4b) | Apr 30, 2022 |
| ASUSTek       | AM1I-A                      | Desktop     | [8fce57c9e4](https://bsd-hardware.info/?probe=8fce57c9e4) | Apr 25, 2022 |
| ASUSTek       | P5KR                        | Desktop     | [cf745ca0da](https://bsd-hardware.info/?probe=cf745ca0da) | Apr 23, 2022 |
| Dell          | Studio 1555                 | Notebook    | [6da8f97bcd](https://bsd-hardware.info/?probe=6da8f97bcd) | Apr 22, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [875d6b2da3](https://bsd-hardware.info/?probe=875d6b2da3) | Apr 22, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [a278852381](https://bsd-hardware.info/?probe=a278852381) | Apr 21, 2022 |
| Dell          | 06JWJY A01                  | Desktop     | [16f4cc5d53](https://bsd-hardware.info/?probe=16f4cc5d53) | Apr 20, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [ab8aea2f5c](https://bsd-hardware.info/?probe=ab8aea2f5c) | Apr 17, 2022 |
| Dell          | Latitude E5450              | Notebook    | [ca5eb083f9](https://bsd-hardware.info/?probe=ca5eb083f9) | Apr 16, 2022 |
| Deciso        | Netboard A10                | Desktop     | [6e0b916230](https://bsd-hardware.info/?probe=6e0b916230) | Apr 16, 2022 |
| HP            | 86E9 A                      | Desktop     | [be43a8efde](https://bsd-hardware.info/?probe=be43a8efde) | Apr 14, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [4b981630d7](https://bsd-hardware.info/?probe=4b981630d7) | Apr 13, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [06720f3c57](https://bsd-hardware.info/?probe=06720f3c57) | Apr 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [e6ba291c2d](https://bsd-hardware.info/?probe=e6ba291c2d) | Apr 12, 2022 |
| Jetway        | 1.0                         | Desktop     | [ac2ab09363](https://bsd-hardware.info/?probe=ac2ab09363) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e208e9425](https://bsd-hardware.info/?probe=4e208e9425) | Apr 10, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [ded0d1a114](https://bsd-hardware.info/?probe=ded0d1a114) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [14a6449380](https://bsd-hardware.info/?probe=14a6449380) | Apr 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [50833ab257](https://bsd-hardware.info/?probe=50833ab257) | Apr 07, 2022 |
| Sophos        | XG                          | Firewall    | [c98fff0cf2](https://bsd-hardware.info/?probe=c98fff0cf2) | Apr 06, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e44ebcb340](https://bsd-hardware.info/?probe=e44ebcb340) | Apr 06, 2022 |
| Deciso        | Netboard A20                | Notebook    | [0829d5a85d](https://bsd-hardware.info/?probe=0829d5a85d) | Apr 06, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [35dcbd74e9](https://bsd-hardware.info/?probe=35dcbd74e9) | Apr 05, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [946c8fd467](https://bsd-hardware.info/?probe=946c8fd467) | Apr 04, 2022 |
| PC Engines    | APU2                        | Desktop     | [5eb2e04d11](https://bsd-hardware.info/?probe=5eb2e04d11) | Apr 02, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [43cbc2ef2c](https://bsd-hardware.info/?probe=43cbc2ef2c) | Apr 02, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [c83fab9193](https://bsd-hardware.info/?probe=c83fab9193) | Apr 01, 2022 |
| Unknown       | Unknown                     | Firewall    | [b5c3949db8](https://bsd-hardware.info/?probe=b5c3949db8) | Mar 29, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [7a991e2f31](https://bsd-hardware.info/?probe=7a991e2f31) | Mar 24, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [acb99d63ce](https://bsd-hardware.info/?probe=acb99d63ce) | Mar 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [05a81cb5d5](https://bsd-hardware.info/?probe=05a81cb5d5) | Mar 22, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [483cf54bfc](https://bsd-hardware.info/?probe=483cf54bfc) | Mar 21, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d0946bc53f](https://bsd-hardware.info/?probe=d0946bc53f) | Mar 21, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d2ecb6259c](https://bsd-hardware.info/?probe=d2ecb6259c) | Mar 20, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [a4a1c8e5ca](https://bsd-hardware.info/?probe=a4a1c8e5ca) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b23ab09f52](https://bsd-hardware.info/?probe=b23ab09f52) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [545e5ebfc9](https://bsd-hardware.info/?probe=545e5ebfc9) | Mar 18, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [b137b25594](https://bsd-hardware.info/?probe=b137b25594) | Mar 15, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [b652261bda](https://bsd-hardware.info/?probe=b652261bda) | Mar 14, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0a2a94839d](https://bsd-hardware.info/?probe=0a2a94839d) | Mar 13, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [e5c8017afb](https://bsd-hardware.info/?probe=e5c8017afb) | Mar 12, 2022 |
| Supermicro    | X11SDV-8C-TLN2F             | Server      | [e1fceaabc0](https://bsd-hardware.info/?probe=e1fceaabc0) | Mar 08, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3b77055bd4](https://bsd-hardware.info/?probe=3b77055bd4) | Mar 07, 2022 |
| CNCTION-IA... | Unknown                     | Desktop     | [0051c86e4c](https://bsd-hardware.info/?probe=0051c86e4c) | Mar 07, 2022 |
| AAEON         | UP-CHT01 V0.4               | Desktop     | [9aaa7c7a32](https://bsd-hardware.info/?probe=9aaa7c7a32) | Mar 05, 2022 |
| Protectli     | VP2410                      | Desktop     | [1f650fc994](https://bsd-hardware.info/?probe=1f650fc994) | Mar 05, 2022 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [d73d3760ce](https://bsd-hardware.info/?probe=d73d3760ce) | Mar 04, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [a3611d42bc](https://bsd-hardware.info/?probe=a3611d42bc) | Mar 04, 2022 |
| PC Engines    | apu1                        | Desktop     | [177dc1fbc8](https://bsd-hardware.info/?probe=177dc1fbc8) | Mar 03, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [43bfceb19d](https://bsd-hardware.info/?probe=43bfceb19d) | Mar 02, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [4367711bff](https://bsd-hardware.info/?probe=4367711bff) | Mar 01, 2022 |
| Dell          | Latitude E5440              | Notebook    | [b0314f9200](https://bsd-hardware.info/?probe=b0314f9200) | Feb 26, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [7b19f71ce1](https://bsd-hardware.info/?probe=7b19f71ce1) | Feb 26, 2022 |
| PC Engines    | apu1                        | Desktop     | [d904aa7790](https://bsd-hardware.info/?probe=d904aa7790) | Feb 24, 2022 |
| Intel         | CARLOW                      | Desktop     | [d46b68cc28](https://bsd-hardware.info/?probe=d46b68cc28) | Feb 23, 2022 |
| HP            | 8169                        | Desktop     | [f449b4cd6c](https://bsd-hardware.info/?probe=f449b4cd6c) | Feb 23, 2022 |
| Dell          | 0W13NR A07                  | Server      | [22846d44fb](https://bsd-hardware.info/?probe=22846d44fb) | Feb 22, 2022 |
| Dell          | 0TY019 A00                  | Server      | [5f750e021e](https://bsd-hardware.info/?probe=5f750e021e) | Feb 20, 2022 |
| Intel         | CARLOW                      | Desktop     | [b64bf97293](https://bsd-hardware.info/?probe=b64bf97293) | Feb 19, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [ef5cc6be72](https://bsd-hardware.info/?probe=ef5cc6be72) | Feb 17, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [18576ef86c](https://bsd-hardware.info/?probe=18576ef86c) | Feb 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [fbc24f90e5](https://bsd-hardware.info/?probe=fbc24f90e5) | Feb 17, 2022 |
| MSI           | MS-7253                     | Desktop     | [c4e971ea82](https://bsd-hardware.info/?probe=c4e971ea82) | Feb 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [df529a84b9](https://bsd-hardware.info/?probe=df529a84b9) | Feb 16, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [1e8904f4fc](https://bsd-hardware.info/?probe=1e8904f4fc) | Feb 15, 2022 |
| AMD           | X64                         | Desktop     | [e5a9ff1138](https://bsd-hardware.info/?probe=e5a9ff1138) | Feb 15, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [ee3a7740ec](https://bsd-hardware.info/?probe=ee3a7740ec) | Feb 13, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b77b926f9b](https://bsd-hardware.info/?probe=b77b926f9b) | Feb 13, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [09a6920a4f](https://bsd-hardware.info/?probe=09a6920a4f) | Feb 12, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [61c103f80d](https://bsd-hardware.info/?probe=61c103f80d) | Feb 11, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [4d8f19ba12](https://bsd-hardware.info/?probe=4d8f19ba12) | Feb 11, 2022 |
| Sophos        | XG                          | Firewall    | [31a8174933](https://bsd-hardware.info/?probe=31a8174933) | Feb 10, 2022 |
| Sophos        | XG                          | Firewall    | [365e4cfbea](https://bsd-hardware.info/?probe=365e4cfbea) | Feb 08, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [8342bcccf5](https://bsd-hardware.info/?probe=8342bcccf5) | Feb 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [91b1ec3b93](https://bsd-hardware.info/?probe=91b1ec3b93) | Feb 06, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [a6b7d2d5e8](https://bsd-hardware.info/?probe=a6b7d2d5e8) | Feb 06, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2accc42e21](https://bsd-hardware.info/?probe=2accc42e21) | Feb 06, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [9213769810](https://bsd-hardware.info/?probe=9213769810) | Feb 05, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [00cabbe0bf](https://bsd-hardware.info/?probe=00cabbe0bf) | Feb 05, 2022 |
| Dell          | 0W13NR A07                  | Server      | [1582d0700a](https://bsd-hardware.info/?probe=1582d0700a) | Feb 03, 2022 |
| Deciso        | Netboard A20                | Notebook    | [8cd43fcfd1](https://bsd-hardware.info/?probe=8cd43fcfd1) | Feb 03, 2022 |
| Intel         | SKYBAY                      | Desktop     | [95c3231a3a](https://bsd-hardware.info/?probe=95c3231a3a) | Feb 03, 2022 |
| MSI           | MS-9A45 0A                  | Desktop     | [cfbfdf0e55](https://bsd-hardware.info/?probe=cfbfdf0e55) | Jan 31, 2022 |
| ASUSTek       | 1015PEM                     | Notebook    | [efea0efb2b](https://bsd-hardware.info/?probe=efea0efb2b) | Jan 31, 2022 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [ccda2302cf](https://bsd-hardware.info/?probe=ccda2302cf) | Jan 30, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [9dc53740a9](https://bsd-hardware.info/?probe=9dc53740a9) | Jan 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| AMD           | Larne CRB                   | Desktop     | [c6a85da1d5](https://bsd-hardware.info/?probe=c6a85da1d5) | Jan 28, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [7a5d842d33](https://bsd-hardware.info/?probe=7a5d842d33) | Jan 27, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f1c7ee0712](https://bsd-hardware.info/?probe=f1c7ee0712) | Jan 26, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [5c58d01f2d](https://bsd-hardware.info/?probe=5c58d01f2d) | Jan 25, 2022 |
| RUNING        | B75M INTEL H3V              | Desktop     | [9a060df0a2](https://bsd-hardware.info/?probe=9a060df0a2) | Jan 23, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [cd745d6377](https://bsd-hardware.info/?probe=cd745d6377) | Jan 23, 2022 |
| AMD           | Larne CRB                   | Desktop     | [6c37b91111](https://bsd-hardware.info/?probe=6c37b91111) | Jan 22, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [b01e6eb706](https://bsd-hardware.info/?probe=b01e6eb706) | Jan 22, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [384d2f888b](https://bsd-hardware.info/?probe=384d2f888b) | Jan 18, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [8449bd20c1](https://bsd-hardware.info/?probe=8449bd20c1) | Jan 18, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3dead218e1](https://bsd-hardware.info/?probe=3dead218e1) | Jan 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [6baaab27fd](https://bsd-hardware.info/?probe=6baaab27fd) | Jan 15, 2022 |
| MSI           | MS-98C8                     | Desktop     | [0102557f05](https://bsd-hardware.info/?probe=0102557f05) | Jan 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [7062b84459](https://bsd-hardware.info/?probe=7062b84459) | Jan 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [1ff4a66d03](https://bsd-hardware.info/?probe=1ff4a66d03) | Jan 12, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [42eb986a58](https://bsd-hardware.info/?probe=42eb986a58) | Jan 11, 2022 |
| Dell          | Latitude E5450              | Notebook    | [a05fbe1c26](https://bsd-hardware.info/?probe=a05fbe1c26) | Jan 05, 2022 |
| Dell          | Latitude E5450              | Notebook    | [c2ef231757](https://bsd-hardware.info/?probe=c2ef231757) | Jan 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [6aeb9adadb](https://bsd-hardware.info/?probe=6aeb9adadb) | Dec 31, 2021 |
| Dell          | 0V52N7 A00                  | Server      | [b6139f57b9](https://bsd-hardware.info/?probe=b6139f57b9) | Dec 30, 2021 |
| ASUSTek       | S550CA                      | Notebook    | [1263a5fb37](https://bsd-hardware.info/?probe=1263a5fb37) | Dec 29, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [8c3181ee8d](https://bsd-hardware.info/?probe=8c3181ee8d) | Dec 29, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [07221fc111](https://bsd-hardware.info/?probe=07221fc111) | Dec 28, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cdb5578df8](https://bsd-hardware.info/?probe=cdb5578df8) | Dec 27, 2021 |
| Gigabyte      | X58A-UD5                    | Desktop     | [62b94dd372](https://bsd-hardware.info/?probe=62b94dd372) | Dec 21, 2021 |
| Samsung       | R720                        | Notebook    | [620195d4aa](https://bsd-hardware.info/?probe=620195d4aa) | Dec 20, 2021 |
| HP            | Compaq 15                   | Notebook    | [1e8b1ce39b](https://bsd-hardware.info/?probe=1e8b1ce39b) | Dec 20, 2021 |
| Supermicro    | X11SSL-F                    | Server      | [a5a440a7a7](https://bsd-hardware.info/?probe=a5a440a7a7) | Dec 20, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [124ac672b0](https://bsd-hardware.info/?probe=124ac672b0) | Dec 20, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [350def9eca](https://bsd-hardware.info/?probe=350def9eca) | Dec 19, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [4147a5824d](https://bsd-hardware.info/?probe=4147a5824d) | Dec 16, 2021 |
| HP            | ProBook 650 G5              | Notebook    | [d4ffc24c6f](https://bsd-hardware.info/?probe=d4ffc24c6f) | Dec 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [225298bcd6](https://bsd-hardware.info/?probe=225298bcd6) | Dec 12, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [26220d3f14](https://bsd-hardware.info/?probe=26220d3f14) | Dec 09, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [eb69e83fbf](https://bsd-hardware.info/?probe=eb69e83fbf) | Dec 09, 2021 |
| RUNING        | B75M INTEL H3V              | Desktop     | [61312aa506](https://bsd-hardware.info/?probe=61312aa506) | Nov 30, 2021 |
| Dell          | VEP-4600-V930 034R2CA03     | Desktop     | [313d1b7032](https://bsd-hardware.info/?probe=313d1b7032) | Nov 25, 2021 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [9e7a72d920](https://bsd-hardware.info/?probe=9e7a72d920) | Nov 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [16206960c4](https://bsd-hardware.info/?probe=16206960c4) | Nov 24, 2021 |
| HP            | 3031h                       | Desktop     | [056352a663](https://bsd-hardware.info/?probe=056352a663) | Nov 21, 2021 |
| RUNING        | B75M INTEL H3V              | Desktop     | [5cfcc8c5f8](https://bsd-hardware.info/?probe=5cfcc8c5f8) | Nov 13, 2021 |
| HP            | 3031h                       | Desktop     | [d63bbcfceb](https://bsd-hardware.info/?probe=d63bbcfceb) | Oct 31, 2021 |
| HP            | 3031h                       | Desktop     | [c5e39a5e6d](https://bsd-hardware.info/?probe=c5e39a5e6d) | Oct 31, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [e2db09bacb](https://bsd-hardware.info/?probe=e2db09bacb) | Oct 30, 2021 |
| ASRockRack    | C3558D4I-4L                 | Desktop     | [dfba84ce5a](https://bsd-hardware.info/?probe=dfba84ce5a) | Oct 29, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e2167afc3b](https://bsd-hardware.info/?probe=e2167afc3b) | Oct 25, 2021 |
| BESSTAR Te... | VB9                         | All in one  | [ac1f5a3339](https://bsd-hardware.info/?probe=ac1f5a3339) | Oct 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3f5b148e23](https://bsd-hardware.info/?probe=3f5b148e23) | Oct 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [6f019f05b6](https://bsd-hardware.info/?probe=6f019f05b6) | Oct 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [4b8fb7992f](https://bsd-hardware.info/?probe=4b8fb7992f) | Oct 16, 2021 |
| Dell          | 0V52N7 A00                  | Server      | [c5226ff226](https://bsd-hardware.info/?probe=c5226ff226) | Oct 13, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [e53866a5d9](https://bsd-hardware.info/?probe=e53866a5d9) | Oct 11, 2021 |
| ASUSTek       | P9X79                       | Desktop     | [be9d90602d](https://bsd-hardware.info/?probe=be9d90602d) | Oct 11, 2021 |
| Dell          | 04JN2K A04                  | Server      | [f529f87cea](https://bsd-hardware.info/?probe=f529f87cea) | Oct 11, 2021 |
| Dell          | 0V52N7 A00                  | Server      | [4ad37c1848](https://bsd-hardware.info/?probe=4ad37c1848) | Oct 10, 2021 |
| Google        | Terra                       | Notebook    | [9ba239a4a3](https://bsd-hardware.info/?probe=9ba239a4a3) | Oct 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [2fd62acb45](https://bsd-hardware.info/?probe=2fd62acb45) | Oct 10, 2021 |
| Lenovo        | 3138                        | Desktop     | [8b5cf892d0](https://bsd-hardware.info/?probe=8b5cf892d0) | Oct 04, 2021 |
| Lenovo        | ThinkPad X220 4290W42       | Notebook    | [8be5183e21](https://bsd-hardware.info/?probe=8be5183e21) | Sep 25, 2021 |
| Lenovo        | ThinkPad T500 2056Y2Z       | Notebook    | [88b86ecf8b](https://bsd-hardware.info/?probe=88b86ecf8b) | Sep 25, 2021 |
| ASUSTek       | F2A85-M                     | Desktop     | [5b7623f03b](https://bsd-hardware.info/?probe=5b7623f03b) | Sep 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [1b8ce81945](https://bsd-hardware.info/?probe=1b8ce81945) | Sep 19, 2021 |
| MSI           | P65 Creator 8RE             | Notebook    | [2684b5021c](https://bsd-hardware.info/?probe=2684b5021c) | Sep 18, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [8611fbfd97](https://bsd-hardware.info/?probe=8611fbfd97) | Sep 14, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [5f78c3411f](https://bsd-hardware.info/?probe=5f78c3411f) | Sep 13, 2021 |
| ASRock        | B460M Pro4                  | Desktop     | [cfc7818691](https://bsd-hardware.info/?probe=cfc7818691) | Sep 10, 2021 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [d5750a95a4](https://bsd-hardware.info/?probe=d5750a95a4) | Sep 08, 2021 |
| Packard Be... | imedia S2110A               | Desktop     | [d62a38660c](https://bsd-hardware.info/?probe=d62a38660c) | Sep 08, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [29cfd33c5e](https://bsd-hardware.info/?probe=29cfd33c5e) | Sep 06, 2021 |
| ASUSTek       | P8B-X series                | Server      | [1e7d58cd40](https://bsd-hardware.info/?probe=1e7d58cd40) | Aug 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d028fc63d4](https://bsd-hardware.info/?probe=d028fc63d4) | Aug 29, 2021 |
| ASRockRack    | X470D4U                     | Desktop     | [827c50f77b](https://bsd-hardware.info/?probe=827c50f77b) | Aug 28, 2021 |
| Dell          | 0G3HR7 A00                  | Desktop     | [7f75f30b75](https://bsd-hardware.info/?probe=7f75f30b75) | Aug 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| PC Engines    | APU2                        | Desktop     | [0a35da2af7](https://bsd-hardware.info/?probe=0a35da2af7) | Aug 24, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3e088c942b](https://bsd-hardware.info/?probe=3e088c942b) | Aug 22, 2021 |
| Fujitsu       | LIFEBOOK NH570              | Notebook    | [51b5325c85](https://bsd-hardware.info/?probe=51b5325c85) | Aug 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [1dd499d54c](https://bsd-hardware.info/?probe=1dd499d54c) | Aug 12, 2021 |
| Dell          | 0XCR8D A03                  | Desktop     | [11526a150b](https://bsd-hardware.info/?probe=11526a150b) | Aug 10, 2021 |
| Shuttle       | FS61                        | Desktop     | [b1fbaa8a6b](https://bsd-hardware.info/?probe=b1fbaa8a6b) | Aug 09, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [bb65c30be3](https://bsd-hardware.info/?probe=bb65c30be3) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [9e0c8e8024](https://bsd-hardware.info/?probe=9e0c8e8024) | Aug 07, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [5f9c53366b](https://bsd-hardware.info/?probe=5f9c53366b) | Aug 05, 2021 |
| Unknown       | YL-SKUL6-7 Series           | Desktop     | [b9ef180b73](https://bsd-hardware.info/?probe=b9ef180b73) | Aug 04, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [3ff984316b](https://bsd-hardware.info/?probe=3ff984316b) | Aug 04, 2021 |
| Dell          | 0G261D A00                  | Desktop     | [2ce00e9f6b](https://bsd-hardware.info/?probe=2ce00e9f6b) | Aug 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [2a1251b320](https://bsd-hardware.info/?probe=2a1251b320) | Aug 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [34d448e1d1](https://bsd-hardware.info/?probe=34d448e1d1) | Jul 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [846b6cca20](https://bsd-hardware.info/?probe=846b6cca20) | Jul 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [8aaf18daa1](https://bsd-hardware.info/?probe=8aaf18daa1) | Jul 28, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [d15eff8bcc](https://bsd-hardware.info/?probe=d15eff8bcc) | Jul 21, 2021 |
| ASRock        | D1800B-ITX                  | Desktop     | [4831cc5183](https://bsd-hardware.info/?probe=4831cc5183) | Jul 21, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [2484df8d38](https://bsd-hardware.info/?probe=2484df8d38) | Jul 18, 2021 |
| Lenovo        | ThinkPad T420 42368A3       | Notebook    | [0a3b5c9c27](https://bsd-hardware.info/?probe=0a3b5c9c27) | Jul 12, 2021 |
| HP            | 2B4B                        | Desktop     | [456625c82f](https://bsd-hardware.info/?probe=456625c82f) | Jul 04, 2021 |
| Notebook      | W510LU                      | Notebook    | [3d6de69bda](https://bsd-hardware.info/?probe=3d6de69bda) | Jul 02, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [1e66c42238](https://bsd-hardware.info/?probe=1e66c42238) | Jul 02, 2021 |
| Shuttle       | NC10U                       | Desktop     | [5d2d20dd04](https://bsd-hardware.info/?probe=5d2d20dd04) | Jul 02, 2021 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [bde8057846](https://bsd-hardware.info/?probe=bde8057846) | Jun 29, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [7ae63d4c6c](https://bsd-hardware.info/?probe=7ae63d4c6c) | Jun 27, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [661d3349cb](https://bsd-hardware.info/?probe=661d3349cb) | Jun 26, 2021 |
| Dell          | Vostro 5481                 | Notebook    | [bb318fbc50](https://bsd-hardware.info/?probe=bb318fbc50) | Jun 26, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [95b0c9a6a3](https://bsd-hardware.info/?probe=95b0c9a6a3) | Jun 25, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0L60... | Notebook    | [6ea6f6ffe7](https://bsd-hardware.info/?probe=6ea6f6ffe7) | Jun 20, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [8f336c0fa3](https://bsd-hardware.info/?probe=8f336c0fa3) | Jun 19, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [dc619f203f](https://bsd-hardware.info/?probe=dc619f203f) | Jun 19, 2021 |
| ASRock        | H110M-ITX                   | Desktop     | [124c75ba7c](https://bsd-hardware.info/?probe=124c75ba7c) | Jun 17, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [007ce2b6ce](https://bsd-hardware.info/?probe=007ce2b6ce) | Jun 17, 2021 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [e6cbfc417b](https://bsd-hardware.info/?probe=e6cbfc417b) | Jun 10, 2021 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [e54175f99f](https://bsd-hardware.info/?probe=e54175f99f) | Jun 06, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | Notebook    | [b60f4a19ee](https://bsd-hardware.info/?probe=b60f4a19ee) | Jun 06, 2021 |
| Dell          | 0TY019 A01                  | Server      | [411477e260](https://bsd-hardware.info/?probe=411477e260) | Jun 04, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [24f3dbd372](https://bsd-hardware.info/?probe=24f3dbd372) | Jun 04, 2021 |
| Shuttle       | FS35V5                      | Mini pc     | [bfd71efa3b](https://bsd-hardware.info/?probe=bfd71efa3b) | May 31, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [cec18015ba](https://bsd-hardware.info/?probe=cec18015ba) | May 30, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [193936b5ca](https://bsd-hardware.info/?probe=193936b5ca) | May 30, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0L60... | Notebook    | [ac567bd12d](https://bsd-hardware.info/?probe=ac567bd12d) | May 28, 2021 |
| Lenovo        | ThinkPad A485 20MVS0FD00    | Notebook    | [2f1ba02130](https://bsd-hardware.info/?probe=2f1ba02130) | May 28, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [16f36a045f](https://bsd-hardware.info/?probe=16f36a045f) | May 26, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [7c8c842fa7](https://bsd-hardware.info/?probe=7c8c842fa7) | May 24, 2021 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [3e650be93d](https://bsd-hardware.info/?probe=3e650be93d) | May 24, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [aafc52d6a1](https://bsd-hardware.info/?probe=aafc52d6a1) | May 24, 2021 |
| Google        | Guado                       | Desktop     | [54f01f821d](https://bsd-hardware.info/?probe=54f01f821d) | May 21, 2021 |
| MSI           | Z77A-G41                    | Desktop     | [c471a8f2fe](https://bsd-hardware.info/?probe=c471a8f2fe) | May 16, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [3468faf656](https://bsd-hardware.info/?probe=3468faf656) | May 07, 2021 |
| ASRockRack    | X470D4U                     | Desktop     | [421da89770](https://bsd-hardware.info/?probe=421da89770) | May 06, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [87e5651fd1](https://bsd-hardware.info/?probe=87e5651fd1) | May 06, 2021 |
| PC Engines    | APU2                        | Desktop     | [c99a0b0e4d](https://bsd-hardware.info/?probe=c99a0b0e4d) | May 05, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [e930fac60b](https://bsd-hardware.info/?probe=e930fac60b) | May 05, 2021 |
| Supermicro    | X8STi                       | Desktop     | [c615ef1edf](https://bsd-hardware.info/?probe=c615ef1edf) | May 04, 2021 |
| ASUSTek       | Rampage II GENE             | Desktop     | [4eac97c85c](https://bsd-hardware.info/?probe=4eac97c85c) | May 04, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [7c642e5e7d](https://bsd-hardware.info/?probe=7c642e5e7d) | Apr 30, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [2e2e69cb9e](https://bsd-hardware.info/?probe=2e2e69cb9e) | Apr 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [4368de8d34](https://bsd-hardware.info/?probe=4368de8d34) | Apr 28, 2021 |
| PC Engines    | APU3                        | Desktop     | [1d6ca07c5a](https://bsd-hardware.info/?probe=1d6ca07c5a) | Apr 27, 2021 |
| PC Engines    | APU3                        | Desktop     | [8fc426b107](https://bsd-hardware.info/?probe=8fc426b107) | Apr 22, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [e262812b4d](https://bsd-hardware.info/?probe=e262812b4d) | Apr 21, 2021 |
| Lenovo        | ThinkPad T430 23495P8       | Notebook    | [2c985c22ef](https://bsd-hardware.info/?probe=2c985c22ef) | Apr 10, 2021 |
| Lenovo        | ThinkPad T420 4236NUG       | Notebook    | [4ff3fa22ff](https://bsd-hardware.info/?probe=4ff3fa22ff) | Apr 07, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [354dc80671](https://bsd-hardware.info/?probe=354dc80671) | Apr 07, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [7901474a09](https://bsd-hardware.info/?probe=7901474a09) | Apr 07, 2021 |
| PC Engines    | apu4                        | Desktop     | [160a01d9e1](https://bsd-hardware.info/?probe=160a01d9e1) | Apr 03, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [f3b6d4d5c4](https://bsd-hardware.info/?probe=f3b6d4d5c4) | Apr 03, 2021 |
| ASUSTek       | P8B-X series                | Server      | [f60388bf6a](https://bsd-hardware.info/?probe=f60388bf6a) | Apr 03, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [7031b0ed1e](https://bsd-hardware.info/?probe=7031b0ed1e) | Mar 31, 2021 |
| PC Engines    | APU2                        | Desktop     | [97554df75d](https://bsd-hardware.info/?probe=97554df75d) | Mar 30, 2021 |
| Lenovo        | ThinkPad X220 4290EE8       | Notebook    | [f46976d85d](https://bsd-hardware.info/?probe=f46976d85d) | Mar 29, 2021 |
| Lenovo        | ThinkPad T490 20N20009FR    | Notebook    | [e1f691ac78](https://bsd-hardware.info/?probe=e1f691ac78) | Mar 29, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [dec8aa97f5](https://bsd-hardware.info/?probe=dec8aa97f5) | Mar 26, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [83ed58b4d0](https://bsd-hardware.info/?probe=83ed58b4d0) | Mar 26, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [e789c55f2e](https://bsd-hardware.info/?probe=e789c55f2e) | Mar 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3cb0e979f8](https://bsd-hardware.info/?probe=3cb0e979f8) | Mar 26, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [0263b0e32e](https://bsd-hardware.info/?probe=0263b0e32e) | Mar 26, 2021 |
| Lenovo        | 3138                        | Desktop     | [f12dd68efb](https://bsd-hardware.info/?probe=f12dd68efb) | Mar 25, 2021 |
| Dell          | 0KRC95 A02                  | Desktop     | [68354c00cf](https://bsd-hardware.info/?probe=68354c00cf) | Mar 25, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [1499695aae](https://bsd-hardware.info/?probe=1499695aae) | Mar 25, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [650cd9b653](https://bsd-hardware.info/?probe=650cd9b653) | Mar 24, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [bef38bd379](https://bsd-hardware.info/?probe=bef38bd379) | Mar 23, 2021 |
| MSI           | MS-N033                     | Notebook    | [650f6a1b70](https://bsd-hardware.info/?probe=650f6a1b70) | Mar 21, 2021 |
| Dell          | Inspiron 7566               | Notebook    | [183ac9b791](https://bsd-hardware.info/?probe=183ac9b791) | Mar 17, 2021 |
| Dell          | Inspiron 7566               | Notebook    | [b4a35aa7b0](https://bsd-hardware.info/?probe=b4a35aa7b0) | Mar 17, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [c0df245c1b](https://bsd-hardware.info/?probe=c0df245c1b) | Mar 13, 2021 |
| SECO          | UDOO x86                    | Notebook    | [f8310915b6](https://bsd-hardware.info/?probe=f8310915b6) | Mar 13, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [565343b334](https://bsd-hardware.info/?probe=565343b334) | Mar 13, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [24b657e7ba](https://bsd-hardware.info/?probe=24b657e7ba) | Mar 12, 2021 |
| Dell          | 05XKKK A05                  | Server      | [d3fe07511a](https://bsd-hardware.info/?probe=d3fe07511a) | Mar 12, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [bbcc01d2ce](https://bsd-hardware.info/?probe=bbcc01d2ce) | Mar 11, 2021 |
| MSI           | B360M BAZOOKA               | Desktop     | [17a763a917](https://bsd-hardware.info/?probe=17a763a917) | Mar 11, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [835842d361](https://bsd-hardware.info/?probe=835842d361) | Mar 10, 2021 |
| Lenovo        | ThinkPad T400 6475P1G       | Notebook    | [6a0907b5e8](https://bsd-hardware.info/?probe=6a0907b5e8) | Mar 06, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [17ed006376](https://bsd-hardware.info/?probe=17ed006376) | Mar 05, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [348d592fab](https://bsd-hardware.info/?probe=348d592fab) | Mar 05, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [9468eeef92](https://bsd-hardware.info/?probe=9468eeef92) | Mar 04, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [fc655524ab](https://bsd-hardware.info/?probe=fc655524ab) | Mar 04, 2021 |
| VeryPC        | S400                        | Desktop     | [77b744169b](https://bsd-hardware.info/?probe=77b744169b) | Mar 04, 2021 |
| VeryPC        | S400                        | Desktop     | [edcea11cb7](https://bsd-hardware.info/?probe=edcea11cb7) | Mar 04, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [de98cd5952](https://bsd-hardware.info/?probe=de98cd5952) | Mar 04, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [03c5808adf](https://bsd-hardware.info/?probe=03c5808adf) | Mar 04, 2021 |
| Dell          | Latitude 5280               | Notebook    | [b84364959d](https://bsd-hardware.info/?probe=b84364959d) | Mar 04, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [1f226262cc](https://bsd-hardware.info/?probe=1f226262cc) | Mar 04, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [e056f1c77c](https://bsd-hardware.info/?probe=e056f1c77c) | Mar 03, 2021 |
| HP            | 86E9 A                      | Desktop     | [215398b88f](https://bsd-hardware.info/?probe=215398b88f) | Feb 28, 2021 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [9bdf9ecec8](https://bsd-hardware.info/?probe=9bdf9ecec8) | Feb 25, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [7def696a61](https://bsd-hardware.info/?probe=7def696a61) | Feb 22, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [0dc468c860](https://bsd-hardware.info/?probe=0dc468c860) | Feb 22, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [b1f1b3cd82](https://bsd-hardware.info/?probe=b1f1b3cd82) | Feb 22, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [929bda8001](https://bsd-hardware.info/?probe=929bda8001) | Feb 22, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [fe7d72b06a](https://bsd-hardware.info/?probe=fe7d72b06a) | Feb 21, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [a88cfd7fdd](https://bsd-hardware.info/?probe=a88cfd7fdd) | Feb 21, 2021 |
| Acer          | EG43M                       | Desktop     | [22552918ee](https://bsd-hardware.info/?probe=22552918ee) | Feb 21, 2021 |
| Gigabyte      | P15FR7                      | Notebook    | [c65b4d297a](https://bsd-hardware.info/?probe=c65b4d297a) | Feb 21, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ade306695d](https://bsd-hardware.info/?probe=ade306695d) | Feb 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [71cfece3a7](https://bsd-hardware.info/?probe=71cfece3a7) | Feb 18, 2021 |
| Supermicro    | X9DRT                       | Server      | [a3bcb2fcf1](https://bsd-hardware.info/?probe=a3bcb2fcf1) | Feb 18, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [261756a327](https://bsd-hardware.info/?probe=261756a327) | Feb 17, 2021 |
| ASUSTek       | X75VC                       | Notebook    | [4a0982db2b](https://bsd-hardware.info/?probe=4a0982db2b) | Feb 15, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [5d39657098](https://bsd-hardware.info/?probe=5d39657098) | Feb 14, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [4f646f53e9](https://bsd-hardware.info/?probe=4f646f53e9) | Feb 14, 2021 |
| Lenovo        | ThinkPad T580 20LAS2TG00    | Notebook    | [d5a1c088b3](https://bsd-hardware.info/?probe=d5a1c088b3) | Feb 13, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ba7f82b343](https://bsd-hardware.info/?probe=ba7f82b343) | Feb 12, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [5781a8b561](https://bsd-hardware.info/?probe=5781a8b561) | Feb 12, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [9b149fcd68](https://bsd-hardware.info/?probe=9b149fcd68) | Feb 12, 2021 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [5965bc8a1d](https://bsd-hardware.info/?probe=5965bc8a1d) | Feb 11, 2021 |
| PC Engines    | APU                         | Desktop     | [282a9596c6](https://bsd-hardware.info/?probe=282a9596c6) | Feb 11, 2021 |
| Dell          | Latitude 3410               | Notebook    | [465dd01c0d](https://bsd-hardware.info/?probe=465dd01c0d) | Feb 11, 2021 |
| Dell          | 0H28RR A02                  | Server      | [0bbf4a51bb](https://bsd-hardware.info/?probe=0bbf4a51bb) | Feb 10, 2021 |
| Dell          | 0H28RR A02                  | Server      | [eaac725443](https://bsd-hardware.info/?probe=eaac725443) | Feb 10, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [23e7163f58](https://bsd-hardware.info/?probe=23e7163f58) | Feb 10, 2021 |
| Gigabyte      | Z97P-D3                     | Desktop     | [a3bd8f5772](https://bsd-hardware.info/?probe=a3bd8f5772) | Feb 10, 2021 |
| Dell          | Latitude E6230              | Notebook    | [696e95fc08](https://bsd-hardware.info/?probe=696e95fc08) | Feb 10, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [94bcab24a8](https://bsd-hardware.info/?probe=94bcab24a8) | Feb 09, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [b3cf6f9142](https://bsd-hardware.info/?probe=b3cf6f9142) | Feb 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [7e5ce355e7](https://bsd-hardware.info/?probe=7e5ce355e7) | Feb 08, 2021 |
| Dell          | Latitude 5280               | Notebook    | [73fca8b178](https://bsd-hardware.info/?probe=73fca8b178) | Feb 08, 2021 |
| PC Engines    | APU3                        | Desktop     | [e21438c3cc](https://bsd-hardware.info/?probe=e21438c3cc) | Feb 07, 2021 |
| Lenovo        | ThinkPad T420 42368A3       | Notebook    | [5d7840d28e](https://bsd-hardware.info/?probe=5d7840d28e) | Feb 07, 2021 |
| Dell          | Latitude 3410               | Notebook    | [f81c1e338f](https://bsd-hardware.info/?probe=f81c1e338f) | Feb 07, 2021 |
| MSI           | Z77A-G41                    | Desktop     | [35bae50659](https://bsd-hardware.info/?probe=35bae50659) | Feb 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [8ef7071a3f](https://bsd-hardware.info/?probe=8ef7071a3f) | Feb 04, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [857c5aade9](https://bsd-hardware.info/?probe=857c5aade9) | Feb 04, 2021 |
| CompuLab      | fitlet2                     | Mini pc     | [7ff0034c98](https://bsd-hardware.info/?probe=7ff0034c98) | Feb 03, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [b005d61a99](https://bsd-hardware.info/?probe=b005d61a99) | Feb 03, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [f66ccf2f33](https://bsd-hardware.info/?probe=f66ccf2f33) | Feb 03, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [c384535b6f](https://bsd-hardware.info/?probe=c384535b6f) | Feb 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [a7494d60a5](https://bsd-hardware.info/?probe=a7494d60a5) | Jan 31, 2021 |
| Dell          | 0JD6X3 A05                  | Server      | [27a3bb8503](https://bsd-hardware.info/?probe=27a3bb8503) | Jan 31, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [c8af335c01](https://bsd-hardware.info/?probe=c8af335c01) | Jan 29, 2021 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [dae16641bb](https://bsd-hardware.info/?probe=dae16641bb) | Jan 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [4c4d549584](https://bsd-hardware.info/?probe=4c4d549584) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [80edc8dae6](https://bsd-hardware.info/?probe=80edc8dae6) | Jan 22, 2021 |
| PC Engines    | apu4                        | Desktop     | [3507544d2e](https://bsd-hardware.info/?probe=3507544d2e) | Jan 20, 2021 |
| Lenovo        | ThinkPad P50 20EQS0U60C     | Notebook    | [d8cf9e878e](https://bsd-hardware.info/?probe=d8cf9e878e) | Jan 19, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [f6df3820b5](https://bsd-hardware.info/?probe=f6df3820b5) | Jan 18, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [f7c32488e9](https://bsd-hardware.info/?probe=f7c32488e9) | Jan 15, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [06cbb5cd5f](https://bsd-hardware.info/?probe=06cbb5cd5f) | Jan 15, 2021 |
| Dell          | Latitude 5280               | Notebook    | [c9bfb73262](https://bsd-hardware.info/?probe=c9bfb73262) | Jan 15, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [a9228fa7c3](https://bsd-hardware.info/?probe=a9228fa7c3) | Jan 15, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [5af442bf61](https://bsd-hardware.info/?probe=5af442bf61) | Jan 15, 2021 |
| HP            | 3399                        | Desktop     | [b11946a41a](https://bsd-hardware.info/?probe=b11946a41a) | Jan 13, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [8093f75ea2](https://bsd-hardware.info/?probe=8093f75ea2) | Jan 13, 2021 |
| Dell          | Latitude 5400               | Notebook    | [f242897c33](https://bsd-hardware.info/?probe=f242897c33) | Jan 13, 2021 |
| Dell          | Latitude 5490               | Notebook    | [3fba47b07f](https://bsd-hardware.info/?probe=3fba47b07f) | Jan 12, 2021 |
| ASUSTek       | N75SF                       | Notebook    | [7efb6557a2](https://bsd-hardware.info/?probe=7efb6557a2) | Jan 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [9ccf63e228](https://bsd-hardware.info/?probe=9ccf63e228) | Jan 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [e18df4623a](https://bsd-hardware.info/?probe=e18df4623a) | Jan 09, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [d894ae5d09](https://bsd-hardware.info/?probe=d894ae5d09) | Jan 07, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d54f451ea5](https://bsd-hardware.info/?probe=d54f451ea5) | Jan 07, 2021 |
| HP            | 3032h                       | Desktop     | [13648fd22d](https://bsd-hardware.info/?probe=13648fd22d) | Jan 07, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ee2d5f3289](https://bsd-hardware.info/?probe=ee2d5f3289) | Jan 07, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [c117ffdc98](https://bsd-hardware.info/?probe=c117ffdc98) | Jan 07, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [36ef631bfe](https://bsd-hardware.info/?probe=36ef631bfe) | Jan 05, 2021 |
| Dell          | Latitude 5280               | Notebook    | [1ae6e6ee2d](https://bsd-hardware.info/?probe=1ae6e6ee2d) | Jan 05, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [893b9111c6](https://bsd-hardware.info/?probe=893b9111c6) | Dec 27, 2020 |
| Gigabyte      | X79-UD3                     | Desktop     | [a8baf509d9](https://bsd-hardware.info/?probe=a8baf509d9) | Dec 26, 2020 |
| Apple         | PowerBook5,8                | Notebook    | [96f550a537](https://bsd-hardware.info/?probe=96f550a537) | Dec 24, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d13e0a1749](https://bsd-hardware.info/?probe=d13e0a1749) | Dec 15, 2020 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [2544123f79](https://bsd-hardware.info/?probe=2544123f79) | Dec 06, 2020 |
| Dell          | Latitude 5280               | Notebook    | [d1be72cc7e](https://bsd-hardware.info/?probe=d1be72cc7e) | Nov 21, 2020 |
| Dell          | Latitude 5280               | Notebook    | [fd4e8756b4](https://bsd-hardware.info/?probe=fd4e8756b4) | Nov 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [9b6b24708e](https://bsd-hardware.info/?probe=9b6b24708e) | Nov 03, 2020 |
| Dell          | 03X6X0 A03                  | Server      | [7d7b8ca054](https://bsd-hardware.info/?probe=7d7b8ca054) | Oct 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [7c8972f650](https://bsd-hardware.info/?probe=7c8972f650) | Oct 29, 2020 |
| ASRock        | J3455-ITX                   | Desktop     | [1d5bd18d14](https://bsd-hardware.info/?probe=1d5bd18d14) | Oct 29, 2020 |
| Supermicro    | X8STi                       | Desktop     | [1b64902781](https://bsd-hardware.info/?probe=1b64902781) | Oct 26, 2020 |
| AZW           | Z83 II                      | Desktop     | [9416876f20](https://bsd-hardware.info/?probe=9416876f20) | Oct 24, 2020 |
| AZW           | Z83 II                      | Desktop     | [19b1b4d85d](https://bsd-hardware.info/?probe=19b1b4d85d) | Oct 24, 2020 |
| Intel         | D2500HN                     | Desktop     | [6dbc4dfa33](https://bsd-hardware.info/?probe=6dbc4dfa33) | Oct 21, 2020 |
| PC Engines    | APU2                        | Desktop     | [d1ca549fe7](https://bsd-hardware.info/?probe=d1ca549fe7) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325AJ9       | Notebook    | [176044b6b8](https://bsd-hardware.info/?probe=176044b6b8) | Oct 21, 2020 |
| Lenovo        | ThinkPad S5-S540 20B3001... | Notebook    | [7e6cb69989](https://bsd-hardware.info/?probe=7e6cb69989) | Oct 21, 2020 |
| ZOTAC         | XXXXXX                      | Desktop     | [0f8960bdd3](https://bsd-hardware.info/?probe=0f8960bdd3) | Oct 21, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [1b1327ac93](https://bsd-hardware.info/?probe=1b1327ac93) | Oct 21, 2020 |
| Intel         | D2500HN                     | Desktop     | [4b432dcb3d](https://bsd-hardware.info/?probe=4b432dcb3d) | Oct 20, 2020 |
| PC Engines    | APU2                        | Desktop     | [b95ef9962d](https://bsd-hardware.info/?probe=b95ef9962d) | Oct 20, 2020 |
| PC Engines    | APU2                        | Desktop     | [aecf376503](https://bsd-hardware.info/?probe=aecf376503) | Oct 20, 2020 |
| ASUSTek       | X102BA                      | Notebook    | [47e04c9378](https://bsd-hardware.info/?probe=47e04c9378) | Oct 19, 2020 |
| ASUSTek       | UX305FA                     | Notebook    | [4ecb1e9cd3](https://bsd-hardware.info/?probe=4ecb1e9cd3) | Sep 25, 2020 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [88f2d98930](https://bsd-hardware.info/?probe=88f2d98930) | Sep 12, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [986575086d](https://bsd-hardware.info/?probe=986575086d) | Sep 05, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [f95de56bcd](https://bsd-hardware.info/?probe=f95de56bcd) | Sep 03, 2020 |
| Intel         | DH61AG AAG23736-505         | Desktop     | [3f99489a19](https://bsd-hardware.info/?probe=3f99489a19) | Aug 19, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [42de38c478](https://bsd-hardware.info/?probe=42de38c478) | Aug 19, 2020 |
| Intel         | DN2800MT AAG81515-900       | Desktop     | [bcfec367a9](https://bsd-hardware.info/?probe=bcfec367a9) | Aug 14, 2020 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [d508fb472b](https://bsd-hardware.info/?probe=d508fb472b) | Aug 10, 2020 |
| Gigabyte      | P35-DS3R                    | Desktop     | [4ed0c89a67](https://bsd-hardware.info/?probe=4ed0c89a67) | Aug 07, 2020 |
| Dell          | 081N4V A07                  | Server      | [2d835336d9](https://bsd-hardware.info/?probe=2d835336d9) | Aug 07, 2020 |
| Dell          | 081N4V A07                  | Server      | [14a20876f4](https://bsd-hardware.info/?probe=14a20876f4) | Aug 07, 2020 |
| HP            | ProLiant DL120 G7           | Server      | [f873647eb9](https://bsd-hardware.info/?probe=f873647eb9) | Aug 07, 2020 |
| ASUSTek       | Z170-P D3                   | Desktop     | [7b8885caf3](https://bsd-hardware.info/?probe=7b8885caf3) | Aug 07, 2020 |
| ASUSTek       | Z170-P D3                   | Desktop     | [2e9821f90f](https://bsd-hardware.info/?probe=2e9821f90f) | Aug 07, 2020 |
| Gigabyte      | EP45-DS4                    | Desktop     | [a56a9c50fc](https://bsd-hardware.info/?probe=a56a9c50fc) | Aug 07, 2020 |
| Sony          | VGN-AR630E                  | Notebook    | [b417df513f](https://bsd-hardware.info/?probe=b417df513f) | Aug 07, 2020 |
| Gigabyte      | P35-DS3R                    | Desktop     | [0b111b137c](https://bsd-hardware.info/?probe=0b111b137c) | Aug 07, 2020 |
| MSI           | P65 Creator 8RE             | Notebook    | [4031d186c2](https://bsd-hardware.info/?probe=4031d186c2) | Aug 06, 2020 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [82de136ad3](https://bsd-hardware.info/?probe=82de136ad3) | Aug 06, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [f3e2acbb66](https://bsd-hardware.info/?probe=f3e2acbb66) | Jul 31, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [7ae8c247e9](https://bsd-hardware.info/?probe=7ae8c247e9) | Jul 31, 2020 |
| Intel         | DH61AGL G71256-202          | Desktop     | [666757a826](https://bsd-hardware.info/?probe=666757a826) | Jun 14, 2020 |
| PC Engines    | APU2                        | Desktop     | [dc1c86095f](https://bsd-hardware.info/?probe=dc1c86095f) | Jun 14, 2020 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [90e2b57f16](https://bsd-hardware.info/?probe=90e2b57f16) | Jun 14, 2020 |
| HPE           | ProLiant MicroServer Gen... | Server      | [be41b5cd29](https://bsd-hardware.info/?probe=be41b5cd29) | Jun 14, 2020 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [9ad34ffa59](https://bsd-hardware.info/?probe=9ad34ffa59) | Jun 14, 2020 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [06beb9ad2c](https://bsd-hardware.info/?probe=06beb9ad2c) | Jun 12, 2020 |
| CompuLab      | fitlet2                     | Mini pc     | [00c1939eac](https://bsd-hardware.info/?probe=00c1939eac) | Jun 03, 2020 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [48dd406069](https://bsd-hardware.info/?probe=48dd406069) | May 30, 2020 |
| Dell          | 0MD99X A12                  | Server      | [e2ab2682cb](https://bsd-hardware.info/?probe=e2ab2682cb) | May 27, 2020 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [94c4617d4e](https://bsd-hardware.info/?probe=94c4617d4e) | May 27, 2020 |
| Dell          | Latitude E6420              | Notebook    | [7c8a68918a](https://bsd-hardware.info/?probe=7c8a68918a) | May 27, 2020 |
| MSI           | Z87I GAMING AC              | Desktop     | [5d38b05178](https://bsd-hardware.info/?probe=5d38b05178) | May 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [bb2fcf8d92](https://bsd-hardware.info/?probe=bb2fcf8d92) | May 25, 2020 |
| Unknown       | Unknown                     | Desktop     | [3bcdac5d97](https://bsd-hardware.info/?probe=3bcdac5d97) | May 24, 2020 |
| HP            | ZBook 15                    | Notebook    | [3e9076f244](https://bsd-hardware.info/?probe=3e9076f244) | May 23, 2020 |
| HP            | ZBook 15                    | Notebook    | [23ec663f87](https://bsd-hardware.info/?probe=23ec663f87) | May 23, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [fa71e5839a](https://bsd-hardware.info/?probe=fa71e5839a) | May 23, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OpenBSD 6.8       | 16        | 3.14%   |
| OPNsense 21.1.5   | 14        | 2.75%   |
| FreeBSD 13.1      | 14        | 2.75%   |
| OPNsense 21.7.7   | 13        | 2.55%   |
| OPNsense 22.1     | 12        | 2.36%   |
| OPNsense 23.1.1   | 11        | 2.16%   |
| helloSystem 0.7.0 | 11        | 2.16%   |
| helloSystem 0.4.0 | 11        | 2.16%   |
| OPNsense 22.1.6   | 10        | 1.96%   |
| OPNsense 22.1.10  | 10        | 1.96%   |
| NomadBSD 1.3.2    | 10        | 1.96%   |
| GhostBSD 20.04.02 | 10        | 1.96%   |
| OPNsense 21.7.1   | 9         | 1.77%   |
| OPNsense 21.1     | 9         | 1.77%   |
| FreeBSD 13.0      | 9         | 1.77%   |
| OPNsense 22.7.9   | 8         | 1.57%   |
| OPNsense 22.7.4   | 8         | 1.57%   |
| OPNsense 22.7     | 8         | 1.57%   |
| OPNsense 22.1.1   | 8         | 1.57%   |
| OPNsense 21.1.3   | 8         | 1.57%   |
| OpenBSD 7.1       | 8         | 1.57%   |
| helloSystem 0.8.1 | 8         | 1.57%   |
| FreeBSD 12.1-p8   | 8         | 1.57%   |
| OPNsense 22.7.7   | 7         | 1.38%   |
| OPNsense 21.7.8   | 7         | 1.38%   |
| helloSystem 0.8.0 | 7         | 1.38%   |
| FreeBSD 13.1-p7   | 7         | 1.38%   |
| OPNsense 23.1     | 6         | 1.18%   |
| OPNsense 22.1.2   | 6         | 1.18%   |
| OPNsense 21.7.3   | 6         | 1.18%   |
| OPNsense 21.1.4   | 6         | 1.18%   |
| OpenBSD 7.2       | 6         | 1.18%   |
| OpenBSD 7.0       | 6         | 1.18%   |
| OpenBSD 6.9       | 6         | 1.18%   |
| helloSystem 0.5.0 | 6         | 1.18%   |
| OPNsense 23.1.3   | 5         | 0.98%   |
| OPNsense 22.1.4   | 5         | 0.98%   |
| OPNsense 21.7     | 5         | 0.98%   |
| OPNsense 21.1.7   | 5         | 0.98%   |
| OPNsense 21.1.6   | 5         | 0.98%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 183       | 44.53%  |
| FreeBSD     | 110       | 26.76%  |
| helloSystem | 39        | 9.49%   |
| OpenBSD     | 38        | 9.25%   |
| NomadBSD    | 18        | 4.38%   |
| GhostBSD    | 14        | 3.41%   |
| NetBSD      | 4         | 0.97%   |
| TrueNAS     | 2         | 0.49%   |
| HardenedBSD | 1         | 0.24%   |
| FuryBSD     | 1         | 0.24%   |
| FreeNAS     | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 391       | 98.24%  |
| i386   | 5         | 1.26%   |
| macppc | 1         | 0.25%   |
| arm64  | 1         | 0.25%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 228       | 54.68%  |
| helloDesktop  | 54        | 12.95%  |
| XFCE          | 34        | 8.15%   |
| KDE5          | 19        | 4.56%   |
| fvwm          | 18        | 4.32%   |
| Openbox       | 16        | 3.84%   |
| MATE          | 15        | 3.6%    |
| TWM           | 9         | 2.16%   |
| GNOME         | 7         | 1.68%   |
| i3            | 4         | 0.96%   |
| xinitrc       | 3         | 0.72%   |
| LXDE          | 3         | 0.72%   |
| AwesomeWM     | 3         | 0.72%   |
| X-Cinnamon    | 1         | 0.24%   |
| sway          | 1         | 0.24%   |
| Enlightenment | 1         | 0.24%   |
| Cinnamon      | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 234       | 58.5%   |
| X11     | 165       | 41.25%  |
| Wayland | 1         | 0.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 282       | 69.12%  |
| SLiM    | 70        | 17.16%  |
| LightDM | 24        | 5.88%   |
| SDDM    | 18        | 4.41%   |
| XDM     | 9         | 2.21%   |
| GDM     | 5         | 1.23%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 253       | 61.56%  |
| fr_FR           | 55        | 13.38%  |
| en_US           | 49        | 11.92%  |
| C               | 42        | 10.22%  |
| fr              | 3         | 0.73%   |
| de_DE           | 3         | 0.73%   |
| en_GB           | 2         | 0.49%   |
| fr_FR.US-ASCII  | 1         | 0.24%   |
| es_ES           | 1         | 0.24%   |
| en_US.ISO8859-1 | 1         | 0.24%   |
| en              | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 312       | 77.61%  |
| BIOS | 90        | 22.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 187       | 45.61%  |
| Zfs    | 172       | 41.95%  |
| Ffs    | 38        | 9.27%   |
| Cd9660 | 13        | 3.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 342       | 85.07%  |
| MBR     | 57        | 14.18%  |
| Unknown | 3         | 0.75%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 63        | 15.83%  |
| ASUSTek Computer        | 46        | 11.56%  |
| Lenovo                  | 42        | 10.55%  |
| Intel                   | 35        | 8.79%   |
| Hewlett-Packard         | 30        | 7.54%   |
| Unknown                 | 22        | 5.53%   |
| PC Engines              | 18        | 4.52%   |
| Gigabyte Technology     | 17        | 4.27%   |
| ASRock                  | 12        | 3.02%   |
| MSI                     | 11        | 2.76%   |
| Supermicro              | 10        | 2.51%   |
| AMI                     | 8         | 2.01%   |
| Apple                   | 7         | 1.76%   |
| Acer                    | 6         | 1.51%   |
| Fujitsu                 | 5         | 1.26%   |
| Deciso                  | 5         | 1.26%   |
| BESSTAR Tech            | 5         | 1.26%   |
| Techvision              | 4         | 1.01%   |
| Shuttle                 | 4         | 1.01%   |
| TUXEDO                  | 3         | 0.75%   |
| Toshiba                 | 3         | 0.75%   |
| Protectli               | 3         | 0.75%   |
| Sony                    | 2         | 0.5%    |
| RUNING                  | 2         | 0.5%    |
| MW                      | 2         | 0.5%    |
| Google                  | 2         | 0.5%    |
| Clevo                   | 2         | 0.5%    |
| AWOW                    | 2         | 0.5%    |
| ASRockRack              | 2         | 0.5%    |
| AMD                     | 2         | 0.5%    |
| ZOTAC                   | 1         | 0.25%   |
| YENTEK                  | 1         | 0.25%   |
| Wistron                 | 1         | 0.25%   |
| VeryPC                  | 1         | 0.25%   |
| Sophos                  | 1         | 0.25%   |
| Soekris Engineering     | 1         | 0.25%   |
| SECO                    | 1         | 0.25%   |
| Samsung Electronics     | 1         | 0.25%   |
| Raspberry Pi Foundation | 1         | 0.25%   |
| Pegatron                | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 23        | 5.78%   |
| Intel Q3XXG4-P V1.0            | 11        | 2.76%   |
| PC Engines APU2                | 10        | 2.51%   |
| AMI Aptio CRB                  | 6         | 1.51%   |
| Techvision TVI7309X            | 4         | 1.01%   |
| Intel H81U                     | 4         | 1.01%   |
| Dell OptiPlex 9020             | 4         | 1.01%   |
| ASUS All Series                | 4         | 1.01%   |
| PC Engines APU3                | 3         | 0.75%   |
| Intel CRESCENTBAY              | 3         | 0.75%   |
| Dell Precision M4500           | 3         | 0.75%   |
| Dell PowerEdge R710            | 3         | 0.75%   |
| Deciso Netboard A20            | 3         | 0.75%   |
| TUXEDO InfinityBook13V3        | 2         | 0.5%    |
| Toshiba PORTEGE Z930           | 2         | 0.5%    |
| Supermicro Super Server        | 2         | 0.5%    |
| Shuttle XS35V5                 | 2         | 0.5%    |
| RUNING B75M INTEL H3V          | 2         | 0.5%    |
| PC Engines apu4                | 2         | 0.5%    |
| PC Engines apu1                | 2         | 0.5%    |
| MW GMLK-2_5G4L                 | 2         | 0.5%    |
| HP ProLiant MicroServer Gen8   | 2         | 0.5%    |
| Gigabyte X570 I AORUS PRO WIFI | 2         | 0.5%    |
| Dell PowerEdge R815            | 2         | 0.5%    |
| Dell PowerEdge R220            | 2         | 0.5%    |
| Dell PowerEdge R200            | 2         | 0.5%    |
| Dell OptiPlex 7010             | 2         | 0.5%    |
| Dell OptiPlex 3050             | 2         | 0.5%    |
| Dell OptiPlex 3010             | 2         | 0.5%    |
| Dell Latitude 3410             | 2         | 0.5%    |
| BESSTAR Tech N40               | 2         | 0.5%    |
| BESSTAR Tech GK41              | 2         | 0.5%    |
| AWOW PC BOX                    | 2         | 0.5%    |
| ASUS Z170-P D3                 | 2         | 0.5%    |
| ASUS PRIME B450M-A             | 2         | 0.5%    |
| ASUS PRIME A320I-K             | 2         | 0.5%    |
| ASUS P8Z68-V LX                | 2         | 0.5%    |
| ZOTAC XXXXXX                   | 1         | 0.25%   |
| YENTEK R250                    | 1         | 0.25%   |
| Wistron ProLiant ML110 G6      | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 32        | 8.04%   |
| Unknown                 | 23        | 5.78%   |
| Dell OptiPlex           | 20        | 5.03%   |
| Dell PowerEdge          | 16        | 4.02%   |
| Dell Latitude           | 12        | 3.02%   |
| Intel Q3XXG4-P          | 11        | 2.76%   |
| PC Engines APU2         | 10        | 2.51%   |
| ASUS PRIME              | 10        | 2.51%   |
| HP Compaq               | 8         | 2.01%   |
| Dell Precision          | 7         | 1.76%   |
| AMI Aptio               | 6         | 1.51%   |
| HP ProLiant             | 5         | 1.26%   |
| Techvision TVI7309X     | 4         | 1.01%   |
| Intel H81U              | 4         | 1.01%   |
| HP ProDesk              | 4         | 1.01%   |
| Deciso Netboard         | 4         | 1.01%   |
| ASUS All                | 4         | 1.01%   |
| Acer Aspire             | 4         | 1.01%   |
| PC Engines APU3         | 3         | 0.75%   |
| Lenovo ThinkCentre      | 3         | 0.75%   |
| Intel CRESCENTBAY       | 3         | 0.75%   |
| HP EliteBook            | 3         | 0.75%   |
| TUXEDO InfinityBook13V3 | 2         | 0.5%    |
| Toshiba PORTEGE         | 2         | 0.5%    |
| Supermicro Super        | 2         | 0.5%    |
| Shuttle XS35V5          | 2         | 0.5%    |
| RUNING B75M             | 2         | 0.5%    |
| PC Engines apu4         | 2         | 0.5%    |
| PC Engines apu1         | 2         | 0.5%    |
| MW GMLK-2               | 2         | 0.5%    |
| Lenovo Legion           | 2         | 0.5%    |
| HP EliteDesk            | 2         | 0.5%    |
| Gigabyte X570           | 2         | 0.5%    |
| Dell Vostro             | 2         | 0.5%    |
| Dell Studio             | 2         | 0.5%    |
| Dell Inspiron           | 2         | 0.5%    |
| BESSTAR Tech N40        | 2         | 0.5%    |
| BESSTAR Tech GK41       | 2         | 0.5%    |
| AWOW PC                 | 2         | 0.5%    |
| ASUS Z170-P             | 2         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 48        | 12.06%  |
| 2016    | 44        | 11.06%  |
| 2018    | 42        | 10.55%  |
| 2020    | 41        | 10.3%   |
| 2021    | 29        | 7.29%   |
| 2013    | 27        | 6.78%   |
| 2012    | 22        | 5.53%   |
| 2022    | 21        | 5.28%   |
| 2015    | 21        | 5.28%   |
| 2014    | 21        | 5.28%   |
| 2011    | 17        | 4.27%   |
| 2010    | 16        | 4.02%   |
| 2017    | 15        | 3.77%   |
| 2008    | 10        | 2.51%   |
| 2009    | 9         | 2.26%   |
| Unknown | 8         | 2.01%   |
| 2007    | 6         | 1.51%   |
| 2006    | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 224       | 56.28%  |
| Notebook       | 115       | 28.89%  |
| Mini pc        | 28        | 7.04%   |
| Server         | 24        | 6.03%   |
| Firewall       | 3         | 0.75%   |
| All in one     | 3         | 0.75%   |
| System on chip | 1         | 0.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 376       | 94.47%  |
| Yes  | 22        | 5.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 137       | 33.83%  |
| 4.01-8.0        | 93        | 22.96%  |
| 16.01-24.0      | 90        | 22.22%  |
| 32.01-64.0      | 28        | 6.91%   |
| 2.01-3.0        | 22        | 5.43%   |
| 64.01-256.0     | 16        | 3.95%   |
| 1.01-2.0        | 6         | 1.48%   |
| 3.01-4.0        | 5         | 1.23%   |
| 24.01-32.0      | 5         | 1.23%   |
| More than 256.0 | 2         | 0.49%   |
| 0.51-1.0        | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 222       | 54.41%  |
| 0.51-1.0    | 108       | 26.47%  |
| 1.01-2.0    | 35        | 8.58%   |
| 2.01-3.0    | 15        | 3.68%   |
| 4.01-8.0    | 6         | 1.47%   |
| 8.01-16.0   | 6         | 1.47%   |
| 3.01-4.0    | 4         | 0.98%   |
| Unknown     | 4         | 0.98%   |
| 32.01-64.0  | 3         | 0.74%   |
| 64.01-256.0 | 2         | 0.49%   |
| 24.01-32.0  | 1         | 0.25%   |
| 16.01-24.0  | 1         | 0.25%   |
| 0           | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 254       | 62.72%  |
| 2      | 67        | 16.54%  |
| 0      | 38        | 9.38%   |
| 3      | 23        | 5.68%   |
| 4      | 8         | 1.98%   |
| 5      | 7         | 1.73%   |
| 6      | 4         | 0.99%   |
| 25     | 2         | 0.49%   |
| 10     | 1         | 0.25%   |
| 8      | 1         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 326       | 80.89%  |
| Yes       | 77        | 19.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 383       | 95.99%  |
| No        | 16        | 4.01%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 217       | 54.39%  |
| Yes       | 182       | 45.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 293       | 72.89%  |
| Yes       | 109       | 27.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| France  | 398       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Paris                    | 87        | 19.33%  |
| Toulouse                 | 8         | 1.78%   |
| Bordeaux                 | 8         | 1.78%   |
| Saint-Denis              | 7         | 1.56%   |
| Roubaix                  | 7         | 1.56%   |
| Franconville             | 7         | 1.56%   |
| Soisy-sur-Seine          | 5         | 1.11%   |
| Melun                    | 5         | 1.11%   |
| Marseille                | 5         | 1.11%   |
| Lyon                     | 5         | 1.11%   |
| Agen                     | 5         | 1.11%   |
| Rennes                   | 4         | 0.89%   |
| Noisy-le-Grand           | 4         | 0.89%   |
| Lille                    | 4         | 0.89%   |
| Colmar                   | 4         | 0.89%   |
| Villeurbanne             | 3         | 0.67%   |
| Vauvillers               | 3         | 0.67%   |
| Vaulx-en-Velin           | 3         | 0.67%   |
| Thionville               | 3         | 0.67%   |
| Rosny-sous-Bois          | 3         | 0.67%   |
| Nantes                   | 3         | 0.67%   |
| Montfermeil              | 3         | 0.67%   |
| Marcq-en-Baroeul         | 3         | 0.67%   |
| Mâcon                   | 3         | 0.67%   |
| Fontenay-sous-Bois       | 3         | 0.67%   |
| Dijon                    | 3         | 0.67%   |
| Cognac                   | 3         | 0.67%   |
| Clermont-Ferrand         | 3         | 0.67%   |
| Carry-le-Rouet           | 3         | 0.67%   |
| Bonson                   | 3         | 0.67%   |
| Asnieres-sur-Seine       | 3         | 0.67%   |
| Г‰chirolles           | 2         | 0.44%   |
| Villeneuve-Saint-Georges | 2         | 0.44%   |
| Villejuif                | 2         | 0.44%   |
| Vichy                    | 2         | 0.44%   |
| Stiring-Wendel           | 2         | 0.44%   |
| Seyssinet-Pariset        | 2         | 0.44%   |
| Sarcelles                | 2         | 0.44%   |
| Sallanches               | 2         | 0.44%   |
| Saint-Raphaël           | 2         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 60        | 89     | 13.02%  |
| Seagate             | 58        | 89     | 12.58%  |
| WDC                 | 52        | 100    | 11.28%  |
| Crucial             | 41        | 51     | 8.89%   |
| Kingston            | 31        | 47     | 6.72%   |
| Transcend           | 25        | 37     | 5.42%   |
| Toshiba             | 25        | 40     | 5.42%   |
| China               | 18        | 28     | 3.9%    |
| SanDisk             | 17        | 27     | 3.69%   |
| Intel               | 13        | 19     | 2.82%   |
| Phison              | 11        | 12     | 2.39%   |
| HGST                | 9         | 16     | 1.95%   |
| PNY                 | 8         | 15     | 1.74%   |
| Micron Technology   | 8         | 12     | 1.74%   |
| NVMe                | 7         | 7      | 1.52%   |
| Hoodisk             | 6         | 6      | 1.3%    |
| SK hynix            | 5         | 5      | 1.08%   |
| Hitachi             | 5         | 5      | 1.08%   |
| Corsair             | 5         | 9      | 1.08%   |
| Fujitsu             | 4         | 4      | 0.87%   |
| FORESEE             | 4         | 5      | 0.87%   |
| Apple               | 4         | 6      | 0.87%   |
| OCZ                 | 3         | 4      | 0.65%   |
| LDLC                | 3         | 3      | 0.65%   |
| Hewlett-Packard     | 3         | 6      | 0.65%   |
| Dell                | 3         | 48     | 0.65%   |
| A-DATA Technology   | 3         | 3      | 0.65%   |
| SPCC                | 2         | 2      | 0.43%   |
| NETAPP              | 2         | 4      | 0.43%   |
| Maxtor              | 2         | 3      | 0.43%   |
| Innodisk            | 2         | 2      | 0.43%   |
| Generic             | 2         | 2      | 0.43%   |
| Fanxiang            | 2         | 2      | 0.43%   |
| TEXTORM             | 1         | 1      | 0.22%   |
| TCSUNBOW            | 1         | 3      | 0.22%   |
| Silicon Power       | 1         | 1      | 0.22%   |
| ShiJi               | 1         | 2      | 0.22%   |
| SABRENT             | 1         | 1      | 0.22%   |
| Pccooler            | 1         | 1      | 0.22%   |
| OPENBSD             | 1         | 2      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Phison SATA SSD 16GB                | 8         | 1.62%   |
| Samsung SSD 850 EVO 250GB           | 7         | 1.41%   |
| Kingston SV300S37A120G 120GB        | 6         | 1.21%   |
| Kingston SA400S37240G 240GB         | 6         | 1.21%   |
| China MSATA 32GB SSD                | 6         | 1.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 5         | 1.01%   |
| Crucial CT250MX500SSD1 250GB        | 5         | 1.01%   |
| Crucial CT1000P1SSD8 1TB            | 5         | 1.01%   |
| Transcend TS256GMTS952T2 256GB      | 4         | 0.81%   |
| SanDisk SSD PLUS 120GB              | 4         | 0.81%   |
| PNY CS900 120GB SSD                 | 4         | 0.81%   |
| Crucial CT120BX500SSD1 120GB        | 4         | 0.81%   |
| Crucial CT1000BX500SSD1 1TB         | 4         | 0.81%   |
| China MSATA 64GB SSD                | 4         | 0.81%   |
| WDC WDS240G2G0A-00JH30 240GB        | 3         | 0.61%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3         | 0.61%   |
| Transcend TS128GMSA230S 128GB       | 3         | 0.61%   |
| Seagate ST3500418AS 500GB           | 3         | 0.61%   |
| Seagate ST1000LM049-2GH172 1TB      | 3         | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 0.61%   |
| Kingston SUV500MS120G 120GB         | 3         | 0.61%   |
| Kingston SA400S37120G 120GB         | 3         | 0.61%   |
| Hoodisk SSD 32GB                    | 3         | 0.61%   |
| HGST HUS724020ALA640 2TB            | 3         | 0.61%   |
| HP RAID 1(1+0) 240GB                | 3         | 0.61%   |
| Crucial CT500MX500SSD1 500GB        | 3         | 0.61%   |
| Crucial CT250P2SSD8 250GB           | 3         | 0.61%   |
| Crucial CT240BX500SSD1 240GB        | 3         | 0.61%   |
| Crucial CT1050MX300SSD1 1TB         | 3         | 0.61%   |
| China SATA SSD 16GB                 | 3         | 0.61%   |
| WDC WD40EFRX-68N32N0 4TB            | 2         | 0.4%    |
| WDC WD3200BPVT-80JJ5T0 320GB        | 2         | 0.4%    |
| WDC WD2000FYYX 2TB                  | 2         | 0.4%    |
| Transcend TS256GSSD230S 256GB       | 2         | 0.4%    |
| Transcend TS256GMTS430S 256GB       | 2         | 0.4%    |
| Transcend TS128GSSD420K 128GB       | 2         | 0.4%    |
| Transcend TS120GMTS420S 120GB       | 2         | 0.4%    |
| Toshiba MK2556GSY 250GB             | 2         | 0.4%    |
| Toshiba KSG60ZMV256G M.2 2280 256GB | 2         | 0.4%    |
| Toshiba HDWD120 2TB                 | 2         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 56        | 86     | 33.33%  |
| WDC                 | 44        | 89     | 26.19%  |
| Toshiba             | 19        | 32     | 11.31%  |
| Samsung Electronics | 9         | 16     | 5.36%   |
| HGST                | 9         | 16     | 5.36%   |
| NVMe                | 5         | 5      | 2.98%   |
| Hitachi             | 5         | 5      | 2.98%   |
| Fujitsu             | 4         | 4      | 2.38%   |
| Hewlett-Packard     | 3         | 6      | 1.79%   |
| Dell                | 3         | 48     | 1.79%   |
| NETAPP              | 2         | 4      | 1.19%   |
| Maxtor              | 2         | 3      | 1.19%   |
| Generic             | 2         | 2      | 1.19%   |
| Apple               | 2         | 4      | 1.19%   |
| SABRENT             | 1         | 1      | 0.6%    |
| OPENBSD             | 1         | 2      | 0.6%    |
| LDLC F6+            | 1         | 1      | 0.6%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 43     | 13.85%  |
| Crucial             | 29        | 33     | 12.55%  |
| Kingston            | 28        | 43     | 12.12%  |
| Transcend           | 24        | 35     | 10.39%  |
| China               | 18        | 28     | 7.79%   |
| SanDisk             | 17        | 27     | 7.36%   |
| PNY                 | 8         | 15     | 3.46%   |
| Phison              | 8         | 9      | 3.46%   |
| Intel               | 7         | 8      | 3.03%   |
| WDC                 | 6         | 7      | 2.6%    |
| Toshiba             | 6         | 8      | 2.6%    |
| Hoodisk             | 6         | 6      | 2.6%    |
| FORESEE             | 4         | 5      | 1.73%   |
| Corsair             | 4         | 5      | 1.73%   |
| SK hynix            | 3         | 3      | 1.3%    |
| OCZ                 | 3         | 4      | 1.3%    |
| A-DATA Technology   | 3         | 3      | 1.3%    |
| SPCC                | 2         | 2      | 0.87%   |
| NVMe                | 2         | 2      | 0.87%   |
| Micron Technology   | 2         | 6      | 0.87%   |
| Innodisk            | 2         | 2      | 0.87%   |
| Apple               | 2         | 2      | 0.87%   |
| TEXTORM             | 1         | 1      | 0.43%   |
| TCSUNBOW            | 1         | 3      | 0.43%   |
| Silicon Power       | 1         | 1      | 0.43%   |
| ShiJi               | 1         | 2      | 0.43%   |
| Seagate             | 1         | 2      | 0.43%   |
| Pccooler            | 1         | 1      | 0.43%   |
| LITEON              | 1         | 2      | 0.43%   |
| Kston               | 1         | 1      | 0.43%   |
| Kingchuxing         | 1         | 2      | 0.43%   |
| Integral            | 1         | 1      | 0.43%   |
| Indilinx            | 1         | 7      | 0.43%   |
| EMTEC               | 1         | 1      | 0.43%   |
| BORY                | 1         | 2      | 0.43%   |
| BIWIN               | 1         | 1      | 0.43%   |
| Apacer              | 1         | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 214       | 324    | 51.82%  |
| HDD  | 139       | 324    | 33.66%  |
| NVMe | 60        | 91     | 14.53%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 318       | 648    | 84.13%  |
| NVMe | 60        | 91     | 15.87%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 260       | 451    | 70.08%  |
| 0.51-1.0   | 65        | 102    | 17.52%  |
| 1.01-2.0   | 30        | 61     | 8.09%   |
| 4.01-10.0  | 6         | 11     | 1.62%   |
| 3.01-4.0   | 5         | 13     | 1.35%   |
| 2.01-3.0   | 5         | 10     | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 137       | 33.58%  |
| 1-20           | 68        | 16.67%  |
| 251-500        | 57        | 13.97%  |
| 21-50          | 48        | 11.76%  |
| 501-1000       | 37        | 9.07%   |
| 51-100         | 37        | 9.07%   |
| 1001-2000      | 12        | 2.94%   |
| More than 3000 | 5         | 1.23%   |
| 2001-3000      | 5         | 1.23%   |
| Unknown        | 2         | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 340       | 83.95%  |
| 21-50          | 27        | 6.67%   |
| 101-250        | 14        | 3.46%   |
| 251-500        | 8         | 1.98%   |
| 51-100         | 8         | 1.98%   |
| 501-1000       | 3         | 0.74%   |
| More than 3000 | 2         | 0.49%   |
| Unknown        | 2         | 0.49%   |
| 1001-2000      | 1         | 0.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB          | 2         | 3      | 3.28%   |
| WDC WD3200BPVT-80JJ5T0 320GB          | 2         | 2      | 3.28%   |
| Seagate ST1000NM0011 1TB              | 2         | 3      | 3.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 3      | 3.28%   |
| Samsung Electronics HD501LJ 500GB     | 2         | 2      | 3.28%   |
| Kingston SV300S37A120G 120GB          | 2         | 2      | 3.28%   |
| WDC WD6400BPVT-22HXZT3 640GB          | 1         | 1      | 1.64%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1         | 1      | 1.64%   |
| WDC WD5002ABYS-18B1B0 500GB           | 1         | 1      | 1.64%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 4      | 1.64%   |
| WDC WD2500BEVS-60UST0 250GB           | 1         | 1      | 1.64%   |
| WDC WD2002FYPS-02W3B0 2TB             | 1         | 1      | 1.64%   |
| WDC WD15EADS-00P8B0 1.5TB             | 1         | 1      | 1.64%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 1.64%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 1.64%   |
| WDC WD10EAVS-00D7B0 1TB               | 1         | 1      | 1.64%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 1.64%   |
| WDC WD1001FAES-75W7A0 1TB             | 1         | 1      | 1.64%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 1.64%   |
| Toshiba MK5065GSX 500GB               | 1         | 1      | 1.64%   |
| Toshiba MK1629GSGF 160GB              | 1         | 3      | 1.64%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 1.64%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 1.64%   |
| Seagate ST9320423AS 320GB             | 1         | 1      | 1.64%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 1.64%   |
| Seagate ST500VT000-1DK142 500GB       | 1         | 1      | 1.64%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 2      | 1.64%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.64%   |
| Seagate ST380013AS 80GB               | 1         | 2      | 1.64%   |
| Seagate ST3250620AS 250GB             | 1         | 1      | 1.64%   |
| Seagate ST320LT012-9WS14C 320GB       | 1         | 6      | 1.64%   |
| Seagate ST3160212AS 160GB             | 1         | 1      | 1.64%   |
| Seagate ST3160023AS 160GB             | 1         | 1      | 1.64%   |
| Seagate ST31000524AS 1TB              | 1         | 1      | 1.64%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 1.64%   |
| SanDisk SDSSDA240G 240GB              | 1         | 1      | 1.64%   |
| SanDisk SD7UB3Q256G1001 256GB         | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 840 EVO 500GB | 1         | 2      | 1.64%   |
| Samsung Electronics HD322GJ 320GB     | 1         | 1      | 1.64%   |
| Samsung Electronics HD256GJ 250GB     | 1         | 1      | 1.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 20     | 27.59%  |
| Seagate             | 16        | 26     | 27.59%  |
| Toshiba             | 4         | 6      | 6.9%    |
| Samsung Electronics | 4         | 7      | 6.9%    |
| Kingston            | 3         | 3      | 5.17%   |
| A-DATA Technology   | 3         | 3      | 5.17%   |
| SanDisk             | 2         | 2      | 3.45%   |
| Hitachi             | 2         | 2      | 3.45%   |
| HGST                | 2         | 3      | 3.45%   |
| OCZ                 | 1         | 2      | 1.72%   |
| Maxtor              | 1         | 1      | 1.72%   |
| Intel               | 1         | 1      | 1.72%   |
| Innodisk            | 1         | 1      | 1.72%   |
| Crucial             | 1         | 1      | 1.72%   |
| Corsair             | 1         | 2      | 1.72%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 26     | 38.1%   |
| WDC                 | 14        | 17     | 33.33%  |
| Toshiba             | 4         | 6      | 9.52%   |
| Samsung Electronics | 3         | 5      | 7.14%   |
| Hitachi             | 2         | 2      | 4.76%   |
| HGST                | 2         | 3      | 4.76%   |
| Maxtor              | 1         | 1      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 60     | 70.37%  |
| SSD  | 16        | 20     | 29.63%  |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 318       | 636    | 82.38%  |
| Malfunc  | 53        | 80     | 13.73%  |
| Detected | 15        | 23     | 3.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 300       | 63.42%  |
| AMD                           | 69        | 14.59%  |
| Samsung Electronics           | 22        | 4.65%   |
| Micron/Crucial Technology     | 14        | 2.96%   |
| Broadcom / LSI                | 14        | 2.96%   |
| ASMedia Technology            | 7         | 1.48%   |
| SanDisk                       | 5         | 1.06%   |
| Micron Technology             | 5         | 1.06%   |
| Silicon Motion                | 4         | 0.85%   |
| Marvell Technology Group      | 4         | 0.85%   |
| Hewlett-Packard               | 4         | 0.85%   |
| Phison Electronics            | 3         | 0.63%   |
| Nvidia                        | 3         | 0.63%   |
| Kingston Technology Company   | 3         | 0.63%   |
| JMicron Technology            | 3         | 0.63%   |
| VIA Technologies              | 2         | 0.42%   |
| SK hynix                      | 2         | 0.42%   |
| MAXIO Technology (Hangzhou)   | 2         | 0.42%   |
| Chelsio Communications        | 2         | 0.42%   |
| Transcend                     | 1         | 0.21%   |
| Silicon Image                 | 1         | 0.21%   |
| Seagate Technology            | 1         | 0.21%   |
| KIOXIA                        | 1         | 0.21%   |
| Integrated Technology Express | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 44        | 8.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 21        | 3.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 19        | 3.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 18        | 3.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 17        | 3.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 2.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 2.06%   |
| Intel SATA Controller [RAID mode]                                                | 10        | 1.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 10        | 1.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 10        | 1.88%   |
| AMD FCH SATA Controller [IDE mode]                                               | 10        | 1.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 9         | 1.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 1.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 1.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 1.5%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 7         | 1.31%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.31%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 7         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 1.31%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 1.13%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 6         | 1.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 6         | 1.13%   |
| AMD 400 Series Chipset SATA Controller                                           | 6         | 1.13%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 0.94%   |
| Micron NVMe Storage Controller                                                   | 5         | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 5         | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 0.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 5         | 0.94%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 5         | 0.94%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 5         | 0.94%   |
| AMD 500 Series Chipset SATA Controller                                           | 5         | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 0.75%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 4         | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 0.75%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 4         | 0.75%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 4         | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 315       | 65.49%  |
| NVMe | 66        | 13.72%  |
| IDE  | 52        | 10.81%  |
| RAID | 36        | 7.48%   |
| SAS  | 6         | 1.25%   |
| SCSI | 6         | 1.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 320       | 80.2%   |
| AMD     | 77        | 19.3%   |
| PowerPC | 1         | 0.25%   |
| ARM     | 1         | 0.25%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| AMD GX-412TC SOC                       | 15        | 3.73%   |
| Intel Core i3-4010U CPU @ 1.70GHz      | 8         | 1.99%   |
| Intel Celeron J4125 CPU @ 2.00GHz      | 7         | 1.74%   |
| Intel Core i5-5300U CPU @ 2.30GHz      | 5         | 1.24%   |
| Intel Core i5-2520M CPU @ 2.50GHz      | 5         | 1.24%   |
| Intel Celeron CPU J1900 @ 1.99GHz      | 5         | 1.24%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 4         | 1%      |
| Intel Celeron N5105 @ 2.00GHz          | 4         | 1%      |
| Intel Celeron CPU J3455 @ 1.50GHz      | 4         | 1%      |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz    | 3         | 0.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz      | 3         | 0.75%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 3         | 0.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 3         | 0.75%   |
| Intel Core i5-6500T CPU @ 2.50GHz      | 3         | 0.75%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3         | 0.75%   |
| Intel Core i5-4300Y CPU @ 1.60GHz      | 3         | 0.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 3         | 0.75%   |
| Intel Core i5-2500K CPU @ 3.30GHz      | 3         | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz     | 3         | 0.75%   |
| Intel Core i5 CPU M 560 @ 2.67GH       | 3         | 0.75%   |
| Intel Core i3-3225 CPU @ 3.30GHz       | 3         | 0.75%   |
| Intel Core i3-3220 CPU @ 3.30GHz       | 3         | 0.75%   |
| Intel Core 2 Quad CPU                  | 3         | 0.75%   |
| Intel Celeron CPU N3160 @ 1.60GHz      | 3         | 0.75%   |
| Intel Celeron CPU N3150 @ 1.60GHz      | 3         | 0.75%   |
| Intel Celeron CPU J3160 @ 1.60GHz      | 3         | 0.75%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz      | 3         | 0.75%   |
| Intel 686-class                        | 3         | 0.75%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 3         | 0.75%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 3         | 0.75%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 3         | 0.75%   |
| AMD G-T40E Processor                   | 3         | 0.75%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz   | 2         | 0.5%    |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz    | 2         | 0.5%    |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz    | 2         | 0.5%    |
| Intel Core i7-9700 CPU @ 3.00GHz       | 2         | 0.5%    |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2         | 0.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz      | 2         | 0.5%    |
| Intel Core i7-6500U CPU @ 2.50GHz      | 2         | 0.5%    |
| Intel Core i7-4510U CPU @ 2.00GHz      | 2         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 86        | 21.45%  |
| Intel Celeron           | 46        | 11.47%  |
| Intel Core i7           | 44        | 10.97%  |
| Intel Core i3           | 43        | 10.72%  |
| Intel Xeon              | 33        | 8.23%   |
| Intel Atom              | 20        | 4.99%   |
| AMD GX                  | 19        | 4.74%   |
| Other                   | 13        | 3.24%   |
| Intel Core 2 Duo        | 12        | 2.99%   |
| AMD Ryzen 7             | 12        | 2.99%   |
| AMD Ryzen 5             | 11        | 2.74%   |
| Intel Pentium           | 7         | 1.75%   |
| Intel Core 2 Quad       | 7         | 1.75%   |
| AMD Ryzen 7 PRO         | 4         | 1%      |
| AMD EPYC                | 4         | 1%      |
| Intel 686-class         | 3         | 0.75%   |
| AMD Opteron             | 3         | 0.75%   |
| AMD G                   | 3         | 0.75%   |
| Intel Xeon Silver       | 2         | 0.5%    |
| Intel Pentium Gold      | 2         | 0.5%    |
| AMD Ryzen 3             | 2         | 0.5%    |
| AMD E1                  | 2         | 0.5%    |
| AMD E                   | 2         | 0.5%    |
| AMD Athlon 64 X2        | 2         | 0.5%    |
| AMD Athlon              | 2         | 0.5%    |
| AMD A8                  | 2         | 0.5%    |
| Intel Pentium Silver    | 1         | 0.25%   |
| Intel Pentium M         | 1         | 0.25%   |
| Intel Pentium Dual-Core | 1         | 0.25%   |
| Intel Pentium Dual      | 1         | 0.25%   |
| Intel Genuine           | 1         | 0.25%   |
| Intel Core M            | 1         | 0.25%   |
| Intel Core 2            | 1         | 0.25%   |
| ARM Cortex              | 1         | 0.25%   |
| AMD Ryzen 9             | 1         | 0.25%   |
| AMD Ryzen 5 PRO         | 1         | 0.25%   |
| AMD Phenom II X4        | 1         | 0.25%   |
| AMD FX                  | 1         | 0.25%   |
| AMD A6                  | 1         | 0.25%   |
| AMD A4                  | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 167       | 41.75%  |
| 2       | 136       | 34%     |
| Unknown | 25        | 6.25%   |
| 8       | 21        | 5.25%   |
| 6       | 15        | 3.75%   |
| 16      | 14        | 3.5%    |
| 12      | 13        | 3.25%   |
| 1       | 3         | 0.75%   |
| 64      | 2         | 0.5%    |
| 32      | 2         | 0.5%    |
| 24      | 1         | 0.25%   |
| 10      | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 374       | 93.97%  |
| Unknown | 13        | 3.27%   |
| 2       | 9         | 2.26%   |
| 4       | 2         | 0.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 201       | 50.38%  |
| 2       | 172       | 43.11%  |
| Unknown | 26        | 6.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 60        | 14.96%  |
| Haswell       | 45        | 11.22%  |
| IvyBridge     | 32        | 7.98%   |
| SandyBridge   | 27        | 6.73%   |
| Skylake       | 26        | 6.48%   |
| Silvermont    | 25        | 6.23%   |
| Unknown       | 20        | 4.99%   |
| Puma          | 17        | 4.24%   |
| Penryn        | 17        | 4.24%   |
| Broadwell     | 13        | 3.24%   |
| Westmere      | 11        | 2.74%   |
| Bonnell       | 11        | 2.74%   |
| Zen 2         | 10        | 2.49%   |
| Goldmont plus | 9         | 2.24%   |
| Goldmont      | 9         | 2.24%   |
| Core          | 9         | 2.24%   |
| Zen+          | 8         | 2%      |
| Zen 3         | 8         | 2%      |
| Zen           | 7         | 1.75%   |
| Nehalem       | 7         | 1.75%   |
| Jaguar        | 6         | 1.5%    |
| Bobcat        | 6         | 1.5%    |
| Piledriver    | 4         | 1%      |
| TigerLake     | 3         | 0.75%   |
| CometLake     | 3         | 0.75%   |
| Steamroller   | 2         | 0.5%    |
| Excavator     | 2         | 0.5%    |
| P6            | 1         | 0.25%   |
| K8 Hammer     | 1         | 0.25%   |
| K10 Llano     | 1         | 0.25%   |
| K10           | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 239       | 61.92%  |
| AMD                        | 59        | 15.28%  |
| Nvidia                     | 55        | 14.25%  |
| Matrox Electronics Systems | 22        | 5.7%    |
| ASPEED Technology          | 11        | 2.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 18        | 4.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 3.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 3.57%   |
| Intel HD Graphics 530                                                                    | 13        | 3.32%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 12        | 3.06%   |
| Intel HD Graphics 620                                                                    | 11        | 2.81%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 11        | 2.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 2.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 2.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 2.3%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 2.3%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 2.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 2.3%    |
| Intel HD Graphics 5500                                                                   | 8         | 2.04%   |
| Intel JasperLake [UHD Graphics]                                                          | 7         | 1.79%   |
| Intel HD Graphics 630                                                                    | 7         | 1.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.53%   |
| Intel HD Graphics 500                                                                    | 5         | 1.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.28%   |
| AMD ES1000                                                                               | 5         | 1.28%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.02%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.02%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 1.02%   |
| Intel HD Graphics 510                                                                    | 4         | 1.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.02%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.02%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 3         | 0.77%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 3         | 0.77%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.77%   |
| Matrox Electronics Systems MGA G200EH                                                    | 3         | 0.77%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 0.77%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 3         | 0.77%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 0.77%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 3         | 0.77%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 207       | 51.62%  |
| 1 x AMD                  | 54        | 13.47%  |
| 1 x Nvidia               | 37        | 9.23%   |
| Other                    | 36        | 8.98%   |
| 1 x Matrox               | 22        | 5.49%   |
| Intel + Nvidia           | 15        | 3.74%   |
| 2 x Intel                | 14        | 3.49%   |
| 1 x ASPEED               | 10        | 2.49%   |
| Intel + AMD              | 2         | 0.5%    |
| 2 x AMD                  | 1         | 0.25%   |
| Nvidia + ASPEED          | 1         | 0.25%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.25%   |
| AMD + Nvidia             | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 331       | 82.54%  |
| Unknown     | 44        | 10.97%  |
| Proprietary | 26        | 6.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 352       | 88%     |
| 0.51-1.0   | 14        | 3.5%    |
| 0.01-0.5   | 9         | 2.25%   |
| 1.01-2.0   | 8         | 2%      |
| 7.01-8.0   | 6         | 1.5%    |
| 5.01-6.0   | 6         | 1.5%    |
| 3.01-4.0   | 3         | 0.75%   |
| 8.01-16.0  | 2         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 18        | 12.86%  |
| LG Display              | 14        | 10%     |
| Chimei Innolux          | 14        | 10%     |
| Dell                    | 12        | 8.57%   |
| Samsung Electronics     | 10        | 7.14%   |
| BOE                     | 8         | 5.71%   |
| Iiyama                  | 7         | 5%      |
| Hewlett-Packard         | 5         | 3.57%   |
| Apple                   | 5         | 3.57%   |
| Philips                 | 4         | 2.86%   |
| Idek Iiyama             | 4         | 2.86%   |
| Goldstar                | 4         | 2.86%   |
| Chi Mei Optoelectronics | 4         | 2.86%   |
| Acer                    | 4         | 2.86%   |
| BenQ                    | 3         | 2.14%   |
| AOC                     | 3         | 2.14%   |
| Ancor Communications    | 3         | 2.14%   |
| LGD                     | 2         | 1.43%   |
| Lenovo                  | 2         | 1.43%   |
| ViewSonic               | 1         | 0.71%   |
| Sony                    | 1         | 0.71%   |
| Sharp                   | 1         | 0.71%   |
| PRI                     | 1         | 0.71%   |
| PKB                     | 1         | 0.71%   |
| Packard Bell            | 1         | 0.71%   |
| Nvidia                  | 1         | 0.71%   |
| LG Electronics          | 1         | 0.71%   |
| Lenovo Group Limited    | 1         | 0.71%   |
| IBM                     | 1         | 0.71%   |
| CSO                     | 1         | 0.71%   |
| CPT                     | 1         | 0.71%   |
| CKL                     | 1         | 0.71%   |
| ASUSTek Computer        | 1         | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 3         | 2.14%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch                 | 2         | 1.43%   |
| LGD LCD Monitor 1600x900                                                 | 2         | 1.43%   |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                     | 2         | 1.43%   |
| Idek Iiyama LCD Monitor PLX2783H 1920x1080                               | 2         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch         | 2         | 1.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 1.43%   |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                    | 2         | 1.43%   |
| BenQ EW3270U BNQ7950 3840x2160 700x390mm 31.5-inch                       | 2         | 1.43%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch           | 2         | 1.43%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 2         | 1.43%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                        | 2         | 1.43%   |
| Acer V223HQ ACR0070 1920x1080 470x270mm 21.3-inch                        | 2         | 1.43%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 480x270mm 21.7-inch               | 1         | 0.71%   |
| Sony TV  *00 SNYF903 3840x2160 950x540mm 43.0-inch                       | 1         | 0.71%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch                  | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch      | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SyncMaster 3520x1200                     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC544E 1024x600 220x130mm 10.1-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                        | 1         | 0.71%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 0.71%   |
| PRI LED-MONITOR PRI0828 3840x2160 1150x650mm 52.0-inch                   | 1         | 0.71%   |
| PKB LCD Monitor MAE200W 1680x1050                                        | 1         | 0.71%   |
| Philips PHL 439P1 PHL0973 3840x2160 940x530mm 42.5-inch                  | 1         | 0.71%   |
| Philips LCD Monitor PHLC00B 1280x1024 340x270mm 17.1-inch                | 1         | 0.71%   |
| Packard Bell Viseo 200Ws PKB00C2 1600x900 440x250mm 19.9-inch            | 1         | 0.71%   |
| Nvidia LCD Monitor Default Flat Panel 1440x900                           | 1         | 0.71%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                        | 1         | 0.71%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 0.71%   |
| LG Display LCD Monitor LGD063F 1920x1080 380x210mm 17.1-inch             | 1         | 0.71%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 0.71%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 1         | 0.71%   |
| LG Display LCD Monitor LGD0438 1366x768 340x190mm 15.3-inch              | 1         | 0.71%   |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch              | 1         | 0.71%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 59        | 43.38%  |
| 1366x768 (WXGA)    | 26        | 19.12%  |
| 3840x2160 (4K)     | 8         | 5.88%   |
| 2560x1440 (QHD)    | 8         | 5.88%   |
| 1600x900 (HD+)     | 7         | 5.15%   |
| 1280x1024 (SXGA)   | 7         | 5.15%   |
| 1280x800 (WXGA)    | 5         | 3.68%   |
| 1680x1050 (WSXGA+) | 4         | 2.94%   |
| 1440x900 (WXGA+)   | 4         | 2.94%   |
| 1024x600           | 2         | 1.47%   |
| 3520x1200          | 1         | 0.74%   |
| 2880x1800          | 1         | 0.74%   |
| 2560x1080          | 1         | 0.74%   |
| 1920x1200 (WUXGA)  | 1         | 0.74%   |
| 1440x960           | 1         | 0.74%   |
| Unknown            | 1         | 0.74%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 19.42%  |
| 13      | 24        | 17.27%  |
| 12      | 12        | 8.63%   |
| Unknown | 12        | 8.63%   |
| 24      | 10        | 7.19%   |
| 27      | 8         | 5.76%   |
| 23      | 8         | 5.76%   |
| 21      | 8         | 5.76%   |
| 19      | 8         | 5.76%   |
| 17      | 8         | 5.76%   |
| 10      | 3         | 2.16%   |
| 52      | 2         | 1.44%   |
| 31      | 2         | 1.44%   |
| 14      | 2         | 1.44%   |
| 43      | 1         | 0.72%   |
| 42      | 1         | 0.72%   |
| 22      | 1         | 0.72%   |
| 18      | 1         | 0.72%   |
| 11      | 1         | 0.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 35.25%  |
| 501-600     | 25        | 17.99%  |
| 201-300     | 23        | 16.55%  |
| 401-500     | 14        | 10.07%  |
| Unknown     | 12        | 8.63%   |
| 351-400     | 9         | 6.47%   |
| 601-700     | 3         | 2.16%   |
| 1001-1500   | 2         | 1.44%   |
| 901-1000    | 2         | 1.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 96        | 75%     |
| Unknown | 12        | 9.38%   |
| 16/10   | 11        | 8.59%   |
| 5/4     | 7         | 5.47%   |
| 3/2     | 2         | 1.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 25        | 17.99%  |
| 91-100         | 23        | 16.55%  |
| 201-250        | 22        | 15.83%  |
| 61-70          | 12        | 8.63%   |
| Unknown        | 12        | 8.63%   |
| 151-200        | 11        | 7.91%   |
| 301-350        | 8         | 5.76%   |
| 121-130        | 5         | 3.6%    |
| 141-150        | 4         | 2.88%   |
| 101-110        | 4         | 2.88%   |
| 41-50          | 3         | 2.16%   |
| More than 1000 | 2         | 1.44%   |
| 351-500        | 2         | 1.44%   |
| 251-300        | 2         | 1.44%   |
| 501-1000       | 2         | 1.44%   |
| 71-80          | 1         | 0.72%   |
| 51-60          | 1         | 0.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 43        | 31.39%  |
| 101-120       | 39        | 28.47%  |
| 51-100        | 34        | 24.82%  |
| Unknown       | 12        | 8.76%   |
| 161-240       | 5         | 3.65%   |
| More than 240 | 3         | 2.19%   |
| 1-50          | 1         | 0.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 254       | 62.56%  |
| 1     | 140       | 34.48%  |
| 2     | 12        | 2.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 275       | 47.99%  |
| Realtek Semiconductor           | 149       | 26%     |
| Broadcom                        | 48        | 8.38%   |
| Qualcomm Atheros                | 41        | 7.16%   |
| AMD                             | 5         | 0.87%   |
| TP-Link                         | 4         | 0.7%    |
| Marvell Technology Group        | 4         | 0.7%    |
| Ralink Technology               | 3         | 0.52%   |
| Qualcomm                        | 3         | 0.52%   |
| Huawei Technologies             | 3         | 0.52%   |
| Edimax Technology               | 3         | 0.52%   |
| Apple                           | 3         | 0.52%   |
| VIA Technologies                | 2         | 0.35%   |
| Sierra Wireless                 | 2         | 0.35%   |
| Ralink                          | 2         | 0.35%   |
| QLogic                          | 2         | 0.35%   |
| Nvidia                          | 2         | 0.35%   |
| MediaTek                        | 2         | 0.35%   |
| IMC Networks                    | 2         | 0.35%   |
| D-Link System                   | 2         | 0.35%   |
| Chelsio Communications          | 2         | 0.35%   |
| Xiaomi                          | 1         | 0.17%   |
| Silicom                         | 1         | 0.17%   |
| Samsung Electronics             | 1         | 0.17%   |
| Sagem                           | 1         | 0.17%   |
| Qualcomm Atheros Communications | 1         | 0.17%   |
| Microchip Technology            | 1         | 0.17%   |
| Mellanox Technologies           | 1         | 0.17%   |
| Hewlett-Packard                 | 1         | 0.17%   |
| Emulex                          | 1         | 0.17%   |
| Dell                            | 1         | 0.17%   |
| Aquantia                        | 1         | 0.17%   |
| American Megatrends             | 1         | 0.17%   |
| Accton Technology               | 1         | 0.17%   |
| 3Com                            | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 129       | 17.89%  |
| Intel I211 Gigabit Network Connection                                         | 47        | 6.52%   |
| Intel I210 Gigabit Network Connection                                         | 25        | 3.47%   |
| Intel 82574L Gigabit Network Connection                                       | 24        | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 20        | 2.77%   |
| Intel Wi-Fi 6 AX200                                                           | 12        | 1.66%   |
| Intel I350 Gigabit Network Connection                                         | 12        | 1.66%   |
| Intel Wireless 8265 / 8275                                                    | 11        | 1.53%   |
| Intel Ethernet Controller I225-V                                              | 11        | 1.53%   |
| Intel Ethernet Connection I217-LM                                             | 11        | 1.53%   |
| Intel Wireless 7265                                                           | 10        | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                             | 9         | 1.25%   |
| Intel Wireless 7260                                                           | 9         | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 8         | 1.11%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 8         | 1.11%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 8         | 1.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 7         | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 7         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 7         | 0.97%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7         | 0.97%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 7         | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 6         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 6         | 0.83%   |
| Intel Wireless-AC 9260                                                        | 6         | 0.83%   |
| Intel Wireless 3165                                                           | 6         | 0.83%   |
| Intel Ethernet Connection (6) I219-V                                          | 6         | 0.83%   |
| Intel 82576 Gigabit Network Connection                                        | 6         | 0.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 0.69%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 5         | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                          | 5         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                         | 5         | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 5         | 0.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 5         | 0.69%   |
| Intel Centrino Advanced-N 6235                                                | 5         | 0.69%   |
| Intel 82579V Gigabit Network Connection                                       | 5         | 0.69%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 5         | 0.69%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 4         | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 4         | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 4         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 111       | 56.06%  |
| Qualcomm Atheros                | 35        | 17.68%  |
| Realtek Semiconductor           | 20        | 10.1%   |
| Broadcom                        | 12        | 6.06%   |
| TP-Link                         | 4         | 2.02%   |
| Ralink Technology               | 3         | 1.52%   |
| Edimax Technology               | 3         | 1.52%   |
| Ralink                          | 2         | 1.01%   |
| MediaTek                        | 2         | 1.01%   |
| IMC Networks                    | 2         | 1.01%   |
| Sagem                           | 1         | 0.51%   |
| Qualcomm Atheros Communications | 1         | 0.51%   |
| Dell                            | 1         | 0.51%   |
| Accton Technology               | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 12        | 6%      |
| Intel Wireless 8265 / 8275                                     | 11        | 5.5%    |
| Intel Wireless 7265                                            | 10        | 5%      |
| Intel Wireless 7260                                            | 9         | 4.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 4%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 3.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 3.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 3.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 3%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 6         | 3%      |
| Intel Wireless-AC 9260                                         | 6         | 3%      |
| Intel Wireless 3165                                            | 6         | 3%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.5%    |
| Intel Centrino Advanced-N 6235                                 | 5         | 2.5%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 4         | 2%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 2%      |
| Intel Wireless 8260                                            | 4         | 2%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 2%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 2%      |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 1.5%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 3         | 1.5%    |
| Broadcom BCM43224 802.11a/b/g/n                                | 3         | 1.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 1%      |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1%      |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1%      |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 1%      |
| Intel WiFi Link 5100                                           | 2         | 1%      |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 2         | 1%      |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 1%      |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 1%      |
| TP-Link Wireless MU-MIMO USB Adapter                           | 1         | 0.5%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 0.5%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 0.5%    |
| Sagem XG-76NA 802.11bg                                         | 1         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 229       | 51.23%  |
| Realtek Semiconductor    | 140       | 31.32%  |
| Broadcom                 | 38        | 8.5%    |
| Qualcomm Atheros         | 9         | 2.01%   |
| AMD                      | 5         | 1.12%   |
| Marvell Technology Group | 4         | 0.89%   |
| Qualcomm                 | 3         | 0.67%   |
| VIA Technologies         | 2         | 0.45%   |
| QLogic                   | 2         | 0.45%   |
| Nvidia                   | 2         | 0.45%   |
| D-Link System            | 2         | 0.45%   |
| Chelsio Communications   | 2         | 0.45%   |
| Apple                    | 2         | 0.45%   |
| Xiaomi                   | 1         | 0.22%   |
| Silicom                  | 1         | 0.22%   |
| Samsung Electronics      | 1         | 0.22%   |
| Emulex                   | 1         | 0.22%   |
| Aquantia                 | 1         | 0.22%   |
| American Megatrends      | 1         | 0.22%   |
| 3Com                     | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 129       | 25.29%  |
| Intel I211 Gigabit Network Connection                                         | 47        | 9.22%   |
| Intel I210 Gigabit Network Connection                                         | 25        | 4.9%    |
| Intel 82574L Gigabit Network Connection                                       | 24        | 4.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 20        | 3.92%   |
| Intel I350 Gigabit Network Connection                                         | 12        | 2.35%   |
| Intel Ethernet Controller I225-V                                              | 11        | 2.16%   |
| Intel Ethernet Connection I217-LM                                             | 11        | 2.16%   |
| Realtek RTL8125 2.5GbE Controller                                             | 9         | 1.76%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 8         | 1.57%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 8         | 1.57%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 1.37%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7         | 1.37%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 7         | 1.37%   |
| Intel Ethernet Connection (6) I219-V                                          | 6         | 1.18%   |
| Intel 82576 Gigabit Network Connection                                        | 6         | 1.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 0.98%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 5         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                                          | 5         | 0.98%   |
| Intel Ethernet Connection (3) I218-LM                                         | 5         | 0.98%   |
| Intel 82579V Gigabit Network Connection                                       | 5         | 0.98%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 5         | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 4         | 0.78%   |
| Intel Ethernet Controller I226-V                                              | 4         | 0.78%   |
| Intel Ethernet Connection X553 1GbE                                           | 4         | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                          | 4         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                         | 4         | 0.78%   |
| Intel 82567LM Gigabit Network Connection                                      | 4         | 0.78%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 4         | 0.78%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 4         | 0.78%   |
| Qualcomm ALCATEL RNDIS Interface                                              | 3         | 0.59%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 0.59%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3         | 0.59%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 0.59%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3         | 0.59%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 3         | 0.59%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 3         | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2         | 0.39%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 2         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 383       | 66.49%  |
| WiFi     | 182       | 31.6%   |
| Unknown  | 7         | 1.22%   |
| Modem    | 4         | 0.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 341       | 80.24%  |
| WiFi     | 84        | 19.76%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 160       | 39.9%   |
| 1     | 74        | 18.45%  |
| 4     | 65        | 16.21%  |
| 3     | 48        | 11.97%  |
| 5     | 17        | 4.24%   |
| 6     | 15        | 3.74%   |
| 8     | 7         | 1.75%   |
| 7     | 5         | 1.25%   |
| 0     | 3         | 0.75%   |
| 12    | 2         | 0.5%    |
| 14    | 1         | 0.25%   |
| 13    | 1         | 0.25%   |
| 11    | 1         | 0.25%   |
| 10    | 1         | 0.25%   |
| 9     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 330       | 78.95%  |
| Yes  | 88        | 21.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 76        | 68.47%  |
| Broadcom                        | 8         | 7.21%   |
| IMC Networks                    | 6         | 5.41%   |
| Apple                           | 5         | 4.5%    |
| Foxconn / Hon Hai               | 3         | 2.7%    |
| Cambridge Silicon Radio         | 3         | 2.7%    |
| Realtek Semiconductor           | 2         | 1.8%    |
| Hewlett-Packard                 | 2         | 1.8%    |
| Dell                            | 2         | 1.8%    |
| Qualcomm Atheros Communications | 1         | 0.9%    |
| HTC (High Tech Computer)        | 1         | 0.9%    |
| Creative Technology             | 1         | 0.9%    |
| ASUSTek Computer                | 1         | 0.9%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 29        | 26.13%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 14        | 12.61%  |
| Intel AX200 Bluetooth                                                | 10        | 9.01%   |
| Intel AX201 Bluetooth                                                | 6         | 5.41%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 5         | 4.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 4         | 3.6%    |
| Intel Wireless-AC 3168 Bluetooth                                     | 4         | 3.6%    |
| Intel AX210 Bluetooth                                                | 4         | 3.6%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                          | 4         | 3.6%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 3         | 2.7%    |
| Apple Bluetooth Host Controller                                      | 3         | 2.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 2         | 1.8%    |
| Foxconn / Hon Hai Bluetooth USB Module                               | 2         | 1.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 1.8%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 2         | 1.8%    |
| Broadcom BCM2045B (BDC-2.1)                                          | 2         | 1.8%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 1         | 0.9%    |
| Realtek Bluetooth Adapter                                            | 1         | 0.9%    |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                               | 1         | 0.9%    |
| IMC Networks Realtek Bluetooth Adapter                               | 1         | 0.9%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS                     | 1         | 0.9%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.9%    |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                            | 1         | 0.9%    |
| Dell DW375 Bluetooth Module                                          | 1         | 0.9%    |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                          | 1         | 0.9%    |
| Creative Creative Bluetooth Audio W2                                 | 1         | 0.9%    |
| Broadcom BCM43142A0 Bluetooth Module                                 | 1         | 0.9%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 1         | 0.9%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1         | 0.9%    |
| Apple Built-in iSight (no firmware loaded)                           | 1         | 0.9%    |
| Apple Bluetooth USB Host Controller                                  | 1         | 0.9%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 242       | 65.41%  |
| AMD                                          | 63        | 17.03%  |
| Nvidia                                       | 38        | 10.27%  |
| GN Netcom                                    | 4         | 1.08%   |
| C-Media Electronics                          | 3         | 0.81%   |
| Texas Instruments                            | 2         | 0.54%   |
| Logitech                                     | 2         | 0.54%   |
| Lenovo                                       | 2         | 0.54%   |
| Kingston Technology                          | 2         | 0.54%   |
| Focusrite-Novation                           | 2         | 0.54%   |
| Creative Labs                                | 2         | 0.54%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.27%   |
| VIA Technologies                             | 1         | 0.27%   |
| Sony                                         | 1         | 0.27%   |
| Micronas                                     | 1         | 0.27%   |
| iCreate Technologies                         | 1         | 0.27%   |
| Giga-Byte Technology                         | 1         | 0.27%   |
| ESS Technology                               | 1         | 0.27%   |
| DSEA A/S                                     | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 4.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 21        | 4.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 21        | 4.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 4.44%   |
| Intel 8 Series HD Audio Controller                                                                | 20        | 4.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 3.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 15        | 3.33%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 2.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 2.89%   |
| AMD FCH Azalia Controller                                                                         | 12        | 2.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 2.44%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 2.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 2.22%   |
| Intel 200 Series PCH HD Audio                                                                     | 10        | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 9         | 2%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 1.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 1.78%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 8         | 1.78%   |
| Intel Jasper Lake HD Audio                                                                        | 7         | 1.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.56%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.33%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.11%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 1.11%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.89%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.67%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.67%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 0.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 80        | 20.51%  |
| SK hynix            | 60        | 15.38%  |
| Unknown             | 42        | 10.77%  |
| Kingston            | 41        | 10.51%  |
| Crucial             | 36        | 9.23%   |
| Corsair             | 30        | 7.69%   |
| Micron Technology   | 27        | 6.92%   |
| G.Skill             | 20        | 5.13%   |
| Transcend           | 8         | 2.05%   |
| Unknown             | 8         | 2.05%   |
| Nanya Technology    | 7         | 1.79%   |
| Unknown (ABCD)      | 6         | 1.54%   |
| Elpida              | 5         | 1.28%   |
| A-DATA Technology   | 3         | 0.77%   |
| Patriot             | 2         | 0.51%   |
| Kimtigo             | 2         | 0.51%   |
| Atermiter           | 2         | 0.51%   |
| Apacer              | 2         | 0.51%   |
| V-Color             | 1         | 0.26%   |
| Unknown (0B38)      | 1         | 0.26%   |
| Teikon              | 1         | 0.26%   |
| SHARETRONIC         | 1         | 0.26%   |
| OCZ                 | 1         | 0.26%   |
| Hewlett-Packard     | 1         | 0.26%   |
| Goldenmars          | 1         | 0.26%   |
| CSX                 | 1         | 0.26%   |
| Avant               | 1         | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 8         | 1.94%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 7         | 1.7%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 6         | 1.46%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 5         | 1.21%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 4         | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 4         | 0.97%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s          | 4         | 0.97%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s         | 3         | 0.73%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s           | 3         | 0.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 3         | 0.73%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 3         | 0.73%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.73%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 3         | 0.73%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 3         | 0.73%   |
| Samsung RAM M393A4K40CB2-CTD 32GB DIMM DDR4 2667MT/s           | 3         | 0.73%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 1600MT/s            | 3         | 0.73%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 3         | 0.73%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 2         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 2         | 0.49%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 2         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 2         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 2         | 0.49%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 2         | 0.49%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s            | 2         | 0.49%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 2         | 0.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.49%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3                    | 2         | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.49%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 2         | 0.49%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 2         | 0.49%   |
| Samsung RAM M471B5773CHS-CK0 2GB DDR3 1600MT/s                 | 2         | 0.49%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 0.49%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.49%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 0.49%   |
| Samsung RAM M393B4G70DM0-YH9 32767MB DIMM DDR3 1333MT/s        | 2         | 0.49%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s            | 2         | 0.49%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s            | 2         | 0.49%   |
| Micron RAM 8HTF12864AZ-800H1 1GB DIMM DDR2 800MT/s             | 2         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 165       | 48.67%  |
| DDR4    | 131       | 38.64%  |
| DDR2    | 18        | 5.31%   |
| Unknown | 14        | 4.13%   |
| LPDDR4  | 6         | 1.77%   |
| LPDDR3  | 5         | 1.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 168       | 49.27%  |
| SODIMM       | 166       | 48.68%  |
| Unknown      | 4         | 1.17%   |
| Row Of Chips | 1         | 0.29%   |
| FB-DIMM      | 1         | 0.29%   |
| Chip         | 1         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 122       | 33.52%  |
| 4096  | 122       | 33.52%  |
| 2048  | 49        | 13.46%  |
| 16384 | 46        | 12.64%  |
| 1024  | 12        | 3.3%    |
| 32768 | 11        | 3.02%   |
| 32767 | 2         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 100       | 28.25%  |
| 1333    | 59        | 16.67%  |
| 3200    | 37        | 10.45%  |
| 2667    | 37        | 10.45%  |
| 2400    | 37        | 10.45%  |
| 2133    | 21        | 5.93%   |
| 800     | 14        | 3.95%   |
| 1334    | 10        | 2.82%   |
| 667     | 9         | 2.54%   |
| 2666    | 7         | 1.98%   |
| 1867    | 4         | 1.13%   |
| 1066    | 4         | 1.13%   |
| Unknown | 3         | 0.85%   |
| 1067    | 2         | 0.56%   |
| 533     | 2         | 0.56%   |
| 5200    | 1         | 0.28%   |
| 3000    | 1         | 0.28%   |
| 1866    | 1         | 0.28%   |
| 1400    | 1         | 0.28%   |
| 1332    | 1         | 0.28%   |
| 1200    | 1         | 0.28%   |
| 975     | 1         | 0.28%   |
| 400     | 1         | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Dymo-CoStar | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seiko Epson Printer                  | 1         | 33.33%  |
| Dymo-CoStar LabelWriter 450          | 1         | 33.33%  |
| Dymo-CoStar DYMO LabelWriter 450 DUO | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 28        | 31.82%  |
| Sunplus Innovation Technology          | 9         | 10.23%  |
| Bison Electronics                      | 9         | 10.23%  |
| Microdia                               | 7         | 7.95%   |
| Realtek Semiconductor                  | 6         | 6.82%   |
| IMC Networks                           | 5         | 5.68%   |
| Syntek                                 | 3         | 3.41%   |
| Logitech                               | 3         | 3.41%   |
| Lite-On Technology                     | 3         | 3.41%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.41%   |
| ARC International                      | 3         | 3.41%   |
| Suyin                                  | 2         | 2.27%   |
| Alcor Micro                            | 2         | 2.27%   |
| ValueHD                                | 1         | 1.14%   |
| SIMPLO Technology                      | 1         | 1.14%   |
| Quanta                                 | 1         | 1.14%   |
| Novatek Microelectronics               | 1         | 1.14%   |
| Apple                                  | 1         | 1.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 10        | 11.24%  |
| Bison Integrated Camera                             | 6         | 6.74%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 4.49%   |
| Microdia Integrated_Webcam_HD                       | 3         | 3.37%   |
| Microdia Integrated Webcam                          | 3         | 3.37%   |
| Chicony HD WebCam                                   | 3         | 3.37%   |
| ARC International Camera                            | 3         | 3.37%   |
| Syntek Integrated Camera                            | 2         | 2.25%   |
| Realtek USB Camera                                  | 2         | 2.25%   |
| Realtek Integrated_Webcam_HD                        | 2         | 2.25%   |
| Logitech Webcam C270                                | 2         | 2.25%   |
| Lite-On Integrated Camera                           | 2         | 2.25%   |
| IMC Networks EasyCamera                             | 2         | 2.25%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 2.25%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 2.25%   |
| Bison SunplusIT Integrated Camera                   | 2         | 2.25%   |
| ValueHD HD Camera                                   | 1         | 1.12%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.12%   |
| Suyin USB 2.0 Camera                                | 1         | 1.12%   |
| Suyin Laptop_Integrated_Webcam_FHD                  | 1         | 1.12%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 1.12%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.12%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.12%   |
| Sunplus Integrated HD Webcam                        | 1         | 1.12%   |
| Sunplus Asus Webcam                                 | 1         | 1.12%   |
| SIMPLO USB 2.0 Camera                               | 1         | 1.12%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.12%   |
| Realtek Integrated Webcam HD                        | 1         | 1.12%   |
| Quanta HD WebCam                                    | 1         | 1.12%   |
| Novatek HP High Definition 2MP Webcam               | 1         | 1.12%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.12%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 1.12%   |
| Lite-On Realtek DMFT RGB                            | 1         | 1.12%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.12%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.12%   |
| IMC Networks Integrated Camera                      | 1         | 1.12%   |
| Chicony UVC 1.00 device HD UVC WebCam               | 1         | 1.12%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.12%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.12%   |
| Chicony ThinkPad T490 Webcam                        | 1         | 1.12%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 28.57%  |
| Synaptics                  | 7         | 25%     |
| AuthenTec                  | 6         | 21.43%  |
| Upek                       | 2         | 7.14%   |
| Shenzhen Goodix Technology | 2         | 7.14%   |
| LighTuning Technology      | 1         | 3.57%   |
| Elan Microelectronics      | 1         | 3.57%   |
| Broadcom                   | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 17.86%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 7.14%   |
| Validity Sensors Synaptics WBDI                                              | 2         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 7.14%   |
| AuthenTec AES2810                                                            | 2         | 7.14%   |
| AuthenTec AES1660                                                            | 2         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 3.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 3.57%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 3.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 3.57%   |
| Synaptics UWP WBDI Device                                                    | 1         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 3.57%   |
| Elan Fingerprint Sensor                                                      | 1         | 3.57%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.57%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 3.57%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 3.57%   |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 168       | 40.29%  |
| 0     | 120       | 28.78%  |
| 2     | 70        | 16.79%  |
| 3     | 35        | 8.39%   |
| 4     | 17        | 4.08%   |
| 6     | 4         | 0.96%   |
| 5     | 2         | 0.48%   |
| 7     | 1         | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 239       | 52.99%  |
| Bluetooth                | 53        | 11.75%  |
| Net/wireless             | 49        | 10.86%  |
| Card reader              | 32        | 7.1%    |
| Firewire controller      | 22        | 4.88%   |
| Fingerprint reader       | 21        | 4.66%   |
| Sound                    | 9         | 2%      |
| Net/ethernet             | 8         | 1.77%   |
| Graphics card            | 6         | 1.33%   |
| Storage                  | 5         | 1.11%   |
| Storage/raid             | 3         | 0.67%   |
| Network                  | 3         | 0.67%   |
| Modem                    | 1         | 0.22%   |

