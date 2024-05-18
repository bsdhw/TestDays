BSD in Russia - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Russia.

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

Total: 340

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Acer          | TravelMate B118-M           | [68d9d26fe5](https://bsd-hardware.info/?probe=68d9d26fe5) | May 09, 2024 |
| Acer          | TravelMate B118-M           | [216637ad84](https://bsd-hardware.info/?probe=216637ad84) | May 08, 2024 |
| Apple         | MacBook4,1                  | [5916d9274d](https://bsd-hardware.info/?probe=5916d9274d) | May 05, 2024 |
| MSI           | GE75 Raider 10SFS           | [227924f274](https://bsd-hardware.info/?probe=227924f274) | May 03, 2024 |
| MSI           | GE75 Raider 10SFS           | [cda74e2f91](https://bsd-hardware.info/?probe=cda74e2f91) | May 02, 2024 |
| Apple         | MacBookPro10,1              | [ae0802fcda](https://bsd-hardware.info/?probe=ae0802fcda) | Apr 25, 2024 |
| Lenovo        | ThinkBook 16 G5+ APH 21K... | [428f8cd2c7](https://bsd-hardware.info/?probe=428f8cd2c7) | Apr 22, 2024 |
| F-Plus Mob... | FLAPTOP r                   | [150e135ba6](https://bsd-hardware.info/?probe=150e135ba6) | Apr 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [20d7b596db](https://bsd-hardware.info/?probe=20d7b596db) | Apr 17, 2024 |
| Lenovo        | ThinkPad E550 20DF005VRT    | [5c50bf1b60](https://bsd-hardware.info/?probe=5c50bf1b60) | Apr 14, 2024 |
| HUAWEI        | MRGFG-XX                    | [94b19fd1c0](https://bsd-hardware.info/?probe=94b19fd1c0) | Apr 13, 2024 |
| Lenovo        | ThinkBook 16 G6+ IMH 21L... | [7ae1277ce9](https://bsd-hardware.info/?probe=7ae1277ce9) | Apr 12, 2024 |
| F-Plus Mob... | FLAPTOP r                   | [21768f1b7a](https://bsd-hardware.info/?probe=21768f1b7a) | Apr 04, 2024 |
| Unknown       | AHP958                      | [69cf299159](https://bsd-hardware.info/?probe=69cf299159) | Apr 04, 2024 |
| Samsung       | 100NZC                      | [2b36397928](https://bsd-hardware.info/?probe=2b36397928) | Apr 03, 2024 |
| Shuttle       | DS77U                       | [1d7eca66fe](https://bsd-hardware.info/?probe=1d7eca66fe) | Mar 31, 2024 |
| MSI           | MS-N014                     | [372cc157f0](https://bsd-hardware.info/?probe=372cc157f0) | Mar 24, 2024 |
| Maibenben     | MaiBook M                   | [48e337257c](https://bsd-hardware.info/?probe=48e337257c) | Mar 14, 2024 |
| Acer          | Nitro AN16-41               | [6ffc9c7b00](https://bsd-hardware.info/?probe=6ffc9c7b00) | Mar 11, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [6b569c8620](https://bsd-hardware.info/?probe=6b569c8620) | Mar 11, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [93771fbea1](https://bsd-hardware.info/?probe=93771fbea1) | Mar 11, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [322c6ac646](https://bsd-hardware.info/?probe=322c6ac646) | Mar 11, 2024 |
| MSI           | Bravo 15 C7VFKP             | [4efb48cb1c](https://bsd-hardware.info/?probe=4efb48cb1c) | Mar 11, 2024 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [7158ba18d1](https://bsd-hardware.info/?probe=7158ba18d1) | Mar 07, 2024 |
| HUAWEI        | CREFG-XX                    | [b16b7180ee](https://bsd-hardware.info/?probe=b16b7180ee) | Mar 05, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [a716cc542a](https://bsd-hardware.info/?probe=a716cc542a) | Mar 04, 2024 |
| Maibenben     | MaiBook X series            | [2a58491971](https://bsd-hardware.info/?probe=2a58491971) | Mar 03, 2024 |
| Acer          | Aspire A715-75G             | [415aa43c5c](https://bsd-hardware.info/?probe=415aa43c5c) | Mar 02, 2024 |
| ASUSTek       | X550EA                      | [42b10a3b6a](https://bsd-hardware.info/?probe=42b10a3b6a) | Mar 01, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [4d63500465](https://bsd-hardware.info/?probe=4d63500465) | Feb 26, 2024 |
| IP3 Techno... | ARN39E                      | [e6405ae506](https://bsd-hardware.info/?probe=e6405ae506) | Feb 26, 2024 |
| ASUSTek       | X550EA                      | [a49aa7d3d8](https://bsd-hardware.info/?probe=a49aa7d3d8) | Feb 24, 2024 |
| HP            | Laptop 15-bs0xx             | [d64816723d](https://bsd-hardware.info/?probe=d64816723d) | Feb 20, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [3cd6bbf6be](https://bsd-hardware.info/?probe=3cd6bbf6be) | Feb 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [a7aada8678](https://bsd-hardware.info/?probe=a7aada8678) | Feb 17, 2024 |
| Deciso        | NetBoard-A20                | [ebbe4a0d21](https://bsd-hardware.info/?probe=ebbe4a0d21) | Feb 17, 2024 |
| ASUSTek       | F8Vr                        | [2f3b6a6089](https://bsd-hardware.info/?probe=2f3b6a6089) | Feb 03, 2024 |
| Intel         | H81U                        | [9b68a7c006](https://bsd-hardware.info/?probe=9b68a7c006) | Jan 25, 2024 |
| Intel         | H81U                        | [c36eaa9c79](https://bsd-hardware.info/?probe=c36eaa9c79) | Jan 24, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [20090cb5c6](https://bsd-hardware.info/?probe=20090cb5c6) | Jan 15, 2024 |
| Rembrandt     | ARB928                      | [47621d7796](https://bsd-hardware.info/?probe=47621d7796) | Jan 10, 2024 |
| Rembrandt     | ARB928                      | [c9a9bfd4aa](https://bsd-hardware.info/?probe=c9a9bfd4aa) | Dec 27, 2023 |
| eMachines     | eM350                       | [00d1d0c359](https://bsd-hardware.info/?probe=00d1d0c359) | Dec 23, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL1... | [97fb2e025e](https://bsd-hardware.info/?probe=97fb2e025e) | Dec 20, 2023 |
| Dell          | Inspiron 5423               | [9368c19a35](https://bsd-hardware.info/?probe=9368c19a35) | Dec 11, 2023 |
| ASUSTek       | X555LB                      | [0df52370a2](https://bsd-hardware.info/?probe=0df52370a2) | Dec 04, 2023 |
| ASUSTek       | X555LB                      | [e96bb84b37](https://bsd-hardware.info/?probe=e96bb84b37) | Dec 02, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [a44d6afa76](https://bsd-hardware.info/?probe=a44d6afa76) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [b67644f2b3](https://bsd-hardware.info/?probe=b67644f2b3) | Nov 24, 2023 |
| Lenovo        | ThinkPad E14 20RA0016RT     | [83b87dac52](https://bsd-hardware.info/?probe=83b87dac52) | Nov 10, 2023 |
| Acer          | Aspire 5336                 | [ebfed0efbc](https://bsd-hardware.info/?probe=ebfed0efbc) | Oct 18, 2023 |
| Intel         | H81U                        | [9ed05368b5](https://bsd-hardware.info/?probe=9ed05368b5) | Oct 18, 2023 |
| Apple         | MacBookPro9,2               | [c88d8880ea](https://bsd-hardware.info/?probe=c88d8880ea) | Oct 11, 2023 |
| Platform      | ARB938                      | [141d043221](https://bsd-hardware.info/?probe=141d043221) | Oct 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [5cd50ed5b5](https://bsd-hardware.info/?probe=5cd50ed5b5) | Sep 24, 2023 |
| Dell          | Latitude E7470              | [11cf3b211c](https://bsd-hardware.info/?probe=11cf3b211c) | Sep 22, 2023 |
| Platform      | ARB938                      | [17b7c850c4](https://bsd-hardware.info/?probe=17b7c850c4) | Sep 14, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [68efc7ef8d](https://bsd-hardware.info/?probe=68efc7ef8d) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [f42dfa2992](https://bsd-hardware.info/?probe=f42dfa2992) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [044910f579](https://bsd-hardware.info/?probe=044910f579) | Sep 01, 2023 |
| MSI           | Sword 17 A11UD              | [4b101af84b](https://bsd-hardware.info/?probe=4b101af84b) | Aug 19, 2023 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0238ea2cab](https://bsd-hardware.info/?probe=0238ea2cab) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [9beb5f6126](https://bsd-hardware.info/?probe=9beb5f6126) | Aug 17, 2023 |
| Fujitsu Si... | LIFEBOOK P1610              | [bb055a94f0](https://bsd-hardware.info/?probe=bb055a94f0) | Aug 12, 2023 |
| Lenovo        | ThinkPad T410 2522NP6       | [194b8efa98](https://bsd-hardware.info/?probe=194b8efa98) | Jul 25, 2023 |
| ASUSTek       | 900                         | [2e55f5d4cc](https://bsd-hardware.info/?probe=2e55f5d4cc) | Jul 20, 2023 |
| MSI           | Sword 17 A11UD              | [c9852c1ee3](https://bsd-hardware.info/?probe=c9852c1ee3) | Jul 19, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [5fcffa5bd6](https://bsd-hardware.info/?probe=5fcffa5bd6) | Jul 19, 2023 |
| IBM           | ThinkPad T43 1871F1G        | [d6fbc6ebfb](https://bsd-hardware.info/?probe=d6fbc6ebfb) | Jul 18, 2023 |
| ASUSTek       | K42Jr                       | [256168572a](https://bsd-hardware.info/?probe=256168572a) | Jul 18, 2023 |
| HP            | EliteBook 6930p             | [12124d8753](https://bsd-hardware.info/?probe=12124d8753) | Jul 15, 2023 |
| Sony          | VPCX115KX                   | [9dab449a23](https://bsd-hardware.info/?probe=9dab449a23) | Jul 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [03e83e60ca](https://bsd-hardware.info/?probe=03e83e60ca) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3096d8532a](https://bsd-hardware.info/?probe=3096d8532a) | Jul 07, 2023 |
| HP            | 250 G6 Notebook PC          | [f7df283c94](https://bsd-hardware.info/?probe=f7df283c94) | Jun 24, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [27ba75252a](https://bsd-hardware.info/?probe=27ba75252a) | Jun 09, 2023 |
| ASUSTek       | 1015BX                      | [ad05aaf9fe](https://bsd-hardware.info/?probe=ad05aaf9fe) | Jun 07, 2023 |
| HP            | Pavilion Notebook           | [1bb0436fe5](https://bsd-hardware.info/?probe=1bb0436fe5) | May 30, 2023 |
| HP            | Pavilion Notebook           | [41ce3c5d11](https://bsd-hardware.info/?probe=41ce3c5d11) | May 21, 2023 |
| Lenovo        | ThinkPad X201 3323BBG       | [7b529b0888](https://bsd-hardware.info/?probe=7b529b0888) | May 17, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [256915976d](https://bsd-hardware.info/?probe=256915976d) | May 12, 2023 |
| MSI           | GE62 6QC                    | [7c3fd3c9ca](https://bsd-hardware.info/?probe=7c3fd3c9ca) | May 08, 2023 |
| HP            | Laptop 14-bs0xx             | [98ea66d6e8](https://bsd-hardware.info/?probe=98ea66d6e8) | May 07, 2023 |
| Samsung       | NC110P/NC108P/NC111P        | [ea55a6fecf](https://bsd-hardware.info/?probe=ea55a6fecf) | May 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [b8d2c0d81d](https://bsd-hardware.info/?probe=b8d2c0d81d) | Apr 16, 2023 |
| Dell          | Inspiron 3542               | [4dfa2f0148](https://bsd-hardware.info/?probe=4dfa2f0148) | Apr 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [b189b0988c](https://bsd-hardware.info/?probe=b189b0988c) | Apr 14, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [3d7bf4205b](https://bsd-hardware.info/?probe=3d7bf4205b) | Apr 13, 2023 |
| HMT           | W041-TF-A-45                | [298d106fd1](https://bsd-hardware.info/?probe=298d106fd1) | Apr 13, 2023 |
| ASUSTek       | X200MA                      | [c30e92db89](https://bsd-hardware.info/?probe=c30e92db89) | Apr 06, 2023 |
| Lenovo        | G570 20079                  | [76cc1653c3](https://bsd-hardware.info/?probe=76cc1653c3) | Apr 03, 2023 |
| Apple         | MacBookPro12,1              | [640aad419a](https://bsd-hardware.info/?probe=640aad419a) | Apr 02, 2023 |
| DNS           | W9x0LU                      | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
| HMT           | W041-TF-A-45                | [666df5a7e0](https://bsd-hardware.info/?probe=666df5a7e0) | Mar 31, 2023 |
| Intel         | Intel                       | [75e9733afd](https://bsd-hardware.info/?probe=75e9733afd) | Mar 30, 2023 |
| Irbis         | NB78                        | [471efbc788](https://bsd-hardware.info/?probe=471efbc788) | Mar 29, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [dddf27cde4](https://bsd-hardware.info/?probe=dddf27cde4) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c2ba6aca7d](https://bsd-hardware.info/?probe=c2ba6aca7d) | Mar 28, 2023 |
| Samsung       | R468/R418                   | [f620a5c6ec](https://bsd-hardware.info/?probe=f620a5c6ec) | Mar 25, 2023 |
| Dell          | G5 5587                     | [9b7714cbab](https://bsd-hardware.info/?probe=9b7714cbab) | Mar 24, 2023 |
| Dell          | G5 5587                     | [c118e0665f](https://bsd-hardware.info/?probe=c118e0665f) | Mar 24, 2023 |
| HUAWEI        | HVY-WXX9                    | [e1b5d66244](https://bsd-hardware.info/?probe=e1b5d66244) | Mar 20, 2023 |
| ASUSTek       | 1015PX                      | [d6c1199165](https://bsd-hardware.info/?probe=d6c1199165) | Mar 20, 2023 |
| ASUSTek       | K501UQ                      | [b7256fddbb](https://bsd-hardware.info/?probe=b7256fddbb) | Mar 19, 2023 |
| IP3 Techno... | ACN1S                       | [d0761f4192](https://bsd-hardware.info/?probe=d0761f4192) | Mar 18, 2023 |
| Toshiba       | Satellite L40               | [2297dcb7e7](https://bsd-hardware.info/?probe=2297dcb7e7) | Mar 17, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [564b1ccce1](https://bsd-hardware.info/?probe=564b1ccce1) | Mar 15, 2023 |
| Samsung       | R468/R418                   | [af44a29d38](https://bsd-hardware.info/?probe=af44a29d38) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [9c1172aa29](https://bsd-hardware.info/?probe=9c1172aa29) | Mar 12, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [5bcd236c4a](https://bsd-hardware.info/?probe=5bcd236c4a) | Mar 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [ef722fc37b](https://bsd-hardware.info/?probe=ef722fc37b) | Feb 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [0232c45faa](https://bsd-hardware.info/?probe=0232c45faa) | Feb 04, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [c2f84d2103](https://bsd-hardware.info/?probe=c2f84d2103) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [d5f06d91db](https://bsd-hardware.info/?probe=d5f06d91db) | Jan 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [448f9265f2](https://bsd-hardware.info/?probe=448f9265f2) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [512bf8f61d](https://bsd-hardware.info/?probe=512bf8f61d) | Jan 27, 2023 |
| Timi          | TM1607                      | [57113d2886](https://bsd-hardware.info/?probe=57113d2886) | Jan 25, 2023 |
| MSI           | PS63 Modern 8M              | [f740e313e5](https://bsd-hardware.info/?probe=f740e313e5) | Jan 24, 2023 |
| Timi          | TM1607                      | [27db14fdbd](https://bsd-hardware.info/?probe=27db14fdbd) | Jan 24, 2023 |
| ASUSTek       | K50IN                       | [6f7a8f3338](https://bsd-hardware.info/?probe=6f7a8f3338) | Jan 23, 2023 |
| Timi          | TM1607                      | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Acer          | Aspire ES1-533              | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| HUAWEI        | CREM-WXX9                   | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| ASUSTek       | K50IN                       | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| Sony          | SVP1321V9RB                 | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| Samsung       | Q430/Q530                   | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| Samsung       | Q430/Q530                   | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| MSI           | PS63 Modern 8M              | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| Acer          | Aspire 5336                 | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
| Kraftway      | KW10T                       | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Dell          | System Vostro 3750          | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| Dell          | Inspiron 15 3511            | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| Dell          | Vostro 5415                 | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [fcfa6205d8](https://bsd-hardware.info/?probe=fcfa6205d8) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6184507a45](https://bsd-hardware.info/?probe=6184507a45) | Aug 21, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Sony          | VGN-UX1XRN                  | [312df080a7](https://bsd-hardware.info/?probe=312df080a7) | Aug 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2da32e59b0](https://bsd-hardware.info/?probe=2da32e59b0) | Aug 14, 2022 |
| Acer          | Aspire 5930                 | [4bd9ec4253](https://bsd-hardware.info/?probe=4bd9ec4253) | Aug 02, 2022 |
| HP            | 250 G6 Notebook PC          | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| Lenovo        | V580 20147                  | [0615e8260d](https://bsd-hardware.info/?probe=0615e8260d) | Jul 02, 2022 |
| Lenovo        | V580 20147                  | [6f1fd71366](https://bsd-hardware.info/?probe=6f1fd71366) | Jul 02, 2022 |
| Acer          | Aspire A114-33              | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Toshiba       | Satellite A300              | [e057898546](https://bsd-hardware.info/?probe=e057898546) | Jun 18, 2022 |
| HP            | Laptop 15s-fq1xxx           | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [73ab89b8f0](https://bsd-hardware.info/?probe=73ab89b8f0) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [637f87f44e](https://bsd-hardware.info/?probe=637f87f44e) | Jun 05, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| HP            | ProBook 455 G7              | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [3ff916acf7](https://bsd-hardware.info/?probe=3ff916acf7) | May 09, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [33367fe342](https://bsd-hardware.info/?probe=33367fe342) | May 09, 2022 |
| Acer          | Aspire ES1-132              | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| HP            | Pavilion g6                 | [4b8ee6729a](https://bsd-hardware.info/?probe=4b8ee6729a) | May 02, 2022 |
| Lenovo        | B50-30 20382                | [5701dac149](https://bsd-hardware.info/?probe=5701dac149) | Apr 30, 2022 |
| DEXP          | NAVIS P100                  | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| DNS           | W9x0LU                      | [8ac57e3b59](https://bsd-hardware.info/?probe=8ac57e3b59) | Apr 06, 2022 |
| Timi          | TM1612                      | [0389c8d487](https://bsd-hardware.info/?probe=0389c8d487) | Apr 05, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [e750905413](https://bsd-hardware.info/?probe=e750905413) | Mar 29, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| Acer          | Aspire A114-33              | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| Packard Be... | EasyNote TE69HW             | [851eea349f](https://bsd-hardware.info/?probe=851eea349f) | Mar 17, 2022 |
| Acer          | Aspire 4820T                | [1617262a28](https://bsd-hardware.info/?probe=1617262a28) | Mar 16, 2022 |
| Acer          | Aspire A315-23              | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| Acer          | Aspire A114-33              | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| ASUSTek       | M51Sr                       | [936a577d1a](https://bsd-hardware.info/?probe=936a577d1a) | Mar 10, 2022 |
| Acer          | Aspire A114-33              | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |
| Acer          | Aspire A114-33              | [da786acd84](https://bsd-hardware.info/?probe=da786acd84) | Feb 20, 2022 |
| Lenovo        | E31-80 80MX                 | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Acer          | Aspire A114-33              | [06887b10fd](https://bsd-hardware.info/?probe=06887b10fd) | Feb 15, 2022 |
| HP            | ProBook 445 G7              | [494195b923](https://bsd-hardware.info/?probe=494195b923) | Feb 08, 2022 |
| Dell          | Venue 11 Pro 7140           | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| HP            | Laptop 15-rb0xx             | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| MSI           | GE75 Raider 10SFS           | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| MSI           | GE75 Raider 10SFS           | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| HP            | Laptop 15-bw0xx             | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [87c8ee9b4c](https://bsd-hardware.info/?probe=87c8ee9b4c) | Dec 31, 2021 |
| HP            | ProBook 655 G1              | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4bb84a33fa](https://bsd-hardware.info/?probe=4bb84a33fa) | Dec 26, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ade9f77281](https://bsd-hardware.info/?probe=ade9f77281) | Nov 25, 2021 |
| Acer          | Aspire 3810T                | [86782a69be](https://bsd-hardware.info/?probe=86782a69be) | Nov 13, 2021 |
| Acer          | Aspire 3810T                | [608e43163d](https://bsd-hardware.info/?probe=608e43163d) | Nov 12, 2021 |
| Lenovo        | S20-30 Touch 20434          | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| ASUSTek       | UX21A                       | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| IBM           | ThinkPad H 1846AQG          | [5e5c7247ca](https://bsd-hardware.info/?probe=5e5c7247ca) | Oct 01, 2021 |
| ASUSTek       | VX7SX                       | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Kraftway      | KW10T                       | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [98072b8db6](https://bsd-hardware.info/?probe=98072b8db6) | Jul 26, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [3fb09d0402](https://bsd-hardware.info/?probe=3fb09d0402) | Jul 24, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [bef816fe74](https://bsd-hardware.info/?probe=bef816fe74) | Jul 24, 2021 |
| Acer          | Aspire A715-75G             | [f613cb0452](https://bsd-hardware.info/?probe=f613cb0452) | Jul 23, 2021 |
| Dell          | Inspiron 5758               | [7542ae751d](https://bsd-hardware.info/?probe=7542ae751d) | Jul 20, 2021 |
| eMachines     | eM350                       | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| eMachines     | eM350                       | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines     | eM350                       | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [62c87cf194](https://bsd-hardware.info/?probe=62c87cf194) | Jun 07, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8fc867cfae](https://bsd-hardware.info/?probe=8fc867cfae) | Jun 06, 2021 |
| Lenovo        | ThinkPad T430 23511A6       | [89fb2aa493](https://bsd-hardware.info/?probe=89fb2aa493) | Jun 05, 2021 |
| Acer          | Aspire ES1-132              | [bf605b741b](https://bsd-hardware.info/?probe=bf605b741b) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [84e93d02e1](https://bsd-hardware.info/?probe=84e93d02e1) | Jun 03, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [1bb850edca](https://bsd-hardware.info/?probe=1bb850edca) | Jun 03, 2021 |
| Acer          | Extensa 2540                | [e7d6ece4ba](https://bsd-hardware.info/?probe=e7d6ece4ba) | Apr 11, 2021 |
| ASUSTek       | 1225B                       | [3eff93bfb5](https://bsd-hardware.info/?probe=3eff93bfb5) | Mar 31, 2021 |
| Samsung       | N145P/N250P/N260P           | [a38a620353](https://bsd-hardware.info/?probe=a38a620353) | Mar 29, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| HP            | ProBook 455 G7              | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| Samsung       | N145P/N250P/N260P           | [eff02dafe1](https://bsd-hardware.info/?probe=eff02dafe1) | Mar 18, 2021 |
| Lenovo        | ThinkPad T480s 20L7001HR... | [ebd44c21d9](https://bsd-hardware.info/?probe=ebd44c21d9) | Mar 17, 2021 |
| Samsung       | N150P                       | [68483fab9d](https://bsd-hardware.info/?probe=68483fab9d) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [52584aaa97](https://bsd-hardware.info/?probe=52584aaa97) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [fb136a79e7](https://bsd-hardware.info/?probe=fb136a79e7) | Mar 13, 2021 |
| Dell          | Latitude 3410               | [80d7bf959a](https://bsd-hardware.info/?probe=80d7bf959a) | Mar 10, 2021 |
| HP            | 255 G3                      | [861bdc647d](https://bsd-hardware.info/?probe=861bdc647d) | Mar 09, 2021 |
| HP            | ProBook 455 G7              | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| HP            | 255 G3                      | [bd82ed65e9](https://bsd-hardware.info/?probe=bd82ed65e9) | Mar 07, 2021 |
| HP            | Compaq 6820s                | [f63d65b78c](https://bsd-hardware.info/?probe=f63d65b78c) | Feb 26, 2021 |
| Dell          | Studio 1537                 | [a4c1d361eb](https://bsd-hardware.info/?probe=a4c1d361eb) | Feb 23, 2021 |
| Apple         | MacBook5,1                  | [41ea02c8bc](https://bsd-hardware.info/?probe=41ea02c8bc) | Feb 21, 2021 |
| Apple         | MacBook5,1                  | [1a374f79df](https://bsd-hardware.info/?probe=1a374f79df) | Feb 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [ed75b3d15b](https://bsd-hardware.info/?probe=ed75b3d15b) | Feb 18, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [3df4abb2e9](https://bsd-hardware.info/?probe=3df4abb2e9) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | [ada1119026](https://bsd-hardware.info/?probe=ada1119026) | Feb 14, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| Sony          | VPCX115KX                   | [fef3d94e6c](https://bsd-hardware.info/?probe=fef3d94e6c) | Feb 12, 2021 |
| Acer          | Extensa 5635Z               | [3b4a7e7fc2](https://bsd-hardware.info/?probe=3b4a7e7fc2) | Feb 10, 2021 |
| Lenovo        | ThinkPad E480 20KN005CRT    | [503378cac9](https://bsd-hardware.info/?probe=503378cac9) | Jan 31, 2021 |
| Sony          | VPCM13M1R                   | [30bb4fc23c](https://bsd-hardware.info/?probe=30bb4fc23c) | Jan 06, 2021 |
| ASUSTek       | X101CH                      | [112792b300](https://bsd-hardware.info/?probe=112792b300) | Jan 02, 2021 |
| ASUSTek       | X101CH                      | [8b571cc947](https://bsd-hardware.info/?probe=8b571cc947) | Jan 02, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [0309e4ac24](https://bsd-hardware.info/?probe=0309e4ac24) | Dec 16, 2020 |
| Acer          | Aspire V5-122               | [ce0c079fd5](https://bsd-hardware.info/?probe=ce0c079fd5) | Dec 14, 2020 |
| Panasonic     | CF-19AHNC8FN                | [04a42812bb](https://bsd-hardware.info/?probe=04a42812bb) | Dec 11, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3a78e7dc1a](https://bsd-hardware.info/?probe=3a78e7dc1a) | Dec 11, 2020 |
| Samsung       | N145P/N250P/N260P           | [b4cb55c681](https://bsd-hardware.info/?probe=b4cb55c681) | Dec 05, 2020 |
| Sony          | SVP1321V9RB                 | [9cddee6a0a](https://bsd-hardware.info/?probe=9cddee6a0a) | Dec 01, 2020 |
| Sony          | VGN-S150(UC)                | [f2f3923ea6](https://bsd-hardware.info/?probe=f2f3923ea6) | Nov 10, 2020 |
| Toshiba       | Satellite M100              | [e6e0a1294c](https://bsd-hardware.info/?probe=e6e0a1294c) | Nov 01, 2020 |
| Sony          | SVP1321V9RB                 | [3f414895be](https://bsd-hardware.info/?probe=3f414895be) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| Dell          | Latitude C400               | [1dcc5e7972](https://bsd-hardware.info/?probe=1dcc5e7972) | Oct 21, 2020 |
| Dell          | Latitude C400               | [8330d23bd7](https://bsd-hardware.info/?probe=8330d23bd7) | Oct 21, 2020 |
| Google        | Chell                       | [4ffe68c199](https://bsd-hardware.info/?probe=4ffe68c199) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [b2e65dd4c5](https://bsd-hardware.info/?probe=b2e65dd4c5) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AL00DKRT    | [623801416c](https://bsd-hardware.info/?probe=623801416c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [a3bc7a0c88](https://bsd-hardware.info/?probe=a3bc7a0c88) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4f54c8f399](https://bsd-hardware.info/?probe=4f54c8f399) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [0e0656d228](https://bsd-hardware.info/?probe=0e0656d228) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [60e72f1c10](https://bsd-hardware.info/?probe=60e72f1c10) | Oct 19, 2020 |
| Acer          | Aspire A315-42              | [1ac21e1660](https://bsd-hardware.info/?probe=1ac21e1660) | Oct 08, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [1f28f1c311](https://bsd-hardware.info/?probe=1f28f1c311) | Aug 30, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [11a0bbb73f](https://bsd-hardware.info/?probe=11a0bbb73f) | Aug 30, 2020 |
| Dell          | Inspiron 15-3567            | [4d1897ed1f](https://bsd-hardware.info/?probe=4d1897ed1f) | Aug 29, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [0e99e72ec9](https://bsd-hardware.info/?probe=0e99e72ec9) | Aug 26, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [b9477154b9](https://bsd-hardware.info/?probe=b9477154b9) | Aug 26, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [19d1c3d086](https://bsd-hardware.info/?probe=19d1c3d086) | Aug 20, 2020 |
| ASUSTek       | X71SL                       | [a2ee0c9edb](https://bsd-hardware.info/?probe=a2ee0c9edb) | Aug 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [bc97c1c0fa](https://bsd-hardware.info/?probe=bc97c1c0fa) | Aug 13, 2020 |
| Dell          | Inspiron 1501               | [9ee3e7cbc2](https://bsd-hardware.info/?probe=9ee3e7cbc2) | Aug 11, 2020 |
| Dell          | Inspiron 1501               | [807aae7095](https://bsd-hardware.info/?probe=807aae7095) | Aug 11, 2020 |
| Dell          | Inspiron 1525               | [d08ea3542e](https://bsd-hardware.info/?probe=d08ea3542e) | Aug 05, 2020 |
| Dell          | Latitude 7490               | [b1d5e8c619](https://bsd-hardware.info/?probe=b1d5e8c619) | Aug 05, 2020 |
| HP            | ProBook 440 G6              | [0227811abb](https://bsd-hardware.info/?probe=0227811abb) | Aug 05, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [0919d8936f](https://bsd-hardware.info/?probe=0919d8936f) | Jul 27, 2020 |
| Lenovo        | G570 20079                  | [15e87049a7](https://bsd-hardware.info/?probe=15e87049a7) | Jul 27, 2020 |
| HP            | ProBook 430 G2              | [3a33aa0d8c](https://bsd-hardware.info/?probe=3a33aa0d8c) | Jun 30, 2020 |
| HP            | ProBook 430 G2              | [365ebdaf9c](https://bsd-hardware.info/?probe=365ebdaf9c) | Jun 30, 2020 |
| Lenovo        | G570 20079                  | [220313b249](https://bsd-hardware.info/?probe=220313b249) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | [7042848932](https://bsd-hardware.info/?probe=7042848932) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | [c7f3bf660a](https://bsd-hardware.info/?probe=c7f3bf660a) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | [b84d1b49d8](https://bsd-hardware.info/?probe=b84d1b49d8) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | [0cc3c53651](https://bsd-hardware.info/?probe=0cc3c53651) | Jun 02, 2020 |
| Dell          | Latitude E5400              | [54854343e4](https://bsd-hardware.info/?probe=54854343e4) | Jun 01, 2020 |
| Dell          | Latitude E6420              | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [68840c222b](https://bsd-hardware.info/?probe=68840c222b) | May 28, 2020 |
| Lenovo        | ThinkPad X240 20AMA52RUK    | [c65cdb97de](https://bsd-hardware.info/?probe=c65cdb97de) | May 28, 2020 |
| Acer          | Aspire 4820T                | [239eea83c6](https://bsd-hardware.info/?probe=239eea83c6) | May 26, 2020 |
| ASUSTek       | GL553VE                     | [dc7bb56859](https://bsd-hardware.info/?probe=dc7bb56859) | May 26, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [9728d93191](https://bsd-hardware.info/?probe=9728d93191) | May 25, 2020 |
| IBM           | ThinkPad X41 2525FAG        | [1e849f86cf](https://bsd-hardware.info/?probe=1e849f86cf) | May 25, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [709a3db7de](https://bsd-hardware.info/?probe=709a3db7de) | May 25, 2020 |
| Lenovo        | G570 20079                  | [0b7b4083bd](https://bsd-hardware.info/?probe=0b7b4083bd) | May 22, 2020 |
| Lenovo        | G570 20079                  | [f7cb1aa38d](https://bsd-hardware.info/?probe=f7cb1aa38d) | May 21, 2020 |
| Dell          | Latitude E6530              | [04cd35a77b](https://bsd-hardware.info/?probe=04cd35a77b) | May 21, 2020 |
| Lenovo        | G570 20079                  | [dc3c3cff26](https://bsd-hardware.info/?probe=dc3c3cff26) | May 21, 2020 |
| Lenovo        | G570 20079                  | [807f3398e3](https://bsd-hardware.info/?probe=807f3398e3) | May 20, 2020 |
| Lenovo        | G570 20079                  | [8212868b9f](https://bsd-hardware.info/?probe=8212868b9f) | May 19, 2020 |
| Lenovo        | G570 20079                  | [ab53dfc003](https://bsd-hardware.info/?probe=ab53dfc003) | May 19, 2020 |
| Lenovo        | G570 20079                  | [d3f180e9ef](https://bsd-hardware.info/?probe=d3f180e9ef) | May 17, 2020 |
| Lenovo        | G570 20079                  | [bdd93164cf](https://bsd-hardware.info/?probe=bdd93164cf) | May 17, 2020 |
| Lenovo        | G570 20079                  | [6a1b7867f0](https://bsd-hardware.info/?probe=6a1b7867f0) | May 16, 2020 |
| Lenovo        | G570 20079                  | [112b83a485](https://bsd-hardware.info/?probe=112b83a485) | May 16, 2020 |
| Lenovo        | G570 20079                  | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| Lenovo        | G570 20079                  | [4a419328b8](https://bsd-hardware.info/?probe=4a419328b8) | May 16, 2020 |
| ASUSTek       | A3L                         | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| ASUSTek       | A3L                         | [0d292bca2f](https://bsd-hardware.info/?probe=0d292bca2f) | May 15, 2020 |
| ASUSTek       | X71SL                       | [2fd46cb7c7](https://bsd-hardware.info/?probe=2fd46cb7c7) | May 15, 2020 |
| ASUSTek       | X71SL                       | [8a027d0a73](https://bsd-hardware.info/?probe=8a027d0a73) | May 14, 2020 |
| Dell          | Latitude E6530              | [2c5eec6613](https://bsd-hardware.info/?probe=2c5eec6613) | May 09, 2020 |
| Dell          | Latitude E6530              | [1542f8e5a8](https://bsd-hardware.info/?probe=1542f8e5a8) | May 09, 2020 |
| ASUSTek       | X71SL                       | [adf290251e](https://bsd-hardware.info/?probe=adf290251e) | May 09, 2020 |
| ASUSTek       | X71SL                       | [7b4d0958ec](https://bsd-hardware.info/?probe=7b4d0958ec) | May 09, 2020 |
| Sony          | SVE1713S1RW                 | [9a751ddfd8](https://bsd-hardware.info/?probe=9a751ddfd8) | May 08, 2020 |
| Lenovo        | G570 20079                  | [25fd1154c0](https://bsd-hardware.info/?probe=25fd1154c0) | May 08, 2020 |
| ASUSTek       | X71SL                       | [ab5297a63d](https://bsd-hardware.info/?probe=ab5297a63d) | May 07, 2020 |
| ASUSTek       | X71SL                       | [b8e364a2c0](https://bsd-hardware.info/?probe=b8e364a2c0) | May 07, 2020 |
| ASUSTek       | X71SL                       | [2aac4c3564](https://bsd-hardware.info/?probe=2aac4c3564) | May 07, 2020 |
| Lenovo        | G570 20079                  | [4909d93faf](https://bsd-hardware.info/?probe=4909d93faf) | May 06, 2020 |
| Lenovo        | G570 20079                  | [fb9c475d48](https://bsd-hardware.info/?probe=fb9c475d48) | May 06, 2020 |
| Lenovo        | G570 20079                  | [2efd2c4c7a](https://bsd-hardware.info/?probe=2efd2c4c7a) | May 06, 2020 |
| Lenovo        | G570 20079                  | [f1c2bcae9d](https://bsd-hardware.info/?probe=f1c2bcae9d) | May 06, 2020 |
| ASUSTek       | A3L                         | [0c73038abc](https://bsd-hardware.info/?probe=0c73038abc) | May 06, 2020 |
| ASUSTek       | A3L                         | [ff5b6e3024](https://bsd-hardware.info/?probe=ff5b6e3024) | May 06, 2020 |
| Lenovo        | G570 20079                  | [eff0d8a3db](https://bsd-hardware.info/?probe=eff0d8a3db) | May 06, 2020 |
| ASUSTek       | X71SL                       | [b48cb0f2ce](https://bsd-hardware.info/?probe=b48cb0f2ce) | May 05, 2020 |
| Lenovo        | G570 20079                  | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |
| Lenovo        | G570 20079                  | [0370bc0522](https://bsd-hardware.info/?probe=0370bc0522) | May 02, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 23        | 9.27%   |
| helloSystem 0.7.0    | 16        | 6.45%   |
| OpenBSD 6.8          | 10        | 4.03%   |
| helloSystem 0.8.0    | 10        | 4.03%   |
| FreeBSD 13.1         | 10        | 4.03%   |
| OpenBSD 7.3          | 8         | 3.23%   |
| FreeBSD 14.0-CURRENT | 8         | 3.23%   |
| NomadBSD 1.3.2       | 7         | 2.82%   |
| FreeBSD 13.1-p5      | 7         | 2.82%   |
| FreeBSD 13.2         | 6         | 2.42%   |
| FreeBSD 13.0         | 6         | 2.42%   |
| OpenBSD 7.1          | 5         | 2.02%   |
| helloSystem 0.8.2    | 5         | 2.02%   |
| FreeBSD 13.0-CURRENT | 5         | 2.02%   |
| NomadBSD 5806f915    | 4         | 1.61%   |
| helloSystem 0.9.0    | 4         | 1.61%   |
| helloSystem 0.6.0    | 4         | 1.61%   |
| FreeBSD 14.0         | 4         | 1.61%   |
| FreeBSD 13.2-p67     | 4         | 1.61%   |
| FreeBSD 12.1-STABLE  | 4         | 1.61%   |
| OpenBSD 6.9          | 3         | 1.21%   |
| GhostBSD 20.04.02    | 3         | 1.21%   |
| FreeBSD 15.0-CURRENT | 3         | 1.21%   |
| FreeBSD 13.2-RC3     | 3         | 1.21%   |
| FreeBSD 13.1-p1      | 3         | 1.21%   |
| FreeBSD 12.2-p4      | 3         | 1.21%   |
| OpenBSD 7.4          | 2         | 0.81%   |
| OpenBSD 7.2          | 2         | 0.81%   |
| OpenBSD 6.7          | 2         | 0.81%   |
| NomadBSD 20221130    | 2         | 0.81%   |
| GhostBSD 24.01.1     | 2         | 0.81%   |
| FreeBSD 14.0-p5      | 2         | 0.81%   |
| FreeBSD 13.2-p9      | 2         | 0.81%   |
| FreeBSD 13.0-p3      | 2         | 0.81%   |
| FreeBSD 12.3-STABLE  | 2         | 0.81%   |
| FreeBSD 12.2-STABLE  | 2         | 0.81%   |
| FreeBSD 12.2-p3      | 2         | 0.81%   |
| FreeBSD 12.1-p8      | 2         | 0.81%   |
| FreeBSD 12.1-p7      | 2         | 0.81%   |
| FreeBSD 12.1-p5      | 2         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 108       | 46.96%  |
| helloSystem | 58        | 25.22%  |
| OpenBSD     | 31        | 13.48%  |
| NomadBSD    | 14        | 6.09%   |
| GhostBSD    | 9         | 3.91%   |
| OPNsense    | 4         | 1.74%   |
| NetBSD      | 3         | 1.3%    |
| OS108       | 1         | 0.43%   |
| LibertyBSD  | 1         | 0.43%   |
| FuguIta     | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 198       | 91.24%  |
| i386  | 19        | 8.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 73        | 31.47%  |
| KDE5          | 35        | 15.09%  |
| Console       | 27        | 11.64%  |
| XFCE          | 21        | 9.05%   |
| Openbox       | 15        | 6.47%   |
| fvwm          | 13        | 5.6%    |
| GNOME         | 12        | 5.17%   |
| MATE          | 10        | 4.31%   |
| TWM           | 8         | 3.45%   |
| ICEWM         | 4         | 1.72%   |
| i3            | 3         | 1.29%   |
| LXQt          | 2         | 0.86%   |
| LXDE          | 2         | 0.86%   |
| AwesomeWM     | 2         | 0.86%   |
| xinitrc       | 1         | 0.43%   |
| StumpWM       | 1         | 0.43%   |
| Lumina        | 1         | 0.43%   |
| Enlightenment | 1         | 0.43%   |
| DWM           | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 189       | 84.75%  |
| Console | 30        | 13.45%  |
| Wayland | 4         | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 84        | 37%     |
| Console | 79        | 34.8%   |
| SDDM    | 35        | 15.42%  |
| LightDM | 15        | 6.61%   |
| XDM     | 6         | 2.64%   |
| GDM     | 6         | 2.64%   |
| PCDM    | 1         | 0.44%   |
| Ly      | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ru_RU   | 80        | 34.33%  |
| Unknown | 50        | 21.46%  |
| en_US   | 49        | 21.03%  |
| C       | 45        | 19.31%  |
| ru      | 4         | 1.72%   |
| fr_FR   | 1         | 0.43%   |
| en_GB   | 1         | 0.43%   |
| en_EN   | 1         | 0.43%   |
| en      | 1         | 0.43%   |
| ba_RU   | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 168       | 75.34%  |
| BIOS | 55        | 24.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 108       | 46.96%  |
| Ufs    | 62        | 26.96%  |
| Ffs    | 33        | 14.35%  |
| Cd9660 | 26        | 11.3%   |
| Xfs    | 1         | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 183       | 83.18%  |
| MBR     | 34        | 15.45%  |
| Unknown | 2         | 0.91%   |
| BSD     | 1         | 0.45%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 60        | 27.65%  |
| ASUSTek Computer    | 28        | 12.9%   |
| Dell                | 22        | 10.14%  |
| Hewlett-Packard     | 19        | 8.76%   |
| Acer                | 18        | 8.29%   |
| Samsung Electronics | 9         | 4.15%   |
| MSI                 | 7         | 3.23%   |
| Sony                | 6         | 2.76%   |
| HUAWEI              | 6         | 2.76%   |
| Apple               | 6         | 2.76%   |
| F-Plus Mobile       | 4         | 1.84%   |
| Toshiba             | 3         | 1.38%   |
| Timi                | 3         | 1.38%   |
| Intel               | 3         | 1.38%   |
| IBM                 | 3         | 1.38%   |
| Maibenben           | 2         | 0.92%   |
| IP3 Technology      | 2         | 0.92%   |
| HMT                 | 2         | 0.92%   |
| Shuttle             | 1         | 0.46%   |
| Rembrandt           | 1         | 0.46%   |
| Platform            | 1         | 0.46%   |
| Panasonic           | 1         | 0.46%   |
| Packard Bell        | 1         | 0.46%   |
| Kraftway            | 1         | 0.46%   |
| Irbis               | 1         | 0.46%   |
| Google              | 1         | 0.46%   |
| Fujitsu Siemens     | 1         | 0.46%   |
| eMachines           | 1         | 0.46%   |
| DNS                 | 1         | 0.46%   |
| DEXP                | 1         | 0.46%   |
| Deciso              | 1         | 0.46%   |
| Unknown             | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| F-Plus Mobile FLAPTOP r       | 4         | 1.84%   |
| Samsung N145P/N250P/N260P     | 2         | 0.92%   |
| MSI PS63 Modern 8M            | 2         | 0.92%   |
| Lenovo IdeaPad 330-15ARR 81D2 | 2         | 0.92%   |
| Lenovo IdeaPad 320-15ISK 80XH | 2         | 0.92%   |
| Lenovo G570 20079             | 2         | 0.92%   |
| Intel H81U                    | 2         | 0.92%   |
| HUAWEI CREM-WXX9              | 2         | 0.92%   |
| HMT W041-TF-A-45              | 2         | 0.92%   |
| Dell Inspiron 15 7000 Gaming  | 2         | 0.92%   |
| Acer Aspire A715-75G          | 2         | 0.92%   |
| Acer Aspire 4820T             | 2         | 0.92%   |
| Toshiba Satellite M100        | 1         | 0.46%   |
| Toshiba Satellite L40         | 1         | 0.46%   |
| Toshiba Satellite A300        | 1         | 0.46%   |
| Timi TM1612                   | 1         | 0.46%   |
| Timi TM1607                   | 1         | 0.46%   |
| Timi Redmi Book Pro 14 2022   | 1         | 0.46%   |
| Sony VPCX115KX                | 1         | 0.46%   |
| Sony VPCM13M1R                | 1         | 0.46%   |
| Sony VGN-UX1XRN               | 1         | 0.46%   |
| Sony VGN-S150(UC)             | 1         | 0.46%   |
| Sony SVP1321V9RB              | 1         | 0.46%   |
| Sony SVE1713S1RW              | 1         | 0.46%   |
| Shuttle DS77U                 | 1         | 0.46%   |
| Samsung R530/R730/R540        | 1         | 0.46%   |
| Samsung R468/R418             | 1         | 0.46%   |
| Samsung Q430/Q530             | 1         | 0.46%   |
| Samsung NC110P/NC108P/NC111P  | 1         | 0.46%   |
| Samsung N150P                 | 1         | 0.46%   |
| Samsung 305E4A/305E5A/305E7A  | 1         | 0.46%   |
| Samsung 100NZC                | 1         | 0.46%   |
| Rembrandt ARB928              | 1         | 0.46%   |
| Platform ARB938               | 1         | 0.46%   |
| Panasonic CF-19AHNC8FN        | 1         | 0.46%   |
| Packard Bell EasyNote TE69HW  | 1         | 0.46%   |
| MSI Sword 17 A11UD            | 1         | 0.46%   |
| MSI MS-N014                   | 1         | 0.46%   |
| MSI GE75 Raider 10SFS         | 1         | 0.46%   |
| MSI GE62 6QC                  | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 30        | 13.82%  |
| Lenovo IdeaPad        | 15        | 6.91%   |
| Acer Aspire           | 14        | 6.45%   |
| Dell Inspiron         | 9         | 4.15%   |
| Dell Latitude         | 8         | 3.69%   |
| HP ProBook            | 6         | 2.76%   |
| ASUS VivoBook         | 6         | 2.76%   |
| Lenovo ThinkBook      | 5         | 2.3%    |
| HP Laptop             | 5         | 2.3%    |
| F-Plus Mobile FLAPTOP | 4         | 1.84%   |
| Toshiba Satellite     | 3         | 1.38%   |
| IBM ThinkPad          | 3         | 1.38%   |
| Samsung N145P         | 2         | 0.92%   |
| MSI PS63              | 2         | 0.92%   |
| Maibenben MaiBook     | 2         | 0.92%   |
| Lenovo Legion         | 2         | 0.92%   |
| Lenovo G570           | 2         | 0.92%   |
| Intel H81U            | 2         | 0.92%   |
| HUAWEI CREM-WXX9      | 2         | 0.92%   |
| HMT W041-TF-A-45      | 2         | 0.92%   |
| HP Pavilion           | 2         | 0.92%   |
| HP EliteBook          | 2         | 0.92%   |
| ASUS ROG              | 2         | 0.92%   |
| Acer Extensa          | 2         | 0.92%   |
| Timi TM1612           | 1         | 0.46%   |
| Timi TM1607           | 1         | 0.46%   |
| Timi Redmi            | 1         | 0.46%   |
| Sony VPCX115KX        | 1         | 0.46%   |
| Sony VPCM13M1R        | 1         | 0.46%   |
| Sony VGN-UX1XRN       | 1         | 0.46%   |
| Sony VGN-S150(UC)     | 1         | 0.46%   |
| Sony SVP1321V9RB      | 1         | 0.46%   |
| Sony SVE1713S1RW      | 1         | 0.46%   |
| Shuttle DS77U         | 1         | 0.46%   |
| Samsung R530          | 1         | 0.46%   |
| Samsung R468          | 1         | 0.46%   |
| Samsung Q430          | 1         | 0.46%   |
| Samsung NC110P        | 1         | 0.46%   |
| Samsung N150P         | 1         | 0.46%   |
| Samsung 305E4A        | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 24        | 11.06%  |
| 2019 | 23        | 10.6%   |
| 2022 | 22        | 10.14%  |
| 2021 | 15        | 6.91%   |
| 2012 | 15        | 6.91%   |
| 2011 | 15        | 6.91%   |
| 2023 | 13        | 5.99%   |
| 2010 | 12        | 5.53%   |
| 2018 | 11        | 5.07%   |
| 2017 | 11        | 5.07%   |
| 2016 | 9         | 4.15%   |
| 2015 | 9         | 4.15%   |
| 2008 | 9         | 4.15%   |
| 2014 | 7         | 3.23%   |
| 2009 | 6         | 2.76%   |
| 2013 | 4         | 1.84%   |
| 2006 | 4         | 1.84%   |
| 2007 | 3         | 1.38%   |
| 2005 | 2         | 0.92%   |
| 2004 | 2         | 0.92%   |
| 2003 | 1         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 217       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 216       | 99.54%  |
| Yes  | 1         | 0.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 61        | 27.6%   |
| 16.01-24.0  | 54        | 24.43%  |
| 4.01-8.0    | 49        | 22.17%  |
| 2.01-3.0    | 19        | 8.6%    |
| 32.01-64.0  | 14        | 6.33%   |
| 1.01-2.0    | 6         | 2.71%   |
| 0.51-1.0    | 6         | 2.71%   |
| 3.01-4.0    | 3         | 1.36%   |
| 24.01-32.0  | 3         | 1.36%   |
| 64.01-256.0 | 3         | 1.36%   |
| 0.01-0.5    | 3         | 1.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 112       | 49.56%  |
| 0.51-1.0   | 55        | 24.34%  |
| 1.01-2.0   | 33        | 14.6%   |
| 2.01-3.0   | 10        | 4.42%   |
| 0          | 5         | 2.21%   |
| Unknown    | 5         | 2.21%   |
| 4.01-8.0   | 4         | 1.77%   |
| 24.01-32.0 | 1         | 0.44%   |
| 8.01-16.0  | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 153       | 66.81%  |
| 2      | 52        | 22.71%  |
| 0      | 19        | 8.3%    |
| 4      | 3         | 1.31%   |
| 3      | 2         | 0.87%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 177       | 81.57%  |
| Yes       | 40        | 18.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 168       | 77.42%  |
| No        | 49        | 22.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 209       | 96.31%  |
| No        | 8         | 3.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 70.64%  |
| No        | 64        | 29.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 217       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Moscow         | 85        | 38.12%  |
| St Petersburg  | 29        | 13%     |
| Yekaterinburg  | 8         | 3.59%   |
| Novosibirsk    | 7         | 3.14%   |
| Vladivostok    | 6         | 2.69%   |
| Ulyanovsk      | 4         | 1.79%   |
| Ufa            | 3         | 1.35%   |
| Tyumen         | 3         | 1.35%   |
| Tolyatti       | 3         | 1.35%   |
| Saratov        | 3         | 1.35%   |
| Perm           | 3         | 1.35%   |
| Krasnoyarsk    | 3         | 1.35%   |
| Kirov          | 3         | 1.35%   |
| Chelyabinsk    | 3         | 1.35%   |
| Tsarskoye Selo | 2         | 0.9%    |
| Surgut         | 2         | 0.9%    |
| Smolensk       | 2         | 0.9%    |
| Ozersk         | 2         | 0.9%    |
| Krasnodar      | 2         | 0.9%    |
| Korolyov       | 2         | 0.9%    |
| Kaliningrad    | 2         | 0.9%    |
| Irkutsk        | 2         | 0.9%    |
| Chita          | 2         | 0.9%    |
| Zhukovskiy     | 1         | 0.45%   |
| Yoshkar-Ola    | 1         | 0.45%   |
| Yegorlykskaya  | 1         | 0.45%   |
| Yaroslavl      | 1         | 0.45%   |
| Voskresensk    | 1         | 0.45%   |
| Voronezh       | 1         | 0.45%   |
| Vorkuta        | 1         | 0.45%   |
| Volgograd      | 1         | 0.45%   |
| Vladimir       | 1         | 0.45%   |
| Vidnoye        | 1         | 0.45%   |
| Ust'-Luga      | 1         | 0.45%   |
| Uba            | 1         | 0.45%   |
| Tver           | 1         | 0.45%   |
| Sochi          | 1         | 0.45%   |
| Snezhinsk      | 1         | 0.45%   |
| Sevastopol'    | 1         | 0.45%   |
| Samara         | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 40        | 49     | 16%     |
| Samsung Electronics | 28        | 37     | 11.2%   |
| Seagate             | 24        | 30     | 9.6%    |
| Toshiba             | 18        | 19     | 7.2%    |
| SanDisk             | 12        | 14     | 4.8%    |
| Intel               | 12        | 15     | 4.8%    |
| SK hynix            | 11        | 12     | 4.4%    |
| Kingston            | 11        | 13     | 4.4%    |
| Hitachi             | 11        | 13     | 4.4%    |
| SPCC                | 7         | 8      | 2.8%    |
| Micron Technology   | 6         | 6      | 2.4%    |
| FORESEE             | 6         | 7      | 2.4%    |
| Transcend           | 5         | 5      | 2%      |
| NVMe                | 5         | 5      | 2%      |
| HGST                | 5         | 7      | 2%      |
| A-DATA Technology   | 5         | 5      | 2%      |
| SSSTC               | 4         | 6      | 1.6%    |
| UMIS                | 3         | 3      | 1.2%    |
| Gigabyte Technology | 3         | 6      | 1.2%    |
| Apple               | 3         | 3      | 1.2%    |
| Apacer              | 3         | 3      | 1.2%    |
| KIOXIA              | 2         | 2      | 0.8%    |
| JetFlash            | 2         | 2      | 0.8%    |
| Innostor            | 2         | 2      | 0.8%    |
| AMD                 | 2         | 2      | 0.8%    |
| USB                 | 1         | 1      | 0.4%    |
| Union Memory        | 1         | 1      | 0.4%    |
| UFD 2.0             | 1         | 1      | 0.4%    |
| Smartbuy            | 1         | 1      | 0.4%    |
| Silicon Motion      | 1         | 1      | 0.4%    |
| SETHRISE            | 1         | 1      | 0.4%    |
| Phison              | 1         | 1      | 0.4%    |
| Patriot             | 1         | 1      | 0.4%    |
| OCZ                 | 1         | 2      | 0.4%    |
| Netac               | 1         | 1      | 0.4%    |
| Lenovo              | 1         | 1      | 0.4%    |
| KLLISRE             | 1         | 1      | 0.4%    |
| KIOXIA-EXCERIA      | 1         | 1      | 0.4%    |
| KINGBANK            | 1         | 1      | 0.4%    |
| Intenso             | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 4         | 1.52%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 1.52%   |
| FORESEE XP1000F001T 1TB              | 4         | 1.52%   |
| WDC WDS240G2G0A-00JH30 240GB         | 3         | 1.14%   |
| SSSTC CL4-8D512 512GB                | 3         | 1.14%   |
| SPCC Solid State Disk 128GB          | 3         | 1.14%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.14%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 1.14%   |
| Samsung SSD 980 1TB                  | 3         | 1.14%   |
| Kingston SV300S37A120G 120GB         | 3         | 1.14%   |
| HGST HTS721010A9E630 1TB             | 3         | 1.14%   |
| WDC WD5000LPVX-60V0TT0 500GB         | 2         | 0.76%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 0.76%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 0.76%   |
| WDC WD2500BEVT-22A23T0 250GB         | 2         | 0.76%   |
| WDC WD10SPZX-08Z10 1TB               | 2         | 0.76%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.76%   |
| WDC PC SN730 SDBPNTY-512G            | 2         | 0.76%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 0.76%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.76%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.76%   |
| SPCC Solid State Disk 120GB          | 2         | 0.76%   |
| Seagate ST9500325AS 500GB            | 2         | 0.76%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.76%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.76%   |
| Samsung MZVL2512HCJQ-00BL2 512GB     | 2         | 0.76%   |
| Samsung MZNTY128HDHP-00000 128GB     | 2         | 0.76%   |
| Micron 2400_MTFDKBA512QFM 512GB      | 2         | 0.76%   |
| Micron 1100 SATA 256GB               | 2         | 0.76%   |
| Kingston SA400S37120G 120GB          | 2         | 0.76%   |
| Kingston OM8SEP4512Q-A0 512GB        | 2         | 0.76%   |
| Intel SSDPEKNU512GZ 512GB            | 2         | 0.76%   |
| Innostor SSD 15GB                    | 2         | 0.76%   |
| Hitachi HDS721616PLA380 160GB        | 2         | 0.76%   |
| Gigabyte GP-AG42TB                   | 2         | 0.76%   |
| A-DATA SX6000LNP 512GB               | 2         | 0.76%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 0.38%   |
| WDC WDS240G1G0B-00RC30 240GB         | 1         | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 30     | 26.67%  |
| WDC                 | 23        | 26     | 25.56%  |
| Toshiba             | 15        | 16     | 16.67%  |
| Hitachi             | 11        | 13     | 12.22%  |
| HGST                | 5         | 7      | 5.56%   |
| NVMe                | 4         | 4      | 4.44%   |
| Samsung Electronics | 2         | 2      | 2.22%   |
| JetFlash            | 2         | 2      | 2.22%   |
| USB                 | 1         | 1      | 1.11%   |
| UFD 2.0             | 1         | 1      | 1.11%   |
| Fujitsu             | 1         | 1      | 1.11%   |
| Apple               | 1         | 1      | 1.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 18     | 15.73%  |
| SanDisk             | 12        | 14     | 13.48%  |
| Kingston            | 8         | 10     | 8.99%   |
| SPCC                | 7         | 8      | 7.87%   |
| Intel               | 7         | 9      | 7.87%   |
| WDC                 | 6         | 7      | 6.74%   |
| Transcend           | 3         | 3      | 3.37%   |
| SK hynix            | 3         | 3      | 3.37%   |
| Micron Technology   | 3         | 3      | 3.37%   |
| Apacer              | 3         | 3      | 3.37%   |
| A-DATA Technology   | 3         | 3      | 3.37%   |
| Innostor            | 2         | 2      | 2.25%   |
| Apple               | 2         | 2      | 2.25%   |
| Union Memory        | 1         | 1      | 1.12%   |
| Smartbuy            | 1         | 1      | 1.12%   |
| SETHRISE            | 1         | 1      | 1.12%   |
| Patriot             | 1         | 1      | 1.12%   |
| OCZ                 | 1         | 2      | 1.12%   |
| NVMe                | 1         | 1      | 1.12%   |
| Netac               | 1         | 1      | 1.12%   |
| KLLISRE             | 1         | 1      | 1.12%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.12%   |
| Intenso             | 1         | 1      | 1.12%   |
| Hewlett-Packard     | 1         | 1      | 1.12%   |
| Goldenfir           | 1         | 1      | 1.12%   |
| Gigabyte Technology | 1         | 3      | 1.12%   |
| FORESEE             | 1         | 2      | 1.12%   |
| ASUSTek Computer    | 1         | 2      | 1.12%   |
| AMD                 | 1         | 1      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 81        | 106    | 35.06%  |
| HDD  | 81        | 104    | 35.06%  |
| NVMe | 69        | 86     | 29.87%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 145       | 210    | 67.76%  |
| NVMe | 69        | 86     | 32.24%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 118       | 161    | 73.29%  |
| 0.51-1.0        | 36        | 42     | 22.36%  |
| 1.01-2.0        | 6         | 6      | 3.73%   |
| More than 100.0 | 1         | 1      | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 62        | 26.27%  |
| 251-500    | 54        | 22.88%  |
| 1-20       | 51        | 21.61%  |
| 501-1000   | 25        | 10.59%  |
| 21-50      | 18        | 7.63%   |
| 51-100     | 18        | 7.63%   |
| 1001-2000  | 6         | 2.54%   |
| Unknown    | 2         | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 170       | 75.56%  |
| 21-50    | 26        | 11.56%  |
| 101-250  | 13        | 5.78%   |
| 51-100   | 8         | 3.56%   |
| 251-500  | 5         | 2.22%   |
| Unknown  | 2         | 0.89%   |
| 501-1000 | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 7.32%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 4.88%   |
| Micron Technology 1100 SATA 256GB     | 2         | 2      | 4.88%   |
| WDC WDS240G2G0A-00JH30 240GB          | 1         | 1      | 2.44%   |
| WDC WD5000LPLX-60ZNTT1 500GB          | 1         | 1      | 2.44%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 2      | 2.44%   |
| WDC WD2000JB-00GVC0 200GB             | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 2.44%   |
| Toshiba MK7575GSX 752GB               | 1         | 1      | 2.44%   |
| Toshiba MK2546GSX 250GB               | 1         | 1      | 2.44%   |
| Toshiba MK1646GSX 160GB               | 1         | 1      | 2.44%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 2.44%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 2.44%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 2.44%   |
| Seagate ST9250320AS 250GB             | 1         | 1      | 2.44%   |
| Seagate ST9250315AS 250GB             | 1         | 2      | 2.44%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 2.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 2.44%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 2.44%   |
| Samsung Electronics HM080HI 80GB      | 1         | 1      | 2.44%   |
| Kingston SV300S37A120G 120GB          | 1         | 1      | 2.44%   |
| Intel SSDSC2KW120H6 120GB             | 1         | 1      | 2.44%   |
| Intel SSDSC2CW060A3 64GB              | 1         | 1      | 2.44%   |
| Intel SSDSC2BW480H6 480GB             | 1         | 1      | 2.44%   |
| Intel SSDSC2BB480G7 480GB             | 1         | 1      | 2.44%   |
| Hitachi HTS725025A9A364 250GB         | 1         | 1      | 2.44%   |
| Hitachi HTS721060G9AT00 64GB          | 1         | 1      | 2.44%   |
| Hitachi HTS547564A9E384 640GB         | 1         | 1      | 2.44%   |
| Hitachi HTS547550A9E384 500GB         | 1         | 1      | 2.44%   |
| Hitachi HTS541616J9SA00 160GB         | 1         | 1      | 2.44%   |
| Hitachi HTS541612J9SA00 120GB         | 1         | 1      | 2.44%   |
| Hitachi HTC426060G9AT00 64GB          | 1         | 1      | 2.44%   |
| Hitachi DK23AA-12 12GB                | 1         | 1      | 2.44%   |
| HGST HTS541075A7E630 752GB            | 1         | 2      | 2.44%   |
| HGST HTE725032A7E630 320GB            | 1         | 1      | 2.44%   |
| Apple SSD SD0128F 121GB               | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 24.39%  |
| Hitachi             | 8         | 8      | 19.51%  |
| Toshiba             | 6         | 6      | 14.63%  |
| WDC                 | 4         | 5      | 9.76%   |
| Intel               | 4         | 4      | 9.76%   |
| Samsung Electronics | 2         | 2      | 4.88%   |
| Micron Technology   | 2         | 2      | 4.88%   |
| HGST                | 2         | 3      | 4.88%   |
| SK hynix            | 1         | 1      | 2.44%   |
| Kingston            | 1         | 1      | 2.44%   |
| Apple               | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 33.33%  |
| Hitachi             | 8         | 8      | 26.67%  |
| Toshiba             | 6         | 6      | 20%     |
| WDC                 | 3         | 4      | 10%     |
| HGST                | 2         | 3      | 6.67%   |
| Samsung Electronics | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 33     | 73.17%  |
| SSD  | 9         | 9      | 21.95%  |
| NVMe | 2         | 2      | 4.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| SanDisk pSSD 16GB             | 1         | 1      | 50%     |
| Hitachi HTS545025B9A300 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 169       | 240    | 76.47%  |
| Malfunc  | 41        | 44     | 18.55%  |
| Detected | 9         | 10     | 4.07%   |
| Failed   | 2         | 2      | 0.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 138       | 55.2%   |
| AMD                                     | 28        | 11.2%   |
| Samsung Electronics                     | 15        | 6%      |
| SanDisk                                 | 14        | 5.6%    |
| SK hynix                                | 10        | 4%      |
| Shenzhen Longsys Electronics            | 5         | 2%      |
| Phison Electronics                      | 5         | 2%      |
| Solid State Storage Technology          | 4         | 1.6%    |
| Silicon Motion                          | 3         | 1.2%    |
| Shenzhen Unionmemory Information System | 3         | 1.2%    |
| Micron Technology                       | 3         | 1.2%    |
| KIOXIA                                  | 3         | 1.2%    |
| Kingston Technology Company             | 3         | 1.2%    |
| Transcend                               | 2         | 0.8%    |
| Toshiba                                 | 2         | 0.8%    |
| Realtek Semiconductor                   | 2         | 0.8%    |
| Nvidia                                  | 2         | 0.8%    |
| Union Memory (Shenzhen)                 | 1         | 0.4%    |
| Silicon Integrated Systems [SiS]        | 1         | 0.4%    |
| Netac Technology                        | 1         | 0.4%    |
| MAXIO Technology (Hangzhou)             | 1         | 0.4%    |
| Marvell Technology Group                | 1         | 0.4%    |
| Lenovo                                  | 1         | 0.4%    |
| JMicron Technology                      | 1         | 0.4%    |
| ADATA Technology                        | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                                                | 24        | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 16        | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 11        | 4.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 9         | 3.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 9         | 3.41%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                                               | 7         | 2.65%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                                                 | 7         | 2.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 6         | 2.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                                                   | 6         | 2.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 6         | 2.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 6         | 2.27%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 5         | 1.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 5         | 1.89%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 5         | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                                                      | 5         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 5         | 1.89%   |
| SK hynix BC501 NVMe Solid State Drive                                                                              | 4         | 1.52%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                                              | 4         | 1.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 4         | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                                                  | 4         | 1.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                                              | 4         | 1.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                                           | 4         | 1.52%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                                                  | 4         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller                                   | 4         | 1.52%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                                             | 4         | 1.52%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                                             | 4         | 1.52%   |
| Solid State Storage CL4-8D512 NVMe SSD M.2 (DRAM-less)                                                             | 3         | 1.14%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                                               | 3         | 1.14%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 3         | 1.14%   |
| Intel Volume Management Device NVMe RAID Controller                                                                | 3         | 1.14%   |
| Intel Tiger Lake-LP SATA Controller                                                                                | 3         | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                                                              | 3         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                                                  | 3         | 1.14%   |
| SK hynix BC511 NVMe SSD                                                                                            | 2         | 0.76%   |
| Shenzhen Unionmemory Information System RPEYJ1T24MKN2QWY PCIe 4.0 NVMe SSD 1024GB (DRAM-less)                      | 2         | 0.76%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                                                  | 2         | 0.76%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 2         | 0.76%   |
| Phison E16 PCIe4 NVMe Controller                                                                                   | 2         | 0.76%   |
| Nvidia MCP79 AHCI Controller                                                                                       | 2         | 0.76%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                                                   | 2         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 141       | 55.73%  |
| NVMe | 78        | 30.83%  |
| IDE  | 25        | 9.88%   |
| RAID | 9         | 3.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 157       | 72.02%  |
| AMD    | 60        | 27.52%  |
| 11th   | 1         | 0.46%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 2.7%    |
| Intel CPU Version                             | 4         | 1.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.8%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 3         | 1.35%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 3         | 1.35%   |
| Intel C1                                      | 3         | 1.35%   |
| Intel Atom CPU N570 @ 1.66GHz                 | 3         | 1.35%   |
| AMD Ryzen 9 7940HS w/ Radeon 780M Graphics    | 3         | 1.35%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 3         | 1.35%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.35%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 3         | 1.35%   |
| Intel Pentium M processor 1.60GHz             | 2         | 0.9%    |
| Intel Pentium M processor                     | 2         | 0.9%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 2         | 0.9%    |
| Intel Genuine CPU                             | 2         | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.9%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.9%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.9%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.9%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.9%    |
| Intel Core 2 Duo                              | 2         | 0.9%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 0.9%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.9%    |
| Intel 686-class                               | 2         | 0.9%    |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 2         | 0.9%    |
| AMD Ryzen 7 7735H with Radeon Graphics        | 2         | 0.9%    |
| AMD Ryzen 7 6800H with Radeon Graphics        | 2         | 0.9%    |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 0.9%    |
| AMD Ryzen 5 5600U with Radeon Graphics        | 2         | 0.9%    |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 0.9%    |
| AMD Ryzen 3 4300U with Radeon Graphics        | 2         | 0.9%    |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 0.9%    |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 2         | 0.9%    |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 2         | 0.9%    |
| Intel Xeon W-10885M CPU @ 2.40GHz             | 1         | 0.45%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 36        | 16.44%  |
| Intel Core i7           | 24        | 10.96%  |
| AMD Ryzen 7             | 20        | 9.13%   |
| Other                   | 19        | 8.68%   |
| Intel Core i3           | 17        | 7.76%   |
| Intel Celeron           | 10        | 4.57%   |
| Intel Atom              | 10        | 4.57%   |
| Intel Core 2 Duo        | 9         | 4.11%   |
| AMD Ryzen 5             | 8         | 3.65%   |
| AMD Ryzen 3             | 8         | 3.65%   |
| Intel Pentium           | 7         | 3.2%    |
| AMD Ryzen 9             | 6         | 2.74%   |
| Intel Pentium M         | 5         | 2.28%   |
| Intel Genuine           | 5         | 2.28%   |
| AMD A6                  | 5         | 2.28%   |
| AMD Ryzen 7 PRO         | 3         | 1.37%   |
| AMD E                   | 3         | 1.37%   |
| Intel Xeon              | 2         | 0.91%   |
| Intel Pentium Silver    | 2         | 0.91%   |
| Intel Pentium Dual-Core | 2         | 0.91%   |
| Intel Core m3           | 2         | 0.91%   |
| Intel 686-class         | 2         | 0.91%   |
| AMD E1                  | 2         | 0.91%   |
| Intel Core Solo         | 1         | 0.46%   |
| Intel Core m5           | 1         | 0.46%   |
| Intel Core M            | 1         | 0.46%   |
| Intel Core i9           | 1         | 0.46%   |
| Intel Core              | 1         | 0.46%   |
| Intel Celeron M         | 1         | 0.46%   |
| Intel Celeron Dual-Core | 1         | 0.46%   |
| AMD EPYC                | 1         | 0.46%   |
| AMD E2                  | 1         | 0.46%   |
| AMD C-60                | 1         | 0.46%   |
| AMD A8                  | 1         | 0.46%   |
| AMD A10                 | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 85        | 38.46%  |
| 4       | 54        | 24.43%  |
| 16      | 24        | 10.86%  |
| Unknown | 20        | 9.05%   |
| 1       | 14        | 6.33%   |
| 8       | 13        | 5.88%   |
| 12      | 6         | 2.71%   |
| 6       | 3         | 1.36%   |
| 22      | 1         | 0.45%   |
| 10      | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 209       | 94.14%  |
| Unknown | 12        | 5.41%   |
| 2       | 1         | 0.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 101       | 45.7%   |
| 1       | 90        | 40.72%  |
| Unknown | 30        | 13.57%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 29        | 13.3%   |
| Unknown       | 21        | 9.63%   |
| Zen 3         | 14        | 6.42%   |
| Skylake       | 14        | 6.42%   |
| SandyBridge   | 12        | 5.5%    |
| Penryn        | 12        | 5.5%    |
| Bonnell       | 12        | 5.5%    |
| P6            | 11        | 5.05%   |
| Zen 2         | 9         | 4.13%   |
| IvyBridge     | 9         | 4.13%   |
| Silvermont    | 8         | 3.67%   |
| Westmere      | 7         | 3.21%   |
| TigerLake     | 7         | 3.21%   |
| Haswell       | 7         | 3.21%   |
| Broadwell     | 7         | 3.21%   |
| Core          | 6         | 2.75%   |
| Zen+          | 5         | 2.29%   |
| Zen           | 4         | 1.83%   |
| Goldmont      | 4         | 1.83%   |
| Excavator     | 4         | 1.83%   |
| CometLake     | 3         | 1.38%   |
| Bobcat        | 3         | 1.38%   |
| Puma          | 2         | 0.92%   |
| Jaguar        | 2         | 0.92%   |
| Goldmont plus | 2         | 0.92%   |
| Piledriver    | 1         | 0.46%   |
| K8 Hammer     | 1         | 0.46%   |
| K10 Llano     | 1         | 0.46%   |
| IceLake       | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 141       | 54.02%  |
| AMD    | 75        | 28.74%  |
| Nvidia | 44        | 16.86%  |
| ATI    | 1         | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 4.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 4.04%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 9         | 3.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 2.94%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 8         | 2.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 2.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 2.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.21%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 2.21%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.84%   |
| AMD Phoenix1                                                                             | 5         | 1.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.47%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.47%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.47%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 3         | 1.1%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 1.1%    |
| Intel HD Graphics 630                                                                    | 3         | 1.1%    |
| Intel HD Graphics 620                                                                    | 3         | 1.1%    |
| Intel HD Graphics 520                                                                    | 3         | 1.1%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3         | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.1%    |
| AMD Barcelo                                                                              | 3         | 1.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.74%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.74%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.74%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                          | 2         | 0.74%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 0.74%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.74%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.74%   |
| Intel HD Graphics 515                                                                    | 2         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 86        | 39.27%  |
| 1 x AMD        | 56        | 25.57%  |
| Intel + Nvidia | 29        | 13.24%  |
| 2 x Intel      | 22        | 10.05%  |
| AMD + Nvidia   | 9         | 4.11%   |
| 1 x Nvidia     | 6         | 2.74%   |
| 2 x AMD        | 5         | 2.28%   |
| Intel + AMD    | 5         | 2.28%   |
| Other          | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 196       | 87.89%  |
| Unknown     | 15        | 6.73%   |
| Proprietary | 12        | 5.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 165       | 73.66%  |
| 0.01-0.5   | 40        | 17.86%  |
| 0.51-1.0   | 9         | 4.02%   |
| 1.01-2.0   | 6         | 2.68%   |
| 3.01-4.0   | 3         | 1.34%   |
| 2.01-3.0   | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 36        | 23.38%  |
| BOE                     | 27        | 17.53%  |
| Chimei Innolux          | 21        | 13.64%  |
| LG Display              | 18        | 11.69%  |
| Samsung Electronics     | 12        | 7.79%   |
| InfoVision              | 4         | 2.6%    |
| Apple                   | 4         | 2.6%    |
| LG Philips              | 3         | 1.95%   |
| HKC                     | 3         | 1.95%   |
| Chi Mei Optoelectronics | 3         | 1.95%   |
| Acer                    | 3         | 1.95%   |
| ViewSonic               | 2         | 1.3%    |
| PANDA                   | 2         | 1.3%    |
| Lenovo                  | 2         | 1.3%    |
| HannStar                | 2         | 1.3%    |
| CSO                     | 2         | 1.3%    |
| Toshiba                 | 1         | 0.65%   |
| TMX                     | 1         | 0.65%   |
| Sharp                   | 1         | 0.65%   |
| Panasonic               | 1         | 0.65%   |
| OOO                     | 1         | 0.65%   |
| NEC Computers           | 1         | 0.65%   |
| Goldstar                | 1         | 0.65%   |
| Dell                    | 1         | 0.65%   |
| CPT                     | 1         | 0.65%   |
| Ancor Communications    | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                    | 3         | 1.94%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 330x210mm 15.4-inch     | 2         | 1.29%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 2         | 1.29%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 2         | 1.29%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch         | 2         | 1.29%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 340x190mm 15.3-inch         | 2         | 1.29%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 2         | 1.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO1457 1366x768 310x170mm 13.9-inch | 2         | 1.29%   |
| BOE LCD Monitor BOE0AC1 2560x1600 340x210mm 15.7-inch                    | 2         | 1.29%   |
| BOE HF BOE0691 1920x1080 280x160mm 12.7-inch                             | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 2         | 1.29%   |
| Acer K272HUL ACR0524 2560x1440 600x340mm 27.2-inch                       | 2         | 1.29%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch            | 1         | 0.65%   |
| ViewSonic LCD Monitor VSC6F2E 1920x1080 480x270mm 21.7-inch              | 1         | 0.65%   |
| Toshiba TV TSB0108 1360x768 890x500mm 40.2-inch                          | 1         | 0.65%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x170mm 13.9-inch                  | 1         | 0.65%   |
| Sharp LQ156T1JW05 SHP1574 2560x1440 340x190mm 15.3-inch                  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5643 1280x800 300x190mm 14.0-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 300x170mm 13.6-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 300x190mm 14.0-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch   | 1         | 0.65%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 0.65%   |
| PANDA LCD Monitor NCP002B 1920x1080 310x170mm 13.9-inch                  | 1         | 0.65%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch              | 1         | 0.65%   |
| OOO HDMI OOO2700 2560x1440 600x330mm 27.0-inch                           | 1         | 0.65%   |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch            | 1         | 0.65%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 0.65%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch              | 1         | 0.65%   |
| LG Philips LCD Monitor LPL0301 1280x800 330x210mm 15.4-inch              | 1         | 0.65%   |
| LG Display LCD Monitor LGD06FF 1920x1080 340x190mm 15.3-inch             | 1         | 0.65%   |
| LG Display LCD Monitor LGD065A 1920x1080 340x190mm 15.3-inch             | 1         | 0.65%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch             | 1         | 0.65%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch             | 1         | 0.65%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 66        | 43.42%  |
| 1366x768 (WXGA)   | 36        | 23.68%  |
| 2560x1440 (QHD)   | 8         | 5.26%   |
| 1280x800 (WXGA)   | 8         | 5.26%   |
| 2560x1600         | 5         | 3.29%   |
| 1600x900 (HD+)    | 5         | 3.29%   |
| 1024x600          | 5         | 3.29%   |
| 1440x900 (WXGA+)  | 4         | 2.63%   |
| 3840x2160 (4K)    | 3         | 1.97%   |
| 2880x1800         | 2         | 1.32%   |
| 1280x1024 (SXGA)  | 2         | 1.32%   |
| 3200x1800 (QHD+)  | 1         | 0.66%   |
| 2560x1080         | 1         | 0.66%   |
| 2520x1680         | 1         | 0.66%   |
| 2240x1400         | 1         | 0.66%   |
| 2160x1440         | 1         | 0.66%   |
| 2160x1350         | 1         | 0.66%   |
| 1920x540          | 1         | 0.66%   |
| 1920x1200 (WUXGA) | 1         | 0.66%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 69        | 44.81%  |
| 13      | 37        | 24.03%  |
| 17      | 10        | 6.49%   |
| 14      | 7         | 4.55%   |
| 11      | 6         | 3.9%    |
| 10      | 6         | 3.9%    |
| 12      | 5         | 3.25%   |
| 27      | 3         | 1.95%   |
| 21      | 2         | 1.3%    |
| 16      | 2         | 1.3%    |
| 54      | 1         | 0.65%   |
| 40      | 1         | 0.65%   |
| 34      | 1         | 0.65%   |
| 31      | 1         | 0.65%   |
| 23      | 1         | 0.65%   |
| 19      | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 99        | 64.29%  |
| 201-300     | 33        | 21.43%  |
| 351-400     | 11        | 7.14%   |
| 501-600     | 4         | 2.6%    |
| 401-500     | 2         | 1.3%    |
| 801-900     | 1         | 0.65%   |
| 701-800     | 1         | 0.65%   |
| 601-700     | 1         | 0.65%   |
| 1001-1500   | 1         | 0.65%   |
| Unknown     | 1         | 0.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 115       | 78.77%  |
| 16/10   | 22        | 15.07%  |
| 3/2     | 5         | 3.42%   |
| 5/4     | 2         | 1.37%   |
| 21/9    | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 56        | 36.36%  |
| 81-90          | 37        | 24.03%  |
| 101-110        | 9         | 5.84%   |
| 71-80          | 7         | 4.55%   |
| 121-130        | 7         | 4.55%   |
| 51-60          | 6         | 3.9%    |
| 41-50          | 6         | 3.9%    |
| 111-120        | 6         | 3.9%    |
| 61-70          | 4         | 2.6%    |
| 301-350        | 3         | 1.95%   |
| 201-250        | 3         | 1.95%   |
| 131-140        | 3         | 1.95%   |
| 351-500        | 2         | 1.3%    |
| More than 1000 | 1         | 0.65%   |
| 151-200        | 1         | 0.65%   |
| 141-150        | 1         | 0.65%   |
| 501-1000       | 1         | 0.65%   |
| Unknown        | 1         | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 68        | 44.16%  |
| 101-120       | 41        | 26.62%  |
| 161-240       | 23        | 14.94%  |
| 51-100        | 16        | 10.39%  |
| More than 240 | 4         | 2.6%    |
| 1-50          | 1         | 0.65%   |
| Unknown       | 1         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 166       | 73.45%  |
| 0     | 48        | 21.24%  |
| 2     | 12        | 5.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 123       | 33.06%  |
| Realtek Semiconductor             | 108       | 29.03%  |
| Qualcomm Atheros                  | 58        | 15.59%  |
| Broadcom                          | 22        | 5.91%   |
| Marvell Technology Group          | 12        | 3.23%   |
| TP-Link                           | 8         | 2.15%   |
| MediaTek                          | 5         | 1.34%   |
| Xiaomi                            | 4         | 1.08%   |
| Ralink Technology                 | 4         | 1.08%   |
| Samsung Electronics               | 3         | 0.81%   |
| Ralink                            | 2         | 0.54%   |
| JMicron Technology                | 2         | 0.54%   |
| Huawei Technologies               | 2         | 0.54%   |
| Fibocom                           | 2         | 0.54%   |
| Ericsson Business Mobile Networks | 2         | 0.54%   |
| Arduino SA                        | 2         | 0.54%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.27%   |
| Shenzhen Goodix Technology        | 1         | 0.27%   |
| Realtek                           | 1         | 0.27%   |
| OPPO Electronics                  | 1         | 0.27%   |
| Nvidia                            | 1         | 0.27%   |
| Mercucys                          | 1         | 0.27%   |
| Dell                              | 1         | 0.27%   |
| D-Link                            | 1         | 0.27%   |
| BUFFALO                           | 1         | 0.27%   |
| Attansic                          | 1         | 0.27%   |
| Atheros                           | 1         | 0.27%   |
| AMD                               | 1         | 0.27%   |
| 3Com                              | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 71        | 16.28%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 3.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 14        | 3.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 2.52%   |
| Intel Wireless 7265                                                     | 11        | 2.52%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 11        | 2.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 1.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 1.83%   |
| Intel Wireless 8265 / 8275                                              | 7         | 1.61%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.38%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 6         | 1.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 5         | 1.15%   |
| Intel Wireless 8260                                                     | 5         | 1.15%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.15%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 4         | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.92%   |
| Intel Wireless 3165                                                     | 4         | 0.92%   |
| Intel Ethernet Connection I219-LM                                       | 4         | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 3         | 0.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 0.69%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.69%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 3         | 0.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.69%   |
| Intel Wireless 7260                                                     | 3         | 0.69%   |
| Intel WiFi Link 5100                                                    | 3         | 0.69%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 3         | 0.69%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 3         | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.69%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                | 3         | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 114       | 48.51%  |
| Qualcomm Atheros      | 50        | 21.28%  |
| Realtek Semiconductor | 34        | 14.47%  |
| Broadcom              | 15        | 6.38%   |
| TP-Link               | 8         | 3.4%    |
| Ralink Technology     | 4         | 1.7%    |
| MediaTek              | 4         | 1.7%    |
| Ralink                | 2         | 0.85%   |
| Mercucys              | 1         | 0.43%   |
| D-Link                | 1         | 0.43%   |
| BUFFALO               | 1         | 0.43%   |
| Atheros               | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 7.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 4.56%   |
| Intel Wireless 7265                                                     | 11        | 4.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 11        | 4.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 3.32%   |
| Intel Wireless 8265 / 8275                                              | 7         | 2.9%    |
| Intel Wi-Fi 6 AX200                                                     | 7         | 2.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 2.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 2.07%   |
| Intel Wireless 8260                                                     | 5         | 2.07%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.07%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.66%   |
| Intel Wireless 3165                                                     | 4         | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.66%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 1.24%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.24%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.24%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 3         | 1.24%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.24%   |
| Intel Wireless 7260                                                     | 3         | 1.24%   |
| Intel WiFi Link 5100                                                    | 3         | 1.24%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 3         | 1.24%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 3         | 1.24%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.24%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.83%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 2         | 0.83%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.83%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 2         | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 88        | 49.44%  |
| Intel                            | 34        | 19.1%   |
| Qualcomm Atheros                 | 17        | 9.55%   |
| Marvell Technology Group         | 12        | 6.74%   |
| Broadcom                         | 10        | 5.62%   |
| Xiaomi                           | 4         | 2.25%   |
| Samsung Electronics              | 3         | 1.69%   |
| JMicron Technology               | 2         | 1.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Realtek                          | 1         | 0.56%   |
| OPPO Electronics                 | 1         | 0.56%   |
| Nvidia                           | 1         | 0.56%   |
| MediaTek                         | 1         | 0.56%   |
| Attansic                         | 1         | 0.56%   |
| AMD                              | 1         | 0.56%   |
| 3Com                             | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 71        | 39.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 14        | 7.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 4.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 6         | 3.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5         | 2.79%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 2.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 1.68%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express               | 3         | 1.68%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 1.12%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 1.12%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 2         | 1.12%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 1.12%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.12%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 1.12%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.12%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.12%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.56%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.56%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1         | 0.56%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.56%   |
| OPPO WAIPIO-MTP _SN:2EE444D0 RNDIS Control RNDIS Ethernet Data         | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.56%   |
| MediaTek USB Ethernet-RNDIS                                            | 1         | 0.56%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                | 1         | 0.56%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.56%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.56%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.56%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                  | 1         | 0.56%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                   | 1         | 0.56%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 1         | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 209       | 53.18%  |
| Ethernet | 168       | 42.75%  |
| Unknown  | 9         | 2.29%   |
| Modem    | 7         | 1.78%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 138       | 57.26%  |
| Ethernet | 101       | 41.91%  |
| Unknown  | 2         | 0.83%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 157       | 72.35%  |
| 1     | 55        | 25.35%  |
| 3     | 3         | 1.38%   |
| 6     | 1         | 0.46%   |
| 0     | 1         | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 214       | 97.27%  |
| Yes  | 6         | 2.73%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 81        | 51.59%  |
| Qualcomm Atheros Communications | 17        | 10.83%  |
| Realtek Semiconductor           | 12        | 7.64%   |
| IMC Networks                    | 7         | 4.46%   |
| Broadcom                        | 6         | 3.82%   |
| Apple                           | 6         | 3.82%   |
| Foxconn / Hon Hai               | 5         | 3.18%   |
| Lite-On Technology              | 4         | 2.55%   |
| ASUSTek Computer                | 4         | 2.55%   |
| Skylight Digital                | 3         | 1.91%   |
| Alps Electric                   | 3         | 1.91%   |
| Hewlett-Packard                 | 2         | 1.27%   |
| TP-Link                         | 1         | 0.64%   |
| Taiyo Yuden                     | 1         | 0.64%   |
| Shenzhen Goodix Technology      | 1         | 0.64%   |
| Ralink                          | 1         | 0.64%   |
| Opticis                         | 1         | 0.64%   |
| MediaTek                        | 1         | 0.64%   |
| Dell                            | 1         | 0.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 27        | 17.2%   |
| Intel AX201 Bluetooth                                       | 12        | 7.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 6.37%   |
| Intel AX210 Bluetooth                                       | 10        | 6.37%   |
| Intel Wireless-AC 3168 Bluetooth                            | 8         | 5.1%    |
| Intel AX200 Bluetooth                                       | 7         | 4.46%   |
| Realtek Bluetooth Adapter                                   | 6         | 3.82%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 5         | 3.18%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 4         | 2.55%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 3         | 1.91%   |
| Realtek RTL8723B Bluetooth                                  | 3         | 1.91%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 1.91%   |
| Intel AX211 Bluetooth                                       | 3         | 1.91%   |
| Apple Bluetooth Host Controller                             | 3         | 1.91%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 2         | 1.27%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 1.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.27%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.27%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.27%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 2         | 1.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 1.27%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.27%   |
| ASUS BT-270 Bluetooth Adapter                               | 2         | 1.27%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 1.27%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 1         | 0.64%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                     | 1         | 0.64%   |
| Shenzhen Goodix retrieving string failed                    | 1         | 0.64%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.64%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.64%   |
| Qualcomm Atheros QCA9565 Bluetooth 4.0 + HS Adapter         | 1         | 0.64%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.64%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.64%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.64%   |
| Opticis Realtek Bluetooth Adapter                           | 1         | 0.64%   |
| MediaTek RZ608 Bluetooth Adapter                            | 1         | 0.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.64%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 0.64%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.64%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 0.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 153       | 62.96%  |
| AMD                              | 64        | 26.34%  |
| Nvidia                           | 17        | 7%      |
| Lenovo                           | 3         | 1.23%   |
| Texas Instruments                | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |
| Generalplus Technology           | 1         | 0.41%   |
| ESS Technology                   | 1         | 0.41%   |
| Creative Technology              | 1         | 0.41%   |
| C-Media Electronics              | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 44        | 13.97%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 25        | 7.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 6.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 4.44%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 12        | 3.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 3.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 3.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 2.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 2.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 2.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.22%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 2.22%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 2.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.9%    |
| AMD FCH Azalia Controller                                                                         | 6         | 1.9%    |
| Unknown                                                                                           | 5         | 1.59%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.27%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.27%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.27%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.95%   |
| Lenovo Realtek USB Audio                                                                          | 3         | 0.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.95%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.95%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 0.95%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.95%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.63%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.63%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 0.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.63%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 63        | 27.39%  |
| SK hynix            | 43        | 18.7%   |
| Unknown             | 28        | 12.17%  |
| Micron Technology   | 24        | 10.43%  |
| Kingston            | 22        | 9.57%   |
| Unknown             | 17        | 7.39%   |
| Elpida              | 5         | 2.17%   |
| Crucial             | 5         | 2.17%   |
| Transcend           | 3         | 1.3%    |
| Ramaxel Technology  | 3         | 1.3%    |
| A-DATA Technology   | 3         | 1.3%    |
| 48spaces            | 3         | 1.3%    |
| Corsair             | 2         | 0.87%   |
| Apacer              | 2         | 0.87%   |
| Unknown (ABCD)      | 1         | 0.43%   |
| Unknown (0x0809)    | 1         | 0.43%   |
| Silicon Power       | 1         | 0.43%   |
| Rayson              | 1         | 0.43%   |
| PUSKILL             | 1         | 0.43%   |
| GeIL                | 1         | 0.43%   |
| AMD                 | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 17        | 6.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 5         | 2.05%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 4         | 1.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                     | 4         | 1.64%   |
| Unknown RAM Module 512MB SODIMM DDR                                       | 3         | 1.23%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 3         | 1.23%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 3         | 1.23%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 3         | 1.23%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 3         | 1.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 3         | 1.23%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.23%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                     | 3         | 1.23%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 3         | 1.23%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s                  | 3         | 1.23%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 3         | 1.23%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s                | 3         | 1.23%   |
| 48spaces RAM 012345678901234567890123456789012345 1GB SODIMM DDR2 800MT/s | 3         | 1.23%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 2         | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s                    | 2         | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 0.82%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.82%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 2         | 0.82%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 2         | 0.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 2         | 0.82%   |
| Samsung RAM M471A1K43EB1-CWE 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.82%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 0.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 0.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.82%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                                | 2         | 0.82%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                      | 2         | 0.82%   |
| Kingston RAM KHX2400C14S4/4G 4GB SODIMM DDR4 2400MT/s                     | 2         | 0.82%   |
| Kingston RAM 9905700-011.A00G 8192MB SODIMM DDR4 2400MT/s                 | 2         | 0.82%   |
| Unknown RAM Module 512MB SODIMM DRAM                                      | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                               | 1         | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                                 | 1         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                               | 1         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3                                        | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 84        | 41.79%  |
| DDR3    | 54        | 26.87%  |
| DDR2    | 18        | 8.96%   |
| LPDDR5  | 8         | 3.98%   |
| DDR5    | 8         | 3.98%   |
| LPDDR3  | 7         | 3.48%   |
| DDR     | 6         | 2.99%   |
| SDRAM   | 5         | 2.49%   |
| Unknown | 5         | 2.49%   |
| DRAM    | 3         | 1.49%   |
| LPDDR4  | 2         | 1%      |
| RAM     | 1         | 0.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 180       | 89.55%  |
| Row Of Chips | 16        | 7.96%   |
| DIMM         | 3         | 1.49%   |
| Chip         | 1         | 0.5%    |
| Unknown      | 1         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 77        | 34.38%  |
| 4096  | 57        | 25.45%  |
| 2048  | 40        | 17.86%  |
| 16384 | 24        | 10.71%  |
| 1024  | 14        | 6.25%   |
| 32768 | 4         | 1.79%   |
| 512   | 4         | 1.79%   |
| 256   | 2         | 0.89%   |
| 2560  | 1         | 0.45%   |
| 128   | 1         | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 38        | 17.92%  |
| 1600    | 34        | 16.04%  |
| 2667    | 28        | 13.21%  |
| 2400    | 18        | 8.49%   |
| 1333    | 12        | 5.66%   |
| 667     | 12        | 5.66%   |
| Unknown | 12        | 5.66%   |
| 800     | 9         | 4.25%   |
| 6400    | 7         | 3.3%    |
| 2133    | 7         | 3.3%    |
| 1867    | 7         | 3.3%    |
| 4800    | 5         | 2.36%   |
| 1334    | 5         | 2.36%   |
| 1067    | 4         | 1.89%   |
| 5600    | 3         | 1.42%   |
| 2048    | 2         | 0.94%   |
| 266     | 2         | 0.94%   |
| 7500    | 1         | 0.47%   |
| 4267    | 1         | 0.47%   |
| 2933    | 1         | 0.47%   |
| 1639    | 1         | 0.47%   |
| 975     | 1         | 0.47%   |
| 400     | 1         | 0.47%   |
| 100     | 1         | 0.47%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 38        | 22.89%  |
| IMC Networks                           | 21        | 12.65%  |
| Microdia                               | 17        | 10.24%  |
| Realtek Semiconductor                  | 13        | 7.83%   |
| Bison Electronics                      | 12        | 7.23%   |
| Quanta                                 | 8         | 4.82%   |
| Syntek                                 | 5         | 3.01%   |
| Suyin                                  | 5         | 3.01%   |
| Sunplus Innovation Technology          | 5         | 3.01%   |
| Silicon Motion                         | 5         | 3.01%   |
| Luxvisions Innotech Limited            | 5         | 3.01%   |
| Lite-On Technology                     | 4         | 2.41%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.41%   |
| ALi                                    | 4         | 2.41%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 1.81%   |
| Jiangxi Shinetech Optical              | 3         | 1.81%   |
| Lenovo                                 | 2         | 1.2%    |
| DigiTech                               | 2         | 1.2%    |
| Apple                                  | 2         | 1.2%    |
| Z-Star Microelectronics                | 1         | 0.6%    |
| Y Media                                | 1         | 0.6%    |
| Unknown (3730304233435731375051)       | 1         | 0.6%    |
| Supreme Electronics                    | 1         | 0.6%    |
| Ricoh                                  | 1         | 0.6%    |
| Intel                                  | 1         | 0.6%    |
| Genesys Logic                          | 1         | 0.6%    |
| Denron                                 | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 13        | 7.74%   |
| Microdia Integrated_Webcam_HD                 | 7         | 4.17%   |
| IMC Networks Integrated Camera                | 6         | 3.57%   |
| Silicon Motion WebCam SCX Series              | 4         | 2.38%   |
| Microdia USB Camera                           | 4         | 2.38%   |
| IMC Networks EasyCamera                       | 4         | 2.38%   |
| Bison Integrated Camera                       | 4         | 2.38%   |
| Realtek USB 2.0 PC Camera                     | 3         | 1.79%   |
| Realtek Acer 640 x 480 laptop camera          | 3         | 1.79%   |
| Quanta VGA WebCam                             | 3         | 1.79%   |
| Luxvisions Innotech Limited Integrated Camera | 3         | 1.79%   |
| Bison Lenovo EasyCamera                       | 3         | 1.79%   |
| ALi Gateway Webcam                            | 3         | 1.79%   |
| Syntek Integrated Camera                      | 2         | 1.19%   |
| Syntek EasyCamera                             | 2         | 1.19%   |
| Sunplus Hy HD Camera                          | 2         | 1.19%   |
| Realtek Integrated Webcam                     | 2         | 1.19%   |
| Quanta Realtek PC Camera                      | 2         | 1.19%   |
| Microdia Integrated Webcam                    | 2         | 1.19%   |
| Lite-On Integrated Camera                     | 2         | 1.19%   |
| Lite-On HP HD Camera                          | 2         | 1.19%   |
| Jiangxi Shinetech Optical HD Camera           | 2         | 1.19%   |
| IMC Networks UVC VGA Webcam                   | 2         | 1.19%   |
| IMC Networks Realtek DMFT RGB                 | 2         | 1.19%   |
| DigiTech WebCam SCB-0350M                     | 2         | 1.19%   |
| Chicony XiaoMi USB 2.0 Webcam                 | 2         | 1.19%   |
| Chicony USB2.0 HD UVC WebCam                  | 2         | 1.19%   |
| Chicony Lenovo EasyCamera                     | 2         | 1.19%   |
| Chicony EasyCamera                            | 2         | 1.19%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 2         | 1.19%   |
| Bison SunplusIT Integrated Camera             | 2         | 1.19%   |
| Bison Lenovo Integrated Webcam                | 2         | 1.19%   |
| Z-Star Webcam                                 | 1         | 0.6%    |
| Y Media USB Camera                            | 1         | 0.6%    |
| Unknown (3730304233435731375051) USB Camera   | 1         | 0.6%    |
| Syntek Lenovo EasyCamera                      | 1         | 0.6%    |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 0.6%    |
| Suyin HP Webcam                               | 1         | 0.6%    |
| Suyin HD WebCam                               | 1         | 0.6%    |
| Suyin HD Video WebCam                         | 1         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 12        | 25%     |
| Validity Sensors           | 10        | 20.83%  |
| FocalTech Systems          | 5         | 10.42%  |
| AuthenTec                  | 5         | 10.42%  |
| STMicroelectronics         | 4         | 8.33%   |
| Elan Microelectronics      | 4         | 8.33%   |
| Upek                       | 3         | 6.25%   |
| Shenzhen Goodix Technology | 3         | 6.25%   |
| Fingerprint Cards          | 1         | 2.08%   |
| Broadcom                   | 1         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 7         | 14.58%  |
| FocalTech Systems Fingerprint Reader                                         | 5         | 10.42%  |
| STMicroelectronics Fingerprint Reader                                        | 4         | 8.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 6.25%   |
| Shenzhen Goodix  Fingerprint Device                                          | 3         | 6.25%   |
| Elan WBF Fingerprint Sensor                                                  | 3         | 6.25%   |
| AuthenTec AES1600                                                            | 3         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 4.17%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 4.17%   |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 2         | 4.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 2.08%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 2.08%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 2.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 2.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 2.08%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 1         | 2.08%   |
| Fingerprint Cards FPC Fingerprint Reader                                     | 1         | 2.08%   |
| Elan Fingerprint Sensor                                                      | 1         | 2.08%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.08%   |
| AuthenTec AES2810                                                            | 1         | 2.08%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 2.08%   |

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
| 1     | 82        | 35.19%  |
| 2     | 56        | 24.03%  |
| 0     | 37        | 15.88%  |
| 3     | 32        | 13.73%  |
| 4     | 18        | 7.73%   |
| 5     | 4         | 1.72%   |
| 9     | 1         | 0.43%   |
| 8     | 1         | 0.43%   |
| 7     | 1         | 0.43%   |
| 6     | 1         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 107       | 30.23%  |
| Net/wireless             | 54        | 15.25%  |
| Bluetooth                | 50        | 14.12%  |
| Card reader              | 44        | 12.43%  |
| Fingerprint reader       | 41        | 11.58%  |
| Firewire controller      | 14        | 3.95%   |
| Graphics card            | 12        | 3.39%   |
| Sound                    | 10        | 2.82%   |
| Network                  | 8         | 2.26%   |
| Storage                  | 5         | 1.41%   |
| Modem                    | 4         | 1.13%   |
| Storage/ata              | 3         | 0.85%   |
| Net/ethernet             | 2         | 0.56%   |

