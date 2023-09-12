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

Total: 307

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| GVC           | DR 738                      | Desktop     | [21b338db1b](https://bsd-hardware.info/?probe=21b338db1b) | Apr 30, 2023 |
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
| GVC           | DR 738                      | Desktop     | [88455ed9e7](https://bsd-hardware.info/?probe=88455ed9e7) | Mar 18, 2023 |
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
| Medion        | S4401 MD61519               | Convertible | [6cd6b15a60](https://bsd-hardware.info/?probe=6cd6b15a60) | Feb 12, 2023 |
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
| HP            | 213D A01                    | Desktop     | [1d30039961](https://bsd-hardware.info/?probe=1d30039961) | Jan 11, 2023 |
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
| GVC           | DR 738                      | Desktop     | [ea08102a81](https://bsd-hardware.info/?probe=ea08102a81) | Aug 06, 2022 |
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
| GVC           | DR 738                      | Desktop     | [938866fb80](https://bsd-hardware.info/?probe=938866fb80) | May 21, 2022 |
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
| GVC           | DR 738                      | Desktop     | [3e8940224f](https://bsd-hardware.info/?probe=3e8940224f) | Jun 13, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [99ce3d3fc6](https://bsd-hardware.info/?probe=99ce3d3fc6) | May 29, 2021 |
| GVC           | DR 738                      | Desktop     | [9ff0fb7df4](https://bsd-hardware.info/?probe=9ff0fb7df4) | May 01, 2021 |
| GVC           | DR 738                      | Desktop     | [2acd0848c8](https://bsd-hardware.info/?probe=2acd0848c8) | May 01, 2021 |
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

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| helloSystem 0.7.0 | 27        | 11.11%  |
| helloSystem 0.8.1 | 16        | 6.58%   |
| helloSystem 0.8.0 | 13        | 5.35%   |
| FreeBSD 13.1      | 10        | 4.12%   |
| helloSystem 0.4.0 | 9         | 3.7%    |
| helloSystem 0.5.0 | 8         | 3.29%   |
| OPNsense 22.1     | 7         | 2.88%   |
| OpenBSD 6.8       | 6         | 2.47%   |
| helloSystem 0.6.0 | 6         | 2.47%   |
| OPNsense 22.7.10  | 5         | 2.06%   |
| OpenBSD 7.2       | 5         | 2.06%   |
| OPNsense 21.7.7   | 4         | 1.65%   |
| OpenBSD 7.1       | 4         | 1.65%   |
| GhostBSD 20.04.02 | 4         | 1.65%   |
| FreeBSD 13.2      | 4         | 1.65%   |
| OPNsense 23.1     | 3         | 1.23%   |
| OPNsense 22.7.6   | 3         | 1.23%   |
| OPNsense 22.7.11  | 3         | 1.23%   |
| OPNsense 21.7.5   | 3         | 1.23%   |
| OPNsense 21.7.1   | 3         | 1.23%   |
| helloSystem 0.8.2 | 3         | 1.23%   |
| FreeBSD 13.0      | 3         | 1.23%   |
| OPNsense 23.7.2   | 2         | 0.82%   |
| OPNsense 23.1.7   | 2         | 0.82%   |
| OPNsense 23.1.11  | 2         | 0.82%   |
| OPNsense 22.7.9   | 2         | 0.82%   |
| OPNsense 22.7.8   | 2         | 0.82%   |
| OPNsense 22.7.4   | 2         | 0.82%   |
| OPNsense 22.7.2   | 2         | 0.82%   |
| OPNsense 22.7.1   | 2         | 0.82%   |
| OPNsense 22.1.5   | 2         | 0.82%   |
| OPNsense 22.1.3   | 2         | 0.82%   |
| OPNsense 22.1.1   | 2         | 0.82%   |
| OPNsense 21.7.6   | 2         | 0.82%   |
| OPNsense 21.7.3   | 2         | 0.82%   |
| OPNsense 21.1.7   | 2         | 0.82%   |
| OPNsense 21.1.6   | 2         | 0.82%   |
| OPNsense 21.1.4   | 2         | 0.82%   |
| OPNsense 21.1.3   | 2         | 0.82%   |
| OPNsense 21.1     | 2         | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| helloSystem | 71        | 36.6%   |
| OPNsense    | 59        | 30.41%  |
| FreeBSD     | 33        | 17.01%  |
| OpenBSD     | 15        | 7.73%   |
| GhostBSD    | 8         | 4.12%   |
| NomadBSD    | 2         | 1.03%   |
| NetBSD      | 2         | 1.03%   |
| FuguIta     | 2         | 1.03%   |
| TrueNAS     | 1         | 0.52%   |
| DragonFly   | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 186       | 97.89%  |
| i386  | 2         | 1.05%   |
| arm64 | 2         | 1.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 81        | 41.54%  |
| Console      | 73        | 37.44%  |
| MATE         | 11        | 5.64%   |
| fvwm         | 7         | 3.59%   |
| XFCE         | 5         | 2.56%   |
| TWM          | 4         | 2.05%   |
| KDE5         | 4         | 2.05%   |
| Openbox      | 3         | 1.54%   |
| i3           | 3         | 1.54%   |
| GNOME        | 3         | 1.54%   |
| Fluxbox      | 1         | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 118       | 61.78%  |
| Console | 71        | 37.17%  |
| Wayland | 2         | 1.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 94        | 48.21%  |
| SLiM    | 77        | 39.49%  |
| LightDM | 11        | 5.64%   |
| SDDM    | 6         | 3.08%   |
| GDM     | 4         | 2.05%   |
| XDM     | 2         | 1.03%   |
| Ly      | 1         | 0.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 83        | 42.13%  |
| en_US            | 48        | 24.37%  |
| es_ES            | 30        | 15.23%  |
| C                | 23        | 11.68%  |
| es               | 5         | 2.54%   |
| fr_FR            | 3         | 1.52%   |
| zh_CN            | 1         | 0.51%   |
| ru_RU            | 1         | 0.51%   |
| fr               | 1         | 0.51%   |
| es_ES.ISO8859-15 | 1         | 0.51%   |
| de_DE            | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 160       | 83.77%  |
| BIOS | 31        | 16.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 94        | 47.24%  |
| Ufs     | 52        | 26.13%  |
| Cd9660  | 34        | 17.09%  |
| Ffs     | 17        | 8.54%   |
| Hammer2 | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 167       | 87.43%  |
| MBR     | 21        | 10.99%  |
| Unknown | 3         | 1.57%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Hewlett-Packard            | 28        | 14.74%  |
| ASUSTek Computer           | 28        | 14.74%  |
| Lenovo                     | 21        | 11.05%  |
| Dell                       | 12        | 6.32%   |
| AMI                        | 10        | 5.26%   |
| Gigabyte Technology        | 9         | 4.74%   |
| Unknown                    | 9         | 4.74%   |
| Acer                       | 8         | 4.21%   |
| MSI                        | 6         | 3.16%   |
| Apple                      | 6         | 3.16%   |
| Intel                      | 5         | 2.63%   |
| Fujitsu                    | 5         | 2.63%   |
| ASRock                     | 5         | 2.63%   |
| YANYU                      | 4         | 2.11%   |
| Medion                     | 3         | 1.58%   |
| Techvision                 | 2         | 1.05%   |
| SLIMBOOK                   | 2         | 1.05%   |
| Samsung Electronics        | 2         | 1.05%   |
| OEM                        | 2         | 1.05%   |
| ECS                        | 2         | 1.05%   |
| ZOTAC                      | 1         | 0.53%   |
| Wistron                    | 1         | 0.53%   |
| TWINHEAD                   | 1         | 0.53%   |
| TUXEDO                     | 1         | 0.53%   |
| Toshiba                    | 1         | 0.53%   |
| Sony                       | 1         | 0.53%   |
| ShenZhen MinWin Technology | 1         | 0.53%   |
| ReachingTech               | 1         | 0.53%   |
| Razer                      | 1         | 0.53%   |
| Raspberry Pi Foundation    | 1         | 0.53%   |
| Pegatron                   | 1         | 0.53%   |
| PC Engines                 | 1         | 0.53%   |
| Packard Bell               | 1         | 0.53%   |
| MW                         | 1         | 0.53%   |
| GVC                        | 1         | 0.53%   |
| Fujitsu Siemens            | 1         | 0.53%   |
| eMachines                  | 1         | 0.53%   |
| Chuwi                      | 1         | 0.53%   |
| BESSTAR Tech               | 1         | 0.53%   |
| AZW                        | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 10        | 5.26%   |
| AMI Aptio CRB                       | 9         | 4.74%   |
| Dell Latitude 7390                  | 3         | 1.58%   |
| ASUS All Series                     | 3         | 1.58%   |
| YANYU R250                          | 2         | 1.05%   |
| YANYU H67SL                         | 2         | 1.05%   |
| Techvision TVI7309X                 | 2         | 1.05%   |
| HP t620 PLUS Quad Core TC           | 2         | 1.05%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 2         | 1.05%   |
| HP EliteDesk 700 G1 SFF             | 2         | 1.05%   |
| ASUS PRIME A320M-K                  | 2         | 1.05%   |
| ASUS K55VD                          | 2         | 1.05%   |
| ASRock N3700-ITX                    | 2         | 1.05%   |
| ZOTAC ZBOXNANO-AQ01                 | 1         | 0.53%   |
| Wistron ProLiant ML110 G6           | 1         | 0.53%   |
| TWINHEAD U12CT                      | 1         | 0.53%   |
| TUXEDO Aura 15 Gen1                 | 1         | 0.53%   |
| Toshiba Satellite A300              | 1         | 0.53%   |
| Sony SVE1511C5E                     | 1         | 0.53%   |
| SLIMBOOK PROX-AMD5                  | 1         | 0.53%   |
| SLIMBOOK ESSENTIAL-15-11            | 1         | 0.53%   |
| ShenZhen MinWin 3865U-6L            | 1         | 0.53%   |
| Samsung Galaxy Book 12              | 1         | 0.53%   |
| Samsung 530U3C/530U4C/532U3C        | 1         | 0.53%   |
| ReachingTech DreamQuest Pro 2022    | 1         | 0.53%   |
| Razer Blade Stealth                 | 1         | 0.53%   |
| RPi Raspberry Pi                    | 1         | 0.53%   |
| Pegatron Elite 7500 Series MT       | 1         | 0.53%   |
| PC Engines APU2                     | 1         | 0.53%   |
| Packard Bell DOT S                  | 1         | 0.53%   |
| OEM NU93 Series                     | 1         | 0.53%   |
| OEM AR-B5800                        | 1         | 0.53%   |
| MW GMLK-2_5G4L                      | 1         | 0.53%   |
| MSI MS-7C91                         | 1         | 0.53%   |
| MSI MS-7C52                         | 1         | 0.53%   |
| MSI MS-7C51                         | 1         | 0.53%   |
| MSI MS-7C09                         | 1         | 0.53%   |
| MSI MS-7B86                         | 1         | 0.53%   |
| MSI GE75 Raider 10SGS               | 1         | 0.53%   |
| Medion S4401 MD61519                | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 11        | 5.79%   |
| Unknown                  | 10        | 5.26%   |
| AMI Aptio                | 9         | 4.74%   |
| ASUS PRIME               | 6         | 3.16%   |
| Acer Aspire              | 6         | 3.16%   |
| Lenovo ThinkCentre       | 5         | 2.63%   |
| HP Pavilion              | 5         | 2.63%   |
| HP EliteDesk             | 4         | 2.11%   |
| HP Compaq                | 4         | 2.11%   |
| Dell Latitude            | 4         | 2.11%   |
| HP ProBook               | 3         | 1.58%   |
| Fujitsu ESPRIMO          | 3         | 1.58%   |
| ASUS TUF                 | 3         | 1.58%   |
| ASUS All                 | 3         | 1.58%   |
| YANYU R250               | 2         | 1.05%   |
| YANYU H67SL              | 2         | 1.05%   |
| Techvision TVI7309X      | 2         | 1.05%   |
| HP t620                  | 2         | 1.05%   |
| HP ProLiant              | 2         | 1.05%   |
| HP OMEN                  | 2         | 1.05%   |
| HP Laptop                | 2         | 1.05%   |
| Dell Precision           | 2         | 1.05%   |
| Dell PowerEdge           | 2         | 1.05%   |
| Dell OptiPlex            | 2         | 1.05%   |
| ASUS M5A78L-M            | 2         | 1.05%   |
| ASUS K55VD               | 2         | 1.05%   |
| ASRock N3700-ITX         | 2         | 1.05%   |
| Apple MacBook5           | 2         | 1.05%   |
| ZOTAC ZBOXNANO-AQ01      | 1         | 0.53%   |
| Wistron ProLiant         | 1         | 0.53%   |
| TWINHEAD U12CT           | 1         | 0.53%   |
| TUXEDO Aura              | 1         | 0.53%   |
| Toshiba Satellite        | 1         | 0.53%   |
| Sony SVE1511C5E          | 1         | 0.53%   |
| SLIMBOOK PROX-AMD5       | 1         | 0.53%   |
| SLIMBOOK ESSENTIAL-15-11 | 1         | 0.53%   |
| ShenZhen MinWin 3865U-6L | 1         | 0.53%   |
| Samsung Galaxy           | 1         | 0.53%   |
| Samsung 530U3C           | 1         | 0.53%   |
| ReachingTech DreamQuest  | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 22        | 11.58%  |
| 2014    | 22        | 11.58%  |
| 2020    | 21        | 11.05%  |
| 2018    | 19        | 10%     |
| 2022    | 13        | 6.84%   |
| 2016    | 12        | 6.32%   |
| 2017    | 10        | 5.26%   |
| 2011    | 10        | 5.26%   |
| 2013    | 9         | 4.74%   |
| 2012    | 9         | 4.74%   |
| 2021    | 8         | 4.21%   |
| 2015    | 8         | 4.21%   |
| 2009    | 8         | 4.21%   |
| 2008    | 8         | 4.21%   |
| 2010    | 6         | 3.16%   |
| Unknown | 2         | 1.05%   |
| 2007    | 1         | 0.53%   |
| 2006    | 1         | 0.53%   |
| 2003    | 1         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 101       | 53.16%  |
| Notebook       | 67        | 35.26%  |
| Mini pc        | 14        | 7.37%   |
| Server         | 4         | 2.11%   |
| System on chip | 1         | 0.53%   |
| Tablet         | 1         | 0.53%   |
| Convertible    | 1         | 0.53%   |
| All in one     | 1         | 0.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 189       | 99.47%  |
| Yes  | 1         | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 80        | 41.03%  |
| 4.01-8.0    | 39        | 20%     |
| 16.01-24.0  | 38        | 19.49%  |
| 32.01-64.0  | 18        | 9.23%   |
| 3.01-4.0    | 6         | 3.08%   |
| 64.01-256.0 | 5         | 2.56%   |
| 2.01-3.0    | 3         | 1.54%   |
| 1.01-2.0    | 3         | 1.54%   |
| 24.01-32.0  | 1         | 0.51%   |
| 0.51-1.0    | 1         | 0.51%   |
| 0.01-0.5    | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 102       | 51.52%  |
| 0.51-1.0   | 61        | 30.81%  |
| 1.01-2.0   | 19        | 9.6%    |
| 3.01-4.0   | 4         | 2.02%   |
| 2.01-3.0   | 4         | 2.02%   |
| 0          | 3         | 1.52%   |
| 4.01-8.0   | 2         | 1.01%   |
| Unknown    | 2         | 1.01%   |
| 24.01-32.0 | 1         | 0.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 115       | 58.67%  |
| 2      | 38        | 19.39%  |
| 0      | 14        | 7.14%   |
| 4      | 10        | 5.1%    |
| 3      | 10        | 5.1%    |
| 5      | 6         | 3.06%   |
| 6      | 2         | 1.02%   |
| 7      | 1         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 145       | 75.92%  |
| Yes       | 46        | 24.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 179       | 94.21%  |
| No        | 11        | 5.79%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 51.31%  |
| No        | 93        | 48.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 59.9%   |
| Yes       | 77        | 40.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Spain   | 190       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Madrid                        | 40        | 18.18%  |
| Barcelona                     | 13        | 5.91%   |
| Valencia                      | 11        | 5%      |
| Ourense                       | 4         | 1.82%   |
| Málaga                       | 4         | 1.82%   |
| Ibiza Town                    | 4         | 1.82%   |
| Terrassa                      | 3         | 1.36%   |
| Seville                       | 3         | 1.36%   |
| San SebastiÃ¡n de los Reyes | 3         | 1.36%   |
| Paterna                       | 3         | 1.36%   |
| Navalcarnero                  | 3         | 1.36%   |
| Alcobendas                    | 3         | 1.36%   |
| Zaragoza                      | 2         | 0.91%   |
| Vitoria-Gasteiz               | 2         | 0.91%   |
| Vigo                          | 2         | 0.91%   |
| Tarragona                     | 2         | 0.91%   |
| Sedavi                        | 2         | 0.91%   |
| Palma                         | 2         | 0.91%   |
| Oviedo                        | 2         | 0.91%   |
| LogroÃ±o                    | 2         | 0.91%   |
| GibraleГіn                  | 2         | 0.91%   |
| Elche                         | 2         | 0.91%   |
| Coria del RÃ­o              | 2         | 0.91%   |
| Castilleja de la Cuesta       | 2         | 0.91%   |
| Bilbao                        | 2         | 0.91%   |
| Barakaldo                     | 2         | 0.91%   |
| Albacete                      | 2         | 0.91%   |
| Zarautz                       | 1         | 0.45%   |
| VГ©lez-MГЎlaga            | 1         | 0.45%   |
| Villena                       | 1         | 0.45%   |
| Villapresente                 | 1         | 0.45%   |
| Villanueva de la Canada       | 1         | 0.45%   |
| Viladecans                    | 1         | 0.45%   |
| Valladolid                    | 1         | 0.45%   |
| Valderrobres                  | 1         | 0.45%   |
| Urnieta                       | 1         | 0.45%   |
| Tudela de Duero               | 1         | 0.45%   |
| Tres Cantos                   | 1         | 0.45%   |
| Trebujena                     | 1         | 0.45%   |
| Torre del Mar                 | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                                 | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC                                    | 40        | 60     | 15.69%  |
| Samsung Electronics                    | 36        | 60     | 14.12%  |
| Seagate                                | 32        | 54     | 12.55%  |
| Kingston                               | 31        | 56     | 12.16%  |
| Crucial                                | 15        | 18     | 5.88%   |
| Toshiba                                | 12        | 16     | 4.71%   |
| Hitachi                                | 10        | 10     | 3.92%   |
| SanDisk                                | 7         | 7      | 2.75%   |
| NVMe                                   | 6         | 9      | 2.35%   |
| Transcend                              | 5         | 6      | 1.96%   |
| China                                  | 5         | 9      | 1.96%   |
| Intel                                  | 4         | 6      | 1.57%   |
| FORESEE                                | 4         | 4      | 1.57%   |
| Micron Technology                      | 3         | 3      | 1.18%   |
| LITEON                                 | 3         | 3      | 1.18%   |
| HGST                                   | 3         | 3      | 1.18%   |
| Corsair                                | 3         | 3      | 1.18%   |
| TCSUNBOW                               | 2         | 4      | 0.78%   |
| Product:              USB Flash Memory | 2         | 2      | 0.78%   |
| Phison                                 | 2         | 2      | 0.78%   |
| OCZ                                    | 2         | 2      | 0.78%   |
| LITEONIT                               | 2         | 2      | 0.78%   |
| Kston                                  | 2         | 3      | 0.78%   |
| Hoodisk                                | 2         | 2      | 0.78%   |
| Fujitsu                                | 2         | 2      | 0.78%   |
| XrayDisk                               | 1         | 1      | 0.39%   |
| Union Memory                           | 1         | 1      | 0.39%   |
| SK hynix                               | 1         | 1      | 0.39%   |
| Silicon Motion                         | 1         | 1      | 0.39%   |
| ShiJi                                  | 1         | 1      | 0.39%   |
| PNY                                    | 1         | 1      | 0.39%   |
| Nfortec                                | 1         | 1      | 0.39%   |
| Netac                                  | 1         | 1      | 0.39%   |
| Lexar                                  | 1         | 1      | 0.39%   |
| KIOXIA-EXCERIA                         | 1         | 1      | 0.39%   |
| KIOXIA                                 | 1         | 1      | 0.39%   |
| KingSpec                               | 1         | 1      | 0.39%   |
| Intenso                                | 1         | 5      | 0.39%   |
| Innodisk                               | 1         | 1      | 0.39%   |
| Fanxiang                               | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB                                  | 8         | 2.78%   |
| Seagate ST500DM002-1BD142 500GB                              | 5         | 1.74%   |
| Seagate ST1000DM010-2EP102 1TB                               | 4         | 1.39%   |
| Kingston SUV500MS120G 120GB                                  | 4         | 1.39%   |
| Samsung SSD 860 EVO 500GB                                    | 3         | 1.04%   |
| Samsung SSD 850 EVO 500GB                                    | 3         | 1.04%   |
| Samsung SSD 850 EVO 250GB                                    | 3         | 1.04%   |
| Kingston SV300S37A120G 120GB                                 | 3         | 1.04%   |
| Kingston SUV400S37240G 240GB                                 | 3         | 1.04%   |
| Kingston SA400S37480G 480GB                                  | 3         | 1.04%   |
| Kingston SA400S37120G 120GB                                  | 3         | 1.04%   |
| Crucial CT240BX500SSD1 240GB                                 | 3         | 1.04%   |
| WDC WDS500G2B0A-00SM50 500GB                                 | 2         | 0.69%   |
| WDC WDS500G1B0A-00H9H0 500GB                                 | 2         | 0.69%   |
| WDC WDS250G1B0A-00H9H0 250GB                                 | 2         | 0.69%   |
| WDC WD20EARX-00PASB0 2TB                                     | 2         | 0.69%   |
| WDC WD10EZEX-60WN4A0 1TB                                     | 2         | 0.69%   |
| Transcend TS120GMTS420S 120GB                                | 2         | 0.69%   |
| Toshiba TR200 240GB                                          | 2         | 0.69%   |
| Seagate ST9500325AS 500GB                                    | 2         | 0.69%   |
| Seagate ST500LM021-1KJ152 500GB                              | 2         | 0.69%   |
| Seagate ST3500418AS 500GB                                    | 2         | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                           | 2         | 0.69%   |
| Seagate ST1000DM003-9YN162 1TB                               | 2         | 0.69%   |
| Seagate ST1000DM003-1ER162 1TB                               | 2         | 0.69%   |
| Samsung HD103SI 1TB                                          | 2         | 0.69%   |
| Product:              USB Flash Memory USB Flash Memory 16GB | 2         | 0.69%   |
| NVMe Samsung SSD 980 500GB                                   | 2         | 0.69%   |
| LITEON CV8-8E128-HP 128GB                                    | 2         | 0.69%   |
| Kingston SV300S37A240G 240GB                                 | 2         | 0.69%   |
| Hitachi HTS545050A7E380 500GB                                | 2         | 0.69%   |
| FORESEE S326M256G 256GB                                      | 2         | 0.69%   |
| Crucial CT500MX500SSD1 500GB                                 | 2         | 0.69%   |
| Crucial CT480BX500SSD1 480GB                                 | 2         | 0.69%   |
| Crucial CT250MX500SSD1 250GB                                 | 2         | 0.69%   |
| XrayDisk SSD 240GB                                           | 1         | 0.35%   |
| WDC WDS500G3XHC-00SJG0 500GB                                 | 1         | 0.35%   |
| WDC WDS500G2B0B-00YS70 500GB                                 | 1         | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB                                 | 1         | 0.35%   |
| WDC WDS240G1G0A-00SS50 240GB                                 | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Seagate                                | 31        | 50     | 32.29%  |
| WDC                                    | 28        | 42     | 29.17%  |
| Hitachi                                | 10        | 10     | 10.42%  |
| Toshiba                                | 8         | 10     | 8.33%   |
| Samsung Electronics                    | 8         | 11     | 8.33%   |
| NVMe                                   | 3         | 5      | 3.13%   |
| HGST                                   | 3         | 3      | 3.13%   |
| Product:              USB Flash Memory | 2         | 2      | 2.08%   |
| Fujitsu                                | 2         | 2      | 2.08%   |
| Apple                                  | 1         | 1      | 1.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 29        | 54     | 23.02%  |
| Samsung Electronics | 21        | 30     | 16.67%  |
| Crucial             | 12        | 15     | 9.52%   |
| WDC                 | 8         | 13     | 6.35%   |
| SanDisk             | 7         | 7      | 5.56%   |
| Transcend           | 5         | 6      | 3.97%   |
| China               | 5         | 9      | 3.97%   |
| Toshiba             | 4         | 4      | 3.17%   |
| FORESEE             | 4         | 4      | 3.17%   |
| LITEON              | 3         | 3      | 2.38%   |
| Intel               | 3         | 5      | 2.38%   |
| TCSUNBOW            | 2         | 4      | 1.59%   |
| OCZ                 | 2         | 2      | 1.59%   |
| NVMe                | 2         | 2      | 1.59%   |
| LITEONIT            | 2         | 2      | 1.59%   |
| Kston               | 2         | 3      | 1.59%   |
| Hoodisk             | 2         | 2      | 1.59%   |
| XrayDisk            | 1         | 1      | 0.79%   |
| ShiJi               | 1         | 1      | 0.79%   |
| Seagate             | 1         | 1      | 0.79%   |
| PNY                 | 1         | 1      | 0.79%   |
| Netac               | 1         | 1      | 0.79%   |
| Micron Technology   | 1         | 1      | 0.79%   |
| KingSpec            | 1         | 1      | 0.79%   |
| Intenso             | 1         | 5      | 0.79%   |
| Innodisk            | 1         | 1      | 0.79%   |
| EMTEC               | 1         | 1      | 0.79%   |
| BR                  | 1         | 3      | 0.79%   |
| BAITITON            | 1         | 1      | 0.79%   |
| Apacer              | 1         | 1      | 0.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 112       | 184    | 49.78%  |
| HDD  | 77        | 136    | 34.22%  |
| NVMe | 36        | 52     | 16%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 158       | 320    | 81.44%  |
| NVMe | 36        | 52     | 18.56%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 139       | 243    | 73.94%  |
| 0.51-1.0   | 34        | 54     | 18.09%  |
| 1.01-2.0   | 9         | 15     | 4.79%   |
| 4.01-10.0  | 4         | 6      | 2.13%   |
| 3.01-4.0   | 1         | 1      | 0.53%   |
| 2.01-3.0   | 1         | 1      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 65        | 32.66%  |
| 101-250    | 57        | 28.64%  |
| 251-500    | 30        | 15.08%  |
| 21-50      | 16        | 8.04%   |
| 51-100     | 15        | 7.54%   |
| 501-1000   | 12        | 6.03%   |
| 1001-2000  | 2         | 1.01%   |
| 2001-3000  | 1         | 0.5%    |
| Unknown    | 1         | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 175       | 88.83%  |
| 21-50    | 11        | 5.58%   |
| 51-100   | 6         | 3.05%   |
| 251-500  | 3         | 1.52%   |
| 501-1000 | 1         | 0.51%   |
| Unknown  | 1         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                 | 2         | 2      | 4.35%   |
| LITEON CV8-8E128-HP 128GB                       | 2         | 2      | 4.35%   |
| Hitachi HTS545050A7E380 500GB                   | 2         | 2      | 4.35%   |
| WDC WDS240G2G0A-00JH30 240GB                    | 1         | 2      | 2.17%   |
| WDC WD6400AAKS-22A7B0 640GB                     | 1         | 1      | 2.17%   |
| WDC WD5000AAKX-22ERMA0 500GB                    | 1         | 1      | 2.17%   |
| WDC WD2500BEVT-35A23T0 250GB                    | 1         | 1      | 2.17%   |
| WDC WD1600AAJS-00WAA0 160GB                     | 1         | 1      | 2.17%   |
| WDC WD10EZEX-21M2NA0 1TB                        | 1         | 1      | 2.17%   |
| Toshiba MQ01UBD100 1TB                          | 1         | 2      | 2.17%   |
| Toshiba MK1229GSG 120GB                         | 1         | 1      | 2.17%   |
| Toshiba MK1059GSM 1TB                           | 1         | 1      | 2.17%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 1      | 2.17%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 2.17%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 2.17%   |
| Seagate ST3500418AS 500GB                       | 1         | 1      | 2.17%   |
| Seagate ST3500413AS 500GB                       | 1         | 3      | 2.17%   |
| Seagate ST3160215AS 160GB                       | 1         | 1      | 2.17%   |
| Seagate ST31000528AS 1TB                        | 1         | 2      | 2.17%   |
| Seagate ST31000333AS 1TB                        | 1         | 1      | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 2.17%   |
| Seagate ST1000DM010-2EP102 1TB                  | 1         | 1      | 2.17%   |
| Seagate ST1000DM003-9YN162 1TB                  | 1         | 1      | 2.17%   |
| Seagate ST1000DM003-1ER162 1TB                  | 1         | 1      | 2.17%   |
| Samsung Electronics HM320JI 320GB               | 1         | 1      | 2.17%   |
| Samsung Electronics HM160HI 160GB               | 1         | 1      | 2.17%   |
| Samsung Electronics HD252HJ 250GB               | 1         | 1      | 2.17%   |
| Samsung Electronics HD103UJ 1TB                 | 1         | 1      | 2.17%   |
| Samsung Electronics HD103SI 1TB                 | 1         | 1      | 2.17%   |
| OCZ AGILITY3 120GB                              | 1         | 1      | 2.17%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 2.17%   |
| Kingston SV300S37A120G 120GB                    | 1         | 1      | 2.17%   |
| Kingston SUV400S37240G 240GB                    | 1         | 3      | 2.17%   |
| Hitachi HTS725050A9A364 500GB                   | 1         | 1      | 2.17%   |
| Hitachi HTS725050A7E630 500GB                   | 1         | 1      | 2.17%   |
| Hitachi HTS543232L9SA00 320GB                   | 1         | 1      | 2.17%   |
| Hitachi HTS542525K9A300 250GB                   | 1         | 1      | 2.17%   |
| Hitachi HTS542516K9SA00 160GB                   | 1         | 1      | 2.17%   |
| Hitachi HDT721010SLA360 1TB                     | 1         | 1      | 2.17%   |
| Hitachi HDP725016GLA380 160GB                   | 1         | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 17     | 26.19%  |
| Hitachi             | 9         | 9      | 21.43%  |
| WDC                 | 6         | 7      | 14.29%  |
| Samsung Electronics | 4         | 5      | 9.52%   |
| Toshiba             | 3         | 4      | 7.14%   |
| LITEON              | 2         | 2      | 4.76%   |
| Kingston            | 2         | 4      | 4.76%   |
| OCZ                 | 1         | 1      | 2.38%   |
| Micron Technology   | 1         | 1      | 2.38%   |
| HGST                | 1         | 1      | 2.38%   |
| Fujitsu             | 1         | 1      | 2.38%   |
| Apple               | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 17     | 31.43%  |
| Hitachi             | 9         | 9      | 25.71%  |
| WDC                 | 5         | 5      | 14.29%  |
| Samsung Electronics | 4         | 5      | 11.43%  |
| Toshiba             | 3         | 4      | 8.57%   |
| HGST                | 1         | 1      | 2.86%   |
| Fujitsu             | 1         | 1      | 2.86%   |
| Apple               | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 43     | 82.05%  |
| SSD  | 7         | 10     | 17.95%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model              | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| SanDisk pSSD 256GB | 1         | 1      | 100%    |

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
| Works    | 151       | 305    | 76.26%  |
| Malfunc  | 39        | 53     | 19.7%   |
| Detected | 7         | 13     | 3.54%   |
| Failed   | 1         | 1      | 0.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 137       | 59.57%  |
| AMD                          | 31        | 13.48%  |
| Samsung Electronics          | 12        | 5.22%   |
| ASMedia Technology           | 8         | 3.48%   |
| Nvidia                       | 7         | 3.04%   |
| Sandisk                      | 6         | 2.61%   |
| Phison Electronics           | 5         | 2.17%   |
| Micron/Crucial Technology    | 4         | 1.74%   |
| Kingston Technology Company  | 3         | 1.3%    |
| SK hynix                     | 2         | 0.87%   |
| Silicon Motion               | 2         | 0.87%   |
| Shenzhen Longsys Electronics | 2         | 0.87%   |
| Micron Technology            | 2         | 0.87%   |
| KIOXIA                       | 2         | 0.87%   |
| VIA Technologies             | 1         | 0.43%   |
| Union Memory (Shenzhen)      | 1         | 0.43%   |
| Toshiba                      | 1         | 0.43%   |
| Seagate Technology           | 1         | 0.43%   |
| Marvell Technology Group     | 1         | 0.43%   |
| JMicron Technology           | 1         | 0.43%   |
| Broadcom / LSI               | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 8.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 21        | 7.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 4.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 3.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 2.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7         | 2.63%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 7         | 2.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 2.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 6         | 2.26%   |
| AMD 400 Series Chipset SATA Controller                                           | 6         | 2.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 1.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.88%   |
| AMD FCH SATA Controller D                                                        | 5         | 1.88%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 1.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.5%    |
| Intel SATA Controller [RAID mode]                                                | 4         | 1.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.5%    |
| Intel Jasper Lake SATA AHCI Controller                                           | 4         | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.5%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 3         | 1.13%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.13%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 1.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 1.13%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2         | 0.75%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 2         | 0.75%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.75%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.75%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 0.75%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.75%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 0.75%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 2         | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 0.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 0.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2         | 0.75%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 155       | 66.81%  |
| NVMe | 40        | 17.24%  |
| IDE  | 25        | 10.78%  |
| RAID | 11        | 4.74%   |
| SAS  | 1         | 0.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 151       | 79.47%  |
| AMD    | 37        | 19.47%  |
| ARM    | 2         | 1.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz        | 6         | 3.16%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 4         | 2.11%   |
| Intel Celeron N5105 @ 2.00GHz            | 4         | 2.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 3         | 1.58%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 3         | 1.58%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 3         | 1.58%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 3         | 1.58%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 3         | 1.58%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 2         | 1.05%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 1.05%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 2         | 1.05%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 2         | 1.05%   |
| Intel Core i5-9500 CPU @ 3.00GHz         | 2         | 1.05%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 2         | 1.05%   |
| Intel Core i5-7400 CPU @ 3.00GHz         | 2         | 1.05%   |
| Intel Core i5-7300U CPU @ 2.60GHz        | 2         | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 2         | 1.05%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 2         | 1.05%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz       | 2         | 1.05%   |
| Intel Core i5-4570T CPU @ 2.90GHz        | 2         | 1.05%   |
| Intel Core i5-2400S CPU @ 2.50GHz        | 2         | 1.05%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 2         | 1.05%   |
| Intel Core i3-3240 CPU @ 3.40GHz         | 2         | 1.05%   |
| Intel Core i3-2120 CPU @ 3.30GHz         | 2         | 1.05%   |
| Intel Core i3-10100 CPU @ 3.60GHz        | 2         | 1.05%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz     | 2         | 1.05%   |
| Intel Celeron CPU N3050 @ 1.60GHz        | 2         | 1.05%   |
| AMD Ryzen 5 4600H with Radeon Graphics   | 2         | 1.05%   |
| AMD Ryzen 5 2600 Six-Core Processor      | 2         | 1.05%   |
| AMD Ryzen 3 1200 Quad-Core Processor     | 2         | 1.05%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 2         | 1.05%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 0.53%   |
| Intel Xeon CPU E5420 @ 2.50GHz           | 1         | 0.53%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz       | 1         | 0.53%   |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz      | 1         | 0.53%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 1         | 0.53%   |
| Intel Pentium II                         | 1         | 0.53%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz   | 1         | 0.53%   |
| Intel Pentium Dual-Core CPU E5300        | 1         | 0.53%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz   | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 22.63%  |
| Intel Celeron           | 24        | 12.63%  |
| Intel Core i7           | 21        | 11.05%  |
| Intel Core i3           | 19        | 10%     |
| Intel Core 2 Duo        | 14        | 7.37%   |
| Intel Xeon              | 8         | 4.21%   |
| AMD Ryzen 7             | 8         | 4.21%   |
| AMD Ryzen 5             | 6         | 3.16%   |
| Other                   | 5         | 2.63%   |
| Intel Pentium           | 4         | 2.11%   |
| Intel Atom              | 4         | 2.11%   |
| AMD Ryzen 3             | 4         | 2.11%   |
| AMD GX                  | 4         | 2.11%   |
| Intel Core 2 Quad       | 3         | 1.58%   |
| AMD FX                  | 3         | 1.58%   |
| AMD A4                  | 3         | 1.58%   |
| ARM Cortex              | 2         | 1.05%   |
| AMD Athlon              | 2         | 1.05%   |
| Intel Pentium Silver    | 1         | 0.53%   |
| Intel Pentium Gold      | 1         | 0.53%   |
| Intel Pentium Dual-Core | 1         | 0.53%   |
| Intel Pentium Dual      | 1         | 0.53%   |
| Intel Genuine           | 1         | 0.53%   |
| Intel Core i9           | 1         | 0.53%   |
| AMD Sempron             | 1         | 0.53%   |
| AMD Ryzen Threadripper  | 1         | 0.53%   |
| AMD E2                  | 1         | 0.53%   |
| AMD E1                  | 1         | 0.53%   |
| AMD E                   | 1         | 0.53%   |
| AMD Athlon XP           | 1         | 0.53%   |
| AMD A8                  | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 84        | 44.21%  |
| 2       | 56        | 29.47%  |
| Unknown | 15        | 7.89%   |
| 8       | 13        | 6.84%   |
| 12      | 6         | 3.16%   |
| 6       | 6         | 3.16%   |
| 16      | 5         | 2.63%   |
| 1       | 4         | 2.11%   |
| 64      | 1         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 182       | 95.79%  |
| 2       | 5         | 2.63%   |
| Unknown | 3         | 1.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 104       | 54.74%  |
| 2       | 70        | 36.84%  |
| Unknown | 16        | 8.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Haswell         | 25        | 13.16%  |
| KabyLake        | 23        | 12.11%  |
| Silvermont      | 17        | 8.95%   |
| Penryn          | 15        | 7.89%   |
| SandyBridge     | 12        | 6.32%   |
| IvyBridge       | 12        | 6.32%   |
| Zen+            | 9         | 4.74%   |
| Skylake         | 9         | 4.74%   |
| Unknown         | 8         | 4.21%   |
| Zen 2           | 6         | 3.16%   |
| Core            | 6         | 3.16%   |
| CometLake       | 6         | 3.16%   |
| Piledriver      | 5         | 2.63%   |
| Goldmont plus   | 5         | 2.63%   |
| Broadwell       | 5         | 2.63%   |
| Jaguar          | 4         | 2.11%   |
| Zen 3           | 3         | 1.58%   |
| Westmere        | 3         | 1.58%   |
| TigerLake       | 3         | 1.58%   |
| Puma            | 3         | 1.58%   |
| Bonnell         | 2         | 1.05%   |
| Zen             | 1         | 0.53%   |
| P6              | 1         | 0.53%   |
| Nehalem         | 1         | 0.53%   |
| K8 Hammer       | 1         | 0.53%   |
| K8 & K10 hybrid | 1         | 0.53%   |
| K6              | 1         | 0.53%   |
| Goldmont        | 1         | 0.53%   |
| Excavator       | 1         | 0.53%   |
| Bobcat          | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 116       | 57.14%  |
| Nvidia                               | 46        | 22.66%  |
| AMD                                  | 34        | 16.75%  |
| Matrox Electronics Systems           | 6         | 2.96%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 3.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 3.38%   |
| Intel HD Graphics 620                                                                    | 7         | 3.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.9%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 2.42%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.42%   |
| Intel HD Graphics 530                                                                    | 5         | 2.42%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 2.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.93%   |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 1.93%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.93%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3         | 1.45%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.45%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.45%   |
| AMD Renoir                                                                               | 3         | 1.45%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.97%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 0.97%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.97%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 0.97%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 0.97%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 0.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.97%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.97%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.97%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 0.97%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 2         | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 97        | 50.52%  |
| 1 x Nvidia                               | 32        | 16.67%  |
| 1 x AMD                                  | 26        | 13.54%  |
| Intel + Nvidia                           | 9         | 4.69%   |
| 2 x Intel                                | 7         | 3.65%   |
| Other                                    | 5         | 2.6%    |
| 1 x Matrox                               | 5         | 2.6%    |
| Intel + AMD                              | 4         | 2.08%   |
| AMD + Nvidia                             | 3         | 1.56%   |
| 2 x Nvidia                               | 1         | 0.52%   |
| 2 x AMD                                  | 1         | 0.52%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.52%   |
| Nvidia + Matrox                          | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 157       | 81.35%  |
| Proprietary | 25        | 12.95%  |
| Unknown     | 11        | 5.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 163       | 84.02%  |
| 0.01-0.5   | 8         | 4.12%   |
| 1.01-2.0   | 7         | 3.61%   |
| 5.01-6.0   | 4         | 2.06%   |
| 3.01-4.0   | 4         | 2.06%   |
| 2.01-3.0   | 3         | 1.55%   |
| 0.51-1.0   | 3         | 1.55%   |
| 7.01-8.0   | 2         | 1.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BenQ                    | 11        | 12.36%  |
| AU Optronics            | 10        | 11.24%  |
| Chimei Innolux          | 6         | 6.74%   |
| BOE                     | 6         | 6.74%   |
| Samsung Electronics     | 5         | 5.62%   |
| LG Display              | 5         | 5.62%   |
| Lenovo                  | 5         | 5.62%   |
| Goldstar                | 5         | 5.62%   |
| Dell                    | 4         | 4.49%   |
| Chi Mei Optoelectronics | 4         | 4.49%   |
| Apple                   | 4         | 4.49%   |
| AOC                     | 3         | 3.37%   |
| Acer                    | 3         | 3.37%   |
| Philips                 | 2         | 2.25%   |
| Hewlett-Packard         | 2         | 2.25%   |
| Vestel Elektronik       | 1         | 1.12%   |
| Sharp                   | 1         | 1.12%   |
| PANDA                   | 1         | 1.12%   |
| MSI                     | 1         | 1.12%   |
| Microstep               | 1         | 1.12%   |
| Mi                      | 1         | 1.12%   |
| Medion                  | 1         | 1.12%   |
| LGD                     | 1         | 1.12%   |
| LG Philips              | 1         | 1.12%   |
| Lenovo Group Limited    | 1         | 1.12%   |
| Impression              | 1         | 1.12%   |
| Fujitsu Siemens         | 1         | 1.12%   |
| CHD                     | 1         | 1.12%   |
| Ancor Communications    | 1         | 1.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                   | 3         | 3.33%   |
| AU Optronics LCD Monitor AUO462D 1920x1080 290x170mm 13.2-inch       | 3         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch     | 2         | 2.22%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                    | 2         | 2.22%   |
| AOC 2050W AOC2050 1600x900 430x240mm 19.4-inch                       | 2         | 2.22%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch   | 1         | 1.11%   |
| Sharp LCD Monitor SHP144D 3840x2160 280x160mm 12.7-inch              | 1         | 1.11%   |
| Samsung Electronics T22C300 SAM0AB3 1920x1080 480x270mm 21.7-inch    | 1         | 1.11%   |
| Samsung Electronics S27H85x SAM0E0F 2560x1440 600x340mm 27.2-inch    | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch | 1         | 1.11%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 1         | 1.11%   |
| Philips 190S PHL083F 1280x1024 380x300mm 19.1-inch                   | 1         | 1.11%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch              | 1         | 1.11%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                      | 1         | 1.11%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080                          | 1         | 1.11%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                     | 1         | 1.11%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                  | 1         | 1.11%   |
| LGD LCD Monitor 5760x1080                                            | 1         | 1.11%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch         | 1         | 1.11%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch         | 1         | 1.11%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch         | 1         | 1.11%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch         | 1         | 1.11%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 530x300mm 24.0-inch             | 1         | 1.11%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch              | 1         | 1.11%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch              | 1         | 1.11%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch              | 1         | 1.11%   |
| Lenovo Group Limited LCD Monitor C24-25 1920x1080                    | 1         | 1.11%   |
| Lenovo C24-25 LEN66B0 1920x1080 530x300mm 24.0-inch                  | 1         | 1.11%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch               | 1         | 1.11%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 510x290mm 23.1-inch         | 1         | 1.11%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch           | 1         | 1.11%   |
| Goldstar W2242 GSM4B6F 1680x1050 490x320mm 23.0-inch                 | 1         | 1.11%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                 | 1         | 1.11%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch             | 1         | 1.11%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch            | 1         | 1.11%   |
| Goldstar L1715S GSM436F 1280x1024 340x270mm 17.1-inch                | 1         | 1.11%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 38        | 44.19%  |
| 1366x768 (WXGA)    | 17        | 19.77%  |
| 1280x800 (WXGA)    | 8         | 9.3%    |
| 2560x1440 (QHD)    | 4         | 4.65%   |
| 1280x1024 (SXGA)   | 4         | 4.65%   |
| 1600x900 (HD+)     | 3         | 3.49%   |
| 1440x900 (WXGA+)   | 3         | 3.49%   |
| 3840x2160 (4K)     | 2         | 2.33%   |
| 5760x1080          | 1         | 1.16%   |
| 3440x1440          | 1         | 1.16%   |
| 2048x1152          | 1         | 1.16%   |
| 1920x540           | 1         | 1.16%   |
| 1680x1050 (WSXGA+) | 1         | 1.16%   |
| 1024x600           | 1         | 1.16%   |
| Unknown            | 1         | 1.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 22        | 24.72%  |
| 13      | 15        | 16.85%  |
| 24      | 11        | 12.36%  |
| 27      | 7         | 7.87%   |
| 19      | 7         | 7.87%   |
| Unknown | 6         | 6.74%   |
| 21      | 5         | 5.62%   |
| 23      | 4         | 4.49%   |
| 18      | 3         | 3.37%   |
| 12      | 3         | 3.37%   |
| 14      | 2         | 2.25%   |
| 42      | 1         | 1.12%   |
| 34      | 1         | 1.12%   |
| 17      | 1         | 1.12%   |
| 9       | 1         | 1.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 32.95%  |
| 501-600     | 21        | 23.86%  |
| 201-300     | 15        | 17.05%  |
| 401-500     | 11        | 12.5%   |
| Unknown     | 6         | 6.82%   |
| 351-400     | 4         | 4.55%   |
| 701-800     | 1         | 1.14%   |
| 901-1000    | 1         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 61        | 72.62%  |
| 16/10   | 10        | 11.9%   |
| Unknown | 6         | 7.14%   |
| 5/4     | 4         | 4.76%   |
| 3/2     | 2         | 2.38%   |
| 21/9    | 1         | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 20        | 22.99%  |
| 201-250        | 19        | 21.84%  |
| 81-90          | 11        | 12.64%  |
| 301-350        | 7         | 8.05%   |
| 151-200        | 7         | 8.05%   |
| 71-80          | 6         | 6.9%    |
| Unknown        | 6         | 6.9%    |
| 61-70          | 3         | 3.45%   |
| 141-150        | 3         | 3.45%   |
| 101-110        | 2         | 2.3%    |
| 351-500        | 1         | 1.15%   |
| 41-50          | 1         | 1.15%   |
| 501-1000       | 1         | 1.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 29        | 33.72%  |
| 51-100        | 28        | 32.56%  |
| 121-160       | 16        | 18.6%   |
| 161-240       | 6         | 6.98%   |
| Unknown       | 6         | 6.98%   |
| More than 240 | 1         | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 95        | 48.97%  |
| 0     | 92        | 47.42%  |
| 2     | 7         | 3.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 107       | 38.35%  |
| Realtek Semiconductor             | 96        | 34.41%  |
| Broadcom                          | 23        | 8.24%   |
| Qualcomm Atheros                  | 19        | 6.81%   |
| TP-Link                           | 5         | 1.79%   |
| Nvidia                            | 5         | 1.79%   |
| Marvell Technology Group          | 5         | 1.79%   |
| Ralink Technology                 | 3         | 1.08%   |
| Xiaomi                            | 2         | 0.72%   |
| Sierra Wireless                   | 2         | 0.72%   |
| Ralink                            | 2         | 0.72%   |
| IMC Networks                      | 2         | 0.72%   |
| D-Link System                     | 2         | 0.72%   |
| Samsung Electronics               | 1         | 0.36%   |
| Qualcomm Atheros Communications   | 1         | 0.36%   |
| MediaTek                          | 1         | 0.36%   |
| Huawei Technologies               | 1         | 0.36%   |
| Ericsson Business Mobile Networks | 1         | 0.36%   |
| Edimax Technology                 | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 82        | 25.39%  |
| Intel I211 Gigabit Network Connection                             | 12        | 3.72%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 2.79%   |
| Intel 82583V Gigabit Network Connection                           | 7         | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 1.86%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.86%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.55%   |
| Intel Wireless 7265                                               | 5         | 1.55%   |
| Intel Wireless 7260                                               | 5         | 1.55%   |
| Intel I210 Gigabit Network Connection                             | 5         | 1.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.24%   |
| Nvidia MCP79 Ethernet                                             | 4         | 1.24%   |
| Intel Wireless 3165                                               | 4         | 1.24%   |
| Intel I350 Gigabit Network Connection                             | 4         | 1.24%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.93%   |
| Intel Wireless 3160                                               | 3         | 0.93%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.93%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 3         | 0.93%   |
| Intel 82580 Gigabit Network Connection                            | 3         | 0.93%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 3         | 0.93%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.62%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.62%   |
| Sierra Wireless EM7345 4G LTE                                     | 2         | 0.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.62%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.62%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.62%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.62%   |
| Intel Wireless-AC 9260                                            | 2         | 0.62%   |
| Intel WiFi Link 5100                                              | 2         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 43.75%  |
| Broadcom                        | 16        | 14.29%  |
| Realtek Semiconductor           | 14        | 12.5%   |
| Qualcomm Atheros                | 14        | 12.5%   |
| TP-Link                         | 5         | 4.46%   |
| Ralink Technology               | 3         | 2.68%   |
| Sierra Wireless                 | 2         | 1.79%   |
| Ralink                          | 2         | 1.79%   |
| IMC Networks                    | 2         | 1.79%   |
| D-Link System                   | 2         | 1.79%   |
| Qualcomm Atheros Communications | 1         | 0.89%   |
| MediaTek                        | 1         | 0.89%   |
| Edimax Technology               | 1         | 0.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 6         | 5.22%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 4.35%   |
| Intel Wireless 7265                                                        | 5         | 4.35%   |
| Intel Wireless 7260                                                        | 5         | 4.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 4         | 3.48%   |
| Intel Wireless 3165                                                        | 4         | 3.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 2.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3         | 2.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 3         | 2.61%   |
| Intel Wireless 3160                                                        | 3         | 2.61%   |
| Intel Wi-Fi 6 AX201                                                        | 3         | 2.61%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 2.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 3         | 2.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 1.74%   |
| Sierra Wireless EM7345 4G LTE                                              | 2         | 1.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 1.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 2         | 1.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 2         | 1.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 2         | 1.74%   |
| Intel Wireless-AC 9260                                                     | 2         | 1.74%   |
| Intel WiFi Link 5100                                                       | 2         | 1.74%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 2         | 1.74%   |
| Intel Centrino Advanced-N 6235                                             | 2         | 1.74%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                       | 2         | 1.74%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 1.74%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 2         | 1.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                            | 2         | 1.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 1         | 0.87%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1         | 0.87%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 1         | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1         | 0.87%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 0.87%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 1         | 0.87%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                      | 1         | 0.87%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 0.87%   |
| Ralink RT3072 Wireless Adapter                                             | 1         | 0.87%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 0.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 91        | 46.67%  |
| Intel                    | 77        | 39.49%  |
| Broadcom                 | 9         | 4.62%   |
| Qualcomm Atheros         | 5         | 2.56%   |
| Nvidia                   | 5         | 2.56%   |
| Marvell Technology Group | 5         | 2.56%   |
| Xiaomi                   | 2         | 1.03%   |
| Samsung Electronics      | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 82        | 40.2%   |
| Intel I211 Gigabit Network Connection                             | 12        | 5.88%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 4.41%   |
| Intel 82583V Gigabit Network Connection                           | 7         | 3.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 2.94%   |
| Intel I210 Gigabit Network Connection                             | 5         | 2.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 2.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.45%   |
| Nvidia MCP79 Ethernet                                             | 4         | 1.96%   |
| Intel I350 Gigabit Network Connection                             | 4         | 1.96%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 1.96%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 3         | 1.47%   |
| Intel 82580 Gigabit Network Connection                            | 3         | 1.47%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 3         | 1.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.98%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.98%   |
| Intel Ethernet Controller I226-V                                  | 2         | 0.98%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.98%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.98%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.98%   |
| Intel 82576 Gigabit Network Connection                            | 2         | 0.98%   |
| Intel 82575GB Gigabit Network Connection                          | 2         | 0.98%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.98%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.49%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.49%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.49%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.49%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.49%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 0.49%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 179       | 63.7%   |
| WiFi     | 98        | 34.88%  |
| Modem    | 2         | 0.71%   |
| Unknown  | 2         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 152       | 76.38%  |
| WiFi     | 46        | 23.12%  |
| Modem    | 1         | 0.5%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 81        | 42.41%  |
| 1     | 60        | 31.41%  |
| 4     | 14        | 7.33%   |
| 3     | 12        | 6.28%   |
| 5     | 9         | 4.71%   |
| 6     | 7         | 3.66%   |
| 8     | 5         | 2.62%   |
| 0     | 2         | 1.05%   |
| 15    | 1         | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 187       | 97.91%  |
| Yes  | 4         | 2.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 46.84%  |
| Cambridge Silicon Radio         | 9         | 11.39%  |
| Realtek Semiconductor           | 7         | 8.86%   |
| Apple                           | 6         | 7.59%   |
| Qualcomm Atheros Communications | 4         | 5.06%   |
| Broadcom                        | 4         | 5.06%   |
| IMC Networks                    | 3         | 3.8%    |
| Hewlett-Packard                 | 3         | 3.8%    |
| Ralink                          | 2         | 2.53%   |
| Foxconn / Hon Hai               | 2         | 2.53%   |
| ASUSTek Computer                | 2         | 2.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 19        | 23.75%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 9         | 11.25%  |
| Intel AX200 Bluetooth                                       | 6         | 7.5%    |
| Intel AX201 Bluetooth                                       | 5         | 6.25%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 3         | 3.75%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 3         | 3.75%   |
| Apple Bluetooth Host Controller                             | 3         | 3.75%   |
| Realtek Bluetooth Adapter                                   | 2         | 2.5%    |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 2.5%    |
| Ralink RT3290 Bluetooth                                     | 2         | 2.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 2.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2         | 2.5%    |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 2.5%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.25%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.25%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.25%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 1.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.25%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.25%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.25%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 1         | 1.25%   |
| IMC Networks Bluetooth module                               | 1         | 1.25%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.25%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 1.25%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.25%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.25%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.25%   |
| Broadcom 4371 Bluetooth 4.1 Adapter                         | 1         | 1.25%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.25%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 1         | 1.25%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.25%   |
| Apple Broadcom Built-in Bluetooth                           | 1         | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 125       | 57.08%  |
| AMD                                          | 41        | 18.72%  |
| Nvidia                                       | 39        | 17.81%  |
| Cambridge Silicon Radio                      | 2         | 0.91%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.46%   |
| VIA Technologies                             | 1         | 0.46%   |
| Texas Instruments                            | 1         | 0.46%   |
| Logitech                                     | 1         | 0.46%   |
| Lenovo                                       | 1         | 0.46%   |
| Hewlett-Packard                              | 1         | 0.46%   |
| Generalplus Technology                       | 1         | 0.46%   |
| GEMBIRD                                      | 1         | 0.46%   |
| Ensoniq                                      | 1         | 0.46%   |
| Dell                                         | 1         | 0.46%   |
| C-Media Electronics                          | 1         | 0.46%   |
| BEHRINGER International                      | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 6.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 5.47%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 5.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 4.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 3.52%   |
| AMD FCH Azalia Controller                                                                         | 8         | 3.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 2.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 2.73%   |
| Intel 200 Series PCH HD Audio                                                                     | 7         | 2.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 2.34%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.34%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 2.34%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 1.95%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 1.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 1.95%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.56%   |
| Intel Jasper Lake HD Audio                                                                        | 4         | 1.56%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.56%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 1.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.56%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.17%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 1.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.17%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.17%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.78%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 0.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.78%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 39        | 18.48%  |
| Samsung Electronics | 35        | 16.59%  |
| SK hynix            | 25        | 11.85%  |
| Crucial             | 23        | 10.9%   |
| Unknown             | 19        | 9%      |
| Micron Technology   | 19        | 9%      |
| Corsair             | 7         | 3.32%   |
| Ramaxel Technology  | 6         | 2.84%   |
| Nanya Technology    | 5         | 2.37%   |
| Unknown             | 5         | 2.37%   |
| G.Skill             | 4         | 1.9%    |
| Elpida              | 4         | 1.9%    |
| Unknown (0B45)      | 2         | 0.95%   |
| Transcend           | 2         | 0.95%   |
| Hewlett-Packard     | 2         | 0.95%   |
| Goldenmars          | 2         | 0.95%   |
| ASint Technology    | 2         | 0.95%   |
| Apacer              | 2         | 0.95%   |
| A-DATA Technology   | 2         | 0.95%   |
| Wodposit            | 1         | 0.47%   |
| Unknown (ABCD)      | 1         | 0.47%   |
| Toshiba             | 1         | 0.47%   |
| Kimtigo             | 1         | 0.47%   |
| GOODRAM             | 1         | 0.47%   |
| Essencore           | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 5         | 2.13%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 3         | 1.28%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 2         | 0.85%   |
| Unknown (0B45) RAM WPBC26D416SWM-16G 16GB SODIMM DDR4 2667MT/s   | 2         | 0.85%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 0.85%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s             | 2         | 0.85%   |
| Kingston RAM KVR13LS9/4 4GB SODIMM DDR3 1333MT/s                 | 2         | 0.85%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 2         | 0.85%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Crucial RAM CT16G4SFRA266.M8FB 16GB SODIMM DDR4 2667MT/s         | 2         | 0.85%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.85%   |
| Wodposit RAM WPBC26D416SWM-16G 16GB SODIMM DDR4 2667MT/s         | 1         | 0.43%   |
| Unknown RAM WPBH16D316SWA-8G 8GB DIMM DDR3 1600MT/s              | 1         | 0.43%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                        | 1         | 0.43%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.43%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                          | 1         | 0.43%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.43%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 0.43%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR 1066MT/s                         | 1         | 0.43%   |
| Unknown RAM Module 256MB DIMM 333MT/s                            | 1         | 0.43%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.43%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                         | 1         | 0.43%   |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1         | 0.43%   |
| Unknown RAM Module 1GB DIMM 400MT/s                              | 1         | 0.43%   |
| Unknown RAM DDR3 NB 4G 1600 4GB DIMM DDR3 1600MT/s               | 1         | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 1         | 0.43%   |
| Transcend RAM TS1GLK72V6H 8GB DIMM DDR3 1600MT/s                 | 1         | 0.43%   |
| Transcend RAM JM1600KSN-4G 4GB SODIMM DDR3 1600MT/s              | 1         | 0.43%   |
| Toshiba RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s            | 1         | 0.43%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3733MT/s             | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 88        | 50.57%  |
| DDR4    | 60        | 34.48%  |
| DDR2    | 15        | 8.62%   |
| Unknown | 4         | 2.3%    |
| SDRAM   | 2         | 1.15%   |
| LPDDR4  | 2         | 1.15%   |
| LPDDR3  | 2         | 1.15%   |
| DDR     | 1         | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 50.29%  |
| DIMM         | 81        | 46.82%  |
| Row Of Chips | 4         | 2.31%   |
| FB-DIMM      | 1         | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 71        | 36.79%  |
| 8192  | 67        | 34.72%  |
| 2048  | 24        | 12.44%  |
| 16384 | 22        | 11.4%   |
| 1024  | 6         | 3.11%   |
| 32768 | 1         | 0.52%   |
| 512   | 1         | 0.52%   |
| 256   | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 67        | 35.83%  |
| 2400    | 21        | 11.23%  |
| 3200    | 18        | 9.63%   |
| 1333    | 16        | 8.56%   |
| 2667    | 15        | 8.02%   |
| 667     | 8         | 4.28%   |
| 2133    | 7         | 3.74%   |
| 800     | 7         | 3.74%   |
| 2666    | 4         | 2.14%   |
| 1067    | 4         | 2.14%   |
| 1867    | 3         | 1.6%    |
| 1866    | 3         | 1.6%    |
| 1334    | 3         | 1.6%    |
| 1066    | 3         | 1.6%    |
| 3733    | 1         | 0.53%   |
| 3600    | 1         | 0.53%   |
| 2048    | 1         | 0.53%   |
| 1332    | 1         | 0.53%   |
| 1033    | 1         | 0.53%   |
| 400     | 1         | 0.53%   |
| 333     | 1         | 0.53%   |
| Unknown | 1         | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 100%    |

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
| Chicony Electronics                    | 11        | 20%     |
| Sunplus Innovation Technology          | 6         | 10.91%  |
| Realtek Semiconductor                  | 4         | 7.27%   |
| Quanta                                 | 4         | 7.27%   |
| Microdia                               | 4         | 7.27%   |
| Bison Electronics                      | 4         | 7.27%   |
| Suyin                                  | 3         | 5.45%   |
| Alcor Micro                            | 3         | 5.45%   |
| Logitech                               | 2         | 3.64%   |
| IMC Networks                           | 2         | 3.64%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.64%   |
| Z-Star Microelectronics                | 1         | 1.82%   |
| USB Camera                             | 1         | 1.82%   |
| Syntek                                 | 1         | 1.82%   |
| Silicon Motion                         | 1         | 1.82%   |
| Ricoh                                  | 1         | 1.82%   |
| OmniVision Technologies                | 1         | 1.82%   |
| Lite-On Technology                     | 1         | 1.82%   |
| Importek                               | 1         | 1.82%   |
| HD WEBCAM                              | 1         | 1.82%   |
| Apple                                  | 1         | 1.82%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 4         | 7.27%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 5.45%   |
| Quanta HP TrueVision HD Camera                                             | 3         | 5.45%   |
| Realtek USB Camera                                                         | 2         | 3.64%   |
| Z-Star Vega USB 2.0 Camera                                                 | 1         | 1.82%   |
| USB Camera USB Camera                                                      | 1         | 1.82%   |
| Syntek EasyCamera                                                          | 1         | 1.82%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 1.82%   |
| Suyin HP webcam [dv6-1190en]                                               | 1         | 1.82%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 1.82%   |
| Sunplus Integrated Camera                                                  | 1         | 1.82%   |
| Sunplus HP HD Webcam [Fixed]                                               | 1         | 1.82%   |
| Sunplus Asus Webcam                                                        | 1         | 1.82%   |
| Silicon Motion Realtek USB 2.0 PC Camera                                   | 1         | 1.82%   |
| Ricoh Integrated Webcam                                                    | 1         | 1.82%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 1.82%   |
| Realtek Acer 640 x 480 laptop camera                                       | 1         | 1.82%   |
| Quanta Realtek DMFT RGB                                                    | 1         | 1.82%   |
| OmniVision Monitor Webcam                                                  | 1         | 1.82%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 1.82%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.82%   |
| Microdia Integrated Webcam                                                 | 1         | 1.82%   |
| Microdia HP Webcam                                                         | 1         | 1.82%   |
| Logitech C505 HD Webcam                                                    | 1         | 1.82%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 1.82%   |
| Lite-On Integrated Camera                                                  | 1         | 1.82%   |
| Importek HP Webcam                                                         | 1         | 1.82%   |
| IMC Networks Realtek PC Camera                                             | 1         | 1.82%   |
| IMC Networks 2M Integrated Webcam                                          | 1         | 1.82%   |
| HD WEBCAM HD WEBCAM                                                        | 1         | 1.82%   |
| Chicony WebCam                                                             | 1         | 1.82%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.82%   |
| Chicony USB 2.0 Camera                                                     | 1         | 1.82%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 1.82%   |
| Chicony Integrated IR Camera                                               | 1         | 1.82%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 1.82%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.82%   |
| Bison SunplusIT Integrated Camera                                          | 1         | 1.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 8         | 66.67%  |
| Upek                  | 1         | 8.33%   |
| Synaptics             | 1         | 8.33%   |
| STMicroelectronics    | 1         | 8.33%   |
| Elan Microelectronics | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                                  | 2         | 16.67%  |
| Validity Sensors VFS101 Fingerprint Reader               | 2         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 16.67%  |
| Validity Sensors Synaptics WBDI                          | 1         | 8.33%   |
| Validity Sensors Fingerprint scanner                     | 1         | 8.33%   |
| Upek TCS5B Fingerprint sensor                            | 1         | 8.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 8.33%   |
| STMicroelectronics Fingerprint Reader                    | 1         | 8.33%   |
| Elan Fingerprint Sensor                                  | 1         | 8.33%   |

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
| 1     | 87        | 43.72%  |
| 0     | 57        | 28.64%  |
| 2     | 33        | 16.58%  |
| 3     | 16        | 8.04%   |
| 4     | 5         | 2.51%   |
| 6     | 1         | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 105       | 50.24%  |
| Net/wireless             | 37        | 17.7%   |
| Bluetooth                | 22        | 10.53%  |
| Card reader              | 16        | 7.66%   |
| Fingerprint reader       | 11        | 5.26%   |
| Network                  | 5         | 2.39%   |
| Graphics card            | 4         | 1.91%   |
| Firewire controller      | 4         | 1.91%   |
| Sound                    | 3         | 1.44%   |
| Storage/ata              | 1         | 0.48%   |
| Net/ethernet             | 1         | 0.48%   |

