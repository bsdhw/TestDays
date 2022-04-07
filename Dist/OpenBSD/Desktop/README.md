OpenBSD - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for OpenBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

Total: 248

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | Raspberry Pi 3 Model B R... | [040f37113c](https://bsd-hardware.info/?probe=040f37113c) | Apr 06, 2022 |
| Intel         | DCP847SKE                   | [a79e298be3](https://bsd-hardware.info/?probe=a79e298be3) | Apr 03, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | [32d27b9404](https://bsd-hardware.info/?probe=32d27b9404) | Mar 19, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | [7361628ed9](https://bsd-hardware.info/?probe=7361628ed9) | Mar 19, 2022 |
| Unknown       | LeMaker Banana Pi           | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |
| Intel         | D945GSEJT                   | [bf6a38dfcb](https://bsd-hardware.info/?probe=bf6a38dfcb) | Feb 26, 2022 |
| Dell          | OptiPlex 755                | [9ddfe010c4](https://bsd-hardware.info/?probe=9ddfe010c4) | Feb 24, 2022 |
| Unknown       | Unknown                     | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |
| Gigabyte      | X58A-UD5                    | [58d57520c1](https://bsd-hardware.info/?probe=58d57520c1) | Feb 20, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [04e528ca9f](https://bsd-hardware.info/?probe=04e528ca9f) | Feb 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | [07546b5925](https://bsd-hardware.info/?probe=07546b5925) | Feb 18, 2022 |
| MSI           | MS-7253                     | [c4e971ea82](https://bsd-hardware.info/?probe=c4e971ea82) | Feb 16, 2022 |
| Raspberry ... | Raspberry Pi 400            | [dd56609ceb](https://bsd-hardware.info/?probe=dd56609ceb) | Feb 14, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | [4691fdb146](https://bsd-hardware.info/?probe=4691fdb146) | Feb 13, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | [97788dfb1a](https://bsd-hardware.info/?probe=97788dfb1a) | Feb 13, 2022 |
| Unknown       | LeMaker Banana Pi           | [77413a3d9d](https://bsd-hardware.info/?probe=77413a3d9d) | Feb 12, 2022 |
| HP            | t620 Quad Core TC           | [965ced51e6](https://bsd-hardware.info/?probe=965ced51e6) | Feb 12, 2022 |
| MSI           | MS-7C96                     | [c08331ad58](https://bsd-hardware.info/?probe=c08331ad58) | Feb 06, 2022 |
| Raspberry ... | Raspberry Pi 400            | [b35265f8f4](https://bsd-hardware.info/?probe=b35265f8f4) | Jan 29, 2022 |
| Gigabyte      | Z590 VISION G               | [9c73c01062](https://bsd-hardware.info/?probe=9c73c01062) | Jan 28, 2022 |
| WYSE          | D CLASS                     | [5f31ae866c](https://bsd-hardware.info/?probe=5f31ae866c) | Jan 24, 2022 |
| ASRock        | X570 Pro4                   | [d77aae8064](https://bsd-hardware.info/?probe=d77aae8064) | Jan 23, 2022 |
| MSI           | MS-7C56                     | [962ac1c7b0](https://bsd-hardware.info/?probe=962ac1c7b0) | Jan 20, 2022 |
| Unknown       | TI AM335x BeagleBone Bla... | [14d6cfb7a4](https://bsd-hardware.info/?probe=14d6cfb7a4) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [ce75fa56bd](https://bsd-hardware.info/?probe=ce75fa56bd) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [612825abe3](https://bsd-hardware.info/?probe=612825abe3) | Dec 27, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING     | [2ee4c7fefe](https://bsd-hardware.info/?probe=2ee4c7fefe) | Dec 27, 2021 |
| PC Engines    | APU2                        | [d271c4a29f](https://bsd-hardware.info/?probe=d271c4a29f) | Dec 15, 2021 |
| Gigabyte      | H81M-S2PV                   | [0d4c532744](https://bsd-hardware.info/?probe=0d4c532744) | Nov 29, 2021 |
| MSI           | MS-7C56                     | [d4e3f14ad4](https://bsd-hardware.info/?probe=d4e3f14ad4) | Nov 23, 2021 |
| PC Engines    | APU2                        | [15a26da041](https://bsd-hardware.info/?probe=15a26da041) | Nov 14, 2021 |
| Unknown       | Hardkernel ODROID-N2        | [42f6e357c9](https://bsd-hardware.info/?probe=42f6e357c9) | Nov 05, 2021 |
| Yanling       | YL-KBR6L                    | [35f1c905eb](https://bsd-hardware.info/?probe=35f1c905eb) | Nov 04, 2021 |
| HP            | 0A60h                       | [5c227c5b61](https://bsd-hardware.info/?probe=5c227c5b61) | Oct 27, 2021 |
| HP            | ProDesk 600 G1 SFF          | [7f19a8a566](https://bsd-hardware.info/?probe=7f19a8a566) | Oct 26, 2021 |
| Supermicro    | X7SBL                       | [f5b4e8e7ab](https://bsd-hardware.info/?probe=f5b4e8e7ab) | Oct 23, 2021 |
| Lenovo        | SHARKBAY No DPK             | [e762f9146e](https://bsd-hardware.info/?probe=e762f9146e) | Oct 16, 2021 |
| ASUSTek       | P10S-I Series               | [d086bf947a](https://bsd-hardware.info/?probe=d086bf947a) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H                  | [445b53ddba](https://bsd-hardware.info/?probe=445b53ddba) | Oct 15, 2021 |
| Protectli     | FW6                         | [de39c4e316](https://bsd-hardware.info/?probe=de39c4e316) | Oct 15, 2021 |
| MSI           | MS-7D54                     | [ac1f6ee8a6](https://bsd-hardware.info/?probe=ac1f6ee8a6) | Oct 13, 2021 |
| Gigabyte      | B450M DS3H                  | [50e4e13ee0](https://bsd-hardware.info/?probe=50e4e13ee0) | Oct 07, 2021 |
| MSI           | MS-7B53                     | [c7104d301e](https://bsd-hardware.info/?probe=c7104d301e) | Oct 05, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [49173900e7](https://bsd-hardware.info/?probe=49173900e7) | Oct 04, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [d05a877535](https://bsd-hardware.info/?probe=d05a877535) | Oct 03, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [46672cf89f](https://bsd-hardware.info/?probe=46672cf89f) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [838a177f57](https://bsd-hardware.info/?probe=838a177f57) | Sep 30, 2021 |
| HP            | Pro3500 Series              | [abf3223f32](https://bsd-hardware.info/?probe=abf3223f32) | Sep 19, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [7a800aec88](https://bsd-hardware.info/?probe=7a800aec88) | Sep 15, 2021 |
| NF541         | Unknown                     | [deb29af749](https://bsd-hardware.info/?probe=deb29af749) | Sep 11, 2021 |
| MSI           | MS-7A34                     | [decfe43121](https://bsd-hardware.info/?probe=decfe43121) | Sep 10, 2021 |
| PC Engines    | apu4                        | [9557835b54](https://bsd-hardware.info/?probe=9557835b54) | Sep 09, 2021 |
| Gigabyte      | BRi3(H)-10110               | [9aa3540749](https://bsd-hardware.info/?probe=9aa3540749) | Sep 09, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [f860e13b6b](https://bsd-hardware.info/?probe=f860e13b6b) | Sep 08, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1b6bf4666c](https://bsd-hardware.info/?probe=1b6bf4666c) | Sep 05, 2021 |
| Gigabyte      | GA-7VT600                   | [83b86f3e8c](https://bsd-hardware.info/?probe=83b86f3e8c) | Aug 23, 2021 |
| Unknown       | FriendlyElec NanoPi R4S     | [ac10928ac3](https://bsd-hardware.info/?probe=ac10928ac3) | Aug 05, 2021 |
| Unknown       | Pine64 Rock64               | [0df3f7572c](https://bsd-hardware.info/?probe=0df3f7572c) | Jul 23, 2021 |
| ASUSTek       | B202                        | [9f5f0a4117](https://bsd-hardware.info/?probe=9f5f0a4117) | Jul 21, 2021 |
| Unknown       | Pine64 Rock64               | [83c18360fc](https://bsd-hardware.info/?probe=83c18360fc) | Jul 12, 2021 |
| HP            | ProLiant DL360e Gen8        | [30eeb098b0](https://bsd-hardware.info/?probe=30eeb098b0) | Jul 10, 2021 |
| HP            | ProLiant DL320 G5           | [3b4ee33976](https://bsd-hardware.info/?probe=3b4ee33976) | Jul 10, 2021 |
| Foxconn       | AT-7000 Series              | [3802fb98b5](https://bsd-hardware.info/?probe=3802fb98b5) | Jul 10, 2021 |
| Unknown       | Pine64 Rock64               | [106c7823a8](https://bsd-hardware.info/?probe=106c7823a8) | Jul 10, 2021 |
| Unknown       | Pine64 Rock64               | [9cffa29c69](https://bsd-hardware.info/?probe=9cffa29c69) | Jul 08, 2021 |
| ASUSTek       | PRIME B560M-A               | [55f46bc85d](https://bsd-hardware.info/?probe=55f46bc85d) | Jul 07, 2021 |
| Unknown       | Unknown                     | [cfb0e172cb](https://bsd-hardware.info/?probe=cfb0e172cb) | Jun 27, 2021 |
| Dell          | 0GTK4K A02                  | [bb610333d0](https://bsd-hardware.info/?probe=bb610333d0) | Jun 22, 2021 |
| ASRock        | X99 WS                      | [201a7417a5](https://bsd-hardware.info/?probe=201a7417a5) | Jun 11, 2021 |
| Supermicro    | X8DTH-i/6/iF/6F             | [1e8ac47693](https://bsd-hardware.info/?probe=1e8ac47693) | Jun 08, 2021 |
| Supermicro    | X8DTH-i/6/iF/6F             | [bd4a74c5e5](https://bsd-hardware.info/?probe=bd4a74c5e5) | Jun 08, 2021 |
| Supermicro    | X10SLH-N6-ST031             | [e54175f99f](https://bsd-hardware.info/?probe=e54175f99f) | Jun 06, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [58c8cdc060](https://bsd-hardware.info/?probe=58c8cdc060) | Jun 05, 2021 |
| Shuttle       | DS77U                       | [5d1c78145e](https://bsd-hardware.info/?probe=5d1c78145e) | May 30, 2021 |
| ASUSTek       | PRIME B560M-A               | [ca05acd52f](https://bsd-hardware.info/?probe=ca05acd52f) | May 30, 2021 |
| ASRock        | X570M Pro4                  | [1d1a5afcfb](https://bsd-hardware.info/?probe=1d1a5afcfb) | May 28, 2021 |
| Alienware     | Aurora Ryzen Edition        | [b9dc8b182c](https://bsd-hardware.info/?probe=b9dc8b182c) | May 28, 2021 |
| Apple         | PowerMac10,1                | [d098ba539d](https://bsd-hardware.info/?probe=d098ba539d) | May 27, 2021 |
| ASUSTek       | B202                        | [0b66a5fd20](https://bsd-hardware.info/?probe=0b66a5fd20) | May 21, 2021 |
| PC Engines    | APU2                        | [c99a0b0e4d](https://bsd-hardware.info/?probe=c99a0b0e4d) | May 05, 2021 |
| ASRock        | X99 WS                      | [eb20367455](https://bsd-hardware.info/?probe=eb20367455) | May 05, 2021 |
| Supermicro    | X8STi                       | [c615ef1edf](https://bsd-hardware.info/?probe=c615ef1edf) | May 04, 2021 |
| Lenovo        | ThinkCentre M93p 10AAS25... | [a9bbd07ad9](https://bsd-hardware.info/?probe=a9bbd07ad9) | May 03, 2021 |
| PC Engines    | apu1                        | [7b4678c7ef](https://bsd-hardware.info/?probe=7b4678c7ef) | May 03, 2021 |
| ASUSTek       | P10S-I Series               | [6548ae7d88](https://bsd-hardware.info/?probe=6548ae7d88) | May 01, 2021 |
| PC Engines    | apu1                        | [c5ae3337e7](https://bsd-hardware.info/?probe=c5ae3337e7) | May 01, 2021 |
| ASUSTek       | All Series                  | [ef6afe88d7](https://bsd-hardware.info/?probe=ef6afe88d7) | Apr 17, 2021 |
| ECT           | One Computer AMD A10-785... | [de7e23b3e3](https://bsd-hardware.info/?probe=de7e23b3e3) | Apr 07, 2021 |
| Gigabyte      | GB-BXBT-2807                | [25e9765fc0](https://bsd-hardware.info/?probe=25e9765fc0) | Apr 03, 2021 |
| ASUSTek       | All Series                  | [c5bc64e4e9](https://bsd-hardware.info/?probe=c5bc64e4e9) | Mar 22, 2021 |
| ASUSTek       | All Series                  | [700ff7d378](https://bsd-hardware.info/?probe=700ff7d378) | Mar 22, 2021 |
| HP            | ProLiant DL360 Gen9         | [b283b34881](https://bsd-hardware.info/?probe=b283b34881) | Mar 17, 2021 |
| HP            | ProLiant DL360 Gen9         | [bf440e72a1](https://bsd-hardware.info/?probe=bf440e72a1) | Mar 17, 2021 |
| HP            | EliteDesk 800 G5 SFF        | [aaf9bc1c12](https://bsd-hardware.info/?probe=aaf9bc1c12) | Mar 17, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HL0... | [954c65dbcf](https://bsd-hardware.info/?probe=954c65dbcf) | Mar 11, 2021 |
| ASUSTek       | All Series                  | [b4aec46644](https://bsd-hardware.info/?probe=b4aec46644) | Mar 07, 2021 |
| ASUSTek       | All Series                  | [f7b1921594](https://bsd-hardware.info/?probe=f7b1921594) | Mar 07, 2021 |
| ASRock        | G31M-VS2                    | [6c7150dc1b](https://bsd-hardware.info/?probe=6c7150dc1b) | Feb 24, 2021 |
| ASRock        | J4205-ITX                   | [c8e0b22858](https://bsd-hardware.info/?probe=c8e0b22858) | Feb 23, 2021 |
| PC Engines    | apu4                        | [b30884fc0e](https://bsd-hardware.info/?probe=b30884fc0e) | Feb 18, 2021 |
| PC Engines    | apu3                        | [449967354c](https://bsd-hardware.info/?probe=449967354c) | Feb 18, 2021 |
| PC Engines    | apu2                        | [b911e3bec2](https://bsd-hardware.info/?probe=b911e3bec2) | Feb 18, 2021 |
| Shuttle       | DS77U                       | [2d0bd0e99a](https://bsd-hardware.info/?probe=2d0bd0e99a) | Feb 14, 2021 |
| Gigabyte      | Z68A-D3H-B3                 | [e1c3b89d0d](https://bsd-hardware.info/?probe=e1c3b89d0d) | Feb 06, 2021 |
| ASUSTek       | PRIME X470-PRO              | [828a9df369](https://bsd-hardware.info/?probe=828a9df369) | Feb 01, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | [c8af335c01](https://bsd-hardware.info/?probe=c8af335c01) | Jan 29, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | [8c953bac3f](https://bsd-hardware.info/?probe=8c953bac3f) | Jan 25, 2021 |
| ASUSTek       | All Series                  | [7ebe6eee38](https://bsd-hardware.info/?probe=7ebe6eee38) | Jan 25, 2021 |
| ASUSTek       | PRIME X370-PRO              | [2a81a1bd1f](https://bsd-hardware.info/?probe=2a81a1bd1f) | Jan 24, 2021 |
| Sun           | SUNW,Sun-Blade-1500         | [647618a0ca](https://bsd-hardware.info/?probe=647618a0ca) | Jan 22, 2021 |
| PC Engines    | apu1                        | [a5d18dcbbc](https://bsd-hardware.info/?probe=a5d18dcbbc) | Jan 21, 2021 |
| PC Engines    | apu1                        | [70918da1e7](https://bsd-hardware.info/?probe=70918da1e7) | Jan 21, 2021 |
| Sun           | SUNW,Sun-Blade-100          | [299c76eb85](https://bsd-hardware.info/?probe=299c76eb85) | Jan 18, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | [36ef631bfe](https://bsd-hardware.info/?probe=36ef631bfe) | Jan 05, 2021 |
| Gigabyte      | 970A-DS3P                   | [f0b9687ab8](https://bsd-hardware.info/?probe=f0b9687ab8) | Dec 22, 2020 |
| Unknown       | ODYSSEY-X86J4105            | [17749e13c8](https://bsd-hardware.info/?probe=17749e13c8) | Dec 16, 2020 |
| ASUSTek       | PRIME B450M-A               | [d13e0a1749](https://bsd-hardware.info/?probe=d13e0a1749) | Dec 15, 2020 |
| Supermicro    | X11DDW-L                    | [57a5022e27](https://bsd-hardware.info/?probe=57a5022e27) | Dec 14, 2020 |
| ASUSTek       | P4P800-VM                   | [4fe4c14195](https://bsd-hardware.info/?probe=4fe4c14195) | Dec 05, 2020 |
| Apple         | Xserve3,1                   | [7329a7650d](https://bsd-hardware.info/?probe=7329a7650d) | Dec 05, 2020 |
| Gigabyte      | Unknown                     | [8a9ae48d42](https://bsd-hardware.info/?probe=8a9ae48d42) | Dec 01, 2020 |
| HP            | Compaq dc7800 Small Form... | [2b49eb75dc](https://bsd-hardware.info/?probe=2b49eb75dc) | Nov 27, 2020 |
| HP            | Compaq dc7800 Small Form... | [3fe6528682](https://bsd-hardware.info/?probe=3fe6528682) | Nov 27, 2020 |
| Dell          | OptiPlex GX1 500M+          | [deb0d463ab](https://bsd-hardware.info/?probe=deb0d463ab) | Nov 27, 2020 |
| Dell          | OptiPlex GX1 500M+          | [5186eb9e52](https://bsd-hardware.info/?probe=5186eb9e52) | Nov 26, 2020 |
| ASUSTek       | PRIME X370-PRO              | [9cf79cf54b](https://bsd-hardware.info/?probe=9cf79cf54b) | Nov 22, 2020 |
| ASUSTek       | PRIME X370-PRO              | [cab036429d](https://bsd-hardware.info/?probe=cab036429d) | Nov 22, 2020 |
| Unknown       | cavium,ubnt_e300            | [b8524b5002](https://bsd-hardware.info/?probe=b8524b5002) | Nov 20, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B      | [c030400069](https://bsd-hardware.info/?probe=c030400069) | Nov 19, 2020 |
| ASRock        | IMB-191                     | [76991234cd](https://bsd-hardware.info/?probe=76991234cd) | Nov 18, 2020 |
| HARDKERNEL    | ODROID-H2                   | [c03bc18b3a](https://bsd-hardware.info/?probe=c03bc18b3a) | Nov 18, 2020 |
| MSI           | MS-B09012                   | [7ba791108f](https://bsd-hardware.info/?probe=7ba791108f) | Nov 18, 2020 |
| PC Engines    | APU2                        | [b4f5d7d344](https://bsd-hardware.info/?probe=b4f5d7d344) | Nov 16, 2020 |
| Supermicro    | X8DTH-i/6/iF/6F             | [778cb9f428](https://bsd-hardware.info/?probe=778cb9f428) | Nov 16, 2020 |
| Gigabyte      | GB-BXBT-2807                | [c11b475d28](https://bsd-hardware.info/?probe=c11b475d28) | Nov 13, 2020 |
| Lenovo        | ThinkCentre M92p 3212AD2    | [579528e284](https://bsd-hardware.info/?probe=579528e284) | Nov 10, 2020 |
| Gigabyte      | M61SME-S2L                  | [d8809eb5e7](https://bsd-hardware.info/?probe=d8809eb5e7) | Nov 09, 2020 |
| Gigabyte      | M61SME-S2L                  | [e5f658c70a](https://bsd-hardware.info/?probe=e5f658c70a) | Nov 09, 2020 |
| Pegatron      | SKLD4-P1                    | [ea548b4c71](https://bsd-hardware.info/?probe=ea548b4c71) | Nov 08, 2020 |
| Soekris En... | net5501                     | [bd9930a18a](https://bsd-hardware.info/?probe=bd9930a18a) | Nov 06, 2020 |
| Soekris En... | net6501                     | [fdf124653b](https://bsd-hardware.info/?probe=fdf124653b) | Nov 06, 2020 |
| MSI           | MS-7A34                     | [8c87d6b643](https://bsd-hardware.info/?probe=8c87d6b643) | Nov 03, 2020 |
| PC Engines    | apu2                        | [e0361ddbad](https://bsd-hardware.info/?probe=e0361ddbad) | Oct 31, 2020 |
| ASUSTek       | B75M-A                      | [43ece33e8c](https://bsd-hardware.info/?probe=43ece33e8c) | Oct 31, 2020 |
| Intel         | D945GCLF2                   | [58678b0643](https://bsd-hardware.info/?probe=58678b0643) | Oct 30, 2020 |
| Intel         | D945GCLF2                   | [3354fb903b](https://bsd-hardware.info/?probe=3354fb903b) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [973b62551f](https://bsd-hardware.info/?probe=973b62551f) | Oct 30, 2020 |
| eMachines     | EL1200                      | [ae59908738](https://bsd-hardware.info/?probe=ae59908738) | Oct 30, 2020 |
| Acer          | Veriton M6610G              | [7dd00aa8b1](https://bsd-hardware.info/?probe=7dd00aa8b1) | Oct 30, 2020 |
| eMachines     | EL1200                      | [5bc54351be](https://bsd-hardware.info/?probe=5bc54351be) | Oct 30, 2020 |
| ECS           | BSWI-D2                     | [c5b07f5c31](https://bsd-hardware.info/?probe=c5b07f5c31) | Oct 30, 2020 |
| ASRock        | N3160-NUC IPC               | [8d13af2f0b](https://bsd-hardware.info/?probe=8d13af2f0b) | Oct 28, 2020 |
| ASRock        | N3160-NUC IPC               | [8714fe0665](https://bsd-hardware.info/?probe=8714fe0665) | Oct 28, 2020 |
| ASUSTek       | PRIME B250M-C               | [4594c1084c](https://bsd-hardware.info/?probe=4594c1084c) | Oct 28, 2020 |
| Shuttle       | DS77U                       | [c70e526574](https://bsd-hardware.info/?probe=c70e526574) | Oct 27, 2020 |
| PC Engines    | apu2                        | [ce4c41d466](https://bsd-hardware.info/?probe=ce4c41d466) | Oct 26, 2020 |
| Dell          | PowerEdge R230              | [1422e9737b](https://bsd-hardware.info/?probe=1422e9737b) | Oct 26, 2020 |
| Supermicro    | X8STi                       | [1b64902781](https://bsd-hardware.info/?probe=1b64902781) | Oct 26, 2020 |
| HP            | 120-1136                    | [12f3eb0227](https://bsd-hardware.info/?probe=12f3eb0227) | Oct 25, 2020 |
| HP            | ProLiant MicroServer        | [04b6ad9952](https://bsd-hardware.info/?probe=04b6ad9952) | Oct 25, 2020 |
| Supermicro    | X11SSW-F                    | [ca07d7ef48](https://bsd-hardware.info/?probe=ca07d7ef48) | Oct 25, 2020 |
| Gigabyte      | X58A-UD5                    | [6e642641e5](https://bsd-hardware.info/?probe=6e642641e5) | Oct 25, 2020 |
| AZW           | Z83 II                      | [9416876f20](https://bsd-hardware.info/?probe=9416876f20) | Oct 24, 2020 |
| AZW           | Z83 II                      | [19b1b4d85d](https://bsd-hardware.info/?probe=19b1b4d85d) | Oct 24, 2020 |
| Dell          | Precision WorkStation T7... | [c01ce9ec81](https://bsd-hardware.info/?probe=c01ce9ec81) | Oct 24, 2020 |
| PC Engines    | APU2                        | [5cee7fa636](https://bsd-hardware.info/?probe=5cee7fa636) | Oct 22, 2020 |
| MSI           | MS-7345                     | [96cc99accc](https://bsd-hardware.info/?probe=96cc99accc) | Oct 22, 2020 |
| MSI           | MS-7816                     | [337e5b8e0c](https://bsd-hardware.info/?probe=337e5b8e0c) | Oct 22, 2020 |
| ASRock        | DN2800MT                    | [b475aa2ead](https://bsd-hardware.info/?probe=b475aa2ead) | Oct 21, 2020 |
| Intel         | D2500HN                     | [6dbc4dfa33](https://bsd-hardware.info/?probe=6dbc4dfa33) | Oct 21, 2020 |
| Intel         | CRESCENTBAY                 | [42d114559b](https://bsd-hardware.info/?probe=42d114559b) | Oct 21, 2020 |
| PC Engines    | apu2                        | [d1ca549fe7](https://bsd-hardware.info/?probe=d1ca549fe7) | Oct 21, 2020 |
| ZOTAC         | XXXXXX                      | [0f8960bdd3](https://bsd-hardware.info/?probe=0f8960bdd3) | Oct 21, 2020 |
| IBM           | Board                       | [11b0b7012f](https://bsd-hardware.info/?probe=11b0b7012f) | Oct 21, 2020 |
| IBM           | Board                       | [a92c08a920](https://bsd-hardware.info/?probe=a92c08a920) | Oct 21, 2020 |
| IBM           | Board                       | [80d5f15a63](https://bsd-hardware.info/?probe=80d5f15a63) | Oct 21, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | [2cb76e5886](https://bsd-hardware.info/?probe=2cb76e5886) | Oct 21, 2020 |
| PC Engines    | apu2                        | [e6ee8a14d5](https://bsd-hardware.info/?probe=e6ee8a14d5) | Oct 20, 2020 |
| ASUSTek       | Z170-K                      | [19cb3ccc34](https://bsd-hardware.info/?probe=19cb3ccc34) | Oct 20, 2020 |
| Intel         | S3000AH                     | [f5b858601a](https://bsd-hardware.info/?probe=f5b858601a) | Oct 20, 2020 |
| Intel         | D2500HN                     | [4b432dcb3d](https://bsd-hardware.info/?probe=4b432dcb3d) | Oct 20, 2020 |
| PC Engines    | APU2                        | [b95ef9962d](https://bsd-hardware.info/?probe=b95ef9962d) | Oct 20, 2020 |
| PC Engines    | APU2                        | [aecf376503](https://bsd-hardware.info/?probe=aecf376503) | Oct 20, 2020 |
| Unknown       | Unknown                     | [bedb4a4b37](https://bsd-hardware.info/?probe=bedb4a4b37) | Oct 20, 2020 |
| Unknown       | Unknown                     | [a28ef1d2b8](https://bsd-hardware.info/?probe=a28ef1d2b8) | Oct 20, 2020 |
| PC Engines    | apu1                        | [c77b06b3eb](https://bsd-hardware.info/?probe=c77b06b3eb) | Oct 20, 2020 |
| Dell          | PowerEdge R620              | [7671a495d1](https://bsd-hardware.info/?probe=7671a495d1) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | [c1a2bc7a51](https://bsd-hardware.info/?probe=c1a2bc7a51) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | [c1c5ee566c](https://bsd-hardware.info/?probe=c1c5ee566c) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | [af87ddbbaa](https://bsd-hardware.info/?probe=af87ddbbaa) | Oct 19, 2020 |
| ASUSTek       | P10S-I Series               | [1a0e9f0100](https://bsd-hardware.info/?probe=1a0e9f0100) | Oct 19, 2020 |
| Unknown       | Unknown                     | [a3db8641e6](https://bsd-hardware.info/?probe=a3db8641e6) | Oct 19, 2020 |
| PC Engines    | apu4                        | [e4cd6d0b48](https://bsd-hardware.info/?probe=e4cd6d0b48) | Oct 19, 2020 |
| PC Engines    | APU                         | [0cf4f6a5f9](https://bsd-hardware.info/?probe=0cf4f6a5f9) | Oct 19, 2020 |
| Lenovo        | SHARKBAY WIN                | [53feb1fec6](https://bsd-hardware.info/?probe=53feb1fec6) | Oct 19, 2020 |
| ASRock        | IMB-191                     | [4ac9e9cf2a](https://bsd-hardware.info/?probe=4ac9e9cf2a) | Oct 19, 2020 |
| PC Engines    | apu2                        | [064e7167a0](https://bsd-hardware.info/?probe=064e7167a0) | Oct 19, 2020 |
| Dell          | OptiPlex 3060               | [13992dbb10](https://bsd-hardware.info/?probe=13992dbb10) | Oct 19, 2020 |
| PC Engines    | apu2                        | [a5b1c3a559](https://bsd-hardware.info/?probe=a5b1c3a559) | Oct 19, 2020 |
| Dell          | PowerEdge T320              | [75c395f941](https://bsd-hardware.info/?probe=75c395f941) | Oct 19, 2020 |
| Dell          | PowerEdge 1950              | [3cfcdfce6d](https://bsd-hardware.info/?probe=3cfcdfce6d) | Oct 19, 2020 |
| Dell          | PowerEdge 1950              | [0865193e7e](https://bsd-hardware.info/?probe=0865193e7e) | Oct 19, 2020 |
| Dell          | PowerEdge R610              | [2ea539bbd3](https://bsd-hardware.info/?probe=2ea539bbd3) | Oct 19, 2020 |
| Dell          | OptiPlex 7020               | [293e6af35e](https://bsd-hardware.info/?probe=293e6af35e) | Oct 19, 2020 |
| PC Engines    | apu2                        | [2ab3051cb8](https://bsd-hardware.info/?probe=2ab3051cb8) | Oct 19, 2020 |
| PC Engines    | apu4                        | [f0116986e0](https://bsd-hardware.info/?probe=f0116986e0) | Oct 19, 2020 |
| IBM           | Board                       | [af2f64a7a8](https://bsd-hardware.info/?probe=af2f64a7a8) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | [dc7b96e637](https://bsd-hardware.info/?probe=dc7b96e637) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | [0184fcedcf](https://bsd-hardware.info/?probe=0184fcedcf) | Oct 19, 2020 |
| ASUSTek       | PRIME X570-P                | [b33e2a5177](https://bsd-hardware.info/?probe=b33e2a5177) | Oct 19, 2020 |
| PC Engines    | apu1                        | [576f4db9e1](https://bsd-hardware.info/?probe=576f4db9e1) | Oct 19, 2020 |
| PC Engines    | apu2                        | [e4030e5ee2](https://bsd-hardware.info/?probe=e4030e5ee2) | Oct 19, 2020 |
| PC Engines    | apu2                        | [ca0480a30d](https://bsd-hardware.info/?probe=ca0480a30d) | Oct 19, 2020 |
| Bluechip C... | bluechip BUSINESSline Wo... | [6dc86d6a5b](https://bsd-hardware.info/?probe=6dc86d6a5b) | Oct 19, 2020 |
| Unknown       | Unknown                     | [e36fc2b2b2](https://bsd-hardware.info/?probe=e36fc2b2b2) | Oct 19, 2020 |
| ASRock        | N68C-S UCC                  | [027fbd78f5](https://bsd-hardware.info/?probe=027fbd78f5) | Oct 19, 2020 |
| ASRock        | A75M-ITX                    | [dff827c2ae](https://bsd-hardware.info/?probe=dff827c2ae) | Oct 19, 2020 |
| PC Engines    | apu1                        | [8aade944d5](https://bsd-hardware.info/?probe=8aade944d5) | Oct 19, 2020 |
| PC Engines    | apu4                        | [ee8a1317f9](https://bsd-hardware.info/?probe=ee8a1317f9) | Oct 19, 2020 |
| Protectli     | FW6                         | [1454991c98](https://bsd-hardware.info/?probe=1454991c98) | Aug 27, 2020 |
| PC Engines    | apu4                        | [8f4ed98a45](https://bsd-hardware.info/?probe=8f4ed98a45) | Aug 21, 2020 |
| Gigabyte      | X58A-UD5                    | [63a429ad0e](https://bsd-hardware.info/?probe=63a429ad0e) | Aug 16, 2020 |
| Dell          | OptiPlex 745                | [6de04c2c9c](https://bsd-hardware.info/?probe=6de04c2c9c) | Aug 14, 2020 |
| PC Engines    | apu4                        | [f0f8a22656](https://bsd-hardware.info/?probe=f0f8a22656) | Aug 05, 2020 |
| Intel         | ChiefRiver                  | [022d2761b9](https://bsd-hardware.info/?probe=022d2761b9) | Aug 03, 2020 |
| PC Engines    | apu3                        | [1eaf8a1484](https://bsd-hardware.info/?probe=1eaf8a1484) | Aug 03, 2020 |
| PC Engines    | APU3                        | [4980462667](https://bsd-hardware.info/?probe=4980462667) | Aug 03, 2020 |
| PC Engines    | APU3                        | [975e23e09d](https://bsd-hardware.info/?probe=975e23e09d) | Aug 03, 2020 |
| Shuttle       | DS437                       | [aa350b6b92](https://bsd-hardware.info/?probe=aa350b6b92) | Aug 03, 2020 |
| PC Engines    | apu2                        | [fe5c2f4838](https://bsd-hardware.info/?probe=fe5c2f4838) | Aug 03, 2020 |
| Lenovo        | ThinkCentre M92p 3212AD2    | [ca76cc5467](https://bsd-hardware.info/?probe=ca76cc5467) | Jul 30, 2020 |
| ASRock        | E350M1                      | [08eec78cdf](https://bsd-hardware.info/?probe=08eec78cdf) | Jul 25, 2020 |
| Pegatron      | 2A73                        | [05dea28605](https://bsd-hardware.info/?probe=05dea28605) | Jul 21, 2020 |
| PC Engines    | apu4                        | [52c611855b](https://bsd-hardware.info/?probe=52c611855b) | Jul 12, 2020 |
| ASUSTek       | All Series                  | [e4f1a19012](https://bsd-hardware.info/?probe=e4f1a19012) | Jun 05, 2020 |
| Unknown       | Unknown                     | [4e3b87cc6c](https://bsd-hardware.info/?probe=4e3b87cc6c) | Jun 01, 2020 |
| Sony UK       | Raspberry Pi 4 Model B      | [483af3998c](https://bsd-hardware.info/?probe=483af3998c) | May 28, 2020 |
| Unknown       | Unknown                     | [80a1eda96f](https://bsd-hardware.info/?probe=80a1eda96f) | May 28, 2020 |
| Dell          | PowerEdge T320              | [eec750b5c5](https://bsd-hardware.info/?probe=eec750b5c5) | May 28, 2020 |
| Gigabyte      | M68MT-S2P                   | [08534174df](https://bsd-hardware.info/?probe=08534174df) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | [8e0f831fd8](https://bsd-hardware.info/?probe=8e0f831fd8) | May 27, 2020 |
| Gigabyte      | M68MT-S2P                   | [03ea0992c4](https://bsd-hardware.info/?probe=03ea0992c4) | May 27, 2020 |
| IBM           | Board                       | [1bcc2b8e0b](https://bsd-hardware.info/?probe=1bcc2b8e0b) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | [74b9526162](https://bsd-hardware.info/?probe=74b9526162) | May 27, 2020 |
| Gigabyte      | Unknown                     | [576771182b](https://bsd-hardware.info/?probe=576771182b) | May 25, 2020 |
| Gigabyte      | Unknown                     | [05e8154b2c](https://bsd-hardware.info/?probe=05e8154b2c) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | [8b9481baf2](https://bsd-hardware.info/?probe=8b9481baf2) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | [33c4579f99](https://bsd-hardware.info/?probe=33c4579f99) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OpenBSD 6.8 | 109      | 54.23%  |
| OpenBSD 7.0 | 31       | 15.42%  |
| OpenBSD 6.9 | 31       | 15.42%  |
| OpenBSD 6.7 | 26       | 12.94%  |
| OpenBSD 7.1 | 3        | 1.49%   |
| OpenBSD 6.6 | 1        | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| OpenBSD | 182      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 152      | 83.52%  |
| i386    | 13       | 7.14%   |
| arm64   | 10       | 5.49%   |
| sparc64 | 2        | 1.1%    |
| octeon  | 2        | 1.1%    |
| armv7   | 2        | 1.1%    |
| macppc  | 1        | 0.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 95       | 51.35%  |
| fvwm         | 86       | 46.49%  |
| XFCE         | 2        | 1.08%   |
| i3           | 1        | 0.54%   |
| helloDesktop | 1        | 0.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 109      | 59.24%  |
| X11     | 75       | 40.76%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 173      | 94.02%  |
| SLiM    | 6        | 3.26%   |
| GDM     | 5        | 2.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 156      | 84.78%  |
| ru_RU   | 12       | 6.52%   |
| en_US   | 8        | 4.35%   |
| de_DE   | 3        | 1.63%   |
| C       | 2        | 1.09%   |
| pl_PL   | 1        | 0.54%   |
| fr_FR   | 1        | 0.54%   |
| en_AU   | 1        | 0.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 117      | 63.24%  |
| EFI  | 68       | 36.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 182      | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 128      | 69.95%  |
| GPT  | 55       | 30.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| PC Engines              | 31       | 17.03%  |
| Gigabyte Technology     | 18       | 9.89%   |
| ASUSTek Computer        | 17       | 9.34%   |
| Unknown                 | 16       | 8.79%   |
| Dell                    | 14       | 7.69%   |
| ASRock                  | 13       | 7.14%   |
| Hewlett-Packard         | 11       | 6.04%   |
| MSI                     | 10       | 5.49%   |
| Lenovo                  | 7        | 3.85%   |
| Intel                   | 7        | 3.85%   |
| Supermicro              | 6        | 3.3%    |
| Raspberry Pi Foundation | 4        | 2.2%    |
| Sun                     | 2        | 1.1%    |
| Soekris Engineering     | 2        | 1.1%    |
| Shuttle                 | 2        | 1.1%    |
| Pegatron                | 2        | 1.1%    |
| IBM                     | 2        | 1.1%    |
| Apple                   | 2        | 1.1%    |
| ZOTAC                   | 1        | 0.55%   |
| Yanling                 | 1        | 0.55%   |
| WYSE                    | 1        | 0.55%   |
| Unknown                 | 1        | 0.55%   |
| Sony UK                 | 1        | 0.55%   |
| Protectli               | 1        | 0.55%   |
| NF541                   | 1        | 0.55%   |
| HARDKERNEL              | 1        | 0.55%   |
| Foxconn                 | 1        | 0.55%   |
| eMachines               | 1        | 0.55%   |
| ECT                     | 1        | 0.55%   |
| ECS                     | 1        | 0.55%   |
| Bluechip Computer       | 1        | 0.55%   |
| AZW                     | 1        | 0.55%   |
| Alienware               | 1        | 0.55%   |
| Acer                    | 1        | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 20       | 10.99%  |
| PC Engines apu2                    | 14       | 7.69%   |
| PC Engines apu4                    | 8        | 4.4%    |
| PC Engines apu1                    | 5        | 2.75%   |
| Dell PowerEdge R620                | 4        | 2.2%    |
| PC Engines apu3                    | 3        | 1.65%   |
| ASUS All Series                    | 3        | 1.65%   |
| RPi Raspberry Pi 400               | 2        | 1.1%    |
| RPi Raspberry Pi 4 Model B         | 2        | 1.1%    |
| MSI MS-7A34                        | 2        | 1.1%    |
| Gigabyte M68MT-S2P                 | 2        | 1.1%    |
| ASUS PRIME X370-PRO                | 2        | 1.1%    |
| ZOTAC XXXXXX                       | 1        | 0.55%   |
| Yanling YL-KBR6L                   | 1        | 0.55%   |
| WYSE D CLASS                       | 1        | 0.55%   |
| Supermicro X8STi                   | 1        | 0.55%   |
| Supermicro X8DTH-i/6/iF/6F         | 1        | 0.55%   |
| Supermicro X7SBL                   | 1        | 0.55%   |
| Supermicro X11SSW-F                | 1        | 0.55%   |
| Supermicro X11DDW-L                | 1        | 0.55%   |
| Supermicro X10SLH-N6-ST031         | 1        | 0.55%   |
| Sun SUNW,Sun-Blade-1500            | 1        | 0.55%   |
| Sun SUNW,Sun-Blade-100             | 1        | 0.55%   |
| Sony UK Raspberry Pi 4 Model B     | 1        | 0.55%   |
| Soekris Engineering net6501        | 1        | 0.55%   |
| Soekris Engineering net5501        | 1        | 0.55%   |
| Shuttle DS77U                      | 1        | 0.55%   |
| Shuttle DS437                      | 1        | 0.55%   |
| Protectli FW6                      | 1        | 0.55%   |
| Pegatron SKLD4-P1                  | 1        | 0.55%   |
| Pegatron Compaq dx2400 Microtower  | 1        | 0.55%   |
| PC Engines APU                     | 1        | 0.55%   |
| MSI MS-B09012                      | 1        | 0.55%   |
| MSI MS-7D54                        | 1        | 0.55%   |
| MSI MS-7C96                        | 1        | 0.55%   |
| MSI MS-7C56                        | 1        | 0.55%   |
| MSI MS-7B53                        | 1        | 0.55%   |
| MSI MS-7816                        | 1        | 0.55%   |
| MSI MS-7345                        | 1        | 0.55%   |
| MSI MS-7253                        | 1        | 0.55%   |
| Lenovo ThinkPad T440p 20AWS1HL00   | 1        | 0.55%   |
| Lenovo ThinkPad T400 2768W3A       | 1        | 0.55%   |
| Lenovo ThinkCentre M93p 10AAS25M00 | 1        | 0.55%   |
| Lenovo ThinkCentre M93p 10AAS1MD00 | 1        | 0.55%   |
| Lenovo ThinkCentre M93p 10A8S0CE09 | 1        | 0.55%   |
| Lenovo ThinkCentre M92p 3212AD2    | 1        | 0.55%   |
| Lenovo ThinkCentre M73z 10BB001DRU | 1        | 0.55%   |
| Intel S3000AH                      | 1        | 0.55%   |
| Intel DCP847SKE                    | 1        | 0.55%   |
| Intel D945GSEJT                    | 1        | 0.55%   |
| Intel D945GCLF2                    | 1        | 0.55%   |
| Intel D2500HN                      | 1        | 0.55%   |
| Intel CRESCENTBAY                  | 1        | 0.55%   |
| Intel ChiefRiver                   | 1        | 0.55%   |
| IBM 81832BG                        | 1        | 0.55%   |
| IBM 8173KUB                        | 1        | 0.55%   |
| HP t620 Quad Core TC               | 1        | 0.55%   |
| HP ProLiant MicroServer            | 1        | 0.55%   |
| HP ProLiant DL360e Gen8            | 1        | 0.55%   |
| HP ProLiant DL360 Gen9             | 1        | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Unknown                     | 20       | 10.99%  |
| PC Engines APU2             | 14       | 7.69%   |
| PC Engines apu4             | 8        | 4.4%    |
| Dell PowerEdge              | 8        | 4.4%    |
| ASUS PRIME                  | 7        | 3.85%   |
| PC Engines apu1             | 5        | 2.75%   |
| Lenovo ThinkCentre          | 5        | 2.75%   |
| Dell OptiPlex               | 5        | 2.75%   |
| RPi Raspberry               | 4        | 2.2%    |
| HP ProLiant                 | 4        | 2.2%    |
| PC Engines apu3             | 3        | 1.65%   |
| ASUS All                    | 3        | 1.65%   |
| Sun SUNW                    | 2        | 1.1%    |
| MSI MS-7A34                 | 2        | 1.1%    |
| Lenovo ThinkPad             | 2        | 1.1%    |
| HP Compaq                   | 2        | 1.1%    |
| Gigabyte M68MT-S2P          | 2        | 1.1%    |
| ASUS ROG                    | 2        | 1.1%    |
| ZOTAC XXXXXX                | 1        | 0.55%   |
| Yanling YL-KBR6L            | 1        | 0.55%   |
| WYSE D                      | 1        | 0.55%   |
| Supermicro X8STi            | 1        | 0.55%   |
| Supermicro X8DTH-i          | 1        | 0.55%   |
| Supermicro X7SBL            | 1        | 0.55%   |
| Supermicro X11SSW-F         | 1        | 0.55%   |
| Supermicro X11DDW-L         | 1        | 0.55%   |
| Supermicro X10SLH-N6-ST031  | 1        | 0.55%   |
| Sony UK Raspberry           | 1        | 0.55%   |
| Soekris Engineering net6501 | 1        | 0.55%   |
| Soekris Engineering net5501 | 1        | 0.55%   |
| Shuttle DS77U               | 1        | 0.55%   |
| Shuttle DS437               | 1        | 0.55%   |
| Protectli FW6               | 1        | 0.55%   |
| Pegatron SKLD4-P1           | 1        | 0.55%   |
| Pegatron Compaq             | 1        | 0.55%   |
| PC Engines APU              | 1        | 0.55%   |
| MSI MS-B09012               | 1        | 0.55%   |
| MSI MS-7D54                 | 1        | 0.55%   |
| MSI MS-7C96                 | 1        | 0.55%   |
| MSI MS-7C56                 | 1        | 0.55%   |
| MSI MS-7B53                 | 1        | 0.55%   |
| MSI MS-7816                 | 1        | 0.55%   |
| MSI MS-7345                 | 1        | 0.55%   |
| MSI MS-7253                 | 1        | 0.55%   |
| Intel S3000AH               | 1        | 0.55%   |
| Intel DCP847SKE             | 1        | 0.55%   |
| Intel D945GSEJT             | 1        | 0.55%   |
| Intel D945GCLF2             | 1        | 0.55%   |
| Intel D2500HN               | 1        | 0.55%   |
| Intel CRESCENTBAY           | 1        | 0.55%   |
| Intel ChiefRiver            | 1        | 0.55%   |
| IBM 81832BG                 | 1        | 0.55%   |
| IBM 8173KUB                 | 1        | 0.55%   |
| HP t620                     | 1        | 0.55%   |
| HP ProDesk                  | 1        | 0.55%   |
| HP Pro3500                  | 1        | 0.55%   |
| HP EliteDesk                | 1        | 0.55%   |
| HP 120-1136                 | 1        | 0.55%   |
| HARDKERNEL ODROID-H2        | 1        | 0.55%   |
| Gigabyte Z68A-D3H-B3        | 1        | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 24       | 13.19%  |
| 2019    | 22       | 12.09%  |
| 2016    | 19       | 10.44%  |
| Unknown | 18       | 9.89%   |
| 2020    | 17       | 9.34%   |
| 2014    | 15       | 8.24%   |
| 2017    | 8        | 4.4%    |
| 2013    | 8        | 4.4%    |
| 2012    | 8        | 4.4%    |
| 2008    | 8        | 4.4%    |
| 2021    | 6        | 3.3%    |
| 2011    | 6        | 3.3%    |
| 2015    | 5        | 2.75%   |
| 2010    | 4        | 2.2%    |
| 2007    | 4        | 2.2%    |
| 2009    | 3        | 1.65%   |
| 2006    | 2        | 1.1%    |
| 2022    | 1        | 0.55%   |
| 2005    | 1        | 0.55%   |
| 2004    | 1        | 0.55%   |
| 2003    | 1        | 0.55%   |
| 2001    | 1        | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 182      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 150      | 82.42%  |
| Yes  | 32       | 17.58%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 4.01-8.0        | 52       | 28.57%  |
| 8.01-16.0       | 28       | 15.38%  |
| 16.01-24.0      | 22       | 12.09%  |
| 3.01-4.0        | 15       | 8.24%   |
| 32.01-64.0      | 14       | 7.69%   |
| 2.01-3.0        | 12       | 6.59%   |
| 1.01-2.0        | 10       | 5.49%   |
| 64.01-256.0     | 8        | 4.4%    |
| 0.01-0.5        | 7        | 3.85%   |
| 24.01-32.0      | 6        | 3.3%    |
| 0.51-1.0        | 6        | 3.3%    |
| More than 256.0 | 2        | 1.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 133      | 73.08%  |
| 0.51-1.0   | 19       | 10.44%  |
| 0          | 15       | 8.24%   |
| 1.01-2.0   | 6        | 3.3%    |
| 4.01-8.0   | 4        | 2.2%    |
| Unknown    | 3        | 1.65%   |
| 16.01-24.0 | 1        | 0.55%   |
| 8.01-16.0  | 1        | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 94       | 49.47%  |
| 2      | 49       | 25.79%  |
| 3      | 22       | 11.58%  |
| 4      | 12       | 6.32%   |
| 5      | 3        | 1.58%   |
| 0      | 3        | 1.58%   |
| 10     | 2        | 1.05%   |
| 7      | 2        | 1.05%   |
| 6      | 2        | 1.05%   |
| 12     | 1        | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 181      | 99.45%  |
| Yes       | 1        | 0.55%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 164      | 90.11%  |
| No        | 18       | 9.89%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 140      | 76.92%  |
| Yes       | 42       | 23.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 164      | 90.11%  |
| Yes       | 18       | 9.89%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 32       | 17.58%  |
| Russia       | 32       | 17.58%  |
| Germany      | 27       | 14.84%  |
| France       | 11       | 6.04%   |
| UK           | 8        | 4.4%    |
| Switzerland  | 8        | 4.4%    |
| Poland       | 8        | 4.4%    |
| Netherlands  | 7        | 3.85%   |
| Taiwan       | 5        | 2.75%   |
| Sweden       | 5        | 2.75%   |
| Spain        | 5        | 2.75%   |
| Austria      | 5        | 2.75%   |
| Ukraine      | 4        | 2.2%    |
| Norway       | 3        | 1.65%   |
| Romania      | 2        | 1.1%    |
| Italy        | 2        | 1.1%    |
| Denmark      | 2        | 1.1%    |
| UAE          | 1        | 0.55%   |
| Saudi Arabia | 1        | 0.55%   |
| New Zealand  | 1        | 0.55%   |
| Moldova      | 1        | 0.55%   |
| Jamaica      | 1        | 0.55%   |
| Indonesia    | 1        | 0.55%   |
| India        | 1        | 0.55%   |
| Hungary      | 1        | 0.55%   |
| Finland      | 1        | 0.55%   |
| Estonia      | 1        | 0.55%   |
| Cyprus       | 1        | 0.55%   |
| Croatia      | 1        | 0.55%   |
| Canada       | 1        | 0.55%   |
| Bulgaria     | 1        | 0.55%   |
| Brazil       | 1        | 0.55%   |
| Australia    | 1        | 0.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Moscow                     | 14       | 7.53%   |
| Berlin                     | 9        | 4.84%   |
| Amsterdam                  | 6        | 3.23%   |
| New Taipei                 | 5        | 2.69%   |
| St Petersburg              | 4        | 2.15%   |
| Zurich                     | 3        | 1.61%   |
| Wittersham                 | 3        | 1.61%   |
| Vienna                     | 3        | 1.61%   |
| Syeverodonets'k            | 3        | 1.61%   |
| Miedziana Gora             | 3        | 1.61%   |
| Malmo                      | 3        | 1.61%   |
| Lausanne                   | 3        | 1.61%   |
| Ibiza Town                 | 3        | 1.61%   |
| Vladivostok                | 2        | 1.08%   |
| Svenstrup                  | 2        | 1.08%   |
| Skien                      | 2        | 1.08%   |
| Saint-Martin-d'HГЁres    | 2        | 1.08%   |
| Paris                      | 2        | 1.08%   |
| Orsk                       | 2        | 1.08%   |
| Onalaska                   | 2        | 1.08%   |
| Oensingen                  | 2        | 1.08%   |
| Lebanon                    | 2        | 1.08%   |
| Gummersbach                | 2        | 1.08%   |
| Gdansk                     | 2        | 1.08%   |
| Braunschweig               | 2        | 1.08%   |
| Atlanta                    | 2        | 1.08%   |
| Zhukovskiy                 | 1        | 0.54%   |
| Zagreb                     | 1        | 0.54%   |
| Zagnansk                   | 1        | 0.54%   |
| Wroclaw                    | 1        | 0.54%   |
| Wolfsburg                  | 1        | 0.54%   |
| Wheaton                    | 1        | 0.54%   |
| Waukesha                   | 1        | 0.54%   |
| Voskresensk                | 1        | 0.54%   |
| Volgograd                  | 1        | 0.54%   |
| Vechta                     | 1        | 0.54%   |
| Varpalota                  | 1        | 0.54%   |
| Van Nuys                   | 1        | 0.54%   |
| Ust'-Charyshskaya Pristan' | 1        | 0.54%   |
| Turrivalignani             | 1        | 0.54%   |
| Tallinn                    | 1        | 0.54%   |
| Sydney                     | 1        | 0.54%   |
| Surgut                     | 1        | 0.54%   |
| Sundbyberg                 | 1        | 0.54%   |
| Stockholm                  | 1        | 0.54%   |
| Springfield                | 1        | 0.54%   |
| Soresina                   | 1        | 0.54%   |
| Sofia                      | 1        | 0.54%   |
| Sheffield                  | 1        | 0.54%   |
| Sedavi                     | 1        | 0.54%   |
| Seattle                    | 1        | 0.54%   |
| Saint-Herblain             | 1        | 0.54%   |
| Ryazan                     | 1        | 0.54%   |
| Rubtsovsk                  | 1        | 0.54%   |
| Roubaix                    | 1        | 0.54%   |
| Riyadh                     | 1        | 0.54%   |
| Rivne                      | 1        | 0.54%   |
| Punta Gorda                | 1        | 0.54%   |
| Porto Alegre               | 1        | 0.54%   |
| Port Byron                 | 1        | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 36       | 60     | 13.79%  |
| WDC                                | 33       | 43     | 12.64%  |
| Samsung Electronics                | 23       | 39     | 8.81%   |
| Kingston                           | 21       | 25     | 8.05%   |
| NVMe                               | 18       | 23     | 6.9%    |
| Phison                             | 13       | 15     | 4.98%   |
| OPENBSD                            | 10       | 12     | 3.83%   |
| Hitachi                            | 10       | 14     | 3.83%   |
| Crucial                            | 10       | 20     | 3.83%   |
| Intel                              | 8        | 12     | 3.07%   |
| Toshiba                            | 7        | 7      | 2.68%   |
| SanDisk                            | 7        | 9      | 2.68%   |
| HGST                               | 7        | 12     | 2.68%   |
| Dell                               | 6        | 10     | 2.3%    |
| Transcend                          | 5        | 12     | 1.92%   |
| A-DATA Technology                  | 4        | 5      | 1.53%   |
| USB                                | 3        | 3      | 1.15%   |
| Hewlett-Packard                    | 3        | 8      | 1.15%   |
| SK Hynix                           | 2        | 2      | 0.77%   |
| Multiple                           | 2        | 2      | 0.77%   |
| MAXTOR                             | 2        | 3      | 0.77%   |
| LSI                                | 2        | 4      | 0.77%   |
| ASMT                               | 2        | 2      | 0.77%   |
| StoreJet                           | 1        | 1      | 0.38%   |
| SSDPR-CX                           | 1        | 1      | 0.38%   |
| SABRENT                            | 1        | 1      | 0.38%   |
| QUMO                               | 1        | 1      | 0.38%   |
| Product:              USB DISK 3.0 | 1        | 1      | 0.38%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.38%   |
| Product:                           | 1        | 1      | 0.38%   |
| PNY                                | 1        | 1      | 0.38%   |
| Patriot                            | 1        | 1      | 0.38%   |
| OCZ                                | 1        | 1      | 0.38%   |
| MidasForce                         | 1        | 1      | 0.38%   |
| Micron Technology                  | 1        | 1      | 0.38%   |
| MEMXPRO                            | 1        | 1      | 0.38%   |
| MaxDigital                         | 1        | 1      | 0.38%   |
| LITEONIT                           | 1        | 1      | 0.38%   |
| Lexar                              | 1        | 1      | 0.38%   |
| JetFlash                           | 1        | 1      | 0.38%   |
| IBM                                | 1        | 1      | 0.38%   |
| HPE                                | 1        | 2      | 0.38%   |
| Hoodisk                            | 1        | 2      | 0.38%   |
| GLOWAY                             | 1        | 1      | 0.38%   |
| Generic                            | 1        | 1      | 0.38%   |
| General                            | 1        | 1      | 0.38%   |
| China                              | 1        | 1      | 0.38%   |
| asmedia                            | 1        | 1      | 0.38%   |
| Apple                              | 1        | 1      | 0.38%   |
| Apacer                             | 1        | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Phison SATA SSD 16GB               | 11       | 3.87%   |
| OPENBSD SR RAID 1 1TB              | 9        | 3.17%   |
| Samsung SSD 860 EVO mSATA 500GB    | 4        | 1.41%   |
| NVMe Samsung SSD 970 250GB         | 4        | 1.41%   |
| Dell PERC H710 282GB               | 4        | 1.41%   |
| WDC WD6400AARS-00Y5B1 640GB        | 3        | 1.06%   |
| USB SanDisk 3.2Gen1 16GB           | 3        | 1.06%   |
| Toshiba MQ04ABF100 1TB             | 3        | 1.06%   |
| Seagate ST250DM000-1BD141 250GB    | 3        | 1.06%   |
| Kingston SUV500MS240G 240GB        | 3        | 1.06%   |
| HGST HUS724020ALA640 2TB           | 3        | 1.06%   |
| Crucial CT120BX500SSD1 120GB       | 3        | 1.06%   |
| WDC WD10EADS-00M2B0 1TB            | 2        | 0.7%    |
| WDC WD Elements 25A1 4TB           | 2        | 0.7%    |
| Seagate ST3320418AS 320GB          | 2        | 0.7%    |
| Seagate ST3250318AS 250GB          | 2        | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB     | 2        | 0.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 0.7%    |
| SanDisk Ultra Fit 16GB             | 2        | 0.7%    |
| SanDisk Ultra 32GB                 | 2        | 0.7%    |
| Samsung SSD 860 EVO M.2 1TB        | 2        | 0.7%    |
| Samsung SSD 860 EVO 250GB          | 2        | 0.7%    |
| Samsung SSD 850 EVO M.2 250GB      | 2        | 0.7%    |
| Samsung SSD 850 EVO 1TB            | 2        | 0.7%    |
| Samsung Flash Drive FIT 32GB       | 2        | 0.7%    |
| NVMe Samsung SSD 960 500GB         | 2        | 0.7%    |
| Multiple Card Reader               | 2        | 0.7%    |
| Kingston SUV500MS120G 120GB        | 2        | 0.7%    |
| Kingston SUV500240G 240GB          | 2        | 0.7%    |
| Kingston SMS200S360G 64GB          | 2        | 0.7%    |
| Kingston SMS200S330G 32GB          | 2        | 0.7%    |
| Kingston SA400S37240G 240GB        | 2        | 0.7%    |
| Intel SSDSC2BW240H6 240GB          | 2        | 0.7%    |
| HGST HTS541010A7E630 1TB           | 2        | 0.7%    |
| Crucial M4-CT064M4SSD2 64GB        | 2        | 0.7%    |
| Crucial CT256MX100SSD1 256GB       | 2        | 0.7%    |
| Crucial CT240BX500SSD1 240GB       | 2        | 0.7%    |
| Crucial CT1000MX500SSD1 1TB        | 2        | 0.7%    |
| ASMT 2115 500GB                    | 2        | 0.7%    |
| WDC WDS500G2B0A-00SM50 500GB       | 1        | 0.35%   |
| WDC WDS250G2B0A-00SM50 250GB       | 1        | 0.35%   |
| WDC WDS240G2G0B-00EPW0 240GB       | 1        | 0.35%   |
| WDC WD82PURZ-85TEUY0 8TB           | 1        | 0.35%   |
| WDC WD5000LUCT-63C26Y0 500GB       | 1        | 0.35%   |
| WDC WD5000BPKX-00HPJT0 500GB       | 1        | 0.35%   |
| WDC WD5000AAKX-603CA0 500GB        | 1        | 0.35%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 1        | 0.35%   |
| WDC WD5000AAKS-00D2B0 500GB        | 1        | 0.35%   |
| WDC WD30EZRZ-00Z5HB0 3TB           | 1        | 0.35%   |
| WDC WD30EZRZ-00GXCB0 3TB           | 1        | 0.35%   |
| WDC WD2500BEVT-22A23T0 250GB       | 1        | 0.35%   |
| WDC WD20PURX-64P6ZY0 2TB           | 1        | 0.35%   |
| WDC WD20EFAX-68FB5N0 2TB           | 1        | 0.35%   |
| WDC WD2002FAEX-007BA0 2TB          | 1        | 0.35%   |
| WDC WD2000FYYZ-01UL1B1 2TB         | 1        | 0.35%   |
| WDC WD1602ABJS-43P5A0 160GB        | 1        | 0.35%   |
| WDC WD1600JB-00REA0 160GB          | 1        | 0.35%   |
| WDC WD1600AAJS-60B4A0 160GB        | 1        | 0.35%   |
| WDC WD15EADS-00P8B0 1.5TB          | 1        | 0.35%   |
| WDC WD1500HLFS-01G6U4 150GB        | 1        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 36       | 60     | 24.49%  |
| WDC                                | 30       | 40     | 20.41%  |
| OPENBSD                            | 10       | 12     | 6.8%    |
| Hitachi                            | 10       | 14     | 6.8%    |
| NVMe                               | 9        | 12     | 6.12%   |
| Toshiba                            | 7        | 7      | 4.76%   |
| HGST                               | 7        | 12     | 4.76%   |
| Samsung Electronics                | 6        | 9      | 4.08%   |
| Dell                               | 6        | 10     | 4.08%   |
| USB                                | 3        | 3      | 2.04%   |
| Multiple                           | 2        | 2      | 1.36%   |
| MAXTOR                             | 2        | 3      | 1.36%   |
| Hewlett-Packard                    | 2        | 6      | 1.36%   |
| ASMT                               | 2        | 2      | 1.36%   |
| StoreJet                           | 1        | 1      | 0.68%   |
| SSDPR-CX                           | 1        | 1      | 0.68%   |
| SABRENT                            | 1        | 1      | 0.68%   |
| Product:              USB DISK 3.0 | 1        | 1      | 0.68%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.68%   |
| Product:                           | 1        | 1      | 0.68%   |
| MaxDigital                         | 1        | 1      | 0.68%   |
| LSI                                | 1        | 2      | 0.68%   |
| Lexar                              | 1        | 1      | 0.68%   |
| JetFlash                           | 1        | 1      | 0.68%   |
| IBM                                | 1        | 1      | 0.68%   |
| Generic                            | 1        | 1      | 0.68%   |
| General                            | 1        | 1      | 0.68%   |
| China                              | 1        | 1      | 0.68%   |
| Apple                              | 1        | 1      | 0.68%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 21       | 25     | 18.42%  |
| Samsung Electronics | 17       | 30     | 14.91%  |
| Phison              | 13       | 15     | 11.4%   |
| Crucial             | 10       | 20     | 8.77%   |
| NVMe                | 9        | 10     | 7.89%   |
| Intel               | 8        | 12     | 7.02%   |
| SanDisk             | 7        | 9      | 6.14%   |
| Transcend           | 5        | 12     | 4.39%   |
| A-DATA Technology   | 4        | 5      | 3.51%   |
| WDC                 | 3        | 3      | 2.63%   |
| SK Hynix            | 2        | 2      | 1.75%   |
| QUMO                | 1        | 1      | 0.88%   |
| PNY                 | 1        | 1      | 0.88%   |
| Patriot             | 1        | 1      | 0.88%   |
| OCZ                 | 1        | 1      | 0.88%   |
| MidasForce          | 1        | 1      | 0.88%   |
| Micron Technology   | 1        | 1      | 0.88%   |
| MEMXPRO             | 1        | 1      | 0.88%   |
| LSI                 | 1        | 2      | 0.88%   |
| LITEONIT            | 1        | 1      | 0.88%   |
| HPE                 | 1        | 2      | 0.88%   |
| Hoodisk             | 1        | 2      | 0.88%   |
| Hewlett-Packard     | 1        | 2      | 0.88%   |
| GLOWAY              | 1        | 1      | 0.88%   |
| asmedia             | 1        | 1      | 0.88%   |
| Apacer              | 1        | 1      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 104      | 208    | 51.23%  |
| SSD  | 98       | 162    | 48.28%  |
| NVMe | 1        | 1      | 0.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 171      | 370    | 99.42%  |
| NVMe | 1        | 1      | 0.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 145      | 232    | 65.61%  |
| 0.51-1.0        | 46       | 71     | 20.81%  |
| 1.01-2.0        | 15       | 46     | 6.79%   |
| 3.01-4.0        | 7        | 8      | 3.17%   |
| 4.01-10.0       | 4        | 7      | 1.81%   |
| 2.01-3.0        | 3        | 5      | 1.36%   |
| More than 100.0 | 1        | 1      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 54       | 29.51%  |
| 251-500        | 42       | 22.95%  |
| 1-20           | 25       | 13.66%  |
| 51-100         | 22       | 12.02%  |
| 21-50          | 15       | 8.2%    |
| More than 3000 | 8        | 4.37%   |
| 501-1000       | 8        | 4.37%   |
| 1001-2000      | 6        | 3.28%   |
| 2001-3000      | 3        | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 125      | 66.84%  |
| 21-50          | 20       | 10.7%   |
| 101-250        | 17       | 9.09%   |
| 51-100         | 10       | 5.35%   |
| 501-1000       | 6        | 3.21%   |
| 1001-2000      | 4        | 2.14%   |
| 251-500        | 3        | 1.6%    |
| More than 3000 | 1        | 0.53%   |
| 2001-3000      | 1        | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba MQ04ABF100 1TB            | 2        | 2      | 8%      |
| Kingston SMS200S330G 32GB         | 2        | 3      | 8%      |
| HGST HTS541010A7E630 1TB          | 2        | 3      | 8%      |
| WDC WD10SPZX-24Z10 1TB            | 1        | 1      | 4%      |
| WDC WD10EADS-00M2B0 1TB           | 1        | 1      | 4%      |
| Transcend 3E128-TS2-550B01 100GB  | 1        | 4      | 4%      |
| Seagate ST9500325AS 500GB         | 1        | 1      | 4%      |
| Seagate ST9160310AS 160GB         | 1        | 2      | 4%      |
| Seagate ST3750640NS 752GB         | 1        | 2      | 4%      |
| Seagate ST3320418AS 320GB         | 1        | 1      | 4%      |
| Seagate ST3120211AS 120GB         | 1        | 1      | 4%      |
| Seagate ST250DM000-1BD141 250GB   | 1        | 1      | 4%      |
| Seagate ST1000DM003-1CH162 1TB    | 1        | 1      | 4%      |
| Samsung Electronics HD154UI 1.5TB | 1        | 1      | 4%      |
| Kingston SV300S37A120G 120GB      | 1        | 1      | 4%      |
| Kingston SMS200S3120G 120GB       | 1        | 1      | 4%      |
| Intel SSDSC2CT180A4 180GB         | 1        | 1      | 4%      |
| Intel SSDSC2BB080G4 80GB          | 1        | 1      | 4%      |
| Hitachi HDS721010CLA332 1TB       | 1        | 2      | 4%      |
| Hitachi HDP725016GLA380 160GB     | 1        | 1      | 4%      |
| GLOWAY FER60GS3-S7 64GB           | 1        | 1      | 4%      |
| A-DATA Technology SU630 240GB     | 1        | 2      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 9      | 28%     |
| Kingston            | 4        | 5      | 16%     |
| WDC                 | 2        | 2      | 8%      |
| Toshiba             | 2        | 2      | 8%      |
| Intel               | 2        | 2      | 8%      |
| Hitachi             | 2        | 3      | 8%      |
| HGST                | 2        | 3      | 8%      |
| Transcend           | 1        | 4      | 4%      |
| Samsung Electronics | 1        | 1      | 4%      |
| GLOWAY              | 1        | 1      | 4%      |
| A-DATA Technology   | 1        | 2      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 9      | 43.75%  |
| WDC                 | 2        | 2      | 12.5%   |
| Toshiba             | 2        | 2      | 12.5%   |
| Hitachi             | 2        | 3      | 12.5%   |
| HGST                | 2        | 3      | 12.5%   |
| Samsung Electronics | 1        | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 20     | 64%     |
| SSD  | 9        | 14     | 36%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB     | 1        | 1      | 50%     |
| Samsung Electronics HD204UI 2TB | 1        | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 132      | 247    | 62.86%  |
| Detected | 51       | 87     | 24.29%  |
| Malfunc  | 25       | 34     | 11.9%   |
| Failed   | 2        | 3      | 0.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 91       | 45.5%   |
| AMD                         | 63       | 31.5%   |
| Samsung Electronics         | 10       | 5%      |
| Broadcom / LSI              | 10       | 5%      |
| Nvidia                      | 5        | 2.5%    |
| Sandisk                     | 4        | 2%      |
| ASMedia Technology          | 3        | 1.5%    |
| VIA Technologies            | 2        | 1%      |
| ULi Electronics             | 2        | 1%      |
| Phison Electronics          | 2        | 1%      |
| Hewlett-Packard             | 2        | 1%      |
| Toshiba                     | 1        | 0.5%    |
| Silicon Image               | 1        | 0.5%    |
| Marvell Technology Group    | 1        | 0.5%    |
| Kingston Technology Company | 1        | 0.5%    |
| HighPoint Technologies      | 1        | 0.5%    |
| Dell                        | 1        | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 31       | 12.81%  |
| AMD FCH SATA Controller [IDE mode]                                               | 15       | 6.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11       | 4.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 10       | 4.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6        | 2.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6        | 2.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6        | 2.48%   |
| AMD 400 Series Chipset SATA Controller                                           | 6        | 2.48%   |
| Nvidia MCP61 SATA Controller                                                     | 5        | 2.07%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5        | 2.07%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 5        | 2.07%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 5        | 2.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4        | 1.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 4        | 1.65%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 4        | 1.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4        | 1.65%   |
| AMD 500 Series Chipset SATA Controller                                           | 4        | 1.65%   |
| Nvidia MCP61 IDE                                                                 | 3        | 1.24%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3        | 1.24%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3        | 1.24%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3        | 1.24%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3        | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3        | 1.24%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3        | 1.24%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 2        | 0.83%   |
| ULi M5229 IDE                                                                    | 2        | 0.83%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2        | 0.83%   |
| Phison E12 NVMe Controller                                                       | 2        | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2        | 0.83%   |
| Intel 82Q35 Express PT IDER Controller                                           | 2        | 0.83%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]              | 2        | 0.83%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                     | 2        | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2        | 0.83%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                     | 2        | 0.83%   |
| Intel 82801EB (ICH5) SATA Controller                                             | 2        | 0.83%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 2        | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2        | 0.83%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2        | 0.83%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 2        | 0.83%   |
| AMD X370 Series Chipset SATA Controller                                          | 2        | 0.83%   |
| AMD FCH IDE Controller                                                           | 2        | 0.83%   |
| AMD CS5536 [Geode companion] IDE                                                 | 2        | 0.83%   |
| AMD 300 Series Chipset SATA Controller                                           | 2        | 0.83%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1        | 0.41%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1        | 0.41%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1        | 0.41%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1        | 0.41%   |
| Sandisk unknown                                                                  | 1        | 0.41%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1        | 0.41%   |
| Samsung NVMe SSD Controller 980                                                  | 1        | 0.41%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                          | 1        | 0.41%   |
| Kingston Company A2000 NVMe SSD                                                  | 1        | 0.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1        | 0.41%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1        | 0.41%   |
| Intel Platform Controller Hub EG20T SATA AHCI Controller                         | 1        | 0.41%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 126      | 60.87%  |
| IDE  | 46       | 22.22%  |
| NVMe | 18       | 8.7%    |
| RAID | 12       | 5.8%    |
| SAS  | 4        | 1.93%   |
| SCSI | 1        | 0.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 95       | 52.2%   |
| AMD     | 70       | 38.46%  |
| ARM     | 12       | 6.59%   |
| Unknown | 4        | 2.2%    |
| PowerPC | 1        | 0.55%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| AMD GX-412TC SOC                                                 | 25       | 13.66%  |
| ARM Cortex-A72 r0p3                                              | 6        | 3.28%   |
| AMD G-T40E Processor                                             | 6        | 3.28%   |
| ARM Cortex-A53 r0p4                                              | 4        | 2.19%   |
|                                                                  | 4        | 2.19%   |
| AMD Ryzen 7 5800X 8-Core Processor                               | 3        | 1.64%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz                               | 2        | 1.09%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                              | 2        | 1.09%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                              | 2        | 1.09%   |
| Intel Core i7-4770K CPU @ 3.50GHz                                | 2        | 1.09%   |
| Intel Core i7-3770 CPU @ 3.40GHz                                 | 2        | 1.09%   |
| Intel Core i5-4570T CPU @ 2.90GHz                                | 2        | 1.09%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz                             | 2        | 1.09%   |
| Intel Celeron CPU 3865U @ 1.80GHz                                | 2        | 1.09%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class)         | 2        | 1.09%   |
| AMD Ryzen 7 5700G with Radeon Graphics                           | 2        | 1.09%   |
| AMD Ryzen 7 2700 Eight-Core Processor                            | 2        | 1.09%   |
| AMD Ryzen 5 3600 6-Core Processor                                | 2        | 1.09%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics                      | 2        | 1.09%   |
| AMD Geode Integrated Processor by PCS ("AuthenticAMD" 586-class) | 2        | 1.09%   |
| AMD E2-1800 APU with Radeon HD Graphics                          | 2        | 1.09%   |
| AMD Athlon II X3 455 Processor                                   | 2        | 1.09%   |
| PowerPC 7447A (Revision 0x101)                                   | 1        | 0.55%   |
| Intel Xeon Gold 5220 CPU @ 2.20GHz                               | 1        | 0.55%   |
| Intel Xeon E-2278G CPU @ 3.40GHz                                 | 1        | 0.55%   |
| Intel Xeon CPU X5680 @ 3.33GHz                                   | 1        | 0.55%   |
| Intel Xeon CPU X5675 @ 3.07GHz                                   | 1        | 0.55%   |
| Intel Xeon CPU W3530 @ 2.80GHz                                   | 1        | 0.55%   |
| Intel Xeon CPU E5620 @ 2.40GHz                                   | 1        | 0.55%   |
| Intel Xeon CPU E5520 @ 2.27GHz                                   | 1        | 0.55%   |
| Intel Xeon CPU E5410 @ 2.33GHz                                   | 1        | 0.55%   |
| Intel Xeon CPU E5320 @ 1.86GHz                                   | 1        | 0.55%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz                               | 1        | 0.55%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz                               | 1        | 0.55%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz                               | 1        | 0.55%   |
| Intel Xeon CPU E5-2403 0 @ 1.80GHz                               | 1        | 0.55%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz                              | 1        | 0.55%   |
| Intel Xeon CPU E3-1230 v6 @ 3.50GHz                              | 1        | 0.55%   |
| Intel Xeon CPU 3065 @ 2.33GHz ("GenuineIntel" 686-class)         | 1        | 0.55%   |
| Intel Pentium Silver N6000 @ 1.10GHz                             | 1        | 0.55%   |
| Intel Pentium III ("GenuineIntel" 686-class, 512KB L2 cache)     | 1        | 0.55%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz                      | 1        | 0.55%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz                      | 1        | 0.55%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz                           | 1        | 0.55%   |
| Intel Pentium D CPU 2.80GHz                                      | 1        | 0.55%   |
| Intel Pentium CPU N4200 @ 1.10GHz                                | 1        | 0.55%   |
| Intel Pentium CPU J4205 @ 1.50GHz                                | 1        | 0.55%   |
| Intel Pentium CPU G4560 @ 3.50GHz                                | 1        | 0.55%   |
| Intel Pentium 4 CPU 3.20GHz ("GenuineIntel" 686-class)           | 1        | 0.55%   |
| Intel Pentium 4 CPU 2.80GHz ("GenuineIntel" 686-class)           | 1        | 0.55%   |
| Intel Pentium 4 CPU 2.80GHz                                      | 1        | 0.55%   |
| Intel Pentium 4 CPU 2.66GHz                                      | 1        | 0.55%   |
| Intel Genuine CPU @ 600MHz                                       | 1        | 0.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz                                | 1        | 0.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz                                | 1        | 0.55%   |
| Intel Core i7-7700K CPU @ 4.20GHz                                | 1        | 0.55%   |
| Intel Core i7-6850K CPU @ 3.60GHz                                | 1        | 0.55%   |
| Intel Core i7-6700 CPU @ 3.40GHz                                 | 1        | 0.55%   |
| Intel Core i7-4770R CPU @ 3.20GHz                                | 1        | 0.55%   |
| Intel Core i7-4770 CPU @ 3.40GHz                                 | 1        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD GX                  | 26       | 14.29%  |
| Intel Xeon              | 21       | 11.54%  |
| Intel Celeron           | 15       | 8.24%   |
| Intel Core i5           | 14       | 7.69%   |
| Intel Core i7           | 13       | 7.14%   |
| ARM Cortex              | 12       | 6.59%   |
| AMD Ryzen 7             | 12       | 6.59%   |
| Other                   | 7        | 3.85%   |
| AMD G                   | 7        | 3.85%   |
| Intel Atom              | 6        | 3.3%    |
| Intel Core i3           | 4        | 2.2%    |
| AMD Ryzen 5             | 4        | 2.2%    |
| Intel Pentium 4         | 3        | 1.65%   |
| Intel Pentium           | 3        | 1.65%   |
| Intel Core 2 Duo        | 3        | 1.65%   |
| AMD Ryzen 3             | 3        | 1.65%   |
| Intel Pentium Dual-Core | 2        | 1.1%    |
| Intel Core 2            | 2        | 1.1%    |
| AMD Geode Integrated    | 2        | 1.1%    |
| AMD E2                  | 2        | 1.1%    |
| AMD Athlon II X3        | 2        | 1.1%    |
| AMD Athlon 64 X2        | 2        | 1.1%    |
| Intel Xeon Gold         | 1        | 0.55%   |
| Intel Pentium Silver    | 1        | 0.55%   |
| Intel Pentium III       | 1        | 0.55%   |
| Intel Pentium Dual      | 1        | 0.55%   |
| Intel Pentium D         | 1        | 0.55%   |
| Intel Genuine           | 1        | 0.55%   |
| Intel Celeron D         | 1        | 0.55%   |
| AMD Turion II Neo       | 1        | 0.55%   |
| AMD Ryzen 7 PRO         | 1        | 0.55%   |
| AMD Phenom II X6        | 1        | 0.55%   |
| AMD Phenom II X4        | 1        | 0.55%   |
| AMD FX                  | 1        | 0.55%   |
| AMD E                   | 1        | 0.55%   |
| AMD Athlon XP           | 1        | 0.55%   |
| AMD Athlon              | 1        | 0.55%   |
| AMD A4                  | 1        | 0.55%   |
| AMD A10                 | 1        | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 63       | 34.62%  |
| Unknown | 38       | 20.88%  |
| 2       | 32       | 17.58%  |
| 1       | 14       | 7.69%   |
| 6       | 11       | 6.04%   |
| 16      | 9        | 4.95%   |
| 8       | 7        | 3.85%   |
| 12      | 5        | 2.75%   |
| 3       | 2        | 1.1%    |
| 36      | 1        | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 131      | 71.58%  |
| Unknown | 46       | 25.14%  |
| 2       | 6        | 3.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 95       | 52.2%   |
| Unknown | 48       | 26.37%  |
| 2       | 39       | 21.43%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 27       | 14.84%  |
| Puma          | 25       | 13.74%  |
| Haswell       | 15       | 8.24%   |
| KabyLake      | 11       | 6.04%   |
| SandyBridge   | 10       | 5.49%   |
| Bobcat        | 10       | 5.49%   |
| Zen 2         | 7        | 3.85%   |
| Silvermont    | 6        | 3.3%    |
| IvyBridge     | 6        | 3.3%    |
| Bonnell       | 6        | 3.3%    |
| Zen           | 5        | 2.75%   |
| Skylake       | 5        | 2.75%   |
| Penryn        | 5        | 2.75%   |
| NetBurst      | 5        | 2.75%   |
| K10           | 5        | 2.75%   |
| Core          | 5        | 2.75%   |
| Westmere      | 4        | 2.2%    |
| Zen+          | 3        | 1.65%   |
| Zen 3         | 3        | 1.65%   |
| Goldmont      | 3        | 1.65%   |
| Piledriver    | 2        | 1.1%    |
| Nehalem       | 2        | 1.1%    |
| K8 Hammer     | 2        | 1.1%    |
| Goldmont plus | 2        | 1.1%    |
| Geode         | 2        | 1.1%    |
| Broadwell     | 2        | 1.1%    |
| P6            | 1        | 0.55%   |
| K6            | 1        | 0.55%   |
| K10 Llano     | 1        | 0.55%   |
| Jaguar        | 1        | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 59       | 42.75%  |
| AMD                                          | 50       | 36.23%  |
| Nvidia                                       | 12       | 8.7%    |
| Matrox Electronics Systems                   | 11       | 7.97%   |
| ASPEED Technology                            | 4        | 2.9%    |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.72%   |
| 3DLabs                                       | 1        | 0.72%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9        | 6.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8        | 5.67%   |
| Matrox Electronics Systems G200eR2                                                       | 6        | 4.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4        | 2.84%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 4        | 2.84%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4        | 2.84%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3        | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 2.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3        | 2.13%   |
| AMD ES1000                                                                               | 3        | 2.13%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 1.42%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 1.42%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2        | 1.42%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2        | 1.42%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2        | 1.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 1.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 1.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 2        | 1.42%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 1.42%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2        | 1.42%   |
| Intel 82865G Integrated Graphics Controller                                              | 2        | 1.42%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 2        | 1.42%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                             | 2        | 1.42%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.42%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 2        | 1.42%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2        | 1.42%   |
| AMD Cezanne                                                                              | 2        | 1.42%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.42%   |
| XGI Technology (eXtreme Graphics Innovation) Z9s/Z9m (XG21 core)                         | 1        | 0.71%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1        | 0.71%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1        | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.71%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.71%   |
| Nvidia GF110 [GeForce GTX 580]                                                           | 1        | 0.71%   |
| Nvidia G96 [GeForce GT 120 Mac Edition]                                                  | 1        | 0.71%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 1        | 0.71%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 0.71%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                                     | 1        | 0.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 0.71%   |
| Intel UHD Graphics 620                                                                   | 1        | 0.71%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 0.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1        | 0.71%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 0.71%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 0.71%   |
| Intel HD Graphics 610                                                                    | 1        | 0.71%   |
| Intel HD Graphics 6000                                                                   | 1        | 0.71%   |
| Intel HD Graphics 530                                                                    | 1        | 0.71%   |
| Intel HD Graphics 510                                                                    | 1        | 0.71%   |
| Intel HD Graphics 500                                                                    | 1        | 0.71%   |
| Intel Crystal Well Integrated Iris Pro Graphics 5200                                     | 1        | 0.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1        | 0.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1        | 0.71%   |
| Intel Coffee Lake UHD Graphics                                                           | 1        | 0.71%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 0.71%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 0.71%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 0.71%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller                                     | 1        | 0.71%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 51       | 27.87%  |
| Other          | 48       | 26.23%  |
| 1 x AMD        | 48       | 26.23%  |
| 1 x Nvidia     | 10       | 5.46%   |
| 1 x Matrox     | 10       | 5.46%   |
| 2 x Intel      | 5        | 2.73%   |
| 1 x ASPEED     | 4        | 2.19%   |
| Intel + Nvidia | 2        | 1.09%   |
| 2 x AMD        | 1        | 0.55%   |
| 1 x XGI        | 1        | 0.55%   |
| Intel + AMD    | 1        | 0.55%   |
| AMD + Matrox   | 1        | 0.55%   |
| 1 x 3DLabs     | 1        | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 120      | 65.57%  |
| Unknown | 63       | 34.43%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 182      | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 12.5%   |
| Goldstar             | 8        | 12.5%   |
| Dell                 | 7        | 10.94%  |
| Ancor Communications | 7        | 10.94%  |
| Philips              | 4        | 6.25%   |
| NEC Computers        | 4        | 6.25%   |
| Iiyama               | 4        | 6.25%   |
| Lenovo               | 3        | 4.69%   |
| Hewlett-Packard      | 3        | 4.69%   |
| LG Display           | 2        | 3.13%   |
| Eizo                 | 2        | 3.13%   |
| BenQ                 | 2        | 3.13%   |
| ASUSTek Computer     | 2        | 3.13%   |
| AOC                  | 2        | 3.13%   |
| Vizio                | 1        | 1.56%   |
| ViewSonic            | 1        | 1.56%   |
| SHI                  | 1        | 1.56%   |
| Medion               | 1        | 1.56%   |
| BOE                  | 1        | 1.56%   |
| Acer                 | 1        | 1.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch  | 3        | 4.55%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                 | 2        | 3.03%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch          | 2        | 3.03%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                     | 2        | 3.03%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                      | 2        | 3.03%   |
| Vizio E320i-A0 VIZ0091 1366x768 700x390mm 31.5-inch                   | 1        | 1.52%   |
| ViewSonic LCD Monitor VSCE032 2560x1440 530x300mm 24.0-inch           | 1        | 1.52%   |
| SHI LCD-TV**** SHI6102 1360x768 700x390mm 31.5-inch                   | 1        | 1.52%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 1        | 1.52%   |
| Samsung Electronics SyncMaster SAM03EF 1680x1050 470x300mm 22.0-inch  | 1        | 1.52%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 380x300mm 19.1-inch  | 1        | 1.52%   |
| Samsung Electronics SyncMaster SAM00A1 1280x1024 340x270mm 17.1-inch  | 1        | 1.52%   |
| Samsung Electronics SMB2340 SAM0691 1920x1080 510x290mm 23.1-inch     | 1        | 1.52%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 800x330mm 34.1-inch      | 1        | 1.52%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch     | 1        | 1.52%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch | 1        | 1.52%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch              | 1        | 1.52%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch              | 1        | 1.52%   |
| Philips LCD Monitor PHLC00B 1280x1024 340x270mm 17.1-inch             | 1        | 1.52%   |
| Philips 190S PHL086B 1280x1024 380x300mm 19.1-inch                    | 1        | 1.52%   |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch         | 1        | 1.52%   |
| NEC Computers LCD190V NEC66D3 1280x1024 380x300mm 19.1-inch           | 1        | 1.52%   |
| NEC Computers EX341R NEC2C7A 3440x1440 800x330mm 34.1-inch            | 1        | 1.52%   |
| NEC Computers EA243WM NEC6866 1920x1200 520x320mm 24.0-inch           | 1        | 1.52%   |
| Medion LCD Monitor MED09A3 1280x1024 380x300mm 19.1-inch              | 1        | 1.52%   |
| LG Display LCD Monitor LGD05D8 1920x1080 340x190mm 15.3-inch          | 1        | 1.52%   |
| LG Display LCD Monitor LGD040A 1920x1080 310x170mm 13.9-inch          | 1        | 1.52%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 530x300mm 24.0-inch              | 1        | 1.52%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch              | 1        | 1.52%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch               | 1        | 1.52%   |
| Iiyama PL3288UH IVM7610 3840x2160 700x390mm 31.5-inch                 | 1        | 1.52%   |
| Iiyama PL2888UH IVM7104 3840x2160 620x340mm 27.8-inch                 | 1        | 1.52%   |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                  | 1        | 1.52%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch      | 1        | 1.52%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch           | 1        | 1.52%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch            | 1        | 1.52%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch              | 1        | 1.52%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 1        | 1.52%   |
| Goldstar L1753S GSM446F 1280x1024 340x270mm 17.1-inch                 | 1        | 1.52%   |
| Goldstar L1715S GSM436F 1280x1024 340x270mm 17.1-inch                 | 1        | 1.52%   |
| Goldstar L1530P GSM3B99 1024x768 300x230mm 14.9-inch                  | 1        | 1.52%   |
| Goldstar 27MP33 GSM5AAE 1920x1080 600x340mm 27.2-inch                 | 1        | 1.52%   |
| Dell UP2715K DEL40B8 3840x2160 600x340mm 27.2-inch                    | 1        | 1.52%   |
| Dell U4919DW DELA107 3840x1080 1200x340mm 49.1-inch                   | 1        | 1.52%   |
| Dell U2715H DELD065 2560x1440 600x340mm 27.2-inch                     | 1        | 1.52%   |
| Dell P2417H DELA0DC 1920x1080 530x300mm 24.0-inch                     | 1        | 1.52%   |
| Dell E2214H DELA09E 1920x1080 480x270mm 21.7-inch                     | 1        | 1.52%   |
| Dell 1909W DELA03D 1440x900 410x260mm 19.1-inch                       | 1        | 1.52%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                  | 1        | 1.52%   |
| BenQ GL940 BNQ7883 1366x768 410x230mm 18.5-inch                       | 1        | 1.52%   |
| BenQ GL2760 BNQ78D5 1920x1080 600x340mm 27.2-inch                     | 1        | 1.52%   |
| ASUSTek Computer VP247 AUS24CA 1920x1080 520x290mm 23.4-inch          | 1        | 1.52%   |
| ASUSTek Computer PB278QV AUS278A 2560x1440 600x340mm 27.2-inch        | 1        | 1.52%   |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                        | 1        | 1.52%   |
| AOC 2270W AOC2270 1920x1080 480x270mm 21.7-inch                       | 1        | 1.52%   |
| Ancor Communications PA249 ACI24B2 1920x1200 520x320mm 24.0-inch      | 1        | 1.52%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 1        | 1.52%   |
| Ancor Communications ASUS VS239 ACI23D2 1920x1080 510x290mm 23.1-inch | 1        | 1.52%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 520x290mm 23.4-inch | 1        | 1.52%   |
| Acer VG220Q ACR06D8 1920x1080 480x270mm 21.7-inch                     | 1        | 1.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 21       | 33.87%  |
| 1280x1024 (SXGA)   | 9        | 14.52%  |
| 3840x2160 (4K)     | 7        | 11.29%  |
| 2560x1440 (QHD)    | 5        | 8.06%   |
| 1440x900 (WXGA+)   | 5        | 8.06%   |
| 1920x1200 (WUXGA)  | 4        | 6.45%   |
| 3440x1440          | 3        | 4.84%   |
| 1366x768 (WXGA)    | 3        | 4.84%   |
| 3840x1080          | 1        | 1.61%   |
| 1680x1050 (WSXGA+) | 1        | 1.61%   |
| 1600x900 (HD+)     | 1        | 1.61%   |
| 1360x768           | 1        | 1.61%   |
| 1024x768 (XGA)     | 1        | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 10       | 16.39%  |
| 19     | 10       | 16.39%  |
| 27     | 9        | 14.75%  |
| 23     | 8        | 13.11%  |
| 31     | 5        | 8.2%    |
| 21     | 4        | 6.56%   |
| 17     | 4        | 6.56%   |
| 34     | 3        | 4.92%   |
| 14     | 2        | 3.28%   |
| 13     | 2        | 3.28%   |
| 49     | 1        | 1.64%   |
| 22     | 1        | 1.64%   |
| 18     | 1        | 1.64%   |
| 15     | 1        | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 26       | 42.62%  |
| 401-500     | 11       | 18.03%  |
| 301-350     | 7        | 11.48%  |
| 601-700     | 6        | 9.84%   |
| 351-400     | 5        | 8.2%    |
| 701-800     | 3        | 4.92%   |
| 201-300     | 2        | 3.28%   |
| 1001-1500   | 1        | 1.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 36       | 60%     |
| 16/10 | 10       | 16.67%  |
| 5/4   | 9        | 15%     |
| 21/9  | 3        | 5%      |
| 4/3   | 1        | 1.67%   |
| 32/9  | 1        | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18       | 30%     |
| 151-200        | 10       | 16.67%  |
| 301-350        | 9        | 15%     |
| 351-500        | 8        | 13.33%  |
| 141-150        | 5        | 8.33%   |
| 251-300        | 4        | 6.67%   |
| 81-90          | 3        | 5%      |
| 101-110        | 1        | 1.67%   |
| 501-1000       | 1        | 1.67%   |
| 91-100         | 1        | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 36       | 58.06%  |
| 101-120 | 10       | 16.13%  |
| 121-160 | 7        | 11.29%  |
| 161-240 | 5        | 8.06%   |
| 1-50    | 4        | 6.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 117      | 63.24%  |
| 1     | 63       | 34.05%  |
| 2     | 4        | 2.16%   |
| 3     | 1        | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 95       | 44.6%   |
| Realtek Semiconductor           | 65       | 30.52%  |
| Broadcom                        | 14       | 6.57%   |
| Qualcomm Atheros                | 11       | 5.16%   |
| Qualcomm Atheros Communications | 5        | 2.35%   |
| U-Blox                          | 4        | 1.88%   |
| VIA Technologies                | 3        | 1.41%   |
| TP-Link                         | 3        | 1.41%   |
| Ralink                          | 3        | 1.41%   |
| 3Com                            | 2        | 0.94%   |
| Oracle/SUN                      | 1        | 0.47%   |
| National Semiconductor          | 1        | 0.47%   |
| MediaTek                        | 1        | 0.47%   |
| LG Electronics                  | 1        | 0.47%   |
| Emulex                          | 1        | 0.47%   |
| Davicom Semiconductor           | 1        | 0.47%   |
| Apple                           | 1        | 0.47%   |
| Accton Technology               | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 53       | 21.72%  |
| Intel I211 Gigabit Network Connection                                                | 24       | 9.84%   |
| Intel I210 Gigabit Network Connection                                                | 19       | 7.79%   |
| Intel 82574L Gigabit Network Connection                                              | 8        | 3.28%   |
| Intel I350 Gigabit Network Connection                                                | 7        | 2.87%   |
| Intel Ethernet Connection I217-LM                                                    | 7        | 2.87%   |
| U-Blox [u-blox 8]                                                                    | 4        | 1.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 4        | 1.64%   |
| Intel Wi-Fi 6 AX200                                                                  | 4        | 1.64%   |
| Realtek RTL8125 2.5GbE Controller                                                    | 3        | 1.23%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 3        | 1.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 3        | 1.23%   |
| VIA VT6105M [Rhine-III]                                                              | 2        | 0.82%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 2        | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 2        | 0.82%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                      | 2        | 0.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 2        | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                | 2        | 0.82%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                            | 2        | 0.82%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                           | 2        | 0.82%   |
| Intel Wireless 7260                                                                  | 2        | 0.82%   |
| Intel Ethernet Controller I225-V                                                     | 2        | 0.82%   |
| Intel Ethernet Connection I217-V                                                     | 2        | 0.82%   |
| Intel Ethernet Connection (7) I219-LM                                                | 2        | 0.82%   |
| Intel Ethernet Connection (2) I219-V                                                 | 2        | 0.82%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                                 | 2        | 0.82%   |
| Intel 82576 Gigabit Network Connection                                               | 2        | 0.82%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                                    | 2        | 0.82%   |
| Intel 82566DM-2 Gigabit Network Connection                                           | 2        | 0.82%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                     | 2        | 0.82%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                                     | 2        | 0.82%   |
| VIA VT6102/VT6103 [Rhine-II]                                                         | 1        | 0.41%   |
| TP-Link TP-LINK Wireless USB Adapter                                                 | 1        | 0.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.41%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 1        | 0.41%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1        | 0.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1        | 0.41%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 0.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 1        | 0.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                                     | 1        | 0.41%   |
| Realtek 802.11n WLAN Adapter                                                         | 1        | 0.41%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 0.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1        | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                            | 1        | 0.41%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 0.41%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170]        | 1        | 0.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1        | 0.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 1        | 0.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1        | 0.41%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                                 | 1        | 0.41%   |
| National DP83815 (MacPhyter) Ethernet Controller                                     | 1        | 0.41%   |
| MediaTek 802.11ac Wireless LAN Card                                                  | 1        | 0.41%   |
| LG Optimus Android Phone [USB tethering mode]                                        | 1        | 0.41%   |
| Intel Wireless 3160                                                                  | 1        | 0.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 1        | 0.41%   |
| Intel Wi-Fi 6 AX201 160MHz                                                           | 1        | 0.41%   |
| Intel Ultimate N WiFi Link 5300                                                      | 1        | 0.41%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller                      | 1        | 0.41%   |
| Intel NM10/ICH7 Family LAN Controller                                                | 1        | 0.41%   |
| Intel I210 Gigabit Fiber Network Connection                                          | 1        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 28.89%  |
| Qualcomm Atheros                | 10       | 22.22%  |
| Realtek Semiconductor           | 9        | 20%     |
| Qualcomm Atheros Communications | 5        | 11.11%  |
| TP-Link                         | 3        | 6.67%   |
| Ralink                          | 3        | 6.67%   |
| MediaTek                        | 1        | 2.22%   |
| Broadcom                        | 1        | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 4        | 8.89%   |
| Intel Wi-Fi 6 AX200                                                                  | 4        | 8.89%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 3        | 6.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 2        | 4.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 2        | 4.44%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                            | 2        | 4.44%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                           | 2        | 4.44%   |
| Intel Wireless 7260                                                                  | 2        | 4.44%   |
| TP-Link TP-LINK Wireless USB Adapter                                                 | 1        | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1        | 2.22%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 1        | 2.22%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1        | 2.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1        | 2.22%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 2.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 1        | 2.22%   |
| Realtek 802.11n WLAN Adapter                                                         | 1        | 2.22%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1        | 2.22%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 2.22%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170]        | 1        | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1        | 2.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 1        | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1        | 2.22%   |
| MediaTek 802.11ac Wireless LAN Card                                                  | 1        | 2.22%   |
| Intel Wireless 3160                                                                  | 1        | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 1        | 2.22%   |
| Intel Wi-Fi 6 AX201 160MHz                                                           | 1        | 2.22%   |
| Intel Ultimate N WiFi Link 5300                                                      | 1        | 2.22%   |
| Intel Centrino Wireless-N 2230                                                       | 1        | 2.22%   |
| Intel Centrino Wireless-N 2200                                                       | 1        | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 1        | 2.22%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 1        | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 90       | 50.85%  |
| Realtek Semiconductor  | 62       | 35.03%  |
| Broadcom               | 13       | 7.34%   |
| VIA Technologies       | 3        | 1.69%   |
| 3Com                   | 2        | 1.13%   |
| Qualcomm Atheros       | 1        | 0.56%   |
| Oracle/SUN             | 1        | 0.56%   |
| National Semiconductor | 1        | 0.56%   |
| Emulex                 | 1        | 0.56%   |
| Davicom Semiconductor  | 1        | 0.56%   |
| Apple                  | 1        | 0.56%   |
| Accton Technology      | 1        | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 53       | 27.46%  |
| Intel I211 Gigabit Network Connection                                         | 24       | 12.44%  |
| Intel I210 Gigabit Network Connection                                         | 19       | 9.84%   |
| Intel 82574L Gigabit Network Connection                                       | 8        | 4.15%   |
| Intel I350 Gigabit Network Connection                                         | 7        | 3.63%   |
| Intel Ethernet Connection I217-LM                                             | 7        | 3.63%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 1.55%   |
| VIA VT6105M [Rhine-III]                                                       | 2        | 1.04%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 1.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.04%   |
| Intel Ethernet Controller I225-V                                              | 2        | 1.04%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 1.04%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.04%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 1.04%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 1.04%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                             | 2        | 1.04%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 1.04%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 1.04%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 1.04%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1        | 0.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1        | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.52%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                                          | 1        | 0.52%   |
| National DP83815 (MacPhyter) Ethernet Controller                              | 1        | 0.52%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller               | 1        | 0.52%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1        | 0.52%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 1        | 0.52%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.52%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 1        | 0.52%   |
| Intel Ethernet Connection I219-LM                                             | 1        | 0.52%   |
| Intel Ethernet Connection (6) I219-V                                          | 1        | 0.52%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.52%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.52%   |
| Intel 82583V Gigabit Network Connection                                       | 1        | 0.52%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.52%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1        | 0.52%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.52%   |
| Intel 82567LM Gigabit Network Connection                                      | 1        | 0.52%   |
| Intel 82562EZ 10/100 Ethernet Controller                                      | 1        | 0.52%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 0.52%   |
| Intel 82546EB Gigabit Ethernet Controller (Copper)                            | 1        | 0.52%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1        | 0.52%   |
| Intel 82541EI Gigabit Ethernet Controller                                     | 1        | 0.52%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 1        | 0.52%   |
| Emulex OneConnect 10Gb NIC (be3)                                              | 1        | 0.52%   |
| Davicom DM9102 Fast Ethernet Controller                                       | 1        | 0.52%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 0.52%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1        | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.52%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 0.52%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 0.52%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1        | 0.52%   |
| Broadcom NetXtreme BCM5714 Gigabit Ethernet                                   | 1        | 0.52%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                 | 1        | 0.52%   |
| Broadcom NetXtreme BCM5703 Gigabit Ethernet                                   | 1        | 0.52%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 1        | 0.52%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                               | 1        | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 164      | 77.36%  |
| WiFi     | 42       | 19.81%  |
| Modem    | 5        | 2.36%   |
| Unknown  | 1        | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 116      | 84.67%  |
| WiFi     | 21       | 15.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 62       | 34.07%  |
| 2     | 44       | 24.18%  |
| 3     | 30       | 16.48%  |
| 4     | 19       | 10.44%  |
| 0     | 17       | 9.34%   |
| 8     | 3        | 1.65%   |
| 7     | 2        | 1.1%    |
| 6     | 2        | 1.1%    |
| 5     | 2        | 1.1%    |
| 12    | 1        | 0.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 182      | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 61.11%  |
| IMC Networks                    | 2        | 11.11%  |
| Realtek Semiconductor           | 1        | 5.56%   |
| Qualcomm Atheros Communications | 1        | 5.56%   |
| Cambridge Silicon Radio         | 1        | 5.56%   |
| ASUSTek Computer                | 1        | 5.56%   |
| Apple                           | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                | 4        | 22.22%  |
| Intel Centrino Bluetooth Wireless Transceiver        | 2        | 11.11%  |
| Intel Bluetooth wireless interface                   | 2        | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 2        | 11.11%  |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip | 2        | 11.11%  |
| Realtek  Bluetooth Adapter                           | 1        | 5.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 1        | 5.56%   |
| Intel AX210 Bluetooth                                | 1        | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 1        | 5.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                   | 1        | 5.56%   |
| Apple Apple Broadcom Built-in Bluetooth              | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 59       | 46.83%  |
| AMD                 | 45       | 35.71%  |
| Nvidia              | 11       | 8.73%   |
| C-Media Electronics | 3        | 2.38%   |
| VIA Technologies    | 2        | 1.59%   |
| ULi Electronics     | 2        | 1.59%   |
| JMTek               | 1        | 0.79%   |
| ESS Technology      | 1        | 0.79%   |
| Creative Labs       | 1        | 0.79%   |
| Blue Microphones    | 1        | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                          | 9        | 5.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9        | 5.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8        | 5.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8        | 5.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6        | 3.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6        | 3.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6        | 3.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5        | 3.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5        | 3.21%   |
| AMD Navi 10 HDMI Audio                                                                            | 5        | 3.21%   |
| Nvidia MCP61 High Definition Audio                                                                | 4        | 2.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4        | 2.56%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4        | 2.56%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3        | 1.92%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3        | 1.92%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3        | 1.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3        | 1.92%   |
| AMD FCH Azalia Controller                                                                         | 3        | 1.92%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3        | 1.92%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                                         | 2        | 1.28%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2        | 1.28%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2        | 1.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2        | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2        | 1.28%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 2        | 1.28%   |
| C-Media Electronics Digital Hifi Audio Digital Hifi Audio SPDIFs                                  | 2        | 1.28%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 1.28%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2        | 1.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 1.28%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 1.28%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1        | 0.64%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1        | 0.64%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 0.64%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 0.64%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 0.64%   |
| Nvidia GF110 High Definition Audio Controller                                                     | 1        | 0.64%   |
| JMTek USB PnP Audio Device                                                                        | 1        | 0.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 0.64%   |
| Intel Jasper Lake HD Audio                                                                        | 1        | 0.64%   |
| Intel Crystal Well HD Audio Controller                                                            | 1        | 0.64%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1        | 0.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1        | 0.64%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1        | 0.64%   |
| Intel Broadwell-U Audio Controller                                                                | 1        | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 0.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1        | 0.64%   |
| Intel 200 Series PCH HD Audio                                                                     | 1        | 0.64%   |
| ESS Technology ES1968 Maestro 2                                                                   | 1        | 0.64%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 1        | 0.64%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 1        | 0.64%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 1        | 0.64%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1        | 0.64%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                                | 1        | 0.64%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1        | 0.64%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1        | 0.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 0.64%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 0.64%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 9        | 47.37%  |
| Transcend           | 2        | 10.53%  |
| Samsung Electronics | 2        | 10.53%  |
| Kingston            | 2        | 10.53%  |
| SK Hynix            | 1        | 5.26%   |
| Ramaxel Technology  | 1        | 5.26%   |
| Nanya Technology    | 1        | 5.26%   |
| Elpida              | 1        | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s          | 2        | 8.33%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s     | 2        | 8.33%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s       | 2        | 8.33%   |
| Unknown RAM Module 512MB DIMM SDRAM                     | 1        | 4.17%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s               | 1        | 4.17%   |
| Unknown RAM Module 512MB DIMM 400MT/s                   | 1        | 4.17%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 1        | 4.17%   |
| Unknown RAM Module 256MB DIMM 333MT/s                   | 1        | 4.17%   |
| Unknown RAM Module 2048MB DIMM DDR2 266MT/s             | 1        | 4.17%   |
| Unknown RAM Module 1GB DIMM 400MT/s                     | 1        | 4.17%   |
| Unknown RAM Module 1024MB DIMM DDR                      | 1        | 4.17%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 1        | 4.17%   |
| Transcend RAM TS1GSK64W6H 8GB DIMM DDR3 1600MT/s        | 1        | 4.17%   |
| Transcend RAM TS128MLQ64V6J 1GB DIMM DDR2 667MT/s       | 1        | 4.17%   |
| SK Hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 667MT/s     | 1        | 4.17%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 4.17%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 4.17%   |
| Samsung RAM M3 78T2953CZ3-CE6 1GB DIMM DDR2 667MT/s     | 1        | 4.17%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s | 1        | 4.17%   |
| Nanya RAM NT1GT64U88D0BY-AD 1024MB DIMM DDR2 800MT/s    | 1        | 4.17%   |
| Elpida RAM EBE11UD8AJWA-8G-E 1024MB DIMM DDR2 800MT/s   | 1        | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 6        | 37.5%   |
| DDR2    | 3        | 18.75%  |
| DDR4    | 2        | 12.5%   |
| DDR     | 2        | 12.5%   |
| Unknown | 2        | 12.5%   |
| SDRAM   | 1        | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 11       | 68.75%  |
| SODIMM | 5        | 31.25%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 4096 | 7        | 35%     |
| 1024 | 5        | 25%     |
| 8192 | 3        | 15%     |
| 512  | 3        | 15%     |
| 2048 | 1        | 5%      |
| 256  | 1        | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 3        | 17.65%  |
| 1333    | 3        | 17.65%  |
| 2400    | 2        | 11.76%  |
| 800     | 2        | 11.76%  |
| 400     | 2        | 11.76%  |
| Unknown | 2        | 11.76%  |
| 667     | 1        | 5.88%   |
| 333     | 1        | 5.88%   |
| 266     | 1        | 5.88%   |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 4        | 44.44%  |
| Chicony Electronics     | 2        | 22.22%  |
| Z-Star Microelectronics | 1        | 11.11%  |
| Quanta                  | 1        | 11.11%  |
| Microdia                | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Z-Star Integrated Camera        | 1        | 11.11%  |
| Quanta VGA WebCam               | 1        | 11.11%  |
| Microdia Ltd., USB  Live camera | 1        | 11.11%  |
| Logitech Webcam C310            | 1        | 11.11%  |
| Logitech Webcam C270            | 1        | 11.11%  |
| Logitech HD Pro Webcam C920     | 1        | 11.11%  |
| Logitech C920 HD Pro Webcam     | 1        | 11.11%  |
| Chicony Ltd., HP 0.3MP Webcam   | 1        | 11.11%  |
| Chicony Integrated Camera       | 1        | 11.11%  |

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
| 0     | 101      | 54.59%  |
| 1     | 50       | 27.03%  |
| 2     | 27       | 14.59%  |
| 3     | 4        | 2.16%   |
| 7     | 2        | 1.08%   |
| 5     | 1        | 0.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 59       | 51.75%  |
| Graphics card            | 22       | 19.3%   |
| Net/wireless             | 8        | 7.02%   |
| Firewire controller      | 8        | 7.02%   |
| Net/ethernet             | 6        | 5.26%   |
| Storage/ata              | 5        | 4.39%   |
| Sound                    | 5        | 4.39%   |
| Storage/raid             | 1        | 0.88%   |

