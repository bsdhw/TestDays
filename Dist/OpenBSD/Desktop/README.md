OpenBSD - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for OpenBSD.

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

Total: 294

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | All Series                  | [ab3b339cf0](https://bsd-hardware.info/?probe=ab3b339cf0) | Sep 24, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [1a89d78fa4](https://bsd-hardware.info/?probe=1a89d78fa4) | Sep 22, 2022 |
| Gigabyte      | H81M-S1                     | [fe9eecb935](https://bsd-hardware.info/?probe=fe9eecb935) | Sep 18, 2022 |
| CncTion       | N5105-4L                    | [2a34dc3fe0](https://bsd-hardware.info/?probe=2a34dc3fe0) | Sep 05, 2022 |
| Dell          | PowerEdge R620              | [66db9eb745](https://bsd-hardware.info/?probe=66db9eb745) | Aug 25, 2022 |
| ASUSTek       | PRIME B460M-A               | [21fed03fa2](https://bsd-hardware.info/?probe=21fed03fa2) | Aug 24, 2022 |
| ASUSTek       | PRIME B460M-A               | [48210e4d2a](https://bsd-hardware.info/?probe=48210e4d2a) | Aug 24, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | [9267873961](https://bsd-hardware.info/?probe=9267873961) | Aug 13, 2022 |
| Biostar       | TA880GU3+                   | [8b0c8541b3](https://bsd-hardware.info/?probe=8b0c8541b3) | Aug 06, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [f2836f4a6c](https://bsd-hardware.info/?probe=f2836f4a6c) | Aug 01, 2022 |
| ASRock        | A320M-DVS R4.0              | [77f61a8711](https://bsd-hardware.info/?probe=77f61a8711) | Aug 01, 2022 |
| Gigabyte      | H87-HD3                     | [e6a9b0dd8b](https://bsd-hardware.info/?probe=e6a9b0dd8b) | Jul 25, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [def87ec245](https://bsd-hardware.info/?probe=def87ec245) | Jul 18, 2022 |
| ASUSTek       | PRIME H410M-A               | [7b6faf5301](https://bsd-hardware.info/?probe=7b6faf5301) | Jul 14, 2022 |
| ASUSTek       | PRIME H410M-A               | [ba243fa7c4](https://bsd-hardware.info/?probe=ba243fa7c4) | Jul 09, 2022 |
| Dell          | OptiPlex 580                | [620888d077](https://bsd-hardware.info/?probe=620888d077) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [77acc9f5cf](https://bsd-hardware.info/?probe=77acc9f5cf) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ffa0086c70](https://bsd-hardware.info/?probe=ffa0086c70) | Jul 01, 2022 |
| Gigabyte      | G41MT-S2                    | [0563158740](https://bsd-hardware.info/?probe=0563158740) | Jun 28, 2022 |
| MSI           | MS-7C02                     | [65265eea62](https://bsd-hardware.info/?probe=65265eea62) | Jun 20, 2022 |
| Lenovo        | ThinkPad T530 24292VG       | [6f744019ce](https://bsd-hardware.info/?probe=6f744019ce) | Jun 19, 2022 |
| Apple         | MacPro4,1                   | [65380f3847](https://bsd-hardware.info/?probe=65380f3847) | Jun 06, 2022 |
| ASUSTek       | PRIME H410M-E               | [8099e7abaf](https://bsd-hardware.info/?probe=8099e7abaf) | Jun 03, 2022 |
| MSI           | MS-6788                     | [f750cb83e3](https://bsd-hardware.info/?probe=f750cb83e3) | May 31, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [ade09344b8](https://bsd-hardware.info/?probe=ade09344b8) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [cc37ea1b7d](https://bsd-hardware.info/?probe=cc37ea1b7d) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [abacee12a9](https://bsd-hardware.info/?probe=abacee12a9) | May 26, 2022 |
| Unknown       | Raspberry Pi 3 Model B P... | [21fa41e4c1](https://bsd-hardware.info/?probe=21fa41e4c1) | May 26, 2022 |
| Gigabyte      | H81M-S2PV                   | [1937e77b97](https://bsd-hardware.info/?probe=1937e77b97) | May 22, 2022 |
| Biostar       | G31-M7 TE                   | [5c7af4b143](https://bsd-hardware.info/?probe=5c7af4b143) | May 21, 2022 |
| ASUSTek       | PRIME B550M-K               | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| MSI           | MS-7C82                     | [2ad883afec](https://bsd-hardware.info/?probe=2ad883afec) | May 15, 2022 |
| ASUSTek       | PRIME X470-PRO              | [9f6b4f114d](https://bsd-hardware.info/?probe=9f6b4f114d) | May 11, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | [154799d7fa](https://bsd-hardware.info/?probe=154799d7fa) | May 08, 2022 |
| Intel         | Q3XXG4-P                    | [ed04988a23](https://bsd-hardware.info/?probe=ed04988a23) | May 03, 2022 |
| MSI           | MS-7C37                     | [aaab7cf22a](https://bsd-hardware.info/?probe=aaab7cf22a) | Apr 28, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| PC Engines    | APU2                        | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Apple         | PowerMac10,1                | [e054e605fa](https://bsd-hardware.info/?probe=e054e605fa) | Apr 23, 2022 |
| Intel         | DH67BL                      | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA     | SH series                   | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| Sony          | VPCL22Z1R                   | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| ASUSTek       | Z170-K                      | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek       | P10S-I Series               | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| Dell          | G5 5090                     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| PC Engines    | apu4                        | [62df504364](https://bsd-hardware.info/?probe=62df504364) | Apr 09, 2022 |
| Unknown       | Raspberry Pi 3 Model B R... | [040f37113c](https://bsd-hardware.info/?probe=040f37113c) | Apr 06, 2022 |
| Intel         | DCP847SKE                   | [a79e298be3](https://bsd-hardware.info/?probe=a79e298be3) | Apr 03, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | [32d27b9404](https://bsd-hardware.info/?probe=32d27b9404) | Mar 19, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | [7361628ed9](https://bsd-hardware.info/?probe=7361628ed9) | Mar 19, 2022 |
| Unknown       | LeMaker Banana Pi           | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |
| Intel         | D945GSEJT                   | [bf6a38dfcb](https://bsd-hardware.info/?probe=bf6a38dfcb) | Feb 26, 2022 |
| Dell          | OptiPlex 755                | [9ddfe010c4](https://bsd-hardware.info/?probe=9ddfe010c4) | Feb 24, 2022 |
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
| PC Engines    | APU3                        | [449967354c](https://bsd-hardware.info/?probe=449967354c) | Feb 18, 2021 |
| PC Engines    | APU2                        | [b911e3bec2](https://bsd-hardware.info/?probe=b911e3bec2) | Feb 18, 2021 |
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
| PC Engines    | APU2                        | [e0361ddbad](https://bsd-hardware.info/?probe=e0361ddbad) | Oct 31, 2020 |
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
| PC Engines    | APU2                        | [ce4c41d466](https://bsd-hardware.info/?probe=ce4c41d466) | Oct 26, 2020 |
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
| PC Engines    | APU2                        | [d1ca549fe7](https://bsd-hardware.info/?probe=d1ca549fe7) | Oct 21, 2020 |
| ZOTAC         | XXXXXX                      | [0f8960bdd3](https://bsd-hardware.info/?probe=0f8960bdd3) | Oct 21, 2020 |
| IBM           | Board                       | [11b0b7012f](https://bsd-hardware.info/?probe=11b0b7012f) | Oct 21, 2020 |
| IBM           | Board                       | [a92c08a920](https://bsd-hardware.info/?probe=a92c08a920) | Oct 21, 2020 |
| IBM           | Board                       | [80d5f15a63](https://bsd-hardware.info/?probe=80d5f15a63) | Oct 21, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | [2cb76e5886](https://bsd-hardware.info/?probe=2cb76e5886) | Oct 21, 2020 |
| PC Engines    | APU2                        | [e6ee8a14d5](https://bsd-hardware.info/?probe=e6ee8a14d5) | Oct 20, 2020 |
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
| PC Engines    | APU2                        | [064e7167a0](https://bsd-hardware.info/?probe=064e7167a0) | Oct 19, 2020 |
| Dell          | OptiPlex 3060               | [13992dbb10](https://bsd-hardware.info/?probe=13992dbb10) | Oct 19, 2020 |
| PC Engines    | APU2                        | [a5b1c3a559](https://bsd-hardware.info/?probe=a5b1c3a559) | Oct 19, 2020 |
| Dell          | PowerEdge T320              | [75c395f941](https://bsd-hardware.info/?probe=75c395f941) | Oct 19, 2020 |
| Dell          | PowerEdge 1950              | [3cfcdfce6d](https://bsd-hardware.info/?probe=3cfcdfce6d) | Oct 19, 2020 |
| Dell          | PowerEdge 1950              | [0865193e7e](https://bsd-hardware.info/?probe=0865193e7e) | Oct 19, 2020 |
| Dell          | PowerEdge R610              | [2ea539bbd3](https://bsd-hardware.info/?probe=2ea539bbd3) | Oct 19, 2020 |
| Dell          | OptiPlex 7020               | [293e6af35e](https://bsd-hardware.info/?probe=293e6af35e) | Oct 19, 2020 |
| PC Engines    | APU2                        | [2ab3051cb8](https://bsd-hardware.info/?probe=2ab3051cb8) | Oct 19, 2020 |
| PC Engines    | apu4                        | [f0116986e0](https://bsd-hardware.info/?probe=f0116986e0) | Oct 19, 2020 |
| IBM           | Board                       | [af2f64a7a8](https://bsd-hardware.info/?probe=af2f64a7a8) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | [dc7b96e637](https://bsd-hardware.info/?probe=dc7b96e637) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | [0184fcedcf](https://bsd-hardware.info/?probe=0184fcedcf) | Oct 19, 2020 |
| ASUSTek       | PRIME X570-P                | [b33e2a5177](https://bsd-hardware.info/?probe=b33e2a5177) | Oct 19, 2020 |
| PC Engines    | apu1                        | [576f4db9e1](https://bsd-hardware.info/?probe=576f4db9e1) | Oct 19, 2020 |
| PC Engines    | APU2                        | [e4030e5ee2](https://bsd-hardware.info/?probe=e4030e5ee2) | Oct 19, 2020 |
| PC Engines    | APU2                        | [ca0480a30d](https://bsd-hardware.info/?probe=ca0480a30d) | Oct 19, 2020 |
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
| PC Engines    | APU3                        | [1eaf8a1484](https://bsd-hardware.info/?probe=1eaf8a1484) | Aug 03, 2020 |
| PC Engines    | APU3                        | [4980462667](https://bsd-hardware.info/?probe=4980462667) | Aug 03, 2020 |
| PC Engines    | APU3                        | [975e23e09d](https://bsd-hardware.info/?probe=975e23e09d) | Aug 03, 2020 |
| Shuttle       | DS437                       | [aa350b6b92](https://bsd-hardware.info/?probe=aa350b6b92) | Aug 03, 2020 |
| PC Engines    | APU2                        | [fe5c2f4838](https://bsd-hardware.info/?probe=fe5c2f4838) | Aug 03, 2020 |
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
| OpenBSD 6.8 | 109      | 44.67%  |
| OpenBSD 7.1 | 42       | 17.21%  |
| OpenBSD 7.0 | 33       | 13.52%  |
| OpenBSD 6.9 | 31       | 12.7%   |
| OpenBSD 6.7 | 26       | 10.66%  |
| OpenBSD 7.2 | 2        | 0.82%   |
| OpenBSD 6.6 | 1        | 0.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| OpenBSD | 220      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 182      | 82.73%  |
| i386    | 15       | 6.82%   |
| arm64   | 15       | 6.82%   |
| sparc64 | 2        | 0.91%   |
| octeon  | 2        | 0.91%   |
| macppc  | 2        | 0.91%   |
| armv7   | 2        | 0.91%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 96       | 42.11%  |
| fvwm          | 85       | 37.28%  |
| helloDesktop  | 38       | 16.67%  |
| XFCE          | 6        | 2.63%   |
| i3            | 1        | 0.44%   |
| GNOME         | 1        | 0.44%   |
| Enlightenment | 1        | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 121      | 54.5%   |
| X11     | 101      | 45.5%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 212      | 95.07%  |
| SLiM    | 6        | 2.69%   |
| GDM     | 5        | 2.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 189      | 85.14%  |
| ru_RU   | 14       | 6.31%   |
| en_US   | 9        | 4.05%   |
| C       | 4        | 1.8%    |
| de_DE   | 3        | 1.35%   |
| pl_PL   | 1        | 0.45%   |
| fr_FR   | 1        | 0.45%   |
| en_AU   | 1        | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 139      | 62.33%  |
| EFI  | 84       | 37.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 220      | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 153      | 69.23%  |
| GPT  | 68       | 30.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| PC Engines              | 32       | 14.55%  |
| ASUSTek Computer        | 26       | 11.82%  |
| Gigabyte Technology     | 21       | 9.55%   |
| Unknown                 | 20       | 9.09%   |
| Dell                    | 17       | 7.73%   |
| ASRock                  | 15       | 6.82%   |
| MSI                     | 14       | 6.36%   |
| Hewlett-Packard         | 11       | 5%      |
| Lenovo                  | 9        | 4.09%   |
| Intel                   | 9        | 4.09%   |
| Supermicro              | 6        | 2.73%   |
| Raspberry Pi Foundation | 4        | 1.82%   |
| Apple                   | 4        | 1.82%   |
| Sun                     | 2        | 0.91%   |
| Soekris Engineering     | 2        | 0.91%   |
| Shuttle                 | 2        | 0.91%   |
| Pegatron                | 2        | 0.91%   |
| IBM                     | 2        | 0.91%   |
| Biostar                 | 2        | 0.91%   |
| ZOTAC                   | 1        | 0.45%   |
| Yanling                 | 1        | 0.45%   |
| WYSE                    | 1        | 0.45%   |
| Unknown                 | 1        | 0.45%   |
| Sony UK                 | 1        | 0.45%   |
| Sony                    | 1        | 0.45%   |
| Protectli               | 1        | 0.45%   |
| NF541                   | 1        | 0.45%   |
| KOHJINSHA               | 1        | 0.45%   |
| HARDKERNEL              | 1        | 0.45%   |
| Fujitsu                 | 1        | 0.45%   |
| Foxconn                 | 1        | 0.45%   |
| eMachines               | 1        | 0.45%   |
| ECT                     | 1        | 0.45%   |
| ECS                     | 1        | 0.45%   |
| CncTion                 | 1        | 0.45%   |
| Bluechip Computer       | 1        | 0.45%   |
| AZW                     | 1        | 0.45%   |
| Alienware               | 1        | 0.45%   |
| Acer                    | 1        | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 24       | 10.91%  |
| PC Engines APU2                   | 14       | 6.36%   |
| PC Engines apu4                   | 9        | 4.09%   |
| PC Engines apu1                   | 5        | 2.27%   |
| Dell PowerEdge R620               | 5        | 2.27%   |
| ASUS All Series                   | 4        | 1.82%   |
| PC Engines APU3                   | 3        | 1.36%   |
| RPi Raspberry Pi 400              | 2        | 0.91%   |
| RPi Raspberry Pi 4 Model B        | 2        | 0.91%   |
| MSI MS-7A34                       | 2        | 0.91%   |
| Gigabyte M68MT-S2P                | 2        | 0.91%   |
| ASUS PRIME X370-PRO               | 2        | 0.91%   |
| ASUS PRIME H410M-A                | 2        | 0.91%   |
| Apple PowerMac10,1                | 2        | 0.91%   |
| ZOTAC XXXXXX                      | 1        | 0.45%   |
| Yanling YL-KBR6L                  | 1        | 0.45%   |
| WYSE D CLASS                      | 1        | 0.45%   |
| Supermicro X8STi                  | 1        | 0.45%   |
| Supermicro X8DTH-i/6/iF/6F        | 1        | 0.45%   |
| Supermicro X7SBL                  | 1        | 0.45%   |
| Supermicro X11SSW-F               | 1        | 0.45%   |
| Supermicro X11DDW-L               | 1        | 0.45%   |
| Supermicro X10SLH-N6-ST031        | 1        | 0.45%   |
| Sun SUNW,Sun-Blade-1500           | 1        | 0.45%   |
| Sun SUNW,Sun-Blade-100            | 1        | 0.45%   |
| Sony VPCL22Z1R                    | 1        | 0.45%   |
| Sony UK Raspberry Pi 4 Model B    | 1        | 0.45%   |
| Soekris Engineering net6501       | 1        | 0.45%   |
| Soekris Engineering net5501       | 1        | 0.45%   |
| Shuttle DS77U                     | 1        | 0.45%   |
| Shuttle DS437                     | 1        | 0.45%   |
| Protectli FW6                     | 1        | 0.45%   |
| Pegatron SKLD4-P1                 | 1        | 0.45%   |
| Pegatron Compaq dx2400 Microtower | 1        | 0.45%   |
| PC Engines APU                    | 1        | 0.45%   |
| MSI MS-B09012                     | 1        | 0.45%   |
| MSI MS-7D54                       | 1        | 0.45%   |
| MSI MS-7C96                       | 1        | 0.45%   |
| MSI MS-7C82                       | 1        | 0.45%   |
| MSI MS-7C56                       | 1        | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Unknown                     | 24       | 10.91%  |
| PC Engines APU2             | 14       | 6.36%   |
| ASUS PRIME                  | 12       | 5.45%   |
| PC Engines apu4             | 9        | 4.09%   |
| Dell PowerEdge              | 9        | 4.09%   |
| Dell OptiPlex               | 6        | 2.73%   |
| PC Engines apu1             | 5        | 2.27%   |
| Lenovo ThinkCentre          | 5        | 2.27%   |
| RPi Raspberry               | 4        | 1.82%   |
| Lenovo ThinkPad             | 4        | 1.82%   |
| HP ProLiant                 | 4        | 1.82%   |
| ASUS All                    | 4        | 1.82%   |
| PC Engines APU3             | 3        | 1.36%   |
| Sun SUNW                    | 2        | 0.91%   |
| MSI MS-7A34                 | 2        | 0.91%   |
| HP Compaq                   | 2        | 0.91%   |
| Gigabyte M68MT-S2P          | 2        | 0.91%   |
| ASUS ROG                    | 2        | 0.91%   |
| ASRock X570                 | 2        | 0.91%   |
| Apple PowerMac10            | 2        | 0.91%   |
| ZOTAC XXXXXX                | 1        | 0.45%   |
| Yanling YL-KBR6L            | 1        | 0.45%   |
| WYSE D                      | 1        | 0.45%   |
| Supermicro X8STi            | 1        | 0.45%   |
| Supermicro X8DTH-i          | 1        | 0.45%   |
| Supermicro X7SBL            | 1        | 0.45%   |
| Supermicro X11SSW-F         | 1        | 0.45%   |
| Supermicro X11DDW-L         | 1        | 0.45%   |
| Supermicro X10SLH-N6-ST031  | 1        | 0.45%   |
| Sony VPCL22Z1R              | 1        | 0.45%   |
| Sony UK Raspberry           | 1        | 0.45%   |
| Soekris Engineering net6501 | 1        | 0.45%   |
| Soekris Engineering net5501 | 1        | 0.45%   |
| Shuttle DS77U               | 1        | 0.45%   |
| Shuttle DS437               | 1        | 0.45%   |
| Protectli FW6               | 1        | 0.45%   |
| Pegatron SKLD4-P1           | 1        | 0.45%   |
| Pegatron Compaq             | 1        | 0.45%   |
| PC Engines APU              | 1        | 0.45%   |
| MSI MS-B09012               | 1        | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 28       | 12.73%  |
| Unknown | 25       | 11.36%  |
| 2019    | 23       | 10.45%  |
| 2020    | 21       | 9.55%   |
| 2016    | 20       | 9.09%   |
| 2014    | 15       | 6.82%   |
| 2021    | 10       | 4.55%   |
| 2012    | 10       | 4.55%   |
| 2017    | 9        | 4.09%   |
| 2011    | 9        | 4.09%   |
| 2010    | 9        | 4.09%   |
| 2013    | 8        | 3.64%   |
| 2008    | 8        | 3.64%   |
| 2015    | 6        | 2.73%   |
| 2007    | 5        | 2.27%   |
| 2022    | 4        | 1.82%   |
| 2009    | 4        | 1.82%   |
| 2006    | 2        | 0.91%   |
| 2005    | 1        | 0.45%   |
| 2004    | 1        | 0.45%   |
| 2003    | 1        | 0.45%   |
| 2001    | 1        | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 220      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 187      | 85%     |
| Yes  | 33       | 15%     |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 4.01-8.0        | 58       | 26.36%  |
| 8.01-16.0       | 39       | 17.73%  |
| 16.01-24.0      | 31       | 14.09%  |
| 3.01-4.0        | 17       | 7.73%   |
| 32.01-64.0      | 14       | 6.36%   |
| 2.01-3.0        | 14       | 6.36%   |
| 1.01-2.0        | 12       | 5.45%   |
| 64.01-256.0     | 10       | 4.55%   |
| 0.51-1.0        | 8        | 3.64%   |
| 24.01-32.0      | 7        | 3.18%   |
| 0.01-0.5        | 7        | 3.18%   |
| More than 256.0 | 3        | 1.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 165      | 75%     |
| 0.51-1.0   | 20       | 9.09%   |
| 0          | 17       | 7.73%   |
| 1.01-2.0   | 6        | 2.73%   |
| 4.01-8.0   | 5        | 2.27%   |
| Unknown    | 3        | 1.36%   |
| 8.01-16.0  | 2        | 0.91%   |
| 3.01-4.0   | 1        | 0.45%   |
| 16.01-24.0 | 1        | 0.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 113      | 49.34%  |
| 2      | 54       | 23.58%  |
| 3      | 27       | 11.79%  |
| 4      | 19       | 8.3%    |
| 5      | 4        | 1.75%   |
| 0      | 4        | 1.75%   |
| 10     | 2        | 0.87%   |
| 7      | 2        | 0.87%   |
| 6      | 2        | 0.87%   |
| 12     | 1        | 0.44%   |
| 8      | 1        | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 218      | 99.09%  |
| Yes       | 2        | 0.91%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 196      | 89.09%  |
| No        | 24       | 10.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 169      | 76.47%  |
| Yes       | 52       | 23.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 198      | 90%     |
| Yes       | 22       | 10%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 38       | 17.19%  |
| USA          | 36       | 16.29%  |
| Germany      | 31       | 14.03%  |
| Netherlands  | 12       | 5.43%   |
| France       | 11       | 4.98%   |
| Poland       | 10       | 4.52%   |
| UK           | 9        | 4.07%   |
| Switzerland  | 9        | 4.07%   |
| Italy        | 8        | 3.62%   |
| Spain        | 7        | 3.17%   |
| Austria      | 7        | 3.17%   |
| Taiwan       | 5        | 2.26%   |
| Sweden       | 5        | 2.26%   |
| Ukraine      | 4        | 1.81%   |
| Norway       | 3        | 1.36%   |
| Canada       | 3        | 1.36%   |
| Romania      | 2        | 0.9%    |
| Denmark      | 2        | 0.9%    |
| UAE          | 1        | 0.45%   |
| Saudi Arabia | 1        | 0.45%   |
| New Zealand  | 1        | 0.45%   |
| Moldova      | 1        | 0.45%   |
| Lithuania    | 1        | 0.45%   |
| Jamaica      | 1        | 0.45%   |
| Indonesia    | 1        | 0.45%   |
| India        | 1        | 0.45%   |
| Hungary      | 1        | 0.45%   |
| Finland      | 1        | 0.45%   |
| Estonia      | 1        | 0.45%   |
| Egypt        | 1        | 0.45%   |
| Czechia      | 1        | 0.45%   |
| Cyprus       | 1        | 0.45%   |
| Croatia      | 1        | 0.45%   |
| Bulgaria     | 1        | 0.45%   |
| Brazil       | 1        | 0.45%   |
| Australia    | 1        | 0.45%   |
| Argentina    | 1        | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Moscow                  | 14       | 6.17%   |
| Berlin                  | 9        | 3.96%   |
| Amsterdam               | 7        | 3.08%   |
| Vladivostok             | 5        | 2.2%    |
| Vienna                  | 5        | 2.2%    |
| New Taipei              | 5        | 2.2%    |
| St Petersburg           | 4        | 1.76%   |
| Poortugaal              | 4        | 1.76%   |
| Milan                   | 4        | 1.76%   |
| Zurich                  | 3        | 1.32%   |
| Wittersham              | 3        | 1.32%   |
| Syeverodonets'k         | 3        | 1.32%   |
| Miedziana Gora          | 3        | 1.32%   |
| Malmo                   | 3        | 1.32%   |
| Lausanne                | 3        | 1.32%   |
| Ibiza Town              | 3        | 1.32%   |
| Wroclaw                 | 2        | 0.88%   |
| Svenstrup               | 2        | 0.88%   |
| Skien                   | 2        | 0.88%   |
| Saint-Martin-d'HГЁres | 2        | 0.88%   |
| Paris                   | 2        | 0.88%   |
| Orsk                    | 2        | 0.88%   |
| Onalaska                | 2        | 0.88%   |
| Oensingen               | 2        | 0.88%   |
| Nuremberg               | 2        | 0.88%   |
| Lebanon                 | 2        | 0.88%   |
| Gummersbach             | 2        | 0.88%   |
| Gdansk                  | 2        | 0.88%   |
| Braunschweig            | 2        | 0.88%   |
| Atlanta                 | 2        | 0.88%   |
| Zhukovskiy              | 1        | 0.44%   |
| Zagreb                  | 1        | 0.44%   |
| Zagnansk                | 1        | 0.44%   |
| Wolverhampton           | 1        | 0.44%   |
| Wolfsburg               | 1        | 0.44%   |
| Wheaton                 | 1        | 0.44%   |
| Waukesha                | 1        | 0.44%   |
| Voskresensk             | 1        | 0.44%   |
| Volgograd               | 1        | 0.44%   |
| Vechta                  | 1        | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 45       | 76     | 14.06%  |
| WDC                                | 42       | 56     | 13.13%  |
| Samsung Electronics                | 29       | 51     | 9.06%   |
| NVMe                               | 27       | 36     | 8.44%   |
| Kingston                           | 23       | 28     | 7.19%   |
| Phison                             | 13       | 15     | 4.06%   |
| Crucial                            | 13       | 23     | 4.06%   |
| Hitachi                            | 12       | 18     | 3.75%   |
| OPENBSD                            | 11       | 15     | 3.44%   |
| Toshiba                            | 10       | 15     | 3.13%   |
| SanDisk                            | 8        | 10     | 2.5%    |
| Intel                              | 8        | 12     | 2.5%    |
| HGST                               | 7        | 13     | 2.19%   |
| Dell                               | 6        | 10     | 1.88%   |
| Transcend                          | 5        | 12     | 1.56%   |
| A-DATA Technology                  | 5        | 6      | 1.56%   |
| USB                                | 3        | 3      | 0.94%   |
| LSI                                | 3        | 5      | 0.94%   |
| Hewlett-Packard                    | 3        | 8      | 0.94%   |
| StoreJet                           | 2        | 2      | 0.63%   |
| SK hynix                           | 2        | 2      | 0.63%   |
| PNY                                | 2        | 2      | 0.63%   |
| OCZ                                | 2        | 2      | 0.63%   |
| Multiple                           | 2        | 2      | 0.63%   |
| Maxtor                             | 2        | 3      | 0.63%   |
| Hoodisk                            | 2        | 3      | 0.63%   |
| Generic                            | 2        | 2      | 0.63%   |
| Corsair                            | 2        | 2      | 0.63%   |
| ASMT                               | 2        | 2      | 0.63%   |
| XPG                                | 1        | 1      | 0.31%   |
| SSDPR-CX                           | 1        | 1      | 0.31%   |
| SPCC                               | 1        | 1      | 0.31%   |
| SABRENT                            | 1        | 1      | 0.31%   |
| Qumo                               | 1        | 1      | 0.31%   |
| Product:              USB DISK 3.0 | 1        | 1      | 0.31%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.31%   |
| Product:                           | 1        | 1      | 0.31%   |
| Patriot                            | 1        | 1      | 0.31%   |
| MidasForce                         | 1        | 1      | 0.31%   |
| Micron Technology                  | 1        | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Phison SATA SSD 16GB               | 11       | 3.16%   |
| OPENBSD SR RAID 1 752GB            | 9        | 2.59%   |
| NVMe Samsung SSD 970 250GB         | 5        | 1.44%   |
| Samsung SSD 860 EVO mSATA 500GB    | 4        | 1.15%   |
| Dell PERC H710 282GB               | 4        | 1.15%   |
| WDC WD6400AARS-00Y5B1 640GB        | 3        | 0.86%   |
| USB SanDisk 3.2Gen1 64GB           | 3        | 0.86%   |
| Toshiba MQ04ABF100 1TB             | 3        | 0.86%   |
| Seagate ST3250318AS 250GB          | 3        | 0.86%   |
| Seagate ST250DM000-1BD141 250GB    | 3        | 0.86%   |
| Seagate ST1000DM010-2EP102 1TB     | 3        | 0.86%   |
| Samsung SSD 860 EVO 250GB          | 3        | 0.86%   |
| NVMe Samsung SSD 980 1TB           | 3        | 0.86%   |
| Kingston SUV500MS240G 240GB        | 3        | 0.86%   |
| HGST HUS724020ALA640 2TB           | 3        | 0.86%   |
| Crucial CT120BX500SSD1 120GB       | 3        | 0.86%   |
| Crucial CT1000MX500SSD1 1TB        | 3        | 0.86%   |
| WDC WD10EADS-00M2B0 1TB            | 2        | 0.57%   |
| WDC WD Elements 25A1 4TB           | 2        | 0.57%   |
| Toshiba HDWG440 4TB                | 2        | 0.57%   |
| StoreJet Transcend 120GB           | 2        | 0.57%   |
| Seagate ST3320418AS 320GB          | 2        | 0.57%   |
| Seagate ST1000LM035-1RK172 1TB     | 2        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB     | 2        | 0.57%   |
| SanDisk Ultra Fit 16GB             | 2        | 0.57%   |
| SanDisk Ultra 32GB                 | 2        | 0.57%   |
| Samsung SSD 860 EVO M.2 1TB        | 2        | 0.57%   |
| Samsung SSD 860 EVO 500GB          | 2        | 0.57%   |
| Samsung SSD 850 EVO M.2 250GB      | 2        | 0.57%   |
| Samsung SSD 850 EVO 1TB            | 2        | 0.57%   |
| Samsung HD161HJ 160GB              | 2        | 0.57%   |
| Samsung Flash Drive FIT 32GB       | 2        | 0.57%   |
| NVMe Samsung SSD 960 500GB         | 2        | 0.57%   |
| Multiple Card Reader               | 2        | 0.57%   |
| Kingston SUV500MS120G 120GB        | 2        | 0.57%   |
| Kingston SUV500240G 240GB          | 2        | 0.57%   |
| Kingston SMS200S360G 64GB          | 2        | 0.57%   |
| Kingston SMS200S330G 32GB          | 2        | 0.57%   |
| Kingston SA400S37240G 240GB        | 2        | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 45       | 76     | 24.73%  |
| WDC                                | 39       | 53     | 21.43%  |
| NVMe                               | 14       | 20     | 7.69%   |
| Hitachi                            | 12       | 18     | 6.59%   |
| OPENBSD                            | 11       | 15     | 6.04%   |
| Toshiba                            | 10       | 15     | 5.49%   |
| Samsung Electronics                | 8        | 12     | 4.4%    |
| HGST                               | 7        | 13     | 3.85%   |
| Dell                               | 6        | 10     | 3.3%    |
| USB                                | 3        | 3      | 1.65%   |
| LSI                                | 3        | 5      | 1.65%   |
| StoreJet                           | 2        | 2      | 1.1%    |
| Multiple                           | 2        | 2      | 1.1%    |
| Maxtor                             | 2        | 3      | 1.1%    |
| Hewlett-Packard                    | 2        | 6      | 1.1%    |
| Generic                            | 2        | 2      | 1.1%    |
| ASMT                               | 2        | 2      | 1.1%    |
| SSDPR-CX                           | 1        | 1      | 0.55%   |
| SABRENT                            | 1        | 1      | 0.55%   |
| Product:              USB DISK 3.0 | 1        | 1      | 0.55%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.55%   |
| Product:                           | 1        | 1      | 0.55%   |
| MaxDigital                         | 1        | 1      | 0.55%   |
| Lexar                              | 1        | 1      | 0.55%   |
| JetFlash                           | 1        | 1      | 0.55%   |
| IBM                                | 1        | 1      | 0.55%   |
| General                            | 1        | 1      | 0.55%   |
| China                              | 1        | 1      | 0.55%   |
| Apple                              | 1        | 1      | 0.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 23       | 28     | 16.79%  |
| Samsung Electronics | 21       | 39     | 15.33%  |
| Phison              | 13       | 15     | 9.49%   |
| Crucial             | 13       | 23     | 9.49%   |
| NVMe                | 12       | 14     | 8.76%   |
| SanDisk             | 8        | 10     | 5.84%   |
| Intel               | 8        | 12     | 5.84%   |
| Transcend           | 5        | 12     | 3.65%   |
| A-DATA Technology   | 5        | 6      | 3.65%   |
| WDC                 | 3        | 3      | 2.19%   |
| SK hynix            | 2        | 2      | 1.46%   |
| PNY                 | 2        | 2      | 1.46%   |
| OCZ                 | 2        | 2      | 1.46%   |
| Hoodisk             | 2        | 3      | 1.46%   |
| Corsair             | 2        | 2      | 1.46%   |
| XPG                 | 1        | 1      | 0.73%   |
| SPCC                | 1        | 1      | 0.73%   |
| Qumo                | 1        | 1      | 0.73%   |
| Patriot             | 1        | 1      | 0.73%   |
| MidasForce          | 1        | 1      | 0.73%   |
| Micron Technology   | 1        | 1      | 0.73%   |
| MEMXPRO             | 1        | 1      | 0.73%   |
| LITEONIT            | 1        | 1      | 0.73%   |
| KingSpec            | 1        | 1      | 0.73%   |
| HPE                 | 1        | 2      | 0.73%   |
| Hewlett-Packard     | 1        | 2      | 0.73%   |
| GOODRAM             | 1        | 1      | 0.73%   |
| GLOWAY              | 1        | 1      | 0.73%   |
| ASMedia             | 1        | 1      | 0.73%   |
| Apacer              | 1        | 1      | 0.73%   |
| AMD                 | 1        | 1      | 0.73%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 128      | 269    | 52.24%  |
| SSD  | 115      | 191    | 46.94%  |
| NVMe | 2        | 2      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 207      | 460    | 99.04%  |
| NVMe | 2        | 2      | 0.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 175      | 279    | 64.81%  |
| 0.51-1.0        | 59       | 96     | 21.85%  |
| 1.01-2.0        | 18       | 57     | 6.67%   |
| 3.01-4.0        | 10       | 14     | 3.7%    |
| 4.01-10.0       | 4        | 8      | 1.48%   |
| 2.01-3.0        | 3        | 5      | 1.11%   |
| More than 100.0 | 1        | 1      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 68       | 30.63%  |
| 251-500        | 52       | 23.42%  |
| 1-20           | 28       | 12.61%  |
| 51-100         | 26       | 11.71%  |
| 21-50          | 19       | 8.56%   |
| 501-1000       | 11       | 4.95%   |
| More than 3000 | 9        | 4.05%   |
| 1001-2000      | 6        | 2.7%    |
| 2001-3000      | 3        | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 160      | 70.8%   |
| 21-50          | 21       | 9.29%   |
| 101-250        | 17       | 7.52%   |
| 51-100         | 13       | 5.75%   |
| 501-1000       | 6        | 2.65%   |
| 1001-2000      | 4        | 1.77%   |
| 251-500        | 3        | 1.33%   |
| More than 3000 | 1        | 0.44%   |
| 2001-3000      | 1        | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba MQ04ABF100 1TB            | 2        | 2      | 5.56%   |
| Kingston SMS200S330G 32GB         | 2        | 3      | 5.56%   |
| HGST HTS541010A7E630 1TB          | 2        | 3      | 5.56%   |
| XPG SX950U 240GB                  | 1        | 1      | 2.78%   |
| WDC WD6400AAKS-22A7B0 640GB       | 1        | 1      | 2.78%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 2.78%   |
| WDC WD1600BEVE-00UYT0 160GB       | 1        | 1      | 2.78%   |
| WDC WD10SPZX-24Z10 1TB            | 1        | 1      | 2.78%   |
| WDC WD10EADS-00M2B0 1TB           | 1        | 1      | 2.78%   |
| Transcend 3E128-TS2-550B01 100GB  | 1        | 4      | 2.78%   |
| Seagate ST9500325AS 500GB         | 1        | 1      | 2.78%   |
| Seagate ST9160310AS 160GB         | 1        | 2      | 2.78%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 2.78%   |
| Seagate ST380815AS 80GB           | 1        | 1      | 2.78%   |
| Seagate ST3750640NS 752GB         | 1        | 4      | 2.78%   |
| Seagate ST3320418AS 320GB         | 1        | 1      | 2.78%   |
| Seagate ST3160212SCE 160GB        | 1        | 1      | 2.78%   |
| Seagate ST3120211AS 120GB         | 1        | 1      | 2.78%   |
| Seagate ST250DM000-1BD141 250GB   | 1        | 2      | 2.78%   |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 1      | 2.78%   |
| Seagate ST1000DM003-1CH162 1TB    | 1        | 1      | 2.78%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 2.78%   |
| Samsung Electronics HD161HJ 160GB | 1        | 1      | 2.78%   |
| Samsung Electronics HD154UI 1.5TB | 1        | 1      | 2.78%   |
| OCZ VERTEX3 120GB                 | 1        | 1      | 2.78%   |
| Kingston SV300S37A120G 120GB      | 1        | 1      | 2.78%   |
| Kingston SMS200S3120G 120GB       | 1        | 1      | 2.78%   |
| Intel SSDSC2CT180A4 180GB         | 1        | 1      | 2.78%   |
| Intel SSDSC2BB080G4 80GB          | 1        | 1      | 2.78%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 2      | 2.78%   |
| Hitachi HDP725016GLA380 160GB     | 1        | 1      | 2.78%   |
| GLOWAY FER60GS3-S7 64GB           | 1        | 1      | 2.78%   |
| A-DATA Technology SU630 240GB     | 1        | 2      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 16     | 28.57%  |
| WDC                 | 5        | 5      | 14.29%  |
| Kingston            | 4        | 5      | 11.43%  |
| Samsung Electronics | 3        | 3      | 8.57%   |
| Toshiba             | 2        | 2      | 5.71%   |
| Intel               | 2        | 2      | 5.71%   |
| Hitachi             | 2        | 3      | 5.71%   |
| HGST                | 2        | 3      | 5.71%   |
| XPG                 | 1        | 1      | 2.86%   |
| Transcend           | 1        | 4      | 2.86%   |
| OCZ                 | 1        | 1      | 2.86%   |
| GLOWAY              | 1        | 1      | 2.86%   |
| A-DATA Technology   | 1        | 2      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 16     | 41.67%  |
| WDC                 | 5        | 5      | 20.83%  |
| Samsung Electronics | 3        | 3      | 12.5%   |
| Toshiba             | 2        | 2      | 8.33%   |
| Hitachi             | 2        | 3      | 8.33%   |
| HGST                | 2        | 3      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 32     | 68.57%  |
| SSD  | 11       | 16     | 31.43%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB     | 1        | 2      | 50%     |
| Samsung Electronics HD204UI 2TB | 1        | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 2      | 50%     |
| Samsung Electronics | 1        | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 159      | 305    | 61.63%  |
| Detected | 63       | 105    | 24.42%  |
| Malfunc  | 34       | 48     | 13.18%  |
| Failed   | 2        | 4      | 0.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 112      | 45.34%  |
| AMD                          | 74       | 29.96%  |
| Samsung Electronics          | 13       | 5.26%   |
| Broadcom / LSI               | 12       | 4.86%   |
| SanDisk                      | 7        | 2.83%   |
| Nvidia                       | 5        | 2.02%   |
| ASMedia Technology           | 4        | 1.62%   |
| VIA Technologies             | 3        | 1.21%   |
| ULi Electronics              | 2        | 0.81%   |
| Phison Electronics           | 2        | 0.81%   |
| Marvell Technology Group     | 2        | 0.81%   |
| Hewlett-Packard              | 2        | 0.81%   |
| Toshiba                      | 1        | 0.4%    |
| Silicon Image                | 1        | 0.4%    |
| Shenzhen Longsys Electronics | 1        | 0.4%    |
| Seagate Technology           | 1        | 0.4%    |
| KIOXIA                       | 1        | 0.4%    |
| Kingston Technology Company  | 1        | 0.4%    |
| HighPoint Technologies       | 1        | 0.4%    |
| Dell                         | 1        | 0.4%    |
| ADATA Technology             | 1        | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 35       | 11.78%  |
| AMD FCH SATA Controller [IDE mode]                                               | 15       | 5.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14       | 4.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 14       | 4.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 8        | 2.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7        | 2.36%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 7        | 2.36%   |
| AMD 400 Series Chipset SATA Controller                                           | 7        | 2.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6        | 2.02%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 6        | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 6        | 2.02%   |
| AMD 500 Series Chipset SATA Controller                                           | 6        | 2.02%   |
| Nvidia MCP61 SATA Controller                                                     | 5        | 1.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 5        | 1.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5        | 1.68%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5        | 1.68%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 5        | 1.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4        | 1.35%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 4        | 1.35%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 4        | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4        | 1.35%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4        | 1.35%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3        | 1.01%   |
| Sandisk unknown                                                                  | 3        | 1.01%   |
| Nvidia MCP61 IDE                                                                 | 3        | 1.01%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3        | 1.01%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3        | 1.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3        | 1.01%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3        | 1.01%   |
| Intel 82801EB (ICH5) SATA Controller                                             | 3        | 1.01%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 2        | 0.67%   |
| ULi M5229 IDE                                                                    | 2        | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2        | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2        | 0.67%   |
| Phison E12 NVMe Controller                                                       | 2        | 0.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2        | 0.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 0.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2        | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2        | 0.67%   |
| Intel 82Q35 Express PT IDER Controller                                           | 2        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 153      | 60.24%  |
| IDE  | 55       | 21.65%  |
| NVMe | 27       | 10.63%  |
| RAID | 13       | 5.12%   |
| SAS  | 5        | 1.97%   |
| SCSI | 1        | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 116      | 52.73%  |
| AMD     | 81       | 36.82%  |
| ARM     | 17       | 7.73%   |
| Unknown | 4        | 1.82%   |
| PowerPC | 2        | 0.91%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| AMD GX-412TC SOC                                                 | 26       | 11.76%  |
| ARM Cortex-A72 r0p3                                              | 10       | 4.52%   |
| AMD G-T40E Processor                                             | 6        | 2.71%   |
| ARM Cortex-A53 r0p4                                              | 5        | 2.26%   |
| AMD Ryzen 7 5800X 8-Core Processor                               | 4        | 1.81%   |
|                                                                  | 4        | 1.81%   |
| Intel Core i5-4570 CPU @ 3.20GHz                                 | 3        | 1.36%   |
| AMD Ryzen 5 3600 6-Core Processor                                | 3        | 1.36%   |
| Intel Xeon CPU E5520 @ 2.27GHz                                   | 2        | 0.9%    |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz                               | 2        | 0.9%    |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz                               | 2        | 0.9%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                              | 2        | 0.9%    |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                              | 2        | 0.9%    |
| Intel Core i7-4770K CPU @ 3.50GHz                                | 2        | 0.9%    |
| Intel Core i7-3770 CPU @ 3.40GHz                                 | 2        | 0.9%    |
| Intel Core i5-4570T CPU @ 2.90GHz                                | 2        | 0.9%    |
| Intel Core i3-10100F CPU @ 3.60GHz                               | 2        | 0.9%    |
| Intel Core i3-10100 CPU @ 3.60GHz                                | 2        | 0.9%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz                             | 2        | 0.9%    |
| Intel Celeron CPU 3865U @ 1.80GHz                                | 2        | 0.9%    |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class)         | 2        | 0.9%    |
| AMD Ryzen 7 5700G with Radeon Graphics                           | 2        | 0.9%    |
| AMD Ryzen 7 2700 Eight-Core Processor                            | 2        | 0.9%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics                      | 2        | 0.9%    |
| AMD Geode Integrated Processor by PCS ("AuthenticAMD" 586-class) | 2        | 0.9%    |
| AMD E2-1800 APU with Radeon HD Graphics                          | 2        | 0.9%    |
| AMD Athlon II X3 455 Processor                                   | 2        | 0.9%    |
| PowerPC 7447A (Revision 0x102)                                   | 1        | 0.45%   |
| PowerPC 7447A (Revision 0x101)                                   | 1        | 0.45%   |
| Intel Xeon Gold 5220 CPU @ 2.20GHz                               | 1        | 0.45%   |
| Intel Xeon E-2278G CPU @ 3.40GHz                                 | 1        | 0.45%   |
| Intel Xeon CPU X5690 @ 3.47GHz                                   | 1        | 0.45%   |
| Intel Xeon CPU X5680 @ 3.33GHz                                   | 1        | 0.45%   |
| Intel Xeon CPU X5675 @ 3.07GHz                                   | 1        | 0.45%   |
| Intel Xeon CPU W3530 @ 2.80GHz                                   | 1        | 0.45%   |
| Intel Xeon CPU E5620 @ 2.40GHz                                   | 1        | 0.45%   |
| Intel Xeon CPU E5410 @ 2.33GHz                                   | 1        | 0.45%   |
| Intel Xeon CPU E5320 @ 1.86GHz                                   | 1        | 0.45%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz                               | 1        | 0.45%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz                               | 1        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD GX                  | 27       | 12.27%  |
| Intel Xeon              | 24       | 10.91%  |
| Intel Core i7           | 17       | 7.73%   |
| Intel Core i5           | 17       | 7.73%   |
| ARM Cortex              | 17       | 7.73%   |
| Intel Celeron           | 16       | 7.27%   |
| AMD Ryzen 7             | 13       | 5.91%   |
| Intel Core i3           | 11       | 5%      |
| Other                   | 9        | 4.09%   |
| AMD G                   | 7        | 3.18%   |
| Intel Atom              | 6        | 2.73%   |
| AMD Ryzen 5             | 6        | 2.73%   |
| Intel Pentium 4         | 4        | 1.82%   |
| Intel Pentium Dual-Core | 3        | 1.36%   |
| Intel Pentium           | 3        | 1.36%   |
| Intel Core 2 Duo        | 3        | 1.36%   |
| AMD Ryzen 3             | 3        | 1.36%   |
| Intel Genuine           | 2        | 0.91%   |
| Intel Core 2            | 2        | 0.91%   |
| AMD Ryzen 9             | 2        | 0.91%   |
| AMD Phenom II X4        | 2        | 0.91%   |
| AMD Geode Integrated    | 2        | 0.91%   |
| AMD E2                  | 2        | 0.91%   |
| AMD Athlon II X3        | 2        | 0.91%   |
| AMD Athlon 64 X2        | 2        | 0.91%   |
| AMD Athlon              | 2        | 0.91%   |
| Intel Xeon Gold         | 1        | 0.45%   |
| Intel Pentium III       | 1        | 0.45%   |
| Intel Pentium Dual      | 1        | 0.45%   |
| Intel Pentium D         | 1        | 0.45%   |
| Intel Core 2 Quad       | 1        | 0.45%   |
| Intel Celeron D         | 1        | 0.45%   |
| AMD Turion II Neo       | 1        | 0.45%   |
| AMD Ryzen 7 PRO         | 1        | 0.45%   |
| AMD Phenom II X6        | 1        | 0.45%   |
| AMD FX                  | 1        | 0.45%   |
| AMD E                   | 1        | 0.45%   |
| AMD Athlon XP           | 1        | 0.45%   |
| AMD Athlon II X4        | 1        | 0.45%   |
| AMD Athlon II X2        | 1        | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 76       | 34.55%  |
| Unknown | 48       | 21.82%  |
| 2       | 36       | 16.36%  |
| 1       | 17       | 7.73%   |
| 6       | 12       | 5.45%   |
| 16      | 9        | 4.09%   |
| 8       | 9        | 4.09%   |
| 12      | 8        | 3.64%   |
| 3       | 2        | 0.91%   |
| 36      | 1        | 0.45%   |
| 32      | 1        | 0.45%   |
| 24      | 1        | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 153      | 69.23%  |
| Unknown | 59       | 26.7%   |
| 2       | 9        | 4.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 107      | 48.64%  |
| Unknown | 61       | 27.73%  |
| 2       | 52       | 23.64%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 35       | 15.91%  |
| Puma          | 26       | 11.82%  |
| Haswell       | 19       | 8.64%   |
| SandyBridge   | 12       | 5.45%   |
| KabyLake      | 12       | 5.45%   |
| Bobcat        | 10       | 4.55%   |
| Zen 2         | 9        | 4.09%   |
| K10           | 9        | 4.09%   |
| IvyBridge     | 8        | 3.64%   |
| Penryn        | 7        | 3.18%   |
| Silvermont    | 6        | 2.73%   |
| NetBurst      | 6        | 2.73%   |
| Bonnell       | 6        | 2.73%   |
| Zen 3         | 5        | 2.27%   |
| Zen           | 5        | 2.27%   |
| Westmere      | 5        | 2.27%   |
| Skylake       | 5        | 2.27%   |
| Core          | 5        | 2.27%   |
| Zen+          | 4        | 1.82%   |
| CometLake     | 4        | 1.82%   |
| Nehalem       | 3        | 1.36%   |
| Goldmont      | 3        | 1.36%   |
| Broadwell     | 3        | 1.36%   |
| Piledriver    | 2        | 0.91%   |
| P6            | 2        | 0.91%   |
| K8 Hammer     | 2        | 0.91%   |
| Goldmont plus | 2        | 0.91%   |
| Geode         | 2        | 0.91%   |
| K6            | 1        | 0.45%   |
| K10 Llano     | 1        | 0.45%   |
| Jaguar        | 1        | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| AMD                                          | 68       | 39.53%  |
| Intel                                        | 67       | 38.95%  |
| Nvidia                                       | 18       | 10.47%  |
| Matrox Electronics Systems                   | 13       | 7.56%   |
| ASPEED Technology                            | 4        | 2.33%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.58%   |
| 3DLabs                                       | 1        | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10       | 5.68%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10       | 5.68%   |
| Matrox Electronics Systems G200eR2                                                       | 7        | 3.98%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 6        | 3.41%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 2.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4        | 2.27%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 4        | 2.27%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3        | 1.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3        | 1.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 1.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3        | 1.7%    |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                             | 3        | 1.7%    |
| AMD ES1000                                                                               | 3        | 1.7%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 1.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 1.14%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 1.14%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2        | 1.14%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2        | 1.14%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 1.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 1.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.14%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 2        | 1.14%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 1.14%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2        | 1.14%   |
| Intel 82865G Integrated Graphics Controller                                              | 2        | 1.14%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 2        | 1.14%   |
| AMD RV280 [Radeon 9200]                                                                  | 2        | 1.14%   |
| AMD RS880 [Radeon HD 4200]                                                               | 2        | 1.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.14%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 2        | 1.14%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2        | 1.14%   |
| AMD Cezanne                                                                              | 2        | 1.14%   |
| XGI Technology (eXtreme Graphics Innovation) Z9s/Z9m (XG21 core)                         | 1        | 0.57%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1        | 0.57%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                                    | 1        | 0.57%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1        | 0.57%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 64       | 28.83%  |
| 1 x Intel      | 58       | 26.13%  |
| Other          | 54       | 24.32%  |
| 1 x Nvidia     | 15       | 6.76%   |
| 1 x Matrox     | 12       | 5.41%   |
| 2 x Intel      | 6        | 2.7%    |
| 1 x ASPEED     | 4        | 1.8%    |
| Intel + Nvidia | 2        | 0.9%    |
| Intel + AMD    | 2        | 0.9%    |
| 2 x AMD        | 1        | 0.45%   |
| 1 x XGI        | 1        | 0.45%   |
| AMD + Nvidia   | 1        | 0.45%   |
| AMD + Matrox   | 1        | 0.45%   |
| 1 x 3DLabs     | 1        | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 149      | 67.42%  |
| Unknown | 72       | 32.58%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 220      | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 11       | 12.79%  |
| Dell                 | 11       | 12.79%  |
| Samsung Electronics  | 10       | 11.63%  |
| Goldstar             | 9        | 10.47%  |
| Ancor Communications | 7        | 8.14%   |
| NEC Computers        | 4        | 4.65%   |
| Iiyama               | 4        | 4.65%   |
| Hewlett-Packard      | 4        | 4.65%   |
| Lenovo               | 3        | 3.49%   |
| BenQ                 | 3        | 3.49%   |
| AOC                  | 3        | 3.49%   |
| ViewSonic            | 2        | 2.33%   |
| MSI                  | 2        | 2.33%   |
| LG Display           | 2        | 2.33%   |
| Eizo                 | 2        | 2.33%   |
| ASUSTek Computer     | 2        | 2.33%   |
| Acer                 | 2        | 2.33%   |
| Vizio                | 1        | 1.16%   |
| SHI                  | 1        | 1.16%   |
| Sceptre Tech         | 1        | 1.16%   |
| Medion               | 1        | 1.16%   |
| InfoVision           | 1        | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                  | 6        | 6.82%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch   | 3        | 3.41%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                  | 2        | 2.27%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch           | 2        | 2.27%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                      | 2        | 2.27%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                       | 2        | 2.27%   |
| Vizio E320i-A0 VIZ0091 1366x768 700x390mm 31.5-inch                    | 1        | 1.14%   |
| ViewSonic LCD Monitor VSCE032 2560x1440 530x300mm 24.0-inch            | 1        | 1.14%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 1        | 1.14%   |
| SHI LCD-TV**** SHI6102 1360x768 700x390mm 31.5-inch                    | 1        | 1.14%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch         | 1        | 1.14%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch      | 1        | 1.14%   |
| Samsung Electronics SyncMaster SAM03EF 1680x1050 470x300mm 22.0-inch   | 1        | 1.14%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch   | 1        | 1.14%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 380x300mm 19.1-inch   | 1        | 1.14%   |
| Samsung Electronics SyncMaster SAM00A1 1280x1024 340x270mm 17.1-inch   | 1        | 1.14%   |
| Samsung Electronics SMB2340 SAM0691 1920x1080 510x290mm 23.1-inch      | 1        | 1.14%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 800x330mm 34.1-inch       | 1        | 1.14%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 1        | 1.14%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch  | 1        | 1.14%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 1.14%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch               | 1        | 1.14%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch               | 1        | 1.14%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 1        | 1.14%   |
| Philips LCD Monitor PHLC00B 1280x1024 340x270mm 17.1-inch              | 1        | 1.14%   |
| Philips 190S PHL086B 1280x1024 380x300mm 19.1-inch                     | 1        | 1.14%   |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch          | 1        | 1.14%   |
| NEC Computers LCD190V NEC66D3 1280x1024 380x300mm 19.1-inch            | 1        | 1.14%   |
| NEC Computers EX341R NEC2C7A 3440x1440 800x330mm 34.1-inch             | 1        | 1.14%   |
| NEC Computers EA243WM NEC6866 1920x1200 520x320mm 24.0-inch            | 1        | 1.14%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                        | 1        | 1.14%   |
| MSI MAG241C MSI3EA2 1920x1080 520x290mm 23.4-inch                      | 1        | 1.14%   |
| Medion LCD Monitor MED09A3 1280x1024 380x300mm 19.1-inch               | 1        | 1.14%   |
| LG Display LCD Monitor LGD05D8 1920x1080 340x190mm 15.3-inch           | 1        | 1.14%   |
| LG Display LCD Monitor LGD040A 1920x1080 310x170mm 13.9-inch           | 1        | 1.14%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 530x300mm 24.0-inch               | 1        | 1.14%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 1        | 1.14%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch                | 1        | 1.14%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch            | 1        | 1.14%   |
| Iiyama PL3288UH IVM7610 3840x2160 700x390mm 31.5-inch                  | 1        | 1.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 33       | 40.24%  |
| 1280x1024 (SXGA)   | 11       | 13.41%  |
| 3840x2160 (4K)     | 8        | 9.76%   |
| 1440x900 (WXGA+)   | 6        | 7.32%   |
| 3440x1440          | 5        | 6.1%    |
| 2560x1440 (QHD)    | 5        | 6.1%    |
| 1920x1200 (WUXGA)  | 4        | 4.88%   |
| 1366x768 (WXGA)    | 4        | 4.88%   |
| 3840x1080          | 1        | 1.22%   |
| 1680x1050 (WSXGA+) | 1        | 1.22%   |
| 1600x900 (HD+)     | 1        | 1.22%   |
| 1600x1200          | 1        | 1.22%   |
| 1360x768           | 1        | 1.22%   |
| 1024x768 (XGA)     | 1        | 1.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 12       | 14.63%  |
| 21     | 12       | 14.63%  |
| 23     | 11       | 13.41%  |
| 19     | 11       | 13.41%  |
| 27     | 9        | 10.98%  |
| 17     | 6        | 7.32%   |
| 31     | 5        | 6.1%    |
| 34     | 4        | 4.88%   |
| 18     | 2        | 2.44%   |
| 14     | 2        | 2.44%   |
| 54     | 1        | 1.22%   |
| 49     | 1        | 1.22%   |
| 35     | 1        | 1.22%   |
| 22     | 1        | 1.22%   |
| 20     | 1        | 1.22%   |
| 15     | 1        | 1.22%   |
| 13     | 1        | 1.22%   |
| 12     | 1        | 1.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 31       | 37.8%   |
| 401-500     | 22       | 26.83%  |
| 301-350     | 8        | 9.76%   |
| 601-700     | 6        | 7.32%   |
| 351-400     | 5        | 6.1%    |
| 701-800     | 4        | 4.88%   |
| 201-300     | 3        | 3.66%   |
| 1001-1500   | 2        | 2.44%   |
| 801-900     | 1        | 1.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 50       | 62.5%   |
| 5/4   | 11       | 13.75%  |
| 16/10 | 11       | 13.75%  |
| 21/9  | 5        | 6.25%   |
| 4/3   | 2        | 2.5%    |
| 32/9  | 1        | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 30       | 37.5%   |
| 151-200        | 12       | 15%     |
| 351-500        | 10       | 12.5%   |
| 301-350        | 9        | 11.25%  |
| 141-150        | 8        | 10%     |
| 251-300        | 4        | 5%      |
| 81-90          | 2        | 2.5%    |
| More than 1000 | 1        | 1.25%   |
| 61-70          | 1        | 1.25%   |
| 101-110        | 1        | 1.25%   |
| 501-1000       | 1        | 1.25%   |
| 91-100         | 1        | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 46       | 56.1%   |
| 101-120 | 19       | 23.17%  |
| 121-160 | 8        | 9.76%   |
| 161-240 | 5        | 6.1%    |
| 1-50    | 4        | 4.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 132      | 59.19%  |
| 1     | 84       | 37.67%  |
| 2     | 5        | 2.24%   |
| 3     | 2        | 0.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 106      | 41.57%  |
| Realtek Semiconductor             | 86       | 33.73%  |
| Broadcom                          | 15       | 5.88%   |
| Qualcomm Atheros                  | 13       | 5.1%    |
| Qualcomm Atheros Communications   | 7        | 2.75%   |
| U-Blox                            | 4        | 1.57%   |
| TP-Link                           | 4        | 1.57%   |
| VIA Technologies                  | 3        | 1.18%   |
| Ralink                            | 3        | 1.18%   |
| Apple                             | 2        | 0.78%   |
| 3Com                              | 2        | 0.78%   |
| Qcom                              | 1        | 0.39%   |
| Oracle/SUN                        | 1        | 0.39%   |
| National Semiconductor            | 1        | 0.39%   |
| MediaTek                          | 1        | 0.39%   |
| LG Electronics                    | 1        | 0.39%   |
| Ericsson Business Mobile Networks | 1        | 0.39%   |
| Emulex                            | 1        | 0.39%   |
| Davicom Semiconductor             | 1        | 0.39%   |
| AVM                               | 1        | 0.39%   |
| Accton Technology                 | 1        | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67       | 22.87%  |
| Intel I211 Gigabit Network Connection                             | 27       | 9.22%   |
| Intel I210 Gigabit Network Connection                             | 20       | 6.83%   |
| Intel 82574L Gigabit Network Connection                           | 11       | 3.75%   |
| Intel I350 Gigabit Network Connection                             | 8        | 2.73%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 1.71%   |
| Qualcomm Atheros AR9271 802.11n                                   | 5        | 1.71%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 1.71%   |
| U-Blox [u-blox 8]                                                 | 4        | 1.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4        | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.02%   |
| Intel Wireless 7260                                               | 3        | 1.02%   |
| Intel Ethernet Controller I225-V                                  | 3        | 1.02%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 3        | 1.02%   |
| VIA VT6105M [Rhine-III]                                           | 2        | 0.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2        | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.68%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2        | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2        | 0.68%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 2        | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.68%   |
| Intel 82576 Gigabit Network Connection                            | 2        | 0.68%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 2        | 0.68%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.68%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 0.68%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 2        | 0.68%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 2        | 0.68%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.34%   |
| TP-Link TP-LINK Wireless USB Adapter                              | 1        | 0.34%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.34%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.34%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 16       | 28.57%  |
| Realtek Semiconductor           | 11       | 19.64%  |
| Qualcomm Atheros                | 11       | 19.64%  |
| Qualcomm Atheros Communications | 7        | 12.5%   |
| TP-Link                         | 4        | 7.14%   |
| Ralink                          | 3        | 5.36%   |
| Broadcom                        | 2        | 3.57%   |
| Qcom                            | 1        | 1.79%   |
| MediaTek                        | 1        | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                                      | 5        | 8.93%   |
| Intel Wi-Fi 6 AX200                                                                  | 5        | 8.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 4        | 7.14%   |
| Intel Wireless 7260                                                                  | 3        | 5.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 2        | 3.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 2        | 3.57%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                            | 2        | 3.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 2        | 3.57%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                           | 2        | 3.57%   |
| TP-Link TP-LINK Wireless USB Adapter                                                 | 1        | 1.79%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 1        | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.79%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 1.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 1        | 1.79%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 1        | 1.79%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1        | 1.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1        | 1.79%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 1.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 1        | 1.79%   |
| Realtek 802.11n WLAN Adapter                                                         | 1        | 1.79%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1        | 1.79%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 1.79%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170]        | 1        | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1        | 1.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 1        | 1.79%   |
| Qcom RT73 USB Wireless LAN Card                                                      | 1        | 1.79%   |
| MediaTek 802.11ac Wireless LAN Card                                                  | 1        | 1.79%   |
| Intel Wireless 3160                                                                  | 1        | 1.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 1        | 1.79%   |
| Intel Ultimate N WiFi Link 5300                                                      | 1        | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 1        | 1.79%   |
| Intel Centrino Wireless-N 2230                                                       | 1        | 1.79%   |
| Intel Centrino Wireless-N 2200                                                       | 1        | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                         | 1        | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 1        | 1.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 1        | 1.79%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                               | 1        | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 101      | 48.1%   |
| Realtek Semiconductor  | 82       | 39.05%  |
| Broadcom               | 13       | 6.19%   |
| VIA Technologies       | 3        | 1.43%   |
| Qualcomm Atheros       | 2        | 0.95%   |
| Apple                  | 2        | 0.95%   |
| 3Com                   | 2        | 0.95%   |
| Oracle/SUN             | 1        | 0.48%   |
| National Semiconductor | 1        | 0.48%   |
| Emulex                 | 1        | 0.48%   |
| Davicom Semiconductor  | 1        | 0.48%   |
| Accton Technology      | 1        | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67       | 29.26%  |
| Intel I211 Gigabit Network Connection                             | 27       | 11.79%  |
| Intel I210 Gigabit Network Connection                             | 20       | 8.73%   |
| Intel 82574L Gigabit Network Connection                           | 11       | 4.8%    |
| Intel I350 Gigabit Network Connection                             | 8        | 3.49%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 3.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 2.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.31%   |
| Intel Ethernet Controller I225-V                                  | 3        | 1.31%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 3        | 1.31%   |
| VIA VT6105M [Rhine-III]                                           | 2        | 0.87%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.87%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.87%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.87%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 0.87%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.87%   |
| Intel 82576 Gigabit Network Connection                            | 2        | 0.87%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 2        | 0.87%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.87%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2        | 0.87%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 2        | 0.87%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 2        | 0.87%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.44%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.44%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                              | 1        | 0.44%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1        | 0.44%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller   | 1        | 0.44%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.44%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 0.44%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.44%   |
| Intel Ethernet Connection X722 for 1GbE                           | 1        | 0.44%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 0.44%   |
| Intel Ethernet Connection I218-LM                                 | 1        | 0.44%   |
| Intel Ethernet Connection (6) I219-V                              | 1        | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 196      | 76.26%  |
| WiFi     | 53       | 20.62%  |
| Modem    | 6        | 2.33%   |
| Unknown  | 2        | 0.78%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 139      | 83.23%  |
| WiFi     | 28       | 16.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 80       | 36.36%  |
| 2     | 51       | 23.18%  |
| 3     | 32       | 14.55%  |
| 4     | 23       | 10.45%  |
| 0     | 23       | 10.45%  |
| 8     | 3        | 1.36%   |
| 5     | 3        | 1.36%   |
| 7     | 2        | 0.91%   |
| 6     | 2        | 0.91%   |
| 12    | 1        | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 220      | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 59.09%  |
| IMC Networks                    | 2        | 9.09%   |
| Apple                           | 2        | 9.09%   |
| Realtek Semiconductor           | 1        | 4.55%   |
| Qualcomm Atheros Communications | 1        | 4.55%   |
| Foxconn / Hon Hai               | 1        | 4.55%   |
| Cambridge Silicon Radio         | 1        | 4.55%   |
| ASUSTek Computer                | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                       | 5        | 22.73%  |
| Intel Bluetooth wireless interface                          | 3        | 13.64%  |
| Intel Centrino Bluetooth Wireless Transceiver               | 2        | 9.09%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 2        | 9.09%   |
| Realtek  Bluetooth Adapter                                  | 1        | 4.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1        | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1        | 4.55%   |
| Intel AX210 Bluetooth                                       | 1        | 4.55%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1        | 4.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1        | 4.55%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 4.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 4.55%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 76       | 44.97%  |
| AMD                 | 63       | 37.28%  |
| Nvidia              | 15       | 8.88%   |
| C-Media Electronics | 5        | 2.96%   |
| VIA Technologies    | 2        | 1.18%   |
| ULi Electronics     | 2        | 1.18%   |
| Creative Labs       | 2        | 1.18%   |
| Lenovo              | 1        | 0.59%   |
| JMTek               | 1        | 0.59%   |
| ESS Technology      | 1        | 0.59%   |
| Blue Microphones    | 1        | 0.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 14       | 6.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 11       | 5.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 10       | 4.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 10       | 4.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 10       | 4.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7        | 3.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7        | 3.32%   |
| AMD Navi 10 HDMI Audio                                                            | 7        | 3.32%   |
| Intel Cannon Lake PCH cAVS                                                        | 6        | 2.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6        | 2.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6        | 2.84%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 6        | 2.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5        | 2.37%   |
| AMD Family 17h/19h HD Audio Controller                                            | 5        | 2.37%   |
| Nvidia MCP61 High Definition Audio                                                | 4        | 1.9%    |
| Intel Comet Lake PCH-V cAVS                                                       | 4        | 1.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 4        | 1.9%    |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3        | 1.42%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 3        | 1.42%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 3        | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 1.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3        | 1.42%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 3        | 1.42%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 3        | 1.42%   |
| AMD FCH Azalia Controller                                                         | 3        | 1.42%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 1.42%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                         | 2        | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 2        | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 0.95%   |
| Intel Sunrise Point-LP HD Audio                                                   | 2        | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2        | 0.95%   |
| Intel Broadwell-U Audio Controller                                                | 2        | 0.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 0.95%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 2        | 0.95%   |
| C-Media Electronics Digital Hifi Audio Digital Hifi Audio SPDIFs                  | 2        | 0.95%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 2        | 0.95%   |
| AMD Wrestler HDMI Audio                                                           | 2        | 0.95%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 0.95%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 9        | 42.86%  |
| Kingston            | 3        | 14.29%  |
| Transcend           | 2        | 9.52%   |
| Samsung Electronics | 2        | 9.52%   |
| SK hynix            | 1        | 4.76%   |
| Ramaxel Technology  | 1        | 4.76%   |
| Nanya Technology    | 1        | 4.76%   |
| Elpida              | 1        | 4.76%   |
| Corsair             | 1        | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s          | 2        | 7.69%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s     | 2        | 7.69%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s       | 2        | 7.69%   |
| Unknown RAM Module 512MB DIMM SDRAM                     | 1        | 3.85%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s               | 1        | 3.85%   |
| Unknown RAM Module 512MB DIMM 400MT/s                   | 1        | 3.85%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 1        | 3.85%   |
| Unknown RAM Module 256MB DIMM 333MT/s                   | 1        | 3.85%   |
| Unknown RAM Module 2048MB DIMM DDR2 266MT/s             | 1        | 3.85%   |
| Unknown RAM Module 1GB DIMM 400MT/s                     | 1        | 3.85%   |
| Unknown RAM Module 1024MB DIMM DDR                      | 1        | 3.85%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 1        | 3.85%   |
| Transcend RAM TS1GSK64W6H 8GB DIMM DDR3 1600MT/s        | 1        | 3.85%   |
| Transcend RAM TS128MLQ64V6J 1GB DIMM DDR2 667MT/s       | 1        | 3.85%   |
| SK hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 667MT/s     | 1        | 3.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 3.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 3.85%   |
| Samsung RAM M3 78T2953CZ3-CE6 1GB DIMM DDR2 667MT/s     | 1        | 3.85%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s | 1        | 3.85%   |
| Nanya RAM NT1GT64U88D0BY-AD 1024MB DIMM DDR2 800MT/s    | 1        | 3.85%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s   | 1        | 3.85%   |
| Elpida RAM EBE11UD8AJWA-8G-E 1024MB DIMM DDR2 800MT/s   | 1        | 3.85%   |
| Corsair RAM CML16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s    | 1        | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 7        | 38.89%  |
| DDR4    | 3        | 16.67%  |
| DDR2    | 3        | 16.67%  |
| DDR     | 2        | 11.11%  |
| Unknown | 2        | 11.11%  |
| SDRAM   | 1        | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 13       | 72.22%  |
| SODIMM | 5        | 27.78%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 7        | 31.82%  |
| 1024  | 5        | 22.73%  |
| 8192  | 4        | 18.18%  |
| 512   | 3        | 13.64%  |
| 32768 | 1        | 4.55%   |
| 2048  | 1        | 4.55%   |
| 256   | 1        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 4        | 21.05%  |
| 2400    | 3        | 15.79%  |
| 1333    | 3        | 15.79%  |
| 800     | 2        | 10.53%  |
| 400     | 2        | 10.53%  |
| Unknown | 2        | 10.53%  |
| 667     | 1        | 5.26%   |
| 333     | 1        | 5.26%   |
| 266     | 1        | 5.26%   |

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
| Logitech                | 4        | 40%     |
| Chicony Electronics     | 3        | 30%     |
| Z-Star Microelectronics | 1        | 10%     |
| Ricoh                   | 1        | 10%     |
| Microdia                | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Z-Star Integrated Camera             | 1        | 10%     |
| Ricoh USB2.0 Camera                  | 1        | 10%     |
| Microdia Ltd., USB  Live camera      | 1        | 10%     |
| Logitech Webcam C310                 | 1        | 10%     |
| Logitech Webcam C270                 | 1        | 10%     |
| Logitech HD Pro Webcam C920          | 1        | 10%     |
| Logitech C920 HD Pro Webcam          | 1        | 10%     |
| Chicony Ltd., HP 0.3MP Webcam        | 1        | 10%     |
| Chicony Integrated Camera [ThinkPad] | 1        | 10%     |
| Chicony Integrated Camera            | 1        | 10%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Validity Sensors | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 100%    |

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
| 0     | 115      | 51.57%  |
| 1     | 65       | 29.15%  |
| 2     | 35       | 15.7%   |
| 3     | 5        | 2.24%   |
| 7     | 2        | 0.9%    |
| 5     | 1        | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 74       | 50.34%  |
| Graphics card            | 27       | 18.37%  |
| Firewire controller      | 14       | 9.52%   |
| Net/wireless             | 10       | 6.8%    |
| Net/ethernet             | 7        | 4.76%   |
| Sound                    | 6        | 4.08%   |
| Storage/ata              | 5        | 3.4%    |
| Storage/raid             | 1        | 0.68%   |
| Storage/ide              | 1        | 0.68%   |
| Storage                  | 1        | 0.68%   |
| Network                  | 1        | 0.68%   |

