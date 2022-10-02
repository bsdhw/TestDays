BSD in Netherlands - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for BSD in Netherlands.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Netherlands/Desktop/README.md) and [notebooks](/Location/Netherlands/Notebook/README.md).

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

Total: 330

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [050c365fcd](https://bsd-hardware.info/?probe=050c365fcd) | Sep 17, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [7bf7249432](https://bsd-hardware.info/?probe=7bf7249432) | Sep 16, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [ad70ccea4d](https://bsd-hardware.info/?probe=ad70ccea4d) | Sep 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [13ec5a6f20](https://bsd-hardware.info/?probe=13ec5a6f20) | Sep 14, 2022 |
| Dell EMC      | VEP1425-V210-CPU A00        | Desktop     | [871a29677b](https://bsd-hardware.info/?probe=871a29677b) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7S2LT00    | Notebook    | [5104875f94](https://bsd-hardware.info/?probe=5104875f94) | Sep 06, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [88d8df1e3a](https://bsd-hardware.info/?probe=88d8df1e3a) | Sep 03, 2022 |
| Dell          | 0DVNTK A00                  | Mini pc     | [216197e933](https://bsd-hardware.info/?probe=216197e933) | Sep 03, 2022 |
| MSI           | H410M-A PRO                 | Desktop     | [d71ca3999c](https://bsd-hardware.info/?probe=d71ca3999c) | Sep 02, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [05bb23ae87](https://bsd-hardware.info/?probe=05bb23ae87) | Aug 26, 2022 |
| Dell          | PowerEdge R620              | Desktop     | [66db9eb745](https://bsd-hardware.info/?probe=66db9eb745) | Aug 25, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [5280e7a6d2](https://bsd-hardware.info/?probe=5280e7a6d2) | Aug 18, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [9ac038fe9d](https://bsd-hardware.info/?probe=9ac038fe9d) | Aug 17, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [28929cae10](https://bsd-hardware.info/?probe=28929cae10) | Aug 17, 2022 |
| PC Engines    | APU2                        | Desktop     | [beb01b4e9c](https://bsd-hardware.info/?probe=beb01b4e9c) | Aug 06, 2022 |
| HP            | 8266                        | Desktop     | [a204146221](https://bsd-hardware.info/?probe=a204146221) | Aug 04, 2022 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [f346b8d7f0](https://bsd-hardware.info/?probe=f346b8d7f0) | Aug 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [ad56307789](https://bsd-hardware.info/?probe=ad56307789) | Aug 01, 2022 |
| Gigabyte      | H310M S2H                   | Desktop     | [03d0919731](https://bsd-hardware.info/?probe=03d0919731) | Jul 29, 2022 |
| Deciso        | Netboard A10                | Desktop     | [3f548f31e3](https://bsd-hardware.info/?probe=3f548f31e3) | Jul 25, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [6daa6d0060](https://bsd-hardware.info/?probe=6daa6d0060) | Jul 24, 2022 |
| Lenovo        | ThinkPad X61s 76693KG       | Notebook    | [445446cc28](https://bsd-hardware.info/?probe=445446cc28) | Jul 18, 2022 |
| Protectli     | FW4B                        | Desktop     | [b1ac4ad0dd](https://bsd-hardware.info/?probe=b1ac4ad0dd) | Jul 18, 2022 |
| ASUSTek       | X751LB                      | Notebook    | [5c2ef28301](https://bsd-hardware.info/?probe=5c2ef28301) | Jul 12, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [d680e0d05d](https://bsd-hardware.info/?probe=d680e0d05d) | Jul 10, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [d48d3e4777](https://bsd-hardware.info/?probe=d48d3e4777) | Jul 05, 2022 |
| Star Labs     | LabTop                      | Notebook    | [390c4c4d55](https://bsd-hardware.info/?probe=390c4c4d55) | Jul 03, 2022 |
| Protectli     | FW4B                        | Desktop     | [c4e6db8739](https://bsd-hardware.info/?probe=c4e6db8739) | Jul 03, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [a76b64487b](https://bsd-hardware.info/?probe=a76b64487b) | Jul 01, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [ff3865e01f](https://bsd-hardware.info/?probe=ff3865e01f) | Jun 05, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [4be827d8fe](https://bsd-hardware.info/?probe=4be827d8fe) | Jun 01, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [5893942a80](https://bsd-hardware.info/?probe=5893942a80) | May 30, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [ade09344b8](https://bsd-hardware.info/?probe=ade09344b8) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [cc37ea1b7d](https://bsd-hardware.info/?probe=cc37ea1b7d) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [abacee12a9](https://bsd-hardware.info/?probe=abacee12a9) | May 26, 2022 |
| Unknown       | Raspberry Pi 3 Model B P... | Desktop     | [21fa41e4c1](https://bsd-hardware.info/?probe=21fa41e4c1) | May 26, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [3dc5a6f7d2](https://bsd-hardware.info/?probe=3dc5a6f7d2) | May 24, 2022 |
| Dell          | Latitude E7240              | Notebook    | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [b9350aeb55](https://bsd-hardware.info/?probe=b9350aeb55) | May 21, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [5cc0eb3e94](https://bsd-hardware.info/?probe=5cc0eb3e94) | May 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [66432302a4](https://bsd-hardware.info/?probe=66432302a4) | May 07, 2022 |
| PC Engines    | APU2                        | Desktop     | [26be7dfcb8](https://bsd-hardware.info/?probe=26be7dfcb8) | Apr 28, 2022 |
| PC Engines    | APU2                        | Desktop     | [4405a65be4](https://bsd-hardware.info/?probe=4405a65be4) | Apr 28, 2022 |
| PC Engines    | APU2                        | Desktop     | [5d79f85176](https://bsd-hardware.info/?probe=5d79f85176) | Apr 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [3fe99889aa](https://bsd-hardware.info/?probe=3fe99889aa) | Apr 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [095a279c7b](https://bsd-hardware.info/?probe=095a279c7b) | Apr 25, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [4e7d57df3b](https://bsd-hardware.info/?probe=4e7d57df3b) | Apr 18, 2022 |
| HP            | 1998                        | Desktop     | [4f15447536](https://bsd-hardware.info/?probe=4f15447536) | Apr 18, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [c78d18300d](https://bsd-hardware.info/?probe=c78d18300d) | Apr 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [f58e088df2](https://bsd-hardware.info/?probe=f58e088df2) | Apr 16, 2022 |
| Sony          | SVZ1311C5E                  | Notebook    | [c1c429a7e6](https://bsd-hardware.info/?probe=c1c429a7e6) | Apr 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [87306109c8](https://bsd-hardware.info/?probe=87306109c8) | Apr 11, 2022 |
| Protectli     | FW6D                        | Desktop     | [e79304e1dc](https://bsd-hardware.info/?probe=e79304e1dc) | Apr 07, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [99343fc0da](https://bsd-hardware.info/?probe=99343fc0da) | Apr 06, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [7db1501c5c](https://bsd-hardware.info/?probe=7db1501c5c) | Apr 06, 2022 |
| ASRock        | H61DE/S3                    | Desktop     | [00183a69ec](https://bsd-hardware.info/?probe=00183a69ec) | Apr 05, 2022 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [634f184200](https://bsd-hardware.info/?probe=634f184200) | Apr 05, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [1ef10e5e36](https://bsd-hardware.info/?probe=1ef10e5e36) | Apr 03, 2022 |
| Supermicro    | X12STL-IF                   | Server      | [87912d52e4](https://bsd-hardware.info/?probe=87912d52e4) | Mar 28, 2022 |
| PC Engines    | apu4                        | Desktop     | [618b2c7955](https://bsd-hardware.info/?probe=618b2c7955) | Mar 27, 2022 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [a1700b0347](https://bsd-hardware.info/?probe=a1700b0347) | Mar 21, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [671c66ca19](https://bsd-hardware.info/?probe=671c66ca19) | Mar 21, 2022 |
| Protectli     | FW4B                        | Desktop     | [5323027ba0](https://bsd-hardware.info/?probe=5323027ba0) | Mar 13, 2022 |
| Dell          | 03X6X0 A01                  | Server      | [00ccb7abb3](https://bsd-hardware.info/?probe=00ccb7abb3) | Mar 08, 2022 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [ec336ddab4](https://bsd-hardware.info/?probe=ec336ddab4) | Mar 08, 2022 |
| Supermicro    | X12STL-IF                   | Server      | [5054f03888](https://bsd-hardware.info/?probe=5054f03888) | Mar 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [19ed08c39c](https://bsd-hardware.info/?probe=19ed08c39c) | Mar 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [c91c5fe588](https://bsd-hardware.info/?probe=c91c5fe588) | Mar 03, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [c6caefebe6](https://bsd-hardware.info/?probe=c6caefebe6) | Feb 28, 2022 |
| Supermicro    | M11SDV-8C-LN4F              | Desktop     | [e4f7f31828](https://bsd-hardware.info/?probe=e4f7f31828) | Feb 28, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [74f28d34fd](https://bsd-hardware.info/?probe=74f28d34fd) | Feb 27, 2022 |
| Sophos        | XG                          | Firewall    | [44c92baffd](https://bsd-hardware.info/?probe=44c92baffd) | Feb 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [a5a8c71167](https://bsd-hardware.info/?probe=a5a8c71167) | Feb 18, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [64ccf1e6a0](https://bsd-hardware.info/?probe=64ccf1e6a0) | Feb 18, 2022 |
| Dell          | 05KX61 A02                  | Server      | [5e72ec3104](https://bsd-hardware.info/?probe=5e72ec3104) | Feb 17, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [f3444924fd](https://bsd-hardware.info/?probe=f3444924fd) | Feb 17, 2022 |
| Lenovo        | ThinkPad X250 20CLS59400    | Notebook    | [92333ad60b](https://bsd-hardware.info/?probe=92333ad60b) | Feb 17, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [f259f73c17](https://bsd-hardware.info/?probe=f259f73c17) | Feb 14, 2022 |
| CompuLab      | uSVR                        | Mini pc     | [9afa228b2a](https://bsd-hardware.info/?probe=9afa228b2a) | Feb 12, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [91870de9fe](https://bsd-hardware.info/?probe=91870de9fe) | Feb 06, 2022 |
| MSI           | H81I                        | Desktop     | [fe3a834f0b](https://bsd-hardware.info/?probe=fe3a834f0b) | Feb 05, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [f785bcb17a](https://bsd-hardware.info/?probe=f785bcb17a) | Feb 04, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [96436a1882](https://bsd-hardware.info/?probe=96436a1882) | Feb 03, 2022 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [f13e7340b1](https://bsd-hardware.info/?probe=f13e7340b1) | Jan 30, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [cb50949dca](https://bsd-hardware.info/?probe=cb50949dca) | Jan 28, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [c7ef0e518f](https://bsd-hardware.info/?probe=c7ef0e518f) | Jan 27, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [c2d7238521](https://bsd-hardware.info/?probe=c2d7238521) | Jan 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [04afa3aa4f](https://bsd-hardware.info/?probe=04afa3aa4f) | Jan 23, 2022 |
| Dell          | 03X6X0 A01                  | Server      | [1c3abdddf5](https://bsd-hardware.info/?probe=1c3abdddf5) | Jan 19, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [e795c7ec91](https://bsd-hardware.info/?probe=e795c7ec91) | Jan 17, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [625c8f0f2c](https://bsd-hardware.info/?probe=625c8f0f2c) | Jan 14, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [d09cf2e0a7](https://bsd-hardware.info/?probe=d09cf2e0a7) | Jan 14, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [462b721778](https://bsd-hardware.info/?probe=462b721778) | Jan 11, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [877bb1b29f](https://bsd-hardware.info/?probe=877bb1b29f) | Jan 10, 2022 |
| Unknown       | Unknown                     | Notebook    | [974e1f4e5e](https://bsd-hardware.info/?probe=974e1f4e5e) | Jan 07, 2022 |
| MSI           | H61I-E35 V2/W8              | Desktop     | [8ae05f9d72](https://bsd-hardware.info/?probe=8ae05f9d72) | Jan 05, 2022 |
| XtReAmEr      | Unknown                     | Desktop     | [bd1315aa70](https://bsd-hardware.info/?probe=bd1315aa70) | Jan 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [0efa2c0531](https://bsd-hardware.info/?probe=0efa2c0531) | Dec 31, 2021 |
| Dell          | 0F9NPY A02                  | Server      | [1e0e3c3739](https://bsd-hardware.info/?probe=1e0e3c3739) | Dec 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [79370c33df](https://bsd-hardware.info/?probe=79370c33df) | Dec 28, 2021 |
| Dell          | 03X6X0 A03                  | Server      | [2a59c1bfa2](https://bsd-hardware.info/?probe=2a59c1bfa2) | Dec 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [c5e31aaf52](https://bsd-hardware.info/?probe=c5e31aaf52) | Dec 28, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [30aab74fbc](https://bsd-hardware.info/?probe=30aab74fbc) | Dec 24, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [6b03a2c4c2](https://bsd-hardware.info/?probe=6b03a2c4c2) | Dec 22, 2021 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [6529da52dc](https://bsd-hardware.info/?probe=6529da52dc) | Dec 21, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [69bf80f0c6](https://bsd-hardware.info/?probe=69bf80f0c6) | Dec 20, 2021 |
| Unknown       | Raspberry Pi 3 Model B P... | Desktop     | [ef0dcfaccf](https://bsd-hardware.info/?probe=ef0dcfaccf) | Dec 20, 2021 |
| TOXIC by B... | 15CL872 1050TI              | Notebook    | [0a1683170a](https://bsd-hardware.info/?probe=0a1683170a) | Dec 20, 2021 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [b099f26b73](https://bsd-hardware.info/?probe=b099f26b73) | Dec 20, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [17cad87a0d](https://bsd-hardware.info/?probe=17cad87a0d) | Dec 19, 2021 |
| PC Engines    | apu4                        | Desktop     | [f72343bec1](https://bsd-hardware.info/?probe=f72343bec1) | Dec 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [cd27dd3e2b](https://bsd-hardware.info/?probe=cd27dd3e2b) | Dec 17, 2021 |
| Lenovo        | ThinkPad A285 20MW000JMH    | Notebook    | [ff53f0763c](https://bsd-hardware.info/?probe=ff53f0763c) | Dec 12, 2021 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fd05f5bf41](https://bsd-hardware.info/?probe=fd05f5bf41) | Dec 11, 2021 |
| HP            | 8105                        | Desktop     | [e38c91e91e](https://bsd-hardware.info/?probe=e38c91e91e) | Dec 11, 2021 |
| HP            | 8105                        | Desktop     | [0b923d55bc](https://bsd-hardware.info/?probe=0b923d55bc) | Dec 11, 2021 |
| Sophos        | XG                          | Firewall    | [59485a80e1](https://bsd-hardware.info/?probe=59485a80e1) | Dec 11, 2021 |
| Protectli     | FW6D                        | Desktop     | [33731d5933](https://bsd-hardware.info/?probe=33731d5933) | Dec 11, 2021 |
| Apple         | MacBookAir1,1               | Notebook    | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [5dbff17614](https://bsd-hardware.info/?probe=5dbff17614) | Dec 06, 2021 |
| Unknown       | Raspberry Pi 3 Model B P... | Desktop     | [646ca92a69](https://bsd-hardware.info/?probe=646ca92a69) | Dec 06, 2021 |
| Alienware     | 01NYPT A00                  | Desktop     | [75aa0c00fb](https://bsd-hardware.info/?probe=75aa0c00fb) | Dec 06, 2021 |
| TOXIC by B... | 15CL872 1050TI              | Notebook    | [4fbb430947](https://bsd-hardware.info/?probe=4fbb430947) | Dec 05, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [b77016bee5](https://bsd-hardware.info/?probe=b77016bee5) | Nov 25, 2021 |
| Dell          | 01V648 A04                  | Server      | [0f0265d958](https://bsd-hardware.info/?probe=0f0265d958) | Nov 25, 2021 |
| ASRock        | IMB-195                     | Desktop     | [58e7426808](https://bsd-hardware.info/?probe=58e7426808) | Nov 24, 2021 |
| Lenovo        | ThinkPad T430 2347G7G       | Notebook    | [66c64c1af9](https://bsd-hardware.info/?probe=66c64c1af9) | Nov 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [2276cb5406](https://bsd-hardware.info/?probe=2276cb5406) | Nov 20, 2021 |
| HP            | 339A                        | Desktop     | [a123d76249](https://bsd-hardware.info/?probe=a123d76249) | Nov 19, 2021 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [1486dc195e](https://bsd-hardware.info/?probe=1486dc195e) | Nov 17, 2021 |
| HP            | 1497                        | Desktop     | [24a8d1bb7a](https://bsd-hardware.info/?probe=24a8d1bb7a) | Nov 17, 2021 |
| PC Engines    | APU                         | Desktop     | [ca05f41685](https://bsd-hardware.info/?probe=ca05f41685) | Nov 16, 2021 |
| Dell          | 0R230R A00                  | Desktop     | [c2c6cf4b4d](https://bsd-hardware.info/?probe=c2c6cf4b4d) | Nov 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [c473c704a9](https://bsd-hardware.info/?probe=c473c704a9) | Nov 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [ec7dfabb51](https://bsd-hardware.info/?probe=ec7dfabb51) | Nov 12, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [04cc56305c](https://bsd-hardware.info/?probe=04cc56305c) | Nov 11, 2021 |
| Protectli     | FW4B                        | Desktop     | [cb7b87cd57](https://bsd-hardware.info/?probe=cb7b87cd57) | Nov 09, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [6f779d5170](https://bsd-hardware.info/?probe=6f779d5170) | Nov 03, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [72f0937505](https://bsd-hardware.info/?probe=72f0937505) | Nov 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [f80c884b6f](https://bsd-hardware.info/?probe=f80c884b6f) | Oct 31, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [e4958e59b0](https://bsd-hardware.info/?probe=e4958e59b0) | Oct 29, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [70da799fd0](https://bsd-hardware.info/?probe=70da799fd0) | Oct 25, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [bc4b7f33d5](https://bsd-hardware.info/?probe=bc4b7f33d5) | Oct 25, 2021 |
| Supermicro    | M11SDV-8C-LN4F              | Desktop     | [54c792ac8a](https://bsd-hardware.info/?probe=54c792ac8a) | Oct 20, 2021 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [9ed491d56a](https://bsd-hardware.info/?probe=9ed491d56a) | Oct 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [67e62d9dd3](https://bsd-hardware.info/?probe=67e62d9dd3) | Oct 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [b3b0308132](https://bsd-hardware.info/?probe=b3b0308132) | Oct 02, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [712bbd0635](https://bsd-hardware.info/?probe=712bbd0635) | Sep 29, 2021 |
| Protectli     | FW6D                        | Desktop     | [ee70d4b2fe](https://bsd-hardware.info/?probe=ee70d4b2fe) | Sep 25, 2021 |
| MSI           | H61I-E35 V2/W8              | Desktop     | [359cb66936](https://bsd-hardware.info/?probe=359cb66936) | Sep 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1afa203e69](https://bsd-hardware.info/?probe=1afa203e69) | Sep 22, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | Desktop     | [ea8fefdf4e](https://bsd-hardware.info/?probe=ea8fefdf4e) | Sep 20, 2021 |
| Shuttle       | XH310V2                     | Desktop     | [f37b485384](https://bsd-hardware.info/?probe=f37b485384) | Sep 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [ba40cc9f75](https://bsd-hardware.info/?probe=ba40cc9f75) | Sep 17, 2021 |
| HP            | 8103 A01                    | Mini pc     | [860e4a3d12](https://bsd-hardware.info/?probe=860e4a3d12) | Sep 16, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [70d35afae8](https://bsd-hardware.info/?probe=70d35afae8) | Sep 15, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | Desktop     | [85ed325446](https://bsd-hardware.info/?probe=85ed325446) | Sep 11, 2021 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | Desktop     | [0510213747](https://bsd-hardware.info/?probe=0510213747) | Aug 30, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [b3a20bafca](https://bsd-hardware.info/?probe=b3a20bafca) | Aug 29, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [03e08762a6](https://bsd-hardware.info/?probe=03e08762a6) | Aug 27, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [36e36edb7a](https://bsd-hardware.info/?probe=36e36edb7a) | Aug 24, 2021 |
| Shuttle       | DH370                       | Desktop     | [dea088a5bd](https://bsd-hardware.info/?probe=dea088a5bd) | Aug 20, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [ad6b718b92](https://bsd-hardware.info/?probe=ad6b718b92) | Aug 20, 2021 |
| Protectli     | FW4B                        | Desktop     | [ab6695bb0b](https://bsd-hardware.info/?probe=ab6695bb0b) | Aug 18, 2021 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [e057495ca3](https://bsd-hardware.info/?probe=e057495ca3) | Aug 14, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [fcf09dfbe5](https://bsd-hardware.info/?probe=fcf09dfbe5) | Aug 13, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [e9335d8295](https://bsd-hardware.info/?probe=e9335d8295) | Aug 13, 2021 |
| HP            | 625                         | Notebook    | [606d75e6a1](https://bsd-hardware.info/?probe=606d75e6a1) | Aug 11, 2021 |
| HP            | 213D A01                    | Desktop     | [6e52020062](https://bsd-hardware.info/?probe=6e52020062) | Aug 10, 2021 |
| Shuttle       | DH370                       | Desktop     | [6d81fef4fb](https://bsd-hardware.info/?probe=6d81fef4fb) | Aug 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [164b888dbe](https://bsd-hardware.info/?probe=164b888dbe) | Aug 08, 2021 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [0ad676c6a9](https://bsd-hardware.info/?probe=0ad676c6a9) | Aug 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [d4122c5eb0](https://bsd-hardware.info/?probe=d4122c5eb0) | Aug 03, 2021 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [4253ffb8fb](https://bsd-hardware.info/?probe=4253ffb8fb) | Aug 02, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [a6de85de91](https://bsd-hardware.info/?probe=a6de85de91) | Jul 29, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1e337fe131](https://bsd-hardware.info/?probe=1e337fe131) | Jul 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [dd66bc21f6](https://bsd-hardware.info/?probe=dd66bc21f6) | Jul 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [b7edcfabb6](https://bsd-hardware.info/?probe=b7edcfabb6) | Jul 25, 2021 |
| Lenovo        | ThinkPad X230 2325IG2       | Notebook    | [158ecc5e0b](https://bsd-hardware.info/?probe=158ecc5e0b) | Jul 14, 2021 |
| PC Engines    | apu4                        | Desktop     | [027bbc5028](https://bsd-hardware.info/?probe=027bbc5028) | Jul 14, 2021 |
| HP            | 18E9                        | Desktop     | [7bac3be335](https://bsd-hardware.info/?probe=7bac3be335) | Jun 29, 2021 |
| Dell EMC      | VEP1425-V210-CPU A00        | Desktop     | [ad34d48259](https://bsd-hardware.info/?probe=ad34d48259) | Jun 27, 2021 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [5f46ba6832](https://bsd-hardware.info/?probe=5f46ba6832) | Jun 26, 2021 |
| Dell          | 0WR7PY A02                  | Desktop     | [ad5db0563f](https://bsd-hardware.info/?probe=ad5db0563f) | Jun 26, 2021 |
| Lenovo        | Yoga 500-14IBD 80N4         | Notebook    | [9fda78d739](https://bsd-hardware.info/?probe=9fda78d739) | Jun 23, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [46dca136f6](https://bsd-hardware.info/?probe=46dca136f6) | Jun 21, 2021 |
| WYSE          | Z CLASS                     | Notebook    | [571fdbf390](https://bsd-hardware.info/?probe=571fdbf390) | Jun 19, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ee8a47b051](https://bsd-hardware.info/?probe=ee8a47b051) | Jun 17, 2021 |
| HP            | 3397                        | Desktop     | [3dd97c60ca](https://bsd-hardware.info/?probe=3dd97c60ca) | Jun 16, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [9ae8146589](https://bsd-hardware.info/?probe=9ae8146589) | Jun 15, 2021 |
| Dell          | Latitude E4300              | Notebook    | [7855973957](https://bsd-hardware.info/?probe=7855973957) | Jun 12, 2021 |
| SLIMBOOK      | Unknown                     | Notebook    | [80a9ba918e](https://bsd-hardware.info/?probe=80a9ba918e) | Jun 11, 2021 |
| MSI           | B85M-P33 V2                 | Desktop     | [0633d1c78e](https://bsd-hardware.info/?probe=0633d1c78e) | Jun 10, 2021 |
| Dell          | 03X6X0 A02                  | Server      | [deb193d10f](https://bsd-hardware.info/?probe=deb193d10f) | Jun 10, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [db12a78352](https://bsd-hardware.info/?probe=db12a78352) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [9a7adb8860](https://bsd-hardware.info/?probe=9a7adb8860) | Jun 06, 2021 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [4607d1410c](https://bsd-hardware.info/?probe=4607d1410c) | May 31, 2021 |
| Inventec      | R CLASS A02                 | Desktop     | [b621aeaac3](https://bsd-hardware.info/?probe=b621aeaac3) | May 30, 2021 |
| Gigabyte      | B85-HD3                     | Desktop     | [331da3091c](https://bsd-hardware.info/?probe=331da3091c) | May 28, 2021 |
| Dell          | 0200DY A02                  | Desktop     | [fcbfbc2dfa](https://bsd-hardware.info/?probe=fcbfbc2dfa) | May 25, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [8448df79cd](https://bsd-hardware.info/?probe=8448df79cd) | May 21, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [594c0438a0](https://bsd-hardware.info/?probe=594c0438a0) | May 21, 2021 |
| Notebook      | NL5xRU                      | Notebook    | [792fb07dd9](https://bsd-hardware.info/?probe=792fb07dd9) | May 10, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [add2c1bcba](https://bsd-hardware.info/?probe=add2c1bcba) | May 09, 2021 |
| Dell          | 03X6X0 A03                  | Server      | [d6312ecf58](https://bsd-hardware.info/?probe=d6312ecf58) | May 09, 2021 |
| Shuttle       | FH87                        | Desktop     | [bf5457ff02](https://bsd-hardware.info/?probe=bf5457ff02) | May 09, 2021 |
| Dell          | 0FJ030                      | Desktop     | [91418a4965](https://bsd-hardware.info/?probe=91418a4965) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [7bee24ee8a](https://bsd-hardware.info/?probe=7bee24ee8a) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [d5277ad9e1](https://bsd-hardware.info/?probe=d5277ad9e1) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [63b1980830](https://bsd-hardware.info/?probe=63b1980830) | Apr 30, 2021 |
| HP            | 1998                        | Desktop     | [f6b53096d4](https://bsd-hardware.info/?probe=f6b53096d4) | Apr 28, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [a90eea4001](https://bsd-hardware.info/?probe=a90eea4001) | Apr 27, 2021 |
| HP            | 1497                        | Desktop     | [26724735db](https://bsd-hardware.info/?probe=26724735db) | Apr 24, 2021 |
| HP            | 1998                        | Desktop     | [051c63e153](https://bsd-hardware.info/?probe=051c63e153) | Apr 24, 2021 |
| ASRock        | J4105-ITX                   | Desktop     | [66eee76b50](https://bsd-hardware.info/?probe=66eee76b50) | Apr 21, 2021 |
| Dell          | 0F9NPY A02                  | Server      | [4ebcbdc297](https://bsd-hardware.info/?probe=4ebcbdc297) | Apr 20, 2021 |
| HP            | 1998                        | Desktop     | [7207f742d6](https://bsd-hardware.info/?probe=7207f742d6) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [634521b082](https://bsd-hardware.info/?probe=634521b082) | Apr 07, 2021 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [31caab92cf](https://bsd-hardware.info/?probe=31caab92cf) | Apr 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [15e5f7932e](https://bsd-hardware.info/?probe=15e5f7932e) | Apr 06, 2021 |
| PC Engines    | apu4                        | Desktop     | [06a59860a8](https://bsd-hardware.info/?probe=06a59860a8) | Apr 04, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [b644ed3914](https://bsd-hardware.info/?probe=b644ed3914) | Mar 31, 2021 |
| Dell          | 0200DY A02                  | Desktop     | [060ebba6d2](https://bsd-hardware.info/?probe=060ebba6d2) | Mar 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [4376accb5e](https://bsd-hardware.info/?probe=4376accb5e) | Mar 29, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [88f2766975](https://bsd-hardware.info/?probe=88f2766975) | Mar 27, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [a5b9f5e79d](https://bsd-hardware.info/?probe=a5b9f5e79d) | Mar 27, 2021 |
| Lenovo        | ThinkPad X230 23255Y4       | Notebook    | [ab871769f0](https://bsd-hardware.info/?probe=ab871769f0) | Mar 27, 2021 |
| Dell          | 0DRR0P A00                  | Server      | [ebc09e92eb](https://bsd-hardware.info/?probe=ebc09e92eb) | Mar 26, 2021 |
| Shuttle       | FS310                       | Desktop     | [6514807d96](https://bsd-hardware.info/?probe=6514807d96) | Mar 25, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [d856b5bf95](https://bsd-hardware.info/?probe=d856b5bf95) | Mar 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [4c06c1a897](https://bsd-hardware.info/?probe=4c06c1a897) | Mar 23, 2021 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [b8f568202d](https://bsd-hardware.info/?probe=b8f568202d) | Mar 22, 2021 |
| Dell          | Latitude E7270              | Notebook    | [5ba79f9aa5](https://bsd-hardware.info/?probe=5ba79f9aa5) | Mar 19, 2021 |
| HP            | ProLiant DL360 Gen9         | Desktop     | [b283b34881](https://bsd-hardware.info/?probe=b283b34881) | Mar 17, 2021 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [d5a1acb61b](https://bsd-hardware.info/?probe=d5a1acb61b) | Mar 17, 2021 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [21d6db75f5](https://bsd-hardware.info/?probe=21d6db75f5) | Mar 17, 2021 |
| HP            | ProLiant DL120 Gen9         | Server      | [533b1e078e](https://bsd-hardware.info/?probe=533b1e078e) | Mar 17, 2021 |
| Fujitsu       | D3279-H1 S26361-D3279-H1... | Server      | [7a9d95b303](https://bsd-hardware.info/?probe=7a9d95b303) | Mar 17, 2021 |
| Supermicro    | Super Server                | Server      | [ec1e532ea9](https://bsd-hardware.info/?probe=ec1e532ea9) | Mar 17, 2021 |
| Lenovo        | ThinkPad X280 20KESA000B    | Notebook    | [e2b586d597](https://bsd-hardware.info/?probe=e2b586d597) | Mar 17, 2021 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [fa0e0228a3](https://bsd-hardware.info/?probe=fa0e0228a3) | Mar 17, 2021 |
| iEi           | E452 V1.00                  | Desktop     | [b5665d0df2](https://bsd-hardware.info/?probe=b5665d0df2) | Mar 17, 2021 |
| HP            | ProLiant DL360 Gen9         | Desktop     | [bf440e72a1](https://bsd-hardware.info/?probe=bf440e72a1) | Mar 17, 2021 |
| HP            | EliteDesk 800 G5 SFF        | Desktop     | [aaf9bc1c12](https://bsd-hardware.info/?probe=aaf9bc1c12) | Mar 17, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [6e0891ce80](https://bsd-hardware.info/?probe=6e0891ce80) | Mar 17, 2021 |
| Dell          | 0F9NPY A02                  | Server      | [ff4d8d8eca](https://bsd-hardware.info/?probe=ff4d8d8eca) | Mar 16, 2021 |
| Dell          | 0F9NPY A02                  | Server      | [cb3c1ad90e](https://bsd-hardware.info/?probe=cb3c1ad90e) | Mar 16, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [ee59c99fe4](https://bsd-hardware.info/?probe=ee59c99fe4) | Mar 15, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [359c03f28d](https://bsd-hardware.info/?probe=359c03f28d) | Mar 12, 2021 |
| HP            | 18E9                        | Desktop     | [cc435f4cd1](https://bsd-hardware.info/?probe=cc435f4cd1) | Mar 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [2093895427](https://bsd-hardware.info/?probe=2093895427) | Mar 10, 2021 |
| Lenovo        | ThinkPad X200s 7470W1V      | Notebook    | [926fe13d8f](https://bsd-hardware.info/?probe=926fe13d8f) | Mar 09, 2021 |
| ASUSTek       | X556UA                      | Notebook    | [57018edd10](https://bsd-hardware.info/?probe=57018edd10) | Mar 07, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [f30a9505dd](https://bsd-hardware.info/?probe=f30a9505dd) | Mar 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [2abc226441](https://bsd-hardware.info/?probe=2abc226441) | Mar 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [60e0b1d346](https://bsd-hardware.info/?probe=60e0b1d346) | Mar 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [db37dfcbf3](https://bsd-hardware.info/?probe=db37dfcbf3) | Mar 02, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [64bf9eb4cf](https://bsd-hardware.info/?probe=64bf9eb4cf) | Mar 01, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [eacaff1fff](https://bsd-hardware.info/?probe=eacaff1fff) | Feb 28, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [47c08e3817](https://bsd-hardware.info/?probe=47c08e3817) | Feb 27, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [9901302790](https://bsd-hardware.info/?probe=9901302790) | Feb 27, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [441133db7f](https://bsd-hardware.info/?probe=441133db7f) | Feb 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [1008505c8a](https://bsd-hardware.info/?probe=1008505c8a) | Feb 23, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [7d9e05b2fd](https://bsd-hardware.info/?probe=7d9e05b2fd) | Feb 21, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [408ba48f1f](https://bsd-hardware.info/?probe=408ba48f1f) | Feb 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [6c0a1e1154](https://bsd-hardware.info/?probe=6c0a1e1154) | Feb 20, 2021 |
| Supermicro    | X8SIL                       | Desktop     | [6318953f01](https://bsd-hardware.info/?probe=6318953f01) | Feb 18, 2021 |
| Dell          | Latitude E4300              | Notebook    | [d5051ef185](https://bsd-hardware.info/?probe=d5051ef185) | Feb 16, 2021 |
| Supermicro    | X9SCL/X9SCM                 | Desktop     | [a57dba0cb2](https://bsd-hardware.info/?probe=a57dba0cb2) | Feb 16, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [8bfcff9039](https://bsd-hardware.info/?probe=8bfcff9039) | Feb 16, 2021 |
| Dell          | 0T7D40 A01                  | Desktop     | [301fc86371](https://bsd-hardware.info/?probe=301fc86371) | Feb 15, 2021 |
| Protectli     | FW2B Ver                    | Desktop     | [57ca4c3cac](https://bsd-hardware.info/?probe=57ca4c3cac) | Feb 15, 2021 |
| Dell          | Latitude E4300              | Notebook    | [981de7fd20](https://bsd-hardware.info/?probe=981de7fd20) | Feb 14, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [d7cca96f72](https://bsd-hardware.info/?probe=d7cca96f72) | Feb 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [994b94b7f5](https://bsd-hardware.info/?probe=994b94b7f5) | Feb 13, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [8f93b4146d](https://bsd-hardware.info/?probe=8f93b4146d) | Feb 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e74d76ecb3](https://bsd-hardware.info/?probe=e74d76ecb3) | Feb 12, 2021 |
| Dell          | Latitude 7280               | Notebook    | [defaee0e5c](https://bsd-hardware.info/?probe=defaee0e5c) | Feb 12, 2021 |
| Dell          | Latitude 7280               | Notebook    | [1e243253d1](https://bsd-hardware.info/?probe=1e243253d1) | Feb 12, 2021 |
| Dell          | Latitude 7280               | Notebook    | [1ba418a5e6](https://bsd-hardware.info/?probe=1ba418a5e6) | Feb 12, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [9ff4167171](https://bsd-hardware.info/?probe=9ff4167171) | Feb 12, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [687008da4f](https://bsd-hardware.info/?probe=687008da4f) | Feb 11, 2021 |
| Dell          | Latitude 7280               | Notebook    | [d62b7120c8](https://bsd-hardware.info/?probe=d62b7120c8) | Feb 11, 2021 |
| Dell          | 0DRR0P A00                  | Server      | [0b9292a0a4](https://bsd-hardware.info/?probe=0b9292a0a4) | Feb 11, 2021 |
| Dell          | Latitude 7370               | Notebook    | [8ec8d28024](https://bsd-hardware.info/?probe=8ec8d28024) | Feb 08, 2021 |
| PC Engines    | apu4                        | Desktop     | [67e0b30093](https://bsd-hardware.info/?probe=67e0b30093) | Feb 05, 2021 |
| PC Engines    | apu4                        | Desktop     | [d4b1d0ae99](https://bsd-hardware.info/?probe=d4b1d0ae99) | Feb 03, 2021 |
| PC Engines    | APU                         | Desktop     | [91da54ca8c](https://bsd-hardware.info/?probe=91da54ca8c) | Feb 02, 2021 |
| Dell          | Latitude E4300              | Notebook    | [84925c014a](https://bsd-hardware.info/?probe=84925c014a) | Feb 01, 2021 |
| Dell          | 0T7D40 A01                  | Desktop     | [1f5bf7092c](https://bsd-hardware.info/?probe=1f5bf7092c) | Feb 01, 2021 |
| Inventec      | VXC Class A02               | Desktop     | [22d0861af3](https://bsd-hardware.info/?probe=22d0861af3) | Jan 29, 2021 |
| Sophos        | SG                          | Firewall    | [d11e60890a](https://bsd-hardware.info/?probe=d11e60890a) | Jan 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [f4b460a5e4](https://bsd-hardware.info/?probe=f4b460a5e4) | Jan 28, 2021 |
| Inventec      | VXC Class A02               | Desktop     | [8c298fa5bf](https://bsd-hardware.info/?probe=8c298fa5bf) | Jan 28, 2021 |
| Inventec      | VXC Class A02               | Desktop     | [6127d635de](https://bsd-hardware.info/?probe=6127d635de) | Jan 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [f76df86f03](https://bsd-hardware.info/?probe=f76df86f03) | Jan 26, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [881d50fc9e](https://bsd-hardware.info/?probe=881d50fc9e) | Jan 26, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [97fd3d11e8](https://bsd-hardware.info/?probe=97fd3d11e8) | Jan 25, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [2577292fe1](https://bsd-hardware.info/?probe=2577292fe1) | Jan 25, 2021 |
| Inventec      | R CLASS A02                 | Desktop     | [545854fcfd](https://bsd-hardware.info/?probe=545854fcfd) | Jan 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5b00abed29](https://bsd-hardware.info/?probe=5b00abed29) | Jan 23, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [f8e3f072fc](https://bsd-hardware.info/?probe=f8e3f072fc) | Jan 23, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3c0683ff11](https://bsd-hardware.info/?probe=3c0683ff11) | Jan 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5d556cc47f](https://bsd-hardware.info/?probe=5d556cc47f) | Jan 22, 2021 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [6a1974bebd](https://bsd-hardware.info/?probe=6a1974bebd) | Jan 22, 2021 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [4b2e64662e](https://bsd-hardware.info/?probe=4b2e64662e) | Jan 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [951a898a3f](https://bsd-hardware.info/?probe=951a898a3f) | Jan 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [a1b0841493](https://bsd-hardware.info/?probe=a1b0841493) | Jan 21, 2021 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [064e82b131](https://bsd-hardware.info/?probe=064e82b131) | Jan 21, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [1fd927e2cd](https://bsd-hardware.info/?probe=1fd927e2cd) | Jan 11, 2021 |
| ASRockRack    | EPC612D4U-8R                | Desktop     | [617694f591](https://bsd-hardware.info/?probe=617694f591) | Dec 19, 2020 |
| Supermicro    | X10SAE                      | Server      | [d29048ae5d](https://bsd-hardware.info/?probe=d29048ae5d) | Oct 29, 2020 |
| ASRock        | B360 Pro4                   | Desktop     | [05d3ab8d4b](https://bsd-hardware.info/?probe=05d3ab8d4b) | Oct 29, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [57ecc0c410](https://bsd-hardware.info/?probe=57ecc0c410) | Oct 29, 2020 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [3cebf4d7db](https://bsd-hardware.info/?probe=3cebf4d7db) | Oct 29, 2020 |
| ASRockRack    | EPC612D4U-8R                | Desktop     | [b9ecd0e2b3](https://bsd-hardware.info/?probe=b9ecd0e2b3) | Oct 29, 2020 |
| Dell          | Precision WorkStation T7... | Desktop     | [c01ce9ec81](https://bsd-hardware.info/?probe=c01ce9ec81) | Oct 24, 2020 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [dc33c84287](https://bsd-hardware.info/?probe=dc33c84287) | Oct 22, 2020 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [2808d1dd6a](https://bsd-hardware.info/?probe=2808d1dd6a) | Oct 20, 2020 |
| Apple         | Macmini7,1                  | Mini pc     | [5caa1e1c7b](https://bsd-hardware.info/?probe=5caa1e1c7b) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [7671a495d1](https://bsd-hardware.info/?probe=7671a495d1) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [c1a2bc7a51](https://bsd-hardware.info/?probe=c1a2bc7a51) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [c1c5ee566c](https://bsd-hardware.info/?probe=c1c5ee566c) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [af87ddbbaa](https://bsd-hardware.info/?probe=af87ddbbaa) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [bee732e516](https://bsd-hardware.info/?probe=bee732e516) | Oct 19, 2020 |
| Intel         | S1200RP G62253-405          | Server      | [2793b07b38](https://bsd-hardware.info/?probe=2793b07b38) | May 30, 2020 |
| Gigabyte      | MQLP7AP-00                  | Desktop     | [07036eab43](https://bsd-hardware.info/?probe=07036eab43) | May 28, 2020 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [85bebeaea0](https://bsd-hardware.info/?probe=85bebeaea0) | May 25, 2020 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [9fea968a19](https://bsd-hardware.info/?probe=9fea968a19) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| OPNsense 21.7.7        | 13        | 4.83%   |
| OPNsense 21.7.5        | 9         | 3.35%   |
| OPNsense 21.1.3        | 9         | 3.35%   |
| OPNsense 21.7.3        | 8         | 2.97%   |
| OPNsense 21.7.1        | 8         | 2.97%   |
| OPNsense 21.1.1        | 8         | 2.97%   |
| OPNsense 20.7.8        | 8         | 2.97%   |
| OpenBSD 6.8            | 8         | 2.97%   |
| OPNsense 21.7.2        | 7         | 2.6%    |
| helloSystem 0.7.0      | 7         | 2.6%    |
| helloSystem 0.5.0      | 7         | 2.6%    |
| FreeBSD 13.0           | 7         | 2.6%    |
| OPNsense 22.1.6        | 6         | 2.23%   |
| OPNsense 22.1.4        | 6         | 2.23%   |
| OPNsense 22.1.1        | 6         | 2.23%   |
| OPNsense 22.1          | 6         | 2.23%   |
| OPNsense 21.1.2        | 6         | 2.23%   |
| OPNsense 21.1          | 6         | 2.23%   |
| OPNsense 22.1.10       | 5         | 1.86%   |
| OPNsense 21.1.7        | 5         | 1.86%   |
| OPNsense 21.1.4        | 5         | 1.86%   |
| OpenBSD 7.1            | 5         | 1.86%   |
| OpenBSD 6.9            | 5         | 1.86%   |
| FreeBSD 13.0-STABLE    | 5         | 1.86%   |
| FreeBSD 13.0-p5        | 5         | 1.86%   |
| OPNsense 22.7.4        | 4         | 1.49%   |
| OPNsense 22.7.2        | 4         | 1.49%   |
| OPNsense 21.7.6        | 4         | 1.49%   |
| OPNsense 21.1.6        | 4         | 1.49%   |
| OPNsense 21.1.5        | 4         | 1.49%   |
| helloSystem 0.6.0      | 4         | 1.49%   |
| helloSystem 0.3.0      | 4         | 1.49%   |
| FreeBSD 13.1           | 4         | 1.49%   |
| OPNsense 22.7.3        | 3         | 1.12%   |
| OPNsense 22.7          | 3         | 1.12%   |
| OPNsense 22.1.2        | 3         | 1.12%   |
| OPNsense 21.7.8        | 3         | 1.12%   |
| OPNsense 21.7.4        | 3         | 1.12%   |
| OPNsense 21.1.9        | 3         | 1.12%   |
| HardenedBSD 12.2--HBSD | 3         | 1.12%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 113       | 54.85%  |
| FreeBSD     | 41        | 19.9%   |
| helloSystem | 23        | 11.17%  |
| OpenBSD     | 20        | 9.71%   |
| HardenedBSD | 4         | 1.94%   |
| GhostBSD    | 3         | 1.46%   |
| pfSense     | 1         | 0.49%   |
| NetBSD      | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 196       | 96.55%  |
| arm64 | 6         | 2.96%   |
| i386  | 1         | 0.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 142       | 68.93%  |
| helloDesktop | 30        | 14.56%  |
| KDE5         | 7         | 3.4%    |
| fvwm         | 7         | 3.4%    |
| GNOME        | 5         | 2.43%   |
| MATE         | 4         | 1.94%   |
| XFCE         | 3         | 1.46%   |
| TWM          | 2         | 0.97%   |
| LXQt         | 2         | 0.97%   |
| i3           | 2         | 0.97%   |
| GNUstep      | 1         | 0.49%   |
| AwesomeWM    | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 144       | 70.94%  |
| X11     | 57        | 28.08%  |
| Wayland | 2         | 0.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 155       | 75.98%  |
| SLiM    | 27        | 13.24%  |
| XDM     | 7         | 3.43%   |
| SDDM    | 6         | 2.94%   |
| LightDM | 5         | 2.45%   |
| GDM     | 4         | 1.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 138       | 66.67%  |
| en_US   | 40        | 19.32%  |
| C       | 27        | 13.04%  |
| nl_NL   | 2         | 0.97%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 165       | 80.49%  |
| BIOS | 40        | 19.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 102       | 49.28%  |
| Zfs    | 80        | 38.65%  |
| Ffs    | 20        | 9.66%   |
| Cd9660 | 5         | 2.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 178       | 87.25%  |
| MBR  | 26        | 12.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 29        | 14.29%  |
| Unknown             | 22        | 10.84%  |
| Lenovo              | 18        | 8.87%   |
| Hewlett-Packard     | 18        | 8.87%   |
| Intel               | 12        | 5.91%   |
| Supermicro          | 10        | 4.93%   |
| ASRock              | 10        | 4.93%   |
| Gigabyte Technology | 9         | 4.43%   |
| PC Engines          | 7         | 3.45%   |
| Apple               | 7         | 3.45%   |
| ASUSTek Computer    | 6         | 2.96%   |
| AMI                 | 6         | 2.96%   |
| Shuttle             | 4         | 1.97%   |
| MSI                 | 4         | 1.97%   |
| Fujitsu             | 4         | 1.97%   |
| Sophos              | 3         | 1.48%   |
| Protectli           | 3         | 1.48%   |
| Inventec            | 3         | 1.48%   |
| Deciso              | 3         | 1.48%   |
| Barracuda Networks  | 2         | 0.99%   |
| ZOTAC               | 1         | 0.49%   |
| XtReAmEr            | 1         | 0.49%   |
| WYSE                | 1         | 0.49%   |
| TUXEDO              | 1         | 0.49%   |
| TOXIC by BTO        | 1         | 0.49%   |
| Toshiba             | 1         | 0.49%   |
| Star Labs           | 1         | 0.49%   |
| Sony                | 1         | 0.49%   |
| SLIMBOOK            | 1         | 0.49%   |
| Sapphire            | 1         | 0.49%   |
| Pegatron            | 1         | 0.49%   |
| Notebook            | 1         | 0.49%   |
| MW                  | 1         | 0.49%   |
| iEi                 | 1         | 0.49%   |
| HPE                 | 1         | 0.49%   |
| HARDKERNEL          | 1         | 0.49%   |
| Dell EMC            | 1         | 0.49%   |
| CompuLab            | 1         | 0.49%   |
| Cisco               | 1         | 0.49%   |
| Biostar             | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 24        | 11.82%  |
| Intel Q3XXG4-P V1.0               | 7         | 3.45%   |
| Dell PowerEdge R620               | 5         | 2.46%   |
| Dell PowerEdge R210 II            | 5         | 2.46%   |
| AMI Aptio CRB                     | 5         | 2.46%   |
| Supermicro Super Server           | 4         | 1.97%   |
| PC Engines apu4                   | 3         | 1.48%   |
| Sophos XG                         | 2         | 0.99%   |
| PC Engines APU2                   | 2         | 0.99%   |
| PC Engines APU                    | 2         | 0.99%   |
| Inventec VXC Class                | 2         | 0.99%   |
| HP EliteDesk 800 G1 SFF           | 2         | 0.99%   |
| Gigabyte X570 AORUS PRO           | 2         | 0.99%   |
| Fujitsu FUTRO S920                | 2         | 0.99%   |
| Dell Latitude E4300               | 2         | 0.99%   |
| ZOTAC ZBOX-CI327NANO-GS-01        | 1         | 0.49%   |
| WYSE Z CLASS                      | 1         | 0.49%   |
| TUXEDO Pulse 15 Gen1              | 1         | 0.49%   |
| TOXIC by BTO 15CL872 1050TI       | 1         | 0.49%   |
| Toshiba Satellite C50-B           | 1         | 0.49%   |
| Supermicro X9SCL/X9SCM            | 1         | 0.49%   |
| Supermicro X8SIL                  | 1         | 0.49%   |
| Supermicro X10SAE                 | 1         | 0.49%   |
| Supermicro AS -E301-9D-8CN4       | 1         | 0.49%   |
| Supermicro AS -5019D-FTN4         | 1         | 0.49%   |
| Supermicro A1SAi                  | 1         | 0.49%   |
| Star Labs LabTop                  | 1         | 0.49%   |
| Sophos SG                         | 1         | 0.49%   |
| Sony SVZ1311C5E                   | 1         | 0.49%   |
| Shuttle XH310V2                   | 1         | 0.49%   |
| Shuttle SH87R                     | 1         | 0.49%   |
| Shuttle DH370                     | 1         | 0.49%   |
| Shuttle DH310                     | 1         | 0.49%   |
| Sapphire EDGE-FT1M1 E450 1AOVU044 | 1         | 0.49%   |
| Protectli FW6D                    | 1         | 0.49%   |
| Protectli FW4B                    | 1         | 0.49%   |
| Protectli FW2B                    | 1         | 0.49%   |
| Pegatron h8-1102nl                | 1         | 0.49%   |
| Notebook NL5xRU                   | 1         | 0.49%   |
| MW GMLK-2_5G4L                    | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 24        | 11.82%  |
| Lenovo ThinkPad              | 13        | 6.4%    |
| Dell PowerEdge               | 13        | 6.4%    |
| Intel Q3XXG4-P               | 7         | 3.45%   |
| Dell Latitude                | 7         | 3.45%   |
| Dell OptiPlex                | 5         | 2.46%   |
| AMI Aptio                    | 5         | 2.46%   |
| Supermicro Super             | 4         | 1.97%   |
| HP EliteDesk                 | 4         | 1.97%   |
| PC Engines apu4              | 3         | 1.48%   |
| HP ProLiant                  | 3         | 1.48%   |
| HP EliteBook                 | 3         | 1.48%   |
| HP Compaq                    | 3         | 1.48%   |
| Supermicro AS                | 2         | 0.99%   |
| Sophos XG                    | 2         | 0.99%   |
| PC Engines APU2              | 2         | 0.99%   |
| PC Engines APU               | 2         | 0.99%   |
| Inventec VXC                 | 2         | 0.99%   |
| HP ProDesk                   | 2         | 0.99%   |
| Gigabyte X570                | 2         | 0.99%   |
| Fujitsu FUTRO                | 2         | 0.99%   |
| Deciso Netboard              | 2         | 0.99%   |
| Barracuda Networks Barracuda | 2         | 0.99%   |
| ASUS PRIME                   | 2         | 0.99%   |
| ZOTAC ZBOX-CI327NANO-GS-01   | 1         | 0.49%   |
| WYSE Z                       | 1         | 0.49%   |
| TUXEDO Pulse                 | 1         | 0.49%   |
| TOXIC by BTO 15CL872         | 1         | 0.49%   |
| Toshiba Satellite            | 1         | 0.49%   |
| Supermicro X9SCL             | 1         | 0.49%   |
| Supermicro X8SIL             | 1         | 0.49%   |
| Supermicro X10SAE            | 1         | 0.49%   |
| Supermicro A1SAi             | 1         | 0.49%   |
| Star Labs LabTop             | 1         | 0.49%   |
| Sophos SG                    | 1         | 0.49%   |
| Sony SVZ1311C5E              | 1         | 0.49%   |
| Shuttle XH310V2              | 1         | 0.49%   |
| Shuttle SH87R                | 1         | 0.49%   |
| Shuttle DH370                | 1         | 0.49%   |
| Shuttle DH310                | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 27        | 13.3%   |
| 2020    | 22        | 10.84%  |
| 2019    | 21        | 10.34%  |
| 2014    | 18        | 8.87%   |
| 2016    | 17        | 8.37%   |
| 2015    | 15        | 7.39%   |
| 2013    | 14        | 6.9%    |
| 2017    | 13        | 6.4%    |
| 2021    | 12        | 5.91%   |
| 2011    | 12        | 5.91%   |
| 2012    | 11        | 5.42%   |
| Unknown | 7         | 3.45%   |
| 2009    | 6         | 2.96%   |
| 2022    | 3         | 1.48%   |
| 2010    | 2         | 0.99%   |
| 2008    | 1         | 0.49%   |
| 2007    | 1         | 0.49%   |
| 2006    | 1         | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 119       | 58.62%  |
| Notebook       | 45        | 22.17%  |
| Server         | 17        | 8.37%   |
| Mini pc        | 14        | 6.9%    |
| Firewall       | 5         | 2.46%   |
| All in one     | 2         | 0.99%   |
| System on chip | 1         | 0.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 193       | 95.07%  |
| Yes  | 10        | 4.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 73        | 35.78%  |
| 4.01-8.0        | 50        | 24.51%  |
| 16.01-24.0      | 36        | 17.65%  |
| 32.01-64.0      | 20        | 9.8%    |
| 2.01-3.0        | 7         | 3.43%   |
| 64.01-256.0     | 7         | 3.43%   |
| 3.01-4.0        | 5         | 2.45%   |
| More than 256.0 | 2         | 0.98%   |
| 1.01-2.0        | 2         | 0.98%   |
| 24.01-32.0      | 1         | 0.49%   |
| 0.51-1.0        | 1         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 114       | 54.29%  |
| 0.51-1.0   | 51        | 24.29%  |
| 1.01-2.0   | 21        | 10%     |
| 4.01-8.0   | 6         | 2.86%   |
| 2.01-3.0   | 4         | 1.9%    |
| 8.01-16.0  | 4         | 1.9%    |
| 3.01-4.0   | 3         | 1.43%   |
| 32.01-64.0 | 2         | 0.95%   |
| 24.01-32.0 | 2         | 0.95%   |
| 16.01-24.0 | 1         | 0.48%   |
| 0          | 1         | 0.48%   |
| Unknown    | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 138       | 67.32%  |
| 2      | 31        | 15.12%  |
| 3      | 11        | 5.37%   |
| 0      | 10        | 4.88%   |
| 4      | 6         | 2.93%   |
| 5      | 4         | 1.95%   |
| 15     | 1         | 0.49%   |
| 12     | 1         | 0.49%   |
| 10     | 1         | 0.49%   |
| 7      | 1         | 0.49%   |
| 6      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 175       | 86.21%  |
| Yes       | 28        | 13.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 94.58%  |
| No        | 11        | 5.42%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 132       | 64.39%  |
| Yes       | 73        | 35.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 157       | 77.34%  |
| Yes       | 46        | 22.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Netherlands | 203       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Amsterdam           | 44        | 19.3%   |
| Utrecht             | 6         | 2.63%   |
| Groningen           | 6         | 2.63%   |
| The Hague           | 5         | 2.19%   |
| Vlaardingen         | 4         | 1.75%   |
| Rotterdam           | 4         | 1.75%   |
| Poortugaal          | 4         | 1.75%   |
| Eindhoven           | 4         | 1.75%   |
| Barneveld           | 4         | 1.75%   |
| Alphen aan den Rijn | 4         | 1.75%   |
| Almere Stad         | 4         | 1.75%   |
| Zeist               | 3         | 1.32%   |
| Zaandam             | 3         | 1.32%   |
| Ospel               | 3         | 1.32%   |
| Hoogeveen           | 3         | 1.32%   |
| Breda               | 3         | 1.32%   |
| Amersfoort          | 3         | 1.32%   |
| Almere Poort        | 3         | 1.32%   |
| Zoetermeer          | 2         | 0.88%   |
| Veenendaal          | 2         | 0.88%   |
| Tilburg             | 2         | 0.88%   |
| Soest               | 2         | 0.88%   |
| Oegstgeest          | 2         | 0.88%   |
| Nieuwegein          | 2         | 0.88%   |
| Naaldwijk           | 2         | 0.88%   |
| Maastricht          | 2         | 0.88%   |
| Leiden              | 2         | 0.88%   |
| IJsselstein         | 2         | 0.88%   |
| Hoofddorp           | 2         | 0.88%   |
| Hengelo             | 2         | 0.88%   |
| Deventer            | 2         | 0.88%   |
| Delft               | 2         | 0.88%   |
| Beekbergen          | 2         | 0.88%   |
| Almelo              | 2         | 0.88%   |
| Aalsmeer            | 2         | 0.88%   |
| 's-Hertogenbosch    | 2         | 0.88%   |
| Zutphen             | 1         | 0.44%   |
| Zuidhorn            | 1         | 0.44%   |
| Zetten              | 1         | 0.44%   |
| Zaltbommel          | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 66     | 18.75%  |
| WDC                 | 26        | 67     | 10.83%  |
| Crucial             | 22        | 37     | 9.17%   |
| Seagate             | 15        | 47     | 6.25%   |
| Kingston            | 14        | 18     | 5.83%   |
| Transcend           | 10        | 15     | 4.17%   |
| SanDisk             | 9         | 9      | 3.75%   |
| Hoodisk             | 8         | 12     | 3.33%   |
| Toshiba             | 7         | 18     | 2.92%   |
| Hitachi             | 5         | 7      | 2.08%   |
| HGST                | 5         | 7      | 2.08%   |
| Hewlett-Packard     | 5         | 10     | 2.08%   |
| China               | 5         | 10     | 2.08%   |
| LITEON              | 4         | 5      | 1.67%   |
| Intel               | 4         | 7      | 1.67%   |
| Gigabyte Technology | 4         | 4      | 1.67%   |
| Dell                | 4         | 8      | 1.67%   |
| UDinfo              | 3         | 3      | 1.25%   |
| Phison              | 3         | 3      | 1.25%   |
| NVMe                | 3         | 3      | 1.25%   |
| FORESEE             | 3         | 6      | 1.25%   |
| Apple               | 3         | 3      | 1.25%   |
| Apacer              | 3         | 4      | 1.25%   |
| OCZ                 | 2         | 2      | 0.83%   |
| NETAPP              | 2         | 7      | 0.83%   |
| Kston               | 2         | 5      | 0.83%   |
| Innodisk            | 2         | 2      | 0.83%   |
| A-DATA Technology   | 2         | 2      | 0.83%   |
| StoreJet            | 1         | 1      | 0.42%   |
| Star Drive          | 1         | 1      | 0.42%   |
| SK hynix            | 1         | 1      | 0.42%   |
| Silicon Motion      | 1         | 1      | 0.42%   |
| Protectli           | 1         | 4      | 0.42%   |
| PNY                 | 1         | 1      | 0.42%   |
| Plextor             | 1         | 1      | 0.42%   |
| OWC                 | 1         | 1      | 0.42%   |
| ORICO               | 1         | 1      | 0.42%   |
| OPENBSD             | 1         | 1      | 0.42%   |
| Mushkin             | 1         | 2      | 0.42%   |
| Micron Technology   | 1         | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB        | 7         | 2.71%   |
| Kingston SUV500MS120G 120GB      | 4         | 1.55%   |
| Hoodisk SSD 128GB                | 4         | 1.55%   |
| Dell PERC H710 282GB             | 4         | 1.55%   |
| Crucial CT250MX500SSD1 250GB     | 4         | 1.55%   |
| UDinfo M2S 120GB                 | 3         | 1.16%   |
| Samsung SSD 850 EVO 500GB        | 3         | 1.16%   |
| Crucial CT240BX500SSD1 240GB     | 3         | 1.16%   |
| WDC WD80EFAX-68KNBN0 8TB         | 2         | 0.78%   |
| WDC WD60EFRX-68L0BN1 6TB         | 2         | 0.78%   |
| WDC WD40EFRX-68WT0N0 4TB         | 2         | 0.78%   |
| WDC WD40EFRX-68N32N0 4TB         | 2         | 0.78%   |
| Transcend TS32GSSD370S 32GB      | 2         | 0.78%   |
| Transcend TS128GMTE110S 128GB    | 2         | 0.78%   |
| Toshiba MQ04ABF100 1TB           | 2         | 0.78%   |
| Seagate ST500LM000-SSHD-8GB      | 2         | 0.78%   |
| Samsung SSD 980 PRO 1TB          | 2         | 0.78%   |
| Samsung SSD 970 EVO 1TB          | 2         | 0.78%   |
| Samsung SSD 840 Series 120GB     | 2         | 0.78%   |
| Samsung SSD 840 EVO 120GB        | 2         | 0.78%   |
| NETAPP X446_RALS200MCHT 200GB    | 2         | 0.78%   |
| LITEON IT LCS-128L9S-HP 128GB    | 2         | 0.78%   |
| LITEON CS1-SP16-11 M.2 2242 16GB | 2         | 0.78%   |
| Kston SSD 128GB                  | 2         | 0.78%   |
| Hoodisk SSD 64GB                 | 2         | 0.78%   |
| HGST HTS725050A7E630 500GB       | 2         | 0.78%   |
| Crucial M4-CT128M4SSD2 128GB     | 2         | 0.78%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.78%   |
| Crucial CT500MX200SSD1 500GB     | 2         | 0.78%   |
| Crucial CT480M500SSD1 480GB      | 2         | 0.78%   |
| Crucial CT120BX500SSD1 120GB     | 2         | 0.78%   |
| China SATA SSD 16GB              | 2         | 0.78%   |
| Apacer 64GB SATA Flash Drive     | 2         | 0.78%   |
| A-DATA IM2S3134N-064GM 64GB      | 2         | 0.78%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 0.39%   |
| WDC WDS500G1X0E-00AFY0 500GB     | 1         | 0.39%   |
| WDC WDS240G2G0B-00EPW0 240GB     | 1         | 0.39%   |
| WDC WDS120G2G0A-00JH30 120GB     | 1         | 0.39%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 1         | 0.39%   |
| WDC WDS100T2B0B-00YS70 1TB       | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 57     | 32.35%  |
| Seagate             | 15        | 47     | 22.06%  |
| Samsung Electronics | 5         | 8      | 7.35%   |
| Hitachi             | 5         | 7      | 7.35%   |
| HGST                | 5         | 7      | 7.35%   |
| Hewlett-Packard     | 4         | 9      | 5.88%   |
| Dell                | 4         | 8      | 5.88%   |
| Toshiba             | 3         | 11     | 4.41%   |
| StoreJet            | 1         | 1      | 1.47%   |
| OPENBSD             | 1         | 1      | 1.47%   |
| NVMe                | 1         | 1      | 1.47%   |
| Lenovo              | 1         | 2      | 1.47%   |
| Apple               | 1         | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 45     | 22.15%  |
| Crucial             | 22        | 33     | 14.77%  |
| Kingston            | 10        | 14     | 6.71%   |
| SanDisk             | 9         | 9      | 6.04%   |
| Transcend           | 8         | 13     | 5.37%   |
| Hoodisk             | 8         | 12     | 5.37%   |
| China               | 5         | 10     | 3.36%   |
| LITEON              | 4         | 5      | 2.68%   |
| Intel               | 4         | 7      | 2.68%   |
| WDC                 | 3         | 6      | 2.01%   |
| UDinfo              | 3         | 3      | 2.01%   |
| Phison              | 3         | 3      | 2.01%   |
| FORESEE             | 3         | 6      | 2.01%   |
| Apacer              | 3         | 4      | 2.01%   |
| Toshiba             | 2         | 4      | 1.34%   |
| OCZ                 | 2         | 2      | 1.34%   |
| NVMe                | 2         | 2      | 1.34%   |
| NETAPP              | 2         | 7      | 1.34%   |
| Kston               | 2         | 5      | 1.34%   |
| Innodisk            | 2         | 2      | 1.34%   |
| Apple               | 2         | 2      | 1.34%   |
| A-DATA Technology   | 2         | 2      | 1.34%   |
| SK hynix            | 1         | 1      | 0.67%   |
| Protectli           | 1         | 4      | 0.67%   |
| PNY                 | 1         | 1      | 0.67%   |
| OWC                 | 1         | 1      | 0.67%   |
| ORICO               | 1         | 1      | 0.67%   |
| Mushkin             | 1         | 2      | 0.67%   |
| Micron Technology   | 1         | 1      | 0.67%   |
| Leven               | 1         | 1      | 0.67%   |
| Intenso             | 1         | 1      | 0.67%   |
| Indilinx            | 1         | 1      | 0.67%   |
| HPE                 | 1         | 1      | 0.67%   |
| Hewlett-Packard     | 1         | 1      | 0.67%   |
| Gigabyte Technology | 1         | 1      | 0.67%   |
| Corsair             | 1         | 2      | 0.67%   |
| BAITITON            | 1         | 2      | 0.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 140       | 217    | 62.22%  |
| HDD  | 60        | 160    | 26.67%  |
| NVMe | 25        | 37     | 11.11%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 178       | 377    | 87.68%  |
| NVMe | 25        | 37     | 12.32%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 159       | 250    | 77.18%  |
| 0.51-1.0   | 23        | 46     | 11.17%  |
| 1.01-2.0   | 9         | 15     | 4.37%   |
| 3.01-4.0   | 7         | 18     | 3.4%    |
| 4.01-10.0  | 7         | 44     | 3.4%    |
| 2.01-3.0   | 1         | 4      | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 77        | 36.67%  |
| 51-100         | 35        | 16.67%  |
| 251-500        | 31        | 14.76%  |
| 1-20           | 29        | 13.81%  |
| 21-50          | 15        | 7.14%   |
| 501-1000       | 11        | 5.24%   |
| 1001-2000      | 6         | 2.86%   |
| More than 3000 | 2         | 0.95%   |
| 2001-3000      | 2         | 0.95%   |
| Unknown        | 2         | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 178       | 86.41%  |
| 21-50    | 10        | 4.85%   |
| 101-250  | 5         | 2.43%   |
| 51-100   | 5         | 2.43%   |
| 251-500  | 3         | 1.46%   |
| 501-1000 | 3         | 1.46%   |
| Unknown  | 2         | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Crucial CT480M500SSD1 480GB               | 2         | 3      | 7.69%   |
| WDC WD15EARS-00Z5B1 1.5TB                 | 1         | 1      | 3.85%   |
| Seagate ST500LT012-9WS142 500GB           | 1         | 2      | 3.85%   |
| Seagate ST500LM021-1KJ152 500GB           | 1         | 1      | 3.85%   |
| Seagate ST3160318AS 160GB                 | 1         | 4      | 3.85%   |
| SanDisk SD7UB3Q256G1001 256GB             | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 870 EVO 1TB       | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 850 EVO mSATA 1TB | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 850 EVO 1TB       | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 840 Series 120GB  | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 840 EVO 120GB     | 1         | 1      | 3.85%   |
| Samsung Electronics HS082HB 80GB          | 1         | 1      | 3.85%   |
| Samsung Electronics HD322HJ 320GB         | 1         | 1      | 3.85%   |
| Samsung Electronics HD103SJ 1TB           | 1         | 2      | 3.85%   |
| Kingston SMS200S3120G 120GB               | 1         | 1      | 3.85%   |
| Intel SSDSC2BA200G3T 200GB                | 1         | 4      | 3.85%   |
| Hitachi HTS545032B9A300 320GB             | 1         | 1      | 3.85%   |
| Hitachi HTS543232A7A384 320GB             | 1         | 1      | 3.85%   |
| Hitachi HDS723015BLA642 1.5TB             | 1         | 3      | 3.85%   |
| HGST HTS725050A7E630 500GB                | 1         | 1      | 3.85%   |
| HGST HDN726060ALE614 6TB                  | 1         | 2      | 3.85%   |
| Hewlett-Packard FB160C4081 160GB          | 1         | 2      | 3.85%   |
| Crucial CT128MX100SSD1 128GB              | 1         | 2      | 3.85%   |
| Corsair Force LS SSD 64GB                 | 1         | 2      | 3.85%   |
| China SH00M128GB                          | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 28%     |
| Seagate             | 3         | 7      | 12%     |
| Hitachi             | 3         | 5      | 12%     |
| Crucial             | 3         | 5      | 12%     |
| HGST                | 2         | 3      | 8%      |
| WDC                 | 1         | 1      | 4%      |
| SanDisk             | 1         | 1      | 4%      |
| Kingston            | 1         | 1      | 4%      |
| Intel               | 1         | 4      | 4%      |
| Hewlett-Packard     | 1         | 2      | 4%      |
| Corsair             | 1         | 2      | 4%      |
| China               | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 7      | 23.08%  |
| Samsung Electronics | 3         | 4      | 23.08%  |
| Hitachi             | 3         | 5      | 23.08%  |
| HGST                | 2         | 3      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| Hewlett-Packard     | 1         | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 22     | 54.17%  |
| SSD  | 11        | 19     | 45.83%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 960 EVO 250GB | 1         | 1      | 50%     |
| HPE MK000480GWUGF 480GB               | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| HPE                 | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 170       | 352    | 82.13%  |
| Malfunc  | 24        | 41     | 11.59%  |
| Detected | 11        | 19     | 5.31%   |
| Failed   | 2         | 2      | 0.97%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 155       | 65.13%  |
| AMD                         | 33        | 13.87%  |
| Samsung Electronics         | 11        | 4.62%   |
| Broadcom / LSI              | 8         | 3.36%   |
| Phison Electronics          | 6         | 2.52%   |
| ASMedia Technology          | 6         | 2.52%   |
| Kingston Technology Company | 3         | 1.26%   |
| Hewlett-Packard             | 3         | 1.26%   |
| Toshiba                     | 2         | 0.84%   |
| SanDisk                     | 2         | 0.84%   |
| Silicon Motion              | 1         | 0.42%   |
| Micron/Crucial Technology   | 1         | 0.42%   |
| Micron Technology           | 1         | 0.42%   |
| Marvell Technology Group    | 1         | 0.42%   |
| Lite-On Technology          | 1         | 0.42%   |
| JMicron Technology          | 1         | 0.42%   |
| Dell                        | 1         | 0.42%   |
| Chelsio Communications      | 1         | 0.42%   |
| Unknown                     | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 8.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 16        | 6.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 5.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 12        | 4.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 3.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 3.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 2.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7         | 2.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 2.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 1.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 1.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 1.95%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 1.95%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 1.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.56%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 4         | 1.56%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 4         | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.17%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 1.17%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 3         | 1.17%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 3         | 1.17%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3         | 1.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 3         | 1.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.17%   |
| Unknown                                                                          | 3         | 1.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.78%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.78%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.78%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.78%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 0.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 0.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.78%   |
| HP Smart Array Gen9 Controllers                                                  | 2         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 173       | 73%     |
| NVMe | 29        | 12.24%  |
| RAID | 19        | 8.02%   |
| IDE  | 11        | 4.64%   |
| SAS  | 4         | 1.69%   |
| SCSI | 1         | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 161       | 79.31%  |
| AMD    | 36        | 17.73%  |
| ARM    | 6         | 2.96%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz    | 5         | 2.46%   |
| Intel Celeron CPU J1900 @ 1.99GHz    | 5         | 2.46%   |
| AMD GX-412TC SOC                     | 5         | 2.46%   |
| Intel Core 2 Duo                     | 4         | 1.97%   |
| ARM Cortex-A72 r0p3                  | 4         | 1.97%   |
| AMD G-T56N Processor                 | 4         | 1.97%   |
| Intel Xeon CPU D-1521 @ 2.40GHz      | 3         | 1.48%   |
| Intel Core i5-5200U CPU @ 2.20GHz    | 3         | 1.48%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz   | 2         | 0.99%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz   | 2         | 0.99%   |
| Intel Core i7-7600U CPU @ 2.80GHz    | 2         | 0.99%   |
| Intel Core i7-5500U CPU @ 2.40GHz    | 2         | 0.99%   |
| Intel Core i7-4600U CPU @ 2.10GHz    | 2         | 0.99%   |
| Intel Core i7-3520M CPU @ 2.90GHz    | 2         | 0.99%   |
| Intel Core i7-2600 CPU @ 3.40GHz     | 2         | 0.99%   |
| Intel Core i5-8600 CPU @ 3.10GHz     | 2         | 0.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz    | 2         | 0.99%   |
| Intel Core i5-5250U CPU @ 1.60GHz    | 2         | 0.99%   |
| Intel Core i5-4690 CPU @ 3.50GHz     | 2         | 0.99%   |
| Intel Core i5-4590 CPU @ 3.30GHz     | 2         | 0.99%   |
| Intel Core i5-3470 CPU @ 3.20GHz     | 2         | 0.99%   |
| Intel Core i5-3210M CPU @ 2.50GHz    | 2         | 0.99%   |
| Intel Core i5-10400 CPU @ 2.90GHz    | 2         | 0.99%   |
| Intel Core i3-5005U CPU @ 2.00GHz    | 2         | 0.99%   |
| Intel Atom CPU C3558 @ 2.20GHz       | 2         | 0.99%   |
| Intel Atom CPU C2358 @ 1.74GHz       | 2         | 0.99%   |
| ARM Cortex-A53 r0p4                  | 2         | 0.99%   |
| AMD G-T40E Processor                 | 2         | 0.99%   |
| AMD EPYC 3251 8-Core Processor       | 2         | 0.99%   |
| Intel Xeon E-2314 CPU @ 2.80GHz      | 1         | 0.49%   |
| Intel Xeon E-2274G CPU @ 4.00GHz     | 1         | 0.49%   |
| Intel Xeon E-2224 CPU @ 3.40GHz      | 1         | 0.49%   |
| Intel Xeon CPU X5680 @ 3.33GHz       | 1         | 0.49%   |
| Intel Xeon CPU X3430 @ 2.40GHz       | 1         | 0.49%   |
| Intel Xeon CPU L3426 @ 1.87GHz       | 1         | 0.49%   |
| Intel Xeon CPU E5606 @ 2.13GHz       | 1         | 0.49%   |
| Intel Xeon CPU E5520 @ 2.27GHz       | 1         | 0.49%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz   | 1         | 0.49%   |
| Intel Xeon CPU E5-2650L v3 @ 1.80GHz | 1         | 0.49%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz  | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 45        | 22.17%  |
| Intel Xeon           | 28        | 13.79%  |
| Intel Core i7        | 25        | 12.32%  |
| Intel Celeron        | 20        | 9.85%   |
| AMD GX               | 11        | 5.42%   |
| Intel Atom           | 10        | 4.93%   |
| Intel Core 2 Duo     | 9         | 4.43%   |
| Intel Core i3        | 8         | 3.94%   |
| Intel Pentium        | 6         | 2.96%   |
| ARM Cortex           | 6         | 2.96%   |
| AMD G                | 6         | 2.96%   |
| Other                | 5         | 2.46%   |
| Intel Pentium Gold   | 3         | 1.48%   |
| AMD Ryzen 7          | 3         | 1.48%   |
| Intel Pentium Silver | 2         | 0.99%   |
| AMD Ryzen 5          | 2         | 0.99%   |
| AMD EPYC             | 2         | 0.99%   |
| Intel Pentium 4      | 1         | 0.49%   |
| Intel Core m7        | 1         | 0.49%   |
| Intel Core 2         | 1         | 0.49%   |
| AMD Ryzen Embedded   | 1         | 0.49%   |
| AMD Ryzen 9          | 1         | 0.49%   |
| AMD Ryzen 7 PRO      | 1         | 0.49%   |
| AMD Ryzen 5 PRO      | 1         | 0.49%   |
| AMD E2               | 1         | 0.49%   |
| AMD E1               | 1         | 0.49%   |
| AMD E                | 1         | 0.49%   |
| AMD Athlon II        | 1         | 0.49%   |
| AMD A8               | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 81        | 39.9%   |
| 2       | 75        | 36.95%  |
| Unknown | 12        | 5.91%   |
| 8       | 11        | 5.42%   |
| 6       | 11        | 5.42%   |
| 12      | 7         | 3.45%   |
| 16      | 4         | 1.97%   |
| 1       | 2         | 0.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 190       | 93.6%   |
| 2       | 7         | 3.45%   |
| Unknown | 6         | 2.96%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 100       | 49.26%  |
| 2       | 91        | 44.83%  |
| Unknown | 12        | 5.91%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 24        | 11.82%  |
| Haswell       | 22        | 10.84%  |
| Silvermont    | 18        | 8.87%   |
| Broadwell     | 18        | 8.87%   |
| IvyBridge     | 17        | 8.37%   |
| SandyBridge   | 15        | 7.39%   |
| Skylake       | 9         | 4.43%   |
| Unknown       | 9         | 4.43%   |
| Puma          | 7         | 3.45%   |
| Penryn        | 7         | 3.45%   |
| Bobcat        | 7         | 3.45%   |
| CometLake     | 6         | 2.96%   |
| Zen 2         | 5         | 2.46%   |
| Zen           | 5         | 2.46%   |
| Jaguar        | 5         | 2.46%   |
| Nehalem       | 4         | 1.97%   |
| Goldmont plus | 4         | 1.97%   |
| Goldmont      | 4         | 1.97%   |
| Westmere      | 3         | 1.48%   |
| Core          | 3         | 1.48%   |
| Excavator     | 2         | 0.99%   |
| Bonnell       | 2         | 0.99%   |
| Zen 3         | 1         | 0.49%   |
| TigerLake     | 1         | 0.49%   |
| Steamroller   | 1         | 0.49%   |
| Piledriver    | 1         | 0.49%   |
| NetBurst      | 1         | 0.49%   |
| K8 Hammer     | 1         | 0.49%   |
| K10           | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 113       | 59.16%  |
| AMD                        | 30        | 15.71%  |
| Matrox Electronics Systems | 20        | 10.47%  |
| Nvidia                     | 15        | 7.85%   |
| ASPEED Technology          | 13        | 6.81%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 13        | 6.7%    |
| Intel HD Graphics 5500                                                                   | 10        | 5.15%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 9         | 4.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 4.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 4.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 3.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 3.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.09%   |
| Matrox Electronics Systems G200eR2                                                       | 5         | 2.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 2.58%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 2.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.06%   |
| Intel HD Graphics 620                                                                    | 4         | 2.06%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 2.06%   |
| Intel HD Graphics 6000                                                                   | 3         | 1.55%   |
| Intel HD Graphics 530                                                                    | 3         | 1.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.55%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 1.55%   |
| AMD Renoir                                                                               | 3         | 1.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.55%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 1.03%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 1.03%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.03%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.03%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 1.03%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.03%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 1.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.03%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.03%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.52%   |
| Nvidia GT218 [ION]                                                                       | 1         | 0.52%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.52%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.52%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 98        | 48.28%  |
| 1 x AMD        | 29        | 14.29%  |
| 1 x Matrox     | 20        | 9.85%   |
| Other          | 18        | 8.87%   |
| 1 x ASPEED     | 13        | 6.4%    |
| 2 x Intel      | 9         | 4.43%   |
| 1 x Nvidia     | 9         | 4.43%   |
| Intel + Nvidia | 6         | 2.96%   |
| 2 x AMD        | 1         | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 176       | 86.7%   |
| Unknown     | 20        | 9.85%   |
| Proprietary | 7         | 3.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 185       | 90.69%  |
| 0.01-0.5   | 7         | 3.43%   |
| 1.01-2.0   | 5         | 2.45%   |
| 7.01-8.0   | 3         | 1.47%   |
| 0.51-1.0   | 3         | 1.47%   |
| 3.01-4.0   | 1         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| LG Display          | 9         | 16.67%  |
| Samsung Electronics | 7         | 12.96%  |
| Chimei Innolux      | 6         | 11.11%  |
| Apple               | 5         | 9.26%   |
| Iiyama              | 4         | 7.41%   |
| BOE                 | 4         | 7.41%   |
| AU Optronics        | 3         | 5.56%   |
| Sony                | 2         | 3.7%    |
| Sharp               | 2         | 3.7%    |
| Philips             | 2         | 3.7%    |
| Lenovo              | 2         | 3.7%    |
| Goldstar            | 2         | 3.7%    |
| Dell                | 2         | 3.7%    |
| ViewSonic           | 1         | 1.85%   |
| PANDA               | 1         | 1.85%   |
| ASUSTek Computer    | 1         | 1.85%   |
| AOC                 | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Philips PHL 328E1 PHLC204 3840x2160 700x390mm 31.5-inch              | 2         | 3.7%    |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch          | 2         | 3.7%    |
| ViewSonic LCD Monitor VX3276-QHD 2560x1440                           | 1         | 1.85%   |
| Sony TV SNYC901 1920x1080                                            | 1         | 1.85%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                        | 1         | 1.85%   |
| Sharp LCD Monitor SHP1461 3200x1800 290x170mm 13.2-inch              | 1         | 1.85%   |
| Sharp LCD Monitor SHP1453 1920x1080 350x190mm 15.7-inch              | 1         | 1.85%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 470x300mm 22.0-inch | 1         | 1.85%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch | 1         | 1.85%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 530x300mm 24.0-inch    | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC4541 1280x800 260x160mm 12.0-inch | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch | 1         | 1.85%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 290x170mm 13.2-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch         | 1         | 1.85%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch         | 1         | 1.85%   |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch          | 1         | 1.85%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 1         | 1.85%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch         | 1         | 1.85%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 1         | 1.85%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch          | 1         | 1.85%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch              | 1         | 1.85%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 1         | 1.85%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch              | 1         | 1.85%   |
| Iiyama PL2740HS IVM6662 1920x1080 600x340mm 27.2-inch                | 1         | 1.85%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                 | 1         | 1.85%   |
| Iiyama PL2209HD IVM560B 1920x1080 480x270mm 21.7-inch                | 1         | 1.85%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch          | 1         | 1.85%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 1         | 1.85%   |
| Dell UP2716D DEL40DD 2560x1440 600x340mm 27.2-inch                   | 1         | 1.85%   |
| Dell U2715H DELD065 2560x1440 600x340mm 27.2-inch                    | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15B5 1366x768 340x190mm 15.3-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 310x170mm 13.9-inch     | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 1         | 1.85%   |
| BOE LCD Monitor BOE07F7 1920x1080 310x170mm 13.9-inch                | 1         | 1.85%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                | 1         | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 17        | 31.48%  |
| 1366x768 (WXGA)    | 10        | 18.52%  |
| 1280x800 (WXGA)    | 7         | 12.96%  |
| 2560x1440 (QHD)    | 6         | 11.11%  |
| 3840x2160 (4K)     | 5         | 9.26%   |
| 1600x900 (HD+)     | 4         | 7.41%   |
| 1680x1050 (WSXGA+) | 2         | 3.7%    |
| 3440x1440          | 1         | 1.85%   |
| 3200x1800 (QHD+)   | 1         | 1.85%   |
| 1600x1200          | 1         | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 15        | 27.78%  |
| 12      | 10        | 18.52%  |
| 15      | 8         | 14.81%  |
| 27      | 6         | 11.11%  |
| 24      | 3         | 5.56%   |
| 31      | 2         | 3.7%    |
| 23      | 2         | 3.7%    |
| 20      | 2         | 3.7%    |
| Unknown | 2         | 3.7%    |
| 34      | 1         | 1.85%   |
| 22      | 1         | 1.85%   |
| 21      | 1         | 1.85%   |
| 17      | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 201-300     | 18        | 33.33%  |
| 301-350     | 15        | 27.78%  |
| 501-600     | 10        | 18.52%  |
| 401-500     | 4         | 7.41%   |
| 601-700     | 3         | 5.56%   |
| Unknown     | 2         | 3.7%    |
| 701-800     | 1         | 1.85%   |
| 351-400     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 41        | 77.36%  |
| 16/10   | 8         | 15.09%  |
| 4/3     | 1         | 1.89%   |
| 3/2     | 1         | 1.89%   |
| 21/9    | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 12        | 22.22%  |
| 61-70          | 10        | 18.52%  |
| 301-350        | 6         | 11.11%  |
| 201-250        | 6         | 11.11%  |
| 91-100         | 6         | 11.11%  |
| 71-80          | 3         | 5.56%   |
| 351-500        | 3         | 5.56%   |
| 151-200        | 2         | 3.7%    |
| 101-110        | 2         | 3.7%    |
| Unknown        | 2         | 3.7%    |
| 251-300        | 1         | 1.85%   |
| 121-130        | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 32.08%  |
| 101-120       | 17        | 32.08%  |
| 51-100        | 8         | 15.09%  |
| 161-240       | 7         | 13.21%  |
| More than 240 | 2         | 3.77%   |
| Unknown       | 2         | 3.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 149       | 73.4%   |
| 1     | 52        | 25.62%  |
| 2     | 2         | 0.99%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 160       | 56.74%  |
| Realtek Semiconductor             | 55        | 19.5%   |
| Broadcom                          | 24        | 8.51%   |
| Qualcomm Atheros                  | 16        | 5.67%   |
| IMC Networks                      | 4         | 1.42%   |
| Ralink Technology                 | 3         | 1.06%   |
| TP-Link                           | 2         | 0.71%   |
| Ralink                            | 2         | 0.71%   |
| Marvell Technology Group          | 2         | 0.71%   |
| Hewlett-Packard                   | 2         | 0.71%   |
| Edimax Technology                 | 2         | 0.71%   |
| U-Blox                            | 1         | 0.35%   |
| Sierra Wireless                   | 1         | 0.35%   |
| Mellanox Technologies             | 1         | 0.35%   |
| Insyde Software                   | 1         | 0.35%   |
| HMD Global                        | 1         | 0.35%   |
| Fibocom                           | 1         | 0.35%   |
| Ericsson Business Mobile Networks | 1         | 0.35%   |
| Chelsio Communications            | 1         | 0.35%   |
| AMD                               | 1         | 0.35%   |
| ADMtek                            | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 43        | 12.61%  |
| Intel I211 Gigabit Network Connection                                         | 30        | 8.8%    |
| Intel I210 Gigabit Network Connection                                         | 22        | 6.45%   |
| Intel I350 Gigabit Network Connection                                         | 19        | 5.57%   |
| Intel 82574L Gigabit Network Connection                                       | 13        | 3.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 11        | 3.23%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7         | 2.05%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 7         | 2.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5         | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 5         | 1.47%   |
| Intel Wi-Fi 6 AX200                                                           | 5         | 1.47%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 1.17%   |
| Intel 82567LM Gigabit Network Connection                                      | 4         | 1.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 0.88%   |
| Intel Wireless-AC 9260                                                        | 3         | 0.88%   |
| Intel Wireless 8265 / 8275                                                    | 3         | 0.88%   |
| Intel Wireless 8260                                                           | 3         | 0.88%   |
| Intel Wireless 7265                                                           | 3         | 0.88%   |
| Intel Wireless 7260                                                           | 3         | 0.88%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 3         | 0.88%   |
| Intel Ethernet Connection X553 1GbE                                           | 3         | 0.88%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 3         | 0.88%   |
| Intel Ethernet Connection I354                                                | 3         | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 0.88%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 3         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 3         | 0.88%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 0.59%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 2         | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 0.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 0.59%   |
| Intel Wireless 3165                                                           | 2         | 0.59%   |
| Intel Wireless 3160                                                           | 2         | 0.59%   |
| Intel WiFi Link 5100                                                          | 2         | 0.59%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 2         | 0.59%   |
| Intel Ethernet Controller I225-V                                              | 2         | 0.59%   |
| Intel Ethernet Connection I219-V                                              | 2         | 0.59%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.59%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 47.06%  |
| Qualcomm Atheros      | 13        | 15.29%  |
| Realtek Semiconductor | 9         | 10.59%  |
| Broadcom              | 9         | 10.59%  |
| IMC Networks          | 4         | 4.71%   |
| Ralink Technology     | 3         | 3.53%   |
| TP-Link               | 2         | 2.35%   |
| Ralink                | 2         | 2.35%   |
| Edimax Technology     | 2         | 2.35%   |
| Sierra Wireless       | 1         | 1.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 5.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 5.88%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 5.88%   |
| Intel Wireless-AC 9260                                                  | 3         | 3.53%   |
| Intel Wireless 8265 / 8275                                              | 3         | 3.53%   |
| Intel Wireless 8260                                                     | 3         | 3.53%   |
| Intel Wireless 7265                                                     | 3         | 3.53%   |
| Intel Wireless 7260                                                     | 3         | 3.53%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 3.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 3.53%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 3         | 3.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 3.53%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 2.35%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter         | 2         | 2.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.35%   |
| Intel Wireless 3165                                                     | 2         | 2.35%   |
| Intel Wireless 3160                                                     | 2         | 2.35%   |
| Intel WiFi Link 5100                                                    | 2         | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.35%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 2.35%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 2.35%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 2.35%   |
| TP-Link TP-LINK Wireless USB Adapter                                    | 1         | 1.18%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 1.18%   |
| Sierra Wireless EM7455                                                  | 1         | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.18%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.18%   |
| Realtek RTL8192SU 802.11n WLAN Adapter                                  | 1         | 1.18%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.18%   |
| Ralink RT3572 Wireless Adapter                                          | 1         | 1.18%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                            | 1         | 1.18%   |
| Ralink RT2500 Wireless 802.11bg                                         | 1         | 1.18%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.18%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.18%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.18%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.18%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 143       | 64.41%  |
| Realtek Semiconductor    | 48        | 21.62%  |
| Broadcom                 | 19        | 8.56%   |
| Qualcomm Atheros         | 5         | 2.25%   |
| Marvell Technology Group | 2         | 0.9%    |
| Insyde Software          | 1         | 0.45%   |
| HMD Global               | 1         | 0.45%   |
| Chelsio Communications   | 1         | 0.45%   |
| AMD                      | 1         | 0.45%   |
| ADMtek                   | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 43        | 17.2%   |
| Intel I211 Gigabit Network Connection                                          | 30        | 12%     |
| Intel I210 Gigabit Network Connection                                          | 22        | 8.8%    |
| Intel I350 Gigabit Network Connection                                          | 19        | 7.6%    |
| Intel 82574L Gigabit Network Connection                                        | 13        | 5.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 4.4%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 7         | 2.8%    |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                 | 7         | 2.8%    |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.6%    |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 1.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 1.2%    |
| Intel Ethernet Connection X553 1GbE                                            | 3         | 1.2%    |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                               | 3         | 1.2%    |
| Intel Ethernet Connection I354                                                 | 3         | 1.2%    |
| Intel I210 Gigabit Fiber Network Connection                                    | 2         | 0.8%    |
| Intel Ethernet Controller I225-V                                               | 2         | 0.8%    |
| Intel Ethernet Connection I219-V                                               | 2         | 0.8%    |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.8%    |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 0.8%    |
| Intel Ethernet Connection (14) I219-V                                          | 2         | 0.8%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2         | 0.8%    |
| Intel 82583V Gigabit Network Connection                                        | 2         | 0.8%    |
| Intel 82576 Gigabit Network Connection                                         | 2         | 0.8%    |
| Intel 82575GB Gigabit Network Connection                                       | 2         | 0.8%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 2         | 0.8%    |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 0.8%    |
| Intel 82541PI Gigabit Ethernet Controller                                      | 2         | 0.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.8%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 2         | 0.8%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 2         | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.4%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.4%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 192       | 70.85%  |
| WiFi     | 73        | 26.94%  |
| Modem    | 3         | 1.11%   |
| Unknown  | 3         | 1.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 173       | 81.6%   |
| WiFi     | 39        | 18.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 79        | 38.73%  |
| 4     | 43        | 21.08%  |
| 1     | 27        | 13.24%  |
| 3     | 15        | 7.35%   |
| 6     | 14        | 6.86%   |
| 5     | 12        | 5.88%   |
| 0     | 5         | 2.45%   |
| 9     | 4         | 1.96%   |
| 8     | 2         | 0.98%   |
| 7     | 2         | 0.98%   |
| 12    | 1         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 177       | 83.89%  |
| Yes  | 34        | 16.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 24        | 51.06%  |
| Apple                   | 7         | 14.89%  |
| Cambridge Silicon Radio | 5         | 10.64%  |
| Broadcom                | 3         | 6.38%   |
| Realtek Semiconductor   | 2         | 4.26%   |
| IMC Networks            | 2         | 4.26%   |
| TP-Link                 | 1         | 2.13%   |
| Lite-On Technology      | 1         | 2.13%   |
| Hewlett-Packard         | 1         | 2.13%   |
| Dell                    | 1         | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 19.15%  |
| Intel AX200 Bluetooth                               | 5         | 10.64%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 10.64%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 8.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 6.38%   |
| Apple Bluetooth Host Controller                     | 3         | 6.38%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 4.26%   |
| TP-Link TP-Link UB500 Adapter                       | 1         | 2.13%   |
| Realtek RTL8723A Bluetooth                          | 1         | 2.13%   |
| Realtek  Bluetooth Adapter                          | 1         | 2.13%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.13%   |
| Intel AX201 Bluetooth                               | 1         | 2.13%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 2.13%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0         | 1         | 2.13%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 2.13%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module         | 1         | 2.13%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 2.13%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 2.13%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.13%   |
| Apple Broadcom Bluetooth 2.1 module                 | 1         | 2.13%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 113       | 71.52%  |
| AMD                         | 31        | 19.62%  |
| Nvidia                      | 10        | 6.33%   |
| VIA Technologies            | 1         | 0.63%   |
| Steinberg Soft-und Hardware | 1         | 0.63%   |
| Creative Labs               | 1         | 0.63%   |
| Corsair                     | 1         | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 6.47%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 5.97%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 5.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 5.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 4.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 3.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 3.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 3.48%   |
| AMD FCH Azalia Controller                                                                         | 7         | 3.48%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 3.48%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.99%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 2.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 2.99%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.99%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.49%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 2.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.99%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.49%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 1.49%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1%      |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1%      |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 1%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 1%      |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1%      |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1%      |
| VIA Technologies USB Audio Device                                                                 | 1         | 0.5%    |
| Steinberg Soft-und Hardware MI4                                                                   | 1         | 0.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.5%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 35        | 18.23%  |
| Kingston              | 30        | 15.63%  |
| Unknown               | 20        | 10.42%  |
| SK hynix              | 20        | 10.42%  |
| Micron Technology     | 19        | 9.9%    |
| Corsair               | 16        | 8.33%   |
| Crucial               | 13        | 6.77%   |
| Kimtigo               | 5         | 2.6%    |
| Transcend             | 4         | 2.08%   |
| Apacer                | 4         | 2.08%   |
| Ramaxel Technology    | 3         | 1.56%   |
| Nanya Technology      | 3         | 1.56%   |
| G.Skill               | 3         | 1.56%   |
| Elpida                | 3         | 1.56%   |
| A-DATA Technology     | 3         | 1.56%   |
| Unknown (ABCD)        | 1         | 0.52%   |
| Unknown (07FB)        | 1         | 0.52%   |
| Toshiba               | 1         | 0.52%   |
| Tigo                  | 1         | 0.52%   |
| Team                  | 1         | 0.52%   |
| SK_Hynix              | 1         | 0.52%   |
| Patriot               | 1         | 0.52%   |
| Kingmax Semiconductor | 1         | 0.52%   |
| HPE                   | 1         | 0.52%   |
| Hewlett-Packard       | 1         | 0.52%   |
| Avant                 | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 4         | 1.95%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 4         | 1.95%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s             | 3         | 1.46%   |
| Apacer RAM 37352E4138334331 2GB SODIMM DDR3 1333MT/s              | 3         | 1.46%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 2         | 0.98%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 2         | 0.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 2         | 0.98%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s              | 2         | 0.98%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                       | 2         | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s               | 2         | 0.98%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 2         | 0.98%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s               | 2         | 0.98%   |
| Kingston RAM 9965669-031.A00G 16GB DIMM DDR4 2400MT/s             | 2         | 0.98%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.98%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s             | 2         | 0.98%   |
| Corsair RAM CMSO8GX4M1A2133C15 8GB SODIMM DDR4 2133MT/s           | 2         | 0.98%   |
| Unknown RAM WPBS16D308SWD-4G 4GB DIMM DDR3 1600MT/s               | 1         | 0.49%   |
| Unknown RAM Module 8GB SODIMM LPDDR3 1867MT/s                     | 1         | 0.49%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                       | 1         | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                         | 1         | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1         | 0.49%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 1         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                                | 1         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                        | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                         | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2                                  | 1         | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                        | 1         | 0.49%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                         | 1         | 0.49%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                          | 1         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 1         | 0.49%   |
| Unknown (07FB) RAM GSA8G4SCL156P-21 8GB SODIMM DDR4 2133MT/s      | 1         | 0.49%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s             | 1         | 0.49%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s               | 1         | 0.49%   |
| Transcend RAM JM1600KLN-4G 4GB DIMM DDR3 1600MT/s                 | 1         | 0.49%   |
| Transcend RAM JM1333KSN-4G 4GB DIMM DDR3 1333MT/s                 | 1         | 0.49%   |
| Toshiba RAM 9965527-025.A00LF 8GB SODIMM DDR3 1600MT/s            | 1         | 0.49%   |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.49%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 2400MT/s              | 1         | 0.49%   |
| SK_Hynix RAM HMA851S6DJR6N-VK 4GB SODIMM DDR4 2666MT/s            | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 100       | 58.14%  |
| DDR4    | 57        | 33.14%  |
| DDR2    | 9         | 5.23%   |
| LPDDR3  | 2         | 1.16%   |
| Unknown | 2         | 1.16%   |
| LPDDR4  | 1         | 0.58%   |
| DDR     | 1         | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 86        | 49.71%  |
| SODIMM       | 83        | 47.98%  |
| Chip         | 2         | 1.16%   |
| Row Of Chips | 1         | 0.58%   |
| Unknown      | 1         | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 70        | 37.23%  |
| 8192  | 66        | 35.11%  |
| 2048  | 29        | 15.43%  |
| 16384 | 16        | 8.51%   |
| 1024  | 4         | 2.13%   |
| 32768 | 3         | 1.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 60        | 33.33%  |
| 1333    | 37        | 20.56%  |
| 2400    | 15        | 8.33%   |
| 2667    | 14        | 7.78%   |
| 2133    | 14        | 7.78%   |
| 3200    | 8         | 4.44%   |
| 800     | 5         | 2.78%   |
| 667     | 5         | 2.78%   |
| 2666    | 4         | 2.22%   |
| 1867    | 3         | 1.67%   |
| 1334    | 3         | 1.67%   |
| 1866    | 2         | 1.11%   |
| 1067    | 2         | 1.11%   |
| Unknown | 2         | 1.11%   |
| 3400    | 1         | 0.56%   |
| 3000    | 1         | 0.56%   |
| 2933    | 1         | 0.56%   |
| 2134    | 1         | 0.56%   |
| 1777    | 1         | 0.56%   |
| 533     | 1         | 0.56%   |

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

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 28.13%  |
| Realtek Semiconductor                  | 6         | 18.75%  |
| Lite-On Technology                     | 3         | 9.38%   |
| Apple                                  | 3         | 9.38%   |
| Microdia                               | 2         | 6.25%   |
| IMC Networks                           | 2         | 6.25%   |
| Acer                                   | 2         | 6.25%   |
| Sunplus Innovation Technology          | 1         | 3.13%   |
| Sonix Technology                       | 1         | 3.13%   |
| Ricoh                                  | 1         | 3.13%   |
| Logitech                               | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek USB Camera                            | 2         | 6.25%   |
| Realtek Integrated_Webcam_HD                  | 2         | 6.25%   |
| Lite-On Integrated Camera                     | 2         | 6.25%   |
| Chicony Integrated Camera                     | 2         | 6.25%   |
| Chicony HD Webcam                             | 2         | 6.25%   |
| Apple FaceTime HD Camera                      | 2         | 6.25%   |
| Sunplus Laptop Integrated Webcam HD           | 1         | 3.13%   |
| Sonix FHD Webcam                              | 1         | 3.13%   |
| Ricoh USB2.0 Camera                           | 1         | 3.13%   |
| Realtek Lenovo EasyCamera                     | 1         | 3.13%   |
| Realtek Integrated Webcam HD                  | 1         | 3.13%   |
| Microdia Integrated_Webcam_HD                 | 1         | 3.13%   |
| Microdia Dell Integrated HD Webcam            | 1         | 3.13%   |
| Logitech HD Pro Webcam C920                   | 1         | 3.13%   |
| Lite-On TOSHIBA Web Camera - HD               | 1         | 3.13%   |
| IMC Networks Integrated Camera                | 1         | 3.13%   |
| IMC Networks EasyCamera                       | 1         | 3.13%   |
| Chicony thinkpad t430s camera                 | 1         | 3.13%   |
| Chicony Integrated Camera (1280x720@30)       | 1         | 3.13%   |
| Chicony HP Webcam [2 MP]                      | 1         | 3.13%   |
| Chicony HD WebCam (Acer)                      | 1         | 3.13%   |
| Chicony Chicony USB2.0 Camera                 | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 1         | 3.13%   |
| Apple FaceTime HD Camera (Built-in)           | 1         | 3.13%   |
| Acer Lenovo EasyCamera                        | 1         | 3.13%   |
| Acer Integrated Camera                        | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 2         | 28.57%  |
| Synaptics          | 2         | 28.57%  |
| AuthenTec          | 2         | 28.57%  |
| STMicroelectronics | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 14.29%  |
| Validity Sensors Synaptics WBDI                   | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader             | 1         | 14.29%  |
| AuthenTec AES2810                                 | 1         | 14.29%  |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 14.29%  |

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
| 1     | 89        | 43%     |
| 0     | 71        | 34.3%   |
| 2     | 31        | 14.98%  |
| 3     | 11        | 5.31%   |
| 4     | 5         | 2.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 115       | 63.89%  |
| Net/wireless             | 19        | 10.56%  |
| Bluetooth                | 13        | 7.22%   |
| Card reader              | 11        | 6.11%   |
| Fingerprint reader       | 6         | 3.33%   |
| Firewire controller      | 5         | 2.78%   |
| Net/ethernet             | 3         | 1.67%   |
| Graphics card            | 3         | 1.67%   |
| Storage/ata              | 2         | 1.11%   |
| Storage/raid             | 1         | 0.56%   |
| Storage                  | 1         | 0.56%   |
| Sound                    | 1         | 0.56%   |

