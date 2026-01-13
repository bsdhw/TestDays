BSD in Spain - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for BSD in Spain.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Spain/Desktop/README.md) and [notebooks](/Location/Spain/Notebook/README.md).

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

Total: 569

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [a8dc8ee7ac](https://bsd-hardware.info/?probe=a8dc8ee7ac) | Dec 26, 2025 |
| Dell          | Inspiron 3521               | Notebook    | [c884d6e443](https://bsd-hardware.info/?probe=c884d6e443) | Dec 25, 2025 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [ffcb3248bd](https://bsd-hardware.info/?probe=ffcb3248bd) | Dec 14, 2025 |
| Unknown       | Unknown                     | Desktop     | [201f46cb2a](https://bsd-hardware.info/?probe=201f46cb2a) | Dec 11, 2025 |
| Unknown       | Unknown                     | Desktop     | [518386ff6e](https://bsd-hardware.info/?probe=518386ff6e) | Dec 10, 2025 |
| Toshiba       | Satellite A110              | Notebook    | [2ecccdf063](https://bsd-hardware.info/?probe=2ecccdf063) | Dec 08, 2025 |
| HP            | 802E                        | Desktop     | [0cab3252b2](https://bsd-hardware.info/?probe=0cab3252b2) | Nov 26, 2025 |
| HP            | ProBook 450 G5              | Notebook    | [ed1fd5f7a2](https://bsd-hardware.info/?probe=ed1fd5f7a2) | Nov 22, 2025 |
| Unknown       | QADL02                      | Desktop     | [1db218dbb5](https://bsd-hardware.info/?probe=1db218dbb5) | Nov 22, 2025 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [25c0e04e46](https://bsd-hardware.info/?probe=25c0e04e46) | Nov 13, 2025 |
| YANYU         | R250                        | Desktop     | [e270d1b38b](https://bsd-hardware.info/?probe=e270d1b38b) | Nov 10, 2025 |
| Raspberry ... | Raspberry Pi                | Soc         | [9461950ae0](https://bsd-hardware.info/?probe=9461950ae0) | Nov 09, 2025 |
| Lenovo        | 312D                        | Mini pc     | [6beb07c823](https://bsd-hardware.info/?probe=6beb07c823) | Nov 01, 2025 |
| Dell          | 0WR7PY A01                  | Desktop     | [e65d8229da](https://bsd-hardware.info/?probe=e65d8229da) | Oct 28, 2025 |
| ASUSTek       | Pro B760M-C                 | Desktop     | [d0b1738757](https://bsd-hardware.info/?probe=d0b1738757) | Oct 26, 2025 |
| Unknown       | Unknown                     | Desktop     | [133a1afce2](https://bsd-hardware.info/?probe=133a1afce2) | Oct 26, 2025 |
| Unknown       | Unknown                     | Desktop     | [acaee3f87a](https://bsd-hardware.info/?probe=acaee3f87a) | Oct 20, 2025 |
| Unknown       | Unknown                     | Desktop     | [72223f838c](https://bsd-hardware.info/?probe=72223f838c) | Oct 14, 2025 |
| Intel         | SKYBAY                      | Desktop     | [a8fbd3ebfb](https://bsd-hardware.info/?probe=a8fbd3ebfb) | Oct 11, 2025 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [ffafedf092](https://bsd-hardware.info/?probe=ffafedf092) | Oct 11, 2025 |
| Intel         | SKYBAY                      | Desktop     | [195aad6591](https://bsd-hardware.info/?probe=195aad6591) | Oct 10, 2025 |
| HP            | 802E                        | Desktop     | [d70f2ad3d1](https://bsd-hardware.info/?probe=d70f2ad3d1) | Oct 07, 2025 |
| Toshiba       | Satellite A110              | Notebook    | [bec0a965e4](https://bsd-hardware.info/?probe=bec0a965e4) | Oct 06, 2025 |
| Toshiba       | Satellite A110              | Notebook    | [d6dad804a7](https://bsd-hardware.info/?probe=d6dad804a7) | Oct 06, 2025 |
| HP            | 802E                        | Desktop     | [e822edbe89](https://bsd-hardware.info/?probe=e822edbe89) | Oct 03, 2025 |
| Dell          | Latitude E6400              | Notebook    | [45c2c1f321](https://bsd-hardware.info/?probe=45c2c1f321) | Sep 30, 2025 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [558100159e](https://bsd-hardware.info/?probe=558100159e) | Sep 25, 2025 |
| ASUSTek       | PRIME B760-PLUS D4          | Desktop     | [ad3a399271](https://bsd-hardware.info/?probe=ad3a399271) | Sep 23, 2025 |
| YANYU         | R250                        | Desktop     | [ac56ab7486](https://bsd-hardware.info/?probe=ac56ab7486) | Sep 18, 2025 |
| Unknown       | Unknown                     | Desktop     | [1ef8a749fc](https://bsd-hardware.info/?probe=1ef8a749fc) | Sep 10, 2025 |
| Toshiba       | Satellite A110              | Notebook    | [f770f0b8d0](https://bsd-hardware.info/?probe=f770f0b8d0) | Aug 31, 2025 |
| GEEKOM        | A5                          | Desktop     | [2cce4efc81](https://bsd-hardware.info/?probe=2cce4efc81) | Aug 15, 2025 |
| Unknown       | Unknown                     | Desktop     | [c4b4e27dc3](https://bsd-hardware.info/?probe=c4b4e27dc3) | Aug 14, 2025 |
| ASRock        | Q1900M Pro3                 | Desktop     | [7a62499b68](https://bsd-hardware.info/?probe=7a62499b68) | Aug 14, 2025 |
| Unknown       | Unknown                     | Desktop     | [d5f6872be9](https://bsd-hardware.info/?probe=d5f6872be9) | Aug 08, 2025 |
| Unknown       | Unknown                     | Desktop     | [19710b244f](https://bsd-hardware.info/?probe=19710b244f) | Aug 07, 2025 |
| GEEKOM        | A5                          | Desktop     | [4ab2cf96b8](https://bsd-hardware.info/?probe=4ab2cf96b8) | Aug 06, 2025 |
| Unknown       | Unknown                     | Desktop     | [9abd3a5471](https://bsd-hardware.info/?probe=9abd3a5471) | Aug 05, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [df265f20df](https://bsd-hardware.info/?probe=df265f20df) | Aug 05, 2025 |
| PC Engines    | APU                         | Desktop     | [ba0ec07b90](https://bsd-hardware.info/?probe=ba0ec07b90) | Jul 19, 2025 |
| HP            | 83E2                        | Desktop     | [2b65ef52ff](https://bsd-hardware.info/?probe=2b65ef52ff) | Jul 16, 2025 |
| Unknown       | Unknown                     | Desktop     | [ee418a0ef5](https://bsd-hardware.info/?probe=ee418a0ef5) | Jul 08, 2025 |
| HP            | Pavilion 15                 | Notebook    | [752aebbc02](https://bsd-hardware.info/?probe=752aebbc02) | Jul 06, 2025 |
| Unknown       | Unknown                     | Desktop     | [c076228d6a](https://bsd-hardware.info/?probe=c076228d6a) | Jul 02, 2025 |
| Unknown       | Unknown                     | Desktop     | [8de02d6893](https://bsd-hardware.info/?probe=8de02d6893) | Jun 26, 2025 |
| Unknown       | Unknown                     | Desktop     | [5c811df9d5](https://bsd-hardware.info/?probe=5c811df9d5) | Jun 26, 2025 |
| Unknown       | Unknown                     | Desktop     | [211aeacdd2](https://bsd-hardware.info/?probe=211aeacdd2) | Jun 13, 2025 |
| Unknown       | Unknown                     | Desktop     | [02e6f74c8d](https://bsd-hardware.info/?probe=02e6f74c8d) | Jun 08, 2025 |
| Unknown       | Unknown                     | Desktop     | [67e35c4164](https://bsd-hardware.info/?probe=67e35c4164) | Jun 07, 2025 |
| Unknown       | Unknown                     | Desktop     | [d6cc6c7ecb](https://bsd-hardware.info/?probe=d6cc6c7ecb) | May 28, 2025 |
| Unknown       | Unknown                     | Desktop     | [3a0bbc4a93](https://bsd-hardware.info/?probe=3a0bbc4a93) | May 28, 2025 |
| MSI           | Modern 15 F13MG             | Notebook    | [1e4f28f01d](https://bsd-hardware.info/?probe=1e4f28f01d) | May 28, 2025 |
| Unknown       | Unknown                     | Desktop     | [3a3a258ec1](https://bsd-hardware.info/?probe=3a3a258ec1) | May 27, 2025 |
| Unknown       | Unknown                     | Notebook    | [c9382cf84d](https://bsd-hardware.info/?probe=c9382cf84d) | May 25, 2025 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [7720ff6548](https://bsd-hardware.info/?probe=7720ff6548) | May 22, 2025 |
| Dell          | 0WR7PY A01                  | Desktop     | [ae030eaa8b](https://bsd-hardware.info/?probe=ae030eaa8b) | May 19, 2025 |
| HP            | 213D A01                    | Desktop     | [551c006392](https://bsd-hardware.info/?probe=551c006392) | May 12, 2025 |
| HP            | 8103 A01                    | Mini pc     | [3054122bb6](https://bsd-hardware.info/?probe=3054122bb6) | May 10, 2025 |
| Unknown       | Unknown                     | Desktop     | [663d045df3](https://bsd-hardware.info/?probe=663d045df3) | May 10, 2025 |
| BESSTAR Te... | GB7                         | Mini pc     | [c32e71a2fe](https://bsd-hardware.info/?probe=c32e71a2fe) | May 06, 2025 |
| Unknown       | Unknown                     | Desktop     | [de2f486d92](https://bsd-hardware.info/?probe=de2f486d92) | May 02, 2025 |
| Unknown       | Unknown                     | Desktop     | [1fd9b729f7](https://bsd-hardware.info/?probe=1fd9b729f7) | Apr 24, 2025 |
| Unknown       | Unknown                     | Desktop     | [46cc0b8a8f](https://bsd-hardware.info/?probe=46cc0b8a8f) | Apr 20, 2025 |
| Sophos        | XG                          | Firewall    | [f05bbd7792](https://bsd-hardware.info/?probe=f05bbd7792) | Apr 20, 2025 |
| Dell          | 01TKCC A00                  | Desktop     | [b29be898f7](https://bsd-hardware.info/?probe=b29be898f7) | Apr 19, 2025 |
| Dell          | 01TKCC A00                  | Desktop     | [2ada39d778](https://bsd-hardware.info/?probe=2ada39d778) | Apr 19, 2025 |
| Unknown       | QADL02                      | Desktop     | [401466415d](https://bsd-hardware.info/?probe=401466415d) | Apr 15, 2025 |
| Unknown       | Unknown                     | Desktop     | [4d91b55035](https://bsd-hardware.info/?probe=4d91b55035) | Apr 13, 2025 |
| Unknown       | Unknown                     | Desktop     | [18adf7f84a](https://bsd-hardware.info/?probe=18adf7f84a) | Apr 11, 2025 |
| Unknown       | Unknown                     | Desktop     | [874440b36d](https://bsd-hardware.info/?probe=874440b36d) | Apr 02, 2025 |
| Gigabyte      | MZBSWAP-00                  | Desktop     | [215c78bf96](https://bsd-hardware.info/?probe=215c78bf96) | Mar 20, 2025 |
| MSI           | A320M-A PRO MAX             | Desktop     | [e66444911a](https://bsd-hardware.info/?probe=e66444911a) | Mar 14, 2025 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [e0f8f84272](https://bsd-hardware.info/?probe=e0f8f84272) | Mar 14, 2025 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [a2a18ebb7f](https://bsd-hardware.info/?probe=a2a18ebb7f) | Mar 11, 2025 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b41215b549](https://bsd-hardware.info/?probe=b41215b549) | Mar 11, 2025 |
| Unknown       | Unknown                     | Desktop     | [8b52cc463d](https://bsd-hardware.info/?probe=8b52cc463d) | Mar 10, 2025 |
| HP            | 1998                        | Desktop     | [7a5a4bfcd9](https://bsd-hardware.info/?probe=7a5a4bfcd9) | Mar 10, 2025 |
| Dell          | 0VNP2H A00                  | Desktop     | [af1c8b5431](https://bsd-hardware.info/?probe=af1c8b5431) | Mar 07, 2025 |
| Dell          | 0VNP2H A00                  | Desktop     | [3f99cc7239](https://bsd-hardware.info/?probe=3f99cc7239) | Mar 07, 2025 |
| Unknown       | Unknown                     | Desktop     | [3b9132406b](https://bsd-hardware.info/?probe=3b9132406b) | Mar 02, 2025 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [ef4e279755](https://bsd-hardware.info/?probe=ef4e279755) | Mar 02, 2025 |
| Unknown       | Unknown                     | Desktop     | [2e2f74e0f0](https://bsd-hardware.info/?probe=2e2f74e0f0) | Feb 27, 2025 |
| AZW           | EQ                          | Desktop     | [987f788d96](https://bsd-hardware.info/?probe=987f788d96) | Feb 27, 2025 |
| Dell          | 042P49 A00                  | Desktop     | [c0882d78d1](https://bsd-hardware.info/?probe=c0882d78d1) | Feb 26, 2025 |
| Dell          | 0WR7PY A01                  | Desktop     | [544cb19310](https://bsd-hardware.info/?probe=544cb19310) | Feb 25, 2025 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [e72d5f45d2](https://bsd-hardware.info/?probe=e72d5f45d2) | Feb 24, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [c3b7a8522a](https://bsd-hardware.info/?probe=c3b7a8522a) | Feb 23, 2025 |
| HP            | ProLiant DL380 G6           | Server      | [1deb3da3b4](https://bsd-hardware.info/?probe=1deb3da3b4) | Feb 17, 2025 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [63f8afbf57](https://bsd-hardware.info/?probe=63f8afbf57) | Feb 16, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [12815485b6](https://bsd-hardware.info/?probe=12815485b6) | Feb 15, 2025 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [4c711cf418](https://bsd-hardware.info/?probe=4c711cf418) | Feb 06, 2025 |
| Unknown       | Unknown                     | Desktop     | [39fdc8bf2f](https://bsd-hardware.info/?probe=39fdc8bf2f) | Feb 05, 2025 |
| HP            | 3398                        | Desktop     | [fd84b616a8](https://bsd-hardware.info/?probe=fd84b616a8) | Feb 04, 2025 |
| Intel         | SKYBAY                      | Desktop     | [396c794397](https://bsd-hardware.info/?probe=396c794397) | Feb 03, 2025 |
| Intel         | SKYBAY                      | Desktop     | [6ab5b666df](https://bsd-hardware.info/?probe=6ab5b666df) | Feb 03, 2025 |
| Unknown       | Unknown                     | Desktop     | [f3e4fd9f73](https://bsd-hardware.info/?probe=f3e4fd9f73) | Feb 02, 2025 |
| Acer          | TravelMate B117-M           | Notebook    | [dba8ee6ee0](https://bsd-hardware.info/?probe=dba8ee6ee0) | Jan 29, 2025 |
| Acer          | FIH57                       | Desktop     | [a6f2511109](https://bsd-hardware.info/?probe=a6f2511109) | Jan 29, 2025 |
| HP            | 8597                        | Desktop     | [6849076ecc](https://bsd-hardware.info/?probe=6849076ecc) | Jan 19, 2025 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [89ce4b4a9f](https://bsd-hardware.info/?probe=89ce4b4a9f) | Jan 06, 2025 |
| MSI           | MS-B1711                    | Desktop     | [98df812bc4](https://bsd-hardware.info/?probe=98df812bc4) | Jan 03, 2025 |
| MSI           | MS-B1711                    | Desktop     | [c58187f624](https://bsd-hardware.info/?probe=c58187f624) | Jan 03, 2025 |
| Dell          | Latitude 7390               | Notebook    | [12d707eac2](https://bsd-hardware.info/?probe=12d707eac2) | Dec 31, 2024 |
| Intel         | CM8I7CB8N K53740-202        | Mini pc     | [5eb4da6e62](https://bsd-hardware.info/?probe=5eb4da6e62) | Dec 30, 2024 |
| Dell          | Precision 5510              | Notebook    | [ebf00fc632](https://bsd-hardware.info/?probe=ebf00fc632) | Dec 24, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [6eebafd5ad](https://bsd-hardware.info/?probe=6eebafd5ad) | Dec 24, 2024 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [32312b45f8](https://bsd-hardware.info/?probe=32312b45f8) | Dec 21, 2024 |
| HPE           | ProLiant MicroServer Gen... | Server      | [a79ab43d5b](https://bsd-hardware.info/?probe=a79ab43d5b) | Dec 18, 2024 |
| HPE           | ProLiant MicroServer Gen... | Server      | [eba843b9d2](https://bsd-hardware.info/?probe=eba843b9d2) | Dec 18, 2024 |
| Intel         | J1900                       | Desktop     | [1eabaeb91b](https://bsd-hardware.info/?probe=1eabaeb91b) | Dec 16, 2024 |
| Dell          | 0WR7PY A01                  | Desktop     | [cac8fa73da](https://bsd-hardware.info/?probe=cac8fa73da) | Dec 15, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [9f9235fcd6](https://bsd-hardware.info/?probe=9f9235fcd6) | Dec 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [23b03d29a7](https://bsd-hardware.info/?probe=23b03d29a7) | Dec 06, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [5f8f2f10e2](https://bsd-hardware.info/?probe=5f8f2f10e2) | Dec 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [5077b94887](https://bsd-hardware.info/?probe=5077b94887) | Dec 06, 2024 |
| Dell          | Precision 5510              | Notebook    | [928a571c76](https://bsd-hardware.info/?probe=928a571c76) | Dec 03, 2024 |
| HP            | ProLiant DL380 G6           | Server      | [8ac50a3d1f](https://bsd-hardware.info/?probe=8ac50a3d1f) | Dec 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [d5087399ae](https://bsd-hardware.info/?probe=d5087399ae) | Dec 02, 2024 |
| Intel         | CM8I7CB8N K53740-202        | Mini pc     | [d29fa868ad](https://bsd-hardware.info/?probe=d29fa868ad) | Nov 30, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [7a03bbeb04](https://bsd-hardware.info/?probe=7a03bbeb04) | Nov 25, 2024 |
| Unknown       | QDNV01                      | Desktop     | [b61894118e](https://bsd-hardware.info/?probe=b61894118e) | Nov 25, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [36ab98d9df](https://bsd-hardware.info/?probe=36ab98d9df) | Nov 25, 2024 |
| Acer          | Nitro AN515-46              | Notebook    | [d66960aa84](https://bsd-hardware.info/?probe=d66960aa84) | Nov 24, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [88032dcf96](https://bsd-hardware.info/?probe=88032dcf96) | Nov 21, 2024 |
| Unknown       | QDNV01                      | Desktop     | [e70e28cd40](https://bsd-hardware.info/?probe=e70e28cd40) | Nov 21, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [4fd991795f](https://bsd-hardware.info/?probe=4fd991795f) | Nov 20, 2024 |
| HP            | 8103 A01                    | Mini pc     | [63c5852e76](https://bsd-hardware.info/?probe=63c5852e76) | Nov 10, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [35add40d90](https://bsd-hardware.info/?probe=35add40d90) | Nov 10, 2024 |
| HP            | Mini 210-1000               | Notebook    | [2e6b2f7727](https://bsd-hardware.info/?probe=2e6b2f7727) | Nov 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [401a8352cd](https://bsd-hardware.info/?probe=401a8352cd) | Nov 05, 2024 |
| HP            | 8597                        | Desktop     | [a20615c5a0](https://bsd-hardware.info/?probe=a20615c5a0) | Oct 29, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [76c5dea6bb](https://bsd-hardware.info/?probe=76c5dea6bb) | Oct 27, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [6c77bc229e](https://bsd-hardware.info/?probe=6c77bc229e) | Oct 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [7d49a8dfcd](https://bsd-hardware.info/?probe=7d49a8dfcd) | Oct 20, 2024 |
| HP            | ProLiant BL460c G7          | Server      | [efbbeb4731](https://bsd-hardware.info/?probe=efbbeb4731) | Oct 18, 2024 |
| HP            | Unknown                     | Notebook    | [254f5a847c](https://bsd-hardware.info/?probe=254f5a847c) | Oct 17, 2024 |
| Intel         | SKYBAY                      | Desktop     | [9847be081f](https://bsd-hardware.info/?probe=9847be081f) | Oct 16, 2024 |
| Acer          | Aspire V5-531               | Notebook    | [31a71a6cb4](https://bsd-hardware.info/?probe=31a71a6cb4) | Oct 15, 2024 |
| Shenzhen M... | F7BFD                       | Desktop     | [def723c09a](https://bsd-hardware.info/?probe=def723c09a) | Oct 15, 2024 |
| HP            | Compaq Presario CQ50        | Desktop     | [462666f013](https://bsd-hardware.info/?probe=462666f013) | Oct 13, 2024 |
| ECS           | APLD-MINI                   | Desktop     | [47d8c66ac9](https://bsd-hardware.info/?probe=47d8c66ac9) | Oct 07, 2024 |
| Medion        | S15449                      | Notebook    | [b7a0fc4f21](https://bsd-hardware.info/?probe=b7a0fc4f21) | Oct 06, 2024 |
| PC Engines    | APU                         | Desktop     | [58bd860024](https://bsd-hardware.info/?probe=58bd860024) | Oct 05, 2024 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [a103b74d47](https://bsd-hardware.info/?probe=a103b74d47) | Sep 30, 2024 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [538ac0af8c](https://bsd-hardware.info/?probe=538ac0af8c) | Sep 30, 2024 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [dcfdda02ff](https://bsd-hardware.info/?probe=dcfdda02ff) | Sep 30, 2024 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [800f9bb0b7](https://bsd-hardware.info/?probe=800f9bb0b7) | Sep 29, 2024 |
| Dell          | G3 3579                     | Notebook    | [1725db4da9](https://bsd-hardware.info/?probe=1725db4da9) | Sep 27, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [9ea21fa783](https://bsd-hardware.info/?probe=9ea21fa783) | Sep 26, 2024 |
| MSI           | Prestige 15 A10SC           | Notebook    | [6cdde2a1ab](https://bsd-hardware.info/?probe=6cdde2a1ab) | Sep 25, 2024 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [d24d0ef32b](https://bsd-hardware.info/?probe=d24d0ef32b) | Sep 24, 2024 |
| ASUSTek       | F3E                         | Notebook    | [cbed34c50d](https://bsd-hardware.info/?probe=cbed34c50d) | Sep 17, 2024 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [41818d9f0a](https://bsd-hardware.info/?probe=41818d9f0a) | Sep 15, 2024 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [8f49a75dc6](https://bsd-hardware.info/?probe=8f49a75dc6) | Sep 07, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [42acfbe729](https://bsd-hardware.info/?probe=42acfbe729) | Sep 07, 2024 |
| Intel         | NUC7JYB M37329-500          | Mini pc     | [0c5980da40](https://bsd-hardware.info/?probe=0c5980da40) | Aug 23, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [260fa51e5f](https://bsd-hardware.info/?probe=260fa51e5f) | Aug 22, 2024 |
| Sophos        | XG                          | Firewall    | [c16d9b16bf](https://bsd-hardware.info/?probe=c16d9b16bf) | Aug 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [424a038d10](https://bsd-hardware.info/?probe=424a038d10) | Aug 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ffdc8ec717](https://bsd-hardware.info/?probe=ffdc8ec717) | Aug 15, 2024 |
| Sophos        | XG                          | Firewall    | [5469029429](https://bsd-hardware.info/?probe=5469029429) | Jul 25, 2024 |
| Dell EMC      | EDGE680-CPU A00             | Desktop     | [4934b78db6](https://bsd-hardware.info/?probe=4934b78db6) | Jul 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [2e77b6eb96](https://bsd-hardware.info/?probe=2e77b6eb96) | Jul 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [0a7faa3d8b](https://bsd-hardware.info/?probe=0a7faa3d8b) | Jul 21, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f2ae8a59aa](https://bsd-hardware.info/?probe=f2ae8a59aa) | Jul 21, 2024 |
| HP            | Pavilion g6                 | Notebook    | [19ddfa696d](https://bsd-hardware.info/?probe=19ddfa696d) | Jul 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2d169fbf2d](https://bsd-hardware.info/?probe=2d169fbf2d) | Jul 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [898dbbc136](https://bsd-hardware.info/?probe=898dbbc136) | Jul 18, 2024 |
| HP            | Compaq Presario CQ71        | Notebook    | [88a0868c03](https://bsd-hardware.info/?probe=88a0868c03) | Jul 18, 2024 |
| HP            | Compaq Presario CQ71        | Notebook    | [45d3874955](https://bsd-hardware.info/?probe=45d3874955) | Jul 13, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [7928a68cca](https://bsd-hardware.info/?probe=7928a68cca) | Jul 11, 2024 |
| OEM           | NU93 Series                 | Desktop     | [8eaae8a84d](https://bsd-hardware.info/?probe=8eaae8a84d) | Jun 24, 2024 |
| HP            | Laptop 14-cf1xxx            | Notebook    | [a0118881e6](https://bsd-hardware.info/?probe=a0118881e6) | Jun 20, 2024 |
| HP            | Laptop 14-cf1xxx            | Notebook    | [70254105eb](https://bsd-hardware.info/?probe=70254105eb) | Jun 19, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [65d6791029](https://bsd-hardware.info/?probe=65d6791029) | Jun 19, 2024 |
| Lenovo        | 312D SDK0J40700 WIN 3258... | Mini pc     | [270522ff15](https://bsd-hardware.info/?probe=270522ff15) | Jun 13, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [5c5138d19f](https://bsd-hardware.info/?probe=5c5138d19f) | Jun 08, 2024 |
| Lenovo        | ThinkPad T530 2429GL9       | Notebook    | [acc2537d8d](https://bsd-hardware.info/?probe=acc2537d8d) | Jun 08, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [ab9b2e3147](https://bsd-hardware.info/?probe=ab9b2e3147) | Jun 07, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [9b896d73b3](https://bsd-hardware.info/?probe=9b896d73b3) | Jun 07, 2024 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [80440d6327](https://bsd-hardware.info/?probe=80440d6327) | Jun 06, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [b11c396037](https://bsd-hardware.info/?probe=b11c396037) | Jun 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [06a1266a2e](https://bsd-hardware.info/?probe=06a1266a2e) | May 30, 2024 |
| HP            | Compaq Presario CQ71        | Notebook    | [ddf13477d5](https://bsd-hardware.info/?probe=ddf13477d5) | May 24, 2024 |
| HP            | Compaq Presario CQ71        | Notebook    | [7646daa3c0](https://bsd-hardware.info/?probe=7646daa3c0) | May 19, 2024 |
| Alienware     | m16 R1                      | Notebook    | [4f607db6c3](https://bsd-hardware.info/?probe=4f607db6c3) | May 18, 2024 |
| Sony          | VPCSB3Q9E                   | Notebook    | [103114e640](https://bsd-hardware.info/?probe=103114e640) | May 14, 2024 |
| Sony          | VPCSB3Q9E                   | Notebook    | [081979c837](https://bsd-hardware.info/?probe=081979c837) | May 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [30cc9d07af](https://bsd-hardware.info/?probe=30cc9d07af) | May 07, 2024 |
| MSI           | MS-7097                     | Desktop     | [df5c7407fd](https://bsd-hardware.info/?probe=df5c7407fd) | May 06, 2024 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [6da31bada9](https://bsd-hardware.info/?probe=6da31bada9) | Apr 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [2caa0fe8f7](https://bsd-hardware.info/?probe=2caa0fe8f7) | Apr 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [1d373fbfcd](https://bsd-hardware.info/?probe=1d373fbfcd) | Apr 26, 2024 |
| AZW           | EQ                          | Desktop     | [9225d89862](https://bsd-hardware.info/?probe=9225d89862) | Apr 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [242348310b](https://bsd-hardware.info/?probe=242348310b) | Apr 22, 2024 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [1bc36f8af1](https://bsd-hardware.info/?probe=1bc36f8af1) | Apr 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [d231a9531b](https://bsd-hardware.info/?probe=d231a9531b) | Apr 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a818576415](https://bsd-hardware.info/?probe=a818576415) | Apr 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d8288ba73a](https://bsd-hardware.info/?probe=d8288ba73a) | Apr 09, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [9057a0522b](https://bsd-hardware.info/?probe=9057a0522b) | Apr 08, 2024 |
| Gigabyte      | G431-MM0-OT                 | Desktop     | [16c58f7ccb](https://bsd-hardware.info/?probe=16c58f7ccb) | Apr 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a26013b913](https://bsd-hardware.info/?probe=a26013b913) | Apr 05, 2024 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3f85beaa54](https://bsd-hardware.info/?probe=3f85beaa54) | Apr 05, 2024 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [b2bbe7eb8d](https://bsd-hardware.info/?probe=b2bbe7eb8d) | Apr 04, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [0ae72ec0ff](https://bsd-hardware.info/?probe=0ae72ec0ff) | Mar 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [0687b8c8e1](https://bsd-hardware.info/?probe=0687b8c8e1) | Mar 29, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [0d486d6705](https://bsd-hardware.info/?probe=0d486d6705) | Mar 26, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [bad44928d7](https://bsd-hardware.info/?probe=bad44928d7) | Mar 25, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [313ab74587](https://bsd-hardware.info/?probe=313ab74587) | Mar 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [25a92fc367](https://bsd-hardware.info/?probe=25a92fc367) | Mar 22, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3a0ef703ef](https://bsd-hardware.info/?probe=3a0ef703ef) | Mar 10, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [88b774a83d](https://bsd-hardware.info/?probe=88b774a83d) | Mar 10, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [9b40b121ec](https://bsd-hardware.info/?probe=9b40b121ec) | Mar 10, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [7cc4588e07](https://bsd-hardware.info/?probe=7cc4588e07) | Mar 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [e35907b66f](https://bsd-hardware.info/?probe=e35907b66f) | Mar 04, 2024 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [05b6d7a915](https://bsd-hardware.info/?probe=05b6d7a915) | Feb 29, 2024 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [0275a7e6b3](https://bsd-hardware.info/?probe=0275a7e6b3) | Feb 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [d3ed7d1552](https://bsd-hardware.info/?probe=d3ed7d1552) | Feb 24, 2024 |
| HPE           | ProLiant MicroServer Gen... | Server      | [0896863043](https://bsd-hardware.info/?probe=0896863043) | Feb 18, 2024 |
| Intel         | CM8I7CB8N K53740-202        | Mini pc     | [4e34435ef4](https://bsd-hardware.info/?probe=4e34435ef4) | Feb 17, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [e9d1b23169](https://bsd-hardware.info/?probe=e9d1b23169) | Feb 16, 2024 |
| ECS           | APLD-MINI                   | Desktop     | [d0d3c5d2c3](https://bsd-hardware.info/?probe=d0d3c5d2c3) | Feb 16, 2024 |
| Unknown       | ITX-M41V                    | Desktop     | [957fb292ad](https://bsd-hardware.info/?probe=957fb292ad) | Feb 06, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [fa94c9a549](https://bsd-hardware.info/?probe=fa94c9a549) | Feb 04, 2024 |
| Unknown       | ITX-M41V                    | Desktop     | [3ab7929f1b](https://bsd-hardware.info/?probe=3ab7929f1b) | Feb 02, 2024 |
| YANYU         | R250                        | Desktop     | [93dceedd1f](https://bsd-hardware.info/?probe=93dceedd1f) | Feb 01, 2024 |
| YANYU         | R250                        | Desktop     | [76a55db1e1](https://bsd-hardware.info/?probe=76a55db1e1) | Jan 31, 2024 |
| YANYU         | R250                        | Desktop     | [f6e4c67d9a](https://bsd-hardware.info/?probe=f6e4c67d9a) | Jan 26, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [f0db40d2f4](https://bsd-hardware.info/?probe=f0db40d2f4) | Jan 24, 2024 |
| Acer          | TravelMate B115-M           | Notebook    | [d7a78aa2cf](https://bsd-hardware.info/?probe=d7a78aa2cf) | Jan 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [2f9d003e12](https://bsd-hardware.info/?probe=2f9d003e12) | Jan 21, 2024 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [ec9b6a27b9](https://bsd-hardware.info/?probe=ec9b6a27b9) | Jan 18, 2024 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [bece75e284](https://bsd-hardware.info/?probe=bece75e284) | Jan 14, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [b56a8b041a](https://bsd-hardware.info/?probe=b56a8b041a) | Jan 14, 2024 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [40b8a056f7](https://bsd-hardware.info/?probe=40b8a056f7) | Jan 07, 2024 |
| Lenovo        | ThinkPad E495 20NE000BSP    | Notebook    | [9ed586661c](https://bsd-hardware.info/?probe=9ed586661c) | Jan 03, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [766493f0dd](https://bsd-hardware.info/?probe=766493f0dd) | Jan 03, 2024 |
| AMI           | Intel                       | Notebook    | [df557e3915](https://bsd-hardware.info/?probe=df557e3915) | Dec 25, 2023 |
| Dell          | Precision 5510              | Notebook    | [4bad5ad995](https://bsd-hardware.info/?probe=4bad5ad995) | Dec 23, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [4ccf9a2566](https://bsd-hardware.info/?probe=4ccf9a2566) | Dec 21, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [1eb8cc9d76](https://bsd-hardware.info/?probe=1eb8cc9d76) | Dec 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7a5e6024cd](https://bsd-hardware.info/?probe=7a5e6024cd) | Dec 15, 2023 |
| Toshiba       | Portable PC                 | Notebook    | [bee6ea8f18](https://bsd-hardware.info/?probe=bee6ea8f18) | Dec 15, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [357a808604](https://bsd-hardware.info/?probe=357a808604) | Dec 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [9a842bf3c8](https://bsd-hardware.info/?probe=9a842bf3c8) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [ef2a5b9804](https://bsd-hardware.info/?probe=ef2a5b9804) | Dec 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [d5da0ab59d](https://bsd-hardware.info/?probe=d5da0ab59d) | Dec 01, 2023 |
| Dell          | Precision 5510              | Notebook    | [3a7b2ae214](https://bsd-hardware.info/?probe=3a7b2ae214) | Nov 28, 2023 |
| Intel         | CM8I7CB8N K53740-202        | Mini pc     | [481571734a](https://bsd-hardware.info/?probe=481571734a) | Nov 25, 2023 |
| YANYU         | R250                        | Desktop     | [74ee81493f](https://bsd-hardware.info/?probe=74ee81493f) | Nov 20, 2023 |
| MSI           | Z170-A PRO                  | Desktop     | [ab9a7eb894](https://bsd-hardware.info/?probe=ab9a7eb894) | Nov 08, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [42b9e61011](https://bsd-hardware.info/?probe=42b9e61011) | Nov 08, 2023 |
| Gigabyte      | MZBSWAP-00                  | Desktop     | [a01a7d9576](https://bsd-hardware.info/?probe=a01a7d9576) | Nov 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [790368b718](https://bsd-hardware.info/?probe=790368b718) | Nov 03, 2023 |
| Gigabyte      | MZBSWAP-00                  | Desktop     | [d52347dd3d](https://bsd-hardware.info/?probe=d52347dd3d) | Nov 02, 2023 |
| ASUSTek       | MINIPC PN53-G               | Desktop     | [57d8823b4b](https://bsd-hardware.info/?probe=57d8823b4b) | Oct 28, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a40b6fde47](https://bsd-hardware.info/?probe=a40b6fde47) | Oct 22, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [b08dc9fc91](https://bsd-hardware.info/?probe=b08dc9fc91) | Oct 16, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [f3036a27e5](https://bsd-hardware.info/?probe=f3036a27e5) | Oct 13, 2023 |
| ECS           | APLD-MINI                   | Desktop     | [d063eeb7d5](https://bsd-hardware.info/?probe=d063eeb7d5) | Oct 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [1aa25f04a8](https://bsd-hardware.info/?probe=1aa25f04a8) | Oct 07, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [0f92b89ffb](https://bsd-hardware.info/?probe=0f92b89ffb) | Sep 09, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [ecfa93eb95](https://bsd-hardware.info/?probe=ecfa93eb95) | Sep 02, 2023 |
| HP            | Pavilion dv3500             | Notebook    | [0c3f84b285](https://bsd-hardware.info/?probe=0c3f84b285) | Aug 29, 2023 |
| Intel         | SKYBAY                      | Desktop     | [9d49471591](https://bsd-hardware.info/?probe=9d49471591) | Aug 29, 2023 |
| YANYU         | R250                        | Desktop     | [69dbe1a014](https://bsd-hardware.info/?probe=69dbe1a014) | Aug 24, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [301a7c7b63](https://bsd-hardware.info/?probe=301a7c7b63) | Aug 19, 2023 |
| YANYU         | R250                        | Desktop     | [95a37ee143](https://bsd-hardware.info/?probe=95a37ee143) | Aug 06, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6bd995374a](https://bsd-hardware.info/?probe=6bd995374a) | Jul 30, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d1a2b99edc](https://bsd-hardware.info/?probe=d1a2b99edc) | Jul 28, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [38255b17fe](https://bsd-hardware.info/?probe=38255b17fe) | Jul 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [61f0b06d5f](https://bsd-hardware.info/?probe=61f0b06d5f) | Jul 16, 2023 |
| Lenovo        | ThinkPad T470s 20HGS3AX0... | Notebook    | [785b9af1f4](https://bsd-hardware.info/?probe=785b9af1f4) | Jul 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [b44e00cdf3](https://bsd-hardware.info/?probe=b44e00cdf3) | Jun 25, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [dc0d876d7b](https://bsd-hardware.info/?probe=dc0d876d7b) | Jun 24, 2023 |
| ASUSTek       | P5K PRO                     | Desktop     | [f0b283fdaf](https://bsd-hardware.info/?probe=f0b283fdaf) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | Notebook    | [b532f1ce9c](https://bsd-hardware.info/?probe=b532f1ce9c) | Jun 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [55a858846e](https://bsd-hardware.info/?probe=55a858846e) | Jun 11, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [83e8a9252f](https://bsd-hardware.info/?probe=83e8a9252f) | Jun 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [9f18b1b304](https://bsd-hardware.info/?probe=9f18b1b304) | Jun 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [85c18dbbb5](https://bsd-hardware.info/?probe=85c18dbbb5) | Jun 06, 2023 |
| Lenovo        | ThinkPad E495 20NE000BSP    | Notebook    | [0e02b323ee](https://bsd-hardware.info/?probe=0e02b323ee) | Jun 01, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [4c8047dca3](https://bsd-hardware.info/?probe=4c8047dca3) | May 19, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [c61a0b39fa](https://bsd-hardware.info/?probe=c61a0b39fa) | May 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [678ab85729](https://bsd-hardware.info/?probe=678ab85729) | May 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [d574fd446b](https://bsd-hardware.info/?probe=d574fd446b) | May 08, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [f899593f61](https://bsd-hardware.info/?probe=f899593f61) | May 01, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Notebook    | [afd28a7425](https://bsd-hardware.info/?probe=afd28a7425) | Apr 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [21b338db1b](https://bsd-hardware.info/?probe=21b338db1b) | Apr 30, 2023 |
| Lenovo        | ThinkPad X270 20HMS06Q1D    | Notebook    | [2df7c991f0](https://bsd-hardware.info/?probe=2df7c991f0) | Apr 23, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Notebook    | [c4b2619dda](https://bsd-hardware.info/?probe=c4b2619dda) | Apr 20, 2023 |
| Dell          | Precision 5510              | Notebook    | [7028fde527](https://bsd-hardware.info/?probe=7028fde527) | Apr 20, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [b7ec959c9f](https://bsd-hardware.info/?probe=b7ec959c9f) | Apr 13, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [64b66f1fed](https://bsd-hardware.info/?probe=64b66f1fed) | Apr 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9ee2a1ee72](https://bsd-hardware.info/?probe=9ee2a1ee72) | Apr 11, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [0747d0a699](https://bsd-hardware.info/?probe=0747d0a699) | Apr 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [e3efaa8d57](https://bsd-hardware.info/?probe=e3efaa8d57) | Apr 09, 2023 |
| Chuwi         | Unknown                     | Notebook    | [5e687fcc83](https://bsd-hardware.info/?probe=5e687fcc83) | Apr 01, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [ca6badc637](https://bsd-hardware.info/?probe=ca6badc637) | Mar 30, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [4f4f6e06d7](https://bsd-hardware.info/?probe=4f4f6e06d7) | Mar 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [2a50573c9f](https://bsd-hardware.info/?probe=2a50573c9f) | Mar 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [88455ed9e7](https://bsd-hardware.info/?probe=88455ed9e7) | Mar 18, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [eb6b70b310](https://bsd-hardware.info/?probe=eb6b70b310) | Mar 16, 2023 |
| HP            | 3398                        | Desktop     | [b14de43688](https://bsd-hardware.info/?probe=b14de43688) | Mar 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cb6b586564](https://bsd-hardware.info/?probe=cb6b586564) | Mar 14, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [34c4bab715](https://bsd-hardware.info/?probe=34c4bab715) | Mar 14, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [b4893ae18f](https://bsd-hardware.info/?probe=b4893ae18f) | Mar 14, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [b337baf50e](https://bsd-hardware.info/?probe=b337baf50e) | Mar 13, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [0eeb0661dd](https://bsd-hardware.info/?probe=0eeb0661dd) | Mar 12, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [b2d29a5bbc](https://bsd-hardware.info/?probe=b2d29a5bbc) | Mar 12, 2023 |
| HP            | 8768 A                      | Desktop     | [5ab1dadbab](https://bsd-hardware.info/?probe=5ab1dadbab) | Mar 12, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [57f357784c](https://bsd-hardware.info/?probe=57f357784c) | Mar 09, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [b6c9cc9c20](https://bsd-hardware.info/?probe=b6c9cc9c20) | Mar 08, 2023 |
| ASUSTek       | 1201N                       | Notebook    | [5dc595eb79](https://bsd-hardware.info/?probe=5dc595eb79) | Mar 05, 2023 |
| ASUSTek       | 1201N                       | Notebook    | [daa787f637](https://bsd-hardware.info/?probe=daa787f637) | Mar 05, 2023 |
| HP            | EliteBook 2730p             | Notebook    | [3c404c9d20](https://bsd-hardware.info/?probe=3c404c9d20) | Mar 05, 2023 |
| Sony          | SVE1511C5E                  | Notebook    | [0e972db389](https://bsd-hardware.info/?probe=0e972db389) | Mar 02, 2023 |
| Sony          | SVE1511C5E                  | Notebook    | [6aa87871c2](https://bsd-hardware.info/?probe=6aa87871c2) | Mar 01, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [06e5309c55](https://bsd-hardware.info/?probe=06e5309c55) | Feb 20, 2023 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [c34d5e6357](https://bsd-hardware.info/?probe=c34d5e6357) | Feb 17, 2023 |
| Fujitsu       | D3229-A1 S26361-D3229-A1... | Server      | [d05d07ca61](https://bsd-hardware.info/?probe=d05d07ca61) | Feb 16, 2023 |
| YANYU         | R250                        | Desktop     | [24ebc43209](https://bsd-hardware.info/?probe=24ebc43209) | Feb 12, 2023 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [6cd6b15a60](https://bsd-hardware.info/?probe=6cd6b15a60) | Feb 12, 2023 |
| Fujitsu       | D3229-A1 S26361-D3229-A1... | Server      | [83f12ac6c1](https://bsd-hardware.info/?probe=83f12ac6c1) | Feb 12, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [81827ccbca](https://bsd-hardware.info/?probe=81827ccbca) | Feb 10, 2023 |
| ASUSTek       | 1201N                       | Notebook    | [3f44d6ed3f](https://bsd-hardware.info/?probe=3f44d6ed3f) | Feb 08, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [85628154a2](https://bsd-hardware.info/?probe=85628154a2) | Feb 05, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7c56590eaa](https://bsd-hardware.info/?probe=7c56590eaa) | Feb 03, 2023 |
| HP            | 1496                        | Desktop     | [fae90baa23](https://bsd-hardware.info/?probe=fae90baa23) | Jan 31, 2023 |
| Razer         | Blade Stealth               | Notebook    | [c0b9641604](https://bsd-hardware.info/?probe=c0b9641604) | Jan 29, 2023 |
| Packard Be... | DOT S                       | Notebook    | [09a2057767](https://bsd-hardware.info/?probe=09a2057767) | Jan 28, 2023 |
| Razer         | Blade Stealth               | Notebook    | [14760d0c64](https://bsd-hardware.info/?probe=14760d0c64) | Jan 28, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [a6b109939f](https://bsd-hardware.info/?probe=a6b109939f) | Jan 28, 2023 |
| YANYU         | R250                        | Desktop     | [866e67f059](https://bsd-hardware.info/?probe=866e67f059) | Jan 27, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e6ad419f5e](https://bsd-hardware.info/?probe=e6ad419f5e) | Jan 20, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [142b3ad8d6](https://bsd-hardware.info/?probe=142b3ad8d6) | Jan 20, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [8580d62bf3](https://bsd-hardware.info/?probe=8580d62bf3) | Jan 19, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | Desktop     | [1424b3641c](https://bsd-hardware.info/?probe=1424b3641c) | Jan 18, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | Desktop     | [d491694079](https://bsd-hardware.info/?probe=d491694079) | Jan 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [cbdab56490](https://bsd-hardware.info/?probe=cbdab56490) | Jan 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [4ccf28379a](https://bsd-hardware.info/?probe=4ccf28379a) | Jan 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [dcdf55f06e](https://bsd-hardware.info/?probe=dcdf55f06e) | Jan 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9d87e4009a](https://bsd-hardware.info/?probe=9d87e4009a) | Jan 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e42082b1c1](https://bsd-hardware.info/?probe=e42082b1c1) | Jan 15, 2023 |
| Dell          | 0NX642 A11                  | Server      | [f98068785d](https://bsd-hardware.info/?probe=f98068785d) | Jan 12, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [1d30039961](https://bsd-hardware.info/?probe=1d30039961) | Jan 11, 2023 |
| Razer         | Blade Stealth               | Notebook    | [2464314a65](https://bsd-hardware.info/?probe=2464314a65) | Jan 11, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [549b75038e](https://bsd-hardware.info/?probe=549b75038e) | Jan 08, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5e81493c8d](https://bsd-hardware.info/?probe=5e81493c8d) | Jan 08, 2023 |
| Intel         | SKYBAY                      | Desktop     | [21ed0daf1c](https://bsd-hardware.info/?probe=21ed0daf1c) | Jan 08, 2023 |
| YANYU         | R250                        | Desktop     | [7ea489eae6](https://bsd-hardware.info/?probe=7ea489eae6) | Jan 06, 2023 |
| SLIMBOOK      | ESSENTIAL-15-11             | Notebook    | [3f758732d3](https://bsd-hardware.info/?probe=3f758732d3) | Jan 05, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [aa6c483d4f](https://bsd-hardware.info/?probe=aa6c483d4f) | Jan 03, 2023 |
| Alienware     | m15 R4                      | Notebook    | [1438237430](https://bsd-hardware.info/?probe=1438237430) | Jan 02, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [07dc4a3178](https://bsd-hardware.info/?probe=07dc4a3178) | Dec 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Alienware     | m15 R4                      | Notebook    | [deaef8f0ef](https://bsd-hardware.info/?probe=deaef8f0ef) | Dec 24, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [0e2278affa](https://bsd-hardware.info/?probe=0e2278affa) | Dec 14, 2022 |
| HP            | Pavilion dv4                | Notebook    | [ee94a86a43](https://bsd-hardware.info/?probe=ee94a86a43) | Dec 12, 2022 |
| YANYU         | R250                        | Desktop     | [bb364271b2](https://bsd-hardware.info/?probe=bb364271b2) | Dec 05, 2022 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [6fe2ba74b7](https://bsd-hardware.info/?probe=6fe2ba74b7) | Dec 01, 2022 |
| Unknown       | A04                         | Server      | [07f21afacc](https://bsd-hardware.info/?probe=07f21afacc) | Nov 29, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [3541df7dd2](https://bsd-hardware.info/?probe=3541df7dd2) | Nov 27, 2022 |
| YANYU         | R250                        | Desktop     | [0be0925e5b](https://bsd-hardware.info/?probe=0be0925e5b) | Nov 27, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [067e8e4d58](https://bsd-hardware.info/?probe=067e8e4d58) | Nov 26, 2022 |
| HP            | 3048h                       | Desktop     | [3f43816a5d](https://bsd-hardware.info/?probe=3f43816a5d) | Nov 25, 2022 |
| Lenovo        | ThinkStation S30 0569A93    | Desktop     | [dd545fb588](https://bsd-hardware.info/?probe=dd545fb588) | Nov 25, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [6fa29c4e4d](https://bsd-hardware.info/?probe=6fa29c4e4d) | Nov 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3c11fc31b2](https://bsd-hardware.info/?probe=3c11fc31b2) | Nov 24, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [fc71b97d90](https://bsd-hardware.info/?probe=fc71b97d90) | Nov 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9701222998](https://bsd-hardware.info/?probe=9701222998) | Nov 23, 2022 |
| HP            | 1998                        | Desktop     | [9239fe7437](https://bsd-hardware.info/?probe=9239fe7437) | Nov 15, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [443891740b](https://bsd-hardware.info/?probe=443891740b) | Nov 13, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [e5b3cb0bcd](https://bsd-hardware.info/?probe=e5b3cb0bcd) | Nov 12, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [5dcd51844e](https://bsd-hardware.info/?probe=5dcd51844e) | Nov 09, 2022 |
| YANYU         | R250                        | Desktop     | [f39d55e42d](https://bsd-hardware.info/?probe=f39d55e42d) | Oct 28, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [079830f938](https://bsd-hardware.info/?probe=079830f938) | Oct 24, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2fa4641b0e](https://bsd-hardware.info/?probe=2fa4641b0e) | Oct 24, 2022 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [50c3c93790](https://bsd-hardware.info/?probe=50c3c93790) | Oct 17, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [baf0edf73a](https://bsd-hardware.info/?probe=baf0edf73a) | Oct 16, 2022 |
| YANYU         | H67SL                       | Desktop     | [373902d38b](https://bsd-hardware.info/?probe=373902d38b) | Oct 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [34d05fe49c](https://bsd-hardware.info/?probe=34d05fe49c) | Oct 07, 2022 |
| HP            | Compaq 6735s                | Notebook    | [f61208cfea](https://bsd-hardware.info/?probe=f61208cfea) | Oct 05, 2022 |
| HP            | Compaq 6735s                | Notebook    | [718126149c](https://bsd-hardware.info/?probe=718126149c) | Oct 05, 2022 |
| HP            | ProBook 4540s               | Notebook    | [df94757940](https://bsd-hardware.info/?probe=df94757940) | Oct 02, 2022 |
| Dell          | 0TDG4V A00                  | Desktop     | [cc92be7e52](https://bsd-hardware.info/?probe=cc92be7e52) | Sep 25, 2022 |
| ASUSTek       | All Series                  | Desktop     | [ab3b339cf0](https://bsd-hardware.info/?probe=ab3b339cf0) | Sep 24, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [10f0cfa344](https://bsd-hardware.info/?probe=10f0cfa344) | Sep 15, 2022 |
| HP            | 213D A01                    | Desktop     | [54288c6759](https://bsd-hardware.info/?probe=54288c6759) | Sep 11, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [7c9c1db9d7](https://bsd-hardware.info/?probe=7c9c1db9d7) | Sep 10, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [ac185c104b](https://bsd-hardware.info/?probe=ac185c104b) | Aug 31, 2022 |
| Dell          | Latitude 7390               | Notebook    | [bc5eb8e237](https://bsd-hardware.info/?probe=bc5eb8e237) | Aug 29, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [e7dc9cc5ee](https://bsd-hardware.info/?probe=e7dc9cc5ee) | Aug 28, 2022 |
| YANYU         | R250                        | Desktop     | [c4f1ec0d5b](https://bsd-hardware.info/?probe=c4f1ec0d5b) | Aug 27, 2022 |
| YANYU         | H67SL                       | Desktop     | [57afa0c5d1](https://bsd-hardware.info/?probe=57afa0c5d1) | Aug 25, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [21fed03fa2](https://bsd-hardware.info/?probe=21fed03fa2) | Aug 24, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [48210e4d2a](https://bsd-hardware.info/?probe=48210e4d2a) | Aug 24, 2022 |
| Lenovo        | ThinkCentre M91p 4512A47    | Desktop     | [3556794570](https://bsd-hardware.info/?probe=3556794570) | Aug 23, 2022 |
| YANYU         | R250                        | Desktop     | [bd7edcafbe](https://bsd-hardware.info/?probe=bd7edcafbe) | Aug 22, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [2325f41325](https://bsd-hardware.info/?probe=2325f41325) | Aug 20, 2022 |
| HP            | 213D A01                    | Desktop     | [4b231023a1](https://bsd-hardware.info/?probe=4b231023a1) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f8c10bf25a](https://bsd-hardware.info/?probe=f8c10bf25a) | Aug 15, 2022 |
| Alienware     | m15 R4                      | Notebook    | [769c5c43f3](https://bsd-hardware.info/?probe=769c5c43f3) | Aug 13, 2022 |
| YANYU         | R250                        | Desktop     | [4552b74317](https://bsd-hardware.info/?probe=4552b74317) | Aug 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [c0daba1c48](https://bsd-hardware.info/?probe=c0daba1c48) | Aug 09, 2022 |
| YANYU         | R250                        | Desktop     | [ffad8eb019](https://bsd-hardware.info/?probe=ffad8eb019) | Aug 07, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b2858de568](https://bsd-hardware.info/?probe=b2858de568) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [ea08102a81](https://bsd-hardware.info/?probe=ea08102a81) | Aug 06, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [50a0d392e7](https://bsd-hardware.info/?probe=50a0d392e7) | Aug 06, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [f2836f4a6c](https://bsd-hardware.info/?probe=f2836f4a6c) | Aug 01, 2022 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [091fe7ca40](https://bsd-hardware.info/?probe=091fe7ca40) | Jul 28, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [6cdc79a36f](https://bsd-hardware.info/?probe=6cdc79a36f) | Jul 22, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [b779706b7a](https://bsd-hardware.info/?probe=b779706b7a) | Jul 21, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [051f604f9a](https://bsd-hardware.info/?probe=051f604f9a) | Jul 21, 2022 |
| Dell          | Studio XPS 1340             | Notebook    | [642da98e96](https://bsd-hardware.info/?probe=642da98e96) | Jul 21, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [a96e41f99e](https://bsd-hardware.info/?probe=a96e41f99e) | Jul 20, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [25e43be096](https://bsd-hardware.info/?probe=25e43be096) | Jul 17, 2022 |
| PC Engines    | APU2                        | Desktop     | [c84cb618c0](https://bsd-hardware.info/?probe=c84cb618c0) | Jul 17, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [5e51d228ec](https://bsd-hardware.info/?probe=5e51d228ec) | Jun 21, 2022 |
| Dell          | Latitude 7390               | Notebook    | [2b888ed291](https://bsd-hardware.info/?probe=2b888ed291) | Jun 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e9dafa8427](https://bsd-hardware.info/?probe=e9dafa8427) | Jun 10, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7a88f52138](https://bsd-hardware.info/?probe=7a88f52138) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [938866fb80](https://bsd-hardware.info/?probe=938866fb80) | May 21, 2022 |
| HP            | ProBook 4340s               | Notebook    | [6cc978f98f](https://bsd-hardware.info/?probe=6cc978f98f) | May 09, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7dde4d8c3e](https://bsd-hardware.info/?probe=7dde4d8c3e) | Apr 23, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0c01c184d4](https://bsd-hardware.info/?probe=0c01c184d4) | Apr 23, 2022 |
| ASUSTek       | X556UJ                      | Notebook    | [ca63749774](https://bsd-hardware.info/?probe=ca63749774) | Apr 19, 2022 |
| OEM           | NU93 Series                 | Desktop     | [e558435c70](https://bsd-hardware.info/?probe=e558435c70) | Apr 12, 2022 |
| OEM           | NU93 Series                 | Desktop     | [505cbbac5d](https://bsd-hardware.info/?probe=505cbbac5d) | Apr 12, 2022 |
| ASUSTek       | CP6230                      | Desktop     | [a407409700](https://bsd-hardware.info/?probe=a407409700) | Apr 11, 2022 |
| HP            | 1998                        | Desktop     | [06f0a28858](https://bsd-hardware.info/?probe=06f0a28858) | Apr 10, 2022 |
| HP            | 213D A01                    | Desktop     | [b8b1c05451](https://bsd-hardware.info/?probe=b8b1c05451) | Mar 25, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [086a58a68f](https://bsd-hardware.info/?probe=086a58a68f) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [f25a608944](https://bsd-hardware.info/?probe=f25a608944) | Mar 19, 2022 |
| HP            | 213D A01                    | Desktop     | [88eb5a2df5](https://bsd-hardware.info/?probe=88eb5a2df5) | Mar 18, 2022 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | Notebook    | [0fbc782835](https://bsd-hardware.info/?probe=0fbc782835) | Mar 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [25f6419f30](https://bsd-hardware.info/?probe=25f6419f30) | Mar 12, 2022 |
| ASUSTek       | P5K PRO                     | Desktop     | [fbde5657e8](https://bsd-hardware.info/?probe=fbde5657e8) | Mar 11, 2022 |
| HP            | 8054                        | Desktop     | [86b6b8373c](https://bsd-hardware.info/?probe=86b6b8373c) | Mar 08, 2022 |
| HP            | 8054                        | Desktop     | [00078554d2](https://bsd-hardware.info/?probe=00078554d2) | Mar 08, 2022 |
| Unknown       | YL-SKUL6-7 Series           | Desktop     | [6f969a5cf2](https://bsd-hardware.info/?probe=6f969a5cf2) | Feb 27, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [a2df68e1d1](https://bsd-hardware.info/?probe=a2df68e1d1) | Feb 26, 2022 |
| Medion        | H61H2-LM3                   | Desktop     | [beb12f2884](https://bsd-hardware.info/?probe=beb12f2884) | Feb 23, 2022 |
| HP            | 1998                        | Desktop     | [485d417a2e](https://bsd-hardware.info/?probe=485d417a2e) | Feb 23, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [e0cf5200de](https://bsd-hardware.info/?probe=e0cf5200de) | Feb 22, 2022 |
| HP            | 213D A01                    | Desktop     | [1506ef3d9c](https://bsd-hardware.info/?probe=1506ef3d9c) | Feb 17, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [eddeb5c246](https://bsd-hardware.info/?probe=eddeb5c246) | Feb 13, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [29756c2371](https://bsd-hardware.info/?probe=29756c2371) | Feb 13, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [84219d3418](https://bsd-hardware.info/?probe=84219d3418) | Feb 10, 2022 |
| TWINHEAD      | U12CT                       | Notebook    | [32247012ca](https://bsd-hardware.info/?probe=32247012ca) | Feb 06, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [2fe214dc2b](https://bsd-hardware.info/?probe=2fe214dc2b) | Feb 01, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [020a9098cd](https://bsd-hardware.info/?probe=020a9098cd) | Feb 01, 2022 |
| Unknown       | YL-1900L4-V2                | Desktop     | [fccaf1b541](https://bsd-hardware.info/?probe=fccaf1b541) | Jan 31, 2022 |
| ECS           | APLD-MINI                   | Desktop     | [e64118d206](https://bsd-hardware.info/?probe=e64118d206) | Jan 30, 2022 |
| HP            | 213D A01                    | Desktop     | [8419869d89](https://bsd-hardware.info/?probe=8419869d89) | Jan 29, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [72630c073d](https://bsd-hardware.info/?probe=72630c073d) | Jan 27, 2022 |
| HP            | 1998                        | Desktop     | [b59dbcdc9c](https://bsd-hardware.info/?probe=b59dbcdc9c) | Jan 23, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [34805f5f83](https://bsd-hardware.info/?probe=34805f5f83) | Jan 17, 2022 |
| Unknown       | YL-1900L4-V2                | Desktop     | [ec13024551](https://bsd-hardware.info/?probe=ec13024551) | Jan 12, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [3c27c8bf31](https://bsd-hardware.info/?probe=3c27c8bf31) | Jan 09, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [bf95cdeb53](https://bsd-hardware.info/?probe=bf95cdeb53) | Jan 04, 2022 |
| ASRock        | N3700-ITX                   | Desktop     | [fb058e0b37](https://bsd-hardware.info/?probe=fb058e0b37) | Jan 03, 2022 |
| ASRock        | N3700-ITX                   | Desktop     | [dda4b4e02b](https://bsd-hardware.info/?probe=dda4b4e02b) | Dec 29, 2021 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [d19f149583](https://bsd-hardware.info/?probe=d19f149583) | Dec 26, 2021 |
| OEM           | AR-B5800                    | Desktop     | [90f43e277a](https://bsd-hardware.info/?probe=90f43e277a) | Dec 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [bb3183702b](https://bsd-hardware.info/?probe=bb3183702b) | Dec 17, 2021 |
| Lenovo        | ThinkPad T440p 20AW007QM... | Notebook    | [9efeb9ee24](https://bsd-hardware.info/?probe=9efeb9ee24) | Dec 16, 2021 |
| ShenZhen M... | 3865U-6L                    | Desktop     | [09d0d26857](https://bsd-hardware.info/?probe=09d0d26857) | Dec 13, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6a1100cfdb](https://bsd-hardware.info/?probe=6a1100cfdb) | Dec 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [48d1f61478](https://bsd-hardware.info/?probe=48d1f61478) | Dec 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [46b91a9c0c](https://bsd-hardware.info/?probe=46b91a9c0c) | Dec 10, 2021 |
| OEM           | AR-B5800                    | Desktop     | [ec11b97e0e](https://bsd-hardware.info/?probe=ec11b97e0e) | Dec 08, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [6dbcac684f](https://bsd-hardware.info/?probe=6dbcac684f) | Dec 04, 2021 |
| Alienware     | m15 R4                      | Notebook    | [a724a7d7c7](https://bsd-hardware.info/?probe=a724a7d7c7) | Nov 29, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [1e7eb2056b](https://bsd-hardware.info/?probe=1e7eb2056b) | Nov 29, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4cd5e5166a](https://bsd-hardware.info/?probe=4cd5e5166a) | Nov 27, 2021 |
| AZW           | BT3 PRO                     | Notebook    | [3454b5492b](https://bsd-hardware.info/?probe=3454b5492b) | Nov 15, 2021 |
| AZW           | BT3 PRO                     | Notebook    | [5d4b48a3a3](https://bsd-hardware.info/?probe=5d4b48a3a3) | Nov 15, 2021 |
| ASUSTek       | Rampage Formula             | Desktop     | [09f67a9982](https://bsd-hardware.info/?probe=09f67a9982) | Nov 09, 2021 |
| ASUSTek       | Rampage Formula             | Desktop     | [183f1a8d62](https://bsd-hardware.info/?probe=183f1a8d62) | Nov 08, 2021 |
| ECS           | APLD-MINI                   | Desktop     | [402d7bc95c](https://bsd-hardware.info/?probe=402d7bc95c) | Nov 07, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [9959c0900a](https://bsd-hardware.info/?probe=9959c0900a) | Oct 23, 2021 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | Notebook    | [d92e6e3c21](https://bsd-hardware.info/?probe=d92e6e3c21) | Oct 11, 2021 |
| ASUSTek       | D940MX                      | Desktop     | [4e798f3ef0](https://bsd-hardware.info/?probe=4e798f3ef0) | Oct 10, 2021 |
| ASUSTek       | U33Jc                       | Notebook    | [07f11b6604](https://bsd-hardware.info/?probe=07f11b6604) | Oct 10, 2021 |
| ASRock        | J5005-ITX                   | Desktop     | [a7f333eedb](https://bsd-hardware.info/?probe=a7f333eedb) | Oct 10, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [67ed0f639c](https://bsd-hardware.info/?probe=67ed0f639c) | Oct 10, 2021 |
| ASRock        | J5005-ITX                   | Desktop     | [6589a62805](https://bsd-hardware.info/?probe=6589a62805) | Oct 08, 2021 |
| BESSTAR Te... | VB9                         | Mini pc     | [e2b78b7ada](https://bsd-hardware.info/?probe=e2b78b7ada) | Sep 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b8408cb369](https://bsd-hardware.info/?probe=b8408cb369) | Sep 06, 2021 |
| BESSTAR Te... | VB9                         | Mini pc     | [e30341b103](https://bsd-hardware.info/?probe=e30341b103) | Sep 06, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [7a42009a08](https://bsd-hardware.info/?probe=7a42009a08) | Sep 02, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [eb81abe401](https://bsd-hardware.info/?probe=eb81abe401) | Sep 02, 2021 |
| Dell          | Latitude E6530              | Notebook    | [8dbff835d2](https://bsd-hardware.info/?probe=8dbff835d2) | Sep 02, 2021 |
| Intel         | CARLOW                      | Desktop     | [035b6b4b42](https://bsd-hardware.info/?probe=035b6b4b42) | Sep 02, 2021 |
| ShenZhen M... | 3865U-6L                    | Desktop     | [ebf562c2d6](https://bsd-hardware.info/?probe=ebf562c2d6) | Sep 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [5c37b14dd5](https://bsd-hardware.info/?probe=5c37b14dd5) | Aug 27, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | Notebook    | [b00c8e76e8](https://bsd-hardware.info/?probe=b00c8e76e8) | Aug 23, 2021 |
| Gigabyte      | GA-7VT600                   | Desktop     | [83b86f3e8c](https://bsd-hardware.info/?probe=83b86f3e8c) | Aug 23, 2021 |
| HP            | 250 G4                      | Notebook    | [24e8c3de59](https://bsd-hardware.info/?probe=24e8c3de59) | Aug 13, 2021 |
| HP            | 250 G4                      | Notebook    | [43a7b112ba](https://bsd-hardware.info/?probe=43a7b112ba) | Aug 11, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [6896c37580](https://bsd-hardware.info/?probe=6896c37580) | Aug 06, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [e77c4adf8a](https://bsd-hardware.info/?probe=e77c4adf8a) | Jul 28, 2021 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [e2f0f95779](https://bsd-hardware.info/?probe=e2f0f95779) | Jul 18, 2021 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [7727ec2d09](https://bsd-hardware.info/?probe=7727ec2d09) | Jul 07, 2021 |
| Gigabyte      | 965P-DS4                    | Desktop     | [c4d4537787](https://bsd-hardware.info/?probe=c4d4537787) | Jul 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [443817737d](https://bsd-hardware.info/?probe=443817737d) | Jun 24, 2021 |
| ASUSTek       | Rampage Formula             | Desktop     | [477a2a84f4](https://bsd-hardware.info/?probe=477a2a84f4) | Jun 24, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [584a4afd69](https://bsd-hardware.info/?probe=584a4afd69) | Jun 14, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [abc94e9198](https://bsd-hardware.info/?probe=abc94e9198) | Jun 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [3e8940224f](https://bsd-hardware.info/?probe=3e8940224f) | Jun 13, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [99ce3d3fc6](https://bsd-hardware.info/?probe=99ce3d3fc6) | May 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [9ff0fb7df4](https://bsd-hardware.info/?probe=9ff0fb7df4) | May 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [2acd0848c8](https://bsd-hardware.info/?probe=2acd0848c8) | May 01, 2021 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [0d584c2a00](https://bsd-hardware.info/?probe=0d584c2a00) | Apr 26, 2021 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [7f9cdc62a2](https://bsd-hardware.info/?probe=7f9cdc62a2) | Apr 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [f49d7529c0](https://bsd-hardware.info/?probe=f49d7529c0) | Apr 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [08da04fdf6](https://bsd-hardware.info/?probe=08da04fdf6) | Apr 09, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [367b6e05d3](https://bsd-hardware.info/?probe=367b6e05d3) | Apr 07, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [6483c8390f](https://bsd-hardware.info/?probe=6483c8390f) | Mar 31, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [ac585b4e0d](https://bsd-hardware.info/?probe=ac585b4e0d) | Mar 30, 2021 |
| Dell          | Latitude 7390               | Notebook    | [2ad87768af](https://bsd-hardware.info/?probe=2ad87768af) | Mar 25, 2021 |
| Lenovo        | ThinkPad L590 20Q7000YSP    | Notebook    | [038fbabfe8](https://bsd-hardware.info/?probe=038fbabfe8) | Mar 24, 2021 |
| MSI           | GE75 Raider 10SGS           | Notebook    | [fea3cdb5d1](https://bsd-hardware.info/?probe=fea3cdb5d1) | Mar 24, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [a05b7c3785](https://bsd-hardware.info/?probe=a05b7c3785) | Mar 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [9c5685e8fa](https://bsd-hardware.info/?probe=9c5685e8fa) | Mar 22, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [10c79ea427](https://bsd-hardware.info/?probe=10c79ea427) | Mar 22, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [c15d8c77ef](https://bsd-hardware.info/?probe=c15d8c77ef) | Mar 11, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b1ee3da46f](https://bsd-hardware.info/?probe=b1ee3da46f) | Mar 06, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [a03927cc2e](https://bsd-hardware.info/?probe=a03927cc2e) | Mar 06, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [01df19257a](https://bsd-hardware.info/?probe=01df19257a) | Mar 05, 2021 |
| ASUSTek       | Rampage Formula             | Desktop     | [3d2377b221](https://bsd-hardware.info/?probe=3d2377b221) | Mar 03, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [ac108deea2](https://bsd-hardware.info/?probe=ac108deea2) | Feb 28, 2021 |
| Acer          | Aspire XC-115               | Desktop     | [95f63df64d](https://bsd-hardware.info/?probe=95f63df64d) | Feb 21, 2021 |
| Samsung       | Galaxy Book 12              | Tablet      | [91c76db748](https://bsd-hardware.info/?probe=91c76db748) | Feb 18, 2021 |
| Samsung       | Galaxy Book 12              | Tablet      | [5f73061749](https://bsd-hardware.info/?probe=5f73061749) | Feb 18, 2021 |
| Dell          | Latitude 7390               | Notebook    | [3fe6eff89a](https://bsd-hardware.info/?probe=3fe6eff89a) | Feb 17, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [bb8beb97be](https://bsd-hardware.info/?probe=bb8beb97be) | Feb 17, 2021 |
| YANYU         | H67SL                       | Desktop     | [d8d30a13fa](https://bsd-hardware.info/?probe=d8d30a13fa) | Feb 14, 2021 |
| HP            | 2B17                        | Desktop     | [572bf634a8](https://bsd-hardware.info/?probe=572bf634a8) | Feb 12, 2021 |
| HP            | 8055                        | Desktop     | [8ecc5bbb55](https://bsd-hardware.info/?probe=8ecc5bbb55) | Feb 12, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [f1bc2178a9](https://bsd-hardware.info/?probe=f1bc2178a9) | Feb 12, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a49ff2b77a](https://bsd-hardware.info/?probe=a49ff2b77a) | Feb 11, 2021 |
| Medion        | H81H3-EM2 H81EM2W08.308     | Desktop     | [9958f514c9](https://bsd-hardware.info/?probe=9958f514c9) | Feb 10, 2021 |
| ASRock        | H270M Pro4                  | Desktop     | [37af53e334](https://bsd-hardware.info/?probe=37af53e334) | Feb 10, 2021 |
| Acer          | Aspire X1700                | Desktop     | [06dc1753ef](https://bsd-hardware.info/?probe=06dc1753ef) | Feb 10, 2021 |
| Acer          | Aspire X1700                | Desktop     | [6886acf351](https://bsd-hardware.info/?probe=6886acf351) | Feb 10, 2021 |
| ZOTAC         | ZBOXNANO-AQ01               | Mini pc     | [78d3ae05f0](https://bsd-hardware.info/?probe=78d3ae05f0) | Jan 30, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [69fdf82488](https://bsd-hardware.info/?probe=69fdf82488) | Jan 30, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [340bcdffc6](https://bsd-hardware.info/?probe=340bcdffc6) | Jan 30, 2021 |
| Dell          | 09T7VV A05                  | Server      | [c1638adfa6](https://bsd-hardware.info/?probe=c1638adfa6) | Jan 27, 2021 |
| ZOTAC         | ZBOXNANO-AQ01               | Mini pc     | [dc3307a2e1](https://bsd-hardware.info/?probe=dc3307a2e1) | Jan 20, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [415023d5a1](https://bsd-hardware.info/?probe=415023d5a1) | Jan 10, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [c51c202b8d](https://bsd-hardware.info/?probe=c51c202b8d) | Dec 25, 2020 |
| Intel         | NUC5i5RYB H40999-506        | Mini pc     | [8a7b8618bf](https://bsd-hardware.info/?probe=8a7b8618bf) | Dec 07, 2020 |
| Apple         | MacBook6,1                  | Notebook    | [64b1b1910c](https://bsd-hardware.info/?probe=64b1b1910c) | Nov 01, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8227b36f77](https://bsd-hardware.info/?probe=8227b36f77) | Oct 31, 2020 |
| eMachines     | EL1200                      | Desktop     | [ae59908738](https://bsd-hardware.info/?probe=ae59908738) | Oct 30, 2020 |
| Acer          | Veriton M6610G              | Desktop     | [7dd00aa8b1](https://bsd-hardware.info/?probe=7dd00aa8b1) | Oct 30, 2020 |
| eMachines     | EL1200                      | Desktop     | [5bc54351be](https://bsd-hardware.info/?probe=5bc54351be) | Oct 30, 2020 |
| ECS           | BSWI-D2                     | Desktop     | [c5b07f5c31](https://bsd-hardware.info/?probe=c5b07f5c31) | Oct 30, 2020 |
| Acer          | Extensa 2540                | Notebook    | [26670a4ae9](https://bsd-hardware.info/?probe=26670a4ae9) | Oct 30, 2020 |
| Lenovo        | SHARKBAY WIN                | Desktop     | [53feb1fec6](https://bsd-hardware.info/?probe=53feb1fec6) | Oct 19, 2020 |
| Lenovo        | G50-80 80E5                 | Notebook    | [e06605a92b](https://bsd-hardware.info/?probe=e06605a92b) | Oct 19, 2020 |
| Acer          | Aspire XC-605               | Desktop     | [d8688fe23f](https://bsd-hardware.info/?probe=d8688fe23f) | Aug 24, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [1dbb703a8b](https://bsd-hardware.info/?probe=1dbb703a8b) | Aug 23, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c7c50d64cf](https://bsd-hardware.info/?probe=c7c50d64cf) | May 29, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a49cf5c20b](https://bsd-hardware.info/?probe=a49cf5c20b) | May 28, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| helloSystem 0.8.1 | 27        | 5.9%    |
| helloSystem 0.7.0 | 27        | 5.9%    |
| helloSystem 0.8.0 | 13        | 2.84%   |
| FreeBSD 13.1      | 10        | 2.18%   |
| helloSystem 0.4.0 | 9         | 1.97%   |
| FreeBSD 14.2      | 9         | 1.97%   |
| helloSystem 0.9.0 | 8         | 1.75%   |
| helloSystem 0.5.0 | 8         | 1.75%   |
| OPNsense 22.1     | 7         | 1.53%   |
| OPNsense 25.1     | 6         | 1.31%   |
| OpenBSD 6.8       | 6         | 1.31%   |
| helloSystem 0.6.0 | 6         | 1.31%   |
| FreeBSD 14.0      | 6         | 1.31%   |
| OPNsense 25.7.1   | 5         | 1.09%   |
| OPNsense 25.1.7   | 5         | 1.09%   |
| OPNsense 23.7.12  | 5         | 1.09%   |
| OPNsense 22.7.10  | 5         | 1.09%   |
| OpenBSD 7.2       | 5         | 1.09%   |
| FreeBSD 14.1-p5   | 5         | 1.09%   |
| FreeBSD 13.2      | 5         | 1.09%   |
| OPNsense 25.1.5   | 4         | 0.87%   |
| OPNsense 24.7.7   | 4         | 0.87%   |
| OPNsense 24.1.6   | 4         | 0.87%   |
| OPNsense 24.1.1   | 4         | 0.87%   |
| OPNsense 23.7.7   | 4         | 0.87%   |
| OPNsense 21.7.7   | 4         | 0.87%   |
| OpenBSD 7.6       | 4         | 0.87%   |
| OpenBSD 7.1       | 4         | 0.87%   |
| NomadBSD 20240711 | 4         | 0.87%   |
| NetBSD 10.0       | 4         | 0.87%   |
| GhostBSD 20.04.02 | 4         | 0.87%   |
| OPNsense 25.7.6   | 3         | 0.66%   |
| OPNsense 25.7.5   | 3         | 0.66%   |
| OPNsense 25.1.2   | 3         | 0.66%   |
| OPNsense 25.1.10  | 3         | 0.66%   |
| OPNsense 25.1.1   | 3         | 0.66%   |
| OPNsense 24.7.9   | 3         | 0.66%   |
| OPNsense 24.7.8   | 3         | 0.66%   |
| OPNsense 24.7.10  | 3         | 0.66%   |
| OPNsense 24.1.8   | 3         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 123       | 35.65%  |
| helloSystem | 88        | 25.51%  |
| FreeBSD     | 73        | 21.16%  |
| OpenBSD     | 23        | 6.67%   |
| GhostBSD    | 20        | 5.8%    |
| NetBSD      | 8         | 2.32%   |
| NomadBSD    | 6         | 1.74%   |
| FuguIta     | 2         | 0.58%   |
| TrueNAS     | 1         | 0.29%   |
| DragonFly   | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 326       | 96.45%  |
| arm64  | 6         | 1.78%   |
| i386   | 3         | 0.89%   |
| evbarm | 3         | 0.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 153       | 43.97%  |
| helloDesktop | 106       | 30.46%  |
| MATE         | 25        | 7.18%   |
| XFCE         | 21        | 6.03%   |
| KDE5         | 11        | 3.16%   |
| TWM          | 8         | 2.3%    |
| fvwm         | 7         | 2.01%   |
| GNOME        | 6         | 1.72%   |
| i3           | 4         | 1.15%   |
| Openbox      | 3         | 0.86%   |
| KDE          | 2         | 0.57%   |
| LXQt         | 1         | 0.29%   |
| Fluxbox      | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 183       | 53.82%  |
| Console | 153       | 45%     |
| Wayland | 4         | 1.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 191       | 55.04%  |
| SLiM    | 95        | 27.38%  |
| LightDM | 27        | 7.78%   |
| SDDM    | 22        | 6.34%   |
| GDM     | 6         | 1.73%   |
| XDM     | 4         | 1.15%   |
| Ly      | 2         | 0.58%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 167       | 47.04%  |
| C                | 68        | 19.15%  |
| es_ES            | 53        | 14.93%  |
| en_US            | 50        | 14.08%  |
| fr_FR            | 6         | 1.69%   |
| es               | 5         | 1.41%   |
| ru_RU            | 2         | 0.56%   |
| zh_CN            | 1         | 0.28%   |
| fr               | 1         | 0.28%   |
| es_ES.ISO8859-15 | 1         | 0.28%   |
| de_DE            | 1         | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 286       | 84.12%  |
| BIOS | 54        | 15.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 182       | 51.41%  |
| Ufs     | 100       | 28.25%  |
| Cd9660  | 45        | 12.71%  |
| Ffs     | 25        | 7.06%   |
| Hammer2 | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 300       | 88.24%  |
| MBR     | 34        | 10%     |
| Unknown | 6         | 1.76%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 49        | 14.5%   |
| Lenovo                               | 36        | 10.65%  |
| ASUSTek Computer                     | 35        | 10.36%  |
| Unknown                              | 34        | 10.06%  |
| Dell                                 | 23        | 6.8%    |
| Gigabyte Technology                  | 16        | 4.73%   |
| AMI                                  | 14        | 4.14%   |
| Acer                                 | 14        | 4.14%   |
| MSI                                  | 12        | 3.55%   |
| Intel                                | 12        | 3.55%   |
| ASRock                               | 9         | 2.66%   |
| Raspberry Pi Foundation              | 8         | 2.37%   |
| Fujitsu                              | 7         | 2.07%   |
| Apple                                | 7         | 2.07%   |
| Techvision                           | 5         | 1.48%   |
| YANYU                                | 4         | 1.18%   |
| Framework                            | 4         | 1.18%   |
| Toshiba                              | 3         | 0.89%   |
| Sophos                               | 3         | 0.89%   |
| Medion                               | 3         | 0.89%   |
| AZW                                  | 3         | 0.89%   |
| Sony                                 | 2         | 0.59%   |
| SLIMBOOK                             | 2         | 0.59%   |
| Samsung Electronics                  | 2         | 0.59%   |
| PC Engines                           | 2         | 0.59%   |
| OEM                                  | 2         | 0.59%   |
| HPE                                  | 2         | 0.59%   |
| ECS                                  | 2         | 0.59%   |
| BESSTAR Tech                         | 2         | 0.59%   |
| Alienware                            | 2         | 0.59%   |
| ZOTAC                                | 1         | 0.3%    |
| Wistron                              | 1         | 0.3%    |
| TWINHEAD                             | 1         | 0.3%    |
| TUXEDO                               | 1         | 0.3%    |
| ShenZhen MinWin Technology           | 1         | 0.3%    |
| Shenzhen Meigao Electronic Equipment | 1         | 0.3%    |
| Seeed Studio                         | 1         | 0.3%    |
| ReachingTech                         | 1         | 0.3%    |
| Razer                                | 1         | 0.3%    |
| Protectli                            | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 36        | 10.65%  |
| AMI Aptio CRB                                     | 11        | 3.25%   |
| RPi Raspberry Pi                                  | 7         | 2.07%   |
| Techvision TVI7309X                               | 5         | 1.48%   |
| Sophos XG                                         | 3         | 0.89%   |
| HP EliteDesk 700 G1 SFF                           | 3         | 0.89%   |
| Fujitsu FUTRO S920                                | 3         | 0.89%   |
| Framework Laptop (13th Gen Intel Core)            | 3         | 0.89%   |
| Dell Precision 5510                               | 3         | 0.89%   |
| Dell Latitude 7390                                | 3         | 0.89%   |
| ASUS All Series                                   | 3         | 0.89%   |
| YANYU R250                                        | 2         | 0.59%   |
| YANYU H67SL                                       | 2         | 0.59%   |
| MSI MS-7C52                                       | 2         | 0.59%   |
| HPE ProLiant MicroServer Gen10                    | 2         | 0.59%   |
| HP t620 PLUS Quad Core TC                         | 2         | 0.59%   |
| HP ProDesk 600 G5 SFF                             | 2         | 0.59%   |
| HP Pavilion Gaming Laptop 15-ec1xxx               | 2         | 0.59%   |
| HP Compaq Elite 8300 USDT                         | 2         | 0.59%   |
| AZW EQ                                            | 2         | 0.59%   |
| ASUS PRIME A320M-K                                | 2         | 0.59%   |
| ASUS K55VD                                        | 2         | 0.59%   |
| ASRock N3700-ITX                                  | 2         | 0.59%   |
| ASRock H81M-VG4 R2.0                              | 2         | 0.59%   |
| Apple Macmini6,2                                  | 2         | 0.59%   |
| ZOTAC ZBOXNANO-AQ01                               | 1         | 0.3%    |
| Wistron ProLiant ML110 G6                         | 1         | 0.3%    |
| TWINHEAD U12CT                                    | 1         | 0.3%    |
| TUXEDO Aura 15 Gen1                               | 1         | 0.3%    |
| Toshiba Satellite A300                            | 1         | 0.3%    |
| Toshiba Satellite A110                            | 1         | 0.3%    |
| Toshiba Portable PC                               | 1         | 0.3%    |
| Sony VPCSB3Q9E                                    | 1         | 0.3%    |
| Sony SVE1511C5E                                   | 1         | 0.3%    |
| SLIMBOOK PROX-AMD5                                | 1         | 0.3%    |
| SLIMBOOK ESSENTIAL-15-11                          | 1         | 0.3%    |
| ShenZhen MinWin 3865U-6L                          | 1         | 0.3%    |
| Shenzhen Meigao Electronic Equipment Venus series | 1         | 0.3%    |
| Seeed Studio ODYSSEY-X86J4105                     | 1         | 0.3%    |
| Samsung Galaxy Book 12                            | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 36        | 10.65%  |
| Lenovo ThinkPad     | 17        | 5.03%   |
| AMI Aptio           | 11        | 3.25%   |
| Lenovo ThinkCentre  | 9         | 2.66%   |
| Acer Aspire         | 9         | 2.66%   |
| RPi Raspberry       | 8         | 2.37%   |
| HP Pavilion         | 8         | 2.37%   |
| HP Compaq           | 7         | 2.07%   |
| Dell OptiPlex       | 7         | 2.07%   |
| ASUS PRIME          | 7         | 2.07%   |
| HP EliteDesk        | 6         | 1.78%   |
| Techvision TVI7309X | 5         | 1.48%   |
| HP ProLiant         | 5         | 1.48%   |
| Dell Latitude       | 5         | 1.48%   |
| Lenovo IdeaPad      | 4         | 1.18%   |
| HP ProBook          | 4         | 1.18%   |
| Framework Laptop    | 4         | 1.18%   |
| Dell Precision      | 4         | 1.18%   |
| Sophos XG           | 3         | 0.89%   |
| HP OMEN             | 3         | 0.89%   |
| HP Laptop           | 3         | 0.89%   |
| Fujitsu FUTRO       | 3         | 0.89%   |
| Fujitsu ESPRIMO     | 3         | 0.89%   |
| ASUS TUF            | 3         | 0.89%   |
| ASUS All            | 3         | 0.89%   |
| YANYU R250          | 2         | 0.59%   |
| YANYU H67SL         | 2         | 0.59%   |
| Toshiba Satellite   | 2         | 0.59%   |
| MSI MS-7C52         | 2         | 0.59%   |
| Intel NUC5i5RYB     | 2         | 0.59%   |
| HPE ProLiant        | 2         | 0.59%   |
| HP t620             | 2         | 0.59%   |
| HP ProDesk          | 2         | 0.59%   |
| Dell PowerEdge      | 2         | 0.59%   |
| Dell Inspiron       | 2         | 0.59%   |
| AZW EQ              | 2         | 0.59%   |
| ASUS M5A78L-M       | 2         | 0.59%   |
| ASUS K55VD          | 2         | 0.59%   |
| ASRock N3700-ITX    | 2         | 0.59%   |
| ASRock H81M-VG4     | 2         | 0.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 31        | 9.17%   |
| 2019    | 28        | 8.28%   |
| 2014    | 28        | 8.28%   |
| 2018    | 26        | 7.69%   |
| 2023    | 23        | 6.8%    |
| 2022    | 22        | 6.51%   |
| 2017    | 21        | 6.21%   |
| 2016    | 18        | 5.33%   |
| 2012    | 18        | 5.33%   |
| 2015    | 16        | 4.73%   |
| 2011    | 14        | 4.14%   |
| 2024    | 13        | 3.85%   |
| 2021    | 13        | 3.85%   |
| 2013    | 12        | 3.55%   |
| 2010    | 12        | 3.55%   |
| 2008    | 11        | 3.25%   |
| 2009    | 10        | 2.96%   |
| Unknown | 9         | 2.66%   |
| 2025    | 7         | 2.07%   |
| 2007    | 2         | 0.59%   |
| 2006    | 2         | 0.59%   |
| 2005    | 1         | 0.3%    |
| 2003    | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 175       | 51.78%  |
| Notebook       | 113       | 33.43%  |
| Mini pc        | 28        | 8.28%   |
| System on chip | 8         | 2.37%   |
| Server         | 8         | 2.37%   |
| Firewall       | 3         | 0.89%   |
| Tablet         | 1         | 0.3%    |
| Convertible    | 1         | 0.3%    |
| All in one     | 1         | 0.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 335       | 99.11%  |
| Yes  | 3         | 0.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 117       | 33.72%  |
| 16.01-24.0  | 88        | 25.36%  |
| 4.01-8.0    | 63        | 18.16%  |
| 32.01-64.0  | 36        | 10.37%  |
| 64.01-256.0 | 13        | 3.75%   |
| 2.01-3.0    | 10        | 2.88%   |
| 3.01-4.0    | 7         | 2.02%   |
| 24.01-32.0  | 4         | 1.15%   |
| 1.01-2.0    | 3         | 0.86%   |
| 0.51-1.0    | 3         | 0.86%   |
| 0.01-0.5    | 3         | 0.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 155       | 44.29%  |
| 0.51-1.0   | 115       | 32.86%  |
| 1.01-2.0   | 44        | 12.57%  |
| 2.01-3.0   | 9         | 2.57%   |
| Unknown    | 8         | 2.29%   |
| 4.01-8.0   | 6         | 1.71%   |
| 3.01-4.0   | 6         | 1.71%   |
| 0          | 5         | 1.43%   |
| 24.01-32.0 | 1         | 0.29%   |
| 8.01-16.0  | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 193       | 54.52%  |
| 0      | 72        | 20.34%  |
| 2      | 55        | 15.54%  |
| 4      | 13        | 3.67%   |
| 3      | 10        | 2.82%   |
| 5      | 6         | 1.69%   |
| 6      | 4         | 1.13%   |
| 7      | 1         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 271       | 79.71%  |
| Yes       | 69        | 20.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 303       | 89.64%  |
| No        | 35        | 10.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 177       | 51.91%  |
| No        | 164       | 48.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 205       | 60.29%  |
| Yes       | 135       | 39.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Spain   | 338       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Madrid                        | 72        | 18.41%  |
| Barcelona                     | 24        | 6.14%   |
| Valencia                      | 17        | 4.35%   |
| Seville                       | 9         | 2.3%    |
| Zaragoza                      | 8         | 2.05%   |
| Valladolid                    | 6         | 1.53%   |
| Vigo                          | 5         | 1.28%   |
| Ourense                       | 5         | 1.28%   |
| Ibiza Town                    | 5         | 1.28%   |
| Santiago de Compostela        | 4         | 1.02%   |
| Paterna                       | 4         | 1.02%   |
| Palma                         | 4         | 1.02%   |
| Málaga                       | 4         | 1.02%   |
| Las Palmas de Gran Canaria    | 4         | 1.02%   |
| Bilbao                        | 4         | 1.02%   |
| Alcobendas                    | 4         | 1.02%   |
| Terrassa                      | 3         | 0.77%   |
| Sedavi                        | 3         | 0.77%   |
| Santa Cruz de Tenerife        | 3         | 0.77%   |
| San SebastiÃ¡n de los Reyes | 3         | 0.77%   |
| San Cristóbal de La Laguna   | 3         | 0.77%   |
| Navalcarnero                  | 3         | 0.77%   |
| Mairena del Aljarafe          | 3         | 0.77%   |
| Los Realejos                  | 3         | 0.77%   |
| Getafe                        | 3         | 0.77%   |
| Elche                         | 3         | 0.77%   |
| Barakaldo                     | 3         | 0.77%   |
| A Coruña                     | 3         | 0.77%   |
| Vitoria-Gasteiz               | 2         | 0.51%   |
| Viladecans                    | 2         | 0.51%   |
| Valdemoro                     | 2         | 0.51%   |
| Torrejon del Rey              | 2         | 0.51%   |
| Tomares                       | 2         | 0.51%   |
| Tarragona                     | 2         | 0.51%   |
| Santa Coloma de Farners       | 2         | 0.51%   |
| Sant Cugat del Vallès        | 2         | 0.51%   |
| Redondela                     | 2         | 0.51%   |
| Port de Sagunt                | 2         | 0.51%   |
| Oviedo                        | 2         | 0.51%   |
| Oleiros                       | 2         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                                 | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Samsung Electronics                    | 51        | 80     | 13.67%  |
| WDC                                    | 49        | 71     | 13.14%  |
| Kingston                               | 44        | 88     | 11.8%   |
| Seagate                                | 38        | 67     | 10.19%  |
| Crucial                                | 25        | 32     | 6.7%    |
| Toshiba                                | 16        | 20     | 4.29%   |
| Hitachi                                | 14        | 16     | 3.75%   |
| SanDisk                                | 11        | 12     | 2.95%   |
| China                                  | 9         | 17     | 2.41%   |
| NVMe                                   | 7         | 10     | 1.88%   |
| Transcend                              | 6         | 11     | 1.61%   |
| HGST                                   | 5         | 5      | 1.34%   |
| FORESEE                                | 5         | 5      | 1.34%   |
| Micron Technology                      | 4         | 4      | 1.07%   |
| Intel                                  | 4         | 6      | 1.07%   |
| A-DATA Technology                      | 4         | 4      | 1.07%   |
| TCSUNBOW                               | 3         | 5      | 0.8%    |
| SK hynix                               | 3         | 3      | 0.8%    |
| Phison                                 | 3         | 3      | 0.8%    |
| OCZ                                    | 3         | 3      | 0.8%    |
| LITEONIT                               | 3         | 5      | 0.8%    |
| LITEON                                 | 3         | 3      | 0.8%    |
| KingSpec                               | 3         | 3      | 0.8%    |
| Intenso                                | 3         | 7      | 0.8%    |
| Hewlett-Packard                        | 3         | 10     | 0.8%    |
| Fujitsu                                | 3         | 3      | 0.8%    |
| Corsair                                | 3         | 3      | 0.8%    |
| Apacer                                 | 3         | 3      | 0.8%    |
| XrayDisk                               | 2         | 2      | 0.54%   |
| ViperTeq                               | 2         | 2      | 0.54%   |
| SPCC                                   | 2         | 2      | 0.54%   |
| Silicon Motion                         | 2         | 2      | 0.54%   |
| ShiJi                                  | 2         | 3      | 0.54%   |
| Product:              USB Flash Memory | 2         | 2      | 0.54%   |
| PNY                                    | 2         | 2      | 0.54%   |
| MARVELL                                | 2         | 2      | 0.54%   |
| Kston                                  | 2         | 4      | 0.54%   |
| KIOXIA                                 | 2         | 2      | 0.54%   |
| Innodisk                               | 2         | 4      | 0.54%   |
| Hoodisk                                | 2         | 2      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB                                  | 13        | 3.17%   |
| Kingston SA400S37480G 480GB                                  | 7         | 1.71%   |
| Seagate ST500DM002-1BD142 500GB                              | 6         | 1.46%   |
| Crucial CT500MX500SSD1 500GB                                 | 5         | 1.22%   |
| Seagate ST1000DM010-2EP102 1TB                               | 4         | 0.98%   |
| Samsung SSD 850 EVO 500GB                                    | 4         | 0.98%   |
| Kingston SV300S37A120G 120GB                                 | 4         | 0.98%   |
| Kingston SUV500MS120G 120GB                                  | 4         | 0.98%   |
| Kingston SA400S37120G 120GB                                  | 4         | 0.98%   |
| Transcend TS120GMTS420S 120GB                                | 3         | 0.73%   |
| Samsung SSD 860 EVO 500GB                                    | 3         | 0.73%   |
| Samsung SSD 850 EVO 250GB                                    | 3         | 0.73%   |
| Samsung SSD 840 PRO Series 128GB                             | 3         | 0.73%   |
| Kingston SUV400S37240G 240GB                                 | 3         | 0.73%   |
| Kingston SKC600MS256G 256GB                                  | 3         | 0.73%   |
| Crucial CT240BX500SSD1 240GB                                 | 3         | 0.73%   |
| WDC WDS500G2B0A-00SM50 500GB                                 | 2         | 0.49%   |
| WDC WDS500G1B0A-00H9H0 500GB                                 | 2         | 0.49%   |
| WDC WDS250G1B0A-00H9H0 250GB                                 | 2         | 0.49%   |
| WDC WDS120G2G0B-00EPW0 120GB                                 | 2         | 0.49%   |
| WDC WD2500BEVS-22UST0 250GB                                  | 2         | 0.49%   |
| WDC WD20EARX-00PASB0 2TB                                     | 2         | 0.49%   |
| WDC WD10EZEX-60WN4A0 1TB                                     | 2         | 0.49%   |
| ViperTeq VT-SSDUP500-120 120GB                               | 2         | 0.49%   |
| Toshiba TR200 240GB                                          | 2         | 0.49%   |
| Toshiba MQ01ABD100 1TB                                       | 2         | 0.49%   |
| Seagate ST9500325AS 500GB                                    | 2         | 0.49%   |
| Seagate ST500LM021-1KJ152 500GB                              | 2         | 0.49%   |
| Seagate ST3500418AS 500GB                                    | 2         | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                           | 2         | 0.49%   |
| Seagate ST1000DM003-9YN162 1TB                               | 2         | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB                               | 2         | 0.49%   |
| SanDisk SSD i100 24GB                                        | 2         | 0.49%   |
| SanDisk SDSSDA240G 240GB                                     | 2         | 0.49%   |
| Samsung MZVLW512HMJP-000L7 512GB                             | 2         | 0.49%   |
| Samsung MZ7LN256HCHP-000L7 256GB                             | 2         | 0.49%   |
| Samsung HD103SI 1TB                                          | 2         | 0.49%   |
| Product:              USB Flash Memory USB Flash Memory 16GB | 2         | 0.49%   |
| NVMe Samsung SSD 980 1TB                                     | 2         | 0.49%   |
| MARVELL Raid VD 8TB                                          | 2         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Seagate                                | 37        | 63     | 30.33%  |
| WDC                                    | 33        | 48     | 27.05%  |
| Hitachi                                | 14        | 16     | 11.48%  |
| Toshiba                                | 11        | 13     | 9.02%   |
| Samsung Electronics                    | 9         | 12     | 7.38%   |
| HGST                                   | 5         | 5      | 4.1%    |
| NVMe                                   | 3         | 5      | 2.46%   |
| Fujitsu                                | 3         | 3      | 2.46%   |
| Product:              USB Flash Memory | 2         | 2      | 1.64%   |
| MARVELL                                | 2         | 2      | 1.64%   |
| Hewlett-Packard                        | 2         | 8      | 1.64%   |
| Apple                                  | 1         | 1      | 0.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 42        | 86     | 20.69%  |
| Samsung Electronics | 30        | 43     | 14.78%  |
| Crucial             | 20        | 26     | 9.85%   |
| WDC                 | 11        | 17     | 5.42%   |
| SanDisk             | 11        | 12     | 5.42%   |
| China               | 9         | 17     | 4.43%   |
| Transcend           | 6         | 11     | 2.96%   |
| FORESEE             | 5         | 5      | 2.46%   |
| Toshiba             | 4         | 4      | 1.97%   |
| A-DATA Technology   | 4         | 4      | 1.97%   |
| TCSUNBOW            | 3         | 5      | 1.48%   |
| OCZ                 | 3         | 3      | 1.48%   |
| NVMe                | 3         | 3      | 1.48%   |
| LITEONIT            | 3         | 5      | 1.48%   |
| LITEON              | 3         | 3      | 1.48%   |
| KingSpec            | 3         | 3      | 1.48%   |
| Intel               | 3         | 5      | 1.48%   |
| Apacer              | 3         | 3      | 1.48%   |
| XrayDisk            | 2         | 2      | 0.99%   |
| ViperTeq            | 2         | 2      | 0.99%   |
| SPCC                | 2         | 2      | 0.99%   |
| ShiJi               | 2         | 3      | 0.99%   |
| PNY                 | 2         | 2      | 0.99%   |
| Kston               | 2         | 4      | 0.99%   |
| Intenso             | 2         | 6      | 0.99%   |
| Innodisk            | 2         | 4      | 0.99%   |
| Hoodisk             | 2         | 2      | 0.99%   |
| VICKTER             | 1         | 1      | 0.49%   |
| Verbatim            | 1         | 1      | 0.49%   |
| SK hynix            | 1         | 1      | 0.49%   |
| SK                  | 1         | 2      | 0.49%   |
| Seagate             | 1         | 1      | 0.49%   |
| Phison              | 1         | 1      | 0.49%   |
| Patriot             | 1         | 1      | 0.49%   |
| Netac               | 1         | 1      | 0.49%   |
| Micron Technology   | 1         | 1      | 0.49%   |
| MicroFrom           | 1         | 2      | 0.49%   |
| Maximus             | 1         | 1      | 0.49%   |
| Kingchuxing         | 1         | 1      | 0.49%   |
| KeepData            | 1         | 1      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 181       | 309    | 54.52%  |
| HDD  | 102       | 178    | 30.72%  |
| NVMe | 49        | 72     | 14.76%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 246       | 487    | 83.39%  |
| NVMe | 49        | 72     | 16.61%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 215       | 383    | 75.44%  |
| 0.51-1.0   | 47        | 68     | 16.49%  |
| 1.01-2.0   | 13        | 24     | 4.56%   |
| 4.01-10.0  | 7         | 9      | 2.46%   |
| 3.01-4.0   | 2         | 2      | 0.7%    |
| 2.01-3.0   | 1         | 1      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 124       | 35.13%  |
| 1-20           | 87        | 24.65%  |
| 251-500        | 62        | 17.56%  |
| 21-50          | 27        | 7.65%   |
| 51-100         | 23        | 6.52%   |
| 501-1000       | 21        | 5.95%   |
| 1001-2000      | 5         | 1.42%   |
| 2001-3000      | 2         | 0.57%   |
| More than 3000 | 1         | 0.28%   |
| Unknown        | 1         | 0.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 313       | 90.72%  |
| 21-50    | 19        | 5.51%   |
| 51-100   | 8         | 2.32%   |
| 251-500  | 3         | 0.87%   |
| 501-1000 | 1         | 0.29%   |
| Unknown  | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB              | 3         | 4      | 4.23%   |
| LITEON CV8-8E128-HP 128GB                    | 2         | 2      | 2.82%   |
| Kingston SV300S37A120G 120GB                 | 2         | 2      | 2.82%   |
| Hitachi HTS545050A7E380 500GB                | 2         | 2      | 2.82%   |
| Hitachi HDT721010SLA360 1TB                  | 2         | 2      | 2.82%   |
| HGST HTS545050A7E380 500GB                   | 2         | 2      | 2.82%   |
| XrayDisk SSD 256GB                           | 1         | 1      | 1.41%   |
| WDC WDS240G2G0B-00EPW0 240GB                 | 1         | 1      | 1.41%   |
| WDC WDS240G2G0A-00JH30 240GB                 | 1         | 2      | 1.41%   |
| WDC WD6400AAKS-22A7B0 640GB                  | 1         | 1      | 1.41%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 1.41%   |
| WDC WD5000AAKX-22ERMA0 500GB                 | 1         | 1      | 1.41%   |
| WDC WD3200BEVT-26A23T0 320GB                 | 1         | 1      | 1.41%   |
| WDC WD2500BEVT-35A23T0 250GB                 | 1         | 1      | 1.41%   |
| WDC WD1600AAJS-00WAA0 160GB                  | 1         | 1      | 1.41%   |
| WDC WD10EZEX-21M2NA0 1TB                     | 1         | 1      | 1.41%   |
| Toshiba MQ01UBD100 1TB                       | 1         | 2      | 1.41%   |
| Toshiba MQ01ACF032 320GB                     | 1         | 1      | 1.41%   |
| Toshiba MK1229GSG 120GB                      | 1         | 1      | 1.41%   |
| Toshiba MK1059GSM 1TB                        | 1         | 1      | 1.41%   |
| SK hynix HFS064G3AMNB-2200A 64GB             | 1         | 1      | 1.41%   |
| Seagate ST6000DM003-2CY186 6TB               | 1         | 1      | 1.41%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 1.41%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 1.41%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 1.41%   |
| Seagate ST3500418AS 500GB                    | 1         | 1      | 1.41%   |
| Seagate ST3500413AS 500GB                    | 1         | 3      | 1.41%   |
| Seagate ST340016A 40GB                       | 1         | 1      | 1.41%   |
| Seagate ST3160215AS 160GB                    | 1         | 1      | 1.41%   |
| Seagate ST31000528AS 1TB                     | 1         | 2      | 1.41%   |
| Seagate ST31000333AS 1TB                     | 1         | 1      | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 1.41%   |
| Seagate ST1000DM010-2EP102 1TB               | 1         | 1      | 1.41%   |
| Seagate ST1000DM003-9YN162 1TB               | 1         | 1      | 1.41%   |
| Seagate ST1000DM003-1ER162 1TB               | 1         | 1      | 1.41%   |
| SanDisk SSD i100 24GB                        | 1         | 1      | 1.41%   |
| Samsung Electronics SSD 840 PRO Series 128GB | 1         | 1      | 1.41%   |
| Samsung Electronics HM320JI 320GB            | 1         | 1      | 1.41%   |
| Samsung Electronics HM160HI 160GB            | 1         | 1      | 1.41%   |
| Samsung Electronics HD252HJ 250GB            | 1         | 1      | 1.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 21     | 20.9%   |
| Hitachi             | 13        | 15     | 19.4%   |
| WDC                 | 9         | 10     | 13.43%  |
| Kingston            | 6         | 13     | 8.96%   |
| Samsung Electronics | 5         | 6      | 7.46%   |
| Toshiba             | 4         | 5      | 5.97%   |
| LITEON              | 2         | 2      | 2.99%   |
| HGST                | 2         | 2      | 2.99%   |
| Fujitsu             | 2         | 2      | 2.99%   |
| XrayDisk            | 1         | 1      | 1.49%   |
| SK hynix            | 1         | 1      | 1.49%   |
| SanDisk             | 1         | 1      | 1.49%   |
| OCZ                 | 1         | 1      | 1.49%   |
| Micron Technology   | 1         | 1      | 1.49%   |
| Maximus             | 1         | 1      | 1.49%   |
| Gigabyte Technology | 1         | 2      | 1.49%   |
| Crucial             | 1         | 1      | 1.49%   |
| China               | 1         | 1      | 1.49%   |
| Apple               | 1         | 1      | 1.49%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 21     | 29.79%  |
| Hitachi             | 13        | 15     | 27.66%  |
| WDC                 | 7         | 7      | 14.89%  |
| Toshiba             | 4         | 5      | 8.51%   |
| Samsung Electronics | 4         | 5      | 8.51%   |
| HGST                | 2         | 2      | 4.26%   |
| Fujitsu             | 2         | 2      | 4.26%   |
| Apple               | 1         | 1      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 58     | 68.75%  |
| SSD  | 19        | 27     | 29.69%  |
| NVMe | 1         | 2      | 1.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model             | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| SanDisk pSSD 32GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 228       | 448    | 74.27%  |
| Malfunc  | 64        | 87     | 20.85%  |
| Detected | 14        | 23     | 4.56%   |
| Failed   | 1         | 1      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 242       | 57.21%  |
| AMD                           | 43        | 10.17%  |
| Samsung Electronics           | 32        | 7.57%   |
| SanDisk                       | 15        | 3.55%   |
| Micron/Crucial Technology     | 11        | 2.6%    |
| ASMedia Technology            | 9         | 2.13%   |
| MAXIO Technology (Hangzhou)   | 8         | 1.89%   |
| Phison Electronics            | 7         | 1.65%   |
| Nvidia                        | 7         | 1.65%   |
| Kingston Technology Company   | 7         | 1.65%   |
| Silicon Motion                | 6         | 1.42%   |
| Toshiba                       | 5         | 1.18%   |
| SK hynix                      | 4         | 0.95%   |
| Shenzhen Longsys Electronics  | 4         | 0.95%   |
| Micron Technology             | 4         | 0.95%   |
| KIOXIA                        | 4         | 0.95%   |
| Marvell Technology Group      | 3         | 0.71%   |
| Hewlett-Packard               | 3         | 0.71%   |
| VIA Technologies              | 1         | 0.24%   |
| Union Memory (Shenzhen)       | 1         | 0.24%   |
| Shenzhen Wodposit Electronics | 1         | 0.24%   |
| Seagate Technology            | 1         | 0.24%   |
| Realtek Semiconductor         | 1         | 0.24%   |
| Netac Technology              | 1         | 0.24%   |
| JMicron Technology            | 1         | 0.24%   |
| Hosin Global Electronics      | 1         | 0.24%   |
| Broadcom / LSI                | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 31        | 6.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 25        | 5.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 17        | 3.57%   |
| Intel Alder Lake-N SATA AHCI Controller                                          | 15        | 3.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 2.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 11        | 2.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 2.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 2.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 10        | 2.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 1.89%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 9         | 1.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 9         | 1.89%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 8         | 1.68%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 8         | 1.68%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 8         | 1.68%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 8         | 1.68%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 6         | 1.26%   |
| Intel SATA Controller [RAID mode]                                                | 6         | 1.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 6         | 1.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 1.26%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                     | 6         | 1.26%   |
| AMD 400 Series Chipset SATA Controller                                           | 6         | 1.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.05%   |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 1.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 1.05%   |
| Sandisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                     | 4         | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 0.84%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 0.84%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 4         | 0.84%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 0.84%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 4         | 0.84%   |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                                   | 3         | 0.63%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                      | 3         | 0.63%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                        | 3         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 262       | 61.65%  |
| NVMe | 105       | 24.71%  |
| IDE  | 35        | 8.24%   |
| RAID | 22        | 5.18%   |
| SAS  | 1         | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 271       | 79.94%  |
| AMD      | 59        | 17.4%   |
| ARM      | 6         | 1.77%   |
| Unknown  | 2         | 0.59%   |
| Broadcom | 1         | 0.29%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel N100                               | 10        | 2.92%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 10        | 2.92%   |
| Intel Celeron N5105 @ 2.00GHz            | 7         | 2.05%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 6         | 1.75%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 4         | 1.17%   |
| Intel Core i5-9500 CPU @ 3.00GHz         | 4         | 1.17%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 4         | 1.17%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 4         | 1.17%   |
| Intel N150                               | 3         | 0.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 3         | 0.88%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz       | 3         | 0.88%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 3         | 0.88%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 3         | 0.88%   |
| Intel Core i3-3240 CPU @ 3.40GHz         | 3         | 0.88%   |
| Intel 13th Gen Core i7-1360P             | 3         | 0.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 3         | 0.88%   |
| ARM Cortex-A72 r0p3                      | 3         | 0.88%   |
| ARM Cortex-A53 r0p4                      | 3         | 0.88%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 3         | 0.88%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 3         | 0.88%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 2         | 0.58%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 2         | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 0.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 0.58%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 2         | 0.58%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 2         | 0.58%   |
| Intel Core i7-3615QM CPU @ 2.30GHz       | 2         | 0.58%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 2         | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 2         | 0.58%   |
| Intel Core i5-7400 CPU @ 3.00GHz         | 2         | 0.58%   |
| Intel Core i5-7300U CPU @ 2.60GHz        | 2         | 0.58%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 2         | 0.58%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 2         | 0.58%   |
| Intel Core i5-5250U CPU @ 1.60GHz        | 2         | 0.58%   |
| Intel Core i5-4570T CPU @ 2.90GHz        | 2         | 0.58%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 2         | 0.58%   |
| Intel Core i5-4200U CPU @ 1.60GHz        | 2         | 0.58%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 2         | 0.58%   |
| Intel Core i5-2430M CPU @ 2.40GHz        | 2         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 68        | 19.94%  |
| Intel Celeron           | 44        | 12.9%   |
| Other                   | 37        | 10.85%  |
| Intel Core i7           | 33        | 9.68%   |
| Intel Core i3           | 29        | 8.5%    |
| Intel Core 2 Duo        | 19        | 5.57%   |
| AMD Ryzen 7             | 14        | 4.11%   |
| Intel Xeon              | 12        | 3.52%   |
| Intel Atom              | 11        | 3.23%   |
| AMD Ryzen 5             | 8         | 2.35%   |
| Intel Pentium           | 7         | 2.05%   |
| AMD GX                  | 7         | 2.05%   |
| ARM Cortex              | 6         | 1.76%   |
| Intel Pentium Silver    | 4         | 1.17%   |
| AMD Ryzen 3             | 4         | 1.17%   |
| Intel Core 2 Quad       | 3         | 0.88%   |
| AMD FX                  | 3         | 0.88%   |
| AMD Athlon              | 3         | 0.88%   |
| AMD A4                  | 3         | 0.88%   |
| Intel Pentium Dual-Core | 2         | 0.59%   |
| Intel Genuine           | 2         | 0.59%   |
| AMD Ryzen 9             | 2         | 0.59%   |
| AMD Opteron             | 2         | 0.59%   |
| Intel Pentium III       | 1         | 0.29%   |
| Intel Pentium Gold      | 1         | 0.29%   |
| Intel Pentium Dual      | 1         | 0.29%   |
| Intel Pentium 4         | 1         | 0.29%   |
| Intel Core i9           | 1         | 0.29%   |
| Intel Core              | 1         | 0.29%   |
| AMD Sempron             | 1         | 0.29%   |
| AMD Ryzen Threadripper  | 1         | 0.29%   |
| AMD Ryzen 7 PRO         | 1         | 0.29%   |
| AMD Ryzen 5 PRO         | 1         | 0.29%   |
| AMD Phenom              | 1         | 0.29%   |
| AMD G                   | 1         | 0.29%   |
| AMD EPYC                | 1         | 0.29%   |
| AMD E2                  | 1         | 0.29%   |
| AMD E1                  | 1         | 0.29%   |
| AMD E                   | 1         | 0.29%   |
| AMD Athlon XP           | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 152       | 44.44%  |
| 2       | 86        | 25.15%  |
| Unknown | 30        | 8.77%   |
| 8       | 27        | 7.89%   |
| 6       | 17        | 4.97%   |
| 16      | 12        | 3.51%   |
| 12      | 8         | 2.34%   |
| 1       | 6         | 1.75%   |
| 14      | 2         | 0.58%   |
| 64      | 1         | 0.29%   |
| 24      | 1         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 319       | 94.1%   |
| Unknown | 12        | 3.54%   |
| 2       | 8         | 2.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 186       | 54.71%  |
| 2       | 123       | 36.18%  |
| Unknown | 31        | 9.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 54        | 15.84%  |
| KabyLake        | 39        | 11.44%  |
| Haswell         | 33        | 9.68%   |
| Silvermont      | 29        | 8.5%    |
| Penryn          | 19        | 5.57%   |
| IvyBridge       | 19        | 5.57%   |
| SandyBridge     | 17        | 4.99%   |
| Skylake         | 16        | 4.69%   |
| Zen+            | 11        | 3.23%   |
| Goldmont plus   | 11        | 3.23%   |
| Core            | 9         | 2.64%   |
| Zen 3           | 8         | 2.35%   |
| Zen 2           | 7         | 2.05%   |
| Jaguar          | 7         | 2.05%   |
| CometLake       | 7         | 2.05%   |
| Broadwell       | 7         | 2.05%   |
| Westmere        | 6         | 1.76%   |
| TigerLake       | 6         | 1.76%   |
| Goldmont        | 6         | 1.76%   |
| Piledriver      | 5         | 1.47%   |
| Puma            | 3         | 0.88%   |
| P6              | 3         | 0.88%   |
| Excavator       | 3         | 0.88%   |
| Bonnell         | 3         | 0.88%   |
| Zen             | 2         | 0.59%   |
| Nehalem         | 2         | 0.59%   |
| Bobcat          | 2         | 0.59%   |
| Steamroller     | 1         | 0.29%   |
| NetBurst        | 1         | 0.29%   |
| K8 Hammer       | 1         | 0.29%   |
| K8 & K10 hybrid | 1         | 0.29%   |
| K6              | 1         | 0.29%   |
| K10             | 1         | 0.29%   |
| IceLake         | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 224       | 63.28%  |
| Nvidia                               | 59        | 16.67%  |
| AMD                                  | 58        | 16.38%  |
| Matrox Electronics Systems           | 8         | 2.26%   |
| ASPEED Technology                    | 4         | 1.13%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 4.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 3.57%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 12        | 3.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 3.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 2.47%   |
| Intel JasperLake [UHD Graphics]                                                          | 9         | 2.47%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 2.47%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 2.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 2.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 1.92%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 7         | 1.92%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 7         | 1.92%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7         | 1.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 1.65%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 6         | 1.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 1.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.37%   |
| Matrox Electronics Systems MGA G200EH                                                    | 4         | 1.1%    |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 4         | 1.1%    |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 4         | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.1%    |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                                  | 4         | 1.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.1%    |
| Intel Alder Lake-N [Intel Graphics]                                                      | 4         | 1.1%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 1.1%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 4         | 1.1%    |
| AMD Rembrandt [Radeon 680M]                                                              | 4         | 1.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.82%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3         | 0.82%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.82%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 3         | 0.82%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 3         | 0.82%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.82%   |
| Intel Broadwell-U GT3 [HD Graphics 6000]                                                 | 3         | 0.82%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 3         | 0.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 188       | 55.13%  |
| 1 x AMD                                  | 44        | 12.9%   |
| 1 x Nvidia                               | 35        | 10.26%  |
| 2 x Intel                                | 16        | 4.69%   |
| Other                                    | 15        | 4.4%    |
| Intel + Nvidia                           | 15        | 4.4%    |
| 1 x Matrox                               | 6         | 1.76%   |
| Intel + AMD                              | 6         | 1.76%   |
| AMD + Nvidia                             | 6         | 1.76%   |
| 1 x ASPEED                               | 4         | 1.17%   |
| 2 x AMD                                  | 2         | 0.59%   |
| Nvidia + Matrox                          | 2         | 0.59%   |
| 2 x Nvidia                               | 1         | 0.29%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 290       | 84.3%   |
| Proprietary | 28        | 8.14%   |
| Unknown     | 26        | 7.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 301       | 87.76%  |
| 1.01-2.0   | 11        | 3.21%   |
| 0.01-0.5   | 11        | 3.21%   |
| 5.01-6.0   | 5         | 1.46%   |
| 0.51-1.0   | 5         | 1.46%   |
| 3.01-4.0   | 4         | 1.17%   |
| 7.01-8.0   | 3         | 0.87%   |
| 2.01-3.0   | 3         | 0.87%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 16        | 11.27%  |
| BenQ                    | 13        | 9.15%   |
| BOE                     | 12        | 8.45%   |
| LG Display              | 11        | 7.75%   |
| Chimei Innolux          | 10        | 7.04%   |
| Dell                    | 9         | 6.34%   |
| Samsung Electronics     | 8         | 5.63%   |
| Goldstar                | 6         | 4.23%   |
| Lenovo                  | 5         | 3.52%   |
| Apple                   | 5         | 3.52%   |
| Sharp                   | 4         | 2.82%   |
| Chi Mei Optoelectronics | 4         | 2.82%   |
| AOC                     | 4         | 2.82%   |
| Acer                    | 4         | 2.82%   |
| Philips                 | 3         | 2.11%   |
| LG Philips              | 3         | 2.11%   |
| Hewlett-Packard         | 3         | 2.11%   |
| ASUSTek Computer        | 3         | 2.11%   |
| Plain Tree Systems      | 2         | 1.41%   |
| PANDA                   | 2         | 1.41%   |
| Lenovo Group Limited    | 2         | 1.41%   |
| Ancor Communications    | 2         | 1.41%   |
| Vestel Elektronik       | 1         | 0.7%    |
| STD                     | 1         | 0.7%    |
| MSI                     | 1         | 0.7%    |
| Microstep               | 1         | 0.7%    |
| Mi                      | 1         | 0.7%    |
| Medion                  | 1         | 0.7%    |
| LGD                     | 1         | 0.7%    |
| Impression              | 1         | 0.7%    |
| HKC                     | 1         | 0.7%    |
| Fujitsu Siemens         | 1         | 0.7%    |
| CHD                     | 1         | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch               | 3         | 2.1%    |
| BOE LCD Monitor BOE0BCA 2256x1504 280x190mm 13.3-inch                 | 3         | 2.1%    |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 3         | 2.1%    |
| AU Optronics LCD Monitor AUO462D 1920x1080 290x170mm 13.2-inch        | 3         | 2.1%    |
| ASUSTek Computer XG49WCR AUS4932 3840x1080 1190x340mm 48.7-inch       | 3         | 2.1%    |
| AOC 2050W AOC2050 1600x900 430x240mm 19.4-inch                        | 3         | 2.1%    |
| Plain Tree Systems LCD Monitor PTS0313 1600x1200 320x240mm 15.7-inch  | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 2         | 1.4%    |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                     | 2         | 1.4%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch         | 2         | 1.4%    |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1         | 0.7%    |
| STD HDMI STD2022 1920x1080 520x310mm 23.8-inch                        | 1         | 0.7%    |
| Sharp LCD Monitor SHP144D 3840x2160 280x160mm 12.7-inch               | 1         | 0.7%    |
| Samsung Electronics T22C300 SAM0AB3 1920x1080 480x270mm 21.7-inch     | 1         | 0.7%    |
| Samsung Electronics S27H85x SAM0E0F 2560x1440 600x340mm 27.2-inch     | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3633 1280x800 330x210mm 15.4-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3152 1024x600 220x130mm 10.1-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch | 1         | 0.7%    |
| Philips PHL 346B1C PHL093E 3440x1440 800x330mm 34.1-inch              | 1         | 0.7%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 1         | 0.7%    |
| Philips 190S PHL083F 1280x1024 380x300mm 19.1-inch                    | 1         | 0.7%    |
| PANDA LCD Monitor NCP004D 1920x1080 340x190mm 15.3-inch               | 1         | 0.7%    |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch               | 1         | 0.7%    |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                       | 1         | 0.7%    |
| Microstep LCD Monitor MSI MAG241C 1920x1080                           | 1         | 0.7%    |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                      | 1         | 0.7%    |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                   | 1         | 0.7%    |
| LGD LCD Monitor 5760x1080                                             | 1         | 0.7%    |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch         | 1         | 0.7%    |
| LG Philips LCD Monitor LPLDB00 1280x800 330x210mm 15.4-inch           | 1         | 0.7%    |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD0773 1920x1200 340x220mm 15.9-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD070B 1920x1080 310x170mm 13.9-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD05D5 1920x1080 340x190mm 15.3-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 1         | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 60        | 43.17%  |
| 1366x768 (WXGA)    | 23        | 16.55%  |
| 1280x800 (WXGA)    | 12        | 8.63%   |
| 3840x2160 (4K)     | 6         | 4.32%   |
| 2560x1440 (QHD)    | 6         | 4.32%   |
| 1600x900 (HD+)     | 5         | 3.6%    |
| 1440x900 (WXGA+)   | 4         | 2.88%   |
| 1280x1024 (SXGA)   | 4         | 2.88%   |
| 3840x1080          | 3         | 2.16%   |
| 2256x1504          | 3         | 2.16%   |
| 3440x1440          | 2         | 1.44%   |
| 1920x1200 (WUXGA)  | 2         | 1.44%   |
| 1600x1200          | 2         | 1.44%   |
| 1024x600           | 2         | 1.44%   |
| 5760x1080          | 1         | 0.72%   |
| 2048x1152          | 1         | 0.72%   |
| 1920x540           | 1         | 0.72%   |
| 1680x1050 (WSXGA+) | 1         | 0.72%   |
| Unknown            | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 41        | 28.87%  |
| 13      | 24        | 16.9%   |
| 24      | 18        | 12.68%  |
| 27      | 10        | 7.04%   |
| 19      | 8         | 5.63%   |
| Unknown | 7         | 4.93%   |
| 23      | 6         | 4.23%   |
| 21      | 6         | 4.23%   |
| 48      | 3         | 2.11%   |
| 18      | 3         | 2.11%   |
| 14      | 3         | 2.11%   |
| 12      | 3         | 2.11%   |
| 34      | 2         | 1.41%   |
| 17      | 2         | 1.41%   |
| 11      | 2         | 1.41%   |
| 42      | 1         | 0.7%    |
| 40      | 1         | 0.7%    |
| 10      | 1         | 0.7%    |
| 9       | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 36.88%  |
| 501-600     | 32        | 22.7%   |
| 201-300     | 24        | 17.02%  |
| 401-500     | 14        | 9.93%   |
| Unknown     | 7         | 4.96%   |
| 351-400     | 5         | 3.55%   |
| 1001-1500   | 3         | 2.13%   |
| 701-800     | 2         | 1.42%   |
| 801-900     | 1         | 0.71%   |
| 901-1000    | 1         | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 94        | 70.15%  |
| 16/10   | 15        | 11.19%  |
| 3/2     | 7         | 5.22%   |
| Unknown | 7         | 5.22%   |
| 5/4     | 4         | 2.99%   |
| 32/9    | 3         | 2.24%   |
| 4/3     | 2         | 1.49%   |
| 21/9    | 2         | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 28        | 20%     |
| 201-250        | 27        | 19.29%  |
| 81-90          | 20        | 14.29%  |
| 301-350        | 10        | 7.14%   |
| 151-200        | 9         | 6.43%   |
| 101-110        | 9         | 6.43%   |
| 71-80          | 7         | 5%      |
| Unknown        | 7         | 5%      |
| 501-1000       | 5         | 3.57%   |
| 111-120        | 4         | 2.86%   |
| 61-70          | 3         | 2.14%   |
| 141-150        | 3         | 2.14%   |
| 51-60          | 2         | 1.43%   |
| 351-500        | 2         | 1.43%   |
| 41-50          | 2         | 1.43%   |
| 251-300        | 1         | 0.71%   |
| 121-130        | 1         | 0.71%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 47        | 34.06%  |
| 101-120       | 37        | 26.81%  |
| 121-160       | 31        | 22.46%  |
| 161-240       | 12        | 8.7%    |
| Unknown       | 7         | 5.07%   |
| More than 240 | 4         | 2.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 190       | 54.91%  |
| 1     | 145       | 41.91%  |
| 2     | 11        | 3.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 205       | 42.62%  |
| Realtek Semiconductor             | 157       | 32.64%  |
| Broadcom                          | 36        | 7.48%   |
| Qualcomm Atheros                  | 32        | 6.65%   |
| TP-Link                           | 8         | 1.66%   |
| MediaTek                          | 6         | 1.25%   |
| Nvidia                            | 5         | 1.04%   |
| Marvell Technology Group          | 5         | 1.04%   |
| D-Link System                     | 4         | 0.83%   |
| Ralink Technology                 | 3         | 0.62%   |
| Xiaomi                            | 2         | 0.42%   |
| Sierra Wireless                   | 2         | 0.42%   |
| Ralink                            | 2         | 0.42%   |
| IMC Networks                      | 2         | 0.42%   |
| Ericsson Business Mobile Networks | 2         | 0.42%   |
| Edimax Technology                 | 2         | 0.42%   |
| Samsung Electronics               | 1         | 0.21%   |
| Qualcomm Atheros Communications   | 1         | 0.21%   |
| NetXen Incorporated               | 1         | 0.21%   |
| Huawei Technologies               | 1         | 0.21%   |
| Google                            | 1         | 0.21%   |
| Emulex                            | 1         | 0.21%   |
| Belkin Components                 | 1         | 0.21%   |
| American Megatrends               | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 122       | 21.33%  |
| Intel Ethernet Controller I226-V                                       | 24        | 4.2%    |
| Intel I211 Gigabit Network Connection                                  | 20        | 3.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 14        | 2.45%   |
| Intel Wi-Fi 6 AX200                                                    | 13        | 2.27%   |
| Intel I350 Gigabit Network Connection                                  | 12        | 2.1%    |
| Intel Ethernet Connection I217-LM                                      | 10        | 1.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 1.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 8         | 1.4%    |
| Intel Wireless 7265                                                    | 8         | 1.4%    |
| Intel I210 Gigabit Network Connection                                  | 8         | 1.4%    |
| Intel Ethernet Controller I225-V                                       | 8         | 1.4%    |
| Intel 82583V Gigabit Network Connection                                | 8         | 1.4%    |
| Intel Wireless 8265 / 8275                                             | 7         | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 1.05%   |
| Intel Wireless 7260                                                    | 6         | 1.05%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 0.87%   |
| Intel 82580 Gigabit Network Connection                                 | 5         | 0.87%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 5         | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4         | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.7%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 4         | 0.7%    |
| Nvidia MCP79 Ethernet                                                  | 4         | 0.7%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 4         | 0.7%    |
| Intel Wireless 3165                                                    | 4         | 0.7%    |
| Intel Wireless 3160                                                    | 4         | 0.7%    |
| Intel Wi-Fi 6 AX201                                                    | 4         | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 4         | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 0.7%    |
| Intel 82574L Gigabit Network Connection                                | 4         | 0.7%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 4         | 0.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 3         | 0.52%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3         | 0.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 0.52%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 3         | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 93        | 46.97%  |
| Realtek Semiconductor           | 27        | 13.64%  |
| Qualcomm Atheros                | 26        | 13.13%  |
| Broadcom                        | 22        | 11.11%  |
| TP-Link                         | 8         | 4.04%   |
| MediaTek                        | 6         | 3.03%   |
| Ralink Technology               | 3         | 1.52%   |
| D-Link System                   | 3         | 1.52%   |
| Sierra Wireless                 | 2         | 1.01%   |
| Ralink                          | 2         | 1.01%   |
| IMC Networks                    | 2         | 1.01%   |
| Edimax Technology               | 2         | 1.01%   |
| Qualcomm Atheros Communications | 1         | 0.51%   |
| Belkin Components               | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 13        | 6.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 8         | 3.94%   |
| Intel Wireless 7265                                                        | 8         | 3.94%   |
| Intel Wireless 8265 / 8275                                                 | 7         | 3.45%   |
| Intel Wireless 7260                                                        | 6         | 2.96%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                  | 5         | 2.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 1.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 4         | 1.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 4         | 1.97%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 4         | 1.97%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]       | 4         | 1.97%   |
| Intel Wireless 3165                                                        | 4         | 1.97%   |
| Intel Wireless 3160                                                        | 4         | 1.97%   |
| Intel Wi-Fi 6 AX201                                                        | 4         | 1.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 4         | 1.97%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter               | 4         | 1.97%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 3         | 1.48%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                | 3         | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 3         | 1.48%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 3         | 1.48%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 3         | 1.48%   |
| Intel WiFi Link 5100                                                       | 3         | 1.48%   |
| Intel Centrino Advanced-N 6235                                             | 3         | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 3         | 1.48%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 3         | 1.48%   |
| Broadcom BCM43228 802.11a/b/g/n                                            | 3         | 1.48%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 3         | 1.48%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 2         | 0.99%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 0.99%   |
| Sierra Wireless EM7345 4G LTE                                              | 2         | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 2         | 0.99%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 2         | 0.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 2         | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 2         | 0.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 2         | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 0.99%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter              | 2         | 0.99%   |
| Intel Wireless 8260                                                        | 2         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 147       | 44.28%  |
| Realtek Semiconductor    | 146       | 43.98%  |
| Broadcom                 | 17        | 5.12%   |
| Qualcomm Atheros         | 6         | 1.81%   |
| Nvidia                   | 5         | 1.51%   |
| Marvell Technology Group | 5         | 1.51%   |
| Xiaomi                   | 2         | 0.6%    |
| Samsung Electronics      | 1         | 0.3%    |
| Emulex                   | 1         | 0.3%    |
| D-Link System            | 1         | 0.3%    |
| American Megatrends      | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 122       | 33.7%   |
| Intel Ethernet Controller I226-V                                       | 24        | 6.63%   |
| Intel I211 Gigabit Network Connection                                  | 20        | 5.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 14        | 3.87%   |
| Intel I350 Gigabit Network Connection                                  | 12        | 3.31%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 2.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 2.76%   |
| Intel I210 Gigabit Network Connection                                  | 8         | 2.21%   |
| Intel Ethernet Controller I225-V                                       | 8         | 2.21%   |
| Intel 82583V Gigabit Network Connection                                | 8         | 2.21%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 1.66%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 1.38%   |
| Intel 82580 Gigabit Network Connection                                 | 5         | 1.38%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 5         | 1.38%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 1.1%    |
| Intel 82574L Gigabit Network Connection                                | 4         | 1.1%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 3         | 0.83%   |
| Intel I210 Gigabit Fiber Network Connection                            | 3         | 0.83%   |
| Intel Ethernet Connection X553 1GbE                                    | 3         | 0.83%   |
| Intel Ethernet Connection (3) I218-V                                   | 3         | 0.83%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 0.83%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 3         | 0.83%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.83%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 3         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.55%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2         | 0.55%   |
| Intel Ethernet Controller I219-V                                       | 2         | 0.55%   |
| Intel Ethernet Connection X553 10 GbE SFP+                             | 2         | 0.55%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.55%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.55%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.55%   |
| Intel Ethernet Connection (2) I218-V                                   | 2         | 0.55%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.55%   |
| Intel 82576 Gigabit Network Connection                                 | 2         | 0.55%   |
| Intel 82575GB Gigabit Network Connection                               | 2         | 0.55%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 2         | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 303       | 62.22%  |
| WiFi     | 177       | 36.34%  |
| Unknown  | 4         | 0.82%   |
| Modem    | 3         | 0.62%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 255       | 76.12%  |
| WiFi     | 79        | 23.58%  |
| Modem    | 1         | 0.3%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 134       | 39.53%  |
| 1     | 84        | 24.78%  |
| 4     | 35        | 10.32%  |
| 3     | 31        | 9.14%   |
| 6     | 17        | 5.01%   |
| 5     | 15        | 4.42%   |
| 0     | 10        | 2.95%   |
| 8     | 5         | 1.47%   |
| 9     | 4         | 1.18%   |
| 16    | 1         | 0.29%   |
| 15    | 1         | 0.29%   |
| 10    | 1         | 0.29%   |
| 7     | 1         | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 331       | 97.35%  |
| Yes  | 9         | 2.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 71        | 50.35%  |
| Realtek Semiconductor           | 13        | 9.22%   |
| Cambridge Silicon Radio         | 11        | 7.8%    |
| Apple                           | 9         | 6.38%   |
| Foxconn / Hon Hai               | 7         | 4.96%   |
| Qualcomm Atheros Communications | 6         | 4.26%   |
| IMC Networks                    | 6         | 4.26%   |
| Broadcom                        | 6         | 4.26%   |
| Hewlett-Packard                 | 4         | 2.84%   |
| Ralink                          | 2         | 1.42%   |
| ASUSTek Computer                | 2         | 1.42%   |
| TP-Link                         | 1         | 0.71%   |
| MediaTek                        | 1         | 0.71%   |
| Lite-On Technology              | 1         | 0.71%   |
| Chicony Electronics             | 1         | 0.71%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 27        | 19.01%  |
| Intel AX200 Bluetooth                                       | 12        | 8.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 11        | 7.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 9         | 6.34%   |
| Intel AX201 Bluetooth                                       | 8         | 5.63%   |
| Realtek Bluetooth Adapter                                   | 6         | 4.23%   |
| Intel AX210 Bluetooth                                       | 5         | 3.52%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 2.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 4         | 2.82%   |
| Apple Bluetooth Host Controller                             | 4         | 2.82%   |
| Realtek Bluetooth 4.2 Adapter                               | 3         | 2.11%   |
| Intel AX211 Bluetooth                                       | 3         | 2.11%   |
| Apple Broadcom Built-in Bluetooth                           | 3         | 2.11%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.41%   |
| Ralink RT3290 Bluetooth                                     | 2         | 1.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 1.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.41%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.41%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                   | 2         | 1.41%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 1.41%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 1.41%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 1.41%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 1         | 0.7%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.7%    |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.7%    |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 0.7%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.7%    |
| MediaTek Bluetooth Adapter                                  | 1         | 0.7%    |
| Lite-On Bluetooth USB Module                                | 1         | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.7%    |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.7%    |
| Intel BE200 Bluetooth                                       | 1         | 0.7%    |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 1         | 0.7%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 0.7%    |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 0.7%    |
| IMC Networks Bluetooth module                               | 1         | 0.7%    |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 0.7%    |
| Chicony Bluetooth (RTL8723BE)                               | 1         | 0.7%    |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 232       | 64.27%  |
| AMD                                          | 62        | 17.17%  |
| Nvidia                                       | 45        | 12.47%  |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.83%   |
| C-Media Electronics                          | 3         | 0.83%   |
| Cambridge Silicon Radio                      | 2         | 0.55%   |
| VIA Technologies                             | 1         | 0.28%   |
| Texas Instruments                            | 1         | 0.28%   |
| Realtek Semiconductor                        | 1         | 0.28%   |
| M-Audio                                      | 1         | 0.28%   |
| Logitech                                     | 1         | 0.28%   |
| Lenovo                                       | 1         | 0.28%   |
| Hewlett-Packard                              | 1         | 0.28%   |
| Generalplus Technology                       | 1         | 0.28%   |
| GEMBIRD                                      | 1         | 0.28%   |
| ESS Technology                               | 1         | 0.28%   |
| Ensoniq                                      | 1         | 0.28%   |
| Dell                                         | 1         | 0.28%   |
| Corsair                                      | 1         | 0.28%   |
| BEHRINGER International                      | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 21        | 5.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 4.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 4.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 16        | 3.82%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 3.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 15        | 3.58%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 15        | 3.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 2.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 2.39%   |
| Intel Jasper Lake HD Audio                                                                        | 9         | 2.15%   |
| Intel 200 Series PCH HD Audio                                                                     | 9         | 2.15%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 9         | 2.15%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 2.15%   |
| AMD FCH Azalia Controller                                                                         | 9         | 2.15%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 1.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 1.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 1.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.43%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 6         | 1.43%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.43%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.43%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 1.43%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 1.19%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.19%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.95%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 4         | 0.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 0.95%   |
| AMD Radeon High Definition Audio Controller                                                       | 4         | 0.95%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 3         | 0.72%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 70        | 19.07%  |
| Kingston            | 54        | 14.71%  |
| Crucial             | 50        | 13.62%  |
| SK hynix            | 41        | 11.17%  |
| Micron Technology   | 39        | 10.63%  |
| Unknown             | 29        | 7.9%    |
| Ramaxel Technology  | 10        | 2.72%   |
| Corsair             | 10        | 2.72%   |
| Unknown             | 10        | 2.72%   |
| Nanya Technology    | 8         | 2.18%   |
| A-DATA Technology   | 7         | 1.91%   |
| G.Skill             | 6         | 1.63%   |
| Elpida              | 5         | 1.36%   |
| Unknown (ABCD)      | 3         | 0.82%   |
| Transcend           | 3         | 0.82%   |
| Apacer              | 3         | 0.82%   |
| Unknown (0x0080)    | 2         | 0.54%   |
| Unknown (0B45)      | 2         | 0.54%   |
| Hewlett-Packard     | 2         | 0.54%   |
| Goldenmars          | 2         | 0.54%   |
| ASint Technology    | 2         | 0.54%   |
| Wodposit            | 1         | 0.27%   |
| Unknown (0x0FBA)    | 1         | 0.27%   |
| Unifosa             | 1         | 0.27%   |
| Toshiba             | 1         | 0.27%   |
| Qimonda             | 1         | 0.27%   |
| Kimtigo             | 1         | 0.27%   |
| Hitachi             | 1         | 0.27%   |
| GOODRAM             | 1         | 0.27%   |
| Essencore           | 1         | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 10        | 2.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 5         | 1.23%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 4         | 0.99%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 3         | 0.74%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                      | 3         | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3200MT/s          | 3         | 0.74%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s          | 3         | 0.74%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s        | 3         | 0.74%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s           | 3         | 0.74%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 3         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3                             | 2         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 2         | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                     | 2         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s   | 2         | 0.49%   |
| Unknown (0B45) RAM WPBC26D416SWM-16G 16GB SODIMM DDR4 2667MT/s | 2         | 0.49%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB DIMM DDR3 1600MT/s           | 2         | 0.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.49%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 0.49%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 2         | 0.49%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 0.49%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.49%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 2         | 0.49%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 0.49%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s         | 2         | 0.49%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 0.49%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 0.49%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s          | 2         | 0.49%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 2         | 0.49%   |
| Micron RAM MTA8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 2         | 0.49%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s           | 2         | 0.49%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 2         | 0.49%   |
| Kingston RAM KVR13LS9/4 4GB SODIMM DDR3 1333MT/s               | 2         | 0.49%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 2         | 0.49%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s         | 2         | 0.49%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 2         | 0.49%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1333MT/s          | 2         | 0.49%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s          | 2         | 0.49%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s          | 2         | 0.49%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s        | 2         | 0.49%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s          | 2         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 127       | 41.1%   |
| DDR4    | 115       | 37.22%  |
| DDR2    | 22        | 7.12%   |
| DDR5    | 19        | 6.15%   |
| LPDDR4  | 8         | 2.59%   |
| LPDDR3  | 5         | 1.62%   |
| SDRAM   | 4         | 1.29%   |
| Unknown | 4         | 1.29%   |
| LPDDR5  | 3         | 0.97%   |
| DDR     | 2         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 166       | 53.9%   |
| DIMM         | 127       | 41.23%  |
| Row Of Chips | 12        | 3.9%    |
| Chip         | 2         | 0.65%   |
| FB-DIMM      | 1         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 120       | 34.99%  |
| 4096  | 97        | 28.28%  |
| 16384 | 58        | 16.91%  |
| 2048  | 45        | 13.12%  |
| 32768 | 11        | 3.21%   |
| 1024  | 9         | 2.62%   |
| 49152 | 1         | 0.29%   |
| 512   | 1         | 0.29%   |
| 256   | 1         | 0.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 93        | 28.01%  |
| 3200    | 47        | 14.16%  |
| 2400    | 37        | 11.14%  |
| 1333    | 30        | 9.04%   |
| 2667    | 23        | 6.93%   |
| 4800    | 15        | 4.52%   |
| 2133    | 15        | 4.52%   |
| 667     | 11        | 3.31%   |
| 800     | 9         | 2.71%   |
| Unknown | 6         | 1.81%   |
| 1334    | 5         | 1.51%   |
| 1067    | 5         | 1.51%   |
| 5600    | 4         | 1.2%    |
| 1867    | 4         | 1.2%    |
| 1866    | 4         | 1.2%    |
| 1066    | 4         | 1.2%    |
| 6400    | 3         | 0.9%    |
| 2666    | 3         | 0.9%    |
| 3600    | 2         | 0.6%    |
| 975     | 2         | 0.6%    |
| 7467    | 1         | 0.3%    |
| 4267    | 1         | 0.3%    |
| 4266    | 1         | 0.3%    |
| 3733    | 1         | 0.3%    |
| 3066    | 1         | 0.3%    |
| 2048    | 1         | 0.3%    |
| 1332    | 1         | 0.3%    |
| 1033    | 1         | 0.3%    |
| 400     | 1         | 0.3%    |
| 333     | 1         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 50%     |
| Brother HL-L2340D series                                                                                          | 1         | 50%     |

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
| Chicony Electronics                    | 19        | 20.65%  |
| Sunplus Innovation Technology          | 10        | 10.87%  |
| Realtek Semiconductor                  | 10        | 10.87%  |
| IMC Networks                           | 8         | 8.7%    |
| Bison Electronics                      | 7         | 7.61%   |
| Suyin                                  | 6         | 6.52%   |
| Quanta                                 | 6         | 6.52%   |
| Microdia                               | 5         | 5.43%   |
| Alcor Micro                            | 3         | 3.26%   |
| Syntek                                 | 2         | 2.17%   |
| Luxvisions Innotech Limited            | 2         | 2.17%   |
| Logitech                               | 2         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.17%   |
| Z-Star Microelectronics                | 1         | 1.09%   |
| USB Camera                             | 1         | 1.09%   |
| Supreme Electronics                    | 1         | 1.09%   |
| Silicon Motion                         | 1         | 1.09%   |
| Ricoh                                  | 1         | 1.09%   |
| OmniVision Technologies                | 1         | 1.09%   |
| Lite-On Technology                     | 1         | 1.09%   |
| Importek                               | 1         | 1.09%   |
| HD WEBCAM                              | 1         | 1.09%   |
| Apple                                  | 1         | 1.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD             | 6         | 6.52%   |
| Chicony Integrated Camera                | 6         | 6.52%   |
| Realtek Laptop Camera                    | 3         | 3.26%   |
| Quanta HP TrueVision HD Camera           | 3         | 3.26%   |
| IMC Networks Realtek PC Camera           | 3         | 3.26%   |
| Bison Integrated Camera                  | 3         | 3.26%   |
| Realtek USB Camera                       | 2         | 2.17%   |
| IMC Networks Integrated Camera           | 2         | 2.17%   |
| Chicony Webcam                           | 2         | 2.17%   |
| Chicony HD Webcam                        | 2         | 2.17%   |
| Z-Star Vega USB 2.0 Camera               | 1         | 1.09%   |
| USB Camera USB Camera                    | 1         | 1.09%   |
| Syntek Lenovo EasyCamera                 | 1         | 1.09%   |
| Syntek EasyCamera                        | 1         | 1.09%   |
| Suyin Laptop_Integrated_Webcam_HD        | 1         | 1.09%   |
| Suyin Integrated_Webcam_HD               | 1         | 1.09%   |
| Suyin HP Webcam-50                       | 1         | 1.09%   |
| Suyin HP Webcam-101                      | 1         | 1.09%   |
| Suyin HP webcam [dv6-1190en]             | 1         | 1.09%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 1.09%   |
| Supreme Realtek PC Camera                | 1         | 1.09%   |
| Sunplus Integrated Camera                | 1         | 1.09%   |
| Sunplus HP HD Webcam [Fixed]             | 1         | 1.09%   |
| Sunplus HD WebCam                        | 1         | 1.09%   |
| Sunplus Asus Webcam                      | 1         | 1.09%   |
| Silicon Motion Realtek USB 2.0 PC Camera | 1         | 1.09%   |
| Ricoh Integrated Webcam                  | 1         | 1.09%   |
| Realtek LG Camera                        | 1         | 1.09%   |
| Realtek Integrated_Webcam_HD             | 1         | 1.09%   |
| Realtek Integrated_Webcam_FHD            | 1         | 1.09%   |
| Realtek HD WebCam                        | 1         | 1.09%   |
| Realtek Acer 640 x 480 laptop camera     | 1         | 1.09%   |
| Quanta Realtek DMFT RGB                  | 1         | 1.09%   |
| Quanta HP Universal Camera               | 1         | 1.09%   |
| Quanta HP True Vision 5MP Camera         | 1         | 1.09%   |
| OmniVision Monitor Webcam                | 1         | 1.09%   |
| Microdia USB 2.0 Camera                  | 1         | 1.09%   |
| Microdia Sonix USB 2.0 Camera            | 1         | 1.09%   |
| Microdia Integrated_Webcam_HD            | 1         | 1.09%   |
| Microdia Integrated Webcam               | 1         | 1.09%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 42.86%  |
| Synaptics                  | 3         | 14.29%  |
| STMicroelectronics         | 2         | 9.52%   |
| Shenzhen Goodix Technology | 2         | 9.52%   |
| Elan Microelectronics      | 2         | 9.52%   |
| Upek                       | 1         | 4.76%   |
| Fingerprint Cards          | 1         | 4.76%   |
| AuthenTec                  | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                                  | 2         | 9.52%   |
| Validity Sensors VFS101 Fingerprint Reader               | 2         | 9.52%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 9.52%   |
| STMicroelectronics Fingerprint Reader                    | 2         | 9.52%   |
| Elan Fingerprint Sensor                                  | 2         | 9.52%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 4.76%   |
| Validity Sensors Synaptics WBDI                          | 1         | 4.76%   |
| Validity Sensors Fingerprint scanner                     | 1         | 4.76%   |
| Upek TCS5B Fingerprint sensor                            | 1         | 4.76%   |
| Synaptics WBDI Fingerprint Reader USB 086                | 1         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 4.76%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4.76%   |
| Shenzhen Goodix  Fingerprint Device                      | 1         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 4.76%   |
| Fingerprint Cards FPC Fingerprint Reader                 | 1         | 4.76%   |
| AuthenTec AES1660 Fingerprint Sensor                     | 1         | 4.76%   |

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
| 1     | 160       | 45.2%   |
| 0     | 91        | 25.71%  |
| 2     | 62        | 17.51%  |
| 3     | 29        | 8.19%   |
| 4     | 8         | 2.26%   |
| 5     | 3         | 0.85%   |
| 6     | 1         | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 200       | 53.05%  |
| Net/wireless             | 57        | 15.12%  |
| Bluetooth                | 48        | 12.73%  |
| Card reader              | 22        | 5.84%   |
| Fingerprint reader       | 17        | 4.51%   |
| Firewire controller      | 8         | 2.12%   |
| Network                  | 7         | 1.86%   |
| Graphics card            | 7         | 1.86%   |
| Sound                    | 6         | 1.59%   |
| Net/ethernet             | 2         | 0.53%   |
| Storage/ata              | 1         | 0.27%   |
| Storage                  | 1         | 0.27%   |
| Dvb card                 | 1         | 0.27%   |

