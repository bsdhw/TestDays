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

Total: 299

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| helloSystem 0.8.1    | 20        | 9.39%   |
| helloSystem 0.7.0    | 15        | 7.04%   |
| OpenBSD 6.8          | 10        | 4.69%   |
| helloSystem 0.8.0    | 10        | 4.69%   |
| FreeBSD 13.1         | 10        | 4.69%   |
| OpenBSD 7.3          | 8         | 3.76%   |
| FreeBSD 14.0-CURRENT | 8         | 3.76%   |
| NomadBSD 1.3.2       | 7         | 3.29%   |
| FreeBSD 13.1-p5      | 7         | 3.29%   |
| FreeBSD 13.0         | 6         | 2.82%   |
| OpenBSD 7.1          | 5         | 2.35%   |
| helloSystem 0.8.2    | 5         | 2.35%   |
| FreeBSD 13.2         | 5         | 2.35%   |
| FreeBSD 13.0-CURRENT | 5         | 2.35%   |
| NomadBSD 5806f915    | 4         | 1.88%   |
| helloSystem 0.6.0    | 4         | 1.88%   |
| FreeBSD 12.1-STABLE  | 4         | 1.88%   |
| OpenBSD 6.9          | 3         | 1.41%   |
| GhostBSD 20.04.02    | 3         | 1.41%   |
| FreeBSD 13.2-RC3     | 3         | 1.41%   |
| FreeBSD 13.1-p1      | 3         | 1.41%   |
| FreeBSD 12.2-p4      | 3         | 1.41%   |
| OpenBSD 7.2          | 2         | 0.94%   |
| OpenBSD 6.7          | 2         | 0.94%   |
| NomadBSD 20221130    | 2         | 0.94%   |
| FreeBSD 13.0-p3      | 2         | 0.94%   |
| FreeBSD 12.3-STABLE  | 2         | 0.94%   |
| FreeBSD 12.2-STABLE  | 2         | 0.94%   |
| FreeBSD 12.2-p3      | 2         | 0.94%   |
| FreeBSD 12.1-p8      | 2         | 0.94%   |
| FreeBSD 12.1-p7      | 2         | 0.94%   |
| FreeBSD 12.1-p5      | 2         | 0.94%   |
| OS108 9.0            | 1         | 0.47%   |
| OPNsense 23.7.6      | 1         | 0.47%   |
| OpenBSD 7.0          | 1         | 0.47%   |
| NomadBSD 1.4         | 1         | 0.47%   |
| NomadBSD 1.3.1       | 1         | 0.47%   |
| NetBSD 9.99.94       | 1         | 0.47%   |
| NetBSD 9.1           | 1         | 0.47%   |
| NetBSD 7.2           | 1         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 88        | 44.9%   |
| helloSystem | 51        | 26.02%  |
| OpenBSD     | 29        | 14.8%   |
| NomadBSD    | 14        | 7.14%   |
| GhostBSD    | 7         | 3.57%   |
| NetBSD      | 3         | 1.53%   |
| OS108       | 1         | 0.51%   |
| OPNsense    | 1         | 0.51%   |
| LibertyBSD  | 1         | 0.51%   |
| FuguIta     | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 166       | 89.73%  |
| i386  | 19        | 10.27%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 65        | 32.83%  |
| KDE5          | 25        | 12.63%  |
| Console       | 20        | 10.1%   |
| XFCE          | 18        | 9.09%   |
| Openbox       | 14        | 7.07%   |
| fvwm          | 13        | 6.57%   |
| MATE          | 10        | 5.05%   |
| GNOME         | 10        | 5.05%   |
| TWM           | 6         | 3.03%   |
| IceWM         | 3         | 1.52%   |
| i3            | 3         | 1.52%   |
| LXQt          | 2         | 1.01%   |
| LXDE          | 2         | 1.01%   |
| AwesomeWM     | 2         | 1.01%   |
| xinitrc       | 1         | 0.51%   |
| StumpWM       | 1         | 0.51%   |
| Lumina        | 1         | 0.51%   |
| Enlightenment | 1         | 0.51%   |
| DWM           | 1         | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 164       | 85.86%  |
| Console | 25        | 13.09%  |
| Wayland | 2         | 1.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 77        | 39.9%   |
| Console | 69        | 35.75%  |
| SDDM    | 24        | 12.44%  |
| LightDM | 11        | 5.7%    |
| XDM     | 6         | 3.11%   |
| GDM     | 4         | 2.07%   |
| PCDM    | 1         | 0.52%   |
| Ly      | 1         | 0.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ru_RU   | 69        | 34.85%  |
| en_US   | 45        | 22.73%  |
| Unknown | 40        | 20.2%   |
| C       | 36        | 18.18%  |
| ru      | 4         | 2.02%   |
| en_GB   | 1         | 0.51%   |
| en_EN   | 1         | 0.51%   |
| en      | 1         | 0.51%   |
| ba_RU   | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 138       | 72.25%  |
| BIOS | 53        | 27.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 85        | 43.59%  |
| Ufs    | 57        | 29.23%  |
| Ffs    | 31        | 15.9%   |
| Cd9660 | 21        | 10.77%  |
| Xfs    | 1         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 151       | 80.32%  |
| MBR     | 34        | 18.09%  |
| Unknown | 2         | 1.06%   |
| BSD     | 1         | 0.53%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 53        | 28.65%  |
| Dell                | 22        | 11.89%  |
| ASUSTek Computer    | 22        | 11.89%  |
| Hewlett-Packard     | 18        | 9.73%   |
| Acer                | 15        | 8.11%   |
| Samsung Electronics | 8         | 4.32%   |
| Sony                | 6         | 3.24%   |
| MSI                 | 5         | 2.7%    |
| HUAWEI              | 4         | 2.16%   |
| Apple               | 4         | 2.16%   |
| Toshiba             | 3         | 1.62%   |
| Timi                | 3         | 1.62%   |
| IBM                 | 3         | 1.62%   |
| F-Plus Mobile       | 3         | 1.62%   |
| Intel               | 2         | 1.08%   |
| HMT                 | 2         | 1.08%   |
| Rembrandt           | 1         | 0.54%   |
| Platform            | 1         | 0.54%   |
| Panasonic           | 1         | 0.54%   |
| Packard Bell        | 1         | 0.54%   |
| Kraftway            | 1         | 0.54%   |
| Irbis               | 1         | 0.54%   |
| IP3 Technology      | 1         | 0.54%   |
| Google              | 1         | 0.54%   |
| Fujitsu Siemens     | 1         | 0.54%   |
| eMachines           | 1         | 0.54%   |
| DNS                 | 1         | 0.54%   |
| DEXP                | 1         | 0.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| F-Plus Mobile FLAPTOP r             | 3         | 1.62%   |
| Samsung N145P/N250P/N260P           | 2         | 1.08%   |
| MSI PS63 Modern 8M                  | 2         | 1.08%   |
| Lenovo IdeaPad 330-15ARR 81D2       | 2         | 1.08%   |
| Lenovo IdeaPad 320-15ISK 80XH       | 2         | 1.08%   |
| Lenovo G570 20079                   | 2         | 1.08%   |
| HUAWEI CREM-WXX9                    | 2         | 1.08%   |
| HMT W041-TF-A-45                    | 2         | 1.08%   |
| Dell Inspiron 15 7000 Gaming        | 2         | 1.08%   |
| Acer Aspire 4820T                   | 2         | 1.08%   |
| Toshiba Satellite M100              | 1         | 0.54%   |
| Toshiba Satellite L40               | 1         | 0.54%   |
| Toshiba Satellite A300              | 1         | 0.54%   |
| Timi TM1612                         | 1         | 0.54%   |
| Timi TM1607                         | 1         | 0.54%   |
| Timi Redmi Book Pro 14 2022         | 1         | 0.54%   |
| Sony VPCX115KX                      | 1         | 0.54%   |
| Sony VPCM13M1R                      | 1         | 0.54%   |
| Sony VGN-UX1XRN                     | 1         | 0.54%   |
| Sony VGN-S150(UC)                   | 1         | 0.54%   |
| Sony SVP1321V9RB                    | 1         | 0.54%   |
| Sony SVE1713S1RW                    | 1         | 0.54%   |
| Samsung R530/R730/R540              | 1         | 0.54%   |
| Samsung R468/R418                   | 1         | 0.54%   |
| Samsung Q430/Q530                   | 1         | 0.54%   |
| Samsung NC110P/NC108P/NC111P        | 1         | 0.54%   |
| Samsung N150P                       | 1         | 0.54%   |
| Samsung 305E4A/305E5A/305E7A        | 1         | 0.54%   |
| Rembrandt ARB928                    | 1         | 0.54%   |
| Platform ARB938                     | 1         | 0.54%   |
| Panasonic CF-19AHNC8FN              | 1         | 0.54%   |
| Packard Bell EasyNote TE69HW        | 1         | 0.54%   |
| MSI Sword 17 A11UD                  | 1         | 0.54%   |
| MSI GE75 Raider 10SFS               | 1         | 0.54%   |
| MSI GE62 6QC                        | 1         | 0.54%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS  | 1         | 0.54%   |
| Lenovo V580 20147                   | 1         | 0.54%   |
| Lenovo ThinkPad Yoga 260 20FES1K81V | 1         | 0.54%   |
| Lenovo ThinkPad X240 20AMA52RUK     | 1         | 0.54%   |
| Lenovo ThinkPad X240 20AL00DKRT     | 1         | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 29        | 15.68%  |
| Lenovo IdeaPad         | 13        | 7.03%   |
| Acer Aspire            | 13        | 7.03%   |
| Dell Inspiron          | 9         | 4.86%   |
| Dell Latitude          | 8         | 4.32%   |
| HP ProBook             | 6         | 3.24%   |
| HP Laptop              | 4         | 2.16%   |
| ASUS VivoBook          | 4         | 2.16%   |
| Toshiba Satellite      | 3         | 1.62%   |
| IBM ThinkPad           | 3         | 1.62%   |
| F-Plus Mobile FLAPTOP  | 3         | 1.62%   |
| Samsung N145P          | 2         | 1.08%   |
| MSI PS63               | 2         | 1.08%   |
| Lenovo ThinkBook       | 2         | 1.08%   |
| Lenovo G570            | 2         | 1.08%   |
| HUAWEI CREM-WXX9       | 2         | 1.08%   |
| HMT W041-TF-A-45       | 2         | 1.08%   |
| HP Pavilion            | 2         | 1.08%   |
| HP EliteBook           | 2         | 1.08%   |
| Acer Extensa           | 2         | 1.08%   |
| Timi TM1612            | 1         | 0.54%   |
| Timi TM1607            | 1         | 0.54%   |
| Timi Redmi             | 1         | 0.54%   |
| Sony VPCX115KX         | 1         | 0.54%   |
| Sony VPCM13M1R         | 1         | 0.54%   |
| Sony VGN-UX1XRN        | 1         | 0.54%   |
| Sony VGN-S150(UC)      | 1         | 0.54%   |
| Sony SVP1321V9RB       | 1         | 0.54%   |
| Sony SVE1713S1RW       | 1         | 0.54%   |
| Samsung R530           | 1         | 0.54%   |
| Samsung R468           | 1         | 0.54%   |
| Samsung Q430           | 1         | 0.54%   |
| Samsung NC110P         | 1         | 0.54%   |
| Samsung N150P          | 1         | 0.54%   |
| Samsung 305E4A         | 1         | 0.54%   |
| Rembrandt ARB928       | 1         | 0.54%   |
| Platform ARB938        | 1         | 0.54%   |
| Panasonic CF-19AHNC8FN | 1         | 0.54%   |
| Packard Bell EasyNote  | 1         | 0.54%   |
| MSI Sword              | 1         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 21        | 11.35%  |
| 2019 | 21        | 11.35%  |
| 2022 | 18        | 9.73%   |
| 2011 | 15        | 8.11%   |
| 2012 | 14        | 7.57%   |
| 2021 | 12        | 6.49%   |
| 2010 | 11        | 5.95%   |
| 2018 | 10        | 5.41%   |
| 2017 | 9         | 4.86%   |
| 2016 | 8         | 4.32%   |
| 2015 | 8         | 4.32%   |
| 2008 | 7         | 3.78%   |
| 2014 | 6         | 3.24%   |
| 2009 | 6         | 3.24%   |
| 2013 | 4         | 2.16%   |
| 2006 | 4         | 2.16%   |
| 2023 | 3         | 1.62%   |
| 2007 | 3         | 1.62%   |
| 2005 | 2         | 1.08%   |
| 2004 | 2         | 1.08%   |
| 2003 | 1         | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 185       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 184       | 99.46%  |
| Yes  | 1         | 0.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 54        | 28.57%  |
| 4.01-8.0    | 47        | 24.87%  |
| 16.01-24.0  | 45        | 23.81%  |
| 2.01-3.0    | 17        | 8.99%   |
| 32.01-64.0  | 6         | 3.17%   |
| 0.51-1.0    | 6         | 3.17%   |
| 1.01-2.0    | 5         | 2.65%   |
| 24.01-32.0  | 3         | 1.59%   |
| 0.01-0.5    | 3         | 1.59%   |
| 3.01-4.0    | 2         | 1.06%   |
| 64.01-256.0 | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 101       | 52.33%  |
| 0.51-1.0   | 48        | 24.87%  |
| 1.01-2.0   | 21        | 10.88%  |
| 2.01-3.0   | 8         | 4.15%   |
| 0          | 5         | 2.59%   |
| Unknown    | 5         | 2.59%   |
| 4.01-8.0   | 3         | 1.55%   |
| 24.01-32.0 | 1         | 0.52%   |
| 8.01-16.0  | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 135       | 69.59%  |
| 2      | 45        | 23.2%   |
| 0      | 9         | 4.64%   |
| 4      | 3         | 1.55%   |
| 3      | 2         | 1.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 148       | 80%     |
| Yes       | 37        | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 78.92%  |
| No        | 39        | 21.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 97.3%   |
| No        | 5         | 2.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 68.82%  |
| No        | 58        | 31.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 185       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Moscow                   | 71        | 37.17%  |
| St Petersburg            | 25        | 13.09%  |
| Novosibirsk              | 7         | 3.66%   |
| Vladivostok              | 6         | 3.14%   |
| Yekaterinburg            | 5         | 2.62%   |
| Ulyanovsk                | 4         | 2.09%   |
| Ufa                      | 3         | 1.57%   |
| Tyumen                   | 3         | 1.57%   |
| Tolyatti                 | 3         | 1.57%   |
| Saratov                  | 3         | 1.57%   |
| Perm                     | 3         | 1.57%   |
| Krasnoyarsk              | 3         | 1.57%   |
| Chelyabinsk              | 3         | 1.57%   |
| Tsarskoye Selo           | 2         | 1.05%   |
| Surgut                   | 2         | 1.05%   |
| Krasnodar                | 2         | 1.05%   |
| Kirov                    | 2         | 1.05%   |
| Kaliningrad              | 2         | 1.05%   |
| Irkutsk                  | 2         | 1.05%   |
| Chita                    | 2         | 1.05%   |
| Zhukovskiy               | 1         | 0.52%   |
| Yoshkar-Ola              | 1         | 0.52%   |
| Yegorlykskaya            | 1         | 0.52%   |
| Yaroslavl                | 1         | 0.52%   |
| Vorkuta                  | 1         | 0.52%   |
| Vladimir                 | 1         | 0.52%   |
| Vidnoye                  | 1         | 0.52%   |
| Ust'-Luga                | 1         | 0.52%   |
| Tver                     | 1         | 0.52%   |
| Sochi                    | 1         | 0.52%   |
| Smolensk                 | 1         | 0.52%   |
| Sevastopol'              | 1         | 0.52%   |
| Rostov-on-Don            | 1         | 0.52%   |
| Pushkino                 | 1         | 0.52%   |
| Petropavlovsk-Kamchatsky | 1         | 0.52%   |
| Penza                    | 1         | 0.52%   |
| Ozersk                   | 1         | 0.52%   |
| Oryol                    | 1         | 0.52%   |
| Omsk                     | 1         | 0.52%   |
| Obninsk                  | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 48     | 17.57%  |
| Samsung Electronics | 22        | 28     | 9.91%   |
| Seagate             | 21        | 25     | 9.46%   |
| Toshiba             | 17        | 18     | 7.66%   |
| SanDisk             | 12        | 14     | 5.41%   |
| Hitachi             | 11        | 13     | 4.95%   |
| SK hynix            | 9         | 10     | 4.05%   |
| Kingston            | 9         | 11     | 4.05%   |
| Intel               | 9         | 12     | 4.05%   |
| SPCC                | 6         | 7      | 2.7%    |
| Micron Technology   | 5         | 5      | 2.25%   |
| HGST                | 5         | 7      | 2.25%   |
| FORESEE             | 5         | 6      | 2.25%   |
| Transcend           | 4         | 4      | 1.8%    |
| NVMe                | 4         | 4      | 1.8%    |
| A-DATA Technology   | 4         | 4      | 1.8%    |
| SSSTC               | 3         | 4      | 1.35%   |
| Gigabyte Technology | 3         | 6      | 1.35%   |
| Apple               | 3         | 3      | 1.35%   |
| Apacer              | 3         | 3      | 1.35%   |
| UMIS                | 2         | 2      | 0.9%    |
| KIOXIA              | 2         | 2      | 0.9%    |
| JetFlash            | 2         | 2      | 0.9%    |
| Innostor            | 2         | 2      | 0.9%    |
| AMD                 | 2         | 2      | 0.9%    |
| USB                 | 1         | 1      | 0.45%   |
| Union Memory        | 1         | 1      | 0.45%   |
| UFD 2.0             | 1         | 1      | 0.45%   |
| Smartbuy            | 1         | 1      | 0.45%   |
| Silicon Motion      | 1         | 1      | 0.45%   |
| SETHRISE            | 1         | 1      | 0.45%   |
| Phison              | 1         | 1      | 0.45%   |
| Patriot             | 1         | 1      | 0.45%   |
| OCZ                 | 1         | 2      | 0.45%   |
| Netac               | 1         | 1      | 0.45%   |
| Lenovo              | 1         | 1      | 0.45%   |
| KLLISRE             | 1         | 1      | 0.45%   |
| KINGBANK            | 1         | 1      | 0.45%   |
| Hoodisk             | 1         | 1      | 0.45%   |
| Hewlett-Packard     | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 4         | 1.72%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 1.72%   |
| FORESEE XP1000F001T 1TB              | 4         | 1.72%   |
| WDC WDS240G2G0A-00JH30 240GB         | 3         | 1.29%   |
| SPCC Solid State Disk 128GB          | 3         | 1.29%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 1.29%   |
| Kingston SV300S37A120G 120GB         | 3         | 1.29%   |
| HGST HTS721010A9E630 1TB             | 3         | 1.29%   |
| WDC WD5000LPVX-60V0TT0 500GB         | 2         | 0.86%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 0.86%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 0.86%   |
| WDC WD2500BEVT-22A23T0 250GB         | 2         | 0.86%   |
| WDC WD10SPZX-08Z10 1TB               | 2         | 0.86%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.86%   |
| WDC PC SN730 SDBPNTY-512G            | 2         | 0.86%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 0.86%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.86%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.86%   |
| SSSTC CL4-8D512 512GB                | 2         | 0.86%   |
| Seagate ST9500325AS 500GB            | 2         | 0.86%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.86%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.86%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.86%   |
| Samsung MZNTY128HDHP-00000 128GB     | 2         | 0.86%   |
| Micron 1100 SATA 256GB               | 2         | 0.86%   |
| Kingston SA400S37120G 120GB          | 2         | 0.86%   |
| Intel SSDPEKNU512GZ 512GB            | 2         | 0.86%   |
| Innostor SSD 15GB                    | 2         | 0.86%   |
| Hitachi HDS721616PLA380 160GB        | 2         | 0.86%   |
| Gigabyte GP-AG42TB                   | 2         | 0.86%   |
| A-DATA SX6000LNP 512GB               | 2         | 0.86%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 0.43%   |
| WDC WDS240G1G0B-00RC30 240GB         | 1         | 0.43%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.43%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.43%   |
| WDC WD5000LPLX-60ZNTT1 500GB         | 1         | 0.43%   |
| WDC WD5000LPLX-00ZNTT0 500GB         | 1         | 0.43%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.43%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 25     | 26.19%  |
| Seagate             | 21        | 25     | 25%     |
| Toshiba             | 14        | 15     | 16.67%  |
| Hitachi             | 11        | 13     | 13.1%   |
| HGST                | 5         | 7      | 5.95%   |
| NVMe                | 3         | 3      | 3.57%   |
| Samsung Electronics | 2         | 2      | 2.38%   |
| JetFlash            | 2         | 2      | 2.38%   |
| USB                 | 1         | 1      | 1.19%   |
| UFD 2.0             | 1         | 1      | 1.19%   |
| Fujitsu             | 1         | 1      | 1.19%   |
| Apple               | 1         | 1      | 1.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 18     | 17.28%  |
| SanDisk             | 12        | 14     | 14.81%  |
| Kingston            | 7         | 9      | 8.64%   |
| WDC                 | 6         | 7      | 7.41%   |
| SPCC                | 6         | 7      | 7.41%   |
| Intel               | 5         | 7      | 6.17%   |
| Transcend           | 3         | 3      | 3.7%    |
| Micron Technology   | 3         | 3      | 3.7%    |
| Apacer              | 3         | 3      | 3.7%    |
| SK hynix            | 2         | 2      | 2.47%   |
| Innostor            | 2         | 2      | 2.47%   |
| Apple               | 2         | 2      | 2.47%   |
| A-DATA Technology   | 2         | 2      | 2.47%   |
| Union Memory        | 1         | 1      | 1.23%   |
| Smartbuy            | 1         | 1      | 1.23%   |
| SETHRISE            | 1         | 1      | 1.23%   |
| Patriot             | 1         | 1      | 1.23%   |
| OCZ                 | 1         | 2      | 1.23%   |
| NVMe                | 1         | 1      | 1.23%   |
| Netac               | 1         | 1      | 1.23%   |
| KLLISRE             | 1         | 1      | 1.23%   |
| Hewlett-Packard     | 1         | 1      | 1.23%   |
| Goldenfir           | 1         | 1      | 1.23%   |
| Gigabyte Technology | 1         | 3      | 1.23%   |
| FORESEE             | 1         | 2      | 1.23%   |
| ASUSTek Computer    | 1         | 2      | 1.23%   |
| AMD                 | 1         | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 75        | 96     | 36.59%  |
| SSD  | 73        | 98     | 35.61%  |
| NVMe | 57        | 68     | 27.8%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 132       | 194    | 69.84%  |
| NVMe | 57        | 68     | 30.16%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 108       | 151    | 73.97%  |
| 0.51-1.0        | 34        | 39     | 23.29%  |
| 1.01-2.0        | 3         | 3      | 2.05%   |
| More than 100.0 | 1         | 1      | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 52        | 25.87%  |
| 1-20       | 49        | 24.38%  |
| 251-500    | 44        | 21.89%  |
| 501-1000   | 19        | 9.45%   |
| 21-50      | 15        | 7.46%   |
| 51-100     | 15        | 7.46%   |
| 1001-2000  | 5         | 2.49%   |
| Unknown    | 2         | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 150       | 78.53%  |
| 21-50    | 17        | 8.9%    |
| 101-250  | 12        | 6.28%   |
| 51-100   | 7         | 3.66%   |
| 251-500  | 2         | 1.05%   |
| Unknown  | 2         | 1.05%   |
| 501-1000 | 1         | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 5.41%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 5.41%   |
| Micron Technology 1100 SATA 256GB   | 2         | 2      | 5.41%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1      | 2.7%    |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 2.7%    |
| WDC WD3200BPVT-80ZEST0 320GB        | 1         | 2      | 2.7%    |
| WDC WD2000JB-00GVC0 200GB           | 1         | 1      | 2.7%    |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 2.7%    |
| Toshiba MK7575GSX 752GB             | 1         | 1      | 2.7%    |
| Toshiba MK2546GSX 250GB             | 1         | 1      | 2.7%    |
| Toshiba MK1646GSX 160GB             | 1         | 1      | 2.7%    |
| Seagate ST9500325AS 500GB           | 1         | 1      | 2.7%    |
| Seagate ST9320325AS 320GB           | 1         | 1      | 2.7%    |
| Seagate ST9250320AS 250GB           | 1         | 1      | 2.7%    |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 2.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 2.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 2.7%    |
| Samsung Electronics HM080HI 80GB    | 1         | 1      | 2.7%    |
| Kingston SV300S37A120G 120GB        | 1         | 1      | 2.7%    |
| Intel SSDSC2KW120H6 120GB           | 1         | 1      | 2.7%    |
| Intel SSDSC2CW060A3 64GB            | 1         | 1      | 2.7%    |
| Intel SSDSC2BW480H6 480GB           | 1         | 1      | 2.7%    |
| Intel SSDSC2BB480G7 480GB           | 1         | 1      | 2.7%    |
| Hitachi HTS725025A9A364 250GB       | 1         | 1      | 2.7%    |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1      | 2.7%    |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 2.7%    |
| Hitachi HTS547550A9E384 500GB       | 1         | 1      | 2.7%    |
| Hitachi HTS541616J9SA00 160GB       | 1         | 1      | 2.7%    |
| Hitachi HTS541612J9SA00 120GB       | 1         | 1      | 2.7%    |
| Hitachi HTC426060G9AT00 64GB        | 1         | 1      | 2.7%    |
| Hitachi DK23AA-12 12GB              | 1         | 1      | 2.7%    |
| HGST HTS541075A7E630 752GB          | 1         | 2      | 2.7%    |
| HGST HTE725032A7E630 320GB          | 1         | 1      | 2.7%    |
| Apple SSD SD0128F 121GB             | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 21.62%  |
| Hitachi             | 8         | 8      | 21.62%  |
| Toshiba             | 6         | 6      | 16.22%  |
| WDC                 | 4         | 5      | 10.81%  |
| Intel               | 4         | 4      | 10.81%  |
| Micron Technology   | 2         | 2      | 5.41%   |
| HGST                | 2         | 3      | 5.41%   |
| Samsung Electronics | 1         | 1      | 2.7%    |
| Kingston            | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 28.57%  |
| Hitachi             | 8         | 8      | 28.57%  |
| Toshiba             | 6         | 6      | 21.43%  |
| WDC                 | 3         | 4      | 10.71%  |
| HGST                | 2         | 3      | 7.14%   |
| Samsung Electronics | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 30     | 75.68%  |
| SSD  | 9         | 9      | 24.32%  |

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
| Works    | 150       | 212    | 76.14%  |
| Malfunc  | 37        | 39     | 18.78%  |
| Detected | 8         | 9      | 4.06%   |
| Failed   | 2         | 2      | 1.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 125       | 58.69%  |
| AMD                                     | 25        | 11.74%  |
| SanDisk                                 | 12        | 5.63%   |
| SK hynix                                | 8         | 3.76%   |
| Samsung Electronics                     | 8         | 3.76%   |
| Shenzhen Longsys Electronics            | 4         | 1.88%   |
| Phison Electronics                      | 4         | 1.88%   |
| Solid State Storage Technology          | 3         | 1.41%   |
| Silicon Motion                          | 3         | 1.41%   |
| KIOXIA                                  | 3         | 1.41%   |
| Toshiba                                 | 2         | 0.94%   |
| Realtek Semiconductor                   | 2         | 0.94%   |
| Nvidia                                  | 2         | 0.94%   |
| Micron Technology                       | 2         | 0.94%   |
| Kingston Technology Company             | 2         | 0.94%   |
| Union Memory (Shenzhen)                 | 1         | 0.47%   |
| Transcend                               | 1         | 0.47%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.47%   |
| Shenzhen Unionmemory Information System | 1         | 0.47%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.47%   |
| Marvell Technology Group                | 1         | 0.47%   |
| Lenovo                                  | 1         | 0.47%   |
| JMicron Technology                      | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 9.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 6.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 4.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 3.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 3.6%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 7         | 3.15%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 7         | 3.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 2.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 2.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 2.25%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 1.8%    |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                                | 4         | 1.8%    |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 4         | 1.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.8%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 1.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.8%    |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 4         | 1.8%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3         | 1.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.35%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 1.35%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.35%   |
| Solid State Storage CL4-8D512 NVMe SSD M.2 (DRAM-less)                           | 2         | 0.9%    |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.9%    |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                | 2         | 0.9%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 2         | 0.9%    |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 0.9%    |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.9%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 0.9%    |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 0.9%    |
| Intel SSD 670p Series [Keystone Harbor]                                          | 2         | 0.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.9%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 0.9%    |
| Intel 82801CAM IDE U100 Controller                                               | 2         | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 130       | 59.91%  |
| NVMe | 58        | 26.73%  |
| IDE  | 21        | 9.68%   |
| RAID | 8         | 3.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 139       | 74.73%  |
| AMD    | 46        | 24.73%  |
| 11th   | 1         | 0.54%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Core i3-6006U CPU @ 2.00GHz                            | 6         | 3.16%   |
| Intel CPU Version                                            | 4         | 2.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz                            | 4         | 2.11%   |
| Intel Core i7-8665U CPU @ 1.90GHz                            | 3         | 1.58%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                            | 3         | 1.58%   |
| Intel C1                                                     | 3         | 1.58%   |
| AMD Ryzen 7 5825U with Radeon Graphics                       | 3         | 1.58%   |
| AMD Ryzen 7 5800H with Radeon Graphics                       | 3         | 1.58%   |
| Intel Pentium M processor 1.60GHz                            | 2         | 1.05%   |
| Intel Pentium M processor                                    | 2         | 1.05%   |
| Intel Pentium CPU N4200 @ 1.10GHz                            | 2         | 1.05%   |
| Intel Genuine CPU                                            | 2         | 1.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz                            | 2         | 1.05%   |
| Intel Core i7-6600U CPU @ 2.60GHz                            | 2         | 1.05%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz                           | 2         | 1.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz                            | 2         | 1.05%   |
| Intel Core i5-2520M CPU @ 2.50GHz                            | 2         | 1.05%   |
| Intel Core i5-2430M CPU @ 2.40GHz                            | 2         | 1.05%   |
| Intel Core i5-10210U CPU @ 1.60GHz                           | 2         | 1.05%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                         | 2         | 1.05%   |
| Intel Core 2 Duo                                             | 2         | 1.05%   |
| Intel Celeron CPU N3350 @ 1.10GHz                            | 2         | 1.05%   |
| Intel Celeron CPU N3060 @ 1.60GHz                            | 2         | 1.05%   |
| Intel Atom CPU N570 @ 1.66GHz                                | 2         | 1.05%   |
| Intel 686-class                                              | 2         | 1.05%   |
| AMD Ryzen 7 7735H with Radeon Graphics                       | 2         | 1.05%   |
| AMD Ryzen 7 6800H with Radeon Graphics                       | 2         | 1.05%   |
| AMD Ryzen 7 5800U with Radeon Graphics                       | 2         | 1.05%   |
| AMD Ryzen 7 4700U with Radeon Graphics                       | 2         | 1.05%   |
| AMD Ryzen 3 4300U with Radeon Graphics                       | 2         | 1.05%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx                | 2         | 1.05%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx                | 2         | 1.05%   |
| Intel Xeon W-10885M CPU @ 2.40GHz                            | 1         | 0.53%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz                         | 1         | 0.53%   |
| Intel Pentium Silver N6000 @ 1.10GHz                         | 1         | 0.53%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                     | 1         | 0.53%   |
| Intel Pentium M processor 1.86GHz ("GenuineIntel" 686-class) | 1         | 0.53%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz                  | 1         | 0.53%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz                  | 1         | 0.53%   |
| Intel Pentium CPU N3700 @ 1.60GHz                            | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 17.65%  |
| Intel Core i7           | 23        | 12.3%   |
| Intel Core i3           | 16        | 8.56%   |
| AMD Ryzen 7             | 16        | 8.56%   |
| Other                   | 14        | 7.49%   |
| Intel Celeron           | 9         | 4.81%   |
| Intel Atom              | 8         | 4.28%   |
| AMD Ryzen 3             | 8         | 4.28%   |
| Intel Core 2 Duo        | 7         | 3.74%   |
| AMD Ryzen 5             | 6         | 3.21%   |
| Intel Pentium M         | 5         | 2.67%   |
| Intel Pentium           | 5         | 2.67%   |
| Intel Genuine           | 5         | 2.67%   |
| AMD A6                  | 4         | 2.14%   |
| AMD Ryzen 7 PRO         | 3         | 1.6%    |
| AMD E                   | 3         | 1.6%    |
| Intel Xeon              | 2         | 1.07%   |
| Intel Pentium Silver    | 2         | 1.07%   |
| Intel Pentium Dual-Core | 2         | 1.07%   |
| Intel Core m3           | 2         | 1.07%   |
| Intel 686-class         | 2         | 1.07%   |
| Intel Core Solo         | 1         | 0.53%   |
| Intel Core m5           | 1         | 0.53%   |
| Intel Core M            | 1         | 0.53%   |
| Intel Core i9           | 1         | 0.53%   |
| Intel Celeron M         | 1         | 0.53%   |
| Intel Celeron Dual-Core | 1         | 0.53%   |
| AMD Ryzen 9             | 1         | 0.53%   |
| AMD E2                  | 1         | 0.53%   |
| AMD E1                  | 1         | 0.53%   |
| AMD C-60                | 1         | 0.53%   |
| AMD A8                  | 1         | 0.53%   |
| AMD A10                 | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 78        | 41.27%  |
| 4       | 47        | 24.87%  |
| Unknown | 18        | 9.52%   |
| 16      | 16        | 8.47%   |
| 1       | 14        | 7.41%   |
| 8       | 9         | 4.76%   |
| 12      | 4         | 2.12%   |
| 6       | 3         | 1.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 179       | 94.21%  |
| Unknown | 11        | 5.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 90        | 47.62%  |
| 1       | 71        | 37.57%  |
| Unknown | 28        | 14.81%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 13.98%  |
| Skylake       | 14        | 7.53%   |
| SandyBridge   | 12        | 6.45%   |
| Zen 3         | 11        | 5.91%   |
| Penryn        | 11        | 5.91%   |
| P6            | 11        | 5.91%   |
| Bonnell       | 10        | 5.38%   |
| Unknown       | 10        | 5.38%   |
| Zen 2         | 8         | 4.3%    |
| IvyBridge     | 8         | 4.3%    |
| Westmere      | 7         | 3.76%   |
| Silvermont    | 7         | 3.76%   |
| Haswell       | 7         | 3.76%   |
| Zen+          | 5         | 2.69%   |
| TigerLake     | 5         | 2.69%   |
| Core          | 5         | 2.69%   |
| Broadwell     | 5         | 2.69%   |
| Goldmont      | 4         | 2.15%   |
| Zen           | 3         | 1.61%   |
| Excavator     | 3         | 1.61%   |
| CometLake     | 3         | 1.61%   |
| Bobcat        | 3         | 1.61%   |
| Puma          | 2         | 1.08%   |
| Piledriver    | 1         | 0.54%   |
| K8 Hammer     | 1         | 0.54%   |
| K10 Llano     | 1         | 0.54%   |
| Jaguar        | 1         | 0.54%   |
| IceLake       | 1         | 0.54%   |
| Goldmont plus | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 124       | 56.62%  |
| AMD    | 61        | 27.85%  |
| Nvidia | 33        | 15.07%  |
| ATI    | 1         | 0.46%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 4.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 3.52%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 8         | 3.52%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 3.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.08%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 7         | 3.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 3.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.2%    |
| AMD Rembrandt [Radeon 680M]                                                              | 5         | 2.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.2%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.76%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.32%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 1.32%   |
| Intel HD Graphics 630                                                                    | 3         | 1.32%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.32%   |
| Intel HD Graphics 520                                                                    | 3         | 1.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.32%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.32%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.32%   |
| AMD Barcelo                                                                              | 3         | 1.32%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.88%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.88%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.88%   |
| Intel HD Graphics 620                                                                    | 2         | 0.88%   |
| Intel HD Graphics 515                                                                    | 2         | 0.88%   |
| Intel HD Graphics 500                                                                    | 2         | 0.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.88%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.88%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 2         | 0.88%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.88%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                                    | 2         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 74        | 39.78%  |
| 1 x AMD        | 51        | 27.42%  |
| Intel + Nvidia | 25        | 13.44%  |
| 2 x Intel      | 20        | 10.75%  |
| 1 x Nvidia     | 6         | 3.23%   |
| Intel + AMD    | 5         | 2.69%   |
| 2 x AMD        | 3         | 1.61%   |
| AMD + Nvidia   | 2         | 1.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 167       | 88.36%  |
| Unknown     | 12        | 6.35%   |
| Proprietary | 10        | 5.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 146       | 76.44%  |
| 0.01-0.5   | 29        | 15.18%  |
| 0.51-1.0   | 7         | 3.66%   |
| 1.01-2.0   | 6         | 3.14%   |
| 3.01-4.0   | 2         | 1.05%   |
| 2.01-3.0   | 1         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 32        | 24.62%  |
| BOE                     | 20        | 15.38%  |
| Chimei Innolux          | 18        | 13.85%  |
| LG Display              | 17        | 13.08%  |
| Samsung Electronics     | 11        | 8.46%   |
| InfoVision              | 4         | 3.08%   |
| LG Philips              | 3         | 2.31%   |
| Chi Mei Optoelectronics | 3         | 2.31%   |
| Acer                    | 3         | 2.31%   |
| ViewSonic               | 2         | 1.54%   |
| PANDA                   | 2         | 1.54%   |
| Lenovo                  | 2         | 1.54%   |
| HKC                     | 2         | 1.54%   |
| HannStar                | 2         | 1.54%   |
| Apple                   | 2         | 1.54%   |
| Toshiba                 | 1         | 0.77%   |
| Panasonic               | 1         | 0.77%   |
| NEC Computers           | 1         | 0.77%   |
| Goldstar                | 1         | 0.77%   |
| CSO                     | 1         | 0.77%   |
| CPT                     | 1         | 0.77%   |
| Ancor Communications    | 1         | 0.77%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3245 1280x800 330x210mm 15.4-inch     | 2         | 1.53%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 2         | 1.53%   |
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                    | 2         | 1.53%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 2         | 1.53%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch         | 2         | 1.53%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 2         | 1.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO1457 1366x768 310x170mm 13.9-inch | 2         | 1.53%   |
| BOE LCD Monitor BOE0AC1 2560x1600 340x210mm 15.7-inch                    | 2         | 1.53%   |
| BOE HF BOE0691 1920x1080 280x160mm 12.7-inch                             | 2         | 1.53%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 2         | 1.53%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 2         | 1.53%   |
| Acer K272HUL ACR0524 2560x1440 600x340mm 27.2-inch                       | 2         | 1.53%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch            | 1         | 0.76%   |
| ViewSonic LCD Monitor VSC6F2E 1920x1080 480x270mm 21.7-inch              | 1         | 0.76%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                          | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC5643 1280x800 300x190mm 14.0-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch    | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch   | 1         | 0.76%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 0.76%   |
| PANDA LCD Monitor NCP002B 1920x1080 310x170mm 13.9-inch                  | 1         | 0.76%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch              | 1         | 0.76%   |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch            | 1         | 0.76%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 0.76%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch              | 1         | 0.76%   |
| LG Philips LCD Monitor LPL0301 1280x800 330x210mm 15.4-inch              | 1         | 0.76%   |
| LG Display LCD Monitor LGD06FF 1920x1080 340x190mm 15.3-inch             | 1         | 0.76%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch             | 1         | 0.76%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch             | 1         | 0.76%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 0.76%   |
| LG Display LCD Monitor LGD05EE 2560x1440 310x170mm 13.9-inch             | 1         | 0.76%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch             | 1         | 0.76%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 1         | 0.76%   |
| LG Display LCD Monitor LGD046B 1366x768 340x190mm 15.3-inch              | 1         | 0.76%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch              | 1         | 0.76%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 0.76%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch              | 1         | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 57        | 43.85%  |
| 1366x768 (WXGA)   | 33        | 25.38%  |
| 1280x800 (WXGA)   | 7         | 5.38%   |
| 2560x1440 (QHD)   | 5         | 3.85%   |
| 1600x900 (HD+)    | 5         | 3.85%   |
| 1024x600          | 5         | 3.85%   |
| 3840x2160 (4K)    | 3         | 2.31%   |
| 1440x900 (WXGA+)  | 3         | 2.31%   |
| 2560x1600         | 2         | 1.54%   |
| 1280x1024 (SXGA)  | 2         | 1.54%   |
| 3200x1800 (QHD+)  | 1         | 0.77%   |
| 2560x1080         | 1         | 0.77%   |
| 2520x1680         | 1         | 0.77%   |
| 2240x1400         | 1         | 0.77%   |
| 2160x1440         | 1         | 0.77%   |
| 2160x1350         | 1         | 0.77%   |
| 1920x540          | 1         | 0.77%   |
| 1920x1200 (WUXGA) | 1         | 0.77%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 54        | 41.54%  |
| 13     | 35        | 26.92%  |
| 17     | 10        | 7.69%   |
| 10     | 6         | 4.62%   |
| 14     | 5         | 3.85%   |
| 12     | 5         | 3.85%   |
| 11     | 5         | 3.85%   |
| 27     | 2         | 1.54%   |
| 21     | 2         | 1.54%   |
| 54     | 1         | 0.77%   |
| 34     | 1         | 0.77%   |
| 31     | 1         | 0.77%   |
| 23     | 1         | 0.77%   |
| 19     | 1         | 0.77%   |
| 16     | 1         | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 83        | 63.85%  |
| 201-300     | 29        | 22.31%  |
| 351-400     | 10        | 7.69%   |
| 501-600     | 3         | 2.31%   |
| 401-500     | 2         | 1.54%   |
| 701-800     | 1         | 0.77%   |
| 601-700     | 1         | 0.77%   |
| 1001-1500   | 1         | 0.77%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 100       | 80.65%  |
| 16/10 | 18        | 14.52%  |
| 3/2   | 3         | 2.42%   |
| 5/4   | 2         | 1.61%   |
| 21/9  | 1         | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 44        | 33.85%  |
| 81-90          | 33        | 25.38%  |
| 101-110        | 9         | 6.92%   |
| 71-80          | 7         | 5.38%   |
| 121-130        | 7         | 5.38%   |
| 41-50          | 6         | 4.62%   |
| 51-60          | 5         | 3.85%   |
| 61-70          | 4         | 3.08%   |
| 201-250        | 3         | 2.31%   |
| 131-140        | 3         | 2.31%   |
| 351-500        | 2         | 1.54%   |
| 301-350        | 2         | 1.54%   |
| 111-120        | 2         | 1.54%   |
| More than 1000 | 1         | 0.77%   |
| 151-200        | 1         | 0.77%   |
| 141-150        | 1         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 57        | 43.85%  |
| 101-120       | 37        | 28.46%  |
| 161-240       | 17        | 13.08%  |
| 51-100        | 16        | 12.31%  |
| More than 240 | 3         | 2.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 145       | 74.74%  |
| 0     | 38        | 19.59%  |
| 2     | 11        | 5.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 101       | 31.66%  |
| Realtek Semiconductor             | 90        | 28.21%  |
| Qualcomm Atheros                  | 53        | 16.61%  |
| Broadcom                          | 19        | 5.96%   |
| Marvell Technology Group          | 11        | 3.45%   |
| TP-Link                           | 8         | 2.51%   |
| Ralink Technology                 | 4         | 1.25%   |
| MediaTek                          | 4         | 1.25%   |
| Xiaomi                            | 3         | 0.94%   |
| Samsung Electronics               | 3         | 0.94%   |
| Ralink                            | 2         | 0.63%   |
| JMicron Technology                | 2         | 0.63%   |
| Huawei Technologies               | 2         | 0.63%   |
| Fibocom                           | 2         | 0.63%   |
| Ericsson Business Mobile Networks | 2         | 0.63%   |
| Arduino SA                        | 2         | 0.63%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.31%   |
| Shenzhen Goodix Technology        | 1         | 0.31%   |
| Realtek                           | 1         | 0.31%   |
| Nvidia                            | 1         | 0.31%   |
| Mercucys                          | 1         | 0.31%   |
| Dell                              | 1         | 0.31%   |
| D-Link                            | 1         | 0.31%   |
| BUFFALO                           | 1         | 0.31%   |
| Attansic                          | 1         | 0.31%   |
| Atheros                           | 1         | 0.31%   |
| 3Com                              | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 59        | 15.65%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 4.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 12        | 3.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 2.65%   |
| Intel Wireless 7265                                                     | 9         | 2.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 1.86%   |
| Intel Wireless 8265 / 8275                                              | 7         | 1.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 1.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.86%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 6         | 1.59%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 1.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 5         | 1.33%   |
| Intel Wireless 8260                                                     | 5         | 1.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.06%   |
| Intel Wireless 3165                                                     | 4         | 1.06%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.06%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 0.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.8%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.8%    |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 3         | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.8%    |
| Intel WiFi Link 5100                                                    | 3         | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 0.8%    |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 3         | 0.8%    |
| Intel Ethernet Connection I219-LM                                       | 3         | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.8%    |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                | 3         | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.53%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 96        | 47.06%  |
| Qualcomm Atheros      | 45        | 22.06%  |
| Realtek Semiconductor | 30        | 14.71%  |
| Broadcom              | 12        | 5.88%   |
| TP-Link               | 8         | 3.92%   |
| Ralink Technology     | 4         | 1.96%   |
| MediaTek              | 3         | 1.47%   |
| Ralink                | 2         | 0.98%   |
| Mercucys              | 1         | 0.49%   |
| D-Link                | 1         | 0.49%   |
| BUFFALO               | 1         | 0.49%   |
| Atheros               | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 8.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 4.78%   |
| Intel Wireless 7265                                                     | 9         | 4.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 3.35%   |
| Intel Wireless 8265 / 8275                                              | 7         | 3.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 3.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 3.35%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 2.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.39%   |
| Intel Wireless 8260                                                     | 5         | 2.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.91%   |
| Intel Wireless 3165                                                     | 4         | 1.91%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.91%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 1.44%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.44%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 3         | 1.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.44%   |
| Intel WiFi Link 5100                                                    | 3         | 1.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 1.44%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 3         | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.96%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.96%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.96%   |
| Intel Wireless 7260                                                     | 2         | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.96%   |
| TP-Link Wireless USB Adapter                                            | 1         | 0.48%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.48%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]     | 1         | 0.48%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.48%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 73        | 47.71%  |
| Intel                            | 29        | 18.95%  |
| Qualcomm Atheros                 | 17        | 11.11%  |
| Marvell Technology Group         | 11        | 7.19%   |
| Broadcom                         | 9         | 5.88%   |
| Xiaomi                           | 3         | 1.96%   |
| Samsung Electronics              | 3         | 1.96%   |
| JMicron Technology               | 2         | 1.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.65%   |
| Realtek                          | 1         | 0.65%   |
| Nvidia                           | 1         | 0.65%   |
| MediaTek                         | 1         | 0.65%   |
| Attansic                         | 1         | 0.65%   |
| 3Com                             | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 38.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 7.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 5.23%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 3.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 3.27%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.96%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 3         | 1.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.31%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.31%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1.31%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.31%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.31%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.31%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.31%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.31%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.65%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.65%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.65%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.65%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.65%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.65%   |
| MediaTek USB Ethernet-RNDIS                                       | 1         | 0.65%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.65%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.65%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.65%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.65%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.65%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.65%   |
| Intel PRO/100 VM Network Connection                               | 1         | 0.65%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 180       | 52.79%  |
| Ethernet | 146       | 42.82%  |
| Unknown  | 8         | 2.35%   |
| Modem    | 7         | 2.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 118       | 55.66%  |
| Ethernet | 92        | 43.4%   |
| Unknown  | 2         | 0.94%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 137       | 74.05%  |
| 1     | 45        | 24.32%  |
| 3     | 2         | 1.08%   |
| 0     | 1         | 0.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 183       | 97.86%  |
| Yes  | 4         | 2.14%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 50%     |
| Qualcomm Atheros Communications | 14        | 10.77%  |
| Realtek Semiconductor           | 10        | 7.69%   |
| IMC Networks                    | 7         | 5.38%   |
| Broadcom                        | 6         | 4.62%   |
| Foxconn / Hon Hai               | 4         | 3.08%   |
| ASUSTek Computer                | 4         | 3.08%   |
| Apple                           | 4         | 3.08%   |
| Skylight Digital                | 3         | 2.31%   |
| Lite-On Technology              | 3         | 2.31%   |
| Alps Electric                   | 3         | 2.31%   |
| Hewlett-Packard                 | 2         | 1.54%   |
| TP-Link                         | 1         | 0.77%   |
| Taiyo Yuden                     | 1         | 0.77%   |
| Ralink                          | 1         | 0.77%   |
| Opticis                         | 1         | 0.77%   |
| Dell                            | 1         | 0.77%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 24        | 18.46%  |
| Intel AX201 Bluetooth                                       | 11        | 8.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                            | 7         | 5.38%   |
| Intel AX200 Bluetooth                                       | 6         | 4.62%   |
| Realtek Bluetooth Adapter                                   | 5         | 3.85%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 4         | 3.08%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 4         | 3.08%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 3         | 2.31%   |
| Intel AX210 Bluetooth                                       | 3         | 2.31%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.54%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 2         | 1.54%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.54%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.54%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.54%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 2         | 1.54%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 1.54%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.54%   |
| ASUS BT-270 Bluetooth Adapter                               | 2         | 1.54%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 1.54%   |
| Apple Bluetooth Host Controller                             | 2         | 1.54%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 1         | 0.77%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                     | 1         | 0.77%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.77%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.77%   |
| Qualcomm Atheros QCA9565 Bluetooth 4.0 + HS Adapter         | 1         | 0.77%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.77%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.77%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.77%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.77%   |
| Opticis Realtek Bluetooth Adapter                           | 1         | 0.77%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.77%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 0.77%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.77%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 0.77%   |
| IMC Networks Bluetooth module                               | 1         | 0.77%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.77%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 0.77%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 135       | 67.16%  |
| AMD                              | 50        | 24.88%  |
| Nvidia                           | 8         | 3.98%   |
| Lenovo                           | 3         | 1.49%   |
| Texas Instruments                | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] | 1         | 0.5%    |
| Generalplus Technology           | 1         | 0.5%    |
| ESS Technology                   | 1         | 0.5%    |
| Creative Technology              | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 33        | 12.84%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 21        | 8.17%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 7.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 4.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 4.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 3.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 3.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 3.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 3.11%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.72%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 2.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.95%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.95%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 5         | 1.95%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.56%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.56%   |
| Lenovo Realtek USB Audio                                                                          | 3         | 1.17%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.17%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.17%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 1.17%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.17%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.17%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.17%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.78%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.78%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.78%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.78%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.39%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 53        | 27.18%  |
| SK hynix            | 34        | 17.44%  |
| Unknown             | 26        | 13.33%  |
| Micron Technology   | 21        | 10.77%  |
| Kingston            | 19        | 9.74%   |
| Unknown             | 13        | 6.67%   |
| Elpida              | 5         | 2.56%   |
| Ramaxel Technology  | 3         | 1.54%   |
| Crucial             | 3         | 1.54%   |
| A-DATA Technology   | 3         | 1.54%   |
| 48spaces            | 3         | 1.54%   |
| Transcend           | 2         | 1.03%   |
| Corsair             | 2         | 1.03%   |
| Unknown (ABCD)      | 1         | 0.51%   |
| Unknown (0x0809)    | 1         | 0.51%   |
| Silicon Power       | 1         | 0.51%   |
| Rayson              | 1         | 0.51%   |
| PUSKILL             | 1         | 0.51%   |
| GeIL                | 1         | 0.51%   |
| Apacer              | 1         | 0.51%   |
| AMD                 | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 13        | 6.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 5         | 2.4%    |
| Unknown RAM Module 512MB SODIMM DDR                                       | 3         | 1.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 3         | 1.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 3         | 1.44%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 3         | 1.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 3         | 1.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                     | 3         | 1.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                     | 3         | 1.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 3         | 1.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s                | 3         | 1.44%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 800MT/s | 3         | 1.44%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 2         | 0.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 0.96%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                         | 2         | 0.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 0.96%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 0.96%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 2         | 0.96%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 2         | 0.96%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 2         | 0.96%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.96%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.96%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                      | 2         | 0.96%   |
| Kingston RAM 9905700-011.A00G 8192MB SODIMM DDR4 2400MT/s                 | 2         | 0.96%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 0.48%   |
| Unknown RAM Module 512MB SODIMM DRAM                                      | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                               | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                                 | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                               | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR3                                        | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                                     | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                       | 1         | 0.48%   |
| Unknown RAM Module 256MB SODIMM DRAM                                      | 1         | 0.48%   |
| Unknown RAM Module 256MB SODIMM DDR 100MT/s                               | 1         | 0.48%   |
| Unknown RAM Module 2560MB SODIMM DDR                                      | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 71        | 41.76%  |
| DDR3    | 49        | 28.82%  |
| DDR2    | 16        | 9.41%   |
| LPDDR3  | 7         | 4.12%   |
| DDR     | 6         | 3.53%   |
| SDRAM   | 5         | 2.94%   |
| LPDDR5  | 4         | 2.35%   |
| Unknown | 4         | 2.35%   |
| DRAM    | 3         | 1.76%   |
| LPDDR4  | 2         | 1.18%   |
| DDR5    | 2         | 1.18%   |
| RAM     | 1         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 152       | 89.94%  |
| Row Of Chips | 12        | 7.1%    |
| DIMM         | 3         | 1.78%   |
| Chip         | 1         | 0.59%   |
| Unknown      | 1         | 0.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 67        | 35.26%  |
| 4096  | 50        | 26.32%  |
| 2048  | 38        | 20%     |
| 16384 | 14        | 7.37%   |
| 1024  | 11        | 5.79%   |
| 512   | 4         | 2.11%   |
| 32768 | 2         | 1.05%   |
| 256   | 2         | 1.05%   |
| 2560  | 1         | 0.53%   |
| 128   | 1         | 0.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 31        | 17.32%  |
| 1600    | 28        | 15.64%  |
| 2667    | 26        | 14.53%  |
| 2400    | 15        | 8.38%   |
| 1333    | 13        | 7.26%   |
| Unknown | 12        | 6.7%    |
| 800     | 9         | 5.03%   |
| 667     | 9         | 5.03%   |
| 1867    | 7         | 3.91%   |
| 2133    | 6         | 3.35%   |
| 6400    | 4         | 2.23%   |
| 1067    | 4         | 2.23%   |
| 1334    | 3         | 1.68%   |
| 4800    | 2         | 1.12%   |
| 2048    | 2         | 1.12%   |
| 266     | 2         | 1.12%   |
| 4267    | 1         | 0.56%   |
| 2933    | 1         | 0.56%   |
| 1639    | 1         | 0.56%   |
| 975     | 1         | 0.56%   |
| 400     | 1         | 0.56%   |
| 100     | 1         | 0.56%   |

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
| Chicony Electronics                    | 33        | 22.92%  |
| IMC Networks                           | 20        | 13.89%  |
| Microdia                               | 14        | 9.72%   |
| Realtek Semiconductor                  | 13        | 9.03%   |
| Bison Electronics                      | 10        | 6.94%   |
| Suyin                                  | 5         | 3.47%   |
| Sunplus Innovation Technology          | 5         | 3.47%   |
| Quanta                                 | 5         | 3.47%   |
| Syntek                                 | 4         | 2.78%   |
| Silicon Motion                         | 4         | 2.78%   |
| Lite-On Technology                     | 4         | 2.78%   |
| ALi                                    | 4         | 2.78%   |
| Luxvisions Innotech Limited            | 3         | 2.08%   |
| Jiangxi Shinetech Optical              | 3         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.08%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 1.39%   |
| Lenovo                                 | 2         | 1.39%   |
| DigiTech                               | 2         | 1.39%   |
| Z-Star Microelectronics                | 1         | 0.69%   |
| Y Media                                | 1         | 0.69%   |
| Supreme Electronics                    | 1         | 0.69%   |
| Ricoh                                  | 1         | 0.69%   |
| Intel                                  | 1         | 0.69%   |
| Genesys Logic                          | 1         | 0.69%   |
| Denron                                 | 1         | 0.69%   |
| Apple                                  | 1         | 0.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 12        | 8.22%   |
| Microdia Integrated_Webcam_HD                 | 7         | 4.79%   |
| IMC Networks Integrated Camera                | 6         | 4.11%   |
| Silicon Motion WebCam SCX Series              | 4         | 2.74%   |
| IMC Networks EasyCamera                       | 4         | 2.74%   |
| Realtek USB 2.0 PC Camera                     | 3         | 2.05%   |
| Realtek Acer 640 x 480 laptop camera          | 3         | 2.05%   |
| Quanta VGA WebCam                             | 3         | 2.05%   |
| Microdia USB Camera                           | 3         | 2.05%   |
| Bison Lenovo EasyCamera                       | 3         | 2.05%   |
| ALi Gateway Webcam                            | 3         | 2.05%   |
| Syntek EasyCamera                             | 2         | 1.37%   |
| Sunplus Hy HD Camera                          | 2         | 1.37%   |
| Realtek Integrated Webcam                     | 2         | 1.37%   |
| Microdia Integrated Webcam                    | 2         | 1.37%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.37%   |
| Lite-On Integrated Camera                     | 2         | 1.37%   |
| Lite-On HP HD Camera                          | 2         | 1.37%   |
| Jiangxi Shinetech Optical HD Camera           | 2         | 1.37%   |
| IMC Networks UVC VGA Webcam                   | 2         | 1.37%   |
| IMC Networks Realtek DMFT RGB                 | 2         | 1.37%   |
| DigiTech WebCam SCB-0350M                     | 2         | 1.37%   |
| Chicony XiaoMi USB 2.0 Webcam                 | 2         | 1.37%   |
| Chicony Lenovo EasyCamera                     | 2         | 1.37%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 2         | 1.37%   |
| Bison SunplusIT Integrated Camera             | 2         | 1.37%   |
| Bison Lenovo Integrated Webcam                | 2         | 1.37%   |
| Bison Integrated Camera                       | 2         | 1.37%   |
| Z-Star Webcam                                 | 1         | 0.68%   |
| Y Media USB Camera                            | 1         | 0.68%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.68%   |
| Syntek Integrated Camera                      | 1         | 0.68%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 0.68%   |
| Suyin HP Webcam                               | 1         | 0.68%   |
| Suyin HD WebCam                               | 1         | 0.68%   |
| Suyin HD Video WebCam                         | 1         | 0.68%   |
| Suyin Acer Crystal Eye webcam                 | 1         | 0.68%   |
| Supreme Integrated Camera                     | 1         | 0.68%   |
| Sunplus Laptop_Integrated_Webcam_HD           | 1         | 0.68%   |
| Sunplus Integrated_Webcam_HD                  | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 12        | 29.27%  |
| Validity Sensors           | 10        | 24.39%  |
| STMicroelectronics         | 4         | 9.76%   |
| FocalTech Systems          | 4         | 9.76%   |
| AuthenTec                  | 4         | 9.76%   |
| Upek                       | 3         | 7.32%   |
| Shenzhen Goodix Technology | 3         | 7.32%   |
| Broadcom                   | 1         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 7         | 17.07%  |
| STMicroelectronics Fingerprint Reader                                        | 4         | 9.76%   |
| FocalTech Systems Fingerprint Reader                                         | 4         | 9.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 7.32%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 7.32%   |
| Shenzhen Goodix  Fingerprint Device                                          | 3         | 7.32%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 4.88%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 4.88%   |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 2         | 4.88%   |
| AuthenTec AES1600                                                            | 2         | 4.88%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 2.44%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 2.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 2.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 2.44%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 2.44%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 1         | 2.44%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.44%   |
| AuthenTec AES2810                                                            | 1         | 2.44%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 2.44%   |

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
| 1     | 76        | 38.19%  |
| 2     | 47        | 23.62%  |
| 0     | 27        | 13.57%  |
| 3     | 24        | 12.06%  |
| 4     | 18        | 9.05%   |
| 5     | 3         | 1.51%   |
| 9     | 1         | 0.5%    |
| 8     | 1         | 0.5%    |
| 7     | 1         | 0.5%    |
| 6     | 1         | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 94        | 30.42%  |
| Net/wireless             | 49        | 15.86%  |
| Bluetooth                | 41        | 13.27%  |
| Card reader              | 37        | 11.97%  |
| Fingerprint reader       | 34        | 11%     |
| Firewire controller      | 14        | 4.53%   |
| Graphics card            | 11        | 3.56%   |
| Sound                    | 10        | 3.24%   |
| Network                  | 7         | 2.27%   |
| Storage                  | 5         | 1.62%   |
| Modem                    | 4         | 1.29%   |
| Storage/ata              | 3         | 0.97%   |

