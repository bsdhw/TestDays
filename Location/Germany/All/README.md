BSD in Germany - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for BSD in Germany.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Germany/Desktop/README.md) and [notebooks](/Location/Germany/Notebook/README.md).

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

Total: 3612

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [0aee6a395a](https://bsd-hardware.info/?probe=0aee6a395a) | May 08, 2024 |
| Supermicro    | X10SBA-LA                   | Server      | [8c25508656](https://bsd-hardware.info/?probe=8c25508656) | May 07, 2024 |
| AAEON         | FWS-2365 V1.0               | Desktop     | [e7f5d7ff38](https://bsd-hardware.info/?probe=e7f5d7ff38) | May 07, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [b56fbf51c6](https://bsd-hardware.info/?probe=b56fbf51c6) | May 07, 2024 |
| Dell          | 0DR845                      | Desktop     | [03e1ebc97e](https://bsd-hardware.info/?probe=03e1ebc97e) | May 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [676aa9858a](https://bsd-hardware.info/?probe=676aa9858a) | May 06, 2024 |
| Unknown       | Unknown                     | Firewall    | [f480571196](https://bsd-hardware.info/?probe=f480571196) | May 06, 2024 |
| Unknown       | Unknown                     | Firewall    | [121ff6feae](https://bsd-hardware.info/?probe=121ff6feae) | May 06, 2024 |
| MSI           | MS-7369                     | Desktop     | [65686a6412](https://bsd-hardware.info/?probe=65686a6412) | May 05, 2024 |
| SHANGZHAOY... | B85M-PRO V1.1               | Desktop     | [873fd32471](https://bsd-hardware.info/?probe=873fd32471) | May 05, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [6541261a86](https://bsd-hardware.info/?probe=6541261a86) | May 05, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [9f494db2bd](https://bsd-hardware.info/?probe=9f494db2bd) | May 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [5dc8d187ee](https://bsd-hardware.info/?probe=5dc8d187ee) | May 04, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [d87059c342](https://bsd-hardware.info/?probe=d87059c342) | May 04, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [35ab248dd4](https://bsd-hardware.info/?probe=35ab248dd4) | May 04, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [ffd31a143f](https://bsd-hardware.info/?probe=ffd31a143f) | May 04, 2024 |
| Lanner        | FW-7543 B-GA                | Desktop     | [d999a95489](https://bsd-hardware.info/?probe=d999a95489) | May 03, 2024 |
| Protectli     | FW4B                        | Desktop     | [db66e06618](https://bsd-hardware.info/?probe=db66e06618) | May 02, 2024 |
| AWOW          | AK10                        | Desktop     | [a8fbc35162](https://bsd-hardware.info/?probe=a8fbc35162) | May 01, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [4878c18c8a](https://bsd-hardware.info/?probe=4878c18c8a) | May 01, 2024 |
| Gigabyte      | B760I AORUS PRO DDR4        | Desktop     | [f6606ff3aa](https://bsd-hardware.info/?probe=f6606ff3aa) | May 01, 2024 |
| MSI           | AM1I                        | Desktop     | [148d52d171](https://bsd-hardware.info/?probe=148d52d171) | May 01, 2024 |
| Sophos        | SG                          | Firewall    | [aa116c84a7](https://bsd-hardware.info/?probe=aa116c84a7) | May 01, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [c04565ec24](https://bsd-hardware.info/?probe=c04565ec24) | Apr 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [39e9c3ddd2](https://bsd-hardware.info/?probe=39e9c3ddd2) | Apr 30, 2024 |
| PC Engines    | APU2                        | Desktop     | [a6953a27eb](https://bsd-hardware.info/?probe=a6953a27eb) | Apr 29, 2024 |
| ASRock        | Q1900M                      | Desktop     | [7f61d481a6](https://bsd-hardware.info/?probe=7f61d481a6) | Apr 29, 2024 |
| PC Engines    | APU2                        | Desktop     | [f18a73e413](https://bsd-hardware.info/?probe=f18a73e413) | Apr 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [d45b3d4001](https://bsd-hardware.info/?probe=d45b3d4001) | Apr 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [4da784940c](https://bsd-hardware.info/?probe=4da784940c) | Apr 27, 2024 |
| HP            | 859B                        | Desktop     | [5d8024a661](https://bsd-hardware.info/?probe=5d8024a661) | Apr 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [2945a5ee0f](https://bsd-hardware.info/?probe=2945a5ee0f) | Apr 27, 2024 |
| AWOW          | AK10                        | Desktop     | [efb7761dc3](https://bsd-hardware.info/?probe=efb7761dc3) | Apr 26, 2024 |
| SJRC          | SJ-ADLN-6L                  | Desktop     | [eba48b51e7](https://bsd-hardware.info/?probe=eba48b51e7) | Apr 26, 2024 |
| System76      | Pangolin                    | Notebook    | [d47c9a5d44](https://bsd-hardware.info/?probe=d47c9a5d44) | Apr 26, 2024 |
| Silicom       | 80300-0214-G01 R306         | Desktop     | [1fda8df8d0](https://bsd-hardware.info/?probe=1fda8df8d0) | Apr 25, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [328e9b0321](https://bsd-hardware.info/?probe=328e9b0321) | Apr 25, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [f92008b628](https://bsd-hardware.info/?probe=f92008b628) | Apr 25, 2024 |
| Sophos        | SG                          | Firewall    | [071c26cca5](https://bsd-hardware.info/?probe=071c26cca5) | Apr 24, 2024 |
| Protectli     | VP2420                      | Desktop     | [540090badd](https://bsd-hardware.info/?probe=540090badd) | Apr 24, 2024 |
| CncTion       | N4505-4L B0                 | Desktop     | [ada59fa5ed](https://bsd-hardware.info/?probe=ada59fa5ed) | Apr 24, 2024 |
| Gigabyte      | N3150ND3V                   | Desktop     | [9e0cb28c91](https://bsd-hardware.info/?probe=9e0cb28c91) | Apr 24, 2024 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [b549100edf](https://bsd-hardware.info/?probe=b549100edf) | Apr 23, 2024 |
| ASRock        | A320M Pro4-F                | Desktop     | [b02849b872](https://bsd-hardware.info/?probe=b02849b872) | Apr 23, 2024 |
| Sophos        | XG                          | Firewall    | [023d1a9570](https://bsd-hardware.info/?probe=023d1a9570) | Apr 22, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [565275ac34](https://bsd-hardware.info/?probe=565275ac34) | Apr 22, 2024 |
| Intel         | BOX-J41L4A V3.01            | Desktop     | [62124a50da](https://bsd-hardware.info/?probe=62124a50da) | Apr 22, 2024 |
| AAEON         | FWS-2280 V1.0               | Desktop     | [071a27c302](https://bsd-hardware.info/?probe=071a27c302) | Apr 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [c3bd100494](https://bsd-hardware.info/?probe=c3bd100494) | Apr 22, 2024 |
| Lanner        | FW-7543 B-GA                | Desktop     | [02a165d26f](https://bsd-hardware.info/?probe=02a165d26f) | Apr 22, 2024 |
| Sophos        | XG                          | Firewall    | [ade17f08b9](https://bsd-hardware.info/?probe=ade17f08b9) | Apr 22, 2024 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [072d422490](https://bsd-hardware.info/?probe=072d422490) | Apr 22, 2024 |
| Lenovo        | ThinkPad T400 6474E18       | Notebook    | [fcd3339ec5](https://bsd-hardware.info/?probe=fcd3339ec5) | Apr 21, 2024 |
| NF541         | 1.0                         | Desktop     | [25cc14f6c9](https://bsd-hardware.info/?probe=25cc14f6c9) | Apr 21, 2024 |
| AAEON         | FWS-2280 V1.0               | Desktop     | [003dbde912](https://bsd-hardware.info/?probe=003dbde912) | Apr 21, 2024 |
| Advantech     | NAMB-1010VC A101            | Desktop     | [e2a9d0cbff](https://bsd-hardware.info/?probe=e2a9d0cbff) | Apr 21, 2024 |
| CWWK          | MINIPC-G12                  | Desktop     | [9e0cee5f8e](https://bsd-hardware.info/?probe=9e0cee5f8e) | Apr 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [71ac1fd7c5](https://bsd-hardware.info/?probe=71ac1fd7c5) | Apr 20, 2024 |
| Sophos        | SG                          | Firewall    | [d97decf8c5](https://bsd-hardware.info/?probe=d97decf8c5) | Apr 18, 2024 |
| Protectli     | FW4B                        | Desktop     | [a5c17e61f1](https://bsd-hardware.info/?probe=a5c17e61f1) | Apr 18, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [82519e798c](https://bsd-hardware.info/?probe=82519e798c) | Apr 18, 2024 |
| SHANGZHAOY... | B85M-PRO V1.1               | Desktop     | [111bf86a64](https://bsd-hardware.info/?probe=111bf86a64) | Apr 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [5dfaef985e](https://bsd-hardware.info/?probe=5dfaef985e) | Apr 18, 2024 |
| Unknown       | Unknown                     | Notebook    | [5886bb9659](https://bsd-hardware.info/?probe=5886bb9659) | Apr 18, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [f8c9b99afe](https://bsd-hardware.info/?probe=f8c9b99afe) | Apr 17, 2024 |
| ASRock        | N68-GS3 UCC                 | Desktop     | [8da917c311](https://bsd-hardware.info/?probe=8da917c311) | Apr 16, 2024 |
| Gigabyte      | Q670M D3H                   | Desktop     | [923a7e28d2](https://bsd-hardware.info/?probe=923a7e28d2) | Apr 16, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [44758d3d74](https://bsd-hardware.info/?probe=44758d3d74) | Apr 16, 2024 |
| PC Engines    | APU2                        | Desktop     | [a0db25b377](https://bsd-hardware.info/?probe=a0db25b377) | Apr 16, 2024 |
| ASRock        | H310CM-DVS                  | Desktop     | [61e73f301e](https://bsd-hardware.info/?probe=61e73f301e) | Apr 15, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [63b60ab68e](https://bsd-hardware.info/?probe=63b60ab68e) | Apr 15, 2024 |
| Lenovo        | ThinkPad T460 20FMA09CGE    | Notebook    | [c7219eb82e](https://bsd-hardware.info/?probe=c7219eb82e) | Apr 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [c02b232857](https://bsd-hardware.info/?probe=c02b232857) | Apr 15, 2024 |
| Unknown       | J3160-4L                    | Desktop     | [1f2e61cf7d](https://bsd-hardware.info/?probe=1f2e61cf7d) | Apr 14, 2024 |
| Fujitsu       | D3375-A1 S26361-D3375-A1... | Server      | [7f5d08b02b](https://bsd-hardware.info/?probe=7f5d08b02b) | Apr 13, 2024 |
| Gigabyte      | N3150ND3V                   | Desktop     | [50cdb5f1c0](https://bsd-hardware.info/?probe=50cdb5f1c0) | Apr 13, 2024 |
| Dell          | 0GM819                      | Desktop     | [6140b5e6ad](https://bsd-hardware.info/?probe=6140b5e6ad) | Apr 12, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [850c749c00](https://bsd-hardware.info/?probe=850c749c00) | Apr 12, 2024 |
| Supermicro    | X11SCL-IF                   | Server      | [72613481e7](https://bsd-hardware.info/?probe=72613481e7) | Apr 11, 2024 |
| Intel         | NUC7i7BNB J31145-306        | Mini pc     | [1ba0813950](https://bsd-hardware.info/?probe=1ba0813950) | Apr 11, 2024 |
| HP            | 8298                        | Desktop     | [c9d7df4ade](https://bsd-hardware.info/?probe=c9d7df4ade) | Apr 08, 2024 |
| Supermicro    | X10SLM+-LN4F                | Server      | [640918e28a](https://bsd-hardware.info/?probe=640918e28a) | Apr 08, 2024 |
| Dell          | 0C27VV A02                  | Desktop     | [838d1cbd76](https://bsd-hardware.info/?probe=838d1cbd76) | Apr 08, 2024 |
| Lenovo        | 3181 SDK0J40697 WIN 3305... | Mini pc     | [da774945c3](https://bsd-hardware.info/?probe=da774945c3) | Apr 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [adb3e3abb5](https://bsd-hardware.info/?probe=adb3e3abb5) | Apr 07, 2024 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [53663c4ae5](https://bsd-hardware.info/?probe=53663c4ae5) | Apr 07, 2024 |
| Sophos        | SG                          | Firewall    | [07510a2576](https://bsd-hardware.info/?probe=07510a2576) | Apr 07, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [8df08d4eb9](https://bsd-hardware.info/?probe=8df08d4eb9) | Apr 06, 2024 |
| HP            | 2B28                        | Desktop     | [b4f2207b5d](https://bsd-hardware.info/?probe=b4f2207b5d) | Apr 06, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [b2c5d9efea](https://bsd-hardware.info/?probe=b2c5d9efea) | Apr 06, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [f454e745a8](https://bsd-hardware.info/?probe=f454e745a8) | Apr 06, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [d0ce6ee00b](https://bsd-hardware.info/?probe=d0ce6ee00b) | Apr 05, 2024 |
| Dell          | 02C2CP A03                  | Server      | [b93ac9480b](https://bsd-hardware.info/?probe=b93ac9480b) | Apr 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [db63931af3](https://bsd-hardware.info/?probe=db63931af3) | Apr 05, 2024 |
| Sophos        | SG                          | Firewall    | [0af8e67986](https://bsd-hardware.info/?probe=0af8e67986) | Apr 05, 2024 |
| HP            | 2B28                        | Desktop     | [5a64d57e01](https://bsd-hardware.info/?probe=5a64d57e01) | Apr 05, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3208fef860](https://bsd-hardware.info/?probe=3208fef860) | Apr 04, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [f6d9d3eaf2](https://bsd-hardware.info/?probe=f6d9d3eaf2) | Apr 03, 2024 |
| OEM           | 1.0                         | Desktop     | [a84e4f90a7](https://bsd-hardware.info/?probe=a84e4f90a7) | Apr 03, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [767ef499db](https://bsd-hardware.info/?probe=767ef499db) | Apr 03, 2024 |
| Intel         | NUC6i3SYB H81132-503        | Mini pc     | [666b875723](https://bsd-hardware.info/?probe=666b875723) | Apr 02, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0ab49168ee](https://bsd-hardware.info/?probe=0ab49168ee) | Apr 02, 2024 |
| ASRock        | B365 Phantom Gaming 4       | Desktop     | [002a5c4b4b](https://bsd-hardware.info/?probe=002a5c4b4b) | Apr 02, 2024 |
| PC Engines    | APU2                        | Desktop     | [8bc45e08fd](https://bsd-hardware.info/?probe=8bc45e08fd) | Apr 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [141a02f122](https://bsd-hardware.info/?probe=141a02f122) | Apr 01, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [cc791d5d6b](https://bsd-hardware.info/?probe=cc791d5d6b) | Apr 01, 2024 |
| Sophos        | SG                          | Firewall    | [349351476b](https://bsd-hardware.info/?probe=349351476b) | Apr 01, 2024 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | Desktop     | [2b8b6454a6](https://bsd-hardware.info/?probe=2b8b6454a6) | Mar 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [9c12506b38](https://bsd-hardware.info/?probe=9c12506b38) | Mar 31, 2024 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [791f0e10d0](https://bsd-hardware.info/?probe=791f0e10d0) | Mar 31, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [a596a6f2fc](https://bsd-hardware.info/?probe=a596a6f2fc) | Mar 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [19cd39be18](https://bsd-hardware.info/?probe=19cd39be18) | Mar 30, 2024 |
| Sophos        | XG                          | Firewall    | [62f04db1ac](https://bsd-hardware.info/?probe=62f04db1ac) | Mar 29, 2024 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [6b02f9805c](https://bsd-hardware.info/?probe=6b02f9805c) | Mar 29, 2024 |
| Unknown       | Unknown                     | Firewall    | [324b4f864d](https://bsd-hardware.info/?probe=324b4f864d) | Mar 29, 2024 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [fd5f6eb3b6](https://bsd-hardware.info/?probe=fd5f6eb3b6) | Mar 29, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [007b6f4e9d](https://bsd-hardware.info/?probe=007b6f4e9d) | Mar 29, 2024 |
| ASRock        | Q1900-ITX                   | Desktop     | [cfceb60c9e](https://bsd-hardware.info/?probe=cfceb60c9e) | Mar 28, 2024 |
| ASRock        | Q1900-ITX                   | Desktop     | [d29def9398](https://bsd-hardware.info/?probe=d29def9398) | Mar 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [88c73f9aac](https://bsd-hardware.info/?probe=88c73f9aac) | Mar 28, 2024 |
| Intel         | ChiefRiver                  | Desktop     | [cad5b112a4](https://bsd-hardware.info/?probe=cad5b112a4) | Mar 28, 2024 |
| PC Engines    | apu4                        | Desktop     | [22943891fe](https://bsd-hardware.info/?probe=22943891fe) | Mar 28, 2024 |
| AAEON         | FWS-2251 V1.0               | Desktop     | [5b53955547](https://bsd-hardware.info/?probe=5b53955547) | Mar 28, 2024 |
| Shuttle       | DS77U                       | Notebook    | [b065bf5918](https://bsd-hardware.info/?probe=b065bf5918) | Mar 27, 2024 |
| Fujitsu       | LIFEBOOK U727               | Notebook    | [76e6dff995](https://bsd-hardware.info/?probe=76e6dff995) | Mar 27, 2024 |
| Fujitsu       | D3644-B1 S26361-D3644-B1    | Desktop     | [ab7e9eb3b3](https://bsd-hardware.info/?probe=ab7e9eb3b3) | Mar 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [32c0457508](https://bsd-hardware.info/?probe=32c0457508) | Mar 27, 2024 |
| AZW           | EQ                          | Desktop     | [720bbb4fce](https://bsd-hardware.info/?probe=720bbb4fce) | Mar 27, 2024 |
| Fujitsu       | D3067-A1 S26361-D3067-A1    | Desktop     | [efa43f3297](https://bsd-hardware.info/?probe=efa43f3297) | Mar 27, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [e777acccde](https://bsd-hardware.info/?probe=e777acccde) | Mar 26, 2024 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | Desktop     | [c01d223879](https://bsd-hardware.info/?probe=c01d223879) | Mar 26, 2024 |
| ASRock        | A520M-ITX/ac                | Desktop     | [ae88fbe955](https://bsd-hardware.info/?probe=ae88fbe955) | Mar 25, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [a5003ca56a](https://bsd-hardware.info/?probe=a5003ca56a) | Mar 25, 2024 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [e5f412499d](https://bsd-hardware.info/?probe=e5f412499d) | Mar 25, 2024 |
| HP            | 8103 A01                    | Mini pc     | [0559e8b0a3](https://bsd-hardware.info/?probe=0559e8b0a3) | Mar 25, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ca39a53bd3](https://bsd-hardware.info/?probe=ca39a53bd3) | Mar 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [83e699ca56](https://bsd-hardware.info/?probe=83e699ca56) | Mar 25, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [c4f7c92b3a](https://bsd-hardware.info/?probe=c4f7c92b3a) | Mar 24, 2024 |
| Fujitsu       | D3067-A1 S26361-D3067-A1    | Desktop     | [d437c9f3ec](https://bsd-hardware.info/?probe=d437c9f3ec) | Mar 24, 2024 |
| Supermicro    | X11SCM-LN8F                 | Server      | [b29ef3bce7](https://bsd-hardware.info/?probe=b29ef3bce7) | Mar 24, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [5b299b5bb4](https://bsd-hardware.info/?probe=5b299b5bb4) | Mar 24, 2024 |
| Dell          | 060J9C A00                  | Mini pc     | [e7e4920292](https://bsd-hardware.info/?probe=e7e4920292) | Mar 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [0e7756d928](https://bsd-hardware.info/?probe=0e7756d928) | Mar 23, 2024 |
| Unknown       | YL-J3160L4                  | Desktop     | [17e05ff99b](https://bsd-hardware.info/?probe=17e05ff99b) | Mar 23, 2024 |
| ASUSTek       | P8H67-I                     | Desktop     | [70e83653e3](https://bsd-hardware.info/?probe=70e83653e3) | Mar 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [5772e3f865](https://bsd-hardware.info/?probe=5772e3f865) | Mar 22, 2024 |
| MW            | GMLK-2_5G4L                 | Desktop     | [220edbe827](https://bsd-hardware.info/?probe=220edbe827) | Mar 22, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [f0f1bda4c6](https://bsd-hardware.info/?probe=f0f1bda4c6) | Mar 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [31d2e2ad77](https://bsd-hardware.info/?probe=31d2e2ad77) | Mar 19, 2024 |
| Sophos        | SG                          | Firewall    | [8a25744371](https://bsd-hardware.info/?probe=8a25744371) | Mar 19, 2024 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [7617a6faa1](https://bsd-hardware.info/?probe=7617a6faa1) | Mar 19, 2024 |
| MI05          | 1.0                         | Desktop     | [15144d304e](https://bsd-hardware.info/?probe=15144d304e) | Mar 19, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [da7c40ce91](https://bsd-hardware.info/?probe=da7c40ce91) | Mar 18, 2024 |
| Dell          | Latitude D830               | Notebook    | [832440d0c3](https://bsd-hardware.info/?probe=832440d0c3) | Mar 17, 2024 |
| HP            | 213D A01                    | Desktop     | [d86065a205](https://bsd-hardware.info/?probe=d86065a205) | Mar 17, 2024 |
| Google        | Cave                        | Notebook    | [d9df48c781](https://bsd-hardware.info/?probe=d9df48c781) | Mar 16, 2024 |
| HP            | 8425                        | Desktop     | [9d64ad4ed7](https://bsd-hardware.info/?probe=9d64ad4ed7) | Mar 15, 2024 |
| ASRock        | H310CM-DVS                  | Desktop     | [3f2a641be5](https://bsd-hardware.info/?probe=3f2a641be5) | Mar 15, 2024 |
| Sophos        | XG                          | Firewall    | [d638c018a7](https://bsd-hardware.info/?probe=d638c018a7) | Mar 14, 2024 |
| ASRock        | J5040-ITX                   | Desktop     | [046fab7e1e](https://bsd-hardware.info/?probe=046fab7e1e) | Mar 14, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e89e238ce9](https://bsd-hardware.info/?probe=e89e238ce9) | Mar 14, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [58cc0f695b](https://bsd-hardware.info/?probe=58cc0f695b) | Mar 14, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [1729736b2c](https://bsd-hardware.info/?probe=1729736b2c) | Mar 14, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [97982c9486](https://bsd-hardware.info/?probe=97982c9486) | Mar 13, 2024 |
| Gigabyte      | X570S UD                    | Desktop     | [c28339af88](https://bsd-hardware.info/?probe=c28339af88) | Mar 13, 2024 |
| AAEON         | FWS-2362 V1.0               | Desktop     | [ecb6ef08ca](https://bsd-hardware.info/?probe=ecb6ef08ca) | Mar 13, 2024 |
| TULPAR        | A5 V20.3                    | Notebook    | [476d91b2cf](https://bsd-hardware.info/?probe=476d91b2cf) | Mar 13, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [4b52e91e24](https://bsd-hardware.info/?probe=4b52e91e24) | Mar 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [180c13e49f](https://bsd-hardware.info/?probe=180c13e49f) | Mar 13, 2024 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a77269ec67](https://bsd-hardware.info/?probe=a77269ec67) | Mar 12, 2024 |
| Acer          | Aspire V5-573G              | Notebook    | [59445c5f19](https://bsd-hardware.info/?probe=59445c5f19) | Mar 12, 2024 |
| ASUSTek       | P8H61-M PRO                 | Desktop     | [cdf413f137](https://bsd-hardware.info/?probe=cdf413f137) | Mar 12, 2024 |
| OEM_MB        | 2A72                        | Desktop     | [ae3340833c](https://bsd-hardware.info/?probe=ae3340833c) | Mar 11, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [da1d8cff5b](https://bsd-hardware.info/?probe=da1d8cff5b) | Mar 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [eb78b18ceb](https://bsd-hardware.info/?probe=eb78b18ceb) | Mar 11, 2024 |
| Intel         | BOX-J41L4A V3.01            | Desktop     | [91980ca805](https://bsd-hardware.info/?probe=91980ca805) | Mar 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [646ddc0a68](https://bsd-hardware.info/?probe=646ddc0a68) | Mar 10, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0ceb5cfbf8](https://bsd-hardware.info/?probe=0ceb5cfbf8) | Mar 10, 2024 |
| Sophos        | SG                          | Firewall    | [1c326d8911](https://bsd-hardware.info/?probe=1c326d8911) | Mar 10, 2024 |
| PC Engines    | APU2                        | Desktop     | [fa374c2fa0](https://bsd-hardware.info/?probe=fa374c2fa0) | Mar 10, 2024 |
| Supermicro    | X10SDV-TP8F                 | Server      | [9684c7dad2](https://bsd-hardware.info/?probe=9684c7dad2) | Mar 10, 2024 |
| ASRock        | Z97 Professional            | Desktop     | [f00b2738c3](https://bsd-hardware.info/?probe=f00b2738c3) | Mar 10, 2024 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [5108629879](https://bsd-hardware.info/?probe=5108629879) | Mar 09, 2024 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [fe33b788e7](https://bsd-hardware.info/?probe=fe33b788e7) | Mar 09, 2024 |
| PC Engines    | apu4                        | Desktop     | [6a8595a3ef](https://bsd-hardware.info/?probe=6a8595a3ef) | Mar 08, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [8363fabd39](https://bsd-hardware.info/?probe=8363fabd39) | Mar 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [58d203b730](https://bsd-hardware.info/?probe=58d203b730) | Mar 08, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [2e0ce432cb](https://bsd-hardware.info/?probe=2e0ce432cb) | Mar 07, 2024 |
| Sophos        | SG                          | Firewall    | [ba4e694ead](https://bsd-hardware.info/?probe=ba4e694ead) | Mar 07, 2024 |
| HP            | 213D A01                    | Desktop     | [964aa8199e](https://bsd-hardware.info/?probe=964aa8199e) | Mar 07, 2024 |
| Supermicro    | X10SRG-F                    | Desktop     | [293c884b40](https://bsd-hardware.info/?probe=293c884b40) | Mar 06, 2024 |
| PC Engines    | APU2                        | Desktop     | [2c64bf49b7](https://bsd-hardware.info/?probe=2c64bf49b7) | Mar 05, 2024 |
| Gigabyte      | IMB1900TN                   | Desktop     | [df5fd8934f](https://bsd-hardware.info/?probe=df5fd8934f) | Mar 04, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [ac0668a6e3](https://bsd-hardware.info/?probe=ac0668a6e3) | Mar 04, 2024 |
| Fujitsu       | D3373-B1 S26361-D3373-B1... | Server      | [89f705df50](https://bsd-hardware.info/?probe=89f705df50) | Mar 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [1e20066df1](https://bsd-hardware.info/?probe=1e20066df1) | Mar 03, 2024 |
| PC Engines    | apu4                        | Desktop     | [ba31193999](https://bsd-hardware.info/?probe=ba31193999) | Mar 02, 2024 |
| Seco          | 0D02 A                      | Desktop     | [4aedb9a14f](https://bsd-hardware.info/?probe=4aedb9a14f) | Mar 02, 2024 |
| Seco          | 0D02 A                      | Desktop     | [3c0fb33c35](https://bsd-hardware.info/?probe=3c0fb33c35) | Mar 02, 2024 |
| Sophos        | UTM                         | Firewall    | [0d201eab65](https://bsd-hardware.info/?probe=0d201eab65) | Feb 29, 2024 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5119d898d7](https://bsd-hardware.info/?probe=5119d898d7) | Feb 28, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [7159414a44](https://bsd-hardware.info/?probe=7159414a44) | Feb 28, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [4ef66ebe1f](https://bsd-hardware.info/?probe=4ef66ebe1f) | Feb 27, 2024 |
| Supermicro    | X9SCL/X9SCM                 | Desktop     | [5a91ab5fef](https://bsd-hardware.info/?probe=5a91ab5fef) | Feb 26, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [7c73382c9d](https://bsd-hardware.info/?probe=7c73382c9d) | Feb 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [1ea892bfd7](https://bsd-hardware.info/?probe=1ea892bfd7) | Feb 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [ecae7c493f](https://bsd-hardware.info/?probe=ecae7c493f) | Feb 25, 2024 |
| Unknown       | QCML03                      | Desktop     | [da0d43e31b](https://bsd-hardware.info/?probe=da0d43e31b) | Feb 25, 2024 |
| HP            | ProLiant DL120 Gen9         | Server      | [66b078de20](https://bsd-hardware.info/?probe=66b078de20) | Feb 24, 2024 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [5c5ee30a7a](https://bsd-hardware.info/?probe=5c5ee30a7a) | Feb 24, 2024 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [4ea9c8a781](https://bsd-hardware.info/?probe=4ea9c8a781) | Feb 24, 2024 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [8139f2fb4a](https://bsd-hardware.info/?probe=8139f2fb4a) | Feb 24, 2024 |
| Dell          | 0DR845                      | Desktop     | [1f5c710591](https://bsd-hardware.info/?probe=1f5c710591) | Feb 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [b812f56645](https://bsd-hardware.info/?probe=b812f56645) | Feb 23, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b305fd520f](https://bsd-hardware.info/?probe=b305fd520f) | Feb 22, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [be7a457bac](https://bsd-hardware.info/?probe=be7a457bac) | Feb 22, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [9c469850bb](https://bsd-hardware.info/?probe=9c469850bb) | Feb 22, 2024 |
| ZOTAC         | ZBOX-ID91                   | Mini pc     | [1977ce2e44](https://bsd-hardware.info/?probe=1977ce2e44) | Feb 22, 2024 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [9105a79b01](https://bsd-hardware.info/?probe=9105a79b01) | Feb 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [6a06080810](https://bsd-hardware.info/?probe=6a06080810) | Feb 20, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [93c97119b6](https://bsd-hardware.info/?probe=93c97119b6) | Feb 20, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [b763a1f3b5](https://bsd-hardware.info/?probe=b763a1f3b5) | Feb 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [2d81dec0b1](https://bsd-hardware.info/?probe=2d81dec0b1) | Feb 20, 2024 |
| PC Engines    | apu4                        | Desktop     | [a81bdf4af4](https://bsd-hardware.info/?probe=a81bdf4af4) | Feb 20, 2024 |
| Unknown       | Unknown                     | Firewall    | [cc7f166eb2](https://bsd-hardware.info/?probe=cc7f166eb2) | Feb 19, 2024 |
| Gigabyte      | IMB1900TN                   | Desktop     | [676b767621](https://bsd-hardware.info/?probe=676b767621) | Feb 19, 2024 |
| HP            | ProLiant DL120 Gen9         | Server      | [876428bf36](https://bsd-hardware.info/?probe=876428bf36) | Feb 19, 2024 |
| Dell          | Latitude E5510              | Notebook    | [4155c54a6c](https://bsd-hardware.info/?probe=4155c54a6c) | Feb 19, 2024 |
| Dell          | Latitude E5510              | Notebook    | [1bc1ac66c3](https://bsd-hardware.info/?probe=1bc1ac66c3) | Feb 18, 2024 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [246fac4a14](https://bsd-hardware.info/?probe=246fac4a14) | Feb 18, 2024 |
| ASRock        | H670M-ITX/ax                | Desktop     | [c67ba39d84](https://bsd-hardware.info/?probe=c67ba39d84) | Feb 18, 2024 |
| ASRock        | H670M-ITX/ax                | Desktop     | [712b7feb38](https://bsd-hardware.info/?probe=712b7feb38) | Feb 18, 2024 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [057ab23bee](https://bsd-hardware.info/?probe=057ab23bee) | Feb 18, 2024 |
| PC Engines    | apu4                        | Desktop     | [2ddf4760e4](https://bsd-hardware.info/?probe=2ddf4760e4) | Feb 18, 2024 |
| Unknown       | J3160-4L                    | Desktop     | [e4b6344125](https://bsd-hardware.info/?probe=e4b6344125) | Feb 18, 2024 |
| Gigabyte      | Z590I VISION D              | Desktop     | [95add8c57a](https://bsd-hardware.info/?probe=95add8c57a) | Feb 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [0d6264dd51](https://bsd-hardware.info/?probe=0d6264dd51) | Feb 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [ac788598a6](https://bsd-hardware.info/?probe=ac788598a6) | Feb 17, 2024 |
| ASUSTek       | B85M-G                      | Desktop     | [0fc891ba64](https://bsd-hardware.info/?probe=0fc891ba64) | Feb 17, 2024 |
| Biostar       | B450NH                      | Desktop     | [9f4dedfcd6](https://bsd-hardware.info/?probe=9f4dedfcd6) | Feb 17, 2024 |
| Sophos        | SG                          | Firewall    | [5224c7efa3](https://bsd-hardware.info/?probe=5224c7efa3) | Feb 16, 2024 |
| Sophos        | SG                          | Firewall    | [6c3e05ea48](https://bsd-hardware.info/?probe=6c3e05ea48) | Feb 16, 2024 |
| HP            | 8AC4                        | Desktop     | [524b8cae7c](https://bsd-hardware.info/?probe=524b8cae7c) | Feb 16, 2024 |
| Biostar       | B450NH                      | Desktop     | [2db279db1d](https://bsd-hardware.info/?probe=2db279db1d) | Feb 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [a4781efc54](https://bsd-hardware.info/?probe=a4781efc54) | Feb 16, 2024 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [65cc201af1](https://bsd-hardware.info/?probe=65cc201af1) | Feb 15, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [947eabeecc](https://bsd-hardware.info/?probe=947eabeecc) | Feb 15, 2024 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [7fcc4087e9](https://bsd-hardware.info/?probe=7fcc4087e9) | Feb 15, 2024 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [f9ad9d25e3](https://bsd-hardware.info/?probe=f9ad9d25e3) | Feb 14, 2024 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [fdeb2cee9d](https://bsd-hardware.info/?probe=fdeb2cee9d) | Feb 14, 2024 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [6a026289ce](https://bsd-hardware.info/?probe=6a026289ce) | Feb 14, 2024 |
| Gigabyte      | IMB1900TN                   | Desktop     | [d0c6d1e44b](https://bsd-hardware.info/?probe=d0c6d1e44b) | Feb 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [5da46d2f84](https://bsd-hardware.info/?probe=5da46d2f84) | Feb 14, 2024 |
| Sophos        | SG                          | Firewall    | [b23c7b93a3](https://bsd-hardware.info/?probe=b23c7b93a3) | Feb 13, 2024 |
| ASRock        | A520M-ITX/ac                | Desktop     | [63408627d9](https://bsd-hardware.info/?probe=63408627d9) | Feb 13, 2024 |
| Gigabyte      | B760I AORUS PRO DDR4        | Desktop     | [0074d80aa1](https://bsd-hardware.info/?probe=0074d80aa1) | Feb 12, 2024 |
| Unknown       | YL-J3160L4                  | Desktop     | [7bb2930dfa](https://bsd-hardware.info/?probe=7bb2930dfa) | Feb 11, 2024 |
| Supermicro    | X10SLL-F                    | Server      | [d08cceec12](https://bsd-hardware.info/?probe=d08cceec12) | Feb 11, 2024 |
| Gigabyte      | B760I AORUS PRO DDR4        | Desktop     | [ab109fa386](https://bsd-hardware.info/?probe=ab109fa386) | Feb 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [ea4fe7a8cf](https://bsd-hardware.info/?probe=ea4fe7a8cf) | Feb 10, 2024 |
| Deciso        | NetBoard-A10                | Notebook    | [8403713b4f](https://bsd-hardware.info/?probe=8403713b4f) | Feb 10, 2024 |
| Sophos        | SG                          | Firewall    | [06bd59ff02](https://bsd-hardware.info/?probe=06bd59ff02) | Feb 10, 2024 |
| Sophos        | SG                          | Firewall    | [1bb50b3634](https://bsd-hardware.info/?probe=1bb50b3634) | Feb 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [eb03c1914f](https://bsd-hardware.info/?probe=eb03c1914f) | Feb 09, 2024 |
| Fujitsu       | D3067-A1 S26361-D3067-A1    | Desktop     | [08ee39a7cf](https://bsd-hardware.info/?probe=08ee39a7cf) | Feb 09, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1401e42d48](https://bsd-hardware.info/?probe=1401e42d48) | Feb 08, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [7ec9f0596a](https://bsd-hardware.info/?probe=7ec9f0596a) | Feb 08, 2024 |
| Unknown       | J3160-4L                    | Desktop     | [353ac982bf](https://bsd-hardware.info/?probe=353ac982bf) | Feb 07, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [2a4911715a](https://bsd-hardware.info/?probe=2a4911715a) | Feb 07, 2024 |
| Dell          | 0F0XJ6 A13                  | Server      | [0493961490](https://bsd-hardware.info/?probe=0493961490) | Feb 07, 2024 |
| SHANGZHAOY... | B85M-PRO V1.1               | Desktop     | [79ec97854e](https://bsd-hardware.info/?probe=79ec97854e) | Feb 07, 2024 |
| AAEON         | FWS-2251 V1.0               | Desktop     | [17853848cd](https://bsd-hardware.info/?probe=17853848cd) | Feb 07, 2024 |
| HP            | 8717                        | Desktop     | [de846f4d11](https://bsd-hardware.info/?probe=de846f4d11) | Feb 07, 2024 |
| OEM           | 1.0                         | Desktop     | [dd3228b447](https://bsd-hardware.info/?probe=dd3228b447) | Feb 07, 2024 |
| PC Engines    | apu4                        | Desktop     | [fb60f908ae](https://bsd-hardware.info/?probe=fb60f908ae) | Feb 07, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4073dda626](https://bsd-hardware.info/?probe=4073dda626) | Feb 07, 2024 |
| AAEON         | FWS-2251 V1.0               | Desktop     | [1def0a68ec](https://bsd-hardware.info/?probe=1def0a68ec) | Feb 07, 2024 |
| Sophos        | SG                          | Firewall    | [5695f7cef3](https://bsd-hardware.info/?probe=5695f7cef3) | Feb 06, 2024 |
| Fujitsu       | D3544-Sx S26361-D3544-Sx... | Mini pc     | [3f9cc1361f](https://bsd-hardware.info/?probe=3f9cc1361f) | Feb 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [38a8200699](https://bsd-hardware.info/?probe=38a8200699) | Feb 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [7f960ac536](https://bsd-hardware.info/?probe=7f960ac536) | Feb 06, 2024 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [a2c1b1addb](https://bsd-hardware.info/?probe=a2c1b1addb) | Feb 06, 2024 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [411de8ca13](https://bsd-hardware.info/?probe=411de8ca13) | Feb 06, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [a26afd4195](https://bsd-hardware.info/?probe=a26afd4195) | Feb 05, 2024 |
| Intel         | DENLOW_WS                   | Desktop     | [2d0479073b](https://bsd-hardware.info/?probe=2d0479073b) | Feb 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [ff4514068b](https://bsd-hardware.info/?probe=ff4514068b) | Feb 05, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [c77173c2f3](https://bsd-hardware.info/?probe=c77173c2f3) | Feb 04, 2024 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [9e7d881690](https://bsd-hardware.info/?probe=9e7d881690) | Feb 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [aef9924665](https://bsd-hardware.info/?probe=aef9924665) | Feb 04, 2024 |
| Sophos        | UTM                         | Firewall    | [743e074269](https://bsd-hardware.info/?probe=743e074269) | Feb 04, 2024 |
| AZW           | EQ                          | Desktop     | [13a1514ea5](https://bsd-hardware.info/?probe=13a1514ea5) | Feb 04, 2024 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [4cb8c45861](https://bsd-hardware.info/?probe=4cb8c45861) | Feb 03, 2024 |
| Deciso        | NetBoard-A10                | Notebook    | [118bac872e](https://bsd-hardware.info/?probe=118bac872e) | Feb 03, 2024 |
| AZW           | EQ                          | Desktop     | [53f9e8c700](https://bsd-hardware.info/?probe=53f9e8c700) | Feb 03, 2024 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [676019447d](https://bsd-hardware.info/?probe=676019447d) | Feb 03, 2024 |
| ASRock        | H570M-ITX/ac                | Desktop     | [df0fcc7727](https://bsd-hardware.info/?probe=df0fcc7727) | Feb 03, 2024 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [a301eadff9](https://bsd-hardware.info/?probe=a301eadff9) | Feb 03, 2024 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [4fdc25bc68](https://bsd-hardware.info/?probe=4fdc25bc68) | Feb 03, 2024 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [e5d18ced76](https://bsd-hardware.info/?probe=e5d18ced76) | Feb 03, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [95f19036db](https://bsd-hardware.info/?probe=95f19036db) | Feb 03, 2024 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [f6b0ead009](https://bsd-hardware.info/?probe=f6b0ead009) | Feb 02, 2024 |
| NU591         | 1.0                         | Desktop     | [deccea813e](https://bsd-hardware.info/?probe=deccea813e) | Feb 02, 2024 |
| AAEON         | FWS-2251 V1.0               | Desktop     | [492271b0b3](https://bsd-hardware.info/?probe=492271b0b3) | Feb 02, 2024 |
| ASRock        | ALiveNF7G-HD720p            | Desktop     | [2bc3971f16](https://bsd-hardware.info/?probe=2bc3971f16) | Feb 02, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [f3322d1b78](https://bsd-hardware.info/?probe=f3322d1b78) | Feb 01, 2024 |
| PC Engines    | APU2                        | Desktop     | [36ea8d39d4](https://bsd-hardware.info/?probe=36ea8d39d4) | Feb 01, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [4768e0001d](https://bsd-hardware.info/?probe=4768e0001d) | Feb 01, 2024 |
| Gigabyte      | IMB1900TN                   | Desktop     | [598cd03428](https://bsd-hardware.info/?probe=598cd03428) | Feb 01, 2024 |
| Protectli     | VP2410 10                   | Desktop     | [7d38bf7f11](https://bsd-hardware.info/?probe=7d38bf7f11) | Feb 01, 2024 |
| Gigabyte      | IMB1900TN                   | Desktop     | [60dd608790](https://bsd-hardware.info/?probe=60dd608790) | Feb 01, 2024 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [ee974b7142](https://bsd-hardware.info/?probe=ee974b7142) | Feb 01, 2024 |
| Gigabyte      | B760I AORUS PRO DDR4        | Desktop     | [ac68b46e30](https://bsd-hardware.info/?probe=ac68b46e30) | Jan 31, 2024 |
| Gigabyte      | IMB1900TN                   | Desktop     | [99f34191a2](https://bsd-hardware.info/?probe=99f34191a2) | Jan 31, 2024 |
| NU591         | 1.0                         | Desktop     | [1a28ec7585](https://bsd-hardware.info/?probe=1a28ec7585) | Jan 31, 2024 |
| AZW           | EQ                          | Desktop     | [543a7683f5](https://bsd-hardware.info/?probe=543a7683f5) | Jan 31, 2024 |
| SHANGZHAOY... | B85M-PRO V1.1               | Desktop     | [2da6441f53](https://bsd-hardware.info/?probe=2da6441f53) | Jan 31, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [101a551862](https://bsd-hardware.info/?probe=101a551862) | Jan 30, 2024 |
| LANCOM Sys... | UF-360                      | Desktop     | [c220e91992](https://bsd-hardware.info/?probe=c220e91992) | Jan 30, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [72acb76c3b](https://bsd-hardware.info/?probe=72acb76c3b) | Jan 30, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [57d4964d77](https://bsd-hardware.info/?probe=57d4964d77) | Jan 30, 2024 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [dc64c3b9e2](https://bsd-hardware.info/?probe=dc64c3b9e2) | Jan 30, 2024 |
| CncTion       | N4505-4L B0                 | Desktop     | [2c14913b53](https://bsd-hardware.info/?probe=2c14913b53) | Jan 29, 2024 |
| CncTion       | N4505-4L B0                 | Desktop     | [f242be3f80](https://bsd-hardware.info/?probe=f242be3f80) | Jan 28, 2024 |
| Unknown       | YL-J3160L4                  | Desktop     | [4eaf392351](https://bsd-hardware.info/?probe=4eaf392351) | Jan 28, 2024 |
| Seco          | 0D02 A                      | Desktop     | [41fa3fa6ae](https://bsd-hardware.info/?probe=41fa3fa6ae) | Jan 28, 2024 |
| Seco          | 0D02 A                      | Desktop     | [076c8b8575](https://bsd-hardware.info/?probe=076c8b8575) | Jan 28, 2024 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [9a1adff9eb](https://bsd-hardware.info/?probe=9a1adff9eb) | Jan 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [94fdaaffaf](https://bsd-hardware.info/?probe=94fdaaffaf) | Jan 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [60507b5afd](https://bsd-hardware.info/?probe=60507b5afd) | Jan 27, 2024 |
| OEM           | 1.0                         | Desktop     | [a6c82ad3f1](https://bsd-hardware.info/?probe=a6c82ad3f1) | Jan 26, 2024 |
| Sophos        | SG                          | Firewall    | [7a20aae305](https://bsd-hardware.info/?probe=7a20aae305) | Jan 25, 2024 |
| PC Engines    | apu4                        | Desktop     | [b3cc677cfa](https://bsd-hardware.info/?probe=b3cc677cfa) | Jan 24, 2024 |
| Dell          | Precision M4700             | Notebook    | [05a9a26c16](https://bsd-hardware.info/?probe=05a9a26c16) | Jan 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [2cd92781d8](https://bsd-hardware.info/?probe=2cd92781d8) | Jan 24, 2024 |
| PC Engines    | APU2                        | Desktop     | [4665b895f7](https://bsd-hardware.info/?probe=4665b895f7) | Jan 24, 2024 |
| Deciso        | Netboard A10                | Desktop     | [cf324e008b](https://bsd-hardware.info/?probe=cf324e008b) | Jan 22, 2024 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [563d52f091](https://bsd-hardware.info/?probe=563d52f091) | Jan 22, 2024 |
| PC Engines    | apu4                        | Desktop     | [0e2082e8dc](https://bsd-hardware.info/?probe=0e2082e8dc) | Jan 22, 2024 |
| PC Engines    | apu4                        | Desktop     | [f36b7e423e](https://bsd-hardware.info/?probe=f36b7e423e) | Jan 22, 2024 |
| MiTAC         | PD11TI AAPD11TI-100         | Desktop     | [71d42d0c05](https://bsd-hardware.info/?probe=71d42d0c05) | Jan 21, 2024 |
| Unknown       | Unknown                     | Notebook    | [6fe553c729](https://bsd-hardware.info/?probe=6fe553c729) | Jan 21, 2024 |
| Unknown       | Unknown                     | Notebook    | [e85605ed72](https://bsd-hardware.info/?probe=e85605ed72) | Jan 21, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [f51a396e5e](https://bsd-hardware.info/?probe=f51a396e5e) | Jan 21, 2024 |
| Dell          | Latitude E7450              | Notebook    | [f2216c5d0f](https://bsd-hardware.info/?probe=f2216c5d0f) | Jan 21, 2024 |
| Protectli     | VP2410 10                   | Desktop     | [e6396f76a1](https://bsd-hardware.info/?probe=e6396f76a1) | Jan 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [4bee671423](https://bsd-hardware.info/?probe=4bee671423) | Jan 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [89747e3a92](https://bsd-hardware.info/?probe=89747e3a92) | Jan 20, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [278905d855](https://bsd-hardware.info/?probe=278905d855) | Jan 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [c1a338bd53](https://bsd-hardware.info/?probe=c1a338bd53) | Jan 20, 2024 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [2f576f617d](https://bsd-hardware.info/?probe=2f576f617d) | Jan 20, 2024 |
| Sophos        | SG                          | Firewall    | [1dd695d794](https://bsd-hardware.info/?probe=1dd695d794) | Jan 20, 2024 |
| AWOW          | AZ51                        | Mini pc     | [f5ad8addfd](https://bsd-hardware.info/?probe=f5ad8addfd) | Jan 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [a944f4d913](https://bsd-hardware.info/?probe=a944f4d913) | Jan 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [b225f25bd6](https://bsd-hardware.info/?probe=b225f25bd6) | Jan 19, 2024 |
| BESSTAR Te... | U820                        | Notebook    | [9d1b8fbbd5](https://bsd-hardware.info/?probe=9d1b8fbbd5) | Jan 18, 2024 |
| BESSTAR Te... | U820                        | Notebook    | [7e38f4e795](https://bsd-hardware.info/?probe=7e38f4e795) | Jan 18, 2024 |
| Supermicro    | X10SLM+-LN4F                | Server      | [36584a392c](https://bsd-hardware.info/?probe=36584a392c) | Jan 17, 2024 |
| HP            | ProLiant DL120 Gen9         | Server      | [aa661caf4f](https://bsd-hardware.info/?probe=aa661caf4f) | Jan 17, 2024 |
| ZX            | H610ITXG                    | Desktop     | [8add6c6c8c](https://bsd-hardware.info/?probe=8add6c6c8c) | Jan 16, 2024 |
| ASRockRack    | W680D4U-2L2T/G5             | Server      | [19838b7ccc](https://bsd-hardware.info/?probe=19838b7ccc) | Jan 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [8cb0bf9ef6](https://bsd-hardware.info/?probe=8cb0bf9ef6) | Jan 16, 2024 |
| Sophos        | UTM                         | Firewall    | [8d4898c463](https://bsd-hardware.info/?probe=8d4898c463) | Jan 16, 2024 |
| PC Engines    | apu4                        | Desktop     | [2c857f37bd](https://bsd-hardware.info/?probe=2c857f37bd) | Jan 15, 2024 |
| PC Engines    | APU2                        | Desktop     | [dd588cfada](https://bsd-hardware.info/?probe=dd588cfada) | Jan 15, 2024 |
| Unknown       | QD-CMU01                    | Desktop     | [f5b7d0415b](https://bsd-hardware.info/?probe=f5b7d0415b) | Jan 15, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [b9653bc7d3](https://bsd-hardware.info/?probe=b9653bc7d3) | Jan 14, 2024 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [6f8d412846](https://bsd-hardware.info/?probe=6f8d412846) | Jan 13, 2024 |
| PC Engines    | apu4                        | Desktop     | [93f07ee3ad](https://bsd-hardware.info/?probe=93f07ee3ad) | Jan 13, 2024 |
| PC Engines    | apu4                        | Desktop     | [aabf377c9a](https://bsd-hardware.info/?probe=aabf377c9a) | Jan 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [37558c7d54](https://bsd-hardware.info/?probe=37558c7d54) | Jan 12, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [023fd3c0ed](https://bsd-hardware.info/?probe=023fd3c0ed) | Jan 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [3ba7f826bb](https://bsd-hardware.info/?probe=3ba7f826bb) | Jan 12, 2024 |
| ASUSTek       | P10S-M Series               | Desktop     | [e9c51e6d9a](https://bsd-hardware.info/?probe=e9c51e6d9a) | Jan 12, 2024 |
| Sophos        | XG                          | Firewall    | [6c7c337b46](https://bsd-hardware.info/?probe=6c7c337b46) | Jan 12, 2024 |
| Unknown       | Unknown                     | Notebook    | [4b22a105d7](https://bsd-hardware.info/?probe=4b22a105d7) | Jan 11, 2024 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [494a88f1ca](https://bsd-hardware.info/?probe=494a88f1ca) | Jan 11, 2024 |
| PC Engines    | apu4                        | Desktop     | [0154684e8f](https://bsd-hardware.info/?probe=0154684e8f) | Jan 11, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f85bbcd879](https://bsd-hardware.info/?probe=f85bbcd879) | Jan 11, 2024 |
| Lenovo        | 312D NOK                    | Mini pc     | [068f7a9c1c](https://bsd-hardware.info/?probe=068f7a9c1c) | Jan 11, 2024 |
| AWOW          | AK10                        | Desktop     | [18ce2740c7](https://bsd-hardware.info/?probe=18ce2740c7) | Jan 10, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [c43a31cf9e](https://bsd-hardware.info/?probe=c43a31cf9e) | Jan 10, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [1dd0e8fc68](https://bsd-hardware.info/?probe=1dd0e8fc68) | Jan 10, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [0f475f8e5d](https://bsd-hardware.info/?probe=0f475f8e5d) | Jan 10, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [6b21d0ae92](https://bsd-hardware.info/?probe=6b21d0ae92) | Jan 09, 2024 |
| Supermicro    | A2SDi-8C-HLN4F              | Server      | [d9e4994892](https://bsd-hardware.info/?probe=d9e4994892) | Jan 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [80a25c3416](https://bsd-hardware.info/?probe=80a25c3416) | Jan 08, 2024 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [7ed7da2383](https://bsd-hardware.info/?probe=7ed7da2383) | Jan 08, 2024 |
| Sophos        | XG                          | Firewall    | [65b6c56556](https://bsd-hardware.info/?probe=65b6c56556) | Jan 08, 2024 |
| SHANGZHAOY... | B85M-PRO V1.1               | Desktop     | [aeed7e4a51](https://bsd-hardware.info/?probe=aeed7e4a51) | Jan 07, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [d2f553598a](https://bsd-hardware.info/?probe=d2f553598a) | Jan 07, 2024 |
| Lanner        | FW-7543 B-GA                | Desktop     | [6687c1ef69](https://bsd-hardware.info/?probe=6687c1ef69) | Jan 07, 2024 |
| ZOTAC         | H67ITX-C-E 02/03/05         | Desktop     | [6aba0c53a6](https://bsd-hardware.info/?probe=6aba0c53a6) | Jan 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [3250ebf7f4](https://bsd-hardware.info/?probe=3250ebf7f4) | Jan 06, 2024 |
| CWWK          | MINIPC-G12                  | Desktop     | [cec3c2ba34](https://bsd-hardware.info/?probe=cec3c2ba34) | Jan 06, 2024 |
| PC Engines    | APU2                        | Desktop     | [680567c89b](https://bsd-hardware.info/?probe=680567c89b) | Jan 05, 2024 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [02161442f5](https://bsd-hardware.info/?probe=02161442f5) | Jan 04, 2024 |
| Sophos        | SG                          | Firewall    | [cd8c505af7](https://bsd-hardware.info/?probe=cd8c505af7) | Jan 04, 2024 |
| Fujitsu       | D2949-B1 S26361-D2949-B1... | Server      | [18538b1bc2](https://bsd-hardware.info/?probe=18538b1bc2) | Jan 03, 2024 |
| Sophos        | SG                          | Firewall    | [f6e7a34edc](https://bsd-hardware.info/?probe=f6e7a34edc) | Jan 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [1fddddcbc7](https://bsd-hardware.info/?probe=1fddddcbc7) | Jan 02, 2024 |
| Unknown       | Unknown                     | Notebook    | [c1d43f83f4](https://bsd-hardware.info/?probe=c1d43f83f4) | Jan 02, 2024 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [6a195bc48f](https://bsd-hardware.info/?probe=6a195bc48f) | Jan 02, 2024 |
| Supermicro    | X11SBA-LN4FA                | Server      | [dbf9225f63](https://bsd-hardware.info/?probe=dbf9225f63) | Dec 31, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [c915c03729](https://bsd-hardware.info/?probe=c915c03729) | Dec 30, 2023 |
| Dell          | 0KYJ8C A00                  | Desktop     | [34246adca9](https://bsd-hardware.info/?probe=34246adca9) | Dec 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [63472bd5e6](https://bsd-hardware.info/?probe=63472bd5e6) | Dec 30, 2023 |
| Intel         | JSL MRD                     | Desktop     | [1c65a367b2](https://bsd-hardware.info/?probe=1c65a367b2) | Dec 30, 2023 |
| Gigabyte      | H110M-D2P-WG-CF             | Desktop     | [77e0d09bf1](https://bsd-hardware.info/?probe=77e0d09bf1) | Dec 29, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [66f7dd1f06](https://bsd-hardware.info/?probe=66f7dd1f06) | Dec 29, 2023 |
| Supermicro    | X8SIE                       | Desktop     | [a7e2e09ef4](https://bsd-hardware.info/?probe=a7e2e09ef4) | Dec 28, 2023 |
| Unknown       | QSKL01                      | Desktop     | [ba39338284](https://bsd-hardware.info/?probe=ba39338284) | Dec 28, 2023 |
| AZW           | EQ                          | Desktop     | [fcbfcb31d5](https://bsd-hardware.info/?probe=fcbfcb31d5) | Dec 28, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [429f1e855f](https://bsd-hardware.info/?probe=429f1e855f) | Dec 27, 2023 |
| ZX            | H610ITXG                    | Desktop     | [8253eb826a](https://bsd-hardware.info/?probe=8253eb826a) | Dec 27, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6f592981ce](https://bsd-hardware.info/?probe=6f592981ce) | Dec 27, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [c2f3692204](https://bsd-hardware.info/?probe=c2f3692204) | Dec 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [b054d33e68](https://bsd-hardware.info/?probe=b054d33e68) | Dec 26, 2023 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [fa5891041a](https://bsd-hardware.info/?probe=fa5891041a) | Dec 26, 2023 |
| Sophos        | UTM                         | Firewall    | [89d19cc2ab](https://bsd-hardware.info/?probe=89d19cc2ab) | Dec 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [23ca4c0419](https://bsd-hardware.info/?probe=23ca4c0419) | Dec 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [72d02dbaa4](https://bsd-hardware.info/?probe=72d02dbaa4) | Dec 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | Notebook    | [b6c3c05155](https://bsd-hardware.info/?probe=b6c3c05155) | Dec 25, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [19c9105326](https://bsd-hardware.info/?probe=19c9105326) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9876dcc6aa](https://bsd-hardware.info/?probe=9876dcc6aa) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9a23873dc4](https://bsd-hardware.info/?probe=9a23873dc4) | Dec 24, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [7ca1ae0c93](https://bsd-hardware.info/?probe=7ca1ae0c93) | Dec 23, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [13699f3359](https://bsd-hardware.info/?probe=13699f3359) | Dec 23, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [ee768bd5a0](https://bsd-hardware.info/?probe=ee768bd5a0) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | Notebook    | [32c06c5669](https://bsd-hardware.info/?probe=32c06c5669) | Dec 23, 2023 |
| Dell          | 03X6X0 A02                  | Server      | [1fc8559747](https://bsd-hardware.info/?probe=1fc8559747) | Dec 23, 2023 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [d8245df746](https://bsd-hardware.info/?probe=d8245df746) | Dec 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [5ed362ce02](https://bsd-hardware.info/?probe=5ed362ce02) | Dec 22, 2023 |
| ZX            | H610ITXG                    | Desktop     | [11edcbeaff](https://bsd-hardware.info/?probe=11edcbeaff) | Dec 22, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [2e35364732](https://bsd-hardware.info/?probe=2e35364732) | Dec 22, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [9eaa02c47c](https://bsd-hardware.info/?probe=9eaa02c47c) | Dec 22, 2023 |
| Supermicro    | X11SSH-LN4F                 | Server      | [132a8d8b6f](https://bsd-hardware.info/?probe=132a8d8b6f) | Dec 21, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [b2597a7f2b](https://bsd-hardware.info/?probe=b2597a7f2b) | Dec 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [ec4c6d8fb5](https://bsd-hardware.info/?probe=ec4c6d8fb5) | Dec 21, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [9a0369cc72](https://bsd-hardware.info/?probe=9a0369cc72) | Dec 21, 2023 |
| Sophos        | UTM                         | Firewall    | [e1e002bdd4](https://bsd-hardware.info/?probe=e1e002bdd4) | Dec 21, 2023 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [094d15625b](https://bsd-hardware.info/?probe=094d15625b) | Dec 21, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [5c6e9bd18a](https://bsd-hardware.info/?probe=5c6e9bd18a) | Dec 20, 2023 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [ec18d4f3a1](https://bsd-hardware.info/?probe=ec18d4f3a1) | Dec 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [f11c353c61](https://bsd-hardware.info/?probe=f11c353c61) | Dec 19, 2023 |
| PC Engines    | apu4                        | Desktop     | [97c6f1ef2a](https://bsd-hardware.info/?probe=97c6f1ef2a) | Dec 19, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [11e5e87b70](https://bsd-hardware.info/?probe=11e5e87b70) | Dec 16, 2023 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [17f70cfb67](https://bsd-hardware.info/?probe=17f70cfb67) | Dec 16, 2023 |
| CSL-Comput... | C15 v3                      | Notebook    | [dd93594896](https://bsd-hardware.info/?probe=dd93594896) | Dec 16, 2023 |
| SHANGZHAOY... | B85M-PRO V1.1               | Desktop     | [3b7ed136da](https://bsd-hardware.info/?probe=3b7ed136da) | Dec 16, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [aefb80936c](https://bsd-hardware.info/?probe=aefb80936c) | Dec 15, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [f05a97db34](https://bsd-hardware.info/?probe=f05a97db34) | Dec 15, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [343d176e9c](https://bsd-hardware.info/?probe=343d176e9c) | Dec 15, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [7a32a123f6](https://bsd-hardware.info/?probe=7a32a123f6) | Dec 15, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [b6845a3e54](https://bsd-hardware.info/?probe=b6845a3e54) | Dec 15, 2023 |
| AZW           | EQ                          | Desktop     | [f1e4bf2224](https://bsd-hardware.info/?probe=f1e4bf2224) | Dec 15, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [c197b26909](https://bsd-hardware.info/?probe=c197b26909) | Dec 14, 2023 |
| Dell          | Latitude E6540              | Notebook    | [77a9b10ab9](https://bsd-hardware.info/?probe=77a9b10ab9) | Dec 13, 2023 |
| Sophos        | SG                          | Firewall    | [13c711aabf](https://bsd-hardware.info/?probe=13c711aabf) | Dec 13, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b5f9416c13](https://bsd-hardware.info/?probe=b5f9416c13) | Dec 12, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [20dd6f1621](https://bsd-hardware.info/?probe=20dd6f1621) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [8a0a469ad0](https://bsd-hardware.info/?probe=8a0a469ad0) | Dec 12, 2023 |
| SHANGZHAOY... | B85M-PRO V1.1               | Desktop     | [5cf5db5a05](https://bsd-hardware.info/?probe=5cf5db5a05) | Dec 11, 2023 |
| Dell          | 08CYF7 A05                  | Server      | [2768b91142](https://bsd-hardware.info/?probe=2768b91142) | Dec 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9a3a20d295](https://bsd-hardware.info/?probe=9a3a20d295) | Dec 11, 2023 |
| Supermicro    | X10SBAA                     | Server      | [f68b2d784b](https://bsd-hardware.info/?probe=f68b2d784b) | Dec 10, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [b6a4782cbf](https://bsd-hardware.info/?probe=b6a4782cbf) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [47480f848d](https://bsd-hardware.info/?probe=47480f848d) | Dec 10, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [d62ad0d622](https://bsd-hardware.info/?probe=d62ad0d622) | Dec 09, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [0fe56565dc](https://bsd-hardware.info/?probe=0fe56565dc) | Dec 09, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [39e0078d08](https://bsd-hardware.info/?probe=39e0078d08) | Dec 09, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [6b4d8c076f](https://bsd-hardware.info/?probe=6b4d8c076f) | Dec 09, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [5b31c551ae](https://bsd-hardware.info/?probe=5b31c551ae) | Dec 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [31619d30b3](https://bsd-hardware.info/?probe=31619d30b3) | Dec 09, 2023 |
| PC Engines    | APU2                        | Desktop     | [8f318ea168](https://bsd-hardware.info/?probe=8f318ea168) | Dec 09, 2023 |
| PC Engines    | APU2                        | Desktop     | [ca43be99fc](https://bsd-hardware.info/?probe=ca43be99fc) | Dec 08, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [eb2eef3d17](https://bsd-hardware.info/?probe=eb2eef3d17) | Dec 08, 2023 |
| PC Engines    | apu4                        | Desktop     | [cdbac53ff6](https://bsd-hardware.info/?probe=cdbac53ff6) | Dec 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [efab62c197](https://bsd-hardware.info/?probe=efab62c197) | Dec 07, 2023 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [d3898c1e39](https://bsd-hardware.info/?probe=d3898c1e39) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [fed92c23db](https://bsd-hardware.info/?probe=fed92c23db) | Dec 07, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [7476cc6440](https://bsd-hardware.info/?probe=7476cc6440) | Dec 06, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [3784a39a41](https://bsd-hardware.info/?probe=3784a39a41) | Dec 06, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [52605948b7](https://bsd-hardware.info/?probe=52605948b7) | Dec 06, 2023 |
| PC Engines    | APU3                        | Desktop     | [06a4e1c23b](https://bsd-hardware.info/?probe=06a4e1c23b) | Dec 06, 2023 |
| PC Engines    | apu4                        | Desktop     | [04dd506405](https://bsd-hardware.info/?probe=04dd506405) | Dec 06, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9d54a02c53](https://bsd-hardware.info/?probe=9d54a02c53) | Dec 05, 2023 |
| Yanling       | YL-KBRL2 Series Ver:1.02    | Desktop     | [3bd3f01055](https://bsd-hardware.info/?probe=3bd3f01055) | Dec 05, 2023 |
| HP            | 8103 A01                    | Mini pc     | [f558be71a3](https://bsd-hardware.info/?probe=f558be71a3) | Dec 05, 2023 |
| HP            | 8103 A01                    | Mini pc     | [a71bdf2036](https://bsd-hardware.info/?probe=a71bdf2036) | Dec 05, 2023 |
| Wortmann      | TERRA_MOBILE_1541           | Notebook    | [63f1a71855](https://bsd-hardware.info/?probe=63f1a71855) | Dec 04, 2023 |
| HP            | 8103 A01                    | Mini pc     | [0da20332e6](https://bsd-hardware.info/?probe=0da20332e6) | Dec 04, 2023 |
| Protectli     | FW2B Ver                    | Desktop     | [9ae293de1b](https://bsd-hardware.info/?probe=9ae293de1b) | Dec 03, 2023 |
| Protectli     | VP2420                      | Desktop     | [31b70f1d0d](https://bsd-hardware.info/?probe=31b70f1d0d) | Dec 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [f23df632e4](https://bsd-hardware.info/?probe=f23df632e4) | Dec 03, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [8a6ce136cc](https://bsd-hardware.info/?probe=8a6ce136cc) | Dec 03, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [150fd26797](https://bsd-hardware.info/?probe=150fd26797) | Dec 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [5efe3ae6f9](https://bsd-hardware.info/?probe=5efe3ae6f9) | Dec 01, 2023 |
| Protectli     | VP2420                      | Desktop     | [4d59cef5e8](https://bsd-hardware.info/?probe=4d59cef5e8) | Nov 30, 2023 |
| Intel         | JSL MRD                     | Desktop     | [0ec285953e](https://bsd-hardware.info/?probe=0ec285953e) | Nov 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [7d3416a30f](https://bsd-hardware.info/?probe=7d3416a30f) | Nov 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [e5be2bebf5](https://bsd-hardware.info/?probe=e5be2bebf5) | Nov 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [9579521c83](https://bsd-hardware.info/?probe=9579521c83) | Nov 30, 2023 |
| Intel         | JSL MRD                     | Desktop     | [f8beb1caa9](https://bsd-hardware.info/?probe=f8beb1caa9) | Nov 30, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [e31a43fc53](https://bsd-hardware.info/?probe=e31a43fc53) | Nov 30, 2023 |
| Yanling       | YL-ALU6L                    | Desktop     | [21135d9aa5](https://bsd-hardware.info/?probe=21135d9aa5) | Nov 29, 2023 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [e98e7bcab5](https://bsd-hardware.info/?probe=e98e7bcab5) | Nov 29, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [895be1e0cd](https://bsd-hardware.info/?probe=895be1e0cd) | Nov 28, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [61bf87efe4](https://bsd-hardware.info/?probe=61bf87efe4) | Nov 28, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [a2a08d6eec](https://bsd-hardware.info/?probe=a2a08d6eec) | Nov 28, 2023 |
| CNCTION-IA... | Unknown                     | Desktop     | [1b4871792b](https://bsd-hardware.info/?probe=1b4871792b) | Nov 28, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [fa32eea2ff](https://bsd-hardware.info/?probe=fa32eea2ff) | Nov 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [55339dbfab](https://bsd-hardware.info/?probe=55339dbfab) | Nov 26, 2023 |
| PC Engines    | APU2                        | Desktop     | [c2ab63093b](https://bsd-hardware.info/?probe=c2ab63093b) | Nov 25, 2023 |
| ASRock        | H570M-ITX/ac                | Desktop     | [a8d3950959](https://bsd-hardware.info/?probe=a8d3950959) | Nov 25, 2023 |
| HP            | 1825                        | Desktop     | [373a147d04](https://bsd-hardware.info/?probe=373a147d04) | Nov 24, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7bb170248d](https://bsd-hardware.info/?probe=7bb170248d) | Nov 24, 2023 |
| Dell          | 0F0XJ6 A13                  | Server      | [f4a31a2e53](https://bsd-hardware.info/?probe=f4a31a2e53) | Nov 24, 2023 |
| PICO PC       | MNHO-113                    | Desktop     | [261b0d936c](https://bsd-hardware.info/?probe=261b0d936c) | Nov 23, 2023 |
| Sophos        | XG                          | Firewall    | [a0539d33da](https://bsd-hardware.info/?probe=a0539d33da) | Nov 23, 2023 |
| Dell          | 00P8G1 A00                  | All in one  | [daca9b37fd](https://bsd-hardware.info/?probe=daca9b37fd) | Nov 23, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [eca8e8785c](https://bsd-hardware.info/?probe=eca8e8785c) | Nov 22, 2023 |
| AZW           | EQ                          | Desktop     | [3407ab2a5b](https://bsd-hardware.info/?probe=3407ab2a5b) | Nov 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [87ab49a51e](https://bsd-hardware.info/?probe=87ab49a51e) | Nov 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [b60795e523](https://bsd-hardware.info/?probe=b60795e523) | Nov 22, 2023 |
| Thomas-Kre... | LES network 6L              | Desktop     | [654e4f96f7](https://bsd-hardware.info/?probe=654e4f96f7) | Nov 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [ff855b549e](https://bsd-hardware.info/?probe=ff855b549e) | Nov 20, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d38d698b2e](https://bsd-hardware.info/?probe=d38d698b2e) | Nov 20, 2023 |
| Intel         | ND2X-NET-PC BIOS Revisio... | Desktop     | [7fd080cf42](https://bsd-hardware.info/?probe=7fd080cf42) | Nov 19, 2023 |
| Panasonic     | CF-31-5                     | Notebook    | [8771ab6139](https://bsd-hardware.info/?probe=8771ab6139) | Nov 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bd12235645](https://bsd-hardware.info/?probe=bd12235645) | Nov 18, 2023 |
| Deciso        | Netboard A10                | Desktop     | [5efc270fa6](https://bsd-hardware.info/?probe=5efc270fa6) | Nov 18, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [947076a4de](https://bsd-hardware.info/?probe=947076a4de) | Nov 18, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [07dbd58d8e](https://bsd-hardware.info/?probe=07dbd58d8e) | Nov 17, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [9061ad4228](https://bsd-hardware.info/?probe=9061ad4228) | Nov 17, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [984f5f2f4b](https://bsd-hardware.info/?probe=984f5f2f4b) | Nov 16, 2023 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [a406ee9805](https://bsd-hardware.info/?probe=a406ee9805) | Nov 16, 2023 |
| PC Engines    | APU2                        | Desktop     | [5ea4af0d94](https://bsd-hardware.info/?probe=5ea4af0d94) | Nov 16, 2023 |
| Intel         | QHSW02                      | Desktop     | [f05cdb2841](https://bsd-hardware.info/?probe=f05cdb2841) | Nov 15, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [e5f0053202](https://bsd-hardware.info/?probe=e5f0053202) | Nov 15, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7719e7606c](https://bsd-hardware.info/?probe=7719e7606c) | Nov 15, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6257d05c99](https://bsd-hardware.info/?probe=6257d05c99) | Nov 15, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [e98965d0f9](https://bsd-hardware.info/?probe=e98965d0f9) | Nov 14, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [0f82d77235](https://bsd-hardware.info/?probe=0f82d77235) | Nov 14, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [fec17c799c](https://bsd-hardware.info/?probe=fec17c799c) | Nov 14, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [8b2811bcf5](https://bsd-hardware.info/?probe=8b2811bcf5) | Nov 14, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [4984b1536a](https://bsd-hardware.info/?probe=4984b1536a) | Nov 14, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [5d9467ed74](https://bsd-hardware.info/?probe=5d9467ed74) | Nov 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [d6f10bf9d2](https://bsd-hardware.info/?probe=d6f10bf9d2) | Nov 13, 2023 |
| Dell          | 015HP0 A00                  | Mini pc     | [b282285d51](https://bsd-hardware.info/?probe=b282285d51) | Nov 13, 2023 |
| Dell          | 015HP0 A00                  | Mini pc     | [2c1f962756](https://bsd-hardware.info/?probe=2c1f962756) | Nov 13, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [49089c64bf](https://bsd-hardware.info/?probe=49089c64bf) | Nov 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [d8cc007961](https://bsd-hardware.info/?probe=d8cc007961) | Nov 12, 2023 |
| PC Engines    | APU3                        | Desktop     | [0c58a923fe](https://bsd-hardware.info/?probe=0c58a923fe) | Nov 12, 2023 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [2f916d0780](https://bsd-hardware.info/?probe=2f916d0780) | Nov 12, 2023 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [faf46e5802](https://bsd-hardware.info/?probe=faf46e5802) | Nov 11, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [9bab52c825](https://bsd-hardware.info/?probe=9bab52c825) | Nov 11, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [da0816e168](https://bsd-hardware.info/?probe=da0816e168) | Nov 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6afb2cc33f](https://bsd-hardware.info/?probe=6afb2cc33f) | Nov 10, 2023 |
| Dell          | 045M96 A02                  | Server      | [afd35f3afa](https://bsd-hardware.info/?probe=afd35f3afa) | Nov 09, 2023 |
| Sophos        | SG                          | Firewall    | [042fb4f2e1](https://bsd-hardware.info/?probe=042fb4f2e1) | Nov 09, 2023 |
| Sophos        | SG                          | Firewall    | [396d8e0dca](https://bsd-hardware.info/?probe=396d8e0dca) | Nov 09, 2023 |
| Sophos        | UTM                         | Firewall    | [8b26d81a35](https://bsd-hardware.info/?probe=8b26d81a35) | Nov 08, 2023 |
| Sophos        | UTM                         | Firewall    | [6d031ab91e](https://bsd-hardware.info/?probe=6d031ab91e) | Nov 08, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [7b3740b7c0](https://bsd-hardware.info/?probe=7b3740b7c0) | Nov 08, 2023 |
| ZOTAC         | ZBOX-MI643/MI623 Rev.00     | Mini pc     | [709dd91ea2](https://bsd-hardware.info/?probe=709dd91ea2) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [700d52c2dd](https://bsd-hardware.info/?probe=700d52c2dd) | Nov 07, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [2c085953ca](https://bsd-hardware.info/?probe=2c085953ca) | Nov 07, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [df41e8f6b2](https://bsd-hardware.info/?probe=df41e8f6b2) | Nov 07, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [cf8fb90fe0](https://bsd-hardware.info/?probe=cf8fb90fe0) | Nov 07, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [5a26b6b1f5](https://bsd-hardware.info/?probe=5a26b6b1f5) | Nov 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [61c7e94f23](https://bsd-hardware.info/?probe=61c7e94f23) | Nov 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [316be7bb33](https://bsd-hardware.info/?probe=316be7bb33) | Nov 06, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [dc54c810d3](https://bsd-hardware.info/?probe=dc54c810d3) | Nov 06, 2023 |
| MSI           | Z270 PC MATE                | Desktop     | [9686c20980](https://bsd-hardware.info/?probe=9686c20980) | Nov 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [b4c8864cef](https://bsd-hardware.info/?probe=b4c8864cef) | Nov 06, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [456fe0a275](https://bsd-hardware.info/?probe=456fe0a275) | Nov 06, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a26912fd0d](https://bsd-hardware.info/?probe=a26912fd0d) | Nov 06, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [4f9885c454](https://bsd-hardware.info/?probe=4f9885c454) | Nov 05, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [ea78913e4c](https://bsd-hardware.info/?probe=ea78913e4c) | Nov 05, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [38b5f3b9ad](https://bsd-hardware.info/?probe=38b5f3b9ad) | Nov 04, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [86aa07c0ae](https://bsd-hardware.info/?probe=86aa07c0ae) | Nov 04, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [a9448cf3b5](https://bsd-hardware.info/?probe=a9448cf3b5) | Nov 04, 2023 |
| ASRock        | B365M-HDV                   | Desktop     | [368366454f](https://bsd-hardware.info/?probe=368366454f) | Nov 03, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [19514dd0bd](https://bsd-hardware.info/?probe=19514dd0bd) | Nov 03, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [e6927b5eb8](https://bsd-hardware.info/?probe=e6927b5eb8) | Nov 03, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [13eb07060d](https://bsd-hardware.info/?probe=13eb07060d) | Nov 03, 2023 |
| PC Engines    | apu4                        | Desktop     | [b85acbe43d](https://bsd-hardware.info/?probe=b85acbe43d) | Nov 03, 2023 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | Desktop     | [d4298a293f](https://bsd-hardware.info/?probe=d4298a293f) | Nov 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b038d8a95d](https://bsd-hardware.info/?probe=b038d8a95d) | Nov 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [691338cb44](https://bsd-hardware.info/?probe=691338cb44) | Nov 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [c6610a58ac](https://bsd-hardware.info/?probe=c6610a58ac) | Nov 02, 2023 |
| PICO PC       | MNHO-113                    | Desktop     | [a4175476a0](https://bsd-hardware.info/?probe=a4175476a0) | Nov 02, 2023 |
| Sophos        | SG                          | Firewall    | [24994d8e2f](https://bsd-hardware.info/?probe=24994d8e2f) | Nov 02, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [8d3cf4e648](https://bsd-hardware.info/?probe=8d3cf4e648) | Nov 01, 2023 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [2fcac7d927](https://bsd-hardware.info/?probe=2fcac7d927) | Nov 01, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [41c4097002](https://bsd-hardware.info/?probe=41c4097002) | Oct 30, 2023 |
| Sophos        | SG                          | Firewall    | [f9c46ab5cb](https://bsd-hardware.info/?probe=f9c46ab5cb) | Oct 30, 2023 |
| AZW           | EQ                          | Desktop     | [034b060507](https://bsd-hardware.info/?probe=034b060507) | Oct 30, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ec852f7037](https://bsd-hardware.info/?probe=ec852f7037) | Oct 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c774066857](https://bsd-hardware.info/?probe=c774066857) | Oct 28, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [fc42f6db17](https://bsd-hardware.info/?probe=fc42f6db17) | Oct 28, 2023 |
| HP            | 1825                        | Desktop     | [8a0a258efc](https://bsd-hardware.info/?probe=8a0a258efc) | Oct 28, 2023 |
| Lenovo        | ThinkPad X230 23205UG       | Notebook    | [f204abc5fc](https://bsd-hardware.info/?probe=f204abc5fc) | Oct 28, 2023 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [6448ed1b12](https://bsd-hardware.info/?probe=6448ed1b12) | Oct 28, 2023 |
| IGEL Techn... | D220                        | Desktop     | [3478db91ef](https://bsd-hardware.info/?probe=3478db91ef) | Oct 28, 2023 |
| Supermicro    | X11SSH-F                    | Desktop     | [73160cea1d](https://bsd-hardware.info/?probe=73160cea1d) | Oct 28, 2023 |
| Intel         | NUC11TNBi3 M11908-500       | Mini pc     | [72634e7285](https://bsd-hardware.info/?probe=72634e7285) | Oct 28, 2023 |
| Protectli     | FW4B                        | Desktop     | [23c31e7f9f](https://bsd-hardware.info/?probe=23c31e7f9f) | Oct 27, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [5d64d42233](https://bsd-hardware.info/?probe=5d64d42233) | Oct 27, 2023 |
| Fujitsu       | D3314-E1 S26361-D3314-E1    | Desktop     | [2cde7906c1](https://bsd-hardware.info/?probe=2cde7906c1) | Oct 27, 2023 |
| Fujitsu       | D3314-A1 S26361-D3314-A1    | Desktop     | [d005339b5f](https://bsd-hardware.info/?probe=d005339b5f) | Oct 27, 2023 |
| Sophos        | UTM                         | Firewall    | [b6232a012b](https://bsd-hardware.info/?probe=b6232a012b) | Oct 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [fe3d35aef8](https://bsd-hardware.info/?probe=fe3d35aef8) | Oct 27, 2023 |
| PC Engines    | apu4                        | Desktop     | [7bbd252741](https://bsd-hardware.info/?probe=7bbd252741) | Oct 27, 2023 |
| Acer          | Veriton X4620G v1.0         | Desktop     | [bc374cdc01](https://bsd-hardware.info/?probe=bc374cdc01) | Oct 26, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [17cdba9414](https://bsd-hardware.info/?probe=17cdba9414) | Oct 26, 2023 |
| Dell          | 0PRWNC A05                  | Server      | [9b44f96ab2](https://bsd-hardware.info/?probe=9b44f96ab2) | Oct 26, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [09cf753c7a](https://bsd-hardware.info/?probe=09cf753c7a) | Oct 26, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [0d97ba1ab0](https://bsd-hardware.info/?probe=0d97ba1ab0) | Oct 24, 2023 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [dcd8b6e432](https://bsd-hardware.info/?probe=dcd8b6e432) | Oct 24, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [dea9eee8a4](https://bsd-hardware.info/?probe=dea9eee8a4) | Oct 24, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [38b1931562](https://bsd-hardware.info/?probe=38b1931562) | Oct 24, 2023 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [cca1027ab8](https://bsd-hardware.info/?probe=cca1027ab8) | Oct 23, 2023 |
| AZW           | EQ                          | Desktop     | [8cb6ac80d2](https://bsd-hardware.info/?probe=8cb6ac80d2) | Oct 23, 2023 |
| HP            | 8103 A01                    | Mini pc     | [9740c7419d](https://bsd-hardware.info/?probe=9740c7419d) | Oct 23, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [3192ead8b5](https://bsd-hardware.info/?probe=3192ead8b5) | Oct 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [7a57e0a112](https://bsd-hardware.info/?probe=7a57e0a112) | Oct 21, 2023 |
| Sophos        | SG                          | Firewall    | [411f124671](https://bsd-hardware.info/?probe=411f124671) | Oct 21, 2023 |
| Supermicro    | X11SBA-LN4FA                | Server      | [682d4aec9e](https://bsd-hardware.info/?probe=682d4aec9e) | Oct 20, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [8943e5449f](https://bsd-hardware.info/?probe=8943e5449f) | Oct 20, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b91ffc9125](https://bsd-hardware.info/?probe=b91ffc9125) | Oct 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [363b63c1a1](https://bsd-hardware.info/?probe=363b63c1a1) | Oct 18, 2023 |
| Sophos        | SG                          | Firewall    | [164161ab82](https://bsd-hardware.info/?probe=164161ab82) | Oct 18, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [4a39ad1a98](https://bsd-hardware.info/?probe=4a39ad1a98) | Oct 18, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [d69749afe5](https://bsd-hardware.info/?probe=d69749afe5) | Oct 18, 2023 |
| Sophos        | SG                          | Firewall    | [2ee4ce0769](https://bsd-hardware.info/?probe=2ee4ce0769) | Oct 17, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [eadbd154ab](https://bsd-hardware.info/?probe=eadbd154ab) | Oct 16, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [f927cf5ba4](https://bsd-hardware.info/?probe=f927cf5ba4) | Oct 16, 2023 |
| PC Engines    | APU2                        | Desktop     | [7fb59a92f0](https://bsd-hardware.info/?probe=7fb59a92f0) | Oct 16, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [5a15dd2166](https://bsd-hardware.info/?probe=5a15dd2166) | Oct 15, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [abe8593d6e](https://bsd-hardware.info/?probe=abe8593d6e) | Oct 15, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [4fc886d589](https://bsd-hardware.info/?probe=4fc886d589) | Oct 15, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [eb383d6f22](https://bsd-hardware.info/?probe=eb383d6f22) | Oct 15, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [72a9b731f6](https://bsd-hardware.info/?probe=72a9b731f6) | Oct 14, 2023 |
| Supermicro    | A1SRi-2758F                 | Mini pc     | [88725f5ed5](https://bsd-hardware.info/?probe=88725f5ed5) | Oct 14, 2023 |
| Sophos        | SG                          | Firewall    | [93d1eca671](https://bsd-hardware.info/?probe=93d1eca671) | Oct 14, 2023 |
| Deciso        | Netboard A20                | Notebook    | [879efbe255](https://bsd-hardware.info/?probe=879efbe255) | Oct 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [248c73db22](https://bsd-hardware.info/?probe=248c73db22) | Oct 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [77a827631b](https://bsd-hardware.info/?probe=77a827631b) | Oct 13, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [8b0d009cc4](https://bsd-hardware.info/?probe=8b0d009cc4) | Oct 13, 2023 |
| Sophos        | SG                          | Firewall    | [896045150c](https://bsd-hardware.info/?probe=896045150c) | Oct 13, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [65acf27cad](https://bsd-hardware.info/?probe=65acf27cad) | Oct 13, 2023 |
| Dell          | 08CYF7 A05                  | Server      | [6b8bbc4ad9](https://bsd-hardware.info/?probe=6b8bbc4ad9) | Oct 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [516eda52f0](https://bsd-hardware.info/?probe=516eda52f0) | Oct 12, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [bb82c13e39](https://bsd-hardware.info/?probe=bb82c13e39) | Oct 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [418d78095d](https://bsd-hardware.info/?probe=418d78095d) | Oct 12, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [f3b384d87a](https://bsd-hardware.info/?probe=f3b384d87a) | Oct 12, 2023 |
| Lenovo        | ThinkPad X250 20CM004VFR    | Notebook    | [e4ab2acd8d](https://bsd-hardware.info/?probe=e4ab2acd8d) | Oct 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [30ec824cf5](https://bsd-hardware.info/?probe=30ec824cf5) | Oct 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [3d5abb3996](https://bsd-hardware.info/?probe=3d5abb3996) | Oct 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4faecc5e8](https://bsd-hardware.info/?probe=e4faecc5e8) | Oct 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [5031b0a5a7](https://bsd-hardware.info/?probe=5031b0a5a7) | Oct 10, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [cf15e11738](https://bsd-hardware.info/?probe=cf15e11738) | Oct 10, 2023 |
| Unknown       | QD-CMU01                    | Desktop     | [8637821e57](https://bsd-hardware.info/?probe=8637821e57) | Oct 09, 2023 |
| Sophos        | UTM                         | Firewall    | [002d6256fa](https://bsd-hardware.info/?probe=002d6256fa) | Oct 09, 2023 |
| ASRock        | A75M-HVS                    | Desktop     | [93709074ae](https://bsd-hardware.info/?probe=93709074ae) | Oct 09, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [862d0bbe4d](https://bsd-hardware.info/?probe=862d0bbe4d) | Oct 08, 2023 |
| Sophos        | SG                          | Firewall    | [2e19b2128b](https://bsd-hardware.info/?probe=2e19b2128b) | Oct 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [57e5ab8786](https://bsd-hardware.info/?probe=57e5ab8786) | Oct 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f7ab105e3](https://bsd-hardware.info/?probe=1f7ab105e3) | Oct 08, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [11b0d7b64f](https://bsd-hardware.info/?probe=11b0d7b64f) | Oct 07, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [d7a7e7338f](https://bsd-hardware.info/?probe=d7a7e7338f) | Oct 07, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e3141878a9](https://bsd-hardware.info/?probe=e3141878a9) | Oct 07, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [dffb96790c](https://bsd-hardware.info/?probe=dffb96790c) | Oct 06, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [91b63fa5c7](https://bsd-hardware.info/?probe=91b63fa5c7) | Oct 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [31c7e1d3f3](https://bsd-hardware.info/?probe=31c7e1d3f3) | Oct 06, 2023 |
| Deciso        | Netboard A8                 | Desktop     | [cf3b678212](https://bsd-hardware.info/?probe=cf3b678212) | Oct 06, 2023 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [5b33d7b22e](https://bsd-hardware.info/?probe=5b33d7b22e) | Oct 04, 2023 |
| PC Engines    | APU2                        | Desktop     | [626d74b530](https://bsd-hardware.info/?probe=626d74b530) | Oct 04, 2023 |
| PC Engines    | apu4                        | Desktop     | [0e813a0050](https://bsd-hardware.info/?probe=0e813a0050) | Oct 04, 2023 |
| Sophos        | SG                          | Firewall    | [c91ad52ddf](https://bsd-hardware.info/?probe=c91ad52ddf) | Oct 04, 2023 |
| Dell          | Latitude 5591               | Notebook    | [8f6ca1e82a](https://bsd-hardware.info/?probe=8f6ca1e82a) | Oct 03, 2023 |
| Fujitsu       | D2863 S26361-D2863-A10 W... | Server      | [f2d65698fb](https://bsd-hardware.info/?probe=f2d65698fb) | Oct 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [f5e7677e76](https://bsd-hardware.info/?probe=f5e7677e76) | Oct 01, 2023 |
| PC Engines    | APU2                        | Desktop     | [064fd13617](https://bsd-hardware.info/?probe=064fd13617) | Oct 01, 2023 |
| Sophos        | SG                          | Firewall    | [40e14eca4b](https://bsd-hardware.info/?probe=40e14eca4b) | Oct 01, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [5524017014](https://bsd-hardware.info/?probe=5524017014) | Oct 01, 2023 |
| Sophos        | SG                          | Firewall    | [13acf2a462](https://bsd-hardware.info/?probe=13acf2a462) | Oct 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [7cfd3d40eb](https://bsd-hardware.info/?probe=7cfd3d40eb) | Sep 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [716f9b28ab](https://bsd-hardware.info/?probe=716f9b28ab) | Sep 30, 2023 |
| Sophos        | SG                          | Firewall    | [c46ccbd5b9](https://bsd-hardware.info/?probe=c46ccbd5b9) | Sep 30, 2023 |
| Sophos        | SG                          | Firewall    | [1429a7de9a](https://bsd-hardware.info/?probe=1429a7de9a) | Sep 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [fb21a44f71](https://bsd-hardware.info/?probe=fb21a44f71) | Sep 29, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [f50d617197](https://bsd-hardware.info/?probe=f50d617197) | Sep 28, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [31da8655d1](https://bsd-hardware.info/?probe=31da8655d1) | Sep 28, 2023 |
| Dell          | Latitude 5591               | Notebook    | [c30943def8](https://bsd-hardware.info/?probe=c30943def8) | Sep 28, 2023 |
| Sophos        | SG                          | Firewall    | [e6a4159f0c](https://bsd-hardware.info/?probe=e6a4159f0c) | Sep 28, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [b3f0a784ab](https://bsd-hardware.info/?probe=b3f0a784ab) | Sep 28, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [0b2b7195c1](https://bsd-hardware.info/?probe=0b2b7195c1) | Sep 26, 2023 |
| Unknown       | YL-J1900L4-V2               | Desktop     | [c186f8b50c](https://bsd-hardware.info/?probe=c186f8b50c) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [1ba135fef1](https://bsd-hardware.info/?probe=1ba135fef1) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c8516c8a8](https://bsd-hardware.info/?probe=9c8516c8a8) | Sep 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [6a2ce1e29f](https://bsd-hardware.info/?probe=6a2ce1e29f) | Sep 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [b31f8c12f8](https://bsd-hardware.info/?probe=b31f8c12f8) | Sep 24, 2023 |
| NU591         | 1.0                         | Desktop     | [99f3260ee0](https://bsd-hardware.info/?probe=99f3260ee0) | Sep 24, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [d99ed8ecd0](https://bsd-hardware.info/?probe=d99ed8ecd0) | Sep 23, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [80f0800cee](https://bsd-hardware.info/?probe=80f0800cee) | Sep 23, 2023 |
| PC Engines    | APU2                        | Desktop     | [3c7bd005ef](https://bsd-hardware.info/?probe=3c7bd005ef) | Sep 23, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [06d8f02eb7](https://bsd-hardware.info/?probe=06d8f02eb7) | Sep 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [16640c7f04](https://bsd-hardware.info/?probe=16640c7f04) | Sep 22, 2023 |
| Sophos        | SG                          | Firewall    | [54ff756b5b](https://bsd-hardware.info/?probe=54ff756b5b) | Sep 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [fcde651e99](https://bsd-hardware.info/?probe=fcde651e99) | Sep 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [e046bd9405](https://bsd-hardware.info/?probe=e046bd9405) | Sep 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [90f89eea16](https://bsd-hardware.info/?probe=90f89eea16) | Sep 21, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [c5a2093552](https://bsd-hardware.info/?probe=c5a2093552) | Sep 21, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [de1bdf0601](https://bsd-hardware.info/?probe=de1bdf0601) | Sep 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [e84cddfaaf](https://bsd-hardware.info/?probe=e84cddfaaf) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [3c479d7824](https://bsd-hardware.info/?probe=3c479d7824) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [13ba11c952](https://bsd-hardware.info/?probe=13ba11c952) | Sep 20, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [92da10b93b](https://bsd-hardware.info/?probe=92da10b93b) | Sep 20, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [95286f41d9](https://bsd-hardware.info/?probe=95286f41d9) | Sep 19, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [3950a0580d](https://bsd-hardware.info/?probe=3950a0580d) | Sep 16, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [029b3cdd58](https://bsd-hardware.info/?probe=029b3cdd58) | Sep 16, 2023 |
| Dell          | 0R5KP9 A09                  | Server      | [54ff0b9d41](https://bsd-hardware.info/?probe=54ff0b9d41) | Sep 16, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [80707f8712](https://bsd-hardware.info/?probe=80707f8712) | Sep 16, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9a30d2d88c](https://bsd-hardware.info/?probe=9a30d2d88c) | Sep 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [1808e7891c](https://bsd-hardware.info/?probe=1808e7891c) | Sep 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [d6acb378a1](https://bsd-hardware.info/?probe=d6acb378a1) | Sep 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [fe010506e6](https://bsd-hardware.info/?probe=fe010506e6) | Sep 15, 2023 |
| Alienware     | m15                         | Notebook    | [609d2ce1ce](https://bsd-hardware.info/?probe=609d2ce1ce) | Sep 14, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [227062e965](https://bsd-hardware.info/?probe=227062e965) | Sep 13, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [0068732d33](https://bsd-hardware.info/?probe=0068732d33) | Sep 13, 2023 |
| Dell          | 0KM5PX A02                  | Server      | [2028895de0](https://bsd-hardware.info/?probe=2028895de0) | Sep 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [5c89a7a1f1](https://bsd-hardware.info/?probe=5c89a7a1f1) | Sep 13, 2023 |
| HP            | ProBook 4530s               | Notebook    | [0b47c15c42](https://bsd-hardware.info/?probe=0b47c15c42) | Sep 12, 2023 |
| HP            | ProBook 4530s               | Notebook    | [4b6daa1f1c](https://bsd-hardware.info/?probe=4b6daa1f1c) | Sep 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [fd131bd648](https://bsd-hardware.info/?probe=fd131bd648) | Sep 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [0797783a1c](https://bsd-hardware.info/?probe=0797783a1c) | Sep 10, 2023 |
| Supermicro    | A1SRi-2558F                 | Mini pc     | [04e0638cca](https://bsd-hardware.info/?probe=04e0638cca) | Sep 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [3c85271913](https://bsd-hardware.info/?probe=3c85271913) | Sep 10, 2023 |
| HP            | 8103 A01                    | Mini pc     | [ff26b688eb](https://bsd-hardware.info/?probe=ff26b688eb) | Sep 09, 2023 |
| Apple         | PowerMac3,6                 | Desktop     | [36daf7ce75](https://bsd-hardware.info/?probe=36daf7ce75) | Sep 09, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [3bc1fc9c7b](https://bsd-hardware.info/?probe=3bc1fc9c7b) | Sep 09, 2023 |
| Sophos        | XG                          | Firewall    | [01ed655ea2](https://bsd-hardware.info/?probe=01ed655ea2) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [68a0e23945](https://bsd-hardware.info/?probe=68a0e23945) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fe6bcbc332](https://bsd-hardware.info/?probe=fe6bcbc332) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [37e25cbcec](https://bsd-hardware.info/?probe=37e25cbcec) | Sep 08, 2023 |
| Lex           | Pineview-D                  | Desktop     | [351aabdb80](https://bsd-hardware.info/?probe=351aabdb80) | Sep 08, 2023 |
| PC Engines    | APU3                        | Desktop     | [ad38dcf54a](https://bsd-hardware.info/?probe=ad38dcf54a) | Sep 07, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [451cfdf64f](https://bsd-hardware.info/?probe=451cfdf64f) | Sep 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [6361addd62](https://bsd-hardware.info/?probe=6361addd62) | Sep 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [48ca84af37](https://bsd-hardware.info/?probe=48ca84af37) | Sep 06, 2023 |
| PC Engines    | APU2                        | Desktop     | [d582e62190](https://bsd-hardware.info/?probe=d582e62190) | Sep 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [f757c58686](https://bsd-hardware.info/?probe=f757c58686) | Sep 05, 2023 |
| Dell          | 0PRWNC A05                  | Server      | [ded67b8cd6](https://bsd-hardware.info/?probe=ded67b8cd6) | Sep 04, 2023 |
| Dell          | 03X6X0 A02                  | Server      | [8d9b81f936](https://bsd-hardware.info/?probe=8d9b81f936) | Sep 04, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [25cc035e73](https://bsd-hardware.info/?probe=25cc035e73) | Sep 03, 2023 |
| PC Engines    | APU2                        | Desktop     | [c9d2cfe6fa](https://bsd-hardware.info/?probe=c9d2cfe6fa) | Sep 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [53cee3b3c8](https://bsd-hardware.info/?probe=53cee3b3c8) | Sep 03, 2023 |
| Biostar       | J4105NHU                    | Desktop     | [2ac770aa55](https://bsd-hardware.info/?probe=2ac770aa55) | Sep 03, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [f95d1da00c](https://bsd-hardware.info/?probe=f95d1da00c) | Sep 01, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [1f4bf47cab](https://bsd-hardware.info/?probe=1f4bf47cab) | Sep 01, 2023 |
| Sophos        | UTM                         | Firewall    | [01a7eea7b9](https://bsd-hardware.info/?probe=01a7eea7b9) | Aug 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [b59ce07b49](https://bsd-hardware.info/?probe=b59ce07b49) | Aug 30, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [56ac0149f8](https://bsd-hardware.info/?probe=56ac0149f8) | Aug 30, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [81cbfbffca](https://bsd-hardware.info/?probe=81cbfbffca) | Aug 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [fc384f5de7](https://bsd-hardware.info/?probe=fc384f5de7) | Aug 28, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [a47cd8ee32](https://bsd-hardware.info/?probe=a47cd8ee32) | Aug 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [5025d5adb6](https://bsd-hardware.info/?probe=5025d5adb6) | Aug 27, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [a684024d8e](https://bsd-hardware.info/?probe=a684024d8e) | Aug 27, 2023 |
| PC Engines    | APU                         | Desktop     | [3b29671556](https://bsd-hardware.info/?probe=3b29671556) | Aug 26, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ed6162710b](https://bsd-hardware.info/?probe=ed6162710b) | Aug 26, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a487121854](https://bsd-hardware.info/?probe=a487121854) | Aug 26, 2023 |
| IGEL Techn... | D220                        | Desktop     | [a7686520e1](https://bsd-hardware.info/?probe=a7686520e1) | Aug 26, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [662ce63a50](https://bsd-hardware.info/?probe=662ce63a50) | Aug 25, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8c6f7098f9](https://bsd-hardware.info/?probe=8c6f7098f9) | Aug 25, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [b8f1609842](https://bsd-hardware.info/?probe=b8f1609842) | Aug 25, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [d8a9af2435](https://bsd-hardware.info/?probe=d8a9af2435) | Aug 24, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a8fa821e5e](https://bsd-hardware.info/?probe=a8fa821e5e) | Aug 24, 2023 |
| Supermicro    | H12SSW-iN                   | Server      | [d0be592303](https://bsd-hardware.info/?probe=d0be592303) | Aug 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [74a7137090](https://bsd-hardware.info/?probe=74a7137090) | Aug 22, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [8622d78a7c](https://bsd-hardware.info/?probe=8622d78a7c) | Aug 22, 2023 |
| Gigabyte      | H610I DDR4                  | Desktop     | [f4310832c2](https://bsd-hardware.info/?probe=f4310832c2) | Aug 22, 2023 |
| Intel         | JSL MRD                     | Desktop     | [56165c654b](https://bsd-hardware.info/?probe=56165c654b) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [03da20b37e](https://bsd-hardware.info/?probe=03da20b37e) | Aug 22, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [71e00307ae](https://bsd-hardware.info/?probe=71e00307ae) | Aug 22, 2023 |
| PC Engines    | APU2                        | Desktop     | [3e32acfdc4](https://bsd-hardware.info/?probe=3e32acfdc4) | Aug 22, 2023 |
| Gigabyte      | H110M-D2P-WG-CF             | Desktop     | [a91c61e3e3](https://bsd-hardware.info/?probe=a91c61e3e3) | Aug 21, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ef28836f5c](https://bsd-hardware.info/?probe=ef28836f5c) | Aug 20, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [01d58784e6](https://bsd-hardware.info/?probe=01d58784e6) | Aug 20, 2023 |
| HP            | 8594                        | Desktop     | [b3e5652c1b](https://bsd-hardware.info/?probe=b3e5652c1b) | Aug 20, 2023 |
| HP            | 8594                        | Desktop     | [77d6ac3f77](https://bsd-hardware.info/?probe=77d6ac3f77) | Aug 20, 2023 |
| Sophos        | XG                          | Firewall    | [2f35580968](https://bsd-hardware.info/?probe=2f35580968) | Aug 19, 2023 |
| Sophos        | SG                          | Firewall    | [30708a275a](https://bsd-hardware.info/?probe=30708a275a) | Aug 18, 2023 |
| Dell          | Latitude 5591               | Notebook    | [972da999fb](https://bsd-hardware.info/?probe=972da999fb) | Aug 18, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [b3625ada4b](https://bsd-hardware.info/?probe=b3625ada4b) | Aug 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [de9a146c44](https://bsd-hardware.info/?probe=de9a146c44) | Aug 16, 2023 |
| Unknown       | Q2XX V1.0                   | Desktop     | [be1252b2ff](https://bsd-hardware.info/?probe=be1252b2ff) | Aug 16, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [18559e2fde](https://bsd-hardware.info/?probe=18559e2fde) | Aug 15, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [73c35b0a8a](https://bsd-hardware.info/?probe=73c35b0a8a) | Aug 15, 2023 |
| Intel         | SKYBAY                      | Desktop     | [77fbc82e41](https://bsd-hardware.info/?probe=77fbc82e41) | Aug 15, 2023 |
| Protectli     | VP4620                      | Desktop     | [0f0695d190](https://bsd-hardware.info/?probe=0f0695d190) | Aug 15, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [680fdcd4f6](https://bsd-hardware.info/?probe=680fdcd4f6) | Aug 14, 2023 |
| PC Engines    | APU2                        | Desktop     | [bdd3050b5f](https://bsd-hardware.info/?probe=bdd3050b5f) | Aug 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [b8e7299136](https://bsd-hardware.info/?probe=b8e7299136) | Aug 13, 2023 |
| Dell          | Latitude 5591               | Notebook    | [a599361016](https://bsd-hardware.info/?probe=a599361016) | Aug 13, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [6c4364fe15](https://bsd-hardware.info/?probe=6c4364fe15) | Aug 13, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [b978121948](https://bsd-hardware.info/?probe=b978121948) | Aug 13, 2023 |
| PC Engines    | apu4                        | Desktop     | [24e025662c](https://bsd-hardware.info/?probe=24e025662c) | Aug 12, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [983bbef1fb](https://bsd-hardware.info/?probe=983bbef1fb) | Aug 12, 2023 |
| WeiBu         | ADL-N Prod                  | Desktop     | [26bbe26e7c](https://bsd-hardware.info/?probe=26bbe26e7c) | Aug 12, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [27f84c75b5](https://bsd-hardware.info/?probe=27f84c75b5) | Aug 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [2e9106fc92](https://bsd-hardware.info/?probe=2e9106fc92) | Aug 11, 2023 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [7b00ddd0a1](https://bsd-hardware.info/?probe=7b00ddd0a1) | Aug 11, 2023 |
| PC Engines    | apu1                        | Desktop     | [0b3594d9a3](https://bsd-hardware.info/?probe=0b3594d9a3) | Aug 11, 2023 |
| PC Engines    | apu4                        | Desktop     | [b81f51408d](https://bsd-hardware.info/?probe=b81f51408d) | Aug 10, 2023 |
| Sophos        | SG                          | Firewall    | [ee7cfb0c22](https://bsd-hardware.info/?probe=ee7cfb0c22) | Aug 10, 2023 |
| Sophos        | UTM                         | Firewall    | [e7e8344a31](https://bsd-hardware.info/?probe=e7e8344a31) | Aug 09, 2023 |
| PC Engines    | APU2                        | Desktop     | [be0e8bf959](https://bsd-hardware.info/?probe=be0e8bf959) | Aug 09, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [fac2fa5cbe](https://bsd-hardware.info/?probe=fac2fa5cbe) | Aug 08, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [8720a76ea8](https://bsd-hardware.info/?probe=8720a76ea8) | Aug 08, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [322b24ffa1](https://bsd-hardware.info/?probe=322b24ffa1) | Aug 08, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [2acf1e4557](https://bsd-hardware.info/?probe=2acf1e4557) | Aug 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [aeccb6e70c](https://bsd-hardware.info/?probe=aeccb6e70c) | Aug 07, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [dadf592128](https://bsd-hardware.info/?probe=dadf592128) | Aug 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [eceed9eb7a](https://bsd-hardware.info/?probe=eceed9eb7a) | Aug 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c4dbcfd67](https://bsd-hardware.info/?probe=9c4dbcfd67) | Aug 05, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [6236e692de](https://bsd-hardware.info/?probe=6236e692de) | Aug 05, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [283fce4c68](https://bsd-hardware.info/?probe=283fce4c68) | Aug 05, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [c449203453](https://bsd-hardware.info/?probe=c449203453) | Aug 04, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ea7a6fba73](https://bsd-hardware.info/?probe=ea7a6fba73) | Aug 04, 2023 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [62ed2f59f6](https://bsd-hardware.info/?probe=62ed2f59f6) | Aug 04, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [b6aafbefd3](https://bsd-hardware.info/?probe=b6aafbefd3) | Aug 04, 2023 |
| PC Engines    | APU2                        | Desktop     | [78c8ed6a89](https://bsd-hardware.info/?probe=78c8ed6a89) | Aug 03, 2023 |
| Dell          | 045M96 A02                  | Server      | [17cf8cd2f0](https://bsd-hardware.info/?probe=17cf8cd2f0) | Aug 03, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [b3fd8251db](https://bsd-hardware.info/?probe=b3fd8251db) | Aug 02, 2023 |
| Shuttle       | DH610                       | Desktop     | [bbdd78fe4b](https://bsd-hardware.info/?probe=bbdd78fe4b) | Aug 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [42c65b8b8b](https://bsd-hardware.info/?probe=42c65b8b8b) | Aug 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [09d17597cf](https://bsd-hardware.info/?probe=09d17597cf) | Aug 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [2a2e7a98e3](https://bsd-hardware.info/?probe=2a2e7a98e3) | Aug 01, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [65667b2f29](https://bsd-hardware.info/?probe=65667b2f29) | Aug 01, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [aa708122cf](https://bsd-hardware.info/?probe=aa708122cf) | Aug 01, 2023 |
| Shuttle       | DH610                       | Desktop     | [e7c63c97d3](https://bsd-hardware.info/?probe=e7c63c97d3) | Aug 01, 2023 |
| Shuttle       | DH370                       | Desktop     | [a3ab1c6344](https://bsd-hardware.info/?probe=a3ab1c6344) | Jul 31, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [9bd5d8fd54](https://bsd-hardware.info/?probe=9bd5d8fd54) | Jul 31, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [42fcdacbf7](https://bsd-hardware.info/?probe=42fcdacbf7) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [64137e0eec](https://bsd-hardware.info/?probe=64137e0eec) | Jul 29, 2023 |
| HP            | Notebook                    | Notebook    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| AWOW          | AK34Pro                     | Mini pc     | [7c8e0ac36d](https://bsd-hardware.info/?probe=7c8e0ac36d) | Jul 29, 2023 |
| PC Engines    | APU2                        | Desktop     | [5eddd5369a](https://bsd-hardware.info/?probe=5eddd5369a) | Jul 28, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [0bb6b16689](https://bsd-hardware.info/?probe=0bb6b16689) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [1c6ab6b999](https://bsd-hardware.info/?probe=1c6ab6b999) | Jul 28, 2023 |
| Sophos        | UTM                         | Firewall    | [c33c212896](https://bsd-hardware.info/?probe=c33c212896) | Jul 28, 2023 |
| PC Engines    | apu1                        | Desktop     | [8bc97daada](https://bsd-hardware.info/?probe=8bc97daada) | Jul 27, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [64b577cd8e](https://bsd-hardware.info/?probe=64b577cd8e) | Jul 27, 2023 |
| NF541         | 1.0                         | Desktop     | [ba959613a5](https://bsd-hardware.info/?probe=ba959613a5) | Jul 26, 2023 |
| Cisco         | ASA5525 A0                  | Desktop     | [f4409bdc8f](https://bsd-hardware.info/?probe=f4409bdc8f) | Jul 26, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [d9c7f4173a](https://bsd-hardware.info/?probe=d9c7f4173a) | Jul 25, 2023 |
| Sophos        | XG                          | Firewall    | [bcf0e85fdc](https://bsd-hardware.info/?probe=bcf0e85fdc) | Jul 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [f7728cee03](https://bsd-hardware.info/?probe=f7728cee03) | Jul 25, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [8aa3f5491e](https://bsd-hardware.info/?probe=8aa3f5491e) | Jul 25, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [af215ad226](https://bsd-hardware.info/?probe=af215ad226) | Jul 24, 2023 |
| PC Engines    | apu4                        | Desktop     | [0aa9951131](https://bsd-hardware.info/?probe=0aa9951131) | Jul 24, 2023 |
| PC Engines    | apu4                        | Desktop     | [514dc1e9f9](https://bsd-hardware.info/?probe=514dc1e9f9) | Jul 24, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [dec2c34899](https://bsd-hardware.info/?probe=dec2c34899) | Jul 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [aab49bd228](https://bsd-hardware.info/?probe=aab49bd228) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [438424a9d9](https://bsd-hardware.info/?probe=438424a9d9) | Jul 23, 2023 |
| PC Engines    | apu4                        | Desktop     | [ea9a81b423](https://bsd-hardware.info/?probe=ea9a81b423) | Jul 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [3b16dab962](https://bsd-hardware.info/?probe=3b16dab962) | Jul 22, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7e1b416d09](https://bsd-hardware.info/?probe=7e1b416d09) | Jul 21, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [489c685ec4](https://bsd-hardware.info/?probe=489c685ec4) | Jul 21, 2023 |
| AZW           | EQ                          | Desktop     | [9883a89b8d](https://bsd-hardware.info/?probe=9883a89b8d) | Jul 21, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [efe49f9e5d](https://bsd-hardware.info/?probe=efe49f9e5d) | Jul 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [cce6d65dfb](https://bsd-hardware.info/?probe=cce6d65dfb) | Jul 20, 2023 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [f3aa06579e](https://bsd-hardware.info/?probe=f3aa06579e) | Jul 20, 2023 |
| Dell          | 08CYF7 A03                  | Server      | [67e68a4ad9](https://bsd-hardware.info/?probe=67e68a4ad9) | Jul 19, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [cbb13789d2](https://bsd-hardware.info/?probe=cbb13789d2) | Jul 19, 2023 |
| Dell          | 0MD99X A12                  | Server      | [eaabbf3ff3](https://bsd-hardware.info/?probe=eaabbf3ff3) | Jul 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [e487955dea](https://bsd-hardware.info/?probe=e487955dea) | Jul 18, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [35ab9e002d](https://bsd-hardware.info/?probe=35ab9e002d) | Jul 17, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [8d82f25df2](https://bsd-hardware.info/?probe=8d82f25df2) | Jul 16, 2023 |
| Unknown       | Unknown                     | Firewall    | [af05859a76](https://bsd-hardware.info/?probe=af05859a76) | Jul 16, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a2602b7fbf](https://bsd-hardware.info/?probe=a2602b7fbf) | Jul 16, 2023 |
| Gigabyte      | GB-BSi7-1165G7              | Desktop     | [c5f92a4c5e](https://bsd-hardware.info/?probe=c5f92a4c5e) | Jul 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [0b90f241cd](https://bsd-hardware.info/?probe=0b90f241cd) | Jul 13, 2023 |
| PICO PC       | JSL-4L                      | Desktop     | [d93e338744](https://bsd-hardware.info/?probe=d93e338744) | Jul 13, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [535720220a](https://bsd-hardware.info/?probe=535720220a) | Jul 13, 2023 |
| Supermicro    | X11SCH-F                    | Server      | [8f25848f38](https://bsd-hardware.info/?probe=8f25848f38) | Jul 13, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [c2cb1e21fa](https://bsd-hardware.info/?probe=c2cb1e21fa) | Jul 11, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [96bda9f774](https://bsd-hardware.info/?probe=96bda9f774) | Jul 11, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [4b7383c876](https://bsd-hardware.info/?probe=4b7383c876) | Jul 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [5625dd24f6](https://bsd-hardware.info/?probe=5625dd24f6) | Jul 11, 2023 |
| PICO PC       | JSL-4L                      | Desktop     | [d8c9a61dcf](https://bsd-hardware.info/?probe=d8c9a61dcf) | Jul 10, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3a544928aa](https://bsd-hardware.info/?probe=3a544928aa) | Jul 09, 2023 |
| MiTAC         | PH13CMI                     | Desktop     | [6d0cd37fce](https://bsd-hardware.info/?probe=6d0cd37fce) | Jul 09, 2023 |
| Biostar       | A68N-2100K                  | Desktop     | [20cb208208](https://bsd-hardware.info/?probe=20cb208208) | Jul 09, 2023 |
| Lex           | Pineview-D                  | Desktop     | [290c53a822](https://bsd-hardware.info/?probe=290c53a822) | Jul 09, 2023 |
| Lenovo        | ThinkPad X250 20CLS13Q06    | Notebook    | [c318ab3cc7](https://bsd-hardware.info/?probe=c318ab3cc7) | Jul 09, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [9cd5d7878b](https://bsd-hardware.info/?probe=9cd5d7878b) | Jul 07, 2023 |
| Yanling       | YL-ELU3L                    | Desktop     | [0a3c74b25c](https://bsd-hardware.info/?probe=0a3c74b25c) | Jul 07, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [5d896a607e](https://bsd-hardware.info/?probe=5d896a607e) | Jul 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [3644875d54](https://bsd-hardware.info/?probe=3644875d54) | Jul 03, 2023 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [877c048c7d](https://bsd-hardware.info/?probe=877c048c7d) | Jul 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [2053dbb697](https://bsd-hardware.info/?probe=2053dbb697) | Jul 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [3725d44c33](https://bsd-hardware.info/?probe=3725d44c33) | Jul 01, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [0f9a1dc60c](https://bsd-hardware.info/?probe=0f9a1dc60c) | Jul 01, 2023 |
| PC Engines    | apu4                        | Desktop     | [62f0b60653](https://bsd-hardware.info/?probe=62f0b60653) | Jun 30, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [d60c967edb](https://bsd-hardware.info/?probe=d60c967edb) | Jun 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [075deef24f](https://bsd-hardware.info/?probe=075deef24f) | Jun 28, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [1785cb2fa3](https://bsd-hardware.info/?probe=1785cb2fa3) | Jun 28, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [2eff359d8f](https://bsd-hardware.info/?probe=2eff359d8f) | Jun 28, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [bcad942162](https://bsd-hardware.info/?probe=bcad942162) | Jun 26, 2023 |
| Unknown       | YL-SKUL6                    | Desktop     | [1512f63972](https://bsd-hardware.info/?probe=1512f63972) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [fa177a2538](https://bsd-hardware.info/?probe=fa177a2538) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [54ef7dc131](https://bsd-hardware.info/?probe=54ef7dc131) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [b056cd0426](https://bsd-hardware.info/?probe=b056cd0426) | Jun 26, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [5ad411cd6b](https://bsd-hardware.info/?probe=5ad411cd6b) | Jun 25, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [8a2ea60929](https://bsd-hardware.info/?probe=8a2ea60929) | Jun 25, 2023 |
| Sophos        | SG                          | Firewall    | [11e1176b5e](https://bsd-hardware.info/?probe=11e1176b5e) | Jun 24, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [18cf91f3a4](https://bsd-hardware.info/?probe=18cf91f3a4) | Jun 23, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [bb4dc2b1a2](https://bsd-hardware.info/?probe=bb4dc2b1a2) | Jun 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [16ceade742](https://bsd-hardware.info/?probe=16ceade742) | Jun 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [508aa0bdb4](https://bsd-hardware.info/?probe=508aa0bdb4) | Jun 23, 2023 |
| Sophos        | SG                          | Firewall    | [6763145000](https://bsd-hardware.info/?probe=6763145000) | Jun 22, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4f80d81bbe](https://bsd-hardware.info/?probe=4f80d81bbe) | Jun 20, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | Notebook    | [6969cd9e1a](https://bsd-hardware.info/?probe=6969cd9e1a) | Jun 20, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | Notebook    | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
| Yanling       | YL-KBRL2 Series Ver:1.02    | Desktop     | [9e8d6110f4](https://bsd-hardware.info/?probe=9e8d6110f4) | Jun 19, 2023 |
| LANCOM Sys... | UF-60                       | Desktop     | [96904b8bdd](https://bsd-hardware.info/?probe=96904b8bdd) | Jun 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [5fc629699d](https://bsd-hardware.info/?probe=5fc629699d) | Jun 18, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [9f41fa4740](https://bsd-hardware.info/?probe=9f41fa4740) | Jun 18, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [8eb0be633d](https://bsd-hardware.info/?probe=8eb0be633d) | Jun 18, 2023 |
| Dell          | Latitude E6520              | Notebook    | [98868960d5](https://bsd-hardware.info/?probe=98868960d5) | Jun 18, 2023 |
| ASRock        | Z97 Professional            | Desktop     | [c978ddda86](https://bsd-hardware.info/?probe=c978ddda86) | Jun 18, 2023 |
| Sophos        | SG                          | Firewall    | [94a6b615cb](https://bsd-hardware.info/?probe=94a6b615cb) | Jun 17, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [06f5a9210b](https://bsd-hardware.info/?probe=06f5a9210b) | Jun 17, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [6412e6fb23](https://bsd-hardware.info/?probe=6412e6fb23) | Jun 16, 2023 |
| AMD           | Kabini CRB                  | Desktop     | [b774a8b586](https://bsd-hardware.info/?probe=b774a8b586) | Jun 16, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [b9c5b6ec05](https://bsd-hardware.info/?probe=b9c5b6ec05) | Jun 15, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [70b0e8172d](https://bsd-hardware.info/?probe=70b0e8172d) | Jun 14, 2023 |
| PC Engines    | apu4                        | Desktop     | [ea036662ca](https://bsd-hardware.info/?probe=ea036662ca) | Jun 14, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [4a6667249e](https://bsd-hardware.info/?probe=4a6667249e) | Jun 13, 2023 |
| Lenovo        | ThinkPad T530 2429AP0       | Notebook    | [ddf37e7b17](https://bsd-hardware.info/?probe=ddf37e7b17) | Jun 13, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [dad27d6099](https://bsd-hardware.info/?probe=dad27d6099) | Jun 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [015a5d839a](https://bsd-hardware.info/?probe=015a5d839a) | Jun 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [27617e1ca6](https://bsd-hardware.info/?probe=27617e1ca6) | Jun 13, 2023 |
| HP            | 3397                        | Desktop     | [a918ce0c4b](https://bsd-hardware.info/?probe=a918ce0c4b) | Jun 12, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [04ae7435e5](https://bsd-hardware.info/?probe=04ae7435e5) | Jun 12, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [6e0b1f598f](https://bsd-hardware.info/?probe=6e0b1f598f) | Jun 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [02509df772](https://bsd-hardware.info/?probe=02509df772) | Jun 12, 2023 |
| Sophos        | UTM                         | Firewall    | [d4856d7798](https://bsd-hardware.info/?probe=d4856d7798) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [2d2052de27](https://bsd-hardware.info/?probe=2d2052de27) | Jun 11, 2023 |
| HP            | 15                          | Notebook    | [4664b4c93f](https://bsd-hardware.info/?probe=4664b4c93f) | Jun 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [8988baa83b](https://bsd-hardware.info/?probe=8988baa83b) | Jun 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [40bb474319](https://bsd-hardware.info/?probe=40bb474319) | Jun 10, 2023 |
| ASRock        | B85M-HDS                    | Desktop     | [09a4700a14](https://bsd-hardware.info/?probe=09a4700a14) | Jun 09, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [d21bdf0cdb](https://bsd-hardware.info/?probe=d21bdf0cdb) | Jun 09, 2023 |
| Wortmann      | terra Nettop 2700           | Desktop     | [e4a90ea530](https://bsd-hardware.info/?probe=e4a90ea530) | Jun 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1ae49c4706](https://bsd-hardware.info/?probe=1ae49c4706) | Jun 08, 2023 |
| Sophos        | SG                          | Firewall    | [6cf087f800](https://bsd-hardware.info/?probe=6cf087f800) | Jun 08, 2023 |
| Intel         | SKYBAY                      | Desktop     | [f1b649ed11](https://bsd-hardware.info/?probe=f1b649ed11) | Jun 08, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [ee85efd1c0](https://bsd-hardware.info/?probe=ee85efd1c0) | Jun 08, 2023 |
| LANCOM Sys... | UF-60                       | Desktop     | [204f10b60f](https://bsd-hardware.info/?probe=204f10b60f) | Jun 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [4e57bbcdb5](https://bsd-hardware.info/?probe=4e57bbcdb5) | Jun 06, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [ce3bef7b5a](https://bsd-hardware.info/?probe=ce3bef7b5a) | Jun 06, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [c9ec51aa84](https://bsd-hardware.info/?probe=c9ec51aa84) | Jun 05, 2023 |
| HP            | 3397                        | Desktop     | [6783902b93](https://bsd-hardware.info/?probe=6783902b93) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [cf9ed85e65](https://bsd-hardware.info/?probe=cf9ed85e65) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [fc66ebba25](https://bsd-hardware.info/?probe=fc66ebba25) | Jun 05, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [42e80f8003](https://bsd-hardware.info/?probe=42e80f8003) | Jun 05, 2023 |
| Sophos        | UTM                         | Firewall    | [05ee8903b5](https://bsd-hardware.info/?probe=05ee8903b5) | Jun 04, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [ab3919bc32](https://bsd-hardware.info/?probe=ab3919bc32) | Jun 04, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [23bd5ef252](https://bsd-hardware.info/?probe=23bd5ef252) | Jun 04, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [56a9981ff3](https://bsd-hardware.info/?probe=56a9981ff3) | Jun 03, 2023 |
| PC Engines    | APU2                        | Desktop     | [31c697459b](https://bsd-hardware.info/?probe=31c697459b) | Jun 02, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [300b958d60](https://bsd-hardware.info/?probe=300b958d60) | May 30, 2023 |
| HP            | 3397                        | Desktop     | [1f8a9a4f27](https://bsd-hardware.info/?probe=1f8a9a4f27) | May 29, 2023 |
| ASRock        | H410M/ac                    | Desktop     | [d3e3d20cc4](https://bsd-hardware.info/?probe=d3e3d20cc4) | May 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2827d90215](https://bsd-hardware.info/?probe=2827d90215) | May 28, 2023 |
| Tactus        | GeoFlex 110                 | Notebook    | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| HP            | 3397                        | Desktop     | [036d4e087c](https://bsd-hardware.info/?probe=036d4e087c) | May 27, 2023 |
| HP            | 3397                        | Desktop     | [19abd8768e](https://bsd-hardware.info/?probe=19abd8768e) | May 27, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [81775d5ca1](https://bsd-hardware.info/?probe=81775d5ca1) | May 26, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [aad8268158](https://bsd-hardware.info/?probe=aad8268158) | May 24, 2023 |
| Nitrokey      | NitroWall                   | Desktop     | [1b3b451dee](https://bsd-hardware.info/?probe=1b3b451dee) | May 24, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [fff8a7a86f](https://bsd-hardware.info/?probe=fff8a7a86f) | May 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [4c7e1d476d](https://bsd-hardware.info/?probe=4c7e1d476d) | May 23, 2023 |
| Nitrokey      | NitroWall                   | Desktop     | [ef701f3991](https://bsd-hardware.info/?probe=ef701f3991) | May 23, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [14583f30e3](https://bsd-hardware.info/?probe=14583f30e3) | May 22, 2023 |
| Unknown       | QD-WHLU01                   | Desktop     | [700bcad7cc](https://bsd-hardware.info/?probe=700bcad7cc) | May 22, 2023 |
| HP            | 158B                        | Desktop     | [1ef3762103](https://bsd-hardware.info/?probe=1ef3762103) | May 20, 2023 |
| HP            | 158B                        | Desktop     | [a9c63041a6](https://bsd-hardware.info/?probe=a9c63041a6) | May 20, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [8156e3fede](https://bsd-hardware.info/?probe=8156e3fede) | May 19, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [612e3a21d4](https://bsd-hardware.info/?probe=612e3a21d4) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8f3c5de741](https://bsd-hardware.info/?probe=8f3c5de741) | May 19, 2023 |
| VIA Techno... | VT82C597                    | Desktop     | [d73db58e48](https://bsd-hardware.info/?probe=d73db58e48) | May 19, 2023 |
| Sophos        | SG                          | Firewall    | [a27da0f165](https://bsd-hardware.info/?probe=a27da0f165) | May 19, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 21.7.7   | 65        | 2.17%   |
| OPNsense 21.1     | 64        | 2.14%   |
| OPNsense 22.7.10  | 59        | 1.97%   |
| OPNsense 21.1.5   | 56        | 1.87%   |
| OPNsense 22.1     | 54        | 1.8%    |
| OPNsense 20.7.8   | 54        | 1.8%    |
| OPNsense 23.1.11  | 52        | 1.74%   |
| OPNsense 21.7.3   | 52        | 1.74%   |
| OPNsense 21.7.1   | 51        | 1.7%    |
| OPNsense 21.1.3   | 45        | 1.5%    |
| OPNsense 21.7.6   | 43        | 1.44%   |
| OPNsense 21.1.2   | 43        | 1.44%   |
| OPNsense 24.1.6   | 42        | 1.4%    |
| OPNsense 23.1.5   | 42        | 1.4%    |
| OPNsense 23.1     | 42        | 1.4%    |
| OPNsense 22.7.6   | 42        | 1.4%    |
| OPNsense 22.7.4   | 42        | 1.4%    |
| OPNsense 22.1.8   | 42        | 1.4%    |
| OPNsense 21.1.1   | 42        | 1.4%    |
| OPNsense 23.7.10  | 41        | 1.37%   |
| OPNsense 22.1.6   | 40        | 1.34%   |
| OPNsense 23.7.12  | 39        | 1.3%    |
| OPNsense 21.1.4   | 39        | 1.3%    |
| OPNsense 22.7.9   | 38        | 1.27%   |
| OPNsense 24.1.4   | 36        | 1.2%    |
| OPNsense 23.7.9   | 35        | 1.17%   |
| OPNsense 23.1.1   | 35        | 1.17%   |
| OPNsense 23.7.7   | 34        | 1.14%   |
| helloSystem 0.8.1 | 34        | 1.14%   |
| helloSystem 0.4.0 | 34        | 1.14%   |
| OPNsense 23.7.6   | 33        | 1.1%    |
| OPNsense 23.1.7   | 33        | 1.1%    |
| OPNsense 24.1.1   | 32        | 1.07%   |
| OPNsense 23.7.1   | 32        | 1.07%   |
| OPNsense 23.1.9   | 31        | 1.04%   |
| OPNsense 23.7.8   | 30        | 1%      |
| OPNsense 22.1.10  | 30        | 1%      |
| OPNsense 24.1.3   | 29        | 0.97%   |
| OPNsense 23.7.3   | 28        | 0.94%   |
| OPNsense 22.7.11  | 28        | 0.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 1678      | 73.66%  |
| FreeBSD     | 271       | 11.9%   |
| helloSystem | 151       | 6.63%   |
| OpenBSD     | 74        | 3.25%   |
| GhostBSD    | 46        | 2.02%   |
| NomadBSD    | 28        | 1.23%   |
| NetBSD      | 9         | 0.4%    |
| TrueNAS     | 8         | 0.35%   |
| MyBee       | 3         | 0.13%   |
| pfSense     | 2         | 0.09%   |
| HardenedBSD | 2         | 0.09%   |
| PC-BSD      | 1         | 0.04%   |
| MidnightBSD | 1         | 0.04%   |
| FuryBSD     | 1         | 0.04%   |
| FreeNAS     | 1         | 0.04%   |
| DragonFly   | 1         | 0.04%   |
| ClonOS      | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 2223      | 98.67%  |
| i386    | 12        | 0.53%   |
| arm64   | 10        | 0.44%   |
| arm     | 5         | 0.22%   |
| macppc  | 2         | 0.09%   |
| sparc64 | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 1814      | 79.28%  |
| helloDesktop  | 168       | 7.34%   |
| MATE          | 62        | 2.71%   |
| KDE5          | 51        | 2.23%   |
| XFCE          | 47        | 2.05%   |
| fvwm          | 38        | 1.66%   |
| GNOME         | 25        | 1.09%   |
| Openbox       | 22        | 0.96%   |
| TWM           | 21        | 0.92%   |
| AwesomeWM     | 11        | 0.48%   |
| i3            | 8         | 0.35%   |
| LXQt          | 3         | 0.13%   |
| Enlightenment | 3         | 0.13%   |
| Cinnamon      | 3         | 0.13%   |
| LXDE          | 2         | 0.09%   |
| ICEWM         | 2         | 0.09%   |
| Fluxbox       | 2         | 0.09%   |
| Picom         | 1         | 0.04%   |
| JWM           | 1         | 0.04%   |
| iwm           | 1         | 0.04%   |
| GNUstep       | 1         | 0.04%   |
| filer         | 1         | 0.04%   |
| Compton       | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1831      | 81.02%  |
| X11     | 426       | 18.85%  |
| Wayland | 2         | 0.09%   |
| Tty     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1915      | 83.81%  |
| SLiM    | 201       | 8.8%    |
| LightDM | 60        | 2.63%   |
| SDDM    | 59        | 2.58%   |
| XDM     | 26        | 1.14%   |
| GDM     | 19        | 0.83%   |
| Ly      | 5         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 1820      | 79.23%  |
| C                | 165       | 7.18%   |
| en_US            | 145       | 6.31%   |
| de_DE            | 125       | 5.44%   |
| de               | 9         | 0.39%   |
| fr_FR            | 8         | 0.35%   |
| en_GB            | 8         | 0.35%   |
| en               | 4         | 0.17%   |
| de_DE.ISO8859-1  | 3         | 0.13%   |
| ru_RU            | 1         | 0.04%   |
| pl_PL            | 1         | 0.04%   |
| ISO8859-15       | 1         | 0.04%   |
| fr               | 1         | 0.04%   |
| en_IE            | 1         | 0.04%   |
| en_GB.ISO8859-1  | 1         | 0.04%   |
| en_DE            | 1         | 0.04%   |
| en_CA            | 1         | 0.04%   |
| de_DE.ISO8859-15 | 1         | 0.04%   |
| de.DE            | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1991      | 87.67%  |
| BIOS | 280       | 12.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 1319      | 57.2%   |
| Zfs     | 858       | 37.21%  |
| Ffs     | 74        | 3.21%   |
| Cd9660  | 54        | 2.34%   |
| Hammer2 | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2106      | 92.9%   |
| MBR     | 131       | 5.78%   |
| Unknown | 29        | 1.28%   |
| BSD     | 1         | 0.04%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 294       | 13.05%  |
| Lenovo              | 159       | 7.06%   |
| PC Engines          | 145       | 6.44%   |
| Fujitsu             | 144       | 6.39%   |
| Supermicro          | 134       | 5.95%   |
| Sophos              | 124       | 5.5%    |
| Hewlett-Packard     | 121       | 5.37%   |
| Dell                | 120       | 5.33%   |
| Intel               | 93        | 4.13%   |
| ASUSTek Computer    | 93        | 4.13%   |
| ASRock              | 78        | 3.46%   |
| Gigabyte Technology | 69        | 3.06%   |
| ZOTAC               | 59        | 2.62%   |
| MSI                 | 50        | 2.22%   |
| AMI                 | 46        | 2.04%   |
| Deciso              | 38        | 1.69%   |
| BESSTAR Tech        | 38        | 1.69%   |
| Protectli           | 37        | 1.64%   |
| Apple               | 33        | 1.46%   |
| Techvision          | 25        | 1.11%   |
| CncTion             | 24        | 1.07%   |
| Shuttle             | 22        | 0.98%   |
| Acer                | 20        | 0.89%   |
| AWOW                | 16        | 0.71%   |
| Hardkernel          | 14        | 0.62%   |
| MW                  | 13        | 0.58%   |
| Thomas-Krenn.AG     | 12        | 0.53%   |
| TUXEDO              | 10        | 0.44%   |
| ASRockRack          | 10        | 0.44%   |
| Yanling             | 9         | 0.4%    |
| CheckPoint          | 9         | 0.4%    |
| AAEON               | 9         | 0.4%    |
| NF541               | 8         | 0.36%   |
| IceWhale Technology | 8         | 0.36%   |
| Biostar             | 8         | 0.36%   |
| IBM                 | 7         | 0.31%   |
| Lanner              | 6         | 0.27%   |
| CWWK                | 6         | 0.27%   |
| Medion              | 5         | 0.22%   |
| Foxconn             | 5         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                             | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Unknown                                          | 299       | 13.27%  |
| Sophos SG                                        | 75        | 3.33%   |
| PC Engines APU2                                  | 70        | 3.11%   |
| Fujitsu FUTRO S920                               | 56        | 2.49%   |
| PC Engines apu4                                  | 49        | 2.17%   |
| Supermicro Super Server                          | 45        | 2%      |
| Sophos UTM                                       | 26        | 1.15%   |
| Techvision TVI7309X                              | 25        | 1.11%   |
| AMI Aptio CRB                                    | 25        | 1.11%   |
| Sophos XG                                        | 23        | 1.02%   |
| Intel Q3XXG4-P V1.0                              | 18        | 0.8%    |
| ZOTAC ZBOX-CI329NANO                             | 16        | 0.71%   |
| Protectli FW6                                    | 14        | 0.62%   |
| Deciso NetBoard-A10                              | 14        | 0.62%   |
| MW GMLK-2_5G4L                                   | 13        | 0.58%   |
| Hardkernel ODROID-H2                             | 13        | 0.58%   |
| Supermicro A1SAi                                 | 11        | 0.49%   |
| Protectli FW4B                                   | 11        | 0.49%   |
| PC Engines APU3                                  | 11        | 0.49%   |
| CncTion N5105-4L                                 | 11        | 0.49%   |
| BESSTAR Tech GK41                                | 11        | 0.49%   |
| ZOTAC ZBOX-CI327NANO-GS-01                       | 10        | 0.44%   |
| PC Engines APU                                   | 10        | 0.44%   |
| Fujitsu FUTRO S930                               | 10        | 0.44%   |
| HP ProLiant MicroServer Gen8                     | 9         | 0.4%    |
| Dell PowerEdge R210 II                           | 9         | 0.4%    |
| BESSTAR Tech X35G                                | 9         | 0.4%    |
| Supermicro 1HE Intel Single-CPU RI1102D-F Server | 8         | 0.36%   |
| HP t620 PLUS Quad Core TC                        | 8         | 0.36%   |
| NF541 1.0                                        | 7         | 0.31%   |
| AWOW PC BOX                                      | 7         | 0.31%   |
| ASUS All Series                                  | 7         | 0.31%   |
| AMI SG                                           | 7         | 0.31%   |
| AMI LES compact 4L                               | 7         | 0.31%   |
| MSI MS-7B89                                      | 6         | 0.27%   |
| IceWhale ZimaBoard 832 ZMB                       | 6         | 0.27%   |
| HP t730 Thin Client                              | 6         | 0.27%   |
| Deciso Netboard A20                              | 6         | 0.27%   |
| ZOTAC ZBOX-MI640/MI660/MI620NANO                 | 5         | 0.22%   |
| ZOTAC ZBOX-CI323NANO                             | 5         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 299       | 13.27%  |
| Lenovo ThinkPad            | 101       | 4.48%   |
| Fujitsu FUTRO              | 82        | 3.64%   |
| Sophos SG                  | 75        | 3.33%   |
| PC Engines APU2            | 70        | 3.11%   |
| PC Engines apu4            | 49        | 2.17%   |
| Supermicro Super           | 45        | 2%      |
| Dell OptiPlex              | 39        | 1.73%   |
| HP ProLiant                | 34        | 1.51%   |
| Dell PowerEdge             | 31        | 1.38%   |
| Lenovo ThinkCentre         | 28        | 1.24%   |
| Sophos UTM                 | 26        | 1.15%   |
| Techvision TVI7309X        | 25        | 1.11%   |
| Dell Latitude              | 25        | 1.11%   |
| AMI Aptio                  | 25        | 1.11%   |
| Sophos XG                  | 23        | 1.02%   |
| Supermicro 1HE             | 19        | 0.84%   |
| Intel Q3XXG4-P             | 18        | 0.8%    |
| Fujitsu ESPRIMO            | 17        | 0.75%   |
| ZOTAC ZBOX-CI329NANO       | 16        | 0.71%   |
| Protectli FW6              | 14        | 0.62%   |
| HP Compaq                  | 14        | 0.62%   |
| Fujitsu PRIMERGY           | 14        | 0.62%   |
| Deciso NetBoard-A10        | 14        | 0.62%   |
| Deciso Netboard            | 14        | 0.62%   |
| MW GMLK-2                  | 13        | 0.58%   |
| HP t620                    | 13        | 0.58%   |
| HP ProDesk                 | 13        | 0.58%   |
| HARDKERNEL ODROID-H2       | 13        | 0.58%   |
| Fujitsu LIFEBOOK           | 12        | 0.53%   |
| ASUS TUF                   | 12        | 0.53%   |
| Supermicro A1SAi           | 11        | 0.49%   |
| Protectli FW4B             | 11        | 0.49%   |
| PC Engines APU3            | 11        | 0.49%   |
| CncTion N5105-4L           | 11        | 0.49%   |
| BESSTAR Tech GK41          | 11        | 0.49%   |
| ASUS PRIME                 | 11        | 0.49%   |
| ZOTAC ZBOX-CI327NANO-GS-01 | 10        | 0.44%   |
| PC Engines APU             | 10        | 0.44%   |
| Thomas-Krenn.AG LES        | 9         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 252       | 11.19%  |
| 2021    | 231       | 10.25%  |
| 2016    | 231       | 10.25%  |
| 2020    | 206       | 9.14%   |
| 2019    | 195       | 8.66%   |
| 2022    | 187       | 8.3%    |
| 2014    | 179       | 7.94%   |
| 2017    | 152       | 6.75%   |
| 2013    | 106       | 4.7%    |
| 2023    | 101       | 4.48%   |
| 2011    | 92        | 4.08%   |
| 2012    | 82        | 3.64%   |
| 2015    | 79        | 3.51%   |
| 2010    | 52        | 2.31%   |
| 2009    | 35        | 1.55%   |
| 2008    | 27        | 1.2%    |
| Unknown | 20        | 0.89%   |
| 2007    | 14        | 0.62%   |
| 2006    | 5         | 0.22%   |
| 2024    | 3         | 0.13%   |
| 2003    | 2         | 0.09%   |
| 2005    | 1         | 0.04%   |
| 2002    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1382      | 61.34%  |
| Notebook       | 339       | 15.05%  |
| Mini pc        | 202       | 8.97%   |
| Server         | 170       | 7.55%   |
| Firewall       | 132       | 5.86%   |
| All in one     | 12        | 0.53%   |
| Convertible    | 9         | 0.4%    |
| System on chip | 7         | 0.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2088      | 92.68%  |
| Yes  | 165       | 7.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 844       | 36.78%  |
| 4.01-8.0        | 524       | 22.83%  |
| 16.01-24.0      | 501       | 21.83%  |
| 32.01-64.0      | 200       | 8.71%   |
| 2.01-3.0        | 90        | 3.92%   |
| 64.01-256.0     | 77        | 3.36%   |
| 3.01-4.0        | 16        | 0.7%    |
| 24.01-32.0      | 14        | 0.61%   |
| 0.51-1.0        | 10        | 0.44%   |
| 1.01-2.0        | 8         | 0.35%   |
| 0.01-0.5        | 7         | 0.31%   |
| More than 256.0 | 3         | 0.13%   |
| 0               | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 1233      | 53.06%  |
| 0.51-1.0    | 734       | 31.58%  |
| 1.01-2.0    | 211       | 9.08%   |
| 2.01-3.0    | 56        | 2.41%   |
| 4.01-8.0    | 25        | 1.08%   |
| 3.01-4.0    | 21        | 0.9%    |
| 0           | 13        | 0.56%   |
| Unknown     | 11        | 0.47%   |
| 8.01-16.0   | 8         | 0.34%   |
| 16.01-24.0  | 6         | 0.26%   |
| 24.01-32.0  | 3         | 0.13%   |
| 64.01-256.0 | 2         | 0.09%   |
| 32.01-64.0  | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1720      | 74.36%  |
| 2      | 250       | 10.81%  |
| 0      | 209       | 9.04%   |
| 3      | 57        | 2.46%   |
| 4      | 36        | 1.56%   |
| 5      | 15        | 0.65%   |
| 6      | 9         | 0.39%   |
| 8      | 6         | 0.26%   |
| 7      | 5         | 0.22%   |
| 9      | 3         | 0.13%   |
| 14     | 1         | 0.04%   |
| 11     | 1         | 0.04%   |
| 10     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1957      | 86.4%   |
| Yes       | 308       | 13.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2197      | 97.51%  |
| No        | 56        | 2.49%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1578      | 69.42%  |
| Yes       | 695       | 30.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1813      | 79.9%   |
| Yes       | 456       | 20.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Germany | 2253      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 200       | 7.87%   |
| Munich            | 93        | 3.66%   |
| Hamburg           | 86        | 3.39%   |
| Cologne           | 64        | 2.52%   |
| Frankfurt am Main | 61        | 2.4%    |
| Stuttgart         | 42        | 1.65%   |
| Karlsruhe         | 28        | 1.1%    |
| Ludwigsburg       | 27        | 1.06%   |
| Nuremberg         | 26        | 1.02%   |
| Bonn              | 26        | 1.02%   |
| Hanover           | 24        | 0.94%   |
| Leipzig           | 22        | 0.87%   |
| Dresden           | 19        | 0.75%   |
| Dortmund          | 19        | 0.75%   |
| Bochum            | 18        | 0.71%   |
| Düsseldorf       | 16        | 0.63%   |
| Wuppertal         | 15        | 0.59%   |
| Wiesbaden         | 14        | 0.55%   |
| Mannheim          | 14        | 0.55%   |
| Falkenstein       | 14        | 0.55%   |
| Essen             | 13        | 0.51%   |
| Darmstadt         | 13        | 0.51%   |
| Bielefeld         | 13        | 0.51%   |
| Bremen            | 12        | 0.47%   |
| Mainz             | 11        | 0.43%   |
| Braunschweig      | 11        | 0.43%   |
| Reutlingen        | 10        | 0.39%   |
| Münster          | 10        | 0.39%   |
| Magdeburg         | 10        | 0.39%   |
| Kassel            | 10        | 0.39%   |
| Heidelberg        | 10        | 0.39%   |
| Chemnitz          | 10        | 0.39%   |
| Aachen            | 10        | 0.39%   |
| Ulm               | 9         | 0.35%   |
| Lingen            | 9         | 0.35%   |
| Heilbronn         | 9         | 0.35%   |
| Halle             | 9         | 0.35%   |
| Erlangen          | 9         | 0.35%   |
| Augsburg          | 9         | 0.35%   |
| Tamm              | 8         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 435       | 675    | 17.99%  |
| Transcend           | 230       | 314    | 9.51%   |
| WDC                 | 185       | 310    | 7.65%   |
| Kingston            | 169       | 273    | 6.99%   |
| Intel               | 131       | 221    | 5.42%   |
| Crucial             | 130       | 199    | 5.38%   |
| SanDisk             | 128       | 180    | 5.29%   |
| Seagate             | 111       | 187    | 4.59%   |
| Toshiba             | 75        | 136    | 3.1%    |
| China               | 72        | 87     | 2.98%   |
| Intenso             | 52        | 79     | 2.15%   |
| A-DATA Technology   | 51        | 64     | 2.11%   |
| Phison              | 42        | 63     | 1.74%   |
| Hitachi             | 41        | 84     | 1.7%    |
| Micron Technology   | 36        | 55     | 1.49%   |
| HGST                | 36        | 70     | 1.49%   |
| Hoodisk             | 35        | 61     | 1.45%   |
| Innodisk            | 31        | 37     | 1.28%   |
| FORESEE             | 29        | 38     | 1.2%    |
| NVMe                | 26        | 45     | 1.08%   |
| ATP                 | 23        | 27     | 0.95%   |
| Patriot             | 19        | 26     | 0.79%   |
| Hewlett-Packard     | 18        | 24     | 0.74%   |
| SK hynix            | 17        | 20     | 0.7%    |
| OCZ                 | 15        | 24     | 0.62%   |
| SPCC                | 14        | 20     | 0.58%   |
| Apple               | 14        | 17     | 0.58%   |
| Protectli           | 13        | 18     | 0.54%   |
| Apacer              | 13        | 23     | 0.54%   |
| Corsair             | 12        | 19     | 0.5%    |
| KIOXIA              | 11        | 12     | 0.45%   |
| Verbatim            | 10        | 16     | 0.41%   |
| Dogfish             | 9         | 11     | 0.37%   |
| TCSUNBOW            | 8         | 9      | 0.33%   |
| PNY                 | 8         | 10     | 0.33%   |
| LITEON              | 7         | 8      | 0.29%   |
| ShiJi               | 6         | 7      | 0.25%   |
| LITEONIT            | 6         | 9      | 0.25%   |
| KingSpec            | 6         | 8      | 0.25%   |
| Gigabyte Technology | 6         | 7      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Transcend TS128GMSA230S 128GB   | 32        | 1.27%   |
| Phison SATA SSD 16GB            | 31        | 1.23%   |
| China SATA SSD 16GB             | 28        | 1.11%   |
| Samsung SSD 850 EVO 250GB       | 25        | 0.99%   |
| A-DATA IM2S3134N-064GM 64GB     | 23        | 0.91%   |
| Samsung SSD 860 EVO 500GB       | 20        | 0.79%   |
| Kingston SA400S37120G 120GB     | 20        | 0.79%   |
| Crucial CT240BX500SSD1 240GB    | 20        | 0.79%   |
| Transcend TS64GMSA230S 64GB     | 18        | 0.71%   |
| Samsung SSD 840 EVO 250GB       | 18        | 0.71%   |
| Samsung SSD 870 EVO 250GB       | 17        | 0.67%   |
| Transcend TS64GSSD370 64GB      | 16        | 0.63%   |
| Transcend TS256GMSA230S 256GB   | 16        | 0.63%   |
| Crucial CT120BX500SSD1 120GB    | 15        | 0.59%   |
| Samsung SSD 840 EVO 120GB       | 14        | 0.55%   |
| FORESEE 128GB SSD               | 14        | 0.55%   |
| Transcend TS32GMSA370 32GB      | 13        | 0.51%   |
| Samsung SSD 860 EVO 250GB       | 13        | 0.51%   |
| Kingston SUV500MS120G 120GB     | 13        | 0.51%   |
| SanDisk SSD PLUS 240GB          | 12        | 0.48%   |
| SanDisk SSD PLUS 120GB          | 12        | 0.48%   |
| Innodisk DEMSR- 08GB mSATA 3ME3 | 12        | 0.48%   |
| Crucial CT250MX500SSD1 250GB    | 12        | 0.48%   |
| SanDisk SDSSDA120G 120GB        | 11        | 0.44%   |
| Samsung SSD 970 EVO Plus 500GB  | 11        | 0.44%   |
| Kingston SKC600MS256G 256GB     | 11        | 0.44%   |
| Kingston SA400S37240G 240GB     | 11        | 0.44%   |
| Intenso SSD 128GB               | 11        | 0.44%   |
| Hoodisk SSD 64GB                | 11        | 0.44%   |
| Hoodisk SSD 128GB               | 11        | 0.44%   |
| Transcend TS32GSSD370S 32GB     | 10        | 0.4%    |
| Transcend TS256GMTE710T 256GB   | 10        | 0.4%    |
| Samsung SSD 850 EVO 500GB       | 10        | 0.4%    |
| Intenso SSD 120GB               | 10        | 0.4%    |
| Intel SSDSC2BB120G4 120GB       | 10        | 0.4%    |
| Crucial CT500MX500SSD1 500GB    | 10        | 0.4%    |
| WDC WD40EFRX-68N32N0 4TB        | 9         | 0.36%   |
| Transcend TS128GMSA370 128GB    | 9         | 0.36%   |
| Kingston SV300S37A120G 120GB    | 9         | 0.36%   |
| Kingston SMS200S360G 64GB       | 9         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 128       | 232    | 29.09%  |
| Seagate             | 104       | 173    | 23.64%  |
| Toshiba             | 48        | 82     | 10.91%  |
| Hitachi             | 39        | 77     | 8.86%   |
| HGST                | 36        | 70     | 8.18%   |
| Samsung Electronics | 22        | 31     | 5%      |
| NVMe                | 17        | 28     | 3.86%   |
| Hewlett-Packard     | 15        | 20     | 3.41%   |
| Fujitsu             | 6         | 6      | 1.36%   |
| LSI                 | 5         | 5      | 1.14%   |
| OPENBSD             | 3         | 7      | 0.68%   |
| Maxtor              | 2         | 2      | 0.45%   |
| LSILOGIC            | 2         | 5      | 0.45%   |
| JetFlash            | 2         | 2      | 0.45%   |
| Generic             | 2         | 2      | 0.45%   |
| Apple               | 2         | 2      | 0.45%   |
| WD MediaMax         | 1         | 3      | 0.23%   |
| Product:            | 1         | 1      | 0.23%   |
| Intenso             | 1         | 1      | 0.23%   |
| IBM/Hitachi         | 1         | 1      | 0.23%   |
| IBM                 | 1         | 1      | 0.23%   |
| General             | 1         | 1      | 0.23%   |
| ASMT                | 1         | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 302       | 458    | 18.48%  |
| Transcend           | 204       | 283    | 12.48%  |
| Kingston            | 134       | 219    | 8.2%    |
| SanDisk             | 127       | 179    | 7.77%   |
| Intel               | 115       | 200    | 7.04%   |
| Crucial             | 114       | 172    | 6.98%   |
| China               | 72        | 87     | 4.41%   |
| A-DATA Technology   | 50        | 62     | 3.06%   |
| Intenso             | 49        | 75     | 3%      |
| Phison              | 36        | 52     | 2.2%    |
| Hoodisk             | 35        | 61     | 2.14%   |
| WDC                 | 33        | 38     | 2.02%   |
| Innodisk            | 31        | 37     | 1.9%    |
| Micron Technology   | 26        | 41     | 1.59%   |
| FORESEE             | 24        | 32     | 1.47%   |
| ATP                 | 20        | 21     | 1.22%   |
| Toshiba             | 18        | 28     | 1.1%    |
| OCZ                 | 15        | 24     | 0.92%   |
| Protectli           | 13        | 18     | 0.8%    |
| Apacer              | 13        | 23     | 0.8%    |
| Apple               | 12        | 15     | 0.73%   |
| Verbatim            | 10        | 16     | 0.61%   |
| SPCC                | 10        | 15     | 0.61%   |
| Patriot             | 10        | 14     | 0.61%   |
| NVMe                | 10        | 15     | 0.61%   |
| SK hynix            | 9         | 12     | 0.55%   |
| Dogfish             | 9         | 11     | 0.55%   |
| TCSUNBOW            | 8         | 9      | 0.49%   |
| PNY                 | 7         | 9      | 0.43%   |
| LITEON              | 7         | 8      | 0.43%   |
| Corsair             | 7         | 11     | 0.43%   |
| ShiJi               | 6         | 7      | 0.37%   |
| LITEONIT            | 6         | 9      | 0.37%   |
| KingSpec            | 6         | 8      | 0.37%   |
| Seagate             | 5         | 12     | 0.31%   |
| VICKTER             | 4         | 4      | 0.24%   |
| Vaseky              | 4         | 4      | 0.24%   |
| Leven               | 4         | 6      | 0.24%   |
| Kston               | 4         | 5      | 0.24%   |
| KingDian            | 4         | 11     | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1523      | 2396   | 67.63%  |
| HDD  | 374       | 753    | 16.61%  |
| NVMe | 355       | 534    | 15.76%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1776      | 3149   | 83.34%  |
| NVMe | 355       | 534    | 16.66%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1618      | 2520   | 83.92%  |
| 0.51-1.0        | 175       | 274    | 9.08%   |
| 1.01-2.0        | 71        | 176    | 3.68%   |
| 3.01-4.0        | 29        | 91     | 1.5%    |
| 2.01-3.0        | 15        | 46     | 0.78%   |
| 4.01-10.0       | 15        | 29     | 0.78%   |
| 10.01-20.0      | 4         | 12     | 0.21%   |
| More than 100.0 | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1010      | 43.57%  |
| 251-500        | 325       | 14.02%  |
| 1-20           | 292       | 12.6%   |
| 51-100         | 257       | 11.09%  |
| 21-50          | 248       | 10.7%   |
| 501-1000       | 124       | 5.35%   |
| 1001-2000      | 27        | 1.16%   |
| More than 3000 | 16        | 0.69%   |
| Unknown        | 13        | 0.56%   |
| 2001-3000      | 6         | 0.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2121      | 91.11%  |
| 21-50          | 103       | 4.42%   |
| 51-100         | 38        | 1.63%   |
| 101-250        | 27        | 1.16%   |
| Unknown        | 13        | 0.56%   |
| 251-500        | 9         | 0.39%   |
| 501-1000       | 7         | 0.3%    |
| 1001-2000      | 5         | 0.21%   |
| More than 3000 | 3         | 0.13%   |
| 2001-3000      | 2         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Kingston SV300S37A60G 64GB                   | 4         | 6      | 2.11%   |
| Kingston SMS200S360G 64GB                    | 4         | 4      | 2.11%   |
| WDC WD2000FYYZ-01UL1B2 2TB                   | 3         | 5      | 1.58%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 3         | 6      | 1.58%   |
| WDC WDS240G2G0A-00JH30 240GB                 | 2         | 3      | 1.05%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 2         | 7      | 1.05%   |
| WDC WD2000FYYZ-01UL1B1 2TB                   | 2         | 4      | 1.05%   |
| WDC WD1600AAJS-75M0A0 160GB                  | 2         | 2      | 1.05%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB         | 2         | 8      | 1.05%   |
| Toshiba THNSNK128GCS8 SATA 128GB             | 2         | 2      | 1.05%   |
| Seagate ST9320325AS 320GB                    | 2         | 2      | 1.05%   |
| Seagate ST3160318AS 160GB                    | 2         | 2      | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 2      | 1.05%   |
| Seagate ST1000DX001-1CM162 1TB               | 2         | 2      | 1.05%   |
| SanDisk SSD PLUS 240GB                       | 2         | 2      | 1.05%   |
| Samsung Electronics HD501LJ 500GB            | 2         | 2      | 1.05%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 2         | 4      | 1.05%   |
| Micron Technology 1100 SATA 256GB            | 2         | 2      | 1.05%   |
| Kingston SMS200S3120G 120GB                  | 2         | 5      | 1.05%   |
| Kingston SHFS37A120G 120GB                   | 2         | 3      | 1.05%   |
| Intenso SSD SATAIII 256GB                    | 2         | 2      | 1.05%   |
| Intel SSDSC2CT180A3 180GB                    | 2         | 2      | 1.05%   |
| Intel SSDSC2CT120A3 120GB                    | 2         | 2      | 1.05%   |
| Intel SSDSC2BF180A4L 180GB                   | 2         | 2      | 1.05%   |
| Hitachi HTS545032B9A300 320GB                | 2         | 4      | 1.05%   |
| Hitachi HTS543232L9SA02 320GB                | 2         | 3      | 1.05%   |
| Hitachi HTS543225L9A300 250GB                | 2         | 2      | 1.05%   |
| HGST HTS541010A9E680 1TB                     | 2         | 3      | 1.05%   |
| HGST HTS541010A7E630 1TB                     | 2         | 4      | 1.05%   |
| Crucial CT275MX300SSD1 275GB                 | 2         | 2      | 1.05%   |
| Crucial CT128MX100SSD1 128GB                 | 2         | 3      | 1.05%   |
| Apacer 8GB SATA Flash Drive                  | 2         | 2      | 1.05%   |
| WDC WD60EFRX-68TGBN1 6TB                     | 1         | 3      | 0.53%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 0.53%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 0.53%   |
| WDC WD3000BLFS-60YBU2 304GB                  | 1         | 2      | 0.53%   |
| WDC WD2503ABYX-01WERA1 256GB                 | 1         | 4      | 0.53%   |
| WDC WD2503ABYX-01WERA0 256GB                 | 1         | 2      | 0.53%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 0.53%   |
| WDC WD1600BEVS-07RST0 160GB                  | 1         | 1      | 0.53%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 35     | 15.43%  |
| WDC                 | 25        | 44     | 13.3%   |
| Kingston            | 18        | 25     | 9.57%   |
| Samsung Electronics | 17        | 23     | 9.04%   |
| Intel               | 15        | 17     | 7.98%   |
| Hitachi             | 15        | 21     | 7.98%   |
| Crucial             | 10        | 25     | 5.32%   |
| Toshiba             | 9         | 19     | 4.79%   |
| HGST                | 9         | 13     | 4.79%   |
| SanDisk             | 8         | 11     | 4.26%   |
| Micron Technology   | 6         | 9      | 3.19%   |
| Apacer              | 4         | 4      | 2.13%   |
| Intenso             | 3         | 3      | 1.6%    |
| A-DATA Technology   | 3         | 4      | 1.6%    |
| Transcend           | 2         | 3      | 1.06%   |
| OCZ                 | 2         | 2      | 1.06%   |
| Maxtor              | 2         | 2      | 1.06%   |
| Corsair             | 2         | 4      | 1.06%   |
| China               | 2         | 3      | 1.06%   |
| SPCC                | 1         | 1      | 0.53%   |
| SMI                 | 1         | 1      | 0.53%   |
| SK hynix            | 1         | 1      | 0.53%   |
| KingSpec            | 1         | 1      | 0.53%   |
| KingDian            | 1         | 4      | 0.53%   |
| Fujitsu             | 1         | 1      | 0.53%   |
| Apple               | 1         | 1      | 0.53%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 35     | 32.58%  |
| WDC                 | 23        | 41     | 25.84%  |
| Hitachi             | 15        | 21     | 16.85%  |
| HGST                | 9         | 13     | 10.11%  |
| Toshiba             | 5         | 9      | 5.62%   |
| Samsung Electronics | 5         | 7      | 5.62%   |
| Maxtor              | 2         | 2      | 2.25%   |
| Fujitsu             | 1         | 1      | 1.12%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 94        | 143    | 50.54%  |
| HDD  | 87        | 129    | 46.77%  |
| NVMe | 5         | 5      | 2.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-16JJ5T0 320GB               | 1         | 1      | 14.29%  |
| Transcend TS32GSSD370S 32GB                | 1         | 2      | 14.29%  |
| Samsung Electronics SSD 980 250GB          | 1         | 2      | 14.29%  |
| Micron Technology 1100_MTFDDAV256TBN 256GB | 1         | 1      | 14.29%  |
| Kingston SV300S37A60G 64GB                 | 1         | 1      | 14.29%  |
| Kingston SMS200S330G 32GB                  | 1         | 1      | 14.29%  |
| Intel SSDSC2BW120H6 120GB                  | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 2         | 2      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Transcend           | 1         | 2      | 14.29%  |
| Samsung Electronics | 1         | 2      | 14.29%  |
| Micron Technology   | 1         | 1      | 14.29%  |
| Intel               | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1901      | 3288   | 88.13%  |
| Malfunc  | 184       | 277    | 8.53%   |
| Detected | 65        | 109    | 3.01%   |
| Failed   | 7         | 9      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1670      | 62.55%  |
| AMD                              | 406       | 15.21%  |
| Samsung Electronics              | 154       | 5.77%   |
| Broadcom / LSI                   | 53        | 1.99%   |
| SanDisk                          | 52        | 1.95%   |
| Kingston Technology Company      | 36        | 1.35%   |
| ASMedia Technology               | 31        | 1.16%   |
| Phison Electronics               | 25        | 0.94%   |
| Transcend                        | 24        | 0.9%    |
| Silicon Motion                   | 23        | 0.86%   |
| MAXIO Technology (Hangzhou)      | 22        | 0.82%   |
| Nvidia                           | 19        | 0.71%   |
| Micron/Crucial Technology        | 18        | 0.67%   |
| Hewlett-Packard                  | 16        | 0.6%    |
| Marvell Technology Group         | 15        | 0.56%   |
| Toshiba                          | 13        | 0.49%   |
| Micron Technology                | 13        | 0.49%   |
| KIOXIA                           | 12        | 0.45%   |
| SK hynix                         | 10        | 0.37%   |
| Shenzhen Longsys Electronics     | 6         | 0.22%   |
| VIA Technologies                 | 5         | 0.19%   |
| JMicron Technology               | 5         | 0.19%   |
| ATP ELECTRONICS                  | 5         | 0.19%   |
| Adaptec                          | 5         | 0.19%   |
| Silicon Image                    | 3         | 0.11%   |
| Realtek Semiconductor            | 3         | 0.11%   |
| Hosin Global Electronics         | 3         | 0.11%   |
| ADATA Technology                 | 3         | 0.11%   |
| 3ware                            | 3         | 0.11%   |
| Yangtze Memory Technologies      | 2         | 0.07%   |
| ULi Electronics                  | 2         | 0.07%   |
| Solid State Storage Technology   | 2         | 0.07%   |
| Seagate Technology               | 2         | 0.07%   |
| Chelsio Communications           | 2         | 0.07%   |
| Unknown                          | 2         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| Integrated Technology Express    | 1         | 0.04%   |
| Enmotus                          | 1         | 0.04%   |
| Artop Electronic                 | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 284       | 9.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 155       | 5.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 143       | 4.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 133       | 4.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 86        | 2.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 85        | 2.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 78        | 2.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 73        | 2.44%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 73        | 2.44%   |
| AMD FCH SATA Controller [IDE mode]                                               | 64        | 2.14%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 60        | 2.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 56        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 50        | 1.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 43        | 1.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 43        | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 43        | 1.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 41        | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 39        | 1.31%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 38        | 1.27%   |
| Intel unknown                                                                    | 37        | 1.24%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 32        | 1.07%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 31        | 1.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 30        | 1%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 29        | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 29        | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 29        | 0.97%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 29        | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 28        | 0.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 27        | 0.9%    |
| AMD 400 Series Chipset SATA Controller                                           | 27        | 0.9%    |
| Intel SATA Controller [RAID mode]                                                | 25        | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                            | 25        | 0.84%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 25        | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 25        | 0.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 25        | 0.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 24        | 0.8%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 22        | 0.74%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 22        | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 21        | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 21        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1885      | 69.07%  |
| NVMe | 422       | 15.46%  |
| IDE  | 276       | 10.11%  |
| RAID | 109       | 3.99%   |
| SAS  | 19        | 0.7%    |
| SCSI | 18        | 0.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1783      | 78.89%  |
| AMD     | 456       | 20.18%  |
| ARM     | 15        | 0.66%   |
| VIA     | 2         | 0.09%   |
| Unknown | 2         | 0.09%   |
| Sun     | 1         | 0.04%   |
| PowerPC | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                          | 131       | 5.75%   |
| Intel Celeron J4125 CPU @ 2.00GHz         | 81        | 3.55%   |
| Intel Celeron N5105 @ 2.00GHz             | 47        | 2.06%   |
| Intel Celeron CPU J1900 @ 1.99GHz         | 43        | 1.89%   |
| Intel Celeron CPU J3160 @ 1.60GHz         | 39        | 1.71%   |
| Intel N100                                | 38        | 1.67%   |
| AMD GX-415GA SOC with Radeon HD Graphics  | 38        | 1.67%   |
| Intel Celeron CPU N3450 @ 1.10GHz         | 27        | 1.18%   |
| Intel Atom CPU C3558 @ 2.20GHz            | 24        | 1.05%   |
| AMD GX-222GC SOC with Radeon R5E Graphics | 24        | 1.05%   |
| Intel Core i5-6500 CPU @ 3.20GHz          | 20        | 0.88%   |
| Intel Celeron N4100 CPU @ 1.10GHz         | 19        | 0.83%   |
| AMD Ryzen Embedded V1500B                 | 19        | 0.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz         | 18        | 0.79%   |
| Intel Celeron J4105 CPU @ 1.50GHz         | 18        | 0.79%   |
| Intel Celeron CPU J3455 @ 1.50GHz         | 18        | 0.79%   |
| Intel Xeon CPU D-1518 @ 2.20GHz           | 17        | 0.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz         | 17        | 0.75%   |
| Intel Atom CPU C2558 @ 2.40GHz            | 17        | 0.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz         | 16        | 0.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz         | 16        | 0.7%    |
| Intel Celeron CPU N3150 @ 1.60GHz         | 16        | 0.7%    |
| Intel Atom CPU D525 @ 1.80GHz             | 16        | 0.7%    |
| Intel Pentium Silver J5005 CPU @ 1.50GHz  | 15        | 0.66%   |
| AMD G-T40E Processor                      | 14        | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz         | 12        | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz         | 12        | 0.53%   |
| Intel Celeron CPU N3160 @ 1.60GHz         | 12        | 0.53%   |
| AMD GX-424CC SOC with Radeon R5E Graphics | 12        | 0.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz         | 11        | 0.48%   |
| Intel Core i3-7100U CPU @ 2.40GHz         | 11        | 0.48%   |
| Intel Celeron J6412 @ 2.00GHz             | 11        | 0.48%   |
| Intel Atom Processor E3940 @ 1.60GHz      | 11        | 0.48%   |
| Intel Atom Processor E3930 @ 1.30GHz      | 11        | 0.48%   |
| Intel Atom CPU N450 @ 1.66GHz             | 11        | 0.48%   |
| Intel Core i5-8365U CPU @ 1.60GHz         | 10        | 0.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz          | 10        | 0.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz        | 10        | 0.44%   |
| Intel Core 2 Duo                          | 10        | 0.44%   |
| Intel Celeron                             | 10        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 452       | 19.9%   |
| Intel Core i5           | 351       | 15.46%  |
| AMD GX                  | 229       | 10.08%  |
| Intel Xeon              | 200       | 8.81%   |
| Intel Atom              | 176       | 7.75%   |
| Intel Core i3           | 167       | 7.35%   |
| Intel Core i7           | 159       | 7%      |
| Other                   | 124       | 5.46%   |
| Intel Pentium           | 49        | 2.16%   |
| AMD Ryzen 7             | 42        | 1.85%   |
| Intel Core 2 Duo        | 37        | 1.63%   |
| AMD Ryzen 5             | 34        | 1.5%    |
| Intel Pentium Silver    | 32        | 1.41%   |
| AMD Ryzen Embedded      | 22        | 0.97%   |
| AMD G                   | 20        | 0.88%   |
| AMD EPYC                | 17        | 0.75%   |
| AMD FX                  | 15        | 0.66%   |
| Intel Pentium Dual-Core | 12        | 0.53%   |
| Intel Core 2 Quad       | 11        | 0.48%   |
| ARM Cortex              | 11        | 0.48%   |
| Intel Pentium Gold      | 10        | 0.44%   |
| AMD Ryzen 7 PRO         | 7         | 0.31%   |
| AMD Ryzen 5 PRO         | 7         | 0.31%   |
| AMD Ryzen 3             | 7         | 0.31%   |
| AMD Ryzen 9             | 6         | 0.26%   |
| AMD Athlon 64 X2        | 5         | 0.22%   |
| AMD Athlon              | 5         | 0.22%   |
| Intel Xeon Silver       | 4         | 0.18%   |
| Intel Xeon Gold         | 4         | 0.18%   |
| AMD E                   | 4         | 0.18%   |
| Intel Pentium M         | 3         | 0.13%   |
| Intel Pentium Dual      | 3         | 0.13%   |
| Intel Genuine           | 3         | 0.13%   |
| Intel Core i9           | 3         | 0.13%   |
| Intel Core 2            | 3         | 0.13%   |
| AMD Turion II Neo       | 3         | 0.13%   |
| AMD Ryzen Threadripper  | 3         | 0.13%   |
| AMD Athlon Dual Core    | 3         | 0.13%   |
| AMD A4                  | 3         | 0.13%   |
| AMD A10                 | 3         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1235      | 54.38%  |
| 2       | 625       | 27.52%  |
| 8       | 118       | 5.2%    |
| 6       | 78        | 3.43%   |
| Unknown | 67        | 2.95%   |
| 16      | 53        | 2.33%   |
| 12      | 44        | 1.94%   |
| 1       | 31        | 1.37%   |
| 32      | 7         | 0.31%   |
| 10      | 6         | 0.26%   |
| 24      | 2         | 0.09%   |
| 128     | 1         | 0.04%   |
| 36      | 1         | 0.04%   |
| 22      | 1         | 0.04%   |
| 20      | 1         | 0.04%   |
| 3       | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2174      | 96.32%  |
| 2       | 55        | 2.44%   |
| Unknown | 28        | 1.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1414      | 62.57%  |
| 2       | 770       | 34.07%  |
| Unknown | 76        | 3.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 284       | 12.53%  |
| Unknown       | 208       | 9.18%   |
| Silvermont    | 207       | 9.13%   |
| Haswell       | 185       | 8.16%   |
| Puma          | 177       | 7.81%   |
| Goldmont plus | 157       | 6.93%   |
| Skylake       | 133       | 5.87%   |
| Goldmont      | 117       | 5.16%   |
| IvyBridge     | 106       | 4.68%   |
| SandyBridge   | 86        | 3.79%   |
| Penryn        | 66        | 2.91%   |
| Broadwell     | 65        | 2.87%   |
| Jaguar        | 59        | 2.6%    |
| Zen           | 54        | 2.38%   |
| Bonnell       | 52        | 2.29%   |
| Westmere      | 37        | 1.63%   |
| Core          | 34        | 1.5%    |
| Zen 2         | 33        | 1.46%   |
| Zen+          | 30        | 1.32%   |
| TigerLake     | 27        | 1.19%   |
| Bobcat        | 25        | 1.1%    |
| CometLake     | 23        | 1.01%   |
| Nehalem       | 18        | 0.79%   |
| Zen 3         | 17        | 0.75%   |
| Piledriver    | 16        | 0.71%   |
| K8 Hammer     | 10        | 0.44%   |
| IceLake       | 10        | 0.44%   |
| Steamroller   | 7         | 0.31%   |
| K10           | 6         | 0.26%   |
| P6            | 4         | 0.18%   |
| NetBurst      | 4         | 0.18%   |
| Bulldozer     | 4         | 0.18%   |
| Excavator     | 3         | 0.13%   |
| Geode         | 2         | 0.09%   |
| K10 Llano     | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1408      | 67.3%   |
| AMD                                          | 263       | 12.57%  |
| ASPEED Technology                            | 172       | 8.22%   |
| Nvidia                                       | 150       | 7.17%   |
| Matrox Electronics Systems                   | 94        | 4.49%   |
| VIA Technologies                             | 2         | 0.1%    |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.05%   |
| Trident Microsystems                         | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 172       | 8.09%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 134       | 6.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 87        | 4.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 80        | 3.76%   |
| Intel HD Graphics 500                                                                    | 75        | 3.53%   |
| Intel JasperLake [UHD Graphics]                                                          | 72        | 3.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 66        | 3.1%    |
| Intel Alder Lake-N [UHD Graphics]                                                        | 53        | 2.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 53        | 2.49%   |
| Intel HD Graphics 620                                                                    | 52        | 2.44%   |
| Intel HD Graphics 530                                                                    | 49        | 2.3%    |
| Intel UHD Graphics 620                                                                   | 43        | 2.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 42        | 1.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 38        | 1.79%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 38        | 1.79%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 38        | 1.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 37        | 1.74%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 37        | 1.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 33        | 1.55%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 33        | 1.55%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 29        | 1.36%   |
| Intel HD Graphics 5500                                                                   | 27        | 1.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 1.18%   |
| Matrox Electronics Systems MGA G200EH                                                    | 24        | 1.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 23        | 1.08%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 23        | 1.08%   |
| Intel HD Graphics 630                                                                    | 20        | 0.94%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 19        | 0.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 19        | 0.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 0.89%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 18        | 0.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 0.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 0.8%    |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 16        | 0.75%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 15        | 0.71%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 14        | 0.66%   |
| Intel HD Graphics 510                                                                    | 13        | 0.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 0.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 0.56%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 12        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1262      | 55.72%  |
| 1 x AMD                  | 248       | 10.95%  |
| Other                    | 245       | 10.82%  |
| 1 x ASPEED               | 155       | 6.84%   |
| 1 x Nvidia               | 105       | 4.64%   |
| 1 x Matrox               | 92        | 4.06%   |
| 2 x Intel                | 79        | 3.49%   |
| Intel + Nvidia           | 41        | 1.81%   |
| Intel + ASPEED           | 15        | 0.66%   |
| Intel + AMD              | 9         | 0.4%    |
| AMD + Nvidia             | 4         | 0.18%   |
| 1 x VIA                  | 2         | 0.09%   |
| Intel + Matrox           | 2         | 0.09%   |
| 2 x AMD                  | 1         | 0.04%   |
| 1 x XGI                  | 1         | 0.04%   |
| 1 x Trident Microsystems | 1         | 0.04%   |
| 1 x SiS                  | 1         | 0.04%   |
| Nvidia + ASPEED          | 1         | 0.04%   |
| AMD + ASPEED             | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1920      | 84.81%  |
| Unknown     | 267       | 11.79%  |
| Proprietary | 77        | 3.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2148      | 94.63%  |
| 1.01-2.0   | 34        | 1.5%    |
| 0.01-0.5   | 30        | 1.32%   |
| 3.01-4.0   | 19        | 0.84%   |
| 7.01-8.0   | 13        | 0.57%   |
| 0.51-1.0   | 11        | 0.48%   |
| 5.01-6.0   | 10        | 0.44%   |
| 2.01-3.0   | 4         | 0.18%   |
| 8.01-16.0  | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 45        | 12%     |
| AU Optronics         | 40        | 10.67%  |
| Samsung Electronics  | 38        | 10.13%  |
| Dell                 | 23        | 6.13%   |
| Chimei Innolux       | 22        | 5.87%   |
| Apple                | 22        | 5.87%   |
| Goldstar             | 21        | 5.6%    |
| BOE                  | 18        | 4.8%    |
| BenQ                 | 17        | 4.53%   |
| Lenovo               | 16        | 4.27%   |
| Acer                 | 11        | 2.93%   |
| Ancor Communications | 10        | 2.67%   |
| Hewlett-Packard      | 9         | 2.4%    |
| Iiyama               | 8         | 2.13%   |
| Eizo                 | 8         | 2.13%   |
| Sharp                | 6         | 1.6%    |
| NEC Computers        | 6         | 1.6%    |
| LG Electronics       | 6         | 1.6%    |
| Fujitsu Siemens      | 6         | 1.6%    |
| AOC                  | 5         | 1.33%   |
| InfoVision           | 4         | 1.07%   |
| Philips              | 3         | 0.8%    |
| PANDA                | 3         | 0.8%    |
| Idek Iiyama          | 3         | 0.8%    |
| Unknown              | 3         | 0.8%    |
| LG Philips           | 2         | 0.53%   |
| HannStar             | 2         | 0.53%   |
| Belinea              | 2         | 0.53%   |
| ASUSTek Computer     | 2         | 0.53%   |
| WYT                  | 1         | 0.27%   |
| Vestel Elektronik    | 1         | 0.27%   |
| TRU                  | 1         | 0.27%   |
| Toshiba              | 1         | 0.27%   |
| Quanta Display       | 1         | 0.27%   |
| Panasonic            | 1         | 0.27%   |
| Mi                   | 1         | 0.27%   |
| Medion               | 1         | 0.27%   |
| LTM                  | 1         | 0.27%   |
| JDI                  | 1         | 0.27%   |
| CSO                  | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 5         | 1.28%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 4         | 1.02%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 4         | 1.02%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 3         | 0.77%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 3         | 0.77%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 3         | 0.77%   |
| Fujitsu Siemens B24-9 WE FUS08C3 1920x1200 520x320mm 24.0-inch       | 3         | 0.77%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                 | 3         | 0.77%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 3         | 0.77%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 3         | 0.77%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 3         | 0.77%   |
| Unknown                                                              | 3         | 0.77%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch              | 2         | 0.51%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch    | 2         | 0.51%   |
| Samsung Electronics C32JG5x SAM0FDE 2560x1440 700x390mm 31.5-inch    | 2         | 0.51%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 600x340mm 27.2-inch    | 2         | 0.51%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch              | 2         | 0.51%   |
| NEC Computers EX341R NEC2C7A 3440x1440 800x330mm 34.1-inch           | 2         | 0.51%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch         | 2         | 0.51%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 2         | 0.51%   |
| LG Display LCD Monitor LGD04A3 1366x768 280x160mm 12.7-inch          | 2         | 0.51%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch         | 2         | 0.51%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch          | 2         | 0.51%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 2         | 0.51%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 2         | 0.51%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 2         | 0.51%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 2         | 0.51%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 2         | 0.51%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 540x350mm 25.3-inch        | 2         | 0.51%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 540x350mm 25.3-inch        | 2         | 0.51%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch         | 2         | 0.51%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                 | 2         | 0.51%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 2         | 0.51%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch             | 2         | 0.51%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                 | 2         | 0.51%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                    | 2         | 0.51%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 2         | 0.51%   |
| Dell LCD Monitor U2412M 3840x1200                                    | 2         | 0.51%   |
| Dell LCD Monitor U2412M                                              | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 2         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 144       | 38.5%   |
| 1366x768 (WXGA)    | 57        | 15.24%  |
| 2560x1440 (QHD)    | 32        | 8.56%   |
| 3840x2160 (4K)     | 29        | 7.75%   |
| 1920x1200 (WUXGA)  | 25        | 6.68%   |
| 1280x800 (WXGA)    | 13        | 3.48%   |
| 1680x1050 (WSXGA+) | 12        | 3.21%   |
| 1280x1024 (SXGA)   | 11        | 2.94%   |
| 1600x900 (HD+)     | 10        | 2.67%   |
| 1440x900 (WXGA+)   | 10        | 2.67%   |
| 3440x1440          | 5         | 1.34%   |
| 2560x1600          | 5         | 1.34%   |
| 2560x1080          | 3         | 0.8%    |
| Unknown            | 3         | 0.8%    |
| 3840x1200          | 2         | 0.53%   |
| 3200x1800 (QHD+)   | 2         | 0.53%   |
| 2880x1800          | 2         | 0.53%   |
| 1920x540           | 2         | 0.53%   |
| 1024x768 (XGA)     | 2         | 0.53%   |
| 9600x2160          | 1         | 0.27%   |
| 720x1280           | 1         | 0.27%   |
| 3840x1080          | 1         | 0.27%   |
| 3600x1080          | 1         | 0.27%   |
| 3000x2000          | 1         | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 73        | 19.47%  |
| 15      | 58        | 15.47%  |
| 27      | 46        | 12.27%  |
| 24      | 43        | 11.47%  |
| 12      | 29        | 7.73%   |
| Unknown | 27        | 7.2%    |
| 23      | 17        | 4.53%   |
| 21      | 15        | 4%      |
| 17      | 9         | 2.4%    |
| 11      | 9         | 2.4%    |
| 14      | 8         | 2.13%   |
| 22      | 7         | 1.87%   |
| 19      | 7         | 1.87%   |
| 34      | 6         | 1.6%    |
| 31      | 4         | 1.07%   |
| 25      | 3         | 0.8%    |
| 20      | 3         | 0.8%    |
| 32      | 2         | 0.53%   |
| 46      | 1         | 0.27%   |
| 42      | 1         | 0.27%   |
| 40      | 1         | 0.27%   |
| 39      | 1         | 0.27%   |
| 29      | 1         | 0.27%   |
| 26      | 1         | 0.27%   |
| 18      | 1         | 0.27%   |
| 16      | 1         | 0.27%   |
| 6       | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 108       | 28.95%  |
| 501-600     | 104       | 27.88%  |
| 201-300     | 71        | 19.03%  |
| Unknown     | 27        | 7.24%   |
| 401-500     | 26        | 6.97%   |
| 351-400     | 14        | 3.75%   |
| 601-700     | 10        | 2.68%   |
| 701-800     | 8         | 2.14%   |
| 801-900     | 2         | 0.54%   |
| 101-200     | 1         | 0.27%   |
| 1001-1500   | 1         | 0.27%   |
| 901-1000    | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 249       | 69.36%  |
| 16/10   | 62        | 17.27%  |
| Unknown | 26        | 7.24%   |
| 5/4     | 8         | 2.23%   |
| 21/9    | 6         | 1.67%   |
| 3/2     | 4         | 1.11%   |
| 4/3     | 3         | 0.84%   |
| 6/5     | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 66        | 17.6%   |
| 201-250        | 59        | 15.73%  |
| 301-350        | 47        | 12.53%  |
| 91-100         | 38        | 10.13%  |
| 61-70          | 29        | 7.73%   |
| Unknown        | 27        | 7.2%    |
| 251-300        | 25        | 6.67%   |
| 101-110        | 21        | 5.6%    |
| 71-80          | 14        | 3.73%   |
| 351-500        | 13        | 3.47%   |
| 151-200        | 12        | 3.2%    |
| 51-60          | 9         | 2.4%    |
| 121-130        | 7         | 1.87%   |
| 501-1000       | 4         | 1.07%   |
| 141-150        | 2         | 0.53%   |
| 1-40           | 1         | 0.27%   |
| 131-140        | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 113       | 30.62%  |
| 121-160       | 109       | 29.54%  |
| 101-120       | 69        | 18.7%   |
| 161-240       | 38        | 10.3%   |
| Unknown       | 27        | 7.32%   |
| More than 240 | 11        | 2.98%   |
| 1-50          | 2         | 0.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1890      | 83.33%  |
| 1     | 342       | 15.08%  |
| 2     | 34        | 1.5%    |
| 3     | 2         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1815      | 58.57%  |
| Realtek Semiconductor             | 698       | 22.52%  |
| Broadcom                          | 172       | 5.55%   |
| Qualcomm Atheros                  | 136       | 4.39%   |
| AMD                               | 30        | 0.97%   |
| Mellanox Technologies             | 19        | 0.61%   |
| IMC Networks                      | 18        | 0.58%   |
| Ralink Technology                 | 15        | 0.48%   |
| Ericsson Business Mobile Networks | 14        | 0.45%   |
| TP-Link                           | 13        | 0.42%   |
| Marvell Technology Group          | 13        | 0.42%   |
| Edimax Technology                 | 12        | 0.39%   |
| Nvidia                            | 11        | 0.35%   |
| Sierra Wireless                   | 10        | 0.32%   |
| U-Blox                            | 9         | 0.29%   |
| American Megatrends               | 9         | 0.29%   |
| Ralink                            | 8         | 0.26%   |
| D-Link System                     | 8         | 0.26%   |
| MediaTek                          | 7         | 0.23%   |
| Chelsio Communications            | 6         | 0.19%   |
| Huawei Technologies               | 5         | 0.16%   |
| Google                            | 5         | 0.16%   |
| Emulex                            | 5         | 0.16%   |
| IBM                               | 4         | 0.13%   |
| Dell                              | 4         | 0.13%   |
| ASUSTek Computer                  | 4         | 0.13%   |
| Aquantia                          | 4         | 0.13%   |
| Samsung Electronics               | 3         | 0.1%    |
| Hewlett-Packard                   | 3         | 0.1%    |
| ZTE WCDMA Technologies MSM        | 2         | 0.06%   |
| Qualcomm Technologies             | 2         | 0.06%   |
| Qualcomm Atheros Communications   | 2         | 0.06%   |
| NetXen Incorporated               | 2         | 0.06%   |
| Insyde Software                   | 2         | 0.06%   |
| ICS Advent                        | 2         | 0.06%   |
| Fibocom                           | 2         | 0.06%   |
| Dresden Elektronik                | 2         | 0.06%   |
| Apple                             | 2         | 0.06%   |
| Xiaomi                            | 1         | 0.03%   |
| Winbond Electronics               | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 600       | 15.54%  |
| Intel I211 Gigabit Network Connection                                         | 395       | 10.23%  |
| Intel I210 Gigabit Network Connection                                         | 294       | 7.61%   |
| Intel I350 Gigabit Network Connection                                         | 150       | 3.88%   |
| Intel Ethernet Controller I225-V                                              | 125       | 3.24%   |
| Intel Ethernet Controller I226-V                                              | 100       | 2.59%   |
| Intel 82574L Gigabit Network Connection                                       | 93        | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 76        | 1.97%   |
| Intel 82580 Gigabit Network Connection                                        | 50        | 1.29%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 44        | 1.14%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 41        | 1.06%   |
| Intel 82576 Gigabit Network Connection                                        | 40        | 1.04%   |
| Intel Wi-Fi 6 AX200                                                           | 39        | 1.01%   |
| Intel Ethernet Connection I354                                                | 39        | 1.01%   |
| Intel 82583V Gigabit Network Connection                                       | 39        | 1.01%   |
| Intel Wireless 7265                                                           | 37        | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                             | 36        | 0.93%   |
| Intel Wireless 3165                                                           | 36        | 0.93%   |
| Intel Ethernet Connection X553 1GbE                                           | 35        | 0.91%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 34        | 0.88%   |
| Intel Ethernet Connection I217-LM                                             | 33        | 0.85%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 30        | 0.78%   |
| AMD XGMAC 10GbE Controller                                                    | 30        | 0.78%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 29        | 0.75%   |
| Intel Wireless 8265 / 8275                                                    | 27        | 0.7%    |
| Intel Ethernet Connection I219-LM                                             | 26        | 0.67%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 24        | 0.62%   |
| Intel Ethernet Connection (2) I219-V                                          | 24        | 0.62%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 24        | 0.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 23        | 0.6%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 22        | 0.57%   |
| Intel Wireless 8260                                                           | 22        | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                                         | 22        | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 20        | 0.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 20        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                                         | 20        | 0.52%   |
| Intel Wireless 7260                                                           | 19        | 0.49%   |
| Intel Ethernet Connection (7) I219-V                                          | 19        | 0.49%   |
| Intel Wireless 3160                                                           | 17        | 0.44%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 17        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 392       | 52.48%  |
| Qualcomm Atheros                | 122       | 16.33%  |
| Realtek Semiconductor           | 87        | 11.65%  |
| Broadcom                        | 53        | 7.1%    |
| IMC Networks                    | 18        | 2.41%   |
| Ralink Technology               | 15        | 2.01%   |
| TP-Link                         | 13        | 1.74%   |
| Edimax Technology               | 12        | 1.61%   |
| Ralink                          | 8         | 1.07%   |
| Sierra Wireless                 | 7         | 0.94%   |
| MediaTek                        | 7         | 0.94%   |
| ASUSTek Computer                | 4         | 0.54%   |
| Qualcomm Technologies           | 2         | 0.27%   |
| Qualcomm Atheros Communications | 2         | 0.27%   |
| NetGear                         | 1         | 0.13%   |
| Micro Star International        | 1         | 0.13%   |
| Marvell Technology Group        | 1         | 0.13%   |
| Dell                            | 1         | 0.13%   |
| Accton Technology               | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                             | 39        | 5.17%   |
| Intel Wireless 7265                                             | 37        | 4.91%   |
| Intel Wireless 3165                                             | 36        | 4.77%   |
| Intel Wireless 8265 / 8275                                      | 27        | 3.58%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 24        | 3.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 23        | 3.05%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 22        | 2.92%   |
| Intel Wireless 8260                                             | 22        | 2.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 20        | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 20        | 2.65%   |
| Intel Wireless 7260                                             | 19        | 2.52%   |
| Intel Wireless 3160                                             | 17        | 2.25%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 17        | 2.25%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 15        | 1.99%   |
| Intel Centrino Ultimate-N 6300                                  | 15        | 1.99%   |
| Intel Centrino Advanced-N 6235                                  | 13        | 1.72%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 12        | 1.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 12        | 1.59%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 11        | 1.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 11        | 1.46%   |
| Broadcom BCM43224 802.11a/b/g/n                                 | 11        | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 10        | 1.33%   |
| Intel Wi-Fi 6 AX201                                             | 10        | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 10        | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 9         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 9         | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 9         | 1.19%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 9         | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 8         | 1.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 7         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 7         | 0.93%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection   | 7         | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 7         | 0.93%   |
| Broadcom BCM4321 802.11a/b/g/n                                  | 7         | 0.93%   |
| Sierra Wireless EM7455                                          | 6         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection           | 6         | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 6         | 0.8%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 6         | 0.8%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller          | 6         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 5         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 1615      | 63.83%  |
| Realtek Semiconductor       | 666       | 26.32%  |
| Broadcom                    | 129       | 5.1%    |
| AMD                         | 30        | 1.19%   |
| Qualcomm Atheros            | 17        | 0.67%   |
| Marvell Technology Group    | 12        | 0.47%   |
| Nvidia                      | 11        | 0.43%   |
| American Megatrends         | 9         | 0.36%   |
| Google                      | 5         | 0.2%    |
| D-Link System               | 5         | 0.2%    |
| Emulex                      | 4         | 0.16%   |
| Aquantia                    | 4         | 0.16%   |
| Samsung Electronics         | 3         | 0.12%   |
| ZTE WCDMA Technologies MSM  | 2         | 0.08%   |
| Insyde Software             | 2         | 0.08%   |
| ICS Advent                  | 2         | 0.08%   |
| Chelsio Communications      | 2         | 0.08%   |
| Apple                       | 2         | 0.08%   |
| Xiaomi                      | 1         | 0.04%   |
| T & A Mobile Phones         | 1         | 0.04%   |
| SysKonnect                  | 1         | 0.04%   |
| Standard Microsystems [SMC] | 1         | 0.04%   |
| QLogic                      | 1         | 0.04%   |
| National Semiconductor      | 1         | 0.04%   |
| MYRICOM                     | 1         | 0.04%   |
| JMicron Technology          | 1         | 0.04%   |
| Digital Equipment           | 1         | 0.04%   |
| Davicom Semiconductor       | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 600       | 19.93%  |
| Intel I211 Gigabit Network Connection                                         | 395       | 13.12%  |
| Intel I210 Gigabit Network Connection                                         | 294       | 9.77%   |
| Intel I350 Gigabit Network Connection                                         | 150       | 4.98%   |
| Intel Ethernet Controller I225-V                                              | 125       | 4.15%   |
| Intel Ethernet Controller I226-V                                              | 100       | 3.32%   |
| Intel 82574L Gigabit Network Connection                                       | 93        | 3.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 76        | 2.52%   |
| Intel 82580 Gigabit Network Connection                                        | 50        | 1.66%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 44        | 1.46%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 41        | 1.36%   |
| Intel 82576 Gigabit Network Connection                                        | 40        | 1.33%   |
| Intel Ethernet Connection I354                                                | 39        | 1.3%    |
| Intel 82583V Gigabit Network Connection                                       | 39        | 1.3%    |
| Realtek RTL8125 2.5GbE Controller                                             | 35        | 1.16%   |
| Intel Ethernet Connection X553 1GbE                                           | 35        | 1.16%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 34        | 1.13%   |
| Intel Ethernet Connection I217-LM                                             | 33        | 1.1%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 30        | 1%      |
| AMD XGMAC 10GbE Controller                                                    | 30        | 1%      |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 29        | 0.96%   |
| Intel Ethernet Connection I219-LM                                             | 26        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                                          | 24        | 0.8%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 24        | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                         | 22        | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                                         | 20        | 0.66%   |
| Intel Ethernet Connection (7) I219-V                                          | 19        | 0.63%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 17        | 0.56%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 16        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 15        | 0.5%    |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 15        | 0.5%    |
| Intel Ethernet Controller X550                                                | 15        | 0.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 14        | 0.47%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 13        | 0.43%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 13        | 0.43%   |
| Intel Ethernet Connection (4) I219-V                                          | 12        | 0.4%    |
| Intel Ethernet Connection I217-V                                              | 11        | 0.37%   |
| Intel 82579V Gigabit Network Connection                                       | 11        | 0.37%   |
| Intel 82577LM Gigabit Network Connection                                      | 11        | 0.37%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 11        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2197      | 73.58%  |
| WiFi     | 695       | 23.28%  |
| Unknown  | 63        | 2.11%   |
| Modem    | 31        | 1.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2096      | 90.23%  |
| WiFi     | 216       | 9.3%    |
| Unknown  | 10        | 0.43%   |
| Modem    | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 513       | 22.44%  |
| 4     | 464       | 20.3%   |
| 3     | 349       | 15.27%  |
| 6     | 280       | 12.25%  |
| 1     | 260       | 11.37%  |
| 5     | 187       | 8.18%   |
| 8     | 103       | 4.51%   |
| 10    | 36        | 1.57%   |
| 7     | 27        | 1.18%   |
| 9     | 23        | 1.01%   |
| 0     | 20        | 0.87%   |
| 12    | 12        | 0.52%   |
| 14    | 5         | 0.22%   |
| 20    | 2         | 0.09%   |
| 16    | 2         | 0.09%   |
| 11    | 2         | 0.09%   |
| 17    | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1817      | 77.22%  |
| Yes  | 536       | 22.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 271       | 58.53%  |
| Realtek Semiconductor           | 33        | 7.13%   |
| Apple                           | 33        | 7.13%   |
| Qualcomm Atheros Communications | 31        | 6.7%    |
| IMC Networks                    | 28        | 6.05%   |
| Broadcom                        | 26        | 5.62%   |
| Foxconn / Hon Hai               | 9         | 1.94%   |
| ASUSTek Computer                | 7         | 1.51%   |
| Lite-On Technology              | 5         | 1.08%   |
| Dell                            | 4         | 0.86%   |
| Cambridge Silicon Radio         | 4         | 0.86%   |
| MediaTek                        | 3         | 0.65%   |
| Hewlett-Packard                 | 3         | 0.65%   |
| USI                             | 2         | 0.43%   |
| Alps Electric                   | 2         | 0.43%   |
| Micro Star International        | 1         | 0.22%   |
| Unknown                         | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 118       | 25.27%  |
| Intel AX200 Bluetooth                                       | 40        | 8.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 37        | 7.92%   |
| Intel AX201 Bluetooth                                       | 24        | 5.14%   |
| Realtek Bluetooth Adapter                                   | 20        | 4.28%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 17        | 3.64%   |
| Apple Bluetooth Host Controller                             | 16        | 3.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 15        | 3.21%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 14        | 3%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 12        | 2.57%   |
| Intel Wireless-AC 3168 Bluetooth                            | 10        | 2.14%   |
| Intel AX210 Bluetooth                                       | 10        | 2.14%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 10        | 2.14%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 9         | 1.93%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 8         | 1.71%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 6         | 1.28%   |
| Realtek Bluetooth 4.2 Adapter                               | 4         | 0.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 4         | 0.86%   |
| IMC Networks Realtek Bluetooth Adapter                      | 4         | 0.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 0.86%   |
| Apple Broadcom Built-in Bluetooth                           | 4         | 0.86%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 0.64%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 3         | 0.64%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 0.64%   |
| MediaTek RZ608 Bluetooth Adapter                            | 3         | 0.64%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 0.64%   |
| ASUS USB-BT500                                              | 3         | 0.64%   |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 2         | 0.43%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 0.43%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 2         | 0.43%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 2         | 0.43%   |
| Intel AX211 Bluetooth                                       | 2         | 0.43%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 2         | 0.43%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 0.43%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 0.43%   |
| Dell DW375 Bluetooth Module                                 | 2         | 0.43%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 2         | 0.43%   |
| Broadcom BCM2045 Bluetooth                                  | 2         | 0.43%   |
| Apple Bluetooth USB Host Controller                         | 2         | 0.43%   |
| Apple Bluetooth HCI                                         | 2         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1225      | 71.6%   |
| AMD                                          | 297       | 17.36%  |
| Nvidia                                       | 105       | 6.14%   |
| C-Media Electronics                          | 18        | 1.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 8         | 0.47%   |
| Logitech                                     | 8         | 0.47%   |
| GN Netcom                                    | 5         | 0.29%   |
| Texas Instruments                            | 4         | 0.23%   |
| JMTek                                        | 4         | 0.23%   |
| VIA Technologies                             | 3         | 0.18%   |
| Tenx Technology                              | 3         | 0.18%   |
| Realtek Semiconductor                        | 3         | 0.18%   |
| Creative Labs                                | 3         | 0.18%   |
| Kingston Technology                          | 2         | 0.12%   |
| Creative Technology                          | 2         | 0.12%   |
| Corsair                                      | 2         | 0.12%   |
| Audient                                      | 2         | 0.12%   |
| ZOOM                                         | 1         | 0.06%   |
| Yamaha                                       | 1         | 0.06%   |
| ULi Electronics                              | 1         | 0.06%   |
| Trust                                        | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.06%   |
| RME                                          | 1         | 0.06%   |
| Phison Electronics                           | 1         | 0.06%   |
| Native Instruments                           | 1         | 0.06%   |
| MosArt Semiconductor                         | 1         | 0.06%   |
| M-Audio                                      | 1         | 0.06%   |
| Lenovo                                       | 1         | 0.06%   |
| Hewlett-Packard                              | 1         | 0.06%   |
| Generalplus Technology                       | 1         | 0.06%   |
| ESS Technology                               | 1         | 0.06%   |
| DSEA A/S                                     | 1         | 0.06%   |
| Blue Microphones                             | 1         | 0.06%   |
| AudioQuest                                   | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 135       | 6.72%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 131       | 6.52%   |
| AMD Kabini HDMI/DP Audio                                                                          | 96        | 4.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 88        | 4.38%   |
| AMD FCH Azalia Controller                                                                         | 83        | 4.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 79        | 3.93%   |
| Intel Jasper Lake HD Audio                                                                        | 72        | 3.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 71        | 3.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 68        | 3.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 56        | 2.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 56        | 2.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 54        | 2.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 51        | 2.54%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 49        | 2.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 45        | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 44        | 2.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 42        | 2.09%   |
| Intel 8 Series HD Audio Controller                                                                | 42        | 2.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 35        | 1.74%   |
| Intel Broadwell-U Audio Controller                                                                | 34        | 1.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 31        | 1.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 30        | 1.49%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 29        | 1.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 27        | 1.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 27        | 1.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 26        | 1.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 24        | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 23        | 1.14%   |
| Intel 200 Series PCH HD Audio                                                                     | 23        | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 22        | 1.09%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 22        | 1.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 18        | 0.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 12        | 0.6%    |
| Intel Elkhart Lake High Density Audio bus interface                                               | 12        | 0.6%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 10        | 0.5%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 10        | 0.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 10        | 0.5%    |
| Nvidia MCP79 High Definition Audio                                                                | 9         | 0.45%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 9         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 418       | 18.4%   |
| Unknown                      | 291       | 12.81%  |
| Crucial                      | 272       | 11.97%  |
| Kingston                     | 242       | 10.65%  |
| SK hynix                     | 233       | 10.26%  |
| Micron Technology            | 179       | 7.88%   |
| G.Skill                      | 99        | 4.36%   |
| Unknown                      | 80        | 3.52%   |
| Corsair                      | 78        | 3.43%   |
| Transcend                    | 66        | 2.9%    |
| A-DATA Technology            | 49        | 2.16%   |
| Unknown (ABCD)               | 47        | 2.07%   |
| ATP                          | 30        | 1.32%   |
| Nanya Technology             | 29        | 1.28%   |
| Ramaxel Technology           | 21        | 0.92%   |
| Hewlett-Packard              | 17        | 0.75%   |
| Apacer                       | 17        | 0.75%   |
| Elpida                       | 11        | 0.48%   |
| Toshiba                      | 7         | 0.31%   |
| Patriot                      | 6         | 0.26%   |
| Kimtigo                      | 6         | 0.26%   |
| Shenzhen Jinge Information   | 5         | 0.22%   |
| Innodisk                     | 4         | 0.18%   |
| Wodposit                     | 3         | 0.13%   |
| SK_Hynix                     | 3         | 0.13%   |
| Mushkin                      | 3         | 0.13%   |
| Avant                        | 3         | 0.13%   |
| Unknown (AB)                 | 2         | 0.09%   |
| Unknown (89EC)               | 2         | 0.09%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 2         | 0.09%   |
| Unknown (09C7)               | 2         | 0.09%   |
| Timetec                      | 2         | 0.09%   |
| Tigo                         | 2         | 0.09%   |
| Teikon                       | 2         | 0.09%   |
| Qimonda                      | 2         | 0.09%   |
| PNY                          | 2         | 0.09%   |
| Lexar Co Limited             | 2         | 0.09%   |
| HPE                          | 2         | 0.09%   |
| GeIL                         | 2         | 0.09%   |
| 48spaces                     | 2         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 80        | 3.35%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 59        | 2.47%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 47        | 1.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 24        | 1%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 21        | 0.88%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s          | 19        | 0.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 16        | 0.67%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s        | 15        | 0.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 14        | 0.59%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 14        | 0.59%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 13        | 0.54%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 13        | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 13        | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 13        | 0.54%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                   | 12        | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 12        | 0.5%    |
| ATP RAM X4G08QA8BNWESO-7-TO1 8GB SODIMM DDR4 3200MT/s        | 11        | 0.46%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 10        | 0.42%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s           | 10        | 0.42%   |
| G.Skill RAM F4-2400C16-8GRS 8GB SODIMM DDR4 2400MT/s         | 10        | 0.42%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 10        | 0.42%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 9         | 0.38%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 9         | 0.38%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 9         | 0.38%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 9         | 0.38%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 9         | 0.38%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s      | 9         | 0.38%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s        | 9         | 0.38%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s        | 9         | 0.38%   |
| ATP RAM AW12P6438BLK0S 4GB DIMM DDR3 1600MT/s                | 9         | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 8         | 0.33%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 8         | 0.33%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s         | 8         | 0.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 7         | 0.29%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                     | 7         | 0.29%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                   | 7         | 0.29%   |
| Transcend RAM TS512MSK64W6H 4GB DIMM DDR3 1600MT/s           | 7         | 0.29%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 7         | 0.29%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 7         | 0.29%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s          | 7         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 917       | 44.21%  |
| DDR4    | 848       | 40.89%  |
| DDR2    | 95        | 4.58%   |
| LPDDR4  | 69        | 3.33%   |
| DDR5    | 48        | 2.31%   |
| Unknown | 38        | 1.83%   |
| SDRAM   | 25        | 1.21%   |
| LPDDR5  | 11        | 0.53%   |
| DDR     | 11        | 0.53%   |
| LPDDR3  | 10        | 0.48%   |
| RAM     | 1         | 0.05%   |
| DRAM    | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1099      | 53.38%  |
| DIMM         | 903       | 43.86%  |
| Row Of Chips | 40        | 1.94%   |
| Unknown      | 9         | 0.44%   |
| Chip         | 6         | 0.29%   |
| FB-DIMM      | 2         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 784       | 35.91%  |
| 4096  | 688       | 31.52%  |
| 16384 | 343       | 15.71%  |
| 2048  | 263       | 12.05%  |
| 32768 | 60        | 2.75%   |
| 1024  | 38        | 1.74%   |
| 512   | 4         | 0.18%   |
| 256   | 2         | 0.09%   |
| 65536 | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 589       | 27.22%  |
| 2400    | 287       | 13.26%  |
| 1333    | 262       | 12.11%  |
| 2667    | 243       | 11.23%  |
| 3200    | 227       | 10.49%  |
| 2133    | 114       | 5.27%   |
| 667     | 69        | 3.19%   |
| 800     | 66        | 3.05%   |
| 4800    | 40        | 1.85%   |
| 1867    | 38        | 1.76%   |
| Unknown | 35        | 1.62%   |
| 2666    | 29        | 1.34%   |
| 1067    | 22        | 1.02%   |
| 1334    | 21        | 0.97%   |
| 1066    | 21        | 0.97%   |
| 1866    | 20        | 0.92%   |
| 3000    | 15        | 0.69%   |
| 2933    | 15        | 0.69%   |
| 6400    | 11        | 0.51%   |
| 5600    | 6         | 0.28%   |
| 4267    | 5         | 0.23%   |
| 3600    | 5         | 0.23%   |
| 533     | 4         | 0.18%   |
| 1033    | 3         | 0.14%   |
| 400     | 3         | 0.14%   |
| 333     | 3         | 0.14%   |
| 5200    | 2         | 0.09%   |
| 975     | 2         | 0.09%   |
| 65535   | 1         | 0.05%   |
| 3534    | 1         | 0.05%   |
| 3500    | 1         | 0.05%   |
| 2800    | 1         | 0.05%   |
| 2600    | 1         | 0.05%   |
| 1639    | 1         | 0.05%   |
| 1419    | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 42.86%  |
| Ricoh               | 1         | 14.29%  |
| QinHeng Electronics | 1         | 14.29%  |
| Prolific Technology | 1         | 14.29%  |
| Hewlett-Packard     | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Brother MFC-7360N             | 2         | 28.57%  |
| Ricoh SP 112                  | 1         | 14.29%  |
| QinHeng CH340S                | 1         | 14.29%  |
| Prolific PL2305 Parallel Port | 1         | 14.29%  |
| HP HP LaserJet P2035 HP Print | 1         | 14.29%  |
| Brother HL-L2310D series      | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 60%     |
| Seiko Epson | 2         | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 2         | 40%     |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 20%     |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                 | 1         | 20%     |
| Canon CanoScan LiDE 120                                                             | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 71        | 31.98%  |
| Bison Electronics                      | 27        | 12.16%  |
| IMC Networks                           | 14        | 6.31%   |
| Realtek Semiconductor                  | 13        | 5.86%   |
| Microdia                               | 13        | 5.86%   |
| Logitech                               | 11        | 4.95%   |
| Lite-On Technology                     | 10        | 4.5%    |
| Suyin                                  | 9         | 4.05%   |
| Sunplus Innovation Technology          | 9         | 4.05%   |
| Apple                                  | 8         | 3.6%    |
| Syntek                                 | 7         | 3.15%   |
| Lenovo                                 | 5         | 2.25%   |
| Alcor Micro                            | 4         | 1.8%    |
| Quanta                                 | 3         | 1.35%   |
| Z-Star Microelectronics                | 2         | 0.9%    |
| Silicon Motion                         | 2         | 0.9%    |
| Luxvisions Innotech Limited            | 2         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 0.9%    |
| ARC International                      | 2         | 0.9%    |
| Trust                                  | 1         | 0.45%   |
| Tripath Technology                     | 1         | 0.45%   |
| SunplusIT                              | 1         | 0.45%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.45%   |
| Ricoh                                  | 1         | 0.45%   |
| Pixart Imaging                         | 1         | 0.45%   |
| Intel                                  | 1         | 0.45%   |
| Cubeternet                             | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 30        | 13.45%  |
| Bison Integrated Camera                  | 13        | 5.83%   |
| IMC Networks Integrated Camera           | 7         | 3.14%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 7         | 3.14%   |
| Lite-On Integrated Camera                | 6         | 2.69%   |
| Chicony FJ Camera                        | 6         | 2.69%   |
| Realtek USB 2.0 PC Camera                | 5         | 2.24%   |
| Microdia Integrated Webcam               | 5         | 2.24%   |
| Chicony HD WebCam                        | 5         | 2.24%   |
| Apple FaceTime HD Camera (Built-in)      | 4         | 1.79%   |
| Syntek Integrated Camera                 | 3         | 1.35%   |
| Suyin RGBIR Camera                       | 3         | 1.35%   |
| Sunplus Integrated_Webcam_HD             | 3         | 1.35%   |
| Microdia Integrated_Webcam_HD            | 3         | 1.35%   |
| Lite-On Realtek PC Camera                | 3         | 1.35%   |
| Chicony Integrated Camera [ThinkPad]     | 3         | 1.35%   |
| Bison ThinkPad Integrated Camera         | 3         | 1.35%   |
| Bison SunplusIT Integrated Camera        | 3         | 1.35%   |
| Alcor Micro USB 2.0 Camera               | 3         | 1.35%   |
| Syntek Lenovo EasyCamera                 | 2         | 0.9%    |
| Syntek EasyCamera                        | 2         | 0.9%    |
| Realtek Integrated_Webcam_HD             | 2         | 0.9%    |
| Quanta HP TrueVision HD Camera           | 2         | 0.9%    |
| Logitech Webcam C270                     | 2         | 0.9%    |
| Logitech HD Pro Webcam C920              | 2         | 0.9%    |
| Logitech C920 PRO HD Webcam              | 2         | 0.9%    |
| Logitech C920 HD Pro Webcam              | 2         | 0.9%    |
| Lenovo Integrated Webcam [R5U877]        | 2         | 0.9%    |
| Lenovo Integrated Camera                 | 2         | 0.9%    |
| IMC Networks XHC Camera                  | 2         | 0.9%    |
| IMC Networks Realtek PC Camera           | 2         | 0.9%    |
| Chicony Integrated IR Camera             | 2         | 0.9%    |
| Chicony HP HD Webcam [Fixed]             | 2         | 0.9%    |
| Chicony HD WebCam (Acer)                 | 2         | 0.9%    |
| Chicony Chicony USB2.0 Camera            | 2         | 0.9%    |
| Bison SunplusIT INC. Integrated Camera   | 2         | 0.9%    |
| Bison Lenovo EasyCamera                  | 2         | 0.9%    |
| ARC International Camera                 | 2         | 0.9%    |
| Apple FaceTime HD Camera                 | 2         | 0.9%    |
| Apple FaceTime Camera                    | 2         | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 29        | 35.8%   |
| Synaptics                  | 14        | 17.28%  |
| Upek                       | 11        | 13.58%  |
| AuthenTec                  | 6         | 7.41%   |
| Shenzhen Goodix Technology | 5         | 6.17%   |
| LighTuning Technology      | 5         | 6.17%   |
| Elan Microelectronics      | 3         | 3.7%    |
| Broadcom                   | 3         | 3.7%    |
| STMicroelectronics         | 2         | 2.47%   |
| Next Biometrics            | 1         | 1.23%   |
| FocalTech Systems          | 1         | 1.23%   |
| DigitalPersona             | 1         | 1.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 11        | 13.58%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 10        | 12.35%  |
| Validity Sensors Synaptics WBDI                                              | 9         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 6         | 7.41%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 4         | 4.94%   |
| Shenzhen Goodix Fingerprint Reader                                           | 4         | 4.94%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 3         | 3.7%    |
| Elan Fingerprint Sensor                                                      | 3         | 3.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 3.7%    |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 2.47%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 2.47%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 2.47%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 2.47%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 2         | 2.47%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 2         | 2.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 1.23%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.23%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 1.23%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 1.23%   |
| Synaptics WBDI                                                               | 1         | 1.23%   |
| Synaptics TouchPad                                                           | 1         | 1.23%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 1.23%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 1.23%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 1.23%   |
| FocalTech Systems Fingerprint Reader                                         | 1         | 1.23%   |
| DigitalPersona Fingerprint Reader                                            | 1         | 1.23%   |
| AuthenTec AES2660                                                            | 1         | 1.23%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 1.23%   |
| AuthenTec AES1660                                                            | 1         | 1.23%   |
| AuthenTec AES1600                                                            | 1         | 1.23%   |
| Unknown                                                                      | 1         | 1.23%   |

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
| 1     | 909       | 39.21%  |
| 0     | 820       | 35.38%  |
| 2     | 353       | 15.23%  |
| 3     | 154       | 6.64%   |
| 4     | 59        | 2.55%   |
| 5     | 19        | 0.82%   |
| 6     | 3         | 0.13%   |
| 7     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1290      | 62.99%  |
| Bluetooth                | 216       | 10.55%  |
| Net/wireless             | 186       | 9.08%   |
| Card reader              | 124       | 6.05%   |
| Fingerprint reader       | 72        | 3.52%   |
| Firewire controller      | 45        | 2.2%    |
| Network                  | 31        | 1.51%   |
| Net/ethernet             | 29        | 1.42%   |
| Sound                    | 26        | 1.27%   |
| Graphics card            | 13        | 0.63%   |
| Modem                    | 5         | 0.24%   |
| Storage                  | 4         | 0.2%    |
| Storage/ide              | 2         | 0.1%    |
| Storage/ata              | 2         | 0.1%    |
| Storage/raid             | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |

