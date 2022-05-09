BSD in Canada - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Canada.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Canada/Desktop/README.md) and [notebooks](/Location/Canada/Notebook/README.md).

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

Total: 370

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Fujitsu       | LIFEBOOK E752               | Notebook    | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [daed3f9401](https://bsd-hardware.info/?probe=daed3f9401) | May 06, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [cf2f288b93](https://bsd-hardware.info/?probe=cf2f288b93) | May 04, 2022 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| HP            | 1495                        | Desktop     | [6e0f1cc72e](https://bsd-hardware.info/?probe=6e0f1cc72e) | Apr 29, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [586d311314](https://bsd-hardware.info/?probe=586d311314) | Apr 28, 2022 |
| HP            | 1998                        | Desktop     | [1244e0583b](https://bsd-hardware.info/?probe=1244e0583b) | Apr 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [b3d5defed1](https://bsd-hardware.info/?probe=b3d5defed1) | Apr 26, 2022 |
| Supermicro    | X12SCZ-TLN4FA               | Server      | [2a9ac1e6ee](https://bsd-hardware.info/?probe=2a9ac1e6ee) | Apr 23, 2022 |
| Sophos        | SG                          | Firewall    | [cbd2585bf3](https://bsd-hardware.info/?probe=cbd2585bf3) | Apr 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [4166c67369](https://bsd-hardware.info/?probe=4166c67369) | Apr 20, 2022 |
| Dell          | G5 5090                     | Desktop     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [01945539d9](https://bsd-hardware.info/?probe=01945539d9) | Apr 17, 2022 |
| Sophos        | SG                          | Firewall    | [ed297e4274](https://bsd-hardware.info/?probe=ed297e4274) | Apr 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [979e868c51](https://bsd-hardware.info/?probe=979e868c51) | Apr 16, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [4023d86091](https://bsd-hardware.info/?probe=4023d86091) | Apr 15, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [29be552d6a](https://bsd-hardware.info/?probe=29be552d6a) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [1173feae11](https://bsd-hardware.info/?probe=1173feae11) | Apr 13, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [6dac56f3bb](https://bsd-hardware.info/?probe=6dac56f3bb) | Apr 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [641d1574ce](https://bsd-hardware.info/?probe=641d1574ce) | Apr 11, 2022 |
| Toshiba       | Satellite Pro T130          | Notebook    | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| HP            | 8103 A01                    | Mini pc     | [1fa67a8d17](https://bsd-hardware.info/?probe=1fa67a8d17) | Apr 04, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [e79f120d82](https://bsd-hardware.info/?probe=e79f120d82) | Apr 01, 2022 |
| Dell          | 081N4V A06                  | Server      | [700e5de168](https://bsd-hardware.info/?probe=700e5de168) | Apr 01, 2022 |
| PC Engines    | APU                         | Desktop     | [e266947055](https://bsd-hardware.info/?probe=e266947055) | Mar 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [ef1a743845](https://bsd-hardware.info/?probe=ef1a743845) | Mar 28, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [1176fca4ab](https://bsd-hardware.info/?probe=1176fca4ab) | Mar 27, 2022 |
| ASUSTek       | ET2411_W8                   | All in one  | [fb186da68e](https://bsd-hardware.info/?probe=fb186da68e) | Mar 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [d0e7b62eda](https://bsd-hardware.info/?probe=d0e7b62eda) | Mar 25, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cf576c571d](https://bsd-hardware.info/?probe=cf576c571d) | Mar 22, 2022 |
| HP            | 213D A01                    | Desktop     | [6baba4f9c1](https://bsd-hardware.info/?probe=6baba4f9c1) | Mar 20, 2022 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [3727ba82af](https://bsd-hardware.info/?probe=3727ba82af) | Mar 19, 2022 |
| ASUSTek       | ET2411_W8                   | All in one  | [b95da98f21](https://bsd-hardware.info/?probe=b95da98f21) | Mar 17, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [f22a45488b](https://bsd-hardware.info/?probe=f22a45488b) | Mar 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a5fd383c40](https://bsd-hardware.info/?probe=a5fd383c40) | Mar 14, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [6024b9491d](https://bsd-hardware.info/?probe=6024b9491d) | Mar 06, 2022 |
| MSI           | MS-7388                     | Desktop     | [ad8209dbdb](https://bsd-hardware.info/?probe=ad8209dbdb) | Mar 05, 2022 |
| MSI           | MS-7388                     | Desktop     | [a59bca8bde](https://bsd-hardware.info/?probe=a59bca8bde) | Mar 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [a6abb45607](https://bsd-hardware.info/?probe=a6abb45607) | Mar 04, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [589f10057f](https://bsd-hardware.info/?probe=589f10057f) | Mar 01, 2022 |
| Intel         | H81U                        | Notebook    | [71068a0577](https://bsd-hardware.info/?probe=71068a0577) | Mar 01, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [e14fd85d4a](https://bsd-hardware.info/?probe=e14fd85d4a) | Feb 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [6b2550968e](https://bsd-hardware.info/?probe=6b2550968e) | Feb 23, 2022 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [5f4e1c30b8](https://bsd-hardware.info/?probe=5f4e1c30b8) | Feb 19, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b69015f0e0](https://bsd-hardware.info/?probe=b69015f0e0) | Feb 16, 2022 |
| PC Engines    | apu4                        | Desktop     | [09f27a0f23](https://bsd-hardware.info/?probe=09f27a0f23) | Feb 14, 2022 |
| Protectli     | FW6                         | Desktop     | [d33b2f1244](https://bsd-hardware.info/?probe=d33b2f1244) | Feb 13, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [04bee98c7e](https://bsd-hardware.info/?probe=04bee98c7e) | Feb 12, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [bd63b06ea9](https://bsd-hardware.info/?probe=bd63b06ea9) | Feb 11, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [12ccb8699b](https://bsd-hardware.info/?probe=12ccb8699b) | Feb 08, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [0d3b560aad](https://bsd-hardware.info/?probe=0d3b560aad) | Feb 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [3dabf0503d](https://bsd-hardware.info/?probe=3dabf0503d) | Feb 08, 2022 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [53abdfa3b1](https://bsd-hardware.info/?probe=53abdfa3b1) | Feb 07, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [1dafdcc71a](https://bsd-hardware.info/?probe=1dafdcc71a) | Feb 05, 2022 |
| Supermicro    | H11DSi                      | Server      | [4e41dc7f8b](https://bsd-hardware.info/?probe=4e41dc7f8b) | Feb 03, 2022 |
| ASRock        | J4105M                      | Desktop     | [09b9d104b9](https://bsd-hardware.info/?probe=09b9d104b9) | Feb 03, 2022 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [342915fccd](https://bsd-hardware.info/?probe=342915fccd) | Feb 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [07d565ad8c](https://bsd-hardware.info/?probe=07d565ad8c) | Feb 02, 2022 |
| Dell          | 00NH4P A03                  | Server      | [1fe915b90a](https://bsd-hardware.info/?probe=1fe915b90a) | Feb 01, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [83975bd2b1](https://bsd-hardware.info/?probe=83975bd2b1) | Jan 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ff629a490d](https://bsd-hardware.info/?probe=ff629a490d) | Jan 29, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4b17ef7a18](https://bsd-hardware.info/?probe=4b17ef7a18) | Jan 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4df3db0379](https://bsd-hardware.info/?probe=4df3db0379) | Jan 26, 2022 |
| Sophos        | SG                          | Firewall    | [3c6601bf94](https://bsd-hardware.info/?probe=3c6601bf94) | Jan 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [5ea082ddf9](https://bsd-hardware.info/?probe=5ea082ddf9) | Jan 13, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | Notebook    | [4ae2360503](https://bsd-hardware.info/?probe=4ae2360503) | Jan 11, 2022 |
| ASUSTek       | P8Z68-M PRO                 | Desktop     | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| Dell          | 0DT021 A02                  | Server      | [d1fdef3d4d](https://bsd-hardware.info/?probe=d1fdef3d4d) | Jan 09, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7863226bbe](https://bsd-hardware.info/?probe=7863226bbe) | Jan 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [ded64258b4](https://bsd-hardware.info/?probe=ded64258b4) | Jan 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d607c1d19](https://bsd-hardware.info/?probe=8d607c1d19) | Jan 03, 2022 |
| Toshiba       | TECRA Z40-B                 | Notebook    | [d498fcd3f8](https://bsd-hardware.info/?probe=d498fcd3f8) | Jan 02, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [a07366611d](https://bsd-hardware.info/?probe=a07366611d) | Jan 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [c183bdd5af](https://bsd-hardware.info/?probe=c183bdd5af) | Jan 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [4848e4009f](https://bsd-hardware.info/?probe=4848e4009f) | Jan 01, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [7d47d0db05](https://bsd-hardware.info/?probe=7d47d0db05) | Dec 30, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [c3884fac44](https://bsd-hardware.info/?probe=c3884fac44) | Dec 30, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [259b5cc7b2](https://bsd-hardware.info/?probe=259b5cc7b2) | Dec 28, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [f4648747b0](https://bsd-hardware.info/?probe=f4648747b0) | Dec 22, 2021 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [839eed529d](https://bsd-hardware.info/?probe=839eed529d) | Dec 21, 2021 |
| Lenovo        | ThinkPad X280 20KF001UUS    | Notebook    | [5b9001009e](https://bsd-hardware.info/?probe=5b9001009e) | Dec 20, 2021 |
| HP            | 8103 A01                    | Mini pc     | [0138a82561](https://bsd-hardware.info/?probe=0138a82561) | Dec 18, 2021 |
| Quanta        | 2AC7 011                    | Desktop     | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| HP            | 843B                        | Desktop     | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP            | 843B                        | Desktop     | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [a86326d049](https://bsd-hardware.info/?probe=a86326d049) | Dec 11, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [624041b5db](https://bsd-hardware.info/?probe=624041b5db) | Dec 09, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [79d9964300](https://bsd-hardware.info/?probe=79d9964300) | Dec 02, 2021 |
| Dell          | 051FJ8 A01                  | Desktop     | [ccfb8336a0](https://bsd-hardware.info/?probe=ccfb8336a0) | Dec 01, 2021 |
| HP            | 843B                        | Desktop     | [376e006a40](https://bsd-hardware.info/?probe=376e006a40) | Nov 30, 2021 |
| HP            | 843B                        | Desktop     | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| HP            | 843B                        | Desktop     | [a8ac0e9efb](https://bsd-hardware.info/?probe=a8ac0e9efb) | Nov 29, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [7154bea350](https://bsd-hardware.info/?probe=7154bea350) | Nov 27, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [dc9d060c7f](https://bsd-hardware.info/?probe=dc9d060c7f) | Nov 27, 2021 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [339779baad](https://bsd-hardware.info/?probe=339779baad) | Nov 26, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [49a0a07721](https://bsd-hardware.info/?probe=49a0a07721) | Nov 25, 2021 |
| Supermicro    | X12SCZ-TLN4FA               | Server      | [3debb4fe22](https://bsd-hardware.info/?probe=3debb4fe22) | Nov 24, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [f922794063](https://bsd-hardware.info/?probe=f922794063) | Nov 22, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [1802f6c891](https://bsd-hardware.info/?probe=1802f6c891) | Nov 21, 2021 |
| Acer          | Aspire X1800                | Desktop     | [a26bc8f2b3](https://bsd-hardware.info/?probe=a26bc8f2b3) | Nov 14, 2021 |
| Gigabyte      | MRZNVMS-00                  | Desktop     | [817cb3e603](https://bsd-hardware.info/?probe=817cb3e603) | Nov 12, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b0a51ac0af](https://bsd-hardware.info/?probe=b0a51ac0af) | Nov 11, 2021 |
| Dell          | Studio 1747                 | Notebook    | [7ab6b58d69](https://bsd-hardware.info/?probe=7ab6b58d69) | Nov 11, 2021 |
| Acer          | Aspire X1800                | Desktop     | [970387f9d9](https://bsd-hardware.info/?probe=970387f9d9) | Nov 09, 2021 |
| Protectli     | FW6E                        | Desktop     | [ebe5b24dee](https://bsd-hardware.info/?probe=ebe5b24dee) | Nov 08, 2021 |
| Protectli     | FW6E                        | Desktop     | [6c12084410](https://bsd-hardware.info/?probe=6c12084410) | Nov 07, 2021 |
| Unknown       | Unknown                     | Firewall    | [053ec385f8](https://bsd-hardware.info/?probe=053ec385f8) | Nov 04, 2021 |
| Acer          | Aspire X1800                | Desktop     | [99b5ab3e42](https://bsd-hardware.info/?probe=99b5ab3e42) | Nov 04, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [bf37ad85e7](https://bsd-hardware.info/?probe=bf37ad85e7) | Nov 03, 2021 |
| Unknown       | Unknown                     | Desktop     | [579cf2ac1a](https://bsd-hardware.info/?probe=579cf2ac1a) | Oct 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7abc8386ec](https://bsd-hardware.info/?probe=7abc8386ec) | Oct 31, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [721ef0235c](https://bsd-hardware.info/?probe=721ef0235c) | Oct 30, 2021 |
| HP            | 843B                        | Desktop     | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [c3d6cddf87](https://bsd-hardware.info/?probe=c3d6cddf87) | Oct 25, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [9e254ab443](https://bsd-hardware.info/?probe=9e254ab443) | Oct 23, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [1d5e3e5bc3](https://bsd-hardware.info/?probe=1d5e3e5bc3) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [3337c00433](https://bsd-hardware.info/?probe=3337c00433) | Oct 22, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [5c8f3708b1](https://bsd-hardware.info/?probe=5c8f3708b1) | Oct 21, 2021 |
| Dell          | Studio 1747                 | Notebook    | [ed704cde92](https://bsd-hardware.info/?probe=ed704cde92) | Oct 20, 2021 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [93f9e34d05](https://bsd-hardware.info/?probe=93f9e34d05) | Oct 19, 2021 |
| Dell          | Studio 1747                 | Notebook    | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [b20953f2f4](https://bsd-hardware.info/?probe=b20953f2f4) | Oct 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [bbdfde368b](https://bsd-hardware.info/?probe=bbdfde368b) | Oct 18, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [1a5bae2227](https://bsd-hardware.info/?probe=1a5bae2227) | Oct 15, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [77101a00b3](https://bsd-hardware.info/?probe=77101a00b3) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |
| Acer          | Aspire X1800                | Desktop     | [cc419789f8](https://bsd-hardware.info/?probe=cc419789f8) | Oct 08, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | Desktop     | [00bafc5f7c](https://bsd-hardware.info/?probe=00bafc5f7c) | Oct 03, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [76866f2db7](https://bsd-hardware.info/?probe=76866f2db7) | Oct 01, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [319470ebbd](https://bsd-hardware.info/?probe=319470ebbd) | Oct 01, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [36a5bc62bf](https://bsd-hardware.info/?probe=36a5bc62bf) | Sep 27, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [01e33c8399](https://bsd-hardware.info/?probe=01e33c8399) | Sep 26, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [137654a2f8](https://bsd-hardware.info/?probe=137654a2f8) | Sep 24, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [ca41aa2f67](https://bsd-hardware.info/?probe=ca41aa2f67) | Sep 23, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [8dc995488e](https://bsd-hardware.info/?probe=8dc995488e) | Sep 13, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [3b709e37c2](https://bsd-hardware.info/?probe=3b709e37c2) | Sep 12, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [1feb22dc52](https://bsd-hardware.info/?probe=1feb22dc52) | Sep 12, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [0e81fce9eb](https://bsd-hardware.info/?probe=0e81fce9eb) | Sep 10, 2021 |
| HP            | 212B                        | Desktop     | [d3894b9f37](https://bsd-hardware.info/?probe=d3894b9f37) | Sep 10, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [df08c4e6d3](https://bsd-hardware.info/?probe=df08c4e6d3) | Sep 09, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [c64c51359c](https://bsd-hardware.info/?probe=c64c51359c) | Sep 09, 2021 |
| MSI           | CSM-B85M-P32                | Desktop     | [e960bc2548](https://bsd-hardware.info/?probe=e960bc2548) | Sep 01, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [3dca10264a](https://bsd-hardware.info/?probe=3dca10264a) | Aug 29, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| HP            | 1589                        | Desktop     | [4d51cc9c4b](https://bsd-hardware.info/?probe=4d51cc9c4b) | Aug 24, 2021 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [da3e8986a3](https://bsd-hardware.info/?probe=da3e8986a3) | Aug 22, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [75f3efc215](https://bsd-hardware.info/?probe=75f3efc215) | Aug 18, 2021 |
| Supermicro    | X11SSW-F                    | Server      | [766c25105d](https://bsd-hardware.info/?probe=766c25105d) | Aug 17, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [bd94ad09ef](https://bsd-hardware.info/?probe=bd94ad09ef) | Aug 12, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | Desktop     | [94201b7633](https://bsd-hardware.info/?probe=94201b7633) | Aug 10, 2021 |
| HP            | Notebook                    | Notebook    | [a3c3297cd2](https://bsd-hardware.info/?probe=a3c3297cd2) | Aug 08, 2021 |
| HP            | Notebook                    | Notebook    | [0c316107a4](https://bsd-hardware.info/?probe=0c316107a4) | Aug 08, 2021 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [6da61be169](https://bsd-hardware.info/?probe=6da61be169) | Aug 08, 2021 |
| ZOTAC         | Board                       | Mini pc     | [e441e5484c](https://bsd-hardware.info/?probe=e441e5484c) | Aug 08, 2021 |
| IBM           | 00Y8494                     | Server      | [92ed5993f4](https://bsd-hardware.info/?probe=92ed5993f4) | Aug 07, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [535b577563](https://bsd-hardware.info/?probe=535b577563) | Aug 03, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [783c2ba254](https://bsd-hardware.info/?probe=783c2ba254) | Aug 02, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [b434d9bfb8](https://bsd-hardware.info/?probe=b434d9bfb8) | Aug 02, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [4d118404a8](https://bsd-hardware.info/?probe=4d118404a8) | Jul 29, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [1c3ec31075](https://bsd-hardware.info/?probe=1c3ec31075) | Jul 28, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [fc13802cd3](https://bsd-hardware.info/?probe=fc13802cd3) | Jul 19, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [5697d53687](https://bsd-hardware.info/?probe=5697d53687) | Jul 19, 2021 |
| IBM           | 00Y8494                     | Server      | [76a17b83e5](https://bsd-hardware.info/?probe=76a17b83e5) | Jul 19, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [c7dbe473bc](https://bsd-hardware.info/?probe=c7dbe473bc) | Jul 17, 2021 |
| Lenovo        | SHARKBAY 0C48431 PRO        | Desktop     | [0a1fa8924e](https://bsd-hardware.info/?probe=0a1fa8924e) | Jul 17, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [b86c2cfc99](https://bsd-hardware.info/?probe=b86c2cfc99) | Jul 16, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [4bd9c0bbb8](https://bsd-hardware.info/?probe=4bd9c0bbb8) | Jul 11, 2021 |
| PC Engines    | apu4                        | Desktop     | [51163b13ef](https://bsd-hardware.info/?probe=51163b13ef) | Jul 11, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [59a1b5f761](https://bsd-hardware.info/?probe=59a1b5f761) | Jul 10, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [f07b30b043](https://bsd-hardware.info/?probe=f07b30b043) | Jul 03, 2021 |
| Gigabyte      | MMLP3AP-00                  | Notebook    | [168e674b55](https://bsd-hardware.info/?probe=168e674b55) | Jul 03, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [d4f6eea56a](https://bsd-hardware.info/?probe=d4f6eea56a) | Jun 27, 2021 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [a326fd4061](https://bsd-hardware.info/?probe=a326fd4061) | Jun 20, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [ef7104e237](https://bsd-hardware.info/?probe=ef7104e237) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX H370-I GAMING     | Desktop     | [d2dd261a2a](https://bsd-hardware.info/?probe=d2dd261a2a) | Jun 20, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [6aa5f8046e](https://bsd-hardware.info/?probe=6aa5f8046e) | Jun 19, 2021 |
| Dell          | Inspiron 15-7579            | Notebook    | [4b8b5f7918](https://bsd-hardware.info/?probe=4b8b5f7918) | Jun 19, 2021 |
| Shuttle       | FS110                       | Desktop     | [9b4093c9a1](https://bsd-hardware.info/?probe=9b4093c9a1) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [7db1345e97](https://bsd-hardware.info/?probe=7db1345e97) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [cbade775b6](https://bsd-hardware.info/?probe=cbade775b6) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [80052d6cdc](https://bsd-hardware.info/?probe=80052d6cdc) | Jun 15, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [34df628c87](https://bsd-hardware.info/?probe=34df628c87) | Jun 14, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [73748c3197](https://bsd-hardware.info/?probe=73748c3197) | Jun 13, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [83cf0bb0fb](https://bsd-hardware.info/?probe=83cf0bb0fb) | Jun 12, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [d239ee4916](https://bsd-hardware.info/?probe=d239ee4916) | Jun 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [459bf008e9](https://bsd-hardware.info/?probe=459bf008e9) | Jun 12, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [d09c80b4d4](https://bsd-hardware.info/?probe=d09c80b4d4) | Jun 11, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [a6d47afc18](https://bsd-hardware.info/?probe=a6d47afc18) | Jun 09, 2021 |
| HP            | 805D                        | Desktop     | [dc4e61ecd4](https://bsd-hardware.info/?probe=dc4e61ecd4) | Jun 07, 2021 |
| HP            | 8523 A01                    | Mini pc     | [d563d65a91](https://bsd-hardware.info/?probe=d563d65a91) | Jun 05, 2021 |
| HP            | 1998                        | Desktop     | [2806e1e8cf](https://bsd-hardware.info/?probe=2806e1e8cf) | Jun 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [95a281e2f8](https://bsd-hardware.info/?probe=95a281e2f8) | Jun 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [65dd81d59e](https://bsd-hardware.info/?probe=65dd81d59e) | Jun 02, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [3bf6f77c19](https://bsd-hardware.info/?probe=3bf6f77c19) | Jun 01, 2021 |
| HP            | 8103 A01                    | Mini pc     | [93a434d951](https://bsd-hardware.info/?probe=93a434d951) | Jun 01, 2021 |
| Apple         | PowerBook5,2                | Notebook    | [8cc0aab53c](https://bsd-hardware.info/?probe=8cc0aab53c) | May 31, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [1cd4e4b333](https://bsd-hardware.info/?probe=1cd4e4b333) | May 28, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [5d64699270](https://bsd-hardware.info/?probe=5d64699270) | May 28, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [b4dd9ca67f](https://bsd-hardware.info/?probe=b4dd9ca67f) | May 27, 2021 |
| HP            | 8103 A01                    | Mini pc     | [df43b9c68e](https://bsd-hardware.info/?probe=df43b9c68e) | May 26, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [fbfd0e7969](https://bsd-hardware.info/?probe=fbfd0e7969) | May 21, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [7e013ea910](https://bsd-hardware.info/?probe=7e013ea910) | May 20, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [ef5e9ec095](https://bsd-hardware.info/?probe=ef5e9ec095) | May 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [65f5931910](https://bsd-hardware.info/?probe=65f5931910) | May 18, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [1e9f399d73](https://bsd-hardware.info/?probe=1e9f399d73) | May 17, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [e6a555b397](https://bsd-hardware.info/?probe=e6a555b397) | May 17, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [109f3afa21](https://bsd-hardware.info/?probe=109f3afa21) | May 17, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [f92f43bc54](https://bsd-hardware.info/?probe=f92f43bc54) | May 17, 2021 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [33bc82e701](https://bsd-hardware.info/?probe=33bc82e701) | May 17, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [bf76401b74](https://bsd-hardware.info/?probe=bf76401b74) | May 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [f90e5f9566](https://bsd-hardware.info/?probe=f90e5f9566) | May 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [e67de92cb9](https://bsd-hardware.info/?probe=e67de92cb9) | May 14, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [273e379d9f](https://bsd-hardware.info/?probe=273e379d9f) | May 14, 2021 |
| Shuttle       | FS110                       | Desktop     | [e39173782f](https://bsd-hardware.info/?probe=e39173782f) | May 08, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [1f78fbb36c](https://bsd-hardware.info/?probe=1f78fbb36c) | May 08, 2021 |
| Dell          | Latitude 3440               | Notebook    | [3c8d21772a](https://bsd-hardware.info/?probe=3c8d21772a) | May 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5a128dd6a3](https://bsd-hardware.info/?probe=5a128dd6a3) | Apr 22, 2021 |
| HP            | 8523 A01                    | Mini pc     | [dde68fc65d](https://bsd-hardware.info/?probe=dde68fc65d) | Apr 22, 2021 |
| HP            | 18E7                        | Desktop     | [e6354de524](https://bsd-hardware.info/?probe=e6354de524) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7a6f106b0e](https://bsd-hardware.info/?probe=7a6f106b0e) | Apr 18, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [cd0467031a](https://bsd-hardware.info/?probe=cd0467031a) | Apr 17, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [5a1a372153](https://bsd-hardware.info/?probe=5a1a372153) | Apr 16, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [31a9bf167b](https://bsd-hardware.info/?probe=31a9bf167b) | Apr 16, 2021 |
| Dell          | 051FJ8 A01                  | Desktop     | [351b13fd3b](https://bsd-hardware.info/?probe=351b13fd3b) | Apr 15, 2021 |
| ASRock        | J4105M                      | Desktop     | [69165e1573](https://bsd-hardware.info/?probe=69165e1573) | Apr 13, 2021 |
| HP            | 8523 A01                    | Mini pc     | [f4e8e7e7e8](https://bsd-hardware.info/?probe=f4e8e7e7e8) | Apr 11, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [5aca6c03c1](https://bsd-hardware.info/?probe=5aca6c03c1) | Apr 09, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [5950dfc99a](https://bsd-hardware.info/?probe=5950dfc99a) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [0e814e53e9](https://bsd-hardware.info/?probe=0e814e53e9) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [817ec0a0da](https://bsd-hardware.info/?probe=817ec0a0da) | Apr 09, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [6f4f9fb14e](https://bsd-hardware.info/?probe=6f4f9fb14e) | Apr 07, 2021 |
| Dell          | 072XWF A01                  | Server      | [77f48d8337](https://bsd-hardware.info/?probe=77f48d8337) | Apr 07, 2021 |
| Dell          | Latitude 3440               | Notebook    | [7e85a38390](https://bsd-hardware.info/?probe=7e85a38390) | Apr 04, 2021 |
| HP            | 2AF7                        | Desktop     | [acd341147c](https://bsd-hardware.info/?probe=acd341147c) | Apr 03, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [39d86447b4](https://bsd-hardware.info/?probe=39d86447b4) | Mar 31, 2021 |
| Dell          | 0TTDMJ A00                  | Desktop     | [b5c0428c8a](https://bsd-hardware.info/?probe=b5c0428c8a) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [6af0a9bc78](https://bsd-hardware.info/?probe=6af0a9bc78) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [aaf140005c](https://bsd-hardware.info/?probe=aaf140005c) | Mar 30, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [636dfb334b](https://bsd-hardware.info/?probe=636dfb334b) | Mar 29, 2021 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [bb65d06888](https://bsd-hardware.info/?probe=bb65d06888) | Mar 28, 2021 |
| Gigabyte      | D525TUD                     | Desktop     | [a48a515986](https://bsd-hardware.info/?probe=a48a515986) | Mar 24, 2021 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [a951f7ffe4](https://bsd-hardware.info/?probe=a951f7ffe4) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [9b84d1e7e6](https://bsd-hardware.info/?probe=9b84d1e7e6) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [cf4b3e0c6f](https://bsd-hardware.info/?probe=cf4b3e0c6f) | Mar 23, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [4a59793120](https://bsd-hardware.info/?probe=4a59793120) | Mar 23, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [7280d52eff](https://bsd-hardware.info/?probe=7280d52eff) | Mar 23, 2021 |
| Dell          | 04YP6J A02                  | Desktop     | [061ad76c0e](https://bsd-hardware.info/?probe=061ad76c0e) | Mar 20, 2021 |
| Dell          | Inspiron 7370               | Notebook    | [7e2328dda3](https://bsd-hardware.info/?probe=7e2328dda3) | Mar 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [03935b2745](https://bsd-hardware.info/?probe=03935b2745) | Mar 20, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [27cb6a75c8](https://bsd-hardware.info/?probe=27cb6a75c8) | Mar 19, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [8964a02114](https://bsd-hardware.info/?probe=8964a02114) | Mar 15, 2021 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [b13ee482e8](https://bsd-hardware.info/?probe=b13ee482e8) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [f46146b79e](https://bsd-hardware.info/?probe=f46146b79e) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [c1ed4c02b8](https://bsd-hardware.info/?probe=c1ed4c02b8) | Mar 11, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [e9ca160a2d](https://bsd-hardware.info/?probe=e9ca160a2d) | Mar 11, 2021 |
| Shuttle       | FS110                       | Desktop     | [fc31311d01](https://bsd-hardware.info/?probe=fc31311d01) | Mar 10, 2021 |
| Unknown       | Unknown                     | Firewall    | [7b7714416c](https://bsd-hardware.info/?probe=7b7714416c) | Mar 09, 2021 |
| Alienware     | 14                          | Notebook    | [0e0cdf952a](https://bsd-hardware.info/?probe=0e0cdf952a) | Mar 06, 2021 |
| Supermicro    | A2SDi-TP8F                  | Desktop     | [c30d805062](https://bsd-hardware.info/?probe=c30d805062) | Mar 05, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [c7b0539b99](https://bsd-hardware.info/?probe=c7b0539b99) | Mar 02, 2021 |
| IBM           | 94Y7614                     | Server      | [7515ccaa7a](https://bsd-hardware.info/?probe=7515ccaa7a) | Mar 01, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [48dfa4a5f6](https://bsd-hardware.info/?probe=48dfa4a5f6) | Mar 01, 2021 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [fc4265eb19](https://bsd-hardware.info/?probe=fc4265eb19) | Feb 24, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [9d35f9e853](https://bsd-hardware.info/?probe=9d35f9e853) | Feb 24, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [dbf040e5a8](https://bsd-hardware.info/?probe=dbf040e5a8) | Feb 22, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [11d6c98009](https://bsd-hardware.info/?probe=11d6c98009) | Feb 21, 2021 |
| Toshiba       | Satellite U500              | Notebook    | [feae098542](https://bsd-hardware.info/?probe=feae098542) | Feb 20, 2021 |
| Protectli     | FW6                         | Desktop     | [b656792690](https://bsd-hardware.info/?probe=b656792690) | Feb 20, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [cfd1824b40](https://bsd-hardware.info/?probe=cfd1824b40) | Feb 18, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [4c7959ac6e](https://bsd-hardware.info/?probe=4c7959ac6e) | Feb 17, 2021 |
| Gigabyte      | MRZNVMS-00                  | Desktop     | [b51cb672a4](https://bsd-hardware.info/?probe=b51cb672a4) | Feb 12, 2021 |
| Lenovo        | ThinkPad T410 253722U       | Notebook    | [219e9cb1d7](https://bsd-hardware.info/?probe=219e9cb1d7) | Feb 10, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3402eabdbf](https://bsd-hardware.info/?probe=3402eabdbf) | Feb 09, 2021 |
| Intel         | H81U                        | Notebook    | [efb1f9d207](https://bsd-hardware.info/?probe=efb1f9d207) | Feb 07, 2021 |
| Lenovo        | 314D SDK0J40700 WIN 3258... | Mini pc     | [5a5119a395](https://bsd-hardware.info/?probe=5a5119a395) | Feb 06, 2021 |
| ASRock        | Z270M-ITX/ac                | Desktop     | [9b50d422e3](https://bsd-hardware.info/?probe=9b50d422e3) | Feb 04, 2021 |
| Supermicro    | X8DT6                       | Server      | [6acb4d8445](https://bsd-hardware.info/?probe=6acb4d8445) | Feb 04, 2021 |
| HP            | 0AECh D                     | Desktop     | [6dde87584c](https://bsd-hardware.info/?probe=6dde87584c) | Feb 04, 2021 |
| HP            | 829A                        | Mini pc     | [ede207c6df](https://bsd-hardware.info/?probe=ede207c6df) | Feb 04, 2021 |
| PC Engines    | apu4                        | Desktop     | [18dfb34a97](https://bsd-hardware.info/?probe=18dfb34a97) | Feb 04, 2021 |
| HP            | 3397                        | Desktop     | [cda4af23ee](https://bsd-hardware.info/?probe=cda4af23ee) | Feb 03, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [0a48224f4b](https://bsd-hardware.info/?probe=0a48224f4b) | Feb 03, 2021 |
| HP            | 3397                        | Desktop     | [65f1db2a70](https://bsd-hardware.info/?probe=65f1db2a70) | Feb 03, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [efe09d459a](https://bsd-hardware.info/?probe=efe09d459a) | Jan 31, 2021 |
| Dell          | 086HF8 A08                  | Server      | [1d5c769e0f](https://bsd-hardware.info/?probe=1d5c769e0f) | Jan 31, 2021 |
| HP            | 82B4                        | Desktop     | [faf58d8f87](https://bsd-hardware.info/?probe=faf58d8f87) | Jan 30, 2021 |
| Dell          | 04YP6J A02                  | Desktop     | [12056c71ad](https://bsd-hardware.info/?probe=12056c71ad) | Jan 30, 2021 |
| PC Engines    | apu2                        | Desktop     | [7e96c61bf9](https://bsd-hardware.info/?probe=7e96c61bf9) | Jan 30, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [0147020401](https://bsd-hardware.info/?probe=0147020401) | Jan 30, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [65bde09c13](https://bsd-hardware.info/?probe=65bde09c13) | Jan 26, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [0a4d4fc896](https://bsd-hardware.info/?probe=0a4d4fc896) | Jan 25, 2021 |
| Dell          | 086HF8 A08                  | Server      | [f2eb601b2a](https://bsd-hardware.info/?probe=f2eb601b2a) | Jan 25, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [e8496a6202](https://bsd-hardware.info/?probe=e8496a6202) | Jan 24, 2021 |
| PC Engines    | apu2                        | Desktop     | [da6e3cd1a6](https://bsd-hardware.info/?probe=da6e3cd1a6) | Jan 23, 2021 |
| Supermicro    | X8DT6                       | Server      | [b24cc06305](https://bsd-hardware.info/?probe=b24cc06305) | Jan 22, 2021 |
| PC Engines    | apu2                        | Desktop     | [3d536a42eb](https://bsd-hardware.info/?probe=3d536a42eb) | Jan 21, 2021 |
| PC Engines    | apu2                        | Desktop     | [043446a653](https://bsd-hardware.info/?probe=043446a653) | Jan 21, 2021 |
| Shuttle       | FS110                       | Desktop     | [fed17a1f77](https://bsd-hardware.info/?probe=fed17a1f77) | Jan 21, 2021 |
| Supermicro    | X8DTH                       | Server      | [9ea2aeeb86](https://bsd-hardware.info/?probe=9ea2aeeb86) | Jan 20, 2021 |
| Supermicro    | X8STi                       | Desktop     | [7cda964f76](https://bsd-hardware.info/?probe=7cda964f76) | Jan 20, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [1cc5f6a07b](https://bsd-hardware.info/?probe=1cc5f6a07b) | Jan 20, 2021 |
| Dell          | 086HF8 A08                  | Server      | [b087a1d9d2](https://bsd-hardware.info/?probe=b087a1d9d2) | Jan 20, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [8c55004504](https://bsd-hardware.info/?probe=8c55004504) | Jan 19, 2021 |
| Intel         | S1200RP_SE G62252-406       | Server      | [49ad4461dc](https://bsd-hardware.info/?probe=49ad4461dc) | Jan 16, 2021 |
| Supermicro    | C7Z170-OCEB                 | Server      | [9f6632de8b](https://bsd-hardware.info/?probe=9f6632de8b) | Jan 10, 2021 |
| Supermicro    | X7SLA                       | Desktop     | [2d31f38bf0](https://bsd-hardware.info/?probe=2d31f38bf0) | Jan 10, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [834cb6c68a](https://bsd-hardware.info/?probe=834cb6c68a) | Jan 10, 2021 |
| Alienware     | 14                          | Notebook    | [dd2cc000a7](https://bsd-hardware.info/?probe=dd2cc000a7) | Jan 07, 2021 |
| Alienware     | 14                          | Notebook    | [48f61623f2](https://bsd-hardware.info/?probe=48f61623f2) | Jan 07, 2021 |
| MSI           | X58 Pro-E                   | Desktop     | [bd108f94d5](https://bsd-hardware.info/?probe=bd108f94d5) | Jan 02, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [11011ecee1](https://bsd-hardware.info/?probe=11011ecee1) | Jan 02, 2021 |
| HP            | 212B                        | Desktop     | [7fe9d2c508](https://bsd-hardware.info/?probe=7fe9d2c508) | Dec 18, 2020 |
| Dell          | 0GM819                      | Desktop     | [adc8eb1931](https://bsd-hardware.info/?probe=adc8eb1931) | Dec 18, 2020 |
| HP            | 805D                        | Desktop     | [dc62857275](https://bsd-hardware.info/?probe=dc62857275) | Dec 17, 2020 |
| Supermicro    | X8STi                       | Desktop     | [80c2762cfb](https://bsd-hardware.info/?probe=80c2762cfb) | Dec 16, 2020 |
| ASRockRack    | D1541D4U-2O8R               | Desktop     | [d59d8a3b6d](https://bsd-hardware.info/?probe=d59d8a3b6d) | Dec 16, 2020 |
| Supermicro    | X11SSH-F                    | Desktop     | [ebb920c0c4](https://bsd-hardware.info/?probe=ebb920c0c4) | Dec 16, 2020 |
| MSI           | X99S SLI PLUS               | Desktop     | [9b2421d9d5](https://bsd-hardware.info/?probe=9b2421d9d5) | Nov 28, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [002b408f7e](https://bsd-hardware.info/?probe=002b408f7e) | Nov 18, 2020 |
| Lenovo        | ThinkPad T440 20B7S0A800    | Notebook    | [d3474f1ca3](https://bsd-hardware.info/?probe=d3474f1ca3) | Nov 18, 2020 |
| Dell          | 0YFVT1 A06                  | Server      | [fd37374e7b](https://bsd-hardware.info/?probe=fd37374e7b) | Nov 11, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | Notebook    | [6a0f910601](https://bsd-hardware.info/?probe=6a0f910601) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | Notebook    | [6dca4cdd18](https://bsd-hardware.info/?probe=6dca4cdd18) | Nov 10, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [714b6539cf](https://bsd-hardware.info/?probe=714b6539cf) | Nov 07, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [9f871ab960](https://bsd-hardware.info/?probe=9f871ab960) | Nov 01, 2020 |
| Intel         | X79 V2.81A                  | Desktop     | [d5b4cdf28a](https://bsd-hardware.info/?probe=d5b4cdf28a) | Oct 30, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [59c940d739](https://bsd-hardware.info/?probe=59c940d739) | Oct 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [8552669e76](https://bsd-hardware.info/?probe=8552669e76) | Oct 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [50966c2f83](https://bsd-hardware.info/?probe=50966c2f83) | Oct 30, 2020 |
| Dell          | 0YFVT1 A06                  | Server      | [fca49dda17](https://bsd-hardware.info/?probe=fca49dda17) | Oct 29, 2020 |
| ADI Engine... | RCC-VE                      | Desktop     | [30440abc03](https://bsd-hardware.info/?probe=30440abc03) | Oct 29, 2020 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [c41d989a06](https://bsd-hardware.info/?probe=c41d989a06) | Oct 28, 2020 |
| IBM           | Board                       | Desktop     | [11b0b7012f](https://bsd-hardware.info/?probe=11b0b7012f) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [a92c08a920](https://bsd-hardware.info/?probe=a92c08a920) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [80d5f15a63](https://bsd-hardware.info/?probe=80d5f15a63) | Oct 21, 2020 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [f287de215c](https://bsd-hardware.info/?probe=f287de215c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [f846609c80](https://bsd-hardware.info/?probe=f846609c80) | Oct 20, 2020 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [feb1da0406](https://bsd-hardware.info/?probe=feb1da0406) | Oct 20, 2020 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [efece2abf7](https://bsd-hardware.info/?probe=efece2abf7) | Oct 20, 2020 |
| ASUSTek       | 1000HE                      | Notebook    | [621df26e0c](https://bsd-hardware.info/?probe=621df26e0c) | Oct 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS1BC01    | Notebook    | [bf6d6d155b](https://bsd-hardware.info/?probe=bf6d6d155b) | Oct 19, 2020 |
| Lenovo        | ThinkPad E495 20NE0001US    | Notebook    | [a1fc75a9b7](https://bsd-hardware.info/?probe=a1fc75a9b7) | Oct 09, 2020 |
| MSI           | MS-7250                     | Desktop     | [41e2d9dab3](https://bsd-hardware.info/?probe=41e2d9dab3) | Sep 04, 2020 |
| HP            | Pavilion dv6500             | Notebook    | [316ffb0740](https://bsd-hardware.info/?probe=316ffb0740) | Sep 04, 2020 |
| HP            | 3031h                       | Desktop     | [1f2695b3a7](https://bsd-hardware.info/?probe=1f2695b3a7) | Aug 25, 2020 |
| Acer          | AOD270                      | Notebook    | [41d2974f13](https://bsd-hardware.info/?probe=41d2974f13) | Aug 20, 2020 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [515042ff2d](https://bsd-hardware.info/?probe=515042ff2d) | Aug 20, 2020 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [e568f0f32e](https://bsd-hardware.info/?probe=e568f0f32e) | Aug 04, 2020 |
| ASUSTek       | Z170-P                      | Desktop     | [49e01a949b](https://bsd-hardware.info/?probe=49e01a949b) | Jul 29, 2020 |
| ASUSTek       | K52JK                       | Notebook    | [d5d32f1334](https://bsd-hardware.info/?probe=d5d32f1334) | Jun 29, 2020 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [0f7697b73a](https://bsd-hardware.info/?probe=0f7697b73a) | May 28, 2020 |
| Dell          | 0T10XW A02                  | Desktop     | [81f39f3061](https://bsd-hardware.info/?probe=81f39f3061) | May 28, 2020 |
| Lenovo        | ThinkPad T420 4180B39       | Notebook    | [05ed5eb1e4](https://bsd-hardware.info/?probe=05ed5eb1e4) | May 25, 2020 |
| Lenovo        | ThinkPad X270 20HNCTO1WW    | Notebook    | [7def094afb](https://bsd-hardware.info/?probe=7def094afb) | May 23, 2020 |
| ASUSTek       | K52JK                       | Notebook    | [6a6b06fc67](https://bsd-hardware.info/?probe=6a6b06fc67) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| OPNsense 21.1.4     | 12        | 4.03%   |
| OPNsense 21.1       | 12        | 4.03%   |
| OpenBSD 7.1         | 11        | 3.69%   |
| helloSystem 0.5.0   | 11        | 3.69%   |
| OPNsense 21.1.3     | 10        | 3.36%   |
| helloSystem 0.7.0   | 10        | 3.36%   |
| OPNsense 22.1.6     | 9         | 3.02%   |
| OPNsense 22.1       | 9         | 3.02%   |
| OPNsense 21.1.6     | 9         | 3.02%   |
| OpenBSD 7.0         | 9         | 3.02%   |
| OpenBSD 6.9         | 9         | 3.02%   |
| FreeBSD 12.2        | 9         | 3.02%   |
| OPNsense 21.7.7     | 8         | 2.68%   |
| OPNsense 21.7.1     | 8         | 2.68%   |
| OPNsense 21.1.5     | 8         | 2.68%   |
| OpenBSD 6.8         | 8         | 2.68%   |
| OPNsense 21.7       | 7         | 2.35%   |
| FreeBSD 13.0        | 7         | 2.35%   |
| OPNsense 21.7.8     | 6         | 2.01%   |
| OPNsense 21.7.3     | 6         | 2.01%   |
| OPNsense 21.1.1     | 6         | 2.01%   |
| OPNsense 20.7.8     | 6         | 2.01%   |
| OPNsense 21.7.5     | 5         | 1.68%   |
| OPNsense 21.7.4     | 5         | 1.68%   |
| OPNsense 21.1.2     | 5         | 1.68%   |
| helloSystem 0.4.0   | 5         | 1.68%   |
| FreeBSD 13.0-p5     | 5         | 1.68%   |
| FreeBSD 12.2-STABLE | 5         | 1.68%   |
| OPNsense 22.1.4     | 4         | 1.34%   |
| OPNsense 22.1.3     | 4         | 1.34%   |
| OPNsense 21.1.8     | 4         | 1.34%   |
| OPNsense 21.1.7     | 4         | 1.34%   |
| OPNsense 22.1.2     | 3         | 1.01%   |
| OPNsense 21.7.2     | 3         | 1.01%   |
| helloSystem 0.6.0   | 3         | 1.01%   |
| FreeBSD 12.1-p8     | 3         | 1.01%   |
| FreeBSD 11.4-p6     | 3         | 1.01%   |
| OPNsense 22.1.1     | 2         | 0.67%   |
| OPNsense 21.1.9     | 2         | 0.67%   |
| FreeNAS 11.3-p14    | 2         | 0.67%   |
| FreeBSD 13.0-p2     | 2         | 0.67%   |
| FreeBSD 12.1-STABLE | 2         | 0.67%   |
| FreeBSD 12.1-p9     | 2         | 0.67%   |
| FreeBSD 12.1-p7     | 2         | 0.67%   |
| FreeBSD 12.1-p5     | 2         | 0.67%   |
| FreeBSD 12.1-p10    | 2         | 0.67%   |
| TrueNAS 12.2-RC3    | 1         | 0.34%   |
| TrueNAS 12.2-p11    | 1         | 0.34%   |
| OPNsense 21.7.6     | 1         | 0.34%   |
| OPNsense 20.7.7     | 1         | 0.34%   |
| OPNsense 20.7.3     | 1         | 0.34%   |
| NetBSD 8.99.51      | 1         | 0.34%   |
| helloSystem 0.8.0   | 1         | 0.34%   |
| GhostBSD 22.04.06   | 1         | 0.34%   |
| GhostBSD 22.02.26   | 1         | 0.34%   |
| GhostBSD 22.02.20   | 1         | 0.34%   |
| GhostBSD 21.08.27   | 1         | 0.34%   |
| GhostBSD 20.04.02   | 1         | 0.34%   |
| FreeNAS 11.4-p4     | 1         | 0.34%   |
| FreeBSD 13.1-RC2    | 1         | 0.34%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 109       | 49.55%  |
| FreeBSD     | 57        | 25.91%  |
| helloSystem | 28        | 12.73%  |
| OpenBSD     | 16        | 7.27%   |
| GhostBSD    | 4         | 1.82%   |
| FreeNAS     | 3         | 1.36%   |
| TrueNAS     | 2         | 0.91%   |
| NetBSD      | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 211       | 96.79%  |
| i386   | 5         | 2.29%   |
| macppc | 1         | 0.46%   |
| arm64  | 1         | 0.46%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 136       | 59.65%  |
| helloDesktop | 38        | 16.67%  |
| XFCE         | 12        | 5.26%   |
| fvwm         | 12        | 5.26%   |
| KDE5         | 7         | 3.07%   |
| MATE         | 6         | 2.63%   |
| TWM          | 4         | 1.75%   |
| GNOME        | 3         | 1.32%   |
| i3           | 2         | 0.88%   |
| Cinnamon     | 2         | 0.88%   |
| X-Cinnamon   | 1         | 0.44%   |
| Openbox      | 1         | 0.44%   |
| LXQt         | 1         | 0.44%   |
| LXDE         | 1         | 0.44%   |
| Lumina       | 1         | 0.44%   |
| Fluxbox      | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 135       | 61.93%  |
| X11     | 81        | 37.16%  |
| Wayland | 2         | 0.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 162       | 73.97%  |
| SLiM    | 31        | 14.16%  |
| XDM     | 9         | 4.11%   |
| SDDM    | 9         | 4.11%   |
| LightDM | 6         | 2.74%   |
| GDM     | 2         | 0.91%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 150       | 68.18%  |
| en_US   | 43        | 19.55%  |
| C       | 16        | 7.27%   |
| en_CA   | 6         | 2.73%   |
| fr_FR   | 3         | 1.36%   |
| fr_CA   | 1         | 0.45%   |
| en_NL   | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 161       | 72.85%  |
| BIOS | 60        | 27.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 118       | 52.44%  |
| Zfs     | 82        | 36.44%  |
| Ffs     | 16        | 7.11%   |
| Cd9660  | 8         | 3.56%   |
| Unknown | 1         | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 189       | 86.7%   |
| MBR     | 27        | 12.39%  |
| Unknown | 2         | 0.92%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 27        | 12.39%  |
| Dell                           | 26        | 11.93%  |
| ASUSTek Computer               | 23        | 10.55%  |
| Lenovo                         | 21        | 9.63%   |
| Supermicro                     | 17        | 7.8%    |
| Intel                          | 16        | 7.34%   |
| ASRock                         | 11        | 5.05%   |
| Gigabyte Technology            | 10        | 4.59%   |
| Unknown                        | 9         | 4.13%   |
| MSI                            | 8         | 3.67%   |
| Protectli                      | 6         | 2.75%   |
| PC Engines                     | 5         | 2.29%   |
| AWOW                           | 4         | 1.83%   |
| AMI                            | 4         | 1.83%   |
| Acer                           | 4         | 1.83%   |
| Toshiba                        | 3         | 1.38%   |
| IBM                            | 3         | 1.38%   |
| Apple                          | 3         | 1.38%   |
| ZOTAC                          | 2         | 0.92%   |
| Panasonic                      | 2         | 0.92%   |
| Matsushita Electric Industrial | 2         | 0.92%   |
| Sophos                         | 1         | 0.46%   |
| Shuttle                        | 1         | 0.46%   |
| SeeedStudio                    | 1         | 0.46%   |
| Raspberry Pi Foundation        | 1         | 0.46%   |
| Quanta                         | 1         | 0.46%   |
| LG Electronics                 | 1         | 0.46%   |
| HPE                            | 1         | 0.46%   |
| HARDKERNEL                     | 1         | 0.46%   |
| Fujitsu                        | 1         | 0.46%   |
| ASRockRack                     | 1         | 0.46%   |
| Alienware                      | 1         | 0.46%   |
| ADI Engineering                | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 9         | 4.13%   |
| Intel Q3XXG4-P V1.0                         | 5         | 2.29%   |
| Supermicro Super Server                     | 4         | 1.83%   |
| AWOW PC BOX                                 | 4         | 1.83%   |
| Protectli FW4B                              | 3         | 1.38%   |
| Intel NDISB533                              | 3         | 1.38%   |
| Dell OptiPlex 9010                          | 3         | 1.38%   |
| Dell G5 5090                                | 3         | 1.38%   |
| ASUS All Series                             | 3         | 1.38%   |
| AMI Aptio CRB                               | 3         | 1.38%   |
| Supermicro X8STi                            | 2         | 0.92%   |
| Protectli FW6                               | 2         | 0.92%   |
| PC Engines apu4                             | 2         | 0.92%   |
| PC Engines apu2                             | 2         | 0.92%   |
| Lenovo ThinkCentre M93p 10A8S16X0J          | 2         | 0.92%   |
| HP Z440 Workstation                         | 2         | 0.92%   |
| HP t730 Thin Client                         | 2         | 0.92%   |
| HP EliteDesk 800 G1 SFF                     | 2         | 0.92%   |
| Dell OptiPlex 3020                          | 2         | 0.92%   |
| ASRock H110M-DGS R3.0                       | 2         | 0.92%   |
| ASRock B450M Pro4                           | 2         | 0.92%   |
| ZOTAC ZBOX-CI341                            | 1         | 0.46%   |
| ZOTAC ZBOX-CI329NANO                        | 1         | 0.46%   |
| Toshiba TECRA Z40-B                         | 1         | 0.46%   |
| Toshiba Satellite U500                      | 1         | 0.46%   |
| Toshiba Satellite Pro T130                  | 1         | 0.46%   |
| Supermicro X8DTH-i/6/iF/6F                  | 1         | 0.46%   |
| Supermicro X8DT6                            | 1         | 0.46%   |
| Supermicro X7SPA-HF                         | 1         | 0.46%   |
| Supermicro X7SLA                            | 1         | 0.46%   |
| Supermicro X10SLH-N6-ST031                  | 1         | 0.46%   |
| Supermicro X10SLH-F/X10SLM+-F               | 1         | 0.46%   |
| Supermicro SYS-E300-9A                      | 1         | 0.46%   |
| Supermicro SYS-5019S-ML                     | 1         | 0.46%   |
| Supermicro SYS-5019D-FN8TP                  | 1         | 0.46%   |
| Supermicro SYS-5019A-FTN4                   | 1         | 0.46%   |
| Supermicro C7Z170-OCE                       | 1         | 0.46%   |
| Sophos SG                                   | 1         | 0.46%   |
| Shuttle DH110                               | 1         | 0.46%   |
| SeeedStudio ODYSSEY-X86J4105                | 1         | 0.46%   |
| RPi Raspberry Pi                            | 1         | 0.46%   |
| Quanta 120-1135                             | 1         | 0.46%   |
| Protectli FW6E                              | 1         | 0.46%   |
| PC Engines APU                              | 1         | 0.46%   |
| Panasonic CF-53AAGHYDM                      | 1         | 0.46%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 0.46%   |
| MSI MS-7B79                                 | 1         | 0.46%   |
| MSI MS-7A40                                 | 1         | 0.46%   |
| MSI MS-7885                                 | 1         | 0.46%   |
| MSI MS-7846                                 | 1         | 0.46%   |
| MSI MS-7693                                 | 1         | 0.46%   |
| MSI MS-7522                                 | 1         | 0.46%   |
| MSI MS-7388                                 | 1         | 0.46%   |
| MSI MS-7250                                 | 1         | 0.46%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 0.46%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 0.46%   |
| LG E500-GP01A9                              | 1         | 0.46%   |
| Lenovo ThinkPad X280 20KF001UUS             | 1         | 0.46%   |
| Lenovo ThinkPad X270 20HNCTO1WW             | 1         | 0.46%   |
| Lenovo ThinkPad X250 20CL001GUS             | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 14        | 6.42%   |
| Dell OptiPlex                | 10        | 4.59%   |
| Unknown                      | 9         | 4.13%   |
| Lenovo ThinkCentre           | 7         | 3.21%   |
| Dell PowerEdge               | 6         | 2.75%   |
| Intel Q3XXG4-P               | 5         | 2.29%   |
| Supermicro Super             | 4         | 1.83%   |
| HP ProDesk                   | 4         | 1.83%   |
| HP Compaq                    | 4         | 1.83%   |
| Dell Inspiron                | 4         | 1.83%   |
| AWOW PC                      | 4         | 1.83%   |
| Protectli FW4B               | 3         | 1.38%   |
| Intel NDISB533               | 3         | 1.38%   |
| HP ProLiant                  | 3         | 1.38%   |
| HP EliteDesk                 | 3         | 1.38%   |
| Dell G5                      | 3         | 1.38%   |
| ASUS All                     | 3         | 1.38%   |
| AMI Aptio                    | 3         | 1.38%   |
| Acer Aspire                  | 3         | 1.38%   |
| Toshiba Satellite            | 2         | 0.92%   |
| Supermicro X8STi             | 2         | 0.92%   |
| Protectli FW6                | 2         | 0.92%   |
| PC Engines apu4              | 2         | 0.92%   |
| PC Engines apu2              | 2         | 0.92%   |
| IBM System                   | 2         | 0.92%   |
| HP Z440                      | 2         | 0.92%   |
| HP t730                      | 2         | 0.92%   |
| HP Pavilion                  | 2         | 0.92%   |
| ASUS TUF                     | 2         | 0.92%   |
| ASUS ROG                     | 2         | 0.92%   |
| ASUS PRIME                   | 2         | 0.92%   |
| ASRock H110M-DGS             | 2         | 0.92%   |
| ASRock B450M                 | 2         | 0.92%   |
| ZOTAC ZBOX-CI341             | 1         | 0.46%   |
| ZOTAC ZBOX-CI329NANO         | 1         | 0.46%   |
| Toshiba TECRA                | 1         | 0.46%   |
| Supermicro X8DTH-i           | 1         | 0.46%   |
| Supermicro X8DT6             | 1         | 0.46%   |
| Supermicro X7SPA-HF          | 1         | 0.46%   |
| Supermicro X7SLA             | 1         | 0.46%   |
| Supermicro X10SLH-N6-ST031   | 1         | 0.46%   |
| Supermicro X10SLH-F          | 1         | 0.46%   |
| Supermicro SYS-E300-9A       | 1         | 0.46%   |
| Supermicro SYS-5019S-ML      | 1         | 0.46%   |
| Supermicro SYS-5019D-FN8TP   | 1         | 0.46%   |
| Supermicro SYS-5019A-FTN4    | 1         | 0.46%   |
| Supermicro C7Z170-OCE        | 1         | 0.46%   |
| Sophos SG                    | 1         | 0.46%   |
| Shuttle DH110                | 1         | 0.46%   |
| SeeedStudio ODYSSEY-X86J4105 | 1         | 0.46%   |
| RPi Raspberry                | 1         | 0.46%   |
| Quanta 120-1135              | 1         | 0.46%   |
| Protectli FW6E               | 1         | 0.46%   |
| PC Engines APU               | 1         | 0.46%   |
| Panasonic CF-53AAGHYDM       | 1         | 0.46%   |
| Panasonic CF-52PFPBSFQ       | 1         | 0.46%   |
| MSI MS-7B79                  | 1         | 0.46%   |
| MSI MS-7A40                  | 1         | 0.46%   |
| MSI MS-7885                  | 1         | 0.46%   |
| MSI MS-7846                  | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 37        | 16.97%  |
| 2020    | 31        | 14.22%  |
| 2014    | 24        | 11.01%  |
| 2010    | 17        | 7.8%    |
| 2019    | 15        | 6.88%   |
| 2015    | 15        | 6.88%   |
| 2016    | 13        | 5.96%   |
| 2013    | 12        | 5.5%    |
| 2011    | 12        | 5.5%    |
| 2009    | 9         | 4.13%   |
| 2017    | 8         | 3.67%   |
| 2012    | 8         | 3.67%   |
| 2021    | 7         | 3.21%   |
| 2008    | 4         | 1.83%   |
| Unknown | 3         | 1.38%   |
| 2006    | 2         | 0.92%   |
| 2002    | 1         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 129       | 59.17%  |
| Notebook       | 43        | 19.72%  |
| Server         | 21        | 9.63%   |
| Mini pc        | 19        | 8.72%   |
| All in one     | 3         | 1.38%   |
| Firewall       | 2         | 0.92%   |
| System on chip | 1         | 0.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 211       | 96.79%  |
| Yes  | 7         | 3.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 72        | 32.58%  |
| 16.01-24.0      | 45        | 20.36%  |
| 4.01-8.0        | 42        | 19%     |
| 32.01-64.0      | 27        | 12.22%  |
| 64.01-256.0     | 11        | 4.98%   |
| 2.01-3.0        | 9         | 4.07%   |
| 3.01-4.0        | 5         | 2.26%   |
| 24.01-32.0      | 4         | 1.81%   |
| 0.51-1.0        | 3         | 1.36%   |
| 1.01-2.0        | 2         | 0.9%    |
| More than 256.0 | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 104       | 46.02%  |
| 0.51-1.0    | 65        | 28.76%  |
| 1.01-2.0    | 28        | 12.39%  |
| 4.01-8.0    | 6         | 2.65%   |
| 3.01-4.0    | 5         | 2.21%   |
| 2.01-3.0    | 5         | 2.21%   |
| 0           | 4         | 1.77%   |
| 24.01-32.0  | 3         | 1.33%   |
| 64.01-256.0 | 2         | 0.88%   |
| 8.01-16.0   | 2         | 0.88%   |
| 32.01-64.0  | 1         | 0.44%   |
| Unknown     | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 147       | 65.63%  |
| 2      | 34        | 15.18%  |
| 0      | 19        | 8.48%   |
| 3      | 8         | 3.57%   |
| 4      | 7         | 3.13%   |
| 7      | 2         | 0.89%   |
| 5      | 2         | 0.89%   |
| 40     | 1         | 0.45%   |
| 25     | 1         | 0.45%   |
| 14     | 1         | 0.45%   |
| 13     | 1         | 0.45%   |
| 10     | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 168       | 76.02%  |
| Yes       | 53        | 23.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 98.17%  |
| No        | 4         | 1.83%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 139       | 63.18%  |
| Yes       | 81        | 36.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 165       | 75.34%  |
| Yes       | 54        | 24.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Canada  | 218       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Montreal                   | 25        | 10.29%  |
| Toronto                    | 20        | 8.23%   |
| Victoria                   | 13        | 5.35%   |
| Ottawa                     | 11        | 4.53%   |
| Calgary                    | 11        | 4.53%   |
| Saint-Laurent              | 9         | 3.7%    |
| Edmonton                   | 9         | 3.7%    |
| Winnipeg                   | 6         | 2.47%   |
| Vancouver                  | 6         | 2.47%   |
| Surrey                     | 6         | 2.47%   |
| QuГ©bec                  | 6         | 2.47%   |
| Kitchener                  | 6         | 2.47%   |
| Brampton                   | 6         | 2.47%   |
| Sainte-Julie               | 4         | 1.65%   |
| Moncton                    | 4         | 1.65%   |
| Gatineau                   | 4         | 1.65%   |
| Windsor                    | 3         | 1.23%   |
| St. Albert                 | 3         | 1.23%   |
| Sherwood Park              | 3         | 1.23%   |
| Regina                     | 3         | 1.23%   |
| QuÃ©bec                  | 3         | 1.23%   |
| Peterborough               | 3         | 1.23%   |
| Oakville                   | 3         | 1.23%   |
| Maple Ridge                | 3         | 1.23%   |
| Laval                      | 3         | 1.23%   |
| Hamilton                   | 3         | 1.23%   |
| Guelph                     | 3         | 1.23%   |
| Smiths Falls               | 2         | 0.82%   |
| Saint-Bruno-de-Montarville | 2         | 0.82%   |
| Québec                    | 2         | 0.82%   |
| London                     | 2         | 0.82%   |
| Lamont                     | 2         | 0.82%   |
| Kingston                   | 2         | 0.82%   |
| Kanata                     | 2         | 0.82%   |
| Greater Sudbury            | 2         | 0.82%   |
| Burlington                 | 2         | 0.82%   |
| West Kelowna               | 1         | 0.41%   |
| Vaughan                    | 1         | 0.41%   |
| Tobique First Nation       | 1         | 0.41%   |
| Terrebonne                 | 1         | 0.41%   |
| St. John's                 | 1         | 0.41%   |
| St. Catharines             | 1         | 0.41%   |
| Sherbrooke                 | 1         | 0.41%   |
| Sechelt                    | 1         | 0.41%   |
| Scarborough                | 1         | 0.41%   |
| Saskatoon                  | 1         | 0.41%   |
| Sarnia                     | 1         | 0.41%   |
| Saint-Colomban             | 1         | 0.41%   |
| Richmond                   | 1         | 0.41%   |
| Renfrew                    | 1         | 0.41%   |
| Pont-Rouge                 | 1         | 0.41%   |
| Pierrefonds                | 1         | 0.41%   |
| Picton                     | 1         | 0.41%   |
| North Vancouver            | 1         | 0.41%   |
| Niagara Falls              | 1         | 0.41%   |
| New-Richmond               | 1         | 0.41%   |
| New Westminster            | 1         | 0.41%   |
| Nanaimo                    | 1         | 0.41%   |
| Mississauga                | 1         | 0.41%   |
| Mission                    | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 47        | 122    | 18.5%   |
| Samsung Electronics | 37        | 54     | 14.57%  |
| Seagate             | 33        | 77     | 12.99%  |
| Kingston            | 21        | 26     | 8.27%   |
| Toshiba             | 11        | 16     | 4.33%   |
| Intel               | 10        | 11     | 3.94%   |
| Crucial             | 10        | 11     | 3.94%   |
| Hitachi             | 9         | 50     | 3.54%   |
| A-DATA Technology   | 9         | 16     | 3.54%   |
| SanDisk             | 6         | 9      | 2.36%   |
| Dogfish             | 6         | 10     | 2.36%   |
| SK Hynix            | 5         | 7      | 1.97%   |
| OCZ                 | 4         | 5      | 1.57%   |
| Micron Technology   | 4         | 7      | 1.57%   |
| Hewlett-Packard     | 4         | 4      | 1.57%   |
| FORESEE             | 4         | 12     | 1.57%   |
| Hoodisk             | 3         | 4      | 1.18%   |
| HGST                | 3         | 39     | 1.18%   |
| VisionTek           | 2         | 6      | 0.79%   |
| Transcend           | 2         | 2      | 0.79%   |
| SPCC                | 2         | 2      | 0.79%   |
| PNY                 | 2         | 3      | 0.79%   |
| NVMe                | 2         | 2      | 0.79%   |
| Mushkin             | 2         | 2      | 0.79%   |
| Lexar               | 2         | 2      | 0.79%   |
| BIWIN               | 2         | 2      | 0.79%   |
| XPG                 | 1         | 1      | 0.39%   |
| SATADOM             | 1         | 2      | 0.39%   |
| Protectli           | 1         | 1      | 0.39%   |
| Phison              | 1         | 1      | 0.39%   |
| Netac               | 1         | 1      | 0.39%   |
| Kston               | 1         | 2      | 0.39%   |
| HPE                 | 1         | 4      | 0.39%   |
| Fujitsu             | 1         | 1      | 0.39%   |
| Corsair             | 1         | 3      | 0.39%   |
| China               | 1         | 1      | 0.39%   |
| AVEXIR              | 1         | 2      | 0.39%   |
| Apacer              | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB     | 8         | 2.82%   |
| Kingston SA400S37240G 240GB     | 6         | 2.11%   |
| Seagate ST1000DM010-2EP102 1TB  | 4         | 1.41%   |
| Samsung SSD 860 EVO 500GB       | 4         | 1.41%   |
| FORESEE 128GB SSD               | 4         | 1.41%   |
| WDC WD20EZRX-00DC0B0 2TB        | 3         | 1.06%   |
| Toshiba DT01ACA100 1TB          | 3         | 1.06%   |
| Seagate ST2000DM008-2FR102 2TB  | 3         | 1.06%   |
| Samsung SSD 850 EVO 250GB       | 3         | 1.06%   |
| WDC WDS500G2B0A-00SM50 500GB    | 2         | 0.7%    |
| WDC WD7500BPKX-00HPJT0 752GB    | 2         | 0.7%    |
| WDC WD40EFRX-68WT0N0 4TB        | 2         | 0.7%    |
| WDC WD30EFRX-68EUZN0 3TB        | 2         | 0.7%    |
| WDC WD20EFRX-68EUZN0 2TB        | 2         | 0.7%    |
| WDC WD120EDAZ-11F3RA0 12TB      | 2         | 0.7%    |
| WDC WD10JPLX-00MBPT0 1TB        | 2         | 0.7%    |
| WDC WD10EZEX-22MFCA0 1TB        | 2         | 0.7%    |
| WDC WD10EZEX-08WN4A0 1TB        | 2         | 0.7%    |
| WDC PC SN520 NVMe 256GB         | 2         | 0.7%    |
| VisionTek mSATA 120GB           | 2         | 0.7%    |
| Seagate ST500DM002-1BD142 500GB | 2         | 0.7%    |
| Seagate ST3500413AS 500GB       | 2         | 0.7%    |
| Seagate ST2000DM001-1ER164 2TB  | 2         | 0.7%    |
| SanDisk SD6SB1M064G1022I 64GB   | 2         | 0.7%    |
| Samsung SSD 860 PRO 256GB       | 2         | 0.7%    |
| Samsung SSD 850 PRO 256GB       | 2         | 0.7%    |
| Samsung SSD 850 EVO 120GB       | 2         | 0.7%    |
| Samsung SSD 840 EVO 120GB       | 2         | 0.7%    |
| PNY CS1311 120GB SSD            | 2         | 0.7%    |
| Mushkin MKNSSDEC60GB 64GB       | 2         | 0.7%    |
| Kingston SUV500MS120G 120GB     | 2         | 0.7%    |
| Intel SSDSA2CW120G3 120GB       | 2         | 0.7%    |
| Dogfish SSD 64GB                | 2         | 0.7%    |
| Dogfish SSD 128GB               | 2         | 0.7%    |
| Crucial CT240BX500SSD1 240GB    | 2         | 0.7%    |
| BIWIN SSD 128GB                 | 2         | 0.7%    |
| A-DATA SU650 120GB              | 2         | 0.7%    |
| XPG GAMMIX S11 Pro 256GB        | 1         | 0.35%   |
| WDC WDS500G3X0C-00SJG0 500GB    | 1         | 0.35%   |
| WDC WDS500G2B0B-00YS70 500GB    | 1         | 0.35%   |
| WDC WDS500G2B0A 500GB           | 1         | 0.35%   |
| WDC WDS250G3X0C-00SJG0 250GB    | 1         | 0.35%   |
| WDC WDS250G2B0A 250GB           | 1         | 0.35%   |
| WDC WDS200T2B0A 2TB             | 1         | 0.35%   |
| WDC WDS120G2G0A-00JH30 120GB    | 1         | 0.35%   |
| WDC WDS100T3X0C-00SJG0 1TB      | 1         | 0.35%   |
| WDC WDS100T2B0A-00SM50 1TB      | 1         | 0.35%   |
| WDC WD7500BPKX-75HPJT0 752GB    | 1         | 0.35%   |
| WDC WD7500BPKT-75PK4T0 752GB    | 1         | 0.35%   |
| WDC WD7500BPKT-00PK4T0 752GB    | 1         | 0.35%   |
| WDC WD6400BEVT-22A0RT0 640GB    | 1         | 0.35%   |
| WDC WD6003FZBX-00K5WB0 6TB      | 1         | 0.35%   |
| WDC WD50EFRX-68L0BN1 5TB        | 1         | 0.35%   |
| WDC WD5000LPVX-22V0TT0 500GB    | 1         | 0.35%   |
| WDC WD5000LPLX-00ZNTT0 500GB    | 1         | 0.35%   |
| WDC WD5000AAKX-75U6AA0 500GB    | 1         | 0.35%   |
| WDC WD5000AAKX-00ERMA0 500GB    | 1         | 0.35%   |
| WDC WD5000AAKS-75A7B0 500GB     | 1         | 0.35%   |
| WDC WD40EFRX-68N32N0 4TB        | 1         | 0.35%   |
| WDC WD3200BEVE-00A0HT0 320GB    | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 35        | 103    | 37.23%  |
| Seagate             | 33        | 77     | 35.11%  |
| Toshiba             | 9         | 12     | 9.57%   |
| Hitachi             | 9         | 50     | 9.57%   |
| HGST                | 3         | 39     | 3.19%   |
| Samsung Electronics | 1         | 1      | 1.06%   |
| NVMe                | 1         | 1      | 1.06%   |
| Lexar               | 1         | 1      | 1.06%   |
| Hewlett-Packard     | 1         | 1      | 1.06%   |
| Fujitsu             | 1         | 1      | 1.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 44     | 22.46%  |
| Kingston            | 21        | 25     | 15.22%  |
| WDC                 | 8         | 10     | 5.8%    |
| Intel               | 8         | 9      | 5.8%    |
| Crucial             | 8         | 9      | 5.8%    |
| A-DATA Technology   | 8         | 15     | 5.8%    |
| SanDisk             | 6         | 9      | 4.35%   |
| DOGFISH             | 6         | 10     | 4.35%   |
| OCZ                 | 4         | 5      | 2.9%    |
| Micron Technology   | 4         | 7      | 2.9%    |
| FORESEE             | 4         | 12     | 2.9%    |
| Hoodisk             | 3         | 4      | 2.17%   |
| VisionTek           | 2         | 6      | 1.45%   |
| Transcend           | 2         | 2      | 1.45%   |
| SPCC                | 2         | 2      | 1.45%   |
| SK Hynix            | 2         | 2      | 1.45%   |
| PNY                 | 2         | 3      | 1.45%   |
| Mushkin             | 2         | 2      | 1.45%   |
| BIWIN               | 2         | 2      | 1.45%   |
| Toshiba             | 1         | 1      | 0.72%   |
| SATADOM             | 1         | 2      | 0.72%   |
| Protectli           | 1         | 1      | 0.72%   |
| Phison              | 1         | 1      | 0.72%   |
| Netac               | 1         | 1      | 0.72%   |
| Lexar               | 1         | 1      | 0.72%   |
| Kston               | 1         | 2      | 0.72%   |
| HPE                 | 1         | 4      | 0.72%   |
| Hewlett-Packard     | 1         | 1      | 0.72%   |
| Corsair             | 1         | 3      | 0.72%   |
| China               | 1         | 1      | 0.72%   |
| AVEXIR              | 1         | 2      | 0.72%   |
| Apacer              | 1         | 1      | 0.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 127       | 199    | 54.98%  |
| HDD  | 80        | 286    | 34.63%  |
| NVMe | 24        | 36     | 10.39%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 189       | 485    | 88.73%  |
| NVMe | 24        | 36     | 11.27%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 151       | 238    | 67.71%  |
| 0.51-1.0   | 36        | 67     | 16.14%  |
| 1.01-2.0   | 15        | 42     | 6.73%   |
| 3.01-4.0   | 7         | 54     | 3.14%   |
| 4.01-10.0  | 6         | 45     | 2.69%   |
| 2.01-3.0   | 5         | 23     | 2.24%   |
| 10.01-20.0 | 3         | 16     | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 81        | 35.53%  |
| 1-20           | 35        | 15.35%  |
| 21-50          | 33        | 14.47%  |
| 251-500        | 31        | 13.6%   |
| 51-100         | 28        | 12.28%  |
| 501-1000       | 12        | 5.26%   |
| 1001-2000      | 5         | 2.19%   |
| Unknown        | 2         | 0.88%   |
| More than 3000 | 1         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 192       | 84.96%  |
| 21-50    | 24        | 10.62%  |
| 51-100   | 5         | 2.21%   |
| Unknown  | 2         | 0.88%   |
| 251-500  | 1         | 0.44%   |
| 101-250  | 1         | 0.44%   |
| 501-1000 | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| VisionTek mSATA 120GB                      | 2         | 6      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB            | 2         | 4      | 5.26%   |
| Seagate ST3500413AS 500GB                  | 2         | 4      | 5.26%   |
| WDC WDS200T2B0A 2TB                        | 1         | 1      | 2.63%   |
| WDC WD7500BPKX-00HPJT0 752GB               | 1         | 2      | 2.63%   |
| WDC WD6400BEVT-22A0RT0 640GB               | 1         | 1      | 2.63%   |
| WDC WD50EFRX-68L0BN1 5TB                   | 1         | 1      | 2.63%   |
| WDC WD40EFRX-68WT0N0 4TB                   | 1         | 2      | 2.63%   |
| WDC WD30EZRX-22D8PB0 3TB                   | 1         | 1      | 2.63%   |
| WDC WD2500AAKX-001CA0 250GB                | 1         | 1      | 2.63%   |
| Toshiba DT01ACA100 1TB                     | 1         | 3      | 2.63%   |
| Seagate ST9500420AS 500GB                  | 1         | 2      | 2.63%   |
| Seagate ST500LM021-1KJ152 500GB            | 1         | 1      | 2.63%   |
| Seagate ST3250318AS 250GB                  | 1         | 1      | 2.63%   |
| Seagate ST3200822AS 200GB                  | 1         | 1      | 2.63%   |
| Seagate ST3160815AS 160GB                  | 1         | 1      | 2.63%   |
| Seagate ST31500341AS 1.5TB                 | 1         | 2      | 2.63%   |
| Seagate ST3120026A 120GB                   | 1         | 1      | 2.63%   |
| Seagate ST31000520AS 1TB                   | 1         | 1      | 2.63%   |
| Seagate ST2000DL003-9VT166 2TB             | 1         | 4      | 2.63%   |
| Seagate ST1000DM003-1CH162 1TB             | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 860 EVO 1TB        | 1         | 1      | 2.63%   |
| OCZ VERTEX 32GB                            | 1         | 2      | 2.63%   |
| Micron Technology M500_MTFDDAK960MAV 960GB | 1         | 4      | 2.63%   |
| Intel SSDSC2CW120A3 120GB                  | 1         | 1      | 2.63%   |
| Intel SSDSC2BB012T7 1.2TB                  | 1         | 2      | 2.63%   |
| Intel SSDSA2M080G2GC 80GB                  | 1         | 1      | 2.63%   |
| Hitachi HTS541612J9SA00 120GB              | 1         | 1      | 2.63%   |
| Hitachi HDT721064SLA360 640GB              | 1         | 1      | 2.63%   |
| Hitachi HDT721010SLA360 1TB                | 1         | 1      | 2.63%   |
| Hitachi HDS5C3030ALA630 3TB                | 1         | 14     | 2.63%   |
| HGST HTS541010A9E680 1TB                   | 1         | 1      | 2.63%   |
| Crucial CT240M500SSD1 240GB                | 1         | 1      | 2.63%   |
| Apacer 16GB SATA Flash Drive               | 1         | 1      | 2.63%   |
| A-DATA Technology SP550 480GB              | 1         | 3      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 23     | 35.14%  |
| WDC                 | 7         | 9      | 18.92%  |
| Hitachi             | 4         | 17     | 10.81%  |
| Intel               | 3         | 4      | 8.11%   |
| VisionTek           | 2         | 6      | 5.41%   |
| Toshiba             | 1         | 3      | 2.7%    |
| Samsung Electronics | 1         | 1      | 2.7%    |
| OCZ                 | 1         | 2      | 2.7%    |
| Micron Technology   | 1         | 4      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |
| Crucial             | 1         | 1      | 2.7%    |
| Apacer              | 1         | 1      | 2.7%    |
| A-DATA Technology   | 1         | 3      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 23     | 52%     |
| WDC     | 6         | 8      | 24%     |
| Hitachi | 4         | 17     | 16%     |
| Toshiba | 1         | 3      | 4%      |
| HGST    | 1         | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 52     | 66.67%  |
| SSD  | 12        | 23     | 33.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-00Z10T0 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 174       | 437    | 79.82%  |
| Malfunc  | 35        | 75     | 16.06%  |
| Detected | 8         | 8      | 3.67%   |
| Failed   | 1         | 1      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 173       | 66.03%  |
| AMD                         | 28        | 10.69%  |
| Broadcom / LSI              | 12        | 4.58%   |
| Sandisk                     | 8         | 3.05%   |
| Samsung Electronics         | 8         | 3.05%   |
| Nvidia                      | 5         | 1.91%   |
| ASMedia Technology          | 4         | 1.53%   |
| SK Hynix                    | 3         | 1.15%   |
| Marvell Technology Group    | 3         | 1.15%   |
| Chelsio Communications      | 3         | 1.15%   |
| Silicon Motion              | 2         | 0.76%   |
| Silicon Image               | 2         | 0.76%   |
| Micron/Crucial Technology   | 2         | 0.76%   |
| JMicron Technology          | 2         | 0.76%   |
| Hewlett-Packard             | 2         | 0.76%   |
| Toshiba                     | 1         | 0.38%   |
| Realtek Semiconductor       | 1         | 0.38%   |
| Kingston Technology Company | 1         | 0.38%   |
| Dell                        | 1         | 0.38%   |
| ADATA Technology            | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 22        | 7.36%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 16        | 5.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 10        | 3.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 2.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 2.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 8         | 2.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 8         | 2.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7         | 2.34%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 6         | 2.01%   |
| AMD 400 Series Chipset SATA Controller                                           | 6         | 2.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 1.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.67%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 5         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.67%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 1.34%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 4         | 1.34%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 1.34%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4         | 1.34%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 4         | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.34%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 1%      |
| Sandisk PC SN520 NVMe SSD                                                        | 3         | 1%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 1%      |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1%      |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 1%      |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 3         | 1%      |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 1%      |
| AMD FCH SATA Controller [IDE mode]                                               | 3         | 1%      |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 2         | 0.67%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 0.67%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.67%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.67%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller            | 2         | 0.67%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2         | 0.67%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 0.67%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 0.67%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 2         | 0.67%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 2         | 0.67%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 2         | 0.67%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 2         | 0.67%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 2         | 0.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 0.67%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 2         | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 0.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 0.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 0.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 0.67%   |
| Chelsio T420-CR Unified Wire Storage Controller                                  | 2         | 0.67%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                               | 2         | 0.67%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 2         | 0.67%   |
| Broadcom / LSI MegaRAID SAS 1078                                                 | 2         | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2         | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 0.67%   |
| AMD FCH IDE Controller                                                           | 2         | 0.67%   |
| Unknown                                                                          | 2         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 173       | 66.03%  |
| IDE  | 37        | 14.12%  |
| NVMe | 26        | 9.92%   |
| RAID | 15        | 5.73%   |
| SAS  | 6         | 2.29%   |
| SCSI | 5         | 1.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 184       | 84.02%  |
| AMD     | 33        | 15.07%  |
| ARM     | 1         | 0.46%   |
| Unknown | 1         | 0.46%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-4570 CPU @ 3.20GHz         | 5         | 2.25%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 4         | 1.8%    |
| Intel Core i5-3570 CPU @ 3.40GHz         | 4         | 1.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz        | 4         | 1.8%    |
| Intel Celeron CPU J3455E @ 1.50GHz       | 4         | 1.8%    |
| Intel Celeron CPU J3160 @ 1.60GHz        | 4         | 1.8%    |
| AMD GX-412TC SOC                         | 4         | 1.8%    |
| Intel Core i7-9700K CPU @ 3.60GHz        | 3         | 1.35%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 3         | 1.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 3         | 1.35%   |
| Intel Core i5-4570TE CPU @ 2.70GHz       | 3         | 1.35%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 3         | 1.35%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 3         | 1.35%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 3         | 1.35%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 2         | 0.9%    |
| Intel Pentium CPU G4560 @ 3.50GHz        | 2         | 0.9%    |
| Intel CPU Version                        | 2         | 0.9%    |
| Intel Core i7-4790K CPU @ 4.00GHz        | 2         | 0.9%    |
| Intel Core i5-8400 CPU @ 2.80GHz         | 2         | 0.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz        | 2         | 0.9%    |
| Intel Core i5-5300U CPU @ 2.30GHz        | 2         | 0.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 0.9%    |
| Intel Core i5-4590 CPU @ 3.30GHz         | 2         | 0.9%    |
| Intel Core i5-4460 CPU @ 3.20GHz         | 2         | 0.9%    |
| Intel Core i5-10400 CPU @ 2.90GHz        | 2         | 0.9%    |
| Intel Core i3-5005U CPU @ 2.00GHz        | 2         | 0.9%    |
| Intel Core i3-4030U CPU @ 1.90GHz        | 2         | 0.9%    |
| Intel Core i3-4010U CPU @ 1.70GHz        | 2         | 0.9%    |
| Intel Celeron N4100 CPU @ 1.10GHz        | 2         | 0.9%    |
| Intel Celeron J4105 CPU @ 1.50GHz        | 2         | 0.9%    |
| AMD RX-427BB with AMD Radeon R7 Graphics | 2         | 0.9%    |
| AMD FX-8350 Eight-Core Processor         | 2         | 0.9%    |
| AMD FX-8320E Eight-Core Processor        | 2         | 0.9%    |
| Intel Xeon D-2146NT CPU @ 2.30GHz        | 1         | 0.45%   |
| Intel Xeon CPU X5680 @ 3.33GHz           | 1         | 0.45%   |
| Intel Xeon CPU X5670 @ 2.93GHz           | 1         | 0.45%   |
| Intel Xeon CPU X5660 @ 2.80GHz           | 1         | 0.45%   |
| Intel Xeon CPU X5650 @ 2.67GHz           | 1         | 0.45%   |
| Intel Xeon CPU X5560 @ 2.80GHz           | 1         | 0.45%   |
| Intel Xeon CPU W3530 @ 2.80GHz           | 1         | 0.45%   |
| Intel Xeon CPU L5640 @ 2.27GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5645 @ 2.40GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5520 @ 2.27GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5506 @ 2.13GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz      | 1         | 0.45%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz       | 1         | 0.45%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz       | 1         | 0.45%   |
| Intel Xeon CPU E5-2450 v2 @ 2.50GHz      | 1         | 0.45%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz      | 1         | 0.45%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz      | 1         | 0.45%   |
| Intel Xeon CPU E5-1603 @ 2.80GHz         | 1         | 0.45%   |
| Intel Xeon CPU E3-1285L v4 @ 3.40GHz     | 1         | 0.45%   |
| Intel Xeon CPU E3-1275 v6 @ 3.80GHz      | 1         | 0.45%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz      | 1         | 0.45%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz      | 1         | 0.45%   |
| Intel Xeon CPU E3-1240L v5 @ 2.10GHz     | 1         | 0.45%   |
| Intel Xeon CPU D-1541 @ 2.10GHz          | 1         | 0.45%   |
| Intel Xeon CPU D-1520 @ 2.20GHz          | 1         | 0.45%   |
| Intel Xeon CPU 5160 @ 3.00GHz            | 1         | 0.45%   |
| Intel Xeon                               | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 55        | 25%     |
| Intel Xeon              | 29        | 13.18%  |
| Intel Core i7           | 23        | 10.45%  |
| Intel Celeron           | 23        | 10.45%  |
| Intel Core i3           | 22        | 10%     |
| Intel Atom              | 11        | 5%      |
| Other                   | 7         | 3.18%   |
| Intel Core 2 Duo        | 6         | 2.73%   |
| AMD GX                  | 5         | 2.27%   |
| Intel Pentium           | 4         | 1.82%   |
| AMD FX                  | 4         | 1.82%   |
| Intel Pentium Dual-Core | 3         | 1.36%   |
| AMD Ryzen 7             | 3         | 1.36%   |
| AMD Ryzen 5             | 3         | 1.36%   |
| Intel Pentium 4         | 2         | 0.91%   |
| Intel Core 2 Quad       | 2         | 0.91%   |
| AMD Ryzen Embedded      | 2         | 0.91%   |
| AMD Ryzen 5 PRO         | 2         | 0.91%   |
| AMD Opteron             | 2         | 0.91%   |
| AMD Athlon 64 X2        | 2         | 0.91%   |
| Intel Genuine           | 1         | 0.45%   |
| ARM Cortex              | 1         | 0.45%   |
| AMD Ryzen 9             | 1         | 0.45%   |
| AMD Ryzen 3             | 1         | 0.45%   |
| AMD Phenom II X6        | 1         | 0.45%   |
| AMD G                   | 1         | 0.45%   |
| AMD EPYC                | 1         | 0.45%   |
| AMD E                   | 1         | 0.45%   |
| AMD Athlon              | 1         | 0.45%   |
| AMD A6                  | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 93        | 42.47%  |
| 2       | 69        | 31.51%  |
| 8       | 17        | 7.76%   |
| 6       | 14        | 6.39%   |
| Unknown | 11        | 5.02%   |
| 12      | 8         | 3.65%   |
| 16      | 4         | 1.83%   |
| 64      | 1         | 0.46%   |
| 32      | 1         | 0.46%   |
| 1       | 1         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 203       | 91.86%  |
| 2       | 12        | 5.43%   |
| Unknown | 6         | 2.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 107       | 48.86%  |
| 2       | 100       | 45.66%  |
| Unknown | 12        | 5.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 35        | 15.84%  |
| KabyLake      | 26        | 11.76%  |
| IvyBridge     | 17        | 7.69%   |
| SandyBridge   | 12        | 5.43%   |
| Silvermont    | 11        | 4.98%   |
| Penryn        | 11        | 4.98%   |
| Broadwell     | 11        | 4.98%   |
| Westmere      | 10        | 4.52%   |
| Skylake       | 10        | 4.52%   |
| Goldmont      | 10        | 4.52%   |
| Zen+          | 6         | 2.71%   |
| Piledriver    | 6         | 2.71%   |
| Nehalem       | 6         | 2.71%   |
| Goldmont plus | 6         | 2.71%   |
| Bonnell       | 6         | 2.71%   |
| CometLake     | 5         | 2.26%   |
| Unknown       | 5         | 2.26%   |
| Puma          | 4         | 1.81%   |
| Zen 2         | 3         | 1.36%   |
| Zen           | 3         | 1.36%   |
| Core          | 3         | 1.36%   |
| Steamroller   | 2         | 0.9%    |
| NetBurst      | 2         | 0.9%    |
| K8 Hammer     | 2         | 0.9%    |
| Jaguar        | 2         | 0.9%    |
| Bobcat        | 2         | 0.9%    |
| Zen 3         | 1         | 0.45%   |
| TigerLake     | 1         | 0.45%   |
| P6            | 1         | 0.45%   |
| K10           | 1         | 0.45%   |
| Excavator     | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 127       | 58.8%   |
| Nvidia                     | 32        | 14.81%  |
| AMD                        | 31        | 14.35%  |
| Matrox Electronics Systems | 15        | 6.94%   |
| ASPEED Technology          | 11        | 5.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 18        | 8.18%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 11        | 5%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.09%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 8         | 3.64%   |
| Intel HD Graphics 5500                                                                   | 8         | 3.64%   |
| Intel HD Graphics 500                                                                    | 8         | 3.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 2.27%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5         | 2.27%   |
| Intel HD Graphics 620                                                                    | 5         | 2.27%   |
| Intel HD Graphics 530                                                                    | 5         | 2.27%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.82%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 1.36%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.36%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.36%   |
| Intel HD Graphics 630                                                                    | 3         | 1.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.36%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.36%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2         | 0.91%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.91%   |
| Nvidia GM107GL [Quadro K620]                                                             | 2         | 0.91%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.91%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 0.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.91%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.91%   |
| Intel HD Graphics 610                                                                    | 2         | 0.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.91%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.91%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 0.91%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.91%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 2         | 0.91%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 0.91%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2         | 0.91%   |
| AMD ES1000                                                                               | 2         | 0.91%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.45%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.45%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.45%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.45%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1         | 0.45%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                        | 1         | 0.45%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.45%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.45%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.45%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1         | 0.45%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1         | 0.45%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 0.45%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 0.45%   |
| Nvidia GF119 [NVS 315]                                                                   | 1         | 0.45%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 0.45%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1         | 0.45%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 113       | 51.83%  |
| 1 x AMD        | 30        | 13.76%  |
| 1 x Nvidia     | 26        | 11.93%  |
| 1 x Matrox     | 15        | 6.88%   |
| 1 x ASPEED     | 10        | 4.59%   |
| Other          | 9         | 4.13%   |
| 2 x Intel      | 8         | 3.67%   |
| Intel + Nvidia | 6         | 2.75%   |
| AMD + ASPEED   | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 190       | 86.76%  |
| Proprietary | 19        | 8.68%   |
| Unknown     | 10        | 4.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 185       | 84.47%  |
| 1.01-2.0   | 9         | 4.11%   |
| 0.51-1.0   | 7         | 3.2%    |
| 3.01-4.0   | 6         | 2.74%   |
| 0.01-0.5   | 5         | 2.28%   |
| 7.01-8.0   | 3         | 1.37%   |
| 5.01-6.0   | 3         | 1.37%   |
| 2.01-3.0   | 1         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Goldstar                | 12        | 17.14%  |
| Samsung Electronics     | 7         | 10%     |
| Dell                    | 6         | 8.57%   |
| Chimei Innolux          | 5         | 7.14%   |
| LG Display              | 4         | 5.71%   |
| BOE                     | 4         | 5.71%   |
| BenQ                    | 4         | 5.71%   |
| AU Optronics            | 4         | 5.71%   |
| Lenovo                  | 3         | 4.29%   |
| Chi Mei Optoelectronics | 3         | 4.29%   |
| Sony                    | 2         | 2.86%   |
| Hewlett-Packard         | 2         | 2.86%   |
| Apple                   | 2         | 2.86%   |
| Ancor Communications    | 2         | 2.86%   |
| ViewSonic               | 1         | 1.43%   |
| Videoseven              | 1         | 1.43%   |
| Toshiba                 | 1         | 1.43%   |
| RTK                     | 1         | 1.43%   |
| LTV                     | 1         | 1.43%   |
| LG Electronics          | 1         | 1.43%   |
| Insignia                | 1         | 1.43%   |
| ASUSTek Computer        | 1         | 1.43%   |
| AOC                     | 1         | 1.43%   |
| Acer                    | 1         | 1.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Sony LCD Monitor TV XV 1920x1080                                          | 2         | 2.74%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch    | 2         | 2.74%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 2.74%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch               | 1         | 1.37%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                    | 1         | 1.37%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch                  | 1         | 1.37%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch      | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 330x210mm 15.4-inch      | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch      | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch      | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1210x680mm 54.6-inch    | 1         | 1.37%   |
| RTK CPL AIO PC RTK2482 1920x1080 510x280mm 22.9-inch                      | 1         | 1.37%   |
| LTV LTV1280M1A LTV0A3C 1024x768 800x450mm 36.1-inch                       | 1         | 1.37%   |
| LG Electronics LCD Monitor LG Ultra HD 7680x2160                          | 1         | 1.37%   |
| LG Electronics LCD Monitor LG Ultra HD                                    | 1         | 1.37%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch               | 1         | 1.37%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch               | 1         | 1.37%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch               | 1         | 1.37%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch              | 1         | 1.37%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch                  | 1         | 1.37%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                   | 1         | 1.37%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                   | 1         | 1.37%   |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch                | 1         | 1.37%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch          | 1         | 1.37%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch                | 1         | 1.37%   |
| Goldstar W2442 GSM56D9 1920x1080 530x300mm 24.0-inch                      | 1         | 1.37%   |
| Goldstar W2052 GSM4E88 1680x1050 470x300mm 22.0-inch                      | 1         | 1.37%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                      | 1         | 1.37%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                      | 1         | 1.37%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch               | 1         | 1.37%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch               | 1         | 1.37%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch                | 1         | 1.37%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 1         | 1.37%   |
| Goldstar LG FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                 | 1         | 1.37%   |
| Goldstar LCD Monitor GSM76F5 1920x1080 700x390mm 31.5-inch                | 1         | 1.37%   |
| Goldstar L1920P GSM4A7B 1280x1024 380x300mm 19.1-inch                     | 1         | 1.37%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                    | 1         | 1.37%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                         | 1         | 1.37%   |
| Dell U2713HM DEL407E 2560x1440 600x340mm 27.2-inch                        | 1         | 1.37%   |
| Dell S2721QS DELA198 3840x2160 600x340mm 27.2-inch                        | 1         | 1.37%   |
| Dell P2715Q DEL40BD 3840x2160 600x340mm 27.2-inch                         | 1         | 1.37%   |
| Dell P2311H DEL4067 1920x1080 510x290mm 23.1-inch                         | 1         | 1.37%   |
| Dell LCD Monitor DEL9400 1920x1080 510x290mm 23.1-inch                    | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 340x190mm 15.3-inch          | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14B7 1366x768 310x170mm 13.9-inch           | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch          | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch           | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1367 1920x1080 290x170mm 13.2-inch          | 1         | 1.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 1         | 1.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1333 1366x768 290x160mm 13.0-inch  | 1         | 1.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1312 1280x800 290x180mm 13.4-inch  | 1         | 1.37%   |
| BOE LCD Monitor BOE0817 1366x768 340x190mm 15.3-inch                      | 1         | 1.37%   |
| BOE LCD Monitor BOE07C9 1920x1080 300x170mm 13.6-inch                     | 1         | 1.37%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                     | 1         | 1.37%   |
| BOE LCD Monitor BOE06C2 1366x768 340x190mm 15.3-inch                      | 1         | 1.37%   |
| BenQ XL2430T BNQ7F3D 1920x1080 530x300mm 24.0-inch                        | 1         | 1.37%   |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                         | 1         | 1.37%   |
| BenQ G900HD BNQ7816 1366x768 410x230mm 18.5-inch                          | 1         | 1.37%   |
| BenQ BL2780 BNQ802B 1920x1080 600x340mm 27.2-inch                         | 1         | 1.37%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch            | 1         | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 42.86%  |
| 1366x768 (WXGA)    | 9         | 12.86%  |
| 3840x2160 (4K)     | 6         | 8.57%   |
| 1600x900 (HD+)     | 6         | 8.57%   |
| 1280x800 (WXGA)    | 3         | 4.29%   |
| 3440x1440          | 2         | 2.86%   |
| 2560x1440 (QHD)    | 2         | 2.86%   |
| 2560x1080          | 2         | 2.86%   |
| 1680x1050 (WSXGA+) | 2         | 2.86%   |
| 1280x1024 (SXGA)   | 2         | 2.86%   |
| 7680x2160          | 1         | 1.43%   |
| 1920x1200 (WUXGA)  | 1         | 1.43%   |
| 1440x900 (WXGA+)   | 1         | 1.43%   |
| 1280x854           | 1         | 1.43%   |
| 1024x768 (XGA)     | 1         | 1.43%   |
| Unknown            | 1         | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 13        | 18.31%  |
| 27      | 8         | 11.27%  |
| 15      | 8         | 11.27%  |
| 24      | 7         | 9.86%   |
| 21      | 5         | 7.04%   |
| 23      | 4         | 5.63%   |
| 19      | 4         | 5.63%   |
| 54      | 3         | 4.23%   |
| 34      | 3         | 4.23%   |
| 22      | 3         | 4.23%   |
| 12      | 3         | 4.23%   |
| Unknown | 3         | 4.23%   |
| 17      | 2         | 2.82%   |
| 36      | 1         | 1.41%   |
| 31      | 1         | 1.41%   |
| 28      | 1         | 1.41%   |
| 18      | 1         | 1.41%   |
| 14      | 1         | 1.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 19        | 27.14%  |
| 301-350     | 16        | 22.86%  |
| 401-500     | 10        | 14.29%  |
| 201-300     | 9         | 12.86%  |
| 701-800     | 4         | 5.71%   |
| 351-400     | 4         | 5.71%   |
| 1001-1500   | 3         | 4.29%   |
| Unknown     | 3         | 4.29%   |
| 601-700     | 2         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 52        | 75.36%  |
| 16/10   | 7         | 10.14%  |
| 21/9    | 4         | 5.8%    |
| Unknown | 3         | 4.35%   |
| 5/4     | 2         | 2.9%    |
| 3/2     | 1         | 1.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 18        | 25.35%  |
| 81-90          | 10        | 14.08%  |
| 301-350        | 8         | 11.27%  |
| 71-80          | 4         | 5.63%   |
| 351-500        | 4         | 5.63%   |
| 151-200        | 4         | 5.63%   |
| 101-110        | 4         | 5.63%   |
| 91-100         | 4         | 5.63%   |
| More than 1000 | 3         | 4.23%   |
| 61-70          | 3         | 4.23%   |
| Unknown        | 3         | 4.23%   |
| 251-300        | 2         | 2.82%   |
| 121-130        | 2         | 2.82%   |
| 141-150        | 1         | 1.41%   |
| 501-1000       | 1         | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 29        | 40.85%  |
| 101-120 | 19        | 26.76%  |
| 121-160 | 13        | 18.31%  |
| 161-240 | 6         | 8.45%   |
| Unknown | 3         | 4.23%   |
| 1-50    | 1         | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 144       | 65.16%  |
| 1     | 70        | 31.67%  |
| 2     | 7         | 3.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 161       | 51.77%  |
| Realtek Semiconductor             | 81        | 26.05%  |
| Broadcom                          | 25        | 8.04%   |
| Qualcomm Atheros                  | 20        | 6.43%   |
| Chelsio Communications            | 5         | 1.61%   |
| Ralink                            | 2         | 0.64%   |
| Nvidia                            | 2         | 0.64%   |
| Marvell Technology Group          | 2         | 0.64%   |
| IBM                               | 2         | 0.64%   |
| TP-Link                           | 1         | 0.32%   |
| Ralink Technology                 | 1         | 0.32%   |
| QLogic                            | 1         | 0.32%   |
| MEDIATEK                          | 1         | 0.32%   |
| JMicron Technology                | 1         | 0.32%   |
| Insyde Software                   | 1         | 0.32%   |
| IMC Networks                      | 1         | 0.32%   |
| Google                            | 1         | 0.32%   |
| Ericsson Business Mobile Networks | 1         | 0.32%   |
| Apple                             | 1         | 0.32%   |
| 3Com                              | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 68        | 17.22%  |
| Intel I211 Gigabit Network Connection                                         | 21        | 5.32%   |
| Intel 82574L Gigabit Network Connection                                       | 15        | 3.8%    |
| Intel I350 Gigabit Network Connection                                         | 14        | 3.54%   |
| Intel I210 Gigabit Network Connection                                         | 14        | 3.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 13        | 3.29%   |
| Intel Ethernet Connection I217-LM                                             | 11        | 2.78%   |
| Intel Wireless 7265                                                           | 8         | 2.03%   |
| Intel 82580 Gigabit Network Connection                                        | 8         | 2.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7         | 1.77%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7         | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 1.52%   |
| Intel 82576 Gigabit Network Connection                                        | 6         | 1.52%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 6         | 1.52%   |
| Intel Wireless 7260                                                           | 5         | 1.27%   |
| Intel Wi-Fi 6 AX200                                                           | 5         | 1.27%   |
| Intel 82583V Gigabit Network Connection                                       | 5         | 1.27%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 1.27%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 1.01%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3         | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 3         | 0.76%   |
| Intel Wireless 8265 / 8275                                                    | 3         | 0.76%   |
| Intel Wireless 8260                                                           | 3         | 0.76%   |
| Intel Wireless 3165                                                           | 3         | 0.76%   |
| Intel Ethernet Connection (3) I218-V                                          | 3         | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3         | 0.76%   |
| Intel Centrino Advanced-N 6200                                                | 3         | 0.76%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 0.76%   |
| Intel 82575GB Gigabit Network Connection                                      | 3         | 0.76%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3         | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2         | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 0.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 0.51%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 2         | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 0.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 0.51%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 0.51%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2         | 0.51%   |
| Intel Ethernet Controller X550                                                | 2         | 0.51%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 0.51%   |
| Intel Ethernet Connection I354                                                | 2         | 0.51%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.51%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2         | 0.51%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 0.51%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                          | 2         | 0.51%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2         | 0.51%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 0.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 0.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 0.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 0.51%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2         | 0.51%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 2         | 0.51%   |
| IBM IBM USB Remote NDIS Network Device                                        | 2         | 0.51%   |
| Chelsio T420-CR Unified Wire Ethernet Controller                              | 2         | 0.51%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 2         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 62.65%  |
| Qualcomm Atheros      | 15        | 18.07%  |
| Realtek Semiconductor | 5         | 6.02%   |
| Broadcom              | 5         | 6.02%   |
| Ralink                | 2         | 2.41%   |
| TP-Link               | 1         | 1.2%    |
| Ralink Technology     | 1         | 1.2%    |
| MEDIATEK              | 1         | 1.2%    |
| IMC Networks          | 1         | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 8         | 9.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 7.23%   |
| Intel Wireless 7260                                                     | 5         | 6.02%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 6.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 3.61%   |
| Intel Wireless 8265 / 8275                                              | 3         | 3.61%   |
| Intel Wireless 8260                                                     | 3         | 3.61%   |
| Intel Wireless 3165                                                     | 3         | 3.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 3.61%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 3.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 2.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 2.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 2.41%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 2.41%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                   | 1         | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 1.2%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.2%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.2%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 1.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.2%    |
| Ralink RT5592 PCIe Wireless Network Adapter                             | 1         | 1.2%    |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1         | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.2%    |
| Qualcomm Atheros AR958x 802.11abgn Wireless Network Adapter             | 1         | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.2%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 1.2%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.2%    |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.2%    |
| Intel Wireless-AC 9260                                                  | 1         | 1.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.2%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.2%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.2%    |
| Intel Centrino Wireless-N 100                                           | 1         | 1.2%    |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 1         | 1.2%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 1         | 1.2%    |
| Broadcom BCM4321 802.11b/g/n                                            | 1         | 1.2%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 1.2%    |
| Broadcom BCM4306 802.11b/g Wireless LAN Controller                      | 1         | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 136       | 52.71%  |
| Realtek Semiconductor    | 81        | 31.4%   |
| Broadcom                 | 20        | 7.75%   |
| Qualcomm Atheros         | 8         | 3.1%    |
| Chelsio Communications   | 3         | 1.16%   |
| Nvidia                   | 2         | 0.78%   |
| Marvell Technology Group | 2         | 0.78%   |
| QLogic                   | 1         | 0.39%   |
| JMicron Technology       | 1         | 0.39%   |
| Insyde Software          | 1         | 0.39%   |
| Google                   | 1         | 0.39%   |
| Apple                    | 1         | 0.39%   |
| 3Com                     | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 68        | 22.44%  |
| Intel I211 Gigabit Network Connection                                         | 21        | 6.93%   |
| Intel 82574L Gigabit Network Connection                                       | 15        | 4.95%   |
| Intel I350 Gigabit Network Connection                                         | 14        | 4.62%   |
| Intel I210 Gigabit Network Connection                                         | 14        | 4.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 13        | 4.29%   |
| Intel Ethernet Connection I217-LM                                             | 11        | 3.63%   |
| Intel 82580 Gigabit Network Connection                                        | 8         | 2.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7         | 2.31%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7         | 2.31%   |
| Intel 82576 Gigabit Network Connection                                        | 6         | 1.98%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 6         | 1.98%   |
| Intel 82583V Gigabit Network Connection                                       | 5         | 1.65%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 1.65%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 1.32%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3         | 0.99%   |
| Intel Ethernet Connection (3) I218-V                                          | 3         | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 0.99%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 0.99%   |
| Intel 82575GB Gigabit Network Connection                                      | 3         | 0.99%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3         | 0.99%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2         | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 0.66%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 2         | 0.66%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 0.66%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 0.66%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2         | 0.66%   |
| Intel Ethernet Controller X550                                                | 2         | 0.66%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 0.66%   |
| Intel Ethernet Connection I354                                                | 2         | 0.66%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.66%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.66%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2         | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 0.66%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.66%   |
| Intel Ethernet Connection (2) I218-V                                          | 2         | 0.66%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2         | 0.66%   |
| Intel Ethernet Connection (11) I219-LM                                        | 2         | 0.66%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2         | 0.66%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 2         | 0.66%   |
| Chelsio T420-CR Unified Wire Ethernet Controller                              | 2         | 0.66%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2         | 0.66%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.33%   |
| QLogic ISP4032-based Ethernet IPv6 NIC                                        | 1         | 0.33%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1         | 0.33%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 0.33%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.33%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 1         | 0.33%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 1         | 0.33%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1         | 0.33%   |
| Intel Ethernet Connection X553/X557-AT 10GBASE-T                              | 1         | 0.33%   |
| Intel Ethernet Connection X553 1GbE                                           | 1         | 0.33%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 1         | 0.33%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1         | 0.33%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 1         | 0.33%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.33%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.33%   |
| Intel Ethernet Connection (6) I219-V                                          | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 214       | 70.39%  |
| WiFi     | 81        | 26.64%  |
| Unknown  | 7         | 2.3%    |
| Modem    | 2         | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 203       | 80.24%  |
| WiFi     | 50        | 19.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 88        | 39.82%  |
| 1     | 31        | 14.03%  |
| 3     | 28        | 12.67%  |
| 4     | 26        | 11.76%  |
| 5     | 19        | 8.6%    |
| 6     | 12        | 5.43%   |
| 7     | 6         | 2.71%   |
| 8     | 5         | 2.26%   |
| 0     | 2         | 0.9%    |
| 14    | 1         | 0.45%   |
| 12    | 1         | 0.45%   |
| 10    | 1         | 0.45%   |
| 9     | 1         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 201       | 88.94%  |
| Yes  | 25        | 11.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 53.7%   |
| Cambridge Silicon Radio         | 5         | 9.26%   |
| Qualcomm Atheros Communications | 3         | 5.56%   |
| Broadcom                        | 3         | 5.56%   |
| Realtek Semiconductor           | 2         | 3.7%    |
| IMC Networks                    | 2         | 3.7%    |
| Foxconn / Hon Hai               | 2         | 3.7%    |
| Apple                           | 2         | 3.7%    |
| Alps Electric                   | 2         | 3.7%    |
| Toshiba                         | 1         | 1.85%   |
| MediaTek                        | 1         | 1.85%   |
| Hewlett-Packard                 | 1         | 1.85%   |
| ASUSTek Computer                | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 13        | 24.07%  |
| Intel AX200 Bluetooth                                       | 6         | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 9.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 5         | 9.26%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 5.56%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 5.56%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 3.7%    |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.85%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 1.85%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.85%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 1.85%   |
| MediaTek Wireless_Device                                    | 1         | 1.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.85%   |
| Intel AX201 Bluetooth                                       | 1         | 1.85%   |
| IMC Networks Bluetooth                                      | 1         | 1.85%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 1.85%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.85%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 1.85%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.85%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 1.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.85%   |
| Apple Bluetooth Host Controller                             | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 131       | 65.83%  |
| AMD                 | 30        | 15.08%  |
| Nvidia              | 27        | 13.57%  |
| C-Media Electronics | 3         | 1.51%   |
| Texas Instruments   | 2         | 1.01%   |
| Logitech            | 2         | 1.01%   |
| Yamaha              | 1         | 0.5%    |
| XMOS                | 1         | 0.5%    |
| SteelSeries ApS     | 1         | 0.5%    |
| Creative Labs       | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                                     | Computers | Percent |
|-----------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                          | 18        | 7.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                                       | 16        | 6.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                                | 12        | 4.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                                       | 9         | 3.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                                   | 8         | 3.31%   |
| Intel Sunrise Point-LP HD Audio                                                                           | 8         | 3.31%   |
| Intel Broadwell-U Audio Controller                                                                        | 8         | 3.31%   |
| Intel 8 Series HD Audio Controller                                                                        | 7         | 2.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                           | 7         | 2.89%   |
| Intel Haswell-ULT HD Audio Controller                                                                     | 6         | 2.48%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                         | 6         | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                                                | 6         | 2.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                                  | 6         | 2.48%   |
| AMD Family 17h/19h HD Audio Controller                                                                    | 6         | 2.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                              | 5         | 2.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                                              | 5         | 2.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                                       | 5         | 2.07%   |
| Nvidia High Definition Audio Controller                                                                   | 4         | 1.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                                   | 4         | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller         | 4         | 1.65%   |
| Intel 200 Series PCH HD Audio                                                                             | 4         | 1.65%   |
| AMD FCH Azalia Controller                                                                                 | 4         | 1.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                                       | 4         | 1.65%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                         | 3         | 1.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                            | 3         | 1.24%   |
| Nvidia MCP79 High Definition Audio                                                                        | 2         | 0.83%   |
| Nvidia GP108 High Definition Audio Controller                                                             | 2         | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                           | 2         | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                             | 2         | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                                     | 2         | 0.83%   |
| Nvidia GK106 HDMI Audio Controller                                                                        | 2         | 0.83%   |
| Nvidia GF119 HDMI Audio Controller                                                                        | 2         | 0.83%   |
| Intel Comet Lake PCH-V cAVS                                                                               | 2         | 0.83%   |
| Intel Comet Lake PCH-LP cAVS                                                                              | 2         | 0.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                                                    | 2         | 0.83%   |
| Intel C610/X99 series chipset HD Audio Controller                                                         | 2         | 0.83%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                            | 2         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                                | 2         | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                          | 2         | 0.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                            | 2         | 0.83%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                          | 2         | 0.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                        | 2         | 0.83%   |
| AMD Navi 10 HDMI Audio                                                                                    | 2         | 0.83%   |
| AMD Kaveri HDMI/DP Audio Controller                                                                       | 2         | 0.83%   |
| AMD Kabini HDMI/DP Audio                                                                                  | 2         | 0.83%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                                    | 2         | 0.83%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                              | 2         | 0.83%   |
| Yamaha Steinberg UR22mkII                                                                                 | 1         | 0.41%   |
| XMOS retrieving string failed                                                                             | 1         | 0.41%   |
| Texas Instruments PCM2902 Audio Codec                                                                     | 1         | 0.41%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                         | 1         | 0.41%   |
| SteelSeries ApS Arctis Pro Wireless Arctis Pro Wireless Chat Arctis Pro Wireless Game Arctis Pro Wireless | 1         | 0.41%   |
| Nvidia TU116 High Definition Audio Controller                                                             | 1         | 0.41%   |
| Nvidia TU104 HD Audio Controller                                                                          | 1         | 0.41%   |
| Nvidia MCP73 High Definition Audio                                                                        | 1         | 0.41%   |
| Nvidia MCP55 High Definition Audio                                                                        | 1         | 0.41%   |
| Nvidia MCP51 AC97 Audio Controller                                                                        | 1         | 0.41%   |
| Nvidia GP106 High Definition Audio Controller                                                             | 1         | 0.41%   |
| Nvidia GM206 High Definition Audio Controller                                                             | 1         | 0.41%   |
| Nvidia GM200 High Definition Audio                                                                        | 1         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 40        | 17.09%  |
| Samsung Electronics | 37        | 15.81%  |
| Unknown             | 33        | 14.1%   |
| Kingston            | 33        | 14.1%   |
| Corsair             | 18        | 7.69%   |
| Micron Technology   | 17        | 7.26%   |
| Crucial             | 14        | 5.98%   |
| G.Skill             | 12        | 5.13%   |
| Unknown (ABCD)      | 5         | 2.14%   |
| Apacer              | 4         | 1.71%   |
| Team                | 3         | 1.28%   |
| Ramaxel Technology  | 3         | 1.28%   |
| A-DATA Technology   | 3         | 1.28%   |
| Patriot             | 2         | 0.85%   |
| Nanya Technology    | 2         | 0.85%   |
| V-Color             | 1         | 0.43%   |
| Transcend           | 1         | 0.43%   |
| Toshiba             | 1         | 0.43%   |
| TIMETEC             | 1         | 0.43%   |
| Teikon              | 1         | 0.43%   |
| Cors                | 1         | 0.43%   |
| Avant               | 1         | 0.43%   |
| Unknown             | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 5         | 1.98%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s           | 4         | 1.58%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 3         | 1.19%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 3         | 1.19%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 3         | 1.19%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 1.19%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s               | 3         | 1.19%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 2         | 0.79%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 2         | 0.79%   |
| Unknown RAM Module 1GB SODIMM DDR2                                | 2         | 0.79%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s               | 2         | 0.79%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.79%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.79%   |
| SK Hynix RAM HMT151R7BFR4C-H9 4GB DIMM DDR3 1333MT/s              | 2         | 0.79%   |
| SK Hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s              | 2         | 0.79%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s             | 2         | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 0.79%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s              | 2         | 0.79%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s               | 2         | 0.79%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s               | 2         | 0.79%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s               | 2         | 0.79%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s           | 2         | 0.79%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s                | 2         | 0.79%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s               | 2         | 0.79%   |
| Corsair RAM CMV8GX3M1A1333C9 8GB DIMM DDR3 1333MT/s               | 2         | 0.79%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1333MT/s               | 2         | 0.79%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s             | 2         | 0.79%   |
| V-Color RAM VCOLOR-TD2G16C9-H8 2GB DIMM 1333MT/s                  | 1         | 0.4%    |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                       | 1         | 0.4%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                       | 1         | 0.4%    |
| Unknown RAM Module 8GB DIMM DDR4 2666MT/s                         | 1         | 0.4%    |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                         | 1         | 0.4%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1         | 0.4%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 1         | 0.4%    |
| Unknown RAM Module 8192MB DIMM 667MT/s                            | 1         | 0.4%    |
| Unknown RAM Module 512MB SODIMM SDRAM                             | 1         | 0.4%    |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                         | 1         | 0.4%    |
| Unknown RAM Module 4096MB SODIMM DDR2                             | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                        | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                       | 1         | 0.4%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                         | 1         | 0.4%    |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                         | 1         | 0.4%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1         | 0.4%    |
| Unknown RAM Module 2GB DIMM DDR 1066MT/s                          | 1         | 0.4%    |
| Unknown RAM Module 2GB DIMM 400MT/s                               | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM SDRAM                            | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                     | 1         | 0.4%    |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                       | 1         | 0.4%    |
| Unknown RAM Module 1GB DIMM SDRAM 667MT/s                         | 1         | 0.4%    |
| Unknown RAM Module 1GB DIMM SDRAM                                 | 1         | 0.4%    |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s                       | 1         | 0.4%    |
| Unknown RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.4%    |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s                | 1         | 0.4%    |
| Toshiba RAM 9905678-024.A00G 4GB DIMM DDR4 2133MT/s               | 1         | 0.4%    |
| TIMETEC RAM SD3-1600 8GB DIMM DDR3 1600MT/s                       | 1         | 0.4%    |
| Teikon RAM TMTS4G58DFRBBPN-16 4GB DIMM DDR3 1600MT/s              | 1         | 0.4%    |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s                | 1         | 0.4%    |
| SK Hynix RAM Module 8GB DIMM DDR4 2133MT/s                        | 1         | 0.4%    |
| SK Hynix RAM Module 4GB DIMM DDR4 2133MT/s                        | 1         | 0.4%    |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 110       | 53.92%  |
| DDR4    | 62        | 30.39%  |
| DDR2    | 10        | 4.9%    |
| Unknown | 8         | 3.92%   |
| SDRAM   | 7         | 3.43%   |
| LPDDR4  | 5         | 2.45%   |
| DDR     | 2         | 0.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 121       | 59.9%   |
| SODIMM       | 77        | 38.12%  |
| Row Of Chips | 1         | 0.5%    |
| RIMM         | 1         | 0.5%    |
| FB-DIMM      | 1         | 0.5%    |
| Chip         | 1         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 79        | 35.91%  |
| 8192  | 71        | 32.27%  |
| 2048  | 31        | 14.09%  |
| 16384 | 30        | 13.64%  |
| 1024  | 6         | 2.73%   |
| 512   | 2         | 0.91%   |
| 32768 | 1         | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 67        | 30.88%  |
| 1333    | 37        | 17.05%  |
| 2400    | 26        | 11.98%  |
| 2133    | 14        | 6.45%   |
| 2667    | 12        | 5.53%   |
| 3200    | 11        | 5.07%   |
| Unknown | 9         | 4.15%   |
| 2666    | 6         | 2.76%   |
| 1067    | 6         | 2.76%   |
| 800     | 6         | 2.76%   |
| 667     | 6         | 2.76%   |
| 1334    | 4         | 1.84%   |
| 3600    | 2         | 0.92%   |
| 1867    | 2         | 0.92%   |
| 1866    | 2         | 0.92%   |
| 1066    | 2         | 0.92%   |
| 400     | 2         | 0.92%   |
| 1400    | 1         | 0.46%   |
| 533     | 1         | 0.46%   |
| 333     | 1         | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 50%     |
| Samsung Electronics | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 25%     |
| HP LaserJet 2200                   | 1         | 25%     |
| HP Color LaserJet CP1215           | 1         | 25%     |
| Brother HL-L5200DW series          | 1         | 25%     |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 12        | 37.5%   |
| Realtek Semiconductor         | 4         | 12.5%   |
| Acer                          | 3         | 9.38%   |
| Sunplus Innovation Technology | 2         | 6.25%   |
| Microdia                      | 2         | 6.25%   |
| Logitech                      | 2         | 6.25%   |
| Lite-On Technology            | 2         | 6.25%   |
| IMC Networks                  | 2         | 6.25%   |
| Syntek                        | 1         | 3.13%   |
| Quanta                        | 1         | 3.13%   |
| Lenovo                        | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony integrated camera                | 3         | 9.38%   |
| Lite-On Integrated Camera                | 2         | 6.25%   |
| Acer Integrated Camera                   | 2         | 6.25%   |
| Syntek ASUS USB2.0 camera                | 1         | 3.13%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 3.13%   |
| Sunplus ASUS Webcam                      | 1         | 3.13%   |
| Realtek Realtek USB2.0 PC Camera         | 1         | 3.13%   |
| Realtek Realtek PC Camera                | 1         | 3.13%   |
| Realtek Integrated Webcam HD             | 1         | 3.13%   |
| Realtek Integrated Webcam                | 1         | 3.13%   |
| Quanta USB2.0 HD UVC WebCam              | 1         | 3.13%   |
| Microdia Sonix USB 2.0 Camera            | 1         | 3.13%   |
| Microdia Laptop_Integrated_Webcam_2M     | 1         | 3.13%   |
| Logitech Webcam C310                     | 1         | 3.13%   |
| Logitech HD Pro Webcam C920              | 1         | 3.13%   |
| Lenovo Integrated Webcam [R5U877]        | 1         | 3.13%   |
| IMC Networks UVC VGA Webcam              | 1         | 3.13%   |
| IMC Networks Integrated Webcam           | 1         | 3.13%   |
| Chicony WebCam                           | 1         | 3.13%   |
| Chicony VGA 24fps UVC Webcam             | 1         | 3.13%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 3.13%   |
| Chicony Sonix ST50220 USB Video Camera   | 1         | 3.13%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 3.13%   |
| Chicony HP HD Camera                     | 1         | 3.13%   |
| Chicony HP 0.3MP Webcam                  | 1         | 3.13%   |
| Chicony FJ Camera                        | 1         | 3.13%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 3.13%   |
| Acer SunplusIT Integrated Camera         | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 28.57%  |
| Upek             | 2         | 28.57%  |
| AuthenTec        | 2         | 28.57%  |
| Synaptics        | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 28.57%  |
| Validity Sensors VFS Fingerprint sensor                | 1         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 14.29%  |
| AuthenTec AuthenTec Inc. AES2660                       | 1         | 14.29%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 14.29%  |

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
| 1     | 99        | 44.59%  |
| 0     | 66        | 29.73%  |
| 2     | 40        | 18.02%  |
| 3     | 12        | 5.41%   |
| 4     | 4         | 1.8%    |
| 5     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 131       | 62.09%  |
| Net/wireless             | 16        | 7.58%   |
| Bluetooth                | 14        | 6.64%   |
| Card reader              | 13        | 6.16%   |
| Firewire controller      | 11        | 5.21%   |
| Sound                    | 5         | 2.37%   |
| Network                  | 5         | 2.37%   |
| Net/ethernet             | 5         | 2.37%   |
| Fingerprint reader       | 5         | 2.37%   |
| Storage                  | 2         | 0.95%   |
| Graphics card            | 2         | 0.95%   |
| Storage/raid             | 1         | 0.47%   |
| Storage/ata              | 1         | 0.47%   |

