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

Total: 381

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [30cc9d07af](https://bsd-hardware.info/?probe=30cc9d07af) | May 07, 2024 |
| MSI           | MS-7097                     | Desktop     | [df5c7407fd](https://bsd-hardware.info/?probe=df5c7407fd) | May 06, 2024 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [6da31bada9](https://bsd-hardware.info/?probe=6da31bada9) | Apr 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [2caa0fe8f7](https://bsd-hardware.info/?probe=2caa0fe8f7) | Apr 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [1d373fbfcd](https://bsd-hardware.info/?probe=1d373fbfcd) | Apr 26, 2024 |
| AZW           | EQ                          | Desktop     | [9225d89862](https://bsd-hardware.info/?probe=9225d89862) | Apr 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [242348310b](https://bsd-hardware.info/?probe=242348310b) | Apr 22, 2024 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [1bc36f8af1](https://bsd-hardware.info/?probe=1bc36f8af1) | Apr 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [d231a9531b](https://bsd-hardware.info/?probe=d231a9531b) | Apr 17, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [a818576415](https://bsd-hardware.info/?probe=a818576415) | Apr 13, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [d8288ba73a](https://bsd-hardware.info/?probe=d8288ba73a) | Apr 09, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [9057a0522b](https://bsd-hardware.info/?probe=9057a0522b) | Apr 08, 2024 |
| Gigabyte      | G431-MM0-OT                 | Desktop     | [16c58f7ccb](https://bsd-hardware.info/?probe=16c58f7ccb) | Apr 07, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [a26013b913](https://bsd-hardware.info/?probe=a26013b913) | Apr 05, 2024 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3f85beaa54](https://bsd-hardware.info/?probe=3f85beaa54) | Apr 05, 2024 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [b2bbe7eb8d](https://bsd-hardware.info/?probe=b2bbe7eb8d) | Apr 04, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [0ae72ec0ff](https://bsd-hardware.info/?probe=0ae72ec0ff) | Mar 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [0687b8c8e1](https://bsd-hardware.info/?probe=0687b8c8e1) | Mar 29, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [0d486d6705](https://bsd-hardware.info/?probe=0d486d6705) | Mar 26, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [bad44928d7](https://bsd-hardware.info/?probe=bad44928d7) | Mar 25, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [313ab74587](https://bsd-hardware.info/?probe=313ab74587) | Mar 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [25a92fc367](https://bsd-hardware.info/?probe=25a92fc367) | Mar 22, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3a0ef703ef](https://bsd-hardware.info/?probe=3a0ef703ef) | Mar 10, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [88b774a83d](https://bsd-hardware.info/?probe=88b774a83d) | Mar 10, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [9b40b121ec](https://bsd-hardware.info/?probe=9b40b121ec) | Mar 10, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [7cc4588e07](https://bsd-hardware.info/?probe=7cc4588e07) | Mar 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [e35907b66f](https://bsd-hardware.info/?probe=e35907b66f) | Mar 04, 2024 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [05b6d7a915](https://bsd-hardware.info/?probe=05b6d7a915) | Feb 29, 2024 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [0275a7e6b3](https://bsd-hardware.info/?probe=0275a7e6b3) | Feb 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [d3ed7d1552](https://bsd-hardware.info/?probe=d3ed7d1552) | Feb 24, 2024 |
| HPE           | ProLiant MicroServer Gen... | Server      | [0896863043](https://bsd-hardware.info/?probe=0896863043) | Feb 18, 2024 |
| Intel         | CM8I7CB8N K53740-202        | Mini pc     | [4e34435ef4](https://bsd-hardware.info/?probe=4e34435ef4) | Feb 17, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [e9d1b23169](https://bsd-hardware.info/?probe=e9d1b23169) | Feb 16, 2024 |
| ECS           | APLD-MINI                   | Desktop     | [d0d3c5d2c3](https://bsd-hardware.info/?probe=d0d3c5d2c3) | Feb 16, 2024 |
| Unknown       | ITX-M41V                    | Desktop     | [957fb292ad](https://bsd-hardware.info/?probe=957fb292ad) | Feb 06, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [fa94c9a549](https://bsd-hardware.info/?probe=fa94c9a549) | Feb 04, 2024 |
| Unknown       | ITX-M41V                    | Desktop     | [3ab7929f1b](https://bsd-hardware.info/?probe=3ab7929f1b) | Feb 02, 2024 |
| YANYU         | R250                        | Desktop     | [93dceedd1f](https://bsd-hardware.info/?probe=93dceedd1f) | Feb 01, 2024 |
| YANYU         | R250                        | Desktop     | [76a55db1e1](https://bsd-hardware.info/?probe=76a55db1e1) | Jan 31, 2024 |
| YANYU         | R250                        | Desktop     | [f6e4c67d9a](https://bsd-hardware.info/?probe=f6e4c67d9a) | Jan 26, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [f0db40d2f4](https://bsd-hardware.info/?probe=f0db40d2f4) | Jan 24, 2024 |
| Acer          | TravelMate B115-M           | Notebook    | [d7a78aa2cf](https://bsd-hardware.info/?probe=d7a78aa2cf) | Jan 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [2f9d003e12](https://bsd-hardware.info/?probe=2f9d003e12) | Jan 21, 2024 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [ec9b6a27b9](https://bsd-hardware.info/?probe=ec9b6a27b9) | Jan 18, 2024 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [bece75e284](https://bsd-hardware.info/?probe=bece75e284) | Jan 14, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [b56a8b041a](https://bsd-hardware.info/?probe=b56a8b041a) | Jan 14, 2024 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [40b8a056f7](https://bsd-hardware.info/?probe=40b8a056f7) | Jan 07, 2024 |
| Lenovo        | ThinkPad E495 20NE000BSP    | Notebook    | [9ed586661c](https://bsd-hardware.info/?probe=9ed586661c) | Jan 03, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [766493f0dd](https://bsd-hardware.info/?probe=766493f0dd) | Jan 03, 2024 |
| AMI           | Intel                       | Notebook    | [df557e3915](https://bsd-hardware.info/?probe=df557e3915) | Dec 25, 2023 |
| Dell          | Precision 5510              | Notebook    | [4bad5ad995](https://bsd-hardware.info/?probe=4bad5ad995) | Dec 23, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [4ccf9a2566](https://bsd-hardware.info/?probe=4ccf9a2566) | Dec 21, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [1eb8cc9d76](https://bsd-hardware.info/?probe=1eb8cc9d76) | Dec 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7a5e6024cd](https://bsd-hardware.info/?probe=7a5e6024cd) | Dec 15, 2023 |
| Toshiba       | Portable PC                 | Notebook    | [bee6ea8f18](https://bsd-hardware.info/?probe=bee6ea8f18) | Dec 15, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [357a808604](https://bsd-hardware.info/?probe=357a808604) | Dec 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [9a842bf3c8](https://bsd-hardware.info/?probe=9a842bf3c8) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [ef2a5b9804](https://bsd-hardware.info/?probe=ef2a5b9804) | Dec 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [d5da0ab59d](https://bsd-hardware.info/?probe=d5da0ab59d) | Dec 01, 2023 |
| Dell          | Precision 5510              | Notebook    | [3a7b2ae214](https://bsd-hardware.info/?probe=3a7b2ae214) | Nov 28, 2023 |
| Intel         | CM8I7CB8N K53740-202        | Mini pc     | [481571734a](https://bsd-hardware.info/?probe=481571734a) | Nov 25, 2023 |
| YANYU         | R250                        | Desktop     | [74ee81493f](https://bsd-hardware.info/?probe=74ee81493f) | Nov 20, 2023 |
| MSI           | Z170-A PRO                  | Desktop     | [ab9a7eb894](https://bsd-hardware.info/?probe=ab9a7eb894) | Nov 08, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [42b9e61011](https://bsd-hardware.info/?probe=42b9e61011) | Nov 08, 2023 |
| Gigabyte      | MZBSWAP-00                  | Desktop     | [a01a7d9576](https://bsd-hardware.info/?probe=a01a7d9576) | Nov 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [790368b718](https://bsd-hardware.info/?probe=790368b718) | Nov 03, 2023 |
| Gigabyte      | MZBSWAP-00                  | Desktop     | [d52347dd3d](https://bsd-hardware.info/?probe=d52347dd3d) | Nov 02, 2023 |
| ASUSTek       | MINIPC PN53-G               | Desktop     | [57d8823b4b](https://bsd-hardware.info/?probe=57d8823b4b) | Oct 28, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a40b6fde47](https://bsd-hardware.info/?probe=a40b6fde47) | Oct 22, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [b08dc9fc91](https://bsd-hardware.info/?probe=b08dc9fc91) | Oct 16, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [f3036a27e5](https://bsd-hardware.info/?probe=f3036a27e5) | Oct 13, 2023 |
| ECS           | APLD-MINI                   | Desktop     | [d063eeb7d5](https://bsd-hardware.info/?probe=d063eeb7d5) | Oct 08, 2023 |
| GVC           | DR 738                      | Desktop     | [1aa25f04a8](https://bsd-hardware.info/?probe=1aa25f04a8) | Oct 07, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [0f92b89ffb](https://bsd-hardware.info/?probe=0f92b89ffb) | Sep 09, 2023 |
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
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [6cd6b15a60](https://bsd-hardware.info/?probe=6cd6b15a60) | Feb 12, 2023 |
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
| helloSystem 0.7.0 | 27        | 8.94%   |
| helloSystem 0.8.1 | 21        | 6.95%   |
| helloSystem 0.8.0 | 13        | 4.3%    |
| FreeBSD 13.1      | 10        | 3.31%   |
| helloSystem 0.4.0 | 9         | 2.98%   |
| helloSystem 0.5.0 | 8         | 2.65%   |
| OPNsense 22.1     | 7         | 2.32%   |
| OpenBSD 6.8       | 6         | 1.99%   |
| helloSystem 0.6.0 | 6         | 1.99%   |
| OPNsense 22.7.10  | 5         | 1.66%   |
| OpenBSD 7.2       | 5         | 1.66%   |
| FreeBSD 13.2      | 5         | 1.66%   |
| OPNsense 24.1.6   | 4         | 1.32%   |
| OPNsense 24.1.1   | 4         | 1.32%   |
| OPNsense 23.7.7   | 4         | 1.32%   |
| OPNsense 23.7.12  | 4         | 1.32%   |
| OPNsense 21.7.7   | 4         | 1.32%   |
| OpenBSD 7.1       | 4         | 1.32%   |
| GhostBSD 20.04.02 | 4         | 1.32%   |
| OPNsense 24.1.4   | 3         | 0.99%   |
| OPNsense 24.1.2   | 3         | 0.99%   |
| OPNsense 24.1     | 3         | 0.99%   |
| OPNsense 23.1     | 3         | 0.99%   |
| OPNsense 22.7.6   | 3         | 0.99%   |
| OPNsense 22.7.11  | 3         | 0.99%   |
| OPNsense 21.7.5   | 3         | 0.99%   |
| OPNsense 21.7.1   | 3         | 0.99%   |
| helloSystem 0.8.2 | 3         | 0.99%   |
| FreeBSD 14.0      | 3         | 0.99%   |
| FreeBSD 13.0      | 3         | 0.99%   |
| OPNsense 23.7.2   | 2         | 0.66%   |
| OPNsense 23.1.7   | 2         | 0.66%   |
| OPNsense 23.1.11  | 2         | 0.66%   |
| OPNsense 22.7.9   | 2         | 0.66%   |
| OPNsense 22.7.8   | 2         | 0.66%   |
| OPNsense 22.7.4   | 2         | 0.66%   |
| OPNsense 22.7.2   | 2         | 0.66%   |
| OPNsense 22.7.1   | 2         | 0.66%   |
| OPNsense 22.1.5   | 2         | 0.66%   |
| OPNsense 22.1.3   | 2         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 80        | 33.9%   |
| helloSystem | 76        | 32.2%   |
| FreeBSD     | 40        | 16.95%  |
| OpenBSD     | 18        | 7.63%   |
| GhostBSD    | 11        | 4.66%   |
| NetBSD      | 5         | 2.12%   |
| NomadBSD    | 2         | 0.85%   |
| FuguIta     | 2         | 0.85%   |
| TrueNAS     | 1         | 0.42%   |
| DragonFly   | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 225       | 97.4%   |
| arm64  | 3         | 1.3%    |
| i386   | 2         | 0.87%   |
| evbarm | 1         | 0.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 98        | 41.35%  |
| helloDesktop | 89        | 37.55%  |
| MATE         | 16        | 6.75%   |
| fvwm         | 7         | 2.95%   |
| XFCE         | 6         | 2.53%   |
| TWM          | 5         | 2.11%   |
| KDE5         | 4         | 1.69%   |
| GNOME        | 4         | 1.69%   |
| Openbox      | 3         | 1.27%   |
| i3           | 3         | 1.27%   |
| LXQt         | 1         | 0.42%   |
| Fluxbox      | 1         | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 132       | 56.9%   |
| Console | 97        | 41.81%  |
| Wayland | 3         | 1.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 123       | 51.9%   |
| SLiM    | 82        | 34.6%   |
| LightDM | 16        | 6.75%   |
| SDDM    | 7         | 2.95%   |
| GDM     | 5         | 2.11%   |
| XDM     | 2         | 0.84%   |
| Ly      | 2         | 0.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 110       | 45.27%  |
| en_US            | 50        | 20.58%  |
| es_ES            | 33        | 13.58%  |
| C                | 33        | 13.58%  |
| fr_FR            | 6         | 2.47%   |
| es               | 5         | 2.06%   |
| ru_RU            | 2         | 0.82%   |
| zh_CN            | 1         | 0.41%   |
| fr               | 1         | 0.41%   |
| es_ES.ISO8859-15 | 1         | 0.41%   |
| de_DE            | 1         | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 196       | 84.48%  |
| BIOS | 36        | 15.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 111       | 45.49%  |
| Ufs     | 72        | 29.51%  |
| Cd9660  | 39        | 15.98%  |
| Ffs     | 20        | 8.2%    |
| Hammer2 | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 205       | 88.36%  |
| MBR     | 23        | 9.91%   |
| Unknown | 4         | 1.72%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Hewlett-Packard            | 31        | 13.42%  |
| ASUSTek Computer           | 31        | 13.42%  |
| Lenovo                     | 23        | 9.96%   |
| Unknown                    | 16        | 6.93%   |
| Dell                       | 14        | 6.06%   |
| Gigabyte Technology        | 13        | 5.63%   |
| AMI                        | 12        | 5.19%   |
| Acer                       | 10        | 4.33%   |
| MSI                        | 8         | 3.46%   |
| ASRock                     | 8         | 3.46%   |
| Intel                      | 7         | 3.03%   |
| Fujitsu                    | 7         | 3.03%   |
| Apple                      | 7         | 3.03%   |
| YANYU                      | 4         | 1.73%   |
| Raspberry Pi Foundation    | 3         | 1.3%    |
| Toshiba                    | 2         | 0.87%   |
| Techvision                 | 2         | 0.87%   |
| SLIMBOOK                   | 2         | 0.87%   |
| Samsung Electronics        | 2         | 0.87%   |
| OEM                        | 2         | 0.87%   |
| Medion                     | 2         | 0.87%   |
| ECS                        | 2         | 0.87%   |
| AZW                        | 2         | 0.87%   |
| ZOTAC                      | 1         | 0.43%   |
| Wistron                    | 1         | 0.43%   |
| TWINHEAD                   | 1         | 0.43%   |
| TUXEDO                     | 1         | 0.43%   |
| Sony                       | 1         | 0.43%   |
| ShenZhen MinWin Technology | 1         | 0.43%   |
| Seeed Studio               | 1         | 0.43%   |
| ReachingTech               | 1         | 0.43%   |
| Razer                      | 1         | 0.43%   |
| Protectli                  | 1         | 0.43%   |
| Pegatron                   | 1         | 0.43%   |
| PC Engines                 | 1         | 0.43%   |
| Packard Bell               | 1         | 0.43%   |
| MW                         | 1         | 0.43%   |
| HPE                        | 1         | 0.43%   |
| GVC                        | 1         | 0.43%   |
| Fujitsu Siemens            | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 17        | 7.36%   |
| AMI Aptio CRB                       | 10        | 4.33%   |
| RPi Raspberry Pi                    | 3         | 1.3%    |
| Fujitsu FUTRO S920                  | 3         | 1.3%    |
| Dell Latitude 7390                  | 3         | 1.3%    |
| ASUS All Series                     | 3         | 1.3%    |
| YANYU R250                          | 2         | 0.87%   |
| YANYU H67SL                         | 2         | 0.87%   |
| Techvision TVI7309X                 | 2         | 0.87%   |
| HP t620 PLUS Quad Core TC           | 2         | 0.87%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 2         | 0.87%   |
| HP EliteDesk 700 G1 SFF             | 2         | 0.87%   |
| ASUS PRIME A320M-K                  | 2         | 0.87%   |
| ASUS K55VD                          | 2         | 0.87%   |
| ASRock N3700-ITX                    | 2         | 0.87%   |
| ASRock H81M-VG4 R2.0                | 2         | 0.87%   |
| ZOTAC ZBOXNANO-AQ01                 | 1         | 0.43%   |
| Wistron ProLiant ML110 G6           | 1         | 0.43%   |
| TWINHEAD U12CT                      | 1         | 0.43%   |
| TUXEDO Aura 15 Gen1                 | 1         | 0.43%   |
| Toshiba Satellite A300              | 1         | 0.43%   |
| Toshiba Portable PC                 | 1         | 0.43%   |
| Sony SVE1511C5E                     | 1         | 0.43%   |
| SLIMBOOK PROX-AMD5                  | 1         | 0.43%   |
| SLIMBOOK ESSENTIAL-15-11            | 1         | 0.43%   |
| ShenZhen MinWin 3865U-6L            | 1         | 0.43%   |
| Seeed Studio ODYSSEY-X86J4105       | 1         | 0.43%   |
| Samsung Galaxy Book 12              | 1         | 0.43%   |
| Samsung 530U3C/530U4C/532U3C        | 1         | 0.43%   |
| ReachingTech DreamQuest Pro 2022    | 1         | 0.43%   |
| Razer Blade Stealth                 | 1         | 0.43%   |
| Protectli FW4B                      | 1         | 0.43%   |
| Pegatron Elite 7500 Series MT       | 1         | 0.43%   |
| PC Engines APU2                     | 1         | 0.43%   |
| Packard Bell DOT S                  | 1         | 0.43%   |
| OEM NU93 Series                     | 1         | 0.43%   |
| OEM AR-B5800                        | 1         | 0.43%   |
| MW GMLK-2_5G4L                      | 1         | 0.43%   |
| MSI MS-7C91                         | 1         | 0.43%   |
| MSI MS-7C52                         | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 17        | 7.36%   |
| Lenovo ThinkPad     | 12        | 5.19%   |
| AMI Aptio           | 10        | 4.33%   |
| Acer Aspire         | 7         | 3.03%   |
| HP Pavilion         | 6         | 2.6%    |
| ASUS PRIME          | 6         | 2.6%    |
| Lenovo ThinkCentre  | 5         | 2.16%   |
| HP EliteDesk        | 4         | 1.73%   |
| HP Compaq           | 4         | 1.73%   |
| Dell Latitude       | 4         | 1.73%   |
| RPi Raspberry       | 3         | 1.3%    |
| HP ProBook          | 3         | 1.3%    |
| HP OMEN             | 3         | 1.3%    |
| Fujitsu FUTRO       | 3         | 1.3%    |
| Fujitsu ESPRIMO     | 3         | 1.3%    |
| Dell OptiPlex       | 3         | 1.3%    |
| ASUS TUF            | 3         | 1.3%    |
| ASUS All            | 3         | 1.3%    |
| YANYU R250          | 2         | 0.87%   |
| YANYU H67SL         | 2         | 0.87%   |
| Techvision TVI7309X | 2         | 0.87%   |
| Lenovo IdeaPad      | 2         | 0.87%   |
| HP t620             | 2         | 0.87%   |
| HP ProLiant         | 2         | 0.87%   |
| HP Laptop           | 2         | 0.87%   |
| Dell Precision      | 2         | 0.87%   |
| Dell PowerEdge      | 2         | 0.87%   |
| ASUS M5A78L-M       | 2         | 0.87%   |
| ASUS K55VD          | 2         | 0.87%   |
| ASRock N3700-ITX    | 2         | 0.87%   |
| ASRock H81M-VG4     | 2         | 0.87%   |
| Apple MacBook5      | 2         | 0.87%   |
| ZOTAC ZBOXNANO-AQ01 | 1         | 0.43%   |
| Wistron ProLiant    | 1         | 0.43%   |
| TWINHEAD U12CT      | 1         | 0.43%   |
| TUXEDO Aura         | 1         | 0.43%   |
| Toshiba Satellite   | 1         | 0.43%   |
| Toshiba Portable    | 1         | 0.43%   |
| Sony SVE1511C5E     | 1         | 0.43%   |
| SLIMBOOK PROX-AMD5  | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 25        | 10.82%  |
| 2014    | 25        | 10.82%  |
| 2019    | 22        | 9.52%   |
| 2018    | 20        | 8.66%   |
| 2022    | 16        | 6.93%   |
| 2016    | 15        | 6.49%   |
| 2017    | 13        | 5.63%   |
| 2015    | 13        | 5.63%   |
| 2023    | 11        | 4.76%   |
| 2011    | 11        | 4.76%   |
| 2012    | 10        | 4.33%   |
| 2021    | 9         | 3.9%    |
| 2013    | 8         | 3.46%   |
| 2009    | 8         | 3.46%   |
| 2008    | 8         | 3.46%   |
| 2010    | 7         | 3.03%   |
| Unknown | 5         | 2.16%   |
| 2007    | 2         | 0.87%   |
| 2006    | 1         | 0.43%   |
| 2005    | 1         | 0.43%   |
| 2003    | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 126       | 54.55%  |
| Notebook       | 78        | 33.77%  |
| Mini pc        | 16        | 6.93%   |
| Server         | 5         | 2.16%   |
| System on chip | 3         | 1.3%    |
| Tablet         | 1         | 0.43%   |
| Convertible    | 1         | 0.43%   |
| All in one     | 1         | 0.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 230       | 99.57%  |
| Yes  | 1         | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 94        | 39.83%  |
| 16.01-24.0  | 52        | 22.03%  |
| 4.01-8.0    | 45        | 19.07%  |
| 32.01-64.0  | 21        | 8.9%    |
| 3.01-4.0    | 6         | 2.54%   |
| 2.01-3.0    | 6         | 2.54%   |
| 64.01-256.0 | 5         | 2.12%   |
| 1.01-2.0    | 3         | 1.27%   |
| 0.01-0.5    | 2         | 0.85%   |
| 24.01-32.0  | 1         | 0.42%   |
| 0.51-1.0    | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 115       | 47.52%  |
| 0.51-1.0   | 80        | 33.06%  |
| 1.01-2.0   | 26        | 10.74%  |
| 2.01-3.0   | 6         | 2.48%   |
| Unknown    | 5         | 2.07%   |
| 3.01-4.0   | 4         | 1.65%   |
| 0          | 3         | 1.24%   |
| 4.01-8.0   | 2         | 0.83%   |
| 24.01-32.0 | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 138       | 57.74%  |
| 2      | 44        | 18.41%  |
| 0      | 26        | 10.88%  |
| 4      | 12        | 5.02%   |
| 3      | 10        | 4.18%   |
| 5      | 6         | 2.51%   |
| 6      | 2         | 0.84%   |
| 7      | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 78.88%  |
| Yes       | 49        | 21.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 213       | 92.21%  |
| No        | 18        | 7.79%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 51.5%   |
| No        | 113       | 48.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 139       | 59.66%  |
| Yes       | 94        | 40.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Spain   | 231       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Madrid                        | 54        | 20.15%  |
| Barcelona                     | 16        | 5.97%   |
| Valencia                      | 13        | 4.85%   |
| Vigo                          | 4         | 1.49%   |
| Seville                       | 4         | 1.49%   |
| Ourense                       | 4         | 1.49%   |
| Málaga                       | 4         | 1.49%   |
| Ibiza Town                    | 4         | 1.49%   |
| Zaragoza                      | 3         | 1.12%   |
| Terrassa                      | 3         | 1.12%   |
| San SebastiÃ¡n de los Reyes | 3         | 1.12%   |
| Paterna                       | 3         | 1.12%   |
| Navalcarnero                  | 3         | 1.12%   |
| Elche                         | 3         | 1.12%   |
| Bilbao                        | 3         | 1.12%   |
| Alcobendas                    | 3         | 1.12%   |
| A Coruña                     | 3         | 1.12%   |
| Vitoria-Gasteiz               | 2         | 0.75%   |
| Viladecans                    | 2         | 0.75%   |
| Torrejon del Rey              | 2         | 0.75%   |
| Tarragona                     | 2         | 0.75%   |
| Sedavi                        | 2         | 0.75%   |
| Santiago de Compostela        | 2         | 0.75%   |
| Santa Cruz de Tenerife        | 2         | 0.75%   |
| Redondela                     | 2         | 0.75%   |
| Palma                         | 2         | 0.75%   |
| Oviedo                        | 2         | 0.75%   |
| LogroÃ±o                    | 2         | 0.75%   |
| GibraleГіn                  | 2         | 0.75%   |
| Coria del RÃ­o              | 2         | 0.75%   |
| Castilleja de la Cuesta       | 2         | 0.75%   |
| Barakaldo                     | 2         | 0.75%   |
| Albacete                      | 2         | 0.75%   |
| Zarautz                       | 1         | 0.37%   |
| VГ©lez-MГЎlaga            | 1         | 0.37%   |
| Villena                       | 1         | 0.37%   |
| Villapresente                 | 1         | 0.37%   |
| Villanueva de la Canada       | 1         | 0.37%   |
| Valmojado                     | 1         | 0.37%   |
| Valleseco                     | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                                 | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC                                    | 42        | 62     | 14.33%  |
| Samsung Electronics                    | 42        | 68     | 14.33%  |
| Kingston                               | 37        | 68     | 12.63%  |
| Seagate                                | 34        | 59     | 11.6%   |
| Crucial                                | 20        | 23     | 6.83%   |
| Toshiba                                | 12        | 16     | 4.1%    |
| Hitachi                                | 10        | 10     | 3.41%   |
| SanDisk                                | 8         | 9      | 2.73%   |
| NVMe                                   | 7         | 10     | 2.39%   |
| China                                  | 6         | 13     | 2.05%   |
| Transcend                              | 5         | 8      | 1.71%   |
| Intel                                  | 4         | 6      | 1.37%   |
| HGST                                   | 4         | 4      | 1.37%   |
| FORESEE                                | 4         | 4      | 1.37%   |
| TCSUNBOW                               | 3         | 5      | 1.02%   |
| OCZ                                    | 3         | 3      | 1.02%   |
| Micron Technology                      | 3         | 3      | 1.02%   |
| LITEON                                 | 3         | 3      | 1.02%   |
| Intenso                                | 3         | 7      | 1.02%   |
| Corsair                                | 3         | 3      | 1.02%   |
| Silicon Motion                         | 2         | 2      | 0.68%   |
| ShiJi                                  | 2         | 2      | 0.68%   |
| Product:              USB Flash Memory | 2         | 2      | 0.68%   |
| Phison                                 | 2         | 2      | 0.68%   |
| LITEONIT                               | 2         | 2      | 0.68%   |
| Kston                                  | 2         | 4      | 0.68%   |
| KIOXIA                                 | 2         | 2      | 0.68%   |
| Innodisk                               | 2         | 2      | 0.68%   |
| Hoodisk                                | 2         | 2      | 0.68%   |
| Fujitsu                                | 2         | 2      | 0.68%   |
| Apple                                  | 2         | 2      | 0.68%   |
| XrayDisk                               | 1         | 1      | 0.34%   |
| ViperTeq                               | 1         | 1      | 0.34%   |
| Union Memory                           | 1         | 1      | 0.34%   |
| SK hynix                               | 1         | 1      | 0.34%   |
| PNY                                    | 1         | 1      | 0.34%   |
| Nfortec                                | 1         | 1      | 0.34%   |
| Netac                                  | 1         | 1      | 0.34%   |
| Maximus                                | 1         | 1      | 0.34%   |
| MARVELL                                | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB                                  | 9         | 2.74%   |
| Seagate ST500DM002-1BD142 500GB                              | 5         | 1.52%   |
| Kingston SA400S37480G 480GB                                  | 5         | 1.52%   |
| Seagate ST1000DM010-2EP102 1TB                               | 4         | 1.22%   |
| Kingston SV300S37A120G 120GB                                 | 4         | 1.22%   |
| Kingston SUV500MS120G 120GB                                  | 4         | 1.22%   |
| Crucial CT500MX500SSD1 500GB                                 | 4         | 1.22%   |
| Samsung SSD 860 EVO 500GB                                    | 3         | 0.91%   |
| Samsung SSD 850 EVO 500GB                                    | 3         | 0.91%   |
| Samsung SSD 850 EVO 250GB                                    | 3         | 0.91%   |
| Kingston SUV400S37240G 240GB                                 | 3         | 0.91%   |
| Kingston SA400S37120G 120GB                                  | 3         | 0.91%   |
| Crucial CT240BX500SSD1 240GB                                 | 3         | 0.91%   |
| WDC WDS500G2B0A-00SM50 500GB                                 | 2         | 0.61%   |
| WDC WDS500G1B0A-00H9H0 500GB                                 | 2         | 0.61%   |
| WDC WDS250G1B0A-00H9H0 250GB                                 | 2         | 0.61%   |
| WDC WD20EARX-00PASB0 2TB                                     | 2         | 0.61%   |
| WDC WD10EZEX-60WN4A0 1TB                                     | 2         | 0.61%   |
| Transcend TS120GMTS420S 120GB                                | 2         | 0.61%   |
| Toshiba TR200 240GB                                          | 2         | 0.61%   |
| Seagate ST9500325AS 500GB                                    | 2         | 0.61%   |
| Seagate ST500LM021-1KJ152 500GB                              | 2         | 0.61%   |
| Seagate ST3500418AS 500GB                                    | 2         | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                           | 2         | 0.61%   |
| Seagate ST1000DM003-9YN162 1TB                               | 2         | 0.61%   |
| Seagate ST1000DM003-1ER162 1TB                               | 2         | 0.61%   |
| Samsung MZVLW512HMJP-000L7 512GB                             | 2         | 0.61%   |
| Samsung HD103SI 1TB                                          | 2         | 0.61%   |
| Product:              USB Flash Memory USB Flash Memory 16GB | 2         | 0.61%   |
| NVMe Samsung SSD 980 1TB                                     | 2         | 0.61%   |
| LITEON CV8-8E128-HP 128GB                                    | 2         | 0.61%   |
| Kingston SV300S37A240G 240GB                                 | 2         | 0.61%   |
| Kingston SKC600MS256G 256GB                                  | 2         | 0.61%   |
| Innodisk DEMSR- 08GB mSATA 3ME A                             | 2         | 0.61%   |
| Hitachi HTS545050A7E380 500GB                                | 2         | 0.61%   |
| FORESEE S326M256G 256GB                                      | 2         | 0.61%   |
| Crucial CT500P1SSD8 500GB                                    | 2         | 0.61%   |
| Crucial CT480BX500SSD1 480GB                                 | 2         | 0.61%   |
| Crucial CT250MX500SSD1 250GB                                 | 2         | 0.61%   |
| XrayDisk SSD 240GB                                           | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Seagate                                | 33        | 55     | 32.67%  |
| WDC                                    | 29        | 43     | 28.71%  |
| Hitachi                                | 10        | 10     | 9.9%    |
| Toshiba                                | 8         | 10     | 7.92%   |
| Samsung Electronics                    | 8         | 11     | 7.92%   |
| HGST                                   | 4         | 4      | 3.96%   |
| NVMe                                   | 3         | 5      | 2.97%   |
| Product:              USB Flash Memory | 2         | 2      | 1.98%   |
| Fujitsu                                | 2         | 2      | 1.98%   |
| MARVELL                                | 1         | 1      | 0.99%   |
| Apple                                  | 1         | 1      | 0.99%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 35        | 66     | 23.81%  |
| Samsung Electronics | 22        | 32     | 14.97%  |
| Crucial             | 15        | 18     | 10.2%   |
| WDC                 | 8         | 13     | 5.44%   |
| SanDisk             | 8         | 9      | 5.44%   |
| China               | 6         | 13     | 4.08%   |
| Transcend           | 5         | 8      | 3.4%    |
| Toshiba             | 4         | 4      | 2.72%   |
| FORESEE             | 4         | 4      | 2.72%   |
| TCSUNBOW            | 3         | 5      | 2.04%   |
| OCZ                 | 3         | 3      | 2.04%   |
| NVMe                | 3         | 3      | 2.04%   |
| LITEON              | 3         | 3      | 2.04%   |
| Intel               | 3         | 5      | 2.04%   |
| ShiJi               | 2         | 2      | 1.36%   |
| LITEONIT            | 2         | 2      | 1.36%   |
| Kston               | 2         | 4      | 1.36%   |
| Intenso             | 2         | 6      | 1.36%   |
| Innodisk            | 2         | 2      | 1.36%   |
| Hoodisk             | 2         | 2      | 1.36%   |
| XrayDisk            | 1         | 1      | 0.68%   |
| ViperTeq            | 1         | 1      | 0.68%   |
| Seagate             | 1         | 1      | 0.68%   |
| PNY                 | 1         | 1      | 0.68%   |
| Netac               | 1         | 1      | 0.68%   |
| Micron Technology   | 1         | 1      | 0.68%   |
| Maximus             | 1         | 1      | 0.68%   |
| KingSpec            | 1         | 1      | 0.68%   |
| EMTEC               | 1         | 1      | 0.68%   |
| BR                  | 1         | 3      | 0.68%   |
| BAITITON            | 1         | 1      | 0.68%   |
| Apple               | 1         | 1      | 0.68%   |
| Apacer              | 1         | 1      | 0.68%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 131       | 219    | 50.58%  |
| HDD  | 82        | 144    | 31.66%  |
| NVMe | 46        | 68     | 17.76%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 179       | 363    | 79.56%  |
| NVMe | 46        | 68     | 20.44%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 158       | 278    | 74.18%  |
| 0.51-1.0   | 37        | 57     | 17.37%  |
| 1.01-2.0   | 11        | 19     | 5.16%   |
| 4.01-10.0  | 4         | 6      | 1.88%   |
| 3.01-4.0   | 2         | 2      | 0.94%   |
| 2.01-3.0   | 1         | 1      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 72        | 29.63%  |
| 101-250        | 71        | 29.22%  |
| 251-500        | 45        | 18.52%  |
| 21-50          | 19        | 7.82%   |
| 51-100         | 17        | 7%      |
| 501-1000       | 13        | 5.35%   |
| 1001-2000      | 3         | 1.23%   |
| More than 3000 | 1         | 0.41%   |
| 2001-3000      | 1         | 0.41%   |
| Unknown        | 1         | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 215       | 90.34%  |
| 21-50    | 12        | 5.04%   |
| 51-100   | 6         | 2.52%   |
| 251-500  | 3         | 1.26%   |
| 501-1000 | 1         | 0.42%   |
| Unknown  | 1         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                 | 2         | 2      | 3.85%   |
| LITEON CV8-8E128-HP 128GB                       | 2         | 2      | 3.85%   |
| Kingston SV300S37A120G 120GB                    | 2         | 2      | 3.85%   |
| Hitachi HTS545050A7E380 500GB                   | 2         | 2      | 3.85%   |
| WDC WDS240G2G0A-00JH30 240GB                    | 1         | 2      | 1.92%   |
| WDC WD6400AAKS-22A7B0 640GB                     | 1         | 1      | 1.92%   |
| WDC WD5000LPVX-22V0TT0 500GB                    | 1         | 1      | 1.92%   |
| WDC WD5000AAKX-22ERMA0 500GB                    | 1         | 1      | 1.92%   |
| WDC WD2500BEVT-35A23T0 250GB                    | 1         | 1      | 1.92%   |
| WDC WD1600AAJS-00WAA0 160GB                     | 1         | 1      | 1.92%   |
| WDC WD10EZEX-21M2NA0 1TB                        | 1         | 1      | 1.92%   |
| Toshiba MQ01UBD100 1TB                          | 1         | 2      | 1.92%   |
| Toshiba MK1229GSG 120GB                         | 1         | 1      | 1.92%   |
| Toshiba MK1059GSM 1TB                           | 1         | 1      | 1.92%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 1      | 1.92%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 1.92%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 1.92%   |
| Seagate ST3500418AS 500GB                       | 1         | 1      | 1.92%   |
| Seagate ST3500413AS 500GB                       | 1         | 3      | 1.92%   |
| Seagate ST340016A 40GB                          | 1         | 1      | 1.92%   |
| Seagate ST3160215AS 160GB                       | 1         | 1      | 1.92%   |
| Seagate ST31000528AS 1TB                        | 1         | 2      | 1.92%   |
| Seagate ST31000333AS 1TB                        | 1         | 1      | 1.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 1.92%   |
| Seagate ST1000DM010-2EP102 1TB                  | 1         | 1      | 1.92%   |
| Seagate ST1000DM003-9YN162 1TB                  | 1         | 1      | 1.92%   |
| Seagate ST1000DM003-1ER162 1TB                  | 1         | 1      | 1.92%   |
| Samsung Electronics HM320JI 320GB               | 1         | 1      | 1.92%   |
| Samsung Electronics HM160HI 160GB               | 1         | 1      | 1.92%   |
| Samsung Electronics HD252HJ 250GB               | 1         | 1      | 1.92%   |
| Samsung Electronics HD103UJ 1TB                 | 1         | 1      | 1.92%   |
| Samsung Electronics HD103SI 1TB                 | 1         | 1      | 1.92%   |
| OCZ AGILITY3 120GB                              | 1         | 1      | 1.92%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 1.92%   |
| Maximus SSD 128GB                               | 1         | 1      | 1.92%   |
| Kingston SUV400S37240G 240GB                    | 1         | 3      | 1.92%   |
| Kingston SHFS37A120G 120GB                      | 1         | 1      | 1.92%   |
| Hitachi HTS725050A9A364 500GB                   | 1         | 1      | 1.92%   |
| Hitachi HTS725050A7E630 500GB                   | 1         | 1      | 1.92%   |
| Hitachi HTS543232L9SA00 320GB                   | 1         | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 18     | 25%     |
| Hitachi             | 9         | 9      | 18.75%  |
| WDC                 | 7         | 8      | 14.58%  |
| Samsung Electronics | 4         | 5      | 8.33%   |
| Kingston            | 4         | 6      | 8.33%   |
| Toshiba             | 3         | 4      | 6.25%   |
| LITEON              | 2         | 2      | 4.17%   |
| OCZ                 | 1         | 1      | 2.08%   |
| Micron Technology   | 1         | 1      | 2.08%   |
| Maximus             | 1         | 1      | 2.08%   |
| HGST                | 1         | 1      | 2.08%   |
| Gigabyte Technology | 1         | 2      | 2.08%   |
| Fujitsu             | 1         | 1      | 2.08%   |
| Apple               | 1         | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 18     | 32.43%  |
| Hitachi             | 9         | 9      | 24.32%  |
| WDC                 | 6         | 6      | 16.22%  |
| Samsung Electronics | 4         | 5      | 10.81%  |
| Toshiba             | 3         | 4      | 8.11%   |
| HGST                | 1         | 1      | 2.7%    |
| Fujitsu             | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 45     | 75.56%  |
| SSD  | 10        | 13     | 22.22%  |
| NVMe | 1         | 2      | 2.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model             | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| SanDisk pSSD 16GB | 1         | 1      | 100%    |

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
| Works    | 175       | 353    | 75.76%  |
| Malfunc  | 45        | 60     | 19.48%  |
| Detected | 10        | 17     | 4.33%   |
| Failed   | 1         | 1      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 163       | 57.8%   |
| AMD                          | 36        | 12.77%  |
| Samsung Electronics          | 19        | 6.74%   |
| ASMedia Technology           | 9         | 3.19%   |
| SanDisk                      | 7         | 2.48%   |
| Nvidia                       | 7         | 2.48%   |
| Micron/Crucial Technology    | 7         | 2.48%   |
| Phison Electronics           | 6         | 2.13%   |
| Silicon Motion               | 4         | 1.42%   |
| Shenzhen Longsys Electronics | 3         | 1.06%   |
| KIOXIA                       | 3         | 1.06%   |
| Kingston Technology Company  | 3         | 1.06%   |
| SK hynix                     | 2         | 0.71%   |
| Micron Technology            | 2         | 0.71%   |
| Marvell Technology Group     | 2         | 0.71%   |
| VIA Technologies             | 1         | 0.35%   |
| Union Memory (Shenzhen)      | 1         | 0.35%   |
| Toshiba                      | 1         | 0.35%   |
| Seagate Technology           | 1         | 0.35%   |
| Realtek Semiconductor        | 1         | 0.35%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.35%   |
| JMicron Technology           | 1         | 0.35%   |
| Hosin Global Electronics     | 1         | 0.35%   |
| Broadcom / LSI               | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 26        | 8.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 24        | 7.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 12        | 3.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 3.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 2.8%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 8         | 2.48%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 2.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7         | 2.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 7         | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 1.86%   |
| Intel unknown                                                                    | 6         | 1.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.86%   |
| AMD 400 Series Chipset SATA Controller                                           | 6         | 1.86%   |
| Intel SATA Controller [RAID mode]                                                | 5         | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 1.55%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5         | 1.55%   |
| AMD FCH SATA Controller D                                                        | 5         | 1.55%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 4         | 1.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 1.24%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 1.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.24%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 0.93%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 3         | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.93%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 0.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 0.93%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.62%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 2         | 0.62%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 2         | 0.62%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 0.62%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.62%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                        | 2         | 0.62%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 184       | 64.79%  |
| NVMe | 57        | 20.07%  |
| IDE  | 28        | 9.86%   |
| RAID | 14        | 4.93%   |
| SAS  | 1         | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 182       | 78.79%  |
| AMD     | 45        | 19.48%  |
| ARM     | 3         | 1.3%    |
| Unknown | 1         | 0.43%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz        | 7         | 3.02%   |
| Intel N100                               | 6         | 2.59%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 4         | 1.72%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 4         | 1.72%   |
| Intel Celeron N5105 @ 2.00GHz            | 4         | 1.72%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 4         | 1.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 3         | 1.29%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 3         | 1.29%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 3         | 1.29%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 3         | 1.29%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 3         | 1.29%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 2         | 0.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 0.86%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 0.86%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 2         | 0.86%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 2         | 0.86%   |
| Intel Core i5-9500 CPU @ 3.00GHz         | 2         | 0.86%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 2         | 0.86%   |
| Intel Core i5-7400 CPU @ 3.00GHz         | 2         | 0.86%   |
| Intel Core i5-7300U CPU @ 2.60GHz        | 2         | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 2         | 0.86%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 2         | 0.86%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz       | 2         | 0.86%   |
| Intel Core i5-4570T CPU @ 2.90GHz        | 2         | 0.86%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 2         | 0.86%   |
| Intel Core i5-2400S CPU @ 2.50GHz        | 2         | 0.86%   |
| Intel Core i3-3240 CPU @ 3.40GHz         | 2         | 0.86%   |
| Intel Core i3-2120 CPU @ 3.30GHz         | 2         | 0.86%   |
| Intel Core i3-10100 CPU @ 3.60GHz        | 2         | 0.86%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz     | 2         | 0.86%   |
| Intel Celeron CPU N3050 @ 1.60GHz        | 2         | 0.86%   |
| Intel Celeron CPU N2930 @ 1.83GHz        | 2         | 0.86%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2         | 0.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 2         | 0.86%   |
| ARM Cortex-A72 r0p3                      | 2         | 0.86%   |
| AMD Ryzen 5 4600H with Radeon Graphics   | 2         | 0.86%   |
| AMD Ryzen 5 2600 Six-Core Processor      | 2         | 0.86%   |
| AMD Ryzen 3 1200 Quad-Core Processor     | 2         | 0.86%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 2         | 0.86%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 48        | 20.69%  |
| Intel Celeron           | 34        | 14.66%  |
| Intel Core i7           | 25        | 10.78%  |
| Intel Core i3           | 21        | 9.05%   |
| Other                   | 16        | 6.9%    |
| Intel Core 2 Duo        | 14        | 6.03%   |
| AMD Ryzen 7             | 9         | 3.88%   |
| Intel Xeon              | 8         | 3.45%   |
| AMD Ryzen 5             | 6         | 2.59%   |
| AMD GX                  | 6         | 2.59%   |
| Intel Pentium           | 4         | 1.72%   |
| Intel Atom              | 4         | 1.72%   |
| AMD Ryzen 3             | 4         | 1.72%   |
| Intel Core 2 Quad       | 3         | 1.29%   |
| ARM Cortex              | 3         | 1.29%   |
| AMD FX                  | 3         | 1.29%   |
| AMD Athlon              | 3         | 1.29%   |
| AMD A4                  | 3         | 1.29%   |
| Intel Pentium Silver    | 1         | 0.43%   |
| Intel Pentium Gold      | 1         | 0.43%   |
| Intel Pentium Dual-Core | 1         | 0.43%   |
| Intel Pentium Dual      | 1         | 0.43%   |
| Intel Pentium 4         | 1         | 0.43%   |
| Intel Genuine           | 1         | 0.43%   |
| Intel Core i9           | 1         | 0.43%   |
| AMD Sempron             | 1         | 0.43%   |
| AMD Ryzen Threadripper  | 1         | 0.43%   |
| AMD Ryzen 9             | 1         | 0.43%   |
| AMD Phenom              | 1         | 0.43%   |
| AMD Opteron             | 1         | 0.43%   |
| AMD EPYC                | 1         | 0.43%   |
| AMD E2                  | 1         | 0.43%   |
| AMD E1                  | 1         | 0.43%   |
| AMD E                   | 1         | 0.43%   |
| AMD Athlon XP           | 1         | 0.43%   |
| AMD A8                  | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 107       | 46.32%  |
| 2       | 65        | 28.14%  |
| Unknown | 20        | 8.66%   |
| 8       | 13        | 5.63%   |
| 16      | 7         | 3.03%   |
| 6       | 7         | 3.03%   |
| 12      | 6         | 2.6%    |
| 1       | 4         | 1.73%   |
| 64      | 1         | 0.43%   |
| 14      | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 220       | 95.24%  |
| Unknown | 6         | 2.6%    |
| 2       | 5         | 2.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 130       | 56.28%  |
| 2       | 80        | 34.63%  |
| Unknown | 21        | 9.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Haswell         | 29        | 12.5%   |
| KabyLake        | 27        | 11.64%  |
| Silvermont      | 23        | 9.91%   |
| Unknown         | 21        | 9.05%   |
| Penryn          | 15        | 6.47%   |
| SandyBridge     | 12        | 5.17%   |
| IvyBridge       | 12        | 5.17%   |
| Zen+            | 10        | 4.31%   |
| Skylake         | 10        | 4.31%   |
| Goldmont plus   | 7         | 3.02%   |
| Core            | 7         | 3.02%   |
| Zen 2           | 6         | 2.59%   |
| Jaguar          | 6         | 2.59%   |
| CometLake       | 6         | 2.59%   |
| Broadwell       | 6         | 2.59%   |
| Piledriver      | 5         | 2.16%   |
| Zen 3           | 4         | 1.72%   |
| TigerLake       | 4         | 1.72%   |
| Westmere        | 3         | 1.29%   |
| Puma            | 3         | 1.29%   |
| Zen             | 2         | 0.86%   |
| P6              | 2         | 0.86%   |
| Excavator       | 2         | 0.86%   |
| Bonnell         | 2         | 0.86%   |
| NetBurst        | 1         | 0.43%   |
| Nehalem         | 1         | 0.43%   |
| K8 Hammer       | 1         | 0.43%   |
| K8 & K10 hybrid | 1         | 0.43%   |
| K6              | 1         | 0.43%   |
| K10             | 1         | 0.43%   |
| Goldmont        | 1         | 0.43%   |
| Bobcat          | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 146       | 59.84%  |
| Nvidia                               | 49        | 20.08%  |
| AMD                                  | 41        | 16.8%   |
| Matrox Electronics Systems           | 6         | 2.46%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.41%   |
| ASPEED Technology                    | 1         | 0.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 5.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 3.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 3.2%    |
| Intel HD Graphics 620                                                                    | 7         | 2.8%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7         | 2.8%    |
| Intel HD Graphics 530                                                                    | 6         | 2.4%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.4%    |
| Intel Alder Lake-N [UHD Graphics]                                                        | 6         | 2.4%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.4%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 2%      |
| Intel UHD Graphics 620                                                                   | 5         | 2%      |
| Intel JasperLake [UHD Graphics]                                                          | 5         | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.6%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1.6%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3         | 1.2%    |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.2%    |
| Intel HD Graphics 630                                                                    | 3         | 1.2%    |
| Intel HD Graphics 5500                                                                   | 3         | 1.2%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.2%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.2%    |
| AMD Kabini [Radeon HD 8330E]                                                             | 3         | 1.2%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.8%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.8%    |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 0.8%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.8%    |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.8%    |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 0.8%    |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 0.8%    |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 0.8%    |
| Intel HD Graphics 6000                                                                   | 2         | 0.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 125       | 53.65%  |
| 1 x Nvidia                               | 33        | 14.16%  |
| 1 x AMD                                  | 32        | 13.73%  |
| Intel + Nvidia                           | 10        | 4.29%   |
| 2 x Intel                                | 8         | 3.43%   |
| Other                                    | 7         | 3%      |
| 1 x Matrox                               | 5         | 2.15%   |
| Intel + AMD                              | 4         | 1.72%   |
| AMD + Nvidia                             | 4         | 1.72%   |
| 2 x Nvidia                               | 1         | 0.43%   |
| 2 x AMD                                  | 1         | 0.43%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.43%   |
| Nvidia + Matrox                          | 1         | 0.43%   |
| 1 x ASPEED                               | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 193       | 82.13%  |
| Proprietary | 26        | 11.06%  |
| Unknown     | 16        | 6.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 201       | 85.17%  |
| 1.01-2.0   | 9         | 3.81%   |
| 0.01-0.5   | 9         | 3.81%   |
| 5.01-6.0   | 5         | 2.12%   |
| 3.01-4.0   | 4         | 1.69%   |
| 2.01-3.0   | 3         | 1.27%   |
| 0.51-1.0   | 3         | 1.27%   |
| 7.01-8.0   | 2         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BenQ                    | 13        | 12.75%  |
| AU Optronics            | 11        | 10.78%  |
| Chimei Innolux          | 7         | 6.86%   |
| BOE                     | 7         | 6.86%   |
| Samsung Electronics     | 5         | 4.9%    |
| LG Display              | 5         | 4.9%    |
| Lenovo                  | 5         | 4.9%    |
| Goldstar                | 5         | 4.9%    |
| Dell                    | 5         | 4.9%    |
| Apple                   | 5         | 4.9%    |
| Chi Mei Optoelectronics | 4         | 3.92%   |
| Acer                    | 4         | 3.92%   |
| Hewlett-Packard         | 3         | 2.94%   |
| AOC                     | 3         | 2.94%   |
| Sharp                   | 2         | 1.96%   |
| Philips                 | 2         | 1.96%   |
| PANDA                   | 2         | 1.96%   |
| Vestel Elektronik       | 1         | 0.98%   |
| Plain Tree Systems      | 1         | 0.98%   |
| MSI                     | 1         | 0.98%   |
| Microstep               | 1         | 0.98%   |
| Mi                      | 1         | 0.98%   |
| Medion                  | 1         | 0.98%   |
| LGD                     | 1         | 0.98%   |
| LG Philips              | 1         | 0.98%   |
| Lenovo Group Limited    | 1         | 0.98%   |
| Impression              | 1         | 0.98%   |
| Fujitsu Siemens         | 1         | 0.98%   |
| CHD                     | 1         | 0.98%   |
| ASUSTek Computer        | 1         | 0.98%   |
| Ancor Communications    | 1         | 0.98%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                   | 3         | 2.91%   |
| AU Optronics LCD Monitor AUO462D 1920x1080 290x170mm 13.2-inch       | 3         | 2.91%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch     | 2         | 1.94%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                    | 2         | 1.94%   |
| AOC 2050W AOC2050 1600x900 430x240mm 19.4-inch                       | 2         | 1.94%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch   | 1         | 0.97%   |
| Sharp LCD Monitor SHP144D 3840x2160 280x160mm 12.7-inch              | 1         | 0.97%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch              | 1         | 0.97%   |
| Samsung Electronics T22C300 SAM0AB3 1920x1080 480x270mm 21.7-inch    | 1         | 0.97%   |
| Samsung Electronics S27H85x SAM0E0F 2560x1440 600x340mm 27.2-inch    | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch | 1         | 0.97%   |
| Plain Tree Systems LCD Monitor PTS0313 1600x1200 320x240mm 15.7-inch | 1         | 0.97%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 1         | 0.97%   |
| Philips 190S PHL083F 1280x1024 380x300mm 19.1-inch                   | 1         | 0.97%   |
| PANDA LCD Monitor NCP004D 1920x1080 340x190mm 15.3-inch              | 1         | 0.97%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch              | 1         | 0.97%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                      | 1         | 0.97%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080                          | 1         | 0.97%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                     | 1         | 0.97%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                  | 1         | 0.97%   |
| LGD LCD Monitor 5760x1080                                            | 1         | 0.97%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch          | 1         | 0.97%   |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch         | 1         | 0.97%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch         | 1         | 0.97%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch          | 1         | 0.97%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch         | 1         | 0.97%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch         | 1         | 0.97%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 530x300mm 24.0-inch             | 1         | 0.97%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch              | 1         | 0.97%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch              | 1         | 0.97%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch              | 1         | 0.97%   |
| Lenovo Group Limited LCD Monitor C24-25 1920x1080                    | 1         | 0.97%   |
| Lenovo C24-25 LEN66B0 1920x1080 530x300mm 24.0-inch                  | 1         | 0.97%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch               | 1         | 0.97%   |
| Hewlett-Packard x23LED HWP2912 1920x1080 510x290mm 23.1-inch         | 1         | 0.97%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch           | 1         | 0.97%   |
| Hewlett-Packard 22er HWP331B 1920x1080 500x300mm 23.0-inch           | 1         | 0.97%   |
| Goldstar W2242 GSM4B6F 1680x1050 490x320mm 23.0-inch                 | 1         | 0.97%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 46.46%  |
| 1366x768 (WXGA)    | 18        | 18.18%  |
| 1280x800 (WXGA)    | 8         | 8.08%   |
| 2560x1440 (QHD)    | 4         | 4.04%   |
| 1440x900 (WXGA+)   | 4         | 4.04%   |
| 1280x1024 (SXGA)   | 4         | 4.04%   |
| 3840x2160 (4K)     | 3         | 3.03%   |
| 1600x900 (HD+)     | 3         | 3.03%   |
| 5760x1080          | 1         | 1.01%   |
| 3840x1080          | 1         | 1.01%   |
| 3440x1440          | 1         | 1.01%   |
| 2048x1152          | 1         | 1.01%   |
| 1920x540           | 1         | 1.01%   |
| 1680x1050 (WSXGA+) | 1         | 1.01%   |
| 1600x1200          | 1         | 1.01%   |
| 1024x600           | 1         | 1.01%   |
| Unknown            | 1         | 1.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 25.49%  |
| 13      | 17        | 16.67%  |
| 24      | 14        | 13.73%  |
| 27      | 8         | 7.84%   |
| 19      | 7         | 6.86%   |
| Unknown | 6         | 5.88%   |
| 23      | 5         | 4.9%    |
| 21      | 5         | 4.9%    |
| 18      | 3         | 2.94%   |
| 12      | 3         | 2.94%   |
| 14      | 2         | 1.96%   |
| 48      | 1         | 0.98%   |
| 42      | 1         | 0.98%   |
| 34      | 1         | 0.98%   |
| 17      | 1         | 0.98%   |
| 11      | 1         | 0.98%   |
| 9       | 1         | 0.98%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 32.67%  |
| 501-600     | 25        | 24.75%  |
| 201-300     | 18        | 17.82%  |
| 401-500     | 12        | 11.88%  |
| Unknown     | 6         | 5.94%   |
| 351-400     | 4         | 3.96%   |
| 701-800     | 1         | 0.99%   |
| 1001-1500   | 1         | 0.99%   |
| 901-1000    | 1         | 0.99%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 71        | 73.2%   |
| 16/10   | 11        | 11.34%  |
| Unknown | 6         | 6.19%   |
| 5/4     | 4         | 4.12%   |
| 3/2     | 2         | 2.06%   |
| 4/3     | 1         | 1.03%   |
| 32/9    | 1         | 1.03%   |
| 21/9    | 1         | 1.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 22        | 22%     |
| 91-100         | 22        | 22%     |
| 81-90          | 12        | 12%     |
| 301-350        | 8         | 8%      |
| 71-80          | 7         | 7%      |
| 151-200        | 7         | 7%      |
| Unknown        | 6         | 6%      |
| 61-70          | 3         | 3%      |
| 141-150        | 3         | 3%      |
| 101-110        | 3         | 3%      |
| 501-1000       | 2         | 2%      |
| 51-60          | 1         | 1%      |
| 351-500        | 1         | 1%      |
| 41-50          | 1         | 1%      |
| 251-300        | 1         | 1%      |
| 111-120        | 1         | 1%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 34        | 34.34%  |
| 101-120       | 29        | 29.29%  |
| 121-160       | 21        | 21.21%  |
| 161-240       | 7         | 7.07%   |
| Unknown       | 6         | 6.06%   |
| More than 240 | 2         | 2.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 121       | 51.27%  |
| 1     | 108       | 45.76%  |
| 2     | 7         | 2.97%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 129       | 38.28%  |
| Realtek Semiconductor             | 118       | 35.01%  |
| Broadcom                          | 27        | 8.01%   |
| Qualcomm Atheros                  | 21        | 6.23%   |
| TP-Link                           | 6         | 1.78%   |
| Nvidia                            | 5         | 1.48%   |
| Marvell Technology Group          | 5         | 1.48%   |
| D-Link System                     | 4         | 1.19%   |
| Ralink Technology                 | 3         | 0.89%   |
| MediaTek                          | 3         | 0.89%   |
| Xiaomi                            | 2         | 0.59%   |
| Sierra Wireless                   | 2         | 0.59%   |
| Ralink                            | 2         | 0.59%   |
| IMC Networks                      | 2         | 0.59%   |
| Edimax Technology                 | 2         | 0.59%   |
| Samsung Electronics               | 1         | 0.3%    |
| Qualcomm Atheros Communications   | 1         | 0.3%    |
| Huawei Technologies               | 1         | 0.3%    |
| Ericsson Business Mobile Networks | 1         | 0.3%    |
| Belkin Components                 | 1         | 0.3%    |
| American Megatrends               | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 98        | 24.81%  |
| Intel I211 Gigabit Network Connection                                      | 15        | 3.8%    |
| Intel Ethernet Connection I217-LM                                          | 9         | 2.28%   |
| Intel Wi-Fi 6 AX200                                                        | 8         | 2.03%   |
| Intel 82583V Gigabit Network Connection                                    | 8         | 2.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 6         | 1.52%   |
| Intel Wireless 7260                                                        | 6         | 1.52%   |
| Intel I210 Gigabit Network Connection                                      | 6         | 1.52%   |
| Intel Ethernet Controller I226-V                                           | 6         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 5         | 1.27%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 1.27%   |
| Intel Wireless 7265                                                        | 5         | 1.27%   |
| Intel I350 Gigabit Network Connection                                      | 5         | 1.27%   |
| Intel Ethernet Controller I225-V                                           | 5         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                      | 5         | 1.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 5         | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 4         | 1.01%   |
| Nvidia MCP79 Ethernet                                                      | 4         | 1.01%   |
| Intel Wireless 3165                                                        | 4         | 1.01%   |
| Intel Wireless 3160                                                        | 4         | 1.01%   |
| Intel 82580 Gigabit Network Connection                                     | 4         | 1.01%   |
| Intel 82574L Gigabit Network Connection                                    | 4         | 1.01%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                           | 4         | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                          | 3         | 0.76%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 3         | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 3         | 0.76%   |
| Intel Wi-Fi 6 AX201                                                        | 3         | 0.76%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                       | 3         | 0.76%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 3         | 0.76%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter               | 3         | 0.76%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 3         | 0.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2         | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 2         | 0.51%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 2         | 0.51%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 0.51%   |
| Sierra Wireless EM7345 4G LTE                                              | 2         | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 43.8%   |
| Realtek Semiconductor           | 19        | 13.87%  |
| Broadcom                        | 17        | 12.41%  |
| Qualcomm Atheros                | 16        | 11.68%  |
| TP-Link                         | 6         | 4.38%   |
| Ralink Technology               | 3         | 2.19%   |
| MediaTek                        | 3         | 2.19%   |
| D-Link System                   | 3         | 2.19%   |
| Sierra Wireless                 | 2         | 1.46%   |
| Ralink                          | 2         | 1.46%   |
| IMC Networks                    | 2         | 1.46%   |
| Edimax Technology               | 2         | 1.46%   |
| Qualcomm Atheros Communications | 1         | 0.73%   |
| Belkin Components               | 1         | 0.73%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 8         | 5.63%   |
| Intel Wireless 7260                                                        | 6         | 4.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 5         | 3.52%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 3.52%   |
| Intel Wireless 7265                                                        | 5         | 3.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 2.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 2.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 4         | 2.82%   |
| Intel Wireless 3165                                                        | 4         | 2.82%   |
| Intel Wireless 3160                                                        | 4         | 2.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 3         | 2.11%   |
| Intel Wi-Fi 6 AX201                                                        | 3         | 2.11%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 3         | 2.11%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter               | 3         | 2.11%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 2.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 3         | 2.11%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 2         | 1.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 2         | 1.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 1.41%   |
| Sierra Wireless EM7345 4G LTE                                              | 2         | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 1.41%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 2         | 1.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 2         | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 2         | 1.41%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 2         | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 2         | 1.41%   |
| Intel WiFi Link 5100                                                       | 2         | 1.41%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                    | 2         | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 2         | 1.41%   |
| Intel Centrino Advanced-N 6235                                             | 2         | 1.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 2         | 1.41%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                       | 2         | 1.41%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]             | 2         | 1.41%   |
| Broadcom BCM43228 802.11a/b/g/n                                            | 2         | 1.41%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1         | 0.7%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                | 1         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1         | 0.7%    |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 0.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 1         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 110       | 46.61%  |
| Intel                    | 94        | 39.83%  |
| Broadcom                 | 12        | 5.08%   |
| Qualcomm Atheros         | 5         | 2.12%   |
| Nvidia                   | 5         | 2.12%   |
| Marvell Technology Group | 5         | 2.12%   |
| Xiaomi                   | 2         | 0.85%   |
| Samsung Electronics      | 1         | 0.42%   |
| D-Link System            | 1         | 0.42%   |
| American Megatrends      | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 98        | 39.36%  |
| Intel I211 Gigabit Network Connection                                  | 15        | 6.02%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 3.61%   |
| Intel 82583V Gigabit Network Connection                                | 8         | 3.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 2.41%   |
| Intel I210 Gigabit Network Connection                                  | 6         | 2.41%   |
| Intel Ethernet Controller I226-V                                       | 6         | 2.41%   |
| Intel I350 Gigabit Network Connection                                  | 5         | 2.01%   |
| Intel Ethernet Controller I225-V                                       | 5         | 2.01%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 2.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 2.01%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 1.61%   |
| Intel 82580 Gigabit Network Connection                                 | 4         | 1.61%   |
| Intel 82574L Gigabit Network Connection                                | 4         | 1.61%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 4         | 1.61%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 3         | 1.2%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 3         | 1.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.8%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2         | 0.8%    |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.8%    |
| Intel Ethernet Connection (3) I218-V                                   | 2         | 0.8%    |
| Intel Ethernet Connection (2) I219-V                                   | 2         | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.8%    |
| Intel 82576 Gigabit Network Connection                                 | 2         | 0.8%    |
| Intel 82575GB Gigabit Network Connection                               | 2         | 0.8%    |
| Intel 82567LM Gigabit Network Connection                               | 2         | 0.8%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 2         | 0.8%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 0.8%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.4%    |
| Nvidia MCP73 Ethernet                                                  | 1         | 0.4%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.4%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 213       | 63.2%   |
| WiFi     | 120       | 35.61%  |
| Modem    | 2         | 0.59%   |
| Unknown  | 2         | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 180       | 76.6%   |
| WiFi     | 54        | 22.98%  |
| Modem    | 1         | 0.43%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 94        | 40.52%  |
| 1     | 66        | 28.45%  |
| 4     | 22        | 9.48%   |
| 3     | 20        | 8.62%   |
| 5     | 12        | 5.17%   |
| 6     | 7         | 3.02%   |
| 8     | 5         | 2.16%   |
| 0     | 5         | 2.16%   |
| 15    | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 228       | 98.28%  |
| Yes  | 4         | 1.72%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 47.42%  |
| Realtek Semiconductor           | 11        | 11.34%  |
| Cambridge Silicon Radio         | 9         | 9.28%   |
| Apple                           | 7         | 7.22%   |
| Qualcomm Atheros Communications | 5         | 5.15%   |
| IMC Networks                    | 4         | 4.12%   |
| Foxconn / Hon Hai               | 4         | 4.12%   |
| Broadcom                        | 4         | 4.12%   |
| Hewlett-Packard                 | 3         | 3.09%   |
| Ralink                          | 2         | 2.06%   |
| ASUSTek Computer                | 2         | 2.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 21        | 21.43%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 9         | 9.18%   |
| Intel AX200 Bluetooth                                       | 8         | 8.16%   |
| Intel AX201 Bluetooth                                       | 6         | 6.12%   |
| Realtek Bluetooth Adapter                                   | 5         | 5.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 5.1%    |
| Realtek Bluetooth 4.2 Adapter                               | 3         | 3.06%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 3         | 3.06%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 3         | 3.06%   |
| Apple Bluetooth Host Controller                             | 3         | 3.06%   |
| Ralink RT3290 Bluetooth                                     | 2         | 2.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 2.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2.04%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 2.04%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 2.04%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.02%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.02%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.02%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 1.02%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.02%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.02%   |
| Intel AX211 Bluetooth                                       | 1         | 1.02%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.02%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 1         | 1.02%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 1.02%   |
| IMC Networks Bluetooth module                               | 1         | 1.02%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                   | 1         | 1.02%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.02%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 1.02%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.02%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.02%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.02%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.02%   |
| Broadcom 4371 Bluetooth 4.1 Adapter                         | 1         | 1.02%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.02%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 1         | 1.02%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.02%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 151       | 58.75%  |
| AMD                                          | 48        | 18.68%  |
| Nvidia                                       | 41        | 15.95%  |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 1.17%   |
| Cambridge Silicon Radio                      | 2         | 0.78%   |
| C-Media Electronics                          | 2         | 0.78%   |
| VIA Technologies                             | 1         | 0.39%   |
| Texas Instruments                            | 1         | 0.39%   |
| Logitech                                     | 1         | 0.39%   |
| Lenovo                                       | 1         | 0.39%   |
| Hewlett-Packard                              | 1         | 0.39%   |
| Generalplus Technology                       | 1         | 0.39%   |
| GEMBIRD                                      | 1         | 0.39%   |
| Ensoniq                                      | 1         | 0.39%   |
| Dell                                         | 1         | 0.39%   |
| BEHRINGER International                      | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 6%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 5%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 4.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 4%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 4%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 3.67%   |
| Intel 200 Series PCH HD Audio                                                                     | 8         | 2.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 2.67%   |
| AMD FCH Azalia Controller                                                                         | 8         | 2.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 2.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 2.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 2%      |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 1.67%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 1.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.67%   |
| Intel Jasper Lake HD Audio                                                                        | 5         | 1.67%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.67%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 5         | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 1.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.33%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 1.33%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 1.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.33%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 3         | 1%      |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1%      |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 1%      |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1%      |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.67%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 45        | 17.72%  |
| Kingston            | 44        | 17.32%  |
| Crucial             | 33        | 12.99%  |
| SK hynix            | 32        | 12.6%   |
| Micron Technology   | 22        | 8.66%   |
| Unknown             | 21        | 8.27%   |
| Ramaxel Technology  | 7         | 2.76%   |
| Corsair             | 7         | 2.76%   |
| Unknown             | 7         | 2.76%   |
| Nanya Technology    | 5         | 1.97%   |
| G.Skill             | 5         | 1.97%   |
| Elpida              | 4         | 1.57%   |
| Unknown (ABCD)      | 2         | 0.79%   |
| Unknown (0B45)      | 2         | 0.79%   |
| Transcend           | 2         | 0.79%   |
| Hewlett-Packard     | 2         | 0.79%   |
| Goldenmars          | 2         | 0.79%   |
| ASint Technology    | 2         | 0.79%   |
| Apacer              | 2         | 0.79%   |
| A-DATA Technology   | 2         | 0.79%   |
| Wodposit            | 1         | 0.39%   |
| Unknown (0x0080)    | 1         | 0.39%   |
| Toshiba             | 1         | 0.39%   |
| Kimtigo             | 1         | 0.39%   |
| GOODRAM             | 1         | 0.39%   |
| Essencore           | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 7         | 2.47%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 4         | 1.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 1.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 2         | 0.71%   |
| Unknown (0B45) RAM WPBC26D416SWM-16G 16GB SODIMM DDR4 2667MT/s | 2         | 0.71%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB DIMM DDR3 1600MT/s           | 2         | 0.71%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.71%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 2         | 0.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 2         | 0.71%   |
| Samsung RAM M471A1K43EB1-CWE 16GB SODIMM DDR4 3200MT/s         | 2         | 0.71%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 0.71%   |
| Micron RAM 18KSF51272AZ-1G4M1 4GB DIMM DDR3 1333MT/s           | 2         | 0.71%   |
| Kingston RAM KVR13LS9/4 4GB SODIMM DDR3 1333MT/s               | 2         | 0.71%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 2         | 0.71%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s         | 2         | 0.71%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 2         | 0.71%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1333MT/s          | 2         | 0.71%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s          | 2         | 0.71%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s        | 2         | 0.71%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s          | 2         | 0.71%   |
| Crucial RAM CT16G4SFRA266.M8FB 16GB SODIMM DDR4 2667MT/s       | 2         | 0.71%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s        | 2         | 0.71%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 2         | 0.71%   |
| Wodposit RAM WPBC26D416SWM-16G 16GB SODIMM DDR4 2667MT/s       | 1         | 0.35%   |
| Unknown RAM WPBH16D316SWA-8G 8GB DIMM DDR3 1600MT/s            | 1         | 0.35%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.35%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                      | 1         | 0.35%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                 | 1         | 0.35%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                        | 1         | 0.35%   |
| Unknown RAM Module 512MB DIMM 400MT/s                          | 1         | 0.35%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.35%   |
| Unknown RAM Module 4GB SODIMM DDR3                             | 1         | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 1         | 0.35%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 1         | 0.35%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                        | 1         | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR3                             | 1         | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR 1066MT/s                       | 1         | 0.35%   |
| Unknown RAM Module 256MB DIMM 333MT/s                          | 1         | 0.35%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                     | 1         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 101       | 47.87%  |
| DDR4    | 71        | 33.65%  |
| DDR2    | 17        | 8.06%   |
| DDR5    | 5         | 2.37%   |
| LPDDR4  | 4         | 1.9%    |
| LPDDR3  | 4         | 1.9%    |
| Unknown | 4         | 1.9%    |
| SDRAM   | 3         | 1.42%   |
| LPDDR5  | 1         | 0.47%   |
| DDR     | 1         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 105       | 49.53%  |
| DIMM         | 97        | 45.75%  |
| Row Of Chips | 9         | 4.25%   |
| FB-DIMM      | 1         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 82        | 35.04%  |
| 8192  | 80        | 34.19%  |
| 16384 | 32        | 13.68%  |
| 2048  | 29        | 12.39%  |
| 1024  | 7         | 2.99%   |
| 32768 | 2         | 0.85%   |
| 512   | 1         | 0.43%   |
| 256   | 1         | 0.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 80        | 34.93%  |
| 2400    | 26        | 11.35%  |
| 3200    | 25        | 10.92%  |
| 1333    | 19        | 8.3%    |
| 2667    | 17        | 7.42%   |
| 2133    | 9         | 3.93%   |
| 667     | 9         | 3.93%   |
| 800     | 8         | 3.49%   |
| 4800    | 4         | 1.75%   |
| 2666    | 4         | 1.75%   |
| 1067    | 4         | 1.75%   |
| 1867    | 3         | 1.31%   |
| 1866    | 3         | 1.31%   |
| 1334    | 3         | 1.31%   |
| 1066    | 3         | 1.31%   |
| 6400    | 2         | 0.87%   |
| Unknown | 2         | 0.87%   |
| 4267    | 1         | 0.44%   |
| 3733    | 1         | 0.44%   |
| 3600    | 1         | 0.44%   |
| 2048    | 1         | 0.44%   |
| 1332    | 1         | 0.44%   |
| 1033    | 1         | 0.44%   |
| 400     | 1         | 0.44%   |
| 333     | 1         | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 50%     |
| Brother HL-L2340D series                                                                                          | 1         | 50%     |

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
| Chicony Electronics                    | 11        | 17.74%  |
| Sunplus Innovation Technology          | 7         | 11.29%  |
| Quanta                                 | 5         | 8.06%   |
| Bison Electronics                      | 5         | 8.06%   |
| Realtek Semiconductor                  | 4         | 6.45%   |
| Microdia                               | 4         | 6.45%   |
| IMC Networks                           | 4         | 6.45%   |
| Suyin                                  | 3         | 4.84%   |
| Alcor Micro                            | 3         | 4.84%   |
| Logitech                               | 2         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.23%   |
| Z-Star Microelectronics                | 1         | 1.61%   |
| USB Camera                             | 1         | 1.61%   |
| Syntek                                 | 1         | 1.61%   |
| Supreme Electronics                    | 1         | 1.61%   |
| Silicon Motion                         | 1         | 1.61%   |
| Ricoh                                  | 1         | 1.61%   |
| OmniVision Technologies                | 1         | 1.61%   |
| Luxvisions Innotech Limited            | 1         | 1.61%   |
| Lite-On Technology                     | 1         | 1.61%   |
| Importek                               | 1         | 1.61%   |
| HD WEBCAM                              | 1         | 1.61%   |
| Apple                                  | 1         | 1.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 4         | 6.45%   |
| Sunplus Integrated_Webcam_HD                         | 3         | 4.84%   |
| Quanta HP TrueVision HD Camera                       | 3         | 4.84%   |
| Realtek USB Camera                                   | 2         | 3.23%   |
| IMC Networks Realtek PC Camera                       | 2         | 3.23%   |
| Bison Integrated Camera                              | 2         | 3.23%   |
| Z-Star Vega USB 2.0 Camera                           | 1         | 1.61%   |
| USB Camera USB Camera                                | 1         | 1.61%   |
| Syntek EasyCamera                                    | 1         | 1.61%   |
| Suyin Integrated_Webcam_HD                           | 1         | 1.61%   |
| Suyin HP webcam [dv6-1190en]                         | 1         | 1.61%   |
| Suyin Acer/HP Integrated Webcam [CN0314]             | 1         | 1.61%   |
| Supreme Realtek PC Camera                            | 1         | 1.61%   |
| Sunplus Integrated Camera                            | 1         | 1.61%   |
| Sunplus HP HD Webcam [Fixed]                         | 1         | 1.61%   |
| Sunplus HD WebCam                                    | 1         | 1.61%   |
| Sunplus Asus Webcam                                  | 1         | 1.61%   |
| Silicon Motion Realtek USB 2.0 PC Camera             | 1         | 1.61%   |
| Ricoh Integrated Webcam                              | 1         | 1.61%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.61%   |
| Realtek Acer 640 x 480 laptop camera                 | 1         | 1.61%   |
| Quanta Realtek DMFT RGB                              | 1         | 1.61%   |
| Quanta HP True Vision 5MP Camera                     | 1         | 1.61%   |
| OmniVision Monitor Webcam                            | 1         | 1.61%   |
| Microdia Sonix USB 2.0 Camera                        | 1         | 1.61%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.61%   |
| Microdia Integrated Webcam                           | 1         | 1.61%   |
| Microdia HP Webcam                                   | 1         | 1.61%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.61%   |
| Logitech C505 HD Webcam                              | 1         | 1.61%   |
| Logitech BRIO Ultra HD Webcam                        | 1         | 1.61%   |
| Lite-On Integrated Camera                            | 1         | 1.61%   |
| Importek HP Webcam                                   | 1         | 1.61%   |
| IMC Networks Integrated Camera                       | 1         | 1.61%   |
| IMC Networks 2M Integrated Webcam                    | 1         | 1.61%   |
| HD WEBCAM HD WEBCAM                                  | 1         | 1.61%   |
| Chicony WebCam                                       | 1         | 1.61%   |
| Chicony USB2.0 0.3M UVC WebCam                       | 1         | 1.61%   |
| Chicony USB 2.0 Camera                               | 1         | 1.61%   |
| Chicony Lenovo EasyCamera                            | 1         | 1.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 53.33%  |
| STMicroelectronics         | 2         | 13.33%  |
| Upek                       | 1         | 6.67%   |
| Synaptics                  | 1         | 6.67%   |
| Shenzhen Goodix Technology | 1         | 6.67%   |
| Fingerprint Cards          | 1         | 6.67%   |
| Elan Microelectronics      | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                                  | 2         | 13.33%  |
| Validity Sensors VFS101 Fingerprint Reader               | 2         | 13.33%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 13.33%  |
| STMicroelectronics Fingerprint Reader                    | 2         | 13.33%  |
| Validity Sensors Synaptics WBDI                          | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                     | 1         | 6.67%   |
| Upek TCS5B Fingerprint sensor                            | 1         | 6.67%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Shenzhen Goodix  Fingerprint Device                      | 1         | 6.67%   |
| Fingerprint Cards FPC Fingerprint Reader                 | 1         | 6.67%   |
| Elan Fingerprint Sensor                                  | 1         | 6.67%   |

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
| 1     | 104       | 42.8%   |
| 0     | 69        | 28.4%   |
| 2     | 41        | 16.87%  |
| 3     | 20        | 8.23%   |
| 4     | 6         | 2.47%   |
| 5     | 2         | 0.82%   |
| 6     | 1         | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 128       | 50%     |
| Net/wireless             | 44        | 17.19%  |
| Bluetooth                | 32        | 12.5%   |
| Card reader              | 18        | 7.03%   |
| Fingerprint reader       | 12        | 4.69%   |
| Graphics card            | 6         | 2.34%   |
| Network                  | 5         | 1.95%   |
| Sound                    | 4         | 1.56%   |
| Firewire controller      | 4         | 1.56%   |
| Storage/ata              | 1         | 0.39%   |
| Storage                  | 1         | 0.39%   |
| Net/ethernet             | 1         | 0.39%   |

