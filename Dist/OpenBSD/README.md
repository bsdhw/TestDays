OpenBSD - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for OpenBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD/Desktop/README.md) and [notebooks](/Dist/OpenBSD/Notebook/README.md).

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

Total: 590

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| MSI           | MS-6788                     | Desktop     | [f750cb83e3](https://bsd-hardware.info/?probe=f750cb83e3) | May 31, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [3b03bdf595](https://bsd-hardware.info/?probe=3b03bdf595) | May 29, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [ade09344b8](https://bsd-hardware.info/?probe=ade09344b8) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [cc37ea1b7d](https://bsd-hardware.info/?probe=cc37ea1b7d) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [abacee12a9](https://bsd-hardware.info/?probe=abacee12a9) | May 26, 2022 |
| Unknown       | Raspberry Pi 3 Model B P... | Desktop     | [21fa41e4c1](https://bsd-hardware.info/?probe=21fa41e4c1) | May 26, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [1937e77b97](https://bsd-hardware.info/?probe=1937e77b97) | May 22, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [5c7af4b143](https://bsd-hardware.info/?probe=5c7af4b143) | May 21, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| MSI           | MS-7C82                     | Desktop     | [2ad883afec](https://bsd-hardware.info/?probe=2ad883afec) | May 15, 2022 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [0419c52079](https://bsd-hardware.info/?probe=0419c52079) | May 11, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [9f6b4f114d](https://bsd-hardware.info/?probe=9f6b4f114d) | May 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [49d1cd3009](https://bsd-hardware.info/?probe=49d1cd3009) | May 10, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [154799d7fa](https://bsd-hardware.info/?probe=154799d7fa) | May 08, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| Intel         | Q3XXG4-P                    | Desktop     | [ed04988a23](https://bsd-hardware.info/?probe=ed04988a23) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| MSI           | MS-7C37                     | Desktop     | [aaab7cf22a](https://bsd-hardware.info/?probe=aaab7cf22a) | Apr 28, 2022 |
| MSI           | Modern 14 B11MOL            | Notebook    | [9a61443be9](https://bsd-hardware.info/?probe=9a61443be9) | Apr 25, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| PC Engines    | APU2                        | Desktop     | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Apple         | PowerMac10,1                | Desktop     | [e054e605fa](https://bsd-hardware.info/?probe=e054e605fa) | Apr 23, 2022 |
| Intel         | DH67BL                      | Desktop     | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA     | SH series                   | Desktop     | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | Desktop     | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| DEXP          | NAVIS P100                  | Notebook    | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Sony          | VPCL22Z1R                   | Desktop     | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | Notebook    | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| Samsung       | DP700A3D-X01RU SEC_SW_RE... | All in one  | [22febd212f](https://bsd-hardware.info/?probe=22febd212f) | Apr 22, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek       | P10S-I Series               | Desktop     | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b4a6761ab3](https://bsd-hardware.info/?probe=b4a6761ab3) | Apr 21, 2022 |
| Dell          | G5 5090                     | Desktop     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [f7aa3576ae](https://bsd-hardware.info/?probe=f7aa3576ae) | Apr 13, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [0e836941e0](https://bsd-hardware.info/?probe=0e836941e0) | Apr 11, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [41d62dde7d](https://bsd-hardware.info/?probe=41d62dde7d) | Apr 10, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [c5f7b5499a](https://bsd-hardware.info/?probe=c5f7b5499a) | Apr 10, 2022 |
| PC Engines    | apu4                        | Desktop     | [62df504364](https://bsd-hardware.info/?probe=62df504364) | Apr 09, 2022 |
| Unknown       | Raspberry Pi 3 Model B R... | Desktop     | [040f37113c](https://bsd-hardware.info/?probe=040f37113c) | Apr 06, 2022 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | Notebook    | [1d1db3eab4](https://bsd-hardware.info/?probe=1d1db3eab4) | Apr 03, 2022 |
| Intel         | DCP847SKE                   | Desktop     | [a79e298be3](https://bsd-hardware.info/?probe=a79e298be3) | Apr 03, 2022 |
| IBM           | 2658MNG                     | Notebook    | [e3a5a587fa](https://bsd-hardware.info/?probe=e3a5a587fa) | Mar 28, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [086a58a68f](https://bsd-hardware.info/?probe=086a58a68f) | Mar 24, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | Desktop     | [32d27b9404](https://bsd-hardware.info/?probe=32d27b9404) | Mar 19, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | Desktop     | [7361628ed9](https://bsd-hardware.info/?probe=7361628ed9) | Mar 19, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [ed0add65a3](https://bsd-hardware.info/?probe=ed0add65a3) | Mar 14, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [e5c8017afb](https://bsd-hardware.info/?probe=e5c8017afb) | Mar 12, 2022 |
| Lenovo        | Yoga 330-11IGM 81A6         | Notebook    | [621ae0501b](https://bsd-hardware.info/?probe=621ae0501b) | Mar 10, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3b77055bd4](https://bsd-hardware.info/?probe=3b77055bd4) | Mar 07, 2022 |
| Unknown       | LeMaker Banana Pi           | Desktop     | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Intel         | D945GSEJT                   | Desktop     | [bf6a38dfcb](https://bsd-hardware.info/?probe=bf6a38dfcb) | Feb 26, 2022 |
| Dell          | OptiPlex 755                | Desktop     | [9ddfe010c4](https://bsd-hardware.info/?probe=9ddfe010c4) | Feb 24, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [11bed21472](https://bsd-hardware.info/?probe=11bed21472) | Feb 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |
| Acer          | Aspire A514-52              | Notebook    | [60f9683fb1](https://bsd-hardware.info/?probe=60f9683fb1) | Feb 21, 2022 |
| Gigabyte      | X58A-UD5                    | Desktop     | [58d57520c1](https://bsd-hardware.info/?probe=58d57520c1) | Feb 20, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [04e528ca9f](https://bsd-hardware.info/?probe=04e528ca9f) | Feb 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [07546b5925](https://bsd-hardware.info/?probe=07546b5925) | Feb 18, 2022 |
| Lenovo        | ThinkPad X250 20CLS59400    | Notebook    | [92333ad60b](https://bsd-hardware.info/?probe=92333ad60b) | Feb 17, 2022 |
| MSI           | MS-7253                     | Desktop     | [c4e971ea82](https://bsd-hardware.info/?probe=c4e971ea82) | Feb 16, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [1e8904f4fc](https://bsd-hardware.info/?probe=1e8904f4fc) | Feb 15, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [dd52bb1163](https://bsd-hardware.info/?probe=dd52bb1163) | Feb 15, 2022 |
| Raspberry ... | Raspberry Pi 400            | Desktop     | [dd56609ceb](https://bsd-hardware.info/?probe=dd56609ceb) | Feb 14, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | Desktop     | [4691fdb146](https://bsd-hardware.info/?probe=4691fdb146) | Feb 13, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | Desktop     | [97788dfb1a](https://bsd-hardware.info/?probe=97788dfb1a) | Feb 13, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b77b926f9b](https://bsd-hardware.info/?probe=b77b926f9b) | Feb 13, 2022 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | Notebook    | [ae597455a4](https://bsd-hardware.info/?probe=ae597455a4) | Feb 13, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [c024d383e7](https://bsd-hardware.info/?probe=c024d383e7) | Feb 13, 2022 |
| Unknown       | LeMaker Banana Pi           | Desktop     | [77413a3d9d](https://bsd-hardware.info/?probe=77413a3d9d) | Feb 12, 2022 |
| HP            | t620 Quad Core TC           | Desktop     | [965ced51e6](https://bsd-hardware.info/?probe=965ced51e6) | Feb 12, 2022 |
| MSI           | MS-7C96                     | Desktop     | [c08331ad58](https://bsd-hardware.info/?probe=c08331ad58) | Feb 06, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [f107f7c1b1](https://bsd-hardware.info/?probe=f107f7c1b1) | Feb 06, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [f8476c0ea7](https://bsd-hardware.info/?probe=f8476c0ea7) | Feb 01, 2022 |
| Raspberry ... | Raspberry Pi 400            | Desktop     | [b35265f8f4](https://bsd-hardware.info/?probe=b35265f8f4) | Jan 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [2d65265b52](https://bsd-hardware.info/?probe=2d65265b52) | Jan 29, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [9c73c01062](https://bsd-hardware.info/?probe=9c73c01062) | Jan 28, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [208819a667](https://bsd-hardware.info/?probe=208819a667) | Jan 27, 2022 |
| WYSE          | D CLASS                     | Desktop     | [5f31ae866c](https://bsd-hardware.info/?probe=5f31ae866c) | Jan 24, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [d77aae8064](https://bsd-hardware.info/?probe=d77aae8064) | Jan 23, 2022 |
| MSI           | MS-7C56                     | Desktop     | [962ac1c7b0](https://bsd-hardware.info/?probe=962ac1c7b0) | Jan 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c36023a724](https://bsd-hardware.info/?probe=c36023a724) | Jan 17, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [26ccd8e3c5](https://bsd-hardware.info/?probe=26ccd8e3c5) | Jan 16, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [42eb986a58](https://bsd-hardware.info/?probe=42eb986a58) | Jan 11, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [e0e7b21668](https://bsd-hardware.info/?probe=e0e7b21668) | Jan 09, 2022 |
| Framework     | Laptop                      | Notebook    | [324f0fdebc](https://bsd-hardware.info/?probe=324f0fdebc) | Jan 05, 2022 |
| Framework     | Laptop                      | Notebook    | [ba81f48282](https://bsd-hardware.info/?probe=ba81f48282) | Jan 05, 2022 |
| Dell          | Latitude 3400               | Notebook    | [41bf32aff1](https://bsd-hardware.info/?probe=41bf32aff1) | Jan 02, 2022 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [0925acabe4](https://bsd-hardware.info/?probe=0925acabe4) | Dec 31, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [14d6cfb7a4](https://bsd-hardware.info/?probe=14d6cfb7a4) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [ce75fa56bd](https://bsd-hardware.info/?probe=ce75fa56bd) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [612825abe3](https://bsd-hardware.info/?probe=612825abe3) | Dec 27, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING     | Desktop     | [2ee4c7fefe](https://bsd-hardware.info/?probe=2ee4c7fefe) | Dec 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [4bb84a33fa](https://bsd-hardware.info/?probe=4bb84a33fa) | Dec 26, 2021 |
| Casper        | EXCALIBUR G900              | Notebook    | [539cf08655](https://bsd-hardware.info/?probe=539cf08655) | Dec 24, 2021 |
| Samsung       | 530XBB                      | Notebook    | [fe0adb59d8](https://bsd-hardware.info/?probe=fe0adb59d8) | Dec 20, 2021 |
| Samsung       | R720                        | Notebook    | [620195d4aa](https://bsd-hardware.info/?probe=620195d4aa) | Dec 20, 2021 |
| HP            | Compaq 15                   | Notebook    | [1e8b1ce39b](https://bsd-hardware.info/?probe=1e8b1ce39b) | Dec 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [d271c4a29f](https://bsd-hardware.info/?probe=d271c4a29f) | Dec 15, 2021 |
| Intel         | SharkBay Platform           | Notebook    | [383d1e31c9](https://bsd-hardware.info/?probe=383d1e31c9) | Dec 14, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [0215354bfc](https://bsd-hardware.info/?probe=0215354bfc) | Dec 13, 2021 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [a86326d049](https://bsd-hardware.info/?probe=a86326d049) | Dec 11, 2021 |
| Dell          | G15 5510                    | Notebook    | [2da7a07664](https://bsd-hardware.info/?probe=2da7a07664) | Dec 07, 2021 |
| Lenovo        | ThinkPad X61 7675H7U        | Notebook    | [545cbe065d](https://bsd-hardware.info/?probe=545cbe065d) | Dec 06, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [0d4c532744](https://bsd-hardware.info/?probe=0d4c532744) | Nov 29, 2021 |
| Dell          | G15 5510                    | Notebook    | [8846b3fd69](https://bsd-hardware.info/?probe=8846b3fd69) | Nov 27, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [923a99fade](https://bsd-hardware.info/?probe=923a99fade) | Nov 27, 2021 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [339779baad](https://bsd-hardware.info/?probe=339779baad) | Nov 26, 2021 |
| MSI           | MS-7C56                     | Desktop     | [d4e3f14ad4](https://bsd-hardware.info/?probe=d4e3f14ad4) | Nov 23, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [8b178d13c7](https://bsd-hardware.info/?probe=8b178d13c7) | Nov 22, 2021 |
| Alienware     | m15                         | Notebook    | [20afd3904b](https://bsd-hardware.info/?probe=20afd3904b) | Nov 21, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [63443924f3](https://bsd-hardware.info/?probe=63443924f3) | Nov 19, 2021 |
| Acer          | AO722                       | Notebook    | [98b88ae138](https://bsd-hardware.info/?probe=98b88ae138) | Nov 15, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [0391bf9ea4](https://bsd-hardware.info/?probe=0391bf9ea4) | Nov 14, 2021 |
| PC Engines    | APU2                        | Desktop     | [15a26da041](https://bsd-hardware.info/?probe=15a26da041) | Nov 14, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [34d905d6f3](https://bsd-hardware.info/?probe=34d905d6f3) | Nov 11, 2021 |
| Apple         | iMac13,1                    | All in one  | [3da0012112](https://bsd-hardware.info/?probe=3da0012112) | Nov 06, 2021 |
| Unknown       | Hardkernel ODROID-N2        | Desktop     | [42f6e357c9](https://bsd-hardware.info/?probe=42f6e357c9) | Nov 05, 2021 |
| Google        | Grunt                       | Notebook    | [aa07a1dd40](https://bsd-hardware.info/?probe=aa07a1dd40) | Nov 05, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [cdccf02902](https://bsd-hardware.info/?probe=cdccf02902) | Nov 04, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [2471e3f337](https://bsd-hardware.info/?probe=2471e3f337) | Nov 04, 2021 |
| Yanling       | YL-KBR6L                    | Desktop     | [35f1c905eb](https://bsd-hardware.info/?probe=35f1c905eb) | Nov 04, 2021 |
| Google        | Grunt                       | Notebook    | [c87e033731](https://bsd-hardware.info/?probe=c87e033731) | Nov 01, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [721ef0235c](https://bsd-hardware.info/?probe=721ef0235c) | Oct 30, 2021 |
| HP            | 0A60h                       | Desktop     | [5c227c5b61](https://bsd-hardware.info/?probe=5c227c5b61) | Oct 27, 2021 |
| HP            | ProDesk 600 G1 SFF          | Desktop     | [7f19a8a566](https://bsd-hardware.info/?probe=7f19a8a566) | Oct 26, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [9e254ab443](https://bsd-hardware.info/?probe=9e254ab443) | Oct 23, 2021 |
| Supermicro    | X7SBL                       | Desktop     | [f5b4e8e7ab](https://bsd-hardware.info/?probe=f5b4e8e7ab) | Oct 23, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [1d5e3e5bc3](https://bsd-hardware.info/?probe=1d5e3e5bc3) | Oct 22, 2021 |
| Google        | Grunt                       | Notebook    | [259f96d9c8](https://bsd-hardware.info/?probe=259f96d9c8) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [3337c00433](https://bsd-hardware.info/?probe=3337c00433) | Oct 22, 2021 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [b20953f2f4](https://bsd-hardware.info/?probe=b20953f2f4) | Oct 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [bbdfde368b](https://bsd-hardware.info/?probe=bbdfde368b) | Oct 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [b4ba704356](https://bsd-hardware.info/?probe=b4ba704356) | Oct 17, 2021 |
| Google        | Grunt                       | Notebook    | [e6d4421a4d](https://bsd-hardware.info/?probe=e6d4421a4d) | Oct 16, 2021 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [e762f9146e](https://bsd-hardware.info/?probe=e762f9146e) | Oct 16, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [1a5bae2227](https://bsd-hardware.info/?probe=1a5bae2227) | Oct 15, 2021 |
| ASUSTek       | P10S-I Series               | Desktop     | [d086bf947a](https://bsd-hardware.info/?probe=d086bf947a) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H                  | Desktop     | [445b53ddba](https://bsd-hardware.info/?probe=445b53ddba) | Oct 15, 2021 |
| Protectli     | FW6                         | Desktop     | [de39c4e316](https://bsd-hardware.info/?probe=de39c4e316) | Oct 15, 2021 |
| Google        | Grunt                       | Notebook    | [ee9b2d7ad3](https://bsd-hardware.info/?probe=ee9b2d7ad3) | Oct 15, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [9eab523504](https://bsd-hardware.info/?probe=9eab523504) | Oct 14, 2021 |
| MSI           | MS-7D54                     | Desktop     | [ac1f6ee8a6](https://bsd-hardware.info/?probe=ac1f6ee8a6) | Oct 13, 2021 |
| Google        | Grunt                       | Notebook    | [e76c73d9a3](https://bsd-hardware.info/?probe=e76c73d9a3) | Oct 11, 2021 |
| Supermicro    | X11SCE-F                    | Server      | [5731b09f69](https://bsd-hardware.info/?probe=5731b09f69) | Oct 11, 2021 |
| Gigabyte      | B450M DS3H                  | Desktop     | [50e4e13ee0](https://bsd-hardware.info/?probe=50e4e13ee0) | Oct 07, 2021 |
| MSI           | MS-7B53                     | Desktop     | [c7104d301e](https://bsd-hardware.info/?probe=c7104d301e) | Oct 05, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [49173900e7](https://bsd-hardware.info/?probe=49173900e7) | Oct 04, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [d05a877535](https://bsd-hardware.info/?probe=d05a877535) | Oct 03, 2021 |
| ASUSTek       | X555LB                      | Notebook    | [e3443d9f27](https://bsd-hardware.info/?probe=e3443d9f27) | Oct 02, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [46672cf89f](https://bsd-hardware.info/?probe=46672cf89f) | Oct 01, 2021 |
| IBM           | ThinkPad H 1846AQG          | Notebook    | [5e5c7247ca](https://bsd-hardware.info/?probe=5e5c7247ca) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [838a177f57](https://bsd-hardware.info/?probe=838a177f57) | Sep 30, 2021 |
| ASUSTek       | UX305FA                     | Notebook    | [decf219ff2](https://bsd-hardware.info/?probe=decf219ff2) | Sep 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [d9762d6c2d](https://bsd-hardware.info/?probe=d9762d6c2d) | Sep 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0d00ce5de9](https://bsd-hardware.info/?probe=0d00ce5de9) | Sep 22, 2021 |
| HP            | Pro3500 Series              | Desktop     | [abf3223f32](https://bsd-hardware.info/?probe=abf3223f32) | Sep 19, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [7a800aec88](https://bsd-hardware.info/?probe=7a800aec88) | Sep 15, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Notebook    | [577e0ed7fe](https://bsd-hardware.info/?probe=577e0ed7fe) | Sep 13, 2021 |
| NF541         | Unknown                     | Desktop     | [deb29af749](https://bsd-hardware.info/?probe=deb29af749) | Sep 11, 2021 |
| MSI           | MS-7A34                     | Desktop     | [decfe43121](https://bsd-hardware.info/?probe=decfe43121) | Sep 10, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [6e50039406](https://bsd-hardware.info/?probe=6e50039406) | Sep 09, 2021 |
| PC Engines    | apu4                        | Desktop     | [9557835b54](https://bsd-hardware.info/?probe=9557835b54) | Sep 09, 2021 |
| Gigabyte      | BRi3(H)-10110               | Desktop     | [9aa3540749](https://bsd-hardware.info/?probe=9aa3540749) | Sep 09, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [4632683b4b](https://bsd-hardware.info/?probe=4632683b4b) | Sep 08, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [f860e13b6b](https://bsd-hardware.info/?probe=f860e13b6b) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [4cc349d29a](https://bsd-hardware.info/?probe=4cc349d29a) | Sep 08, 2021 |
| Lenovo        | ThinkPad X250 20CM0046US    | Notebook    | [1ed50b75f1](https://bsd-hardware.info/?probe=1ed50b75f1) | Sep 08, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1b6bf4666c](https://bsd-hardware.info/?probe=1b6bf4666c) | Sep 05, 2021 |
| Sony          | VGN-P698E                   | Notebook    | [c8274e858d](https://bsd-hardware.info/?probe=c8274e858d) | Aug 30, 2021 |
| Lenovo        | FLEX 3-1120 80LX            | Notebook    | [2f1a1a42b8](https://bsd-hardware.info/?probe=2f1a1a42b8) | Aug 29, 2021 |
| Lenovo        | ThinkPad P73 20QRS00200     | Notebook    | [dfc86a0368](https://bsd-hardware.info/?probe=dfc86a0368) | Aug 29, 2021 |
| Gigabyte      | GA-7VT600                   | Desktop     | [83b86f3e8c](https://bsd-hardware.info/?probe=83b86f3e8c) | Aug 23, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [43c82b1b16](https://bsd-hardware.info/?probe=43c82b1b16) | Aug 22, 2021 |
| IBM           | ThinkPad T42 2374K46        | Notebook    | [d93b6d68fa](https://bsd-hardware.info/?probe=d93b6d68fa) | Aug 18, 2021 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | Notebook    | [f7725f06df](https://bsd-hardware.info/?probe=f7725f06df) | Aug 18, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Notebook    | [6f7976c329](https://bsd-hardware.info/?probe=6f7976c329) | Aug 16, 2021 |
| Standard      | TF                          | Notebook    | [c7995f2022](https://bsd-hardware.info/?probe=c7995f2022) | Aug 12, 2021 |
| HP            | Notebook                    | Notebook    | [a3c3297cd2](https://bsd-hardware.info/?probe=a3c3297cd2) | Aug 08, 2021 |
| HP            | Notebook                    | Notebook    | [0c316107a4](https://bsd-hardware.info/?probe=0c316107a4) | Aug 08, 2021 |
| Unknown       | FriendlyElec NanoPi R4S     | Desktop     | [ac10928ac3](https://bsd-hardware.info/?probe=ac10928ac3) | Aug 05, 2021 |
| Lenovo        | ThinkPad T430 2349U2B       | Notebook    | [90d85e011f](https://bsd-hardware.info/?probe=90d85e011f) | Jul 31, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Notebook    | [5404f763dd](https://bsd-hardware.info/?probe=5404f763dd) | Jul 26, 2021 |
| Lenovo        | ThinkPad T400 2767WSB       | Notebook    | [36ce1d1e00](https://bsd-hardware.info/?probe=36ce1d1e00) | Jul 24, 2021 |
| Unknown       | Pine64 Rock64               | Desktop     | [0df3f7572c](https://bsd-hardware.info/?probe=0df3f7572c) | Jul 23, 2021 |
| MSI           | MS-1613                     | Notebook    | [795e61c1a3](https://bsd-hardware.info/?probe=795e61c1a3) | Jul 21, 2021 |
| ASUSTek       | B202                        | Desktop     | [9f5f0a4117](https://bsd-hardware.info/?probe=9f5f0a4117) | Jul 21, 2021 |
| Lenovo        | ThinkPad X270 20HNA006ID    | Notebook    | [6fc7c972a5](https://bsd-hardware.info/?probe=6fc7c972a5) | Jul 19, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [5b43300a93](https://bsd-hardware.info/?probe=5b43300a93) | Jul 13, 2021 |
| Unknown       | Pine64 Rock64               | Desktop     | [83c18360fc](https://bsd-hardware.info/?probe=83c18360fc) | Jul 12, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [740c5182d3](https://bsd-hardware.info/?probe=740c5182d3) | Jul 11, 2021 |
| HP            | ProLiant DL360e Gen8        | Desktop     | [30eeb098b0](https://bsd-hardware.info/?probe=30eeb098b0) | Jul 10, 2021 |
| HP            | ProLiant DL320 G5           | Desktop     | [3b4ee33976](https://bsd-hardware.info/?probe=3b4ee33976) | Jul 10, 2021 |
| Foxconn       | AT-7000 Series              | Desktop     | [3802fb98b5](https://bsd-hardware.info/?probe=3802fb98b5) | Jul 10, 2021 |
| Unknown       | Pine64 Rock64               | Desktop     | [106c7823a8](https://bsd-hardware.info/?probe=106c7823a8) | Jul 10, 2021 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [a8c497b58b](https://bsd-hardware.info/?probe=a8c497b58b) | Jul 09, 2021 |
| Unknown       | Pine64 Rock64               | Desktop     | [9cffa29c69](https://bsd-hardware.info/?probe=9cffa29c69) | Jul 08, 2021 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [55f46bc85d](https://bsd-hardware.info/?probe=55f46bc85d) | Jul 07, 2021 |
| HP            | Pavilion dm1                | Notebook    | [a863347147](https://bsd-hardware.info/?probe=a863347147) | Jul 03, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Notebook    | [72e208aa92](https://bsd-hardware.info/?probe=72e208aa92) | Jul 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [cfb0e172cb](https://bsd-hardware.info/?probe=cfb0e172cb) | Jun 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [443817737d](https://bsd-hardware.info/?probe=443817737d) | Jun 24, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [1b8d66e5f0](https://bsd-hardware.info/?probe=1b8d66e5f0) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [bb610333d0](https://bsd-hardware.info/?probe=bb610333d0) | Jun 22, 2021 |
| Unknown       | Unknown                     | Notebook    | [f37bf77853](https://bsd-hardware.info/?probe=f37bf77853) | Jun 20, 2021 |
| ASRock        | X99 WS                      | Desktop     | [201a7417a5](https://bsd-hardware.info/?probe=201a7417a5) | Jun 11, 2021 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [1e8ac47693](https://bsd-hardware.info/?probe=1e8ac47693) | Jun 08, 2021 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [bd4a74c5e5](https://bsd-hardware.info/?probe=bd4a74c5e5) | Jun 08, 2021 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [e54175f99f](https://bsd-hardware.info/?probe=e54175f99f) | Jun 06, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | Notebook    | [b60f4a19ee](https://bsd-hardware.info/?probe=b60f4a19ee) | Jun 06, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [58c8cdc060](https://bsd-hardware.info/?probe=58c8cdc060) | Jun 05, 2021 |
| Lenovo        | ThinkPad T430 23511A6       | Notebook    | [89fb2aa493](https://bsd-hardware.info/?probe=89fb2aa493) | Jun 05, 2021 |
| Lenovo        | ThinkPad T400 6475K43       | Notebook    | [1b3e80e2e9](https://bsd-hardware.info/?probe=1b3e80e2e9) | Jun 03, 2021 |
| Supermicro    | Super Server                | Server      | [68579d4660](https://bsd-hardware.info/?probe=68579d4660) | Jun 03, 2021 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [392df069bd](https://bsd-hardware.info/?probe=392df069bd) | Jun 02, 2021 |
| Apple         | PowerBook5,2                | Notebook    | [8cc0aab53c](https://bsd-hardware.info/?probe=8cc0aab53c) | May 31, 2021 |
| Shuttle       | DS77U                       | Desktop     | [5d1c78145e](https://bsd-hardware.info/?probe=5d1c78145e) | May 30, 2021 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [ca05acd52f](https://bsd-hardware.info/?probe=ca05acd52f) | May 30, 2021 |
| HP            | 530 Notebook PC(KP477AA#... | Notebook    | [9c7b85c190](https://bsd-hardware.info/?probe=9c7b85c190) | May 30, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [1d1a5afcfb](https://bsd-hardware.info/?probe=1d1a5afcfb) | May 28, 2021 |
| Alienware     | Aurora Ryzen Edition        | Desktop     | [b9dc8b182c](https://bsd-hardware.info/?probe=b9dc8b182c) | May 28, 2021 |
| Apple         | PowerMac10,1                | Desktop     | [d098ba539d](https://bsd-hardware.info/?probe=d098ba539d) | May 27, 2021 |
| ASUSTek       | B202                        | Desktop     | [0b66a5fd20](https://bsd-hardware.info/?probe=0b66a5fd20) | May 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [b296fb35e2](https://bsd-hardware.info/?probe=b296fb35e2) | May 19, 2021 |
| Unknown       | Unknown                     | Notebook    | [750e01de05](https://bsd-hardware.info/?probe=750e01de05) | May 19, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [ef5e9ec095](https://bsd-hardware.info/?probe=ef5e9ec095) | May 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [65f5931910](https://bsd-hardware.info/?probe=65f5931910) | May 18, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [1e9f399d73](https://bsd-hardware.info/?probe=1e9f399d73) | May 17, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [109f3afa21](https://bsd-hardware.info/?probe=109f3afa21) | May 17, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [f92f43bc54](https://bsd-hardware.info/?probe=f92f43bc54) | May 17, 2021 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [33bc82e701](https://bsd-hardware.info/?probe=33bc82e701) | May 17, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [bf76401b74](https://bsd-hardware.info/?probe=bf76401b74) | May 17, 2021 |
| PC Engines    | APU2                        | Desktop     | [c99a0b0e4d](https://bsd-hardware.info/?probe=c99a0b0e4d) | May 05, 2021 |
| ASRock        | X99 WS                      | Desktop     | [eb20367455](https://bsd-hardware.info/?probe=eb20367455) | May 05, 2021 |
| Supermicro    | X8STi                       | Desktop     | [c615ef1edf](https://bsd-hardware.info/?probe=c615ef1edf) | May 04, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [bfe7ec0975](https://bsd-hardware.info/?probe=bfe7ec0975) | May 03, 2021 |
| Lenovo        | ThinkCentre M93p 10AAS25... | Desktop     | [a9bbd07ad9](https://bsd-hardware.info/?probe=a9bbd07ad9) | May 03, 2021 |
| PC Engines    | apu1                        | Desktop     | [7b4678c7ef](https://bsd-hardware.info/?probe=7b4678c7ef) | May 03, 2021 |
| Acer          | AO531h                      | Notebook    | [614326a3d3](https://bsd-hardware.info/?probe=614326a3d3) | May 03, 2021 |
| Acer          | AO531h                      | Notebook    | [9de7465352](https://bsd-hardware.info/?probe=9de7465352) | May 03, 2021 |
| ASUSTek       | P10S-I Series               | Desktop     | [6548ae7d88](https://bsd-hardware.info/?probe=6548ae7d88) | May 01, 2021 |
| PC Engines    | apu1                        | Desktop     | [c5ae3337e7](https://bsd-hardware.info/?probe=c5ae3337e7) | May 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [6e8891f184](https://bsd-hardware.info/?probe=6e8891f184) | Apr 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [7ec73fe36d](https://bsd-hardware.info/?probe=7ec73fe36d) | Apr 23, 2021 |
| ASUSTek       | All Series                  | Desktop     | [ef6afe88d7](https://bsd-hardware.info/?probe=ef6afe88d7) | Apr 17, 2021 |
| Lenovo        | ThinkPad X201 Tablet 298... | Notebook    | [4faceaf6e5](https://bsd-hardware.info/?probe=4faceaf6e5) | Apr 17, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [f31eda4c16](https://bsd-hardware.info/?probe=f31eda4c16) | Apr 16, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [403a237513](https://bsd-hardware.info/?probe=403a237513) | Apr 14, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | Notebook    | [dcf202ea95](https://bsd-hardware.info/?probe=dcf202ea95) | Apr 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | Notebook    | [ee371f3e8f](https://bsd-hardware.info/?probe=ee371f3e8f) | Apr 08, 2021 |
| ECT           | One Computer AMD A10-785... | Desktop     | [de7e23b3e3](https://bsd-hardware.info/?probe=de7e23b3e3) | Apr 07, 2021 |
| HP            | t630 Thin Client            | Mini pc     | [994a246318](https://bsd-hardware.info/?probe=994a246318) | Apr 06, 2021 |
| Gigabyte      | GB-BXBT-2807                | Desktop     | [25e9765fc0](https://bsd-hardware.info/?probe=25e9765fc0) | Apr 03, 2021 |
| Lenovo        | ThinkPad Edge 05796AU       | Notebook    | [4a094815c0](https://bsd-hardware.info/?probe=4a094815c0) | Mar 24, 2021 |
| ASUSTek       | All Series                  | Desktop     | [c5bc64e4e9](https://bsd-hardware.info/?probe=c5bc64e4e9) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | Notebook    | [8d81204137](https://bsd-hardware.info/?probe=8d81204137) | Mar 22, 2021 |
| ASUSTek       | All Series                  | Desktop     | [700ff7d378](https://bsd-hardware.info/?probe=700ff7d378) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291EM4       | Notebook    | [9d393db103](https://bsd-hardware.info/?probe=9d393db103) | Mar 20, 2021 |
| Dell          | Latitude E7270              | Notebook    | [5ba79f9aa5](https://bsd-hardware.info/?probe=5ba79f9aa5) | Mar 19, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [b35adf782c](https://bsd-hardware.info/?probe=b35adf782c) | Mar 17, 2021 |
| HP            | ProLiant DL360 Gen9         | Desktop     | [b283b34881](https://bsd-hardware.info/?probe=b283b34881) | Mar 17, 2021 |
| Supermicro    | Super Server                | Server      | [ec1e532ea9](https://bsd-hardware.info/?probe=ec1e532ea9) | Mar 17, 2021 |
| Lenovo        | ThinkPad X280 20KESA000B    | Notebook    | [e2b586d597](https://bsd-hardware.info/?probe=e2b586d597) | Mar 17, 2021 |
| HP            | ProLiant DL360 Gen9         | Desktop     | [bf440e72a1](https://bsd-hardware.info/?probe=bf440e72a1) | Mar 17, 2021 |
| HP            | EliteDesk 800 G5 SFF        | Desktop     | [aaf9bc1c12](https://bsd-hardware.info/?probe=aaf9bc1c12) | Mar 17, 2021 |
| ASUSTek       | X510UA                      | Notebook    | [440f1ef3ec](https://bsd-hardware.info/?probe=440f1ef3ec) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [52584aaa97](https://bsd-hardware.info/?probe=52584aaa97) | Mar 14, 2021 |
| Apple         | iMac12,1                    | All in one  | [17466db7fd](https://bsd-hardware.info/?probe=17466db7fd) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [fb136a79e7](https://bsd-hardware.info/?probe=fb136a79e7) | Mar 13, 2021 |
| Panasonic     | CF-30KTP48NL                | Notebook    | [119b4875e9](https://bsd-hardware.info/?probe=119b4875e9) | Mar 12, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HL0... | Desktop     | [954c65dbcf](https://bsd-hardware.info/?probe=954c65dbcf) | Mar 11, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [9f4a3cd83d](https://bsd-hardware.info/?probe=9f4a3cd83d) | Mar 08, 2021 |
| ASUSTek       | All Series                  | Desktop     | [b4aec46644](https://bsd-hardware.info/?probe=b4aec46644) | Mar 07, 2021 |
| ASUSTek       | All Series                  | Desktop     | [f7b1921594](https://bsd-hardware.info/?probe=f7b1921594) | Mar 07, 2021 |
| Lenovo        | ThinkPad T400 6475P1G       | Notebook    | [6a0907b5e8](https://bsd-hardware.info/?probe=6a0907b5e8) | Mar 06, 2021 |
| ASUSTek       | X510UA                      | Notebook    | [f22eeba366](https://bsd-hardware.info/?probe=f22eeba366) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7d1ff5416d](https://bsd-hardware.info/?probe=7d1ff5416d) | Mar 01, 2021 |
| Acer          | Spin SP111-32N              | Notebook    | [9f44af71aa](https://bsd-hardware.info/?probe=9f44af71aa) | Feb 28, 2021 |
| Dell          | Inspiron 1000               | Notebook    | [70604dcbfa](https://bsd-hardware.info/?probe=70604dcbfa) | Feb 28, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [fb890afc86](https://bsd-hardware.info/?probe=fb890afc86) | Feb 28, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [6c7150dc1b](https://bsd-hardware.info/?probe=6c7150dc1b) | Feb 24, 2021 |
| ASRock        | J4205-ITX                   | Desktop     | [c8e0b22858](https://bsd-hardware.info/?probe=c8e0b22858) | Feb 23, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [41ea02c8bc](https://bsd-hardware.info/?probe=41ea02c8bc) | Feb 21, 2021 |
| Acer          | AOA150                      | Notebook    | [91e5ec60b9](https://bsd-hardware.info/?probe=91e5ec60b9) | Feb 21, 2021 |
| IBM           | ThinkPad T42 2374K46        | Notebook    | [311f93ab37](https://bsd-hardware.info/?probe=311f93ab37) | Feb 20, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [529baeb345](https://bsd-hardware.info/?probe=529baeb345) | Feb 20, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [65f1904b56](https://bsd-hardware.info/?probe=65f1904b56) | Feb 20, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [c2dded2160](https://bsd-hardware.info/?probe=c2dded2160) | Feb 19, 2021 |
| PC Engines    | apu4                        | Desktop     | [b30884fc0e](https://bsd-hardware.info/?probe=b30884fc0e) | Feb 18, 2021 |
| PC Engines    | apu3                        | Desktop     | [449967354c](https://bsd-hardware.info/?probe=449967354c) | Feb 18, 2021 |
| PC Engines    | apu2                        | Desktop     | [b911e3bec2](https://bsd-hardware.info/?probe=b911e3bec2) | Feb 18, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [4f646f53e9](https://bsd-hardware.info/?probe=4f646f53e9) | Feb 14, 2021 |
| Shuttle       | DS77U                       | Desktop     | [2d0bd0e99a](https://bsd-hardware.info/?probe=2d0bd0e99a) | Feb 14, 2021 |
| Dell          | Inspiron 1000               | Notebook    | [104175ae13](https://bsd-hardware.info/?probe=104175ae13) | Feb 13, 2021 |
| Sony          | VPCX115KX                   | Notebook    | [fef3d94e6c](https://bsd-hardware.info/?probe=fef3d94e6c) | Feb 12, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [3b4a7e7fc2](https://bsd-hardware.info/?probe=3b4a7e7fc2) | Feb 10, 2021 |
| Sony          | VPCF12C5E                   | Notebook    | [df8c1de8a5](https://bsd-hardware.info/?probe=df8c1de8a5) | Feb 07, 2021 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [e1c3b89d0d](https://bsd-hardware.info/?probe=e1c3b89d0d) | Feb 06, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [b35f7a5610](https://bsd-hardware.info/?probe=b35f7a5610) | Feb 05, 2021 |
| Microsoft     | Surface Go 2                | Tablet      | [69c8123ec6](https://bsd-hardware.info/?probe=69c8123ec6) | Feb 01, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [828a9df369](https://bsd-hardware.info/?probe=828a9df369) | Feb 01, 2021 |
| IBM           | ThinkPad T42 2373K9G        | Notebook    | [a12c3a0b21](https://bsd-hardware.info/?probe=a12c3a0b21) | Feb 01, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [c8af335c01](https://bsd-hardware.info/?probe=c8af335c01) | Jan 29, 2021 |
| Lenovo        | ThinkPad T61 7661AU5        | Notebook    | [23e498234e](https://bsd-hardware.info/?probe=23e498234e) | Jan 28, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | Desktop     | [8c953bac3f](https://bsd-hardware.info/?probe=8c953bac3f) | Jan 25, 2021 |
| ASUSTek       | All Series                  | Desktop     | [7ebe6eee38](https://bsd-hardware.info/?probe=7ebe6eee38) | Jan 25, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2a81a1bd1f](https://bsd-hardware.info/?probe=2a81a1bd1f) | Jan 24, 2021 |
| Sun           | SUNW,Sun-Blade-1500         | Desktop     | [647618a0ca](https://bsd-hardware.info/?probe=647618a0ca) | Jan 22, 2021 |
| PC Engines    | apu1                        | Desktop     | [a5d18dcbbc](https://bsd-hardware.info/?probe=a5d18dcbbc) | Jan 21, 2021 |
| PC Engines    | apu1                        | Desktop     | [70918da1e7](https://bsd-hardware.info/?probe=70918da1e7) | Jan 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5f469ceeb9](https://bsd-hardware.info/?probe=5f469ceeb9) | Jan 20, 2021 |
| Sun           | SUNW,Sun-Blade-100          | Desktop     | [299c76eb85](https://bsd-hardware.info/?probe=299c76eb85) | Jan 18, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [36ef631bfe](https://bsd-hardware.info/?probe=36ef631bfe) | Jan 05, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [6cd195aa69](https://bsd-hardware.info/?probe=6cd195aa69) | Jan 05, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [50ca36db01](https://bsd-hardware.info/?probe=50ca36db01) | Jan 05, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [112792b300](https://bsd-hardware.info/?probe=112792b300) | Jan 02, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [8b571cc947](https://bsd-hardware.info/?probe=8b571cc947) | Jan 02, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [893b9111c6](https://bsd-hardware.info/?probe=893b9111c6) | Dec 27, 2020 |
| HP            | 240 G1                      | Notebook    | [3ee90471d0](https://bsd-hardware.info/?probe=3ee90471d0) | Dec 26, 2020 |
| Apple         | PowerBook5,8                | Notebook    | [96f550a537](https://bsd-hardware.info/?probe=96f550a537) | Dec 24, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [f0b9687ab8](https://bsd-hardware.info/?probe=f0b9687ab8) | Dec 22, 2020 |
| Lenovo        | ThinkPad T400 6475K43       | Notebook    | [30500a25d3](https://bsd-hardware.info/?probe=30500a25d3) | Dec 18, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d019e14245](https://bsd-hardware.info/?probe=d019e14245) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7e80ced15e](https://bsd-hardware.info/?probe=7e80ced15e) | Dec 16, 2020 |
| Unknown       | ODYSSEY-X86J4105            | Desktop     | [17749e13c8](https://bsd-hardware.info/?probe=17749e13c8) | Dec 16, 2020 |
| Unknown       | Spring Peak                 | Notebook    | [b61f5c268a](https://bsd-hardware.info/?probe=b61f5c268a) | Dec 15, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d13e0a1749](https://bsd-hardware.info/?probe=d13e0a1749) | Dec 15, 2020 |
| Supermicro    | X11DDW-L                    | Desktop     | [57a5022e27](https://bsd-hardware.info/?probe=57a5022e27) | Dec 14, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3a78e7dc1a](https://bsd-hardware.info/?probe=3a78e7dc1a) | Dec 11, 2020 |
| Dell          | Latitude 3300               | Notebook    | [108a030875](https://bsd-hardware.info/?probe=108a030875) | Dec 07, 2020 |
| Fujitsu       | LIFEBOOK P1610              | Notebook    | [e8ee627d6e](https://bsd-hardware.info/?probe=e8ee627d6e) | Dec 07, 2020 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [2544123f79](https://bsd-hardware.info/?probe=2544123f79) | Dec 06, 2020 |
| Lenovo        | ThinkPad T410 2537NB5       | Notebook    | [d6a3aa6f8d](https://bsd-hardware.info/?probe=d6a3aa6f8d) | Dec 06, 2020 |
| Lenovo        | ThinkPad X201 3680FAG       | Notebook    | [1ba69078df](https://bsd-hardware.info/?probe=1ba69078df) | Dec 06, 2020 |
| ASUSTek       | P4P800-VM                   | Desktop     | [4fe4c14195](https://bsd-hardware.info/?probe=4fe4c14195) | Dec 05, 2020 |
| Apple         | Xserve3,1                   | Desktop     | [7329a7650d](https://bsd-hardware.info/?probe=7329a7650d) | Dec 05, 2020 |
| Gigabyte      | Unknown                     | Desktop     | [8a9ae48d42](https://bsd-hardware.info/?probe=8a9ae48d42) | Dec 01, 2020 |
| Lenovo        | ThinkPad W520 42763JU       | Notebook    | [5c50582307](https://bsd-hardware.info/?probe=5c50582307) | Nov 30, 2020 |
| HP            | Compaq dc7800 Small Form... | Desktop     | [2b49eb75dc](https://bsd-hardware.info/?probe=2b49eb75dc) | Nov 27, 2020 |
| HP            | Compaq dc7800 Small Form... | Desktop     | [3fe6528682](https://bsd-hardware.info/?probe=3fe6528682) | Nov 27, 2020 |
| Dell          | OptiPlex GX1 500M+          | Desktop     | [deb0d463ab](https://bsd-hardware.info/?probe=deb0d463ab) | Nov 27, 2020 |
| Dell          | OptiPlex GX1 500M+          | Desktop     | [5186eb9e52](https://bsd-hardware.info/?probe=5186eb9e52) | Nov 26, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | Notebook    | [467a6fc001](https://bsd-hardware.info/?probe=467a6fc001) | Nov 26, 2020 |
| Lenovo        | Unknown                     | Notebook    | [1cf65625a7](https://bsd-hardware.info/?probe=1cf65625a7) | Nov 24, 2020 |
| HP            | Setzer                      | Notebook    | [da7914cdd5](https://bsd-hardware.info/?probe=da7914cdd5) | Nov 22, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9cf79cf54b](https://bsd-hardware.info/?probe=9cf79cf54b) | Nov 22, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [cab036429d](https://bsd-hardware.info/?probe=cab036429d) | Nov 22, 2020 |
| Unknown       | cavium,ubnt_e300            | Desktop     | [b8524b5002](https://bsd-hardware.info/?probe=b8524b5002) | Nov 20, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B      | Desktop     | [c030400069](https://bsd-hardware.info/?probe=c030400069) | Nov 19, 2020 |
| ASRock        | IMB-191                     | Desktop     | [76991234cd](https://bsd-hardware.info/?probe=76991234cd) | Nov 18, 2020 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c03bc18b3a](https://bsd-hardware.info/?probe=c03bc18b3a) | Nov 18, 2020 |
| MSI           | MS-B09012                   | Desktop     | [7ba791108f](https://bsd-hardware.info/?probe=7ba791108f) | Nov 18, 2020 |
| PC Engines    | APU2                        | Desktop     | [b4f5d7d344](https://bsd-hardware.info/?probe=b4f5d7d344) | Nov 16, 2020 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [778cb9f428](https://bsd-hardware.info/?probe=778cb9f428) | Nov 16, 2020 |
| Lenovo        | ThinkPad T450 20BVA020AU    | Notebook    | [5d8bce59e8](https://bsd-hardware.info/?probe=5d8bce59e8) | Nov 16, 2020 |
| Gigabyte      | GB-BXBT-2807                | Desktop     | [c11b475d28](https://bsd-hardware.info/?probe=c11b475d28) | Nov 13, 2020 |
| Lenovo        | ThinkPad T60 87445BU        | Notebook    | [bfd9130d4b](https://bsd-hardware.info/?probe=bfd9130d4b) | Nov 10, 2020 |
| Lenovo        | ThinkCentre M92p 3212AD2    | Desktop     | [579528e284](https://bsd-hardware.info/?probe=579528e284) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | Notebook    | [6a0f910601](https://bsd-hardware.info/?probe=6a0f910601) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | Notebook    | [6dca4cdd18](https://bsd-hardware.info/?probe=6dca4cdd18) | Nov 10, 2020 |
| Lenovo        | ThinkPad T450s 20BWS2XS0... | Notebook    | [0b04a395a7](https://bsd-hardware.info/?probe=0b04a395a7) | Nov 10, 2020 |
| Gigabyte      | M61SME-S2L                  | Desktop     | [d8809eb5e7](https://bsd-hardware.info/?probe=d8809eb5e7) | Nov 09, 2020 |
| Gigabyte      | M61SME-S2L                  | Desktop     | [e5f658c70a](https://bsd-hardware.info/?probe=e5f658c70a) | Nov 09, 2020 |
| Pegatron      | SKLD4-P1                    | Desktop     | [ea548b4c71](https://bsd-hardware.info/?probe=ea548b4c71) | Nov 08, 2020 |
| Lenovo        | ThinkPad T460 20FN003LGE    | Notebook    | [1b7b105e5c](https://bsd-hardware.info/?probe=1b7b105e5c) | Nov 08, 2020 |
| IBM           | ThinkPad T42 2373K9G        | Notebook    | [e041100bb6](https://bsd-hardware.info/?probe=e041100bb6) | Nov 08, 2020 |
| Soekris En... | net5501                     | Desktop     | [bd9930a18a](https://bsd-hardware.info/?probe=bd9930a18a) | Nov 06, 2020 |
| Soekris En... | net6501                     | Desktop     | [fdf124653b](https://bsd-hardware.info/?probe=fdf124653b) | Nov 06, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | Notebook    | [bdc2de68ce](https://bsd-hardware.info/?probe=bdc2de68ce) | Nov 05, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | Notebook    | [8cfb32120b](https://bsd-hardware.info/?probe=8cfb32120b) | Nov 05, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [ebd246c141](https://bsd-hardware.info/?probe=ebd246c141) | Nov 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [f2e085e11a](https://bsd-hardware.info/?probe=f2e085e11a) | Nov 04, 2020 |
| MSI           | MS-7A34                     | Desktop     | [8c87d6b643](https://bsd-hardware.info/?probe=8c87d6b643) | Nov 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [9b6b24708e](https://bsd-hardware.info/?probe=9b6b24708e) | Nov 03, 2020 |
| Dell          | Precision M4800             | Notebook    | [ca6d4c4bb7](https://bsd-hardware.info/?probe=ca6d4c4bb7) | Nov 03, 2020 |
| Dell          | Precision M4800             | Notebook    | [c6a7b68c75](https://bsd-hardware.info/?probe=c6a7b68c75) | Nov 03, 2020 |
| Lenovo        | ThinkPad T500 2087A16       | Notebook    | [334eacfe16](https://bsd-hardware.info/?probe=334eacfe16) | Nov 03, 2020 |
| Lenovo        | ThinkPad W530 2436CTO       | Notebook    | [ded161fe2e](https://bsd-hardware.info/?probe=ded161fe2e) | Oct 31, 2020 |
| Lenovo        | ThinkPad W530 2436CTO       | Notebook    | [e108d4a375](https://bsd-hardware.info/?probe=e108d4a375) | Oct 31, 2020 |
| ASUSTek       | X102BA                      | Notebook    | [9156250b96](https://bsd-hardware.info/?probe=9156250b96) | Oct 31, 2020 |
| PC Engines    | apu2                        | Desktop     | [e0361ddbad](https://bsd-hardware.info/?probe=e0361ddbad) | Oct 31, 2020 |
| Intel         | NUC7i5BNH                   | Mini pc     | [ea59613cff](https://bsd-hardware.info/?probe=ea59613cff) | Oct 31, 2020 |
| ASUSTek       | B75M-A                      | Desktop     | [43ece33e8c](https://bsd-hardware.info/?probe=43ece33e8c) | Oct 31, 2020 |
| Intel         | D945GCLF2                   | Desktop     | [58678b0643](https://bsd-hardware.info/?probe=58678b0643) | Oct 30, 2020 |
| Intel         | D945GCLF2                   | Desktop     | [3354fb903b](https://bsd-hardware.info/?probe=3354fb903b) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [973b62551f](https://bsd-hardware.info/?probe=973b62551f) | Oct 30, 2020 |
| eMachines     | EL1200                      | Desktop     | [ae59908738](https://bsd-hardware.info/?probe=ae59908738) | Oct 30, 2020 |
| Acer          | Veriton M6610G              | Desktop     | [7dd00aa8b1](https://bsd-hardware.info/?probe=7dd00aa8b1) | Oct 30, 2020 |
| eMachines     | EL1200                      | Desktop     | [5bc54351be](https://bsd-hardware.info/?probe=5bc54351be) | Oct 30, 2020 |
| ECS           | BSWI-D2                     | Desktop     | [c5b07f5c31](https://bsd-hardware.info/?probe=c5b07f5c31) | Oct 30, 2020 |
| Acer          | Extensa 2540                | Notebook    | [26670a4ae9](https://bsd-hardware.info/?probe=26670a4ae9) | Oct 30, 2020 |
| ASRock        | N3160-NUC IPC               | Desktop     | [8d13af2f0b](https://bsd-hardware.info/?probe=8d13af2f0b) | Oct 28, 2020 |
| ASRock        | N3160-NUC IPC               | Desktop     | [8714fe0665](https://bsd-hardware.info/?probe=8714fe0665) | Oct 28, 2020 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [4594c1084c](https://bsd-hardware.info/?probe=4594c1084c) | Oct 28, 2020 |
| Shuttle       | DS77U                       | Desktop     | [c70e526574](https://bsd-hardware.info/?probe=c70e526574) | Oct 27, 2020 |
| Intel         | NUC5CPYB                    | Mini pc     | [1ec5c12f0b](https://bsd-hardware.info/?probe=1ec5c12f0b) | Oct 27, 2020 |
| Lenovo        | ThinkPad T450 20BV0005US    | Notebook    | [603e66300a](https://bsd-hardware.info/?probe=603e66300a) | Oct 27, 2020 |
| PC Engines    | apu2                        | Desktop     | [ce4c41d466](https://bsd-hardware.info/?probe=ce4c41d466) | Oct 26, 2020 |
| Dell          | PowerEdge R230              | Desktop     | [1422e9737b](https://bsd-hardware.info/?probe=1422e9737b) | Oct 26, 2020 |
| Supermicro    | X8STi                       | Desktop     | [1b64902781](https://bsd-hardware.info/?probe=1b64902781) | Oct 26, 2020 |
| HP            | 120-1136                    | Desktop     | [12f3eb0227](https://bsd-hardware.info/?probe=12f3eb0227) | Oct 25, 2020 |
| Lenovo        | ThinkPad T500 2087A16       | Notebook    | [cf8228f878](https://bsd-hardware.info/?probe=cf8228f878) | Oct 25, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [04b6ad9952](https://bsd-hardware.info/?probe=04b6ad9952) | Oct 25, 2020 |
| Supermicro    | X11SSW-F                    | Desktop     | [ca07d7ef48](https://bsd-hardware.info/?probe=ca07d7ef48) | Oct 25, 2020 |
| Gigabyte      | X58A-UD5                    | Desktop     | [6e642641e5](https://bsd-hardware.info/?probe=6e642641e5) | Oct 25, 2020 |
| AZW           | Z83 II                      | Desktop     | [9416876f20](https://bsd-hardware.info/?probe=9416876f20) | Oct 24, 2020 |
| AZW           | Z83 II                      | Desktop     | [19b1b4d85d](https://bsd-hardware.info/?probe=19b1b4d85d) | Oct 24, 2020 |
| Dell          | Precision WorkStation T7... | Desktop     | [c01ce9ec81](https://bsd-hardware.info/?probe=c01ce9ec81) | Oct 24, 2020 |
| Lenovo        | Unknown                     | Notebook    | [7bab490506](https://bsd-hardware.info/?probe=7bab490506) | Oct 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [03602ed2c0](https://bsd-hardware.info/?probe=03602ed2c0) | Oct 23, 2020 |
| Lenovo        | Unknown                     | Notebook    | [c659708e94](https://bsd-hardware.info/?probe=c659708e94) | Oct 23, 2020 |
| IBM           | ThinkPad X41 2525F8G        | Notebook    | [c58f946d2a](https://bsd-hardware.info/?probe=c58f946d2a) | Oct 22, 2020 |
| PC Engines    | APU2                        | Desktop     | [5cee7fa636](https://bsd-hardware.info/?probe=5cee7fa636) | Oct 22, 2020 |
| MSI           | MS-7345                     | Desktop     | [96cc99accc](https://bsd-hardware.info/?probe=96cc99accc) | Oct 22, 2020 |
| Dell          | Precision 3510              | Notebook    | [85a55ab7c3](https://bsd-hardware.info/?probe=85a55ab7c3) | Oct 22, 2020 |
| MSI           | MS-7816                     | Desktop     | [337e5b8e0c](https://bsd-hardware.info/?probe=337e5b8e0c) | Oct 22, 2020 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [f4aa59ba56](https://bsd-hardware.info/?probe=f4aa59ba56) | Oct 22, 2020 |
| ASRock        | DN2800MT                    | Desktop     | [b475aa2ead](https://bsd-hardware.info/?probe=b475aa2ead) | Oct 21, 2020 |
| Intel         | D2500HN                     | Desktop     | [6dbc4dfa33](https://bsd-hardware.info/?probe=6dbc4dfa33) | Oct 21, 2020 |
| Intel         | CRESCENTBAY                 | Desktop     | [42d114559b](https://bsd-hardware.info/?probe=42d114559b) | Oct 21, 2020 |
| PC Engines    | apu2                        | Desktop     | [d1ca549fe7](https://bsd-hardware.info/?probe=d1ca549fe7) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325AJ9       | Notebook    | [176044b6b8](https://bsd-hardware.info/?probe=176044b6b8) | Oct 21, 2020 |
| Lenovo        | ThinkPad S5-S540 20B3001... | Notebook    | [7e6cb69989](https://bsd-hardware.info/?probe=7e6cb69989) | Oct 21, 2020 |
| Dell          | Latitude C400               | Notebook    | [1dcc5e7972](https://bsd-hardware.info/?probe=1dcc5e7972) | Oct 21, 2020 |
| Dell          | Latitude C400               | Notebook    | [8330d23bd7](https://bsd-hardware.info/?probe=8330d23bd7) | Oct 21, 2020 |
| ZOTAC         | XXXXXX                      | Desktop     | [0f8960bdd3](https://bsd-hardware.info/?probe=0f8960bdd3) | Oct 21, 2020 |
| Lenovo        | ThinkPad X60s 17033JM       | Notebook    | [67e701adb7](https://bsd-hardware.info/?probe=67e701adb7) | Oct 21, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [1b1327ac93](https://bsd-hardware.info/?probe=1b1327ac93) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [11b0b7012f](https://bsd-hardware.info/?probe=11b0b7012f) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [a92c08a920](https://bsd-hardware.info/?probe=a92c08a920) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [80d5f15a63](https://bsd-hardware.info/?probe=80d5f15a63) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325R74       | Notebook    | [82398321f6](https://bsd-hardware.info/?probe=82398321f6) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325R74       | Notebook    | [1cc3cc20e8](https://bsd-hardware.info/?probe=1cc3cc20e8) | Oct 21, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [2cb76e5886](https://bsd-hardware.info/?probe=2cb76e5886) | Oct 21, 2020 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [f287de215c](https://bsd-hardware.info/?probe=f287de215c) | Oct 20, 2020 |
| PC Engines    | apu2                        | Desktop     | [e6ee8a14d5](https://bsd-hardware.info/?probe=e6ee8a14d5) | Oct 20, 2020 |
| ASUSTek       | Z170-K                      | Desktop     | [19cb3ccc34](https://bsd-hardware.info/?probe=19cb3ccc34) | Oct 20, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | Notebook    | [b2e65dd4c5](https://bsd-hardware.info/?probe=b2e65dd4c5) | Oct 20, 2020 |
| Intel         | S3000AH                     | Desktop     | [f5b858601a](https://bsd-hardware.info/?probe=f5b858601a) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [e6b45d36e5](https://bsd-hardware.info/?probe=e6b45d36e5) | Oct 20, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [901c82d31e](https://bsd-hardware.info/?probe=901c82d31e) | Oct 20, 2020 |
| Intel         | D2500HN                     | Desktop     | [4b432dcb3d](https://bsd-hardware.info/?probe=4b432dcb3d) | Oct 20, 2020 |
| PC Engines    | APU2                        | Desktop     | [b95ef9962d](https://bsd-hardware.info/?probe=b95ef9962d) | Oct 20, 2020 |
| PC Engines    | APU2                        | Desktop     | [aecf376503](https://bsd-hardware.info/?probe=aecf376503) | Oct 20, 2020 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [2808d1dd6a](https://bsd-hardware.info/?probe=2808d1dd6a) | Oct 20, 2020 |
| Unknown       | Unknown                     | Desktop     | [bedb4a4b37](https://bsd-hardware.info/?probe=bedb4a4b37) | Oct 20, 2020 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [f846609c80](https://bsd-hardware.info/?probe=f846609c80) | Oct 20, 2020 |
| Unknown       | Unknown                     | Desktop     | [a28ef1d2b8](https://bsd-hardware.info/?probe=a28ef1d2b8) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AL00DKRT    | Notebook    | [623801416c](https://bsd-hardware.info/?probe=623801416c) | Oct 20, 2020 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [feb1da0406](https://bsd-hardware.info/?probe=feb1da0406) | Oct 20, 2020 |
| PC Engines    | apu1                        | Desktop     | [c77b06b3eb](https://bsd-hardware.info/?probe=c77b06b3eb) | Oct 20, 2020 |
| Intel         | NUC5i3RYB                   | Mini pc     | [3d03473ea9](https://bsd-hardware.info/?probe=3d03473ea9) | Oct 20, 2020 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [efece2abf7](https://bsd-hardware.info/?probe=efece2abf7) | Oct 20, 2020 |
| Apple         | Macmini7,1                  | Mini pc     | [5caa1e1c7b](https://bsd-hardware.info/?probe=5caa1e1c7b) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [7671a495d1](https://bsd-hardware.info/?probe=7671a495d1) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [c1a2bc7a51](https://bsd-hardware.info/?probe=c1a2bc7a51) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [c1c5ee566c](https://bsd-hardware.info/?probe=c1c5ee566c) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [af87ddbbaa](https://bsd-hardware.info/?probe=af87ddbbaa) | Oct 19, 2020 |
| ASUSTek       | P10S-I Series               | Desktop     | [1a0e9f0100](https://bsd-hardware.info/?probe=1a0e9f0100) | Oct 19, 2020 |
| ASUSTek       | K53SV                       | Notebook    | [e776458c9e](https://bsd-hardware.info/?probe=e776458c9e) | Oct 19, 2020 |
| Lenovo        | ThinkPad T560 20FJS0CE00    | Notebook    | [be16cb1839](https://bsd-hardware.info/?probe=be16cb1839) | Oct 19, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | Notebook    | [fdc7310ca7](https://bsd-hardware.info/?probe=fdc7310ca7) | Oct 19, 2020 |
| Unknown       | Unknown                     | Desktop     | [a3db8641e6](https://bsd-hardware.info/?probe=a3db8641e6) | Oct 19, 2020 |
| ASUSTek       | 1000HE                      | Notebook    | [621df26e0c](https://bsd-hardware.info/?probe=621df26e0c) | Oct 19, 2020 |
| PC Engines    | apu4                        | Desktop     | [e4cd6d0b48](https://bsd-hardware.info/?probe=e4cd6d0b48) | Oct 19, 2020 |
| PC Engines    | APU                         | Desktop     | [0cf4f6a5f9](https://bsd-hardware.info/?probe=0cf4f6a5f9) | Oct 19, 2020 |
| Lenovo        | SHARKBAY WIN                | Desktop     | [53feb1fec6](https://bsd-hardware.info/?probe=53feb1fec6) | Oct 19, 2020 |
| ASRock        | IMB-191                     | Desktop     | [4ac9e9cf2a](https://bsd-hardware.info/?probe=4ac9e9cf2a) | Oct 19, 2020 |
| PC Engines    | apu2                        | Desktop     | [064e7167a0](https://bsd-hardware.info/?probe=064e7167a0) | Oct 19, 2020 |
| Dell          | OptiPlex 3060               | Desktop     | [13992dbb10](https://bsd-hardware.info/?probe=13992dbb10) | Oct 19, 2020 |
| PC Engines    | apu2                        | Desktop     | [a5b1c3a559](https://bsd-hardware.info/?probe=a5b1c3a559) | Oct 19, 2020 |
| Acer          | Aspire 5251                 | Notebook    | [da9ebcf25e](https://bsd-hardware.info/?probe=da9ebcf25e) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [857f9809b7](https://bsd-hardware.info/?probe=857f9809b7) | Oct 19, 2020 |
| Dell          | PowerEdge T320              | Desktop     | [75c395f941](https://bsd-hardware.info/?probe=75c395f941) | Oct 19, 2020 |
| Dell          | PowerEdge 1950              | Desktop     | [3cfcdfce6d](https://bsd-hardware.info/?probe=3cfcdfce6d) | Oct 19, 2020 |
| Dell          | PowerEdge 1950              | Desktop     | [0865193e7e](https://bsd-hardware.info/?probe=0865193e7e) | Oct 19, 2020 |
| Dell          | PowerEdge R610              | Desktop     | [2ea539bbd3](https://bsd-hardware.info/?probe=2ea539bbd3) | Oct 19, 2020 |
| Dell          | OptiPlex 7020               | Desktop     | [293e6af35e](https://bsd-hardware.info/?probe=293e6af35e) | Oct 19, 2020 |
| Lenovo        | ThinkPad X270 20HNA004CD    | Notebook    | [79160b17c4](https://bsd-hardware.info/?probe=79160b17c4) | Oct 19, 2020 |
| PC Engines    | apu2                        | Desktop     | [2ab3051cb8](https://bsd-hardware.info/?probe=2ab3051cb8) | Oct 19, 2020 |
| PC Engines    | apu4                        | Desktop     | [f0116986e0](https://bsd-hardware.info/?probe=f0116986e0) | Oct 19, 2020 |
| IBM           | Board                       | Desktop     | [af2f64a7a8](https://bsd-hardware.info/?probe=af2f64a7a8) | Oct 19, 2020 |
| ASUSTek       | X102BA                      | Notebook    | [47e04c9378](https://bsd-hardware.info/?probe=47e04c9378) | Oct 19, 2020 |
| Lenovo        | G50-80 80E5                 | Notebook    | [e06605a92b](https://bsd-hardware.info/?probe=e06605a92b) | Oct 19, 2020 |
| Panasonic     | CF-C1BT02EGE                | Notebook    | [8a80fb614e](https://bsd-hardware.info/?probe=8a80fb614e) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [bee732e516](https://bsd-hardware.info/?probe=bee732e516) | Oct 19, 2020 |
| Apple         | PowerBook6,7                | Notebook    | [7ac5f5530a](https://bsd-hardware.info/?probe=7ac5f5530a) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | Desktop     | [dc7b96e637](https://bsd-hardware.info/?probe=dc7b96e637) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | Desktop     | [0184fcedcf](https://bsd-hardware.info/?probe=0184fcedcf) | Oct 19, 2020 |
| Alienware     | m15                         | Notebook    | [8f8cf7d956](https://bsd-hardware.info/?probe=8f8cf7d956) | Oct 19, 2020 |
| Lenovo        | ThinkPad T480 20L6S4GR02    | Notebook    | [6c2d8a57ea](https://bsd-hardware.info/?probe=6c2d8a57ea) | Oct 19, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b33e2a5177](https://bsd-hardware.info/?probe=b33e2a5177) | Oct 19, 2020 |
| PC Engines    | apu1                        | Desktop     | [576f4db9e1](https://bsd-hardware.info/?probe=576f4db9e1) | Oct 19, 2020 |
| PC Engines    | apu2                        | Desktop     | [e4030e5ee2](https://bsd-hardware.info/?probe=e4030e5ee2) | Oct 19, 2020 |
| PC Engines    | apu2                        | Desktop     | [ca0480a30d](https://bsd-hardware.info/?probe=ca0480a30d) | Oct 19, 2020 |
| Bluechip C... | bluechip BUSINESSline Wo... | Desktop     | [6dc86d6a5b](https://bsd-hardware.info/?probe=6dc86d6a5b) | Oct 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [fd77b4658f](https://bsd-hardware.info/?probe=fd77b4658f) | Oct 19, 2020 |
| Apple         | MacBookAir6,2               | Notebook    | [9f80fdafb0](https://bsd-hardware.info/?probe=9f80fdafb0) | Oct 19, 2020 |
| Unknown       | Unknown                     | Desktop     | [e36fc2b2b2](https://bsd-hardware.info/?probe=e36fc2b2b2) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | Notebook    | [017b41dfd7](https://bsd-hardware.info/?probe=017b41dfd7) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [4f54c8f399](https://bsd-hardware.info/?probe=4f54c8f399) | Oct 19, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [027fbd78f5](https://bsd-hardware.info/?probe=027fbd78f5) | Oct 19, 2020 |
| HP            | OmniBook PC                 | Notebook    | [0e0656d228](https://bsd-hardware.info/?probe=0e0656d228) | Oct 19, 2020 |
| HP            | OmniBook PC                 | Notebook    | [60e72f1c10](https://bsd-hardware.info/?probe=60e72f1c10) | Oct 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS1BC01    | Notebook    | [bf6d6d155b](https://bsd-hardware.info/?probe=bf6d6d155b) | Oct 19, 2020 |
| Lenovo        | 3000 N100 0768B9G           | Notebook    | [c44a86f589](https://bsd-hardware.info/?probe=c44a86f589) | Oct 19, 2020 |
| ASRock        | A75M-ITX                    | Desktop     | [dff827c2ae](https://bsd-hardware.info/?probe=dff827c2ae) | Oct 19, 2020 |
| PC Engines    | apu1                        | Desktop     | [8aade944d5](https://bsd-hardware.info/?probe=8aade944d5) | Oct 19, 2020 |
| ASUSTek       | G551JW                      | Notebook    | [594e6f28fb](https://bsd-hardware.info/?probe=594e6f28fb) | Oct 19, 2020 |
| PC Engines    | apu4                        | Desktop     | [ee8a1317f9](https://bsd-hardware.info/?probe=ee8a1317f9) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [ee1f866775](https://bsd-hardware.info/?probe=ee1f866775) | Oct 13, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | Notebook    | [fbf90aaf0d](https://bsd-hardware.info/?probe=fbf90aaf0d) | Sep 11, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | Notebook    | [e06815d9dc](https://bsd-hardware.info/?probe=e06815d9dc) | Sep 11, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | Notebook    | [1f28f1c311](https://bsd-hardware.info/?probe=1f28f1c311) | Aug 30, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | Notebook    | [11a0bbb73f](https://bsd-hardware.info/?probe=11a0bbb73f) | Aug 30, 2020 |
| Protectli     | FW6                         | Desktop     | [1454991c98](https://bsd-hardware.info/?probe=1454991c98) | Aug 27, 2020 |
| PC Engines    | apu4                        | Desktop     | [8f4ed98a45](https://bsd-hardware.info/?probe=8f4ed98a45) | Aug 21, 2020 |
| Lenovo        | ThinkPad P40 Yoga 20GQ00... | Notebook    | [ac92b69122](https://bsd-hardware.info/?probe=ac92b69122) | Aug 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [3032cd9409](https://bsd-hardware.info/?probe=3032cd9409) | Aug 20, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [547b36ea62](https://bsd-hardware.info/?probe=547b36ea62) | Aug 19, 2020 |
| HCL Infosy... | Calistoga & ICH7M Chipse... | Notebook    | [6adc98922d](https://bsd-hardware.info/?probe=6adc98922d) | Aug 19, 2020 |
| Gigabyte      | X58A-UD5                    | Desktop     | [63a429ad0e](https://bsd-hardware.info/?probe=63a429ad0e) | Aug 16, 2020 |
| Dell          | OptiPlex 745                | Desktop     | [6de04c2c9c](https://bsd-hardware.info/?probe=6de04c2c9c) | Aug 14, 2020 |
| IBM           | ThinkPad T42 2373K9G        | Notebook    | [fa35e7ec26](https://bsd-hardware.info/?probe=fa35e7ec26) | Aug 11, 2020 |
| PC Engines    | apu4                        | Desktop     | [f0f8a22656](https://bsd-hardware.info/?probe=f0f8a22656) | Aug 05, 2020 |
| Intel         | ChiefRiver                  | Desktop     | [022d2761b9](https://bsd-hardware.info/?probe=022d2761b9) | Aug 03, 2020 |
| PC Engines    | apu3                        | Desktop     | [1eaf8a1484](https://bsd-hardware.info/?probe=1eaf8a1484) | Aug 03, 2020 |
| PC Engines    | APU3                        | Desktop     | [4980462667](https://bsd-hardware.info/?probe=4980462667) | Aug 03, 2020 |
| PC Engines    | APU3                        | Desktop     | [975e23e09d](https://bsd-hardware.info/?probe=975e23e09d) | Aug 03, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [a8953b4964](https://bsd-hardware.info/?probe=a8953b4964) | Aug 03, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [a97053c5d4](https://bsd-hardware.info/?probe=a97053c5d4) | Aug 03, 2020 |
| Shuttle       | DS437                       | Desktop     | [aa350b6b92](https://bsd-hardware.info/?probe=aa350b6b92) | Aug 03, 2020 |
| PC Engines    | apu2                        | Desktop     | [fe5c2f4838](https://bsd-hardware.info/?probe=fe5c2f4838) | Aug 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [20f3e760eb](https://bsd-hardware.info/?probe=20f3e760eb) | Aug 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [b305c0df5e](https://bsd-hardware.info/?probe=b305c0df5e) | Aug 03, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [f3e2acbb66](https://bsd-hardware.info/?probe=f3e2acbb66) | Jul 31, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [7ae8c247e9](https://bsd-hardware.info/?probe=7ae8c247e9) | Jul 31, 2020 |
| Lenovo        | ThinkPad T60 87445BU        | Notebook    | [37a42caa92](https://bsd-hardware.info/?probe=37a42caa92) | Jul 30, 2020 |
| Lenovo        | ThinkCentre M92p 3212AD2    | Desktop     | [ca76cc5467](https://bsd-hardware.info/?probe=ca76cc5467) | Jul 30, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [ac13b0591f](https://bsd-hardware.info/?probe=ac13b0591f) | Jul 27, 2020 |
| ASRock        | E350M1                      | Desktop     | [08eec78cdf](https://bsd-hardware.info/?probe=08eec78cdf) | Jul 25, 2020 |
| Pegatron      | 2A73                        | Desktop     | [05dea28605](https://bsd-hardware.info/?probe=05dea28605) | Jul 21, 2020 |
| PC Engines    | apu4                        | Desktop     | [52c611855b](https://bsd-hardware.info/?probe=52c611855b) | Jul 12, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [c1f2cdf7a8](https://bsd-hardware.info/?probe=c1f2cdf7a8) | Jul 03, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [b79f3127ee](https://bsd-hardware.info/?probe=b79f3127ee) | Jul 03, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [dfef5fdcbf](https://bsd-hardware.info/?probe=dfef5fdcbf) | Jun 10, 2020 |
| ASUSTek       | All Series                  | Desktop     | [e4f1a19012](https://bsd-hardware.info/?probe=e4f1a19012) | Jun 05, 2020 |
| Toshiba       | Satellite L775D             | Notebook    | [bb218a14a6](https://bsd-hardware.info/?probe=bb218a14a6) | Jun 03, 2020 |
| Toshiba       | Satellite L775D             | Notebook    | [f0ec90217a](https://bsd-hardware.info/?probe=f0ec90217a) | Jun 03, 2020 |
| Unknown       | Unknown                     | Desktop     | [4e3b87cc6c](https://bsd-hardware.info/?probe=4e3b87cc6c) | Jun 01, 2020 |
| Lenovo        | ThinkPad X220 4291C35       | Notebook    | [f22c83f68b](https://bsd-hardware.info/?probe=f22c83f68b) | May 31, 2020 |
| Panasonic     | CF-19ADUAX1M                | Notebook    | [cefc742c62](https://bsd-hardware.info/?probe=cefc742c62) | May 29, 2020 |
| Sony UK       | Raspberry Pi 4 Model B      | Desktop     | [483af3998c](https://bsd-hardware.info/?probe=483af3998c) | May 28, 2020 |
| Unknown       | Unknown                     | Desktop     | [80a1eda96f](https://bsd-hardware.info/?probe=80a1eda96f) | May 28, 2020 |
| Dell          | PowerEdge T320              | Desktop     | [eec750b5c5](https://bsd-hardware.info/?probe=eec750b5c5) | May 28, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [08534174df](https://bsd-hardware.info/?probe=08534174df) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [8e0f831fd8](https://bsd-hardware.info/?probe=8e0f831fd8) | May 27, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [03ea0992c4](https://bsd-hardware.info/?probe=03ea0992c4) | May 27, 2020 |
| IBM           | Board                       | Desktop     | [1bcc2b8e0b](https://bsd-hardware.info/?probe=1bcc2b8e0b) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [74b9526162](https://bsd-hardware.info/?probe=74b9526162) | May 27, 2020 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [b02640458b](https://bsd-hardware.info/?probe=b02640458b) | May 26, 2020 |
| Lenovo        | ThinkPad X230 2324A57       | Notebook    | [6ea713bf51](https://bsd-hardware.info/?probe=6ea713bf51) | May 25, 2020 |
| Lenovo        | ThinkPad X230 2324A57       | Notebook    | [7b67911c5a](https://bsd-hardware.info/?probe=7b67911c5a) | May 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b4ca8bbc46](https://bsd-hardware.info/?probe=b4ca8bbc46) | May 25, 2020 |
| Gigabyte      | Unknown                     | Desktop     | [576771182b](https://bsd-hardware.info/?probe=576771182b) | May 25, 2020 |
| Gigabyte      | Unknown                     | Desktop     | [05e8154b2c](https://bsd-hardware.info/?probe=05e8154b2c) | May 25, 2020 |
| Lenovo        | ThinkPad T420 4180B39       | Notebook    | [916596bfa8](https://bsd-hardware.info/?probe=916596bfa8) | May 25, 2020 |
| IBM           | ThinkPad X41 2525FAG        | Notebook    | [1e849f86cf](https://bsd-hardware.info/?probe=1e849f86cf) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | Desktop     | [8b9481baf2](https://bsd-hardware.info/?probe=8b9481baf2) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | Desktop     | [33c4579f99](https://bsd-hardware.info/?probe=33c4579f99) | May 25, 2020 |
| Lenovo        | ThinkPad T440 20B7S1C600    | Notebook    | [a4a62cb85e](https://bsd-hardware.info/?probe=a4a62cb85e) | May 24, 2020 |
| Lenovo        | ThinkPad T440s 20AR003VM... | Notebook    | [3f72b76851](https://bsd-hardware.info/?probe=3f72b76851) | May 23, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [fa71e5839a](https://bsd-hardware.info/?probe=fa71e5839a) | May 23, 2020 |
| Lenovo        | ThinkPad X260 20F5S1H800    | Notebook    | [85567202a8](https://bsd-hardware.info/?probe=85567202a8) | May 23, 2020 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | Notebook    | [9ff1537692](https://bsd-hardware.info/?probe=9ff1537692) | May 23, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [8212868b9f](https://bsd-hardware.info/?probe=8212868b9f) | May 19, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [bdd93164cf](https://bsd-hardware.info/?probe=bdd93164cf) | May 17, 2020 |
| ASUSTek       | A3L                         | Notebook    | [0c73038abc](https://bsd-hardware.info/?probe=0c73038abc) | May 06, 2020 |
| ASUSTek       | A3L                         | Notebook    | [ff5b6e3024](https://bsd-hardware.info/?probe=ff5b6e3024) | May 06, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OpenBSD 6.8 | 208       | 42.98%  |
| OpenBSD 6.9 | 89        | 18.39%  |
| OpenBSD 7.0 | 84        | 17.36%  |
| OpenBSD 7.1 | 50        | 10.33%  |
| OpenBSD 6.7 | 50        | 10.33%  |
| OpenBSD 6.6 | 3         | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| OpenBSD | 422       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 359       | 85.07%  |
| i386    | 37        | 8.77%   |
| arm64   | 15        | 3.55%   |
| macppc  | 5         | 1.18%   |
| sparc64 | 2         | 0.47%   |
| octeon  | 2         | 0.47%   |
| armv7   | 2         | 0.47%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| fvwm          | 272       | 61.4%   |
| Console       | 115       | 25.96%  |
| helloDesktop  | 39        | 8.8%    |
| XFCE          | 8         | 1.81%   |
| Mutter        | 2         | 0.45%   |
| i3            | 2         | 0.45%   |
| Openbox       | 1         | 0.23%   |
| MATE          | 1         | 0.23%   |
| iwm           | 1         | 0.23%   |
| GNOME         | 1         | 0.23%   |
| Enlightenment | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 284       | 66.82%  |
| Console | 141       | 33.18%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 377       | 87.88%  |
| SLiM    | 30        | 6.99%   |
| GDM     | 22        | 5.13%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 333       | 77.62%  |
| en_US   | 39        | 9.09%   |
| ru_RU   | 22        | 5.13%   |
| C       | 10        | 2.33%   |
| fr_FR   | 5         | 1.17%   |
| en_GB   | 5         | 1.17%   |
| de_DE   | 4         | 0.93%   |
| es_CO   | 2         | 0.47%   |
| en_AU   | 2         | 0.47%   |
| zh_CN   | 1         | 0.23%   |
| pl_PL   | 1         | 0.23%   |
| ja_JP   | 1         | 0.23%   |
| fr_CA   | 1         | 0.23%   |
| es_ES   | 1         | 0.23%   |
| en_EN   | 1         | 0.23%   |
| en_CA   | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 226       | 52.8%   |
| EFI  | 202       | 47.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 422       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 246       | 57.61%  |
| GPT     | 177       | 41.45%  |
| Unknown | 4         | 0.94%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 110       | 26.07%  |
| PC Engines                     | 32        | 7.58%   |
| ASUSTek Computer               | 32        | 7.58%   |
| Dell                           | 30        | 7.11%   |
| Hewlett-Packard                | 29        | 6.87%   |
| Unknown                        | 24        | 5.69%   |
| Gigabyte Technology            | 18        | 4.27%   |
| Apple                          | 17        | 4.03%   |
| MSI                            | 15        | 3.55%   |
| Intel                          | 13        | 3.08%   |
| ASRock                         | 13        | 3.08%   |
| Acer                           | 10        | 2.37%   |
| Supermicro                     | 9         | 2.13%   |
| IBM                            | 8         | 1.9%    |
| Panasonic                      | 5         | 1.18%   |
| Sony                           | 4         | 0.95%   |
| Samsung Electronics            | 4         | 0.95%   |
| Raspberry Pi Foundation        | 4         | 0.95%   |
| Microsoft                      | 3         | 0.71%   |
| Fujitsu                        | 3         | 0.71%   |
| TUXEDO                         | 2         | 0.47%   |
| Sun                            | 2         | 0.47%   |
| Soekris Engineering            | 2         | 0.47%   |
| Shuttle                        | 2         | 0.47%   |
| Pegatron                       | 2         | 0.47%   |
| Matsushita Electric Industrial | 2         | 0.47%   |
| Alienware                      | 2         | 0.47%   |
| ZOTAC                          | 1         | 0.24%   |
| Yanling                        | 1         | 0.24%   |
| WYSE                           | 1         | 0.24%   |
| Unknown                        | 1         | 0.24%   |
| Toshiba                        | 1         | 0.24%   |
| Standard                       | 1         | 0.24%   |
| Sony UK                        | 1         | 0.24%   |
| Protectli                      | 1         | 0.24%   |
| NF541                          | 1         | 0.24%   |
| KOHJINSHA                      | 1         | 0.24%   |
| HCL Infosystems Limited        | 1         | 0.24%   |
| HARDKERNEL                     | 1         | 0.24%   |
| Google                         | 1         | 0.24%   |
| Framework                      | 1         | 0.24%   |
| Foxconn                        | 1         | 0.24%   |
| eMachines                      | 1         | 0.24%   |
| ECT                            | 1         | 0.24%   |
| ECS                            | 1         | 0.24%   |
| DEXP                           | 1         | 0.24%   |
| Clevo                          | 1         | 0.24%   |
| Casper                         | 1         | 0.24%   |
| Bluechip Computer              | 1         | 0.24%   |
| Biostar                        | 1         | 0.24%   |
| AZW                            | 1         | 0.24%   |
| AMI                            | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 29        | 6.87%   |
| PC Engines apu2                             | 14        | 3.32%   |
| PC Engines apu4                             | 9         | 2.13%   |
| Lenovo ThinkPad X200 745969G                | 6         | 1.42%   |
| PC Engines apu1                             | 5         | 1.18%   |
| Dell PowerEdge R620                         | 4         | 0.95%   |
| PC Engines apu3                             | 3         | 0.71%   |
| ASUS All Series                             | 3         | 0.71%   |
| Supermicro Super Server                     | 2         | 0.47%   |
| RPi Raspberry Pi 400                        | 2         | 0.47%   |
| RPi Raspberry Pi 4 Model B                  | 2         | 0.47%   |
| MSI MS-7A34                                 | 2         | 0.47%   |
| Microsoft Surface Pro 7                     | 2         | 0.47%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW    | 2         | 0.47%   |
| HP ZBook 15 G4                              | 2         | 0.47%   |
| Gigabyte M68MT-S2P                          | 2         | 0.47%   |
| ASUS X102BA                                 | 2         | 0.47%   |
| ASUS PRIME X370-PRO                         | 2         | 0.47%   |
| Apple PowerMac10,1                          | 2         | 0.47%   |
| Apple MacBookAir6,2                         | 2         | 0.47%   |
| Apple MacBook5,1                            | 2         | 0.47%   |
| ZOTAC XXXXXX                                | 1         | 0.24%   |
| Yanling YL-KBR6L                            | 1         | 0.24%   |
| WYSE D CLASS                                | 1         | 0.24%   |
| TUXEDO Pulse 15 Gen1                        | 1         | 0.24%   |
| TUXEDO Aura 15 Gen1                         | 1         | 0.24%   |
| Toshiba Satellite L775D                     | 1         | 0.24%   |
| Supermicro X8STi                            | 1         | 0.24%   |
| Supermicro X8DTH-i/6/iF/6F                  | 1         | 0.24%   |
| Supermicro X7SBL                            | 1         | 0.24%   |
| Supermicro X11SSW-F                         | 1         | 0.24%   |
| Supermicro X11SCE-F                         | 1         | 0.24%   |
| Supermicro X11DDW-L                         | 1         | 0.24%   |
| Supermicro X10SLH-N6-ST031                  | 1         | 0.24%   |
| Sun SUNW,Sun-Blade-1500                     | 1         | 0.24%   |
| Sun SUNW,Sun-Blade-100                      | 1         | 0.24%   |
| Standard TF                                 | 1         | 0.24%   |
| Sony VPCX115KX                              | 1         | 0.24%   |
| Sony VPCL22Z1R                              | 1         | 0.24%   |
| Sony VPCF12C5E                              | 1         | 0.24%   |
| Sony VGN-P698E                              | 1         | 0.24%   |
| Sony UK Raspberry Pi 4 Model B              | 1         | 0.24%   |
| Soekris Engineering net6501                 | 1         | 0.24%   |
| Soekris Engineering net5501                 | 1         | 0.24%   |
| Shuttle DS77U                               | 1         | 0.24%   |
| Shuttle DS437                               | 1         | 0.24%   |
| Samsung R720                                | 1         | 0.24%   |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 0.24%   |
| Samsung 530XBB                              | 1         | 0.24%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV    | 1         | 0.24%   |
| Protectli FW6                               | 1         | 0.24%   |
| Pegatron SKLD4-P1                           | 1         | 0.24%   |
| Pegatron Compaq dx2400 Microtower           | 1         | 0.24%   |
| PC Engines APU                              | 1         | 0.24%   |
| Panasonic CF-C1BT02EGE                      | 1         | 0.24%   |
| Panasonic CF-53AAGHYDM                      | 1         | 0.24%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 0.24%   |
| Panasonic CF-30KTP48NL                      | 1         | 0.24%   |
| Panasonic CF-19ADUAX1M                      | 1         | 0.24%   |
| MSI MS-B09012                               | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 92        | 21.8%   |
| Unknown                     | 29        | 6.87%   |
| PC Engines apu2             | 14        | 3.32%   |
| PC Engines apu4             | 9         | 2.13%   |
| Dell PowerEdge              | 8         | 1.9%    |
| ASUS PRIME                  | 8         | 1.9%    |
| PC Engines apu1             | 5         | 1.18%   |
| Lenovo ThinkCentre          | 5         | 1.18%   |
| IBM ThinkPad                | 5         | 1.18%   |
| Dell OptiPlex               | 5         | 1.18%   |
| RPi Raspberry               | 4         | 0.95%   |
| Lenovo IdeaPad              | 4         | 0.95%   |
| HP ProLiant                 | 4         | 0.95%   |
| Dell Latitude               | 4         | 0.95%   |
| PC Engines apu3             | 3         | 0.71%   |
| Microsoft Surface           | 3         | 0.71%   |
| Lenovo Yoga                 | 3         | 0.71%   |
| HP Pavilion                 | 3         | 0.71%   |
| HP Compaq                   | 3         | 0.71%   |
| Fujitsu LIFEBOOK            | 3         | 0.71%   |
| Dell XPS                    | 3         | 0.71%   |
| Dell Precision              | 3         | 0.71%   |
| Dell Inspiron               | 3         | 0.71%   |
| ASUS VivoBook               | 3         | 0.71%   |
| ASUS All                    | 3         | 0.71%   |
| Acer Aspire                 | 3         | 0.71%   |
| Supermicro Super            | 2         | 0.47%   |
| Sun SUNW                    | 2         | 0.47%   |
| MSI MS-7A34                 | 2         | 0.47%   |
| Lenovo Flex                 | 2         | 0.47%   |
| HP ZBook                    | 2         | 0.47%   |
| Gigabyte M68MT-S2P          | 2         | 0.47%   |
| Dell Vostro                 | 2         | 0.47%   |
| ASUS X102BA                 | 2         | 0.47%   |
| ASUS ROG                    | 2         | 0.47%   |
| Apple PowerMac10            | 2         | 0.47%   |
| Apple PowerBook5            | 2         | 0.47%   |
| Apple MacBookAir6           | 2         | 0.47%   |
| Apple MacBook5              | 2         | 0.47%   |
| Acer Extensa                | 2         | 0.47%   |
| ZOTAC XXXXXX                | 1         | 0.24%   |
| Yanling YL-KBR6L            | 1         | 0.24%   |
| WYSE D                      | 1         | 0.24%   |
| TUXEDO Pulse                | 1         | 0.24%   |
| TUXEDO Aura                 | 1         | 0.24%   |
| Toshiba Satellite           | 1         | 0.24%   |
| Supermicro X8STi            | 1         | 0.24%   |
| Supermicro X8DTH-i          | 1         | 0.24%   |
| Supermicro X7SBL            | 1         | 0.24%   |
| Supermicro X11SSW-F         | 1         | 0.24%   |
| Supermicro X11SCE-F         | 1         | 0.24%   |
| Supermicro X11DDW-L         | 1         | 0.24%   |
| Supermicro X10SLH-N6-ST031  | 1         | 0.24%   |
| Standard TF                 | 1         | 0.24%   |
| Sony VPCX115KX              | 1         | 0.24%   |
| Sony VPCL22Z1R              | 1         | 0.24%   |
| Sony VPCF12C5E              | 1         | 0.24%   |
| Sony VGN-P698E              | 1         | 0.24%   |
| Sony UK Raspberry           | 1         | 0.24%   |
| Soekris Engineering net6501 | 1         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 50        | 11.85%  |
| 2019    | 46        | 10.9%   |
| 2018    | 40        | 9.48%   |
| Unknown | 31        | 7.35%   |
| 2016    | 28        | 6.64%   |
| 2015    | 26        | 6.16%   |
| 2011    | 25        | 5.92%   |
| 2017    | 21        | 4.98%   |
| 2013    | 21        | 4.98%   |
| 2021    | 20        | 4.74%   |
| 2009    | 19        | 4.5%    |
| 2014    | 18        | 4.27%   |
| 2012    | 17        | 4.03%   |
| 2010    | 16        | 3.79%   |
| 2008    | 13        | 3.08%   |
| 2007    | 10        | 2.37%   |
| 2006    | 9         | 2.13%   |
| 2004    | 3         | 0.71%   |
| 2003    | 3         | 0.71%   |
| 2022    | 2         | 0.47%   |
| 2005    | 2         | 0.47%   |
| 2002    | 1         | 0.24%   |
| 2001    | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 205       | 48.58%  |
| Desktop     | 201       | 47.63%  |
| Mini pc     | 6         | 1.42%   |
| Tablet      | 3         | 0.71%   |
| All in one  | 3         | 0.71%   |
| Server      | 3         | 0.71%   |
| Convertible | 1         | 0.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 385       | 91.23%  |
| Yes  | 37        | 8.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 112       | 26.54%  |
| 4.01-8.0        | 93        | 22.04%  |
| 16.01-24.0      | 57        | 13.51%  |
| 3.01-4.0        | 41        | 9.72%   |
| 32.01-64.0      | 28        | 6.64%   |
| 2.01-3.0        | 27        | 6.4%    |
| 1.01-2.0        | 22        | 5.21%   |
| 0.51-1.0        | 16        | 3.79%   |
| 0.01-0.5        | 10        | 2.37%   |
| 64.01-256.0     | 8         | 1.9%    |
| 24.01-32.0      | 6         | 1.42%   |
| More than 256.0 | 2         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 340       | 80.38%  |
| 0          | 33        | 7.8%    |
| 0.51-1.0   | 31        | 7.33%   |
| 1.01-2.0   | 7         | 1.65%   |
| Unknown    | 6         | 1.42%   |
| 4.01-8.0   | 4         | 0.95%   |
| 16.01-24.0 | 1         | 0.24%   |
| 8.01-16.0  | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 224       | 51.38%  |
| 2      | 133       | 30.5%   |
| 3      | 41        | 9.4%    |
| 4      | 23        | 5.28%   |
| 0      | 5         | 1.15%   |
| 5      | 3         | 0.69%   |
| 10     | 2         | 0.46%   |
| 7      | 2         | 0.46%   |
| 6      | 2         | 0.46%   |
| 12     | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 421       | 99.53%  |
| Yes       | 2         | 0.47%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 369       | 87.44%  |
| No        | 53        | 12.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 257       | 60.76%  |
| No        | 166       | 39.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 270       | 63.68%  |
| Yes       | 154       | 36.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 81        | 19.06%  |
| Russia       | 57        | 13.41%  |
| Germany      | 56        | 13.18%  |
| France       | 26        | 6.12%   |
| Poland       | 19        | 4.47%   |
| Netherlands  | 18        | 4.24%   |
| UK           | 17        | 4%      |
| Canada       | 16        | 3.76%   |
| Sweden       | 15        | 3.53%   |
| Switzerland  | 12        | 2.82%   |
| Spain        | 9         | 2.12%   |
| Ukraine      | 8         | 1.88%   |
| Norway       | 8         | 1.88%   |
| Austria      | 7         | 1.65%   |
| Italy        | 6         | 1.41%   |
| Taiwan       | 5         | 1.18%   |
| Australia    | 5         | 1.18%   |
| Latvia       | 4         | 0.94%   |
| Czechia      | 4         | 0.94%   |
| Portugal     | 3         | 0.71%   |
| Japan        | 3         | 0.71%   |
| India        | 3         | 0.71%   |
| Finland      | 3         | 0.71%   |
| Croatia      | 3         | 0.71%   |
| Brazil       | 3         | 0.71%   |
| Turkey       | 2         | 0.47%   |
| Saudi Arabia | 2         | 0.47%   |
| Romania      | 2         | 0.47%   |
| Philippines  | 2         | 0.47%   |
| Malaysia     | 2         | 0.47%   |
| Indonesia    | 2         | 0.47%   |
| Denmark      | 2         | 0.47%   |
| Colombia     | 2         | 0.47%   |
| Bulgaria     | 2         | 0.47%   |
| Vietnam      | 1         | 0.24%   |
| UAE          | 1         | 0.24%   |
| Slovenia     | 1         | 0.24%   |
| New Zealand  | 1         | 0.24%   |
| Moldova      | 1         | 0.24%   |
| Jamaica      | 1         | 0.24%   |
| Hungary      | 1         | 0.24%   |
| Honduras     | 1         | 0.24%   |
| Estonia      | 1         | 0.24%   |
| Ecuador      | 1         | 0.24%   |
| Cyprus       | 1         | 0.24%   |
| Costa Rica   | 1         | 0.24%   |
| China        | 1         | 0.24%   |
| Chile        | 1         | 0.24%   |
| Belarus      | 1         | 0.24%   |
| Argentina    | 1         | 0.24%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 16        | 3.53%   |
| Berlin                  | 13        | 2.87%   |
| Vladivostok             | 11        | 2.43%   |
| Montreal                | 11        | 2.43%   |
| Amsterdam               | 10        | 2.21%   |
| Saint-Laurent           | 9         | 1.99%   |
| St Petersburg           | 8         | 1.77%   |
| Paris                   | 7         | 1.55%   |
| Gdansk                  | 7         | 1.55%   |
| Zurich                  | 6         | 1.32%   |
| Vienna                  | 5         | 1.1%    |
| QuГ©bec               | 5         | 1.1%    |
| New Taipei              | 5         | 1.1%    |
| Riga                    | 4         | 0.88%   |
| Poortugaal              | 4         | 0.88%   |
| Oslo                    | 4         | 0.88%   |
| Miedziana Gora          | 4         | 0.88%   |
| Malmo                   | 4         | 0.88%   |
| Ibiza Town              | 4         | 0.88%   |
| Gummersbach             | 4         | 0.88%   |
| Frankfurt am Main       | 4         | 0.88%   |
| Brooklyn                | 4         | 0.88%   |
| Yekaterinburg           | 3         | 0.66%   |
| Wittersham              | 3         | 0.66%   |
| Syeverodonets'k         | 3         | 0.66%   |
| Sydney                  | 3         | 0.66%   |
| Portland                | 3         | 0.66%   |
| Lausanne                | 3         | 0.66%   |
| Zhukovskiy              | 2         | 0.44%   |
| Wroclaw                 | 2         | 0.44%   |
| Wolfsburg               | 2         | 0.44%   |
| Svenstrup               | 2         | 0.44%   |
| Sofia                   | 2         | 0.44%   |
| Skien                   | 2         | 0.44%   |
| Saint-Martin-d'HГЁres | 2         | 0.44%   |
| Saint-Herblain          | 2         | 0.44%   |
| Prague                  | 2         | 0.44%   |
| Papillion               | 2         | 0.44%   |
| Orsk                    | 2         | 0.44%   |
| Onalaska                | 2         | 0.44%   |
| Oensingen               | 2         | 0.44%   |
| Nuremberg               | 2         | 0.44%   |
| Nantes                  | 2         | 0.44%   |
| Munich                  | 2         | 0.44%   |
| Milan                   | 2         | 0.44%   |
| Los Angeles             | 2         | 0.44%   |
| Leipzig                 | 2         | 0.44%   |
| Lebanon                 | 2         | 0.44%   |
| Kyiv                    | 2         | 0.44%   |
| Krakow                  | 2         | 0.44%   |
| Henan                   | 2         | 0.44%   |
| Harrisburg              | 2         | 0.44%   |
| Gettysburg              | 2         | 0.44%   |
| Fort Lauderdale         | 2         | 0.44%   |
| Erlangen                | 2         | 0.44%   |
| Erding                  | 2         | 0.44%   |
| Dublin                  | 2         | 0.44%   |
| Devizes                 | 2         | 0.44%   |
| Dallas                  | 2         | 0.44%   |
| Braunschweig            | 2         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| NVMe                               | 77        | 101    | 14.21%  |
| WDC                                | 68        | 99     | 12.55%  |
| Samsung Electronics                | 68        | 93     | 12.55%  |
| Seagate                            | 55        | 87     | 10.15%  |
| Kingston                           | 29        | 35     | 5.35%   |
| SanDisk                            | 23        | 28     | 4.24%   |
| Toshiba                            | 20        | 25     | 3.69%   |
| Crucial                            | 20        | 30     | 3.69%   |
| Hitachi                            | 18        | 24     | 3.32%   |
| Phison                             | 14        | 16     | 2.58%   |
| Intel                              | 14        | 18     | 2.58%   |
| OPENBSD                            | 11        | 15     | 2.03%   |
| HGST                               | 11        | 19     | 2.03%   |
| Transcend                          | 10        | 17     | 1.85%   |
| Apple                              | 7         | 7      | 1.29%   |
| Dell                               | 6         | 10     | 1.11%   |
| A-DATA Technology                  | 6         | 9      | 1.11%   |
| SK Hynix                           | 5         | 5      | 0.92%   |
| PNY                                | 5         | 5      | 0.92%   |
| USB                                | 4         | 4      | 0.74%   |
| Hewlett-Packard                    | 4         | 9      | 0.74%   |
| Innostor                           | 3         | 3      | 0.55%   |
| Generic                            | 3         | 3      | 0.55%   |
| StoreJet                           | 2         | 2      | 0.37%   |
| SPCC                               | 2         | 2      | 0.37%   |
| PLEXTOR                            | 2         | 2      | 0.37%   |
| Patriot                            | 2         | 2      | 0.37%   |
| OCZ                                | 2         | 2      | 0.37%   |
| Netac                              | 2         | 2      | 0.37%   |
| Multiple                           | 2         | 2      | 0.37%   |
| Micron Technology                  | 2         | 2      | 0.37%   |
| MAXTOR                             | 2         | 3      | 0.37%   |
| LSI                                | 2         | 4      | 0.37%   |
| LITEONIT                           | 2         | 2      | 0.37%   |
| Lexar                              | 2         | 2      | 0.37%   |
| KingSpec                           | 2         | 2      | 0.37%   |
| Hoodisk                            | 2         | 3      | 0.37%   |
| ASMT                               | 2         | 2      | 0.37%   |
| Apacer                             | 2         | 2      | 0.37%   |
| Zheino                             | 1         | 2      | 0.18%   |
| XPG                                | 1         | 1      | 0.18%   |
| UFD 2.0                            | 1         | 1      | 0.18%   |
| UDinfo                             | 1         | 1      | 0.18%   |
| Team                               | 1         | 1      | 0.18%   |
| SSDPR-CX                           | 1         | 1      | 0.18%   |
| SABRENT                            | 1         | 1      | 0.18%   |
| QUMO                               | 1         | 1      | 0.18%   |
| Product:              USB DISK 3.0 | 1         | 1      | 0.18%   |
| Product:              USB DISK 2.0 | 1         | 1      | 0.18%   |
| Product:                           | 1         | 1      | 0.18%   |
| OWC                                | 1         | 1      | 0.18%   |
| MidasForce                         | 1         | 1      | 0.18%   |
| MEMXPRO                            | 1         | 1      | 0.18%   |
| MaxDigital                         | 1         | 1      | 0.18%   |
| LITEON                             | 1         | 1      | 0.18%   |
| Leven                              | 1         | 1      | 0.18%   |
| LDLC F6+                           | 1         | 1      | 0.18%   |
| JetFlash                           | 1         | 1      | 0.18%   |
| IBM                                | 1         | 1      | 0.18%   |
| HPE                                | 1         | 2      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Phison SATA SSD 16GB                | 11        | 1.91%   |
| OPENBSD SR RAID 1 752GB             | 10        | 1.74%   |
| NVMe Samsung SSD 970 250GB          | 9         | 1.57%   |
| NVMe WDC PC SN730 SDB 256GB         | 8         | 1.39%   |
| Seagate ST1000LM035-1RK172 1TB      | 7         | 1.22%   |
| Samsung HM321HI 320GB               | 6         | 1.04%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 4         | 0.7%    |
| USB SanDisk 3.2Gen1 64GB            | 4         | 0.7%    |
| Samsung SSD 860 EVO mSATA 500GB     | 4         | 0.7%    |
| Samsung SSD 860 EVO 250GB           | 4         | 0.7%    |
| Samsung SSD 850 EVO 250GB           | 4         | 0.7%    |
| NVMe Samsung SSD 980 1TB            | 4         | 0.7%    |
| NVMe Samsung SSD 960 500GB          | 4         | 0.7%    |
| NVMe SAMSUNG MZVLB256 256GB         | 4         | 0.7%    |
| Kingston SUV500MS240G 240GB         | 4         | 0.7%    |
| Kingston SA400S37240G 240GB         | 4         | 0.7%    |
| Dell PERC H710 282GB                | 4         | 0.7%    |
| Crucial CT1000MX500SSD1 1TB         | 4         | 0.7%    |
| WDC WD6400AARS-00Y5B1 640GB         | 3         | 0.52%   |
| Toshiba MQ04ABF100 1TB              | 3         | 0.52%   |
| Seagate ST3250318AS 250GB           | 3         | 0.52%   |
| Seagate ST250DM000-1BD141 250GB     | 3         | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 0.52%   |
| SanDisk Ultra Fit 16GB              | 3         | 0.52%   |
| Samsung SSD 850 EVO 500GB           | 3         | 0.52%   |
| Samsung SSD 850 EVO 1TB             | 3         | 0.52%   |
| Samsung Flash Drive FIT 32GB        | 3         | 0.52%   |
| Innostor SSD 15GB                   | 3         | 0.52%   |
| HGST HUS724020ALA640 2TB            | 3         | 0.52%   |
| Crucial CT240BX500SSD1 240GB        | 3         | 0.52%   |
| Crucial CT120BX500SSD1 120GB        | 3         | 0.52%   |
| WDC WDS500G2B0A-00SM50 500GB        | 2         | 0.35%   |
| WDC WDS240G2G0B-00EPW0 240GB        | 2         | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 0.35%   |
| WDC WD10JPLX-00MBPT0 1TB            | 2         | 0.35%   |
| WDC WD10EADS-00M2B0 1TB             | 2         | 0.35%   |
| WDC WD Elements 25A1 4TB            | 2         | 0.35%   |
| Toshiba MK8025GAS 80GB              | 2         | 0.35%   |
| Toshiba MK2556GSY 250GB             | 2         | 0.35%   |
| StoreJet Transcend 120GB            | 2         | 0.35%   |
| SK Hynix SC311 SATA 256GB           | 2         | 0.35%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 0.35%   |
| Seagate ST3320418AS 320GB           | 2         | 0.35%   |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 0.35%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 0.35%   |
| SanDisk Ultra 32GB                  | 2         | 0.35%   |
| SanDisk SSD U110 16GB               | 2         | 0.35%   |
| SanDisk Cruzer Fit 32GB             | 2         | 0.35%   |
| SanDisk Cruzer Blade 32GB           | 2         | 0.35%   |
| Samsung SSD 860 EVO M.2 1TB         | 2         | 0.35%   |
| Samsung SSD 860 EVO 500GB           | 2         | 0.35%   |
| Samsung SSD 860 EVO 2TB             | 2         | 0.35%   |
| Samsung SSD 860 EVO 1TB             | 2         | 0.35%   |
| Samsung SSD 850 PRO 256GB           | 2         | 0.35%   |
| Samsung SSD 850 EVO M.2 250GB       | 2         | 0.35%   |
| Samsung SSD 850 EVO 120GB           | 2         | 0.35%   |
| Samsung SSD 840 Series 120GB        | 2         | 0.35%   |
| Samsung SSD 840 EVO 120GB           | 2         | 0.35%   |
| Samsung MZ7TD256HAFV-000L7 256GB    | 2         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 58        | 88     | 20.79%  |
| Seagate                            | 55        | 87     | 19.71%  |
| NVMe                               | 50        | 66     | 17.92%  |
| Hitachi                            | 18        | 24     | 6.45%   |
| Toshiba                            | 17        | 22     | 6.09%   |
| Samsung Electronics                | 15        | 21     | 5.38%   |
| OPENBSD                            | 11        | 15     | 3.94%   |
| HGST                               | 11        | 19     | 3.94%   |
| Dell                               | 6         | 10     | 2.15%   |
| USB                                | 4         | 4      | 1.43%   |
| Apple                              | 4         | 4      | 1.43%   |
| Generic                            | 3         | 3      | 1.08%   |
| StoreJet                           | 2         | 2      | 0.72%   |
| Multiple                           | 2         | 2      | 0.72%   |
| MAXTOR                             | 2         | 3      | 0.72%   |
| LSI                                | 2         | 4      | 0.72%   |
| Lexar                              | 2         | 2      | 0.72%   |
| Hewlett-Packard                    | 2         | 6      | 0.72%   |
| ASMT                               | 2         | 2      | 0.72%   |
| UFD 2.0                            | 1         | 1      | 0.36%   |
| SSDPR-CX                           | 1         | 1      | 0.36%   |
| SABRENT                            | 1         | 1      | 0.36%   |
| Product:              USB DISK 3.0 | 1         | 1      | 0.36%   |
| Product:              USB DISK 2.0 | 1         | 1      | 0.36%   |
| Product:                           | 1         | 1      | 0.36%   |
| MaxDigital                         | 1         | 1      | 0.36%   |
| LDLC F6+                           | 1         | 1      | 0.36%   |
| JetFlash                           | 1         | 1      | 0.36%   |
| IBM                                | 1         | 1      | 0.36%   |
| General                            | 1         | 1      | 0.36%   |
| Fujitsu                            | 1         | 1      | 0.36%   |
| China                              | 1         | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 54        | 72     | 20.69%  |
| Kingston            | 29        | 35     | 11.11%  |
| NVMe                | 24        | 27     | 9.2%    |
| SanDisk             | 23        | 28     | 8.81%   |
| Crucial             | 20        | 30     | 7.66%   |
| Phison              | 14        | 16     | 5.36%   |
| Intel               | 14        | 18     | 5.36%   |
| WDC                 | 10        | 11     | 3.83%   |
| Transcend           | 10        | 17     | 3.83%   |
| A-DATA Technology   | 6         | 9      | 2.3%    |
| SK Hynix            | 5         | 5      | 1.92%   |
| PNY                 | 5         | 5      | 1.92%   |
| Toshiba             | 3         | 3      | 1.15%   |
| Innostor            | 3         | 3      | 1.15%   |
| Apple               | 3         | 3      | 1.15%   |
| SPCC                | 2         | 2      | 0.77%   |
| PLEXTOR             | 2         | 2      | 0.77%   |
| Patriot             | 2         | 2      | 0.77%   |
| OCZ                 | 2         | 2      | 0.77%   |
| Netac               | 2         | 2      | 0.77%   |
| Micron Technology   | 2         | 2      | 0.77%   |
| LITEONIT            | 2         | 2      | 0.77%   |
| KingSpec            | 2         | 2      | 0.77%   |
| Hoodisk             | 2         | 3      | 0.77%   |
| Hewlett-Packard     | 2         | 3      | 0.77%   |
| Apacer              | 2         | 2      | 0.77%   |
| Zheino              | 1         | 2      | 0.38%   |
| XPG                 | 1         | 1      | 0.38%   |
| UDinfo              | 1         | 1      | 0.38%   |
| Team                | 1         | 1      | 0.38%   |
| QUMO                | 1         | 1      | 0.38%   |
| OWC                 | 1         | 1      | 0.38%   |
| MidasForce          | 1         | 1      | 0.38%   |
| MEMXPRO             | 1         | 1      | 0.38%   |
| LITEON              | 1         | 1      | 0.38%   |
| Leven               | 1         | 1      | 0.38%   |
| HPE                 | 1         | 2      | 0.38%   |
| GLOWAY              | 1         | 1      | 0.38%   |
| Gigabyte Technology | 1         | 1      | 0.38%   |
| Dogfish             | 1         | 1      | 0.38%   |
| CORSAIR             | 1         | 1      | 0.38%   |
| asmedia             | 1         | 1      | 0.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 228       | 324    | 49.46%  |
| HDD  | 226       | 397    | 49.02%  |
| NVMe | 7         | 8      | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 398       | 721    | 98.27%  |
| NVMe | 7         | 8      | 1.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 328       | 483    | 68.76%  |
| 0.51-1.0        | 102       | 144    | 21.38%  |
| 1.01-2.0        | 28        | 68     | 5.87%   |
| 3.01-4.0        | 8         | 10     | 1.68%   |
| 4.01-10.0       | 5         | 8      | 1.05%   |
| 2.01-3.0        | 3         | 5      | 0.63%   |
| More than 100.0 | 2         | 2      | 0.42%   |
| 0               | 1         | 1      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 145       | 33.49%  |
| 251-500        | 109       | 25.17%  |
| 51-100         | 56        | 12.93%  |
| 1-20           | 41        | 9.47%   |
| 21-50          | 37        | 8.55%   |
| 501-1000       | 20        | 4.62%   |
| 1001-2000      | 13        | 3%      |
| More than 3000 | 8         | 1.85%   |
| 2001-3000      | 4         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 301       | 69.35%  |
| 21-50          | 42        | 9.68%   |
| 101-250        | 38        | 8.76%   |
| 51-100         | 28        | 6.45%   |
| 251-500        | 9         | 2.07%   |
| 501-1000       | 8         | 1.84%   |
| 1001-2000      | 6         | 1.38%   |
| More than 3000 | 1         | 0.23%   |
| 2001-3000      | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB            | 2         | 2      | 3.85%   |
| Kingston SMS200S330G 32GB         | 2         | 3      | 3.85%   |
| Intel SSDSC2KF256H6L 256GB        | 2         | 2      | 3.85%   |
| HGST HTS541010A7E630 1TB          | 2         | 3      | 3.85%   |
| XPG SX950U 240GB                  | 1         | 1      | 1.92%   |
| WDC WD1600BEVT-22ZCT0 160GB       | 1         | 1      | 1.92%   |
| WDC WD1600BEVE-00UYT0 160GB       | 1         | 1      | 1.92%   |
| WDC WD10SPZX-24Z10 1TB            | 1         | 1      | 1.92%   |
| WDC WD10EADS-00M2B0 1TB           | 1         | 1      | 1.92%   |
| Transcend 3E128-TS2-550B01 100GB  | 1         | 4      | 1.92%   |
| Toshiba MK6006GAH 64GB            | 1         | 1      | 1.92%   |
| Toshiba MK1629GSGF 160GB          | 1         | 3      | 1.92%   |
| Seagate ST9500420AS 500GB         | 1         | 2      | 1.92%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 1.92%   |
| Seagate ST9320423AS 320GB         | 1         | 1      | 1.92%   |
| Seagate ST9160310AS 160GB         | 1         | 2      | 1.92%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 1.92%   |
| Seagate ST3750640NS 752GB         | 1         | 4      | 1.92%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 1.92%   |
| Seagate ST3320418AS 320GB         | 1         | 1      | 1.92%   |
| Seagate ST3120211AS 120GB         | 1         | 1      | 1.92%   |
| Seagate ST250DM000-1BD141 250GB   | 1         | 2      | 1.92%   |
| Seagate ST2000DM006-2DM164 2TB    | 1         | 1      | 1.92%   |
| Seagate ST1000DM003-1CH162 1TB    | 1         | 1      | 1.92%   |
| SanDisk SD7UB3Q256G1001 256GB     | 1         | 2      | 1.92%   |
| Samsung Electronics HM500JI 500GB | 1         | 2      | 1.92%   |
| Samsung Electronics HD154UI 1.5TB | 1         | 1      | 1.92%   |
| OCZ VERTEX3 120GB                 | 1         | 1      | 1.92%   |
| Kingston SV300S37A120G 120GB      | 1         | 1      | 1.92%   |
| Kingston SMSM151S3128GD 128GB     | 1         | 1      | 1.92%   |
| Kingston SMS200S3120G 120GB       | 1         | 1      | 1.92%   |
| KingSpec KSD-PA25.6-032MS 32GB    | 1         | 1      | 1.92%   |
| Intel SSDSC2CT180A4 180GB         | 1         | 1      | 1.92%   |
| Intel SSDSC2BB080G4 80GB          | 1         | 1      | 1.92%   |
| Intel SSDSA2M080G2GC 80GB         | 1         | 1      | 1.92%   |
| Hitachi HTS722010K9SA00 100GB     | 1         | 1      | 1.92%   |
| Hitachi HTS541060G9SA00 64GB      | 1         | 1      | 1.92%   |
| Hitachi HTC426060G9AT00 64GB      | 1         | 1      | 1.92%   |
| Hitachi HDS721010CLA332 1TB       | 1         | 2      | 1.92%   |
| Hitachi HDP725016GLA380 160GB     | 1         | 1      | 1.92%   |
| Hitachi DK23AA-12 12GB            | 1         | 1      | 1.92%   |
| HGST HTS545050A7E660 500GB        | 1         | 2      | 1.92%   |
| HGST HTE725032A7E630 320GB        | 1         | 1      | 1.92%   |
| GLOWAY FER60GS3-S7 64GB           | 1         | 1      | 1.92%   |
| Apple SSD SD0128F 121GB           | 1         | 1      | 1.92%   |
| A-DATA Technology SU630 240GB     | 1         | 2      | 1.92%   |
| A-DATA Technology SP550 480GB     | 1         | 3      | 1.92%   |
| A-DATA Technology SP550 240GB     | 1         | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 18     | 23.08%  |
| Hitachi             | 6         | 7      | 11.54%  |
| Kingston            | 5         | 6      | 9.62%   |
| Intel               | 5         | 5      | 9.62%   |
| WDC                 | 4         | 4      | 7.69%   |
| Toshiba             | 4         | 6      | 7.69%   |
| HGST                | 4         | 6      | 7.69%   |
| A-DATA Technology   | 3         | 6      | 5.77%   |
| Samsung Electronics | 2         | 3      | 3.85%   |
| XPG                 | 1         | 1      | 1.92%   |
| Transcend           | 1         | 4      | 1.92%   |
| SanDisk             | 1         | 2      | 1.92%   |
| OCZ                 | 1         | 1      | 1.92%   |
| KingSpec            | 1         | 1      | 1.92%   |
| GLOWAY              | 1         | 1      | 1.92%   |
| Apple               | 1         | 1      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 18     | 37.5%   |
| Hitachi             | 6         | 7      | 18.75%  |
| WDC                 | 4         | 4      | 12.5%   |
| Toshiba             | 4         | 6      | 12.5%   |
| HGST                | 4         | 6      | 12.5%   |
| Samsung Electronics | 2         | 3      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 44     | 61.54%  |
| SSD  | 20        | 28     | 38.46%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB     | 1         | 2      | 50%     |
| Samsung Electronics HD204UI 2TB | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 2      | 50%     |
| Samsung Electronics | 1         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 299       | 481    | 64.16%  |
| Detected | 114       | 172    | 24.46%  |
| Malfunc  | 51        | 72     | 10.94%  |
| Failed   | 2         | 4      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 259       | 56.67%  |
| AMD                              | 84        | 18.38%  |
| Samsung Electronics              | 34        | 7.44%   |
| Sandisk                          | 20        | 4.38%   |
| Broadcom / LSI                   | 10        | 2.19%   |
| Nvidia                           | 8         | 1.75%   |
| KIOXIA                           | 5         | 1.09%   |
| SK Hynix                         | 4         | 0.88%   |
| Phison Electronics               | 4         | 0.88%   |
| Marvell Technology Group         | 4         | 0.88%   |
| Kingston Technology Company      | 4         | 0.88%   |
| ASMedia Technology               | 4         | 0.88%   |
| VIA Technologies                 | 3         | 0.66%   |
| ULi Electronics                  | 2         | 0.44%   |
| Toshiba                          | 2         | 0.44%   |
| Lenovo                           | 2         | 0.44%   |
| Hewlett-Packard                  | 2         | 0.44%   |
| Union Memory (Shenzhen)          | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Silicon Image                    | 1         | 0.22%   |
| HighPoint Technologies           | 1         | 0.22%   |
| Dell                             | 1         | 0.22%   |
| ADATA Technology                 | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 46        | 8.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 21        | 4.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 21        | 4.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 18        | 3.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 17        | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 16        | 3.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 2.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 15        | 2.91%   |
| AMD FCH SATA Controller [IDE mode]                                               | 15        | 2.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 14        | 2.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 14        | 2.71%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 11        | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 1.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 9         | 1.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 1.74%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 8         | 1.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 6         | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 6         | 1.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 1.16%   |
| AMD 400 Series Chipset SATA Controller                                           | 6         | 1.16%   |
| Nvidia MCP61 SATA Controller                                                     | 5         | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 0.97%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 5         | 0.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 5         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 0.97%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 5         | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                           | 5         | 0.97%   |
| KIOXIA unknown                                                                   | 4         | 0.78%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 4         | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 0.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 0.78%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 4         | 0.78%   |
| Intel 82801CAM IDE U100 Controller                                               | 4         | 0.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 4         | 0.78%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4         | 0.78%   |
| Sandisk unknown                                                                  | 3         | 0.58%   |
| Sandisk PC SN520 NVMe SSD                                                        | 3         | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.58%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.58%   |
| Nvidia MCP61 IDE                                                                 | 3         | 0.58%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.58%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 0.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.58%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3         | 0.58%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 3         | 0.58%   |
| Intel 82801EB (ICH5) SATA Controller                                             | 3         | 0.58%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 3         | 0.58%   |
| AMD FCH IDE Controller                                                           | 3         | 0.58%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 2         | 0.39%   |
| ULi M5229 IDE                                                                    | 2         | 0.39%   |
| SK Hynix hynix unknown                                                           | 2         | 0.39%   |
| Samsung SM951 AHCI                                                               | 2         | 0.39%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.39%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.39%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 2         | 0.39%   |
| Lenovo unknown                                                                   | 2         | 0.39%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 292       | 62%     |
| IDE  | 84        | 17.83%  |
| NVMe | 77        | 16.35%  |
| RAID | 13        | 2.76%   |
| SAS  | 4         | 0.85%   |
| SCSI | 1         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 296       | 70.14%  |
| AMD     | 99        | 23.46%  |
| ARM     | 17        | 4.03%   |
| Unknown | 5         | 1.18%   |
| PowerPC | 4         | 0.95%   |
| 11th    | 1         | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                                             | 26        | 6.07%   |
| Intel Core i5-2520M CPU @ 2.50GHz                            | 12        | 2.8%    |
| ARM Cortex-A72 r0p3                                          | 10        | 2.34%   |
| Intel Core i5-3320M CPU @ 2.60GHz                            | 7         | 1.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                         | 7         | 1.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz                            | 6         | 1.4%    |
| AMD G-T40E Processor                                         | 6         | 1.4%    |
| Intel Core i5-5300U CPU @ 2.30GHz                            | 5         | 1.17%   |
| ARM Cortex-A53 r0p4                                          | 5         | 1.17%   |
|                                                              | 5         | 1.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz                            | 4         | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz                            | 4         | 0.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz                            | 4         | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz                            | 4         | 0.93%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class)     | 4         | 0.93%   |
| AMD Ryzen 7 5800X 8-Core Processor                           | 4         | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz                            | 3         | 0.7%    |
| Intel Core i7-5600U CPU @ 2.60GHz                            | 3         | 0.7%    |
| Intel Core i7-3520M CPU @ 2.90GHz                            | 3         | 0.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz                            | 3         | 0.7%    |
| Intel Core i3-6006U CPU @ 2.00GHz                            | 3         | 0.7%    |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                         | 3         | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics                       | 3         | 0.7%    |
| AMD Ryzen 7 4700U with Radeon Graphics                       | 3         | 0.7%    |
| PowerPC 7447A (Revision 0x105)                               | 2         | 0.47%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz                           | 2         | 0.47%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz                          | 2         | 0.47%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz                         | 2         | 0.47%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                          | 2         | 0.47%   |
| Intel Pentium M processor 1.70GHz ("GenuineIntel" 686-class) | 2         | 0.47%   |
| Intel Pentium CPU N4200 @ 1.10GHz                            | 2         | 0.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz                            | 2         | 0.47%   |
| Intel Core i7-6600U CPU @ 2.60GHz                            | 2         | 0.47%   |
| Intel Core i7-4770K CPU @ 3.50GHz                            | 2         | 0.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz                             | 2         | 0.47%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                           | 2         | 0.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz                           | 2         | 0.47%   |
| Intel Core i5-4570T CPU @ 2.90GHz                            | 2         | 0.47%   |
| Intel Core i5-4300U CPU @ 1.90GHz                            | 2         | 0.47%   |
| Intel Core i5-4260U CPU @ 1.40GHz                            | 2         | 0.47%   |
| Intel Core i5-4200U CPU @ 1.60GHz                            | 2         | 0.47%   |
| Intel Core i5-3230M CPU @ 2.60GHz                            | 2         | 0.47%   |
| Intel Core i5-2540M CPU @ 2.60GHz                            | 2         | 0.47%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz                           | 2         | 0.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz                           | 2         | 0.47%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                            | 2         | 0.47%   |
| Intel Core i3-5010U CPU @ 2.10GHz                            | 2         | 0.47%   |
| Intel Core i3-5005U CPU @ 2.00GHz                            | 2         | 0.47%   |
| Intel Core i3-4010U CPU @ 1.70GHz                            | 2         | 0.47%   |
| Intel Core i3-10110U CPU @ 2.10GHz                           | 2         | 0.47%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz                         | 2         | 0.47%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz                         | 2         | 0.47%   |
| Intel Celeron N4000 CPU @ 1.10GHz                            | 2         | 0.47%   |
| Intel Celeron CPU N3350 @ 1.10GHz                            | 2         | 0.47%   |
| Intel Celeron CPU N3050 @ 1.60GHz                            | 2         | 0.47%   |
| Intel Celeron CPU J1900 @ 1.99GHz                            | 2         | 0.47%   |
| Intel Celeron CPU 3865U @ 1.80GHz                            | 2         | 0.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                      | 2         | 0.47%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx              | 2         | 0.47%   |
| AMD Ryzen 7 5700G with Radeon Graphics                       | 2         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 87        | 20.57%  |
| Intel Core i7           | 52        | 12.29%  |
| AMD GX                  | 27        | 6.38%   |
| Intel Xeon              | 25        | 5.91%   |
| Intel Celeron           | 25        | 5.91%   |
| Intel Core i3           | 21        | 4.96%   |
| Intel Core 2 Duo        | 21        | 4.96%   |
| Other                   | 19        | 4.49%   |
| AMD Ryzen 7             | 19        | 4.49%   |
| ARM Cortex              | 17        | 4.02%   |
| Intel Atom              | 13        | 3.07%   |
| AMD Ryzen 5             | 8         | 1.89%   |
| AMD G                   | 7         | 1.65%   |
| Intel Pentium M         | 5         | 1.18%   |
| Intel Pentium 4         | 5         | 1.18%   |
| AMD Ryzen 3             | 5         | 1.18%   |
| Intel Pentium Dual-Core | 4         | 0.95%   |
| Intel Pentium           | 4         | 0.95%   |
| Intel Genuine           | 4         | 0.95%   |
| Intel Core 2            | 4         | 0.95%   |
| AMD Ryzen 7 PRO         | 4         | 0.95%   |
| AMD A4                  | 4         | 0.95%   |
| Intel Pentium Silver    | 3         | 0.71%   |
| Intel Core m3           | 2         | 0.47%   |
| Intel Core Duo          | 2         | 0.47%   |
| AMD Geode Integrated    | 2         | 0.47%   |
| AMD E2                  | 2         | 0.47%   |
| AMD E                   | 2         | 0.47%   |
| AMD Athlon II X3        | 2         | 0.47%   |
| AMD Athlon 64 X2        | 2         | 0.47%   |
| Intel Xeon Gold         | 1         | 0.24%   |
| Intel Pentium III       | 1         | 0.24%   |
| Intel Pentium Dual      | 1         | 0.24%   |
| Intel Pentium D         | 1         | 0.24%   |
| Intel Mobile Pentium 4  | 1         | 0.24%   |
| Intel Mobile Celeron    | 1         | 0.24%   |
| Intel Core Solo         | 1         | 0.24%   |
| Intel Core M            | 1         | 0.24%   |
| Intel Core i9           | 1         | 0.24%   |
| Intel Celeron M         | 1         | 0.24%   |
| Intel Celeron D         | 1         | 0.24%   |
| AMD V120                | 1         | 0.24%   |
| AMD Turion II Neo       | 1         | 0.24%   |
| AMD Ryzen 5 PRO         | 1         | 0.24%   |
| AMD Phenom II X6        | 1         | 0.24%   |
| AMD Phenom II X4        | 1         | 0.24%   |
| AMD FX                  | 1         | 0.24%   |
| AMD Embedded            | 1         | 0.24%   |
| AMD E1                  | 1         | 0.24%   |
| AMD C-50                | 1         | 0.24%   |
| AMD Athlon XP           | 1         | 0.24%   |
| AMD Athlon II X4        | 1         | 0.24%   |
| AMD Athlon II Neo       | 1         | 0.24%   |
| AMD Athlon              | 1         | 0.24%   |
| AMD A6                  | 1         | 0.24%   |
| AMD A10                 | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 139       | 32.94%  |
| 4       | 117       | 27.73%  |
| Unknown | 79        | 18.72%  |
| 1       | 32        | 7.58%   |
| 8       | 17        | 4.03%   |
| 6       | 14        | 3.32%   |
| 16      | 13        | 3.08%   |
| 12      | 8         | 1.9%    |
| 3       | 2         | 0.47%   |
| 36      | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 318       | 74.65%  |
| Unknown | 102       | 23.94%  |
| 2       | 6         | 1.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 176       | 41.71%  |
| 1       | 140       | 33.18%  |
| Unknown | 106       | 25.12%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 51        | 12.03%  |
| Unknown       | 42        | 9.91%   |
| Haswell       | 31        | 7.31%   |
| SandyBridge   | 29        | 6.84%   |
| Puma          | 26        | 6.13%   |
| Penryn        | 24        | 5.66%   |
| IvyBridge     | 24        | 5.66%   |
| Broadwell     | 22        | 5.19%   |
| Zen 2         | 16        | 3.77%   |
| Skylake       | 16        | 3.77%   |
| P6            | 15        | 3.54%   |
| Bonnell       | 12        | 2.83%   |
| Bobcat        | 12        | 2.83%   |
| Westmere      | 11        | 2.59%   |
| Silvermont    | 11        | 2.59%   |
| NetBurst      | 9         | 2.12%   |
| Zen           | 8         | 1.89%   |
| K10           | 8         | 1.89%   |
| Core          | 8         | 1.89%   |
| Goldmont plus | 7         | 1.65%   |
| Goldmont      | 7         | 1.65%   |
| Zen+          | 6         | 1.42%   |
| Zen 3         | 4         | 0.94%   |
| Jaguar        | 4         | 0.94%   |
| TigerLake     | 3         | 0.71%   |
| Nehalem       | 3         | 0.71%   |
| IceLake       | 3         | 0.71%   |
| Piledriver    | 2         | 0.47%   |
| K8 Hammer     | 2         | 0.47%   |
| K10 Llano     | 2         | 0.47%   |
| Geode         | 2         | 0.47%   |
| Excavator     | 2         | 0.47%   |
| K6            | 1         | 0.24%   |
| CometLake     | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 237       | 58.96%  |
| AMD                                          | 103       | 25.62%  |
| Nvidia                                       | 41        | 10.2%   |
| Matrox Electronics Systems                   | 11        | 2.74%   |
| ASPEED Technology                            | 7         | 1.74%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.25%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.25%   |
| 3DLabs                                       | 1         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 5.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 4.3%    |
| Intel HD Graphics 5500                                                                   | 17        | 4.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 3.34%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 13        | 3.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 2.86%   |
| Intel UHD Graphics 620                                                                   | 11        | 2.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.39%   |
| AMD Renoir                                                                               | 10        | 2.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.91%   |
| Intel HD Graphics 620                                                                    | 8         | 1.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 7         | 1.67%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 7         | 1.67%   |
| Matrox Electronics Systems G200eR2                                                       | 6         | 1.43%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 6         | 1.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.43%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.19%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.19%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5         | 1.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 0.95%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 0.72%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3         | 0.72%   |
| Intel HD Graphics 500                                                                    | 3         | 0.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.72%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3         | 0.72%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                             | 3         | 0.72%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                                      | 3         | 0.72%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 3         | 0.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 0.72%   |
| AMD ES1000                                                                               | 3         | 0.72%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.72%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 0.72%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.48%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.48%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 0.48%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 0.48%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.48%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 0.48%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 2         | 0.48%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.48%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.48%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.48%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 0.48%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 0.48%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 2         | 0.48%   |
| Intel HD Graphics P630                                                                   | 2         | 0.48%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.48%   |
| Intel HD Graphics 530                                                                    | 2         | 0.48%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.48%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.48%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2         | 0.48%   |
| Intel 82865G Integrated Graphics Controller                                              | 2         | 0.48%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 2         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 177       | 41.75%  |
| 1 x AMD        | 89        | 20.99%  |
| Other          | 54        | 12.74%  |
| 2 x Intel      | 32        | 7.55%   |
| Intel + Nvidia | 19        | 4.48%   |
| 1 x Nvidia     | 18        | 4.25%   |
| 1 x Matrox     | 10        | 2.36%   |
| Intel + AMD    | 9         | 2.12%   |
| 1 x ASPEED     | 7         | 1.65%   |
| AMD + Nvidia   | 3         | 0.71%   |
| 2 x Nvidia     | 1         | 0.24%   |
| 2 x AMD        | 1         | 0.24%   |
| 1 x XGI        | 1         | 0.24%   |
| 1 x SiS        | 1         | 0.24%   |
| AMD + Matrox   | 1         | 0.24%   |
| 1 x 3DLabs     | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 341       | 80.61%  |
| Unknown | 82        | 19.39%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 422       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 35        | 14.89%  |
| AU Optronics            | 32        | 13.62%  |
| BOE                     | 25        | 10.64%  |
| Samsung Electronics     | 20        | 8.51%   |
| Lenovo                  | 17        | 7.23%   |
| Chimei Innolux          | 16        | 6.81%   |
| Dell                    | 12        | 5.11%   |
| Goldstar                | 10        | 4.26%   |
| Ancor Communications    | 8         | 3.4%    |
| Apple                   | 7         | 2.98%   |
| Philips                 | 6         | 2.55%   |
| Iiyama                  | 5         | 2.13%   |
| NEC Computers           | 4         | 1.7%    |
| Sharp                   | 3         | 1.28%   |
| PANDA                   | 3         | 1.28%   |
| InfoVision              | 3         | 1.28%   |
| Hewlett-Packard         | 3         | 1.28%   |
| BenQ                    | 3         | 1.28%   |
| Acer                    | 3         | 1.28%   |
| ViewSonic               | 2         | 0.85%   |
| IBM                     | 2         | 0.85%   |
| Eizo                    | 2         | 0.85%   |
| Chi Mei Optoelectronics | 2         | 0.85%   |
| ASUSTek Computer        | 2         | 0.85%   |
| AOC                     | 2         | 0.85%   |
| Vizio                   | 1         | 0.43%   |
| SHI                     | 1         | 0.43%   |
| Medion                  | 1         | 0.43%   |
| LTM                     | 1         | 0.43%   |
| LG Philips              | 1         | 0.43%   |
| HannStar                | 1         | 0.43%   |
| Gigabyte Technology     | 1         | 0.43%   |
| CSO                     | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                | 6         | 2.53%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch          | 6         | 2.53%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch           | 3         | 1.27%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch                | 3         | 1.27%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch   | 3         | 1.27%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch   | 2         | 0.84%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                  | 2         | 0.84%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch           | 2         | 0.84%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch           | 2         | 0.84%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch           | 2         | 0.84%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 2         | 0.84%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch           | 2         | 0.84%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch               | 2         | 0.84%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                  | 2         | 0.84%   |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                   | 2         | 0.84%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                  | 2         | 0.84%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch           | 2         | 0.84%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                      | 2         | 0.84%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                       | 2         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch        | 2         | 0.84%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 310x170mm 13.9-inch        | 2         | 0.84%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch        | 2         | 0.84%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                  | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch         | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch         | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch          | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch         | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch          | 2         | 0.84%   |
| Vizio E320i-A0 VIZ0091 1366x768 700x390mm 31.5-inch                    | 1         | 0.42%   |
| ViewSonic LCD Monitor VSCE032 2560x1440 530x300mm 24.0-inch            | 1         | 0.42%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 1         | 0.42%   |
| SHI LCD-TV**** SHI6102 1360x768 700x390mm 31.5-inch                    | 1         | 0.42%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 340x190mm 15.3-inch                | 1         | 0.42%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch                | 1         | 0.42%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                | 1         | 0.42%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch      | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM03EF 1680x1050 470x300mm 22.0-inch   | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 380x300mm 19.1-inch   | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM00A1 1280x1024 340x270mm 17.1-inch   | 1         | 0.42%   |
| Samsung Electronics SMB2340 SAM0691 1920x1080 510x290mm 23.1-inch      | 1         | 0.42%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 800x330mm 34.1-inch       | 1         | 0.42%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 1         | 0.42%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 520x320mm 24.0-inch      | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch   | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch   | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch   | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SDC374A 3200x1800 290x170mm 13.2-inch  | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch   | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch  | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SAM0D3E 3840x2160 1210x680mm 54.6-inch | 1         | 0.42%   |
| Samsung Electronics DM700A-D SEM0324 1920x1080 520x290mm 23.4-inch     | 1         | 0.42%   |
| Samsung Electronics C34H89x SAM0E25 3440x1440 800x330mm 34.1-inch      | 1         | 0.42%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch               | 1         | 0.42%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch               | 1         | 0.42%   |
| Philips LCD Monitor PHLC00B 1280x1024 340x270mm 17.1-inch              | 1         | 0.42%   |
| Philips 190S PHL086B 1280x1024 380x300mm 19.1-inch                     | 1         | 0.42%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                | 1         | 0.42%   |
| PANDA LCD Monitor NCP0046 1920x1080 340x190mm 15.3-inch                | 1         | 0.42%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch                | 1         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 81        | 35.06%  |
| 1366x768 (WXGA)    | 56        | 24.24%  |
| 3840x2160 (4K)     | 13        | 5.63%   |
| 1280x800 (WXGA)    | 13        | 5.63%   |
| 2560x1440 (QHD)    | 11        | 4.76%   |
| 1440x900 (WXGA+)   | 10        | 4.33%   |
| 1280x1024 (SXGA)   | 9         | 3.9%    |
| 3440x1440          | 6         | 2.6%    |
| 1920x1200 (WUXGA)  | 6         | 2.6%    |
| 1600x900 (HD+)     | 6         | 2.6%    |
| 1680x1050 (WSXGA+) | 4         | 1.73%   |
| 2736x1824          | 2         | 0.87%   |
| 1360x768           | 2         | 0.87%   |
| 1024x768 (XGA)     | 2         | 0.87%   |
| 720x1280           | 1         | 0.43%   |
| 3840x2400          | 1         | 0.43%   |
| 3840x1080          | 1         | 0.43%   |
| 3200x1800 (QHD+)   | 1         | 0.43%   |
| 2256x1504          | 1         | 0.43%   |
| 1920x1280          | 1         | 0.43%   |
| 1600x1200          | 1         | 0.43%   |
| 1440x960           | 1         | 0.43%   |
| 1280x854           | 1         | 0.43%   |
| 1024x600           | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 52        | 22.41%  |
| 15     | 48        | 20.69%  |
| 12     | 30        | 12.93%  |
| 24     | 13        | 5.6%    |
| 23     | 12        | 5.17%   |
| 27     | 10        | 4.31%   |
| 19     | 10        | 4.31%   |
| 11     | 10        | 4.31%   |
| 21     | 8         | 3.45%   |
| 14     | 8         | 3.45%   |
| 34     | 6         | 2.59%   |
| 31     | 5         | 2.16%   |
| 17     | 5         | 2.16%   |
| 18     | 4         | 1.72%   |
| 10     | 3         | 1.29%   |
| 54     | 2         | 0.86%   |
| 49     | 1         | 0.43%   |
| 28     | 1         | 0.43%   |
| 22     | 1         | 0.43%   |
| 20     | 1         | 0.43%   |
| 9      | 1         | 0.43%   |
| 6      | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 90        | 38.79%  |
| 201-300     | 65        | 28.02%  |
| 501-600     | 33        | 14.22%  |
| 401-500     | 20        | 8.62%   |
| 601-700     | 7         | 3.02%   |
| 701-800     | 6         | 2.59%   |
| 351-400     | 6         | 2.59%   |
| 1001-1500   | 3         | 1.29%   |
| 101-200     | 2         | 0.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 165       | 73.33%  |
| 16/10 | 34        | 15.11%  |
| 5/4   | 9         | 4%      |
| 3/2   | 7         | 3.11%   |
| 21/9  | 6         | 2.67%   |
| 4/3   | 3         | 1.33%   |
| 32/9  | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 50        | 21.65%  |
| 91-100         | 39        | 16.88%  |
| 61-70          | 30        | 12.99%  |
| 201-250        | 28        | 12.12%  |
| 351-500        | 12        | 5.19%   |
| 51-60          | 11        | 4.76%   |
| 151-200        | 11        | 4.76%   |
| 301-350        | 10        | 4.33%   |
| 101-110        | 10        | 4.33%   |
| 71-80          | 9         | 3.9%    |
| 141-150        | 8         | 3.46%   |
| 251-300        | 5         | 2.16%   |
| More than 1000 | 2         | 0.87%   |
| 41-50          | 2         | 0.87%   |
| 1-40           | 2         | 0.87%   |
| 121-130        | 1         | 0.43%   |
| 501-1000       | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 93        | 40.09%  |
| 51-100        | 54        | 23.28%  |
| 101-120       | 48        | 20.69%  |
| 161-240       | 25        | 10.78%  |
| More than 240 | 8         | 3.45%   |
| 1-50          | 4         | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 254       | 59.62%  |
| 0     | 156       | 36.62%  |
| 2     | 15        | 3.52%   |
| 3     | 1         | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 267       | 47.34%  |
| Realtek Semiconductor             | 145       | 25.71%  |
| Qualcomm Atheros                  | 44        | 7.8%    |
| Broadcom                          | 33        | 5.85%   |
| Qualcomm Atheros Communications   | 9         | 1.6%    |
| Marvell Technology Group          | 7         | 1.24%   |
| TP-Link                           | 5         | 0.89%   |
| Ericsson Business Mobile Networks | 5         | 0.89%   |
| Apple                             | 5         | 0.89%   |
| U-Blox                            | 4         | 0.71%   |
| Ralink                            | 4         | 0.71%   |
| Edimax Technology                 | 4         | 0.71%   |
| VIA Technologies                  | 3         | 0.53%   |
| Nvidia                            | 3         | 0.53%   |
| 3Com                              | 3         | 0.53%   |
| Sierra Wireless                   | 2         | 0.35%   |
| Ralink Technology                 | 2         | 0.35%   |
| Xiaomi                            | 1         | 0.18%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.18%   |
| Samsung Electronics               | 1         | 0.18%   |
| Qcom                              | 1         | 0.18%   |
| Oracle/SUN                        | 1         | 0.18%   |
| National Semiconductor            | 1         | 0.18%   |
| Microsoft                         | 1         | 0.18%   |
| Micro Star International          | 1         | 0.18%   |
| MediaTek                          | 1         | 0.18%   |
| LG Electronics                    | 1         | 0.18%   |
| Google                            | 1         | 0.18%   |
| Fibocom                           | 1         | 0.18%   |
| Emulex                            | 1         | 0.18%   |
| Dell                              | 1         | 0.18%   |
| Davicom Semiconductor             | 1         | 0.18%   |
| D-Link System                     | 1         | 0.18%   |
| D-Link                            | 1         | 0.18%   |
| AVM                               | 1         | 0.18%   |
| Accton Technology                 | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 110       | 15.56%  |
| Intel I211 Gigabit Network Connection                                       | 26        | 3.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 25        | 3.54%   |
| Intel I210 Gigabit Network Connection                                       | 19        | 2.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 19        | 2.69%   |
| Intel Wireless 8265 / 8275                                                  | 17        | 2.4%    |
| Intel Wi-Fi 6 AX200                                                         | 17        | 2.4%    |
| Intel Wireless 7265                                                         | 15        | 2.12%   |
| Intel Wireless 7260                                                         | 15        | 2.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 14        | 1.98%   |
| Intel 82567LM Gigabit Network Connection                                    | 13        | 1.84%   |
| Intel 82574L Gigabit Network Connection                                     | 10        | 1.41%   |
| Intel Ethernet Connection I217-LM                                           | 9         | 1.27%   |
| Intel Wireless 8260                                                         | 8         | 1.13%   |
| Intel Ultimate N WiFi Link 5300                                             | 8         | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                                       | 8         | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 7         | 0.99%   |
| Intel I350 Gigabit Network Connection                                       | 7         | 0.99%   |
| Intel Ethernet Connection I219-LM                                           | 7         | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 6         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 6         | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                             | 6         | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 6         | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 6         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                                        | 6         | 0.85%   |
| Intel Centrino Advanced-N 6200                                              | 6         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 5         | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 5         | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 5         | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 5         | 0.71%   |
| Intel Wireless 3165                                                         | 5         | 0.71%   |
| Intel 82577LM Gigabit Network Connection                                    | 5         | 0.71%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 5         | 0.71%   |
| U-Blox [u-blox 8]                                                           | 4         | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                           | 4         | 0.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 4         | 0.57%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                     | 4         | 0.57%   |
| Intel Wireless-AC 9260                                                      | 4         | 0.57%   |
| Intel Wi-Fi 6 AX201                                                         | 4         | 0.57%   |
| Intel Ethernet Connection I218-LM                                           | 4         | 0.57%   |
| Intel Ethernet Connection (6) I219-V                                        | 4         | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 4         | 0.57%   |
| Intel Centrino Wireless-N 2230                                              | 4         | 0.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 4         | 0.57%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 4         | 0.57%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 4         | 0.57%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                             | 4         | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 3         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 3         | 0.42%   |
| Nvidia MCP79 Ethernet                                                       | 3         | 0.42%   |
| Intel Wireless 3160                                                         | 3         | 0.42%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 3         | 0.42%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                   | 3         | 0.42%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                             | 3         | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                       | 3         | 0.42%   |
| Intel Ethernet Connection (4) I219-LM                                       | 3         | 0.42%   |
| Intel Ethernet Connection (3) I218-V                                        | 3         | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                                       | 3         | 0.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 3         | 0.42%   |
| Intel Centrino Wireless-N 2200                                              | 3         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 168       | 59.57%  |
| Qualcomm Atheros                | 39        | 13.83%  |
| Realtek Semiconductor           | 27        | 9.57%   |
| Broadcom                        | 16        | 5.67%   |
| Qualcomm Atheros Communications | 9         | 3.19%   |
| TP-Link                         | 5         | 1.77%   |
| Ralink                          | 4         | 1.42%   |
| Edimax Technology               | 4         | 1.42%   |
| Sierra Wireless                 | 2         | 0.71%   |
| Ralink Technology               | 2         | 0.71%   |
| Qcom                            | 1         | 0.35%   |
| Micro Star International        | 1         | 0.35%   |
| MediaTek                        | 1         | 0.35%   |
| Dell                            | 1         | 0.35%   |
| D-Link System                   | 1         | 0.35%   |
| D-Link                          | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 19        | 6.71%   |
| Intel Wireless 8265 / 8275                                                    | 17        | 6.01%   |
| Intel Wi-Fi 6 AX200                                                           | 17        | 6.01%   |
| Intel Wireless 7265                                                           | 15        | 5.3%    |
| Intel Wireless 7260                                                           | 15        | 5.3%    |
| Intel Wireless 8260                                                           | 8         | 2.83%   |
| Intel Ultimate N WiFi Link 5300                                               | 8         | 2.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 7         | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 2.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 6         | 2.12%   |
| Qualcomm Atheros AR9271 802.11n                                               | 6         | 2.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 6         | 2.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 6         | 2.12%   |
| Intel Centrino Advanced-N 6200                                                | 6         | 2.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5         | 1.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 1.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 5         | 1.77%   |
| Intel Wireless 3165                                                           | 5         | 1.77%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 5         | 1.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 4         | 1.41%   |
| Intel Wireless-AC 9260                                                        | 4         | 1.41%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 1.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 4         | 1.41%   |
| Intel Centrino Wireless-N 2230                                                | 4         | 1.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 4         | 1.41%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 4         | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 3         | 1.06%   |
| Intel Wireless 3160                                                           | 3         | 1.06%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 3         | 1.06%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 3         | 1.06%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 3         | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 1.06%   |
| Intel Centrino Wireless-N 2200                                                | 3         | 1.06%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 3         | 1.06%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 2         | 0.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2         | 0.71%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2         | 0.71%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 2         | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 0.71%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 2         | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 0.71%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 2         | 0.71%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 2         | 0.71%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 2         | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 2         | 0.71%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 2         | 0.71%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 0.71%   |
| TP-Link TP-LINK Wireless USB Adapter                                          | 1         | 0.35%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                 | 1         | 0.35%   |
| Sierra Wireless EM7455                                                        | 1         | 0.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.35%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1         | 0.35%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 0.35%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1         | 0.35%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 0.35%   |
| Realtek 802.11n WLAN Adapter                                                  | 1         | 0.35%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.35%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 189       | 48.96%  |
| Realtek Semiconductor            | 136       | 35.23%  |
| Broadcom                         | 22        | 5.7%    |
| Qualcomm Atheros                 | 9         | 2.33%   |
| Marvell Technology Group         | 7         | 1.81%   |
| Apple                            | 4         | 1.04%   |
| VIA Technologies                 | 3         | 0.78%   |
| Nvidia                           | 3         | 0.78%   |
| 3Com                             | 3         | 0.78%   |
| Xiaomi                           | 1         | 0.26%   |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |
| Samsung Electronics              | 1         | 0.26%   |
| Oracle/SUN                       | 1         | 0.26%   |
| National Semiconductor           | 1         | 0.26%   |
| Microsoft                        | 1         | 0.26%   |
| Google                           | 1         | 0.26%   |
| Emulex                           | 1         | 0.26%   |
| Davicom Semiconductor            | 1         | 0.26%   |
| Accton Technology                | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 110       | 27.3%   |
| Intel I211 Gigabit Network Connection                             | 26        | 6.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 6.2%    |
| Intel I210 Gigabit Network Connection                             | 19        | 4.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 3.47%   |
| Intel 82567LM Gigabit Network Connection                          | 13        | 3.23%   |
| Intel 82574L Gigabit Network Connection                           | 10        | 2.48%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 2.23%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 1.99%   |
| Intel I350 Gigabit Network Connection                             | 7         | 1.74%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.74%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 1.24%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.99%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 4         | 0.99%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.99%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.99%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 4         | 0.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.74%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.74%   |
| Intel Ethernet Connection (3) I218-V                              | 3         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.74%   |
| Intel 82573L Gigabit Ethernet Controller                          | 3         | 0.74%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 3         | 0.74%   |
| VIA VT6105M [Rhine-III]                                           | 2         | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.5%    |
| Intel Ethernet Controller I225-V                                  | 2         | 0.5%    |
| Intel Ethernet Connection I218-V                                  | 2         | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 2         | 0.5%    |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.5%    |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.5%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 2         | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.5%    |
| Intel 82576 Gigabit Network Connection                            | 2         | 0.5%    |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 2         | 0.5%    |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.5%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.5%    |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 0.5%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.5%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 0.5%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 2         | 0.5%    |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 2         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.25%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 0.25%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.25%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.25%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.25%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.25%   |
| Oracle/SUN RIO 10/100 Ethernet [eri]                              | 1         | 0.25%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 370       | 57.01%  |
| WiFi     | 258       | 39.75%  |
| Modem    | 13        | 2%      |
| Unknown  | 8         | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 201       | 53.17%  |
| WiFi     | 177       | 46.83%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 222       | 52.61%  |
| 1     | 110       | 26.07%  |
| 3     | 35        | 8.29%   |
| 0     | 23        | 5.45%   |
| 4     | 22        | 5.21%   |
| 8     | 3         | 0.71%   |
| 7     | 2         | 0.47%   |
| 6     | 2         | 0.47%   |
| 5     | 2         | 0.47%   |
| 12    | 1         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 422       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 87        | 56.13%  |
| Broadcom                        | 20        | 12.9%   |
| Apple                           | 12        | 7.74%   |
| IMC Networks                    | 8         | 5.16%   |
| Alps Electric                   | 7         | 4.52%   |
| Realtek Semiconductor           | 6         | 3.87%   |
| Qualcomm Atheros Communications | 5         | 3.23%   |
| Foxconn / Hon Hai               | 3         | 1.94%   |
| Cambridge Silicon Radio         | 2         | 1.29%   |
| ASUSTek Computer                | 2         | 1.29%   |
| Ralink                          | 1         | 0.65%   |
| Lite-On Technology              | 1         | 0.65%   |
| Creative Technology             | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 43        | 27.74%  |
| Intel AX200 Bluetooth                                                               | 15        | 9.68%   |
| Intel AX201 Bluetooth                                                               | 10        | 6.45%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 7         | 4.52%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 3.87%   |
| Apple Apple Broadcom Built-in Bluetooth                                             | 6         | 3.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 3.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 5         | 3.23%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 5         | 3.23%   |
| Apple Bluetooth Host Controller                                                     | 5         | 3.23%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 5         | 3.23%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 2.58%   |
| Realtek  Bluetooth Adapter                                                          | 3         | 1.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.94%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.29%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip                                | 2         | 1.29%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                                         | 2         | 1.29%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]                              | 2         | 1.29%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.29%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 2         | 1.29%   |
| Realtek  Bluetooth 4.0 Adapter                                                      | 1         | 0.65%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.65%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                                             | 1         | 0.65%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE                                 | 1         | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.65%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.65%   |
| IMC Networks Realtek Bluetooth Adapter                                              | 1         | 0.65%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS                                    | 1         | 0.65%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter                         | 1         | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.65%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device                            | 1         | 0.65%   |
| Creative Creative Bluetooth Audio W2                                                | 1         | 0.65%   |
| Broadcom BCM43142A0 Bluetooth Module                                                | 1         | 0.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.65%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.65%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 0.65%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.65%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 251       | 67.11%  |
| AMD                              | 80        | 21.39%  |
| Nvidia                           | 24        | 6.42%   |
| C-Media Electronics              | 5         | 1.34%   |
| VIA Technologies                 | 2         | 0.53%   |
| ULi Electronics                  | 2         | 0.53%   |
| ESS Technology                   | 2         | 0.53%   |
| Creative Labs                    | 2         | 0.53%   |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |
| Logitech                         | 1         | 0.27%   |
| Lenovo                           | 1         | 0.27%   |
| JMTek                            | 1         | 0.27%   |
| Generalplus Technology           | 1         | 0.27%   |
| Blue Microphones                 | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 33        | 7.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 5.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 4.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 20        | 4.31%   |
| Intel Broadwell-U Audio Controller                                                                | 20        | 4.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 19        | 4.09%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 19        | 4.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 18        | 3.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 2.59%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 2.59%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.59%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 11        | 2.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 2.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.16%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 1.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9         | 1.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 1.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.51%   |
| AMD FCH Azalia Controller                                                                         | 7         | 1.51%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.29%   |
| AMD Navi 10 HDMI Audio                                                                            | 6         | 1.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 1.29%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.08%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.08%   |
| Nvidia MCP61 High Definition Audio                                                                | 4         | 0.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.86%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 0.86%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 0.86%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 4         | 0.86%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 0.86%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.65%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 0.65%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 3         | 0.65%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.65%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 0.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.65%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                                         | 2         | 0.43%   |
| Nvidia unknown                                                                                    | 2         | 0.43%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.43%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.43%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 0.43%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.43%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 2         | 0.43%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.43%   |
| C-Media Electronics Digital Hifi Audio Digital Hifi Audio SPDIFs                                  | 2         | 0.43%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2         | 0.43%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.43%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 19        | 33.93%  |
| Samsung Electronics | 12        | 21.43%  |
| SK Hynix            | 6         | 10.71%  |
| Kingston            | 4         | 7.14%   |
| Micron Technology   | 3         | 5.36%   |
| Elpida              | 3         | 5.36%   |
| Transcend           | 2         | 3.57%   |
| Ramaxel Technology  | 2         | 3.57%   |
| Crucial             | 2         | 3.57%   |
| Nanya Technology    | 1         | 1.79%   |
| A-DATA Technology   | 1         | 1.79%   |
| Unknown             | 1         | 1.79%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 3         | 4.76%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 3         | 4.76%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s          | 2         | 3.17%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 3.17%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s     | 2         | 3.17%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s       | 2         | 3.17%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 2         | 3.17%   |
| Unknown RAM Module 512MB SODIMM SDRAM                   | 1         | 1.59%   |
| Unknown RAM Module 512MB SODIMM DDR                     | 1         | 1.59%   |
| Unknown RAM Module 512MB DIMM SDRAM                     | 1         | 1.59%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s               | 1         | 1.59%   |
| Unknown RAM Module 512MB DIMM 400MT/s                   | 1         | 1.59%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 1.59%   |
| Unknown RAM Module 256MB SODIMM DRAM                    | 1         | 1.59%   |
| Unknown RAM Module 256MB DIMM 333MT/s                   | 1         | 1.59%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s          | 1         | 1.59%   |
| Unknown RAM Module 2048MB SODIMM DDR2                   | 1         | 1.59%   |
| Unknown RAM Module 2048MB DIMM DDR2 266MT/s             | 1         | 1.59%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 1.59%   |
| Unknown RAM Module 1GB DIMM 400MT/s                     | 1         | 1.59%   |
| Unknown RAM Module 128MB SODIMM DRAM                    | 1         | 1.59%   |
| Unknown RAM Module 1024MB SODIMM DDR                    | 1         | 1.59%   |
| Unknown RAM Module 1024MB DIMM DDR                      | 1         | 1.59%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 1         | 1.59%   |
| Transcend RAM TS1GSK64W6H 8GB DIMM DDR3 1600MT/s        | 1         | 1.59%   |
| Transcend RAM TS128MLQ64V6J 1GB DIMM DDR2 667MT/s       | 1         | 1.59%   |
| SK Hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 667MT/s     | 1         | 1.59%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 1.59%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 1         | 1.59%   |
| SK Hynix RAM 484D543332355336 2GB SODIMM DDR3 1333MT/s  | 1         | 1.59%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 1         | 1.59%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s   | 1         | 1.59%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s   | 1         | 1.59%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 1.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 1.59%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 1.59%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 1.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1         | 1.59%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s   | 1         | 1.59%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s  | 1         | 1.59%   |
| Samsung RAM M3 78T2953CZ3-CE6 1GB DIMM DDR2 667MT/s     | 1         | 1.59%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s | 1         | 1.59%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s | 1         | 1.59%   |
| Nanya RAM NT1GT64U88D0BY-AD 1024MB DIMM DDR2 800MT/s    | 1         | 1.59%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s   | 1         | 1.59%   |
| Micron RAM 8JSF12864HZ-1G1F1 1GB SODIMM DDR3 800MT/s    | 1         | 1.59%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s   | 1         | 1.59%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s   | 1         | 1.59%   |
| Kingston RAM 4143523531325836 4GB SODIMM DDR3 1333MT/s  | 1         | 1.59%   |
| Elpida RAM Module 1GB SODIMM DDR2 533MT/s               | 1         | 1.59%   |
| Elpida RAM EDJ4216EFBG-L 2048MB SODIMM DDR3 1600MT/s    | 1         | 1.59%   |
| Elpida RAM EBE11UD8AJWA-8G-E 1024MB DIMM DDR2 800MT/s   | 1         | 1.59%   |
| A-DATA RAM AM1U16BC4P2-B19C 4GB SODIMM DDR3 1600MT/s    | 1         | 1.59%   |
| Unknown                                                 | 1         | 1.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 27        | 56.25%  |
| DDR2    | 6         | 12.5%   |
| DDR4    | 5         | 10.42%  |
| SDRAM   | 3         | 6.25%   |
| DDR     | 3         | 6.25%   |
| DRAM    | 2         | 4.17%   |
| Unknown | 2         | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 37        | 77.08%  |
| DIMM   | 11        | 22.92%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 21        | 37.5%   |
| 2048  | 9         | 16.07%  |
| 1024  | 9         | 16.07%  |
| 8192  | 7         | 12.5%   |
| 512   | 5         | 8.93%   |
| 16384 | 2         | 3.57%   |
| 256   | 2         | 3.57%   |
| 128   | 1         | 1.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 14        | 27.45%  |
| Unknown | 9         | 17.65%  |
| 1333    | 8         | 15.69%  |
| 1334    | 4         | 7.84%   |
| 3200    | 3         | 5.88%   |
| 800     | 3         | 5.88%   |
| 2400    | 2         | 3.92%   |
| 1067    | 2         | 3.92%   |
| 400     | 2         | 3.92%   |
| 667     | 1         | 1.96%   |
| 533     | 1         | 1.96%   |
| 333     | 1         | 1.96%   |
| 266     | 1         | 1.96%   |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 47        | 34.06%  |
| Acer                                   | 17        | 12.32%  |
| IMC Networks                           | 16        | 11.59%  |
| Realtek Semiconductor                  | 8         | 5.8%    |
| Microdia                               | 7         | 5.07%   |
| Lite-On Technology                     | 7         | 5.07%   |
| Logitech                               | 5         | 3.62%   |
| Syntek                                 | 3         | 2.17%   |
| Suyin                                  | 3         | 2.17%   |
| Silicon Motion                         | 3         | 2.17%   |
| Ricoh                                  | 3         | 2.17%   |
| Quanta                                 | 3         | 2.17%   |
| Apple                                  | 3         | 2.17%   |
| Sunplus Innovation Technology          | 2         | 1.45%   |
| Luxvisions Innotech Limited            | 2         | 1.45%   |
| Lenovo                                 | 2         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.45%   |
| Alcor Micro                            | 2         | 1.45%   |
| Z-Star Microelectronics                | 1         | 0.72%   |
| Denron                                 | 1         | 0.72%   |
| ALi                                    | 1         | 0.72%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony integrated camera                                   | 18        | 12.95%  |
| Lite-On Integrated Camera                                   | 7         | 5.04%   |
| IMC Networks Integrated Camera                              | 7         | 5.04%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 5         | 3.6%    |
| Acer Integrated Camera                                      | 5         | 3.6%    |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 2.16%   |
| Chicony Integrated Camera [ThinkPad]                        | 3         | 2.16%   |
| Acer EasyCamera                                             | 3         | 2.16%   |
| Syntek Lenovo EasyCamera                                    | 2         | 1.44%   |
| Realtek USB 2 Webcam                                        | 2         | 1.44%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.44%   |
| Microdia Integrated_Webcam_HD                               | 2         | 1.44%   |
| Lenovo Integrated Webcam                                    | 2         | 1.44%   |
| Chicony ThinkPad T490 Webcam                                | 2         | 1.44%   |
| Chicony Ltd., Integrated Camera                             | 2         | 1.44%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.44%   |
| Chicony HD Webcam                                           | 2         | 1.44%   |
| Chicony FJ Camera                                           | 2         | 1.44%   |
| Apple FaceTime HD Camera                                    | 2         | 1.44%   |
| Acer SunplusIT Integrated Camera                            | 2         | 1.44%   |
| Acer Lenovo EasyCamera                                      | 2         | 1.44%   |
| Z-Star Integrated Camera                                    | 1         | 0.72%   |
| Syntek EasyCamera                                           | 1         | 0.72%   |
| Suyin Asus Integrated Webcam                                | 1         | 0.72%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 0.72%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.72%   |
| Sunplus Integrated_Webcam_FHD                               | 1         | 0.72%   |
| Sunplus Dell E5570 integrated webcam                        | 1         | 0.72%   |
| Silicon Motion WebCam SC-10IRQ12340N                        | 1         | 0.72%   |
| Silicon Motion Web Camera                                   | 1         | 0.72%   |
| Silicon Motion Realtek USB2.0 PC Camera                     | 1         | 0.72%   |
| Ricoh USB2.0 Camera                                         | 1         | 0.72%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 0.72%   |
| Ricoh Integrated Webcam                                     | 1         | 0.72%   |
| Realtek USB2.0 HD UVC WebCam                                | 1         | 0.72%   |
| Realtek Integrated Webcam                                   | 1         | 0.72%   |
| Realtek EasyCamera                                          | 1         | 0.72%   |
| Realtek Acer 640 x 480 laptop camera                        | 1         | 0.72%   |
| Quanta VGA WebCam                                           | 1         | 0.72%   |
| Quanta HP Webcam-50                                         | 1         | 0.72%   |
| Quanta HP TrueVision HD Camera                              | 1         | 0.72%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 0.72%   |
| Microdia PC Camera (SN9C201 + OV9650)                       | 1         | 0.72%   |
| Microdia Ltd., USB  Live camera                             | 1         | 0.72%   |
| Microdia Integrated Webcam HD                               | 1         | 0.72%   |
| Microdia Integrated Webcam                                  | 1         | 0.72%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 0.72%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera        | 1         | 0.72%   |
| Logitech Webcam C310                                        | 1         | 0.72%   |
| Logitech Webcam C270                                        | 1         | 0.72%   |
| Logitech HD Pro Webcam C920                                 | 1         | 0.72%   |
| Logitech C920 HD Pro Webcam                                 | 1         | 0.72%   |
| Logitech BRIO Ultra HD Webcam                               | 1         | 0.72%   |
| IMC Networks VGA UVC WebCam                                 | 1         | 0.72%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 1         | 0.72%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 0.72%   |
| IMC Networks Lenovo EasyCamera                              | 1         | 0.72%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 0.72%   |
| IMC Networks EasyCamera                                     | 1         | 0.72%   |
| Denron Corp., 2M Front Camera                               | 1         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 33.33%  |
| Upek                       | 8         | 16.67%  |
| Synaptics                  | 7         | 14.58%  |
| STMicroelectronics         | 6         | 12.5%   |
| AuthenTec                  | 6         | 12.5%   |
| Shenzhen Goodix Technology | 3         | 6.25%   |
| Samsung Electronics        | 1         | 2.08%   |
| Elan Microelectronics      | 1         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 12        | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 8         | 16.67%  |
| STMicroelectronics Fingerprint Reader                  | 6         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 3         | 6.25%   |
| AuthenTec AES2810                                      | 3         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 4.17%   |
| Validity Sensors Synaptics WBDI                        | 2         | 4.17%   |
| Synaptics product 0x00be                               | 2         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 4.17%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 4.17%   |
| Synaptics  WBDI                                        | 1         | 2.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.08%   |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 2.08%   |
| Samsung Fingerprint Device                             | 1         | 2.08%   |
| Elan ELAN WBF Fingerprint Sensor                       | 1         | 2.08%   |
| AuthenTec AuthenTec Inc. AES2660                       | 1         | 2.08%   |

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
| 1     | 171       | 39.86%  |
| 0     | 131       | 30.54%  |
| 2     | 90        | 20.98%  |
| 3     | 16        | 3.73%   |
| 4     | 11        | 2.56%   |
| 5     | 4         | 0.93%   |
| 7     | 3         | 0.7%    |
| 6     | 2         | 0.47%   |
| 8     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 219       | 49.44%  |
| Graphics card            | 80        | 18.06%  |
| Net/wireless             | 46        | 10.38%  |
| Firewire controller      | 38        | 8.58%   |
| Sound                    | 15        | 3.39%   |
| Storage/ata              | 11        | 2.48%   |
| Net/ethernet             | 11        | 2.48%   |
| Network                  | 7         | 1.58%   |
| Modem                    | 7         | 1.58%   |
| Storage/ide              | 2         | 0.45%   |
| Storage                  | 2         | 0.45%   |
| Card reader              | 2         | 0.45%   |
| Storage/raid             | 1         | 0.23%   |
| Storage/nvme             | 1         | 0.23%   |
| Bluetooth                | 1         | 0.23%   |

