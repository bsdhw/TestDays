OpenBSD - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for OpenBSD.

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

Total: 313

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop X545... | [bf5cea4ab5](https://bsd-hardware.info/?probe=bf5cea4ab5) | Jul 30, 2022 |
| Lenovo        | ThinkPad X200 7458NP9       | [4192abf903](https://bsd-hardware.info/?probe=4192abf903) | Jul 20, 2022 |
| ASUSTek       | X751LB                      | [5c2ef28301](https://bsd-hardware.info/?probe=5c2ef28301) | Jul 12, 2022 |
| Acer          | Nitro AN515-55              | [f98a69101e](https://bsd-hardware.info/?probe=f98a69101e) | Jul 08, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | [c1bf998d6a](https://bsd-hardware.info/?probe=c1bf998d6a) | Jul 07, 2022 |
| Dell          | Inspiron 5515               | [dca437b993](https://bsd-hardware.info/?probe=dca437b993) | Jul 01, 2022 |
| ASUSTek       | K53TA                       | [6ce39c5e61](https://bsd-hardware.info/?probe=6ce39c5e61) | Jun 27, 2022 |
| HP            | EliteBook 8440p             | [25d5a77b59](https://bsd-hardware.info/?probe=25d5a77b59) | Jun 17, 2022 |
| Lenovo        | ThinkPad L530 24812TG       | [5b66684c4a](https://bsd-hardware.info/?probe=5b66684c4a) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [73ab89b8f0](https://bsd-hardware.info/?probe=73ab89b8f0) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [637f87f44e](https://bsd-hardware.info/?probe=637f87f44e) | Jun 05, 2022 |
| Apple         | MacBookPro5,3               | [3b03bdf595](https://bsd-hardware.info/?probe=3b03bdf595) | May 29, 2022 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [0419c52079](https://bsd-hardware.info/?probe=0419c52079) | May 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| TUXEDO        | Aura 15 Gen1                | [49d1cd3009](https://bsd-hardware.info/?probe=49d1cd3009) | May 10, 2022 |
| Fujitsu       | LIFEBOOK E752               | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| ASUSTek       | 1000HE                      | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| Matsushita... | CF-48V4KNDQM                | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| Lenovo        | ThinkPad X220 429043U       | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Panasonic     | CF-53AAGHYDM                | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Panasonic     | CF-52PFPBSFQ                | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| MSI           | Modern 14 B11MOL            | [9a61443be9](https://bsd-hardware.info/?probe=9a61443be9) | Apr 25, 2022 |
| DEXP          | NAVIS P100                  | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [b4a6761ab3](https://bsd-hardware.info/?probe=b4a6761ab3) | Apr 21, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [f7aa3576ae](https://bsd-hardware.info/?probe=f7aa3576ae) | Apr 13, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [0e836941e0](https://bsd-hardware.info/?probe=0e836941e0) | Apr 11, 2022 |
| Apple         | MacBook5,1                  | [41d62dde7d](https://bsd-hardware.info/?probe=41d62dde7d) | Apr 10, 2022 |
| Apple         | MacBook5,1                  | [c5f7b5499a](https://bsd-hardware.info/?probe=c5f7b5499a) | Apr 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | [1d1db3eab4](https://bsd-hardware.info/?probe=1d1db3eab4) | Apr 03, 2022 |
| IBM           | 2658MNG                     | [e3a5a587fa](https://bsd-hardware.info/?probe=e3a5a587fa) | Mar 28, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [086a58a68f](https://bsd-hardware.info/?probe=086a58a68f) | Mar 24, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [ed0add65a3](https://bsd-hardware.info/?probe=ed0add65a3) | Mar 14, 2022 |
| HP            | EliteBook 2530p             | [e5c8017afb](https://bsd-hardware.info/?probe=e5c8017afb) | Mar 12, 2022 |
| Lenovo        | Yoga 330-11IGM 81A6         | [621ae0501b](https://bsd-hardware.info/?probe=621ae0501b) | Mar 10, 2022 |
| Lenovo        | Flex 2-15 20405             | [3b77055bd4](https://bsd-hardware.info/?probe=3b77055bd4) | Mar 07, 2022 |
| Dell          | Vostro 3550                 | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| Dell          | Vostro 3550                 | [11bed21472](https://bsd-hardware.info/?probe=11bed21472) | Feb 21, 2022 |
| Acer          | Aspire A114-33              | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |
| Acer          | Aspire A514-52              | [60f9683fb1](https://bsd-hardware.info/?probe=60f9683fb1) | Feb 21, 2022 |
| Lenovo        | ThinkPad X250 20CLS59400    | [92333ad60b](https://bsd-hardware.info/?probe=92333ad60b) | Feb 17, 2022 |
| Lenovo        | Flex 2-15 20405             | [1e8904f4fc](https://bsd-hardware.info/?probe=1e8904f4fc) | Feb 15, 2022 |
| HP            | EliteBook 2530p             | [dd52bb1163](https://bsd-hardware.info/?probe=dd52bb1163) | Feb 15, 2022 |
| Lenovo        | Flex 2-15 20405             | [b77b926f9b](https://bsd-hardware.info/?probe=b77b926f9b) | Feb 13, 2022 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | [ae597455a4](https://bsd-hardware.info/?probe=ae597455a4) | Feb 13, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [c024d383e7](https://bsd-hardware.info/?probe=c024d383e7) | Feb 13, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [f107f7c1b1](https://bsd-hardware.info/?probe=f107f7c1b1) | Feb 06, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [f8476c0ea7](https://bsd-hardware.info/?probe=f8476c0ea7) | Feb 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [2d65265b52](https://bsd-hardware.info/?probe=2d65265b52) | Jan 29, 2022 |
| Apple         | MacBookPro9,2               | [208819a667](https://bsd-hardware.info/?probe=208819a667) | Jan 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c36023a724](https://bsd-hardware.info/?probe=c36023a724) | Jan 17, 2022 |
| HP            | EliteBook 2530p             | [42eb986a58](https://bsd-hardware.info/?probe=42eb986a58) | Jan 11, 2022 |
| Lenovo        | V130-15IGM 81HL             | [e0e7b21668](https://bsd-hardware.info/?probe=e0e7b21668) | Jan 09, 2022 |
| Framework     | Laptop                      | [324f0fdebc](https://bsd-hardware.info/?probe=324f0fdebc) | Jan 05, 2022 |
| Framework     | Laptop                      | [ba81f48282](https://bsd-hardware.info/?probe=ba81f48282) | Jan 05, 2022 |
| Dell          | Latitude 3400               | [41bf32aff1](https://bsd-hardware.info/?probe=41bf32aff1) | Jan 02, 2022 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [0925acabe4](https://bsd-hardware.info/?probe=0925acabe4) | Dec 31, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4bb84a33fa](https://bsd-hardware.info/?probe=4bb84a33fa) | Dec 26, 2021 |
| Casper        | EXCALIBUR G900              | [539cf08655](https://bsd-hardware.info/?probe=539cf08655) | Dec 24, 2021 |
| Samsung       | 530XBB                      | [fe0adb59d8](https://bsd-hardware.info/?probe=fe0adb59d8) | Dec 20, 2021 |
| Samsung       | R720                        | [620195d4aa](https://bsd-hardware.info/?probe=620195d4aa) | Dec 20, 2021 |
| HP            | Compaq 15                   | [1e8b1ce39b](https://bsd-hardware.info/?probe=1e8b1ce39b) | Dec 20, 2021 |
| Intel         | SharkBay Platform           | [383d1e31c9](https://bsd-hardware.info/?probe=383d1e31c9) | Dec 14, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | [0215354bfc](https://bsd-hardware.info/?probe=0215354bfc) | Dec 13, 2021 |
| Lenovo        | ThinkPad T420s 41742BU      | [a86326d049](https://bsd-hardware.info/?probe=a86326d049) | Dec 11, 2021 |
| Dell          | G15 5510                    | [2da7a07664](https://bsd-hardware.info/?probe=2da7a07664) | Dec 07, 2021 |
| Lenovo        | ThinkPad X61 7675H7U        | [545cbe065d](https://bsd-hardware.info/?probe=545cbe065d) | Dec 06, 2021 |
| Dell          | G15 5510                    | [8846b3fd69](https://bsd-hardware.info/?probe=8846b3fd69) | Nov 27, 2021 |
| Dell          | Vostro 3500                 | [923a99fade](https://bsd-hardware.info/?probe=923a99fade) | Nov 27, 2021 |
| Lenovo        | ThinkPad X220 429043U       | [339779baad](https://bsd-hardware.info/?probe=339779baad) | Nov 26, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [8b178d13c7](https://bsd-hardware.info/?probe=8b178d13c7) | Nov 22, 2021 |
| Alienware     | m15                         | [20afd3904b](https://bsd-hardware.info/?probe=20afd3904b) | Nov 21, 2021 |
| Dell          | Vostro 3500                 | [63443924f3](https://bsd-hardware.info/?probe=63443924f3) | Nov 19, 2021 |
| Acer          | AO722                       | [98b88ae138](https://bsd-hardware.info/?probe=98b88ae138) | Nov 15, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | [0391bf9ea4](https://bsd-hardware.info/?probe=0391bf9ea4) | Nov 14, 2021 |
| Dell          | Vostro 3500                 | [34d905d6f3](https://bsd-hardware.info/?probe=34d905d6f3) | Nov 11, 2021 |
| Google        | Grunt                       | [aa07a1dd40](https://bsd-hardware.info/?probe=aa07a1dd40) | Nov 05, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [cdccf02902](https://bsd-hardware.info/?probe=cdccf02902) | Nov 04, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [2471e3f337](https://bsd-hardware.info/?probe=2471e3f337) | Nov 04, 2021 |
| Google        | Grunt                       | [c87e033731](https://bsd-hardware.info/?probe=c87e033731) | Nov 01, 2021 |
| Panasonic     | CF-53AAGHYDM                | [721ef0235c](https://bsd-hardware.info/?probe=721ef0235c) | Oct 30, 2021 |
| Matsushita... | CF-48V4KNDQM                | [9e254ab443](https://bsd-hardware.info/?probe=9e254ab443) | Oct 23, 2021 |
| ASUSTek       | 1000HE                      | [1d5e3e5bc3](https://bsd-hardware.info/?probe=1d5e3e5bc3) | Oct 22, 2021 |
| Google        | Grunt                       | [259f96d9c8](https://bsd-hardware.info/?probe=259f96d9c8) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | [3337c00433](https://bsd-hardware.info/?probe=3337c00433) | Oct 22, 2021 |
| Matsushita... | CF-51RCVDNLM                | [b20953f2f4](https://bsd-hardware.info/?probe=b20953f2f4) | Oct 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | [bbdfde368b](https://bsd-hardware.info/?probe=bbdfde368b) | Oct 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [b4ba704356](https://bsd-hardware.info/?probe=b4ba704356) | Oct 17, 2021 |
| Google        | Grunt                       | [e6d4421a4d](https://bsd-hardware.info/?probe=e6d4421a4d) | Oct 16, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | [1a5bae2227](https://bsd-hardware.info/?probe=1a5bae2227) | Oct 15, 2021 |
| Google        | Grunt                       | [ee9b2d7ad3](https://bsd-hardware.info/?probe=ee9b2d7ad3) | Oct 15, 2021 |
| Dell          | Inspiron 5570               | [9eab523504](https://bsd-hardware.info/?probe=9eab523504) | Oct 14, 2021 |
| Google        | Grunt                       | [e76c73d9a3](https://bsd-hardware.info/?probe=e76c73d9a3) | Oct 11, 2021 |
| ASUSTek       | X555LB                      | [e3443d9f27](https://bsd-hardware.info/?probe=e3443d9f27) | Oct 02, 2021 |
| IBM           | ThinkPad H 1846AQG          | [5e5c7247ca](https://bsd-hardware.info/?probe=5e5c7247ca) | Oct 01, 2021 |
| ASUSTek       | UX305FA                     | [decf219ff2](https://bsd-hardware.info/?probe=decf219ff2) | Sep 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [d9762d6c2d](https://bsd-hardware.info/?probe=d9762d6c2d) | Sep 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0d00ce5de9](https://bsd-hardware.info/?probe=0d00ce5de9) | Sep 22, 2021 |
| Dell          | XPS 13 7390 2-in-1          | [577e0ed7fe](https://bsd-hardware.info/?probe=577e0ed7fe) | Sep 13, 2021 |
| HP            | 250 G5 Notebook PC          | [6e50039406](https://bsd-hardware.info/?probe=6e50039406) | Sep 09, 2021 |
| Apple         | MacBookPro6,2               | [4632683b4b](https://bsd-hardware.info/?probe=4632683b4b) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [4cc349d29a](https://bsd-hardware.info/?probe=4cc349d29a) | Sep 08, 2021 |
| Lenovo        | ThinkPad X250 20CM0046US    | [1ed50b75f1](https://bsd-hardware.info/?probe=1ed50b75f1) | Sep 08, 2021 |
| Sony          | VGN-P698E                   | [c8274e858d](https://bsd-hardware.info/?probe=c8274e858d) | Aug 30, 2021 |
| Lenovo        | FLEX 3-1120 80LX            | [2f1a1a42b8](https://bsd-hardware.info/?probe=2f1a1a42b8) | Aug 29, 2021 |
| Lenovo        | ThinkPad P73 20QRS00200     | [dfc86a0368](https://bsd-hardware.info/?probe=dfc86a0368) | Aug 29, 2021 |
| Acer          | Aspire ES1-132              | [43c82b1b16](https://bsd-hardware.info/?probe=43c82b1b16) | Aug 22, 2021 |
| IBM           | ThinkPad T42 2374K46        | [d93b6d68fa](https://bsd-hardware.info/?probe=d93b6d68fa) | Aug 18, 2021 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | [f7725f06df](https://bsd-hardware.info/?probe=f7725f06df) | Aug 18, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | [6f7976c329](https://bsd-hardware.info/?probe=6f7976c329) | Aug 16, 2021 |
| Standard      | TF                          | [c7995f2022](https://bsd-hardware.info/?probe=c7995f2022) | Aug 12, 2021 |
| HP            | Notebook                    | [a3c3297cd2](https://bsd-hardware.info/?probe=a3c3297cd2) | Aug 08, 2021 |
| HP            | Notebook                    | [0c316107a4](https://bsd-hardware.info/?probe=0c316107a4) | Aug 08, 2021 |
| Lenovo        | ThinkPad T430 2349U2B       | [90d85e011f](https://bsd-hardware.info/?probe=90d85e011f) | Jul 31, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | [5404f763dd](https://bsd-hardware.info/?probe=5404f763dd) | Jul 26, 2021 |
| Lenovo        | ThinkPad T400 2767WSB       | [36ce1d1e00](https://bsd-hardware.info/?probe=36ce1d1e00) | Jul 24, 2021 |
| MSI           | MS-1613                     | [795e61c1a3](https://bsd-hardware.info/?probe=795e61c1a3) | Jul 21, 2021 |
| Lenovo        | ThinkPad X270 20HNA006ID    | [6fc7c972a5](https://bsd-hardware.info/?probe=6fc7c972a5) | Jul 19, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | [5b43300a93](https://bsd-hardware.info/?probe=5b43300a93) | Jul 13, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [740c5182d3](https://bsd-hardware.info/?probe=740c5182d3) | Jul 11, 2021 |
| Lenovo        | ThinkPad X230 232578G       | [a8c497b58b](https://bsd-hardware.info/?probe=a8c497b58b) | Jul 09, 2021 |
| HP            | Pavilion dm1                | [a863347147](https://bsd-hardware.info/?probe=a863347147) | Jul 03, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | [72e208aa92](https://bsd-hardware.info/?probe=72e208aa92) | Jul 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [443817737d](https://bsd-hardware.info/?probe=443817737d) | Jun 24, 2021 |
| Unknown       | Unknown                     | [f37bf77853](https://bsd-hardware.info/?probe=f37bf77853) | Jun 20, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | [b60f4a19ee](https://bsd-hardware.info/?probe=b60f4a19ee) | Jun 06, 2021 |
| Lenovo        | ThinkPad T430 23511A6       | [89fb2aa493](https://bsd-hardware.info/?probe=89fb2aa493) | Jun 05, 2021 |
| Lenovo        | ThinkPad T400 6475K43       | [1b3e80e2e9](https://bsd-hardware.info/?probe=1b3e80e2e9) | Jun 03, 2021 |
| Lenovo        | IdeaPad S210 Touch 20257    | [392df069bd](https://bsd-hardware.info/?probe=392df069bd) | Jun 02, 2021 |
| Apple         | PowerBook5,2                | [8cc0aab53c](https://bsd-hardware.info/?probe=8cc0aab53c) | May 31, 2021 |
| HP            | 530 Notebook PC(KP477AA#... | [9c7b85c190](https://bsd-hardware.info/?probe=9c7b85c190) | May 30, 2021 |
| Unknown       | Unknown                     | [b296fb35e2](https://bsd-hardware.info/?probe=b296fb35e2) | May 19, 2021 |
| Unknown       | Unknown                     | [750e01de05](https://bsd-hardware.info/?probe=750e01de05) | May 19, 2021 |
| Panasonic     | CF-53AAGHYDM                | [ef5e9ec095](https://bsd-hardware.info/?probe=ef5e9ec095) | May 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | [65f5931910](https://bsd-hardware.info/?probe=65f5931910) | May 18, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | [1e9f399d73](https://bsd-hardware.info/?probe=1e9f399d73) | May 17, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | [109f3afa21](https://bsd-hardware.info/?probe=109f3afa21) | May 17, 2021 |
| ASUSTek       | 1000HE                      | [f92f43bc54](https://bsd-hardware.info/?probe=f92f43bc54) | May 17, 2021 |
| Matsushita... | CF-51RCVDNLM                | [33bc82e701](https://bsd-hardware.info/?probe=33bc82e701) | May 17, 2021 |
| Matsushita... | CF-48V4KNDQM                | [bf76401b74](https://bsd-hardware.info/?probe=bf76401b74) | May 17, 2021 |
| ASUSTek       | UX430UNR                    | [bfe7ec0975](https://bsd-hardware.info/?probe=bfe7ec0975) | May 03, 2021 |
| Acer          | AO531h                      | [614326a3d3](https://bsd-hardware.info/?probe=614326a3d3) | May 03, 2021 |
| Acer          | AO531h                      | [9de7465352](https://bsd-hardware.info/?probe=9de7465352) | May 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [6e8891f184](https://bsd-hardware.info/?probe=6e8891f184) | Apr 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [7ec73fe36d](https://bsd-hardware.info/?probe=7ec73fe36d) | Apr 23, 2021 |
| Lenovo        | ThinkPad X201 Tablet 298... | [4faceaf6e5](https://bsd-hardware.info/?probe=4faceaf6e5) | Apr 17, 2021 |
| ASUSTek       | UX430UNR                    | [f31eda4c16](https://bsd-hardware.info/?probe=f31eda4c16) | Apr 16, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [403a237513](https://bsd-hardware.info/?probe=403a237513) | Apr 14, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | [dcf202ea95](https://bsd-hardware.info/?probe=dcf202ea95) | Apr 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | [ee371f3e8f](https://bsd-hardware.info/?probe=ee371f3e8f) | Apr 08, 2021 |
| Lenovo        | ThinkPad Edge 05796AU       | [4a094815c0](https://bsd-hardware.info/?probe=4a094815c0) | Mar 24, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | [8d81204137](https://bsd-hardware.info/?probe=8d81204137) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291EM4       | [9d393db103](https://bsd-hardware.info/?probe=9d393db103) | Mar 20, 2021 |
| Dell          | Latitude E7270              | [5ba79f9aa5](https://bsd-hardware.info/?probe=5ba79f9aa5) | Mar 19, 2021 |
| Dell          | Inspiron 15-3567            | [b35adf782c](https://bsd-hardware.info/?probe=b35adf782c) | Mar 17, 2021 |
| Lenovo        | ThinkPad X280 20KESA000B    | [e2b586d597](https://bsd-hardware.info/?probe=e2b586d597) | Mar 17, 2021 |
| ASUSTek       | X510UA                      | [440f1ef3ec](https://bsd-hardware.info/?probe=440f1ef3ec) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [52584aaa97](https://bsd-hardware.info/?probe=52584aaa97) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [fb136a79e7](https://bsd-hardware.info/?probe=fb136a79e7) | Mar 13, 2021 |
| Panasonic     | CF-30KTP48NL                | [119b4875e9](https://bsd-hardware.info/?probe=119b4875e9) | Mar 12, 2021 |
| HP            | ProBook 450 G2              | [9f4a3cd83d](https://bsd-hardware.info/?probe=9f4a3cd83d) | Mar 08, 2021 |
| Lenovo        | ThinkPad T400 6475P1G       | [6a0907b5e8](https://bsd-hardware.info/?probe=6a0907b5e8) | Mar 06, 2021 |
| ASUSTek       | X510UA                      | [f22eeba366](https://bsd-hardware.info/?probe=f22eeba366) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7d1ff5416d](https://bsd-hardware.info/?probe=7d1ff5416d) | Mar 01, 2021 |
| Acer          | Spin SP111-32N              | [9f44af71aa](https://bsd-hardware.info/?probe=9f44af71aa) | Feb 28, 2021 |
| Dell          | Inspiron 1000               | [70604dcbfa](https://bsd-hardware.info/?probe=70604dcbfa) | Feb 28, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [fb890afc86](https://bsd-hardware.info/?probe=fb890afc86) | Feb 28, 2021 |
| Apple         | MacBook5,1                  | [41ea02c8bc](https://bsd-hardware.info/?probe=41ea02c8bc) | Feb 21, 2021 |
| Acer          | AOA150                      | [91e5ec60b9](https://bsd-hardware.info/?probe=91e5ec60b9) | Feb 21, 2021 |
| IBM           | ThinkPad T42 2374K46        | [311f93ab37](https://bsd-hardware.info/?probe=311f93ab37) | Feb 20, 2021 |
| ASUSTek       | X102BA                      | [529baeb345](https://bsd-hardware.info/?probe=529baeb345) | Feb 20, 2021 |
| ASUSTek       | X102BA                      | [65f1904b56](https://bsd-hardware.info/?probe=65f1904b56) | Feb 20, 2021 |
| Dell          | XPS 13 9360                 | [c2dded2160](https://bsd-hardware.info/?probe=c2dded2160) | Feb 19, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [4f646f53e9](https://bsd-hardware.info/?probe=4f646f53e9) | Feb 14, 2021 |
| Dell          | Inspiron 1000               | [104175ae13](https://bsd-hardware.info/?probe=104175ae13) | Feb 13, 2021 |
| Sony          | VPCX115KX                   | [fef3d94e6c](https://bsd-hardware.info/?probe=fef3d94e6c) | Feb 12, 2021 |
| Acer          | Extensa 5635Z               | [3b4a7e7fc2](https://bsd-hardware.info/?probe=3b4a7e7fc2) | Feb 10, 2021 |
| Sony          | VPCF12C5E                   | [df8c1de8a5](https://bsd-hardware.info/?probe=df8c1de8a5) | Feb 07, 2021 |
| IBM           | ThinkPad T42 2373K9G        | [a12c3a0b21](https://bsd-hardware.info/?probe=a12c3a0b21) | Feb 01, 2021 |
| Lenovo        | ThinkPad T61 7661AU5        | [23e498234e](https://bsd-hardware.info/?probe=23e498234e) | Jan 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5f469ceeb9](https://bsd-hardware.info/?probe=5f469ceeb9) | Jan 20, 2021 |
| Dell          | XPS 15 7590                 | [6cd195aa69](https://bsd-hardware.info/?probe=6cd195aa69) | Jan 05, 2021 |
| Dell          | XPS 15 7590                 | [50ca36db01](https://bsd-hardware.info/?probe=50ca36db01) | Jan 05, 2021 |
| ASUSTek       | X101CH                      | [112792b300](https://bsd-hardware.info/?probe=112792b300) | Jan 02, 2021 |
| ASUSTek       | X101CH                      | [8b571cc947](https://bsd-hardware.info/?probe=8b571cc947) | Jan 02, 2021 |
| ASUSTek       | X102BA                      | [893b9111c6](https://bsd-hardware.info/?probe=893b9111c6) | Dec 27, 2020 |
| HP            | 240 G1                      | [3ee90471d0](https://bsd-hardware.info/?probe=3ee90471d0) | Dec 26, 2020 |
| Apple         | PowerBook5,8                | [96f550a537](https://bsd-hardware.info/?probe=96f550a537) | Dec 24, 2020 |
| Lenovo        | ThinkPad T400 6475K43       | [30500a25d3](https://bsd-hardware.info/?probe=30500a25d3) | Dec 18, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [d019e14245](https://bsd-hardware.info/?probe=d019e14245) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7e80ced15e](https://bsd-hardware.info/?probe=7e80ced15e) | Dec 16, 2020 |
| Unknown       | Spring Peak                 | [b61f5c268a](https://bsd-hardware.info/?probe=b61f5c268a) | Dec 15, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3a78e7dc1a](https://bsd-hardware.info/?probe=3a78e7dc1a) | Dec 11, 2020 |
| Dell          | Latitude 3300               | [108a030875](https://bsd-hardware.info/?probe=108a030875) | Dec 07, 2020 |
| Fujitsu       | LIFEBOOK P1610              | [e8ee627d6e](https://bsd-hardware.info/?probe=e8ee627d6e) | Dec 07, 2020 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [2544123f79](https://bsd-hardware.info/?probe=2544123f79) | Dec 06, 2020 |
| Lenovo        | ThinkPad T410 2537NB5       | [d6a3aa6f8d](https://bsd-hardware.info/?probe=d6a3aa6f8d) | Dec 06, 2020 |
| Lenovo        | ThinkPad X201 3680FAG       | [1ba69078df](https://bsd-hardware.info/?probe=1ba69078df) | Dec 06, 2020 |
| Lenovo        | ThinkPad W520 42763JU       | [5c50582307](https://bsd-hardware.info/?probe=5c50582307) | Nov 30, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | [467a6fc001](https://bsd-hardware.info/?probe=467a6fc001) | Nov 26, 2020 |
| Lenovo        | Unknown                     | [1cf65625a7](https://bsd-hardware.info/?probe=1cf65625a7) | Nov 24, 2020 |
| HP            | Setzer                      | [da7914cdd5](https://bsd-hardware.info/?probe=da7914cdd5) | Nov 22, 2020 |
| Lenovo        | ThinkPad T450 20BVA020AU    | [5d8bce59e8](https://bsd-hardware.info/?probe=5d8bce59e8) | Nov 16, 2020 |
| Lenovo        | ThinkPad T60 87445BU        | [bfd9130d4b](https://bsd-hardware.info/?probe=bfd9130d4b) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | [6a0f910601](https://bsd-hardware.info/?probe=6a0f910601) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | [6dca4cdd18](https://bsd-hardware.info/?probe=6dca4cdd18) | Nov 10, 2020 |
| Lenovo        | ThinkPad T450s 20BWS2XS0... | [0b04a395a7](https://bsd-hardware.info/?probe=0b04a395a7) | Nov 10, 2020 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [1b7b105e5c](https://bsd-hardware.info/?probe=1b7b105e5c) | Nov 08, 2020 |
| IBM           | ThinkPad T42 2373K9G        | [e041100bb6](https://bsd-hardware.info/?probe=e041100bb6) | Nov 08, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | [bdc2de68ce](https://bsd-hardware.info/?probe=bdc2de68ce) | Nov 05, 2020 |
| Lenovo        | Yoga 720-13IKB 81C3         | [8cfb32120b](https://bsd-hardware.info/?probe=8cfb32120b) | Nov 05, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [ebd246c141](https://bsd-hardware.info/?probe=ebd246c141) | Nov 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f2e085e11a](https://bsd-hardware.info/?probe=f2e085e11a) | Nov 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [9b6b24708e](https://bsd-hardware.info/?probe=9b6b24708e) | Nov 03, 2020 |
| Dell          | Precision M4800             | [ca6d4c4bb7](https://bsd-hardware.info/?probe=ca6d4c4bb7) | Nov 03, 2020 |
| Dell          | Precision M4800             | [c6a7b68c75](https://bsd-hardware.info/?probe=c6a7b68c75) | Nov 03, 2020 |
| Lenovo        | ThinkPad T500 2087A16       | [334eacfe16](https://bsd-hardware.info/?probe=334eacfe16) | Nov 03, 2020 |
| Lenovo        | ThinkPad W530 2436CTO       | [ded161fe2e](https://bsd-hardware.info/?probe=ded161fe2e) | Oct 31, 2020 |
| Lenovo        | ThinkPad W530 2436CTO       | [e108d4a375](https://bsd-hardware.info/?probe=e108d4a375) | Oct 31, 2020 |
| ASUSTek       | X102BA                      | [9156250b96](https://bsd-hardware.info/?probe=9156250b96) | Oct 31, 2020 |
| Acer          | Extensa 2540                | [26670a4ae9](https://bsd-hardware.info/?probe=26670a4ae9) | Oct 30, 2020 |
| Lenovo        | ThinkPad T450 20BV0005US    | [603e66300a](https://bsd-hardware.info/?probe=603e66300a) | Oct 27, 2020 |
| Lenovo        | ThinkPad T500 2087A16       | [cf8228f878](https://bsd-hardware.info/?probe=cf8228f878) | Oct 25, 2020 |
| Lenovo        | Unknown                     | [7bab490506](https://bsd-hardware.info/?probe=7bab490506) | Oct 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [03602ed2c0](https://bsd-hardware.info/?probe=03602ed2c0) | Oct 23, 2020 |
| Lenovo        | Unknown                     | [c659708e94](https://bsd-hardware.info/?probe=c659708e94) | Oct 23, 2020 |
| IBM           | ThinkPad X41 2525F8G        | [c58f946d2a](https://bsd-hardware.info/?probe=c58f946d2a) | Oct 22, 2020 |
| Dell          | Precision 3510              | [85a55ab7c3](https://bsd-hardware.info/?probe=85a55ab7c3) | Oct 22, 2020 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [f4aa59ba56](https://bsd-hardware.info/?probe=f4aa59ba56) | Oct 22, 2020 |
| Lenovo        | ThinkPad X230 2325AJ9       | [176044b6b8](https://bsd-hardware.info/?probe=176044b6b8) | Oct 21, 2020 |
| Lenovo        | ThinkPad S5-S540 20B3001... | [7e6cb69989](https://bsd-hardware.info/?probe=7e6cb69989) | Oct 21, 2020 |
| Dell          | Latitude C400               | [1dcc5e7972](https://bsd-hardware.info/?probe=1dcc5e7972) | Oct 21, 2020 |
| Dell          | Latitude C400               | [8330d23bd7](https://bsd-hardware.info/?probe=8330d23bd7) | Oct 21, 2020 |
| Lenovo        | ThinkPad X60s 17033JM       | [67e701adb7](https://bsd-hardware.info/?probe=67e701adb7) | Oct 21, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [1b1327ac93](https://bsd-hardware.info/?probe=1b1327ac93) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325R74       | [82398321f6](https://bsd-hardware.info/?probe=82398321f6) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325R74       | [1cc3cc20e8](https://bsd-hardware.info/?probe=1cc3cc20e8) | Oct 21, 2020 |
| Lenovo        | ThinkPad T430 2347GZU       | [f287de215c](https://bsd-hardware.info/?probe=f287de215c) | Oct 20, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [b2e65dd4c5](https://bsd-hardware.info/?probe=b2e65dd4c5) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | [e6b45d36e5](https://bsd-hardware.info/?probe=e6b45d36e5) | Oct 20, 2020 |
| Apple         | MacBookAir7,2               | [901c82d31e](https://bsd-hardware.info/?probe=901c82d31e) | Oct 20, 2020 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [2808d1dd6a](https://bsd-hardware.info/?probe=2808d1dd6a) | Oct 20, 2020 |
| Lenovo        | ThinkPad T410 2537N24       | [f846609c80](https://bsd-hardware.info/?probe=f846609c80) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AL00DKRT    | [623801416c](https://bsd-hardware.info/?probe=623801416c) | Oct 20, 2020 |
| Panasonic     | CF-52PFPBSFQ                | [feb1da0406](https://bsd-hardware.info/?probe=feb1da0406) | Oct 20, 2020 |
| Matsushita... | CF-51RCVDNLM                | [efece2abf7](https://bsd-hardware.info/?probe=efece2abf7) | Oct 20, 2020 |
| ASUSTek       | K53SV                       | [e776458c9e](https://bsd-hardware.info/?probe=e776458c9e) | Oct 19, 2020 |
| Lenovo        | ThinkPad T560 20FJS0CE00    | [be16cb1839](https://bsd-hardware.info/?probe=be16cb1839) | Oct 19, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | [fdc7310ca7](https://bsd-hardware.info/?probe=fdc7310ca7) | Oct 19, 2020 |
| ASUSTek       | 1000HE                      | [621df26e0c](https://bsd-hardware.info/?probe=621df26e0c) | Oct 19, 2020 |
| Acer          | Aspire 5251                 | [da9ebcf25e](https://bsd-hardware.info/?probe=da9ebcf25e) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [857f9809b7](https://bsd-hardware.info/?probe=857f9809b7) | Oct 19, 2020 |
| Lenovo        | ThinkPad X270 20HNA004CD    | [79160b17c4](https://bsd-hardware.info/?probe=79160b17c4) | Oct 19, 2020 |
| ASUSTek       | X102BA                      | [47e04c9378](https://bsd-hardware.info/?probe=47e04c9378) | Oct 19, 2020 |
| Lenovo        | G50-80 80E5                 | [e06605a92b](https://bsd-hardware.info/?probe=e06605a92b) | Oct 19, 2020 |
| Panasonic     | CF-C1BT02EGE                | [8a80fb614e](https://bsd-hardware.info/?probe=8a80fb614e) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [bee732e516](https://bsd-hardware.info/?probe=bee732e516) | Oct 19, 2020 |
| Apple         | PowerBook6,7                | [7ac5f5530a](https://bsd-hardware.info/?probe=7ac5f5530a) | Oct 19, 2020 |
| Alienware     | m15                         | [8f8cf7d956](https://bsd-hardware.info/?probe=8f8cf7d956) | Oct 19, 2020 |
| Lenovo        | ThinkPad T480 20L6S4GR02    | [6c2d8a57ea](https://bsd-hardware.info/?probe=6c2d8a57ea) | Oct 19, 2020 |
| Unknown       | Unknown                     | [fd77b4658f](https://bsd-hardware.info/?probe=fd77b4658f) | Oct 19, 2020 |
| Apple         | MacBookAir6,2               | [9f80fdafb0](https://bsd-hardware.info/?probe=9f80fdafb0) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | [017b41dfd7](https://bsd-hardware.info/?probe=017b41dfd7) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4f54c8f399](https://bsd-hardware.info/?probe=4f54c8f399) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [0e0656d228](https://bsd-hardware.info/?probe=0e0656d228) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [60e72f1c10](https://bsd-hardware.info/?probe=60e72f1c10) | Oct 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS1BC01    | [bf6d6d155b](https://bsd-hardware.info/?probe=bf6d6d155b) | Oct 19, 2020 |
| Lenovo        | 3000 N100 0768B9G           | [c44a86f589](https://bsd-hardware.info/?probe=c44a86f589) | Oct 19, 2020 |
| ASUSTek       | G551JW                      | [594e6f28fb](https://bsd-hardware.info/?probe=594e6f28fb) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ee1f866775](https://bsd-hardware.info/?probe=ee1f866775) | Oct 13, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | [fbf90aaf0d](https://bsd-hardware.info/?probe=fbf90aaf0d) | Sep 11, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | [e06815d9dc](https://bsd-hardware.info/?probe=e06815d9dc) | Sep 11, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [1f28f1c311](https://bsd-hardware.info/?probe=1f28f1c311) | Aug 30, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [11a0bbb73f](https://bsd-hardware.info/?probe=11a0bbb73f) | Aug 30, 2020 |
| Lenovo        | ThinkPad P40 Yoga 20GQ00... | [ac92b69122](https://bsd-hardware.info/?probe=ac92b69122) | Aug 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3032cd9409](https://bsd-hardware.info/?probe=3032cd9409) | Aug 20, 2020 |
| HP            | Laptop 15-dw0xxx            | [547b36ea62](https://bsd-hardware.info/?probe=547b36ea62) | Aug 19, 2020 |
| HCL Infosy... | Calistoga & ICH7M Chipse... | [6adc98922d](https://bsd-hardware.info/?probe=6adc98922d) | Aug 19, 2020 |
| IBM           | ThinkPad T42 2373K9G        | [fa35e7ec26](https://bsd-hardware.info/?probe=fa35e7ec26) | Aug 11, 2020 |
| HP            | ZBook 15 G4                 | [a8953b4964](https://bsd-hardware.info/?probe=a8953b4964) | Aug 03, 2020 |
| HP            | ZBook 15 G4                 | [a97053c5d4](https://bsd-hardware.info/?probe=a97053c5d4) | Aug 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [20f3e760eb](https://bsd-hardware.info/?probe=20f3e760eb) | Aug 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [b305c0df5e](https://bsd-hardware.info/?probe=b305c0df5e) | Aug 03, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [f3e2acbb66](https://bsd-hardware.info/?probe=f3e2acbb66) | Jul 31, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [7ae8c247e9](https://bsd-hardware.info/?probe=7ae8c247e9) | Jul 31, 2020 |
| Lenovo        | ThinkPad T60 87445BU        | [37a42caa92](https://bsd-hardware.info/?probe=37a42caa92) | Jul 30, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [ac13b0591f](https://bsd-hardware.info/?probe=ac13b0591f) | Jul 27, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dfef5fdcbf](https://bsd-hardware.info/?probe=dfef5fdcbf) | Jun 10, 2020 |
| Toshiba       | Satellite L775D             | [bb218a14a6](https://bsd-hardware.info/?probe=bb218a14a6) | Jun 03, 2020 |
| Toshiba       | Satellite L775D             | [f0ec90217a](https://bsd-hardware.info/?probe=f0ec90217a) | Jun 03, 2020 |
| Lenovo        | ThinkPad X220 4291C35       | [f22c83f68b](https://bsd-hardware.info/?probe=f22c83f68b) | May 31, 2020 |
| Panasonic     | CF-19ADUAX1M                | [cefc742c62](https://bsd-hardware.info/?probe=cefc742c62) | May 29, 2020 |
| Fujitsu       | LIFEBOOK A357               | [b02640458b](https://bsd-hardware.info/?probe=b02640458b) | May 26, 2020 |
| Lenovo        | ThinkPad X230 2324A57       | [6ea713bf51](https://bsd-hardware.info/?probe=6ea713bf51) | May 25, 2020 |
| Lenovo        | ThinkPad X230 2324A57       | [7b67911c5a](https://bsd-hardware.info/?probe=7b67911c5a) | May 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b4ca8bbc46](https://bsd-hardware.info/?probe=b4ca8bbc46) | May 25, 2020 |
| Lenovo        | ThinkPad T420 4180B39       | [916596bfa8](https://bsd-hardware.info/?probe=916596bfa8) | May 25, 2020 |
| IBM           | ThinkPad X41 2525FAG        | [1e849f86cf](https://bsd-hardware.info/?probe=1e849f86cf) | May 25, 2020 |
| Lenovo        | ThinkPad T440 20B7S1C600    | [a4a62cb85e](https://bsd-hardware.info/?probe=a4a62cb85e) | May 24, 2020 |
| Lenovo        | ThinkPad T440s 20AR003VM... | [3f72b76851](https://bsd-hardware.info/?probe=3f72b76851) | May 23, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [fa71e5839a](https://bsd-hardware.info/?probe=fa71e5839a) | May 23, 2020 |
| Lenovo        | ThinkPad X260 20F5S1H800    | [85567202a8](https://bsd-hardware.info/?probe=85567202a8) | May 23, 2020 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | [9ff1537692](https://bsd-hardware.info/?probe=9ff1537692) | May 23, 2020 |
| Lenovo        | G570 20079                  | [8212868b9f](https://bsd-hardware.info/?probe=8212868b9f) | May 19, 2020 |
| Lenovo        | G570 20079                  | [bdd93164cf](https://bsd-hardware.info/?probe=bdd93164cf) | May 17, 2020 |
| ASUSTek       | A3L                         | [0c73038abc](https://bsd-hardware.info/?probe=0c73038abc) | May 06, 2020 |
| ASUSTek       | A3L                         | [ff5b6e3024](https://bsd-hardware.info/?probe=ff5b6e3024) | May 06, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| OpenBSD 6.8 | 90        | 35.43%  |
| OpenBSD 6.9 | 55        | 21.65%  |
| OpenBSD 7.0 | 50        | 19.69%  |
| OpenBSD 7.1 | 33        | 12.99%  |
| OpenBSD 6.7 | 23        | 9.06%   |
| OpenBSD 6.6 | 2         | 0.79%   |
| OpenBSD 7.2 | 1         | 0.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| OpenBSD | 215       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 189       | 87.91%  |
| i386   | 23        | 10.7%   |
| macppc | 3         | 1.4%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| fvwm         | 181       | 79.04%  |
| helloDesktop | 25        | 10.92%  |
| Console      | 11        | 4.8%    |
| XFCE         | 5         | 2.18%   |
| Mutter       | 2         | 0.87%   |
| Openbox      | 1         | 0.44%   |
| MATE         | 1         | 0.44%   |
| iwm          | 1         | 0.44%   |
| i3           | 1         | 0.44%   |
| GNOME        | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 199       | 92.13%  |
| Console | 17        | 7.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 180       | 81.82%  |
| SLiM    | 24        | 10.91%  |
| GDM     | 16        | 7.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 161       | 73.18%  |
| en_US   | 27        | 12.27%  |
| ru_RU   | 7         | 3.18%   |
| C       | 6         | 2.73%   |
| en_GB   | 5         | 2.27%   |
| fr_FR   | 4         | 1.82%   |
| es_CO   | 2         | 0.91%   |
| zh_CN   | 1         | 0.45%   |
| ja_JP   | 1         | 0.45%   |
| fr_CA   | 1         | 0.45%   |
| es_ES   | 1         | 0.45%   |
| en_EN   | 1         | 0.45%   |
| en_CA   | 1         | 0.45%   |
| en_AU   | 1         | 0.45%   |
| de_DE   | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 120       | 55.05%  |
| BIOS | 98        | 44.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ffs  | 215       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 110       | 50.23%  |
| MBR     | 105       | 47.95%  |
| Unknown | 4         | 1.83%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 106       | 49.3%   |
| Hewlett-Packard                | 17        | 7.91%   |
| Dell                           | 16        | 7.44%   |
| ASUSTek Computer               | 15        | 6.98%   |
| Apple                          | 11        | 5.12%   |
| Acer                           | 11        | 5.12%   |
| IBM                            | 6         | 2.79%   |
| Panasonic                      | 5         | 2.33%   |
| Sony                           | 3         | 1.4%    |
| Samsung Electronics            | 3         | 1.4%    |
| Fujitsu                        | 3         | 1.4%    |
| Unknown                        | 3         | 1.4%    |
| TUXEDO                         | 2         | 0.93%   |
| MSI                            | 2         | 0.93%   |
| Matsushita Electric Industrial | 2         | 0.93%   |
| Toshiba                        | 1         | 0.47%   |
| Standard                       | 1         | 0.47%   |
| Intel                          | 1         | 0.47%   |
| HCL Infosystems Limited        | 1         | 0.47%   |
| Google                         | 1         | 0.47%   |
| Framework                      | 1         | 0.47%   |
| DEXP                           | 1         | 0.47%   |
| Clevo                          | 1         | 0.47%   |
| Casper                         | 1         | 0.47%   |
| Alienware                      | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad X200 745969G                | 6         | 2.79%   |
| Unknown                                     | 4         | 1.86%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW    | 2         | 0.93%   |
| HP ZBook 15 G4                              | 2         | 0.93%   |
| ASUS X102BA                                 | 2         | 0.93%   |
| Apple MacBookAir6,2                         | 2         | 0.93%   |
| Apple MacBook5,1                            | 2         | 0.93%   |
| TUXEDO Pulse 15 Gen1                        | 1         | 0.47%   |
| TUXEDO Aura 15 Gen1                         | 1         | 0.47%   |
| Toshiba Satellite L775D                     | 1         | 0.47%   |
| Standard TF                                 | 1         | 0.47%   |
| Sony VPCX115KX                              | 1         | 0.47%   |
| Sony VPCF12C5E                              | 1         | 0.47%   |
| Sony VGN-P698E                              | 1         | 0.47%   |
| Samsung R720                                | 1         | 0.47%   |
| Samsung 530XBB                              | 1         | 0.47%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV    | 1         | 0.47%   |
| Panasonic CF-C1BT02EGE                      | 1         | 0.47%   |
| Panasonic CF-53AAGHYDM                      | 1         | 0.47%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 0.47%   |
| Panasonic CF-30KTP48NL                      | 1         | 0.47%   |
| Panasonic CF-19ADUAX1M                      | 1         | 0.47%   |
| MSI MS-1613                                 | 1         | 0.47%   |
| MSI Modern 14 B11MOL                        | 1         | 0.47%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 0.47%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 0.47%   |
| Lenovo Yoga 720-13IKB 81C3                  | 1         | 0.47%   |
| Lenovo Yoga 6 13ARE05 82FN                  | 1         | 0.47%   |
| Lenovo Yoga 330-11IGM 81A6                  | 1         | 0.47%   |
| Lenovo V130-15IGM 81HL                      | 1         | 0.47%   |
| Lenovo ThinkPad Yoga 260 20FES1K81V         | 1         | 0.47%   |
| Lenovo ThinkPad Yoga 11e 20DAS02S00         | 1         | 0.47%   |
| Lenovo ThinkPad X61 7675H7U                 | 1         | 0.47%   |
| Lenovo ThinkPad X60s 17033JM                | 1         | 0.47%   |
| Lenovo ThinkPad X395 20NL000HGE             | 1         | 0.47%   |
| Lenovo ThinkPad X280 20KESA000B             | 1         | 0.47%   |
| Lenovo ThinkPad X270 20HNA006ID             | 1         | 0.47%   |
| Lenovo ThinkPad X270 20HNA004CD             | 1         | 0.47%   |
| Lenovo ThinkPad X260 20F5S1H800             | 1         | 0.47%   |
| Lenovo ThinkPad X260 20F5S08Q00             | 1         | 0.47%   |
| Lenovo ThinkPad X250 20CM0046US             | 1         | 0.47%   |
| Lenovo ThinkPad X250 20CLS7WY04             | 1         | 0.47%   |
| Lenovo ThinkPad X250 20CLS59400             | 1         | 0.47%   |
| Lenovo ThinkPad X250 20CLS4WV08             | 1         | 0.47%   |
| Lenovo ThinkPad X250 20CLS1LC13             | 1         | 0.47%   |
| Lenovo ThinkPad X240 20AMS2QD0C             | 1         | 0.47%   |
| Lenovo ThinkPad X240 20AL00DKRT             | 1         | 0.47%   |
| Lenovo ThinkPad X230 2325Y36                | 1         | 0.47%   |
| Lenovo ThinkPad X230 2325R74                | 1         | 0.47%   |
| Lenovo ThinkPad X230 2325AJ9                | 1         | 0.47%   |
| Lenovo ThinkPad X230 232578G                | 1         | 0.47%   |
| Lenovo ThinkPad X230 2324A57                | 1         | 0.47%   |
| Lenovo ThinkPad X220 4291QT1                | 1         | 0.47%   |
| Lenovo ThinkPad X220 4291ON5                | 1         | 0.47%   |
| Lenovo ThinkPad X220 4291EM4                | 1         | 0.47%   |
| Lenovo ThinkPad X220 4291C35                | 1         | 0.47%   |
| Lenovo ThinkPad X220 429043U                | 1         | 0.47%   |
| Lenovo ThinkPad X201 Tablet 2985F4U         | 1         | 0.47%   |
| Lenovo ThinkPad X201 3680FAG                | 1         | 0.47%   |
| Lenovo ThinkPad X200 7458NP9                | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 92        | 42.79%  |
| Lenovo IdeaPad                              | 5         | 2.33%   |
| IBM ThinkPad                                | 5         | 2.33%   |
| Dell Latitude                               | 4         | 1.86%   |
| Dell Inspiron                               | 4         | 1.86%   |
| Acer Aspire                                 | 4         | 1.86%   |
| Unknown                                     | 4         | 1.86%   |
| Lenovo Yoga                                 | 3         | 1.4%    |
| HP Pavilion                                 | 3         | 1.4%    |
| Fujitsu LIFEBOOK                            | 3         | 1.4%    |
| Dell XPS                                    | 3         | 1.4%    |
| ASUS VivoBook                               | 3         | 1.4%    |
| Lenovo Flex                                 | 2         | 0.93%   |
| HP ZBook                                    | 2         | 0.93%   |
| HP EliteBook                                | 2         | 0.93%   |
| Dell Vostro                                 | 2         | 0.93%   |
| Dell Precision                              | 2         | 0.93%   |
| ASUS X102BA                                 | 2         | 0.93%   |
| Apple PowerBook5                            | 2         | 0.93%   |
| Apple MacBookAir6                           | 2         | 0.93%   |
| Apple MacBook5                              | 2         | 0.93%   |
| Acer Extensa                                | 2         | 0.93%   |
| TUXEDO Pulse                                | 1         | 0.47%   |
| TUXEDO Aura                                 | 1         | 0.47%   |
| Toshiba Satellite                           | 1         | 0.47%   |
| Standard TF                                 | 1         | 0.47%   |
| Sony VPCX115KX                              | 1         | 0.47%   |
| Sony VPCF12C5E                              | 1         | 0.47%   |
| Sony VGN-P698E                              | 1         | 0.47%   |
| Samsung R720                                | 1         | 0.47%   |
| Samsung 530XBB                              | 1         | 0.47%   |
| Samsung 3570R                               | 1         | 0.47%   |
| Panasonic CF-C1BT02EGE                      | 1         | 0.47%   |
| Panasonic CF-53AAGHYDM                      | 1         | 0.47%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 0.47%   |
| Panasonic CF-30KTP48NL                      | 1         | 0.47%   |
| Panasonic CF-19ADUAX1M                      | 1         | 0.47%   |
| MSI MS-1613                                 | 1         | 0.47%   |
| MSI Modern                                  | 1         | 0.47%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 0.47%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 0.47%   |
| Lenovo V130-15IGM                           | 1         | 0.47%   |
| Lenovo G50-80                               | 1         | 0.47%   |
| Lenovo 3000                                 | 1         | 0.47%   |
| Intel SharkBay                              | 1         | 0.47%   |
| IBM 2658MNG                                 | 1         | 0.47%   |
| HP Setzer                                   | 1         | 0.47%   |
| HP ProBook                                  | 1         | 0.47%   |
| HP OmniBook                                 | 1         | 0.47%   |
| HP OMEN                                     | 1         | 0.47%   |
| HP Notebook                                 | 1         | 0.47%   |
| HP Laptop                                   | 1         | 0.47%   |
| HP Compaq                                   | 1         | 0.47%   |
| HP 530                                      | 1         | 0.47%   |
| HP 250                                      | 1         | 0.47%   |
| HP 240                                      | 1         | 0.47%   |
| HCL Infosystems Limited Calistoga           | 1         | 0.47%   |
| Google Grunt                                | 1         | 0.47%   |
| Framework Laptop                            | 1         | 0.47%   |
| DEXP NAVIS                                  | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 25        | 11.63%  |
| 2019    | 21        | 9.77%   |
| 2015    | 20        | 9.3%    |
| 2011    | 18        | 8.37%   |
| 2009    | 18        | 8.37%   |
| 2021    | 14        | 6.51%   |
| 2018    | 14        | 6.51%   |
| 2013    | 12        | 5.58%   |
| 2017    | 10        | 4.65%   |
| 2012    | 10        | 4.65%   |
| 2010    | 10        | 4.65%   |
| 2016    | 8         | 3.72%   |
| 2006    | 7         | 3.26%   |
| Unknown | 7         | 3.26%   |
| 2008    | 5         | 2.33%   |
| 2007    | 5         | 2.33%   |
| 2014    | 4         | 1.86%   |
| 2004    | 2         | 0.93%   |
| 2003    | 2         | 0.93%   |
| 2022    | 1         | 0.47%   |
| 2005    | 1         | 0.47%   |
| 2002    | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 215       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 211       | 98.14%  |
| Yes  | 4         | 1.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 75        | 34.88%  |
| 4.01-8.0   | 40        | 18.6%   |
| 16.01-24.0 | 31        | 14.42%  |
| 3.01-4.0   | 22        | 10.23%  |
| 2.01-3.0   | 14        | 6.51%   |
| 32.01-64.0 | 12        | 5.58%   |
| 1.01-2.0   | 10        | 4.65%   |
| 0.51-1.0   | 8         | 3.72%   |
| 0.01-0.5   | 3         | 1.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 186       | 86.11%  |
| 0        | 16        | 7.41%   |
| 0.51-1.0 | 10        | 4.63%   |
| Unknown  | 3         | 1.39%   |
| 1.01-2.0 | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 114       | 51.82%  |
| 2      | 80        | 36.36%  |
| 3      | 18        | 8.18%   |
| 4      | 7         | 3.18%   |
| 0      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 215       | 99.54%  |
| Yes       | 1         | 0.46%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 186       | 86.51%  |
| No        | 29        | 13.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 207       | 96.28%  |
| No        | 8         | 3.72%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 127       | 58.53%  |
| No        | 90        | 41.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 43        | 19.82%  |
| Germany      | 28        | 12.9%   |
| Russia       | 20        | 9.22%   |
| France       | 18        | 8.29%   |
| Canada       | 14        | 6.45%   |
| Poland       | 10        | 4.61%   |
| UK           | 8         | 3.69%   |
| Sweden       | 6         | 2.76%   |
| Netherlands  | 6         | 2.76%   |
| Norway       | 5         | 2.3%    |
| Spain        | 4         | 1.84%   |
| Latvia       | 4         | 1.84%   |
| Australia    | 4         | 1.84%   |
| Ukraine      | 3         | 1.38%   |
| Switzerland  | 3         | 1.38%   |
| Portugal     | 3         | 1.38%   |
| Philippines  | 3         | 1.38%   |
| Italy        | 3         | 1.38%   |
| India        | 3         | 1.38%   |
| Czechia      | 3         | 1.38%   |
| Turkey       | 2         | 0.92%   |
| Malaysia     | 2         | 0.92%   |
| Japan        | 2         | 0.92%   |
| Finland      | 2         | 0.92%   |
| Croatia      | 2         | 0.92%   |
| Colombia     | 2         | 0.92%   |
| Brazil       | 2         | 0.92%   |
| Vietnam      | 1         | 0.46%   |
| Slovenia     | 1         | 0.46%   |
| Saudi Arabia | 1         | 0.46%   |
| Indonesia    | 1         | 0.46%   |
| Honduras     | 1         | 0.46%   |
| Ecuador      | 1         | 0.46%   |
| Costa Rica   | 1         | 0.46%   |
| China        | 1         | 0.46%   |
| Chile        | 1         | 0.46%   |
| Bulgaria     | 1         | 0.46%   |
| Belarus      | 1         | 0.46%   |
| Austria      | 1         | 0.46%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Montreal           | 11        | 4.6%    |
| Saint-Laurent      | 9         | 3.77%   |
| Vladivostok        | 5         | 2.09%   |
| QuГ©bec          | 5         | 2.09%   |
| Paris              | 5         | 2.09%   |
| Gdansk             | 5         | 2.09%   |
| Riga               | 4         | 1.67%   |
| Berlin             | 4         | 1.67%   |
| Amsterdam          | 4         | 1.67%   |
| Zurich             | 3         | 1.26%   |
| Yekaterinburg      | 3         | 1.26%   |
| St Petersburg      | 3         | 1.26%   |
| Portland           | 3         | 1.26%   |
| Oslo               | 3         | 1.26%   |
| Frankfurt am Main  | 3         | 1.26%   |
| Brooklyn           | 3         | 1.26%   |
| Sydney             | 2         | 0.84%   |
| Quezon City        | 2         | 0.84%   |
| Prague             | 2         | 0.84%   |
| Papillion          | 2         | 0.84%   |
| Moscow             | 2         | 0.84%   |
| Mâcon             | 2         | 0.84%   |
| Los Angeles        | 2         | 0.84%   |
| Krakow             | 2         | 0.84%   |
| Henan              | 2         | 0.84%   |
| Gummersbach        | 2         | 0.84%   |
| Gettysburg         | 2         | 0.84%   |
| Dublin             | 2         | 0.84%   |
| 's-Hertogenbosch   | 2         | 0.84%   |
| Zhukovskiy         | 1         | 0.42%   |
| Yoshkar-Ola        | 1         | 0.42%   |
| Wolfsburg          | 1         | 0.42%   |
| Wetzlar            | 1         | 0.42%   |
| West Valley City   | 1         | 0.42%   |
| Weinbohla          | 1         | 0.42%   |
| Watford            | 1         | 0.42%   |
| Warner             | 1         | 0.42%   |
| Vienna             | 1         | 0.42%   |
| Victoria           | 1         | 0.42%   |
| Vantaa             | 1         | 0.42%   |
| Valdivia           | 1         | 0.42%   |
| Vacaville          | 1         | 0.42%   |
| Tustin             | 1         | 0.42%   |
| Turin              | 1         | 0.42%   |
| Trondheim          | 1         | 0.42%   |
| Tokyo              | 1         | 0.42%   |
| Thrissur           | 1         | 0.42%   |
| Teriang            | 1         | 0.42%   |
| Temple City        | 1         | 0.42%   |
| Tegucigalpa        | 1         | 0.42%   |
| SГЈo Paulo       | 1         | 0.42%   |
| Sutton             | 1         | 0.42%   |
| Surabaya           | 1         | 0.42%   |
| Stuttgart          | 1         | 0.42%   |
| Strasburg          | 1         | 0.42%   |
| Starogard Gdański | 1         | 0.42%   |
| Springboro         | 1         | 0.42%   |
| Spokane            | 1         | 0.42%   |
| Solna              | 1         | 0.42%   |
| Sofia              | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 52        | 69     | 20.88%  |
| Samsung Electronics | 41        | 48     | 16.47%  |
| WDC                 | 29        | 45     | 11.65%  |
| Seagate             | 16        | 20     | 6.43%   |
| SanDisk             | 15        | 18     | 6.02%   |
| Toshiba             | 13        | 17     | 5.22%   |
| Crucial             | 9         | 9      | 3.61%   |
| Kingston            | 8         | 9      | 3.21%   |
| Hitachi             | 8         | 9      | 3.21%   |
| Intel               | 6         | 6      | 2.41%   |
| HGST                | 5         | 7      | 2.01%   |
| Transcend           | 4         | 4      | 1.61%   |
| PNY                 | 4         | 4      | 1.61%   |
| Apple               | 4         | 4      | 1.61%   |
| SK hynix            | 3         | 3      | 1.2%    |
| SPCC                | 2         | 2      | 0.8%    |
| Plextor             | 2         | 2      | 0.8%    |
| Netac               | 2         | 2      | 0.8%    |
| Innostor            | 2         | 2      | 0.8%    |
| Generic             | 2         | 2      | 0.8%    |
| Apacer              | 2         | 2      | 0.8%    |
| A-DATA Technology   | 2         | 4      | 0.8%    |
| Zheino              | 1         | 2      | 0.4%    |
| USB                 | 1         | 1      | 0.4%    |
| UFD 2.0             | 1         | 1      | 0.4%    |
| Team                | 1         | 1      | 0.4%    |
| Patriot             | 1         | 1      | 0.4%    |
| OWC                 | 1         | 1      | 0.4%    |
| OPENBSD             | 1         | 1      | 0.4%    |
| Micron Technology   | 1         | 1      | 0.4%    |
| LITEONIT            | 1         | 1      | 0.4%    |
| LITEON              | 1         | 1      | 0.4%    |
| Lexar               | 1         | 1      | 0.4%    |
| Leven               | 1         | 1      | 0.4%    |
| LDLC F6+            | 1         | 1      | 0.4%    |
| KingSpec            | 1         | 1      | 0.4%    |
| Hewlett-Packard     | 1         | 1      | 0.4%    |
| Gigabyte Technology | 1         | 1      | 0.4%    |
| Fujitsu             | 1         | 1      | 0.4%    |
| Dogfish             | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| NVMe WDC PC SN730 SDB 256GB         | 8         | 3.14%   |
| Samsung HM321HI 320GB               | 6         | 2.35%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 5         | 1.96%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 1.96%   |
| Samsung SSD 850 EVO 500GB           | 4         | 1.57%   |
| Samsung SSD 850 EVO 250GB           | 3         | 1.18%   |
| NVMe Samsung SSD 970 250GB          | 3         | 1.18%   |
| NVMe SAMSUNG MZVLB256 256GB         | 3         | 1.18%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 0.78%   |
| WDC WD10JPLX-00MBPT0 1TB            | 2         | 0.78%   |
| Toshiba MK8025GAS 80GB              | 2         | 0.78%   |
| Toshiba MK2556GSY 250GB             | 2         | 0.78%   |
| SK hynix SC311 SATA 256GB           | 2         | 0.78%   |
| Seagate ST9320423AS 320GB           | 2         | 0.78%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 0.78%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 0.78%   |
| SanDisk SSD U110 16GB               | 2         | 0.78%   |
| SanDisk Cruzer Blade 32GB           | 2         | 0.78%   |
| Samsung SSD 860 EVO 1TB             | 2         | 0.78%   |
| Samsung SSD 850 PRO 256GB           | 2         | 0.78%   |
| Samsung MZ7TD256HAFV-000L7 256GB    | 2         | 0.78%   |
| Samsung MZ7PC128HAFU-000L1 128GB    | 2         | 0.78%   |
| PNY CS900 120GB SSD                 | 2         | 0.78%   |
| NVMe WDC PC SN530 SDB 256GB         | 2         | 0.78%   |
| NVMe Samsung SSD 980 1TB            | 2         | 0.78%   |
| NVMe Samsung SSD 960 500GB          | 2         | 0.78%   |
| NVMe SAMSUNG MZVLW256 256GB         | 2         | 0.78%   |
| NVMe SAMSUNG MZVLB1T0 1TB           | 2         | 0.78%   |
| NVMe INTEL SSDPEKNW51 512GB         | 2         | 0.78%   |
| NVMe INTEL SSDPEKKF25 256GB         | 2         | 0.78%   |
| Kingston SA400S37480G 480GB         | 2         | 0.78%   |
| Kingston SA400S37240G 240GB         | 2         | 0.78%   |
| Intel SSDSC2KF256H6L 256GB          | 2         | 0.78%   |
| Innostor SSD 15GB                   | 2         | 0.78%   |
| Crucial CT500MX500SSD1 500GB        | 2         | 0.78%   |
| Crucial CT1000MX500SSD1 1TB         | 2         | 0.78%   |
| Apple SSD SD0128F 121GB             | 2         | 0.78%   |
| Zheino CHN-mSATAQ3-120 120GB        | 1         | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB        | 1         | 0.39%   |
| WDC WDS480G2G0B-00EPW0 480GB        | 1         | 0.39%   |
| WDC WDS240G2G0B-00EPW0 240GB        | 1         | 0.39%   |
| WDC WDS100T2B0A-00SM50 1TB          | 1         | 0.39%   |
| WDC WDBNCE5000PNC 500GB             | 1         | 0.39%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 0.39%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 1         | 0.39%   |
| WDC WD7500BPKT-22PK4T0 752GB        | 1         | 0.39%   |
| WDC WD7500BPKT-00PK4T0 752GB        | 1         | 0.39%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 0.39%   |
| WDC WD5000LPCX-75VHAT0 500GB        | 1         | 0.39%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 1         | 0.39%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 1         | 0.39%   |
| WDC WD5000LPCX-21VHAT0 500GB        | 1         | 0.39%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 1         | 0.39%   |
| WDC WD3200BEVE-00A0HT0 320GB        | 1         | 0.39%   |
| WDC WD3200BEKT-08PVMT1 320GB        | 1         | 0.39%   |
| WDC WD1600BEVE-00WZT0 160GB         | 1         | 0.39%   |
| WDC WD10JPVX-08JC3T5 1TB            | 1         | 0.39%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 0.39%   |
| USB SanDisk 3.2Gen1 64GB            | 1         | 0.39%   |
| UFD 2.0 Silicon-Power16G 18302PB    | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 38        | 49     | 32.76%  |
| WDC                 | 22        | 37     | 18.97%  |
| Seagate             | 16        | 20     | 13.79%  |
| Toshiba             | 10        | 14     | 8.62%   |
| Samsung Electronics | 8         | 10     | 6.9%    |
| Hitachi             | 8         | 9      | 6.9%    |
| HGST                | 5         | 7      | 4.31%   |
| Generic             | 2         | 2      | 1.72%   |
| USB                 | 1         | 1      | 0.86%   |
| UFD 2.0             | 1         | 1      | 0.86%   |
| OPENBSD             | 1         | 1      | 0.86%   |
| Lexar               | 1         | 1      | 0.86%   |
| LDLC F6+            | 1         | 1      | 0.86%   |
| Fujitsu             | 1         | 1      | 0.86%   |
| Apple               | 1         | 1      | 0.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 38     | 25.19%  |
| SanDisk             | 15        | 18     | 11.45%  |
| NVMe                | 12        | 14     | 9.16%   |
| Crucial             | 9         | 9      | 6.87%   |
| Kingston            | 8         | 9      | 6.11%   |
| WDC                 | 7         | 8      | 5.34%   |
| Intel               | 6         | 6      | 4.58%   |
| Transcend           | 4         | 4      | 3.05%   |
| PNY                 | 4         | 4      | 3.05%   |
| Toshiba             | 3         | 3      | 2.29%   |
| SK hynix            | 3         | 3      | 2.29%   |
| Apple               | 3         | 3      | 2.29%   |
| SPCC                | 2         | 2      | 1.53%   |
| Plextor             | 2         | 2      | 1.53%   |
| Netac               | 2         | 2      | 1.53%   |
| Innostor            | 2         | 2      | 1.53%   |
| Apacer              | 2         | 2      | 1.53%   |
| A-DATA Technology   | 2         | 4      | 1.53%   |
| Zheino              | 1         | 2      | 0.76%   |
| Team                | 1         | 1      | 0.76%   |
| Patriot             | 1         | 1      | 0.76%   |
| OWC                 | 1         | 1      | 0.76%   |
| Micron Technology   | 1         | 1      | 0.76%   |
| LITEONIT            | 1         | 1      | 0.76%   |
| LITEON              | 1         | 1      | 0.76%   |
| Leven               | 1         | 1      | 0.76%   |
| KingSpec            | 1         | 1      | 0.76%   |
| Hewlett-Packard     | 1         | 1      | 0.76%   |
| Gigabyte Technology | 1         | 1      | 0.76%   |
| Dogfish             | 1         | 1      | 0.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 117       | 146    | 50.87%  |
| HDD  | 108       | 155    | 46.96%  |
| NVMe | 5         | 6      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 205       | 301    | 97.62%  |
| NVMe | 5         | 6      | 2.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 163       | 222    | 72.44%  |
| 0.51-1.0        | 50        | 61     | 22.22%  |
| 1.01-2.0        | 9         | 15     | 4%      |
| More than 100.0 | 1         | 1      | 0.44%   |
| 4.01-10.0       | 1         | 1      | 0.44%   |
| 0               | 1         | 1      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 82        | 36.61%  |
| 251-500    | 62        | 27.68%  |
| 51-100     | 29        | 12.95%  |
| 21-50      | 20        | 8.93%   |
| 1-20       | 13        | 5.8%    |
| 501-1000   | 12        | 5.36%   |
| 1001-2000  | 6         | 2.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 152       | 68.47%  |
| 21-50    | 22        | 9.91%   |
| 101-250  | 20        | 9.01%   |
| 51-100   | 19        | 8.56%   |
| 251-500  | 7         | 3.15%   |
| 501-1000 | 2         | 0.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST9320423AS 320GB         | 2         | 2      | 8.7%    |
| Intel SSDSC2KF256H6L 256GB        | 2         | 2      | 8.7%    |
| WDC WD1600BEVT-22ZCT0 160GB       | 1         | 1      | 4.35%   |
| Toshiba MK6006GAH 64GB            | 1         | 1      | 4.35%   |
| Toshiba MK1629GSGF 160GB          | 1         | 3      | 4.35%   |
| Seagate ST9500420AS 500GB         | 1         | 2      | 4.35%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 4.35%   |
| SanDisk SD7UB3Q256G1001 256GB     | 1         | 2      | 4.35%   |
| Samsung Electronics HM500JI 500GB | 1         | 2      | 4.35%   |
| Kingston SMSM151S3128GD 128GB     | 1         | 1      | 4.35%   |
| KingSpec KSD-PA25.6-032MS 32GB    | 1         | 1      | 4.35%   |
| Intel SSDSA2M080G2GC 80GB         | 1         | 1      | 4.35%   |
| Hitachi HTS722010K9SA00 100GB     | 1         | 1      | 4.35%   |
| Hitachi HTS541060G9SA00 64GB      | 1         | 1      | 4.35%   |
| Hitachi HTC426060G9AT00 64GB      | 1         | 1      | 4.35%   |
| Hitachi DK23AA-12 12GB            | 1         | 1      | 4.35%   |
| HGST HTS545050A7E660 500GB        | 1         | 2      | 4.35%   |
| HGST HTE725032A7E630 320GB        | 1         | 1      | 4.35%   |
| Apple SSD SD0128F 121GB           | 1         | 1      | 4.35%   |
| A-DATA Technology SP550 480GB     | 1         | 3      | 4.35%   |
| A-DATA Technology SP550 240GB     | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 17.39%  |
| Hitachi             | 4         | 4      | 17.39%  |
| Intel               | 3         | 3      | 13.04%  |
| Toshiba             | 2         | 4      | 8.7%    |
| HGST                | 2         | 3      | 8.7%    |
| A-DATA Technology   | 2         | 4      | 8.7%    |
| WDC                 | 1         | 1      | 4.35%   |
| SanDisk             | 1         | 2      | 4.35%   |
| Samsung Electronics | 1         | 2      | 4.35%   |
| Kingston            | 1         | 1      | 4.35%   |
| KingSpec            | 1         | 1      | 4.35%   |
| Apple               | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 28.57%  |
| Hitachi             | 4         | 4      | 28.57%  |
| Toshiba             | 2         | 4      | 14.29%  |
| HGST                | 2         | 3      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 19     | 60.87%  |
| SSD  | 9         | 12     | 39.13%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 151       | 203    | 65.94%  |
| Detected | 55        | 73     | 24.02%  |
| Malfunc  | 23        | 31     | 10.04%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 156       | 67.24%  |
| Samsung Electronics              | 19        | 8.19%   |
| AMD                              | 18        | 7.76%   |
| SanDisk                          | 15        | 6.47%   |
| SK hynix                         | 4         | 1.72%   |
| KIOXIA                           | 4         | 1.72%   |
| Nvidia                           | 3         | 1.29%   |
| Kingston Technology Company      | 3         | 1.29%   |
| Phison Electronics               | 2         | 0.86%   |
| Marvell Technology Group         | 2         | 0.86%   |
| Lenovo                           | 2         | 0.86%   |
| Union Memory (Shenzhen)          | 1         | 0.43%   |
| Toshiba                          | 1         | 0.43%   |
| Silicon Integrated Systems [SiS] | 1         | 0.43%   |
| ADATA Technology                 | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 7.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 6.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 16        | 6.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 6.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 14        | 5.67%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 5.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 8         | 3.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 3.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 3.24%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 2.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 2.43%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 6         | 2.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 2.43%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 5         | 2.02%   |
| Intel 82801CAM IDE U100 Controller                                             | 4         | 1.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.62%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.21%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.21%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3         | 1.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.21%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 3         | 1.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.21%   |
| SK hynix hynix unknown                                                         | 2         | 0.81%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.81%   |
| Samsung SM951 AHCI                                                             | 2         | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.81%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 0.81%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 2         | 0.81%   |
| Lenovo unknown                                                                 | 2         | 0.81%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.81%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 0.81%   |
| Intel SSD 660P Series                                                          | 2         | 0.81%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.81%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.81%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 2         | 0.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 0.81%   |
| Union Memory (Shenzhen) Memory unknown                                         | 1         | 0.4%    |
| Toshiba unknown                                                                | 1         | 0.4%    |
| SK hynix BC511                                                                 | 1         | 0.4%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] 5518 UDMA IDE Controller                      | 1         | 0.4%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.4%    |
| SanDisk WD Black NVMe SSD                                                      | 1         | 0.4%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.4%    |
| SanDisk unknown                                                                | 1         | 0.4%    |
| SanDisk PC SN530                                                               | 1         | 0.4%    |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.4%    |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.4%    |
| Phison E12 NVMe Controller                                                     | 1         | 0.4%    |
| Nvidia MCP79 SATA Controller                                                   | 1         | 0.4%    |
| KIOXIA NVMe SSD                                                                | 1         | 0.4%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.4%    |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.4%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 0.4%    |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 1         | 0.4%    |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 0.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 154       | 63.64%  |
| NVMe | 52        | 21.49%  |
| IDE  | 35        | 14.46%  |
| RAID | 1         | 0.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 185       | 86.05%  |
| AMD     | 26        | 12.09%  |
| PowerPC | 2         | 0.93%   |
| 11th    | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                                   | 12        | 5.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz                                   | 7         | 3.18%   |
| Intel Core i5-8250U CPU @ 1.60GHz                                   | 6         | 2.73%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                                | 6         | 2.73%   |
| Intel Core i5-6300U CPU @ 2.40GHz                                   | 5         | 2.27%   |
| Intel Core i5-5300U CPU @ 2.30GHz                                   | 5         | 2.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz                                   | 4         | 1.82%   |
| Intel Core i7-7500U CPU @ 2.70GHz                                   | 4         | 1.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz                                   | 4         | 1.82%   |
| Intel Core i7-5600U CPU @ 2.60GHz                                   | 3         | 1.36%   |
| Intel Core i7-3520M CPU @ 2.90GHz                                   | 3         | 1.36%   |
| Intel Core i5-8265U CPU @ 1.60GHz                                   | 3         | 1.36%   |
| Intel Core i3-6006U CPU @ 2.00GHz                                   | 3         | 1.36%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                                | 3         | 1.36%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class)            | 3         | 1.36%   |
| AMD Ryzen 7 4800H with Radeon Graphics                              | 3         | 1.36%   |
| AMD Ryzen 7 4700U with Radeon Graphics                              | 3         | 1.36%   |
| PowerPC 7447A (Revision 0x105)                                      | 2         | 0.91%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz                                | 2         | 0.91%   |
| Intel Pentium M processor 1.70GHz ("GenuineIntel" 686-class)        | 2         | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz                                   | 2         | 0.91%   |
| Intel Core i7-6600U CPU @ 2.60GHz                                   | 2         | 0.91%   |
| Intel Core i7-5500U CPU @ 2.40GHz                                   | 2         | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz                                  | 2         | 0.91%   |
| Intel Core i5-4300U CPU @ 1.90GHz                                   | 2         | 0.91%   |
| Intel Core i5-4200U CPU @ 1.60GHz                                   | 2         | 0.91%   |
| Intel Core i5-3230M CPU @ 2.60GHz                                   | 2         | 0.91%   |
| Intel Core i5-2540M CPU @ 2.60GHz                                   | 2         | 0.91%   |
| Intel Core i5-10210U CPU @ 1.60GHz                                  | 2         | 0.91%   |
| Intel Core i5 CPU M 560 @ 2.67GHz                                   | 2         | 0.91%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                                   | 2         | 0.91%   |
| Intel Core i3-5005U CPU @ 2.00GHz                                   | 2         | 0.91%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz                                | 2         | 0.91%   |
| Intel Celeron N4000 CPU @ 1.10GHz                                   | 2         | 0.91%   |
| Intel Celeron CPU N3350 @ 1.10GHz                                   | 2         | 0.91%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                             | 2         | 0.91%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx                     | 2         | 0.91%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx                       | 2         | 0.91%   |
| AMD A6-3400M APU with Radeon HD Graphics                            | 2         | 0.91%   |
| AMD A4-1200 APU with Radeon HD Graphics                             | 2         | 0.91%   |
| Intel Pentium Silver N6000 @ 1.10GHz                                | 1         | 0.45%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz                            | 1         | 0.45%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                            | 1         | 0.45%   |
| Intel Pentium M processor 2.00GHz ("GenuineIntel" 686-class)        | 1         | 0.45%   |
| Intel Pentium M processor 1.86GHz ("GenuineIntel" 686-class)        | 1         | 0.45%   |
| Intel Pentium M processor 1.60GHz ("GenuineIntel" 686-class)        | 1         | 0.45%   |
| Intel Pentium M processor                                           | 1         | 0.45%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz                         | 1         | 0.45%   |
| Intel Pentium CPU N4200 @ 1.10GHz                                   | 1         | 0.45%   |
| Intel Pentium 4 Mobile CPU 1.60GHz ("GenuineIntel" 686-class)       | 1         | 0.45%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                                  | 1         | 0.45%   |
| Intel Mobile Pentium III CPU - M 1200MHz ("GenuineIntel" 686-class) | 1         | 0.45%   |
| Intel Mobile Pentium III CPU - M 1000MHz ("GenuineIntel" 686-class) | 1         | 0.45%   |
| Intel Mobile Pentium 4 - M CPU 1.70GHz ("GenuineIntel" 686-class)   | 1         | 0.45%   |
| Intel Mobile Celeron CPU 2.20GHz ("GenuineIntel" 686-class)         | 1         | 0.45%   |
| Intel Genuine CPU T2300 @ 1.66GHz                                   | 1         | 0.45%   |
| Intel Genuine CPU T2250 @ 1.73GHz ("GenuineIntel" 686-class)        | 1         | 0.45%   |
| Intel CPU T2300 @ 1.66GHz ("GenuineIntel" 686-class)                | 1         | 0.45%   |
| Intel Core Solo CPU U1400 @ 1.20GHz ("GenuineIntel" 686-class)      | 1         | 0.45%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz                                    | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 68        | 31.48%  |
| Intel Core i7           | 38        | 17.59%  |
| Intel Core 2 Duo        | 19        | 8.8%    |
| Intel Core i3           | 13        | 6.02%   |
| Other                   | 11        | 5.09%   |
| Intel Celeron           | 8         | 3.7%    |
| Intel Atom              | 7         | 3.24%   |
| AMD Ryzen 7             | 6         | 2.78%   |
| Intel Pentium M         | 5         | 2.31%   |
| AMD Ryzen 5             | 4         | 1.85%   |
| Intel Pentium Silver    | 3         | 1.39%   |
| AMD Ryzen 7 PRO         | 3         | 1.39%   |
| AMD A4                  | 3         | 1.39%   |
| Intel Xeon              | 2         | 0.93%   |
| Intel Genuine           | 2         | 0.93%   |
| Intel Core Duo          | 2         | 0.93%   |
| Intel Core 2            | 2         | 0.93%   |
| AMD Ryzen 3             | 2         | 0.93%   |
| AMD A6                  | 2         | 0.93%   |
| Intel Pentium Dual-Core | 1         | 0.46%   |
| Intel Pentium 4         | 1         | 0.46%   |
| Intel Pentium           | 1         | 0.46%   |
| Intel Mobile Pentium 4  | 1         | 0.46%   |
| Intel Mobile Celeron    | 1         | 0.46%   |
| Intel Core Solo         | 1         | 0.46%   |
| Intel Core m3           | 1         | 0.46%   |
| Intel Core M            | 1         | 0.46%   |
| Intel Core i9           | 1         | 0.46%   |
| Intel Celeron M         | 1         | 0.46%   |
| AMD V120                | 1         | 0.46%   |
| AMD Ryzen 5 PRO         | 1         | 0.46%   |
| AMD E1                  | 1         | 0.46%   |
| AMD E                   | 1         | 0.46%   |
| AMD C-50                | 1         | 0.46%   |
| AMD Athlon II Neo       | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 101       | 46.98%  |
| 4       | 46        | 21.4%   |
| Unknown | 35        | 16.28%  |
| 1       | 15        | 6.98%   |
| 8       | 9         | 4.19%   |
| 16      | 4         | 1.86%   |
| 12      | 3         | 1.4%    |
| 6       | 2         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 171       | 78.44%  |
| Unknown | 47        | 21.56%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 128       | 59.53%  |
| Unknown | 49        | 22.79%  |
| 1       | 38        | 17.67%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 35        | 16.13%  |
| Penryn        | 19        | 8.76%   |
| Broadwell     | 18        | 8.29%   |
| SandyBridge   | 17        | 7.83%   |
| IvyBridge     | 16        | 7.37%   |
| Haswell       | 14        | 6.45%   |
| P6            | 13        | 5.99%   |
| Skylake       | 12        | 5.53%   |
| Zen 2         | 9         | 4.15%   |
| Unknown       | 9         | 4.15%   |
| Westmere      | 8         | 3.69%   |
| Bonnell       | 7         | 3.23%   |
| Goldmont plus | 5         | 2.3%    |
| Zen+          | 3         | 1.38%   |
| Zen           | 3         | 1.38%   |
| TigerLake     | 3         | 1.38%   |
| Silvermont    | 3         | 1.38%   |
| NetBurst      | 3         | 1.38%   |
| Jaguar        | 3         | 1.38%   |
| Goldmont      | 3         | 1.38%   |
| Core          | 3         | 1.38%   |
| K10 Llano     | 2         | 0.92%   |
| K10           | 2         | 0.92%   |
| CometLake     | 2         | 0.92%   |
| Bobcat        | 2         | 0.92%   |
| Nehalem       | 1         | 0.46%   |
| IceLake       | 1         | 0.46%   |
| Excavator     | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 171       | 69.8%   |
| AMD                              | 44        | 17.96%  |
| Nvidia                           | 29        | 11.84%  |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 18        | 6.92%   |
| Intel HD Graphics 5500                                                        | 16        | 6.15%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 16        | 6.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 14        | 5.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 11        | 4.23%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 11        | 4.23%   |
| Intel UHD Graphics 620                                                        | 10        | 3.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 10        | 3.85%   |
| AMD Renoir                                                                    | 9         | 3.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 7         | 2.69%   |
| Intel HD Graphics 620                                                         | 7         | 2.69%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 6         | 2.31%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 2.31%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 1.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 4         | 1.54%   |
| Nvidia C79 [GeForce 9400M]                                                    | 3         | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 1.15%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 3         | 1.15%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 1.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.15%   |
| Nvidia TU117M                                                                 | 2         | 0.77%   |
| Nvidia GT218M [NVS 3100M]                                                     | 2         | 0.77%   |
| Nvidia GT216M [GeForce GT 330M]                                               | 2         | 0.77%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 2         | 0.77%   |
| Nvidia GM108M [GeForce 940M]                                                  | 2         | 0.77%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 0.77%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 0.77%   |
| Intel HD Graphics P630                                                        | 2         | 0.77%   |
| Intel HD Graphics 500                                                         | 2         | 0.77%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 2         | 0.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 0.77%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 2         | 0.77%   |
| AMD Sumo [Radeon HD 6520G]                                                    | 2         | 0.77%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                 | 2         | 0.77%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 2         | 0.77%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                     | 2         | 0.77%   |
| AMD Kabini [Radeon HD 8180]                                                   | 2         | 0.77%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter     | 1         | 0.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.38%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 0.38%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                              | 1         | 0.38%   |
| Nvidia GP108M [GeForce MX330]                                                 | 1         | 0.38%   |
| Nvidia GP108M [GeForce MX150]                                                 | 1         | 0.38%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 0.38%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                       | 1         | 0.38%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 0.38%   |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                                 | 1         | 0.38%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 1         | 0.38%   |
| Nvidia GK107GLM [Quadro K1100M]                                               | 1         | 0.38%   |
| Nvidia GK106GLM [Quadro K2100M]                                               | 1         | 0.38%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.38%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 0.38%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 0.38%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 0.38%   |
| Nvidia G96CM [GeForce 9600M GT]                                               | 1         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 117       | 54.42%  |
| 1 x AMD        | 33        | 15.35%  |
| 2 x Intel      | 28        | 13.02%  |
| Intel + Nvidia | 19        | 8.84%   |
| 1 x Nvidia     | 6         | 2.79%   |
| Intel + AMD    | 6         | 2.79%   |
| AMD + Nvidia   | 3         | 1.4%    |
| 2 x Nvidia     | 1         | 0.47%   |
| 2 x AMD        | 1         | 0.47%   |
| 1 x SiS        | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 206       | 95.81%  |
| Unknown | 9         | 4.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 215       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 33        | 20.5%   |
| LG Display              | 32        | 19.88%  |
| BOE                     | 24        | 14.91%  |
| Chimei Innolux          | 17        | 10.56%  |
| Lenovo                  | 15        | 9.32%   |
| Samsung Electronics     | 8         | 4.97%   |
| Apple                   | 7         | 4.35%   |
| Sharp                   | 3         | 1.86%   |
| PANDA                   | 3         | 1.86%   |
| Chi Mei Optoelectronics | 3         | 1.86%   |
| InfoVision              | 2         | 1.24%   |
| IBM                     | 2         | 1.24%   |
| Goldstar                | 2         | 1.24%   |
| LTM                     | 1         | 0.62%   |
| LG Philips              | 1         | 0.62%   |
| Iiyama                  | 1         | 0.62%   |
| HannStar                | 1         | 0.62%   |
| Gigabyte Technology     | 1         | 0.62%   |
| Dell                    | 1         | 0.62%   |
| CSO                     | 1         | 0.62%   |
| BenQ                    | 1         | 0.62%   |
| Ancor Communications    | 1         | 0.62%   |
| Acer                    | 1         | 0.62%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 6         | 3.73%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 6         | 3.73%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch             | 3         | 1.86%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 2         | 1.24%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 2         | 1.24%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch             | 2         | 1.24%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 2         | 1.24%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch             | 2         | 1.24%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 2         | 1.24%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch                  | 2         | 1.24%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                  | 2         | 1.24%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                    | 2         | 1.24%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 2         | 1.24%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 310x170mm 13.9-inch          | 2         | 1.24%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 2         | 1.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 1.24%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                    | 2         | 1.24%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch           | 2         | 1.24%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch           | 2         | 1.24%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 2         | 1.24%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 2         | 1.24%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch            | 2         | 1.24%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 340x190mm 15.3-inch                  | 1         | 0.62%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch                  | 1         | 0.62%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC374A 3200x1800 290x170mm 13.2-inch    | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch     | 1         | 0.62%   |
| Samsung Electronics C34H89x SAM0E25 3440x1440 800x330mm 34.1-inch        | 1         | 0.62%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 0.62%   |
| PANDA LCD Monitor NCP0046 1920x1080 340x190mm 15.3-inch                  | 1         | 0.62%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch                  | 1         | 0.62%   |
| LTM LCD Monitor LTM3937 720x1280 130x80mm 6.0-inch                       | 1         | 0.62%   |
| LG Philips LCD Monitor LPLDB00 1280x800 330x210mm 15.4-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD0525 1366x768 340x190mm 15.3-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 1         | 0.62%   |
| LG Display LCD Monitor LGD04F0 2560x1440 310x170mm 13.9-inch             | 1         | 0.62%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD04A3 1366x768 280x160mm 12.7-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch             | 1         | 0.62%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch             | 1         | 0.62%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD0438 1366x768 340x190mm 15.3-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD03DB 1366x768 350x190mm 15.7-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD02F7 1600x900 380x210mm 17.1-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch             | 1         | 0.62%   |
| LG Display LCD Monitor LGD01AB 1280x800 260x160mm 12.0-inch              | 1         | 0.62%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 1         | 0.62%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 1         | 0.62%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 1         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 35.22%  |
| 1366x768 (WXGA)    | 53        | 33.33%  |
| 1280x800 (WXGA)    | 15        | 9.43%   |
| 2560x1440 (QHD)    | 6         | 3.77%   |
| 1600x900 (HD+)     | 6         | 3.77%   |
| 1440x900 (WXGA+)   | 5         | 3.14%   |
| 3840x2160 (4K)     | 4         | 2.52%   |
| 1680x1050 (WSXGA+) | 3         | 1.89%   |
| 720x1280           | 1         | 0.63%   |
| 3840x2400          | 1         | 0.63%   |
| 3440x1440          | 1         | 0.63%   |
| 3200x1800 (QHD+)   | 1         | 0.63%   |
| 2256x1504          | 1         | 0.63%   |
| 1920x1200 (WUXGA)  | 1         | 0.63%   |
| 1440x960           | 1         | 0.63%   |
| 1360x768           | 1         | 0.63%   |
| 1280x854           | 1         | 0.63%   |
| 1024x768 (XGA)     | 1         | 0.63%   |
| 1024x600           | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 50        | 31.06%  |
| 13     | 50        | 31.06%  |
| 12     | 29        | 18.01%  |
| 11     | 10        | 6.21%   |
| 14     | 6         | 3.73%   |
| 24     | 2         | 1.24%   |
| 23     | 2         | 1.24%   |
| 18     | 2         | 1.24%   |
| 17     | 2         | 1.24%   |
| 10     | 2         | 1.24%   |
| 34     | 1         | 0.62%   |
| 28     | 1         | 0.62%   |
| 27     | 1         | 0.62%   |
| 21     | 1         | 0.62%   |
| 9      | 1         | 0.62%   |
| 6      | 1         | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 87        | 54.04%  |
| 201-300     | 60        | 37.27%  |
| 501-600     | 4         | 2.48%   |
| 401-500     | 4         | 2.48%   |
| 351-400     | 2         | 1.24%   |
| 101-200     | 2         | 1.24%   |
| 701-800     | 1         | 0.62%   |
| 601-700     | 1         | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 124       | 80%     |
| 16/10 | 23        | 14.84%  |
| 3/2   | 6         | 3.87%   |
| 4/3   | 1         | 0.65%   |
| 21/9  | 1         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 48        | 29.81%  |
| 91-100         | 40        | 24.84%  |
| 61-70          | 29        | 18.01%  |
| 51-60          | 10        | 6.21%   |
| 101-110        | 10        | 6.21%   |
| 71-80          | 8         | 4.97%   |
| 201-250        | 5         | 3.11%   |
| 351-500        | 2         | 1.24%   |
| 41-50          | 2         | 1.24%   |
| 1-40           | 2         | 1.24%   |
| 141-150        | 2         | 1.24%   |
| 121-130        | 2         | 1.24%   |
| 301-350        | 1         | 0.62%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 89        | 55.63%  |
| 101-120       | 35        | 21.88%  |
| 161-240       | 18        | 11.25%  |
| 51-100        | 12        | 7.5%    |
| More than 240 | 6         | 3.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 183       | 84.72%  |
| 0     | 23        | 10.65%  |
| 2     | 10        | 4.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 161       | 50%     |
| Realtek Semiconductor             | 71        | 22.05%  |
| Qualcomm Atheros                  | 32        | 9.94%   |
| Broadcom                          | 16        | 4.97%   |
| Marvell Technology Group          | 7         | 2.17%   |
| Ericsson Business Mobile Networks | 5         | 1.55%   |
| Edimax Technology                 | 4         | 1.24%   |
| Qualcomm Atheros Communications   | 3         | 0.93%   |
| Nvidia                            | 3         | 0.93%   |
| Apple                             | 3         | 0.93%   |
| TP-Link                           | 2         | 0.62%   |
| Sierra Wireless                   | 2         | 0.62%   |
| Ralink Technology                 | 2         | 0.62%   |
| Xiaomi                            | 1         | 0.31%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.31%   |
| Samsung Electronics               | 1         | 0.31%   |
| Ralink                            | 1         | 0.31%   |
| Micro Star International          | 1         | 0.31%   |
| Google                            | 1         | 0.31%   |
| Fibocom                           | 1         | 0.31%   |
| Dell                              | 1         | 0.31%   |
| D-Link System                     | 1         | 0.31%   |
| D-Link                            | 1         | 0.31%   |
| 3Com                              | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 52        | 12.01%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 22        | 5.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 19        | 4.39%   |
| Intel Wireless 8265 / 8275                                                  | 16        | 3.7%    |
| Intel Wireless 7265                                                         | 14        | 3.23%   |
| Intel 82567LM Gigabit Network Connection                                    | 13        | 3%      |
| Intel Wireless 7260                                                         | 12        | 2.77%   |
| Intel Wi-Fi 6 AX200                                                         | 11        | 2.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 10        | 2.31%   |
| Intel Wireless 8260                                                         | 9         | 2.08%   |
| Intel Ultimate N WiFi Link 5300                                             | 8         | 1.85%   |
| Intel Ethernet Connection (3) I218-LM                                       | 8         | 1.85%   |
| Intel Ethernet Connection I219-LM                                           | 7         | 1.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 6         | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 6         | 1.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 6         | 1.39%   |
| Intel Centrino Advanced-N 6200                                              | 6         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                                    | 6         | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 5         | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 5         | 1.15%   |
| Intel Ethernet Connection (4) I219-V                                        | 5         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 4         | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 4         | 0.92%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                     | 4         | 0.92%   |
| Intel Wireless-AC 9260                                                      | 4         | 0.92%   |
| Intel Wireless 3165                                                         | 4         | 0.92%   |
| Intel Wi-Fi 6 AX201                                                         | 4         | 0.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 4         | 0.92%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 4         | 0.92%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 4         | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 3         | 0.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 3         | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 3         | 0.69%   |
| Nvidia MCP79 Ethernet                                                       | 3         | 0.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 3         | 0.69%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                   | 3         | 0.69%   |
| Intel Ethernet Connection I218-LM                                           | 3         | 0.69%   |
| Intel Ethernet Connection (6) I219-V                                        | 3         | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                                       | 3         | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                       | 3         | 0.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 3         | 0.69%   |
| Intel Centrino Wireless-N 2230                                              | 3         | 0.69%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                    | 3         | 0.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 3         | 0.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 3         | 0.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                 | 2         | 0.46%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 2         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 2         | 0.46%   |
| Qualcomm Atheros AR9271 802.11n                                             | 2         | 0.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet              | 2         | 0.46%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                       | 2         | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                     | 2         | 0.46%   |
| Intel Wireless 3160                                                         | 2         | 0.46%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection               | 2         | 0.46%   |
| Intel Ethernet Connection I218-V                                            | 2         | 0.46%   |
| Intel Ethernet Connection I217-LM                                           | 2         | 0.46%   |
| Intel Ethernet Connection (3) I218-V                                        | 2         | 0.46%   |
| Intel Ethernet Connection (10) I219-V                                       | 2         | 0.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 151       | 65.94%  |
| Qualcomm Atheros                | 28        | 12.23%  |
| Realtek Semiconductor           | 19        | 8.3%    |
| Broadcom                        | 13        | 5.68%   |
| Edimax Technology               | 4         | 1.75%   |
| Qualcomm Atheros Communications | 3         | 1.31%   |
| TP-Link                         | 2         | 0.87%   |
| Sierra Wireless                 | 2         | 0.87%   |
| Ralink Technology               | 2         | 0.87%   |
| Ralink                          | 1         | 0.44%   |
| Micro Star International        | 1         | 0.44%   |
| Dell                            | 1         | 0.44%   |
| D-Link System                   | 1         | 0.44%   |
| D-Link                          | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 19        | 8.26%   |
| Intel Wireless 8265 / 8275                                                            | 16        | 6.96%   |
| Intel Wireless 7265                                                                   | 14        | 6.09%   |
| Intel Wireless 7260                                                                   | 12        | 5.22%   |
| Intel Wi-Fi 6 AX200                                                                   | 11        | 4.78%   |
| Intel Wireless 8260                                                                   | 9         | 3.91%   |
| Intel Ultimate N WiFi Link 5300                                                       | 8         | 3.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 6         | 2.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 6         | 2.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 6         | 2.61%   |
| Intel Centrino Advanced-N 6200                                                        | 6         | 2.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 5         | 2.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 5         | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 4         | 1.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 1.74%   |
| Intel Wireless-AC 9260                                                                | 4         | 1.74%   |
| Intel Wireless 3165                                                                   | 4         | 1.74%   |
| Intel Wi-Fi 6 AX201                                                                   | 4         | 1.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 4         | 1.74%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                        | 4         | 1.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 3         | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 1.3%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 3         | 1.3%    |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                             | 3         | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 1.3%    |
| Intel Centrino Wireless-N 2230                                                        | 3         | 1.3%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 3         | 1.3%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 3         | 1.3%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                           | 2         | 0.87%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 2         | 0.87%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 0.87%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                                 | 2         | 0.87%   |
| Intel Wireless 3160                                                                   | 2         | 0.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 2         | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 2         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 2         | 0.87%   |
| Intel Centrino Wireless-N 2200                                                        | 2         | 0.87%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                         | 1         | 0.43%   |
| Sierra Wireless EM7455                                                                | 1         | 0.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.43%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 1         | 0.43%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                 | 1         | 0.43%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 0.43%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170]         | 1         | 0.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.43%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.43%   |
| Micro Star International RT2573                                                       | 1         | 0.43%   |
| Intel WiFi Link 5100                                                                  | 1         | 0.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 0.43%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 0.43%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 1         | 0.43%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 1         | 0.43%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 0.43%   |
| Intel Centrino Wireless-N 6150                                                        | 1         | 0.43%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                         | 1         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 92        | 48.68%  |
| Realtek Semiconductor            | 65        | 34.39%  |
| Qualcomm Atheros                 | 8         | 4.23%   |
| Marvell Technology Group         | 7         | 3.7%    |
| Broadcom                         | 7         | 3.7%    |
| Nvidia                           | 3         | 1.59%   |
| Apple                            | 2         | 1.06%   |
| Xiaomi                           | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] | 1         | 0.53%   |
| Samsung Electronics              | 1         | 0.53%   |
| Google                           | 1         | 0.53%   |
| 3Com                             | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 52        | 27.51%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 22        | 11.64%  |
| Intel 82567LM Gigabit Network Connection                             | 13        | 6.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 10        | 5.29%   |
| Intel Ethernet Connection (3) I218-LM                                | 8         | 4.23%   |
| Intel Ethernet Connection I219-LM                                    | 7         | 3.7%    |
| Intel 82577LM Gigabit Network Connection                             | 6         | 3.17%   |
| Intel Ethernet Connection (4) I219-V                                 | 5         | 2.65%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller              | 4         | 2.12%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 3         | 1.59%   |
| Nvidia MCP79 Ethernet                                                | 3         | 1.59%   |
| Intel Ethernet Connection I218-LM                                    | 3         | 1.59%   |
| Intel Ethernet Connection (6) I219-V                                 | 3         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                                | 3         | 1.59%   |
| Intel Ethernet Connection (2) I219-LM                                | 3         | 1.59%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express             | 3         | 1.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 2         | 1.06%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 2         | 1.06%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller              | 2         | 1.06%   |
| Intel Ethernet Connection I218-V                                     | 2         | 1.06%   |
| Intel Ethernet Connection I217-LM                                    | 2         | 1.06%   |
| Intel Ethernet Connection (3) I218-V                                 | 2         | 1.06%   |
| Intel Ethernet Connection (10) I219-V                                | 2         | 1.06%   |
| Intel 82573L Gigabit Ethernet Controller                             | 2         | 1.06%   |
| Intel 82566MM Gigabit Network Connection                             | 2         | 1.06%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                   | 2         | 1.06%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                      | 2         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet            | 1         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller            | 1         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 1         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 1         | 0.53%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller              | 1         | 0.53%   |
| Intel Ethernet Connection I219-V                                     | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                                | 1         | 0.53%   |
| Intel 82801CAM (ICH3) PRO/100 VM (KM) Ethernet Controller            | 1         | 0.53%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller           | 1         | 0.53%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 0.53%   |
| Google Nexus/Pixel Device (charging + debug)                         | 1         | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 1         | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                    | 1         | 0.53%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                  | 1         | 0.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1         | 0.53%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                        | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 208       | 50.86%  |
| Ethernet | 187       | 45.72%  |
| Modem    | 8         | 1.96%   |
| Unknown  | 6         | 1.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 154       | 69.06%  |
| Ethernet | 69        | 30.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 173       | 80.47%  |
| 1     | 38        | 17.67%  |
| 3     | 3         | 1.4%    |
| 0     | 1         | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 214       | 99.53%  |
| Yes  | 1         | 0.47%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 54.69%  |
| Broadcom                        | 22        | 17.19%  |
| Apple                           | 8         | 6.25%   |
| IMC Networks                    | 7         | 5.47%   |
| Alps Electric                   | 7         | 5.47%   |
| Realtek Semiconductor           | 5         | 3.91%   |
| Qualcomm Atheros Communications | 3         | 2.34%   |
| Foxconn / Hon Hai               | 2         | 1.56%   |
| Ralink                          | 1         | 0.78%   |
| Lite-On Technology              | 1         | 0.78%   |
| Creative Technology             | 1         | 0.78%   |
| ASUSTek Computer                | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 38        | 29.69%  |
| Intel AX201 Bluetooth                                                               | 9         | 7.03%   |
| Intel AX200 Bluetooth                                                               | 9         | 7.03%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 7         | 5.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 4.69%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 5         | 3.91%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 5         | 3.91%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 3.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 3.13%   |
| Apple Bluetooth Host Controller                                                     | 4         | 3.13%   |
| Apple Apple Broadcom Built-in Bluetooth                                             | 4         | 3.13%   |
| Realtek  Bluetooth Adapter                                                          | 2         | 1.56%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.56%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                                         | 2         | 1.56%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS                                    | 2         | 1.56%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]                              | 2         | 1.56%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 2         | 1.56%   |
| Realtek  Bluetooth 4.0 Adapter                                                      | 1         | 0.78%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.78%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                                             | 1         | 0.78%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE                                 | 1         | 0.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.78%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.78%   |
| IMC Networks Realtek Bluetooth Adapter                                              | 1         | 0.78%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.78%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device                            | 1         | 0.78%   |
| Creative Creative Bluetooth Audio W2                                                | 1         | 0.78%   |
| Broadcom BCM43142A0 Bluetooth Module                                                | 1         | 0.78%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.78%   |
| Broadcom BCM2046 Bluetooth Device                                                   | 1         | 0.78%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.78%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 182       | 80.18%  |
| AMD                              | 27        | 11.89%  |
| Nvidia                           | 13        | 5.73%   |
| Silicon Integrated Systems [SiS] | 1         | 0.44%   |
| Logitech                         | 1         | 0.44%   |
| Generalplus Technology           | 1         | 0.44%   |
| ESS Technology                   | 1         | 0.44%   |
| C-Media Electronics              | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 29        | 10.28%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 18        | 6.38%   |
| Intel Broadwell-U Audio Controller                                                                | 18        | 6.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 6.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 5.67%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 5.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 15        | 5.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 4.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 3.55%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 3.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 3.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.77%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.42%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.06%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.06%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 1.06%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 3         | 1.06%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.71%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.71%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.71%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 0.71%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.71%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.71%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.71%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.71%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.71%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.71%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.35%   |
| Nvidia unknown                                                                                    | 1         | 0.35%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.35%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Logitech H390 headset with microphone                                                             | 1         | 0.35%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.35%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.35%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.35%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.35%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 0.35%   |
| C-Media Electronics Anua Mic CM 900                                                               | 1         | 0.35%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.35%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 10        | 27.78%  |
| Samsung Electronics | 10        | 27.78%  |
| SK hynix            | 5         | 13.89%  |
| Micron Technology   | 3         | 8.33%   |
| Kingston            | 2         | 5.56%   |
| Elpida              | 2         | 5.56%   |
| Crucial             | 2         | 5.56%   |
| Ramaxel Technology  | 1         | 2.78%   |
| Unknown             | 1         | 2.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 3         | 7.89%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 2         | 5.26%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 5.26%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 2         | 5.26%   |
| Unknown RAM Module 512MB SODIMM SDRAM                   | 1         | 2.63%   |
| Unknown RAM Module 512MB SODIMM DDR                     | 1         | 2.63%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 2.63%   |
| Unknown RAM Module 256MB SODIMM DRAM                    | 1         | 2.63%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s          | 1         | 2.63%   |
| Unknown RAM Module 2048MB SODIMM DDR2                   | 1         | 2.63%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 2.63%   |
| Unknown RAM Module 128MB SODIMM DRAM                    | 1         | 2.63%   |
| Unknown RAM Module 1024MB SODIMM DDR                    | 1         | 2.63%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 2.63%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 1         | 2.63%   |
| SK hynix RAM 484D543332355336 2GB SODIMM DDR3 1333MT/s  | 1         | 2.63%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 1         | 2.63%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s   | 1         | 2.63%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s   | 1         | 2.63%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 2.63%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 2.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1         | 2.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s   | 1         | 2.63%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s  | 1         | 2.63%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s | 1         | 2.63%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s   | 1         | 2.63%   |
| Micron RAM 8JSF12864HZ-1G1F1 1GB SODIMM DDR3 800MT/s    | 1         | 2.63%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s   | 1         | 2.63%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s   | 1         | 2.63%   |
| Kingston RAM 4143523531325836 4GB SODIMM DDR3 1333MT/s  | 1         | 2.63%   |
| Elpida RAM Module 1GB SODIMM DDR2 533MT/s               | 1         | 2.63%   |
| Elpida RAM EDJ4216EFBG-L 2048MB SODIMM DDR3 1600MT/s    | 1         | 2.63%   |
| Unknown                                                 | 1         | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 20        | 64.52%  |
| DDR4  | 3         | 9.68%   |
| DDR2  | 3         | 9.68%   |
| SDRAM | 2         | 6.45%   |
| DRAM  | 2         | 6.45%   |
| DDR   | 1         | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 31        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 13        | 37.14%  |
| 2048  | 8         | 22.86%  |
| 8192  | 4         | 11.43%  |
| 1024  | 4         | 11.43%  |
| 16384 | 2         | 5.71%   |
| 512   | 2         | 5.71%   |
| 256   | 1         | 2.86%   |
| 128   | 1         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 10        | 30.3%   |
| Unknown | 7         | 21.21%  |
| 1333    | 5         | 15.15%  |
| 1334    | 4         | 12.12%  |
| 3200    | 3         | 9.09%   |
| 1067    | 2         | 6.06%   |
| 800     | 1         | 3.03%   |
| 533     | 1         | 3.03%   |

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
| Chicony Electronics                    | 48        | 36.09%  |
| Acer                                   | 18        | 13.53%  |
| IMC Networks                           | 16        | 12.03%  |
| Realtek Semiconductor                  | 9         | 6.77%   |
| Lite-On Technology                     | 7         | 5.26%   |
| Microdia                               | 6         | 4.51%   |
| Syntek                                 | 3         | 2.26%   |
| Suyin                                  | 3         | 2.26%   |
| Sunplus Innovation Technology          | 3         | 2.26%   |
| Quanta                                 | 3         | 2.26%   |
| Alcor Micro                            | 3         | 2.26%   |
| Silicon Motion                         | 2         | 1.5%    |
| Ricoh                                  | 2         | 1.5%    |
| Luxvisions Innotech Limited            | 2         | 1.5%    |
| Lenovo                                 | 2         | 1.5%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.5%    |
| Logitech                               | 1         | 0.75%   |
| Denron                                 | 1         | 0.75%   |
| Apple                                  | 1         | 0.75%   |
| ALi                                    | 1         | 0.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 20        | 14.93%  |
| Lite-On Integrated Camera                                   | 7         | 5.22%   |
| IMC Networks Integrated Camera                              | 7         | 5.22%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 5         | 3.73%   |
| Acer Integrated Camera                                      | 5         | 3.73%   |
| Chicony Integrated Camera [ThinkPad]                        | 4         | 2.99%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 2.24%   |
| Acer EasyCamera                                             | 3         | 2.24%   |
| Syntek Lenovo EasyCamera                                    | 2         | 1.49%   |
| Realtek USB 2 Webcam                                        | 2         | 1.49%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.49%   |
| Microdia Integrated_Webcam_HD                               | 2         | 1.49%   |
| Lenovo Integrated Webcam                                    | 2         | 1.49%   |
| Chicony ThinkPad T490 Webcam                                | 2         | 1.49%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.49%   |
| Chicony HD Webcam                                           | 2         | 1.49%   |
| Chicony FJ Camera                                           | 2         | 1.49%   |
| Acer SunplusIT Integrated Camera                            | 2         | 1.49%   |
| Acer Lenovo EasyCamera                                      | 2         | 1.49%   |
| Syntek EasyCamera                                           | 1         | 0.75%   |
| Suyin Asus Integrated Webcam                                | 1         | 0.75%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 0.75%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.75%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.75%   |
| Sunplus Integrated_Webcam_FHD                               | 1         | 0.75%   |
| Sunplus Dell E5570 integrated webcam                        | 1         | 0.75%   |
| Silicon Motion Web Camera                                   | 1         | 0.75%   |
| Silicon Motion Realtek USB2.0 PC Camera                     | 1         | 0.75%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 0.75%   |
| Ricoh Integrated Webcam                                     | 1         | 0.75%   |
| Realtek USB2.0 HD UVC WebCam                                | 1         | 0.75%   |
| Realtek USB Camera                                          | 1         | 0.75%   |
| Realtek Integrated Webcam                                   | 1         | 0.75%   |
| Realtek EasyCamera                                          | 1         | 0.75%   |
| Realtek Acer 640 x 480 laptop camera                        | 1         | 0.75%   |
| Quanta VGA WebCam                                           | 1         | 0.75%   |
| Quanta HP Webcam-50                                         | 1         | 0.75%   |
| Quanta HP TrueVision HD Camera                              | 1         | 0.75%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 0.75%   |
| Microdia PC Camera (SN9C201 + OV9650)                       | 1         | 0.75%   |
| Microdia Integrated Webcam HD                               | 1         | 0.75%   |
| Microdia Integrated Webcam                                  | 1         | 0.75%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 0.75%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera        | 1         | 0.75%   |
| Logitech BRIO Ultra HD Webcam                               | 1         | 0.75%   |
| IMC Networks VGA UVC WebCam                                 | 1         | 0.75%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 1         | 0.75%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 0.75%   |
| IMC Networks Lenovo EasyCamera                              | 1         | 0.75%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 0.75%   |
| IMC Networks EasyCamera                                     | 1         | 0.75%   |
| Denron Corp., 2M Front Camera                               | 1         | 0.75%   |
| Chicony VGA WebCam                                          | 1         | 0.75%   |
| Chicony USB2.0 0.3M UVC WebCam                              | 1         | 0.75%   |
| Chicony thinkpad t430s camera                               | 1         | 0.75%   |
| Chicony Sonix ST50220 USB Video Camera                      | 1         | 0.75%   |
| Chicony Ltd., VGA Webcam                                    | 1         | 0.75%   |
| Chicony Ltd., USB2.0 HD UVC WebCam                          | 1         | 0.75%   |
| Chicony Ltd., TOSHIBA Web Camera - MP                       | 1         | 0.75%   |
| Chicony Lenovo Integrated Camera UVC                        | 1         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 34%     |
| Upek                       | 9         | 18%     |
| Synaptics                  | 7         | 14%     |
| STMicroelectronics         | 6         | 12%     |
| AuthenTec                  | 6         | 12%     |
| Shenzhen Goodix Technology | 3         | 6%      |
| Samsung Electronics        | 1         | 2%      |
| Elan Microelectronics      | 1         | 2%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 11        | 22%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 9         | 18%     |
| STMicroelectronics Fingerprint Reader                  | 6         | 12%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 3         | 6%      |
| AuthenTec AES2810                                      | 3         | 6%      |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 4%      |
| Validity Sensors Synaptics WBDI                        | 2         | 4%      |
| Synaptics product 0x00be                               | 2         | 4%      |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 4%      |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 4%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2%      |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 2%      |
| Synaptics  WBDI                                        | 1         | 2%      |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2%      |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 2%      |
| Samsung Fingerprint Device                             | 1         | 2%      |
| Elan ELAN WBF Fingerprint Sensor                       | 1         | 2%      |
| AuthenTec AuthenTec Inc. AES2660                       | 1         | 2%      |

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
| 1     | 111       | 50.68%  |
| 2     | 60        | 27.4%   |
| 0     | 21        | 9.59%   |
| 3     | 13        | 5.94%   |
| 4     | 8         | 3.65%   |
| 6     | 2         | 0.91%   |
| 5     | 2         | 0.91%   |
| 8     | 1         | 0.46%   |
| 7     | 1         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 149       | 48.38%  |
| Graphics card            | 57        | 18.51%  |
| Net/wireless             | 37        | 12.01%  |
| Firewire controller      | 27        | 8.77%   |
| Sound                    | 9         | 2.92%   |
| Modem                    | 7         | 2.27%   |
| Network                  | 6         | 1.95%   |
| Storage/ata              | 5         | 1.62%   |
| Net/ethernet             | 4         | 1.3%    |
| Storage/ide              | 2         | 0.65%   |
| Card reader              | 2         | 0.65%   |
| Storage/nvme             | 1         | 0.32%   |
| Storage                  | 1         | 0.32%   |
| Bluetooth                | 1         | 0.32%   |

