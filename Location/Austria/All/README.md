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

Total: 542

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [a5bbf2798d](https://bsd-hardware.info/?probe=a5bbf2798d) | Jan 02, 2026 |
| Protectli     | VP2420                      | Desktop     | [4484909d41](https://bsd-hardware.info/?probe=4484909d41) | Jan 02, 2026 |
| Deciso        | NetBoard-A20                | Notebook    | [06217f37f3](https://bsd-hardware.info/?probe=06217f37f3) | Dec 22, 2025 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [8131ecd9da](https://bsd-hardware.info/?probe=8131ecd9da) | Dec 21, 2025 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c88818f69d](https://bsd-hardware.info/?probe=c88818f69d) | Dec 20, 2025 |
| ASRock        | Q1900-ITX                   | Desktop     | [acb81d8969](https://bsd-hardware.info/?probe=acb81d8969) | Dec 18, 2025 |
| Unknown       | QDNV01                      | Desktop     | [8eb6ab2620](https://bsd-hardware.info/?probe=8eb6ab2620) | Dec 16, 2025 |
| Unknown       | QDNV01                      | Desktop     | [90f4b107ea](https://bsd-hardware.info/?probe=90f4b107ea) | Dec 16, 2025 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [116062e3c7](https://bsd-hardware.info/?probe=116062e3c7) | Dec 15, 2025 |
| Unknown       | Unknown                     | Desktop     | [c691b0e51d](https://bsd-hardware.info/?probe=c691b0e51d) | Dec 11, 2025 |
| ASUSTek       | PL64                        | Mini pc     | [bb33f74dca](https://bsd-hardware.info/?probe=bb33f74dca) | Dec 08, 2025 |
| Trigkey       | Key N                       | Mini pc     | [bd385dd978](https://bsd-hardware.info/?probe=bd385dd978) | Dec 05, 2025 |
| Unknown       | Unknown                     | Desktop     | [29df952d4a](https://bsd-hardware.info/?probe=29df952d4a) | Nov 28, 2025 |
| Unknown       | Unknown                     | Desktop     | [9649d80895](https://bsd-hardware.info/?probe=9649d80895) | Nov 27, 2025 |
| Unknown       | Unknown                     | Desktop     | [c9aa3f5191](https://bsd-hardware.info/?probe=c9aa3f5191) | Nov 22, 2025 |
| Unknown       | J3160-4L                    | Desktop     | [5f628c632b](https://bsd-hardware.info/?probe=5f628c632b) | Nov 09, 2025 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [a442ce289f](https://bsd-hardware.info/?probe=a442ce289f) | Nov 09, 2025 |
| Shuttle       | FH170                       | Desktop     | [f11cadf088](https://bsd-hardware.info/?probe=f11cadf088) | Nov 06, 2025 |
| KEBA          | CP505_BIOS_01.03            | Desktop     | [2a633926d0](https://bsd-hardware.info/?probe=2a633926d0) | Nov 03, 2025 |
| Unknown       | Unknown                     | Desktop     | [badddca379](https://bsd-hardware.info/?probe=badddca379) | Oct 31, 2025 |
| Advantech     | NAMB-T012MB A101            | Desktop     | [707d01496d](https://bsd-hardware.info/?probe=707d01496d) | Oct 31, 2025 |
| Supermicro    | A1SRM-2758F                 | Server      | [828badf4d0](https://bsd-hardware.info/?probe=828badf4d0) | Oct 23, 2025 |
| Supermicro    | A1SRM-2758F                 | Server      | [5bdad8d14f](https://bsd-hardware.info/?probe=5bdad8d14f) | Oct 23, 2025 |
| Supermicro    | X7SPA-H                     | Desktop     | [12ad7b8f29](https://bsd-hardware.info/?probe=12ad7b8f29) | Oct 19, 2025 |
| KEBA          | CP505_BIOS_01.03            | Desktop     | [8ea204f91f](https://bsd-hardware.info/?probe=8ea204f91f) | Oct 17, 2025 |
| ASRockRack    | X570D4U                     | Server      | [bf7d9b2d0c](https://bsd-hardware.info/?probe=bf7d9b2d0c) | Oct 12, 2025 |
| Unknown       | Unknown                     | Desktop     | [e9474a54d3](https://bsd-hardware.info/?probe=e9474a54d3) | Oct 07, 2025 |
| PC Engines    | APU2                        | Desktop     | [d97d5f0270](https://bsd-hardware.info/?probe=d97d5f0270) | Sep 28, 2025 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [f0a8ec4c1e](https://bsd-hardware.info/?probe=f0a8ec4c1e) | Sep 21, 2025 |
| PC Engines    | apu4                        | Desktop     | [c4a7907774](https://bsd-hardware.info/?probe=c4a7907774) | Sep 19, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [ed91a1d13e](https://bsd-hardware.info/?probe=ed91a1d13e) | Sep 18, 2025 |
| Lenovo        | ThinkPad T420 4236PGG       | Notebook    | [a29d54028d](https://bsd-hardware.info/?probe=a29d54028d) | Sep 12, 2025 |
| Unknown       | Unknown                     | Desktop     | [7da1ee8005](https://bsd-hardware.info/?probe=7da1ee8005) | Sep 04, 2025 |
| Unknown       | Unknown                     | Desktop     | [e80a8e0bf6](https://bsd-hardware.info/?probe=e80a8e0bf6) | Sep 04, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [46da47e328](https://bsd-hardware.info/?probe=46da47e328) | Aug 25, 2025 |
| Unknown       | YL-J3160L4                  | Desktop     | [bc11a79847](https://bsd-hardware.info/?probe=bc11a79847) | Aug 24, 2025 |
| KEBA          | CP505_BIOS_01.03            | Desktop     | [0762924857](https://bsd-hardware.info/?probe=0762924857) | Aug 20, 2025 |
| Unknown       | Unknown                     | Desktop     | [4033c541b0](https://bsd-hardware.info/?probe=4033c541b0) | Aug 20, 2025 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [c974569ce6](https://bsd-hardware.info/?probe=c974569ce6) | Aug 14, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [b1605aa260](https://bsd-hardware.info/?probe=b1605aa260) | Aug 14, 2025 |
| Deciso        | NetBoard-A20                | Notebook    | [29c55af4bd](https://bsd-hardware.info/?probe=29c55af4bd) | Aug 13, 2025 |
| Raspberry ... | Raspberry Pi                | Soc         | [c60bcb30f4](https://bsd-hardware.info/?probe=c60bcb30f4) | Aug 11, 2025 |
| Raspberry ... | Raspberry Pi                | Soc         | [ca88befdff](https://bsd-hardware.info/?probe=ca88befdff) | Aug 11, 2025 |
| Gigabyte      | B365M DS3H                  | Desktop     | [fa0753c30d](https://bsd-hardware.info/?probe=fa0753c30d) | Aug 08, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [99124c137a](https://bsd-hardware.info/?probe=99124c137a) | Aug 04, 2025 |
| Lenovo        | ThinkPad T430 2347H76       | Notebook    | [84bb1f6dc9](https://bsd-hardware.info/?probe=84bb1f6dc9) | Aug 02, 2025 |
| PC Engines    | APU2                        | Desktop     | [04187d0e44](https://bsd-hardware.info/?probe=04187d0e44) | Aug 01, 2025 |
| Unknown       | Unknown                     | Desktop     | [5d9b70f9b3](https://bsd-hardware.info/?probe=5d9b70f9b3) | Jul 29, 2025 |
| Unknown       | Unknown                     | Desktop     | [33c00c1b14](https://bsd-hardware.info/?probe=33c00c1b14) | Jul 23, 2025 |
| Gigabyte      | B365M DS3H                  | Desktop     | [fc4b20232a](https://bsd-hardware.info/?probe=fc4b20232a) | Jul 20, 2025 |
| HP            | Compaq 8000 Elite CMT PC    | Desktop     | [55dce3d3b6](https://bsd-hardware.info/?probe=55dce3d3b6) | Jul 17, 2025 |
| Unknown       | Unknown                     | Desktop     | [3b3e04c891](https://bsd-hardware.info/?probe=3b3e04c891) | Jul 17, 2025 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [b716deca5e](https://bsd-hardware.info/?probe=b716deca5e) | Jul 14, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [afc0b4763b](https://bsd-hardware.info/?probe=afc0b4763b) | Jul 12, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [353a524eb8](https://bsd-hardware.info/?probe=353a524eb8) | Jul 10, 2025 |
| Protectli     | FW6 Ver                     | Desktop     | [b3da12e3ad](https://bsd-hardware.info/?probe=b3da12e3ad) | Jul 10, 2025 |
| Lenovo        | ThinkPad T430 2347H76       | Notebook    | [74c977c0d0](https://bsd-hardware.info/?probe=74c977c0d0) | Jul 06, 2025 |
| XtReAmEr      | Unknown                     | Desktop     | [89994ef7a1](https://bsd-hardware.info/?probe=89994ef7a1) | Jun 24, 2025 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [df09b5c1ba](https://bsd-hardware.info/?probe=df09b5c1ba) | Jun 22, 2025 |
| Deciso        | NetBoard-A10 Gen.3          | Notebook    | [023b220776](https://bsd-hardware.info/?probe=023b220776) | Jun 21, 2025 |
| Lenovo        | ThinkPad T440p 20AWS4FB0... | Notebook    | [e04c5c639b](https://bsd-hardware.info/?probe=e04c5c639b) | Jun 09, 2025 |
| PC Engines    | APU2                        | Desktop     | [6910deed6d](https://bsd-hardware.info/?probe=6910deed6d) | Jun 02, 2025 |
| Unknown       | Unknown                     | Notebook    | [125098edef](https://bsd-hardware.info/?probe=125098edef) | Jun 01, 2025 |
| PC Engines    | APU2                        | Desktop     | [3d2951b09c](https://bsd-hardware.info/?probe=3d2951b09c) | May 26, 2025 |
| PC Engines    | APU2                        | Desktop     | [cdffd2a69b](https://bsd-hardware.info/?probe=cdffd2a69b) | May 25, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2a723a4eba](https://bsd-hardware.info/?probe=2a723a4eba) | May 23, 2025 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [abddc46806](https://bsd-hardware.info/?probe=abddc46806) | May 21, 2025 |
| Unknown       | Unknown                     | Desktop     | [2bdfcdbeb4](https://bsd-hardware.info/?probe=2bdfcdbeb4) | May 19, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7990014758](https://bsd-hardware.info/?probe=7990014758) | May 05, 2025 |
| Sophos        | SG                          | Firewall    | [59bd524d65](https://bsd-hardware.info/?probe=59bd524d65) | May 04, 2025 |
| Sophos        | SG                          | Firewall    | [d3c549317c](https://bsd-hardware.info/?probe=d3c549317c) | May 03, 2025 |
| Deciso        | NetBoard-A20                | Notebook    | [c25601af23](https://bsd-hardware.info/?probe=c25601af23) | May 01, 2025 |
| HP            | 8158 A01                    | Mini pc     | [d191f00a78](https://bsd-hardware.info/?probe=d191f00a78) | Apr 25, 2025 |
| ASRock        | J4105-ITX                   | Desktop     | [0d27aa2971](https://bsd-hardware.info/?probe=0d27aa2971) | Apr 23, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [3e4e3c0f0b](https://bsd-hardware.info/?probe=3e4e3c0f0b) | Apr 23, 2025 |
| SJRC          | ADLN-6L                     | Desktop     | [31cec72f4b](https://bsd-hardware.info/?probe=31cec72f4b) | Apr 20, 2025 |
| Dell          | 0T7D40 A01                  | Desktop     | [1fbea4adab](https://bsd-hardware.info/?probe=1fbea4adab) | Apr 20, 2025 |
| Cisco         | ASA5525 A0                  | Desktop     | [469a0b425f](https://bsd-hardware.info/?probe=469a0b425f) | Apr 16, 2025 |
| Cisco         | ASA5525 A0                  | Desktop     | [1d5ee001ba](https://bsd-hardware.info/?probe=1d5ee001ba) | Apr 16, 2025 |
| PC Engines    | APU3                        | Desktop     | [2d3330a447](https://bsd-hardware.info/?probe=2d3330a447) | Apr 11, 2025 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [62eac0ae06](https://bsd-hardware.info/?probe=62eac0ae06) | Apr 09, 2025 |
| Gigabyte      | B650I AX                    | Desktop     | [0943d0a6f3](https://bsd-hardware.info/?probe=0943d0a6f3) | Apr 05, 2025 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [c985c42149](https://bsd-hardware.info/?probe=c985c42149) | Apr 03, 2025 |
| Unknown       | Unknown                     | Desktop     | [44baf5b1a9](https://bsd-hardware.info/?probe=44baf5b1a9) | Apr 01, 2025 |
| Unknown       | Unknown                     | Desktop     | [4b3254de12](https://bsd-hardware.info/?probe=4b3254de12) | Mar 31, 2025 |
| ASRock        | QC5000-ITX/PH               | Desktop     | [6f0e81baa8](https://bsd-hardware.info/?probe=6f0e81baa8) | Mar 29, 2025 |
| SJRC          | ADLN-6L                     | Desktop     | [fd692ed504](https://bsd-hardware.info/?probe=fd692ed504) | Mar 28, 2025 |
| Unknown       | Unknown                     | Desktop     | [6c7aa89210](https://bsd-hardware.info/?probe=6c7aa89210) | Mar 27, 2025 |
| Unknown       | Unknown                     | Desktop     | [af1ed787cb](https://bsd-hardware.info/?probe=af1ed787cb) | Mar 21, 2025 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [b70f43e5ef](https://bsd-hardware.info/?probe=b70f43e5ef) | Mar 20, 2025 |
| Unknown       | Unknown                     | Desktop     | [6922a92985](https://bsd-hardware.info/?probe=6922a92985) | Mar 20, 2025 |
| Unknown       | Unknown                     | Desktop     | [7029156a31](https://bsd-hardware.info/?probe=7029156a31) | Mar 18, 2025 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [1520623759](https://bsd-hardware.info/?probe=1520623759) | Mar 12, 2025 |
| Dell          | 00F82W A01                  | Desktop     | [3b2c9eff89](https://bsd-hardware.info/?probe=3b2c9eff89) | Mar 10, 2025 |
| ASRock        | J4105-ITX                   | Desktop     | [93813c620a](https://bsd-hardware.info/?probe=93813c620a) | Mar 03, 2025 |
| PC Engines    | APU2                        | Desktop     | [a768be5c92](https://bsd-hardware.info/?probe=a768be5c92) | Feb 28, 2025 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [25c180967a](https://bsd-hardware.info/?probe=25c180967a) | Feb 20, 2025 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [19788aa01d](https://bsd-hardware.info/?probe=19788aa01d) | Feb 16, 2025 |
| PC Engines    | APU2                        | Desktop     | [f2a291c09b](https://bsd-hardware.info/?probe=f2a291c09b) | Feb 10, 2025 |
| ASRock        | J4105-ITX                   | Desktop     | [d825e90c38](https://bsd-hardware.info/?probe=d825e90c38) | Feb 10, 2025 |
| KEBA          | CP505_BIOS_01.03            | Desktop     | [b4a568dfcf](https://bsd-hardware.info/?probe=b4a568dfcf) | Feb 07, 2025 |
| Sophos        | XG                          | Firewall    | [75d7e67a93](https://bsd-hardware.info/?probe=75d7e67a93) | Feb 02, 2025 |
| CncTion       | N5105-4L B0                 | Desktop     | [6677396a66](https://bsd-hardware.info/?probe=6677396a66) | Feb 01, 2025 |
| KEBA          | CP505_BIOS_01.03            | Desktop     | [4d92746f67](https://bsd-hardware.info/?probe=4d92746f67) | Jan 31, 2025 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [937101cc19](https://bsd-hardware.info/?probe=937101cc19) | Jan 30, 2025 |
| Unknown       | Unknown                     | Desktop     | [201687956a](https://bsd-hardware.info/?probe=201687956a) | Jan 29, 2025 |
| Protectli     | FW2B                        | Desktop     | [fdf4c0fc65](https://bsd-hardware.info/?probe=fdf4c0fc65) | Jan 22, 2025 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [dd6e0adc6e](https://bsd-hardware.info/?probe=dd6e0adc6e) | Jan 18, 2025 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [f8cd5798b5](https://bsd-hardware.info/?probe=f8cd5798b5) | Jan 06, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [692f11c086](https://bsd-hardware.info/?probe=692f11c086) | Jan 05, 2025 |
| Unknown       | Unknown                     | Notebook    | [1d7ea0d455](https://bsd-hardware.info/?probe=1d7ea0d455) | Jan 02, 2025 |
| Unknown       | Unknown                     | Desktop     | [2c400cdb2c](https://bsd-hardware.info/?probe=2c400cdb2c) | Jan 02, 2025 |
| Unknown       | Unknown                     | Desktop     | [c23c86dc99](https://bsd-hardware.info/?probe=c23c86dc99) | Jan 01, 2025 |
| Unknown       | Unknown                     | Desktop     | [63fd28f073](https://bsd-hardware.info/?probe=63fd28f073) | Dec 26, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [af31d44d1f](https://bsd-hardware.info/?probe=af31d44d1f) | Dec 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [bba86ddcba](https://bsd-hardware.info/?probe=bba86ddcba) | Dec 21, 2024 |
| ASRock        | E3C226D2I                   | Desktop     | [37b9937cf0](https://bsd-hardware.info/?probe=37b9937cf0) | Dec 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [a36cfd03b0](https://bsd-hardware.info/?probe=a36cfd03b0) | Dec 18, 2024 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [2d4c35ab71](https://bsd-hardware.info/?probe=2d4c35ab71) | Dec 17, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [ced3ab3213](https://bsd-hardware.info/?probe=ced3ab3213) | Dec 16, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [78fc5bf7e9](https://bsd-hardware.info/?probe=78fc5bf7e9) | Dec 15, 2024 |
| Lenovo        | ThinkPad T490 20N3S61A13    | Notebook    | [150320a6b1](https://bsd-hardware.info/?probe=150320a6b1) | Dec 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [dd2a5f051e](https://bsd-hardware.info/?probe=dd2a5f051e) | Dec 13, 2024 |
| ASRock        | E3C226D2I                   | Desktop     | [0aa040bcda](https://bsd-hardware.info/?probe=0aa040bcda) | Dec 10, 2024 |
| Sophos        | SG                          | Firewall    | [a7e440194c](https://bsd-hardware.info/?probe=a7e440194c) | Dec 05, 2024 |
| Supermicro    | X7SPA-H                     | Desktop     | [dbfc4db35b](https://bsd-hardware.info/?probe=dbfc4db35b) | Nov 29, 2024 |
| ASUSTek       | AM1M-A                      | Desktop     | [473deeae6a](https://bsd-hardware.info/?probe=473deeae6a) | Nov 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [c7e7359910](https://bsd-hardware.info/?probe=c7e7359910) | Nov 21, 2024 |
| Intel         | J1900                       | Desktop     | [e6c410d6de](https://bsd-hardware.info/?probe=e6c410d6de) | Nov 20, 2024 |
| Dell          | 096JG8 A01                  | Desktop     | [7e1caf1e87](https://bsd-hardware.info/?probe=7e1caf1e87) | Nov 20, 2024 |
| Dell          | 096JG8 A01                  | Desktop     | [bcb0eacfea](https://bsd-hardware.info/?probe=bcb0eacfea) | Nov 18, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [bc58379358](https://bsd-hardware.info/?probe=bc58379358) | Nov 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [10ead77144](https://bsd-hardware.info/?probe=10ead77144) | Nov 15, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [a53ffa9bf6](https://bsd-hardware.info/?probe=a53ffa9bf6) | Nov 13, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [4b829e1b6d](https://bsd-hardware.info/?probe=4b829e1b6d) | Nov 13, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [d70ca808ea](https://bsd-hardware.info/?probe=d70ca808ea) | Nov 10, 2024 |
| Shuttle       | DS57U                       | Notebook    | [32c044d7d9](https://bsd-hardware.info/?probe=32c044d7d9) | Nov 10, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [015d104076](https://bsd-hardware.info/?probe=015d104076) | Nov 09, 2024 |
| Sophos        | SG                          | Firewall    | [5dcece4b15](https://bsd-hardware.info/?probe=5dcece4b15) | Nov 09, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e962f6d14f](https://bsd-hardware.info/?probe=e962f6d14f) | Nov 08, 2024 |
| PC Engines    | APU                         | Desktop     | [8ebdbe84c2](https://bsd-hardware.info/?probe=8ebdbe84c2) | Nov 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [e0e10e6e1f](https://bsd-hardware.info/?probe=e0e10e6e1f) | Nov 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [b95602ad1d](https://bsd-hardware.info/?probe=b95602ad1d) | Nov 01, 2024 |
| HP            | 3397                        | Desktop     | [0144b4437f](https://bsd-hardware.info/?probe=0144b4437f) | Oct 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [104ca1a87e](https://bsd-hardware.info/?probe=104ca1a87e) | Oct 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [abee83c3b8](https://bsd-hardware.info/?probe=abee83c3b8) | Oct 25, 2024 |
| Protectli     | VP2420                      | Desktop     | [da2839c086](https://bsd-hardware.info/?probe=da2839c086) | Oct 21, 2024 |
| Protectli     | VP2420                      | Desktop     | [d3e7371387](https://bsd-hardware.info/?probe=d3e7371387) | Oct 18, 2024 |
| ASUSTek       | AT3GC-I                     | Desktop     | [c733d93d11](https://bsd-hardware.info/?probe=c733d93d11) | Oct 02, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [c69ca23766](https://bsd-hardware.info/?probe=c69ca23766) | Sep 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [bbba7d5d52](https://bsd-hardware.info/?probe=bbba7d5d52) | Sep 14, 2024 |
| KEBA          | CP505_BIOS_01.03            | Desktop     | [c8091ab802](https://bsd-hardware.info/?probe=c8091ab802) | Sep 13, 2024 |
| KEBA          | CP505_BIOS_01.03            | Desktop     | [404e36fbfa](https://bsd-hardware.info/?probe=404e36fbfa) | Sep 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [2078937889](https://bsd-hardware.info/?probe=2078937889) | Sep 09, 2024 |
| KEBA          | CP505_BIOS_01.03            | Desktop     | [7f33805fee](https://bsd-hardware.info/?probe=7f33805fee) | Sep 06, 2024 |
| KEBA          | CP505_BIOS_01.03            | Desktop     | [d63da5029b](https://bsd-hardware.info/?probe=d63da5029b) | Sep 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [d39290caaf](https://bsd-hardware.info/?probe=d39290caaf) | Aug 24, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [aedfdb1704](https://bsd-hardware.info/?probe=aedfdb1704) | Aug 22, 2024 |
| Gigabyte      | H410M S2H V3                | Desktop     | [0060403317](https://bsd-hardware.info/?probe=0060403317) | Aug 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [6d1e481cf0](https://bsd-hardware.info/?probe=6d1e481cf0) | Aug 13, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [d051177b97](https://bsd-hardware.info/?probe=d051177b97) | Aug 12, 2024 |
| Dell          | 03X6X0 A00                  | Server      | [8f63a94f5f](https://bsd-hardware.info/?probe=8f63a94f5f) | Aug 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [9596202f52](https://bsd-hardware.info/?probe=9596202f52) | Aug 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [3d29ca3d8e](https://bsd-hardware.info/?probe=3d29ca3d8e) | Jul 26, 2024 |
| PC Engines    | APU                         | Desktop     | [18517be69f](https://bsd-hardware.info/?probe=18517be69f) | Jul 08, 2024 |
| AWOW          | AK10                        | Desktop     | [6259d72d34](https://bsd-hardware.info/?probe=6259d72d34) | Jul 07, 2024 |
| HP            | ProLiant DL380 G7           | Server      | [f1b2513fe7](https://bsd-hardware.info/?probe=f1b2513fe7) | Jul 03, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [9713e10693](https://bsd-hardware.info/?probe=9713e10693) | Jul 03, 2024 |
| Gigabyte      | Z590 VISION G               | Desktop     | [39bb67c433](https://bsd-hardware.info/?probe=39bb67c433) | Jun 25, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [6df2b85c04](https://bsd-hardware.info/?probe=6df2b85c04) | Jun 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [3fb7d4a270](https://bsd-hardware.info/?probe=3fb7d4a270) | Jun 13, 2024 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [f6cce31cc6](https://bsd-hardware.info/?probe=f6cce31cc6) | May 17, 2024 |
| OEM           | 1.0                         | Desktop     | [a6fa59cebd](https://bsd-hardware.info/?probe=a6fa59cebd) | May 09, 2024 |
| Chuwi         | LarkBox X                   | Mini pc     | [4c54b5b3e0](https://bsd-hardware.info/?probe=4c54b5b3e0) | May 02, 2024 |
| Supermicro    | X11SCL-IF                   | Server      | [93394181dc](https://bsd-hardware.info/?probe=93394181dc) | Apr 29, 2024 |
| PC Engines    | APU                         | Desktop     | [7fbd1ae00c](https://bsd-hardware.info/?probe=7fbd1ae00c) | Apr 28, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [9dfb20c904](https://bsd-hardware.info/?probe=9dfb20c904) | Apr 23, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a2cbe8253b](https://bsd-hardware.info/?probe=a2cbe8253b) | Apr 09, 2024 |
| Unknown       | Unknown                     | Notebook    | [ac12463cc2](https://bsd-hardware.info/?probe=ac12463cc2) | Apr 08, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3ccdd0084b](https://bsd-hardware.info/?probe=3ccdd0084b) | Apr 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [f6ead7640d](https://bsd-hardware.info/?probe=f6ead7640d) | Mar 30, 2024 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [2a5a6e7f07](https://bsd-hardware.info/?probe=2a5a6e7f07) | Mar 24, 2024 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [204c0e441b](https://bsd-hardware.info/?probe=204c0e441b) | Mar 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [28feb266fd](https://bsd-hardware.info/?probe=28feb266fd) | Mar 24, 2024 |
| ASUSTek       | Pro B660M-C D4              | Desktop     | [dea6d03494](https://bsd-hardware.info/?probe=dea6d03494) | Mar 24, 2024 |
| Intel         | D53427RKE G87971-403        | Desktop     | [5cf0576fee](https://bsd-hardware.info/?probe=5cf0576fee) | Mar 23, 2024 |
| HP            | ProLiant MicroServer        | Desktop     | [c158a70e91](https://bsd-hardware.info/?probe=c158a70e91) | Mar 22, 2024 |
| PC Engines    | APU2                        | Desktop     | [1f2d9aef5b](https://bsd-hardware.info/?probe=1f2d9aef5b) | Mar 22, 2024 |
| Sun           | SUNW,Ultra-1                | Desktop     | [33ed69952b](https://bsd-hardware.info/?probe=33ed69952b) | Mar 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [07a7ed8dde](https://bsd-hardware.info/?probe=07a7ed8dde) | Mar 15, 2024 |
| Chuwi         | LarkBox X                   | Mini pc     | [543f854b16](https://bsd-hardware.info/?probe=543f854b16) | Mar 14, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [5b8f4fe788](https://bsd-hardware.info/?probe=5b8f4fe788) | Mar 14, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [8f4dfa8bb2](https://bsd-hardware.info/?probe=8f4dfa8bb2) | Mar 10, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [81d6b5c7e8](https://bsd-hardware.info/?probe=81d6b5c7e8) | Mar 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [a10048c3e7](https://bsd-hardware.info/?probe=a10048c3e7) | Mar 01, 2024 |
| Intel         | QHSW02                      | Desktop     | [11ee14ed87](https://bsd-hardware.info/?probe=11ee14ed87) | Feb 26, 2024 |
| Shuttle       | XH610                       | Desktop     | [e7780e6013](https://bsd-hardware.info/?probe=e7780e6013) | Feb 26, 2024 |
| Sophos        | XG                          | Firewall    | [a41aa9f9b8](https://bsd-hardware.info/?probe=a41aa9f9b8) | Feb 25, 2024 |
| Shuttle       | XH610                       | Desktop     | [dc854cc185](https://bsd-hardware.info/?probe=dc854cc185) | Feb 25, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [151b04e792](https://bsd-hardware.info/?probe=151b04e792) | Feb 23, 2024 |
| Sophos        | SG                          | Firewall    | [a731a68c5b](https://bsd-hardware.info/?probe=a731a68c5b) | Feb 22, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [7aeebe2c82](https://bsd-hardware.info/?probe=7aeebe2c82) | Feb 18, 2024 |
| Hardkernel    | ODROID-H2                   | Desktop     | [a4045617ec](https://bsd-hardware.info/?probe=a4045617ec) | Feb 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [ef910cb303](https://bsd-hardware.info/?probe=ef910cb303) | Feb 14, 2024 |
| Shuttle       | FH170                       | Desktop     | [e7eaced298](https://bsd-hardware.info/?probe=e7eaced298) | Feb 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [11b10e5acb](https://bsd-hardware.info/?probe=11b10e5acb) | Feb 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [4437069c86](https://bsd-hardware.info/?probe=4437069c86) | Feb 05, 2024 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [5b7342de3f](https://bsd-hardware.info/?probe=5b7342de3f) | Feb 04, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [19ab947fb4](https://bsd-hardware.info/?probe=19ab947fb4) | Jan 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [c28104b9b5](https://bsd-hardware.info/?probe=c28104b9b5) | Jan 28, 2024 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [17c3586ebc](https://bsd-hardware.info/?probe=17c3586ebc) | Jan 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [0b0142d5dd](https://bsd-hardware.info/?probe=0b0142d5dd) | Jan 19, 2024 |
| PC Engines    | APU2                        | Desktop     | [189362d834](https://bsd-hardware.info/?probe=189362d834) | Jan 19, 2024 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [14e2e2c18c](https://bsd-hardware.info/?probe=14e2e2c18c) | Jan 16, 2024 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8707b73983](https://bsd-hardware.info/?probe=8707b73983) | Jan 08, 2024 |
| Sophos        | XG                          | Firewall    | [c30f177b0f](https://bsd-hardware.info/?probe=c30f177b0f) | Dec 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [058859b9c4](https://bsd-hardware.info/?probe=058859b9c4) | Dec 26, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [7ad0451a6f](https://bsd-hardware.info/?probe=7ad0451a6f) | Dec 25, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [80e8d502be](https://bsd-hardware.info/?probe=80e8d502be) | Dec 24, 2023 |
| PC Engines    | apu4                        | Desktop     | [48a0e27e11](https://bsd-hardware.info/?probe=48a0e27e11) | Dec 22, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [7f8968ee0a](https://bsd-hardware.info/?probe=7f8968ee0a) | Dec 22, 2023 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [a2aa82ed5d](https://bsd-hardware.info/?probe=a2aa82ed5d) | Dec 16, 2023 |
| Intel         | DH67BL AAG10189-207         | Desktop     | [e6210120bd](https://bsd-hardware.info/?probe=e6210120bd) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [be6c7879b4](https://bsd-hardware.info/?probe=be6c7879b4) | Dec 07, 2023 |
| Protectli     | FW4B                        | Desktop     | [dab9b84618](https://bsd-hardware.info/?probe=dab9b84618) | Dec 03, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [e1a3d3ff53](https://bsd-hardware.info/?probe=e1a3d3ff53) | Nov 30, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [6ceeb87719](https://bsd-hardware.info/?probe=6ceeb87719) | Nov 30, 2023 |
| Intel         | DH67BL AAG10189-207         | Desktop     | [734103b696](https://bsd-hardware.info/?probe=734103b696) | Nov 22, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [6074d7118a](https://bsd-hardware.info/?probe=6074d7118a) | Nov 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [8854b07e12](https://bsd-hardware.info/?probe=8854b07e12) | Nov 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [0662bae41e](https://bsd-hardware.info/?probe=0662bae41e) | Nov 12, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [bdc4fdaf9c](https://bsd-hardware.info/?probe=bdc4fdaf9c) | Nov 05, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [1859b56be4](https://bsd-hardware.info/?probe=1859b56be4) | Nov 02, 2023 |
| Shuttle       | DS437                       | Notebook    | [45c2e3460c](https://bsd-hardware.info/?probe=45c2e3460c) | Oct 30, 2023 |
| Sophos        | SG                          | Firewall    | [7bdc18c407](https://bsd-hardware.info/?probe=7bdc18c407) | Oct 19, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [34ae4abdcc](https://bsd-hardware.info/?probe=34ae4abdcc) | Oct 17, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [4b685d7ff1](https://bsd-hardware.info/?probe=4b685d7ff1) | Oct 14, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [12b5a57360](https://bsd-hardware.info/?probe=12b5a57360) | Oct 10, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [ab5400f952](https://bsd-hardware.info/?probe=ab5400f952) | Oct 08, 2023 |
| Barracuda ... | Barracuda NG Firewall F2... | Firewall    | [bdf86afe1c](https://bsd-hardware.info/?probe=bdf86afe1c) | Oct 07, 2023 |
| Barracuda ... | Barracuda NG Firewall F2... | Firewall    | [f76e1fb940](https://bsd-hardware.info/?probe=f76e1fb940) | Oct 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [13f17e09d4](https://bsd-hardware.info/?probe=13f17e09d4) | Oct 06, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [5076395072](https://bsd-hardware.info/?probe=5076395072) | Oct 06, 2023 |
| PC Engines    | apu4                        | Desktop     | [20c432e07b](https://bsd-hardware.info/?probe=20c432e07b) | Oct 02, 2023 |
| ShenZhen M... | 3865U-6L                    | Desktop     | [53a70ddb3b](https://bsd-hardware.info/?probe=53a70ddb3b) | Oct 02, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [8809e169a1](https://bsd-hardware.info/?probe=8809e169a1) | Sep 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [20fb7f1ba8](https://bsd-hardware.info/?probe=20fb7f1ba8) | Sep 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e82c0f66d](https://bsd-hardware.info/?probe=7e82c0f66d) | Sep 29, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8ebba0ee37](https://bsd-hardware.info/?probe=8ebba0ee37) | Sep 19, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [35544a61bd](https://bsd-hardware.info/?probe=35544a61bd) | Sep 16, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [281e4a541b](https://bsd-hardware.info/?probe=281e4a541b) | Aug 26, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [c5745af495](https://bsd-hardware.info/?probe=c5745af495) | Aug 26, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [97321f0843](https://bsd-hardware.info/?probe=97321f0843) | Aug 20, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [f5a3c00551](https://bsd-hardware.info/?probe=f5a3c00551) | Aug 19, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [87bc92631a](https://bsd-hardware.info/?probe=87bc92631a) | Aug 16, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [ec68697ed9](https://bsd-hardware.info/?probe=ec68697ed9) | Aug 16, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [a92e1efca1](https://bsd-hardware.info/?probe=a92e1efca1) | Aug 07, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [e903094a75](https://bsd-hardware.info/?probe=e903094a75) | Aug 03, 2023 |
| ASRock        | J3355B-ITX                  | Desktop     | [234f0fd8aa](https://bsd-hardware.info/?probe=234f0fd8aa) | Aug 01, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [aeb59c510b](https://bsd-hardware.info/?probe=aeb59c510b) | Jul 26, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [24e7268bbe](https://bsd-hardware.info/?probe=24e7268bbe) | Jul 19, 2023 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [49d1520c4a](https://bsd-hardware.info/?probe=49d1520c4a) | Jul 17, 2023 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [aedd3a8255](https://bsd-hardware.info/?probe=aedd3a8255) | Jun 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | Notebook    | [722403df31](https://bsd-hardware.info/?probe=722403df31) | Jun 15, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [cc5fe45365](https://bsd-hardware.info/?probe=cc5fe45365) | Jun 15, 2023 |
| ShenZhen M... | 3865U-6L                    | Desktop     | [5733ad3c03](https://bsd-hardware.info/?probe=5733ad3c03) | May 25, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [3966c4828d](https://bsd-hardware.info/?probe=3966c4828d) | May 12, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [d72b0581a4](https://bsd-hardware.info/?probe=d72b0581a4) | May 11, 2023 |
| PC Engines    | apu4                        | Desktop     | [2589a0c02c](https://bsd-hardware.info/?probe=2589a0c02c) | May 10, 2023 |
| AWOW          | AK34Pro                     | Mini pc     | [463ffd90f0](https://bsd-hardware.info/?probe=463ffd90f0) | May 08, 2023 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [d7b4814da7](https://bsd-hardware.info/?probe=d7b4814da7) | May 08, 2023 |
| Gigabyte      | H81M-D2V                    | Desktop     | [5f9bbf2d15](https://bsd-hardware.info/?probe=5f9bbf2d15) | May 04, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [f6c39a3582](https://bsd-hardware.info/?probe=f6c39a3582) | Apr 30, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [7b44e1591f](https://bsd-hardware.info/?probe=7b44e1591f) | Apr 29, 2023 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [e7e7a6470d](https://bsd-hardware.info/?probe=e7e7a6470d) | Apr 27, 2023 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [b517729fb4](https://bsd-hardware.info/?probe=b517729fb4) | Apr 27, 2023 |
| ShenZhen M... | 3865U-6L                    | Desktop     | [1548471a4d](https://bsd-hardware.info/?probe=1548471a4d) | Apr 25, 2023 |
| Shuttle       | DS437                       | Notebook    | [284decb573](https://bsd-hardware.info/?probe=284decb573) | Apr 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [0d7a1b58ed](https://bsd-hardware.info/?probe=0d7a1b58ed) | Apr 21, 2023 |
| MSI           | 2A78h                       | Desktop     | [8560ebd69c](https://bsd-hardware.info/?probe=8560ebd69c) | Apr 18, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [8c3cdf29a2](https://bsd-hardware.info/?probe=8c3cdf29a2) | Apr 17, 2023 |
| Shuttle       | DS10U                       | Desktop     | [7f98ef1865](https://bsd-hardware.info/?probe=7f98ef1865) | Apr 10, 2023 |
| Shuttle       | FS61                        | Desktop     | [9c3df7e926](https://bsd-hardware.info/?probe=9c3df7e926) | Apr 09, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8452deae22](https://bsd-hardware.info/?probe=8452deae22) | Apr 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [11f0439894](https://bsd-hardware.info/?probe=11f0439894) | Apr 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [9a5ccefb18](https://bsd-hardware.info/?probe=9a5ccefb18) | Mar 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [f80047716b](https://bsd-hardware.info/?probe=f80047716b) | Mar 15, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [cb6c76df00](https://bsd-hardware.info/?probe=cb6c76df00) | Mar 13, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [62c09245a4](https://bsd-hardware.info/?probe=62c09245a4) | Mar 10, 2023 |
| ASUSTek       | P11C-M Series               | Desktop     | [80814c04b6](https://bsd-hardware.info/?probe=80814c04b6) | Mar 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| ASUSTek       | P11C-M Series               | Desktop     | [242677230a](https://bsd-hardware.info/?probe=242677230a) | Mar 09, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [e27931f082](https://bsd-hardware.info/?probe=e27931f082) | Mar 07, 2023 |
| ASUSTek       | P11C-M Series               | Desktop     | [866573ffa0](https://bsd-hardware.info/?probe=866573ffa0) | Mar 03, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [bf21395f79](https://bsd-hardware.info/?probe=bf21395f79) | Feb 24, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [f6f5953979](https://bsd-hardware.info/?probe=f6f5953979) | Feb 23, 2023 |
| HP            | 3397                        | Desktop     | [8b231fd832](https://bsd-hardware.info/?probe=8b231fd832) | Feb 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [be8fb945ef](https://bsd-hardware.info/?probe=be8fb945ef) | Feb 12, 2023 |
| Intel         | ChiefRiver                  | Desktop     | [ae6ea07868](https://bsd-hardware.info/?probe=ae6ea07868) | Feb 05, 2023 |
| PC Engines    | APU2                        | Desktop     | [d59ed5b52f](https://bsd-hardware.info/?probe=d59ed5b52f) | Feb 02, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [d9746ad1c3](https://bsd-hardware.info/?probe=d9746ad1c3) | Jan 28, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [84375af67f](https://bsd-hardware.info/?probe=84375af67f) | Jan 27, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | Notebook    | [24544f4a94](https://bsd-hardware.info/?probe=24544f4a94) | Jan 24, 2023 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [9954516f1a](https://bsd-hardware.info/?probe=9954516f1a) | Jan 22, 2023 |
| Unknown       | YL-E3845L4-V2               | Desktop     | [d93eb933f1](https://bsd-hardware.info/?probe=d93eb933f1) | Jan 20, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ba99fba661](https://bsd-hardware.info/?probe=ba99fba661) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [22015084fc](https://bsd-hardware.info/?probe=22015084fc) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [78327c664e](https://bsd-hardware.info/?probe=78327c664e) | Jan 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [247370372d](https://bsd-hardware.info/?probe=247370372d) | Jan 15, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d4846c3ec1](https://bsd-hardware.info/?probe=d4846c3ec1) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [87d79c88e1](https://bsd-hardware.info/?probe=87d79c88e1) | Jan 11, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [5a4affef3e](https://bsd-hardware.info/?probe=5a4affef3e) | Jan 04, 2023 |
| Sophos        | SG                          | Firewall    | [8679b4c8f4](https://bsd-hardware.info/?probe=8679b4c8f4) | Dec 31, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [b685ddc2ad](https://bsd-hardware.info/?probe=b685ddc2ad) | Dec 28, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [f7700c781d](https://bsd-hardware.info/?probe=f7700c781d) | Dec 17, 2022 |
| Intel         | H81U                        | Notebook    | [fab3eecc66](https://bsd-hardware.info/?probe=fab3eecc66) | Dec 15, 2022 |
| Intel         | H81U                        | Notebook    | [fe1c3cb754](https://bsd-hardware.info/?probe=fe1c3cb754) | Dec 14, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [657972a55d](https://bsd-hardware.info/?probe=657972a55d) | Dec 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [33f23b1291](https://bsd-hardware.info/?probe=33f23b1291) | Dec 06, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [2299087d09](https://bsd-hardware.info/?probe=2299087d09) | Nov 29, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [d48dbd053d](https://bsd-hardware.info/?probe=d48dbd053d) | Nov 28, 2022 |
| PC Engines    | apu4                        | Desktop     | [588e065800](https://bsd-hardware.info/?probe=588e065800) | Nov 28, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [45d96a0b5a](https://bsd-hardware.info/?probe=45d96a0b5a) | Nov 24, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [2f812bd8c3](https://bsd-hardware.info/?probe=2f812bd8c3) | Nov 22, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [86dcacdb40](https://bsd-hardware.info/?probe=86dcacdb40) | Nov 13, 2022 |
| PC Engines    | apu4                        | Desktop     | [7ed7638be3](https://bsd-hardware.info/?probe=7ed7638be3) | Nov 03, 2022 |
| PC Engines    | APU2                        | Desktop     | [0c573848ce](https://bsd-hardware.info/?probe=0c573848ce) | Oct 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [0677b5c196](https://bsd-hardware.info/?probe=0677b5c196) | Oct 25, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [9757e40c42](https://bsd-hardware.info/?probe=9757e40c42) | Oct 13, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [53dfc5844c](https://bsd-hardware.info/?probe=53dfc5844c) | Oct 01, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [30cb759583](https://bsd-hardware.info/?probe=30cb759583) | Sep 30, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [2c1aad67d1](https://bsd-hardware.info/?probe=2c1aad67d1) | Sep 26, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [c33dc6a072](https://bsd-hardware.info/?probe=c33dc6a072) | Sep 25, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [37cafd59eb](https://bsd-hardware.info/?probe=37cafd59eb) | Sep 20, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [e0b8ceecae](https://bsd-hardware.info/?probe=e0b8ceecae) | Sep 16, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [e082eca671](https://bsd-hardware.info/?probe=e082eca671) | Sep 08, 2022 |
| PC Engines    | APU2                        | Desktop     | [1650d8c419](https://bsd-hardware.info/?probe=1650d8c419) | Sep 05, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Location/Austria/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| OPNsense 21.7.3  | 9         | 1.97%   |
| OPNsense 22.1.1  | 8         | 1.75%   |
| OPNsense 25.1.4  | 7         | 1.54%   |
| OPNsense 24.7.11 | 7         | 1.54%   |
| OPNsense 23.7.5  | 7         | 1.54%   |
| OPNsense 21.7.7  | 7         | 1.54%   |
| OPNsense 25.1.5  | 6         | 1.32%   |
| OPNsense 24.7.12 | 6         | 1.32%   |
| OPNsense 24.1.2  | 6         | 1.32%   |
| OPNsense 22.4.3  | 6         | 1.32%   |
| OPNsense 21.1.4  | 6         | 1.32%   |
| OPNsense 20.7.8  | 6         | 1.32%   |
| FreeBSD 13.1     | 6         | 1.32%   |
| OPNsense 25.1.3  | 5         | 1.1%    |
| OPNsense 25.1    | 5         | 1.1%    |
| OPNsense 24.7.8  | 5         | 1.1%    |
| OPNsense 24.7.7  | 5         | 1.1%    |
| OPNsense 24.1.6  | 5         | 1.1%    |
| OPNsense 23.7.10 | 5         | 1.1%    |
| OPNsense 23.1.6  | 5         | 1.1%    |
| OPNsense 23.1.5  | 5         | 1.1%    |
| OPNsense 22.7.9  | 5         | 1.1%    |
| OPNsense 22.7.11 | 5         | 1.1%    |
| OPNsense 22.1    | 5         | 1.1%    |
| OPNsense 21.7.6  | 5         | 1.1%    |
| OPNsense 21.1.5  | 5         | 1.1%    |
| OPNsense 21.1.3  | 5         | 1.1%    |
| OPNsense 21.1.2  | 5         | 1.1%    |
| OPNsense 21.1    | 5         | 1.1%    |
| OpenBSD 6.8      | 5         | 1.1%    |
| OPNsense 25.7.9  | 4         | 0.88%   |
| OPNsense 25.7.1  | 4         | 0.88%   |
| OPNsense 25.1.7  | 4         | 0.88%   |
| OPNsense 24.7.9  | 4         | 0.88%   |
| OPNsense 24.7.10 | 4         | 0.88%   |
| OPNsense 24.1.9  | 4         | 0.88%   |
| OPNsense 24.1.4  | 4         | 0.88%   |
| OPNsense 23.7.9  | 4         | 0.88%   |
| OPNsense 23.7.8  | 4         | 0.88%   |
| OPNsense 23.7.12 | 4         | 0.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 253       | 76.2%   |
| FreeBSD     | 51        | 15.36%  |
| OpenBSD     | 10        | 3.01%   |
| helloSystem | 6         | 1.81%   |
| GhostBSD    | 6         | 1.81%   |
| FreeNAS     | 3         | 0.9%    |
| TrueNAS     | 1         | 0.3%    |
| NomadBSD    | 1         | 0.3%    |
| NetBSD      | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 325       | 98.19%  |
| arm64   | 4         | 1.21%   |
| sparc64 | 1         | 0.3%    |
| i386    | 1         | 0.3%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 278       | 82.99%  |
| KDE5         | 12        | 3.58%   |
| XFCE         | 10        | 2.99%   |
| helloDesktop | 10        | 2.99%   |
| MATE         | 7         | 2.09%   |
| LXQt         | 3         | 0.9%    |
| Cinnamon     | 3         | 0.9%    |
| TWM          | 2         | 0.6%    |
| i3           | 2         | 0.6%    |
| GNOME        | 2         | 0.6%    |
| fvwm         | 2         | 0.6%    |
| xinitrc      | 1         | 0.3%    |
| wlroots      | 1         | 0.3%    |
| Openbox      | 1         | 0.3%    |
| Lumina       | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 282       | 84.43%  |
| X11     | 49        | 14.67%  |
| Wayland | 3         | 0.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 296       | 88.36%  |
| SDDM    | 16        | 4.78%   |
| LightDM | 10        | 2.99%   |
| SLiM    | 9         | 2.69%   |
| GDM     | 2         | 0.6%    |
| XDM     | 1         | 0.3%    |
| Ly      | 1         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 272       | 80.24%  |
| C       | 34        | 10.03%  |
| en_US   | 20        | 5.9%    |
| de_DE   | 8         | 2.36%   |
| de_AT   | 2         | 0.59%   |
| cs_CZ   | 2         | 0.59%   |
| fr_FR   | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 299       | 90.06%  |
| BIOS | 33        | 9.94%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 166       | 48.54%  |
| Zfs     | 163       | 47.66%  |
| Ffs     | 10        | 2.92%   |
| Cd9660  | 2         | 0.58%   |
| Unknown | 1         | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 314       | 94.58%  |
| MBR     | 13        | 3.92%   |
| Unknown | 5         | 1.51%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 54        | 16.31%  |
| Lenovo                     | 29        | 8.76%   |
| PC Engines                 | 21        | 6.34%   |
| Hewlett-Packard            | 19        | 5.74%   |
| Dell                       | 17        | 5.14%   |
| Supermicro                 | 14        | 4.23%   |
| Fujitsu                    | 13        | 3.93%   |
| ASUSTek Computer           | 13        | 3.93%   |
| Intel                      | 12        | 3.63%   |
| Gigabyte Technology        | 11        | 3.32%   |
| Sophos                     | 10        | 3.02%   |
| Deciso                     | 10        | 3.02%   |
| Shuttle                    | 9         | 2.72%   |
| Protectli                  | 9         | 2.72%   |
| ASRock                     | 8         | 2.42%   |
| AMI                        | 8         | 2.42%   |
| ZOTAC                      | 7         | 2.11%   |
| BESSTAR Tech               | 7         | 2.11%   |
| IceWhale Technology        | 5         | 1.51%   |
| MW                         | 4         | 1.21%   |
| Barracuda Networks         | 4         | 1.21%   |
| AWOW                       | 4         | 1.21%   |
| Techvision                 | 3         | 0.91%   |
| Apple                      | 3         | 0.91%   |
| SJRC                       | 2         | 0.6%    |
| Secudos                    | 2         | 0.6%    |
| Raspberry Pi Foundation    | 2         | 0.6%    |
| MSI                        | 2         | 0.6%    |
| Hardkernel                 | 2         | 0.6%    |
| Biostar                    | 2         | 0.6%    |
| AAEON                      | 2         | 0.6%    |
| XtReAmEr                   | 1         | 0.3%    |
| Winston Marriot            | 1         | 0.3%    |
| TUXEDO                     | 1         | 0.3%    |
| Trigkey                    | 1         | 0.3%    |
| Sun                        | 1         | 0.3%    |
| Silicom                    | 1         | 0.3%    |
| ShenZhen MinWin Technology | 1         | 0.3%    |
| SeeedStudio                | 1         | 0.3%    |
| Seeed Studio               | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 58        | 17.52%  |
| PC Engines APU2                              | 10        | 3.02%   |
| Sophos SG                                    | 7         | 2.11%   |
| PC Engines apu4                              | 7         | 2.11%   |
| Deciso Netboard A10 GEN2 Model G             | 6         | 1.81%   |
| IceWhale ZimaBoard 832 ZMB                   | 5         | 1.51%   |
| Supermicro Super Server                      | 4         | 1.21%   |
| MW GMLK-2_5G4L                               | 4         | 1.21%   |
| AMI Aptio CRB                                | 4         | 1.21%   |
| Techvision TVI7309X                          | 3         | 0.91%   |
| Sophos XG                                    | 3         | 0.91%   |
| Shuttle DH170                                | 3         | 0.91%   |
| Protectli VP2420                             | 3         | 0.91%   |
| Protectli FW4B                               | 3         | 0.91%   |
| PC Engines APU                               | 3         | 0.91%   |
| Intel Q3XXG4-P V1.0                          | 3         | 0.91%   |
| Fujitsu FUTRO S920                           | 3         | 0.91%   |
| Dell OptiPlex 5040                           | 3         | 0.91%   |
| Barracuda Networks Barracuda NG Firewall F18 | 3         | 0.91%   |
| ZOTAC ZBOX-CI341                             | 2         | 0.6%    |
| ZOTAC ZBOX-CI323NANO                         | 2         | 0.6%    |
| Supermicro X7SPA-H                           | 2         | 0.6%    |
| SJRC ADLN-6L                                 | 2         | 0.6%    |
| Shuttle DS10U                                | 2         | 0.6%    |
| RPi Raspberry Pi                             | 2         | 0.6%    |
| Lenovo ThinkPad T490 20N2CTO1WW              | 2         | 0.6%    |
| HP ProLiant DL360 G6                         | 2         | 0.6%    |
| HP EliteBook 850 G7 Notebook PC              | 2         | 0.6%    |
| Hardkernel ODROID-H2                         | 2         | 0.6%    |
| Fujitsu FUTRO S720                           | 2         | 0.6%    |
| Fujitsu ESPRIMO C720                         | 2         | 0.6%    |
| Dell OptiPlex 7040                           | 2         | 0.6%    |
| BESSTAR Tech GK41                            | 2         | 0.6%    |
| AWOW AK34                                    | 2         | 0.6%    |
| AMI LES compact 4L                           | 2         | 0.6%    |
| AAEON UP-APL01                               | 2         | 0.6%    |
| ZOTAC ZBOXNANO-ID63/ID64/ID65                | 1         | 0.3%    |
| ZOTAC ZBOX-CI527/CI547NANO                   | 1         | 0.3%    |
| Winston Marriot PICO PC  PICOPC              | 1         | 0.3%    |
| TUXEDO InfinityBook Pro 14 Gen6              | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 58        | 17.52%  |
| Lenovo ThinkPad              | 17        | 5.14%   |
| PC Engines APU2              | 10        | 3.02%   |
| Dell OptiPlex                | 9         | 2.72%   |
| Sophos SG                    | 7         | 2.11%   |
| PC Engines apu4              | 7         | 2.11%   |
| Lenovo ThinkCentre           | 7         | 2.11%   |
| HP ProLiant                  | 7         | 2.11%   |
| Fujitsu FUTRO                | 6         | 1.81%   |
| Deciso Netboard              | 6         | 1.81%   |
| IceWhale ZimaBoard           | 5         | 1.51%   |
| Fujitsu ESPRIMO              | 5         | 1.51%   |
| Supermicro Super             | 4         | 1.21%   |
| MW GMLK-2                    | 4         | 1.21%   |
| HP EliteBook                 | 4         | 1.21%   |
| Barracuda Networks Barracuda | 4         | 1.21%   |
| AMI Aptio                    | 4         | 1.21%   |
| Techvision TVI7309X          | 3         | 0.91%   |
| Supermicro 1HE               | 3         | 0.91%   |
| Sophos XG                    | 3         | 0.91%   |
| Shuttle DH170                | 3         | 0.91%   |
| Protectli VP2420             | 3         | 0.91%   |
| Protectli FW4B               | 3         | 0.91%   |
| PC Engines APU               | 3         | 0.91%   |
| Intel Q3XXG4-P               | 3         | 0.91%   |
| HP Compaq                    | 3         | 0.91%   |
| Dell PowerEdge               | 3         | 0.91%   |
| ASUS PRIME                   | 3         | 0.91%   |
| ZOTAC ZBOX-CI341             | 2         | 0.6%    |
| ZOTAC ZBOX-CI323NANO         | 2         | 0.6%    |
| Supermicro X7SPA-H           | 2         | 0.6%    |
| SJRC ADLN-6L                 | 2         | 0.6%    |
| Shuttle DS10U                | 2         | 0.6%    |
| RPi Raspberry                | 2         | 0.6%    |
| Lenovo IdeaPad               | 2         | 0.6%    |
| Lenovo IdeaCentre            | 2         | 0.6%    |
| Hardkernel ODROID-H2         | 2         | 0.6%    |
| Dell Precision               | 2         | 0.6%    |
| Deciso NetBoard-A10          | 2         | 0.6%    |
| BESSTAR Tech GK41            | 2         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 39        | 11.78%  |
| 2021    | 37        | 11.18%  |
| 2016    | 28        | 8.46%   |
| 2023    | 27        | 8.16%   |
| 2022    | 26        | 7.85%   |
| 2017    | 25        | 7.55%   |
| 2014    | 25        | 7.55%   |
| 2019    | 22        | 6.65%   |
| 2020    | 21        | 6.34%   |
| 2024    | 15        | 4.53%   |
| 2015    | 14        | 4.23%   |
| 2011    | 14        | 4.23%   |
| 2013    | 12        | 3.63%   |
| 2010    | 6         | 1.81%   |
| Unknown | 6         | 1.81%   |
| 2009    | 5         | 1.51%   |
| 2012    | 4         | 1.21%   |
| 2025    | 3         | 0.91%   |
| 2007    | 1         | 0.3%    |
| 2006    | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 218       | 65.86%  |
| Notebook       | 43        | 12.99%  |
| Mini pc        | 29        | 8.76%   |
| Server         | 22        | 6.65%   |
| Firewall       | 14        | 4.23%   |
| System on chip | 3         | 0.91%   |
| Convertible    | 1         | 0.3%    |
| All in one     | 1         | 0.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 300       | 90.36%  |
| Yes  | 32        | 9.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 133       | 39.23%  |
| 16.01-24.0      | 81        | 23.89%  |
| 4.01-8.0        | 60        | 17.7%   |
| 32.01-64.0      | 29        | 8.55%   |
| 2.01-3.0        | 12        | 3.54%   |
| 64.01-256.0     | 10        | 2.95%   |
| More than 256.0 | 4         | 1.18%   |
| 3.01-4.0        | 4         | 1.18%   |
| 24.01-32.0      | 3         | 0.88%   |
| 1.01-2.0        | 1         | 0.29%   |
| 0.51-1.0        | 1         | 0.29%   |
| 0.01-0.5        | 1         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 159       | 46.63%  |
| 0.51-1.0    | 122       | 35.78%  |
| 1.01-2.0    | 37        | 10.85%  |
| 2.01-3.0    | 8         | 2.35%   |
| 4.01-8.0    | 5         | 1.47%   |
| 32.01-64.0  | 3         | 0.88%   |
| 0           | 3         | 0.88%   |
| 3.01-4.0    | 1         | 0.29%   |
| 64.01-256.0 | 1         | 0.29%   |
| 16.01-24.0  | 1         | 0.29%   |
| Unknown     | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 235       | 68.51%  |
| 0      | 57        | 16.62%  |
| 2      | 34        | 9.91%   |
| 3      | 6         | 1.75%   |
| 4      | 5         | 1.46%   |
| 17     | 1         | 0.29%   |
| 15     | 1         | 0.29%   |
| 13     | 1         | 0.29%   |
| 9      | 1         | 0.29%   |
| 7      | 1         | 0.29%   |
| 6      | 1         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 303       | 90.45%  |
| Yes       | 32        | 9.55%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 322       | 97.28%  |
| No        | 9         | 2.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 242       | 72.02%  |
| Yes       | 94        | 27.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 266       | 79.64%  |
| Yes       | 68        | 20.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Austria | 331       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Vienna                  | 166       | 45.11%  |
| Graz                    | 26        | 7.07%   |
| Linz                    | 13        | 3.53%   |
| Innsbruck               | 9         | 2.45%   |
| Feldkirch               | 7         | 1.9%    |
| Wels                    | 6         | 1.63%   |
| Salzburg                | 6         | 1.63%   |
| Stockerau               | 4         | 1.09%   |
| Pirching am Traubenberg | 4         | 1.09%   |
| Leoben                  | 4         | 1.09%   |
| Krems                   | 3         | 0.82%   |
| Wiener Neustadt         | 2         | 0.54%   |
| Trausdorf an der Wulka  | 2         | 0.54%   |
| Sankt Veit an der Glan  | 2         | 0.54%   |
| Rankweil                | 2         | 0.54%   |
| Purkersdorf             | 2         | 0.54%   |
| Ohlsdorf                | 2         | 0.54%   |
| Neumarkt im Muehlkreis  | 2         | 0.54%   |
| Neulengbach             | 2         | 0.54%   |
| Lanzenkirchen           | 2         | 0.54%   |
| Klagenfurt              | 2         | 0.54%   |
| Hittisau                | 2         | 0.54%   |
| Grossgmain              | 2         | 0.54%   |
| Deutschlandsberg        | 2         | 0.54%   |
| Bruck an der Mur        | 2         | 0.54%   |
| Bregenz                 | 2         | 0.54%   |
| Baden bei Wien          | 2         | 0.54%   |
| Axams                   | 2         | 0.54%   |
| Atzenbrugg              | 2         | 0.54%   |
| Zwettl Stadt            | 1         | 0.27%   |
| Zell am See             | 1         | 0.27%   |
| Wolfsberg               | 1         | 0.27%   |
| Wilhering               | 1         | 0.27%   |
| Weidlingbach            | 1         | 0.27%   |
| Wang                    | 1         | 0.27%   |
| Vorchdorf               | 1         | 0.27%   |
| Voggenberg              | 1         | 0.27%   |
| Tulln                   | 1         | 0.27%   |
| Tragwein                | 1         | 0.27%   |
| Stinatz                 | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 57        | 84     | 16.67%  |
| Transcend           | 37        | 48     | 10.82%  |
| Kingston            | 30        | 47     | 8.77%   |
| WDC                 | 25        | 54     | 7.31%   |
| Crucial             | 22        | 30     | 6.43%   |
| Intel               | 20        | 27     | 5.85%   |
| SanDisk             | 15        | 24     | 4.39%   |
| China               | 15        | 20     | 4.39%   |
| Seagate             | 12        | 34     | 3.51%   |
| HGST                | 8         | 21     | 2.34%   |
| A-DATA Technology   | 8         | 12     | 2.34%   |
| FORESEE             | 7         | 8      | 2.05%   |
| SK hynix            | 6         | 14     | 1.75%   |
| Micron Technology   | 6         | 11     | 1.75%   |
| Hoodisk             | 6         | 8      | 1.75%   |
| Toshiba             | 4         | 7      | 1.17%   |
| Phison              | 4         | 5      | 1.17%   |
| Hewlett-Packard     | 4         | 4      | 1.17%   |
| ATP                 | 4         | 4      | 1.17%   |
| Silicon Motion      | 3         | 3      | 0.88%   |
| Patriot             | 3         | 5      | 0.88%   |
| OCZ                 | 3         | 3      | 0.88%   |
| AirDisk             | 3         | 4      | 0.88%   |
| Plextor             | 2         | 2      | 0.58%   |
| LITEONIT            | 2         | 3      | 0.58%   |
| Intenso             | 2         | 3      | 0.58%   |
| Innodisk            | 2         | 3      | 0.58%   |
| Hitachi             | 2         | 2      | 0.58%   |
| Dogfish             | 2         | 2      | 0.58%   |
| Dell                | 2         | 2      | 0.58%   |
| Corsair             | 2         | 5      | 0.58%   |
| BORY                | 2         | 5      | 0.58%   |
| BIWIN               | 2         | 2      | 0.58%   |
| BAITITON            | 2         | 2      | 0.58%   |
| Apple               | 2         | 2      | 0.58%   |
| VICKTER             | 1         | 1      | 0.29%   |
| Verbatim            | 1         | 1      | 0.29%   |
| SYNOLOGY            | 1         | 1      | 0.29%   |
| SPCC                | 1         | 2      | 0.29%   |
| Qunion              | 1         | 2      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 840 EVO 250GB               | 8         | 2.2%    |
| Kingston SKC600MS256G 256GB             | 7         | 1.92%   |
| Transcend TS128GMSA370 128GB            | 6         | 1.65%   |
| Transcend TS128GMSA230S 128GB           | 6         | 1.65%   |
| China SATA SSD 16GB                     | 6         | 1.65%   |
| Samsung SSD 850 EVO 250GB               | 5         | 1.37%   |
| Samsung SSD 860 EVO 250GB               | 4         | 1.1%    |
| FORESEE 128GB SSD                       | 4         | 1.1%    |
| Crucial CT120BX500SSD1 120GB            | 4         | 1.1%    |
| SanDisk SSD PLUS 240GB                  | 3         | 0.82%   |
| SanDisk SSD PLUS 120GB                  | 3         | 0.82%   |
| Samsung SSD 850 EVO 500GB               | 3         | 0.82%   |
| Samsung SSD 830 Series 256GB            | 3         | 0.82%   |
| Kingston SUV500MS120G 120GB             | 3         | 0.82%   |
| Kingston SA400S37240G 240GB             | 3         | 0.82%   |
| Intel SSDSC2KW128G8 128GB               | 3         | 0.82%   |
| HGST HTS725050A7E630 500GB              | 3         | 0.82%   |
| Crucial CT240BX500SSD1 240GB            | 3         | 0.82%   |
| WDC WD60EFRX-68L0BN1 6TB                | 2         | 0.55%   |
| WDC WD40EFRX-68N32N0 4TB                | 2         | 0.55%   |
| Transcend TS64GMTS400SD 64GB            | 2         | 0.55%   |
| Transcend TS64GMSA230S 64GB             | 2         | 0.55%   |
| Transcend TS480GMTS420S 480GB           | 2         | 0.55%   |
| Transcend TS256GMTS430S 256GB           | 2         | 0.55%   |
| Transcend TS256GMTE652T2 256GB          | 2         | 0.55%   |
| Transcend TS256GMSA230S 256GB           | 2         | 0.55%   |
| Transcend TS240GSSD220S 240GB           | 2         | 0.55%   |
| Transcend TS16GMSA370 16GB              | 2         | 0.55%   |
| Transcend TS128GMTS830S 128GB           | 2         | 0.55%   |
| SK hynix SC308 SATA 128GB               | 2         | 0.55%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 0.55%   |
| Silicon Motion P10D 1TB                 | 2         | 0.55%   |
| Seagate ST4000VN008-2DR166 4TB          | 2         | 0.55%   |
| SanDisk SSD PLUS 480GB                  | 2         | 0.55%   |
| Samsung SSD 980 250GB                   | 2         | 0.55%   |
| Samsung SSD 970 EVO Plus 250GB          | 2         | 0.55%   |
| Samsung SSD 870 EVO 250GB               | 2         | 0.55%   |
| Samsung SSD 860 EVO 500GB               | 2         | 0.55%   |
| Samsung MZALQ512HBLU-00BL1 512GB        | 2         | 0.55%   |
| Phison SATA SSD 16GB                    | 2         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 21        | 47     | 38.89%  |
| Seagate             | 11        | 27     | 20.37%  |
| HGST                | 8         | 21     | 14.81%  |
| Toshiba             | 4         | 7      | 7.41%   |
| Samsung Electronics | 2         | 3      | 3.7%    |
| Hitachi             | 2         | 2      | 3.7%    |
| Hewlett-Packard     | 2         | 2      | 3.7%    |
| Dell                | 2         | 2      | 3.7%    |
| SYNOLOGY            | 1         | 1      | 1.85%   |
| Apple               | 1         | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 40        | 57     | 16.74%  |
| Transcend           | 34        | 43     | 14.23%  |
| Kingston            | 28        | 45     | 11.72%  |
| Crucial             | 17        | 25     | 7.11%   |
| SanDisk             | 15        | 24     | 6.28%   |
| China               | 15        | 20     | 6.28%   |
| Intel               | 14        | 18     | 5.86%   |
| FORESEE             | 7         | 8      | 2.93%   |
| Hoodisk             | 6         | 8      | 2.51%   |
| A-DATA Technology   | 6         | 7      | 2.51%   |
| Micron Technology   | 5         | 10     | 2.09%   |
| WDC                 | 4         | 5      | 1.67%   |
| SK hynix            | 4         | 12     | 1.67%   |
| Phison              | 3         | 4      | 1.26%   |
| OCZ                 | 3         | 3      | 1.26%   |
| ATP                 | 3         | 3      | 1.26%   |
| AirDisk             | 3         | 4      | 1.26%   |
| LITEONIT            | 2         | 3      | 0.84%   |
| Intenso             | 2         | 3      | 0.84%   |
| Innodisk            | 2         | 3      | 0.84%   |
| Hewlett-Packard     | 2         | 2      | 0.84%   |
| Dogfish             | 2         | 2      | 0.84%   |
| BORY                | 2         | 5      | 0.84%   |
| BAITITON            | 2         | 2      | 0.84%   |
| VICKTER             | 1         | 1      | 0.42%   |
| Verbatim            | 1         | 1      | 0.42%   |
| SPCC                | 1         | 2      | 0.42%   |
| Seagate             | 1         | 7      | 0.42%   |
| Qunion              | 1         | 2      | 0.42%   |
| Protectli           | 1         | 1      | 0.42%   |
| Plextor             | 1         | 1      | 0.42%   |
| Patriot             | 1         | 1      | 0.42%   |
| Mushkin             | 1         | 1      | 0.42%   |
| Leven               | 1         | 2      | 0.42%   |
| Kston               | 1         | 1      | 0.42%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.42%   |
| KingSpec            | 1         | 1      | 0.42%   |
| KeepData            | 1         | 1      | 0.42%   |
| GOODRAM             | 1         | 1      | 0.42%   |
| BR                  | 1         | 1      | 0.42%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 220       | 343    | 69.84%  |
| NVMe | 50        | 74     | 15.87%  |
| HDD  | 45        | 113    | 14.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 240       | 456    | 82.76%  |
| NVMe | 50        | 74     | 17.24%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 220       | 351    | 80.59%  |
| 0.51-1.0   | 30        | 40     | 10.99%  |
| 4.01-10.0  | 8         | 29     | 2.93%   |
| 1.01-2.0   | 7         | 15     | 2.56%   |
| 3.01-4.0   | 6         | 18     | 2.2%    |
| 10.01-20.0 | 2         | 3      | 0.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 179       | 51.14%  |
| 251-500    | 63        | 18%     |
| 51-100     | 35        | 10%     |
| 21-50      | 27        | 7.71%   |
| 1-20       | 26        | 7.43%   |
| 501-1000   | 16        | 4.57%   |
| 1001-2000  | 4         | 1.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 316       | 92.94%  |
| 21-50    | 18        | 5.29%   |
| 101-250  | 2         | 0.59%   |
| 51-100   | 2         | 0.59%   |
| 251-500  | 1         | 0.29%   |
| 501-1000 | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| SK hynix SC308 SATA 128GB                       | 2         | 10     | 6.67%   |
| HGST HTS725050A7E630 500GB                      | 2         | 12     | 6.67%   |
| A-DATA Technology ASU800SS-256GT 256GB          | 2         | 2      | 6.67%   |
| WDC WD60EFRX-68L0BN1 6TB                        | 1         | 1      | 3.33%   |
| WDC WD5000AAKS-00YGA0 500GB                     | 1         | 1      | 3.33%   |
| WDC WD3200BEVT-22ZCT0 320GB                     | 1         | 1      | 3.33%   |
| WDC WD2500BEKT-66PVMT0 250GB                    | 1         | 1      | 3.33%   |
| WDC WD1600BEVS-00UST0 160GB                     | 1         | 1      | 3.33%   |
| WDC WD1600BEKT-08PVMT1 160GB                    | 1         | 2      | 3.33%   |
| Seagate ST9500325AS 500GB                       | 1         | 1      | 3.33%   |
| SanDisk SSD PLUS 240GB                          | 1         | 1      | 3.33%   |
| SanDisk SD7SB3Q128G1001 128GB                   | 1         | 2      | 3.33%   |
| Samsung Electronics SSD 970 EVO 1TB             | 1         | 1      | 3.33%   |
| Samsung Electronics MZ7PA128HMCD-010H1 128GB    | 1         | 1      | 3.33%   |
| Samsung Electronics HM500LI 500GB               | 1         | 2      | 3.33%   |
| OCZ AGILITY3 120GB                              | 1         | 1      | 3.33%   |
| Micron Technology MTFDDAK256TDL-1AW1ZABHA 256GB | 1         | 1      | 3.33%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB      | 1         | 2      | 3.33%   |
| Intel SSDSCKKF256G8H 256GB                      | 1         | 2      | 3.33%   |
| Intel SSDSC2KF512G8 SATA 512GB                  | 1         | 2      | 3.33%   |
| Intel SSDPEKKW128G7 128GB                       | 1         | 1      | 3.33%   |
| Hitachi HTS541040G9SA00 40GB                    | 1         | 1      | 3.33%   |
| Hitachi HDS721050CLA660 500GB                   | 1         | 1      | 3.33%   |
| HGST HTS721010A9E630 1TB                        | 1         | 1      | 3.33%   |
| China XJH-128GB                                 | 1         | 1      | 3.33%   |
| A-DATA Technology SU630 240GB                   | 1         | 1      | 3.33%   |
| A-DATA Technology ASU800SS-128GT 128GB          | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 20%     |
| A-DATA Technology   | 4         | 4      | 13.33%  |
| Samsung Electronics | 3         | 4      | 10%     |
| Intel               | 3         | 5      | 10%     |
| HGST                | 3         | 13     | 10%     |
| SK hynix            | 2         | 10     | 6.67%   |
| SanDisk             | 2         | 3      | 6.67%   |
| Micron Technology   | 2         | 3      | 6.67%   |
| Hitachi             | 2         | 2      | 6.67%   |
| Seagate             | 1         | 1      | 3.33%   |
| OCZ                 | 1         | 1      | 3.33%   |
| China               | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 46.15%  |
| HGST                | 3         | 13     | 23.08%  |
| Hitachi             | 2         | 2      | 15.38%  |
| Seagate             | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 15        | 27     | 50%     |
| HDD  | 13        | 25     | 43.33%  |
| NVMe | 2         | 2      | 6.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Intel SSDPEKKW128G7 128GB | 1         | 1      | 50%     |
| Crucial CT250P2SSD8 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Intel   | 1         | 1      | 50%     |
| Crucial | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 257       | 465    | 87.71%  |
| Malfunc  | 27        | 54     | 9.22%   |
| Detected | 7         | 9      | 2.39%   |
| Failed   | 2         | 2      | 0.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 255       | 61.3%   |
| AMD                         | 52        | 12.5%   |
| Samsung Electronics         | 24        | 5.77%   |
| Silicon Motion              | 8         | 1.92%   |
| Phison Electronics          | 8         | 1.92%   |
| SanDisk                     | 7         | 1.68%   |
| Broadcom / LSI              | 7         | 1.68%   |
| ASMedia Technology          | 7         | 1.68%   |
| Micron/Crucial Technology   | 6         | 1.44%   |
| MAXIO Technology (Hangzhou) | 5         | 1.2%    |
| Hewlett-Packard             | 5         | 1.2%    |
| Transcend                   | 4         | 0.96%   |
| SK hynix                    | 4         | 0.96%   |
| Micron Technology           | 4         | 0.96%   |
| Kingston Technology Company | 3         | 0.72%   |
| Marvell Technology Group    | 2         | 0.48%   |
| Lite-On Technology          | 2         | 0.48%   |
| KIOXIA                      | 2         | 0.48%   |
| JMicron Technology          | 2         | 0.48%   |
| Chelsio Communications      | 2         | 0.48%   |
| Yangtze Memory Technologies | 1         | 0.24%   |
| Toshiba                     | 1         | 0.24%   |
| Realtek Semiconductor       | 1         | 0.24%   |
| Dell                        | 1         | 0.24%   |
| ATP ELECTRONICS             | 1         | 0.24%   |
| Apple                       | 1         | 0.24%   |
| ADATA Technology            | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 37        | 8.3%    |
| Intel Alder Lake-N SATA AHCI Controller                                          | 25        | 5.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 19        | 4.26%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 18        | 4.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 18        | 4.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 17        | 3.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 3.36%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 10        | 2.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 2.02%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 9         | 2.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 2.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 2.02%   |
| AMD FCH SATA Controller [IDE mode]                                               | 8         | 1.79%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 7         | 1.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7         | 1.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7         | 1.57%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 6         | 1.35%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 6         | 1.35%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 5         | 1.12%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 5         | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.12%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 1.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 1.12%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 0.9%    |
| HP Smart Array G6 controllers                                                    | 4         | 0.9%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 4         | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 0.9%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 3         | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.67%   |
| Micron 2550 NVMe SSD (DRAM-less)                                                 | 3         | 0.67%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.67%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 0.67%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 3         | 0.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.67%   |
| Intel Elkhart Lake SATA AHCI                                                     | 3         | 0.67%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 3         | 0.67%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 3         | 0.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 284       | 67.94%  |
| NVMe | 86        | 20.57%  |
| IDE  | 25        | 5.98%   |
| RAID | 13        | 3.11%   |
| SCSI | 6         | 1.44%   |
| SAS  | 4         | 0.96%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 268       | 80.97%  |
| AMD     | 58        | 17.52%  |
| ARM     | 3         | 0.91%   |
| Unknown | 2         | 0.6%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel N100                             | 21        | 6.31%   |
| AMD GX-412TC SOC                       | 18        | 5.41%   |
| Intel Celeron N5105 @ 2.00GHz          | 11        | 3.3%    |
| Intel Celeron J4125 CPU @ 2.00GHz      | 10        | 3%      |
| Intel Celeron CPU J3160 @ 1.60GHz      | 9         | 2.7%    |
| AMD GX-420MC SOC                       | 6         | 1.8%    |
| Intel Celeron CPU N3450 @ 1.10GHz      | 5         | 1.5%    |
| Intel Core i5-7200U CPU @ 2.50GHz      | 4         | 1.2%    |
| Intel Core i5-6500 CPU @ 3.20GHz       | 4         | 1.2%    |
| Intel Core i3-6100T CPU @ 3.20GHz      | 4         | 1.2%    |
| Intel Celeron J4105 CPU @ 1.50GHz      | 4         | 1.2%    |
| Intel Celeron CPU J3455 @ 1.50GHz      | 4         | 1.2%    |
| Intel Celeron CPU J1900 @ 1.99GHz      | 4         | 1.2%    |
| Intel Atom CPU C3558 @ 2.20GHz         | 4         | 1.2%    |
| Intel Xeon CPU E5620 @ 2.40GHz         | 3         | 0.9%    |
| Intel N150                             | 3         | 0.9%    |
| Intel Core i5-4200U CPU @ 1.60GHz      | 3         | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz     | 3         | 0.9%    |
| Intel Celeron J6412 @ 2.00GHz          | 3         | 0.9%    |
| Intel Celeron CPU N3150 @ 1.60GHz      | 3         | 0.9%    |
| Intel Atom CPU E3845 @ 1.91GHz         | 3         | 0.9%    |
| Intel Atom CPU D525 @ 1.80GHz          | 3         | 0.9%    |
| Intel Atom CPU C2358 @ 1.74GHz         | 3         | 0.9%    |
| AMD Ryzen Embedded V1500B              | 3         | 0.9%    |
| AMD Ryzen 5 5500U with Radeon Graphics | 3         | 0.9%    |
| AMD G-T40E Processor                   | 3         | 0.9%    |
| Intel Pentium CPU N4200 @ 1.10GHz      | 2         | 0.6%    |
| Intel Pentium CPU N3700 @ 1.60GHz      | 2         | 0.6%    |
| Intel Pentium CPU G3220 @ 3.00GHz      | 2         | 0.6%    |
| Intel N200                             | 2         | 0.6%    |
| Intel Core i7-8665U CPU @ 1.90GHz      | 2         | 0.6%    |
| Intel Core i7-8565U CPU @ 1.80GHz      | 2         | 0.6%    |
| Intel Core i5-8365U CPU @ 1.60GHz      | 2         | 0.6%    |
| Intel Core i5-6600 CPU @ 3.30GHz       | 2         | 0.6%    |
| Intel Core i5-6400 CPU @ 2.70GHz       | 2         | 0.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz       | 2         | 0.6%    |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2         | 0.6%    |
| Intel Core i5-10310U CPU @ 1.70GHz     | 2         | 0.6%    |
| Intel Core i5 CPU M 520 @ 2.40GHz      | 2         | 0.6%    |
| Intel Core i3-N305                     | 2         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 73        | 21.92%  |
| Intel Core i5           | 54        | 16.22%  |
| Other                   | 41        | 12.31%  |
| AMD GX                  | 29        | 8.71%   |
| Intel Core i3           | 24        | 7.21%   |
| Intel Atom              | 23        | 6.91%   |
| Intel Xeon              | 22        | 6.61%   |
| Intel Core i7           | 20        | 6.01%   |
| Intel Pentium           | 8         | 2.4%    |
| AMD Ryzen 5             | 7         | 2.1%    |
| Intel Core 2 Duo        | 3         | 0.9%    |
| AMD Ryzen Embedded      | 3         | 0.9%    |
| AMD G                   | 3         | 0.9%    |
| ARM Cortex              | 2         | 0.6%    |
| AMD Ryzen 9             | 2         | 0.6%    |
| AMD Ryzen 7             | 2         | 0.6%    |
| AMD Ryzen 5 PRO         | 2         | 0.6%    |
| AMD Athlon              | 2         | 0.6%    |
| Intel Pentium Silver    | 1         | 0.3%    |
| Intel Pentium Dual-Core | 1         | 0.3%    |
| Intel Pentium 4         | 1         | 0.3%    |
| Intel Genuine           | 1         | 0.3%    |
| Intel Core 2 Quad       | 1         | 0.3%    |
| Intel Core 2            | 1         | 0.3%    |
| AMD Turion II Neo       | 1         | 0.3%    |
| AMD Ryzen Threadripper  | 1         | 0.3%    |
| AMD Opteron             | 1         | 0.3%    |
| AMD FX                  | 1         | 0.3%    |
| AMD EPYC                | 1         | 0.3%    |
| AMD Embedded            | 1         | 0.3%    |
| AMD A4                  | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 191       | 57.53%  |
| 2       | 84        | 25.3%   |
| 8       | 21        | 6.33%   |
| 6       | 11        | 3.31%   |
| Unknown | 10        | 3.01%   |
| 12      | 8         | 2.41%   |
| 16      | 2         | 0.6%    |
| 1       | 2         | 0.6%    |
| 64      | 1         | 0.3%    |
| 24      | 1         | 0.3%    |
| 14      | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 313       | 94.56%  |
| Unknown | 10        | 3.02%   |
| 2       | 8         | 2.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 215       | 64.56%  |
| 2       | 106       | 31.83%  |
| Unknown | 12        | 3.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 58        | 17.47%  |
| KabyLake      | 38        | 11.45%  |
| Silvermont    | 33        | 9.94%   |
| Puma          | 25        | 7.53%   |
| Goldmont      | 23        | 6.93%   |
| Skylake       | 21        | 6.33%   |
| Haswell       | 19        | 5.72%   |
| Goldmont plus | 18        | 5.42%   |
| IvyBridge     | 16        | 4.82%   |
| SandyBridge   | 11        | 3.31%   |
| Broadwell     | 9         | 2.71%   |
| Zen           | 8         | 2.41%   |
| Westmere      | 8         | 2.41%   |
| Penryn        | 6         | 1.81%   |
| Jaguar        | 6         | 1.81%   |
| TigerLake     | 4         | 1.2%    |
| Excavator     | 4         | 1.2%    |
| Bonnell       | 4         | 1.2%    |
| Zen 3         | 3         | 0.9%    |
| Zen 2         | 3         | 0.9%    |
| CometLake     | 3         | 0.9%    |
| Bobcat        | 3         | 0.9%    |
| Nehalem       | 2         | 0.6%    |
| IceLake       | 2         | 0.6%    |
| Core          | 2         | 0.6%    |
| Zen+          | 1         | 0.3%    |
| NetBurst      | 1         | 0.3%    |
| K10           | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 222       | 73.75%  |
| AMD                        | 33        | 10.96%  |
| ASPEED Technology          | 27        | 8.97%   |
| Nvidia                     | 13        | 4.32%   |
| Matrox Electronics Systems | 5         | 1.66%   |
| Huawei Technologies        | 1         | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 27        | 8.85%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 25        | 8.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 5.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 5.57%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 15        | 4.92%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 15        | 4.92%   |
| Intel JasperLake [UHD Graphics]                                                          | 11        | 3.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 2.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 2.62%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 2.3%    |
| AMD ES1000                                                                               | 7         | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.97%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 6         | 1.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.97%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                                  | 5         | 1.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.31%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.31%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 3         | 0.98%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 3         | 0.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.98%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 3         | 0.98%   |
| Intel Alder Lake-N [Intel Graphics]                                                      | 3         | 0.98%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.98%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.98%   |
| AMD Lucienne                                                                             | 3         | 0.98%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 0.66%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 0.66%   |
| Intel Skylake-S GT1 [HD Graphics 510]                                                    | 2         | 0.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.66%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 0.66%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.66%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.66%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 2         | 0.66%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 2         | 0.66%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 0.66%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| 1 x Intel                    | 213       | 64.16%  |
| Other                        | 37        | 11.14%  |
| 1 x AMD                      | 32        | 9.64%   |
| 1 x ASPEED                   | 24        | 7.23%   |
| 1 x Nvidia                   | 10        | 3.01%   |
| 2 x Intel                    | 5         | 1.51%   |
| 1 x Matrox                   | 5         | 1.51%   |
| Intel + ASPEED               | 2         | 0.6%    |
| Nvidia + Huawei Technologies | 1         | 0.3%    |
| Nvidia + ASPEED              | 1         | 0.3%    |
| Intel + Nvidia               | 1         | 0.3%    |
| Intel + AMD                  | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 286       | 86.4%   |
| Unknown     | 37        | 11.18%  |
| Proprietary | 8         | 2.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 317       | 95.2%   |
| 0.51-1.0   | 4         | 1.2%    |
| 7.01-8.0   | 3         | 0.9%    |
| 3.01-4.0   | 3         | 0.9%    |
| 0.01-0.5   | 3         | 0.9%    |
| 1.01-2.0   | 2         | 0.6%    |
| 16.01-24.0 | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 6         | 11.32%  |
| LG Display           | 6         | 11.32%  |
| AU Optronics         | 6         | 11.32%  |
| Lenovo               | 5         | 9.43%   |
| Dell                 | 4         | 7.55%   |
| Philips              | 3         | 5.66%   |
| Chimei Innolux       | 3         | 5.66%   |
| BOE                  | 3         | 5.66%   |
| BenQ                 | 3         | 5.66%   |
| Ancor Communications | 3         | 5.66%   |
| Goldstar             | 2         | 3.77%   |
| Apple                | 2         | 3.77%   |
| Unknown              | 1         | 1.89%   |
| PANDA                | 1         | 1.89%   |
| Medion               | 1         | 1.89%   |
| InfoVision           | 1         | 1.89%   |
| Hewlett-Packard      | 1         | 1.89%   |
| DENON                | 1         | 1.89%   |
| ASUSTek Computer     | 1         | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Ancor Communications ASUS MG278 ACI27A8 2560x1440 600x340mm 27.2-inch | 3         | 5.45%   |
| Samsung Electronics C34J79x SAM0F1E 3440x1440 800x330mm 34.1-inch     | 2         | 3.64%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch               | 2         | 3.64%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch          | 2         | 3.64%   |
| BenQ BL2405 BNQ8016 1920x1080 530x300mm 24.0-inch                     | 2         | 3.64%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 310x170mm 13.9-inch        | 2         | 3.64%   |
| Unknown LCD Monitor Sharp 3840x2160                                   | 1         | 1.82%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch     | 1         | 1.82%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch  | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 700x390mm 31.5-inch | 1         | 1.82%   |
| Samsung Electronics CJG9S SAM9596 3840x1080                           | 1         | 1.82%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 1         | 1.82%   |
| Philips PHL BDM4037U PHLC142 3840x2160 890x500mm 40.2-inch            | 1         | 1.82%   |
| PANDA LM116LF3L02 NCP000A 1920x1080 260x150mm 11.8-inch               | 1         | 1.82%   |
| Medion MD22321 MEA8302 1920x1080 700x390mm 31.5-inch                  | 1         | 1.82%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD03FC 1600x900 310x170mm 13.9-inch           | 1         | 1.82%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 1.82%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 1         | 1.82%   |
| Lenovo P24h-10 LEN61AE 2560x1440 530x300mm 24.0-inch                  | 1         | 1.82%   |
| Lenovo LCD Monitor LEN40B0 1366x768 350x190mm 15.7-inch               | 1         | 1.82%   |
| Lenovo LCD Monitor LEN4043 1400x1050 300x230mm 14.9-inch              | 1         | 1.82%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch               | 1         | 1.82%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch               | 1         | 1.82%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 1.82%   |
| Hewlett-Packard E273 HPN3470 1920x1080 600x340mm 27.2-inch            | 1         | 1.82%   |
| Goldstar LG ULTRAGEAR+ GSM5C34 2560x1440 590x330mm 26.6-inch          | 1         | 1.82%   |
| Goldstar LG ULTRAGEAR+ GSM5C33 2560x1440 590x330mm 26.6-inch          | 1         | 1.82%   |
| DENON AVR DON004B 1920x1080 1330x750mm 60.1-inch                      | 1         | 1.82%   |
| Dell U2715H DELD069 2560x1440 600x340mm 27.2-inch                     | 1         | 1.82%   |
| Dell U2715H DELD066 2560x1440 600x340mm 27.2-inch                     | 1         | 1.82%   |
| Dell P2719H DEL4185 1920x1080 600x340mm 27.2-inch                     | 1         | 1.82%   |
| Dell P2210 DEL404E 1680x1050 470x300mm 22.0-inch                      | 1         | 1.82%   |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                     | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch       | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 1         | 1.82%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                 | 1         | 1.82%   |
| BOE LCD Monitor BOE0791 1920x1080 310x170mm 13.9-inch                 | 1         | 1.82%   |
| BOE LCD Monitor BOE0714 1920x1080 310x170mm 13.9-inch                 | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 40%     |
| 2560x1440 (QHD)    | 10        | 20%     |
| 1366x768 (WXGA)    | 4         | 8%      |
| 3840x2160 (4K)     | 3         | 6%      |
| 1600x900 (HD+)     | 3         | 6%      |
| 3440x1440          | 2         | 4%      |
| 1680x1050 (WSXGA+) | 2         | 4%      |
| 1440x900 (WXGA+)   | 2         | 4%      |
| 3840x1080          | 1         | 2%      |
| 1600x1200          | 1         | 2%      |
| 1400x1050          | 1         | 2%      |
| 1280x800 (WXGA)    | 1         | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 15        | 27.78%  |
| 27      | 12        | 22.22%  |
| 15      | 4         | 7.41%   |
| 24      | 3         | 5.56%   |
| 14      | 3         | 5.56%   |
| Unknown | 3         | 5.56%   |
| 34      | 2         | 3.7%    |
| 31      | 2         | 3.7%    |
| 26      | 2         | 3.7%    |
| 20      | 2         | 3.7%    |
| 11      | 2         | 3.7%    |
| 60      | 1         | 1.85%   |
| 46      | 1         | 1.85%   |
| 40      | 1         | 1.85%   |
| 22      | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 35.29%  |
| 501-600     | 14        | 27.45%  |
| 201-300     | 6         | 11.76%  |
| 401-500     | 3         | 5.88%   |
| Unknown     | 3         | 5.88%   |
| 701-800     | 2         | 3.92%   |
| 601-700     | 2         | 3.92%   |
| 1001-1500   | 2         | 3.92%   |
| 801-900     | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 33        | 73.33%  |
| 16/10   | 5         | 11.11%  |
| 4/3     | 2         | 4.44%   |
| 21/9    | 2         | 4.44%   |
| Unknown | 2         | 4.44%   |
| 32/9    | 1         | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 17        | 32.69%  |
| 301-350        | 12        | 23.08%  |
| 351-500        | 4         | 7.69%   |
| 201-250        | 4         | 7.69%   |
| 101-110        | 3         | 5.77%   |
| Unknown        | 3         | 5.77%   |
| 51-60          | 2         | 3.85%   |
| 151-200        | 2         | 3.85%   |
| 501-1000       | 2         | 3.85%   |
| 91-100         | 2         | 3.85%   |
| More than 1000 | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 16        | 32%     |
| 51-100  | 13        | 26%     |
| 101-120 | 12        | 24%     |
| 161-240 | 4         | 8%      |
| Unknown | 3         | 6%      |
| 1-50    | 2         | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 286       | 85.89%  |
| 1     | 35        | 10.51%  |
| 2     | 11        | 3.3%    |
| 3     | 1         | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 268       | 63.36%  |
| Realtek Semiconductor             | 94        | 22.22%  |
| Broadcom                          | 16        | 3.78%   |
| Qualcomm Atheros                  | 11        | 2.6%    |
| TP-Link                           | 4         | 0.95%   |
| AMD                               | 4         | 0.95%   |
| LG Electronics                    | 3         | 0.71%   |
| Edimax Technology                 | 3         | 0.71%   |
| Mellanox Technologies             | 2         | 0.47%   |
| Chelsio Communications            | 2         | 0.47%   |
| Seeed Technology                  | 1         | 0.24%   |
| Samsung Electronics               | 1         | 0.24%   |
| QLogic                            | 1         | 0.24%   |
| Microchip Technology              | 1         | 0.24%   |
| MediaTek                          | 1         | 0.24%   |
| Lenovo                            | 1         | 0.24%   |
| Hewlett-Packard                   | 1         | 0.24%   |
| Google                            | 1         | 0.24%   |
| Ericsson Business Mobile Networks | 1         | 0.24%   |
| Dresden Elektronik                | 1         | 0.24%   |
| Dell                              | 1         | 0.24%   |
| Davicom Semiconductor             | 1         | 0.24%   |
| AVM                               | 1         | 0.24%   |
| Arduino SA                        | 1         | 0.24%   |
| Apple                             | 1         | 0.24%   |
| American Megatrends               | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 81        | 14.89%  |
| Intel I211 Gigabit Network Connection                                         | 56        | 10.29%  |
| Intel I210 Gigabit Network Connection                                         | 41        | 7.54%   |
| Intel Ethernet Controller I226-V                                              | 40        | 7.35%   |
| Intel Ethernet Controller I225-V                                              | 17        | 3.13%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 15        | 2.76%   |
| Intel I350 Gigabit Network Connection                                         | 14        | 2.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 14        | 2.57%   |
| Intel Wireless 7265                                                           | 9         | 1.65%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 9         | 1.65%   |
| Intel Ethernet Connection (2) I219-LM                                         | 9         | 1.65%   |
| Intel 82574L Gigabit Network Connection                                       | 8         | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7         | 1.29%   |
| Intel Wi-Fi 6 AX200                                                           | 7         | 1.29%   |
| Intel Wireless 7260                                                           | 6         | 1.1%    |
| Intel Ethernet Connection I354                                                | 6         | 1.1%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 6         | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 5         | 0.92%   |
| Intel Wireless 3165                                                           | 5         | 0.92%   |
| Intel Ethernet Connection X553 1GbE                                           | 5         | 0.92%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 0.92%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 4         | 0.74%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 0.74%   |
| Intel Ethernet Connection (6) I219-LM                                         | 4         | 0.74%   |
| Intel Centrino Ultimate-N 6300                                                | 4         | 0.74%   |
| AMD XGMAC 10GbE Controller                                                    | 4         | 0.74%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 3         | 0.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 3         | 0.55%   |
| LG Optimus Android Phone [USB tethering mode]                                 | 3         | 0.55%   |
| Intel Wireless 3160                                                           | 3         | 0.55%   |
| Intel Ethernet Connection I217-V                                              | 3         | 0.55%   |
| Intel Ethernet Connection I217-LM                                             | 3         | 0.55%   |
| Intel Centrino Advanced-N 6235                                                | 3         | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 3         | 0.55%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 0.55%   |
| Intel 82580 Gigabit Network Connection                                        | 3         | 0.55%   |
| Intel 82577LM Gigabit Network Connection                                      | 3         | 0.55%   |
| Intel 82575EB Gigabit Network Connection                                      | 3         | 0.55%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 64        | 64%     |
| Realtek Semiconductor | 15        | 15%     |
| Qualcomm Atheros      | 10        | 10%     |
| TP-Link               | 4         | 4%      |
| Edimax Technology     | 3         | 3%      |
| Broadcom              | 2         | 2%      |
| MediaTek              | 1         | 1%      |
| Dell                  | 1         | 1%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                             | 9         | 8.91%   |
| Intel Wi-Fi 6 AX200                                             | 7         | 6.93%   |
| Intel Wireless 7260                                             | 6         | 5.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 5         | 4.95%   |
| Intel Wireless 3165                                             | 5         | 4.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 4         | 3.96%   |
| Intel Wireless 8265 / 8275                                      | 4         | 3.96%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 3         | 2.97%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 3         | 2.97%   |
| Intel Wireless 3160                                             | 3         | 2.97%   |
| Intel Centrino Ultimate-N 6300                                  | 3         | 2.97%   |
| Intel Centrino Advanced-N 6235                                  | 3         | 2.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 3         | 2.97%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 3         | 2.97%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter        | 2         | 1.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 2         | 1.98%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 2         | 1.98%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 2         | 1.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 2         | 1.98%   |
| TP-Link 802.11ac WLAN Adapter 802.11ac WLAN Adapter             | 1         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 1         | 0.99%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 1         | 0.99%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                 | 1         | 0.99%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 1         | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 1         | 0.99%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1         | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 1         | 0.99%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1         | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 1         | 0.99%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 1         | 0.99%   |
| Intel Wireless 8260                                             | 1         | 0.99%   |
| Intel WiFi Link 5100                                            | 1         | 0.99%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 1         | 0.99%   |
| Intel Wi-Fi 6 AX201                                             | 1         | 0.99%   |
| Intel Ultimate N WiFi Link 5300                                 | 1         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection           | 1         | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                 | 1         | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                 | 1         | 0.99%   |
| Intel Centrino Wireless-N 2230                                  | 1         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 241       | 67.13%  |
| Realtek Semiconductor  | 88        | 24.51%  |
| Broadcom               | 16        | 4.46%   |
| AMD                    | 4         | 1.11%   |
| Chelsio Communications | 2         | 0.56%   |
| Samsung Electronics    | 1         | 0.28%   |
| Qualcomm Atheros       | 1         | 0.28%   |
| QLogic                 | 1         | 0.28%   |
| Microchip Technology   | 1         | 0.28%   |
| Lenovo                 | 1         | 0.28%   |
| Davicom Semiconductor  | 1         | 0.28%   |
| Apple                  | 1         | 0.28%   |
| American Megatrends    | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 81        | 18.88%  |
| Intel I211 Gigabit Network Connection                                         | 56        | 13.05%  |
| Intel I210 Gigabit Network Connection                                         | 41        | 9.56%   |
| Intel Ethernet Controller I226-V                                              | 40        | 9.32%   |
| Intel Ethernet Controller I225-V                                              | 17        | 3.96%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 15        | 3.5%    |
| Intel I350 Gigabit Network Connection                                         | 14        | 3.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 14        | 3.26%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 9         | 2.1%    |
| Intel Ethernet Connection (2) I219-LM                                         | 9         | 2.1%    |
| Intel 82574L Gigabit Network Connection                                       | 8         | 1.86%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7         | 1.63%   |
| Intel Ethernet Connection I354                                                | 6         | 1.4%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 6         | 1.4%    |
| Intel Ethernet Connection X553 1GbE                                           | 5         | 1.17%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 1.17%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 1.17%   |
| Intel Ethernet Connection (6) I219-LM                                         | 4         | 0.93%   |
| AMD XGMAC 10GbE Controller                                                    | 4         | 0.93%   |
| Intel Ethernet Connection I217-V                                              | 3         | 0.7%    |
| Intel Ethernet Connection I217-LM                                             | 3         | 0.7%    |
| Intel 82583V Gigabit Network Connection                                       | 3         | 0.7%    |
| Intel 82580 Gigabit Network Connection                                        | 3         | 0.7%    |
| Intel 82577LM Gigabit Network Connection                                      | 3         | 0.7%    |
| Intel 82575EB Gigabit Network Connection                                      | 3         | 0.7%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 0.7%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 2         | 0.47%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 2         | 0.47%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 2         | 0.47%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2         | 0.47%   |
| Intel Ethernet Connection (3) I218-V                                          | 2         | 0.47%   |
| Intel Ethernet Connection (17) I219-V                                         | 2         | 0.47%   |
| Intel Ethernet Connection (14) I219-V                                         | 2         | 0.47%   |
| Intel 82567LM Gigabit Network Connection                                      | 2         | 0.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 2         | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.23%   |
| Realtek USB 2.5GbE Controller                                                 | 1         | 0.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 322       | 74.88%  |
| WiFi     | 94        | 21.86%  |
| Modem    | 7         | 1.63%   |
| Unknown  | 7         | 1.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 309       | 92.24%  |
| WiFi     | 25        | 7.46%   |
| Modem    | 1         | 0.3%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 4     | 79        | 23.65%  |
| 2     | 79        | 23.65%  |
| 3     | 64        | 19.16%  |
| 6     | 34        | 10.18%  |
| 1     | 33        | 9.88%   |
| 5     | 15        | 4.49%   |
| 8     | 10        | 2.99%   |
| 9     | 7         | 2.1%    |
| 12    | 4         | 1.2%    |
| 7     | 4         | 1.2%    |
| 0     | 4         | 1.2%    |
| 10    | 1         | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 311       | 92.01%  |
| Yes  | 27        | 7.99%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 69.01%  |
| Realtek Semiconductor           | 8         | 11.27%  |
| Broadcom                        | 4         | 5.63%   |
| IMC Networks                    | 3         | 4.23%   |
| Qualcomm Atheros Communications | 2         | 2.82%   |
| Apple                           | 2         | 2.82%   |
| MediaTek                        | 1         | 1.41%   |
| Lite-On Technology              | 1         | 1.41%   |
| Alps Electric                   | 1         | 1.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 22        | 30.99%  |
| Intel AX200 Bluetooth                            | 8         | 11.27%  |
| Realtek Bluetooth Adapter                        | 6         | 8.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 5         | 7.04%   |
| Intel AX201 Bluetooth                            | 5         | 7.04%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 4         | 5.63%   |
| Broadcom BCM2045B (BDC-2.1)                      | 3         | 4.23%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1           | 2         | 2.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 2         | 2.82%   |
| IMC Networks Realtek Bluetooth Adapter           | 2         | 2.82%   |
| Realtek RTL8821A Bluetooth                       | 1         | 1.41%   |
| Realtek Bluetooth 5.1 Adapter                    | 1         | 1.41%   |
| MediaTek RZ608 Bluetooth Adapter                 | 1         | 1.41%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 1.41%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 1.41%   |
| Intel AX211 Bluetooth                            | 1         | 1.41%   |
| Intel AX210 Bluetooth                            | 1         | 1.41%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1      | 1         | 1.41%   |
| Broadcom BCM2035 Bluetooth dongle                | 1         | 1.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI             | 1         | 1.41%   |
| Apple Broadcom Built-in Bluetooth                | 1         | 1.41%   |
| Alps Electric UGTZ4 Bluetooth                    | 1         | 1.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 200       | 76.92%  |
| AMD                                          | 30        | 11.54%  |
| Nvidia                                       | 9         | 3.46%   |
| Plantronics                                  | 4         | 1.54%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 1.15%   |
| Kingston Technology                          | 3         | 1.15%   |
| Lenovo                                       | 2         | 0.77%   |
| Walmart                                      | 1         | 0.38%   |
| Texas Instruments                            | 1         | 0.38%   |
| Sony                                         | 1         | 0.38%   |
| RODE Microphones                             | 1         | 0.38%   |
| ROCCAT                                       | 1         | 0.38%   |
| GN Netcom                                    | 1         | 0.38%   |
| Creative Labs                                | 1         | 0.38%   |
| C-Media Electronics                          | 1         | 0.38%   |
| Apple                                        | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 28        | 9.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 17        | 5.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 5.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 16        | 5.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 13        | 4.35%   |
| Intel Jasper Lake HD Audio                                                                        | 11        | 3.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 3.68%   |
| AMD Ryzen HD Audio Controller                                                                     | 11        | 3.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 3.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.68%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 2.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 2.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 2.34%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.01%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.67%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.67%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.67%   |
| Plantronics Plantronics Blackwire 315.1                                                           | 4         | 1.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.34%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.34%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 4         | 1.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.34%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 3         | 1%      |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1%      |
| Kingston Technology HyperX QuadCast                                                               | 3         | 1%      |
| Intel Elkhart Lake High Density Audio bus interface                                               | 3         | 1%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1%      |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 1%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1%      |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.67%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 2         | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.67%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 49        | 15.22%  |
| Crucial             | 45        | 13.98%  |
| Unknown             | 36        | 11.18%  |
| Kingston            | 35        | 10.87%  |
| SK hynix            | 33        | 10.25%  |
| Micron Technology   | 28        | 8.7%    |
| Corsair             | 17        | 5.28%   |
| Unknown (ABCD)      | 15        | 4.66%   |
| Unknown             | 15        | 4.66%   |
| A-DATA Technology   | 8         | 2.48%   |
| Transcend           | 7         | 2.17%   |
| G.Skill             | 6         | 1.86%   |
| Nanya Technology    | 3         | 0.93%   |
| Unknown (0x0FBA)    | 2         | 0.62%   |
| Toshiba             | 2         | 0.62%   |
| Ramaxel Technology  | 2         | 0.62%   |
| Kimtigo             | 2         | 0.62%   |
| Timetec             | 1         | 0.31%   |
| tigo                | 1         | 0.31%   |
| Smart Modular       | 1         | 0.31%   |
| Mushkin             | 1         | 0.31%   |
| Miron               | 1         | 0.31%   |
| Lexar Co Limited    | 1         | 0.31%   |
| Kingmax             | 1         | 0.31%   |
| Innodisk            | 1         | 0.31%   |
| GOODRAM             | 1         | 0.31%   |
| GeIL                | 1         | 0.31%   |
| Elpida              | 1         | 0.31%   |
| DSL                 | 1         | 0.31%   |
| Axiom               | 1         | 0.31%   |
| Avant               | 1         | 0.31%   |
| ATP                 | 1         | 0.31%   |
| AMD                 | 1         | 0.31%   |
| A-DA                | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s | 15        | 4.5%    |
| Unknown                                                      | 15        | 4.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 8         | 2.4%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 4         | 1.2%    |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s      | 4         | 1.2%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 3         | 0.9%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 3         | 0.9%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 3         | 0.9%    |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s          | 3         | 0.9%    |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                | 3         | 0.9%    |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s          | 3         | 0.9%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 3         | 0.9%    |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 3200MT/s       | 3         | 0.9%    |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s      | 3         | 0.9%    |
| A-DATA RAM Module 4GB SODIMM DDR3 1600MT/s                   | 3         | 0.9%    |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s                   | 2         | 0.6%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 2         | 0.6%    |
| Unknown RAM AW24P64F8BLK0S 8GB DIMM DDR3 1600MT/s            | 2         | 0.6%    |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s         | 2         | 0.6%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.6%    |
| SK hynix RAM HMT125U6BFR8C-G7 2GB DIMM DDR3 1067MT/s         | 2         | 0.6%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 2         | 0.6%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 2         | 0.6%    |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s       | 2         | 0.6%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s        | 2         | 0.6%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s          | 2         | 0.6%    |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s      | 2         | 0.6%    |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s           | 2         | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 0.6%    |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s        | 2         | 0.6%    |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s         | 2         | 0.6%    |
| G.Skill RAM F3-1600C11-8GSL 8GB SODIMM DDR3 1600MT/s         | 2         | 0.6%    |
| Crucial RAM CT8G4SFS824A.M8FRS 8GB DIMM DDR4 2400MT/s        | 2         | 0.6%    |
| Crucial RAM CT8G4SFRA266.M8FRS 8GB SODIMM DDR4 2667MT/s      | 2         | 0.6%    |
| Crucial RAM CT4G4SFS824A.C8FBD 4GB SODIMM DDR4 2400MT/s      | 2         | 0.6%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 2         | 0.6%    |
| A-DATA RAM AM1P24HC4U1-B9RS 4GB SODIMM DDR4 2400MT/s         | 2         | 0.6%    |
| Unknown RAM X4B08QD8BNVFSO-7-TO1 8GB DIMM DDR4 2933MT/s      | 1         | 0.3%    |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 0.3%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 1         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 123       | 41.98%  |
| DDR4    | 114       | 38.91%  |
| DDR5    | 24        | 8.19%   |
| LPDDR4  | 19        | 6.48%   |
| DDR2    | 5         | 1.71%   |
| LPDDR5  | 4         | 1.37%   |
| Unknown | 2         | 0.68%   |
| LPDDR3  | 1         | 0.34%   |
| DRAM    | 1         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 158       | 54.3%   |
| DIMM         | 119       | 40.89%  |
| Row Of Chips | 9         | 3.09%   |
| Unknown      | 3         | 1.03%   |
| Chip         | 2         | 0.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 119       | 38.64%  |
| 4096  | 79        | 25.65%  |
| 16384 | 61        | 19.81%  |
| 2048  | 26        | 8.44%   |
| 32768 | 16        | 5.19%   |
| 3072  | 3         | 0.97%   |
| 1024  | 3         | 0.97%   |
| 6144  | 1         | 0.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 77        | 25.08%  |
| 2400    | 49        | 15.96%  |
| 3200    | 44        | 14.33%  |
| 1333    | 39        | 12.7%   |
| 2667    | 28        | 9.12%   |
| 4800    | 18        | 5.86%   |
| 2133    | 11        | 3.58%   |
| 5600    | 5         | 1.63%   |
| 6400    | 4         | 1.3%    |
| 1334    | 4         | 1.3%    |
| 1067    | 4         | 1.3%    |
| 800     | 4         | 1.3%    |
| 2666    | 2         | 0.65%   |
| 1867    | 2         | 0.65%   |
| 1066    | 2         | 0.65%   |
| 667     | 2         | 0.65%   |
| Unknown | 2         | 0.65%   |
| 65535   | 1         | 0.33%   |
| 5200    | 1         | 0.33%   |
| 4000    | 1         | 0.33%   |
| 3600    | 1         | 0.33%   |
| 3000    | 1         | 0.33%   |
| 2933    | 1         | 0.33%   |
| 1866    | 1         | 0.33%   |
| 1033    | 1         | 0.33%   |
| 933     | 1         | 0.33%   |
| 533     | 1         | 0.33%   |

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
| Chicony Electronics                    | 12        | 41.38%  |
| Microdia                               | 3         | 10.34%  |
| Bison Electronics                      | 3         | 10.34%  |
| Realtek Semiconductor                  | 2         | 6.9%    |
| Logitech                               | 2         | 6.9%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.9%    |
| Apple                                  | 2         | 6.9%    |
| Lite-On Technology                     | 1         | 3.45%   |
| Lenovo                                 | 1         | 3.45%   |
| IMC Networks                           | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony ThinkPad T490 Webcam                                | 3         | 10.34%  |
| Chicony integrated camera                                   | 3         | 10.34%  |
| Realtek USB 2.0 PC Camera                                   | 2         | 6.9%    |
| Chicony HP HD Camera                                        | 2         | 6.9%    |
| Apple FaceTime HD Camera                                    | 2         | 6.9%    |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 3.45%   |
| Microdia Integrated Webcam HD                               | 1         | 3.45%   |
| Microdia Integrated Webcam                                  | 1         | 3.45%   |
| Logitech Webcam C170                                        | 1         | 3.45%   |
| Logitech HD Pro Webcam C920                                 | 1         | 3.45%   |
| Lite-On HP HD Camera                                        | 1         | 3.45%   |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 3.45%   |
| IMC Networks Integrated Camera                              | 1         | 3.45%   |
| Chicony Integrated IR Camera                                | 1         | 3.45%   |
| Chicony Integrated HD WebCam                                | 1         | 3.45%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 3.45%   |
| Chicony HP Universal Camera                                 | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) Webcam               | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 3.45%   |
| Bison SunplusIT Integrated Camera                           | 1         | 3.45%   |
| Bison Lenovo EasyCamera                                     | 1         | 3.45%   |
| Bison Integrated Camera                                     | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 36.84%  |
| Upek                       | 4         | 21.05%  |
| Synaptics                  | 4         | 21.05%  |
| Shenzhen Goodix Technology | 2         | 10.53%  |
| STMicroelectronics         | 1         | 5.26%   |
| Elan Microelectronics      | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 4         | 21.05%  |
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 15.79%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 10.53%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 10.53%  |
| Shenzhen Goodix Fingerprint Reader                       | 2         | 10.53%  |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 5.26%   |
| Validity Sensors VFS491                                  | 1         | 5.26%   |
| STMicroelectronics Fingerprint Reader                    | 1         | 5.26%   |
| Elan Fingerprint Sensor                                  | 1         | 5.26%   |

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
| 1     | 139       | 40.41%  |
| 0     | 106       | 30.81%  |
| 2     | 57        | 16.57%  |
| 3     | 33        | 9.59%   |
| 4     | 7         | 2.03%   |
| 5     | 2         | 0.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 210       | 65.42%  |
| Bluetooth                | 31        | 9.66%   |
| Net/wireless             | 25        | 7.79%   |
| Fingerprint reader       | 19        | 5.92%   |
| Card reader              | 19        | 5.92%   |
| Firewire controller      | 5         | 1.56%   |
| Net/ethernet             | 4         | 1.25%   |
| Network                  | 3         | 0.93%   |
| Sound                    | 2         | 0.62%   |
| Graphics card            | 2         | 0.62%   |
| Storage/nvme             | 1         | 0.31%   |

