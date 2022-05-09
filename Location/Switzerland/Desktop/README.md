BSD in Switzerland - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for BSD in Switzerland.

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

Total: 147

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| PC Engines    | APU2                        | [a2b68686f0](https://bsd-hardware.info/?probe=a2b68686f0) | Apr 27, 2022 |
| Dell          | 0TP406                      | [775061bc83](https://bsd-hardware.info/?probe=775061bc83) | Apr 25, 2022 |
| Biostar       | H61MHV2                     | [7d9806d719](https://bsd-hardware.info/?probe=7d9806d719) | Apr 21, 2022 |
| Gigabyte      | 990FXA-UD3                  | [378021707a](https://bsd-hardware.info/?probe=378021707a) | Apr 17, 2022 |
| PC Engines    | apu4                        | [62df504364](https://bsd-hardware.info/?probe=62df504364) | Apr 09, 2022 |
| Dell          | 0TP406                      | [9a29305ef1](https://bsd-hardware.info/?probe=9a29305ef1) | Apr 06, 2022 |
| Unknown       | Unknown                     | [b6b1ec9dc1](https://bsd-hardware.info/?probe=b6b1ec9dc1) | Mar 30, 2022 |
| ASRockRack    | X570D4U-2L2T                | [7e042aa70d](https://bsd-hardware.info/?probe=7e042aa70d) | Mar 25, 2022 |
| Unknown       | Unknown                     | [abb17bcb42](https://bsd-hardware.info/?probe=abb17bcb42) | Mar 21, 2022 |
| Unknown       | Unknown                     | [1d97ecbc95](https://bsd-hardware.info/?probe=1d97ecbc95) | Mar 20, 2022 |
| Unknown       | Unknown                     | [e169892276](https://bsd-hardware.info/?probe=e169892276) | Mar 18, 2022 |
| Dell          | 0X4N41 A01                  | [456b55de38](https://bsd-hardware.info/?probe=456b55de38) | Mar 17, 2022 |
| Unknown       | Unknown                     | [1ed23967fd](https://bsd-hardware.info/?probe=1ed23967fd) | Mar 17, 2022 |
| Dell          | 0X4N41 A01                  | [4d7d8fd92b](https://bsd-hardware.info/?probe=4d7d8fd92b) | Mar 17, 2022 |
| Unknown       | Unknown                     | [95154c4898](https://bsd-hardware.info/?probe=95154c4898) | Mar 16, 2022 |
| PC Engines    | APU2                        | [6e5badb880](https://bsd-hardware.info/?probe=6e5badb880) | Mar 04, 2022 |
| Intel         | Q3XXG4-P V1.0               | [7da5182091](https://bsd-hardware.info/?probe=7da5182091) | Feb 27, 2022 |
| PC Engines    | APU2                        | [40ba1b35da](https://bsd-hardware.info/?probe=40ba1b35da) | Feb 24, 2022 |
| PC Engines    | APU2                        | [3ac0b6f7c4](https://bsd-hardware.info/?probe=3ac0b6f7c4) | Feb 21, 2022 |
| Dell          | 0X4N41 A01                  | [fea17bcf92](https://bsd-hardware.info/?probe=fea17bcf92) | Feb 19, 2022 |
| PC Engines    | APU2                        | [547be2fb61](https://bsd-hardware.info/?probe=547be2fb61) | Feb 19, 2022 |
| Dell          | 0X4N41 A01                  | [a62eea5e4e](https://bsd-hardware.info/?probe=a62eea5e4e) | Feb 11, 2022 |
| Dell          | 0X4N41 A01                  | [55b7348a0c](https://bsd-hardware.info/?probe=55b7348a0c) | Feb 11, 2022 |
| PC Engines    | APU2                        | [566948b2c1](https://bsd-hardware.info/?probe=566948b2c1) | Feb 09, 2022 |
| Acer          | Aspire XC-885 V:1.1         | [76fadb9527](https://bsd-hardware.info/?probe=76fadb9527) | Feb 09, 2022 |
| HP            | 0B54h D                     | [c2b43efb8f](https://bsd-hardware.info/?probe=c2b43efb8f) | Feb 07, 2022 |
| HP            | ProLiant ML350p Gen8        | [7987f643d7](https://bsd-hardware.info/?probe=7987f643d7) | Feb 06, 2022 |
| HP            | 0B54h D                     | [1878f5822c](https://bsd-hardware.info/?probe=1878f5822c) | Feb 06, 2022 |
| HP            | ProLiant ML350p Gen8        | [b9e0021bfb](https://bsd-hardware.info/?probe=b9e0021bfb) | Feb 06, 2022 |
| Unknown       | Unknown                     | [000331f38e](https://bsd-hardware.info/?probe=000331f38e) | Jan 31, 2022 |
| Unknown       | Unknown                     | [df6e313377](https://bsd-hardware.info/?probe=df6e313377) | Jan 31, 2022 |
| Unknown       | Unknown                     | [74b8fc0269](https://bsd-hardware.info/?probe=74b8fc0269) | Jan 30, 2022 |
| PC Engines    | apu4                        | [4f6a1c9c9a](https://bsd-hardware.info/?probe=4f6a1c9c9a) | Jan 25, 2022 |
| Unknown       | Unknown                     | [b572e30460](https://bsd-hardware.info/?probe=b572e30460) | Jan 19, 2022 |
| HP            | 3396                        | [236ed20a86](https://bsd-hardware.info/?probe=236ed20a86) | Jan 11, 2022 |
| Unknown       | Unknown                     | [e38915ac8c](https://bsd-hardware.info/?probe=e38915ac8c) | Jan 08, 2022 |
| Unknown       | Unknown                     | [0a82e095ee](https://bsd-hardware.info/?probe=0a82e095ee) | Jan 08, 2022 |
| Unknown       | Unknown                     | [9c67eb6ecd](https://bsd-hardware.info/?probe=9c67eb6ecd) | Dec 30, 2021 |
| Gigabyte      | H97N-WIFI                   | [3ccd5eace4](https://bsd-hardware.info/?probe=3ccd5eace4) | Dec 15, 2021 |
| ASRock        | B550 Taichi                 | [ed2fd72332](https://bsd-hardware.info/?probe=ed2fd72332) | Dec 14, 2021 |
| PC Engines    | apu4                        | [a06765ebb1](https://bsd-hardware.info/?probe=a06765ebb1) | Dec 09, 2021 |
| Dell          | 0X4N41 A01                  | [015319ce8c](https://bsd-hardware.info/?probe=015319ce8c) | Dec 08, 2021 |
| Supermicro    | X11SDW-4C-TP13F             | [f424260bfa](https://bsd-hardware.info/?probe=f424260bfa) | Dec 03, 2021 |
| ASRockRack    | X570D4U-2L2T                | [b35a4b529c](https://bsd-hardware.info/?probe=b35a4b529c) | Nov 22, 2021 |
| Intel         | HURONRIVER                  | [741fd0e126](https://bsd-hardware.info/?probe=741fd0e126) | Nov 13, 2021 |
| Dell          | 0X4N41 A01                  | [d08d7fde4a](https://bsd-hardware.info/?probe=d08d7fde4a) | Nov 13, 2021 |
| PC Engines    | apu4                        | [64cad2ccf6](https://bsd-hardware.info/?probe=64cad2ccf6) | Nov 08, 2021 |
| HP            | 3397                        | [3434fa8427](https://bsd-hardware.info/?probe=3434fa8427) | Nov 07, 2021 |
| HP            | 3397                        | [155eceb394](https://bsd-hardware.info/?probe=155eceb394) | Nov 07, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [15d56aee58](https://bsd-hardware.info/?probe=15d56aee58) | Oct 21, 2021 |
| Apple         | Mac-F221BEC8                | [cb2cc35e6c](https://bsd-hardware.info/?probe=cb2cc35e6c) | Oct 19, 2021 |
| Apple         | Mac-F221BEC8                | [4e91fa71b2](https://bsd-hardware.info/?probe=4e91fa71b2) | Oct 19, 2021 |
| Unknown       | Unknown                     | [734ec7d9fc](https://bsd-hardware.info/?probe=734ec7d9fc) | Oct 18, 2021 |
| Unknown       | Unknown                     | [4ecab88e78](https://bsd-hardware.info/?probe=4ecab88e78) | Oct 17, 2021 |
| ASRock        | A320M-ITX                   | [06a8c0d2ac](https://bsd-hardware.info/?probe=06a8c0d2ac) | Oct 08, 2021 |
| ASRock        | B550 Taichi                 | [7599775c70](https://bsd-hardware.info/?probe=7599775c70) | Oct 08, 2021 |
| PC Engines    | APU2                        | [7a21594bf7](https://bsd-hardware.info/?probe=7a21594bf7) | Oct 08, 2021 |
| PC Engines    | apu6                        | [a184c5f1b2](https://bsd-hardware.info/?probe=a184c5f1b2) | Oct 06, 2021 |
| PC Engines    | APU2                        | [d36e631149](https://bsd-hardware.info/?probe=d36e631149) | Oct 03, 2021 |
| Gigabyte      | B450M DS3H-CF               | [1038e3314d](https://bsd-hardware.info/?probe=1038e3314d) | Sep 21, 2021 |
| PC Engines    | apu4                        | [9557835b54](https://bsd-hardware.info/?probe=9557835b54) | Sep 09, 2021 |
| Gigabyte      | BRi3(H)-10110               | [9aa3540749](https://bsd-hardware.info/?probe=9aa3540749) | Sep 09, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [a78cc6a11b](https://bsd-hardware.info/?probe=a78cc6a11b) | Sep 04, 2021 |
| ASRock        | A320M-ITX                   | [051ca0708f](https://bsd-hardware.info/?probe=051ca0708f) | Sep 03, 2021 |
| ASRock        | A320M-ITX                   | [23bccfa11c](https://bsd-hardware.info/?probe=23bccfa11c) | Sep 01, 2021 |
| ASUSTek       | P8Z77-V                     | [eb4948e855](https://bsd-hardware.info/?probe=eb4948e855) | Aug 31, 2021 |
| Unknown       | Unknown                     | [114a632ab4](https://bsd-hardware.info/?probe=114a632ab4) | Aug 30, 2021 |
| ASRock        | A320M-ITX                   | [b0339f73bc](https://bsd-hardware.info/?probe=b0339f73bc) | Aug 28, 2021 |
| Unknown       | Unknown                     | [5bb434cb3f](https://bsd-hardware.info/?probe=5bb434cb3f) | Aug 27, 2021 |
| ASRock        | A320M-ITX                   | [c28bfd784d](https://bsd-hardware.info/?probe=c28bfd784d) | Aug 27, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [47284b4819](https://bsd-hardware.info/?probe=47284b4819) | Aug 27, 2021 |
| PC Engines    | apu4                        | [9f5ec6c23f](https://bsd-hardware.info/?probe=9f5ec6c23f) | Aug 23, 2021 |
| PC Engines    | apu4                        | [514a974f68](https://bsd-hardware.info/?probe=514a974f68) | Aug 10, 2021 |
| PC Engines    | APU2                        | [823fdc32f0](https://bsd-hardware.info/?probe=823fdc32f0) | Aug 09, 2021 |
| ASRock        | J4105-ITX                   | [1ac35fcecf](https://bsd-hardware.info/?probe=1ac35fcecf) | Aug 08, 2021 |
| Shuttle       | DS10U                       | [fa151322fc](https://bsd-hardware.info/?probe=fa151322fc) | Aug 03, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [772a9416ab](https://bsd-hardware.info/?probe=772a9416ab) | Aug 01, 2021 |
| PC Engines    | APU2                        | [4c2b89d2e6](https://bsd-hardware.info/?probe=4c2b89d2e6) | Jul 31, 2021 |
| Dell          | 0X4N41 A01                  | [a528966ab8](https://bsd-hardware.info/?probe=a528966ab8) | Jul 30, 2021 |
| Dell          | 0X4N41 A01                  | [51136572fc](https://bsd-hardware.info/?probe=51136572fc) | Jul 29, 2021 |
| ASRockRack    | X470D4U2-2T                 | [8a2efd6b5b](https://bsd-hardware.info/?probe=8a2efd6b5b) | Jul 25, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [fea747e9eb](https://bsd-hardware.info/?probe=fea747e9eb) | Jul 25, 2021 |
| Dell          | 0X4N41 A01                  | [f29fab4508](https://bsd-hardware.info/?probe=f29fab4508) | Jul 23, 2021 |
| Dell          | 0X4N41 A01                  | [b7c3a2b2e4](https://bsd-hardware.info/?probe=b7c3a2b2e4) | Jul 23, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [89938d9a3a](https://bsd-hardware.info/?probe=89938d9a3a) | Jul 20, 2021 |
| Supermicro    | X9SCL/X9SCMA                | [c2721a852b](https://bsd-hardware.info/?probe=c2721a852b) | Jul 18, 2021 |
| Supermicro    | PDSML+                      | [f8a9ca42d6](https://bsd-hardware.info/?probe=f8a9ca42d6) | Jul 11, 2021 |
| PC Engines    | APU2                        | [fe77a10950](https://bsd-hardware.info/?probe=fe77a10950) | Jul 08, 2021 |
| Protectli     | FW6                         | [c28479f624](https://bsd-hardware.info/?probe=c28479f624) | Jun 20, 2021 |
| ASRockRack    | X470D4U2-2T                 | [6efb43e299](https://bsd-hardware.info/?probe=6efb43e299) | Jun 18, 2021 |
| Protectli     | FW6                         | [36d53d9465](https://bsd-hardware.info/?probe=36d53d9465) | Jun 17, 2021 |
| Protectli     | FW6                         | [9579e972f2](https://bsd-hardware.info/?probe=9579e972f2) | Jun 13, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [15ba8e73e1](https://bsd-hardware.info/?probe=15ba8e73e1) | Jun 09, 2021 |
| PC Engines    | apu4                        | [7ffaed1505](https://bsd-hardware.info/?probe=7ffaed1505) | Jun 06, 2021 |
| HPE           | ProLiant MicroServer Gen... | [74f5dbcf1b](https://bsd-hardware.info/?probe=74f5dbcf1b) | Jun 01, 2021 |
| PC Engines    | apu4                        | [aad3e6a309](https://bsd-hardware.info/?probe=aad3e6a309) | May 28, 2021 |
| Shuttle       | DS10U                       | [bd8bea4a6a](https://bsd-hardware.info/?probe=bd8bea4a6a) | May 27, 2021 |
| ASRock        | X99M Extreme4               | [ef131c774d](https://bsd-hardware.info/?probe=ef131c774d) | May 02, 2021 |
| Lenovo        | 318E NOK                    | [115f2c7b35](https://bsd-hardware.info/?probe=115f2c7b35) | Apr 27, 2021 |
| Unknown       | Unknown                     | [44e10ac014](https://bsd-hardware.info/?probe=44e10ac014) | Apr 19, 2021 |
| PC Engines    | APU2                        | [8b425e6086](https://bsd-hardware.info/?probe=8b425e6086) | Apr 08, 2021 |
| PC Engines    | apu2                        | [f261049b51](https://bsd-hardware.info/?probe=f261049b51) | Apr 07, 2021 |
| Unknown       | Unknown                     | [09e3c55edf](https://bsd-hardware.info/?probe=09e3c55edf) | Mar 26, 2021 |
| PC Engines    | APU2                        | [6204024271](https://bsd-hardware.info/?probe=6204024271) | Mar 24, 2021 |
| PC Engines    | APU2                        | [b39d8ba487](https://bsd-hardware.info/?probe=b39d8ba487) | Mar 24, 2021 |
| HPE           | ProLiant MicroServer Gen... | [40ec36ad78](https://bsd-hardware.info/?probe=40ec36ad78) | Mar 18, 2021 |
| PC Engines    | apu4                        | [e10b5c92e9](https://bsd-hardware.info/?probe=e10b5c92e9) | Mar 16, 2021 |
| Unknown       | Unknown                     | [36f81afd88](https://bsd-hardware.info/?probe=36f81afd88) | Mar 13, 2021 |
| PC Engines    | apu4                        | [6d42054ec5](https://bsd-hardware.info/?probe=6d42054ec5) | Mar 13, 2021 |
| PC Engines    | apu4                        | [9268ee6857](https://bsd-hardware.info/?probe=9268ee6857) | Mar 13, 2021 |
| HPE           | ProLiant MicroServer Gen... | [2c0b0d8eb0](https://bsd-hardware.info/?probe=2c0b0d8eb0) | Mar 09, 2021 |
| BESSTAR Te... | IB9                         | [6d455b5e28](https://bsd-hardware.info/?probe=6d455b5e28) | Mar 08, 2021 |
| PC Engines    | APU3                        | [cf397191d2](https://bsd-hardware.info/?probe=cf397191d2) | Mar 04, 2021 |
| HP            | 0B54h D                     | [eb8428d5f3](https://bsd-hardware.info/?probe=eb8428d5f3) | Mar 01, 2021 |
| PC Engines    | apu2                        | [2ac1695054](https://bsd-hardware.info/?probe=2ac1695054) | Feb 28, 2021 |
| Unknown       | Unknown                     | [b6c6031b46](https://bsd-hardware.info/?probe=b6c6031b46) | Feb 27, 2021 |
| ASUSTek       | Z170-K                      | [aa525de283](https://bsd-hardware.info/?probe=aa525de283) | Feb 13, 2021 |
| Unknown       | Unknown                     | [ad3998234a](https://bsd-hardware.info/?probe=ad3998234a) | Feb 11, 2021 |
| PC Engines    | apu2                        | [836a3035f1](https://bsd-hardware.info/?probe=836a3035f1) | Feb 06, 2021 |
| PC Engines    | apu2                        | [22b310774a](https://bsd-hardware.info/?probe=22b310774a) | Feb 06, 2021 |
| PC Engines    | apu2                        | [290957c97b](https://bsd-hardware.info/?probe=290957c97b) | Feb 04, 2021 |
| PC Engines    | apu2                        | [4985fa31bf](https://bsd-hardware.info/?probe=4985fa31bf) | Feb 03, 2021 |
| PC Engines    | apu4                        | [c740c17c50](https://bsd-hardware.info/?probe=c740c17c50) | Feb 01, 2021 |
| YANYU         | D19SL_B                     | [d16128eed9](https://bsd-hardware.info/?probe=d16128eed9) | Jan 28, 2021 |
| Unknown       | Unknown                     | [d2895512c0](https://bsd-hardware.info/?probe=d2895512c0) | Jan 27, 2021 |
| Unknown       | Unknown                     | [b936d5a273](https://bsd-hardware.info/?probe=b936d5a273) | Jan 27, 2021 |
| PC Engines    | apu2                        | [3448eacd29](https://bsd-hardware.info/?probe=3448eacd29) | Jan 24, 2021 |
| PC Engines    | apu2                        | [72e0243d73](https://bsd-hardware.info/?probe=72e0243d73) | Jan 23, 2021 |
| Sun           | SUNW,Sun-Blade-1500         | [647618a0ca](https://bsd-hardware.info/?probe=647618a0ca) | Jan 22, 2021 |
| PC Engines    | apu2                        | [c6c764813a](https://bsd-hardware.info/?probe=c6c764813a) | Jan 21, 2021 |
| PC Engines    | apu2                        | [bf1b93e96d](https://bsd-hardware.info/?probe=bf1b93e96d) | Jan 21, 2021 |
| ADI Engine... | RCC                         | [199da8eab6](https://bsd-hardware.info/?probe=199da8eab6) | Jan 20, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [c107103d53](https://bsd-hardware.info/?probe=c107103d53) | Jan 19, 2021 |
| Sun           | SUNW,Sun-Blade-100          | [299c76eb85](https://bsd-hardware.info/?probe=299c76eb85) | Jan 18, 2021 |
| HP            | 1495                        | [2606547041](https://bsd-hardware.info/?probe=2606547041) | Dec 22, 2020 |
| HP            | 0B54h D                     | [de35ebc178](https://bsd-hardware.info/?probe=de35ebc178) | Dec 04, 2020 |
| PC Engines    | apu2                        | [e6ee8a14d5](https://bsd-hardware.info/?probe=e6ee8a14d5) | Oct 20, 2020 |
| PC Engines    | apu4                        | [e4cd6d0b48](https://bsd-hardware.info/?probe=e4cd6d0b48) | Oct 19, 2020 |
| HP            | ProLiant MicroServer Gen... | [94a279c84d](https://bsd-hardware.info/?probe=94a279c84d) | Sep 03, 2020 |
| HP            | 0B54h D                     | [840b12f1f9](https://bsd-hardware.info/?probe=840b12f1f9) | Aug 09, 2020 |
| HP            | 0B54h D                     | [c4454eaa39](https://bsd-hardware.info/?probe=c4454eaa39) | Aug 09, 2020 |
| Gigabyte      | H67A-UD3H-B3                | [aa29eb9c75](https://bsd-hardware.info/?probe=aa29eb9c75) | Aug 01, 2020 |
| PC Engines    | apu4                        | [52c611855b](https://bsd-hardware.info/?probe=52c611855b) | Jul 12, 2020 |
| HP            | 158A                        | [dfff5dd2f9](https://bsd-hardware.info/?probe=dfff5dd2f9) | Jun 09, 2020 |
| Unknown       | Unknown                     | [80a1eda96f](https://bsd-hardware.info/?probe=80a1eda96f) | May 28, 2020 |
| ASUSTek       | H81M-C                      | [d65f5372ec](https://bsd-hardware.info/?probe=d65f5372ec) | May 26, 2020 |
| HP            | 0B54h D                     | [b43db1d84e](https://bsd-hardware.info/?probe=b43db1d84e) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| OPNsense 21.7.3      | 7        | 6.36%   |
| OPNsense 21.7.1      | 7        | 6.36%   |
| OPNsense 21.1.6      | 7        | 6.36%   |
| OPNsense 20.7.8      | 7        | 6.36%   |
| OPNsense 21.7.6      | 5        | 4.55%   |
| OPNsense 22.1.3      | 4        | 3.64%   |
| OPNsense 21.7.7      | 4        | 3.64%   |
| OPNsense 21.1.3      | 4        | 3.64%   |
| OPNsense 21.1        | 4        | 3.64%   |
| OpenBSD 6.8          | 4        | 3.64%   |
| OPNsense 22.1.1      | 3        | 2.73%   |
| OPNsense 21.7        | 3        | 2.73%   |
| OPNsense 21.1.8      | 3        | 2.73%   |
| OPNsense 21.1.2      | 3        | 2.73%   |
| OPNsense 22.1.6      | 2        | 1.82%   |
| OPNsense 22.1.4      | 2        | 1.82%   |
| OPNsense 22.1.2      | 2        | 1.82%   |
| OPNsense 22.1        | 2        | 1.82%   |
| OPNsense 21.7.5      | 2        | 1.82%   |
| OPNsense 21.7.4      | 2        | 1.82%   |
| OPNsense 21.1.9      | 2        | 1.82%   |
| OPNsense 21.1.7      | 2        | 1.82%   |
| OPNsense 21.1.5      | 2        | 1.82%   |
| OPNsense 21.1.4      | 2        | 1.82%   |
| OpenBSD 7.0          | 2        | 1.82%   |
| OpenBSD 6.7          | 2        | 1.82%   |
| FreeBSD 13.0-p7      | 2        | 1.82%   |
| FreeBSD 12.2-p2      | 2        | 1.82%   |
| FreeBSD 12.1-STABLE  | 2        | 1.82%   |
| FreeBSD 12.1-p5      | 2        | 1.82%   |
| TrueNAS 12.2-p6      | 1        | 0.91%   |
| TrueNAS 12.2-p12     | 1        | 0.91%   |
| OPNsense 20.7.5      | 1        | 0.91%   |
| OpenBSD 6.9          | 1        | 0.91%   |
| helloSystem 0.6.0    | 1        | 0.91%   |
| helloSystem 0.4.0    | 1        | 0.91%   |
| GhostBSD 20.04.02    | 1        | 0.91%   |
| FreeBSD 14.0-CURRENT | 1        | 0.91%   |
| FreeBSD 13.0-p5      | 1        | 0.91%   |
| FreeBSD 12.2-p4      | 1        | 0.91%   |
| FreeBSD 12.2-p1      | 1        | 0.91%   |
| FreeBSD 12.2         | 1        | 0.91%   |
| FreeBSD 12.1-p8      | 1        | 0.91%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 60       | 71.43%  |
| FreeBSD     | 10       | 11.9%   |
| OpenBSD     | 9        | 10.71%  |
| TrueNAS     | 2        | 2.38%   |
| helloSystem | 2        | 2.38%   |
| GhostBSD    | 1        | 1.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 81       | 96.43%  |
| sparc64 | 2        | 2.38%   |
| i386    | 1        | 1.19%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 73       | 85.88%  |
| KDE5         | 3        | 3.53%   |
| fvwm         | 3        | 3.53%   |
| helloDesktop | 2        | 2.35%   |
| MATE         | 1        | 1.18%   |
| LXQt         | 1        | 1.18%   |
| i3           | 1        | 1.18%   |
| CDE          | 1        | 1.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 74       | 88.1%   |
| X11     | 10       | 11.9%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 78       | 92.86%  |
| SLiM    | 2        | 2.38%   |
| LightDM | 2        | 2.38%   |
| SDDM    | 1        | 1.19%   |
| GDM     | 1        | 1.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 71       | 83.53%  |
| en_US   | 8        | 9.41%   |
| C       | 4        | 4.71%   |
| de_DE   | 1        | 1.18%   |
| de_CH   | 1        | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 70       | 83.33%  |
| BIOS | 14       | 16.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ufs  | 53       | 63.1%   |
| Zfs  | 22       | 26.19%  |
| Ffs  | 9        | 10.71%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 75       | 89.29%  |
| MBR     | 8        | 9.52%   |
| Unknown | 1        | 1.19%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| PC Engines          | 27       | 32.14%  |
| Hewlett-Packard     | 7        | 8.33%   |
| Unknown             | 7        | 8.33%   |
| Gigabyte Technology | 6        | 7.14%   |
| ASRock              | 6        | 7.14%   |
| ASUSTek Computer    | 5        | 5.95%   |
| Supermicro          | 3        | 3.57%   |
| Protectli           | 3        | 3.57%   |
| Dell                | 3        | 3.57%   |
| Sun                 | 2        | 2.38%   |
| Shuttle             | 2        | 2.38%   |
| Intel               | 2        | 2.38%   |
| ASRockRack          | 2        | 2.38%   |
| Apple               | 2        | 2.38%   |
| YANYU               | 1        | 1.19%   |
| Lenovo              | 1        | 1.19%   |
| HPE                 | 1        | 1.19%   |
| Biostar             | 1        | 1.19%   |
| BESSTAR Tech        | 1        | 1.19%   |
| ADI Engineering     | 1        | 1.19%   |
| Acer                | 1        | 1.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| PC Engines APU2                          | 15       | 17.86%  |
| PC Engines apu4                          | 10       | 11.9%   |
| Unknown                                  | 7        | 8.33%   |
| Protectli FW6                            | 3        | 3.57%   |
| ASRock A320M-ITX                         | 3        | 3.57%   |
| Shuttle DS10U                            | 2        | 2.38%   |
| Dell Precision 3440                      | 2        | 2.38%   |
| YANYU D19SL_B                            | 1        | 1.19%   |
| Supermicro X9SCL/X9SCM                   | 1        | 1.19%   |
| Supermicro SYS-1019D-4C-FHN13TP          | 1        | 1.19%   |
| Supermicro PDSML                         | 1        | 1.19%   |
| Sun SUNW,Sun-Blade-1500                  | 1        | 1.19%   |
| Sun SUNW,Sun-Blade-100                   | 1        | 1.19%   |
| PC Engines apu6                          | 1        | 1.19%   |
| PC Engines APU3                          | 1        | 1.19%   |
| Lenovo ThinkCentre M75t Gen 2 11KECTO1WW | 1        | 1.19%   |
| Intel Q3XXG4-P V1.0                      | 1        | 1.19%   |
| Intel HURONRIVER                         | 1        | 1.19%   |
| HPE ProLiant MicroServer Gen10           | 1        | 1.19%   |
| HP Z620 Workstation                      | 1        | 1.19%   |
| HP Z600 Workstation                      | 1        | 1.19%   |
| HP ProLiant ML350p Gen8                  | 1        | 1.19%   |
| HP ProLiant MicroServer Gen8             | 1        | 1.19%   |
| HP Compaq Elite 8300 SFF                 | 1        | 1.19%   |
| HP Compaq Elite 8300 CMT                 | 1        | 1.19%   |
| HP Compaq 8200 Elite SFF PC              | 1        | 1.19%   |
| Gigabyte X399 DESIGNARE EX               | 1        | 1.19%   |
| Gigabyte H97N-WIFI                       | 1        | 1.19%   |
| Gigabyte H67A-UD3H-B3                    | 1        | 1.19%   |
| Gigabyte BRi3(H)-10110                   | 1        | 1.19%   |
| Gigabyte B450M DS3H                      | 1        | 1.19%   |
| Gigabyte 990FXA-UD3                      | 1        | 1.19%   |
| Dell XPS420                              | 1        | 1.19%   |
| Biostar H61MHV2                          | 1        | 1.19%   |
| BESSTAR Tech X35G                        | 1        | 1.19%   |
| ASUS Z170-K                              | 1        | 1.19%   |
| ASUS SABERTOOTH Z77                      | 1        | 1.19%   |
| ASUS ROG STRIX Z370-I GAMING             | 1        | 1.19%   |
| ASUS P8Z77-V                             | 1        | 1.19%   |
| ASUS All Series                          | 1        | 1.19%   |
| ASRockRack X570D4U-2L2T                  | 1        | 1.19%   |
| ASRockRack X470D4U2-2T                   | 1        | 1.19%   |
| ASRock X99M Extreme4                     | 1        | 1.19%   |
| ASRock J4105-ITX                         | 1        | 1.19%   |
| ASRock B550 Taichi                       | 1        | 1.19%   |
| Apple MacPro5,1                          | 1        | 1.19%   |
| Apple MacPro3,1                          | 1        | 1.19%   |
| ADI Engineering RCC                      | 1        | 1.19%   |
| Acer Aspire XC-885                       | 1        | 1.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| PC Engines apu2                 | 15       | 17.86%  |
| PC Engines apu4                 | 10       | 11.9%   |
| Unknown                         | 7        | 8.33%   |
| Protectli FW6                   | 3        | 3.57%   |
| HP Compaq                       | 3        | 3.57%   |
| ASRock A320M-ITX                | 3        | 3.57%   |
| Sun SUNW                        | 2        | 2.38%   |
| Shuttle DS10U                   | 2        | 2.38%   |
| HP ProLiant                     | 2        | 2.38%   |
| Dell Precision                  | 2        | 2.38%   |
| YANYU D19SL                     | 1        | 1.19%   |
| Supermicro X9SCL                | 1        | 1.19%   |
| Supermicro SYS-1019D-4C-FHN13TP | 1        | 1.19%   |
| Supermicro PDSML                | 1        | 1.19%   |
| PC Engines apu6                 | 1        | 1.19%   |
| PC Engines APU3                 | 1        | 1.19%   |
| Lenovo ThinkCentre              | 1        | 1.19%   |
| Intel Q3XXG4-P                  | 1        | 1.19%   |
| Intel HURONRIVER                | 1        | 1.19%   |
| HPE ProLiant                    | 1        | 1.19%   |
| HP Z620                         | 1        | 1.19%   |
| HP Z600                         | 1        | 1.19%   |
| Gigabyte X399                   | 1        | 1.19%   |
| Gigabyte H97N-WIFI              | 1        | 1.19%   |
| Gigabyte H67A-UD3H-B3           | 1        | 1.19%   |
| Gigabyte BRi3(H)-10110          | 1        | 1.19%   |
| Gigabyte B450M                  | 1        | 1.19%   |
| Gigabyte 990FXA-UD3             | 1        | 1.19%   |
| Dell XPS420                     | 1        | 1.19%   |
| Biostar H61MHV2                 | 1        | 1.19%   |
| BESSTAR Tech X35G               | 1        | 1.19%   |
| ASUS Z170-K                     | 1        | 1.19%   |
| ASUS SABERTOOTH                 | 1        | 1.19%   |
| ASUS ROG                        | 1        | 1.19%   |
| ASUS P8Z77-V                    | 1        | 1.19%   |
| ASUS All                        | 1        | 1.19%   |
| ASRockRack X570D4U-2L2T         | 1        | 1.19%   |
| ASRockRack X470D4U2-2T          | 1        | 1.19%   |
| ASRock X99M                     | 1        | 1.19%   |
| ASRock J4105-ITX                | 1        | 1.19%   |
| ASRock B550                     | 1        | 1.19%   |
| Apple MacPro5                   | 1        | 1.19%   |
| Apple MacPro3                   | 1        | 1.19%   |
| ADI Engineering RCC             | 1        | 1.19%   |
| Acer Aspire                     | 1        | 1.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 20       | 23.81%  |
| 2016    | 17       | 20.24%  |
| 2020    | 14       | 16.67%  |
| 2012    | 6        | 7.14%   |
| 2021    | 5        | 5.95%   |
| 2019    | 5        | 5.95%   |
| 2013    | 4        | 4.76%   |
| 2017    | 3        | 3.57%   |
| Unknown | 3        | 3.57%   |
| 2015    | 2        | 2.38%   |
| 2008    | 2        | 2.38%   |
| 2022    | 1        | 1.19%   |
| 2011    | 1        | 1.19%   |
| 2007    | 1        | 1.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 84       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 53       | 63.1%   |
| Yes  | 31       | 36.9%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 29       | 34.12%  |
| 16.01-24.0  | 23       | 27.06%  |
| 8.01-16.0   | 16       | 18.82%  |
| 32.01-64.0  | 9        | 10.59%  |
| 2.01-3.0    | 3        | 3.53%   |
| 64.01-256.0 | 2        | 2.35%   |
| 1.01-2.0    | 1        | 1.18%   |
| 0.01-0.5    | 1        | 1.18%   |
| Unknown     | 1        | 1.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 39       | 43.33%  |
| 0.51-1.0   | 27       | 30%     |
| 2.01-3.0   | 7        | 7.78%   |
| 1.01-2.0   | 7        | 7.78%   |
| 4.01-8.0   | 3        | 3.33%   |
| 8.01-16.0  | 2        | 2.22%   |
| 0          | 2        | 2.22%   |
| 3.01-4.0   | 1        | 1.11%   |
| 16.01-24.0 | 1        | 1.11%   |
| Unknown    | 1        | 1.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 58       | 68.24%  |
| 0      | 11       | 12.94%  |
| 2      | 5        | 5.88%   |
| 4      | 4        | 4.71%   |
| 6      | 3        | 3.53%   |
| 3      | 2        | 2.35%   |
| 17     | 1        | 1.18%   |
| 16     | 1        | 1.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 84.52%  |
| Yes       | 13       | 15.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 83       | 98.81%  |
| No        | 1        | 1.19%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 72       | 85.71%  |
| Yes       | 12       | 14.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 89.29%  |
| Yes       | 9        | 10.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Switzerland | 84       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Zurich                   | 21       | 21.65%  |
| Gordola                  | 5        | 5.15%   |
| Gachnang                 | 4        | 4.12%   |
| Winterthur               | 3        | 3.09%   |
| St. Moritz               | 3        | 3.09%   |
| Lausanne                 | 3        | 3.09%   |
| Riehen                   | 2        | 2.06%   |
| Oensingen                | 2        | 2.06%   |
| Mettmenstetten           | 2        | 2.06%   |
| Lenzburg                 | 2        | 2.06%   |
| Basel                    | 2        | 2.06%   |
| Yverdon-les-Bains        | 1        | 1.03%   |
| Yens                     | 1        | 1.03%   |
| Worblaufen               | 1        | 1.03%   |
| Willisau                 | 1        | 1.03%   |
| Wetzikon                 | 1        | 1.03%   |
| Wettswil                 | 1        | 1.03%   |
| Welschenrohr             | 1        | 1.03%   |
| Uster                    | 1        | 1.03%   |
| Trogen                   | 1        | 1.03%   |
| Suhr                     | 1        | 1.03%   |
| Steckborn                | 1        | 1.03%   |
| St. Gallen               | 1        | 1.03%   |
| Sitterdorf               | 1        | 1.03%   |
| Rumlang                  | 1        | 1.03%   |
| Riviera                  | 1        | 1.03%   |
| Rickenbach bei Wil       | 1        | 1.03%   |
| Richterswil              | 1        | 1.03%   |
| Renens                   | 1        | 1.03%   |
| Pfaeffikon               | 1        | 1.03%   |
| Ottenbach                | 1        | 1.03%   |
| Opfikon                  | 1        | 1.03%   |
| Oftringen                | 1        | 1.03%   |
| Niederbipp               | 1        | 1.03%   |
| Nidau                    | 1        | 1.03%   |
| Naters                   | 1        | 1.03%   |
| Moosseedorf              | 1        | 1.03%   |
| Mellingen                | 1        | 1.03%   |
| Lupfig                   | 1        | 1.03%   |
| Lucerne                  | 1        | 1.03%   |
| Lohnstorf                | 1        | 1.03%   |
| Liestal                  | 1        | 1.03%   |
| La Tour-de-Peilz         | 1        | 1.03%   |
| Jona                     | 1        | 1.03%   |
| Hittnau / Hittnau (Dorf) | 1        | 1.03%   |
| Hemberg                  | 1        | 1.03%   |
| Geneva                   | 1        | 1.03%   |
| Frauenfeld               | 1        | 1.03%   |
| Fechy                    | 1        | 1.03%   |
| Ennetbaden               | 1        | 1.03%   |
| Eiken                    | 1        | 1.03%   |
| Dubendorf                | 1        | 1.03%   |
| Dietikon                 | 1        | 1.03%   |
| Diepoldsau               | 1        | 1.03%   |
| Davesco                  | 1        | 1.03%   |
| Burgdorf                 | 1        | 1.03%   |
| Buchs / Buchs (Dorf)     | 1        | 1.03%   |
| Baden                    | 1        | 1.03%   |
| Attalens                 | 1        | 1.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 16       | 30     | 18.18%  |
| Phison              | 13       | 16     | 14.77%  |
| WDC                 | 10       | 16     | 11.36%  |
| Kingston            | 8        | 8      | 9.09%   |
| Seagate             | 7        | 8      | 7.95%   |
| Hoodisk             | 5        | 5      | 5.68%   |
| Crucial             | 4        | 10     | 4.55%   |
| Intel               | 3        | 16     | 3.41%   |
| HPT                 | 3        | 35     | 3.41%   |
| Toshiba             | 2        | 3      | 2.27%   |
| SanDisk             | 2        | 4      | 2.27%   |
| Hitachi             | 2        | 2      | 2.27%   |
| Corsair             | 2        | 3      | 2.27%   |
| China               | 2        | 3      | 2.27%   |
| Transcend           | 1        | 1      | 1.14%   |
| SPCC                | 1        | 1      | 1.14%   |
| OPENBSD             | 1        | 1      | 1.14%   |
| Micron Technology   | 1        | 2      | 1.14%   |
| Hewlett-Packard     | 1        | 5      | 1.14%   |
| FORESEE             | 1        | 1      | 1.14%   |
| BIWIN               | 1        | 1      | 1.14%   |
| Apple               | 1        | 1      | 1.14%   |
| A-DATA Technology   | 1        | 1      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Phison SATA SSD 16GB                 | 10       | 8%      |
| Hoodisk SSD 32GB                     | 5        | 4%      |
| Samsung SSD 860 EVO 250GB            | 4        | 3.2%    |
| Phison SATA SSD 32GB                 | 3        | 2.4%    |
| Kingston RBUSNS8180DS3128GH 128GB    | 3        | 2.4%    |
| HPT DISK 0_3 3TB                     | 3        | 2.4%    |
| HPT DISK 0_2 3TB                     | 3        | 2.4%    |
| HPT DISK 0_1 6TB                     | 3        | 2.4%    |
| HPT DISK 0_0 4TB                     | 3        | 2.4%    |
| WDC WD6002FRYZ-01WD5B1 6TB           | 2        | 1.6%    |
| Samsung SSD 960 EVO 250GB            | 2        | 1.6%    |
| Samsung SSD 860 PRO 256GB            | 2        | 1.6%    |
| HPT DISK 0_9 3TB                     | 2        | 1.6%    |
| HPT DISK 0_8 3TB                     | 2        | 1.6%    |
| HPT DISK 0_7 3TB                     | 2        | 1.6%    |
| HPT DISK 0_6 3TB                     | 2        | 1.6%    |
| HPT DISK 0_5 18TB                    | 2        | 1.6%    |
| HPT DISK 0_4 18TB                    | 2        | 1.6%    |
| HPT DISK 0_14 3TB                    | 2        | 1.6%    |
| HPT DISK 0_13 2TB                    | 2        | 1.6%    |
| HPT DISK 0_12 1TB                    | 2        | 1.6%    |
| HPT DISK 0_11 1TB                    | 2        | 1.6%    |
| HPT DISK 0_10 1TB                    | 2        | 1.6%    |
| Hitachi HDS721050CLA360 500GB        | 2        | 1.6%    |
| Crucial CT250MX500SSD1 250GB         | 2        | 1.6%    |
| WDC WDS250G2B0C-00PXH0 250GB         | 1        | 0.8%    |
| WDC WDS240G2G0B-00EPW0 240GB         | 1        | 0.8%    |
| WDC WDS120G2G0B-00EPW0 120GB         | 1        | 0.8%    |
| WDC WDS120G2G0A-00JH30 120GB         | 1        | 0.8%    |
| WDC WD40EFRX-68WT0N0 4TB             | 1        | 0.8%    |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 0.8%    |
| WDC WD2002FYPS-01U1B0 2TB            | 1        | 0.8%    |
| WDC WD10EALX-009BA0 1TB              | 1        | 0.8%    |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1        | 0.8%    |
| Transcend TS64GMSA230S 64GB          | 1        | 0.8%    |
| Toshiba MQ03UBB300 3TB               | 1        | 0.8%    |
| Toshiba MK1059GSM 1TB                | 1        | 0.8%    |
| Toshiba DT01ACA200 2TB               | 1        | 0.8%    |
| SPCC Solid State Disk 256GB          | 1        | 0.8%    |
| Seagate ST9250410AS 250GB            | 1        | 0.8%    |
| Seagate ST5000DM000-1FK178 5TB       | 1        | 0.8%    |
| Seagate ST3500413AS 500GB            | 1        | 0.8%    |
| Seagate ST3320820A 320GB             | 1        | 0.8%    |
| Seagate ST320LT007-9ZV142 320GB      | 1        | 0.8%    |
| Seagate ST315320A 16GB               | 1        | 0.8%    |
| Seagate ST2000VN004-2E4164 2TB       | 1        | 0.8%    |
| SanDisk SSD U100 24GB                | 1        | 0.8%    |
| SanDisk Cruzer Fit 32GB              | 1        | 0.8%    |
| Samsung SSD 980 PRO 250GB            | 1        | 0.8%    |
| Samsung SSD 970 EVO Plus 1TB         | 1        | 0.8%    |
| Samsung SSD 850 PRO 256GB            | 1        | 0.8%    |
| Samsung SSD 850 EVO 250GB            | 1        | 0.8%    |
| Samsung SSD 840 Series 120GB         | 1        | 0.8%    |
| Samsung MZVPW256HEGL-00000 256GB     | 1        | 0.8%    |
| Samsung MZ7TE256HMHP-000H1 256GB     | 1        | 0.8%    |
| Samsung MZ7PD256HAFV-000H7 256GB     | 1        | 0.8%    |
| Samsung 980 PRO with Heatsink 1TB    | 1        | 0.8%    |
| OPENBSD SR RAID 1 752GB              | 1        | 0.8%    |
| Micron MTFDDAK256MAM-1K12 256GB      | 1        | 0.8%    |
| Kingston SV300S37A120G 120GB         | 1        | 0.8%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| Seagate         | 7        | 8      | 30.43%  |
| WDC             | 5        | 10     | 21.74%  |
| HPT             | 3        | 35     | 13.04%  |
| Toshiba         | 2        | 3      | 8.7%    |
| Hitachi         | 2        | 2      | 8.7%    |
| OPENBSD         | 1        | 1      | 4.35%   |
| Hewlett-Packard | 1        | 1      | 4.35%   |
| China           | 1        | 1      | 4.35%   |
| Apple           | 1        | 1      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Phison              | 13       | 16     | 22.03%  |
| Samsung Electronics | 11       | 23     | 18.64%  |
| Kingston            | 8        | 8      | 13.56%  |
| Hoodisk             | 5        | 5      | 8.47%   |
| Crucial             | 4        | 10     | 6.78%   |
| WDC                 | 3        | 4      | 5.08%   |
| Intel               | 3        | 16     | 5.08%   |
| SanDisk             | 2        | 4      | 3.39%   |
| Corsair             | 2        | 3      | 3.39%   |
| Transcend           | 1        | 1      | 1.69%   |
| SPCC                | 1        | 1      | 1.69%   |
| Micron Technology   | 1        | 2      | 1.69%   |
| Hewlett-Packard     | 1        | 4      | 1.69%   |
| FORESEE             | 1        | 1      | 1.69%   |
| China               | 1        | 2      | 1.69%   |
| BIWIN               | 1        | 1      | 1.69%   |
| A-DATA Technology   | 1        | 1      | 1.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 58       | 102    | 70.73%  |
| HDD  | 16       | 62     | 19.51%  |
| NVMe | 8        | 9      | 9.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 65       | 164    | 89.04%  |
| NVMe | 8        | 9      | 10.96%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 64       | 109    | 68.82%  |
| 0.51-1.0   | 7        | 12     | 7.53%   |
| 4.01-10.0  | 6        | 10     | 6.45%   |
| 2.01-3.0   | 5        | 19     | 5.38%   |
| 1.01-2.0   | 5        | 6      | 5.38%   |
| 3.01-4.0   | 4        | 4      | 4.3%    |
| 10.01-20.0 | 2        | 4      | 2.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 39       | 45.35%  |
| 1-20       | 16       | 18.6%   |
| 21-50      | 12       | 13.95%  |
| 51-100     | 12       | 13.95%  |
| 501-1000   | 4        | 4.65%   |
| 251-500    | 2        | 2.33%   |
| 1001-2000  | 1        | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 79       | 89.77%  |
| 21-50   | 6        | 6.82%   |
| 51-100  | 2        | 2.27%   |
| 251-500 | 1        | 1.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WDS120G2G0A-00JH30 120GB | 1        | 1      | 10%     |
| WDC WD6002FRYZ-01WD5B1 6TB   | 1        | 5      | 10%     |
| WDC WD40EFRX-68WT0N0 4TB     | 1        | 1      | 10%     |
| WDC WD2002FYPS-01U1B0 2TB    | 1        | 1      | 10%     |
| Toshiba MK1059GSM 1TB        | 1        | 1      | 10%     |
| Seagate ST3500413AS 500GB    | 1        | 1      | 10%     |
| Kingston SV300S37A120G 120GB | 1        | 1      | 10%     |
| Intel SSDSC2BW240A4 240GB    | 1        | 1      | 10%     |
| Intel SSDSA2BW160G3H 160GB   | 1        | 5      | 10%     |
| Corsair Force 3 SSD 120GB    | 1        | 2      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 3        | 8      | 33.33%  |
| Intel    | 2        | 6      | 22.22%  |
| Toshiba  | 1        | 1      | 11.11%  |
| Seagate  | 1        | 1      | 11.11%  |
| Kingston | 1        | 1      | 11.11%  |
| Corsair  | 1        | 2      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 7      | 50%     |
| Toshiba | 1        | 1      | 25%     |
| Seagate | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 5        | 10     | 62.5%   |
| HDD  | 3        | 9      | 37.5%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 67       | 112    | 84.81%  |
| Malfunc  | 7        | 19     | 8.86%   |
| Detected | 5        | 42     | 6.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 41       | 41%     |
| AMD                      | 39       | 39%     |
| Samsung Electronics      | 7        | 7%      |
| HighPoint Technologies   | 3        | 3%      |
| ASMedia Technology       | 3        | 3%      |
| ULi Electronics          | 2        | 2%      |
| Sandisk                  | 2        | 2%      |
| Marvell Technology Group | 2        | 2%      |
| Hewlett-Packard          | 1        | 1%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26       | 22.22%  |
| AMD FCH SATA Controller [IDE mode]                                                      | 9        | 7.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 3.42%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 3.42%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 3.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 2.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3        | 2.56%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.56%   |
| AMD FCH SATA Controller D                                                               | 3        | 2.56%   |
| ULi M5229 IDE                                                                           | 2        | 1.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.71%   |
| Intel Atom Processor C3000 Series SATA Controller 1                                     | 2        | 1.71%   |
| Intel Atom Processor C3000 Series SATA Controller 0                                     | 2        | 1.71%   |
| HighPoint RocketRAID 2760 SAS Controller                                                | 2        | 1.71%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.71%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 1.71%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.85%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.85%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.85%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 0.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 0.85%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1        | 0.85%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 0.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 0.85%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 1        | 0.85%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.85%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.85%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 0.85%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                                | 1        | 0.85%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                                | 1        | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.85%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                        | 1        | 0.85%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                        | 1        | 0.85%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.85%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.85%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 0.85%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 0.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1        | 0.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 0.85%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 1        | 0.85%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1        | 0.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 0.85%   |
| HighPoint RocketRAID 230x 4 Port SATA-II Controller                                     | 1        | 0.85%   |
| HP Smart Array Gen8 Controllers                                                         | 1        | 0.85%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 0.85%   |
| AMD CS5536 [Geode companion] IDE                                                        | 1        | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 66       | 66%     |
| IDE  | 17       | 17%     |
| NVMe | 9        | 9%      |
| RAID | 6        | 6%      |
| SAS  | 1        | 1%      |
| SCSI | 1        | 1%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 43       | 51.19%  |
| AMD     | 39       | 46.43%  |
| Unknown | 2        | 2.38%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| AMD GX-412TC SOC                                                 | 27       | 32.14%  |
| Intel Celeron CPU 3865U @ 1.80GHz                                | 3        | 3.57%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics                      | 3        | 3.57%   |
| Intel Core i7-3770K CPU @ 3.50GHz                                | 2        | 2.38%   |
| Intel Core i5-10500 CPU @ 3.10GHz                                | 2        | 2.38%   |
| Intel Atom CPU C3758 @ 2.20GHz                                   | 2        | 2.38%   |
|                                                                  | 2        | 2.38%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz                                | 1        | 1.19%   |
| Intel Xeon CPU W3680 @ 3.33GHz                                   | 1        | 1.19%   |
| Intel Xeon CPU E5630 @ 2.53GHz                                   | 1        | 1.19%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz                              | 1        | 1.19%   |
| Intel Xeon CPU E5-2620 @ 2.00GHz                                 | 1        | 1.19%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz                               | 1        | 1.19%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz                              | 1        | 1.19%   |
| Intel Xeon CPU E3-1220L V2 @ 2.30GHz                             | 1        | 1.19%   |
| Intel Xeon CPU E                                                 | 1        | 1.19%   |
| Intel Core i7-9700 CPU @ 3.00GHz                                 | 1        | 1.19%   |
| Intel Core i7-6700K CPU @ 4.00GHz                                | 1        | 1.19%   |
| Intel Core i7-3770 CPU @ 3.40GHz                                 | 1        | 1.19%   |
| Intel Core i7-2600K CPU                                          | 1        | 1.19%   |
| Intel Core i5-9400 CPU @ 2.90GHz                                 | 1        | 1.19%   |
| Intel Core i5-8365U CPU @ 1.60GHz                                | 1        | 1.19%   |
| Intel Core i5-5250U CPU @ 1.60GHz                                | 1        | 1.19%   |
| Intel Core i5-4570S CPU @ 2.90GHz                                | 1        | 1.19%   |
| Intel Core i5-3550 CPU @ 3.30GHz                                 | 1        | 1.19%   |
| Intel Core i5-3470 CPU @ 3.20GHz                                 | 1        | 1.19%   |
| Intel Core i5-2520M CPU @ 2.50GHz                                | 1        | 1.19%   |
| Intel Core i5-2500 CPU @ 3.30GHz                                 | 1        | 1.19%   |
| Intel Core i5-10210U CPU @ 1.60GHz                               | 1        | 1.19%   |
| Intel Core i3-8350K CPU @ 4.00GHz                                | 1        | 1.19%   |
| Intel Core i3-8145U CPU @ 2.10GHz                                | 1        | 1.19%   |
| Intel Core i3-4150 CPU @ 3.50GHz                                 | 1        | 1.19%   |
| Intel Core i3-10110U CPU @ 2.10GHz                               | 1        | 1.19%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz                               | 1        | 1.19%   |
| Intel Core 2 Duo CPU 2.40GH                                      | 1        | 1.19%   |
| Intel Core 2 Duo                                                 | 1        | 1.19%   |
| Intel Celeron J4105 CPU @ 1.50GHz                                | 1        | 1.19%   |
| Intel Celeron CPU J1900 @ 1.99GHz                                | 1        | 1.19%   |
| Intel Celeron CPU 4205U @ 1.80GHz                                | 1        | 1.19%   |
| Intel Atom CPU C2758 @ 2.40GHz                                   | 1        | 1.19%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                          | 1        | 1.19%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor                   | 1        | 1.19%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics                       | 1        | 1.19%   |
| AMD Ryzen 7 5800X 8-Core Processor                               | 1        | 1.19%   |
| AMD Ryzen 7 1800X Eight-Core Processor                           | 1        | 1.19%   |
| AMD Ryzen 5 5600G with Radeon Graphics                           | 1        | 1.19%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics                      | 1        | 1.19%   |
| AMD Opteron X3421 APU                                            | 1        | 1.19%   |
| AMD Geode Integrated Processor by PCS ("AuthenticAMD" 586-class) | 1        | 1.19%   |
| AMD FX-8350 Eight-Core Processor                                 | 1        | 1.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD GX                 | 27       | 32.14%  |
| Intel Core i5          | 11       | 13.1%   |
| Intel Xeon             | 9        | 10.71%  |
| Intel Core i7          | 6        | 7.14%   |
| Intel Celeron          | 6        | 7.14%   |
| Intel Core i3          | 5        | 5.95%   |
| AMD Ryzen 5            | 4        | 4.76%   |
| Other                  | 3        | 3.57%   |
| Intel Atom             | 3        | 3.57%   |
| Intel Core 2 Duo       | 2        | 2.38%   |
| AMD Ryzen 7            | 2        | 2.38%   |
| AMD Ryzen Threadripper | 1        | 1.19%   |
| AMD Ryzen 7 PRO        | 1        | 1.19%   |
| AMD Ryzen 3            | 1        | 1.19%   |
| AMD Opteron            | 1        | 1.19%   |
| AMD Geode Integrated   | 1        | 1.19%   |
| AMD FX                 | 1        | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 48       | 57.14%  |
| 2       | 11       | 13.1%   |
| 8       | 9        | 10.71%  |
| 6       | 4        | 4.76%   |
| 16      | 3        | 3.57%   |
| 1       | 3        | 3.57%   |
| 12      | 2        | 2.38%   |
| Unknown | 2        | 2.38%   |
| 32      | 1        | 1.19%   |
| 10      | 1        | 1.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 79       | 94.05%  |
| 2       | 2        | 2.38%   |
| Unknown | 2        | 2.38%   |
| 4       | 1        | 1.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 57       | 67.86%  |
| 2       | 23       | 27.38%  |
| Unknown | 4        | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Puma          | 27       | 32.14%  |
| KabyLake      | 11       | 13.1%   |
| IvyBridge     | 7        | 8.33%   |
| SandyBridge   | 5        | 5.95%   |
| Zen+          | 3        | 3.57%   |
| Zen           | 3        | 3.57%   |
| Haswell       | 3        | 3.57%   |
| Zen 3         | 2        | 2.38%   |
| Westmere      | 2        | 2.38%   |
| Skylake       | 2        | 2.38%   |
| Silvermont    | 2        | 2.38%   |
| Goldmont      | 2        | 2.38%   |
| Core          | 2        | 2.38%   |
| CometLake     | 2        | 2.38%   |
| Unknown       | 2        | 2.38%   |
| Zen 2         | 1        | 1.19%   |
| TigerLake     | 1        | 1.19%   |
| Piledriver    | 1        | 1.19%   |
| Penryn        | 1        | 1.19%   |
| IceLake       | 1        | 1.19%   |
| Goldmont plus | 1        | 1.19%   |
| Geode         | 1        | 1.19%   |
| Excavator     | 1        | 1.19%   |
| Broadwell     | 1        | 1.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 24       | 43.64%  |
| AMD                                          | 12       | 21.82%  |
| Nvidia                                       | 9        | 16.36%  |
| ASPEED Technology                            | 5        | 9.09%   |
| Matrox Electronics Systems                   | 3        | 5.45%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 1.82%   |
| 3DLabs                                       | 1        | 1.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| ASPEED Technology ASPEED Graphics Family                                  | 5        | 9.09%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                      | 3        | 5.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 3        | 5.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3        | 5.45%   |
| Matrox Electronics Systems MGA G200EH                                     | 2        | 3.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2        | 3.64%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                    | 2        | 3.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2        | 3.64%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 2        | 3.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2        | 3.64%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                      | 2        | 3.64%   |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)            | 1        | 1.82%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1        | 1.82%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                       | 1        | 1.82%   |
| Nvidia GM206 [GeForce GTX 960]                                            | 1        | 1.82%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1        | 1.82%   |
| Nvidia GK107 [GeForce GT 640]                                             | 1        | 1.82%   |
| Nvidia GK104 [GeForce GTX 680]                                            | 1        | 1.82%   |
| Nvidia GF108GL [Quadro 600]                                               | 1        | 1.82%   |
| Nvidia G98 [Quadro NVS 295]                                               | 1        | 1.82%   |
| Nvidia G92 [GeForce 8800 GT]                                              | 1        | 1.82%   |
| Matrox Electronics Systems MGA G200eW WPCM450                             | 1        | 1.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 1.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1        | 1.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1        | 1.82%   |
| Intel HD Graphics 6000                                                    | 1        | 1.82%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1        | 1.82%   |
| Intel Coffee Lake UHD 610 Graphics Controller                             | 1        | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1        | 1.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 1.82%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 1        | 1.82%   |
| AMD Tonga XT / Amethyst XT [Radeon R9 380X / R9 M295X]                    | 1        | 1.82%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                          | 1        | 1.82%   |
| AMD Renoir                                                                | 1        | 1.82%   |
| AMD Rage 3 [Rage XL PCI]                                                  | 1        | 1.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 1        | 1.82%   |
| AMD Cezanne                                                               | 1        | 1.82%   |
| 3DLabs Sun XVR-500 Graphics Accelerator                                   | 1        | 1.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Other      | 29       | 34.52%  |
| 1 x Intel  | 24       | 28.57%  |
| 1 x AMD    | 12       | 14.29%  |
| 1 x Nvidia | 9        | 10.71%  |
| 1 x ASPEED | 5        | 5.95%   |
| 1 x Matrox | 3        | 3.57%   |
| 1 x XGI    | 1        | 1.19%   |
| 1 x 3DLabs | 1        | 1.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 47       | 55.95%  |
| Unknown     | 31       | 36.9%   |
| Proprietary | 6        | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 77       | 91.67%  |
| 1.01-2.0   | 3        | 3.57%   |
| 3.01-4.0   | 2        | 2.38%   |
| 5.01-6.0   | 1        | 1.19%   |
| 2.01-3.0   | 1        | 1.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Acer                 | 2        | 20%     |
| Samsung Electronics  | 1        | 10%     |
| Philips              | 1        | 10%     |
| NEC Computers        | 1        | 10%     |
| LG Electronics       | 1        | 10%     |
| Lenovo               | 1        | 10%     |
| Iiyama               | 1        | 10%     |
| Eizo                 | 1        | 10%     |
| Ancor Communications | 1        | 10%     |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Samsung Electronics S27E390 SAM0C1B 1920x1080 600x340mm 27.2-inch | 1        | 9.09%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                | 1        | 9.09%   |
| NEC Computers LCD Monitor EA224WMi 1920x1080                      | 1        | 9.09%   |
| LG Electronics LCD Monitor LG Ultra HD 11520x2160                 | 1        | 9.09%   |
| LG Electronics LCD Monitor LG Ultra HD                            | 1        | 9.09%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 600x340mm 27.2-inch          | 1        | 9.09%   |
| Iiyama PL3288UH IVM7610 3840x2160 700x390mm 31.5-inch             | 1        | 9.09%   |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                | 1        | 9.09%   |
| Ancor Communications VS278 ACI27A1 1920x1080 600x340mm 27.2-inch  | 1        | 9.09%   |
| Acer XB271HU ACR0490 2560x1440 600x340mm 27.2-inch                | 1        | 9.09%   |
| Acer XB271HU A ACR052F 2560x1440 600x340mm 27.2-inch              | 1        | 9.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Desktops | Percent |
|-----------------|----------|---------|
| 1920x1080 (FHD) | 5        | 45.45%  |
| 2560x1440 (QHD) | 3        | 27.27%  |
| 3840x2160 (4K)  | 1        | 9.09%   |
| 11520x2160      | 1        | 9.09%   |
| Unknown         | 1        | 9.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 5        | 50%     |
| Unknown | 2        | 20%     |
| 65      | 1        | 10%     |
| 31      | 1        | 10%     |
| 23      | 1        | 10%     |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 60%     |
| Unknown     | 2        | 20%     |
| 601-700     | 1        | 10%     |
| 1001-1500   | 1        | 10%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 8        | 80%     |
| Unknown | 2        | 20%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 5        | 50%     |
| Unknown        | 2        | 20%     |
| More than 1000 | 1        | 10%     |
| 351-500        | 1        | 10%     |
| 201-250        | 1        | 10%     |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 101-120 | 3        | 30%     |
| 51-100  | 3        | 30%     |
| Unknown | 2        | 20%     |
| 1-50    | 1        | 10%     |
| 121-160 | 1        | 10%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 74       | 88.1%   |
| 1     | 9        | 10.71%  |
| 2     | 1        | 1.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 72       | 66.67%  |
| Realtek Semiconductor             | 14       | 12.96%  |
| Broadcom                          | 8        | 7.41%   |
| Qualcomm Atheros                  | 2        | 1.85%   |
| Mellanox Technologies             | 2        | 1.85%   |
| American Megatrends               | 2        | 1.85%   |
| VIA Technologies                  | 1        | 0.93%   |
| U-Blox                            | 1        | 0.93%   |
| Qualcomm Atheros Communications   | 1        | 0.93%   |
| QLogic                            | 1        | 0.93%   |
| Oracle/SUN                        | 1        | 0.93%   |
| Huawei Technologies               | 1        | 0.93%   |
| Free Software Initiative of Japan | 1        | 0.93%   |
| Aquantia                          | 1        | 0.93%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 27       | 19.01%  |
| Intel I210 Gigabit Network Connection                                         | 19       | 13.38%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 11       | 7.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 4.23%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4        | 2.82%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 2.82%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 2.11%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3        | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 1.41%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 1.41%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 1.41%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 2        | 1.41%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2        | 1.41%   |
| Intel Ethernet Controller X550                                                | 2        | 1.41%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2        | 1.41%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 1.41%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2        | 1.41%   |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2        | 1.41%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 1.41%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 1.41%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 1.41%   |
| American Megatrends Virtual Ethernet                                          | 2        | 1.41%   |
| VIA VT6105M [Rhine-III]                                                       | 1        | 0.7%    |
| U-Blox [u-blox 7]                                                             | 1        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.7%    |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 0.7%    |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 0.7%    |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                          | 1        | 0.7%    |
| Mellanox MT2894 Family [ConnectX-6 Lx]                                        | 1        | 0.7%    |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                       | 1        | 0.7%    |
| Intel Wireless 8265 / 8275                                                    | 1        | 0.7%    |
| Intel Wireless 7260                                                           | 1        | 0.7%    |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                              | 1        | 0.7%    |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                              | 1        | 0.7%    |
| Intel Ethernet Controller I225-V                                              | 1        | 0.7%    |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 1        | 0.7%    |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1        | 0.7%    |
| Intel Ethernet Connection I354                                                | 1        | 0.7%    |
| Intel Ethernet Connection I217-V                                              | 1        | 0.7%    |
| Intel Ethernet Connection (6) I219-V                                          | 1        | 0.7%    |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 0.7%    |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 0.7%    |
| Intel 82573L Gigabit Ethernet Controller                                      | 1        | 0.7%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.7%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.7%    |
| Intel 82566DC-2 Gigabit Network Connection                                    | 1        | 0.7%    |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                        | 1        | 0.7%    |
| Huawei ME909u-521 mPCIe LTE/GPS card                                          | 1        | 0.7%    |
| Free Software Initiative of Japan NeuG True RNG                               | 1        | 0.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.7%    |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.7%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1        | 0.7%    |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1        | 0.7%    |
| Broadcom NetXtreme BCM5703 Gigabit Ethernet                                   | 1        | 0.7%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1        | 0.7%    |
| Aquantia AQC100 10G Ethernet MAC controller [AQtion]                          | 1        | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 5        | 45.45%  |
| Realtek Semiconductor           | 3        | 27.27%  |
| Qualcomm Atheros Communications | 1        | 9.09%   |
| Qualcomm Atheros                | 1        | 9.09%   |
| Broadcom                        | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 18.18%  |
| Intel Wi-Fi 6 AX200                                            | 2        | 18.18%  |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 9.09%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 9.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 9.09%   |
| Intel Wireless 8265 / 8275                                     | 1        | 9.09%   |
| Intel Wireless 7260                                            | 1        | 9.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1        | 9.09%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 70       | 73.68%  |
| Realtek Semiconductor | 11       | 11.58%  |
| Broadcom              | 7        | 7.37%   |
| American Megatrends   | 2        | 2.11%   |
| VIA Technologies      | 1        | 1.05%   |
| Qualcomm Atheros      | 1        | 1.05%   |
| QLogic                | 1        | 1.05%   |
| Oracle/SUN            | 1        | 1.05%   |
| Aquantia              | 1        | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 27       | 21.43%  |
| Intel I210 Gigabit Network Connection                                         | 19       | 15.08%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 11       | 8.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 4.76%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4        | 3.17%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 3.17%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 2.38%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3        | 2.38%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 1.59%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 2        | 1.59%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2        | 1.59%   |
| Intel Ethernet Controller X550                                                | 2        | 1.59%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2        | 1.59%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 1.59%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2        | 1.59%   |
| Intel 82599 10 Gigabit TN Network Connection                                  | 2        | 1.59%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 1.59%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 1.59%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 1.59%   |
| American Megatrends Virtual Ethernet                                          | 2        | 1.59%   |
| VIA VT6105M [Rhine-III]                                                       | 1        | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.79%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 0.79%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                          | 1        | 0.79%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                              | 1        | 0.79%   |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                              | 1        | 0.79%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.79%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 1        | 0.79%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1        | 0.79%   |
| Intel Ethernet Connection I354                                                | 1        | 0.79%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                          | 1        | 0.79%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 0.79%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.79%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1        | 0.79%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.79%   |
| Intel 82566DC-2 Gigabit Network Connection                                    | 1        | 0.79%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                        | 1        | 0.79%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.79%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.79%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1        | 0.79%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1        | 0.79%   |
| Broadcom NetXtreme BCM5703 Gigabit Ethernet                                   | 1        | 0.79%   |
| Aquantia AQC100 10G Ethernet MAC controller [AQtion]                          | 1        | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 83       | 83.84%  |
| WiFi     | 11       | 11.11%  |
| Unknown  | 3        | 3.03%   |
| Modem    | 2        | 2.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 79       | 97.53%  |
| WiFi     | 2        | 2.47%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 3     | 30       | 35.29%  |
| 4     | 15       | 17.65%  |
| 1     | 11       | 12.94%  |
| 6     | 10       | 11.76%  |
| 5     | 8        | 9.41%   |
| 2     | 6        | 7.06%   |
| 13    | 2        | 2.35%   |
| 14    | 1        | 1.18%   |
| 8     | 1        | 1.18%   |
| 7     | 1        | 1.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 68       | 76.4%   |
| Yes  | 21       | 23.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 4        | 44.44%  |
| IMC Networks     | 2        | 22.22%  |
| ASUSTek Computer | 2        | 22.22%  |
| Apple            | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                          | 2        | 22.22%  |
| IMC Networks Realtek Bluetooth Adapter         | 2        | 22.22%  |
| Intel Bluetooth wireless interface             | 1        | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1        | 11.11%  |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1        | 11.11%  |
| ASUS Bluetooth Controller                      | 1        | 11.11%  |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 30       | 56.6%   |
| AMD                   | 12       | 22.64%  |
| Nvidia                | 7        | 13.21%  |
| ULi Electronics       | 2        | 3.77%   |
| Realtek Semiconductor | 1        | 1.89%   |
| Logitech              | 1        | 1.89%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 5        | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4        | 6.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 3        | 5%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3        | 5%      |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                         | 2        | 3.33%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2        | 3.33%   |
| Intel Comet Lake PCH cAVS                                                         | 2        | 3.33%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 3.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 3.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 3.33%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 3.33%   |
| Realtek Semiconductor USB Audio Maono Elf retrieving string failed                | 1        | 1.67%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 1.67%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1        | 1.67%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 1.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 1.67%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1        | 1.67%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 1.67%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1        | 1.67%   |
| Logitech H600 [Wireless Headset]                                                  | 1        | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 1.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 1.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1        | 1.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 1        | 1.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 1.67%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 1        | 1.67%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 1.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 1.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 1        | 1.67%   |
| Intel 631xESB/632xESB High Definition Audio Controller                            | 1        | 1.67%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 1.67%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                          | 1        | 1.67%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1        | 1.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1        | 1.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 22       | 27.85%  |
| Unknown             | 19       | 24.05%  |
| Samsung Electronics | 8        | 10.13%  |
| Crucial             | 7        | 8.86%   |
| Corsair             | 7        | 8.86%   |
| SK Hynix            | 6        | 7.59%   |
| Micron Technology   | 3        | 3.8%    |
| Hewlett-Packard     | 2        | 2.53%   |
| Unknown (0x05F7)    | 1        | 1.27%   |
| Unknown (07FB)      | 1        | 1.27%   |
| Tigo                | 1        | 1.27%   |
| Super Talent        | 1        | 1.27%   |
| Nanya Technology    | 1        | 1.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 12       | 14.63%  |
| SK Hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s         | 3        | 3.66%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2400MT/s         | 3        | 3.66%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2133MT/s       | 3        | 3.66%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 2        | 2.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                  | 2        | 2.44%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s         | 2        | 2.44%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1333MT/s        | 2        | 2.44%   |
| Crucial RAM CT8G4DFS8266.M8FJ 8GB DIMM DDR4 2666MT/s         | 2        | 2.44%   |
| Crucial RAM CT8G4DFRA266.C8FB 8GB DIMM DDR4 2666MT/s         | 2        | 2.44%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                   | 1        | 1.22%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                   | 1        | 1.22%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 1        | 1.22%   |
| Unknown (0x05F7) RAM Module 1GB FB-DIMM DDR2 800MT/s         | 1        | 1.22%   |
| Unknown (07FB) RAM GSA8G4SCL196P-26 8GB SODIMM DDR4 2667MT/s | 1        | 1.22%   |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                 | 1        | 1.22%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1333MT/s        | 1        | 1.22%   |
| SK Hynix RAM Module 1GB FB-DIMM DDR2 800MT/s                 | 1        | 1.22%   |
| SK Hynix RAM HMT42GR7MFR4C-PB 16384MB DIMM DDR3 1600MT/s     | 1        | 1.22%   |
| SK Hynix RAM HMT325U7BFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 1.22%   |
| Samsung RAM Module 16GB DIMM DDR3 1333MT/s                   | 1        | 1.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 1        | 1.22%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1        | 1.22%   |
| Samsung RAM M393B2G70DB0-CK0 16GB DIMM DDR3 1600MT/s         | 1        | 1.22%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s         | 1        | 1.22%   |
| Samsung RAM M393B1K70BH1-CH9 8GB DIMM DDR3 1333MT/s          | 1        | 1.22%   |
| Samsung RAM M393A1K43BB1-CTD 8GB RIMM DDR4 2133MT/s          | 1        | 1.22%   |
| Samsung RAM M391B5673EH1-CH9 2048MB DIMM DDR3 1333MT/s       | 1        | 1.22%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 1.22%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s            | 1        | 1.22%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s           | 1        | 1.22%   |
| Micron RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1        | 1.22%   |
| Micron RAM 18ASF2G72AZ-2G3B1 16GB DIMM DDR4 2400MT/s         | 1        | 1.22%   |
| Kingston RAM MSI24D4U7S8MB-8 8192MB DIMM DDR4 2400MT/s       | 1        | 1.22%   |
| Kingston RAM Module 4GB DIMM DDR4 2666MT/s                   | 1        | 1.22%   |
| Kingston RAM KHX1866C10D3/8GX 8GB DIMM DDR3 1800MT/s         | 1        | 1.22%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s         | 1        | 1.22%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 1        | 1.22%   |
| Kingston RAM CBD16D3LS1KBG/8G 8GB DIMM DDR3 1600MT/s         | 1        | 1.22%   |
| Kingston RAM 99U5663-007.A00G 16GB SODIMM DDR4 2667MT/s      | 1        | 1.22%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s        | 1        | 1.22%   |
| Kingston RAM 99U5471-002.A01LF 2GB DIMM DDR3 1333MT/s        | 1        | 1.22%   |
| Kingston RAM 9965745-028.A00G 16GB DIMM DDR4 2667MT/s        | 1        | 1.22%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3200MT/s        | 1        | 1.22%   |
| Kingston RAM 9905402-544.A00LF 4096MB DIMM DDR3 1333MT/s     | 1        | 1.22%   |
| Kingston RAM 9905316-005.A04LF 1GB DIMM DDR2 667MT/s         | 1        | 1.22%   |
| HP RAM 669239-081 8GB DIMM DDR3 1600MT/s                     | 1        | 1.22%   |
| HP RAM 647647-071 4GB DIMM DDR3 1333MT/s                     | 1        | 1.22%   |
| Crucial RAM CT8G4SFS824A.M8FD 8GB SODIMM DDR4 2400MT/s       | 1        | 1.22%   |
| Crucial RAM CT8G4SFRA32A.M8FR 8GB SODIMM DDR4 3200MT/s       | 1        | 1.22%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16GB SODIMM DDR4 3200MT/s     | 1        | 1.22%   |
| Crucial RAM BLS8G3D1609DS 8192MB DIMM DDR3 800MT/s           | 1        | 1.22%   |
| Corsair RAM CMX8GX3M1A1333C9 8GB DIMM DDR3 1333MT/s          | 1        | 1.22%   |
| Corsair RAM CMSO4GX4M1A2133C15 4GB SODIMM DDR4 2133MT/s      | 1        | 1.22%   |
| Corsair RAM CMK16GX4M4B3300C16 4GB DIMM DDR4 2133MT/s        | 1        | 1.22%   |
| Corsair RAM CMK16GX4M2Z3600C18 8GB DIMM DDR4 2667MT/s        | 1        | 1.22%   |
| Corsair RAM CMD16GX4M2B3000C15 8192MB DIMM DDR4 2133MT/s     | 1        | 1.22%   |
| Corsair RAM CMD16GX4M2A2666C15 8GB DIMM DDR4 2667MT/s        | 1        | 1.22%   |
| Corsair RAM CMD128GX4M8A2400C14 16GB DIMM DDR4 2133MT/s      | 1        | 1.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 35       | 50.72%  |
| DDR4    | 29       | 42.03%  |
| DDR2    | 3        | 4.35%   |
| LPDDR4  | 1        | 1.45%   |
| Unknown | 1        | 1.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 40       | 57.97%  |
| SODIMM       | 26       | 37.68%  |
| Row Of Chips | 1        | 1.45%   |
| RIMM         | 1        | 1.45%   |
| FB-DIMM      | 1        | 1.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 33       | 45.83%  |
| 4096  | 24       | 33.33%  |
| 16384 | 7        | 9.72%   |
| 2048  | 4        | 5.56%   |
| 1024  | 2        | 2.78%   |
| 32768 | 1        | 1.39%   |
| 512   | 1        | 1.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 27       | 35.53%  |
| 2667  | 9        | 11.84%  |
| 2133  | 8        | 10.53%  |
| 1600  | 8        | 10.53%  |
| 3200  | 7        | 9.21%   |
| 2400  | 6        | 7.89%   |
| 2666  | 5        | 6.58%   |
| 667   | 3        | 3.95%   |
| 800   | 2        | 2.63%   |
| 1800  | 1        | 1.32%   |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 42       | 48.28%  |
| 1     | 26       | 29.89%  |
| 2     | 12       | 13.79%  |
| 3     | 6        | 6.9%    |
| 4     | 1        | 1.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 33       | 55.93%  |
| Firewire controller      | 8        | 13.56%  |
| Net/wireless             | 5        | 8.47%   |
| Net/ethernet             | 4        | 6.78%   |
| Bluetooth                | 4        | 6.78%   |
| Sound                    | 2        | 3.39%   |
| Card reader              | 2        | 3.39%   |
| Graphics card            | 1        | 1.69%   |

