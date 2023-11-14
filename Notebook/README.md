BSD - Tested Hardware & Statistics (Notebooks)
----------------------------------------------

A project to collect tested hardware configurations for BSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This report is for real hardware. Report for virtual hardware: [TestDays_VE](https://github.com/bsdhw/TestDays_VE)

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

Total: 4042

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude E6540              | [a26912fd0d](https://bsd-hardware.info/?probe=a26912fd0d) | Nov 06, 2023 |
| Dell          | Inspiron N4050              | [9bc3c5e163](https://bsd-hardware.info/?probe=9bc3c5e163) | Nov 05, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [4f9885c454](https://bsd-hardware.info/?probe=4f9885c454) | Nov 05, 2023 |
| ASUSTek       | K56CB                       | [7d6d03a42b](https://bsd-hardware.info/?probe=7d6d03a42b) | Nov 05, 2023 |
| Dell          | Precision 7720              | [ef59e0f80d](https://bsd-hardware.info/?probe=ef59e0f80d) | Nov 05, 2023 |
| Lenovo        | Z50-70 20354                | [641e875b3b](https://bsd-hardware.info/?probe=641e875b3b) | Nov 04, 2023 |
| Dell          | XPS 13 9360                 | [c7d016caa9](https://bsd-hardware.info/?probe=c7d016caa9) | Nov 04, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [a9448cf3b5](https://bsd-hardware.info/?probe=a9448cf3b5) | Nov 04, 2023 |
| LG Electro... | 16UD70R-G.AX59B             | [a7df4f645f](https://bsd-hardware.info/?probe=a7df4f645f) | Nov 04, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [19514dd0bd](https://bsd-hardware.info/?probe=19514dd0bd) | Nov 03, 2023 |
| Dell          | Inspiron 1525               | [538444f1d2](https://bsd-hardware.info/?probe=538444f1d2) | Nov 02, 2023 |
| Dell          | Precision 7720              | [cc321f8dea](https://bsd-hardware.info/?probe=cc321f8dea) | Nov 01, 2023 |
| Apple         | MacBookPro7,1               | [91d07ef080](https://bsd-hardware.info/?probe=91d07ef080) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480 20L5000WUS    | [4dcf84c76c](https://bsd-hardware.info/?probe=4dcf84c76c) | Oct 31, 2023 |
| Shuttle       | DS437                       | [45c2e3460c](https://bsd-hardware.info/?probe=45c2e3460c) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | [32b7f19d78](https://bsd-hardware.info/?probe=32b7f19d78) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | [522298f90a](https://bsd-hardware.info/?probe=522298f90a) | Oct 29, 2023 |
| TUXEDO        | Aura 15 Gen1                | [7a6b4537f3](https://bsd-hardware.info/?probe=7a6b4537f3) | Oct 29, 2023 |
| HP            | Pavilion g6                 | [6aee98fb1a](https://bsd-hardware.info/?probe=6aee98fb1a) | Oct 29, 2023 |
| Dell          | Vostro 3500                 | [875b045b38](https://bsd-hardware.info/?probe=875b045b38) | Oct 29, 2023 |
| HP            | ZBook 15 G3                 | [74c3cbd1a3](https://bsd-hardware.info/?probe=74c3cbd1a3) | Oct 29, 2023 |
| Lenovo        | Z50-70 20354                | [f3d9534b2d](https://bsd-hardware.info/?probe=f3d9534b2d) | Oct 28, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | [e6aca7e0c8](https://bsd-hardware.info/?probe=e6aca7e0c8) | Oct 28, 2023 |
| Toshiba       | Satellite P300              | [49d23c8fda](https://bsd-hardware.info/?probe=49d23c8fda) | Oct 28, 2023 |
| Toshiba       | Satellite P300              | [a133633304](https://bsd-hardware.info/?probe=a133633304) | Oct 28, 2023 |
| Lenovo        | ThinkPad X230 23205UG       | [f204abc5fc](https://bsd-hardware.info/?probe=f204abc5fc) | Oct 28, 2023 |
| Deciso        | OPNsense Appliance          | [9508bd06f5](https://bsd-hardware.info/?probe=9508bd06f5) | Oct 28, 2023 |
| IBM           | ThinkPad R51 2889W11        | [26d2e55032](https://bsd-hardware.info/?probe=26d2e55032) | Oct 28, 2023 |
| Datto         | Unknown                     | [8b59510085](https://bsd-hardware.info/?probe=8b59510085) | Oct 27, 2023 |
| Panasonic     | CF-C2CEAZXCM                | [a871fb0596](https://bsd-hardware.info/?probe=a871fb0596) | Oct 27, 2023 |
| Lenovo        | ThinkPad X270 20HN006CUS    | [aa85ff898d](https://bsd-hardware.info/?probe=aa85ff898d) | Oct 26, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [09cf753c7a](https://bsd-hardware.info/?probe=09cf753c7a) | Oct 26, 2023 |
| Deciso        | NetBoard-A10                | [d0ee609c75](https://bsd-hardware.info/?probe=d0ee609c75) | Oct 25, 2023 |
| Toshiba       | Unknown                     | [de44a16738](https://bsd-hardware.info/?probe=de44a16738) | Oct 24, 2023 |
| Lenovo        | G50-30 80G0                 | [e2dad0b43a](https://bsd-hardware.info/?probe=e2dad0b43a) | Oct 24, 2023 |
| Deciso        | OPNsense Appliance          | [d9f0644c56](https://bsd-hardware.info/?probe=d9f0644c56) | Oct 24, 2023 |
| Lenovo        | ThinkPad T490 20N3X50500    | [364c7828be](https://bsd-hardware.info/?probe=364c7828be) | Oct 24, 2023 |
| Panasonic     | CF-52PFPBSFQ                | [4a97ab307a](https://bsd-hardware.info/?probe=4a97ab307a) | Oct 22, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [1f76a6c28c](https://bsd-hardware.info/?probe=1f76a6c28c) | Oct 22, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [6569410f91](https://bsd-hardware.info/?probe=6569410f91) | Oct 22, 2023 |
| Seco          | UDOO x86                    | [260f8194ed](https://bsd-hardware.info/?probe=260f8194ed) | Oct 22, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | [88ae89f787](https://bsd-hardware.info/?probe=88ae89f787) | Oct 22, 2023 |
| Panasonic     | CF-53AAGHYDM                | [6f29731875](https://bsd-hardware.info/?probe=6f29731875) | Oct 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [7a57e0a112](https://bsd-hardware.info/?probe=7a57e0a112) | Oct 21, 2023 |
| ASUSTek       | 1000HE                      | [249959fd2c](https://bsd-hardware.info/?probe=249959fd2c) | Oct 21, 2023 |
| Matsushita... | CF-51RCVDNLM                | [ec5aff8b6b](https://bsd-hardware.info/?probe=ec5aff8b6b) | Oct 21, 2023 |
| Matsushita... | CF-48V4KNDQM                | [625f272fcd](https://bsd-hardware.info/?probe=625f272fcd) | Oct 21, 2023 |
| HP            | Laptop 15s-eq3xxx           | [5a7e4222f1](https://bsd-hardware.info/?probe=5a7e4222f1) | Oct 21, 2023 |
| ASUSTek       | N73SV                       | [31fff3e92b](https://bsd-hardware.info/?probe=31fff3e92b) | Oct 21, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [e4b35a3ff6](https://bsd-hardware.info/?probe=e4b35a3ff6) | Oct 21, 2023 |
| Dell          | G16 7630                    | [deb5f3bd32](https://bsd-hardware.info/?probe=deb5f3bd32) | Oct 21, 2023 |
| ASUSTek       | N73SV                       | [30726f25a0](https://bsd-hardware.info/?probe=30726f25a0) | Oct 21, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [965e71ac80](https://bsd-hardware.info/?probe=965e71ac80) | Oct 21, 2023 |
| Dell          | Latitude 5490               | [eeab525ffd](https://bsd-hardware.info/?probe=eeab525ffd) | Oct 20, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | [fd75aab1c6](https://bsd-hardware.info/?probe=fd75aab1c6) | Oct 20, 2023 |
| Panasonic     | CFSX4-1                     | [d3ad63aa13](https://bsd-hardware.info/?probe=d3ad63aa13) | Oct 19, 2023 |
| Unknown       | Unknown                     | [363b63c1a1](https://bsd-hardware.info/?probe=363b63c1a1) | Oct 18, 2023 |
| Acer          | Aspire 5336                 | [ebfed0efbc](https://bsd-hardware.info/?probe=ebfed0efbc) | Oct 18, 2023 |
| Intel         | H81U                        | [9ed05368b5](https://bsd-hardware.info/?probe=9ed05368b5) | Oct 18, 2023 |
| Dell          | Inspiron 5559               | [0ae4cee8b3](https://bsd-hardware.info/?probe=0ae4cee8b3) | Oct 17, 2023 |
| Unknown       | Unknown                     | [ea04f97748](https://bsd-hardware.info/?probe=ea04f97748) | Oct 17, 2023 |
| Apple         | MacBook5,2                  | [5f364ec930](https://bsd-hardware.info/?probe=5f364ec930) | Oct 17, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b08dc9fc91](https://bsd-hardware.info/?probe=b08dc9fc91) | Oct 16, 2023 |
| Dell          | Latitude 3440               | [3e6826570c](https://bsd-hardware.info/?probe=3e6826570c) | Oct 16, 2023 |
| ASUSTek       | N552VX                      | [f927cf5ba4](https://bsd-hardware.info/?probe=f927cf5ba4) | Oct 16, 2023 |
| ASUSTek       | X455LD                      | [e61ce1bc9a](https://bsd-hardware.info/?probe=e61ce1bc9a) | Oct 15, 2023 |
| Acer          | Aspire E5-575G              | [f38d89e6c0](https://bsd-hardware.info/?probe=f38d89e6c0) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [20fe904881](https://bsd-hardware.info/?probe=20fe904881) | Oct 15, 2023 |
| Acer          | Aspire E5-575G              | [0aa91c2a5c](https://bsd-hardware.info/?probe=0aa91c2a5c) | Oct 15, 2023 |
| Fujitsu       | LIFEBOOK E744               | [72a9b731f6](https://bsd-hardware.info/?probe=72a9b731f6) | Oct 14, 2023 |
| Deciso        | Netboard A20                | [879efbe255](https://bsd-hardware.info/?probe=879efbe255) | Oct 14, 2023 |
| Deciso        | NetBoard-A20                | [7ed49c5f2f](https://bsd-hardware.info/?probe=7ed49c5f2f) | Oct 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0f3cd5aa25](https://bsd-hardware.info/?probe=0f3cd5aa25) | Oct 13, 2023 |
| ASUSTek       | X455LD                      | [b1a7a3f656](https://bsd-hardware.info/?probe=b1a7a3f656) | Oct 13, 2023 |
| Acer          | Aspire ES1-571              | [f3036a27e5](https://bsd-hardware.info/?probe=f3036a27e5) | Oct 13, 2023 |
| IBM           | ThinkPad R51 2889W11        | [45836fafc3](https://bsd-hardware.info/?probe=45836fafc3) | Oct 12, 2023 |
| Toshiba       | Satellite C55-A             | [f27ea283cf](https://bsd-hardware.info/?probe=f27ea283cf) | Oct 12, 2023 |
| Lenovo        | ThinkPad X250 20CM004VFR    | [e4ab2acd8d](https://bsd-hardware.info/?probe=e4ab2acd8d) | Oct 11, 2023 |
| Lenovo        | G550 2958                   | [6dfadd1ff2](https://bsd-hardware.info/?probe=6dfadd1ff2) | Oct 11, 2023 |
| Apple         | MacBook5,1                  | [518658e176](https://bsd-hardware.info/?probe=518658e176) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | [c88d8880ea](https://bsd-hardware.info/?probe=c88d8880ea) | Oct 11, 2023 |
| ASUSTek       | K45VM                       | [054a6c3902](https://bsd-hardware.info/?probe=054a6c3902) | Oct 11, 2023 |
| Dell          | Precision 7550              | [a21e06c16c](https://bsd-hardware.info/?probe=a21e06c16c) | Oct 11, 2023 |
| Deciso        | NetBoard-A20                | [b9c11f29c9](https://bsd-hardware.info/?probe=b9c11f29c9) | Oct 10, 2023 |
| Deciso        | NetBoard-A10                | [12b5a57360](https://bsd-hardware.info/?probe=12b5a57360) | Oct 10, 2023 |
| Deciso        | NetBoard-A20                | [ddffd0a126](https://bsd-hardware.info/?probe=ddffd0a126) | Oct 10, 2023 |
| Unknown       | Unknown                     | [9c6c7f9d6b](https://bsd-hardware.info/?probe=9c6c7f9d6b) | Oct 10, 2023 |
| Dell          | Latitude D830               | [4cf27e5d29](https://bsd-hardware.info/?probe=4cf27e5d29) | Oct 09, 2023 |
| Dell          | Inspiron 13 5320            | [43c1b405d0](https://bsd-hardware.info/?probe=43c1b405d0) | Oct 09, 2023 |
| Unknown       | Unknown                     | [57e5ab8786](https://bsd-hardware.info/?probe=57e5ab8786) | Oct 08, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [b192196423](https://bsd-hardware.info/?probe=b192196423) | Oct 08, 2023 |
| Dell          | Vostro 3700                 | [8262e3923f](https://bsd-hardware.info/?probe=8262e3923f) | Oct 08, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [5be3eb1296](https://bsd-hardware.info/?probe=5be3eb1296) | Oct 08, 2023 |
| Unknown       | Unknown                     | [1f7ab105e3](https://bsd-hardware.info/?probe=1f7ab105e3) | Oct 08, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [0aac5f52c9](https://bsd-hardware.info/?probe=0aac5f52c9) | Oct 08, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [36daf066ca](https://bsd-hardware.info/?probe=36daf066ca) | Oct 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [c646a3b663](https://bsd-hardware.info/?probe=c646a3b663) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | [ac6742bd0f](https://bsd-hardware.info/?probe=ac6742bd0f) | Oct 07, 2023 |
| Timi          | A34R                        | [3cd3f35eaa](https://bsd-hardware.info/?probe=3cd3f35eaa) | Oct 07, 2023 |
| Timi          | A34R                        | [03f00603f7](https://bsd-hardware.info/?probe=03f00603f7) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | [3e15173331](https://bsd-hardware.info/?probe=3e15173331) | Oct 07, 2023 |
| Apple         | MacBookPro6,2               | [85e94bd511](https://bsd-hardware.info/?probe=85e94bd511) | Oct 06, 2023 |
| Deciso        | Netboard A20                | [c549fc9540](https://bsd-hardware.info/?probe=c549fc9540) | Oct 05, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [88e8c64b6f](https://bsd-hardware.info/?probe=88e8c64b6f) | Oct 04, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [aecfeaa518](https://bsd-hardware.info/?probe=aecfeaa518) | Oct 04, 2023 |
| ASUSTek       | K73E                        | [ce5fcbdc3e](https://bsd-hardware.info/?probe=ce5fcbdc3e) | Oct 04, 2023 |
| Lenovo        | ThinkPad X230 2325J67       | [bfbc6beca8](https://bsd-hardware.info/?probe=bfbc6beca8) | Oct 04, 2023 |
| Dell          | Latitude 5591               | [8f6ca1e82a](https://bsd-hardware.info/?probe=8f6ca1e82a) | Oct 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [25fecdaad5](https://bsd-hardware.info/?probe=25fecdaad5) | Oct 03, 2023 |
| HP            | ZBook 17 G2                 | [4e12d36770](https://bsd-hardware.info/?probe=4e12d36770) | Oct 03, 2023 |
| Lenovo        | B40-30 80F1                 | [00c5e6adda](https://bsd-hardware.info/?probe=00c5e6adda) | Oct 03, 2023 |
| Platform      | ARB938                      | [141d043221](https://bsd-hardware.info/?probe=141d043221) | Oct 02, 2023 |
| Google        | Auron_Paine                 | [d202b4dd6f](https://bsd-hardware.info/?probe=d202b4dd6f) | Oct 02, 2023 |
| Google        | Auron_Paine                 | [1c44cf70e8](https://bsd-hardware.info/?probe=1c44cf70e8) | Oct 02, 2023 |
| Apple         | MacBookPro7,1               | [070c5dab4f](https://bsd-hardware.info/?probe=070c5dab4f) | Oct 02, 2023 |
| ASUSTek       | K40IN                       | [6b58792f5e](https://bsd-hardware.info/?probe=6b58792f5e) | Oct 02, 2023 |
| Deciso        | NetBoard-A10                | [5524017014](https://bsd-hardware.info/?probe=5524017014) | Oct 01, 2023 |
| Apple         | MacBookPro9,1               | [9b9f826560](https://bsd-hardware.info/?probe=9b9f826560) | Oct 01, 2023 |
| Google        | Auron_Paine                 | [021624028a](https://bsd-hardware.info/?probe=021624028a) | Oct 01, 2023 |
| Dell          | Inspiron 5559               | [7a6b97e997](https://bsd-hardware.info/?probe=7a6b97e997) | Oct 01, 2023 |
| Acer          | TravelMate 5730             | [dffc2e116d](https://bsd-hardware.info/?probe=dffc2e116d) | Sep 30, 2023 |
| Unknown       | Unknown                     | [7cfd3d40eb](https://bsd-hardware.info/?probe=7cfd3d40eb) | Sep 30, 2023 |
| Deciso        | Netboard A20                | [3877143e37](https://bsd-hardware.info/?probe=3877143e37) | Sep 29, 2023 |
| ASUSTek       | 1005PXD                     | [1b05e8cf1b](https://bsd-hardware.info/?probe=1b05e8cf1b) | Sep 29, 2023 |
| Apple         | MacBookPro9,1               | [b0aca42c84](https://bsd-hardware.info/?probe=b0aca42c84) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | [68b8b9f531](https://bsd-hardware.info/?probe=68b8b9f531) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | [e732d89b06](https://bsd-hardware.info/?probe=e732d89b06) | Sep 29, 2023 |
| Apple         | MacBookPro7,1               | [714516a696](https://bsd-hardware.info/?probe=714516a696) | Sep 29, 2023 |
| Apple         | MacBookPro9,1               | [cac0950717](https://bsd-hardware.info/?probe=cac0950717) | Sep 29, 2023 |
| ASUSTek       | K40IN                       | [3c69dd7003](https://bsd-hardware.info/?probe=3c69dd7003) | Sep 29, 2023 |
| ASUSTek       | K40IN                       | [f98d4be34d](https://bsd-hardware.info/?probe=f98d4be34d) | Sep 29, 2023 |
| Dell          | Latitude 5591               | [c30943def8](https://bsd-hardware.info/?probe=c30943def8) | Sep 28, 2023 |
| Dell          | Latitude E6430              | [bec165c243](https://bsd-hardware.info/?probe=bec165c243) | Sep 27, 2023 |
| Panasonic     | CFSX4-1                     | [86abd76c4e](https://bsd-hardware.info/?probe=86abd76c4e) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HHC... | [74d0396f87](https://bsd-hardware.info/?probe=74d0396f87) | Sep 27, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [0c56aeb6b5](https://bsd-hardware.info/?probe=0c56aeb6b5) | Sep 27, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [231aedbf9e](https://bsd-hardware.info/?probe=231aedbf9e) | Sep 25, 2023 |
| Dell          | Latitude 3410               | [1bd71b0bf0](https://bsd-hardware.info/?probe=1bd71b0bf0) | Sep 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | [b31f8c12f8](https://bsd-hardware.info/?probe=b31f8c12f8) | Sep 24, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [5cd50ed5b5](https://bsd-hardware.info/?probe=5cd50ed5b5) | Sep 24, 2023 |
| GPD           | G1619-04                    | [30ad9b72b5](https://bsd-hardware.info/?probe=30ad9b72b5) | Sep 23, 2023 |
| Intel         | Milstead Platform           | [04e544d5f1](https://bsd-hardware.info/?probe=04e544d5f1) | Sep 22, 2023 |
| Dell          | Latitude E7470              | [11cf3b211c](https://bsd-hardware.info/?probe=11cf3b211c) | Sep 22, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [de1bdf0601](https://bsd-hardware.info/?probe=de1bdf0601) | Sep 21, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [8a3d3b3d0d](https://bsd-hardware.info/?probe=8a3d3b3d0d) | Sep 21, 2023 |
| Dell          | G16 7630                    | [4e39a5ebdf](https://bsd-hardware.info/?probe=4e39a5ebdf) | Sep 21, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | [a1945198c6](https://bsd-hardware.info/?probe=a1945198c6) | Sep 21, 2023 |
| Panasonic     | CFSX4-1                     | [398d7a6f26](https://bsd-hardware.info/?probe=398d7a6f26) | Sep 20, 2023 |
| HP            | ZBook 17 G2                 | [f29233649e](https://bsd-hardware.info/?probe=f29233649e) | Sep 20, 2023 |
| Dell          | XPS 13 7390                 | [6bb6186f22](https://bsd-hardware.info/?probe=6bb6186f22) | Sep 19, 2023 |
| Lenovo        | ThinkPad L390 20NRS00Q00    | [b9885ea126](https://bsd-hardware.info/?probe=b9885ea126) | Sep 17, 2023 |
| Lenovo        | ThinkPad T470 20HES0HU00    | [a64fe205a9](https://bsd-hardware.info/?probe=a64fe205a9) | Sep 17, 2023 |
| Unknown       | Unknown                     | [5aebf0e729](https://bsd-hardware.info/?probe=5aebf0e729) | Sep 16, 2023 |
| Lenovo        | ThinkPad T480s 20L7S24F0... | [bb7eb8b380](https://bsd-hardware.info/?probe=bb7eb8b380) | Sep 15, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| Deciso        | NetBoard-A20                | [0c65fb5e8c](https://bsd-hardware.info/?probe=0c65fb5e8c) | Sep 15, 2023 |
| Dell          | XPS 9320                    | [d80b3d5a54](https://bsd-hardware.info/?probe=d80b3d5a54) | Sep 14, 2023 |
| Dell          | Latitude E6420              | [b90b748742](https://bsd-hardware.info/?probe=b90b748742) | Sep 14, 2023 |
| eMachines     | G640                        | [c05619033c](https://bsd-hardware.info/?probe=c05619033c) | Sep 14, 2023 |
| Platform      | ARB938                      | [17b7c850c4](https://bsd-hardware.info/?probe=17b7c850c4) | Sep 14, 2023 |
| Alienware     | m15                         | [609d2ce1ce](https://bsd-hardware.info/?probe=609d2ce1ce) | Sep 14, 2023 |
| HP            | Pavilion dv5                | [b7dad77d0d](https://bsd-hardware.info/?probe=b7dad77d0d) | Sep 14, 2023 |
| Deciso        | NetBoard-A10                | [0068732d33](https://bsd-hardware.info/?probe=0068732d33) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | [03a8809fe4](https://bsd-hardware.info/?probe=03a8809fe4) | Sep 13, 2023 |
| ASUSTek       | N751JK                      | [67d1f42d7c](https://bsd-hardware.info/?probe=67d1f42d7c) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | [7ba189ff8a](https://bsd-hardware.info/?probe=7ba189ff8a) | Sep 13, 2023 |
| OEGStone      | doceo 510                   | [9f3b47e30f](https://bsd-hardware.info/?probe=9f3b47e30f) | Sep 13, 2023 |
| HP            | ProBook 4530s               | [0b47c15c42](https://bsd-hardware.info/?probe=0b47c15c42) | Sep 12, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [54b04ea958](https://bsd-hardware.info/?probe=54b04ea958) | Sep 12, 2023 |
| HP            | ProBook 4530s               | [4b6daa1f1c](https://bsd-hardware.info/?probe=4b6daa1f1c) | Sep 12, 2023 |
| HP            | Mini 110-3100               | [14f75b6704](https://bsd-hardware.info/?probe=14f75b6704) | Sep 11, 2023 |
| HP            | ZBook 17 G2                 | [e2d694053a](https://bsd-hardware.info/?probe=e2d694053a) | Sep 10, 2023 |
| Acer          | Monserrat                   | [9c79dbac8b](https://bsd-hardware.info/?probe=9c79dbac8b) | Sep 10, 2023 |
| Acer          | AOHAPPY2                    | [d615a8daba](https://bsd-hardware.info/?probe=d615a8daba) | Sep 10, 2023 |
| Acer          | AOHAPPY2                    | [6f5db06303](https://bsd-hardware.info/?probe=6f5db06303) | Sep 10, 2023 |
| HP            | OMEN by Laptop              | [f0fc4f47b8](https://bsd-hardware.info/?probe=f0fc4f47b8) | Sep 10, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3LR0... | [cbac96a24f](https://bsd-hardware.info/?probe=cbac96a24f) | Sep 09, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [252fc12d3b](https://bsd-hardware.info/?probe=252fc12d3b) | Sep 09, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [0f92b89ffb](https://bsd-hardware.info/?probe=0f92b89ffb) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [d331bd9a11](https://bsd-hardware.info/?probe=d331bd9a11) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | [d9d6fc45f8](https://bsd-hardware.info/?probe=d9d6fc45f8) | Sep 08, 2023 |
| HP            | Pavilion g7                 | [4870da3b0e](https://bsd-hardware.info/?probe=4870da3b0e) | Sep 07, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | [2e6af170b9](https://bsd-hardware.info/?probe=2e6af170b9) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [cbde759aa2](https://bsd-hardware.info/?probe=cbde759aa2) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [22ec8197cc](https://bsd-hardware.info/?probe=22ec8197cc) | Sep 07, 2023 |
| Apple         | MacBookPro9,2               | [e011df1d78](https://bsd-hardware.info/?probe=e011df1d78) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [68efc7ef8d](https://bsd-hardware.info/?probe=68efc7ef8d) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [f42dfa2992](https://bsd-hardware.info/?probe=f42dfa2992) | Sep 06, 2023 |
| Unknown       | Unknown                     | [516b89740b](https://bsd-hardware.info/?probe=516b89740b) | Sep 06, 2023 |
| Unknown       | Unknown                     | [084127fd8b](https://bsd-hardware.info/?probe=084127fd8b) | Sep 06, 2023 |
| LG Electro... | 16U70Q-K.AAS7U1             | [82e3b2e5f8](https://bsd-hardware.info/?probe=82e3b2e5f8) | Sep 06, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [67e9eafa7e](https://bsd-hardware.info/?probe=67e9eafa7e) | Sep 05, 2023 |
| Lenovo        | ThinkPad X240 20AMA1Y3UK    | [8277297743](https://bsd-hardware.info/?probe=8277297743) | Sep 05, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [00dd1bd84e](https://bsd-hardware.info/?probe=00dd1bd84e) | Sep 04, 2023 |
| HP            | G62                         | [b4777b6ba5](https://bsd-hardware.info/?probe=b4777b6ba5) | Sep 04, 2023 |
| HP            | EliteBook 8570p             | [cfecf51114](https://bsd-hardware.info/?probe=cfecf51114) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| ASUSTek       | K40IN                       | [00a4f6e5a0](https://bsd-hardware.info/?probe=00a4f6e5a0) | Sep 04, 2023 |
| Shuttle       | DS67U                       | [55c2922a25](https://bsd-hardware.info/?probe=55c2922a25) | Sep 04, 2023 |
| Samsung       | 270E5J/2570EJ               | [3feb685296](https://bsd-hardware.info/?probe=3feb685296) | Sep 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [e4f0ac6bb9](https://bsd-hardware.info/?probe=e4f0ac6bb9) | Sep 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [4bce25bd89](https://bsd-hardware.info/?probe=4bce25bd89) | Sep 03, 2023 |
| HP            | EliteBook 8570p             | [d240fba8b7](https://bsd-hardware.info/?probe=d240fba8b7) | Sep 03, 2023 |
| ASUSTek       | 1005PXD                     | [8dac93d19d](https://bsd-hardware.info/?probe=8dac93d19d) | Sep 03, 2023 |
| ASUSTek       | K40IN                       | [df0a3f55c2](https://bsd-hardware.info/?probe=df0a3f55c2) | Sep 03, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | [9d1b9e7af6](https://bsd-hardware.info/?probe=9d1b9e7af6) | Sep 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [1bfe26df6e](https://bsd-hardware.info/?probe=1bfe26df6e) | Sep 02, 2023 |
| Fujitsu       | LIFEBOOK S935               | [a6cfe011fe](https://bsd-hardware.info/?probe=a6cfe011fe) | Sep 02, 2023 |
| Apple         | MacBookPro7,1               | [d49b8413db](https://bsd-hardware.info/?probe=d49b8413db) | Sep 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9b322dc202](https://bsd-hardware.info/?probe=9b322dc202) | Sep 02, 2023 |
| MSI           | CX62 6QD                    | [4356e5b30f](https://bsd-hardware.info/?probe=4356e5b30f) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [044910f579](https://bsd-hardware.info/?probe=044910f579) | Sep 01, 2023 |
| HP            | EliteBook 8540w             | [5e44dfed67](https://bsd-hardware.info/?probe=5e44dfed67) | Sep 01, 2023 |
| Deciso        | NetBoard-A10                | [f95d1da00c](https://bsd-hardware.info/?probe=f95d1da00c) | Sep 01, 2023 |
| Panasonic     | CFSX4-1                     | [8f54654916](https://bsd-hardware.info/?probe=8f54654916) | Sep 01, 2023 |
| HP            | 2000                        | [6d9c442ae6](https://bsd-hardware.info/?probe=6d9c442ae6) | Aug 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [0ebdda5146](https://bsd-hardware.info/?probe=0ebdda5146) | Aug 31, 2023 |
| Deciso        | NetBoard-A20                | [bf4ed827a5](https://bsd-hardware.info/?probe=bf4ed827a5) | Aug 31, 2023 |
| Acer          | Aspire A515-55              | [fcbd8a3f31](https://bsd-hardware.info/?probe=fcbd8a3f31) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [a308c3a87b](https://bsd-hardware.info/?probe=a308c3a87b) | Aug 31, 2023 |
| Deciso        | NetBoard-A20                | [0119402f80](https://bsd-hardware.info/?probe=0119402f80) | Aug 30, 2023 |
| Toshiba       | Satellite S55t-B            | [c2ed5fa6bd](https://bsd-hardware.info/?probe=c2ed5fa6bd) | Aug 30, 2023 |
| Dell          | Latitude E4310              | [7645de3654](https://bsd-hardware.info/?probe=7645de3654) | Aug 30, 2023 |
| HP            | EliteBook 8570p             | [0dda7a609c](https://bsd-hardware.info/?probe=0dda7a609c) | Aug 29, 2023 |
| HP            | Pavilion dv3500             | [0c3f84b285](https://bsd-hardware.info/?probe=0c3f84b285) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| Fujitsu       | FMVA0803D                   | [36528b957c](https://bsd-hardware.info/?probe=36528b957c) | Aug 28, 2023 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [978cd1d6bc](https://bsd-hardware.info/?probe=978cd1d6bc) | Aug 28, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [f0fb53394d](https://bsd-hardware.info/?probe=f0fb53394d) | Aug 28, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [dc8ad6c7c5](https://bsd-hardware.info/?probe=dc8ad6c7c5) | Aug 28, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [c8c17a9db2](https://bsd-hardware.info/?probe=c8c17a9db2) | Aug 28, 2023 |
| Toshiba       | Satellite S55t-B            | [eb85f0b975](https://bsd-hardware.info/?probe=eb85f0b975) | Aug 27, 2023 |
| Dell          | Latitude 7280               | [c858f191cf](https://bsd-hardware.info/?probe=c858f191cf) | Aug 27, 2023 |
| Lenovo        | ThinkPad X230 2325IB1       | [41fbf7d1ca](https://bsd-hardware.info/?probe=41fbf7d1ca) | Aug 26, 2023 |
| Fujitsu       | FMVA0803D                   | [8ce6118bf4](https://bsd-hardware.info/?probe=8ce6118bf4) | Aug 26, 2023 |
| IGEL Techn... | H830C                       | [da76c18be6](https://bsd-hardware.info/?probe=da76c18be6) | Aug 26, 2023 |
| IGEL Techn... | H830C                       | [9d25214ddb](https://bsd-hardware.info/?probe=9d25214ddb) | Aug 26, 2023 |
| Dell          | G5 5590                     | [2e496efada](https://bsd-hardware.info/?probe=2e496efada) | Aug 26, 2023 |
| Dell          | G5 5590                     | [fd4f457391](https://bsd-hardware.info/?probe=fd4f457391) | Aug 26, 2023 |
| HP            | ENVY Notebook 13-ab0XX      | [3d96f4d5b4](https://bsd-hardware.info/?probe=3d96f4d5b4) | Aug 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c8e95f3772](https://bsd-hardware.info/?probe=c8e95f3772) | Aug 26, 2023 |
| Getac         | V110G2                      | [884803a6bd](https://bsd-hardware.info/?probe=884803a6bd) | Aug 25, 2023 |
| Dell          | Latitude E6420              | [a085ba3865](https://bsd-hardware.info/?probe=a085ba3865) | Aug 25, 2023 |
| NVN-ED01      | Unknown                     | [dba43e889a](https://bsd-hardware.info/?probe=dba43e889a) | Aug 25, 2023 |
| Lenovo        | ThinkPad P50 20EN0009MS     | [4b3fcfa17e](https://bsd-hardware.info/?probe=4b3fcfa17e) | Aug 25, 2023 |
| ASUSTek       | S500CA                      | [019366a664](https://bsd-hardware.info/?probe=019366a664) | Aug 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f1a43ebe23](https://bsd-hardware.info/?probe=f1a43ebe23) | Aug 24, 2023 |
| Deciso        | NetBoard-A20                | [e9e295eae3](https://bsd-hardware.info/?probe=e9e295eae3) | Aug 24, 2023 |
| Dell          | Inspiron 15-7568            | [9e555f0b24](https://bsd-hardware.info/?probe=9e555f0b24) | Aug 24, 2023 |
| Dell          | Latitude 7490               | [0b05de2297](https://bsd-hardware.info/?probe=0b05de2297) | Aug 24, 2023 |
| Datto         | Unknown                     | [418eab5eaa](https://bsd-hardware.info/?probe=418eab5eaa) | Aug 23, 2023 |
| ASUSTek       | N751JK                      | [3ac93594a2](https://bsd-hardware.info/?probe=3ac93594a2) | Aug 20, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | [c32aad1b1f](https://bsd-hardware.info/?probe=c32aad1b1f) | Aug 20, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | [5fefc051e1](https://bsd-hardware.info/?probe=5fefc051e1) | Aug 20, 2023 |
| MSI           | Sword 17 A11UD              | [4b101af84b](https://bsd-hardware.info/?probe=4b101af84b) | Aug 19, 2023 |
| Deciso        | NetBoard-A20                | [c38eb6b9bd](https://bsd-hardware.info/?probe=c38eb6b9bd) | Aug 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0UD0... | [3c3610a93f](https://bsd-hardware.info/?probe=3c3610a93f) | Aug 19, 2023 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0238ea2cab](https://bsd-hardware.info/?probe=0238ea2cab) | Aug 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [26995b5321](https://bsd-hardware.info/?probe=26995b5321) | Aug 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [27cf2b3e46](https://bsd-hardware.info/?probe=27cf2b3e46) | Aug 19, 2023 |
| Acer          | Aspire A515-56              | [301a7c7b63](https://bsd-hardware.info/?probe=301a7c7b63) | Aug 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1bc7f67754](https://bsd-hardware.info/?probe=1bc7f67754) | Aug 18, 2023 |
| ASUSTek       | N751JK                      | [3b430afdad](https://bsd-hardware.info/?probe=3b430afdad) | Aug 18, 2023 |
| ASUSTek       | N751JK                      | [66449212d1](https://bsd-hardware.info/?probe=66449212d1) | Aug 18, 2023 |
| Star Labs     | Lite                        | [eabab74d7b](https://bsd-hardware.info/?probe=eabab74d7b) | Aug 18, 2023 |
| Dell          | Latitude 5591               | [972da999fb](https://bsd-hardware.info/?probe=972da999fb) | Aug 18, 2023 |
| HP            | EliteBook 8570p             | [434ec73823](https://bsd-hardware.info/?probe=434ec73823) | Aug 18, 2023 |
| Dell          | Latitude 3420               | [0e171f3f87](https://bsd-hardware.info/?probe=0e171f3f87) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [9beb5f6126](https://bsd-hardware.info/?probe=9beb5f6126) | Aug 17, 2023 |
| ASUSTek       | X553MA                      | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| Acer          | Aspire A315-59              | [9a8ad54cd3](https://bsd-hardware.info/?probe=9a8ad54cd3) | Aug 16, 2023 |
| ASUSTek       | GL753VD                     | [8ccbffdd73](https://bsd-hardware.info/?probe=8ccbffdd73) | Aug 15, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [be7bd4b126](https://bsd-hardware.info/?probe=be7bd4b126) | Aug 15, 2023 |
| Lenovo        | ThinkPad T460p 20FXS06A1... | [378d093019](https://bsd-hardware.info/?probe=378d093019) | Aug 15, 2023 |
| ASUSTek       | N751JK                      | [664ee85747](https://bsd-hardware.info/?probe=664ee85747) | Aug 15, 2023 |
| Dell          | Latitude 5591               | [a599361016](https://bsd-hardware.info/?probe=a599361016) | Aug 13, 2023 |
| Unknown       | Unknown                     | [4176afcb0d](https://bsd-hardware.info/?probe=4176afcb0d) | Aug 13, 2023 |
| Fujitsu Si... | LIFEBOOK P1610              | [bb055a94f0](https://bsd-hardware.info/?probe=bb055a94f0) | Aug 12, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| MSI           | Modern 14 B11SBL            | [1e02b41824](https://bsd-hardware.info/?probe=1e02b41824) | Aug 12, 2023 |
| Lenovo        | ThinkPad T60 1951CZ1        | [46766bc381](https://bsd-hardware.info/?probe=46766bc381) | Aug 11, 2023 |
| ASUSTek       | N751JK                      | [46a6b88b33](https://bsd-hardware.info/?probe=46a6b88b33) | Aug 11, 2023 |
| ASUSTek       | 1001P                       | [ac53dba211](https://bsd-hardware.info/?probe=ac53dba211) | Aug 11, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [2db86b4dff](https://bsd-hardware.info/?probe=2db86b4dff) | Aug 11, 2023 |
| ASUSTek       | 1001P                       | [2424d8acdc](https://bsd-hardware.info/?probe=2424d8acdc) | Aug 11, 2023 |
| Acer          | Aspire V3-371               | [21c262aadb](https://bsd-hardware.info/?probe=21c262aadb) | Aug 09, 2023 |
| Acer          | Aspire V3-371               | [68bceee682](https://bsd-hardware.info/?probe=68bceee682) | Aug 09, 2023 |
| Notebook      | N7x0WU                      | [418b98798e](https://bsd-hardware.info/?probe=418b98798e) | Aug 09, 2023 |
| Notebook      | N7x0WU                      | [60d49b408a](https://bsd-hardware.info/?probe=60d49b408a) | Aug 09, 2023 |
| Apple         | MacBookAir4,2               | [b1c97a3a9d](https://bsd-hardware.info/?probe=b1c97a3a9d) | Aug 09, 2023 |
| MSI           | Modern 14 B11SBL            | [ba3ab230dc](https://bsd-hardware.info/?probe=ba3ab230dc) | Aug 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9693a5fc69](https://bsd-hardware.info/?probe=9693a5fc69) | Aug 08, 2023 |
| Apple         | MacBookAir4,2               | [4fdd124b61](https://bsd-hardware.info/?probe=4fdd124b61) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9c01814bdc](https://bsd-hardware.info/?probe=9c01814bdc) | Aug 07, 2023 |
| MSI           | Modern 14 B11SBL            | [48483213f9](https://bsd-hardware.info/?probe=48483213f9) | Aug 06, 2023 |
| Dell          | Inspiron 14-3467            | [5db7e9b7a1](https://bsd-hardware.info/?probe=5db7e9b7a1) | Aug 05, 2023 |
| Compaq        | Presario CQ-17              | [f97feb2db0](https://bsd-hardware.info/?probe=f97feb2db0) | Aug 04, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [b90e62e27d](https://bsd-hardware.info/?probe=b90e62e27d) | Aug 04, 2023 |
| Apple         | MacBookPro11,1              | [4a2c98005b](https://bsd-hardware.info/?probe=4a2c98005b) | Aug 04, 2023 |
| Samsung       | Q210                        | [2e25c6d2ec](https://bsd-hardware.info/?probe=2e25c6d2ec) | Aug 03, 2023 |
| Samsung       | Q210                        | [d3c5ab902d](https://bsd-hardware.info/?probe=d3c5ab902d) | Aug 03, 2023 |
| HP            | EliteBook 840 G5            | [6496fe0cfe](https://bsd-hardware.info/?probe=6496fe0cfe) | Aug 03, 2023 |
| Chuwi         | CoreBook X                  | [2854f97c81](https://bsd-hardware.info/?probe=2854f97c81) | Aug 01, 2023 |
| Unknown       | Unknown                     | [09d17597cf](https://bsd-hardware.info/?probe=09d17597cf) | Aug 01, 2023 |
| Unknown       | Unknown                     | [2a2e7a98e3](https://bsd-hardware.info/?probe=2a2e7a98e3) | Aug 01, 2023 |
| Deciso        | NetBoard-A10                | [65667b2f29](https://bsd-hardware.info/?probe=65667b2f29) | Aug 01, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | [1e372622c1](https://bsd-hardware.info/?probe=1e372622c1) | Jul 31, 2023 |
| Deciso        | NetBoard-A20                | [9bd5d8fd54](https://bsd-hardware.info/?probe=9bd5d8fd54) | Jul 31, 2023 |
| Lenovo        | ThinkPad X270 20HNA04GCD    | [6547f4a73b](https://bsd-hardware.info/?probe=6547f4a73b) | Jul 31, 2023 |
| Deciso        | NetBoard-A10                | [42fcdacbf7](https://bsd-hardware.info/?probe=42fcdacbf7) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| ASUSTek       | X555LD                      | [9c0c41b663](https://bsd-hardware.info/?probe=9c0c41b663) | Jul 30, 2023 |
| Acer          | Aspire E5-511               | [93faaaff91](https://bsd-hardware.info/?probe=93faaaff91) | Jul 30, 2023 |
| HP            | EliteBook 8570p             | [2619fadb11](https://bsd-hardware.info/?probe=2619fadb11) | Jul 29, 2023 |
| Fujitsu Si... | AMILO Li3710                | [7a5d32eb7f](https://bsd-hardware.info/?probe=7a5d32eb7f) | Jul 29, 2023 |
| HP            | Notebook                    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | [53e133857b](https://bsd-hardware.info/?probe=53e133857b) | Jul 29, 2023 |
| HP            | Pavilion g6                 | [bdd2349f1c](https://bsd-hardware.info/?probe=bdd2349f1c) | Jul 28, 2023 |
| Dell          | Latitude 5480               | [e1521ed9d2](https://bsd-hardware.info/?probe=e1521ed9d2) | Jul 26, 2023 |
| Dell          | Inspiron 3180               | [e97b5d9219](https://bsd-hardware.info/?probe=e97b5d9219) | Jul 25, 2023 |
| Lenovo        | ThinkPad T410 2522NP6       | [194b8efa98](https://bsd-hardware.info/?probe=194b8efa98) | Jul 25, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [1b3ba2b86a](https://bsd-hardware.info/?probe=1b3ba2b86a) | Jul 25, 2023 |
| Deciso        | Netboard A20                | [9030d92418](https://bsd-hardware.info/?probe=9030d92418) | Jul 25, 2023 |
| ASUSTek       | 1015PX                      | [b0745153e4](https://bsd-hardware.info/?probe=b0745153e4) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | [461ad23cc9](https://bsd-hardware.info/?probe=461ad23cc9) | Jul 24, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| Lenovo        | B590 20208                  | [ce1aade2c0](https://bsd-hardware.info/?probe=ce1aade2c0) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | [1ac1ddd084](https://bsd-hardware.info/?probe=1ac1ddd084) | Jul 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [173fe60308](https://bsd-hardware.info/?probe=173fe60308) | Jul 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [26e44ab6e6](https://bsd-hardware.info/?probe=26e44ab6e6) | Jul 23, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [020e17c2f8](https://bsd-hardware.info/?probe=020e17c2f8) | Jul 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [56fc67d3eb](https://bsd-hardware.info/?probe=56fc67d3eb) | Jul 22, 2023 |
| NOBLEX        | SF20BA                      | [a6a17eb5ca](https://bsd-hardware.info/?probe=a6a17eb5ca) | Jul 21, 2023 |
| Panasonic     | CF-F9JYFNDR                 | [be7b261f26](https://bsd-hardware.info/?probe=be7b261f26) | Jul 21, 2023 |
| HP            | EliteBook 8570p             | [9f4f71236e](https://bsd-hardware.info/?probe=9f4f71236e) | Jul 21, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BK0... | [01f4886e09](https://bsd-hardware.info/?probe=01f4886e09) | Jul 21, 2023 |
| Lenovo        | ThinkPad T520 42435GG       | [f3aa06579e](https://bsd-hardware.info/?probe=f3aa06579e) | Jul 20, 2023 |
| ASUSTek       | 900                         | [2e55f5d4cc](https://bsd-hardware.info/?probe=2e55f5d4cc) | Jul 20, 2023 |
| Acer          | Aspire 4736Z                | [bccf97f694](https://bsd-hardware.info/?probe=bccf97f694) | Jul 20, 2023 |
| Toshiba       | Satellite L655              | [67080aeb1d](https://bsd-hardware.info/?probe=67080aeb1d) | Jul 20, 2023 |
| Dell          | Precision 5550              | [4c9dd227a7](https://bsd-hardware.info/?probe=4c9dd227a7) | Jul 20, 2023 |
| ASUSTek       | 1015PX                      | [dc06c76cf9](https://bsd-hardware.info/?probe=dc06c76cf9) | Jul 19, 2023 |
| MSI           | Sword 17 A11UD              | [c9852c1ee3](https://bsd-hardware.info/?probe=c9852c1ee3) | Jul 19, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [5fcffa5bd6](https://bsd-hardware.info/?probe=5fcffa5bd6) | Jul 19, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [386a80104d](https://bsd-hardware.info/?probe=386a80104d) | Jul 19, 2023 |
| IBM           | ThinkPad T43 1871F1G        | [d6fbc6ebfb](https://bsd-hardware.info/?probe=d6fbc6ebfb) | Jul 18, 2023 |
| ASUSTek       | K42Jr                       | [256168572a](https://bsd-hardware.info/?probe=256168572a) | Jul 18, 2023 |
| Deciso        | NetBoard-A20                | [c4a85b9853](https://bsd-hardware.info/?probe=c4a85b9853) | Jul 18, 2023 |
| Samsung       | 100NZB                      | [5515e88fc1](https://bsd-hardware.info/?probe=5515e88fc1) | Jul 17, 2023 |
| Samsung       | RC530/RC730                 | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | [57b4bfc1bf](https://bsd-hardware.info/?probe=57b4bfc1bf) | Jul 17, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [826ba238d8](https://bsd-hardware.info/?probe=826ba238d8) | Jul 16, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [0273f2f271](https://bsd-hardware.info/?probe=0273f2f271) | Jul 16, 2023 |
| Lenovo        | B590 20208                  | [f734b93999](https://bsd-hardware.info/?probe=f734b93999) | Jul 16, 2023 |
| HP            | Laptop 15s-eq3xxx           | [ff4dbbacdf](https://bsd-hardware.info/?probe=ff4dbbacdf) | Jul 15, 2023 |
| Lenovo        | ThinkPad R14 Gen 4 21E5A... | [e0fc7135e5](https://bsd-hardware.info/?probe=e0fc7135e5) | Jul 15, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [d4265533e2](https://bsd-hardware.info/?probe=d4265533e2) | Jul 15, 2023 |
| HP            | EliteBook 6930p             | [12124d8753](https://bsd-hardware.info/?probe=12124d8753) | Jul 15, 2023 |
| Sony          | VPCX115KX                   | [9dab449a23](https://bsd-hardware.info/?probe=9dab449a23) | Jul 15, 2023 |
| Deciso        | Netboard A20                | [e82dfa5520](https://bsd-hardware.info/?probe=e82dfa5520) | Jul 14, 2023 |
| 10ZiG Tech... | 5900q                       | [3c3668fcd2](https://bsd-hardware.info/?probe=3c3668fcd2) | Jul 14, 2023 |
| Lenovo        | ThinkPad T470s 20HGS3AX0... | [785b9af1f4](https://bsd-hardware.info/?probe=785b9af1f4) | Jul 13, 2023 |
| Deciso        | NetBoard-A10                | [535720220a](https://bsd-hardware.info/?probe=535720220a) | Jul 13, 2023 |
| HP            | Laptop 14-cf2xxx            | [91965a9c00](https://bsd-hardware.info/?probe=91965a9c00) | Jul 13, 2023 |
| Lenovo        | G550 2958                   | [bc36695565](https://bsd-hardware.info/?probe=bc36695565) | Jul 13, 2023 |
| Tactus        | GeoBook 140                 | [4b7383c876](https://bsd-hardware.info/?probe=4b7383c876) | Jul 11, 2023 |
| HONOR         | NMH-WCX9                    | [f573d1d5c4](https://bsd-hardware.info/?probe=f573d1d5c4) | Jul 11, 2023 |
| ASUSTek       | X541UVK                     | [17f58b70e4](https://bsd-hardware.info/?probe=17f58b70e4) | Jul 10, 2023 |
| Getac         | F110G2                      | [b7b9efc38d](https://bsd-hardware.info/?probe=b7b9efc38d) | Jul 09, 2023 |
| Lenovo        | ThinkPad X250 20CLS13Q06    | [c318ab3cc7](https://bsd-hardware.info/?probe=c318ab3cc7) | Jul 09, 2023 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | [80ac9dddda](https://bsd-hardware.info/?probe=80ac9dddda) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [4274ca291e](https://bsd-hardware.info/?probe=4274ca291e) | Jul 08, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [7119cd7ae3](https://bsd-hardware.info/?probe=7119cd7ae3) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [03e83e60ca](https://bsd-hardware.info/?probe=03e83e60ca) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3096d8532a](https://bsd-hardware.info/?probe=3096d8532a) | Jul 07, 2023 |
| HP            | EliteBook 8570p             | [44b85aad5e](https://bsd-hardware.info/?probe=44b85aad5e) | Jul 07, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | [9e3b26b01b](https://bsd-hardware.info/?probe=9e3b26b01b) | Jul 06, 2023 |
| Dell          | Latitude E6420              | [3151e6d3bb](https://bsd-hardware.info/?probe=3151e6d3bb) | Jul 05, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [2519fb81d6](https://bsd-hardware.info/?probe=2519fb81d6) | Jul 05, 2023 |
| Dell          | G3 3579                     | [8d9b29f231](https://bsd-hardware.info/?probe=8d9b29f231) | Jul 05, 2023 |
| Dell          | G3 3579                     | [f6fc15b1f4](https://bsd-hardware.info/?probe=f6fc15b1f4) | Jul 05, 2023 |
| Deciso        | Netboard A20                | [dd0a39a4d0](https://bsd-hardware.info/?probe=dd0a39a4d0) | Jul 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1HL0... | [f7b57506f0](https://bsd-hardware.info/?probe=f7b57506f0) | Jul 04, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [f74b33bc25](https://bsd-hardware.info/?probe=f74b33bc25) | Jul 03, 2023 |
| HP            | Compaq Presario CQ61        | [d070292855](https://bsd-hardware.info/?probe=d070292855) | Jul 03, 2023 |
| Unknown       | Unknown                     | [13c087ef5e](https://bsd-hardware.info/?probe=13c087ef5e) | Jul 03, 2023 |
| Unknown       | Unknown                     | [ae2bb37185](https://bsd-hardware.info/?probe=ae2bb37185) | Jul 03, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [f9f815c60e](https://bsd-hardware.info/?probe=f9f815c60e) | Jul 02, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [39e46fd477](https://bsd-hardware.info/?probe=39e46fd477) | Jul 02, 2023 |
| ASUSTek       | 1005PXD                     | [246032ee65](https://bsd-hardware.info/?probe=246032ee65) | Jul 02, 2023 |
| Unknown       | Unknown                     | [3725d44c33](https://bsd-hardware.info/?probe=3725d44c33) | Jul 01, 2023 |
| Lenovo        | ThinkPad T60 20076PU        | [cb47bfef12](https://bsd-hardware.info/?probe=cb47bfef12) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1aff07438c](https://bsd-hardware.info/?probe=1aff07438c) | Jun 28, 2023 |
| HP            | EliteBook 840 G3            | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Deciso        | NetBoard-A10                | [2eff359d8f](https://bsd-hardware.info/?probe=2eff359d8f) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | [03c29939fc](https://bsd-hardware.info/?probe=03c29939fc) | Jun 28, 2023 |
| Deciso        | DEC2700 - OPNsense Appli... | [aedd3a8255](https://bsd-hardware.info/?probe=aedd3a8255) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | [748ae83ba1](https://bsd-hardware.info/?probe=748ae83ba1) | Jun 27, 2023 |
| Dell          | XPS 13 9360                 | [648c09752f](https://bsd-hardware.info/?probe=648c09752f) | Jun 27, 2023 |
| HP            | EliteBook 850 G5            | [4bae8cd192](https://bsd-hardware.info/?probe=4bae8cd192) | Jun 27, 2023 |
| Deciso        | OPNsense Appliance          | [be0008eb2a](https://bsd-hardware.info/?probe=be0008eb2a) | Jun 26, 2023 |
| Dell          | Latitude 3420               | [057f065baa](https://bsd-hardware.info/?probe=057f065baa) | Jun 26, 2023 |
| Lenovo        | ThinkPad T440p 20AW000BU... | [9a7628d17b](https://bsd-hardware.info/?probe=9a7628d17b) | Jun 26, 2023 |
| Dell          | Inspiron 5570               | [a6e959358f](https://bsd-hardware.info/?probe=a6e959358f) | Jun 25, 2023 |
| HP            | EliteBook 8570p             | [e7dfbf94d0](https://bsd-hardware.info/?probe=e7dfbf94d0) | Jun 25, 2023 |
| Dell          | Latitude E4310              | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| HP            | Laptop 15-bs1xx             | [dc0d876d7b](https://bsd-hardware.info/?probe=dc0d876d7b) | Jun 24, 2023 |
| HP            | Laptop 15-ra0xx             | [8c31502b68](https://bsd-hardware.info/?probe=8c31502b68) | Jun 24, 2023 |
| HP            | EliteBook 750 G1            | [e0af4797d4](https://bsd-hardware.info/?probe=e0af4797d4) | Jun 24, 2023 |
| HP            | EliteBook 750 G1            | [aba91c70d1](https://bsd-hardware.info/?probe=aba91c70d1) | Jun 24, 2023 |
| HP            | 250 G6 Notebook PC          | [f7df283c94](https://bsd-hardware.info/?probe=f7df283c94) | Jun 24, 2023 |
| Dell          | Latitude 5490               | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| Unknown       | Unknown                     | [b324d1f4fc](https://bsd-hardware.info/?probe=b324d1f4fc) | Jun 23, 2023 |
| HP            | Pavilion g4                 | [ef66b5588a](https://bsd-hardware.info/?probe=ef66b5588a) | Jun 23, 2023 |
| HP            | 1000                        | [21faecd7a6](https://bsd-hardware.info/?probe=21faecd7a6) | Jun 23, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [d194e8bc0d](https://bsd-hardware.info/?probe=d194e8bc0d) | Jun 22, 2023 |
| Acer          | Aspire 5749                 | [75ad2ddb6f](https://bsd-hardware.info/?probe=75ad2ddb6f) | Jun 22, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [6969cd9e1a](https://bsd-hardware.info/?probe=6969cd9e1a) | Jun 20, 2023 |
| Acer          | Aspire 5749                 | [1e91633580](https://bsd-hardware.info/?probe=1e91633580) | Jun 20, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
| Unknown       | Unknown                     | [c017b848dc](https://bsd-hardware.info/?probe=c017b848dc) | Jun 19, 2023 |
| Apple         | MacBook2,1                  | [9e864bfe3b](https://bsd-hardware.info/?probe=9e864bfe3b) | Jun 18, 2023 |
| HP            | Pavilion 15                 | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| Dell          | Latitude E6520              | [98868960d5](https://bsd-hardware.info/?probe=98868960d5) | Jun 18, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [81bbc73e72](https://bsd-hardware.info/?probe=81bbc73e72) | Jun 18, 2023 |
| Dell          | Inspiron 5559               | [b0659ff5bf](https://bsd-hardware.info/?probe=b0659ff5bf) | Jun 18, 2023 |
| Samsung       | NC210/NC110                 | [06f5a9210b](https://bsd-hardware.info/?probe=06f5a9210b) | Jun 17, 2023 |
| HP            | EliteBook 8570p             | [53bbc07cc8](https://bsd-hardware.info/?probe=53bbc07cc8) | Jun 17, 2023 |
| Apple         | MacBook7,1                  | [6412e6fb23](https://bsd-hardware.info/?probe=6412e6fb23) | Jun 16, 2023 |
| HUAWEI        | BOHB-WAX9                   | [d8079e6155](https://bsd-hardware.info/?probe=d8079e6155) | Jun 16, 2023 |
| Notebook      | NL5xRU                      | [04ca736537](https://bsd-hardware.info/?probe=04ca736537) | Jun 15, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | [722403df31](https://bsd-hardware.info/?probe=722403df31) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [834f9f8748](https://bsd-hardware.info/?probe=834f9f8748) | Jun 15, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [7e1aa76e45](https://bsd-hardware.info/?probe=7e1aa76e45) | Jun 15, 2023 |
| Unknown       | Unknown                     | [e218344894](https://bsd-hardware.info/?probe=e218344894) | Jun 15, 2023 |
| Panasonic     | CFSX4-1                     | [ff83a965d2](https://bsd-hardware.info/?probe=ff83a965d2) | Jun 15, 2023 |
| Deciso        | OPNsense Appliance          | [43936f5f1c](https://bsd-hardware.info/?probe=43936f5f1c) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | [01df487b47](https://bsd-hardware.info/?probe=01df487b47) | Jun 14, 2023 |
| ASUSTek       | 1015P                       | [c700224684](https://bsd-hardware.info/?probe=c700224684) | Jun 14, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [ecdb80adc0](https://bsd-hardware.info/?probe=ecdb80adc0) | Jun 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4841a6b1d2](https://bsd-hardware.info/?probe=4841a6b1d2) | Jun 14, 2023 |
| HP            | Compaq 6830s                | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Lenovo        | ThinkPad T530 2429AP0       | [ddf37e7b17](https://bsd-hardware.info/?probe=ddf37e7b17) | Jun 13, 2023 |
| Samsung       | NC210/NC110                 | [dad27d6099](https://bsd-hardware.info/?probe=dad27d6099) | Jun 13, 2023 |
| Fujitsu Si... | AMILO Li3710                | [f6540a4d85](https://bsd-hardware.info/?probe=f6540a4d85) | Jun 13, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [76809610f9](https://bsd-hardware.info/?probe=76809610f9) | Jun 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [b532f1ce9c](https://bsd-hardware.info/?probe=b532f1ce9c) | Jun 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [dd937d0914](https://bsd-hardware.info/?probe=dd937d0914) | Jun 12, 2023 |
| HP            | EliteBook 840 G6            | [1d3675e09e](https://bsd-hardware.info/?probe=1d3675e09e) | Jun 11, 2023 |
| Acer          | Aspire E5-571G              | [9279b8ab4e](https://bsd-hardware.info/?probe=9279b8ab4e) | Jun 11, 2023 |
| Samsung       | R530/R730/R540              | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
| HP            | 15                          | [4664b4c93f](https://bsd-hardware.info/?probe=4664b4c93f) | Jun 11, 2023 |
| Dell          | Inspiron 3180               | [cb769078b4](https://bsd-hardware.info/?probe=cb769078b4) | Jun 10, 2023 |
| Dell          | Inspiron 5593               | [8bedc249ea](https://bsd-hardware.info/?probe=8bedc249ea) | Jun 10, 2023 |
| Dell          | Inspiron 7548               | [c80bb80e8f](https://bsd-hardware.info/?probe=c80bb80e8f) | Jun 10, 2023 |
| Lenovo        | B40-30 80F1                 | [769c678314](https://bsd-hardware.info/?probe=769c678314) | Jun 10, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [439e6a5034](https://bsd-hardware.info/?probe=439e6a5034) | Jun 10, 2023 |
| Unknown       | Unknown                     | [9afa1aea18](https://bsd-hardware.info/?probe=9afa1aea18) | Jun 10, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [27ba75252a](https://bsd-hardware.info/?probe=27ba75252a) | Jun 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP4C    | [b891388109](https://bsd-hardware.info/?probe=b891388109) | Jun 07, 2023 |
| ASUSTek       | 1015BX                      | [ad05aaf9fe](https://bsd-hardware.info/?probe=ad05aaf9fe) | Jun 07, 2023 |
| Deciso        | NetBoard-A20                | [0754642fe6](https://bsd-hardware.info/?probe=0754642fe6) | Jun 07, 2023 |
| Unknown       | Unknown                     | [422b9d51a7](https://bsd-hardware.info/?probe=422b9d51a7) | Jun 06, 2023 |
| Dell          | Inspiron 5559               | [fe5f99c4b0](https://bsd-hardware.info/?probe=fe5f99c4b0) | Jun 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [9f18b1b304](https://bsd-hardware.info/?probe=9f18b1b304) | Jun 06, 2023 |
| Lenovo        | ThinkPad T500 2082BNU       | [dedd066084](https://bsd-hardware.info/?probe=dedd066084) | Jun 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [85c18dbbb5](https://bsd-hardware.info/?probe=85c18dbbb5) | Jun 06, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [03e1e6d302](https://bsd-hardware.info/?probe=03e1e6d302) | Jun 05, 2023 |
| Deciso        | Netboard A20                | [eb03ae7215](https://bsd-hardware.info/?probe=eb03ae7215) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | [cf9ed85e65](https://bsd-hardware.info/?probe=cf9ed85e65) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | [fc66ebba25](https://bsd-hardware.info/?probe=fc66ebba25) | Jun 05, 2023 |
| Lenovo        | S10-3                       | [f874a66e78](https://bsd-hardware.info/?probe=f874a66e78) | Jun 05, 2023 |
| Lenovo        | S10-3                       | [b76483ab8b](https://bsd-hardware.info/?probe=b76483ab8b) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e1a7d29d74](https://bsd-hardware.info/?probe=e1a7d29d74) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d0d9de7cf3](https://bsd-hardware.info/?probe=d0d9de7cf3) | Jun 04, 2023 |
| Deciso        | NetBoard-A10                | [ab3919bc32](https://bsd-hardware.info/?probe=ab3919bc32) | Jun 04, 2023 |
| Lenovo        | B590 20208                  | [dc65d735c8](https://bsd-hardware.info/?probe=dc65d735c8) | Jun 04, 2023 |
| Unknown       | Unknown                     | [a243045cc3](https://bsd-hardware.info/?probe=a243045cc3) | Jun 04, 2023 |
| Dell          | G5 5505                     | [5a3c1f19a0](https://bsd-hardware.info/?probe=5a3c1f19a0) | Jun 03, 2023 |
| Lenovo        | ThinkPad X240 20AMS0250T    | [047c7b72b4](https://bsd-hardware.info/?probe=047c7b72b4) | Jun 02, 2023 |
| Panasonic     | CF-NX1GDHYS                 | [fb1f293997](https://bsd-hardware.info/?probe=fb1f293997) | Jun 02, 2023 |
| Deciso        | NetBoard-A20                | [48a63a2328](https://bsd-hardware.info/?probe=48a63a2328) | Jun 02, 2023 |
| Dell          | G5 5505                     | [1b10aecc38](https://bsd-hardware.info/?probe=1b10aecc38) | Jun 02, 2023 |
| HP            | EliteBook 8570p             | [22572f1df6](https://bsd-hardware.info/?probe=22572f1df6) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | [330c08c388](https://bsd-hardware.info/?probe=330c08c388) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | [53cf3cea13](https://bsd-hardware.info/?probe=53cf3cea13) | Jun 01, 2023 |
| Lenovo        | ThinkPad E495 20NE000BSP    | [0e02b323ee](https://bsd-hardware.info/?probe=0e02b323ee) | Jun 01, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [8cc6299ba9](https://bsd-hardware.info/?probe=8cc6299ba9) | May 31, 2023 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [b5f507c034](https://bsd-hardware.info/?probe=b5f507c034) | May 31, 2023 |
| HP            | Pavilion Notebook           | [1bb0436fe5](https://bsd-hardware.info/?probe=1bb0436fe5) | May 30, 2023 |
| IGEL Techn... | H830C                       | [01e377524a](https://bsd-hardware.info/?probe=01e377524a) | May 29, 2023 |
| Apple         | MacBookPro10,2              | [c274e2c9db](https://bsd-hardware.info/?probe=c274e2c9db) | May 29, 2023 |
| Dell          | System XPS L702X            | [f56d7090f9](https://bsd-hardware.info/?probe=f56d7090f9) | May 28, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [6701dce30e](https://bsd-hardware.info/?probe=6701dce30e) | May 28, 2023 |
| Dell          | Inspiron 5559               | [23cad3f06e](https://bsd-hardware.info/?probe=23cad3f06e) | May 28, 2023 |
| Deciso        | OPNsense Appliance          | [c47f62b522](https://bsd-hardware.info/?probe=c47f62b522) | May 28, 2023 |
| Fujitsu       | Unknown                     | [3b5c9ab914](https://bsd-hardware.info/?probe=3b5c9ab914) | May 27, 2023 |
| Toshiba       | NB250                       | [62c572e895](https://bsd-hardware.info/?probe=62c572e895) | May 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [3944241750](https://bsd-hardware.info/?probe=3944241750) | May 27, 2023 |
| Tactus        | GeoFlex 110                 | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| HP            | EliteBook 8570p             | [65376d6b42](https://bsd-hardware.info/?probe=65376d6b42) | May 27, 2023 |
| Acer          | Nitro AN515-42              | [adc687fcfe](https://bsd-hardware.info/?probe=adc687fcfe) | May 26, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [580c52399f](https://bsd-hardware.info/?probe=580c52399f) | May 25, 2023 |
| Deciso        | NetBoard-A20                | [0c5fd49340](https://bsd-hardware.info/?probe=0c5fd49340) | May 25, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [a2726e621b](https://bsd-hardware.info/?probe=a2726e621b) | May 25, 2023 |
| Timi          | TM1701                      | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| Acer          | Nitro AN515-57              | [c39ea00de5](https://bsd-hardware.info/?probe=c39ea00de5) | May 25, 2023 |
| Dell          | System XPS L702X            | [857016be75](https://bsd-hardware.info/?probe=857016be75) | May 24, 2023 |
| Lenovo        | ThinkPad T430 2347CTO       | [68937b1686](https://bsd-hardware.info/?probe=68937b1686) | May 24, 2023 |
| Unknown       | Unknown                     | [3b4be5b07a](https://bsd-hardware.info/?probe=3b4be5b07a) | May 24, 2023 |
| HP            | EliteBook 8570p             | [a1a68c0f7d](https://bsd-hardware.info/?probe=a1a68c0f7d) | May 24, 2023 |
| Acer          | Aspire E5-573               | [7bcb7c96be](https://bsd-hardware.info/?probe=7bcb7c96be) | May 23, 2023 |
| ASUSTek       | K42Jc                       | [3da2928a08](https://bsd-hardware.info/?probe=3da2928a08) | May 23, 2023 |
| Dell          | Inspiron 5559               | [9a2c066dfa](https://bsd-hardware.info/?probe=9a2c066dfa) | May 23, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [84e3ac62d5](https://bsd-hardware.info/?probe=84e3ac62d5) | May 23, 2023 |
| HP            | EliteBook 8570p             | [b5f17b6bf8](https://bsd-hardware.info/?probe=b5f17b6bf8) | May 23, 2023 |
| Google        | Sentry                      | [107124dd66](https://bsd-hardware.info/?probe=107124dd66) | May 22, 2023 |
| Sony          | VPCEG15FB                   | [8777493861](https://bsd-hardware.info/?probe=8777493861) | May 21, 2023 |
| HP            | Pavilion Notebook           | [41ce3c5d11](https://bsd-hardware.info/?probe=41ce3c5d11) | May 21, 2023 |
| Apple         | MacBookPro10,1              | [643f7277de](https://bsd-hardware.info/?probe=643f7277de) | May 21, 2023 |
| HP            | ZBook 15 G3                 | [4965fc4251](https://bsd-hardware.info/?probe=4965fc4251) | May 21, 2023 |
| Acer          | Aspire A514-54              | [7aed9d938a](https://bsd-hardware.info/?probe=7aed9d938a) | May 21, 2023 |
| Dell          | Inspiron 5559               | [a87acae699](https://bsd-hardware.info/?probe=a87acae699) | May 21, 2023 |
| HP            | ProBook 455 G3              | [b6a6c91115](https://bsd-hardware.info/?probe=b6a6c91115) | May 21, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0S300     | [44d30cfcf6](https://bsd-hardware.info/?probe=44d30cfcf6) | May 21, 2023 |
| Unknown       | Unknown                     | [2a2b4272f9](https://bsd-hardware.info/?probe=2a2b4272f9) | May 20, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | [5e25a49c65](https://bsd-hardware.info/?probe=5e25a49c65) | May 20, 2023 |
| Packard Be... | EasyNote LJ65               | [36d3e7aaf7](https://bsd-hardware.info/?probe=36d3e7aaf7) | May 19, 2023 |
| HP            | EliteBook 8570p             | [70d54595c2](https://bsd-hardware.info/?probe=70d54595c2) | May 19, 2023 |
| Valve         | Jupiter                     | [7be0869603](https://bsd-hardware.info/?probe=7be0869603) | May 19, 2023 |
| Valve         | Jupiter                     | [ef56a2bd17](https://bsd-hardware.info/?probe=ef56a2bd17) | May 19, 2023 |
| Lenovo        | ThinkPad T560 20FJS03Q00    | [a2110471aa](https://bsd-hardware.info/?probe=a2110471aa) | May 18, 2023 |
| Deciso        | NetBoard-A20                | [313796fd3e](https://bsd-hardware.info/?probe=313796fd3e) | May 18, 2023 |
| Lenovo        | ThinkPad X201 3323BBG       | [7b529b0888](https://bsd-hardware.info/?probe=7b529b0888) | May 17, 2023 |
| Panasonic     | CF-30KAPAXAM                | [62910ad9d9](https://bsd-hardware.info/?probe=62910ad9d9) | May 17, 2023 |
| Dell          | Inspiron 5559               | [dca662fc41](https://bsd-hardware.info/?probe=dca662fc41) | May 16, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [7732b2cfa7](https://bsd-hardware.info/?probe=7732b2cfa7) | May 15, 2023 |
| Dell          | Inspiron 3581               | [25c403ca33](https://bsd-hardware.info/?probe=25c403ca33) | May 15, 2023 |
| HP            | EliteBook 8570p             | [e252dc5ff2](https://bsd-hardware.info/?probe=e252dc5ff2) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [b6071c549a](https://bsd-hardware.info/?probe=b6071c549a) | May 15, 2023 |
| Dell          | Inspiron 3581               | [8d445a3fb3](https://bsd-hardware.info/?probe=8d445a3fb3) | May 14, 2023 |
| Sony          | SVF14A15CBB                 | [4ada2dca25](https://bsd-hardware.info/?probe=4ada2dca25) | May 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [526906c806](https://bsd-hardware.info/?probe=526906c806) | May 14, 2023 |
| Alienware     | 17 R4                       | [df734c8e64](https://bsd-hardware.info/?probe=df734c8e64) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [8aede62ca8](https://bsd-hardware.info/?probe=8aede62ca8) | May 14, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [256915976d](https://bsd-hardware.info/?probe=256915976d) | May 12, 2023 |
| TUXEDO        | Aura 15 Gen1                | [3d889e8b9b](https://bsd-hardware.info/?probe=3d889e8b9b) | May 11, 2023 |
| Intel         | HuronRiver Platform         | [83494ffd65](https://bsd-hardware.info/?probe=83494ffd65) | May 11, 2023 |
| Medion        | Major X10                   | [99228fd9da](https://bsd-hardware.info/?probe=99228fd9da) | May 10, 2023 |
| Deciso        | NetBoard-A10                | [37ee98e0b6](https://bsd-hardware.info/?probe=37ee98e0b6) | May 09, 2023 |
| Apple         | MacBook5,1                  | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| Notebook      | N7x0WU                      | [7a646e185a](https://bsd-hardware.info/?probe=7a646e185a) | May 09, 2023 |
| MSI           | GE62 6QC                    | [7c3fd3c9ca](https://bsd-hardware.info/?probe=7c3fd3c9ca) | May 08, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [95695f78c5](https://bsd-hardware.info/?probe=95695f78c5) | May 08, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | [6cd0f02045](https://bsd-hardware.info/?probe=6cd0f02045) | May 08, 2023 |
| Matsushita... | CF-48V4KNDQM                | [79f10d24d6](https://bsd-hardware.info/?probe=79f10d24d6) | May 07, 2023 |
| HP            | Laptop 14-bs0xx             | [98ea66d6e8](https://bsd-hardware.info/?probe=98ea66d6e8) | May 07, 2023 |
| Deciso        | OPNsense Appliance          | [2745eadfd9](https://bsd-hardware.info/?probe=2745eadfd9) | May 07, 2023 |
| ASUSTek       | 1000HE                      | [36214f8bed](https://bsd-hardware.info/?probe=36214f8bed) | May 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [d2bd7a8764](https://bsd-hardware.info/?probe=d2bd7a8764) | May 07, 2023 |
| Acer          | V5-131                      | [9d3ba324bc](https://bsd-hardware.info/?probe=9d3ba324bc) | May 06, 2023 |
| Lenovo        | ThinkPad T500 205663G       | [d706da9400](https://bsd-hardware.info/?probe=d706da9400) | May 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8A00KC... | [44ddee0eec](https://bsd-hardware.info/?probe=44ddee0eec) | May 06, 2023 |
| Panasonic     | CF-30KAPAXAM                | [1c918b79b0](https://bsd-hardware.info/?probe=1c918b79b0) | May 06, 2023 |
| Matsushita... | CF-51RCVDNLM                | [105a885451](https://bsd-hardware.info/?probe=105a885451) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 41742BU      | [161fe49de4](https://bsd-hardware.info/?probe=161fe49de4) | May 05, 2023 |
| Lenovo        | ThinkPad X230 2325T4T       | [00303b7a59](https://bsd-hardware.info/?probe=00303b7a59) | May 05, 2023 |
| Lenovo        | ThinkPad X220 429043U       | [bb714a4350](https://bsd-hardware.info/?probe=bb714a4350) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [28e76d5531](https://bsd-hardware.info/?probe=28e76d5531) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | [8c3f486dbc](https://bsd-hardware.info/?probe=8c3f486dbc) | May 03, 2023 |
| Apple         | MacBookPro11,5              | [45bffd3275](https://bsd-hardware.info/?probe=45bffd3275) | May 03, 2023 |
| Lenovo        | Flex 2-15 20405             | [3773da7851](https://bsd-hardware.info/?probe=3773da7851) | May 03, 2023 |
| Panasonic     | CF-52PFPBSFQ                | [e2c3df29b5](https://bsd-hardware.info/?probe=e2c3df29b5) | May 03, 2023 |
| HP            | Compaq Presario CQ50        | [f296048a29](https://bsd-hardware.info/?probe=f296048a29) | May 03, 2023 |
| Samsung       | NC110P/NC108P/NC111P        | [ea55a6fecf](https://bsd-hardware.info/?probe=ea55a6fecf) | May 02, 2023 |
| Apple         | MacBook5,1                  | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| Panasonic     | CF-53AAGHYDM                | [c7daf17edb](https://bsd-hardware.info/?probe=c7daf17edb) | May 02, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [f899593f61](https://bsd-hardware.info/?probe=f899593f61) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [b09acffe7b](https://bsd-hardware.info/?probe=b09acffe7b) | May 01, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [c4af168c4a](https://bsd-hardware.info/?probe=c4af168c4a) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [cf504f51df](https://bsd-hardware.info/?probe=cf504f51df) | May 01, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | [afd28a7425](https://bsd-hardware.info/?probe=afd28a7425) | Apr 30, 2023 |
| Fujitsu       | LIFEBOOK E752               | [44ea9fb6ae](https://bsd-hardware.info/?probe=44ea9fb6ae) | Apr 30, 2023 |
| Dell          | Latitude E5570              | [98e3f9821b](https://bsd-hardware.info/?probe=98e3f9821b) | Apr 29, 2023 |
| HP            | ProBook 640 G4              | [7b44e1591f](https://bsd-hardware.info/?probe=7b44e1591f) | Apr 29, 2023 |
| Deciso        | NetBoard-A10                | [79c36f752c](https://bsd-hardware.info/?probe=79c36f752c) | Apr 28, 2023 |
| Deciso        | NetBoard-A20                | [baa443b8ea](https://bsd-hardware.info/?probe=baa443b8ea) | Apr 28, 2023 |
| Apple         | MacBookPro8,3               | [08e155a558](https://bsd-hardware.info/?probe=08e155a558) | Apr 27, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [fc81710889](https://bsd-hardware.info/?probe=fc81710889) | Apr 27, 2023 |
| Apple         | MacBook5,1                  | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [692df89c1f](https://bsd-hardware.info/?probe=692df89c1f) | Apr 26, 2023 |
| Apple         | MacBook5,1                  | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| Deciso        | NetBoard-A20                | [3d0f6b629d](https://bsd-hardware.info/?probe=3d0f6b629d) | Apr 25, 2023 |
| Shuttle       | DS437                       | [284decb573](https://bsd-hardware.info/?probe=284decb573) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | [247810c987](https://bsd-hardware.info/?probe=247810c987) | Apr 24, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [7caed06fdb](https://bsd-hardware.info/?probe=7caed06fdb) | Apr 24, 2023 |
| Google        | Peppy                       | [d162160498](https://bsd-hardware.info/?probe=d162160498) | Apr 24, 2023 |
| Fujitsu Si... | AMILO Li3710                | [214b0c30e0](https://bsd-hardware.info/?probe=214b0c30e0) | Apr 23, 2023 |
| HP            | Unknown                     | [e2aa3620b4](https://bsd-hardware.info/?probe=e2aa3620b4) | Apr 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS06Q1D    | [2df7c991f0](https://bsd-hardware.info/?probe=2df7c991f0) | Apr 23, 2023 |
| Lenovo        | G500 20236                  | [e7387bfd6e](https://bsd-hardware.info/?probe=e7387bfd6e) | Apr 23, 2023 |
| Dell          | Inspiron 3421               | [ef4870410f](https://bsd-hardware.info/?probe=ef4870410f) | Apr 23, 2023 |
| HP            | Pavilion Notebook           | [243a9c2f22](https://bsd-hardware.info/?probe=243a9c2f22) | Apr 22, 2023 |
| Intel Clie... | LAPBC510                    | [68b1300903](https://bsd-hardware.info/?probe=68b1300903) | Apr 22, 2023 |
| HP            | Pavilion 17                 | [0f891b4377](https://bsd-hardware.info/?probe=0f891b4377) | Apr 21, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | [51f0a87f01](https://bsd-hardware.info/?probe=51f0a87f01) | Apr 21, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [93b498fb0c](https://bsd-hardware.info/?probe=93b498fb0c) | Apr 21, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [e17bcecec8](https://bsd-hardware.info/?probe=e17bcecec8) | Apr 21, 2023 |
| Dell          | Latitude 7280               | [254acb5df8](https://bsd-hardware.info/?probe=254acb5df8) | Apr 20, 2023 |
| HP            | EliteBook 8570p             | [6e82f69c4c](https://bsd-hardware.info/?probe=6e82f69c4c) | Apr 20, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [541f3e7f7e](https://bsd-hardware.info/?probe=541f3e7f7e) | Apr 20, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | [c4b2619dda](https://bsd-hardware.info/?probe=c4b2619dda) | Apr 20, 2023 |
| Dell          | Precision 5510              | [7028fde527](https://bsd-hardware.info/?probe=7028fde527) | Apr 20, 2023 |
| Lenovo        | ThinkPad X201 3626WNP       | [d642970071](https://bsd-hardware.info/?probe=d642970071) | Apr 19, 2023 |
| Packard Be... | DOT SE                      | [f456e964db](https://bsd-hardware.info/?probe=f456e964db) | Apr 19, 2023 |
| Dell          | Latitude 7410               | [d5c047907d](https://bsd-hardware.info/?probe=d5c047907d) | Apr 19, 2023 |
| Acer          | V5-131                      | [4c2332c3b8](https://bsd-hardware.info/?probe=4c2332c3b8) | Apr 19, 2023 |
| HP            | Unknown                     | [941c021569](https://bsd-hardware.info/?probe=941c021569) | Apr 18, 2023 |
| HP            | Laptop 14-dk1xxx            | [464059d8b1](https://bsd-hardware.info/?probe=464059d8b1) | Apr 18, 2023 |
| Medion        | E15302                      | [f47f32e1cc](https://bsd-hardware.info/?probe=f47f32e1cc) | Apr 17, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [b8d2c0d81d](https://bsd-hardware.info/?probe=b8d2c0d81d) | Apr 16, 2023 |
| Apple         | MacBookPro11,5              | [4f6fb0c095](https://bsd-hardware.info/?probe=4f6fb0c095) | Apr 16, 2023 |
| Apple         | MacBookPro11,5              | [052f95c2a9](https://bsd-hardware.info/?probe=052f95c2a9) | Apr 16, 2023 |
| Toshiba       | PORTEGE R700                | [8b196955ac](https://bsd-hardware.info/?probe=8b196955ac) | Apr 15, 2023 |
| Apple         | MacBook3,1                  | [74986a169a](https://bsd-hardware.info/?probe=74986a169a) | Apr 15, 2023 |
| Dell          | Inspiron 3542               | [4dfa2f0148](https://bsd-hardware.info/?probe=4dfa2f0148) | Apr 15, 2023 |
| Unknown       | Unknown                     | [c221bccd5d](https://bsd-hardware.info/?probe=c221bccd5d) | Apr 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [b189b0988c](https://bsd-hardware.info/?probe=b189b0988c) | Apr 14, 2023 |
| Lenovo        | G570 20079                  | [0ebba481d1](https://bsd-hardware.info/?probe=0ebba481d1) | Apr 14, 2023 |
| Lenovo        | ThinkPad T440s 20ARA07PL... | [04ddab3620](https://bsd-hardware.info/?probe=04ddab3620) | Apr 14, 2023 |
| Lenovo        | ThinkPad R61 89208RU        | [e892cdffee](https://bsd-hardware.info/?probe=e892cdffee) | Apr 13, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [3d7bf4205b](https://bsd-hardware.info/?probe=3d7bf4205b) | Apr 13, 2023 |
| HMT           | W041-TF-A-45                | [298d106fd1](https://bsd-hardware.info/?probe=298d106fd1) | Apr 13, 2023 |
| Google        | Terra                       | [ef1619f65f](https://bsd-hardware.info/?probe=ef1619f65f) | Apr 13, 2023 |
| Google        | Terra                       | [bf598bc5bf](https://bsd-hardware.info/?probe=bf598bc5bf) | Apr 13, 2023 |
| Samsung       | 370E4K                      | [c363d008bf](https://bsd-hardware.info/?probe=c363d008bf) | Apr 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [bee20c6a4c](https://bsd-hardware.info/?probe=bee20c6a4c) | Apr 12, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | [c7e40ee8ea](https://bsd-hardware.info/?probe=c7e40ee8ea) | Apr 12, 2023 |
| Lenovo        | ThinkPad X230 23257EP       | [e94085cd2d](https://bsd-hardware.info/?probe=e94085cd2d) | Apr 12, 2023 |
| Samsung       | N150/N210/N220              | [f6e5189f54](https://bsd-hardware.info/?probe=f6e5189f54) | Apr 11, 2023 |
| Lenovo        | ThinkPad X280 20KESB4T00    | [fb6c7b3b09](https://bsd-hardware.info/?probe=fb6c7b3b09) | Apr 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [add8280600](https://bsd-hardware.info/?probe=add8280600) | Apr 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [0249b4e73f](https://bsd-hardware.info/?probe=0249b4e73f) | Apr 11, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | [52aac5fc6f](https://bsd-hardware.info/?probe=52aac5fc6f) | Apr 11, 2023 |
| Unknown       | Unknown                     | [5bfbfb213e](https://bsd-hardware.info/?probe=5bfbfb213e) | Apr 09, 2023 |
| Fujitsu Si... | AMILO Li3710                | [6dabd5d84a](https://bsd-hardware.info/?probe=6dabd5d84a) | Apr 08, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [692b42afcd](https://bsd-hardware.info/?probe=692b42afcd) | Apr 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| Dell          | Latitude 7300               | [d036260cce](https://bsd-hardware.info/?probe=d036260cce) | Apr 08, 2023 |
| Dell          | XPS 13 9343                 | [8354aed46e](https://bsd-hardware.info/?probe=8354aed46e) | Apr 07, 2023 |
| Fujitsu       | CELSIUS H920                | [0551eecbcc](https://bsd-hardware.info/?probe=0551eecbcc) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | [385751dbc3](https://bsd-hardware.info/?probe=385751dbc3) | Apr 06, 2023 |
| ASUSTek       | X200MA                      | [c30e92db89](https://bsd-hardware.info/?probe=c30e92db89) | Apr 06, 2023 |
| SIEMENS       | SIMATIC IPC127E             | [40a11e4c68](https://bsd-hardware.info/?probe=40a11e4c68) | Apr 06, 2023 |
| Fujitsu       | LIFEBOOK U810               | [3073cd605c](https://bsd-hardware.info/?probe=3073cd605c) | Apr 06, 2023 |
| Dell          | Inspiron 5567               | [a305360215](https://bsd-hardware.info/?probe=a305360215) | Apr 05, 2023 |
| IGEL Techn... | M340C                       | [6c8b2b7af7](https://bsd-hardware.info/?probe=6c8b2b7af7) | Apr 05, 2023 |
| Google        | Wolf                        | [2546416afd](https://bsd-hardware.info/?probe=2546416afd) | Apr 05, 2023 |
| HP            | Laptop 15-bw0xx             | [93ea83eef5](https://bsd-hardware.info/?probe=93ea83eef5) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK U810               | [c7718b4aa3](https://bsd-hardware.info/?probe=c7718b4aa3) | Apr 03, 2023 |
| Lenovo        | G570 20079                  | [76cc1653c3](https://bsd-hardware.info/?probe=76cc1653c3) | Apr 03, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [48b0a1024e](https://bsd-hardware.info/?probe=48b0a1024e) | Apr 02, 2023 |
| Apple         | MacBookPro12,1              | [640aad419a](https://bsd-hardware.info/?probe=640aad419a) | Apr 02, 2023 |
| Lenovo        | G50-30 80G0                 | [911a1723a2](https://bsd-hardware.info/?probe=911a1723a2) | Apr 02, 2023 |
| Lenovo        | ThinkPad T450s 20BW001KL... | [4f6a7e2739](https://bsd-hardware.info/?probe=4f6a7e2739) | Apr 02, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | [0b93ef8199](https://bsd-hardware.info/?probe=0b93ef8199) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9bac0139f1](https://bsd-hardware.info/?probe=9bac0139f1) | Apr 01, 2023 |
| ASUSTek       | X58C                        | [dad28a9d36](https://bsd-hardware.info/?probe=dad28a9d36) | Apr 01, 2023 |
| Chuwi         | Unknown                     | [5e687fcc83](https://bsd-hardware.info/?probe=5e687fcc83) | Apr 01, 2023 |
| Fujitsu       | CELSIUS H920                | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| DNS           | W9x0LU                      | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
| HMT           | W041-TF-A-45                | [666df5a7e0](https://bsd-hardware.info/?probe=666df5a7e0) | Mar 31, 2023 |
| Acer          | Aspire 5745DG               | [2b8bf9802e](https://bsd-hardware.info/?probe=2b8bf9802e) | Mar 31, 2023 |
| Lenovo        | ThinkPad X220 4290DK6       | [96c83a2846](https://bsd-hardware.info/?probe=96c83a2846) | Mar 31, 2023 |
| Deciso        | NetBoard-A20                | [33ca458105](https://bsd-hardware.info/?probe=33ca458105) | Mar 30, 2023 |
| Intel         | Intel                       | [75e9733afd](https://bsd-hardware.info/?probe=75e9733afd) | Mar 30, 2023 |
| Toshiba       | Satellite L675D             | [0bf578daec](https://bsd-hardware.info/?probe=0bf578daec) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [ff14982ad9](https://bsd-hardware.info/?probe=ff14982ad9) | Mar 29, 2023 |
| Dell          | Latitude 5590               | [7e87d436df](https://bsd-hardware.info/?probe=7e87d436df) | Mar 29, 2023 |
| Google        | Stout                       | [d8346bb5da](https://bsd-hardware.info/?probe=d8346bb5da) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [0af5cebe20](https://bsd-hardware.info/?probe=0af5cebe20) | Mar 29, 2023 |
| Lenovo        | ThinkPad X230 23255NG       | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| Dell          | Inspiron 5547               | [4f4f6e06d7](https://bsd-hardware.info/?probe=4f4f6e06d7) | Mar 29, 2023 |
| Unknown       | Unknown                     | [2a50573c9f](https://bsd-hardware.info/?probe=2a50573c9f) | Mar 29, 2023 |
| Lenovo        | ThinkPad T540p 20BFS10W0... | [30c5fc2625](https://bsd-hardware.info/?probe=30c5fc2625) | Mar 29, 2023 |
| Irbis         | NB78                        | [471efbc788](https://bsd-hardware.info/?probe=471efbc788) | Mar 29, 2023 |
| Unknown       | Unknown                     | [ee06e14aa2](https://bsd-hardware.info/?probe=ee06e14aa2) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f4e450fed1](https://bsd-hardware.info/?probe=f4e450fed1) | Mar 29, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [dddf27cde4](https://bsd-hardware.info/?probe=dddf27cde4) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c2ba6aca7d](https://bsd-hardware.info/?probe=c2ba6aca7d) | Mar 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [fb4eec9c34](https://bsd-hardware.info/?probe=fb4eec9c34) | Mar 27, 2023 |
| HP            | Pavilion dv6                | [ce2cc6852d](https://bsd-hardware.info/?probe=ce2cc6852d) | Mar 27, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [b4805cd318](https://bsd-hardware.info/?probe=b4805cd318) | Mar 27, 2023 |
| LG Electro... | COLUMBIA                    | [4872f6c377](https://bsd-hardware.info/?probe=4872f6c377) | Mar 27, 2023 |
| Dell          | Inspiron 7437               | [2c4de59558](https://bsd-hardware.info/?probe=2c4de59558) | Mar 27, 2023 |
| Lenovo        | IdeaPad S210 20256          | [2e22ee87c3](https://bsd-hardware.info/?probe=2e22ee87c3) | Mar 27, 2023 |
| Lenovo        | ThinkPad T410 2518A37       | [f5537face6](https://bsd-hardware.info/?probe=f5537face6) | Mar 27, 2023 |
| Lenovo        | ThinkPad T430 2349G5P       | [9ea67d3893](https://bsd-hardware.info/?probe=9ea67d3893) | Mar 27, 2023 |
| Dell          | Latitude 5420               | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| LG Electro... | E500-L.A2M4A2               | [8dab794233](https://bsd-hardware.info/?probe=8dab794233) | Mar 26, 2023 |
| Dell          | Inspiron 5559               | [7652c9891e](https://bsd-hardware.info/?probe=7652c9891e) | Mar 26, 2023 |
| HP            | EliteBook Folio 9470m       | [ea2865cbf5](https://bsd-hardware.info/?probe=ea2865cbf5) | Mar 26, 2023 |
| Samsung       | R468/R418                   | [f620a5c6ec](https://bsd-hardware.info/?probe=f620a5c6ec) | Mar 25, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | [b960dc3bde](https://bsd-hardware.info/?probe=b960dc3bde) | Mar 25, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [7df625b1df](https://bsd-hardware.info/?probe=7df625b1df) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a46f77ccdc](https://bsd-hardware.info/?probe=a46f77ccdc) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b64571464f](https://bsd-hardware.info/?probe=b64571464f) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [8e798ca6ef](https://bsd-hardware.info/?probe=8e798ca6ef) | Mar 25, 2023 |
| eMachines     | eM350                       | [bb900ace2d](https://bsd-hardware.info/?probe=bb900ace2d) | Mar 25, 2023 |
| Alienware     | 14                          | [742d648570](https://bsd-hardware.info/?probe=742d648570) | Mar 25, 2023 |
| Acer          | AOD270                      | [73877008e9](https://bsd-hardware.info/?probe=73877008e9) | Mar 25, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | [34b156c20c](https://bsd-hardware.info/?probe=34b156c20c) | Mar 24, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | [4cd1097c65](https://bsd-hardware.info/?probe=4cd1097c65) | Mar 24, 2023 |
| Intel         | H81U                        | [af9a6469c9](https://bsd-hardware.info/?probe=af9a6469c9) | Mar 24, 2023 |
| Dell          | G5 5587                     | [9b7714cbab](https://bsd-hardware.info/?probe=9b7714cbab) | Mar 24, 2023 |
| Dell          | G5 5587                     | [c118e0665f](https://bsd-hardware.info/?probe=c118e0665f) | Mar 24, 2023 |
| Dell          | Latitude 5500               | [8db518ef3d](https://bsd-hardware.info/?probe=8db518ef3d) | Mar 24, 2023 |
| Acer          | Aspire F5-573G              | [a8f794f3fb](https://bsd-hardware.info/?probe=a8f794f3fb) | Mar 24, 2023 |
| Acer          | Nitro AN515-53              | [a46e065fac](https://bsd-hardware.info/?probe=a46e065fac) | Mar 23, 2023 |
| Dell          | Inspiron 5559               | [f294f7ae04](https://bsd-hardware.info/?probe=f294f7ae04) | Mar 23, 2023 |
| Intel         | SandyBridge Platform        | [954a21f7de](https://bsd-hardware.info/?probe=954a21f7de) | Mar 23, 2023 |
| Lenovo        | ThinkPad T410 2518A37       | [42fffdf3f2](https://bsd-hardware.info/?probe=42fffdf3f2) | Mar 23, 2023 |
| Lenovo        | ThinkPad T61 7658CTO        | [f00e571f76](https://bsd-hardware.info/?probe=f00e571f76) | Mar 23, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | [d9efc1e30b](https://bsd-hardware.info/?probe=d9efc1e30b) | Mar 22, 2023 |
| ASUSTek       | X71Vn                       | [6e96ea55ee](https://bsd-hardware.info/?probe=6e96ea55ee) | Mar 22, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [136a6641be](https://bsd-hardware.info/?probe=136a6641be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| Lenovo        | G500 20236                  | [55dc82af1c](https://bsd-hardware.info/?probe=55dc82af1c) | Mar 20, 2023 |
| HUAWEI        | HVY-WXX9                    | [e1b5d66244](https://bsd-hardware.info/?probe=e1b5d66244) | Mar 20, 2023 |
| ASUSTek       | 1015PX                      | [d6c1199165](https://bsd-hardware.info/?probe=d6c1199165) | Mar 20, 2023 |
| Lenovo        | ThinkPad E595 20NF0002BM    | [83ee1d297d](https://bsd-hardware.info/?probe=83ee1d297d) | Mar 20, 2023 |
| ASUSTek       | K501UQ                      | [b7256fddbb](https://bsd-hardware.info/?probe=b7256fddbb) | Mar 19, 2023 |
| Apple         | MacBookPro5,1               | [9e300b5797](https://bsd-hardware.info/?probe=9e300b5797) | Mar 19, 2023 |
| MECHREVO S... | S1 Series                   | [58ae2c4605](https://bsd-hardware.info/?probe=58ae2c4605) | Mar 19, 2023 |
| Toshiba       | Satellite P300              | [81b7ca608e](https://bsd-hardware.info/?probe=81b7ca608e) | Mar 19, 2023 |
| Lenovo        | ThinkPad T520 4242PN3       | [3ea33f0cad](https://bsd-hardware.info/?probe=3ea33f0cad) | Mar 19, 2023 |
| ASUSTek       | G750JS                      | [bb6117addd](https://bsd-hardware.info/?probe=bb6117addd) | Mar 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [e35600705f](https://bsd-hardware.info/?probe=e35600705f) | Mar 19, 2023 |
| Samsung       | R520/R522/R620              | [096d52b83d](https://bsd-hardware.info/?probe=096d52b83d) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [be9a45f529](https://bsd-hardware.info/?probe=be9a45f529) | Mar 18, 2023 |
| HP            | ProBook 640 G3              | [860471150b](https://bsd-hardware.info/?probe=860471150b) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a365a5b411](https://bsd-hardware.info/?probe=a365a5b411) | Mar 18, 2023 |
| Apple         | MacBook4,1                  | [6f2790802d](https://bsd-hardware.info/?probe=6f2790802d) | Mar 18, 2023 |
| Lenovo        | ThinkPad A275 20KCS07010    | [4d6daf66c1](https://bsd-hardware.info/?probe=4d6daf66c1) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [c83b0dda87](https://bsd-hardware.info/?probe=c83b0dda87) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [50a5ed6b41](https://bsd-hardware.info/?probe=50a5ed6b41) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [9ac4738956](https://bsd-hardware.info/?probe=9ac4738956) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | [705ac0b37f](https://bsd-hardware.info/?probe=705ac0b37f) | Mar 18, 2023 |
| IGEL Techn... | M350C                       | [a04efafd2e](https://bsd-hardware.info/?probe=a04efafd2e) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | [dcab531d1e](https://bsd-hardware.info/?probe=dcab531d1e) | Mar 18, 2023 |
| HP            | Pavilion dv5                | [113fe74799](https://bsd-hardware.info/?probe=113fe74799) | Mar 18, 2023 |
| IP3 Techno... | ACN1S                       | [d0761f4192](https://bsd-hardware.info/?probe=d0761f4192) | Mar 18, 2023 |
| HP            | EliteBook 850 G2            | [653dbe54a4](https://bsd-hardware.info/?probe=653dbe54a4) | Mar 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| Intel         | S1200RP_SE                  | [5ae9400f0b](https://bsd-hardware.info/?probe=5ae9400f0b) | Mar 17, 2023 |
| Lenovo        | ThinkPad T440p              | [575123c3ac](https://bsd-hardware.info/?probe=575123c3ac) | Mar 17, 2023 |
| Dell          | Inspiron 3442               | [cbb9f6bfbb](https://bsd-hardware.info/?probe=cbb9f6bfbb) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [8b9aa95420](https://bsd-hardware.info/?probe=8b9aa95420) | Mar 17, 2023 |
| Toshiba       | Satellite L40               | [2297dcb7e7](https://bsd-hardware.info/?probe=2297dcb7e7) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [937a7c9385](https://bsd-hardware.info/?probe=937a7c9385) | Mar 17, 2023 |
| Lenovo        | ThinkPad X201 36801T6       | [decaf0c347](https://bsd-hardware.info/?probe=decaf0c347) | Mar 17, 2023 |
| OEGStone      | W54_55SU1,SUW               | [7a2b28c47f](https://bsd-hardware.info/?probe=7a2b28c47f) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| Dell          | Inspiron 5557               | [ff199c6d21](https://bsd-hardware.info/?probe=ff199c6d21) | Mar 16, 2023 |
| HP            | Unknown                     | [0b79535c7f](https://bsd-hardware.info/?probe=0b79535c7f) | Mar 16, 2023 |
| ASUSTek       | 1001P                       | [76eae56ba3](https://bsd-hardware.info/?probe=76eae56ba3) | Mar 15, 2023 |
| OEGStone      | W54_55SU1,SUW               | [64316408f0](https://bsd-hardware.info/?probe=64316408f0) | Mar 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [564b1ccce1](https://bsd-hardware.info/?probe=564b1ccce1) | Mar 15, 2023 |
| Acer          | Aspire E5-571G              | [ca34dac813](https://bsd-hardware.info/?probe=ca34dac813) | Mar 15, 2023 |
| Samsung       | 275E4E/275E5E               | [dd4f7ef594](https://bsd-hardware.info/?probe=dd4f7ef594) | Mar 15, 2023 |
| HP            | Pavilion TS Sleekbook 14    | [d57e5b1b88](https://bsd-hardware.info/?probe=d57e5b1b88) | Mar 15, 2023 |
| Acer          | Aspire V3-112P              | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [89a5ee25f9](https://bsd-hardware.info/?probe=89a5ee25f9) | Mar 14, 2023 |
| Acer          | TravelMate P249-G2-M        | [090f37a821](https://bsd-hardware.info/?probe=090f37a821) | Mar 14, 2023 |
| Dell          | Latitude D630               | [da1fa73418](https://bsd-hardware.info/?probe=da1fa73418) | Mar 14, 2023 |
| HP            | Laptop 14-bs0xx             | [cd76713b75](https://bsd-hardware.info/?probe=cd76713b75) | Mar 14, 2023 |
| Dynabook E... | Satellite Pro E10-G-101     | [c58a37ef03](https://bsd-hardware.info/?probe=c58a37ef03) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [eaaf0fc8c7](https://bsd-hardware.info/?probe=eaaf0fc8c7) | Mar 14, 2023 |
| Toshiba       | Satellite L50-B             | [7052b38ba8](https://bsd-hardware.info/?probe=7052b38ba8) | Mar 14, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [b4893ae18f](https://bsd-hardware.info/?probe=b4893ae18f) | Mar 14, 2023 |
| Toshiba       | Satellite A200              | [c49985d00b](https://bsd-hardware.info/?probe=c49985d00b) | Mar 13, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [d9d7368322](https://bsd-hardware.info/?probe=d9d7368322) | Mar 13, 2023 |
| Dell          | Inspiron 5567               | [b878473783](https://bsd-hardware.info/?probe=b878473783) | Mar 13, 2023 |
| Acer          | Swift SF314-56              | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Acer          | Nitro AN515-55              | [e023282dcd](https://bsd-hardware.info/?probe=e023282dcd) | Mar 13, 2023 |
| Samsung       | R468/R418                   | [af44a29d38](https://bsd-hardware.info/?probe=af44a29d38) | Mar 13, 2023 |
| Dell          | Inspiron 7520               | [8b259d99ec](https://bsd-hardware.info/?probe=8b259d99ec) | Mar 13, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [5ce3dfe4a2](https://bsd-hardware.info/?probe=5ce3dfe4a2) | Mar 13, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [882cc7fc62](https://bsd-hardware.info/?probe=882cc7fc62) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | [8b112aa100](https://bsd-hardware.info/?probe=8b112aa100) | Mar 13, 2023 |
| Toshiba       | Satellite C845              | [0b680543b7](https://bsd-hardware.info/?probe=0b680543b7) | Mar 13, 2023 |
| Sony          | VGN-FZ19VN                  | [73809d943a](https://bsd-hardware.info/?probe=73809d943a) | Mar 13, 2023 |
| Dell          | Inspiron 5567               | [b2ef9ff3dc](https://bsd-hardware.info/?probe=b2ef9ff3dc) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK E736               | [1040a34321](https://bsd-hardware.info/?probe=1040a34321) | Mar 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [9c1172aa29](https://bsd-hardware.info/?probe=9c1172aa29) | Mar 12, 2023 |
| HP            | Laptop 14-bs1xx             | [99446c8dd0](https://bsd-hardware.info/?probe=99446c8dd0) | Mar 12, 2023 |
| Lenovo        | ThinkPad X200 2024AY7       | [bb432faf36](https://bsd-hardware.info/?probe=bb432faf36) | Mar 12, 2023 |
| Lenovo        | ZIUS6                       | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Dell          | Latitude E6330              | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Lenovo        | ThinkPad T440p              | [6d372db804](https://bsd-hardware.info/?probe=6d372db804) | Mar 12, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [5bcd236c4a](https://bsd-hardware.info/?probe=5bcd236c4a) | Mar 12, 2023 |
| Deciso        | OPNsense Appliance          | [faebab61f2](https://bsd-hardware.info/?probe=faebab61f2) | Mar 12, 2023 |
| Google        | Kohaku                      | [88491d298e](https://bsd-hardware.info/?probe=88491d298e) | Mar 12, 2023 |
| Acer          | Nitro AN515-54              | [6e97a003ec](https://bsd-hardware.info/?probe=6e97a003ec) | Mar 12, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [80dd48bca9](https://bsd-hardware.info/?probe=80dd48bca9) | Mar 12, 2023 |
| Dell          | Precision 7720              | [01f5f21b76](https://bsd-hardware.info/?probe=01f5f21b76) | Mar 12, 2023 |
| Acer          | Swift SF314-42              | [aa89c48cb7](https://bsd-hardware.info/?probe=aa89c48cb7) | Mar 12, 2023 |
| Apple         | MacBookAir1,1               | [2142f08b3f](https://bsd-hardware.info/?probe=2142f08b3f) | Mar 12, 2023 |
| HP            | Laptop 15-bs1xx             | [1df045ffd0](https://bsd-hardware.info/?probe=1df045ffd0) | Mar 11, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [aa70f61a87](https://bsd-hardware.info/?probe=aa70f61a87) | Mar 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| Dell          | Latitude E5450              | [4bb2040221](https://bsd-hardware.info/?probe=4bb2040221) | Mar 11, 2023 |
| Lenovo        | ThinkPad L590 20Q7U04602    | [64a11e18da](https://bsd-hardware.info/?probe=64a11e18da) | Mar 11, 2023 |
| Star Labs     | StarBook                    | [80f6445f54](https://bsd-hardware.info/?probe=80f6445f54) | Mar 10, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [a4366e53ba](https://bsd-hardware.info/?probe=a4366e53ba) | Mar 10, 2023 |
| Fujitsu       | FMVA532BSJ                  | [695e38d0ea](https://bsd-hardware.info/?probe=695e38d0ea) | Mar 10, 2023 |
| Intel         | Jasper Lake Client Platf... | [88de48013c](https://bsd-hardware.info/?probe=88de48013c) | Mar 10, 2023 |
| Intel         | Jasper Lake Client Platf... | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495 20NKS0HN1N    | [af190c38e9](https://bsd-hardware.info/?probe=af190c38e9) | Mar 10, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | [223879138d](https://bsd-hardware.info/?probe=223879138d) | Mar 10, 2023 |
| Lenovo        | ThinkPad X230 23252G8       | [2ff46d6b7c](https://bsd-hardware.info/?probe=2ff46d6b7c) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [e5a43dd311](https://bsd-hardware.info/?probe=e5a43dd311) | Mar 10, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [44a8bf8fbc](https://bsd-hardware.info/?probe=44a8bf8fbc) | Mar 10, 2023 |
| HP            | EliteBook 2530p             | [e70d97f7d6](https://bsd-hardware.info/?probe=e70d97f7d6) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| Dell          | Latitude D620               | [8b3ad4e8b9](https://bsd-hardware.info/?probe=8b3ad4e8b9) | Mar 09, 2023 |
| Dell          | Latitude D620               | [d42a8ee079](https://bsd-hardware.info/?probe=d42a8ee079) | Mar 09, 2023 |
| Samsung       | 750XEE                      | [47d2204f58](https://bsd-hardware.info/?probe=47d2204f58) | Mar 08, 2023 |
| Lenovo        | ThinkPad X230 2324A14       | [124b3bdb95](https://bsd-hardware.info/?probe=124b3bdb95) | Mar 08, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | [aafc670aa7](https://bsd-hardware.info/?probe=aafc670aa7) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444F... | [1a31b27b2a](https://bsd-hardware.info/?probe=1a31b27b2a) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9466e6d4f4](https://bsd-hardware.info/?probe=9466e6d4f4) | Mar 07, 2023 |
| Deciso        | OPNsense Appliance          | [1cca4a556d](https://bsd-hardware.info/?probe=1cca4a556d) | Mar 07, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| ASUSTek       | 1201N                       | [5dc595eb79](https://bsd-hardware.info/?probe=5dc595eb79) | Mar 05, 2023 |
| ASUSTek       | 1201N                       | [daa787f637](https://bsd-hardware.info/?probe=daa787f637) | Mar 05, 2023 |
| Lenovo        | G400s 20244                 | [215f16c5d9](https://bsd-hardware.info/?probe=215f16c5d9) | Mar 05, 2023 |
| Lenovo        | IdeaPad 310-14IKB 80TU      | [8037475831](https://bsd-hardware.info/?probe=8037475831) | Mar 05, 2023 |
| HP            | EliteBook 2730p             | [3c404c9d20](https://bsd-hardware.info/?probe=3c404c9d20) | Mar 05, 2023 |
| Acer          | TravelMate TX50-G2          | [81ab6d240f](https://bsd-hardware.info/?probe=81ab6d240f) | Mar 05, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | [6d7b30d2c4](https://bsd-hardware.info/?probe=6d7b30d2c4) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f9db95d778](https://bsd-hardware.info/?probe=f9db95d778) | Mar 03, 2023 |
| HP            | G62                         | [18487b3ab2](https://bsd-hardware.info/?probe=18487b3ab2) | Mar 02, 2023 |
| Sony          | SVE1511C5E                  | [0e972db389](https://bsd-hardware.info/?probe=0e972db389) | Mar 02, 2023 |
| Sony          | SVE1511C5E                  | [6aa87871c2](https://bsd-hardware.info/?probe=6aa87871c2) | Mar 01, 2023 |
| Deciso        | NetBoard-A10                | [ca59a5e6f4](https://bsd-hardware.info/?probe=ca59a5e6f4) | Feb 28, 2023 |
| HP            | 240 G6 Notebook PC          | [d872652e25](https://bsd-hardware.info/?probe=d872652e25) | Feb 28, 2023 |
| Lenovo        | ThinkPad T430 2349S31       | [2b13f68cd6](https://bsd-hardware.info/?probe=2b13f68cd6) | Feb 28, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | [0e051e7291](https://bsd-hardware.info/?probe=0e051e7291) | Feb 27, 2023 |
| Notebook      | N2x0WU                      | [9545f36dee](https://bsd-hardware.info/?probe=9545f36dee) | Feb 27, 2023 |
| ASUSTek       | X541SA                      | [9d406d735e](https://bsd-hardware.info/?probe=9d406d735e) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [115bd3bc38](https://bsd-hardware.info/?probe=115bd3bc38) | Feb 26, 2023 |
| HP            | EliteBook 8570p             | [1a4897cb53](https://bsd-hardware.info/?probe=1a4897cb53) | Feb 26, 2023 |
| Dell          | Inspiron 15 3515            | [b480a98b22](https://bsd-hardware.info/?probe=b480a98b22) | Feb 26, 2023 |
| Acer          | Aspire ES1-571              | [d736d59649](https://bsd-hardware.info/?probe=d736d59649) | Feb 26, 2023 |
| Acer          | Aspire ES1-571              | [48aa652a09](https://bsd-hardware.info/?probe=48aa652a09) | Feb 26, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [59e609fbb2](https://bsd-hardware.info/?probe=59e609fbb2) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [2ab690000c](https://bsd-hardware.info/?probe=2ab690000c) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [ae0dc68ba6](https://bsd-hardware.info/?probe=ae0dc68ba6) | Feb 25, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [45549e4faf](https://bsd-hardware.info/?probe=45549e4faf) | Feb 25, 2023 |
| Toshiba       | dynabook R63/P              | [c41c3adfa4](https://bsd-hardware.info/?probe=c41c3adfa4) | Feb 25, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005SU... | [7750c38cd0](https://bsd-hardware.info/?probe=7750c38cd0) | Feb 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [b3e56e9656](https://bsd-hardware.info/?probe=b3e56e9656) | Feb 25, 2023 |
| Dell          | Latitude 5591               | [fb33d7a0c4](https://bsd-hardware.info/?probe=fb33d7a0c4) | Feb 25, 2023 |
| HP            | EliteBook 840 G1            | [0480ce43f2](https://bsd-hardware.info/?probe=0480ce43f2) | Feb 24, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [97d9b10c8a](https://bsd-hardware.info/?probe=97d9b10c8a) | Feb 24, 2023 |
| HP            | EliteBook 8570p             | [1e548fa114](https://bsd-hardware.info/?probe=1e548fa114) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [95c66df5a4](https://bsd-hardware.info/?probe=95c66df5a4) | Feb 24, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [aef791947c](https://bsd-hardware.info/?probe=aef791947c) | Feb 23, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [3dae7e3ebb](https://bsd-hardware.info/?probe=3dae7e3ebb) | Feb 23, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [6669622646](https://bsd-hardware.info/?probe=6669622646) | Feb 23, 2023 |
| Deciso        | NetBoard-A20                | [d23ae47425](https://bsd-hardware.info/?probe=d23ae47425) | Feb 23, 2023 |
| Plaisio       | Turbo X                     | [e0a8a02bb9](https://bsd-hardware.info/?probe=e0a8a02bb9) | Feb 23, 2023 |
| Lenovo        | ThinkPad T440 20B60061MB    | [16a141cc35](https://bsd-hardware.info/?probe=16a141cc35) | Feb 23, 2023 |
| HP            | EliteBook 840 G1            | [77c17e4a2f](https://bsd-hardware.info/?probe=77c17e4a2f) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [7d7fa2bbc9](https://bsd-hardware.info/?probe=7d7fa2bbc9) | Feb 22, 2023 |
| Lenovo        | ThinkPad T440 20B60061MB    | [4867945cfb](https://bsd-hardware.info/?probe=4867945cfb) | Feb 22, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [d04d402809](https://bsd-hardware.info/?probe=d04d402809) | Feb 21, 2023 |
| Deciso        | Netboard A20                | [25077b7e64](https://bsd-hardware.info/?probe=25077b7e64) | Feb 21, 2023 |
| HP            | ZBook 15 G3                 | [ff6ddb74bb](https://bsd-hardware.info/?probe=ff6ddb74bb) | Feb 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b2ed608da5](https://bsd-hardware.info/?probe=b2ed608da5) | Feb 21, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [06e5309c55](https://bsd-hardware.info/?probe=06e5309c55) | Feb 20, 2023 |
| Lenovo        | ThinkPad T410 2537B94       | [9f9cb3e201](https://bsd-hardware.info/?probe=9f9cb3e201) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FMS3320G    | [c85f94d574](https://bsd-hardware.info/?probe=c85f94d574) | Feb 19, 2023 |
| Acer          | Aspire E1-421               | [db00abb833](https://bsd-hardware.info/?probe=db00abb833) | Feb 19, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [92bca4d026](https://bsd-hardware.info/?probe=92bca4d026) | Feb 19, 2023 |
| Lenovo        | G400s 20244                 | [f2c258a0ae](https://bsd-hardware.info/?probe=f2c258a0ae) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | [e7ef795b9b](https://bsd-hardware.info/?probe=e7ef795b9b) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | [cd2273037f](https://bsd-hardware.info/?probe=cd2273037f) | Feb 19, 2023 |
| Acer          | Aspire 7738                 | [e61cd20061](https://bsd-hardware.info/?probe=e61cd20061) | Feb 18, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| HP            | EliteBook 8570p             | [1ba2a827d9](https://bsd-hardware.info/?probe=1ba2a827d9) | Feb 18, 2023 |
| Lenovo        | ThinkPad W520 427638U       | [baa0e928a8](https://bsd-hardware.info/?probe=baa0e928a8) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | [39b4581223](https://bsd-hardware.info/?probe=39b4581223) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [67b2e8db2b](https://bsd-hardware.info/?probe=67b2e8db2b) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | [fd58d235b3](https://bsd-hardware.info/?probe=fd58d235b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [f7646f9d7f](https://bsd-hardware.info/?probe=f7646f9d7f) | Feb 18, 2023 |
| IGEL Techn... | H830C                       | [069249225f](https://bsd-hardware.info/?probe=069249225f) | Feb 17, 2023 |
| Lenovo        | ThinkPad R60e 0658W2M       | [dba66ebfb5](https://bsd-hardware.info/?probe=dba66ebfb5) | Feb 17, 2023 |
| Lenovo        | ThinkPad T430u 33522D5      | [d5bbbb8cbe](https://bsd-hardware.info/?probe=d5bbbb8cbe) | Feb 17, 2023 |
| Apple         | MacBookPro11,1              | [673f6c0a01](https://bsd-hardware.info/?probe=673f6c0a01) | Feb 17, 2023 |
| Google        | Lulu                        | [cf598483cf](https://bsd-hardware.info/?probe=cf598483cf) | Feb 17, 2023 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | [59713ca193](https://bsd-hardware.info/?probe=59713ca193) | Feb 15, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |
| Deciso        | OPNsense Appliance          | [1eda4c5b48](https://bsd-hardware.info/?probe=1eda4c5b48) | Feb 15, 2023 |
| Deciso        | NetBoard-A20                | [ffc9e123b4](https://bsd-hardware.info/?probe=ffc9e123b4) | Feb 14, 2023 |
| Deciso        | Netboard A20                | [7c91a0f01b](https://bsd-hardware.info/?probe=7c91a0f01b) | Feb 14, 2023 |
| Lenovo        | ThinkPad T430 2347FV6       | [cf016ce514](https://bsd-hardware.info/?probe=cf016ce514) | Feb 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [00142b4e4c](https://bsd-hardware.info/?probe=00142b4e4c) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | [26c3b9bf4f](https://bsd-hardware.info/?probe=26c3b9bf4f) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | [1d948a1a23](https://bsd-hardware.info/?probe=1d948a1a23) | Feb 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c176577762](https://bsd-hardware.info/?probe=c176577762) | Feb 14, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |
| Acer          | Aspire one V1.05            | [eec371a28f](https://bsd-hardware.info/?probe=eec371a28f) | Feb 13, 2023 |
| Dell          | Inspiron 5567               | [df5f01d72e](https://bsd-hardware.info/?probe=df5f01d72e) | Feb 13, 2023 |
| Panasonic     | CF-30KAPAXAM                | [f686e3756c](https://bsd-hardware.info/?probe=f686e3756c) | Feb 13, 2023 |
| Shuttle       | DS437T                      | [9a16ad9fec](https://bsd-hardware.info/?probe=9a16ad9fec) | Feb 12, 2023 |
| Alienware     | m15                         | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| HP            | ProBook 450 G2              | [acff807555](https://bsd-hardware.info/?probe=acff807555) | Feb 12, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8d49d50738](https://bsd-hardware.info/?probe=8d49d50738) | Feb 11, 2023 |
| Unknown       | Unknown                     | [c2735d8120](https://bsd-hardware.info/?probe=c2735d8120) | Feb 11, 2023 |
| Apple         | MacBookAir6,1               | [96fa5325d1](https://bsd-hardware.info/?probe=96fa5325d1) | Feb 11, 2023 |
| Acer          | Aspire A315-58              | [81827ccbca](https://bsd-hardware.info/?probe=81827ccbca) | Feb 10, 2023 |
| MSI           | GF76 12UE                   | [371f734e07](https://bsd-hardware.info/?probe=371f734e07) | Feb 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a9928bd16e](https://bsd-hardware.info/?probe=a9928bd16e) | Feb 10, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [0c9cf4e002](https://bsd-hardware.info/?probe=0c9cf4e002) | Feb 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [ca1e51a042](https://bsd-hardware.info/?probe=ca1e51a042) | Feb 09, 2023 |
| Sony          | SVF1421E4E                  | [d0a9e97993](https://bsd-hardware.info/?probe=d0a9e97993) | Feb 09, 2023 |
| HP            | Laptop 14-df0xxx            | [1dc503f21d](https://bsd-hardware.info/?probe=1dc503f21d) | Feb 09, 2023 |
| Acer          | Aspire 4739Z                | [1e97a0b938](https://bsd-hardware.info/?probe=1e97a0b938) | Feb 09, 2023 |
| HP            | Pavilion dv6                | [d6c8ad1034](https://bsd-hardware.info/?probe=d6c8ad1034) | Feb 08, 2023 |
| ASUSTek       | N76VZ                       | [3b7e2ee70b](https://bsd-hardware.info/?probe=3b7e2ee70b) | Feb 08, 2023 |
| ASUSTek       | K84L                        | [d58c178c51](https://bsd-hardware.info/?probe=d58c178c51) | Feb 08, 2023 |
| HP            | Notebook                    | [507e85c092](https://bsd-hardware.info/?probe=507e85c092) | Feb 08, 2023 |
| ASUSTek       | 1201N                       | [3f44d6ed3f](https://bsd-hardware.info/?probe=3f44d6ed3f) | Feb 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f3b0d5ac82](https://bsd-hardware.info/?probe=f3b0d5ac82) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [4fc5363829](https://bsd-hardware.info/?probe=4fc5363829) | Feb 07, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [4d69517a13](https://bsd-hardware.info/?probe=4d69517a13) | Feb 07, 2023 |
| Panasonic     | CF-30KAPAXAM                | [baa7612257](https://bsd-hardware.info/?probe=baa7612257) | Feb 07, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [3345f50844](https://bsd-hardware.info/?probe=3345f50844) | Feb 06, 2023 |
| HP            | Notebook                    | [8d8e5c294a](https://bsd-hardware.info/?probe=8d8e5c294a) | Feb 06, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [8083410c50](https://bsd-hardware.info/?probe=8083410c50) | Feb 06, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [78a978a8d4](https://bsd-hardware.info/?probe=78a978a8d4) | Feb 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [ef722fc37b](https://bsd-hardware.info/?probe=ef722fc37b) | Feb 06, 2023 |
| HP            | Victus by Gaming Laptop ... | [b97af82e5c](https://bsd-hardware.info/?probe=b97af82e5c) | Feb 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [80f8e59cab](https://bsd-hardware.info/?probe=80f8e59cab) | Feb 05, 2023 |
| HP            | 650                         | [48099613ec](https://bsd-hardware.info/?probe=48099613ec) | Feb 05, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [a98d28355d](https://bsd-hardware.info/?probe=a98d28355d) | Feb 05, 2023 |
| Deciso        | OPNsense Appliance          | [62452eaaaa](https://bsd-hardware.info/?probe=62452eaaaa) | Feb 05, 2023 |
| HP            | 2000                        | [7c997ce022](https://bsd-hardware.info/?probe=7c997ce022) | Feb 05, 2023 |
| Samsung       | 700T1C                      | [91d5c568d1](https://bsd-hardware.info/?probe=91d5c568d1) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c771b7daf4](https://bsd-hardware.info/?probe=c771b7daf4) | Feb 05, 2023 |
| Toshiba       | PORTEGE Z930                | [5462140da0](https://bsd-hardware.info/?probe=5462140da0) | Feb 05, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [8a2bba8635](https://bsd-hardware.info/?probe=8a2bba8635) | Feb 05, 2023 |
| Deciso        | OPNsense Appliance          | [96df89832f](https://bsd-hardware.info/?probe=96df89832f) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN0008GE     | [8cb09e34ec](https://bsd-hardware.info/?probe=8cb09e34ec) | Feb 04, 2023 |
| Lenovo        | G70-70 80HW006AGE           | [a52e13cf4e](https://bsd-hardware.info/?probe=a52e13cf4e) | Feb 04, 2023 |
| Lenovo        | B50-80 80EW                 | [97da411601](https://bsd-hardware.info/?probe=97da411601) | Feb 04, 2023 |
| Lenovo        | B50-80 80EW                 | [a8ec146fc6](https://bsd-hardware.info/?probe=a8ec146fc6) | Feb 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [0232c45faa](https://bsd-hardware.info/?probe=0232c45faa) | Feb 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [b7a491a010](https://bsd-hardware.info/?probe=b7a491a010) | Feb 03, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [c0a6490fc8](https://bsd-hardware.info/?probe=c0a6490fc8) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d36789c493](https://bsd-hardware.info/?probe=d36789c493) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS04200    | [3178015cd3](https://bsd-hardware.info/?probe=3178015cd3) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.2               | [3e58da5c30](https://bsd-hardware.info/?probe=3e58da5c30) | Feb 02, 2023 |
| Unknown       | Unknown                     | [a7d54d41c8](https://bsd-hardware.info/?probe=a7d54d41c8) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.2               | [3309453ed5](https://bsd-hardware.info/?probe=3309453ed5) | Feb 02, 2023 |
| HP            | Mini 210-1000               | [eaabd2a89d](https://bsd-hardware.info/?probe=eaabd2a89d) | Feb 02, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a54516414a](https://bsd-hardware.info/?probe=a54516414a) | Feb 01, 2023 |
| Lenovo        | ThinkPad T460p 20FW0018A... | [932e722b2d](https://bsd-hardware.info/?probe=932e722b2d) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | [402494618a](https://bsd-hardware.info/?probe=402494618a) | Feb 01, 2023 |
| Unknown       | Unknown                     | [4cae5c6bb7](https://bsd-hardware.info/?probe=4cae5c6bb7) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | [63d90da096](https://bsd-hardware.info/?probe=63d90da096) | Feb 01, 2023 |
| Acer          | Aspire ES1-520              | [efac696b1a](https://bsd-hardware.info/?probe=efac696b1a) | Jan 31, 2023 |
| MSI           | Modern 15 A5M               | [afda1bcf60](https://bsd-hardware.info/?probe=afda1bcf60) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [341bae363a](https://bsd-hardware.info/?probe=341bae363a) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0b48f96d1e](https://bsd-hardware.info/?probe=0b48f96d1e) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [c2f84d2103](https://bsd-hardware.info/?probe=c2f84d2103) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| HP            | EliteBook 8440p             | [d732f4d6c4](https://bsd-hardware.info/?probe=d732f4d6c4) | Jan 31, 2023 |
| MSI           | Modern 15 A5M               | [26d140b290](https://bsd-hardware.info/?probe=26d140b290) | Jan 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [39ae8fb9c8](https://bsd-hardware.info/?probe=39ae8fb9c8) | Jan 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [bccdd2f331](https://bsd-hardware.info/?probe=bccdd2f331) | Jan 30, 2023 |
| Dell          | Precision 5540              | [de7ac2f8d1](https://bsd-hardware.info/?probe=de7ac2f8d1) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | [75b9ef6ee6](https://bsd-hardware.info/?probe=75b9ef6ee6) | Jan 30, 2023 |
| Apple         | MacBookAir5,1               | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [6da773c078](https://bsd-hardware.info/?probe=6da773c078) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [21398109dc](https://bsd-hardware.info/?probe=21398109dc) | Jan 29, 2023 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 225       | 7.05%   |
| helloSystem 0.8.1    | 195       | 6.11%   |
| helloSystem 0.8.0    | 134       | 4.2%    |
| helloSystem 0.5.0    | 116       | 3.64%   |
| FreeBSD 13.1         | 114       | 3.57%   |
| FreeBSD 13.0         | 111       | 3.48%   |
| helloSystem 0.4.0    | 92        | 2.88%   |
| OpenBSD 6.8          | 91        | 2.85%   |
| FreeBSD 14.0-CURRENT | 75        | 2.35%   |
| helloSystem 0.6.0    | 72        | 2.26%   |
| FreeBSD 13.2         | 71        | 2.23%   |
| FreeBSD 12.2         | 59        | 1.85%   |
| GhostBSD 20.04.02    | 58        | 1.82%   |
| OpenBSD 7.2          | 56        | 1.75%   |
| OpenBSD 6.9          | 55        | 1.72%   |
| OpenBSD 7.3          | 51        | 1.6%    |
| OpenBSD 7.0          | 50        | 1.57%   |
| OpenBSD 7.1          | 41        | 1.28%   |
| FreeBSD 13.1-p5      | 41        | 1.28%   |
| FreeBSD 13.0-p4      | 35        | 1.1%    |
| NomadBSD 1.3.2       | 34        | 1.07%   |
| helloSystem 0.8.2    | 34        | 1.07%   |
| FreeBSD 12.2-p2      | 34        | 1.07%   |
| NomadBSD 5806f915    | 32        | 1%      |
| FreeBSD 13.0-CURRENT | 31        | 0.97%   |
| GhostBSD 21.08.27    | 29        | 0.91%   |
| FreeBSD 13.0-STABLE  | 28        | 0.88%   |
| FreeBSD 12.1         | 28        | 0.88%   |
| NomadBSD 20221130    | 27        | 0.85%   |
| FreeBSD 12.1-p8      | 26        | 0.81%   |
| FreeBSD 13.0-p5      | 25        | 0.78%   |
| OpenBSD 6.7          | 23        | 0.72%   |
| FreeBSD 13.0-p3      | 23        | 0.72%   |
| FreeBSD 12.2-p4      | 23        | 0.72%   |
| FreeBSD 12.1-p10     | 23        | 0.72%   |
| FreeBSD 13.1-p7      | 22        | 0.69%   |
| FreeBSD 13.1-p2      | 21        | 0.66%   |
| FreeBSD 12.1-p5      | 20        | 0.63%   |
| FreeBSD 13.0-p7      | 19        | 0.6%    |
| NomadBSD 1.4         | 18        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 1000      | 36.6%   |
| helloSystem | 833       | 30.49%  |
| OpenBSD     | 297       | 10.87%  |
| OPNsense    | 248       | 9.08%   |
| GhostBSD    | 174       | 6.37%   |
| NomadBSD    | 125       | 4.58%   |
| NetBSD      | 22        | 0.81%   |
| HardenedBSD | 7         | 0.26%   |
| FuryBSD     | 6         | 0.22%   |
| DragonFly   | 6         | 0.22%   |
| FuguIta     | 5         | 0.18%   |
| MidnightBSD | 4         | 0.15%   |
| OS108       | 2         | 0.07%   |
| PC-BSD      | 1         | 0.04%   |
| MyBee       | 1         | 0.04%   |
| LibertyBSD  | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 2548      | 96.41%  |
| i386   | 90        | 3.41%   |
| macppc | 3         | 0.11%   |
| arm64  | 2         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 923       | 32.99%  |
| Console       | 403       | 14.4%   |
| XFCE          | 287       | 10.26%  |
| KDE5          | 232       | 8.29%   |
| MATE          | 209       | 7.47%   |
| fvwm          | 182       | 6.5%    |
| Openbox       | 135       | 4.82%   |
| GNOME         | 116       | 4.15%   |
| TWM           | 96        | 3.43%   |
| i3            | 82        | 2.93%   |
| Cinnamon      | 20        | 0.71%   |
| LXQt          | 18        | 0.64%   |
| AwesomeWM     | 15        | 0.54%   |
| Fluxbox       | 12        | 0.43%   |
| Enlightenment | 9         | 0.32%   |
| LXDE          | 8         | 0.29%   |
| xinitrc       | 7         | 0.25%   |
| Lumina        | 5         | 0.18%   |
| DWM           | 5         | 0.18%   |
| IceWM         | 4         | 0.14%   |
| ctwm          | 4         | 0.14%   |
| GNUstep       | 3         | 0.11%   |
| Window Maker  | 2         | 0.07%   |
| StumpWM       | 2         | 0.07%   |
| spectrwm      | 2         | 0.07%   |
| Picom         | 2         | 0.07%   |
| Mutter        | 2         | 0.07%   |
| Budgie        | 2         | 0.07%   |
| awesome       | 2         | 0.07%   |
| Xfwm4         | 1         | 0.04%   |
| X-Cinnamon    | 1         | 0.04%   |
| sway          | 1         | 0.04%   |
| sdorfehs      | 1         | 0.04%   |
| Potato        | 1         | 0.04%   |
| JWM           | 1         | 0.04%   |
| iwm           | 1         | 0.04%   |
| Compton       | 1         | 0.04%   |
| CDE           | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2219      | 82.98%  |
| Console | 414       | 15.48%  |
| Wayland | 41        | 1.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 1106      | 40.12%  |
| Console | 948       | 34.39%  |
| LightDM | 263       | 9.54%   |
| SDDM    | 260       | 9.43%   |
| XDM     | 86        | 3.12%   |
| GDM     | 77        | 2.79%   |
| Ly      | 14        | 0.51%   |
| PCDM    | 2         | 0.07%   |
| WDM     | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 901       | 32.27%  |
| Unknown         | 798       | 28.58%  |
| C               | 561       | 20.09%  |
| ru_RU           | 74        | 2.65%   |
| fr_FR           | 69        | 2.47%   |
| de_DE           | 58        | 2.08%   |
| en              | 51        | 1.83%   |
| en_GB           | 38        | 1.36%   |
| es_ES           | 28        | 1%      |
| zh_CN           | 21        | 0.75%   |
| pl_PL           | 19        | 0.68%   |
| pt_BR           | 16        | 0.57%   |
| it_IT           | 12        | 0.43%   |
| zh_TW           | 7         | 0.25%   |
| en_CA           | 7         | 0.25%   |
| de              | 7         | 0.25%   |
| ru              | 6         | 0.21%   |
| pt              | 6         | 0.21%   |
| en_AU           | 6         | 0.21%   |
| nl_NL           | 5         | 0.18%   |
| ja_JP           | 5         | 0.18%   |
| fi_FI           | 5         | 0.18%   |
| en_NZ           | 5         | 0.18%   |
| cs_CZ           | 5         | 0.18%   |
| uk_UA           | 4         | 0.14%   |
| tr_TR           | 4         | 0.14%   |
| nb_NO           | 4         | 0.14%   |
| es              | 4         | 0.14%   |
| ko_KR           | 3         | 0.11%   |
| en_US.US-ASCII  | 3         | 0.11%   |
| en_US.ISO8859-1 | 3         | 0.11%   |
| sv_SE           | 2         | 0.07%   |
| pt_PT           | 2         | 0.07%   |
| jp_JP           | 2         | 0.07%   |
| it              | 2         | 0.07%   |
| hu_HU           | 2         | 0.07%   |
| fr              | 2         | 0.07%   |
| es_CO           | 2         | 0.07%   |
| es_AR           | 2         | 0.07%   |
| en_SG           | 2         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2131      | 79.69%  |
| BIOS | 543       | 20.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 1477      | 54%     |
| Ufs     | 648       | 23.69%  |
| Ffs     | 303       | 11.08%  |
| Cd9660  | 300       | 10.97%  |
| Hammer2 | 5         | 0.18%   |
| Xfs     | 1         | 0.04%   |
| Nfs     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2347      | 87.84%  |
| MBR     | 293       | 10.97%  |
| Unknown | 26        | 0.97%   |
| BSD     | 6         | 0.22%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 870       | 32.94%  |
| Dell                           | 384       | 14.54%  |
| Hewlett-Packard                | 274       | 10.37%  |
| ASUSTek Computer               | 181       | 6.85%   |
| Acer                           | 146       | 5.53%   |
| Apple                          | 107       | 4.05%   |
| Deciso                         | 77        | 2.92%   |
| Toshiba                        | 60        | 2.27%   |
| Unknown                        | 56        | 2.12%   |
| Samsung Electronics            | 48        | 1.82%   |
| Sony                           | 33        | 1.25%   |
| MSI                            | 32        | 1.21%   |
| Fujitsu                        | 31        | 1.17%   |
| Intel                          | 23        | 0.87%   |
| Google                         | 22        | 0.83%   |
| Panasonic                      | 19        | 0.72%   |
| TUXEDO                         | 18        | 0.68%   |
| Notebook                       | 17        | 0.64%   |
| System76                       | 15        | 0.57%   |
| IBM                            | 15        | 0.57%   |
| HUAWEI                         | 15        | 0.57%   |
| Packard Bell                   | 9         | 0.34%   |
| Timi                           | 8         | 0.3%    |
| LG Electronics                 | 8         | 0.3%    |
| Fujitsu Siemens                | 8         | 0.3%    |
| Framework                      | 8         | 0.3%    |
| Alienware                      | 8         | 0.3%    |
| Shuttle                        | 6         | 0.23%   |
| Gigabyte Technology            | 6         | 0.23%   |
| eMachines                      | 6         | 0.23%   |
| Star Labs                      | 5         | 0.19%   |
| Medion                         | 5         | 0.19%   |
| Gateway                        | 5         | 0.19%   |
| Datto                          | 5         | 0.19%   |
| SLIMBOOK                       | 4         | 0.15%   |
| GPD                            | 4         | 0.15%   |
| Clevo                          | 4         | 0.15%   |
| Chuwi                          | 4         | 0.15%   |
| Razer                          | 3         | 0.11%   |
| Matsushita Electric Industrial | 3         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 71        | 2.69%   |
| Deciso NetBoard-A10                 | 23        | 0.87%   |
| Deciso Netboard A20                 | 23        | 0.87%   |
| Deciso NetBoard-A20                 | 15        | 0.57%   |
| Intel H81U                          | 10        | 0.38%   |
| Dell Latitude E6420                 | 10        | 0.38%   |
| Deciso OPNsense Appliance           | 10        | 0.38%   |
| HP EliteBook 840 G3                 | 9         | 0.34%   |
| Dell Latitude E7240                 | 8         | 0.3%    |
| Dell Latitude E6430                 | 8         | 0.3%    |
| Apple MacBookPro9,2                 | 8         | 0.3%    |
| HP Notebook                         | 7         | 0.27%   |
| Framework Laptop                    | 7         | 0.27%   |
| Dell Inspiron 3542                  | 7         | 0.27%   |
| Dell Inspiron 3442                  | 7         | 0.27%   |
| Apple MacBook5,1                    | 7         | 0.27%   |
| Apple MacBook4,1                    | 7         | 0.27%   |
| Lenovo ThinkPad X200 745969G        | 6         | 0.23%   |
| HP Pavilion dv6                     | 6         | 0.23%   |
| HP 2000                             | 6         | 0.23%   |
| Dell XPS 13 9360                    | 6         | 0.23%   |
| Dell Latitude E5570                 | 6         | 0.23%   |
| Dell Inspiron 15-3567               | 6         | 0.23%   |
| Deciso DEC2700 - OPNsense Appliance | 6         | 0.23%   |
| Apple MacBookPro8,1                 | 6         | 0.23%   |
| TUXEDO Pulse 15 Gen1                | 5         | 0.19%   |
| Lenovo ThinkPad X220 4286CTO        | 5         | 0.19%   |
| HP Pavilion Notebook                | 5         | 0.19%   |
| HP Pavilion g6                      | 5         | 0.19%   |
| Dell Precision M4800                | 5         | 0.19%   |
| Dell Latitude E6540                 | 5         | 0.19%   |
| Dell Latitude E5470                 | 5         | 0.19%   |
| Dell Latitude 7280                  | 5         | 0.19%   |
| Dell Latitude 5400                  | 5         | 0.19%   |
| Dell Inspiron 3521                  | 5         | 0.19%   |
| Apple MacBookPro6,2                 | 5         | 0.19%   |
| Apple MacBookAir5,1                 | 5         | 0.19%   |
| System76 Lemur Pro                  | 4         | 0.15%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS  | 4         | 0.15%   |
| Lenovo ThinkPad T490 20N2CTO1WW     | 4         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 679       | 25.71%  |
| Dell Latitude       | 175       | 6.63%   |
| Dell Inspiron       | 105       | 3.98%   |
| Acer Aspire         | 97        | 3.67%   |
| Lenovo IdeaPad      | 81        | 3.07%   |
| Unknown             | 71        | 2.69%   |
| HP EliteBook        | 53        | 2.01%   |
| HP Pavilion         | 50        | 1.89%   |
| Toshiba Satellite   | 40        | 1.51%   |
| HP ProBook          | 36        | 1.36%   |
| Dell Precision      | 36        | 1.36%   |
| HP Laptop           | 34        | 1.29%   |
| Dell XPS            | 28        | 1.06%   |
| Fujitsu LIFEBOOK    | 24        | 0.91%   |
| Deciso NetBoard-A10 | 23        | 0.87%   |
| Deciso Netboard     | 23        | 0.87%   |
| Dell Vostro         | 20        | 0.76%   |
| ASUS VivoBook       | 20        | 0.76%   |
| Lenovo Legion       | 17        | 0.64%   |
| Lenovo Yoga         | 15        | 0.57%   |
| Deciso NetBoard-A20 | 15        | 0.57%   |
| HP Compaq           | 14        | 0.53%   |
| IBM ThinkPad        | 13        | 0.49%   |
| HP ZBook            | 13        | 0.49%   |
| Intel H81U          | 10        | 0.38%   |
| Deciso OPNsense     | 10        | 0.38%   |
| ASUS ASUS           | 10        | 0.38%   |
| Apple MacBookPro9   | 10        | 0.38%   |
| Apple MacBookPro8   | 10        | 0.38%   |
| Apple MacBook5      | 10        | 0.38%   |
| Acer TravelMate     | 10        | 0.38%   |
| HP OMEN             | 9         | 0.34%   |
| ASUS ZenBook        | 9         | 0.34%   |
| Apple MacBookPro5   | 9         | 0.34%   |
| Apple MacBookPro11  | 9         | 0.34%   |
| TUXEDO Pulse        | 8         | 0.3%    |
| Framework Laptop    | 8         | 0.3%    |
| Acer Swift          | 8         | 0.3%    |
| Acer Nitro          | 8         | 0.3%    |
| Toshiba PORTEGE     | 7         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 257       | 9.73%   |
| 2019    | 233       | 8.82%   |
| 2021    | 217       | 8.22%   |
| 2011    | 197       | 7.46%   |
| 2013    | 191       | 7.23%   |
| 2018    | 180       | 6.82%   |
| 2022    | 173       | 6.55%   |
| 2016    | 162       | 6.13%   |
| 2015    | 162       | 6.13%   |
| 2012    | 162       | 6.13%   |
| 2017    | 135       | 5.11%   |
| 2010    | 132       | 5%      |
| 2014    | 129       | 4.88%   |
| 2009    | 102       | 3.86%   |
| 2008    | 78        | 2.95%   |
| 2007    | 44        | 1.67%   |
| 2023    | 29        | 1.1%    |
| 2006    | 26        | 0.98%   |
| Unknown | 11        | 0.42%   |
| 2005    | 8         | 0.3%    |
| 2004    | 5         | 0.19%   |
| 2003    | 5         | 0.19%   |
| 2002    | 3         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2641      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2595      | 98.26%  |
| Yes  | 46        | 1.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 973       | 36.33%  |
| 4.01-8.0    | 625       | 23.34%  |
| 16.01-24.0  | 615       | 22.96%  |
| 32.01-64.0  | 148       | 5.53%   |
| 2.01-3.0    | 130       | 4.85%   |
| 3.01-4.0    | 66        | 2.46%   |
| 24.01-32.0  | 33        | 1.23%   |
| 64.01-256.0 | 29        | 1.08%   |
| 0.51-1.0    | 29        | 1.08%   |
| 1.01-2.0    | 21        | 0.78%   |
| 0.01-0.5    | 8         | 0.3%    |
| 0           | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Notebooks | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 1507      | 55.61%  |
| 0.51-1.0    | 756       | 27.9%   |
| 1.01-2.0    | 255       | 9.41%   |
| 2.01-3.0    | 75        | 2.77%   |
| Unknown     | 27        | 1%      |
| 4.01-8.0    | 26        | 0.96%   |
| 0           | 22        | 0.81%   |
| 8.01-16.0   | 21        | 0.77%   |
| 3.01-4.0    | 10        | 0.37%   |
| 24.01-32.0  | 4         | 0.15%   |
| 16.01-24.0  | 4         | 0.15%   |
| 32.01-64.0  | 2         | 0.07%   |
| 64.01-256.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1970      | 72.56%  |
| 2      | 511       | 18.82%  |
| 0      | 152       | 5.6%    |
| 3      | 71        | 2.62%   |
| 4      | 10        | 0.37%   |
| 58     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1919      | 72.01%  |
| Yes       | 746       | 27.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2269      | 85.88%  |
| No        | 373       | 14.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2449      | 92.59%  |
| No        | 196       | 7.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1740      | 65.12%  |
| No        | 932       | 34.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 510       | 19.16%  |
| Germany     | 297       | 11.16%  |
| Russia      | 179       | 6.72%   |
| France      | 133       | 5%      |
| UK          | 109       | 4.09%   |
| Brazil      | 101       | 3.79%   |
| Poland      | 86        | 3.23%   |
| Canada      | 83        | 3.12%   |
| China       | 76        | 2.85%   |
| Spain       | 70        | 2.63%   |
| Italy       | 70        | 2.63%   |
| Netherlands | 65        | 2.44%   |
| Australia   | 54        | 2.03%   |
| Indonesia   | 45        | 1.69%   |
| Ukraine     | 44        | 1.65%   |
| Switzerland | 42        | 1.58%   |
| India       | 39        | 1.47%   |
| Sweden      | 34        | 1.28%   |
| Austria     | 33        | 1.24%   |
| Czechia     | 29        | 1.09%   |
| Romania     | 27        | 1.01%   |
| Japan       | 26        | 0.98%   |
| Hungary     | 26        | 0.98%   |
| Finland     | 24        | 0.9%    |
| Norway      | 23        | 0.86%   |
| Mexico      | 23        | 0.86%   |
| Argentina   | 21        | 0.79%   |
| Turkey      | 20        | 0.75%   |
| Portugal    | 20        | 0.75%   |
| Bulgaria    | 19        | 0.71%   |
| Taiwan      | 16        | 0.6%    |
| Denmark     | 15        | 0.56%   |
| Colombia    | 15        | 0.56%   |
| Greece      | 14        | 0.53%   |
| Belgium     | 13        | 0.49%   |
| Philippines | 12        | 0.45%   |
| New Zealand | 12        | 0.45%   |
| Vietnam     | 11        | 0.41%   |
| Latvia      | 11        | 0.41%   |
| Ireland     | 11        | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 67        | 2.32%   |
| Berlin            | 29        | 1%      |
| Vienna            | 28        | 0.97%   |
| St Petersburg     | 25        | 0.87%   |
| Montreal          | 24        | 0.83%   |
| Paris             | 23        | 0.8%    |
| Brooklyn          | 22        | 0.76%   |
| Sydney            | 19        | 0.66%   |
| Zurich            | 18        | 0.62%   |
| Jakarta           | 17        | 0.59%   |
| Warsaw            | 16        | 0.55%   |
| Amsterdam         | 15        | 0.52%   |
| Seattle           | 14        | 0.49%   |
| Saint-Laurent     | 14        | 0.49%   |
| Rome              | 14        | 0.49%   |
| Kyiv              | 14        | 0.49%   |
| Portland          | 13        | 0.45%   |
| Madrid            | 12        | 0.42%   |
| Wroclaw           | 11        | 0.38%   |
| Riga              | 11        | 0.38%   |
| Munich            | 11        | 0.38%   |
| Los Angeles       | 11        | 0.38%   |
| London            | 11        | 0.38%   |
| Frankfurt am Main | 11        | 0.38%   |
| Dublin            | 11        | 0.38%   |
| Sao Paulo         | 10        | 0.35%   |
| New York          | 10        | 0.35%   |
| Budapest          | 10        | 0.35%   |
| Bucharest         | 10        | 0.35%   |
| Shanghai          | 9         | 0.31%   |
| Milan             | 9         | 0.31%   |
| Krakow            | 9         | 0.31%   |
| Hamburg           | 9         | 0.31%   |
| Vilnius           | 8         | 0.28%   |
| Vancouver         | 8         | 0.28%   |
| Sofia             | 8         | 0.28%   |
| Istanbul          | 8         | 0.28%   |
| Gdansk            | 8         | 0.28%   |
| Chicago           | 8         | 0.28%   |
| Brighton          | 8         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 527       | 705    | 17.4%   |
| WDC                 | 374       | 486    | 12.35%  |
| Seagate             | 260       | 327    | 8.58%   |
| Toshiba             | 216       | 299    | 7.13%   |
| Kingston            | 194       | 234    | 6.4%    |
| SanDisk             | 151       | 175    | 4.99%   |
| Crucial             | 146       | 194    | 4.82%   |
| Transcend           | 128       | 187    | 4.23%   |
| Hitachi             | 116       | 137    | 3.83%   |
| Intel               | 99        | 122    | 3.27%   |
| NVMe                | 85        | 113    | 2.81%   |
| SK hynix            | 65        | 77     | 2.15%   |
| HGST                | 59        | 138    | 1.95%   |
| Micron Technology   | 50        | 59     | 1.65%   |
| A-DATA Technology   | 49        | 66     | 1.62%   |
| Apple               | 40        | 42     | 1.32%   |
| Fujitsu             | 26        | 35     | 0.86%   |
| PNY                 | 24        | 28     | 0.79%   |
| SPCC                | 23        | 29     | 0.76%   |
| KIOXIA              | 19        | 19     | 0.63%   |
| Phison              | 18        | 26     | 0.59%   |
| KingSpec            | 17        | 21     | 0.56%   |
| China               | 17        | 19     | 0.56%   |
| LITEON              | 15        | 21     | 0.5%    |
| Intenso             | 15        | 16     | 0.5%    |
| Gigabyte Technology | 15        | 21     | 0.5%    |
| Patriot             | 12        | 16     | 0.4%    |
| OCZ                 | 12        | 16     | 0.4%    |
| Corsair             | 12        | 13     | 0.4%    |
| FORESEE             | 11        | 13     | 0.36%   |
| Apacer              | 11        | 14     | 0.36%   |
| SSSTC               | 10        | 11     | 0.33%   |
| Silicon Motion      | 10        | 11     | 0.33%   |
| Hewlett-Packard     | 10        | 13     | 0.33%   |
| OWC                 | 9         | 10     | 0.3%    |
| Lexar               | 9         | 16     | 0.3%    |
| LITEONIT            | 8         | 8      | 0.26%   |
| Netac               | 7         | 7      | 0.23%   |
| GOODRAM             | 7         | 7      | 0.23%   |
| UMIS                | 6         | 6      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 42        | 1.34%   |
| Transcend TS256GMTS952T2 256GB     | 34        | 1.09%   |
| Seagate ST1000LM035-1RK172 1TB     | 33        | 1.06%   |
| Toshiba MQ01ABD100 1TB             | 29        | 0.93%   |
| Samsung SSD 860 EVO 500GB          | 26        | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 25        | 0.8%    |
| Toshiba MQ01ABF050 500GB           | 24        | 0.77%   |
| Transcend TS256GMTE652T2 256GB     | 22        | 0.7%    |
| Crucial CT500MX500SSD1 500GB       | 22        | 0.7%    |
| Samsung SSD 850 EVO 250GB          | 21        | 0.67%   |
| Kingston SA400S37120G 120GB        | 19        | 0.61%   |
| HGST HTS721010A9E630 1TB           | 18        | 0.58%   |
| Samsung SSD 850 EVO 500GB          | 15        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB        | 15        | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB       | 14        | 0.45%   |
| Kingston SA400S37480G 480GB        | 14        | 0.45%   |
| HGST HTS725050A7E630 500GB         | 14        | 0.45%   |
| Seagate ST500LT012-9WS142 500GB    | 13        | 0.42%   |
| Seagate ST500LT012-1DG142 500GB    | 13        | 0.42%   |
| Samsung SSD 860 EVO 250GB          | 13        | 0.42%   |
| Kingston SV300S37A120G 120GB       | 13        | 0.42%   |
| Toshiba MQ04ABF100 1TB             | 12        | 0.38%   |
| Seagate ST9500325AS 500GB          | 12        | 0.38%   |
| SanDisk SSD PLUS 240GB             | 11        | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB       | 11        | 0.35%   |
| Samsung MZVLW256HEHP-000L7 256GB   | 11        | 0.35%   |
| Crucial CT240BX500SSD1 240GB       | 11        | 0.35%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 10        | 0.32%   |
| Seagate ST9500420AS 500GB          | 10        | 0.32%   |
| Seagate ST1000LM049-2GH172 1TB     | 10        | 0.32%   |
| Samsung SSD 860 EVO 1TB            | 10        | 0.32%   |
| Samsung SSD 840 EVO 250GB          | 10        | 0.32%   |
| Intel SSDPEKKF256G8L 256GB         | 10        | 0.32%   |
| Crucial CT480BX500SSD1 480GB       | 10        | 0.32%   |
| WDC WD10JPVX-22JC3T0 1TB           | 9         | 0.29%   |
| Transcend TS128GMTE110S 128GB      | 9         | 0.29%   |
| Seagate ST9320423AS 320GB          | 9         | 0.29%   |
| Seagate ST1000LM048-2E7172 1TB     | 9         | 0.29%   |
| Samsung HM321HI 320GB              | 9         | 0.29%   |
| NVMe WDC PC SN730 SDB 512GB        | 9         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Seagate                                | 259       | 326    | 26.87%  |
| WDC                                    | 237       | 304    | 24.59%  |
| Toshiba                                | 152       | 207    | 15.77%  |
| Hitachi                                | 116       | 137    | 12.03%  |
| NVMe                                   | 59        | 76     | 6.12%   |
| HGST                                   | 59        | 138    | 6.12%   |
| Samsung Electronics                    | 33        | 37     | 3.42%   |
| Fujitsu                                | 25        | 33     | 2.59%   |
| Apple                                  | 6         | 6      | 0.62%   |
| Jetflash                               | 3         | 3      | 0.31%   |
| Product:              USB Flash Memory | 2         | 2      | 0.21%   |
| Lexar                                  | 2         | 3      | 0.21%   |
| Generic                                | 2         | 2      | 0.21%   |
| Verbatim                               | 1         | 1      | 0.1%    |
| USB                                    | 1         | 1      | 0.1%    |
| UFD 2.0                                | 1         | 1      | 0.1%    |
| SMI                                    | 1         | 1      | 0.1%    |
| OPENBSD                                | 1         | 1      | 0.1%    |
| LDLC F6+                               | 1         | 1      | 0.1%    |
| IBM/Hitachi                            | 1         | 1      | 0.1%    |
| HPE                                    | 1         | 5      | 0.1%    |
| General                                | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 301       | 400    | 20.87%  |
| Kingston            | 163       | 197    | 11.3%   |
| SanDisk             | 150       | 174    | 10.4%   |
| Crucial             | 122       | 158    | 8.46%   |
| Transcend           | 87        | 140    | 6.03%   |
| WDC                 | 65        | 85     | 4.51%   |
| Intel               | 60        | 78     | 4.16%   |
| Apple               | 34        | 36     | 2.36%   |
| A-DATA Technology   | 31        | 43     | 2.15%   |
| Toshiba             | 30        | 38     | 2.08%   |
| Micron Technology   | 26        | 31     | 1.8%    |
| SK hynix            | 25        | 26     | 1.73%   |
| NVMe                | 23        | 26     | 1.6%    |
| PNY                 | 22        | 26     | 1.53%   |
| SPCC                | 21        | 26     | 1.46%   |
| KingSpec            | 17        | 21     | 1.18%   |
| China               | 17        | 19     | 1.18%   |
| LITEON              | 14        | 20     | 0.97%   |
| Intenso             | 14        | 15     | 0.97%   |
| Patriot             | 12        | 16     | 0.83%   |
| OCZ                 | 12        | 16     | 0.83%   |
| Corsair             | 12        | 13     | 0.83%   |
| Apacer              | 11        | 14     | 0.76%   |
| Gigabyte Technology | 10        | 13     | 0.69%   |
| OWC                 | 9         | 10     | 0.62%   |
| Hewlett-Packard     | 9         | 12     | 0.62%   |
| LITEONIT            | 8         | 8      | 0.55%   |
| Netac               | 7         | 7      | 0.49%   |
| Lexar               | 7         | 13     | 0.49%   |
| GOODRAM             | 7         | 7      | 0.49%   |
| Team                | 6         | 8      | 0.42%   |
| Plextor             | 6         | 6      | 0.42%   |
| Phison              | 5         | 6      | 0.35%   |
| Kston               | 5         | 7      | 0.35%   |
| Hoodisk             | 5         | 6      | 0.35%   |
| FORESEE             | 5         | 7      | 0.35%   |
| Zheino              | 4         | 7      | 0.28%   |
| Mushkin             | 4         | 4      | 0.28%   |
| Dogfish             | 4         | 5      | 0.28%   |
| Leven               | 3         | 3      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1302      | 1832   | 46.3%   |
| HDD  | 903       | 1287   | 32.11%  |
| NVMe | 607       | 813    | 21.59%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2031      | 3119   | 76.99%  |
| NVMe | 607       | 813    | 23.01%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1639      | 2321   | 74.91%  |
| 0.51-1.0        | 461       | 634    | 21.07%  |
| 1.01-2.0        | 76        | 103    | 3.47%   |
| 3.01-4.0        | 4         | 52     | 0.18%   |
| 4.01-10.0       | 3         | 3      | 0.14%   |
| More than 100.0 | 2         | 2      | 0.09%   |
| 2.01-3.0        | 2         | 3      | 0.09%   |
| 0               | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 878       | 31.32%  |
| 1-20           | 664       | 23.69%  |
| 251-500        | 569       | 20.3%   |
| 501-1000       | 244       | 8.7%    |
| 51-100         | 224       | 7.99%   |
| 21-50          | 153       | 5.46%   |
| 1001-2000      | 45        | 1.61%   |
| Unknown        | 22        | 0.78%   |
| 2001-3000      | 3         | 0.11%   |
| More than 3000 | 1         | 0.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2294      | 83.69%  |
| 21-50          | 227       | 8.28%   |
| 51-100         | 85        | 3.1%    |
| 101-250        | 78        | 2.85%   |
| 251-500        | 23        | 0.84%   |
| Unknown        | 22        | 0.8%    |
| 501-1000       | 11        | 0.4%    |
| More than 3000 | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 11        | 12     | 2.39%   |
| Seagate ST500LT012-9WS142 500GB     | 10        | 14     | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 9         | 12     | 1.95%   |
| HGST HTS725050A7E630 500GB          | 9         | 15     | 1.95%   |
| Seagate ST9500420AS 500GB           | 8         | 10     | 1.74%   |
| Hitachi HTS541612J9SA00 120GB       | 8         | 8      | 1.74%   |
| Toshiba MQ01ABF050 500GB            | 7         | 9      | 1.52%   |
| Seagate ST9320423AS 320GB           | 6         | 6      | 1.3%    |
| Seagate ST500LT012-1DG142 500GB     | 6         | 6      | 1.3%    |
| Seagate ST500LM021-1KJ152 500GB     | 6         | 6      | 1.3%    |
| Seagate ST9500325AS 500GB           | 5         | 8      | 1.08%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 6      | 1.08%   |
| Hitachi HTS545050B9A300 500GB       | 5         | 6      | 1.08%   |
| Toshiba MK3261GSYN 320GB            | 4         | 6      | 0.87%   |
| Seagate ST9320325AS 320GB           | 4         | 4      | 0.87%   |
| Intel SSDSC2BF180A4L 180GB          | 4         | 4      | 0.87%   |
| Hitachi HTS547550A9E384 500GB       | 4         | 4      | 0.87%   |
| Hitachi HTS545050A7E380 500GB       | 4         | 4      | 0.87%   |
| Hitachi HTS545032B9A300 320GB       | 4         | 6      | 0.87%   |
| HGST HTS721010A9E630 1TB            | 4         | 23     | 0.87%   |
| Toshiba MQ01ABD075 752GB            | 3         | 3      | 0.65%   |
| Toshiba MQ01ABD032 320GB            | 3         | 4      | 0.65%   |
| Seagate ST9250315AS 250GB           | 3         | 4      | 0.65%   |
| Seagate ST9160412AS 160GB           | 3         | 3      | 0.65%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 3         | 3      | 0.65%   |
| Seagate ST320LT020-9YG142 320GB     | 3         | 4      | 0.65%   |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 3      | 0.65%   |
| SanDisk SSD PLUS 240GB              | 3         | 3      | 0.65%   |
| Samsung Electronics HM160HI 160GB   | 3         | 3      | 0.65%   |
| Micron Technology 1100 SATA 256GB   | 3         | 3      | 0.65%   |
| Kingston SV300S37A120G 120GB        | 3         | 3      | 0.65%   |
| Kingston SA400S37240G 240GB         | 3         | 3      | 0.65%   |
| Hitachi HTS545025B9SA02 250GB       | 3         | 5      | 0.65%   |
| Hitachi HTS542525K9A300 250GB       | 3         | 3      | 0.65%   |
| HGST HTS541010A9E680 1TB            | 3         | 4      | 0.65%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 2         | 2      | 0.43%   |
| WDC WD3200BPVT-80JJ5T0 320GB        | 2         | 2      | 0.43%   |
| WDC WD3200BPVT-75ZEST0 320GB        | 2         | 2      | 0.43%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 2      | 0.43%   |
| WDC WD10JPVX-75JC3T0 1TB            | 2         | 2      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 109       | 139    | 23.96%  |
| Toshiba             | 68        | 94     | 14.95%  |
| Hitachi             | 66        | 75     | 14.51%  |
| WDC                 | 54        | 58     | 11.87%  |
| Samsung Electronics | 31        | 35     | 6.81%   |
| Kingston            | 23        | 25     | 5.05%   |
| HGST                | 22        | 52     | 4.84%   |
| Intel               | 18        | 21     | 3.96%   |
| SanDisk             | 10        | 11     | 2.2%    |
| Micron Technology   | 8         | 8      | 1.76%   |
| Crucial             | 7         | 11     | 1.54%   |
| Fujitsu             | 5         | 8      | 1.1%    |
| Apple               | 5         | 5      | 1.1%    |
| SK hynix            | 4         | 4      | 0.88%   |
| A-DATA Technology   | 4         | 10     | 0.88%   |
| OCZ                 | 3         | 3      | 0.66%   |
| Corsair             | 3         | 3      | 0.66%   |
| SSSTC               | 2         | 2      | 0.44%   |
| LITEON              | 2         | 2      | 0.44%   |
| China               | 2         | 3      | 0.44%   |
| Transcend           | 1         | 1      | 0.22%   |
| SMI                 | 1         | 1      | 0.22%   |
| Patriot             | 1         | 1      | 0.22%   |
| Kston               | 1         | 1      | 0.22%   |
| KingSpec            | 1         | 1      | 0.22%   |
| IBM/Hitachi         | 1         | 1      | 0.22%   |
| Hewlett-Packard     | 1         | 2      | 0.22%   |
| Fanxiang            | 1         | 1      | 0.22%   |
| AGI                 | 1         | 1      | 0.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 109       | 139    | 32.63%  |
| Hitachi             | 66        | 75     | 19.76%  |
| Toshiba             | 65        | 85     | 19.46%  |
| WDC                 | 52        | 56     | 15.57%  |
| HGST                | 22        | 52     | 6.59%   |
| Samsung Electronics | 12        | 14     | 3.59%   |
| Fujitsu             | 5         | 8      | 1.5%    |
| Apple               | 2         | 2      | 0.6%    |
| IBM/Hitachi         | 1         | 1      | 0.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 321       | 432    | 72.62%  |
| SSD  | 116       | 142    | 26.24%  |
| NVMe | 5         | 5      | 1.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| SanDisk pSSD 256GB                | 3         | 3      | 42.86%  |
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 14.29%  |
| Samsung Electronics HM250JI 250GB | 1         | 1      | 14.29%  |
| HPE MK000480GWUGF 480GB           | 1         | 1      | 14.29%  |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 42.86%  |
| Samsung Electronics | 2         | 2      | 28.57%  |
| HPE                 | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2106      | 3199   | 79.08%  |
| Malfunc  | 441       | 579    | 16.56%  |
| Detected | 109       | 147    | 4.09%   |
| Failed   | 7         | 7      | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1931      | 65.59%  |
| Samsung Electronics                     | 253       | 8.59%   |
| AMD                                     | 247       | 8.39%   |
| SanDisk                                 | 109       | 3.7%    |
| SK hynix                                | 48        | 1.63%   |
| Transcend                               | 38        | 1.29%   |
| Kingston Technology Company             | 36        | 1.22%   |
| Toshiba                                 | 34        | 1.15%   |
| Nvidia                                  | 31        | 1.05%   |
| Phison Electronics                      | 29        | 0.99%   |
| Micron Technology                       | 28        | 0.95%   |
| Micron/Crucial Technology               | 24        | 0.82%   |
| KIOXIA                                  | 24        | 0.82%   |
| Silicon Motion                          | 23        | 0.78%   |
| ADATA Technology                        | 15        | 0.51%   |
| Solid State Storage Technology          | 9         | 0.31%   |
| Silicon Integrated Systems [SiS]        | 8         | 0.27%   |
| Realtek Semiconductor                   | 7         | 0.24%   |
| Lenovo                                  | 7         | 0.24%   |
| Union Memory (Shenzhen)                 | 6         | 0.2%    |
| Marvell Technology Group                | 6         | 0.2%    |
| Shenzhen Longsys Electronics            | 5         | 0.17%   |
| MAXIO Technology (Hangzhou)             | 5         | 0.17%   |
| JMicron Technology                      | 5         | 0.17%   |
| Shenzhen Unionmemory Information System | 4         | 0.14%   |
| Biwin Storage Technology                | 4         | 0.14%   |
| VIA Technologies                        | 2         | 0.07%   |
| INNOGRIT                                | 2         | 0.07%   |
| ULi Electronics                         | 1         | 0.03%   |
| Lite-On Technology                      | 1         | 0.03%   |
| Broadcom / LSI                          | 1         | 0.03%   |
| Apple                                   | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 257       | 8.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 238       | 7.53%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 208       | 6.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 192       | 6.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 154       | 4.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 127       | 4.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 117       | 3.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 104       | 3.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 93        | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 71        | 2.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 70        | 2.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 60        | 1.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 56        | 1.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 49        | 1.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 48        | 1.52%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 47        | 1.49%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 47        | 1.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 38        | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                            | 35        | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 34        | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 33        | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 33        | 1.04%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)      | 30        | 0.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 29        | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 28        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 28        | 0.89%   |
| Nvidia MCP79 AHCI Controller                                                     | 27        | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 26        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 26        | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 26        | 0.82%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 25        | 0.79%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 25        | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 24        | 0.76%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 20        | 0.63%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 20        | 0.63%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 19        | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 19        | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 16        | 0.51%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 16        | 0.51%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 15        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1981      | 65.27%  |
| NVMe | 683       | 22.5%   |
| IDE  | 257       | 8.47%   |
| RAID | 113       | 3.72%   |
| SAS  | 1         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2253      | 85.15%  |
| AMD          | 385       | 14.55%  |
| PowerPC      | 2         | 0.08%   |
| 11th         | 2         | 0.08%   |
| Unknown      | 2         | 0.08%   |
| ARM          | 1         | 0.04%   |
| 123456789ABC | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 62        | 2.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 52        | 1.95%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 49        | 1.84%   |
| Intel CPU Version                       | 45        | 1.69%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 38        | 1.43%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 37        | 1.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 35        | 1.31%   |
| AMD Ryzen Embedded V1500B               | 35        | 1.31%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 33        | 1.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 32        | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 31        | 1.16%   |
| AMD EPYC 3201 8-Core Processor          | 29        | 1.09%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 28        | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 28        | 1.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 27        | 1.01%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 27        | 1.01%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 24        | 0.9%    |
| Intel Core i5-4300U CPU @ 1.90GHz       | 24        | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz       | 22        | 0.83%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 22        | 0.83%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 21        | 0.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 21        | 0.79%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 20        | 0.75%   |
| Intel Core 2 Duo                        | 20        | 0.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 20        | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 20        | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 19        | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 19        | 0.71%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 18        | 0.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 18        | 0.68%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 18        | 0.68%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 18        | 0.68%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 17        | 0.64%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 17        | 0.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 16        | 0.6%    |
| Intel Core i7-5600U CPU @ 2.60GHz       | 15        | 0.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 15        | 0.56%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 15        | 0.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 14        | 0.53%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 14        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 805       | 30.35%  |
| Intel Core i7           | 548       | 20.66%  |
| Other                   | 184       | 6.94%   |
| Intel Core i3           | 183       | 6.9%    |
| Intel Core 2 Duo        | 162       | 6.11%   |
| Intel Celeron           | 147       | 5.54%   |
| AMD Ryzen 7             | 76        | 2.87%   |
| AMD Ryzen 5             | 60        | 2.26%   |
| Intel Atom              | 56        | 2.11%   |
| Intel Pentium           | 49        | 1.85%   |
| AMD EPYC                | 42        | 1.58%   |
| AMD Ryzen Embedded      | 36        | 1.36%   |
| Intel Pentium M         | 22        | 0.83%   |
| Intel Genuine           | 18        | 0.68%   |
| Intel Core 2            | 18        | 0.68%   |
| AMD A6                  | 18        | 0.68%   |
| AMD Ryzen 7 PRO         | 17        | 0.64%   |
| Intel Xeon              | 16        | 0.6%    |
| AMD Ryzen 3             | 14        | 0.53%   |
| Intel Pentium Silver    | 12        | 0.45%   |
| AMD Ryzen 5 PRO         | 11        | 0.41%   |
| AMD E1                  | 11        | 0.41%   |
| AMD E                   | 10        | 0.38%   |
| AMD A8                  | 10        | 0.38%   |
| Intel Pentium Dual      | 9         | 0.34%   |
| AMD A4                  | 9         | 0.34%   |
| AMD A10                 | 9         | 0.34%   |
| Intel Pentium Dual-Core | 8         | 0.3%    |
| Intel Core m3           | 6         | 0.23%   |
| Intel Core i9           | 6         | 0.23%   |
| AMD E2                  | 6         | 0.23%   |
| Intel Celeron M         | 5         | 0.19%   |
| AMD Athlon              | 5         | 0.19%   |
| Intel Pentium 4         | 4         | 0.15%   |
| Intel Core M            | 4         | 0.15%   |
| Intel Core Duo          | 4         | 0.15%   |
| Intel Celeron Dual-Core | 4         | 0.15%   |
| AMD Ryzen 9             | 4         | 0.15%   |
| AMD GX                  | 4         | 0.15%   |
| AMD C-50                | 4         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1341      | 50.53%  |
| 4       | 674       | 25.4%   |
| Unknown | 219       | 8.25%   |
| 8       | 150       | 5.65%   |
| 16      | 74        | 2.79%   |
| 1       | 74        | 2.79%   |
| 6       | 71        | 2.68%   |
| 12      | 41        | 1.54%   |
| 10      | 7         | 0.26%   |
| 20      | 2         | 0.08%   |
| 24      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 2546      | 95.97%  |
| Unknown | 65        | 2.45%   |
| 2       | 42        | 1.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1693      | 63.81%  |
| 1       | 699       | 26.35%  |
| Unknown | 261       | 9.84%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 440       | 16.61%  |
| IvyBridge       | 261       | 9.85%   |
| Haswell         | 243       | 9.17%   |
| SandyBridge     | 232       | 8.76%   |
| Skylake         | 189       | 7.13%   |
| Penryn          | 156       | 5.89%   |
| Broadwell       | 139       | 5.25%   |
| Westmere        | 109       | 4.11%   |
| Zen             | 94        | 3.55%   |
| Core            | 91        | 3.44%   |
| Unknown         | 91        | 3.44%   |
| TigerLake       | 68        | 2.57%   |
| Bonnell         | 66        | 2.49%   |
| Silvermont      | 63        | 2.38%   |
| Zen 2           | 55        | 2.08%   |
| Zen+            | 49        | 1.85%   |
| P6              | 38        | 1.43%   |
| Zen 3           | 35        | 1.32%   |
| CometLake       | 35        | 1.32%   |
| Goldmont plus   | 30        | 1.13%   |
| Excavator       | 24        | 0.91%   |
| Bobcat          | 23        | 0.87%   |
| Goldmont        | 20        | 0.76%   |
| Puma            | 17        | 0.64%   |
| Jaguar          | 16        | 0.6%    |
| IceLake         | 16        | 0.6%    |
| K10             | 10        | 0.38%   |
| Piledriver      | 8         | 0.3%    |
| NetBurst        | 7         | 0.26%   |
| Nehalem         | 6         | 0.23%   |
| K10 Llano       | 6         | 0.23%   |
| K8 Hammer       | 5         | 0.19%   |
| Steamroller     | 3         | 0.11%   |
| K8 & K10 hybrid | 3         | 0.11%   |
| Geode           | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2037      | 67.58%  |
| Nvidia                           | 516       | 17.12%  |
| AMD                              | 446       | 14.8%   |
| Silicon Integrated Systems [SiS] | 6         | 0.2%    |
| Silicon Motion                   | 3         | 0.1%    |
| VIA Technologies                 | 2         | 0.07%   |
| Trident Microsystems             | 1         | 0.03%   |
| S3 Graphics                      | 1         | 0.03%   |
| Matrox Electronics Systems       | 1         | 0.03%   |
| ATI                              | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 243       | 7.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 216       | 6.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 168       | 5.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 131       | 4.18%   |
| Intel HD Graphics 5500                                                                   | 120       | 3.83%   |
| Intel UHD Graphics 620                                                                   | 104       | 3.32%   |
| Intel HD Graphics 620                                                                    | 100       | 3.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 85        | 2.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 83        | 2.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 65        | 2.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 63        | 2.01%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 62        | 1.98%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 60        | 1.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 54        | 1.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 54        | 1.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 53        | 1.69%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 53        | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 49        | 1.56%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 46        | 1.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 38        | 1.21%   |
| Intel HD Graphics 530                                                                    | 38        | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 34        | 1.08%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 34        | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 28        | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 27        | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 27        | 0.86%   |
| AMD Lucienne                                                                             | 26        | 0.83%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 24        | 0.77%   |
| Intel HD Graphics 630                                                                    | 24        | 0.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 23        | 0.73%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 22        | 0.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 21        | 0.67%   |
| Nvidia C79 [GeForce 9400M]                                                               | 20        | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 19        | 0.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 19        | 0.61%   |
| Intel HD Graphics 500                                                                    | 15        | 0.48%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 15        | 0.48%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 15        | 0.48%   |
| Nvidia GP108M [GeForce MX150]                                                            | 14        | 0.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 14        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1401      | 52.71%  |
| Intel + Nvidia           | 338       | 12.72%  |
| 1 x AMD                  | 326       | 12.26%  |
| 2 x Intel                | 225       | 8.47%   |
| 1 x Nvidia               | 147       | 5.53%   |
| Other                    | 82        | 3.09%   |
| Intel + AMD              | 76        | 2.86%   |
| AMD + Nvidia             | 30        | 1.13%   |
| 2 x AMD                  | 12        | 0.45%   |
| 1 x SiS                  | 6         | 0.23%   |
| 2 x Nvidia               | 5         | 0.19%   |
| 1 x Silicon Motion       | 3         | 0.11%   |
| 1 x VIA                  | 2         | 0.08%   |
| 2 x Intel + 1 x Nvidia   | 1         | 0.04%   |
| 1 x Trident Microsystems | 1         | 0.04%   |
| 1 x S3 Graphics          | 1         | 0.04%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.04%   |
| AMD + Matrox             | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2334      | 87.15%  |
| Unknown     | 175       | 6.53%   |
| Proprietary | 169       | 6.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2346      | 87.21%  |
| 0.01-0.5   | 166       | 6.17%   |
| 1.01-2.0   | 70        | 2.6%    |
| 0.51-1.0   | 49        | 1.82%   |
| 3.01-4.0   | 31        | 1.15%   |
| 5.01-6.0   | 12        | 0.45%   |
| 7.01-8.0   | 11        | 0.41%   |
| 2.01-3.0   | 4         | 0.15%   |
| 8.01-16.0  | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 370       | 19.55%  |
| LG Display              | 344       | 18.17%  |
| Chimei Innolux          | 232       | 12.26%  |
| BOE                     | 214       | 11.3%   |
| Samsung Electronics     | 157       | 8.29%   |
| Lenovo                  | 106       | 5.6%    |
| Apple                   | 62        | 3.28%   |
| Sharp                   | 41        | 2.17%   |
| Chi Mei Optoelectronics | 41        | 2.17%   |
| Dell                    | 28        | 1.48%   |
| InfoVision              | 27        | 1.43%   |
| Goldstar                | 19        | 1%      |
| Hewlett-Packard         | 18        | 0.95%   |
| PANDA                   | 16        | 0.85%   |
| LG Philips              | 16        | 0.85%   |
| AOC                     | 16        | 0.85%   |
| BenQ                    | 15        | 0.79%   |
| Philips                 | 13        | 0.69%   |
| Acer                    | 12        | 0.63%   |
| HannStar                | 11        | 0.58%   |
| CSO                     | 11        | 0.58%   |
| Ancor Communications    | 10        | 0.53%   |
| LGD                     | 9         | 0.48%   |
| CPT                     | 7         | 0.37%   |
| Panasonic               | 6         | 0.32%   |
| JDI                     | 6         | 0.32%   |
| ViewSonic               | 5         | 0.26%   |
| Toshiba                 | 5         | 0.26%   |
| Iiyama                  | 5         | 0.26%   |
| Unknown                 | 5         | 0.26%   |
| Sceptre Tech            | 4         | 0.21%   |
| IBM                     | 4         | 0.21%   |
| Fujitsu Siemens         | 4         | 0.21%   |
| BOE Technology Group    | 4         | 0.21%   |
| Lenovo Group Limited    | 3         | 0.16%   |
| Eizo                    | 3         | 0.16%   |
| ASUSTek Computer        | 3         | 0.16%   |
| Vizio                   | 2         | 0.11%   |
| Unknown                 | 2         | 0.11%   |
| Sony                    | 2         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 24        | 1.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 17        | 0.89%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 13        | 0.68%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 12        | 0.63%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 12        | 0.63%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 10        | 0.52%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 10        | 0.52%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 10        | 0.52%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 9         | 0.47%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 9         | 0.47%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 9         | 0.47%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 9         | 0.47%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 9         | 0.47%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 9         | 0.47%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 9         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch     | 8         | 0.42%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 8         | 0.42%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 8         | 0.42%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 8         | 0.42%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 8         | 0.42%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                  | 8         | 0.42%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 8         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 8         | 0.42%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 7         | 0.37%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 7         | 0.37%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch         | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch         | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 7         | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 7         | 0.37%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                    | 7         | 0.37%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 7         | 0.37%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 7         | 0.37%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch           | 7         | 0.37%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 6         | 0.31%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 6         | 0.31%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch              | 6         | 0.31%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 6         | 0.31%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                 | 6         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 665       | 36%     |
| 1366x768 (WXGA)    | 624       | 33.78%  |
| 1280x800 (WXGA)    | 114       | 6.17%   |
| 1600x900 (HD+)     | 108       | 5.85%   |
| 3840x2160 (4K)     | 54        | 2.92%   |
| 2560x1440 (QHD)    | 51        | 2.76%   |
| 1024x600           | 33        | 1.79%   |
| 1440x900 (WXGA+)   | 32        | 1.73%   |
| 1920x1200 (WUXGA)  | 28        | 1.52%   |
| 2560x1600          | 14        | 0.76%   |
| 1680x1050 (WSXGA+) | 14        | 0.76%   |
| 1280x1024 (SXGA)   | 12        | 0.65%   |
| 3200x1800 (QHD+)   | 10        | 0.54%   |
| 2880x1800          | 9         | 0.49%   |
| 2560x1080          | 8         | 0.43%   |
| 2256x1504          | 8         | 0.43%   |
| 1024x768 (XGA)     | 7         | 0.38%   |
| 2880x1620          | 6         | 0.32%   |
| Unknown            | 6         | 0.32%   |
| 3440x1440          | 5         | 0.27%   |
| 1920x540           | 4         | 0.22%   |
| 3000x2000          | 3         | 0.16%   |
| 2160x1440          | 3         | 0.16%   |
| 1400x1050          | 3         | 0.16%   |
| 3840x2400          | 2         | 0.11%   |
| 1360x768           | 2         | 0.11%   |
| 9600x2160          | 1         | 0.05%   |
| 720x1280           | 1         | 0.05%   |
| 7040x1440          | 1         | 0.05%   |
| 5760x2160          | 1         | 0.05%   |
| 5760x1080          | 1         | 0.05%   |
| 5440x1080          | 1         | 0.05%   |
| 4480x1080          | 1         | 0.05%   |
| 3840x1600          | 1         | 0.05%   |
| 3840x1200          | 1         | 0.05%   |
| 3840x1080          | 1         | 0.05%   |
| 3520x1080          | 1         | 0.05%   |
| 3456x2160          | 1         | 0.05%   |
| 3200x2000          | 1         | 0.05%   |
| 3120x2080          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 639       | 33.86%  |
| 13      | 582       | 30.84%  |
| 12      | 170       | 9.01%   |
| 17      | 76        | 4.03%   |
| 14      | 70        | 3.71%   |
| 11      | 61        | 3.23%   |
| 24      | 48        | 2.54%   |
| 27      | 42        | 2.23%   |
| Unknown | 39        | 2.07%   |
| 10      | 31        | 1.64%   |
| 23      | 28        | 1.48%   |
| 21      | 15        | 0.79%   |
| 19      | 14        | 0.74%   |
| 34      | 9         | 0.48%   |
| 31      | 9         | 0.48%   |
| 18      | 9         | 0.48%   |
| 9       | 6         | 0.32%   |
| 22      | 4         | 0.21%   |
| 64      | 3         | 0.16%   |
| 40      | 3         | 0.16%   |
| 29      | 3         | 0.16%   |
| 26      | 3         | 0.16%   |
| 20      | 3         | 0.16%   |
| 16      | 3         | 0.16%   |
| 42      | 2         | 0.11%   |
| 39      | 2         | 0.11%   |
| 54      | 1         | 0.05%   |
| 49      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 46      | 1         | 0.05%   |
| 43      | 1         | 0.05%   |
| 37      | 1         | 0.05%   |
| 35      | 1         | 0.05%   |
| 33      | 1         | 0.05%   |
| 32      | 1         | 0.05%   |
| 28      | 1         | 0.05%   |
| 8       | 1         | 0.05%   |
| 6       | 1         | 0.05%   |
| 5       | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1071      | 56.91%  |
| 201-300     | 490       | 26.04%  |
| 501-600     | 109       | 5.79%   |
| 351-400     | 80        | 4.25%   |
| 401-500     | 39        | 2.07%   |
| Unknown     | 39        | 2.07%   |
| 601-700     | 21        | 1.12%   |
| 701-800     | 11        | 0.58%   |
| 1001-1500   | 8         | 0.43%   |
| 801-900     | 7         | 0.37%   |
| 101-200     | 4         | 0.21%   |
| 901-1000    | 2         | 0.11%   |
| 1-100       | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1433      | 81.51%  |
| 16/10   | 209       | 11.89%  |
| Unknown | 37        | 2.1%    |
| 3/2     | 33        | 1.88%   |
| 4/3     | 15        | 0.85%   |
| 21/9    | 14        | 0.8%    |
| 5/4     | 12        | 0.68%   |
| 6/5     | 1         | 0.06%   |
| 3.18    | 1         | 0.06%   |
| 11/10   | 1         | 0.06%   |
| 1.96    | 1         | 0.06%   |
| 0.46    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 548       | 29.03%  |
| 91-100         | 498       | 26.38%  |
| 61-70          | 167       | 8.85%   |
| 101-110        | 144       | 7.63%   |
| 71-80          | 95        | 5.03%   |
| 201-250        | 85        | 4.5%    |
| 121-130        | 66        | 3.5%    |
| 51-60          | 60        | 3.18%   |
| 301-350        | 47        | 2.49%   |
| Unknown        | 39        | 2.07%   |
| 41-50          | 35        | 1.85%   |
| 351-500        | 22        | 1.17%   |
| 151-200        | 17        | 0.9%    |
| 141-150        | 14        | 0.74%   |
| 251-300        | 12        | 0.64%   |
| 111-120        | 11        | 0.58%   |
| 501-1000       | 11        | 0.58%   |
| 131-140        | 7         | 0.37%   |
| More than 1000 | 5         | 0.26%   |
| 1-40           | 5         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 793       | 42.52%  |
| 101-120       | 574       | 30.78%  |
| 51-100        | 235       | 12.6%   |
| 161-240       | 168       | 9.01%   |
| More than 240 | 53        | 2.84%   |
| Unknown       | 39        | 2.09%   |
| 1-50          | 3         | 0.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1844      | 67.72%  |
| 0     | 685       | 25.16%  |
| 2     | 185       | 6.79%   |
| 3     | 8         | 0.29%   |
| 4     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 1761      | 42.4%   |
| Realtek Semiconductor                  | 1021      | 24.58%  |
| Qualcomm Atheros                       | 513       | 12.35%  |
| Broadcom                               | 292       | 7.03%   |
| AMD                                    | 78        | 1.88%   |
| Marvell Technology Group               | 59        | 1.42%   |
| TP-Link                                | 36        | 0.87%   |
| Ralink Technology                      | 35        | 0.84%   |
| Ericsson Business Mobile Networks      | 33        | 0.79%   |
| Sierra Wireless                        | 32        | 0.77%   |
| Nvidia                                 | 26        | 0.63%   |
| Samsung Electronics                    | 25        | 0.6%    |
| Edimax Technology                      | 24        | 0.58%   |
| Ralink                                 | 23        | 0.55%   |
| MediaTek                               | 20        | 0.48%   |
| Xiaomi                                 | 17        | 0.41%   |
| Dell                                   | 15        | 0.36%   |
| Google                                 | 13        | 0.31%   |
| JMicron Technology                     | 12        | 0.29%   |
| Huawei Technologies                    | 10        | 0.24%   |
| Hewlett-Packard                        | 10        | 0.24%   |
| Silicon Integrated Systems [SiS]       | 8         | 0.19%   |
| NetGear                                | 8         | 0.19%   |
| D-Link System                          | 8         | 0.19%   |
| D-Link                                 | 7         | 0.17%   |
| Qualcomm Atheros Communications        | 6         | 0.14%   |
| ASUSTek Computer                       | 6         | 0.14%   |
| Qualcomm                               | 5         | 0.12%   |
| Apple                                  | 4         | 0.1%    |
| Fibocom                                | 3         | 0.07%   |
| VIA Technologies                       | 2         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.05%   |
| Realtek                                | 2         | 0.05%   |
| Qualcomm Technologies                  | 2         | 0.05%   |
| OPPO Electronics                       | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.05%   |
| Novatel Wireless                       | 2         | 0.05%   |
| Lenovo                                 | 2         | 0.05%   |
| BUFFALO                                | 2         | 0.05%   |
| Atheros                                | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 664       | 12.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 219       | 4.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 214       | 4.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 158       | 2.99%   |
| Intel Wireless 8265 / 8275                                              | 157       | 2.97%   |
| Intel Wireless 7265                                                     | 124       | 2.34%   |
| Intel Wireless 7260                                                     | 122       | 2.31%   |
| Intel Wireless 8260                                                     | 121       | 2.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 93        | 1.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 89        | 1.68%   |
| Intel Wi-Fi 6 AX200                                                     | 83        | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 80        | 1.51%   |
| AMD XGMAC 10GbE Controller                                              | 77        | 1.46%   |
| Intel Ethernet Connection I219-LM                                       | 71        | 1.34%   |
| Intel I210 Gigabit Network Connection                                   | 69        | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                                   | 62        | 1.17%   |
| Intel Wi-Fi 6 AX201                                                     | 59        | 1.12%   |
| Intel Ethernet Connection (3) I218-LM                                   | 56        | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 55        | 1.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 53        | 1%      |
| Intel 82577LM Gigabit Network Connection                                | 53        | 1%      |
| Intel Ethernet Connection I218-LM                                       | 50        | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 50        | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 46        | 0.87%   |
| Intel Wireless 3165                                                     | 45        | 0.85%   |
| Intel Ethernet Connection I217-LM                                       | 42        | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 0.77%   |
| Intel I211 Gigabit Network Connection                                   | 40        | 0.76%   |
| Intel Centrino Ultimate-N 6300                                          | 40        | 0.76%   |
| Intel 82567LM Gigabit Network Connection                                | 40        | 0.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 38        | 0.72%   |
| Intel Ethernet Connection (4) I219-V                                    | 38        | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 38        | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 37        | 0.7%    |
| Intel Wireless-AC 9260                                                  | 36        | 0.68%   |
| Intel Centrino Advanced-N 6200                                          | 34        | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 33        | 0.62%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 32        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 31        | 0.59%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 30        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1537      | 56.9%   |
| Qualcomm Atheros                | 449       | 16.62%  |
| Realtek Semiconductor           | 283       | 10.48%  |
| Broadcom                        | 222       | 8.22%   |
| TP-Link                         | 36        | 1.33%   |
| Ralink Technology               | 35        | 1.3%    |
| Edimax Technology               | 24        | 0.89%   |
| Sierra Wireless                 | 23        | 0.85%   |
| Ralink                          | 23        | 0.85%   |
| MediaTek                        | 17        | 0.63%   |
| NetGear                         | 8         | 0.3%    |
| Dell                            | 7         | 0.26%   |
| D-Link System                   | 7         | 0.26%   |
| D-Link                          | 7         | 0.26%   |
| Qualcomm Atheros Communications | 6         | 0.22%   |
| ASUSTek Computer                | 6         | 0.22%   |
| Qualcomm Technologies           | 2         | 0.07%   |
| BUFFALO                         | 2         | 0.07%   |
| Atheros                         | 2         | 0.07%   |
| Sagem                           | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Mercucys                        | 1         | 0.04%   |
| IMC Networks                    | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 158       | 5.78%   |
| Intel Wireless 8265 / 8275                                              | 157       | 5.74%   |
| Intel Wireless 7265                                                     | 124       | 4.53%   |
| Intel Wireless 7260                                                     | 122       | 4.46%   |
| Intel Wireless 8260                                                     | 121       | 4.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 93        | 3.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 89        | 3.25%   |
| Intel Wi-Fi 6 AX200                                                     | 83        | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 80        | 2.93%   |
| Intel Wi-Fi 6 AX201                                                     | 59        | 2.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 55        | 2.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 53        | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 50        | 1.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 46        | 1.68%   |
| Intel Wireless 3165                                                     | 45        | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 1.5%    |
| Intel Centrino Ultimate-N 6300                                          | 39        | 1.43%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 38        | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 38        | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 37        | 1.35%   |
| Intel Wireless-AC 9260                                                  | 36        | 1.32%   |
| Intel Centrino Advanced-N 6200                                          | 34        | 1.24%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 33        | 1.21%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 32        | 1.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 31        | 1.13%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 30        | 1.1%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 27        | 0.99%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 27        | 0.99%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 27        | 0.99%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 26        | 0.95%   |
| Intel Wireless 3160                                                     | 25        | 0.91%   |
| Intel WiFi Link 5100                                                    | 25        | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 25        | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 24        | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 24        | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 24        | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 24        | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 23        | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 23        | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 987       | 40.79%  |
| Realtek Semiconductor                  | 901       | 37.23%  |
| Qualcomm Atheros                       | 137       | 5.66%   |
| Broadcom                               | 125       | 5.17%   |
| AMD                                    | 77        | 3.18%   |
| Marvell Technology Group               | 59        | 2.44%   |
| Nvidia                                 | 26        | 1.07%   |
| Samsung Electronics                    | 25        | 1.03%   |
| Xiaomi                                 | 17        | 0.7%    |
| JMicron Technology                     | 12        | 0.5%    |
| Google                                 | 10        | 0.41%   |
| Silicon Integrated Systems [SiS]       | 7         | 0.29%   |
| Qualcomm                               | 5         | 0.21%   |
| Huawei Technologies                    | 4         | 0.17%   |
| MediaTek                               | 3         | 0.12%   |
| Apple                                  | 3         | 0.12%   |
| VIA Technologies                       | 2         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.08%   |
| Realtek                                | 2         | 0.08%   |
| OPPO Electronics                       | 2         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.08%   |
| Novatel Wireless                       | 2         | 0.08%   |
| Lenovo                                 | 2         | 0.08%   |
| National Semiconductor                 | 1         | 0.04%   |
| Motorola PCS                           | 1         | 0.04%   |
| Microsoft                              | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| HMD Global                             | 1         | 0.04%   |
| Attansic                               | 1         | 0.04%   |
| Aquantia                               | 1         | 0.04%   |
| 3Com                                   | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 664       | 27.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 219       | 8.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 214       | 8.77%   |
| AMD XGMAC 10GbE Controller                                        | 77        | 3.16%   |
| Intel Ethernet Connection I219-LM                                 | 71        | 2.91%   |
| Intel I210 Gigabit Network Connection                             | 69        | 2.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 62        | 2.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 56        | 2.3%    |
| Intel 82577LM Gigabit Network Connection                          | 53        | 2.17%   |
| Intel Ethernet Connection I218-LM                                 | 50        | 2.05%   |
| Intel Ethernet Connection I217-LM                                 | 42        | 1.72%   |
| Intel I211 Gigabit Network Connection                             | 40        | 1.64%   |
| Intel 82567LM Gigabit Network Connection                          | 40        | 1.64%   |
| Intel Ethernet Connection (4) I219-V                              | 38        | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 27        | 1.11%   |
| Nvidia MCP79 Ethernet                                             | 25        | 1.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 24        | 0.98%   |
| Intel 82566MM Gigabit Network Connection                          | 22        | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 20        | 0.82%   |
| Intel Ethernet Connection I219-V                                  | 19        | 0.78%   |
| Intel Ethernet Connection (6) I219-V                              | 18        | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 17        | 0.7%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 15        | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 14        | 0.57%   |
| Intel Ethernet Connection (6) I219-LM                             | 14        | 0.57%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 14        | 0.57%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 13        | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 13        | 0.53%   |
| Intel 82574L Gigabit Network Connection                           | 13        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12        | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 12        | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11        | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.45%   |
| Intel Ethernet Connection (3) I218-V                              | 11        | 0.45%   |
| Intel 82573L Gigabit Ethernet Controller                          | 11        | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 10        | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 9         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2449      | 50.65%  |
| Ethernet | 2269      | 46.93%  |
| Modem    | 63        | 1.3%    |
| Unknown  | 54        | 1.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1672      | 50.41%  |
| Ethernet | 1621      | 48.87%  |
| Modem    | 13        | 0.39%   |
| Unknown  | 11        | 0.33%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2012      | 76.01%  |
| 1     | 447       | 16.89%  |
| 6     | 69        | 2.61%   |
| 3     | 59        | 2.23%   |
| 5     | 35        | 1.32%   |
| 0     | 15        | 0.57%   |
| 8     | 4         | 0.15%   |
| 4     | 4         | 0.15%   |
| 10    | 1         | 0.04%   |
| 7     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2468      | 91.82%  |
| Yes  | 220       | 8.18%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 957       | 54.31%  |
| Broadcom                        | 177       | 10.05%  |
| Qualcomm Atheros Communications | 119       | 6.75%   |
| Realtek Semiconductor           | 102       | 5.79%   |
| Apple                           | 100       | 5.68%   |
| IMC Networks                    | 60        | 3.41%   |
| Foxconn / Hon Hai               | 55        | 3.12%   |
| Lite-On Technology              | 50        | 2.84%   |
| Dell                            | 35        | 1.99%   |
| Hewlett-Packard                 | 28        | 1.59%   |
| Alps Electric                   | 18        | 1.02%   |
| Cambridge Silicon Radio         | 17        | 0.96%   |
| ASUSTek Computer                | 16        | 0.91%   |
| Ralink                          | 9         | 0.51%   |
| Skylight Digital                | 6         | 0.34%   |
| Toshiba                         | 2         | 0.11%   |
| Taiyo Yuden                     | 2         | 0.11%   |
| Creative Technology             | 2         | 0.11%   |
| USI                             | 1         | 0.06%   |
| TP-Link                         | 1         | 0.06%   |
| Ralink Technology               | 1         | 0.06%   |
| Opticis                         | 1         | 0.06%   |
| Fujitsu                         | 1         | 0.06%   |
| Esel International              | 1         | 0.06%   |
| Askey Computer                  | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 490       | 27.75%  |
| Intel AX201 Bluetooth                                       | 135       | 7.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 113       | 6.4%    |
| Intel AX200 Bluetooth                                       | 80        | 4.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 60        | 3.4%    |
| Apple Bluetooth Host Controller                             | 55        | 3.11%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 54        | 3.06%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 34        | 1.93%   |
| Realtek Bluetooth Adapter                                   | 33        | 1.87%   |
| Intel Wireless-AC 3168 Bluetooth                            | 31        | 1.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 29        | 1.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 25        | 1.42%   |
| Intel AX210 Bluetooth                                       | 24        | 1.36%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 23        | 1.3%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 18        | 1.02%   |
| Lite-On Atheros AR3012 Bluetooth                            | 17        | 0.96%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 17        | 0.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 17        | 0.96%   |
| Apple Broadcom Built-in Bluetooth                           | 17        | 0.96%   |
| Realtek  Bluetooth 4.2 Adapter                              | 16        | 0.91%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 16        | 0.91%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 14        | 0.79%   |
| Dell DW375 Bluetooth Module                                 | 14        | 0.79%   |
| Apple Built-in iSight (no firmware loaded)                  | 14        | 0.79%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 13        | 0.74%   |
| Realtek Bluetooth 4.0 Adapter                               | 12        | 0.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 12        | 0.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 12        | 0.68%   |
| IMC Networks Realtek Bluetooth Adapter                      | 12        | 0.68%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 12        | 0.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 12        | 0.68%   |
| Alps Electric UGTZ4 Bluetooth                               | 12        | 0.68%   |
| Realtek RTL8723B Bluetooth                                  | 10        | 0.57%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 10        | 0.57%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 10        | 0.57%   |
| Ralink RT3290 Bluetooth                                     | 9         | 0.51%   |
| Intel AX211 Bluetooth                                       | 9         | 0.51%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 9         | 0.51%   |
| HP Broadcom 2070 Bluetooth Combo                            | 9         | 0.51%   |
| Realtek RTL8821A Bluetooth                                  | 8         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2178      | 74.77%  |
| AMD                                          | 429       | 14.73%  |
| Nvidia                                       | 200       | 6.87%   |
| Lenovo                                       | 15        | 0.51%   |
| Realtek Semiconductor                        | 9         | 0.31%   |
| Silicon Integrated Systems [SiS]             | 8         | 0.27%   |
| Texas Instruments                            | 7         | 0.24%   |
| Logitech                                     | 7         | 0.24%   |
| GN Netcom                                    | 7         | 0.24%   |
| C-Media Electronics                          | 7         | 0.24%   |
| ASUSTek Computer                             | 4         | 0.14%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.1%    |
| SteelSeries ApS                              | 3         | 0.1%    |
| Plantronics                                  | 3         | 0.1%    |
| Kingston Technology                          | 3         | 0.1%    |
| Generalplus Technology                       | 3         | 0.1%    |
| Creative Technology                          | 3         | 0.1%    |
| VIA Technologies                             | 2         | 0.07%   |
| JMTek                                        | 2         | 0.07%   |
| ESS Technology                               | 2         | 0.07%   |
| CMX Systems                                  | 2         | 0.07%   |
| XMOS                                         | 1         | 0.03%   |
| ULi Electronics                              | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.03%   |
| Sony                                         | 1         | 0.03%   |
| RODE Microphones                             | 1         | 0.03%   |
| PS Audio                                     | 1         | 0.03%   |
| Phison Electronics                           | 1         | 0.03%   |
| Microsoft                                    | 1         | 0.03%   |
| M-Audio                                      | 1         | 0.03%   |
| Hewlett-Packard                              | 1         | 0.03%   |
| Elitegroup Computer Systems (ECS)            | 1         | 0.03%   |
| DSEA A/S                                     | 1         | 0.03%   |
| Conexant Systems                             | 1         | 0.03%   |
| Cambridge Silicon Radio                      | 1         | 0.03%   |
| Cambridge Audio                              | 1         | 0.03%   |
| Blue Microphones                             | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 351       | 9.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 278       | 7.84%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 218       | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 203       | 5.72%   |
| Intel 8 Series HD Audio Controller                                                                | 166       | 4.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 165       | 4.65%   |
| Intel Broadwell-U Audio Controller                                                                | 139       | 3.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 133       | 3.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 116       | 3.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 113       | 3.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 98        | 2.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 93        | 2.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 77        | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 72        | 2.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 69        | 1.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 69        | 1.95%   |
| Intel Cannon Lake PCH cAVS                                                                        | 66        | 1.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 61        | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 60        | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 60        | 1.69%   |
| AMD FCH Azalia Controller                                                                         | 56        | 1.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 44        | 1.24%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 43        | 1.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 40        | 1.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 37        | 1.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 34        | 0.96%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 33        | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 32        | 0.9%    |
| Intel CM238 HD Audio Controller                                                                   | 30        | 0.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 30        | 0.85%   |
| Nvidia MCP79 High Definition Audio                                                                | 28        | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 27        | 0.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 22        | 0.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 20        | 0.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 20        | 0.56%   |
| AMD Wrestler HDMI Audio                                                                           | 19        | 0.54%   |
| AMD High Definition Audio Controller                                                              | 19        | 0.54%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 17        | 0.48%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 16        | 0.45%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 13        | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 768       | 26.92%  |
| SK hynix            | 578       | 20.26%  |
| Micron Technology   | 287       | 10.06%  |
| Kingston            | 244       | 8.55%   |
| Unknown             | 215       | 7.54%   |
| Crucial             | 122       | 4.28%   |
| Transcend           | 96        | 3.36%   |
| Unknown             | 80        | 2.8%    |
| Elpida              | 69        | 2.42%   |
| Ramaxel Technology  | 62        | 2.17%   |
| A-DATA Technology   | 46        | 1.61%   |
| Nanya Technology    | 40        | 1.4%    |
| Corsair             | 33        | 1.16%   |
| Smart               | 29        | 1.02%   |
| G.Skill             | 22        | 0.77%   |
| Team                | 15        | 0.53%   |
| Unknown (ABCD)      | 14        | 0.49%   |
| 48spaces            | 9         | 0.32%   |
| PNY                 | 8         | 0.28%   |
| GOODRAM             | 8         | 0.28%   |
| Apacer              | 8         | 0.28%   |
| Teikon              | 7         | 0.25%   |
| Avant               | 6         | 0.21%   |
| ASint Technology    | 6         | 0.21%   |
| Smart Brazil        | 5         | 0.18%   |
| Patriot             | 5         | 0.18%   |
| Neo Forza           | 5         | 0.18%   |
| High Bridge         | 5         | 0.18%   |
| Goldkey             | 4         | 0.14%   |
| SHARETRONIC         | 3         | 0.11%   |
| Magnum Tech         | 3         | 0.11%   |
| V-GeN               | 2         | 0.07%   |
| Toshiba             | 2         | 0.07%   |
| Super Talent        | 2         | 0.07%   |
| Silicon Power       | 2         | 0.07%   |
| Sesame              | 2         | 0.07%   |
| PUSKILL             | 2         | 0.07%   |
| Multilaser          | 2         | 0.07%   |
| KomputerBay         | 2         | 0.07%   |
| GSkill              | 2         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 80        | 2.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 52        | 1.71%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 45        | 1.48%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 44        | 1.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 43        | 1.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 42        | 1.38%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 40        | 1.31%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 35        | 1.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 35        | 1.15%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 31        | 1.02%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 29        | 0.95%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 27        | 0.89%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 26        | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.82%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 24        | 0.79%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM 1600MT/s                 | 23        | 0.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 21        | 0.69%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 20        | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 19        | 0.62%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.59%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.56%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s            | 16        | 0.53%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 16        | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 16        | 0.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.46%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 14        | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 14        | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 13        | 0.43%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 13        | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 13        | 0.43%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s              | 13        | 0.43%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 13        | 0.43%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 13        | 0.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.43%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 13        | 0.43%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 13        | 0.43%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1136      | 47.29%  |
| DDR4    | 845       | 35.18%  |
| DDR2    | 186       | 7.74%   |
| LPDDR3  | 68        | 2.83%   |
| LPDDR4  | 52        | 2.16%   |
| Unknown | 30        | 1.25%   |
| DDR     | 29        | 1.21%   |
| SDRAM   | 21        | 0.87%   |
| DDR5    | 13        | 0.54%   |
| LPDDR5  | 10        | 0.42%   |
| DRAM    | 9         | 0.37%   |
| RAM     | 2         | 0.08%   |
| SRAM    | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2211      | 91.51%  |
| Row Of Chips | 122       | 5.05%   |
| Chip         | 51        | 2.11%   |
| Unknown      | 18        | 0.75%   |
| DIMM         | 14        | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 904       | 33.96%  |
| 4096  | 883       | 33.17%  |
| 2048  | 462       | 17.36%  |
| 16384 | 255       | 9.58%   |
| 1024  | 94        | 3.53%   |
| 32768 | 39        | 1.47%   |
| 512   | 16        | 0.6%    |
| 256   | 6         | 0.23%   |
| 128   | 2         | 0.08%   |
| 2560  | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 716       | 27.54%  |
| 2667    | 338       | 13%     |
| 1333    | 238       | 9.15%   |
| 2400    | 233       | 8.96%   |
| 3200    | 220       | 8.46%   |
| 2133    | 159       | 6.12%   |
| 1334    | 143       | 5.5%    |
| 667     | 126       | 4.85%   |
| 1067    | 79        | 3.04%   |
| Unknown | 77        | 2.96%   |
| 1867    | 67        | 2.58%   |
| 800     | 59        | 2.27%   |
| 4267    | 26        | 1%      |
| 533     | 23        | 0.88%   |
| 1066    | 20        | 0.77%   |
| 4800    | 12        | 0.46%   |
| 975     | 12        | 0.46%   |
| 6400    | 8         | 0.31%   |
| 4266    | 7         | 0.27%   |
| 2048    | 6         | 0.23%   |
| 1866    | 5         | 0.19%   |
| 1200    | 4         | 0.15%   |
| 3733    | 3         | 0.12%   |
| 333     | 3         | 0.12%   |
| 2933    | 2         | 0.08%   |
| 1639    | 2         | 0.08%   |
| 400     | 2         | 0.08%   |
| 266     | 2         | 0.08%   |
| 166     | 2         | 0.08%   |
| 5600    | 1         | 0.04%   |
| 2666    | 1         | 0.04%   |
| 1596    | 1         | 0.04%   |
| 666     | 1         | 0.04%   |
| 200     | 1         | 0.04%   |
| 100     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| ELGIN               | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Prolific Technology | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| ELGIN L42PRO                       | 2         | 40%     |
| Samsung ML-1610 Mono Laser Printer | 1         | 20%     |
| Prolific PL2305 Parallel Port      | 1         | 20%     |
| HP LaserJet 1020                   | 1         | 20%     |

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
| Chicony Electronics                    | 547       | 29.66%  |
| Bison Electronics                      | 208       | 11.28%  |
| IMC Networks                           | 180       | 9.76%   |
| Realtek Semiconductor                  | 158       | 8.57%   |
| Microdia                               | 154       | 8.35%   |
| Sunplus Innovation Technology          | 103       | 5.59%   |
| Suyin                                  | 65        | 3.52%   |
| Lite-On Technology                     | 62        | 3.36%   |
| Syntek                                 | 43        | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) | 43        | 2.33%   |
| Quanta                                 | 39        | 2.11%   |
| Apple                                  | 32        | 1.74%   |
| Silicon Motion                         | 28        | 1.52%   |
| Lenovo                                 | 26        | 1.41%   |
| Luxvisions Innotech Limited            | 25        | 1.36%   |
| Alcor Micro                            | 24        | 1.3%    |
| ALi                                    | 15        | 0.81%   |
| Z-Star Microelectronics                | 11        | 0.6%    |
| Ricoh                                  | 11        | 0.6%    |
| Logitech                               | 11        | 0.6%    |
| Importek                               | 10        | 0.54%   |
| Supreme Electronics                    | 5         | 0.27%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.27%   |
| Primax Electronics                     | 4         | 0.22%   |
| Intel                                  | 4         | 0.22%   |
| Tripath Technology                     | 3         | 0.16%   |
| OmniVision Technologies                | 3         | 0.16%   |
| Jiangxi Shinetech Optical              | 3         | 0.16%   |
| DigiTech                               | 3         | 0.16%   |
| USB Camera                             | 2         | 0.11%   |
| Unknown                                | 2         | 0.11%   |
| Pixart Imaging                         | 2         | 0.11%   |
| Genesys Logic                          | 2         | 0.11%   |
| Cubeternet                             | 2         | 0.11%   |
| Y Media                                | 1         | 0.05%   |
| SunplusIT                              | 1         | 0.05%   |
| SIMPLO Technology                      | 1         | 0.05%   |
| Qtech                                  | 1         | 0.05%   |
| Nanchang BYD Electronics               | 1         | 0.05%   |
| Goodong Industry                       | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 168       | 9.02%   |
| Bison Integrated Camera                       | 95        | 5.1%    |
| IMC Networks Integrated Camera                | 59        | 3.17%   |
| Microdia Integrated_Webcam_HD                 | 45        | 2.42%   |
| Realtek Integrated_Webcam_HD                  | 41        | 2.2%    |
| Lite-On Integrated Camera                     | 41        | 2.2%    |
| Chicony Lenovo Integrated Camera (0.3MP)      | 38        | 2.04%   |
| Microdia Integrated Webcam                    | 37        | 1.99%   |
| Chicony HD WebCam                             | 37        | 1.99%   |
| Sunplus Integrated_Webcam_HD                  | 32        | 1.72%   |
| Realtek USB 2.0 PC Camera                     | 26        | 1.4%    |
| Chicony Integrated Camera (1280x720@30)       | 26        | 1.4%    |
| Bison Lenovo EasyCamera                       | 24        | 1.29%   |
| IMC Networks Realtek PC Camera                | 20        | 1.07%   |
| Apple FaceTime HD Camera                      | 20        | 1.07%   |
| IMC Networks EasyCamera                       | 19        | 1.02%   |
| Chicony Integrated Camera [ThinkPad]          | 19        | 1.02%   |
| Bison SunplusIT Integrated Camera             | 19        | 1.02%   |
| Syntek Lenovo EasyCamera                      | 16        | 0.86%   |
| Lenovo Integrated Webcam [R5U877]             | 15        | 0.81%   |
| Chicony Realtek DMFT RGB                      | 15        | 0.81%   |
| Chicony Integrated IR Camera                  | 15        | 0.81%   |
| Bison ThinkPad Integrated Camera              | 15        | 0.81%   |
| Realtek USB Camera                            | 14        | 0.75%   |
| Chicony HP HD Webcam [Fixed]                  | 14        | 0.75%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 13        | 0.7%    |
| Syntek Integrated Camera                      | 12        | 0.64%   |
| Syntek EasyCamera                             | 12        | 0.64%   |
| Luxvisions Innotech Limited Integrated Camera | 12        | 0.64%   |
| Chicony Lenovo EasyCamera                     | 12        | 0.64%   |
| Chicony FJ Camera                             | 12        | 0.64%   |
| Chicony Chicony USB2.0 Camera                 | 12        | 0.64%   |
| Bison Lenovo Integrated Webcam                | 12        | 0.64%   |
| Microdia Dell Laptop Integrated Webcam HD     | 11        | 0.59%   |
| IMC Networks UVC VGA Webcam                   | 11        | 0.59%   |
| Bison HD Webcam                               | 11        | 0.59%   |
| IMC Networks Realtek DMFT RGB                 | 10        | 0.54%   |
| IMC Networks Integrated Webcam                | 10        | 0.54%   |
| Chicony USB2.0 VGA UVC WebCam                 | 10        | 0.54%   |
| Chicony ThinkPad T490 Webcam                  | 10        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 195       | 37.21%  |
| Synaptics                  | 98        | 18.7%   |
| Upek                       | 62        | 11.83%  |
| AuthenTec                  | 45        | 8.59%   |
| Shenzhen Goodix Technology | 42        | 8.02%   |
| STMicroelectronics         | 29        | 5.53%   |
| Broadcom                   | 18        | 3.44%   |
| LighTuning Technology      | 13        | 2.48%   |
| Elan Microelectronics      | 13        | 2.48%   |
| FocalTech Systems          | 5         | 0.95%   |
| Samsung Electronics        | 2         | 0.38%   |
| Next Biometrics            | 1         | 0.19%   |
| Fingerprint Cards          | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 66        | 12.6%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 59        | 11.26%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 42        | 8.02%   |
| Validity Sensors Synaptics WBDI                                              | 32        | 6.11%   |
| Shenzhen Goodix Fingerprint Reader                                           | 31        | 5.92%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 29        | 5.53%   |
| STMicroelectronics Fingerprint Reader                                        | 29        | 5.53%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 23        | 4.39%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 19        | 3.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 3.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 16        | 3.05%   |
| AuthenTec AES2810                                                            | 14        | 2.67%   |
| Elan Fingerprint Sensor                                                      | 13        | 2.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 11        | 2.1%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 8         | 1.53%   |
| AuthenTec AES1660                                                            | 8         | 1.53%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 7         | 1.34%   |
| Shenzhen Goodix  Fingerprint Device                                          | 7         | 1.34%   |
| Validity Sensors VFS491                                                      | 6         | 1.15%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 6         | 1.15%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 6         | 1.15%   |
| AuthenTec AES1600                                                            | 6         | 1.15%   |
| Validity Sensors Fingerprint scanner                                         | 5         | 0.95%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 4         | 0.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 4         | 0.76%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 4         | 0.76%   |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 4         | 0.76%   |
| Synaptics WBDI                                                               | 4         | 0.76%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 4         | 0.76%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 4         | 0.76%   |
| FocalTech Systems Fingerprint Reader                                         | 4         | 0.76%   |
| Validity Sensors VFS101 Fingerprint Reader                                   | 3         | 0.57%   |
| Validity Sensors VFS Fingerprint sensor                                      | 3         | 0.57%   |
| Upek TCS5B Fingerprint sensor                                                | 3         | 0.57%   |
| AuthenTec AES2660                                                            | 3         | 0.57%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 2         | 0.38%   |
| Synaptics UWP WBDI Device                                                    | 2         | 0.38%   |
| Samsung CanvasBio Fingerprint Reader                                         | 2         | 0.38%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 2         | 0.38%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 0.19%   |

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
| 1     | 916       | 33%     |
| 2     | 785       | 28.28%  |
| 3     | 435       | 15.67%  |
| 0     | 393       | 14.16%  |
| 4     | 180       | 6.48%   |
| 5     | 46        | 1.66%   |
| 6     | 14        | 0.5%    |
| 7     | 5         | 0.18%   |
| 9     | 1         | 0.04%   |
| 8     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1829      | 42.1%   |
| Bluetooth                | 604       | 13.9%   |
| Net/wireless             | 508       | 11.69%  |
| Card reader              | 505       | 11.63%  |
| Fingerprint reader       | 446       | 10.27%  |
| Firewire controller      | 176       | 4.05%   |
| Graphics card            | 78        | 1.8%    |
| Sound                    | 50        | 1.15%   |
| Storage                  | 46        | 1.06%   |
| Network                  | 40        | 0.92%   |
| Modem                    | 24        | 0.55%   |
| Net/ethernet             | 20        | 0.46%   |
| Storage/ata              | 9         | 0.21%   |
| Storage/raid             | 3         | 0.07%   |
| Storage/nvme             | 2         | 0.05%   |
| Storage/ide              | 2         | 0.05%   |
| Dvb card                 | 2         | 0.05%   |

