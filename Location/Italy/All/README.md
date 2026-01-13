BSD in Italy - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for BSD in Italy.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Italy/Desktop/README.md) and [notebooks](/Location/Italy/Notebook/README.md).

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

Total: 708

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [c14d381fb6](https://bsd-hardware.info/?probe=c14d381fb6) | Jan 02, 2026 |
| Unknown       | Unknown                     | Desktop     | [d1e02c8726](https://bsd-hardware.info/?probe=d1e02c8726) | Jan 01, 2026 |
| Unknown       | Unknown                     | Desktop     | [b01f762000](https://bsd-hardware.info/?probe=b01f762000) | Dec 31, 2025 |
| GEEKOM        | Mini IT13                   | Server      | [46ff41bff0](https://bsd-hardware.info/?probe=46ff41bff0) | Dec 30, 2025 |
| GEEKOM        | Mini IT13                   | Server      | [2d9e73adde](https://bsd-hardware.info/?probe=2d9e73adde) | Dec 30, 2025 |
| MSI           | Z77A-G43                    | Desktop     | [1d2c2d4b4e](https://bsd-hardware.info/?probe=1d2c2d4b4e) | Dec 28, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d80d321b9c](https://bsd-hardware.info/?probe=d80d321b9c) | Dec 28, 2025 |
| Intel         | NUC7i3BNHX                  | Mini pc     | [fe7562fd80](https://bsd-hardware.info/?probe=fe7562fd80) | Dec 27, 2025 |
| Unknown       | Unknown                     | Desktop     | [38f59185e0](https://bsd-hardware.info/?probe=38f59185e0) | Dec 27, 2025 |
| Unknown       | Unknown                     | Desktop     | [0021edd329](https://bsd-hardware.info/?probe=0021edd329) | Dec 24, 2025 |
| Unknown       | Unknown                     | Desktop     | [36273958a1](https://bsd-hardware.info/?probe=36273958a1) | Dec 21, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [ba9f5083a7](https://bsd-hardware.info/?probe=ba9f5083a7) | Dec 21, 2025 |
| Unknown       | Unknown                     | Desktop     | [cf2d44af5c](https://bsd-hardware.info/?probe=cf2d44af5c) | Dec 18, 2025 |
| Protectli     | VP6630                      | Desktop     | [f067712413](https://bsd-hardware.info/?probe=f067712413) | Dec 13, 2025 |
| Unknown       | Unknown                     | Desktop     | [aeef8c73de](https://bsd-hardware.info/?probe=aeef8c73de) | Dec 12, 2025 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [cdfec7a726](https://bsd-hardware.info/?probe=cdfec7a726) | Dec 12, 2025 |
| Lenovo        | ThinkPad T480s 20L8S2340... | Notebook    | [8b275be7b0](https://bsd-hardware.info/?probe=8b275be7b0) | Dec 10, 2025 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | Notebook    | [576e8fb25d](https://bsd-hardware.info/?probe=576e8fb25d) | Dec 08, 2025 |
| Shenzhen M... | AHWSA                       | Desktop     | [4240ba2e4c](https://bsd-hardware.info/?probe=4240ba2e4c) | Dec 05, 2025 |
| Shenzhen M... | AHWSA                       | Desktop     | [c12bbd3e82](https://bsd-hardware.info/?probe=c12bbd3e82) | Dec 03, 2025 |
| Unknown       | Unknown                     | Desktop     | [ba04fcb31b](https://bsd-hardware.info/?probe=ba04fcb31b) | Nov 28, 2025 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [724aa072b9](https://bsd-hardware.info/?probe=724aa072b9) | Nov 26, 2025 |
| Shenzhen M... | AHWSA                       | Desktop     | [150845c9eb](https://bsd-hardware.info/?probe=150845c9eb) | Nov 26, 2025 |
| Dell          | 0RW203                      | Desktop     | [f641a90c54](https://bsd-hardware.info/?probe=f641a90c54) | Nov 26, 2025 |
| Lenovo        | ThinkPad T480s 20L8S2340... | Notebook    | [97c632ed57](https://bsd-hardware.info/?probe=97c632ed57) | Nov 25, 2025 |
| Unknown       | Unknown                     | Desktop     | [6193d555ed](https://bsd-hardware.info/?probe=6193d555ed) | Nov 24, 2025 |
| HP            | 83E2                        | Desktop     | [ed9ad7be47](https://bsd-hardware.info/?probe=ed9ad7be47) | Nov 18, 2025 |
| Lenovo        | ThinkPad T480s 20L8S2340... | Notebook    | [1618017f79](https://bsd-hardware.info/?probe=1618017f79) | Nov 17, 2025 |
| Apple         | MacBookPro6,2               | Notebook    | [70a14286fc](https://bsd-hardware.info/?probe=70a14286fc) | Nov 08, 2025 |
| Unknown       | Unknown                     | Desktop     | [4bed31a02e](https://bsd-hardware.info/?probe=4bed31a02e) | Nov 08, 2025 |
| Unknown       | Unknown                     | Desktop     | [b1ad0a1f46](https://bsd-hardware.info/?probe=b1ad0a1f46) | Nov 08, 2025 |
| Unknown       | Unknown                     | Desktop     | [f94ceec067](https://bsd-hardware.info/?probe=f94ceec067) | Nov 07, 2025 |
| Lenovo        | ThinkPad X220 4291ZFR       | Notebook    | [c7e13a8f2d](https://bsd-hardware.info/?probe=c7e13a8f2d) | Oct 31, 2025 |
| ASUSTek       | K53SJ                       | Notebook    | [092f586122](https://bsd-hardware.info/?probe=092f586122) | Oct 28, 2025 |
| ASUSTek       | K52JB                       | Notebook    | [831c17b144](https://bsd-hardware.info/?probe=831c17b144) | Oct 28, 2025 |
| Supermicro    | X11SDV-8C-TP8F              | Server      | [dfe355e06f](https://bsd-hardware.info/?probe=dfe355e06f) | Oct 15, 2025 |
| Supermicro    | X11SDV-8C-TP8F              | Server      | [412d35e387](https://bsd-hardware.info/?probe=412d35e387) | Oct 15, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [8921028708](https://bsd-hardware.info/?probe=8921028708) | Sep 27, 2025 |
| Unknown       | Unknown                     | Desktop     | [03ab11d815](https://bsd-hardware.info/?probe=03ab11d815) | Sep 26, 2025 |
| HP            | 8062                        | Desktop     | [ae1ae3a406](https://bsd-hardware.info/?probe=ae1ae3a406) | Sep 25, 2025 |
| MSI           | H170M PRO-DH                | Desktop     | [4a04153296](https://bsd-hardware.info/?probe=4a04153296) | Sep 23, 2025 |
| Dell EMC      | EDGE640VN-CPU A00           | Desktop     | [150bbf9587](https://bsd-hardware.info/?probe=150bbf9587) | Sep 19, 2025 |
| Dell EMC      | EDGE640VN-CPU A00           | Desktop     | [dd4c64a2dc](https://bsd-hardware.info/?probe=dd4c64a2dc) | Sep 12, 2025 |
| Shenzhen M... | AHWSA                       | Desktop     | [f5b19faa2c](https://bsd-hardware.info/?probe=f5b19faa2c) | Sep 08, 2025 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [707d6b12a2](https://bsd-hardware.info/?probe=707d6b12a2) | Sep 07, 2025 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [2e9c36debb](https://bsd-hardware.info/?probe=2e9c36debb) | Aug 31, 2025 |
| HP            | 18E9                        | Desktop     | [a28ae7a998](https://bsd-hardware.info/?probe=a28ae7a998) | Aug 19, 2025 |
| Unknown       | Unknown                     | Desktop     | [a14d958133](https://bsd-hardware.info/?probe=a14d958133) | Aug 16, 2025 |
| Unknown       | Unknown                     | Desktop     | [4f1cc80df8](https://bsd-hardware.info/?probe=4f1cc80df8) | Aug 07, 2025 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [6f524bddcc](https://bsd-hardware.info/?probe=6f524bddcc) | Jul 30, 2025 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b5fd89caa2](https://bsd-hardware.info/?probe=b5fd89caa2) | Jul 29, 2025 |
| Unknown       | Unknown                     | Desktop     | [8600606d50](https://bsd-hardware.info/?probe=8600606d50) | Jul 24, 2025 |
| Shenzhen M... | AHWSA                       | Desktop     | [fdc2bc916f](https://bsd-hardware.info/?probe=fdc2bc916f) | Jul 23, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [836b17ca7e](https://bsd-hardware.info/?probe=836b17ca7e) | Jul 19, 2025 |
| Unknown       | Unknown                     | Desktop     | [452524a101](https://bsd-hardware.info/?probe=452524a101) | Jul 14, 2025 |
| Unknown       | Unknown                     | Desktop     | [5f397f2ca0](https://bsd-hardware.info/?probe=5f397f2ca0) | Jul 14, 2025 |
| Unknown       | Unknown                     | Desktop     | [c4ea0e3429](https://bsd-hardware.info/?probe=c4ea0e3429) | Jul 11, 2025 |
| ASUSTek       | NUC12WSK-B                  | Desktop     | [ba6cf411aa](https://bsd-hardware.info/?probe=ba6cf411aa) | Jul 11, 2025 |
| Intel(R) C... | NUC12WSKi7                  | Mini pc     | [d493c3c79f](https://bsd-hardware.info/?probe=d493c3c79f) | Jul 11, 2025 |
| SLIMBOOK      | ZERO-N100-4RJ               | Desktop     | [dc2404f78c](https://bsd-hardware.info/?probe=dc2404f78c) | Jul 09, 2025 |
| Unknown       | Unknown                     | Desktop     | [25aa244d08](https://bsd-hardware.info/?probe=25aa244d08) | Jul 07, 2025 |
| ASUSTek       | P12R-M Series 60SB0AU0-S... | Server      | [188dd6ec41](https://bsd-hardware.info/?probe=188dd6ec41) | Jul 07, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [5a6158da81](https://bsd-hardware.info/?probe=5a6158da81) | Jul 05, 2025 |
| BESSTAR Te... | GB1B                        | Mini pc     | [215109c02f](https://bsd-hardware.info/?probe=215109c02f) | Jun 23, 2025 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [195b1c4b3d](https://bsd-hardware.info/?probe=195b1c4b3d) | Jun 18, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [f6a757b3c9](https://bsd-hardware.info/?probe=f6a757b3c9) | Jun 18, 2025 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [898be8e5a3](https://bsd-hardware.info/?probe=898be8e5a3) | Jun 16, 2025 |
| Lenovo        | ThinkCentre M90P 5852W3Z    | Desktop     | [1d5a2636c1](https://bsd-hardware.info/?probe=1d5a2636c1) | Jun 10, 2025 |
| HP            | 8597                        | Desktop     | [87b77cb314](https://bsd-hardware.info/?probe=87b77cb314) | Jun 09, 2025 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [ebaaa9be17](https://bsd-hardware.info/?probe=ebaaa9be17) | Jun 06, 2025 |
| ASUSTek       | K53SJ                       | Notebook    | [7105ddca26](https://bsd-hardware.info/?probe=7105ddca26) | May 31, 2025 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [c5dd1d6d14](https://bsd-hardware.info/?probe=c5dd1d6d14) | May 26, 2025 |
| Dell EMC      | EDGE640VN-CPU A00           | Desktop     | [8b320aa03c](https://bsd-hardware.info/?probe=8b320aa03c) | May 23, 2025 |
| Unknown       | Unknown                     | Desktop     | [5c60338974](https://bsd-hardware.info/?probe=5c60338974) | May 22, 2025 |
| Unknown       | Unknown                     | Desktop     | [edebd0c073](https://bsd-hardware.info/?probe=edebd0c073) | May 22, 2025 |
| Deciso        | NetBoard-A10_Gen.3          | Notebook    | [47d8451b23](https://bsd-hardware.info/?probe=47d8451b23) | May 21, 2025 |
| HP            | ProLiant DL180 G6           | Server      | [d16b64ff46](https://bsd-hardware.info/?probe=d16b64ff46) | May 20, 2025 |
| Unknown       | Unknown                     | Desktop     | [d0f18c6ef4](https://bsd-hardware.info/?probe=d0f18c6ef4) | May 20, 2025 |
| Unknown       | Unknown                     | Desktop     | [a476fe916e](https://bsd-hardware.info/?probe=a476fe916e) | May 19, 2025 |
| Deciso        | NetBoard-A10_Gen.3          | Notebook    | [5189ae5b2c](https://bsd-hardware.info/?probe=5189ae5b2c) | May 08, 2025 |
| ASUSTek       | K53SJ                       | Notebook    | [4fc246d3b4](https://bsd-hardware.info/?probe=4fc246d3b4) | May 01, 2025 |
| Unknown       | Unknown                     | Desktop     | [40db23a4d2](https://bsd-hardware.info/?probe=40db23a4d2) | Apr 30, 2025 |
| HP            | ProLiant DL380 G4           | Server      | [41de138f36](https://bsd-hardware.info/?probe=41de138f36) | Apr 29, 2025 |
| Unknown       | Unknown                     | Desktop     | [79834121ab](https://bsd-hardware.info/?probe=79834121ab) | Apr 28, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [52162cb731](https://bsd-hardware.info/?probe=52162cb731) | Apr 23, 2025 |
| Unknown       | Unknown                     | Desktop     | [aacce335c3](https://bsd-hardware.info/?probe=aacce335c3) | Apr 22, 2025 |
| Unknown       | Unknown                     | Desktop     | [8f37744635](https://bsd-hardware.info/?probe=8f37744635) | Apr 22, 2025 |
| Unknown       | Unknown                     | Desktop     | [054e36f578](https://bsd-hardware.info/?probe=054e36f578) | Apr 22, 2025 |
| LG Electro... | 16Z90P-G.AP75D              | Notebook    | [c855a0ced2](https://bsd-hardware.info/?probe=c855a0ced2) | Apr 22, 2025 |
| Protectli     | V1410                       | Desktop     | [fa9d928df3](https://bsd-hardware.info/?probe=fa9d928df3) | Apr 18, 2025 |
| ASUSTek       | K53SJ                       | Notebook    | [3a312f438d](https://bsd-hardware.info/?probe=3a312f438d) | Apr 18, 2025 |
| ASUSTek       | K53SJ                       | Notebook    | [1e240331e0](https://bsd-hardware.info/?probe=1e240331e0) | Apr 18, 2025 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [c13fa53421](https://bsd-hardware.info/?probe=c13fa53421) | Apr 15, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [81c04ee408](https://bsd-hardware.info/?probe=81c04ee408) | Apr 15, 2025 |
| HP            | 8062                        | Desktop     | [ab4217bf1e](https://bsd-hardware.info/?probe=ab4217bf1e) | Apr 14, 2025 |
| Protectli     | V1410                       | Desktop     | [b0b3d1e253](https://bsd-hardware.info/?probe=b0b3d1e253) | Apr 06, 2025 |
| ASUSTek       | P13R-M Series               | Desktop     | [85d1427084](https://bsd-hardware.info/?probe=85d1427084) | Apr 03, 2025 |
| ASUSTek       | PRIME A620M-A               | Desktop     | [cfaef0f33c](https://bsd-hardware.info/?probe=cfaef0f33c) | Mar 28, 2025 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [38343a4b77](https://bsd-hardware.info/?probe=38343a4b77) | Mar 27, 2025 |
| Shenzhen M... | AHWSA                       | Desktop     | [02687add35](https://bsd-hardware.info/?probe=02687add35) | Mar 27, 2025 |
| Protectli     | FW6 Ver                     | Desktop     | [4e80f45d8e](https://bsd-hardware.info/?probe=4e80f45d8e) | Mar 26, 2025 |
| Unknown       | Unknown                     | Desktop     | [43978f0ebb](https://bsd-hardware.info/?probe=43978f0ebb) | Mar 25, 2025 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [21c9ed292b](https://bsd-hardware.info/?probe=21c9ed292b) | Mar 25, 2025 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [051eaee678](https://bsd-hardware.info/?probe=051eaee678) | Mar 24, 2025 |
| Protectli     | VP2420                      | Desktop     | [d32b5f5149](https://bsd-hardware.info/?probe=d32b5f5149) | Mar 23, 2025 |
| Intel         | DENLOW_WS                   | Desktop     | [ef36020a56](https://bsd-hardware.info/?probe=ef36020a56) | Mar 22, 2025 |
| HP            | 8597                        | Desktop     | [fd288dc789](https://bsd-hardware.info/?probe=fd288dc789) | Mar 20, 2025 |
| BESSTAR Te... | GB7                         | Mini pc     | [894ac6fead](https://bsd-hardware.info/?probe=894ac6fead) | Mar 18, 2025 |
| ASUSTek       | PN42                        | Mini pc     | [b378117374](https://bsd-hardware.info/?probe=b378117374) | Mar 18, 2025 |
| Unknown       | Unknown                     | Desktop     | [92d332ce44](https://bsd-hardware.info/?probe=92d332ce44) | Mar 18, 2025 |
| Unknown       | Unknown                     | Desktop     | [7b4ec3b12f](https://bsd-hardware.info/?probe=7b4ec3b12f) | Mar 16, 2025 |
| Sophos        | XG                          | Firewall    | [50e7cfb2c2](https://bsd-hardware.info/?probe=50e7cfb2c2) | Mar 14, 2025 |
| HP            | ProLiant MicroServer        | Desktop     | [076a90265c](https://bsd-hardware.info/?probe=076a90265c) | Mar 12, 2025 |
| Unknown       | Unknown                     | Desktop     | [15fbd064b1](https://bsd-hardware.info/?probe=15fbd064b1) | Mar 11, 2025 |
| HP            | ProLiant MicroServer        | Desktop     | [13fad386ab](https://bsd-hardware.info/?probe=13fad386ab) | Mar 11, 2025 |
| Apple         | MacBook5,1                  | Notebook    | [8c618c0e44](https://bsd-hardware.info/?probe=8c618c0e44) | Mar 09, 2025 |
| SJRC          | ADLN-6L                     | Desktop     | [ce880e20dc](https://bsd-hardware.info/?probe=ce880e20dc) | Mar 09, 2025 |
| Unknown       | Unknown                     | Desktop     | [2a4269b2b1](https://bsd-hardware.info/?probe=2a4269b2b1) | Mar 08, 2025 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [41f8aea871](https://bsd-hardware.info/?probe=41f8aea871) | Mar 07, 2025 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [9d63ab90bc](https://bsd-hardware.info/?probe=9d63ab90bc) | Mar 07, 2025 |
| ASUSTek       | PN42                        | Mini pc     | [5c0e47be05](https://bsd-hardware.info/?probe=5c0e47be05) | Mar 07, 2025 |
| ASUSTek       | K55VD                       | Notebook    | [4672d15867](https://bsd-hardware.info/?probe=4672d15867) | Mar 04, 2025 |
| ASUSTek       | B85M-G                      | Desktop     | [d374326c41](https://bsd-hardware.info/?probe=d374326c41) | Mar 04, 2025 |
| ASUSTek       | K55VD                       | Notebook    | [7eac5f9cf2](https://bsd-hardware.info/?probe=7eac5f9cf2) | Mar 02, 2025 |
| Protectli     | VP2420                      | Desktop     | [44698fb9c6](https://bsd-hardware.info/?probe=44698fb9c6) | Feb 28, 2025 |
| Lenovo        | 3141 SDK0J40697 WIN 3305... | Desktop     | [1534f06286](https://bsd-hardware.info/?probe=1534f06286) | Feb 28, 2025 |
| SJRC          | ADLN-6L                     | Desktop     | [d2219e106a](https://bsd-hardware.info/?probe=d2219e106a) | Feb 24, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [88aaf66f95](https://bsd-hardware.info/?probe=88aaf66f95) | Feb 24, 2025 |
| HP            | 8597                        | Desktop     | [4c57c3f8aa](https://bsd-hardware.info/?probe=4c57c3f8aa) | Feb 22, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [572b0a788f](https://bsd-hardware.info/?probe=572b0a788f) | Feb 20, 2025 |
| Unknown       | Unknown                     | Desktop     | [1e6f77842a](https://bsd-hardware.info/?probe=1e6f77842a) | Feb 19, 2025 |
| Supermicro    | X10SDV-TP8F                 | Server      | [8dfb0bddda](https://bsd-hardware.info/?probe=8dfb0bddda) | Feb 18, 2025 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b9aa6b21b0](https://bsd-hardware.info/?probe=b9aa6b21b0) | Feb 17, 2025 |
| Unknown       | Unknown                     | Desktop     | [4ea07ef557](https://bsd-hardware.info/?probe=4ea07ef557) | Feb 17, 2025 |
| Dell          | 0F0XJ6 A00                  | Server      | [842169bbf9](https://bsd-hardware.info/?probe=842169bbf9) | Feb 16, 2025 |
| Dell          | 0F0XJ6 A00                  | Server      | [3cef973762](https://bsd-hardware.info/?probe=3cef973762) | Feb 16, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [10970503a3](https://bsd-hardware.info/?probe=10970503a3) | Feb 16, 2025 |
| Protectli     | VP2420                      | Desktop     | [8a5fa7a583](https://bsd-hardware.info/?probe=8a5fa7a583) | Feb 15, 2025 |
| Unknown       | Unknown                     | Desktop     | [e322d6037a](https://bsd-hardware.info/?probe=e322d6037a) | Feb 15, 2025 |
| Intel         | CARLOW                      | Desktop     | [a1ba1acb8d](https://bsd-hardware.info/?probe=a1ba1acb8d) | Feb 12, 2025 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [a9024da72c](https://bsd-hardware.info/?probe=a9024da72c) | Feb 08, 2025 |
| Unknown       | Unknown                     | Desktop     | [95ecb6a312](https://bsd-hardware.info/?probe=95ecb6a312) | Feb 07, 2025 |
| NF692         | 1.0                         | Desktop     | [a8be44f5d5](https://bsd-hardware.info/?probe=a8be44f5d5) | Feb 07, 2025 |
| Unknown       | Unknown                     | Desktop     | [a04c952ea4](https://bsd-hardware.info/?probe=a04c952ea4) | Feb 02, 2025 |
| Unknown       | Unknown                     | Desktop     | [ddb2939d37](https://bsd-hardware.info/?probe=ddb2939d37) | Jan 31, 2025 |
| Protectli     | V1410                       | Desktop     | [5551ff6b2c](https://bsd-hardware.info/?probe=5551ff6b2c) | Jan 27, 2025 |
| HP            | 8597                        | Desktop     | [686e686b76](https://bsd-hardware.info/?probe=686e686b76) | Jan 25, 2025 |
| ASUSTek       | K31CD-K                     | Desktop     | [a473dadfcd](https://bsd-hardware.info/?probe=a473dadfcd) | Jan 20, 2025 |
| Unknown       | Unknown                     | Desktop     | [0ebb71103b](https://bsd-hardware.info/?probe=0ebb71103b) | Jan 20, 2025 |
| PICO PC       | JSL-4L                      | Desktop     | [19e8df6a4f](https://bsd-hardware.info/?probe=19e8df6a4f) | Jan 17, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [39818955e2](https://bsd-hardware.info/?probe=39818955e2) | Jan 17, 2025 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [b1e011d2f4](https://bsd-hardware.info/?probe=b1e011d2f4) | Jan 15, 2025 |
| Unknown       | Unknown                     | Desktop     | [53eed46736](https://bsd-hardware.info/?probe=53eed46736) | Jan 12, 2025 |
| Intel         | JSL MRD                     | Desktop     | [445b14eb63](https://bsd-hardware.info/?probe=445b14eb63) | Jan 12, 2025 |
| Dell          | 0MGK50 A02                  | Desktop     | [fe0b9484f5](https://bsd-hardware.info/?probe=fe0b9484f5) | Jan 05, 2025 |
| HP            | 18E7                        | Desktop     | [fdac2d0362](https://bsd-hardware.info/?probe=fdac2d0362) | Jan 03, 2025 |
| Dell          | Latitude E7250              | Notebook    | [dbff7c2ebb](https://bsd-hardware.info/?probe=dbff7c2ebb) | Jan 02, 2025 |
| SJRC          | ADLN-6L                     | Desktop     | [90498561c8](https://bsd-hardware.info/?probe=90498561c8) | Jan 02, 2025 |
| Lenovo        | ThinkPad X270 20HN0015MX    | Notebook    | [66b1686a32](https://bsd-hardware.info/?probe=66b1686a32) | Dec 25, 2024 |
| NF692         | 1.0                         | Desktop     | [b129c164c5](https://bsd-hardware.info/?probe=b129c164c5) | Dec 24, 2024 |
| Protectli     | VP2420                      | Desktop     | [6fe419fedc](https://bsd-hardware.info/?probe=6fe419fedc) | Dec 24, 2024 |
| SHENZHEN Y... | M1                          | Mini pc     | [d2695d230e](https://bsd-hardware.info/?probe=d2695d230e) | Dec 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [94d37d7a1e](https://bsd-hardware.info/?probe=94d37d7a1e) | Dec 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [806188d557](https://bsd-hardware.info/?probe=806188d557) | Dec 13, 2024 |
| Intel         | X79_PLUS                    | Desktop     | [0382eb3cd4](https://bsd-hardware.info/?probe=0382eb3cd4) | Dec 10, 2024 |
| Huanan        | X58-RX3.0 V110              | Desktop     | [7aa0eb6533](https://bsd-hardware.info/?probe=7aa0eb6533) | Dec 07, 2024 |
| ASUSTek       | N550JV                      | Notebook    | [43db70e6e9](https://bsd-hardware.info/?probe=43db70e6e9) | Dec 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [5c01d44547](https://bsd-hardware.info/?probe=5c01d44547) | Dec 07, 2024 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [827453a946](https://bsd-hardware.info/?probe=827453a946) | Dec 06, 2024 |
| Supermicro    | X10SDV-F                    | Server      | [d08d4af555](https://bsd-hardware.info/?probe=d08d4af555) | Dec 01, 2024 |
| HP            | 0A64h                       | Desktop     | [4d668a54a4](https://bsd-hardware.info/?probe=4d668a54a4) | Dec 01, 2024 |
| Intel         | B75 V1.5                    | Desktop     | [a579cb0709](https://bsd-hardware.info/?probe=a579cb0709) | Nov 29, 2024 |
| HP            | ProLiant DL180 G6           | Server      | [f13e4185c7](https://bsd-hardware.info/?probe=f13e4185c7) | Nov 27, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [90f5e4c5de](https://bsd-hardware.info/?probe=90f5e4c5de) | Nov 23, 2024 |
| HP            | 802F                        | Desktop     | [7685aa4970](https://bsd-hardware.info/?probe=7685aa4970) | Nov 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [0d7c205328](https://bsd-hardware.info/?probe=0d7c205328) | Nov 20, 2024 |
| HP            | 0A64h                       | Desktop     | [132bd7b8cc](https://bsd-hardware.info/?probe=132bd7b8cc) | Nov 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [a656bb922f](https://bsd-hardware.info/?probe=a656bb922f) | Nov 12, 2024 |
| ASRock        | X570 PG Velocita            | Desktop     | [2a30e356a7](https://bsd-hardware.info/?probe=2a30e356a7) | Nov 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [d205d862c1](https://bsd-hardware.info/?probe=d205d862c1) | Nov 01, 2024 |
| HP            | 8062                        | Desktop     | [3a8dfb73b6](https://bsd-hardware.info/?probe=3a8dfb73b6) | Oct 31, 2024 |
| Quantum en... | HackBoard 2                 | Desktop     | [77f7cc8b05](https://bsd-hardware.info/?probe=77f7cc8b05) | Oct 27, 2024 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [0c7e857ac8](https://bsd-hardware.info/?probe=0c7e857ac8) | Oct 27, 2024 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [35c1fa9e04](https://bsd-hardware.info/?probe=35c1fa9e04) | Oct 26, 2024 |
| Gigabyte      | A620M H                     | Desktop     | [c1e5a0fe6f](https://bsd-hardware.info/?probe=c1e5a0fe6f) | Oct 22, 2024 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [96bf4191cc](https://bsd-hardware.info/?probe=96bf4191cc) | Oct 17, 2024 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [af0a059e28](https://bsd-hardware.info/?probe=af0a059e28) | Oct 16, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [6d6ba6974b](https://bsd-hardware.info/?probe=6d6ba6974b) | Oct 12, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [549e8b3887](https://bsd-hardware.info/?probe=549e8b3887) | Oct 12, 2024 |
| Dell          | 0TY179 A05                  | Server      | [0bfcb0cf45](https://bsd-hardware.info/?probe=0bfcb0cf45) | Oct 09, 2024 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [87cd1c965c](https://bsd-hardware.info/?probe=87cd1c965c) | Oct 07, 2024 |
| MSI           | MS-7D16                     | Desktop     | [e9bddb011d](https://bsd-hardware.info/?probe=e9bddb011d) | Oct 01, 2024 |
| Dell          | Latitude E7250              | Notebook    | [025ea9ef12](https://bsd-hardware.info/?probe=025ea9ef12) | Sep 30, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [3a5bb1ef92](https://bsd-hardware.info/?probe=3a5bb1ef92) | Sep 28, 2024 |
| Dell          | Latitude E7250              | Notebook    | [2dfb20ed35](https://bsd-hardware.info/?probe=2dfb20ed35) | Sep 27, 2024 |
| MACHINIST     | X99-MR9A PRO MAX V1.2       | Desktop     | [71545c2b0e](https://bsd-hardware.info/?probe=71545c2b0e) | Sep 24, 2024 |
| HP            | 213D A01                    | Desktop     | [edc8edec39](https://bsd-hardware.info/?probe=edc8edec39) | Sep 22, 2024 |
| MSI           | MS-B1061                    | All in one  | [0c456f4cd7](https://bsd-hardware.info/?probe=0c456f4cd7) | Sep 13, 2024 |
| HP            | Mini 210-1000               | Notebook    | [5271409065](https://bsd-hardware.info/?probe=5271409065) | Sep 11, 2024 |
| HPE           | ProLiant DL380 Gen10        | Server      | [a7e1d263f1](https://bsd-hardware.info/?probe=a7e1d263f1) | Sep 06, 2024 |
| Pegatron      | 2ACF                        | Desktop     | [eeb702f96d](https://bsd-hardware.info/?probe=eeb702f96d) | Aug 29, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [e014463bd0](https://bsd-hardware.info/?probe=e014463bd0) | Aug 28, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [308b201c35](https://bsd-hardware.info/?probe=308b201c35) | Aug 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [2e271c0d9e](https://bsd-hardware.info/?probe=2e271c0d9e) | Aug 19, 2024 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [942d148e6e](https://bsd-hardware.info/?probe=942d148e6e) | Aug 17, 2024 |
| ASUSTek       | 1215N                       | Notebook    | [0970f34b42](https://bsd-hardware.info/?probe=0970f34b42) | Aug 15, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [24dc7d5ecf](https://bsd-hardware.info/?probe=24dc7d5ecf) | Aug 07, 2024 |
| MW            | GMLK-2_5G4L                 | Desktop     | [c78e39d7b2](https://bsd-hardware.info/?probe=c78e39d7b2) | Aug 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [059091972d](https://bsd-hardware.info/?probe=059091972d) | Jul 31, 2024 |
| iEi           | B508 V1.00                  | Desktop     | [5286578613](https://bsd-hardware.info/?probe=5286578613) | Jul 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [0c003d992b](https://bsd-hardware.info/?probe=0c003d992b) | Jul 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [52ce09a582](https://bsd-hardware.info/?probe=52ce09a582) | Jul 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [c33fd5610f](https://bsd-hardware.info/?probe=c33fd5610f) | Jul 23, 2024 |
| Protectli     | V1210                       | Desktop     | [f22c04d928](https://bsd-hardware.info/?probe=f22c04d928) | Jul 14, 2024 |
| Protectli     | VP2420                      | Desktop     | [5dab536cca](https://bsd-hardware.info/?probe=5dab536cca) | Jul 05, 2024 |
| Intel(R) C... | NUC13ANKi5                  | Mini pc     | [17f7122809](https://bsd-hardware.info/?probe=17f7122809) | Jul 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [5766ba4f99](https://bsd-hardware.info/?probe=5766ba4f99) | Jun 28, 2024 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [52b02922bc](https://bsd-hardware.info/?probe=52b02922bc) | Jun 27, 2024 |
| ASRock        | X300M-STX                   | Desktop     | [2c4cc4c744](https://bsd-hardware.info/?probe=2c4cc4c744) | Jun 26, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [ddb6ff92c1](https://bsd-hardware.info/?probe=ddb6ff92c1) | Jun 26, 2024 |
| Unknown       | YL-SKUL6                    | Desktop     | [e6e7050b09](https://bsd-hardware.info/?probe=e6e7050b09) | Jun 25, 2024 |
| Supermicro    | X10SDV-F                    | Server      | [df7e8fd69c](https://bsd-hardware.info/?probe=df7e8fd69c) | Jun 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [14bd339dfc](https://bsd-hardware.info/?probe=14bd339dfc) | Jun 18, 2024 |
| AWOW          | AK34Pro                     | Mini pc     | [96cdef5a25](https://bsd-hardware.info/?probe=96cdef5a25) | Jun 17, 2024 |
| Lenovo        | NOK                         | Desktop     | [9ae535f558](https://bsd-hardware.info/?probe=9ae535f558) | Jun 11, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [8f7f98fc18](https://bsd-hardware.info/?probe=8f7f98fc18) | Jun 07, 2024 |
| AZW           | EQ                          | Desktop     | [4b940b4e22](https://bsd-hardware.info/?probe=4b940b4e22) | Jun 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [6e4e779799](https://bsd-hardware.info/?probe=6e4e779799) | Jun 05, 2024 |
| ASUSTek       | X555UJ                      | Notebook    | [df9f681ce9](https://bsd-hardware.info/?probe=df9f681ce9) | Jun 05, 2024 |
| ASRock        | J5040-ITX                   | Desktop     | [dfb7f31242](https://bsd-hardware.info/?probe=dfb7f31242) | Jun 02, 2024 |
| Dell          | Latitude E7250              | Notebook    | [b5504e5573](https://bsd-hardware.info/?probe=b5504e5573) | Jun 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [002ead7053](https://bsd-hardware.info/?probe=002ead7053) | May 24, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [169fdec0c9](https://bsd-hardware.info/?probe=169fdec0c9) | May 22, 2024 |
| MW            | GMLK-2_5G4L                 | Desktop     | [0ba0e09a89](https://bsd-hardware.info/?probe=0ba0e09a89) | May 20, 2024 |
| ASUSTek       | X555LAB                     | Notebook    | [e39c22cfc5](https://bsd-hardware.info/?probe=e39c22cfc5) | May 18, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [121c0144ee](https://bsd-hardware.info/?probe=121c0144ee) | May 16, 2024 |
| Dell          | 0F0XJ6 A00                  | Server      | [c049ffad9d](https://bsd-hardware.info/?probe=c049ffad9d) | May 06, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [2656d00123](https://bsd-hardware.info/?probe=2656d00123) | May 03, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [3e01e5ffbf](https://bsd-hardware.info/?probe=3e01e5ffbf) | May 03, 2024 |
| Quantum en... | HackBoard 2                 | Desktop     | [a7b0ea1eca](https://bsd-hardware.info/?probe=a7b0ea1eca) | Apr 28, 2024 |
| Dell          | 096JG8 A01                  | Desktop     | [a696ddada6](https://bsd-hardware.info/?probe=a696ddada6) | Apr 20, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [67e558c746](https://bsd-hardware.info/?probe=67e558c746) | Apr 16, 2024 |
| PC Engines    | apu1                        | Desktop     | [cceec3e9bd](https://bsd-hardware.info/?probe=cceec3e9bd) | Apr 14, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [962837890c](https://bsd-hardware.info/?probe=962837890c) | Apr 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [a9c935db85](https://bsd-hardware.info/?probe=a9c935db85) | Apr 09, 2024 |
| Intel         | NUC7i3BNHX                  | Mini pc     | [be1566e796](https://bsd-hardware.info/?probe=be1566e796) | Apr 07, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [426677818b](https://bsd-hardware.info/?probe=426677818b) | Apr 07, 2024 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [574ff40323](https://bsd-hardware.info/?probe=574ff40323) | Apr 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [1af73d4146](https://bsd-hardware.info/?probe=1af73d4146) | Apr 04, 2024 |
| HPE           | ProLiant DL380 Gen10        | Server      | [d566684a72](https://bsd-hardware.info/?probe=d566684a72) | Apr 02, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [b6dc892e24](https://bsd-hardware.info/?probe=b6dc892e24) | Mar 31, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [4a80e4b570](https://bsd-hardware.info/?probe=4a80e4b570) | Mar 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [b9c567bdde](https://bsd-hardware.info/?probe=b9c567bdde) | Mar 21, 2024 |
| HP            | 2B5E                        | Desktop     | [35b1572267](https://bsd-hardware.info/?probe=35b1572267) | Mar 17, 2024 |
| PC Engines    | APU2                        | Desktop     | [9cd0068a06](https://bsd-hardware.info/?probe=9cd0068a06) | Mar 13, 2024 |
| PC Engines    | APU2                        | Desktop     | [891b69ea9c](https://bsd-hardware.info/?probe=891b69ea9c) | Mar 13, 2024 |
| BESSTAR Te... | VB9                         | All in one  | [0fdf31a212](https://bsd-hardware.info/?probe=0fdf31a212) | Feb 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [7f49c436eb](https://bsd-hardware.info/?probe=7f49c436eb) | Feb 27, 2024 |
| PC Engines    | APU2                        | Desktop     | [bd47726af7](https://bsd-hardware.info/?probe=bd47726af7) | Feb 25, 2024 |
| Intel(R) C... | NUC10i3FNH                  | Mini pc     | [924461c416](https://bsd-hardware.info/?probe=924461c416) | Feb 22, 2024 |
| Intel         | NUC7i3BNHX                  | Mini pc     | [cf452e34d1](https://bsd-hardware.info/?probe=cf452e34d1) | Feb 20, 2024 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [8f0a5d2d0a](https://bsd-hardware.info/?probe=8f0a5d2d0a) | Feb 16, 2024 |
| PC Engines    | APU2                        | Desktop     | [df18317865](https://bsd-hardware.info/?probe=df18317865) | Feb 14, 2024 |
| PC Engines    | APU2                        | Desktop     | [251265d29e](https://bsd-hardware.info/?probe=251265d29e) | Feb 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [19e59c140c](https://bsd-hardware.info/?probe=19e59c140c) | Feb 09, 2024 |
| HP            | ProLiant DL380 G4           | Server      | [1d58307095](https://bsd-hardware.info/?probe=1d58307095) | Feb 09, 2024 |
| PC Engines    | APU2                        | Desktop     | [6d52e4dad5](https://bsd-hardware.info/?probe=6d52e4dad5) | Feb 07, 2024 |
| ASUSTek       | K52F                        | Notebook    | [bc31c4707c](https://bsd-hardware.info/?probe=bc31c4707c) | Feb 04, 2024 |
| ASUSTek       | K52F                        | Notebook    | [9022031518](https://bsd-hardware.info/?probe=9022031518) | Feb 03, 2024 |
| PC Engines    | APU2                        | Desktop     | [591ead54fc](https://bsd-hardware.info/?probe=591ead54fc) | Jan 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [f2406d4352](https://bsd-hardware.info/?probe=f2406d4352) | Jan 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [4ff002fe77](https://bsd-hardware.info/?probe=4ff002fe77) | Jan 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [de7d99595c](https://bsd-hardware.info/?probe=de7d99595c) | Jan 23, 2024 |
| ASUSTek       | X555LAB                     | Notebook    | [c396fcc8d9](https://bsd-hardware.info/?probe=c396fcc8d9) | Jan 22, 2024 |
| HP            | 1494                        | Desktop     | [45c45d492a](https://bsd-hardware.info/?probe=45c45d492a) | Jan 18, 2024 |
| HP            | Mini 210-1000               | Notebook    | [f25c646418](https://bsd-hardware.info/?probe=f25c646418) | Jan 16, 2024 |
| HP            | Mini 210-1000               | Notebook    | [fb086c3baa](https://bsd-hardware.info/?probe=fb086c3baa) | Jan 15, 2024 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [e0d9f347e9](https://bsd-hardware.info/?probe=e0d9f347e9) | Jan 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [df4f6b185b](https://bsd-hardware.info/?probe=df4f6b185b) | Jan 09, 2024 |
| PC Engines    | APU2                        | Desktop     | [b08ca32731](https://bsd-hardware.info/?probe=b08ca32731) | Jan 07, 2024 |
| Samsung       | R510/P510                   | Notebook    | [920e7e2d14](https://bsd-hardware.info/?probe=920e7e2d14) | Dec 31, 2023 |
| Fujitsu       | D3090-A1 S26361-D3090-A1    | Server      | [1952b64d3d](https://bsd-hardware.info/?probe=1952b64d3d) | Dec 28, 2023 |
| Protectli     | VP2420                      | Desktop     | [5368ee9cc8](https://bsd-hardware.info/?probe=5368ee9cc8) | Dec 24, 2023 |
| TULPAR        | A5 V20.3                    | Notebook    | [89b65e7036](https://bsd-hardware.info/?probe=89b65e7036) | Dec 23, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [2556fa3be1](https://bsd-hardware.info/?probe=2556fa3be1) | Dec 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [7b24999fbb](https://bsd-hardware.info/?probe=7b24999fbb) | Dec 22, 2023 |
| Protectli     | VP2420                      | Desktop     | [74c1ede426](https://bsd-hardware.info/?probe=74c1ede426) | Dec 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [426e43d7f2](https://bsd-hardware.info/?probe=426e43d7f2) | Dec 08, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [4a74f06217](https://bsd-hardware.info/?probe=4a74f06217) | Dec 06, 2023 |
| PC Engines    | APU2                        | Desktop     | [6bbcef15d3](https://bsd-hardware.info/?probe=6bbcef15d3) | Dec 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [ca548efdec](https://bsd-hardware.info/?probe=ca548efdec) | Dec 04, 2023 |
| PC Engines    | APU2                        | Desktop     | [46fa133d51](https://bsd-hardware.info/?probe=46fa133d51) | Dec 04, 2023 |
| HP            | 1825                        | Desktop     | [3edf79b1ba](https://bsd-hardware.info/?probe=3edf79b1ba) | Dec 03, 2023 |
| Lenovo        | ThinkPad X280 20KES5M300    | Notebook    | [28d67ab74a](https://bsd-hardware.info/?probe=28d67ab74a) | Dec 02, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [b394563830](https://bsd-hardware.info/?probe=b394563830) | Nov 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [5631aa6b68](https://bsd-hardware.info/?probe=5631aa6b68) | Nov 27, 2023 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [3997370fc6](https://bsd-hardware.info/?probe=3997370fc6) | Nov 25, 2023 |
| YANYU         | ITX-M9F VER:1.3 baytrail    | Desktop     | [c9e7bbc120](https://bsd-hardware.info/?probe=c9e7bbc120) | Nov 23, 2023 |
| Lenovo        | ThinkCentre M720s 10SUSB... | Desktop     | [a44a9f3526](https://bsd-hardware.info/?probe=a44a9f3526) | Nov 23, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e26144a9ce](https://bsd-hardware.info/?probe=e26144a9ce) | Nov 23, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [17d29b1055](https://bsd-hardware.info/?probe=17d29b1055) | Nov 19, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [98fac2d452](https://bsd-hardware.info/?probe=98fac2d452) | Nov 15, 2023 |
| YENTEK        | D41SL                       | Desktop     | [8cb79449c8](https://bsd-hardware.info/?probe=8cb79449c8) | Nov 10, 2023 |
| BESSTAR Te... | VB9                         | All in one  | [e750d16fb3](https://bsd-hardware.info/?probe=e750d16fb3) | Nov 05, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [018805dc37](https://bsd-hardware.info/?probe=018805dc37) | Nov 03, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [7077dec0a1](https://bsd-hardware.info/?probe=7077dec0a1) | Nov 01, 2023 |
| YANYU         | M9F baytrail                | Desktop     | [746772e77b](https://bsd-hardware.info/?probe=746772e77b) | Oct 30, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [bb195148f7](https://bsd-hardware.info/?probe=bb195148f7) | Oct 29, 2023 |
| Dell          | PowerEdge T110 II           | Desktop     | [f93395bc11](https://bsd-hardware.info/?probe=f93395bc11) | Oct 28, 2023 |
| YANYU         | M9F baytrail                | Desktop     | [f9e833a5f9](https://bsd-hardware.info/?probe=f9e833a5f9) | Oct 27, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [8af7ab0e4d](https://bsd-hardware.info/?probe=8af7ab0e4d) | Oct 27, 2023 |
| Toshiba       | Unknown                     | Notebook    | [de44a16738](https://bsd-hardware.info/?probe=de44a16738) | Oct 24, 2023 |
| HP            | 213D A01                    | Desktop     | [6a023bfe9f](https://bsd-hardware.info/?probe=6a023bfe9f) | Oct 14, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [fbc9fe11b1](https://bsd-hardware.info/?probe=fbc9fe11b1) | Oct 13, 2023 |
| ANGXUN        | X79-VG2 V1.3                | Desktop     | [c823cbad48](https://bsd-hardware.info/?probe=c823cbad48) | Oct 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [1bb43f3258](https://bsd-hardware.info/?probe=1bb43f3258) | Oct 10, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [9e99e33fa3](https://bsd-hardware.info/?probe=9e99e33fa3) | Oct 09, 2023 |
| Dell          | Latitude D830               | Notebook    | [4cf27e5d29](https://bsd-hardware.info/?probe=4cf27e5d29) | Oct 09, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [08dab02121](https://bsd-hardware.info/?probe=08dab02121) | Oct 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [af88ff7c18](https://bsd-hardware.info/?probe=af88ff7c18) | Oct 07, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9190b85f99](https://bsd-hardware.info/?probe=9190b85f99) | Oct 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [914de9ed88](https://bsd-hardware.info/?probe=914de9ed88) | Oct 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ba9a892240](https://bsd-hardware.info/?probe=ba9a892240) | Oct 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [002103bb3a](https://bsd-hardware.info/?probe=002103bb3a) | Oct 02, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [dffc2e116d](https://bsd-hardware.info/?probe=dffc2e116d) | Sep 30, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [29bcb3ca3e](https://bsd-hardware.info/?probe=29bcb3ca3e) | Sep 29, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [8d5549809c](https://bsd-hardware.info/?probe=8d5549809c) | Sep 27, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [cba80ecde3](https://bsd-hardware.info/?probe=cba80ecde3) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [dcf1ebd901](https://bsd-hardware.info/?probe=dcf1ebd901) | Sep 20, 2023 |
| AZW           | U59                         | Desktop     | [ae0d8568d1](https://bsd-hardware.info/?probe=ae0d8568d1) | Sep 15, 2023 |
| AZW           | U59                         | Desktop     | [7e094459f9](https://bsd-hardware.info/?probe=7e094459f9) | Sep 14, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [67d1f42d7c](https://bsd-hardware.info/?probe=67d1f42d7c) | Sep 13, 2023 |
| Fujitsu       | D3090-A1 S26361-D3090-A1    | Server      | [f509d12cea](https://bsd-hardware.info/?probe=f509d12cea) | Aug 29, 2023 |
| PC Engines    | APU2                        | Desktop     | [3d3b16c0cf](https://bsd-hardware.info/?probe=3d3b16c0cf) | Aug 25, 2023 |
| AZW           | U59                         | Desktop     | [e08540ab36](https://bsd-hardware.info/?probe=e08540ab36) | Aug 25, 2023 |
| Protectli     | FW4B                        | Desktop     | [4b358b0106](https://bsd-hardware.info/?probe=4b358b0106) | Aug 24, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [3ac93594a2](https://bsd-hardware.info/?probe=3ac93594a2) | Aug 20, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [3b430afdad](https://bsd-hardware.info/?probe=3b430afdad) | Aug 18, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [66449212d1](https://bsd-hardware.info/?probe=66449212d1) | Aug 18, 2023 |
| BESSTAR Te... | IB9                         | Desktop     | [c9f5ede507](https://bsd-hardware.info/?probe=c9f5ede507) | Aug 18, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [664ee85747](https://bsd-hardware.info/?probe=664ee85747) | Aug 15, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [46a6b88b33](https://bsd-hardware.info/?probe=46a6b88b33) | Aug 11, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f0398bfb85](https://bsd-hardware.info/?probe=f0398bfb85) | Aug 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [28f0d503fd](https://bsd-hardware.info/?probe=28f0d503fd) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [6238337b24](https://bsd-hardware.info/?probe=6238337b24) | Aug 07, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d3fac2e3fe](https://bsd-hardware.info/?probe=d3fac2e3fe) | Aug 06, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [155f885c95](https://bsd-hardware.info/?probe=155f885c95) | Aug 01, 2023 |
| ASUSTek       | P8P67                       | Desktop     | [0e10359af8](https://bsd-hardware.info/?probe=0e10359af8) | Jul 29, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [e74d459c5a](https://bsd-hardware.info/?probe=e74d459c5a) | Jul 28, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [a3624fdcfc](https://bsd-hardware.info/?probe=a3624fdcfc) | Jul 24, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [a441b76fb8](https://bsd-hardware.info/?probe=a441b76fb8) | Jul 20, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | Notebook    | [57b4bfc1bf](https://bsd-hardware.info/?probe=57b4bfc1bf) | Jul 17, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [0f55bad1af](https://bsd-hardware.info/?probe=0f55bad1af) | Jul 08, 2023 |
| MSI           | H510I PRO WIFI              | Desktop     | [743d249ba5](https://bsd-hardware.info/?probe=743d249ba5) | Jul 07, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [48fcb6e4ab](https://bsd-hardware.info/?probe=48fcb6e4ab) | Jul 05, 2023 |
| Protectli     | FW4B                        | Desktop     | [a3cf476fe8](https://bsd-hardware.info/?probe=a3cf476fe8) | Jul 03, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [c30f91d5cc](https://bsd-hardware.info/?probe=c30f91d5cc) | Jul 01, 2023 |
| ASUSTek       | N3700T                      | Desktop     | [16b73b05ef](https://bsd-hardware.info/?probe=16b73b05ef) | Jun 26, 2023 |
| HP            | Pavilion 15                 | Notebook    | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| ASUSTek       | 1015P                       | Notebook    | [c700224684](https://bsd-hardware.info/?probe=c700224684) | Jun 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [229e573059](https://bsd-hardware.info/?probe=229e573059) | Jun 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d271bc94c](https://bsd-hardware.info/?probe=9d271bc94c) | Jun 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fe412825f2](https://bsd-hardware.info/?probe=fe412825f2) | Jun 10, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [c8496622be](https://bsd-hardware.info/?probe=c8496622be) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [b9f7e3e209](https://bsd-hardware.info/?probe=b9f7e3e209) | Jun 03, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [d08f309c4c](https://bsd-hardware.info/?probe=d08f309c4c) | May 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [9160d45441](https://bsd-hardware.info/?probe=9160d45441) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [8b5ec8c5f4](https://bsd-hardware.info/?probe=8b5ec8c5f4) | May 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [582dc6ab9f](https://bsd-hardware.info/?probe=582dc6ab9f) | May 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [b26eac2277](https://bsd-hardware.info/?probe=b26eac2277) | May 13, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [1dac5a7bb2](https://bsd-hardware.info/?probe=1dac5a7bb2) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [bf8246ecb5](https://bsd-hardware.info/?probe=bf8246ecb5) | May 11, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [be83fbb0f2](https://bsd-hardware.info/?probe=be83fbb0f2) | May 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [5c6c169e73](https://bsd-hardware.info/?probe=5c6c169e73) | May 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [d572f5ff91](https://bsd-hardware.info/?probe=d572f5ff91) | May 01, 2023 |
| Unknown       | HX90                        | Desktop     | [b3300c45bc](https://bsd-hardware.info/?probe=b3300c45bc) | May 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [1774da050f](https://bsd-hardware.info/?probe=1774da050f) | Apr 29, 2023 |
| AWOW          | AK34Pro                     | Mini pc     | [0471af8c22](https://bsd-hardware.info/?probe=0471af8c22) | Apr 24, 2023 |
| AWOW          | AK34Pro                     | Mini pc     | [30062ec670](https://bsd-hardware.info/?probe=30062ec670) | Apr 23, 2023 |
| HP            | 82B4                        | Desktop     | [9ec1e6d6f4](https://bsd-hardware.info/?probe=9ec1e6d6f4) | Apr 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [03dd920110](https://bsd-hardware.info/?probe=03dd920110) | Apr 22, 2023 |
| Sophos        | UTM                         | Firewall    | [85bf260703](https://bsd-hardware.info/?probe=85bf260703) | Apr 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [d343800c53](https://bsd-hardware.info/?probe=d343800c53) | Apr 16, 2023 |
| PC Engines    | apu4                        | Desktop     | [9217e1982f](https://bsd-hardware.info/?probe=9217e1982f) | Apr 14, 2023 |
| ASRock        | G31M-S                      | Desktop     | [fed4a42c32](https://bsd-hardware.info/?probe=fed4a42c32) | Apr 08, 2023 |
| ASRock        | G31M-S                      | Desktop     | [4596f78aee](https://bsd-hardware.info/?probe=4596f78aee) | Apr 08, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [8354aed46e](https://bsd-hardware.info/?probe=8354aed46e) | Apr 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [5168183b15](https://bsd-hardware.info/?probe=5168183b15) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [385751dbc3](https://bsd-hardware.info/?probe=385751dbc3) | Apr 06, 2023 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [45f590d129](https://bsd-hardware.info/?probe=45f590d129) | Apr 04, 2023 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [ab0643727f](https://bsd-hardware.info/?probe=ab0643727f) | Apr 02, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fb6477d43e](https://bsd-hardware.info/?probe=fb6477d43e) | Mar 31, 2023 |
| Dell          | 0M877N A01                  | Server      | [dabe853e69](https://bsd-hardware.info/?probe=dabe853e69) | Mar 30, 2023 |
| LG Electro... | COLUMBIA                    | Notebook    | [4872f6c377](https://bsd-hardware.info/?probe=4872f6c377) | Mar 27, 2023 |
| YANYU         | H17SL                       | Desktop     | [0f9829ebe4](https://bsd-hardware.info/?probe=0f9829ebe4) | Mar 26, 2023 |
| ASUSTek       | F1A55                       | Desktop     | [91ad5bab75](https://bsd-hardware.info/?probe=91ad5bab75) | Mar 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a7e98f9a10](https://bsd-hardware.info/?probe=a7e98f9a10) | Mar 23, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [eb2bc1cd51](https://bsd-hardware.info/?probe=eb2bc1cd51) | Mar 23, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [cbbeb5c41c](https://bsd-hardware.info/?probe=cbbeb5c41c) | Mar 22, 2023 |
| HP            | 8054                        | Desktop     | [6e5a18f346](https://bsd-hardware.info/?probe=6e5a18f346) | Mar 20, 2023 |
| Intel         | S1200RP_SE                  | Notebook    | [5ae9400f0b](https://bsd-hardware.info/?probe=5ae9400f0b) | Mar 17, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [575123c3ac](https://bsd-hardware.info/?probe=575123c3ac) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [8b9aa95420](https://bsd-hardware.info/?probe=8b9aa95420) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [937a7c9385](https://bsd-hardware.info/?probe=937a7c9385) | Mar 17, 2023 |
| SiComputer    | Embedded                    | Soc         | [9d6aa61a5c](https://bsd-hardware.info/?probe=9d6aa61a5c) | Mar 17, 2023 |
| YANYU         | H17SL                       | Desktop     | [37a549331f](https://bsd-hardware.info/?probe=37a549331f) | Mar 14, 2023 |
| MSI           | 0A48                        | Desktop     | [815f019a8c](https://bsd-hardware.info/?probe=815f019a8c) | Mar 14, 2023 |
| AZW           | U59                         | Desktop     | [5a6ef3fb8d](https://bsd-hardware.info/?probe=5a6ef3fb8d) | Mar 14, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7949f20162](https://bsd-hardware.info/?probe=7949f20162) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a3f921de9a](https://bsd-hardware.info/?probe=a3f921de9a) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2050921c3d](https://bsd-hardware.info/?probe=2050921c3d) | Mar 12, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [6d372db804](https://bsd-hardware.info/?probe=6d372db804) | Mar 12, 2023 |
| Gigabyte      | B450M K                     | Desktop     | [0d0433284e](https://bsd-hardware.info/?probe=0d0433284e) | Mar 11, 2023 |
| NF692         | 1.0                         | Desktop     | [16fa0b0102](https://bsd-hardware.info/?probe=16fa0b0102) | Mar 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [6729453203](https://bsd-hardware.info/?probe=6729453203) | Mar 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [6dee276a48](https://bsd-hardware.info/?probe=6dee276a48) | Mar 07, 2023 |
| Gigabyte      | H97M-HD3                    | Desktop     | [77a58527da](https://bsd-hardware.info/?probe=77a58527da) | Mar 01, 2023 |
| Stonesoft     | FW-315-C1                   | Desktop     | [e8a2206ad2](https://bsd-hardware.info/?probe=e8a2206ad2) | Feb 28, 2023 |
| Lenovo        | ThinkPad T410 2537B94       | Notebook    | [9f9cb3e201](https://bsd-hardware.info/?probe=9f9cb3e201) | Feb 19, 2023 |
| Intel         | JSL MRD                     | Desktop     | [1587ea95da](https://bsd-hardware.info/?probe=1587ea95da) | Feb 18, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [df7f4524d7](https://bsd-hardware.info/?probe=df7f4524d7) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [7f9208dc11](https://bsd-hardware.info/?probe=7f9208dc11) | Feb 06, 2023 |
| HP            | Mini 210-1000               | Notebook    | [eaabd2a89d](https://bsd-hardware.info/?probe=eaabd2a89d) | Feb 02, 2023 |
| HP            | 213D A01                    | Desktop     | [659939cc8b](https://bsd-hardware.info/?probe=659939cc8b) | Jan 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [aa940792fc](https://bsd-hardware.info/?probe=aa940792fc) | Jan 25, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [803a152afc](https://bsd-hardware.info/?probe=803a152afc) | Jan 23, 2023 |
| ASUSTek       | PRO A520M-C                 | Desktop     | [bebcd1a008](https://bsd-hardware.info/?probe=bebcd1a008) | Jan 20, 2023 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [d0e2e85346](https://bsd-hardware.info/?probe=d0e2e85346) | Jan 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [c1e1ba5558](https://bsd-hardware.info/?probe=c1e1ba5558) | Jan 16, 2023 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [942d966486](https://bsd-hardware.info/?probe=942d966486) | Jan 11, 2023 |
| Sophos        | UTM                         | Firewall    | [6379cce732](https://bsd-hardware.info/?probe=6379cce732) | Jan 06, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | Notebook    | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2265227a5c](https://bsd-hardware.info/?probe=2265227a5c) | Dec 26, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [eea4262af2](https://bsd-hardware.info/?probe=eea4262af2) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [cae00eb4d6](https://bsd-hardware.info/?probe=cae00eb4d6) | Dec 22, 2022 |
| MSI           | MS-7922                     | Desktop     | [95dbf4f7a8](https://bsd-hardware.info/?probe=95dbf4f7a8) | Dec 19, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [511f2a6d16](https://bsd-hardware.info/?probe=511f2a6d16) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| Gigabyte      | N3160ND3V                   | Desktop     | [c84bedc821](https://bsd-hardware.info/?probe=c84bedc821) | Dec 15, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [435807287e](https://bsd-hardware.info/?probe=435807287e) | Dec 15, 2022 |
| AZW           | U59                         | Desktop     | [9b22c68e98](https://bsd-hardware.info/?probe=9b22c68e98) | Dec 13, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [6860cd72f8](https://bsd-hardware.info/?probe=6860cd72f8) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [cfdb06e761](https://bsd-hardware.info/?probe=cfdb06e761) | Nov 26, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| Dell          | 0VD5HY A00                  | Desktop     | [1a0df311e3](https://bsd-hardware.info/?probe=1a0df311e3) | Nov 07, 2022 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Acer          | Veriton X2610G              | Desktop     | [e4289c3f15](https://bsd-hardware.info/?probe=e4289c3f15) | Oct 24, 2022 |
| Sophos        | UTM                         | Firewall    | [6a4c00a973](https://bsd-hardware.info/?probe=6a4c00a973) | Oct 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [1188b56e14](https://bsd-hardware.info/?probe=1188b56e14) | Oct 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [915c66f8bd](https://bsd-hardware.info/?probe=915c66f8bd) | Oct 19, 2022 |
| PC Engines    | apu4                        | Desktop     | [20cfd8a3c8](https://bsd-hardware.info/?probe=20cfd8a3c8) | Oct 17, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [c57cc3a923](https://bsd-hardware.info/?probe=c57cc3a923) | Oct 17, 2022 |
| ASRock        | Q1900M                      | Desktop     | [7d0380e2d0](https://bsd-hardware.info/?probe=7d0380e2d0) | Oct 15, 2022 |
| Sophos        | UTM                         | Firewall    | [364e007b1c](https://bsd-hardware.info/?probe=364e007b1c) | Oct 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [d802705c1d](https://bsd-hardware.info/?probe=d802705c1d) | Oct 10, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [a28ea59f1f](https://bsd-hardware.info/?probe=a28ea59f1f) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [81722a937a](https://bsd-hardware.info/?probe=81722a937a) | Sep 13, 2022 |
| HP            | 8648                        | Desktop     | [e7e610794c](https://bsd-hardware.info/?probe=e7e610794c) | Sep 12, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b54e6663f9](https://bsd-hardware.info/?probe=b54e6663f9) | Sep 10, 2022 |
| Intel         | J1900                       | Desktop     | [a95dd12c65](https://bsd-hardware.info/?probe=a95dd12c65) | Sep 06, 2022 |
| HP            | 1496                        | Desktop     | [7cd97bd330](https://bsd-hardware.info/?probe=7cd97bd330) | Sep 05, 2022 |
| PC Engines    | APU2                        | Desktop     | [d9216cb730](https://bsd-hardware.info/?probe=d9216cb730) | Sep 05, 2022 |
| HP            | 1496                        | Desktop     | [94e8713f6d](https://bsd-hardware.info/?probe=94e8713f6d) | Sep 03, 2022 |
| Dell          | 0TY179 A05                  | Server      | [482bca3952](https://bsd-hardware.info/?probe=482bca3952) | Sep 01, 2022 |
| HP            | 1496                        | Desktop     | [1567aa1c21](https://bsd-hardware.info/?probe=1567aa1c21) | Sep 01, 2022 |
| Unknown       | HX90                        | Desktop     | [568468e95b](https://bsd-hardware.info/?probe=568468e95b) | Sep 01, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2349014a6c](https://bsd-hardware.info/?probe=2349014a6c) | Aug 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [b3d60c2790](https://bsd-hardware.info/?probe=b3d60c2790) | Aug 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [02e11159f5](https://bsd-hardware.info/?probe=02e11159f5) | Aug 18, 2022 |
| Fujitsu       | D3373-B1 S26361-D3373-B1... | Server      | [676fd4e9b4](https://bsd-hardware.info/?probe=676fd4e9b4) | Aug 17, 2022 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [c03da8657e](https://bsd-hardware.info/?probe=c03da8657e) | Aug 17, 2022 |
| PC Engines    | APU2                        | Desktop     | [028dc7aa20](https://bsd-hardware.info/?probe=028dc7aa20) | Aug 17, 2022 |
| BESSTAR Te... | VB9                         | All in one  | [ec5b4884a7](https://bsd-hardware.info/?probe=ec5b4884a7) | Aug 13, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [1d4ccaabda](https://bsd-hardware.info/?probe=1d4ccaabda) | Aug 13, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [17dc06ed68](https://bsd-hardware.info/?probe=17dc06ed68) | Aug 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [af3d9689c2](https://bsd-hardware.info/?probe=af3d9689c2) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [5049417b7b](https://bsd-hardware.info/?probe=5049417b7b) | Aug 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c7010b7ebc](https://bsd-hardware.info/?probe=c7010b7ebc) | Aug 09, 2022 |
| Shenzhen M... | AHWSA                       | Desktop     | [21cda0eb5d](https://bsd-hardware.info/?probe=21cda0eb5d) | Aug 09, 2022 |
| Intel         | SKYBAY                      | Desktop     | [bc7d4d8e1e](https://bsd-hardware.info/?probe=bc7d4d8e1e) | Aug 08, 2022 |
| eMachines     | eME728                      | Notebook    | [96d745589c](https://bsd-hardware.info/?probe=96d745589c) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [df3667156b](https://bsd-hardware.info/?probe=df3667156b) | Aug 02, 2022 |
| Lex           | Pineview-D                  | Desktop     | [7d7195024e](https://bsd-hardware.info/?probe=7d7195024e) | Aug 02, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [d6a3d57165](https://bsd-hardware.info/?probe=d6a3d57165) | Jul 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [bb5d45a75d](https://bsd-hardware.info/?probe=bb5d45a75d) | Jul 29, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [e3655742ba](https://bsd-hardware.info/?probe=e3655742ba) | Jul 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [4b9e0bb7bb](https://bsd-hardware.info/?probe=4b9e0bb7bb) | Jul 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [af1e80d15d](https://bsd-hardware.info/?probe=af1e80d15d) | Jul 18, 2022 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [def87ec245](https://bsd-hardware.info/?probe=def87ec245) | Jul 18, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [7b6faf5301](https://bsd-hardware.info/?probe=7b6faf5301) | Jul 14, 2022 |
| Dell          | Latitude E5450              | Notebook    | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | Notebook    | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0434c94fad](https://bsd-hardware.info/?probe=0434c94fad) | Jul 09, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [ba243fa7c4](https://bsd-hardware.info/?probe=ba243fa7c4) | Jul 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [4ac86f5979](https://bsd-hardware.info/?probe=4ac86f5979) | Jul 09, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [d3aba12432](https://bsd-hardware.info/?probe=d3aba12432) | Jul 09, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [6011c70ca4](https://bsd-hardware.info/?probe=6011c70ca4) | Jul 07, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [dbbe9124a2](https://bsd-hardware.info/?probe=dbbe9124a2) | Jul 05, 2022 |
| HP            | 0A98h                       | Desktop     | [655fc531fb](https://bsd-hardware.info/?probe=655fc531fb) | Jun 30, 2022 |
| Acer          | AOD260                      | Notebook    | [08dc464d1b](https://bsd-hardware.info/?probe=08dc464d1b) | Jun 30, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [e461a4559d](https://bsd-hardware.info/?probe=e461a4559d) | Jun 29, 2022 |
| HP            | 304Bh                       | Desktop     | [8a3151b3cd](https://bsd-hardware.info/?probe=8a3151b3cd) | Jun 16, 2022 |
| NF692         | 1.0                         | Desktop     | [e87866bf5a](https://bsd-hardware.info/?probe=e87866bf5a) | Jun 10, 2022 |
| Lenovo        | ThinkPad L530 24812TG       | Notebook    | [5b66684c4a](https://bsd-hardware.info/?probe=5b66684c4a) | Jun 05, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [8099e7abaf](https://bsd-hardware.info/?probe=8099e7abaf) | Jun 03, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [4b3b7a0929](https://bsd-hardware.info/?probe=4b3b7a0929) | May 31, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [5d3db8382f](https://bsd-hardware.info/?probe=5d3db8382f) | May 31, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | Notebook    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| T-bao         | MINI PC V1.0                | Desktop     | [a89b2081bb](https://bsd-hardware.info/?probe=a89b2081bb) | May 25, 2022 |
| ASUSTek       | F50SL                       | Notebook    | [e26b522868](https://bsd-hardware.info/?probe=e26b522868) | May 22, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [23396b461f](https://bsd-hardware.info/?probe=23396b461f) | May 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [2769c8f286](https://bsd-hardware.info/?probe=2769c8f286) | May 17, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [55cda59c51](https://bsd-hardware.info/?probe=55cda59c51) | May 17, 2022 |
| ASUSTek       | K52F                        | Notebook    | [6e86ce2a12](https://bsd-hardware.info/?probe=6e86ce2a12) | May 15, 2022 |
| ASUSTek       | K52F                        | Notebook    | [4c12c55177](https://bsd-hardware.info/?probe=4c12c55177) | May 15, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [5e781a451d](https://bsd-hardware.info/?probe=5e781a451d) | May 12, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [407fc42fad](https://bsd-hardware.info/?probe=407fc42fad) | May 05, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [5ff176fff8](https://bsd-hardware.info/?probe=5ff176fff8) | May 05, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [8a8db12cf2](https://bsd-hardware.info/?probe=8a8db12cf2) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4236BD5       | Notebook    | [867ed989e2](https://bsd-hardware.info/?probe=867ed989e2) | Apr 27, 2022 |
| MSI           | GF65 Thin 10SER             | Notebook    | [cedf98c955](https://bsd-hardware.info/?probe=cedf98c955) | Apr 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| Dell          | 0TY179 A05                  | Server      | [124e42e2c1](https://bsd-hardware.info/?probe=124e42e2c1) | Apr 21, 2022 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [9a50fe43a7](https://bsd-hardware.info/?probe=9a50fe43a7) | Apr 21, 2022 |
| Pegatron      | Benicia                     | Desktop     | [9045b4f449](https://bsd-hardware.info/?probe=9045b4f449) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [680303f943](https://bsd-hardware.info/?probe=680303f943) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [47d17d48a7](https://bsd-hardware.info/?probe=47d17d48a7) | Apr 15, 2022 |
| Dell          | 07978V A08                  | Server      | [f315c33e95](https://bsd-hardware.info/?probe=f315c33e95) | Apr 06, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [fbdd8d4f48](https://bsd-hardware.info/?probe=fbdd8d4f48) | Apr 05, 2022 |
| HP            | 212B                        | Desktop     | [33e7c65907](https://bsd-hardware.info/?probe=33e7c65907) | Apr 04, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [3877a33214](https://bsd-hardware.info/?probe=3877a33214) | Apr 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [3da637e3c6](https://bsd-hardware.info/?probe=3da637e3c6) | Apr 02, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [7b79164c18](https://bsd-hardware.info/?probe=7b79164c18) | Apr 01, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [9f760529c1](https://bsd-hardware.info/?probe=9f760529c1) | Mar 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [bddd5d8963](https://bsd-hardware.info/?probe=bddd5d8963) | Mar 18, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [bb895c5df3](https://bsd-hardware.info/?probe=bb895c5df3) | Mar 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [65ada9d5da](https://bsd-hardware.info/?probe=65ada9d5da) | Mar 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [0394e3272e](https://bsd-hardware.info/?probe=0394e3272e) | Mar 03, 2022 |
| HP            | 3397                        | Desktop     | [841ed56816](https://bsd-hardware.info/?probe=841ed56816) | Mar 02, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [6696106165](https://bsd-hardware.info/?probe=6696106165) | Feb 19, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [e098f52d51](https://bsd-hardware.info/?probe=e098f52d51) | Feb 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| Acer          | V5-131                      | Notebook    | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ea7cf2885f](https://bsd-hardware.info/?probe=ea7cf2885f) | Feb 13, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [946c9acc2e](https://bsd-hardware.info/?probe=946c9acc2e) | Feb 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7a3744a41a](https://bsd-hardware.info/?probe=7a3744a41a) | Feb 07, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| HP            | Mini 210-1000               | Notebook    | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| Dell          | 0TK7TF A00                  | Desktop     | [d13ca7163c](https://bsd-hardware.info/?probe=d13ca7163c) | Jan 30, 2022 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [f4d8bd7979](https://bsd-hardware.info/?probe=f4d8bd7979) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [f7e7df9416](https://bsd-hardware.info/?probe=f7e7df9416) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [fc63aa695e](https://bsd-hardware.info/?probe=fc63aa695e) | Jan 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [52bd5dc1ce](https://bsd-hardware.info/?probe=52bd5dc1ce) | Jan 26, 2022 |
| ASUSTek       | BM6835_BM6635_BP6335        | Desktop     | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cf360a6098](https://bsd-hardware.info/?probe=cf360a6098) | Jan 16, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [d76873c5dd](https://bsd-hardware.info/?probe=d76873c5dd) | Jan 16, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ed9f5d1a27](https://bsd-hardware.info/?probe=ed9f5d1a27) | Jan 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [c2b05fc937](https://bsd-hardware.info/?probe=c2b05fc937) | Jan 14, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [7b99b0eaa6](https://bsd-hardware.info/?probe=7b99b0eaa6) | Jan 10, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [4ac0707c49](https://bsd-hardware.info/?probe=4ac0707c49) | Jan 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [341401bb02](https://bsd-hardware.info/?probe=341401bb02) | Jan 04, 2022 |
| Unknown       | Unknown                     | Notebook    | [46e5f9b021](https://bsd-hardware.info/?probe=46e5f9b021) | Dec 29, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [7a43524381](https://bsd-hardware.info/?probe=7a43524381) | Dec 13, 2021 |
| Packard Be... | EasyNote_MX61-B-038         | Notebook    | [235d60060d](https://bsd-hardware.info/?probe=235d60060d) | Dec 12, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [60a25af38c](https://bsd-hardware.info/?probe=60a25af38c) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| ASUSTek       | 1000                        | Notebook    | [da8689c840](https://bsd-hardware.info/?probe=da8689c840) | Dec 08, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ddcab97db2](https://bsd-hardware.info/?probe=ddcab97db2) | Dec 03, 2021 |
| Toshiba       | Satellite C855-1U4          | Notebook    | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [2ac9bea1e6](https://bsd-hardware.info/?probe=2ac9bea1e6) | Nov 13, 2021 |
| T-bao         | MINI PC V1.0                | Desktop     | [4ee7de3597](https://bsd-hardware.info/?probe=4ee7de3597) | Nov 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [22a18ba45e](https://bsd-hardware.info/?probe=22a18ba45e) | Nov 08, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [5f026ff3a2](https://bsd-hardware.info/?probe=5f026ff3a2) | Oct 17, 2021 |
| Pegatron      | 2ACF                        | Desktop     | [ca23d3bbf0](https://bsd-hardware.info/?probe=ca23d3bbf0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [b3b31d25b0](https://bsd-hardware.info/?probe=b3b31d25b0) | Oct 13, 2021 |
| Pegatron      | 2ACF                        | Desktop     | [97aa5e56e4](https://bsd-hardware.info/?probe=97aa5e56e4) | Oct 12, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [5a7c1871b1](https://bsd-hardware.info/?probe=5a7c1871b1) | Oct 11, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [a9c135bf27](https://bsd-hardware.info/?probe=a9c135bf27) | Oct 10, 2021 |
| Acer          | Veriton X2610G              | Desktop     | [1e9ed23164](https://bsd-hardware.info/?probe=1e9ed23164) | Oct 03, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [51b47d9321](https://bsd-hardware.info/?probe=51b47d9321) | Sep 27, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [de031313ff](https://bsd-hardware.info/?probe=de031313ff) | Sep 27, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [e0ad80acf9](https://bsd-hardware.info/?probe=e0ad80acf9) | Sep 20, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [0d23147c7d](https://bsd-hardware.info/?probe=0d23147c7d) | Sep 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [e0ae9af4ab](https://bsd-hardware.info/?probe=e0ae9af4ab) | Sep 15, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [f1a2baeecb](https://bsd-hardware.info/?probe=f1a2baeecb) | Sep 14, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [bc2a287495](https://bsd-hardware.info/?probe=bc2a287495) | Sep 13, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [3607c373aa](https://bsd-hardware.info/?probe=3607c373aa) | Sep 11, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [73912d5852](https://bsd-hardware.info/?probe=73912d5852) | Sep 09, 2021 |
| Protectli     | FW4B                        | Desktop     | [861a1f7012](https://bsd-hardware.info/?probe=861a1f7012) | Aug 25, 2021 |
| MSI           | MS-B1591                    | Desktop     | [679b2010e9](https://bsd-hardware.info/?probe=679b2010e9) | Aug 03, 2021 |
| MSI           | MS-B1591                    | Desktop     | [b370a74ec0](https://bsd-hardware.info/?probe=b370a74ec0) | Aug 02, 2021 |
| Lenovo        | G505 20240                  | Notebook    | [16e6ec4054](https://bsd-hardware.info/?probe=16e6ec4054) | Aug 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [acfe0caa83](https://bsd-hardware.info/?probe=acfe0caa83) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9c9d4cc782](https://bsd-hardware.info/?probe=9c9d4cc782) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3d5e512e18](https://bsd-hardware.info/?probe=3d5e512e18) | Jul 18, 2021 |
| Gigabyte      | P55A-UD3                    | Desktop     | [dc1b4d8a6b](https://bsd-hardware.info/?probe=dc1b4d8a6b) | Jul 16, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [d51149c1d5](https://bsd-hardware.info/?probe=d51149c1d5) | Jul 13, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [7fe4b5ff70](https://bsd-hardware.info/?probe=7fe4b5ff70) | Jul 12, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [dbacaa5c65](https://bsd-hardware.info/?probe=dbacaa5c65) | Jul 08, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [31d42f4469](https://bsd-hardware.info/?probe=31d42f4469) | Jul 05, 2021 |
| Lenovo        | B590 62743PG                | Notebook    | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [f0e80b0788](https://bsd-hardware.info/?probe=f0e80b0788) | Jun 28, 2021 |
| PC Engines    | APU2                        | Desktop     | [dde9077545](https://bsd-hardware.info/?probe=dde9077545) | Jun 24, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [7cf77c6f1f](https://bsd-hardware.info/?probe=7cf77c6f1f) | Jun 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [822df8eb91](https://bsd-hardware.info/?probe=822df8eb91) | May 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [cc17eea606](https://bsd-hardware.info/?probe=cc17eea606) | May 10, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [e26ecef661](https://bsd-hardware.info/?probe=e26ecef661) | May 03, 2021 |
| MSI           | B450-A PRO                  | Desktop     | [ed656e816f](https://bsd-hardware.info/?probe=ed656e816f) | May 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [df793cf09f](https://bsd-hardware.info/?probe=df793cf09f) | Apr 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [62376c16a4](https://bsd-hardware.info/?probe=62376c16a4) | Mar 31, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [5a7ba137e0](https://bsd-hardware.info/?probe=5a7ba137e0) | Mar 27, 2021 |
| Acer          | EG43M                       | Desktop     | [0bc978756c](https://bsd-hardware.info/?probe=0bc978756c) | Mar 27, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [139e702b9a](https://bsd-hardware.info/?probe=139e702b9a) | Mar 27, 2021 |
| Lenovo        | ThinkPad L530 24812TG       | Notebook    | [520982317e](https://bsd-hardware.info/?probe=520982317e) | Mar 25, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f9c3fc3b84](https://bsd-hardware.info/?probe=f9c3fc3b84) | Mar 19, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [5ae508dfa8](https://bsd-hardware.info/?probe=5ae508dfa8) | Mar 19, 2021 |
| Lenovo        | ThinkPad X260 20F5S82N00    | Notebook    | [aa3deadedd](https://bsd-hardware.info/?probe=aa3deadedd) | Mar 19, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [0a3b290f9f](https://bsd-hardware.info/?probe=0a3b290f9f) | Mar 15, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [1c30f7523f](https://bsd-hardware.info/?probe=1c30f7523f) | Mar 15, 2021 |
| PC Engines    | APU3                        | Desktop     | [822a83f208](https://bsd-hardware.info/?probe=822a83f208) | Mar 11, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [c672201bcb](https://bsd-hardware.info/?probe=c672201bcb) | Mar 10, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [66a223add9](https://bsd-hardware.info/?probe=66a223add9) | Mar 08, 2021 |
| Dell          | 00NH4P A07                  | Server      | [7cff5a5c58](https://bsd-hardware.info/?probe=7cff5a5c58) | Mar 08, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bf572bc102](https://bsd-hardware.info/?probe=bf572bc102) | Mar 06, 2021 |
| Dell          | 0R849J A00                  | Desktop     | [1bd1dc24c9](https://bsd-hardware.info/?probe=1bd1dc24c9) | Mar 06, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [55045aa9e5](https://bsd-hardware.info/?probe=55045aa9e5) | Mar 03, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [10d02d0982](https://bsd-hardware.info/?probe=10d02d0982) | Mar 03, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [3c5bd7b7f8](https://bsd-hardware.info/?probe=3c5bd7b7f8) | Mar 02, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [04e66ca239](https://bsd-hardware.info/?probe=04e66ca239) | Mar 02, 2021 |
| ASUSTek       | G1S                         | Notebook    | [593c12aa06](https://bsd-hardware.info/?probe=593c12aa06) | Feb 28, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [50652a4263](https://bsd-hardware.info/?probe=50652a4263) | Feb 26, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [58c6bf426e](https://bsd-hardware.info/?probe=58c6bf426e) | Feb 22, 2021 |
| Dell          | 00NH4P A07                  | Server      | [fff0533829](https://bsd-hardware.info/?probe=fff0533829) | Feb 20, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [5257239fdc](https://bsd-hardware.info/?probe=5257239fdc) | Feb 20, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [6fe9279f1f](https://bsd-hardware.info/?probe=6fe9279f1f) | Feb 18, 2021 |
| eMachines     | eME732ZG                    | Notebook    | [d0c0433452](https://bsd-hardware.info/?probe=d0c0433452) | Feb 16, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [74d43ccd10](https://bsd-hardware.info/?probe=74d43ccd10) | Feb 16, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [c996e74ebc](https://bsd-hardware.info/?probe=c996e74ebc) | Feb 14, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [f808e6bb4a](https://bsd-hardware.info/?probe=f808e6bb4a) | Feb 13, 2021 |
| eMachines     | eME732ZG                    | Notebook    | [c51678397d](https://bsd-hardware.info/?probe=c51678397d) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | Desktop     | [32acfb4467](https://bsd-hardware.info/?probe=32acfb4467) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b861820636](https://bsd-hardware.info/?probe=b861820636) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | Desktop     | [2ff05af403](https://bsd-hardware.info/?probe=2ff05af403) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [3a3d7d0701](https://bsd-hardware.info/?probe=3a3d7d0701) | Feb 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [37e4e7c85c](https://bsd-hardware.info/?probe=37e4e7c85c) | Feb 12, 2021 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | Desktop     | [6fdcef7c9e](https://bsd-hardware.info/?probe=6fdcef7c9e) | Feb 10, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a77e980850](https://bsd-hardware.info/?probe=a77e980850) | Feb 09, 2021 |
| ASUSTek       | X502CA                      | Notebook    | [5e15d06a9b](https://bsd-hardware.info/?probe=5e15d06a9b) | Feb 06, 2021 |
| ASUSTek       | X502CA                      | Notebook    | [1a2df26f19](https://bsd-hardware.info/?probe=1a2df26f19) | Feb 06, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [4d225e7ebe](https://bsd-hardware.info/?probe=4d225e7ebe) | Feb 04, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [01a2dd5a52](https://bsd-hardware.info/?probe=01a2dd5a52) | Feb 02, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [f813782c8a](https://bsd-hardware.info/?probe=f813782c8a) | Jan 29, 2021 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [2aa7735e59](https://bsd-hardware.info/?probe=2aa7735e59) | Jan 24, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [622589c8e7](https://bsd-hardware.info/?probe=622589c8e7) | Jan 22, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [7a3cb6a061](https://bsd-hardware.info/?probe=7a3cb6a061) | Jan 22, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [9eca3b0463](https://bsd-hardware.info/?probe=9eca3b0463) | Jan 22, 2021 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [12ea57f317](https://bsd-hardware.info/?probe=12ea57f317) | Jan 22, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [fcc759e013](https://bsd-hardware.info/?probe=fcc759e013) | Jan 21, 2021 |
| ASRock        | H81 Pro BTC                 | Desktop     | [afb7cd1f1a](https://bsd-hardware.info/?probe=afb7cd1f1a) | Jan 20, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [92577053eb](https://bsd-hardware.info/?probe=92577053eb) | Jan 20, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [33a6dda088](https://bsd-hardware.info/?probe=33a6dda088) | Jan 20, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [539b95f535](https://bsd-hardware.info/?probe=539b95f535) | Jan 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [a178f8eb47](https://bsd-hardware.info/?probe=a178f8eb47) | Jan 19, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [bc4bca1e5e](https://bsd-hardware.info/?probe=bc4bca1e5e) | Jan 18, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [e39a46cadf](https://bsd-hardware.info/?probe=e39a46cadf) | Jan 17, 2021 |
| MSI           | Boston                      | Desktop     | [aa9d7bae21](https://bsd-hardware.info/?probe=aa9d7bae21) | Jan 17, 2021 |
| MSI           | Boston                      | Desktop     | [f21954fa35](https://bsd-hardware.info/?probe=f21954fa35) | Jan 17, 2021 |
| Supermicro    | X8STi                       | Desktop     | [7d0e121099](https://bsd-hardware.info/?probe=7d0e121099) | Jan 15, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [c4eecdac67](https://bsd-hardware.info/?probe=c4eecdac67) | Jan 14, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| Unknown       | Unknown                     | Desktop     | [d2cdc0fc7f](https://bsd-hardware.info/?probe=d2cdc0fc7f) | Nov 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [aee9f448af](https://bsd-hardware.info/?probe=aee9f448af) | Nov 25, 2020 |
| Lenovo        | ThinkPad T495 20NJS0KP00    | Notebook    | [7a706e46de](https://bsd-hardware.info/?probe=7a706e46de) | Oct 31, 2020 |
| Lenovo        | ThinkPad T430 23501B3       | Notebook    | [53233cc736](https://bsd-hardware.info/?probe=53233cc736) | Oct 31, 2020 |
| Intel         | D945GCLF2                   | Desktop     | [58678b0643](https://bsd-hardware.info/?probe=58678b0643) | Oct 30, 2020 |
| Intel         | D945GCLF2                   | Desktop     | [3354fb903b](https://bsd-hardware.info/?probe=3354fb903b) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [973b62551f](https://bsd-hardware.info/?probe=973b62551f) | Oct 30, 2020 |
| AZW           | BT3 X                       | Desktop     | [b9f23ee753](https://bsd-hardware.info/?probe=b9f23ee753) | Oct 30, 2020 |
| Dell          | Precision 3510              | Notebook    | [85a55ab7c3](https://bsd-hardware.info/?probe=85a55ab7c3) | Oct 22, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7faf1699d6](https://bsd-hardware.info/?probe=7faf1699d6) | Oct 04, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [36d0d99aa6](https://bsd-hardware.info/?probe=36d0d99aa6) | Oct 04, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1d227a9cd2](https://bsd-hardware.info/?probe=1d227a9cd2) | Oct 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2f119a81b4](https://bsd-hardware.info/?probe=2f119a81b4) | Aug 13, 2020 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [f437a3b5ab](https://bsd-hardware.info/?probe=f437a3b5ab) | Jul 06, 2020 |
| ASRock        | 990FX Extreme9              | Desktop     | [6c0bba6d4f](https://bsd-hardware.info/?probe=6c0bba6d4f) | Jun 26, 2020 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [6b854263e7](https://bsd-hardware.info/?probe=6b854263e7) | May 25, 2020 |
| Lenovo        | ThinkPad T440 20B7S1C600    | Notebook    | [a4a62cb85e](https://bsd-hardware.info/?probe=a4a62cb85e) | May 24, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N    | Notebook    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| helloSystem 0.8.1 | 28        | 4.84%   |
| helloSystem 0.7.0 | 19        | 3.29%   |
| helloSystem 0.4.0 | 12        | 2.08%   |
| OPNsense 25.1.3   | 10        | 1.73%   |
| OPNsense 24.7.12  | 10        | 1.73%   |
| OPNsense 25.1.5   | 9         | 1.56%   |
| OPNsense 25.1.1   | 9         | 1.56%   |
| OpenBSD 7.1       | 9         | 1.56%   |
| helloSystem 0.9.0 | 9         | 1.56%   |
| helloSystem 0.5.0 | 9         | 1.56%   |
| OPNsense 25.1.7   | 8         | 1.38%   |
| OPNsense 23.7.9   | 7         | 1.21%   |
| OPNsense 22.7     | 7         | 1.21%   |
| helloSystem 0.8.0 | 7         | 1.21%   |
| OPNsense 25.7.7   | 6         | 1.04%   |
| OPNsense 25.7.10  | 6         | 1.04%   |
| OPNsense 25.1.2   | 6         | 1.04%   |
| OPNsense 24.7.10  | 6         | 1.04%   |
| OPNsense 24.1.9   | 6         | 1.04%   |
| OPNsense 23.7.5   | 6         | 1.04%   |
| OPNsense 23.1.6   | 6         | 1.04%   |
| OPNsense 23.1.5   | 6         | 1.04%   |
| OPNsense 23.1.11  | 6         | 1.04%   |
| helloSystem 0.6.0 | 6         | 1.04%   |
| FreeBSD 13.1      | 6         | 1.04%   |
| OPNsense 24.1.8   | 5         | 0.87%   |
| OPNsense 23.7.7   | 5         | 0.87%   |
| OPNsense 23.7.12  | 5         | 0.87%   |
| OPNsense 22.1.6   | 5         | 0.87%   |
| OPNsense 21.1     | 5         | 0.87%   |
| OpenBSD 7.6       | 5         | 0.87%   |
| OpenBSD 7.5       | 5         | 0.87%   |
| OpenBSD 7.2       | 5         | 0.87%   |
| helloSystem 0.3.0 | 5         | 0.87%   |
| OPNsense 25.7.9   | 4         | 0.69%   |
| OPNsense 24.7.9   | 4         | 0.69%   |
| OPNsense 24.7.8   | 4         | 0.69%   |
| OPNsense 24.7.11  | 4         | 0.69%   |
| OPNsense 24.7     | 4         | 0.69%   |
| OPNsense 24.1.5   | 4         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 218       | 51.78%  |
| helloSystem | 83        | 19.71%  |
| FreeBSD     | 55        | 13.06%  |
| OpenBSD     | 36        | 8.55%   |
| NetBSD      | 11        | 2.61%   |
| GhostBSD    | 9         | 2.14%   |
| NomadBSD    | 8         | 1.9%    |
| XigmaNAS    | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 410       | 98.09%  |
| i386    | 3         | 0.72%   |
| evbarm  | 3         | 0.72%   |
| sparc64 | 2         | 0.48%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 234       | 54.8%   |
| helloDesktop  | 92        | 21.55%  |
| XFCE          | 35        | 8.2%    |
| MATE          | 11        | 2.58%   |
| KDE5          | 11        | 2.58%   |
| TWM           | 9         | 2.11%   |
| Openbox       | 7         | 1.64%   |
| fvwm          | 5         | 1.17%   |
| ctwm          | 5         | 1.17%   |
| i3            | 4         | 0.94%   |
| Cinnamon      | 3         | 0.7%    |
| xfwm          | 2         | 0.47%   |
| Enlightenment | 2         | 0.47%   |
| mango         | 1         | 0.23%   |
| LXQt          | 1         | 0.23%   |
| LXDE          | 1         | 0.23%   |
| KDE6          | 1         | 0.23%   |
| KDE           | 1         | 0.23%   |
| IceWM         | 1         | 0.23%   |
| Fluxbox       | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 233       | 55.61%  |
| X11     | 184       | 43.91%  |
| Wayland | 2         | 0.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 294       | 69.67%  |
| SLiM    | 96        | 22.75%  |
| LightDM | 15        | 3.55%   |
| SDDM    | 11        | 2.61%   |
| XDM     | 4         | 0.95%   |
| Ly      | 1         | 0.24%   |
| GDM     | 1         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 263       | 61.02%  |
| en_US            | 68        | 15.78%  |
| it_IT            | 44        | 10.21%  |
| C                | 36        | 8.35%   |
| fr_FR            | 7         | 1.62%   |
| it               | 3         | 0.7%    |
| it_IT.ISO8859-15 | 2         | 0.46%   |
| en               | 2         | 0.46%   |
| ru_RU            | 1         | 0.23%   |
| LANG="en_US"     | 1         | 0.23%   |
| it_IT.ISO8859-1  | 1         | 0.23%   |
| fi_FI            | 1         | 0.23%   |
| en_GB            | 1         | 0.23%   |
| en_EN            | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 371       | 88.33%  |
| BIOS | 49        | 11.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 195       | 45.35%  |
| Ufs    | 162       | 37.67%  |
| Cd9660 | 37        | 8.6%    |
| Ffs    | 36        | 8.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 388       | 92.16%  |
| MBR     | 22        | 5.23%   |
| Unknown | 11        | 2.61%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 61        | 14.59%  |
| Unknown                              | 57        | 13.64%  |
| Lenovo                               | 36        | 8.61%   |
| Hewlett-Packard                      | 32        | 7.66%   |
| Dell                                 | 29        | 6.94%   |
| Intel                                | 23        | 5.5%    |
| Gigabyte Technology                  | 13        | 3.11%   |
| PC Engines                           | 11        | 2.63%   |
| MSI                                  | 11        | 2.63%   |
| ASRock                               | 11        | 2.63%   |
| Protectli                            | 10        | 2.39%   |
| Supermicro                           | 9         | 2.15%   |
| Fujitsu                              | 9         | 2.15%   |
| Acer                                 | 9         | 2.15%   |
| Apple                                | 8         | 1.91%   |
| AMI                                  | 8         | 1.91%   |
| BESSTAR Tech                         | 6         | 1.44%   |
| AZW                                  | 5         | 1.2%    |
| YANYU                                | 3         | 0.72%   |
| Toshiba                              | 3         | 0.72%   |
| Sophos                               | 3         | 0.72%   |
| Samsung Electronics                  | 3         | 0.72%   |
| Intel(R) Client Systems              | 3         | 0.72%   |
| Deciso                               | 3         | 0.72%   |
| ZOTAC                                | 2         | 0.48%   |
| Techvision                           | 2         | 0.48%   |
| SJRC                                 | 2         | 0.48%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.48%   |
| Pegatron                             | 2         | 0.48%   |
| NF692                                | 2         | 0.48%   |
| MW                                   | 2         | 0.48%   |
| LG Electronics                       | 2         | 0.48%   |
| IceWhale Technology                  | 2         | 0.48%   |
| eMachines                            | 2         | 0.48%   |
| CWWK                                 | 2         | 0.48%   |
| YENTEK                               | 1         | 0.24%   |
| TUXEDO                               | 1         | 0.24%   |
| TULPAR                               | 1         | 0.24%   |
| T-bao                                | 1         | 0.24%   |
| Sun Microsystems                     | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 58        | 13.88%  |
| PC Engines APU2                                   | 7         | 1.67%   |
| Supermicro Super Server                           | 6         | 1.44%   |
| ASUS PRIME B650-PLUS                              | 4         | 0.96%   |
| AMI Aptio CRB                                     | 4         | 0.96%   |
| Protectli VP2420                                  | 3         | 0.72%   |
| Intel Q3XXG4-P V1.0                               | 3         | 0.72%   |
| Fujitsu FUTRO S920                                | 3         | 0.72%   |
| Dell Latitude E7250                               | 3         | 0.72%   |
| BESSTAR Tech N40                                  | 3         | 0.72%   |
| ASUS PRIME H410M-A                                | 3         | 0.72%   |
| Techvision TVI7309X                               | 2         | 0.48%   |
| Sophos UTM                                        | 2         | 0.48%   |
| SJRC ADLN-6L                                      | 2         | 0.48%   |
| Shenzhen Meigao Electronic Equipment Venus Series | 2         | 0.48%   |
| Protectli V1410                                   | 2         | 0.48%   |
| Protectli FW4B                                    | 2         | 0.48%   |
| PC Engines apu4                                   | 2         | 0.48%   |
| NF692 1.0                                         | 2         | 0.48%   |
| MW GMLK-2_5G4L                                    | 2         | 0.48%   |
| MSI MS-7D16                                       | 2         | 0.48%   |
| MSI MS-7B86                                       | 2         | 0.48%   |
| Lenovo ThinkCentre M83 10AHS35Q00                 | 2         | 0.48%   |
| Intel NCB-4210WG                                  | 2         | 0.48%   |
| Intel Jasper Lake Client Platform                 | 2         | 0.48%   |
| HP t620 PLUS Quad Core TC                         | 2         | 0.48%   |
| HP Laptop 15-da0xxx                               | 2         | 0.48%   |
| Gigabyte X570 AORUS ELITE                         | 2         | 0.48%   |
| Gigabyte A520M S2H                                | 2         | 0.48%   |
| Dell PowerEdge R300                               | 2         | 0.48%   |
| Dell OptiPlex 3020                                | 2         | 0.48%   |
| CWWK CW-ADLN-6L                                   | 2         | 0.48%   |
| AZW U59                                           | 2         | 0.48%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA            | 2         | 0.48%   |
| ASUS P8Z77-V LX                                   | 2         | 0.48%   |
| ASUS MINIPC PN42                                  | 2         | 0.48%   |
| ASUS M4A88TD-V EVO/USB3                           | 2         | 0.48%   |
| ASUS IP4BL-ME                                     | 2         | 0.48%   |
| ASUS All Series                                   | 2         | 0.48%   |
| Apple MacBook4,1                                  | 2         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 58        | 13.88%  |
| Lenovo ThinkPad                            | 21        | 5.02%   |
| ASUS PRIME                                 | 14        | 3.35%   |
| Lenovo ThinkCentre                         | 10        | 2.39%   |
| Dell PowerEdge                             | 8         | 1.91%   |
| PC Engines APU2                            | 7         | 1.67%   |
| Supermicro Super                           | 6         | 1.44%   |
| Dell OptiPlex                              | 6         | 1.44%   |
| Dell Latitude                              | 6         | 1.44%   |
| HP ProLiant                                | 5         | 1.2%    |
| HP ProDesk                                 | 5         | 1.2%    |
| HP Compaq                                  | 5         | 1.2%    |
| Fujitsu FUTRO                              | 4         | 0.96%   |
| Dell Precision                             | 4         | 0.96%   |
| AMI Aptio                                  | 4         | 0.96%   |
| Acer Aspire                                | 4         | 0.96%   |
| Protectli VP2420                           | 3         | 0.72%   |
| Intel Q3XXG4-P                             | 3         | 0.72%   |
| HP EliteDesk                               | 3         | 0.72%   |
| Gigabyte X570                              | 3         | 0.72%   |
| Fujitsu ESPRIMO                            | 3         | 0.72%   |
| BESSTAR Tech N40                           | 3         | 0.72%   |
| ASUS VivoBook                              | 3         | 0.72%   |
| ASUS P8Z77-V                               | 3         | 0.72%   |
| Techvision TVI7309X                        | 2         | 0.48%   |
| Sophos UTM                                 | 2         | 0.48%   |
| SJRC ADLN-6L                               | 2         | 0.48%   |
| Shenzhen Meigao Electronic Equipment Venus | 2         | 0.48%   |
| Protectli V1410                            | 2         | 0.48%   |
| Protectli FW4B                             | 2         | 0.48%   |
| PC Engines apu4                            | 2         | 0.48%   |
| NF692 1.0                                  | 2         | 0.48%   |
| MW GMLK-2                                  | 2         | 0.48%   |
| MSI MS-7D16                                | 2         | 0.48%   |
| MSI MS-7B86                                | 2         | 0.48%   |
| Intel NUC5i5RYB                            | 2         | 0.48%   |
| Intel NCB-4210WG                           | 2         | 0.48%   |
| Intel Jasper                               | 2         | 0.48%   |
| IceWhale ZimaBoard                         | 2         | 0.48%   |
| HP t620                                    | 2         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2023    | 40        | 9.57%   |
| 2014    | 34        | 8.13%   |
| 2021    | 33        | 7.89%   |
| 2022    | 30        | 7.18%   |
| 2016    | 30        | 7.18%   |
| 2018    | 26        | 6.22%   |
| 2019    | 25        | 5.98%   |
| 2020    | 24        | 5.74%   |
| 2024    | 23        | 5.5%    |
| 2010    | 22        | 5.26%   |
| 2013    | 21        | 5.02%   |
| 2012    | 20        | 4.78%   |
| 2011    | 20        | 4.78%   |
| 2017    | 17        | 4.07%   |
| 2009    | 12        | 2.87%   |
| 2015    | 11        | 2.63%   |
| 2008    | 11        | 2.63%   |
| 2025    | 8         | 1.91%   |
| Unknown | 5         | 1.2%    |
| 2007    | 3         | 0.72%   |
| 2005    | 2         | 0.48%   |
| 2006    | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 259       | 61.96%  |
| Notebook       | 100       | 23.92%  |
| Mini pc        | 30        | 7.18%   |
| Server         | 20        | 4.78%   |
| Firewall       | 3         | 0.72%   |
| All in one     | 3         | 0.72%   |
| System on chip | 2         | 0.48%   |
| Tablet         | 1         | 0.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 406       | 96.9%   |
| Yes  | 13        | 3.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 170       | 39.91%  |
| 4.01-8.0    | 90        | 21.13%  |
| 16.01-24.0  | 84        | 19.72%  |
| 32.01-64.0  | 37        | 8.69%   |
| 2.01-3.0    | 22        | 5.16%   |
| 64.01-256.0 | 9         | 2.11%   |
| 3.01-4.0    | 5         | 1.17%   |
| 24.01-32.0  | 4         | 0.94%   |
| 0.51-1.0    | 3         | 0.7%    |
| 0.01-0.5    | 2         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 237       | 55.5%   |
| 0.51-1.0   | 123       | 28.81%  |
| 1.01-2.0   | 35        | 8.2%    |
| Unknown    | 11        | 2.58%   |
| 4.01-8.0   | 9         | 2.11%   |
| 2.01-3.0   | 9         | 2.11%   |
| 3.01-4.0   | 1         | 0.23%   |
| 24.01-32.0 | 1         | 0.23%   |
| 8.01-16.0  | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 267       | 62.38%  |
| 0      | 75        | 17.52%  |
| 2      | 56        | 13.08%  |
| 3      | 12        | 2.8%    |
| 4      | 10        | 2.34%   |
| 7      | 3         | 0.7%    |
| 6      | 2         | 0.47%   |
| 10     | 1         | 0.23%   |
| 9      | 1         | 0.23%   |
| 5      | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 326       | 77.62%  |
| Yes       | 94        | 22.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 399       | 95.45%  |
| No        | 19        | 4.55%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 255       | 60.71%  |
| Yes       | 165       | 39.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 300       | 71.09%  |
| Yes       | 122       | 28.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Italy   | 418       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Milan                 | 71        | 14.12%  |
| Rome                  | 54        | 10.74%  |
| Turin                 | 16        | 3.18%   |
| Bologna               | 14        | 2.78%   |
| Naples                | 9         | 1.79%   |
| Trieste               | 8         | 1.59%   |
| Brescia               | 7         | 1.39%   |
| Padova                | 6         | 1.19%   |
| Milano                | 6         | 1.19%   |
| Palermo               | 5         | 0.99%   |
| Monza                 | 5         | 0.99%   |
| Arezzo                | 5         | 0.99%   |
| Verona                | 4         | 0.8%    |
| Rho                   | 4         | 0.8%    |
| Genoa                 | 4         | 0.8%    |
| Bari                  | 4         | 0.8%    |
| Venice                | 3         | 0.6%    |
| Treviso               | 3         | 0.6%    |
| Sesto San Giovanni    | 3         | 0.6%    |
| Reggio Emilia         | 3         | 0.6%    |
| Pistoia               | 3         | 0.6%    |
| Momo                  | 3         | 0.6%    |
| Catania               | 3         | 0.6%    |
| Bergamo               | 3         | 0.6%    |
| Turrivalignani        | 2         | 0.4%    |
| Taviano               | 2         | 0.4%    |
| Somma Vesuviana       | 2         | 0.4%    |
| Silea                 | 2         | 0.4%    |
| Scandicci             | 2         | 0.4%    |
| Sasso Marconi         | 2         | 0.4%    |
| San Giustino Valdarno | 2         | 0.4%    |
| San Giuliano Terme    | 2         | 0.4%    |
| Rosignano Marittimo   | 2         | 0.4%    |
| Reggio Calabria       | 2         | 0.4%    |
| Ravenna               | 2         | 0.4%    |
| Ponte San Pietro      | 2         | 0.4%    |
| Pavia                 | 2         | 0.4%    |
| Parma                 | 2         | 0.4%    |
| Oulx                  | 2         | 0.4%    |
| Novara                | 2         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 62        | 85     | 14%     |
| WDC                 | 44        | 85     | 9.93%   |
| Seagate             | 44        | 84     | 9.93%   |
| Kingston            | 38        | 50     | 8.58%   |
| Crucial             | 38        | 60     | 8.58%   |
| Toshiba             | 28        | 54     | 6.32%   |
| Transcend           | 26        | 43     | 5.87%   |
| SanDisk             | 14        | 15     | 3.16%   |
| China               | 11        | 24     | 2.48%   |
| NVMe                | 10        | 11     | 2.26%   |
| Intel               | 8         | 10     | 1.81%   |
| Hoodisk             | 8         | 12     | 1.81%   |
| Hitachi             | 8         | 10     | 1.81%   |
| SPCC                | 6         | 9      | 1.35%   |
| Micron Technology   | 5         | 5      | 1.13%   |
| Maxtor              | 5         | 5      | 1.13%   |
| FORESEE             | 5         | 8      | 1.13%   |
| PNY                 | 4         | 8      | 0.9%    |
| OCZ                 | 4         | 4      | 0.9%    |
| Innodisk            | 4         | 6      | 0.9%    |
| HGST                | 4         | 5      | 0.9%    |
| Emtec               | 4         | 7      | 0.9%    |
| SK hynix            | 3         | 3      | 0.68%   |
| Silicon Motion      | 3         | 4      | 0.68%   |
| KingSpec            | 3         | 4      | 0.68%   |
| Dogfish             | 3         | 3      | 0.68%   |
| Corsair             | 3         | 4      | 0.68%   |
| BAITITON            | 3         | 3      | 0.68%   |
| A-DATA Technology   | 3         | 4      | 0.68%   |
| Protectli           | 2         | 5      | 0.45%   |
| Phison              | 2         | 2      | 0.45%   |
| Pccooler            | 2         | 4      | 0.45%   |
| LITEON              | 2         | 3      | 0.45%   |
| Lexar               | 2         | 2      | 0.45%   |
| Leven               | 2         | 2      | 0.45%   |
| Intenso             | 2         | 2      | 0.45%   |
| Indilinx            | 2         | 2      | 0.45%   |
| Apple               | 2         | 2      | 0.45%   |
| VICKTER             | 1         | 1      | 0.23%   |
| VICK                | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB   | 11        | 2.32%   |
| Samsung SSD 860 EVO 500GB      | 6         | 1.27%   |
| Samsung SSD 860 EVO 250GB      | 6         | 1.27%   |
| Samsung SSD 850 EVO 250GB      | 6         | 1.27%   |
| Kingston SA400S37120G 120GB    | 6         | 1.27%   |
| Samsung SSD 990 PRO 1TB        | 5         | 1.05%   |
| NVMe Samsung SSD 980 1TB       | 5         | 1.05%   |
| Transcend TS64GSSD370 64GB     | 4         | 0.84%   |
| Samsung SSD 870 EVO 250GB      | 4         | 0.84%   |
| Kingston SA400S37240G 240GB    | 4         | 0.84%   |
| Crucial CT500MX500SSD1 500GB   | 4         | 0.84%   |
| Crucial CT120BX500SSD1 120GB   | 4         | 0.84%   |
| Transcend TS256GSSD230S 256GB  | 3         | 0.63%   |
| Transcend TS128GMSA230S 128GB  | 3         | 0.63%   |
| Toshiba MQ01ABD100 1TB         | 3         | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB | 3         | 0.63%   |
| Samsung SSD 850 EVO 500GB      | 3         | 0.63%   |
| Kingston SV300S37A120G 120GB   | 3         | 0.63%   |
| Kingston SEDC500M480G 480GB    | 3         | 0.63%   |
| Hoodisk SSD 256GB              | 3         | 0.63%   |
| Hoodisk SSD 128GB              | 3         | 0.63%   |
| FORESEE 64GB SSD               | 3         | 0.63%   |
| Emtec X150 120GB               | 3         | 0.63%   |
| Crucial CT250MX500SSD1 250GB   | 3         | 0.63%   |
| BAITITON BT58SSD08M 128GB      | 3         | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB   | 2         | 0.42%   |
| WDC WD6400AAKS-65A7B0 640GB    | 2         | 0.42%   |
| WDC WD5000AAKX-75U6AA0 500GB   | 2         | 0.42%   |
| WDC WD5000AAKX-00ERMA0 500GB   | 2         | 0.42%   |
| WDC WD5000AAKS-22V1A0 500GB    | 2         | 0.42%   |
| Transcend TS64GMSA370 64GB     | 2         | 0.42%   |
| Transcend TS256GMTS430S 256GB  | 2         | 0.42%   |
| Transcend TS16GMSA370 16GB     | 2         | 0.42%   |
| Toshiba Q300 240GB             | 2         | 0.42%   |
| Toshiba MQ04ABF100 1TB         | 2         | 0.42%   |
| Toshiba HDWG440 4TB            | 2         | 0.42%   |
| Toshiba HDWD110 1TB            | 2         | 0.42%   |
| Toshiba DT01ACA100 1TB         | 2         | 0.42%   |
| Toshiba DT01ACA050 500GB       | 2         | 0.42%   |
| SPCC Solid State Disk 256GB    | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 84     | 33.85%  |
| WDC                 | 35        | 73     | 26.92%  |
| Toshiba             | 24        | 45     | 18.46%  |
| Hitachi             | 8         | 10     | 6.15%   |
| Samsung Electronics | 5         | 5      | 3.85%   |
| Maxtor              | 5         | 5      | 3.85%   |
| HGST                | 4         | 5      | 3.08%   |
| NVMe                | 2         | 3      | 1.54%   |
| HPE                 | 1         | 2      | 0.77%   |
| Hewlett-Packard     | 1         | 2      | 0.77%   |
| Fujitsu             | 1         | 1      | 0.77%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 65     | 16.43%  |
| Crucial             | 35        | 53     | 12.5%   |
| Kingston            | 30        | 40     | 10.71%  |
| Transcend           | 24        | 41     | 8.57%   |
| SanDisk             | 14        | 15     | 5%      |
| China               | 11        | 24     | 3.93%   |
| WDC                 | 8         | 10     | 2.86%   |
| NVMe                | 8         | 8      | 2.86%   |
| Hoodisk             | 8         | 12     | 2.86%   |
| Intel               | 7         | 9      | 2.5%    |
| SPCC                | 5         | 8      | 1.79%   |
| FORESEE             | 5         | 8      | 1.79%   |
| Toshiba             | 4         | 9      | 1.43%   |
| PNY                 | 4         | 8      | 1.43%   |
| OCZ                 | 4         | 4      | 1.43%   |
| Micron Technology   | 4         | 4      | 1.43%   |
| Innodisk            | 4         | 6      | 1.43%   |
| Emtec               | 4         | 7      | 1.43%   |
| SK hynix            | 3         | 3      | 1.07%   |
| KingSpec            | 3         | 4      | 1.07%   |
| Dogfish             | 3         | 3      | 1.07%   |
| Corsair             | 3         | 4      | 1.07%   |
| BAITITON            | 3         | 3      | 1.07%   |
| A-DATA Technology   | 3         | 4      | 1.07%   |
| Protectli           | 2         | 5      | 0.71%   |
| Phison              | 2         | 2      | 0.71%   |
| Pccooler            | 2         | 4      | 0.71%   |
| LITEON              | 2         | 3      | 0.71%   |
| Lexar               | 2         | 2      | 0.71%   |
| Leven               | 2         | 2      | 0.71%   |
| Intenso             | 2         | 2      | 0.71%   |
| Indilinx            | 2         | 2      | 0.71%   |
| Apple               | 2         | 2      | 0.71%   |
| VICKTER             | 1         | 1      | 0.36%   |
| VICK                | 1         | 1      | 0.36%   |
| Verbatim            | 1         | 1      | 0.36%   |
| T-FORCE             | 1         | 1      | 0.36%   |
| Silicon             | 1         | 1      | 0.36%   |
| ShiJi               | 1         | 1      | 0.36%   |
| S3+                 | 1         | 2      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 246       | 400    | 63.4%   |
| HDD  | 105       | 235    | 27.06%  |
| NVMe | 37        | 47     | 9.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 320       | 635    | 89.64%  |
| NVMe | 37        | 47     | 10.36%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 271       | 464    | 74.86%  |
| 0.51-1.0   | 59        | 108    | 16.3%   |
| 1.01-2.0   | 16        | 20     | 4.42%   |
| 3.01-4.0   | 9         | 19     | 2.49%   |
| 4.01-10.0  | 4         | 11     | 1.1%    |
| 2.01-3.0   | 2         | 5      | 0.55%   |
| 10.01-20.0 | 1         | 8      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 164       | 38.05%  |
| 1-20           | 86        | 19.95%  |
| 251-500        | 79        | 18.33%  |
| 51-100         | 33        | 7.66%   |
| 21-50          | 31        | 7.19%   |
| 501-1000       | 29        | 6.73%   |
| More than 3000 | 5         | 1.16%   |
| 1001-2000      | 3         | 0.7%    |
| Unknown        | 1         | 0.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 390       | 90.07%  |
| 21-50          | 25        | 5.77%   |
| 51-100         | 8         | 1.85%   |
| 101-250        | 4         | 0.92%   |
| More than 3000 | 2         | 0.46%   |
| 501-1000       | 2         | 0.46%   |
| 1001-2000      | 1         | 0.23%   |
| Unknown        | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB            | 2         | 3      | 3.13%   |
| WDC WD5000AAKS-22V1A0 500GB             | 2         | 2      | 3.13%   |
| Seagate ST320LT007-9ZV142 320GB         | 2         | 2      | 3.13%   |
| OCZ VERTEX3 120GB                       | 2         | 2      | 3.13%   |
| Maxtor 6E040L0 40GB                     | 2         | 2      | 3.13%   |
| Intel SSDSC2BF180A4L 180GB              | 2         | 2      | 3.13%   |
| BAITITON BT58SSD08M 128GB               | 2         | 2      | 3.13%   |
| WDC WD800JD-75MSA3 80GB                 | 1         | 1      | 1.56%   |
| WDC WD6400AAKS-65A7B0 640GB             | 1         | 1      | 1.56%   |
| WDC WD5000AAKS-00E4A0 500GB             | 1         | 1      | 1.56%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 1      | 1.56%   |
| WDC WD20EVDS-63T3B0 2TB                 | 1         | 1      | 1.56%   |
| WDC WD2002FYPS-01U1B1 2TB               | 1         | 1      | 1.56%   |
| WDC WD10EZEX-60M2NA0 1TB                | 1         | 1      | 1.56%   |
| WDC WD1000DHTZ-04N21V1 1TB              | 1         | 2      | 1.56%   |
| Transcend TS128GMSA230S 128GB           | 1         | 2      | 1.56%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 1.56%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 1.56%   |
| Toshiba MK5065GSX 500GB                 | 1         | 1      | 1.56%   |
| Toshiba MK3259GSXP 320GB                | 1         | 1      | 1.56%   |
| SK hynix SC313 HFS256G32TNF-N3A0A 256GB | 1         | 1      | 1.56%   |
| SK hynix SC210 mSATA 256GB              | 1         | 1      | 1.56%   |
| Seagate ST9750420AS 752GB               | 1         | 1      | 1.56%   |
| Seagate ST9500325AS 500GB               | 1         | 1      | 1.56%   |
| Seagate ST9320423AS 320GB               | 1         | 1      | 1.56%   |
| Seagate ST9160821AS 160GB               | 1         | 1      | 1.56%   |
| Seagate ST750LM022 HN-M750MBB 752GB     | 1         | 1      | 1.56%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1      | 1.56%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1      | 1.56%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 7      | 1.56%   |
| Seagate ST4000LM024-2AN17V 4TB          | 1         | 1      | 1.56%   |
| Seagate ST31500341AS 1.5TB              | 1         | 1      | 1.56%   |
| Seagate ST31000524AS 1TB                | 1         | 1      | 1.56%   |
| SanDisk SSD PLUS 1000GB                 | 1         | 1      | 1.56%   |
| SanDisk SDSSDP064G 64GB                 | 1         | 1      | 1.56%   |
| SanDisk SD9SN8W-128G-1006 128GB         | 1         | 1      | 1.56%   |
| Samsung Electronics SSD 870 EVO 500GB   | 1         | 1      | 1.56%   |
| Samsung Electronics HM501II 500GB       | 1         | 1      | 1.56%   |
| Samsung Electronics HM321HI 320GB       | 1         | 1      | 1.56%   |
| Netac SSD 256GB                         | 1         | 1      | 1.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 19     | 20.31%  |
| WDC                 | 12        | 14     | 18.75%  |
| Toshiba             | 4         | 4      | 6.25%   |
| SanDisk             | 3         | 3      | 4.69%   |
| Samsung Electronics | 3         | 3      | 4.69%   |
| Maxtor              | 3         | 3      | 4.69%   |
| Hitachi             | 3         | 5      | 4.69%   |
| HGST                | 3         | 4      | 4.69%   |
| China               | 3         | 3      | 4.69%   |
| SK hynix            | 2         | 2      | 3.13%   |
| OCZ                 | 2         | 2      | 3.13%   |
| Intel               | 2         | 2      | 3.13%   |
| Crucial             | 2         | 4      | 3.13%   |
| BAITITON            | 2         | 2      | 3.13%   |
| Transcend           | 1         | 2      | 1.56%   |
| Netac               | 1         | 1      | 1.56%   |
| Micron Technology   | 1         | 1      | 1.56%   |
| LITEON              | 1         | 2      | 1.56%   |
| Kingston            | 1         | 1      | 1.56%   |
| Corsair             | 1         | 1      | 1.56%   |
| A-DATA Technology   | 1         | 1      | 1.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 19     | 32.5%   |
| WDC                 | 12        | 14     | 30%     |
| Toshiba             | 4         | 4      | 10%     |
| Maxtor              | 3         | 3      | 7.5%    |
| Hitachi             | 3         | 5      | 7.5%    |
| HGST                | 3         | 4      | 7.5%    |
| Samsung Electronics | 2         | 2      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 51     | 61.67%  |
| SSD  | 23        | 28     | 38.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Crucial CT500P3SSD8 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Crucial | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 289       | 562    | 77.69%  |
| Malfunc  | 60        | 79     | 16.13%  |
| Detected | 22        | 40     | 5.91%   |
| Failed   | 1         | 1      | 0.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 314       | 61.93%  |
| AMD                                     | 64        | 12.62%  |
| Samsung Electronics                     | 31        | 6.11%   |
| Kingston Technology Company             | 14        | 2.76%   |
| Phison Electronics                      | 7         | 1.38%   |
| Micron/Crucial Technology               | 7         | 1.38%   |
| MAXIO Technology (Hangzhou)             | 7         | 1.38%   |
| Silicon Motion                          | 6         | 1.18%   |
| SanDisk                                 | 6         | 1.18%   |
| ASMedia Technology                      | 6         | 1.18%   |
| Marvell Technology Group                | 5         | 0.99%   |
| Broadcom / LSI                          | 5         | 0.99%   |
| Micron Technology                       | 4         | 0.79%   |
| Transcend                               | 3         | 0.59%   |
| Nvidia                                  | 3         | 0.59%   |
| VIA Technologies                        | 2         | 0.39%   |
| ULi Electronics                         | 2         | 0.39%   |
| SK hynix                                | 2         | 0.39%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.39%   |
| JMicron Technology                      | 2         | 0.39%   |
| Adaptec                                 | 2         | 0.39%   |
| Yangtze Memory Technologies             | 1         | 0.2%    |
| Union Memory (Shenzhen)                 | 1         | 0.2%    |
| TenaFe                                  | 1         | 0.2%    |
| Silicon Image                           | 1         | 0.2%    |
| Shenzhen Unionmemory Information System | 1         | 0.2%    |
| Shenzhen Longsys Electronics            | 1         | 0.2%    |
| Realtek Semiconductor                   | 1         | 0.2%    |
| KIOXIA                                  | 1         | 0.2%    |
| Integrated Technology Express           | 1         | 0.2%    |
| Hosin Global Electronics                | 1         | 0.2%    |
| Compaq Computer                         | 1         | 0.2%    |
| Biwin Storage Technology                | 1         | 0.2%    |
| Unknown                                 | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 36        | 6.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 26        | 4.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 21        | 3.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 3.01%   |
| Intel Alder Lake-N SATA AHCI Controller                                          | 17        | 3.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 16        | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 14        | 2.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 2.3%    |
| Intel Jasper Lake SATA AHCI Controller                                           | 12        | 2.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 12        | 2.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 1.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 10        | 1.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 1.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 9         | 1.59%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 9         | 1.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 9         | 1.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 1.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 8         | 1.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 8         | 1.42%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 1.42%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                      | 7         | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 1.24%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 6         | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 1.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6         | 1.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 1.06%   |
| AMD 600 Series Chipset SATA Controller                                           | 6         | 1.06%   |
| AMD 400 Series Chipset SATA Controller                                           | 6         | 1.06%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 5         | 0.88%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 5         | 0.88%   |
| Intel Elkhart Lake SATA AHCI                                                     | 5         | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 0.88%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 5         | 0.88%   |
| AMD 500 Series Chipset SATA Controller                                           | 5         | 0.88%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 0.71%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 0.71%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 4         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 339       | 66.34%  |
| NVMe | 97        | 18.98%  |
| IDE  | 54        | 10.57%  |
| RAID | 16        | 3.13%   |
| SCSI | 3         | 0.59%   |
| SAS  | 2         | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 344       | 82.1%   |
| AMD                | 69        | 16.47%  |
| SUNW,UltraAX-i2    | 1         | 0.24%   |
| SUNW,Sun-Blade-100 | 1         | 0.24%   |
| Broadcom           | 1         | 0.24%   |
| Arm                | 1         | 0.24%   |
| 11th               | 1         | 0.24%   |
| Unknown            | 1         | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel N100                                    | 14        | 3.33%   |
| Intel Celeron N5105 @ 2.00GHz                 | 11        | 2.61%   |
| AMD GX-412TC SOC                              | 10        | 2.38%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 9         | 2.14%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 9         | 2.14%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 5         | 1.19%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 5         | 1.19%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 4         | 0.95%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.95%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.95%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 0.95%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.95%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 0.95%   |
| Intel Celeron J6412 @ 2.00GHz                 | 4         | 0.95%   |
| Intel Xeon CPU X5650 @ 2.67GHz                | 3         | 0.71%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz      | 3         | 0.71%   |
| Intel Pentium Gold 8505                       | 3         | 0.71%   |
| Intel N95                                     | 3         | 0.71%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 0.71%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 3         | 0.71%   |
| Intel Core i5-3470S CPU @ 2.90GHz             | 3         | 0.71%   |
| Intel Core i3-N305                            | 3         | 0.71%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 3         | 0.71%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 3         | 0.71%   |
| Intel Celeron CPU J3160 @ 1.60GHz             | 3         | 0.71%   |
| Intel Atom CPU E3826 @ 1.46GHz                | 3         | 0.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.71%   |
| AMD Phenom II X4 965 Processor                | 3         | 0.71%   |
| AMD GX-415GA SOC with Radeon HD Graphics      | 3         | 0.71%   |
| Intel Xeon CPU E3113 @ 3.00GHz                | 2         | 0.48%   |
| Intel Xeon                                    | 2         | 0.48%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 2         | 0.48%   |
| Intel N150                                    | 2         | 0.48%   |
| Intel CPU Version                             | 2         | 0.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.48%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.48%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 2         | 0.48%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.48%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2         | 0.48%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 72        | 17.1%   |
| Intel Core i5           | 69        | 16.39%  |
| Other                   | 43        | 10.21%  |
| Intel Xeon              | 35        | 8.31%   |
| Intel Core i7           | 30        | 7.13%   |
| Intel Core i3           | 29        | 6.89%   |
| Intel Atom              | 25        | 5.94%   |
| AMD GX                  | 17        | 4.04%   |
| Intel Pentium           | 14        | 3.33%   |
| AMD Ryzen 5             | 13        | 3.09%   |
| Intel Core 2 Duo        | 12        | 2.85%   |
| AMD Ryzen 7             | 8         | 1.9%    |
| AMD Ryzen 9             | 6         | 1.43%   |
| Intel Pentium Dual-Core | 5         | 1.19%   |
| Intel Pentium Silver    | 3         | 0.71%   |
| Intel Pentium Gold      | 3         | 0.71%   |
| Intel Pentium Dual      | 3         | 0.71%   |
| AMD Phenom II X4        | 3         | 0.71%   |
| AMD EPYC                | 3         | 0.71%   |
| Intel Core 2 Quad       | 2         | 0.48%   |
| AMD Ryzen Embedded      | 2         | 0.48%   |
| AMD A4                  | 2         | 0.48%   |
| Intel Xeon Silver       | 1         | 0.24%   |
| Intel Xeon Gold         | 1         | 0.24%   |
| Intel Pentium M         | 1         | 0.24%   |
| Intel Pentium 4         | 1         | 0.24%   |
| Intel Core 2 Extreme    | 1         | 0.24%   |
| Intel Core 2            | 1         | 0.24%   |
| Intel Core              | 1         | 0.24%   |
| Intel 686-class         | 1         | 0.24%   |
| AMD Turion II Neo       | 1         | 0.24%   |
| AMD Turion 64 X2 Mobile | 1         | 0.24%   |
| AMD Ryzen 7 PRO         | 1         | 0.24%   |
| AMD Ryzen 5 PRO         | 1         | 0.24%   |
| AMD Ryzen 3             | 1         | 0.24%   |
| AMD Opteron             | 1         | 0.24%   |
| AMD G                   | 1         | 0.24%   |
| AMD FX                  | 1         | 0.24%   |
| AMD E2                  | 1         | 0.24%   |
| AMD E1                  | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 176       | 41.51%  |
| 2       | 134       | 31.6%   |
| 8       | 28        | 6.6%    |
| Unknown | 26        | 6.13%   |
| 16      | 15        | 3.54%   |
| 12      | 14        | 3.3%    |
| 6       | 13        | 3.07%   |
| 1       | 8         | 1.89%   |
| 10      | 4         | 0.94%   |
| 32      | 3         | 0.71%   |
| 3       | 2         | 0.47%   |
| 24      | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 399       | 95.23%  |
| 2       | 11        | 2.63%   |
| Unknown | 9         | 2.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 244       | 57.55%  |
| 2       | 154       | 36.32%  |
| Unknown | 26        | 6.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 76        | 18.05%  |
| KabyLake      | 36        | 8.55%   |
| Haswell       | 31        | 7.36%   |
| Penryn        | 25        | 5.94%   |
| Silvermont    | 24        | 5.7%    |
| SandyBridge   | 23        | 5.46%   |
| Goldmont plus | 21        | 4.99%   |
| Skylake       | 20        | 4.75%   |
| IvyBridge     | 20        | 4.75%   |
| Broadwell     | 19        | 4.51%   |
| Bonnell       | 17        | 4.04%   |
| Puma          | 13        | 3.09%   |
| Westmere      | 12        | 2.85%   |
| Zen 3         | 9         | 2.14%   |
| Goldmont      | 9         | 2.14%   |
| Zen           | 8         | 1.9%    |
| CometLake     | 8         | 1.9%    |
| Zen+          | 7         | 1.66%   |
| Jaguar        | 7         | 1.66%   |
| Nehalem       | 6         | 1.43%   |
| K10           | 5         | 1.19%   |
| Core          | 5         | 1.19%   |
| Zen 2         | 4         | 0.95%   |
| TigerLake     | 4         | 0.95%   |
| NetBurst      | 2         | 0.48%   |
| K8 Hammer     | 2         | 0.48%   |
| K10 Llano     | 2         | 0.48%   |
| Bobcat        | 2         | 0.48%   |
| Piledriver    | 1         | 0.24%   |
| P6            | 1         | 0.24%   |
| IceLake       | 1         | 0.24%   |
| Bulldozer     | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 270       | 64.13%  |
| AMD                              | 76        | 18.05%  |
| Nvidia                           | 51        | 12.11%  |
| Matrox Electronics Systems       | 12        | 2.85%   |
| ASPEED Technology                | 11        | 2.61%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-N [UHD Graphics]                                                        | 20        | 4.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 18        | 4.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 3.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 3.71%   |
| Intel JasperLake [UHD Graphics]                                                          | 15        | 3.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 14        | 3.25%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 13        | 3.02%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 11        | 2.55%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 10        | 2.32%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 9         | 2.09%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 8         | 1.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.62%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 7         | 1.62%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.39%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 6         | 1.39%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 5         | 1.16%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 5         | 1.16%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 5         | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.16%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 5         | 1.16%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 5         | 1.16%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 1.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.93%   |
| Intel Broadwell-U GT3 [HD Graphics 6000]                                                 | 4         | 0.93%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 4         | 0.93%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4         | 0.93%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 0.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 0.93%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 0.93%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 0.7%    |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 3         | 0.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.7%    |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 3         | 0.7%    |
| Intel Kaby Lake-U GT1 [HD Graphics 610]                                                  | 3         | 0.7%    |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                                  | 3         | 0.7%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.7%    |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 3         | 0.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 231       | 55%     |
| 1 x AMD                | 65        | 15.48%  |
| 1 x Nvidia             | 31        | 7.38%   |
| Other                  | 22        | 5.24%   |
| 2 x Intel              | 20        | 4.76%   |
| Intel + Nvidia         | 16        | 3.81%   |
| 1 x Matrox             | 11        | 2.62%   |
| 1 x ASPEED             | 11        | 2.62%   |
| 2 x AMD                | 5         | 1.19%   |
| AMD + Nvidia           | 3         | 0.71%   |
| Intel + AMD            | 2         | 0.48%   |
| 2 x Intel + 1 x Nvidia | 1         | 0.24%   |
| 1 x SiS                | 1         | 0.24%   |
| AMD + Matrox           | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 362       | 85.78%  |
| Unknown     | 31        | 7.35%   |
| Proprietary | 29        | 6.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 365       | 86.9%   |
| 0.01-0.5   | 17        | 4.05%   |
| 1.01-2.0   | 13        | 3.1%    |
| 3.01-4.0   | 7         | 1.67%   |
| 0.51-1.0   | 6         | 1.43%   |
| 5.01-6.0   | 5         | 1.19%   |
| 7.01-8.0   | 4         | 0.95%   |
| 2.01-3.0   | 2         | 0.48%   |
| 8.01-16.0  | 1         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Philips                 | 26        | 16.99%  |
| AU Optronics            | 19        | 12.42%  |
| Samsung Electronics     | 18        | 11.76%  |
| LG Display              | 14        | 9.15%   |
| Hewlett-Packard         | 12        | 7.84%   |
| Chimei Innolux          | 9         | 5.88%   |
| BOE                     | 9         | 5.88%   |
| Acer                    | 7         | 4.58%   |
| Dell                    | 6         | 3.92%   |
| HannStar                | 4         | 2.61%   |
| Apple                   | 4         | 2.61%   |
| Iiyama                  | 3         | 1.96%   |
| Goldstar                | 3         | 1.96%   |
| Lenovo                  | 2         | 1.31%   |
| Eizo                    | 2         | 1.31%   |
| Ancor Communications    | 2         | 1.31%   |
| ___                     | 1         | 0.65%   |
| Sony                    | 1         | 0.65%   |
| Packard Bell            | 1         | 0.65%   |
| Orion                   | 1         | 0.65%   |
| MSI                     | 1         | 0.65%   |
| Mi                      | 1         | 0.65%   |
| LPL                     | 1         | 0.65%   |
| LG Philips              | 1         | 0.65%   |
| LG Electronics          | 1         | 0.65%   |
| HKC                     | 1         | 0.65%   |
| Fujitsu Siemens         | 1         | 0.65%   |
| Chi Mei Optoelectronics | 1         | 0.65%   |
| ASUSTek Computer        | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 21        | 13.73%  |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 3         | 1.96%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 3         | 1.96%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 3         | 1.96%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 2         | 1.31%   |
| Hewlett-Packard 32 Display HPN351A 1920x1080 700x390mm 31.5-inch      | 2         | 1.31%   |
| Hewlett-Packard 27w HPN3494 1920x1080 600x340mm 27.2-inch             | 2         | 1.31%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO2A3C 1366x768 310x170mm 13.9-inch         | 2         | 1.31%   |
| Acer V193W ACR0025 1440x900 400x250mm 18.6-inch                       | 2         | 1.31%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 0.65%   |
| Sony TV SNY5D01 1360x768                                              | 1         | 0.65%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                      | 1         | 0.65%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch     | 1         | 0.65%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x170mm 12.2-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 340x190mm 15.3-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM7032 1920x1080 700x390mm 31.5-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor B2430L 1920x1080                      | 1         | 0.65%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch              | 1         | 0.65%   |
| Philips PHL 278B1 PHL0949 3840x2160 600x340mm 27.2-inch               | 1         | 0.65%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 600x340mm 27.2-inch              | 1         | 0.65%   |
| Philips 22PFL3404D PHLD05D 1920x1080 640x360mm 28.9-inch              | 1         | 0.65%   |
| Philips 170S PHL082B 1280x1024 340x270mm 17.1-inch                    | 1         | 0.65%   |
| Packard Bell Viseo 193 Ws PKB008C 1440x900 410x260mm 19.1-inch        | 1         | 0.65%   |
| Orion LCD Monitor ORN1207 1920x1080                                   | 1         | 0.65%   |
| MSI G272QPF MSI3CD3 2560x1440 600x340mm 27.2-inch                     | 1         | 0.65%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                      | 1         | 0.65%   |
| LPL LCD Monitor 1680x1050                                             | 1         | 0.65%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 0.65%   |
| LG Electronics LCD Monitor E2360 1920x1080                            | 1         | 0.65%   |
| LG Display LCD Monitor LGD06AA 3840x2400 340x210mm 15.7-inch          | 1         | 0.65%   |
| LG Display LCD Monitor LGD0694 2560x1600 340x220mm 15.9-inch          | 1         | 0.65%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch          | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 74        | 50%     |
| 1366x768 (WXGA)    | 33        | 22.3%   |
| 1440x900 (WXGA+)   | 6         | 4.05%   |
| 1280x1024 (SXGA)   | 5         | 3.38%   |
| 1024x600           | 4         | 2.7%    |
| 3840x2160 (4K)     | 3         | 2.03%   |
| 2560x1440 (QHD)    | 3         | 2.03%   |
| 1920x1200 (WUXGA)  | 3         | 2.03%   |
| 1600x900 (HD+)     | 3         | 2.03%   |
| 1280x800 (WXGA)    | 3         | 2.03%   |
| 2560x1080          | 2         | 1.35%   |
| 3840x2400          | 1         | 0.68%   |
| 3440x1440          | 1         | 0.68%   |
| 2736x1824          | 1         | 0.68%   |
| 2560x1600          | 1         | 0.68%   |
| 2160x1440          | 1         | 0.68%   |
| 1680x1050 (WSXGA+) | 1         | 0.68%   |
| 1600x1200          | 1         | 0.68%   |
| 1360x768           | 1         | 0.68%   |
| 1024x768 (XGA)     | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 35        | 22.88%  |
| 21      | 25        | 16.34%  |
| 27      | 13        | 8.5%    |
| 13      | 13        | 8.5%    |
| Unknown | 12        | 7.84%   |
| 24      | 11        | 7.19%   |
| 12      | 10        | 6.54%   |
| 19      | 7         | 4.58%   |
| 23      | 5         | 3.27%   |
| 31      | 4         | 2.61%   |
| 10      | 4         | 2.61%   |
| 17      | 3         | 1.96%   |
| 34      | 2         | 1.31%   |
| 18      | 2         | 1.31%   |
| 14      | 2         | 1.31%   |
| 39      | 1         | 0.65%   |
| 28      | 1         | 0.65%   |
| 22      | 1         | 0.65%   |
| 20      | 1         | 0.65%   |
| 11      | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 31.13%  |
| 401-500     | 30        | 19.87%  |
| 501-600     | 26        | 17.22%  |
| 201-300     | 19        | 12.58%  |
| Unknown     | 12        | 7.95%   |
| 601-700     | 7         | 4.64%   |
| 351-400     | 7         | 4.64%   |
| 701-800     | 2         | 1.32%   |
| 901-1000    | 1         | 0.66%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 113       | 77.93%  |
| 16/10   | 14        | 9.66%   |
| Unknown | 5         | 3.45%   |
| 5/4     | 4         | 2.76%   |
| 3/2     | 4         | 2.76%   |
| 21/9    | 3         | 2.07%   |
| 4/3     | 2         | 1.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 36        | 24.16%  |
| 91-100         | 23        | 15.44%  |
| 81-90          | 13        | 8.72%   |
| 301-350        | 13        | 8.72%   |
| Unknown        | 12        | 8.05%   |
| 101-110        | 11        | 7.38%   |
| 61-70          | 10        | 6.71%   |
| 151-200        | 9         | 6.04%   |
| 351-500        | 7         | 4.7%    |
| 41-50          | 4         | 2.68%   |
| 251-300        | 3         | 2.01%   |
| 111-120        | 3         | 2.01%   |
| 121-130        | 2         | 1.34%   |
| 51-60          | 1         | 0.67%   |
| 141-150        | 1         | 0.67%   |
| 501-1000       | 1         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 54        | 36.24%  |
| 51-100        | 48        | 32.21%  |
| 121-160       | 28        | 18.79%  |
| Unknown       | 12        | 8.05%   |
| 161-240       | 5         | 3.36%   |
| More than 240 | 2         | 1.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 260       | 61.61%  |
| 1     | 157       | 37.2%   |
| 2     | 5         | 1.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 281       | 48.53%  |
| Realtek Semiconductor            | 152       | 26.25%  |
| Qualcomm Atheros                 | 47        | 8.12%   |
| Broadcom                         | 41        | 7.08%   |
| MediaTek                         | 6         | 1.04%   |
| Marvell Technology Group         | 5         | 0.86%   |
| Ralink Technology                | 4         | 0.69%   |
| Mellanox Technologies            | 3         | 0.52%   |
| AMD                              | 3         | 0.52%   |
| T & A Mobile Phones              | 2         | 0.35%   |
| Samsung Electronics              | 2         | 0.35%   |
| Ralink                           | 2         | 0.35%   |
| Nvidia                           | 2         | 0.35%   |
| JMicron Technology               | 2         | 0.35%   |
| Huawei Technologies              | 2         | 0.35%   |
| Edimax Technology                | 2         | 0.35%   |
| Davicom Semiconductor            | 2         | 0.35%   |
| D-Link System                    | 2         | 0.35%   |
| Xiaomi                           | 1         | 0.17%   |
| Sitecom Europe                   | 1         | 0.17%   |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |
| Oracle/SUN                       | 1         | 0.17%   |
| OPPO Electronics                 | 1         | 0.17%   |
| NetGear                          | 1         | 0.17%   |
| National Semiconductor           | 1         | 0.17%   |
| Motorola PCS                     | 1         | 0.17%   |
| Lenovo                           | 1         | 0.17%   |
| IMC Networks                     | 1         | 0.17%   |
| Hewlett-Packard                  | 1         | 0.17%   |
| Google                           | 1         | 0.17%   |
| Emulex                           | 1         | 0.17%   |
| Digital Equipment                | 1         | 0.17%   |
| Dell                             | 1         | 0.17%   |
| BUFFALO                          | 1         | 0.17%   |
| Aquantia                         | 1         | 0.17%   |
| Apple                            | 1         | 0.17%   |
| American Megatrends              | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 128       | 17.88%  |
| Intel Ethernet Controller I226-V                                              | 44        | 6.15%   |
| Intel I211 Gigabit Network Connection                                         | 40        | 5.59%   |
| Intel I210 Gigabit Network Connection                                         | 18        | 2.51%   |
| Intel 82574L Gigabit Network Connection                                       | 16        | 2.23%   |
| Intel I350 Gigabit Network Connection                                         | 14        | 1.96%   |
| Intel Ethernet Controller I225-V                                              | 14        | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                             | 12        | 1.68%   |
| Intel Wireless 7265                                                           | 11        | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 11        | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 8         | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 8         | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 8         | 1.12%   |
| Intel Wireless 8265 / 8275                                                    | 8         | 1.12%   |
| Intel Wireless 3165                                                           | 8         | 1.12%   |
| Intel 82583V Gigabit Network Connection                                       | 8         | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 7         | 0.98%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 7         | 0.98%   |
| Intel Ethernet Connection I217-LM                                             | 7         | 0.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6         | 0.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 6         | 0.84%   |
| Intel Ethernet Connection (3) I218-LM                                         | 6         | 0.84%   |
| Intel 82576 Gigabit Network Connection                                        | 6         | 0.84%   |
| Intel Wireless 8260                                                           | 5         | 0.7%    |
| Intel Ethernet Connection (4) I219-V                                          | 5         | 0.7%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 5         | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 4         | 0.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 4         | 0.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 4         | 0.56%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                                          | 4         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 0.56%   |
| Intel DH8900CC Null Device                                                    | 4         | 0.56%   |
| Intel Alder Lake-N PCH CNVi WiFi                                              | 4         | 0.56%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 0.56%   |
| Intel 82580 Gigabit Network Connection                                        | 4         | 0.56%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 0.56%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 4         | 0.56%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 4         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 75        | 42.37%  |
| Qualcomm Atheros         | 45        | 25.42%  |
| Realtek Semiconductor    | 22        | 12.43%  |
| Broadcom                 | 16        | 9.04%   |
| MediaTek                 | 5         | 2.82%   |
| Ralink Technology        | 4         | 2.26%   |
| Ralink                   | 2         | 1.13%   |
| Edimax Technology        | 2         | 1.13%   |
| Sitecom Europe           | 1         | 0.56%   |
| NetGear                  | 1         | 0.56%   |
| Marvell Technology Group | 1         | 0.56%   |
| IMC Networks             | 1         | 0.56%   |
| Dell                     | 1         | 0.56%   |
| BUFFALO                  | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 11        | 6.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 4.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 4.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 4.4%    |
| Intel Wireless 8265 / 8275                                              | 8         | 4.4%    |
| Intel Wireless 3165                                                     | 8         | 4.4%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.3%    |
| Intel Wireless 8260                                                     | 5         | 2.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.2%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 4         | 2.2%    |
| Intel Alder Lake-N PCH CNVi WiFi                                        | 4         | 2.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.2%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.65%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.65%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 3         | 1.65%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 3         | 1.65%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.1%    |
| Ralink RT5370 Wireless Adapter                                          | 2         | 1.1%    |
| Intel Wireless 7260                                                     | 2         | 1.1%    |
| Intel WiFi Link 5100                                                    | 2         | 1.1%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2         | 1.1%    |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.1%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.1%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.1%    |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 1.1%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.1%    |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.1%    |
| Sitecom Europe 802.11n WLAN Adapter                                     | 1         | 0.55%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.55%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 246       | 53.13%  |
| Realtek Semiconductor            | 147       | 31.75%  |
| Broadcom                         | 27        | 5.83%   |
| Qualcomm Atheros                 | 11        | 2.38%   |
| Marvell Technology Group         | 4         | 0.86%   |
| AMD                              | 3         | 0.65%   |
| T & A Mobile Phones              | 2         | 0.43%   |
| Samsung Electronics              | 2         | 0.43%   |
| Nvidia                           | 2         | 0.43%   |
| JMicron Technology               | 2         | 0.43%   |
| Davicom Semiconductor            | 2         | 0.43%   |
| D-Link System                    | 2         | 0.43%   |
| Xiaomi                           | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Oracle/SUN                       | 1         | 0.22%   |
| OPPO Electronics                 | 1         | 0.22%   |
| National Semiconductor           | 1         | 0.22%   |
| Motorola PCS                     | 1         | 0.22%   |
| MediaTek                         | 1         | 0.22%   |
| Lenovo                           | 1         | 0.22%   |
| Emulex                           | 1         | 0.22%   |
| Digital Equipment                | 1         | 0.22%   |
| Aquantia                         | 1         | 0.22%   |
| Apple                            | 1         | 0.22%   |
| American Megatrends              | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 128       | 24.52%  |
| Intel Ethernet Controller I226-V                                              | 44        | 8.43%   |
| Intel I211 Gigabit Network Connection                                         | 40        | 7.66%   |
| Intel I210 Gigabit Network Connection                                         | 18        | 3.45%   |
| Intel 82574L Gigabit Network Connection                                       | 16        | 3.07%   |
| Intel I350 Gigabit Network Connection                                         | 14        | 2.68%   |
| Intel Ethernet Controller I225-V                                              | 14        | 2.68%   |
| Realtek RTL8125 2.5GbE Controller                                             | 12        | 2.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 11        | 2.11%   |
| Intel 82583V Gigabit Network Connection                                       | 8         | 1.53%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 7         | 1.34%   |
| Intel Ethernet Connection I217-LM                                             | 7         | 1.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6         | 1.15%   |
| Intel Ethernet Connection (3) I218-LM                                         | 6         | 1.15%   |
| Intel 82576 Gigabit Network Connection                                        | 6         | 1.15%   |
| Intel Ethernet Connection (4) I219-V                                          | 5         | 0.96%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 5         | 0.96%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 0.77%   |
| Intel Ethernet Connection (7) I219-V                                          | 4         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 0.77%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 0.77%   |
| Intel 82580 Gigabit Network Connection                                        | 4         | 0.77%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 0.77%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 4         | 0.77%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 4         | 0.77%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 4         | 0.77%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 3         | 0.57%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 0.57%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 0.57%   |
| Intel 82575EB Gigabit Network Connection                                      | 3         | 0.57%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 3         | 0.57%   |
| AMD XGMAC 10GbE Controller                                                    | 3         | 0.57%   |
| T & A Mobile Phones ALCATEL RNDIS Interface                                   | 2         | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2         | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2         | 0.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 2         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 399       | 69.27%  |
| WiFi     | 165       | 28.65%  |
| Unknown  | 9         | 1.56%   |
| Modem    | 3         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 353       | 82.28%  |
| WiFi     | 76        | 17.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 141       | 33.25%  |
| 1     | 85        | 20.05%  |
| 4     | 68        | 16.04%  |
| 3     | 43        | 10.14%  |
| 6     | 33        | 7.78%   |
| 5     | 27        | 6.37%   |
| 8     | 8         | 1.89%   |
| 7     | 6         | 1.42%   |
| 10    | 4         | 0.94%   |
| 9     | 3         | 0.71%   |
| 0     | 3         | 0.71%   |
| 15    | 1         | 0.24%   |
| 14    | 1         | 0.24%   |
| 12    | 1         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 405       | 95.97%  |
| Yes  | 17        | 4.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 48.41%  |
| Realtek Semiconductor           | 11        | 8.73%   |
| IMC Networks                    | 10        | 7.94%   |
| Qualcomm Atheros Communications | 7         | 5.56%   |
| Broadcom                        | 7         | 5.56%   |
| Apple                           | 7         | 5.56%   |
| Cambridge Silicon Radio         | 6         | 4.76%   |
| Lite-On Technology              | 4         | 3.17%   |
| MediaTek                        | 3         | 2.38%   |
| Integrated System Solution      | 2         | 1.59%   |
| ASUSTek Computer                | 2         | 1.59%   |
| Toshiba                         | 1         | 0.79%   |
| Skylight Digital                | 1         | 0.79%   |
| Hewlett-Packard                 | 1         | 0.79%   |
| Foxconn / Hon Hai               | 1         | 0.79%   |
| Dell                            | 1         | 0.79%   |
| Belkin Components               | 1         | 0.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 30        | 23.81%  |
| Intel AX201 Bluetooth                                       | 14        | 11.11%  |
| Realtek Bluetooth Adapter                                   | 6         | 4.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 6         | 4.76%   |
| Intel AX211 Bluetooth                                       | 4         | 3.17%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 4         | 3.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 3         | 2.38%   |
| Intel AX200 Bluetooth                                       | 3         | 2.38%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.59%   |
| MediaTek Wireless_Device                                    | 2         | 1.59%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 2         | 1.59%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 1.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2         | 1.59%   |
| Intel AX210 Bluetooth                                       | 2         | 1.59%   |
| Integrated System Solution Bluetooth Device                 | 2         | 1.59%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 1.59%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.59%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 1.59%   |
| Apple Bluetooth Host Controller                             | 2         | 1.59%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 0.79%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 1         | 0.79%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.79%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.79%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.79%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.79%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1         | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.79%   |
| MediaTek RZ608 Bluetooth Adapter                            | 1         | 0.79%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.79%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 0.79%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.79%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS     | 1         | 0.79%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 0.79%   |
| IMC Networks Bluetooth module                               | 1         | 0.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 278       | 67.15%  |
| AMD                                          | 74        | 17.87%  |
| Nvidia                                       | 36        | 8.7%    |
| C-Media Electronics                          | 7         | 1.69%   |
| Zoran Co. Personal Media Division (Nogatech) | 4         | 0.97%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.48%   |
| Samson Technologies                          | 2         | 0.48%   |
| Logitech                                     | 2         | 0.48%   |
| KTMicro                                      | 2         | 0.48%   |
| ULi Electronics                              | 1         | 0.24%   |
| Texas Instruments                            | 1         | 0.24%   |
| Plantronics                                  | 1         | 0.24%   |
| Generalplus Technology                       | 1         | 0.24%   |
| Creative Labs                                | 1         | 0.24%   |
| Bose                                         | 1         | 0.24%   |
| Apogee Electronics                           | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 23        | 4.67%   |
| AMD Ryzen HD Audio Controller                                                                     | 22        | 4.46%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 4.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 20        | 4.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 3.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 3.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 3.45%   |
| Intel Jasper Lake HD Audio                                                                        | 15        | 3.04%   |
| Intel Broadwell-U Audio Controller                                                                | 14        | 2.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 2.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 2.43%   |
| AMD FCH Azalia Controller                                                                         | 11        | 2.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 2.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 2.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 1.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 9         | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 7         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.42%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 1.42%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 7         | 1.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.42%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 7         | 1.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.22%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.22%   |
| AMD Radeon High Definition Audio Controller                                                       | 6         | 1.22%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 5         | 1.01%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 5         | 1.01%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 4         | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 0.81%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 4         | 0.81%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 4         | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 92        | 21.55%  |
| SK hynix                     | 58        | 13.58%  |
| Kingston                     | 47        | 11.01%  |
| Unknown                      | 43        | 10.07%  |
| Crucial                      | 39        | 9.13%   |
| Micron Technology            | 36        | 8.43%   |
| Unknown                      | 20        | 4.68%   |
| Transcend                    | 12        | 2.81%   |
| Unknown (ABCD)               | 11        | 2.58%   |
| Corsair                      | 10        | 2.34%   |
| Nanya Technology             | 8         | 1.87%   |
| A-DATA Technology            | 7         | 1.64%   |
| Elpida                       | 6         | 1.41%   |
| Ramaxel Technology           | 5         | 1.17%   |
| SK_Hynix                     | 3         | 0.7%    |
| Apacer                       | 3         | 0.7%    |
| Unknown (AB)                 | 2         | 0.47%   |
| Kimtigo                      | 2         | 0.47%   |
| G.Skill                      | 2         | 0.47%   |
| Unknown (F301)               | 1         | 0.23%   |
| Unknown (89F8)               | 1         | 0.23%   |
| Unknown (0x0DD5)             | 1         | 0.23%   |
| Unknown (0x0C32)             | 1         | 0.23%   |
| Unknown (0x0B45)             | 1         | 0.23%   |
| Unknown (0B38)               | 1         | 0.23%   |
| Toshiba                      | 1         | 0.23%   |
| Patriot Memory (PDP Systems) | 1         | 0.23%   |
| Lexar Co Limited             | 1         | 0.23%   |
| KomputerBay                  | 1         | 0.23%   |
| Juhor                        | 1         | 0.23%   |
| Intersil                     | 1         | 0.23%   |
| HPE                          | 1         | 0.23%   |
| Hewlett-Packard              | 1         | 0.23%   |
| Heoriady                     | 1         | 0.23%   |
| ASint Technology             | 1         | 0.23%   |
| 48spaces                     | 1         | 0.23%   |
| 2C0C0843D7349CA2             | 1         | 0.23%   |
| 2C0C0843D7349C9D             | 1         | 0.23%   |
| 2C080815D82F5C7B             | 1         | 0.23%   |
| 2C0108214C359D20             | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Unknown                                                       | 20        | 4.36%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s  | 11        | 2.4%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                   | 6         | 1.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 6         | 1.31%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                    | 5         | 1.09%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 4         | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 4         | 0.87%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s                    | 3         | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                      | 3         | 0.65%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s           | 3         | 0.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3200MT/s         | 3         | 0.65%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s         | 3         | 0.65%   |
| Samsung RAM M425R1GB4BB0-CWMOD 8GB SODIMM DDR5 5600MT/s       | 3         | 0.65%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s           | 3         | 0.65%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s       | 3         | 0.65%   |
| Micron RAM 53D512M64D4RQ-046 8GB Row Of Chips LPDDR4 4800MT/s | 3         | 0.65%   |
| Kingston RAM 9965754-059.C00G 32GB DIMM DDR4 3200MT/s         | 3         | 0.65%   |
| Crucial RAM CT16G56C46S5.M8G1 16GB SODIMM DDR5 5600MT/s       | 3         | 0.65%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s       | 3         | 0.65%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                          | 2         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                   | 2         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                 | 2         | 0.44%   |
| Unknown RAM Module 1GB DIMM SDRAM                             | 2         | 0.44%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                      | 2         | 0.44%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s            | 2         | 0.44%   |
| Transcend RAM Module 4GB SODIMM DDR3 1600MT/s                 | 2         | 0.44%   |
| SK_Hynix RAM HMA81GS6AFR8N-VK 8GB SODIMM DDR4 2400MT/s        | 2         | 0.44%   |
| SK hynix RAM HYMP151P72CP4-Y5 4GB DIMM DDR2 667MT/s           | 2         | 0.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 2         | 0.44%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s          | 2         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 2         | 0.44%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s        | 2         | 0.44%   |
| SK hynix RAM HMT125U7BFR8C-H9 2GB DIMM DDR3 1333MT/s          | 2         | 0.44%   |
| SK hynix RAM HMAG56EXNSA051N 4GB SODIMM DDR4 3200MT/s         | 2         | 0.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s        | 2         | 0.44%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 2         | 0.44%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                     | 2         | 0.44%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR5 6400MT/s           | 2         | 0.44%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s         | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 159       | 42.4%   |
| DDR4    | 120       | 32%     |
| DDR2    | 31        | 8.27%   |
| DDR5    | 22        | 5.87%   |
| LPDDR4  | 20        | 5.33%   |
| Unknown | 10        | 2.67%   |
| SDRAM   | 5         | 1.33%   |
| LPDDR5  | 3         | 0.8%    |
| DDR     | 3         | 0.8%    |
| LPDDR3  | 2         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 202       | 54.16%  |
| DIMM         | 149       | 39.95%  |
| Row Of Chips | 15        | 4.02%   |
| Chip         | 4         | 1.07%   |
| FB-DIMM      | 2         | 0.54%   |
| Unknown      | 1         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 130       | 32.34%  |
| 8192  | 119       | 29.6%   |
| 2048  | 67        | 16.67%  |
| 16384 | 59        | 14.68%  |
| 1024  | 13        | 3.23%   |
| 32768 | 12        | 2.99%   |
| 65536 | 1         | 0.25%   |
| 256   | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 90        | 22.44%  |
| 3200    | 52        | 12.97%  |
| 1333    | 49        | 12.22%  |
| 2400    | 45        | 11.22%  |
| 2667    | 24        | 5.99%   |
| 667     | 21        | 5.24%   |
| 800     | 18        | 4.49%   |
| 4800    | 16        | 3.99%   |
| 2133    | 16        | 3.99%   |
| 1067    | 13        | 3.24%   |
| 5600    | 8         | 2%      |
| Unknown | 7         | 1.75%   |
| 1066    | 6         | 1.5%    |
| 1867    | 5         | 1.25%   |
| 1334    | 5         | 1.25%   |
| 6400    | 3         | 0.75%   |
| 3600    | 3         | 0.75%   |
| 2933    | 3         | 0.75%   |
| 1866    | 3         | 0.75%   |
| 3733    | 2         | 0.5%    |
| 2666    | 2         | 0.5%    |
| 5200    | 1         | 0.25%   |
| 4267    | 1         | 0.25%   |
| 3066    | 1         | 0.25%   |
| 3000    | 1         | 0.25%   |
| 2048    | 1         | 0.25%   |
| 1896    | 1         | 0.25%   |
| 1200    | 1         | 0.25%   |
| 975     | 1         | 0.25%   |
| 400     | 1         | 0.25%   |
| 333     | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Apple               | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-1640 Series Laser Printer | 1         | 50%     |
| Apple Gamesir-G3v 1.00               | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 50%     |
| Canon CanoScan N650U/N656U                    | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 27        | 30.68%  |
| IMC Networks                           | 12        | 13.64%  |
| Sunplus Innovation Technology          | 8         | 9.09%   |
| Realtek Semiconductor                  | 8         | 9.09%   |
| Bison Electronics                      | 7         | 7.95%   |
| Microdia                               | 3         | 3.41%   |
| Logitech                               | 3         | 3.41%   |
| ALi                                    | 3         | 3.41%   |
| Z-Star Microelectronics                | 2         | 2.27%   |
| Trust                                  | 2         | 2.27%   |
| Silicon Motion                         | 2         | 2.27%   |
| Genesys Logic                          | 2         | 2.27%   |
| Syntek                                 | 1         | 1.14%   |
| Suyin                                  | 1         | 1.14%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.14%   |
| Lite-On Technology                     | 1         | 1.14%   |
| Lenovo                                 | 1         | 1.14%   |
| KYE Systems (Mouse Systems)            | 1         | 1.14%   |
| Cubeternet                             | 1         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.14%   |
| Apple                                  | 1         | 1.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 6         | 6.82%   |
| Bison Integrated Camera                          | 4         | 4.55%   |
| Realtek Integrated_Webcam_HD                     | 3         | 3.41%   |
| Trust Trust QHD Webcam                           | 2         | 2.27%   |
| Realtek USB Camera                               | 2         | 2.27%   |
| Realtek Lenovo EasyCamera                        | 2         | 2.27%   |
| Microdia Integrated_Webcam_HD                    | 2         | 2.27%   |
| IMC Networks UVC VGA Webcam                      | 2         | 2.27%   |
| IMC Networks Realtek PC Camera                   | 2         | 2.27%   |
| IMC Networks Integrated Webcam                   | 2         | 2.27%   |
| IMC Networks Integrated Camera                   | 2         | 2.27%   |
| Genesys Logic Digital Microscope                 | 2         | 2.27%   |
| Chicony USB2.0 VGA UVC WebCam                    | 2         | 2.27%   |
| Chicony Integrated Camera (1280x720@30)          | 2         | 2.27%   |
| Chicony HD WebCam (Asus N-series)                | 2         | 2.27%   |
| Chicony HD WebCam (Acer)                         | 2         | 2.27%   |
| ALi Gateway Webcam                               | 2         | 2.27%   |
| Z-Star Webcam                                    | 1         | 1.14%   |
| Z-Star Vega USB 2.0 Camera                       | 1         | 1.14%   |
| Syntek EasyCamera                                | 1         | 1.14%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 1         | 1.14%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 1.14%   |
| Sunplus Laptop Integrated Webcam HD              | 1         | 1.14%   |
| Sunplus Integrated_Webcam_HD                     | 1         | 1.14%   |
| Sunplus Integrated Camera                        | 1         | 1.14%   |
| Sunplus Hy HD Camera                             | 1         | 1.14%   |
| Sunplus Dell E5570 integrated webcam             | 1         | 1.14%   |
| Sunplus Aukey-PC-LM1E Camera                     | 1         | 1.14%   |
| Sunplus 1.3M HD WebCam                           | 1         | 1.14%   |
| Silicon Motion Realtek USB 2.0 PC Camera         | 1         | 1.14%   |
| Silicon Motion HP Webcam-50                      | 1         | 1.14%   |
| Shenzhen Kingcome Optoelectronic HD Webcam       | 1         | 1.14%   |
| Realtek USB2.0 VGA UVC WebCam                    | 1         | 1.14%   |
| Microdia ASUS USB 2.0 Webcam                     | 1         | 1.14%   |
| Logitech Webcam C310                             | 1         | 1.14%   |
| Logitech Webcam C270                             | 1         | 1.14%   |
| Logitech C505 HD Webcam                          | 1         | 1.14%   |
| Lite-On HP TrueVision HD Camera                  | 1         | 1.14%   |
| Lenovo Integrated Webcam [R5U877]                | 1         | 1.14%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera | 1         | 1.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 26.32%  |
| Validity Sensors           | 4         | 21.05%  |
| AuthenTec                  | 3         | 15.79%  |
| Upek                       | 2         | 10.53%  |
| Shenzhen Goodix Technology | 2         | 10.53%  |
| STMicroelectronics         | 1         | 5.26%   |
| Elan Microelectronics      | 1         | 5.26%   |
| Broadcom                   | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 10.53%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 10.53%  |
| AuthenTec AES1600                                                            | 2         | 10.53%  |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 5.26%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 5.26%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 5.26%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 1         | 5.26%   |
| Synaptics UWP WBDI Device                                                    | 1         | 5.26%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 5.26%   |
| Shenzhen Goodix  Fingerprint Device                                          | 1         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 5.26%   |
| Elan Fingerprint Sensor                                                      | 1         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.26%   |
| AuthenTec AES2810                                                            | 1         | 5.26%   |

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
| 1     | 186       | 43.16%  |
| 0     | 128       | 29.7%   |
| 2     | 66        | 15.31%  |
| 3     | 44        | 10.21%  |
| 4     | 7         | 1.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 250       | 59.81%  |
| Net/wireless             | 45        | 10.77%  |
| Bluetooth                | 42        | 10.05%  |
| Card reader              | 28        | 6.7%    |
| Fingerprint reader       | 18        | 4.31%   |
| Firewire controller      | 14        | 3.35%   |
| Graphics card            | 7         | 1.67%   |
| Network                  | 6         | 1.44%   |
| Storage                  | 2         | 0.48%   |
| Net/ethernet             | 2         | 0.48%   |
| Dvb card                 | 2         | 0.48%   |
| Sound                    | 1         | 0.24%   |
| Modem                    | 1         | 0.24%   |

