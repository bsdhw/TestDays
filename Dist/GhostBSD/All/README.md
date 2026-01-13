GhostBSD - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for GhostBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/GhostBSD/Desktop/README.md) and [notebooks](/Dist/GhostBSD/Notebook/README.md).

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

Total: 672

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude 5520               | Notebook    | [3d736273f2](https://bsd-hardware.info/?probe=3d736273f2) | Jan 03, 2026 |
| Dell          | Latitude 5520               | Notebook    | [cced2f8275](https://bsd-hardware.info/?probe=cced2f8275) | Jan 03, 2026 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [eb83aa2496](https://bsd-hardware.info/?probe=eb83aa2496) | Jan 01, 2026 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [8b6c965d1a](https://bsd-hardware.info/?probe=8b6c965d1a) | Dec 31, 2025 |
| Dell          | Inspiron 7570               | Notebook    | [a2828cbfd3](https://bsd-hardware.info/?probe=a2828cbfd3) | Dec 30, 2025 |
| Dell          | Latitude 7480               | Notebook    | [29771b2eb5](https://bsd-hardware.info/?probe=29771b2eb5) | Dec 28, 2025 |
| HP            | EliteBook Folio 9470m       | Notebook    | [e5cd4a5c15](https://bsd-hardware.info/?probe=e5cd4a5c15) | Dec 28, 2025 |
| ASUSTek       | X550MD                      | Notebook    | [99a920a6c2](https://bsd-hardware.info/?probe=99a920a6c2) | Dec 28, 2025 |
| ASUSTek       | X550MD                      | Notebook    | [02b8060e38](https://bsd-hardware.info/?probe=02b8060e38) | Dec 27, 2025 |
| Lenovo        | ThinkPad P50 20EN0008GE     | Notebook    | [b3d69c9aa9](https://bsd-hardware.info/?probe=b3d69c9aa9) | Dec 25, 2025 |
| Lenovo        | ThinkPad T480 20L6S9UJ0Y    | Notebook    | [6799072e37](https://bsd-hardware.info/?probe=6799072e37) | Dec 21, 2025 |
| Lenovo        | ThinkPad T480 20L6S9UJ0Y    | Notebook    | [e523952624](https://bsd-hardware.info/?probe=e523952624) | Dec 21, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [f83dfc4109](https://bsd-hardware.info/?probe=f83dfc4109) | Dec 21, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [d811e53da8](https://bsd-hardware.info/?probe=d811e53da8) | Dec 21, 2025 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [ffcb3248bd](https://bsd-hardware.info/?probe=ffcb3248bd) | Dec 14, 2025 |
| Dynabook      | TECRA A65-M                 | Notebook    | [840b58a6a7](https://bsd-hardware.info/?probe=840b58a6a7) | Dec 13, 2025 |
| Dell          | Latitude 5410               | Notebook    | [0754c58554](https://bsd-hardware.info/?probe=0754c58554) | Dec 13, 2025 |
| Lenovo        | 36DB SDK0J40709 WIN 3259... | All in one  | [7dcf325338](https://bsd-hardware.info/?probe=7dcf325338) | Dec 09, 2025 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [28e7de1846](https://bsd-hardware.info/?probe=28e7de1846) | Dec 08, 2025 |
| Dell          | Precision 3561              | Notebook    | [54c5a30bf4](https://bsd-hardware.info/?probe=54c5a30bf4) | Dec 08, 2025 |
| Dell          | Precision 3561              | Notebook    | [fcedc4b737](https://bsd-hardware.info/?probe=fcedc4b737) | Dec 08, 2025 |
| Dell          | Latitude 5520               | Notebook    | [a8c5ee2142](https://bsd-hardware.info/?probe=a8c5ee2142) | Dec 08, 2025 |
| Dell          | Latitude 5520               | Notebook    | [05c34d8bb3](https://bsd-hardware.info/?probe=05c34d8bb3) | Dec 08, 2025 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [36459b9771](https://bsd-hardware.info/?probe=36459b9771) | Dec 08, 2025 |
| Dell          | Latitude E5470              | Notebook    | [a7cb7055f2](https://bsd-hardware.info/?probe=a7cb7055f2) | Nov 08, 2025 |
| HP            | 2B29                        | Desktop     | [2ffc0d081c](https://bsd-hardware.info/?probe=2ffc0d081c) | Nov 06, 2025 |
| Acer          | Aspire One 721              | Notebook    | [0eaa05c265](https://bsd-hardware.info/?probe=0eaa05c265) | Nov 04, 2025 |
| Dell          | 0KYWH7 A03                  | Desktop     | [0b80128cad](https://bsd-hardware.info/?probe=0b80128cad) | Oct 31, 2025 |
| OEM           | MCR-A520M-DXV4 V1.0         | Desktop     | [57c7b475bd](https://bsd-hardware.info/?probe=57c7b475bd) | Oct 26, 2025 |
| ASUSTek       | Pro B760M-C                 | Desktop     | [d0b1738757](https://bsd-hardware.info/?probe=d0b1738757) | Oct 26, 2025 |
| HP            | 83E9                        | Desktop     | [46f390df07](https://bsd-hardware.info/?probe=46f390df07) | Oct 12, 2025 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [69314d3cdb](https://bsd-hardware.info/?probe=69314d3cdb) | Oct 12, 2025 |
| Dell          | Inspiron 5559               | Notebook    | [99739a132e](https://bsd-hardware.info/?probe=99739a132e) | Oct 08, 2025 |
| Maibenben     | Perfectum Series            | Notebook    | [e978b41d08](https://bsd-hardware.info/?probe=e978b41d08) | Oct 08, 2025 |
| Maibenben     | Perfectum Series            | Notebook    | [6bc4e3e498](https://bsd-hardware.info/?probe=6bc4e3e498) | Oct 07, 2025 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [eca4ec1a99](https://bsd-hardware.info/?probe=eca4ec1a99) | Sep 30, 2025 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [af8dc3a74c](https://bsd-hardware.info/?probe=af8dc3a74c) | Sep 24, 2025 |
| Apple         | MacBookPro13,3              | Notebook    | [49878f209a](https://bsd-hardware.info/?probe=49878f209a) | Sep 24, 2025 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [2250adb9c8](https://bsd-hardware.info/?probe=2250adb9c8) | Sep 23, 2025 |
| Acer          | Nitro N50-620               | Desktop     | [8aaad76f25](https://bsd-hardware.info/?probe=8aaad76f25) | Sep 18, 2025 |
| HP            | 83E9                        | Desktop     | [2b42999eeb](https://bsd-hardware.info/?probe=2b42999eeb) | Sep 18, 2025 |
| HP            | 8522 A01                    | Mini pc     | [0a78711e50](https://bsd-hardware.info/?probe=0a78711e50) | Sep 18, 2025 |
| Microsoft     | Surface Pro 6               | Tablet      | [929869ed2c](https://bsd-hardware.info/?probe=929869ed2c) | Sep 18, 2025 |
| HP            | EliteBook Folio 9470m       | Notebook    | [4db41bab3d](https://bsd-hardware.info/?probe=4db41bab3d) | Sep 17, 2025 |
| HP            | EliteBook Folio 9470m       | Notebook    | [de941693ae](https://bsd-hardware.info/?probe=de941693ae) | Sep 17, 2025 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [ed24422e1b](https://bsd-hardware.info/?probe=ed24422e1b) | Sep 16, 2025 |
| Lenovo        | ThinkPad T420 4236PGG       | Notebook    | [a29d54028d](https://bsd-hardware.info/?probe=a29d54028d) | Sep 12, 2025 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [be8b97c582](https://bsd-hardware.info/?probe=be8b97c582) | Sep 09, 2025 |
| Gigabyte      | H97M-D3H                    | Desktop     | [572bdf3e93](https://bsd-hardware.info/?probe=572bdf3e93) | Sep 09, 2025 |
| Lenovo        | ThinkPad T580 20LAS1KA00    | Notebook    | [89a15e05f2](https://bsd-hardware.info/?probe=89a15e05f2) | Sep 09, 2025 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [852dacdd82](https://bsd-hardware.info/?probe=852dacdd82) | Sep 08, 2025 |
| Toshiba       | Satellite C800D             | Notebook    | [34b6824adf](https://bsd-hardware.info/?probe=34b6824adf) | Aug 31, 2025 |
| ASUSTek       | PN50-E1                     | Mini pc     | [4b91980131](https://bsd-hardware.info/?probe=4b91980131) | Aug 29, 2025 |
| Acer          | Aspire V5-552               | Notebook    | [4fa113dd6b](https://bsd-hardware.info/?probe=4fa113dd6b) | Aug 28, 2025 |
| Lenovo        | ThinkPad T495 20NKS0VS00    | Notebook    | [d5e5e1f2f8](https://bsd-hardware.info/?probe=d5e5e1f2f8) | Aug 26, 2025 |
| HP            | 81C7 MVB 0C                 | Server      | [57de780c36](https://bsd-hardware.info/?probe=57de780c36) | Aug 07, 2025 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [ba04eb8570](https://bsd-hardware.info/?probe=ba04eb8570) | Aug 05, 2025 |
| Lenovo        | ThinkPad T430 2347H76       | Notebook    | [84bb1f6dc9](https://bsd-hardware.info/?probe=84bb1f6dc9) | Aug 02, 2025 |
| Lenovo        | G550 2958                   | Notebook    | [7c91a69398](https://bsd-hardware.info/?probe=7c91a69398) | Jul 19, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [afc0b4763b](https://bsd-hardware.info/?probe=afc0b4763b) | Jul 12, 2025 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [5890b3ef81](https://bsd-hardware.info/?probe=5890b3ef81) | Jul 08, 2025 |
| TongFang      | GX4HRXL                     | Notebook    | [62273ded61](https://bsd-hardware.info/?probe=62273ded61) | Jul 07, 2025 |
| HP            | Pavilion 15                 | Notebook    | [752aebbc02](https://bsd-hardware.info/?probe=752aebbc02) | Jul 06, 2025 |
| TongFang      | GX4HRXL                     | Notebook    | [b54a0dfd0b](https://bsd-hardware.info/?probe=b54a0dfd0b) | Jul 04, 2025 |
| Lenovo        | ThinkPad E450 20DDA01N00    | Notebook    | [1b5cdf08d1](https://bsd-hardware.info/?probe=1b5cdf08d1) | Jul 03, 2025 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [358f4cfd1b](https://bsd-hardware.info/?probe=358f4cfd1b) | Jun 28, 2025 |
| XtReAmEr      | Unknown                     | Desktop     | [89994ef7a1](https://bsd-hardware.info/?probe=89994ef7a1) | Jun 24, 2025 |
| ASRock        | B550 Steel Legend           | Desktop     | [ee9f85800e](https://bsd-hardware.info/?probe=ee9f85800e) | Jun 12, 2025 |
| Lenovo        | ThinkPad X140e 20BLS0030... | Notebook    | [91a25e5e00](https://bsd-hardware.info/?probe=91a25e5e00) | Jun 11, 2025 |
| Lenovo        | ThinkPad T480 20L6S01Q0L    | Notebook    | [dec1fd17c7](https://bsd-hardware.info/?probe=dec1fd17c7) | May 30, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [90aebce5fd](https://bsd-hardware.info/?probe=90aebce5fd) | May 30, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [90d94c1634](https://bsd-hardware.info/?probe=90d94c1634) | May 30, 2025 |
| Lenovo        | ThinkPad L460 20FVS09Y00    | Notebook    | [c2a9872e05](https://bsd-hardware.info/?probe=c2a9872e05) | May 21, 2025 |
| HP            | 805D                        | Desktop     | [438daf2f8c](https://bsd-hardware.info/?probe=438daf2f8c) | May 19, 2025 |
| Gigabyte      | MRHM5AP                     | Desktop     | [32f0e5d317](https://bsd-hardware.info/?probe=32f0e5d317) | May 18, 2025 |
| Lenovo        | Edge 2-1580 80QF            | Notebook    | [1149223c0f](https://bsd-hardware.info/?probe=1149223c0f) | May 18, 2025 |
| Supermicro    | H13SAE-MF                   | Desktop     | [5c5c221640](https://bsd-hardware.info/?probe=5c5c221640) | Apr 30, 2025 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [ec1b01599f](https://bsd-hardware.info/?probe=ec1b01599f) | Apr 29, 2025 |
| Acer          | Aspire A715-72G             | Notebook    | [732e17bbc7](https://bsd-hardware.info/?probe=732e17bbc7) | Apr 27, 2025 |
| ASUSTek       | K54C                        | Notebook    | [edee4fc655](https://bsd-hardware.info/?probe=edee4fc655) | Apr 27, 2025 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [f000d65830](https://bsd-hardware.info/?probe=f000d65830) | Apr 17, 2025 |
| Lenovo        | ThinkPad T410s 2912WAV      | Notebook    | [a95acc5b5c](https://bsd-hardware.info/?probe=a95acc5b5c) | Apr 13, 2025 |
| Acer          | Aspire S3-391               | Notebook    | [a7147a8af2](https://bsd-hardware.info/?probe=a7147a8af2) | Apr 09, 2025 |
| Acer          | Aspire A715-72G             | Notebook    | [b96f13784f](https://bsd-hardware.info/?probe=b96f13784f) | Apr 03, 2025 |
| Lenovo        | ThinkPad X140e 20BLS0030... | Notebook    | [09033922c5](https://bsd-hardware.info/?probe=09033922c5) | Mar 31, 2025 |
| Intel(R) C... | NUC7i5BNK                   | Mini pc     | [2a2e2d3351](https://bsd-hardware.info/?probe=2a2e2d3351) | Mar 29, 2025 |
| Intel(R) C... | NUC7i5BNK                   | Mini pc     | [8b3f1ab26f](https://bsd-hardware.info/?probe=8b3f1ab26f) | Mar 29, 2025 |
| Dell          | XPS 13 9360                 | Notebook    | [31f9120390](https://bsd-hardware.info/?probe=31f9120390) | Mar 28, 2025 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [38343a4b77](https://bsd-hardware.info/?probe=38343a4b77) | Mar 27, 2025 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [57351b1d8a](https://bsd-hardware.info/?probe=57351b1d8a) | Mar 26, 2025 |
| Medion        | H81H3-EM2                   | Desktop     | [f7dd5b559d](https://bsd-hardware.info/?probe=f7dd5b559d) | Mar 25, 2025 |
| Lenovo        | ThinkPad E14 Gen 6 21M3C... | Notebook    | [c97f313465](https://bsd-hardware.info/?probe=c97f313465) | Mar 25, 2025 |
| HP            | 2B3C                        | Desktop     | [418c3c1366](https://bsd-hardware.info/?probe=418c3c1366) | Mar 22, 2025 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [cc3cc39541](https://bsd-hardware.info/?probe=cc3cc39541) | Mar 21, 2025 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [e0f8f84272](https://bsd-hardware.info/?probe=e0f8f84272) | Mar 14, 2025 |
| Medion        | B660H7-M20                  | Desktop     | [f508283941](https://bsd-hardware.info/?probe=f508283941) | Mar 12, 2025 |
| AZW           | EQ                          | Desktop     | [a1a5b7a8f1](https://bsd-hardware.info/?probe=a1a5b7a8f1) | Mar 12, 2025 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | Desktop     | [44e1c528f4](https://bsd-hardware.info/?probe=44e1c528f4) | Mar 10, 2025 |
| HP            | EliteBook 820 G2            | Notebook    | [0e727af2b4](https://bsd-hardware.info/?probe=0e727af2b4) | Mar 10, 2025 |
| HP            | 81C5 MVB                    | Desktop     | [01ab4c29b9](https://bsd-hardware.info/?probe=01ab4c29b9) | Mar 09, 2025 |
| Dell          | 0VNP2H A00                  | Desktop     | [3f99cc7239](https://bsd-hardware.info/?probe=3f99cc7239) | Mar 07, 2025 |
| Lenovo        | ThinkPad W550s 20E2000QU... | Notebook    | [8e2f33a68c](https://bsd-hardware.info/?probe=8e2f33a68c) | Mar 07, 2025 |
| Lenovo        | ThinkPad W550s 20E2000QU... | Notebook    | [0243819ad2](https://bsd-hardware.info/?probe=0243819ad2) | Mar 07, 2025 |
| HUAWEI        | MACHR-WX9                   | Notebook    | [b5535a2385](https://bsd-hardware.info/?probe=b5535a2385) | Mar 05, 2025 |
| HP            | EliteBook 820 G2            | Notebook    | [ed0e3bf954](https://bsd-hardware.info/?probe=ed0e3bf954) | Mar 05, 2025 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [cac24c9711](https://bsd-hardware.info/?probe=cac24c9711) | Mar 05, 2025 |
| Lenovo        | ThinkPad T530 2394AG9       | Notebook    | [5c28f10554](https://bsd-hardware.info/?probe=5c28f10554) | Mar 04, 2025 |
| Apple         | Mac-F2268CC8                | All in one  | [11ae530edd](https://bsd-hardware.info/?probe=11ae530edd) | Mar 03, 2025 |
| Medion        | B660H7-M20                  | Desktop     | [f5c4614e12](https://bsd-hardware.info/?probe=f5c4614e12) | Mar 03, 2025 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [84a91bc1c5](https://bsd-hardware.info/?probe=84a91bc1c5) | Mar 03, 2025 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [391ed13764](https://bsd-hardware.info/?probe=391ed13764) | Feb 27, 2025 |
| Dell          | Vostro 15 3510              | Notebook    | [d47e0cff38](https://bsd-hardware.info/?probe=d47e0cff38) | Feb 25, 2025 |
| Toshiba       | Satellite L50-C             | Notebook    | [9d0d1b266c](https://bsd-hardware.info/?probe=9d0d1b266c) | Feb 20, 2025 |
| HP            | ProBook 4310s               | Notebook    | [134569627f](https://bsd-hardware.info/?probe=134569627f) | Feb 20, 2025 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [63f8afbf57](https://bsd-hardware.info/?probe=63f8afbf57) | Feb 16, 2025 |
| HP            | Dev One Notebook PC         | Notebook    | [8d9ec6acdb](https://bsd-hardware.info/?probe=8d9ec6acdb) | Feb 15, 2025 |
| Dell          | 0Y5DDC A00                  | Desktop     | [960fc0ef21](https://bsd-hardware.info/?probe=960fc0ef21) | Feb 11, 2025 |
| Apple         | MacBookPro11,2              | Notebook    | [3e1c40aa06](https://bsd-hardware.info/?probe=3e1c40aa06) | Feb 06, 2025 |
| Acer          | TravelMate P648-G3-M        | Notebook    | [a36092b332](https://bsd-hardware.info/?probe=a36092b332) | Feb 04, 2025 |
| Pegatron      | 2ACB                        | Desktop     | [f4368ec81a](https://bsd-hardware.info/?probe=f4368ec81a) | Jan 21, 2025 |
| Lenovo        | ThinkPad Edge E531 68855... | Notebook    | [abbd058fa0](https://bsd-hardware.info/?probe=abbd058fa0) | Jan 21, 2025 |
| Dell          | 0200DY A02                  | Desktop     | [a0adaade37](https://bsd-hardware.info/?probe=a0adaade37) | Jan 21, 2025 |
| Dell          | 0Y5DDC A00                  | Desktop     | [1915fdf658](https://bsd-hardware.info/?probe=1915fdf658) | Jan 21, 2025 |
| Apple         | Mac-F2218FC8                | All in one  | [9360814d92](https://bsd-hardware.info/?probe=9360814d92) | Jan 21, 2025 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [2b452affdf](https://bsd-hardware.info/?probe=2b452affdf) | Jan 21, 2025 |
| HP            | 21B4 A01                    | Desktop     | [7acfb028cc](https://bsd-hardware.info/?probe=7acfb028cc) | Jan 21, 2025 |
| Dell          | 0200DY A02                  | Desktop     | [45b61fed84](https://bsd-hardware.info/?probe=45b61fed84) | Jan 21, 2025 |
| HP            | 81C6 MVB 0C                 | Server      | [1252c14377](https://bsd-hardware.info/?probe=1252c14377) | Jan 21, 2025 |
| Lenovo        | ThinkPad L380 20M6S2FU00    | Notebook    | [8cb99e3fe8](https://bsd-hardware.info/?probe=8cb99e3fe8) | Jan 20, 2025 |
| Apple         | Mac-F2218FC8                | All in one  | [59133e3bb7](https://bsd-hardware.info/?probe=59133e3bb7) | Jan 20, 2025 |
| Lenovo        | CRESCENTBAY SDK0J40700 W... | Desktop     | [63f70042ff](https://bsd-hardware.info/?probe=63f70042ff) | Jan 16, 2025 |
| Gigabyte      | A520M DS3H V2               | Desktop     | [aafeff8a9e](https://bsd-hardware.info/?probe=aafeff8a9e) | Jan 15, 2025 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [2ca6604184](https://bsd-hardware.info/?probe=2ca6604184) | Jan 15, 2025 |
| Supermicro    | C7H170-M                    | Server      | [3e8c16380f](https://bsd-hardware.info/?probe=3e8c16380f) | Jan 09, 2025 |
| Lenovo        | ThinkPad T490 20N3S4PX00    | Notebook    | [4954bab835](https://bsd-hardware.info/?probe=4954bab835) | Jan 07, 2025 |
| Dell          | Inspiron 3476               | Notebook    | [3dc38e6815](https://bsd-hardware.info/?probe=3dc38e6815) | Jan 03, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c6697164fc](https://bsd-hardware.info/?probe=c6697164fc) | Jan 02, 2025 |
| HUAWEI        | KPL-W0X                     | Notebook    | [51514fe0c0](https://bsd-hardware.info/?probe=51514fe0c0) | Dec 28, 2024 |
| HUAWEI        | KPL-W0X                     | Notebook    | [7d9a498768](https://bsd-hardware.info/?probe=7d9a498768) | Dec 28, 2024 |
| ASUSTek       | NUC12WSB-M 60AS00F0-MB5A... | Mini pc     | [a7565e386d](https://bsd-hardware.info/?probe=a7565e386d) | Dec 26, 2024 |
| Lenovo        | ThinkPad T430 2342CTO       | Notebook    | [10ab9145d9](https://bsd-hardware.info/?probe=10ab9145d9) | Dec 24, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [e0ed997df8](https://bsd-hardware.info/?probe=e0ed997df8) | Dec 23, 2024 |
| Dell          | XPS 9320                    | Notebook    | [659b5961cc](https://bsd-hardware.info/?probe=659b5961cc) | Dec 23, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [aa6a6969b9](https://bsd-hardware.info/?probe=aa6a6969b9) | Dec 12, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cfc56b5602](https://bsd-hardware.info/?probe=cfc56b5602) | Dec 11, 2024 |
| HP            | 250 G3                      | Notebook    | [102fa9b597](https://bsd-hardware.info/?probe=102fa9b597) | Dec 04, 2024 |
| MSI           | Z490-A PRO                  | Desktop     | [50ca527f2b](https://bsd-hardware.info/?probe=50ca527f2b) | Dec 01, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [7a03bbeb04](https://bsd-hardware.info/?probe=7a03bbeb04) | Nov 25, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [36ab98d9df](https://bsd-hardware.info/?probe=36ab98d9df) | Nov 25, 2024 |
| Dell          | Latitude E5440              | Notebook    | [289f3c134f](https://bsd-hardware.info/?probe=289f3c134f) | Nov 24, 2024 |
| Samsung       | 530XBB                      | Notebook    | [9d6127f039](https://bsd-hardware.info/?probe=9d6127f039) | Nov 18, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | Notebook    | [ab3ba2edf5](https://bsd-hardware.info/?probe=ab3ba2edf5) | Nov 18, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | Notebook    | [2a9c5b1e5c](https://bsd-hardware.info/?probe=2a9c5b1e5c) | Nov 18, 2024 |
| Notebook      | NL40_50CU                   | Notebook    | [9b197cd6fc](https://bsd-hardware.info/?probe=9b197cd6fc) | Nov 18, 2024 |
| Notebook      | NL40_50CU                   | Notebook    | [88b9892dd2](https://bsd-hardware.info/?probe=88b9892dd2) | Nov 18, 2024 |
| Toshiba       | Satellite L655              | Notebook    | [dc1b79d2f5](https://bsd-hardware.info/?probe=dc1b79d2f5) | Nov 13, 2024 |
| Toshiba       | Satellite L655              | Notebook    | [8a36444ca1](https://bsd-hardware.info/?probe=8a36444ca1) | Nov 13, 2024 |
| MSI           | B450-A PRO MAX              | Desktop     | [265f542246](https://bsd-hardware.info/?probe=265f542246) | Nov 12, 2024 |
| Apple         | Mac-F2218EA9                | All in one  | [0d18fbeaf8](https://bsd-hardware.info/?probe=0d18fbeaf8) | Nov 07, 2024 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [aa3a0567b3](https://bsd-hardware.info/?probe=aa3a0567b3) | Nov 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3eedf19995](https://bsd-hardware.info/?probe=3eedf19995) | Oct 30, 2024 |
| HP            | 3397                        | Desktop     | [ddf2d83456](https://bsd-hardware.info/?probe=ddf2d83456) | Oct 27, 2024 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [a6ccceed97](https://bsd-hardware.info/?probe=a6ccceed97) | Oct 24, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [4a1456a0fa](https://bsd-hardware.info/?probe=4a1456a0fa) | Oct 22, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [5ac0371f28](https://bsd-hardware.info/?probe=5ac0371f28) | Oct 18, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [553b42ed1a](https://bsd-hardware.info/?probe=553b42ed1a) | Oct 18, 2024 |
| Dell          | Inspiron 13-7368            | Notebook    | [2dc255b034](https://bsd-hardware.info/?probe=2dc255b034) | Oct 17, 2024 |
| HP            | Unknown                     | Notebook    | [254f5a847c](https://bsd-hardware.info/?probe=254f5a847c) | Oct 17, 2024 |
| Dell          | XPS 13 7390                 | Notebook    | [425f5093f7](https://bsd-hardware.info/?probe=425f5093f7) | Oct 13, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [29ab309c41](https://bsd-hardware.info/?probe=29ab309c41) | Oct 12, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [1b0b42530b](https://bsd-hardware.info/?probe=1b0b42530b) | Oct 11, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [1c29a0f0a3](https://bsd-hardware.info/?probe=1c29a0f0a3) | Oct 11, 2024 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [f009e46a16](https://bsd-hardware.info/?probe=f009e46a16) | Oct 09, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1b5dcf47fe](https://bsd-hardware.info/?probe=1b5dcf47fe) | Oct 07, 2024 |
| Notebook      | NL40_50CU                   | Notebook    | [680cd09351](https://bsd-hardware.info/?probe=680cd09351) | Oct 06, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [869d37ac5e](https://bsd-hardware.info/?probe=869d37ac5e) | Oct 04, 2024 |
| Biostar       | B450MHP                     | Desktop     | [af6e8cf307](https://bsd-hardware.info/?probe=af6e8cf307) | Sep 29, 2024 |
| Dell          | G3 3579                     | Notebook    | [1725db4da9](https://bsd-hardware.info/?probe=1725db4da9) | Sep 27, 2024 |
| Notebook      | NL40_50CU                   | Notebook    | [95fbcd46d1](https://bsd-hardware.info/?probe=95fbcd46d1) | Sep 26, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [8836aa08ec](https://bsd-hardware.info/?probe=8836aa08ec) | Sep 23, 2024 |
| Dell          | Vostro 5490                 | Notebook    | [32de340e28](https://bsd-hardware.info/?probe=32de340e28) | Sep 23, 2024 |
| ASUSTek       | PN50                        | Mini pc     | [213143884b](https://bsd-hardware.info/?probe=213143884b) | Sep 21, 2024 |
| Dell          | Latitude E6540              | Notebook    | [14fbf15794](https://bsd-hardware.info/?probe=14fbf15794) | Sep 13, 2024 |
| MSI           | MS-B1061                    | All in one  | [0c456f4cd7](https://bsd-hardware.info/?probe=0c456f4cd7) | Sep 13, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [c6c35c6a96](https://bsd-hardware.info/?probe=c6c35c6a96) | Sep 05, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [cd17d71b66](https://bsd-hardware.info/?probe=cd17d71b66) | Sep 05, 2024 |
| HP            | 18E7                        | Desktop     | [7bdd288f75](https://bsd-hardware.info/?probe=7bdd288f75) | Sep 03, 2024 |
| Lenovo        | ThinkCentre M715q 10M2S0... | Desktop     | [66a3b3e94e](https://bsd-hardware.info/?probe=66a3b3e94e) | Sep 02, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [ce0404f7c9](https://bsd-hardware.info/?probe=ce0404f7c9) | Aug 31, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [aedfdb1704](https://bsd-hardware.info/?probe=aedfdb1704) | Aug 22, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [a0abac7ab7](https://bsd-hardware.info/?probe=a0abac7ab7) | Aug 21, 2024 |
| Fujitsu       | LIFEBOOK U727               | Notebook    | [d3eb2cd128](https://bsd-hardware.info/?probe=d3eb2cd128) | Aug 14, 2024 |
| HP            | Pavilion 17                 | Notebook    | [ae76b7e522](https://bsd-hardware.info/?probe=ae76b7e522) | Aug 10, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [9ae98f134a](https://bsd-hardware.info/?probe=9ae98f134a) | Aug 09, 2024 |
| ASUSTek       | EX-H110M-V                  | Desktop     | [9f18579edf](https://bsd-hardware.info/?probe=9f18579edf) | Aug 05, 2024 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [7f3e4230e3](https://bsd-hardware.info/?probe=7f3e4230e3) | Aug 05, 2024 |
| ASRock        | X300M-STX                   | Desktop     | [50dd5072a2](https://bsd-hardware.info/?probe=50dd5072a2) | Aug 04, 2024 |
| ASUSTek       | M4A88T-M                    | Desktop     | [133cfcbe40](https://bsd-hardware.info/?probe=133cfcbe40) | Jul 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [3d93b160f7](https://bsd-hardware.info/?probe=3d93b160f7) | Jul 25, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [b671ec6c8d](https://bsd-hardware.info/?probe=b671ec6c8d) | Jul 21, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [388efa9ea9](https://bsd-hardware.info/?probe=388efa9ea9) | Jul 18, 2024 |
| HP            | Compaq Presario CQ71        | Notebook    | [88a0868c03](https://bsd-hardware.info/?probe=88a0868c03) | Jul 18, 2024 |
| Biostar       | B450MH                      | Desktop     | [425858d6af](https://bsd-hardware.info/?probe=425858d6af) | Jul 18, 2024 |
| ASRock        | J3455-ITX                   | Desktop     | [3b31af23f2](https://bsd-hardware.info/?probe=3b31af23f2) | Jul 05, 2024 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [a82831432b](https://bsd-hardware.info/?probe=a82831432b) | Jun 25, 2024 |
| Biostar       | A68N-5200                   | Desktop     | [9299915b62](https://bsd-hardware.info/?probe=9299915b62) | Jun 20, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [2ccb52d7b5](https://bsd-hardware.info/?probe=2ccb52d7b5) | Jun 11, 2024 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [5b53bd70e9](https://bsd-hardware.info/?probe=5b53bd70e9) | Jun 08, 2024 |
| MSI           | H110M PRO-D                 | Desktop     | [3f2aaa6b19](https://bsd-hardware.info/?probe=3f2aaa6b19) | May 29, 2024 |
| ASUSTek       | UX410UAR                    | Notebook    | [263af3de44](https://bsd-hardware.info/?probe=263af3de44) | May 23, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [e123332fb8](https://bsd-hardware.info/?probe=e123332fb8) | May 16, 2024 |
| Dell          | 055H3G A01                  | Desktop     | [5d0cd53384](https://bsd-hardware.info/?probe=5d0cd53384) | May 16, 2024 |
| Biostar       | B450MH                      | Desktop     | [6fc7467762](https://bsd-hardware.info/?probe=6fc7467762) | May 13, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [d5f43a27aa](https://bsd-hardware.info/?probe=d5f43a27aa) | May 12, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [3c3432b2c0](https://bsd-hardware.info/?probe=3c3432b2c0) | May 11, 2024 |
| Infinix       | INBook X1                   | Notebook    | [847a9cb112](https://bsd-hardware.info/?probe=847a9cb112) | May 10, 2024 |
| Acer          | TravelMate B118-M           | Notebook    | [68d9d26fe5](https://bsd-hardware.info/?probe=68d9d26fe5) | May 09, 2024 |
| Alienware     | Area-51m A00                | Notebook    | [53d5d4eb1e](https://bsd-hardware.info/?probe=53d5d4eb1e) | May 07, 2024 |
| Unknown       | X133                        | Notebook    | [524b7e6d8e](https://bsd-hardware.info/?probe=524b7e6d8e) | May 07, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [c9ad91fc61](https://bsd-hardware.info/?probe=c9ad91fc61) | May 07, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [79c4a2608c](https://bsd-hardware.info/?probe=79c4a2608c) | May 07, 2024 |
| Gigabyte      | P55-USB3                    | Desktop     | [9024f0074b](https://bsd-hardware.info/?probe=9024f0074b) | May 07, 2024 |
| Lenovo        | ThinkPad X240 20AMS3FY00    | Notebook    | [1dc74d60e6](https://bsd-hardware.info/?probe=1dc74d60e6) | May 06, 2024 |
| Dell          | Latitude 7390               | Notebook    | [b9b511f4d6](https://bsd-hardware.info/?probe=b9b511f4d6) | May 04, 2024 |
| MSI           | B360M BAZOOKA               | Desktop     | [d33325e752](https://bsd-hardware.info/?probe=d33325e752) | May 02, 2024 |
| MSI           | GE75 Raider 10SFS           | Notebook    | [cda74e2f91](https://bsd-hardware.info/?probe=cda74e2f91) | May 02, 2024 |
| ASUSTek       | X202E                       | Notebook    | [0ed385a36d](https://bsd-hardware.info/?probe=0ed385a36d) | May 02, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [4878c18c8a](https://bsd-hardware.info/?probe=4878c18c8a) | May 01, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [26185f189e](https://bsd-hardware.info/?probe=26185f189e) | Apr 30, 2024 |
| HP            | EliteBook 2560p             | Notebook    | [bb6303ed5b](https://bsd-hardware.info/?probe=bb6303ed5b) | Apr 29, 2024 |
| Lenovo        | ThinkPad X220 429135G       | Notebook    | [b681d0b406](https://bsd-hardware.info/?probe=b681d0b406) | Apr 23, 2024 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [150e135ba6](https://bsd-hardware.info/?probe=150e135ba6) | Apr 18, 2024 |
| Dell          | Latitude 7490               | Notebook    | [38f6023f20](https://bsd-hardware.info/?probe=38f6023f20) | Apr 14, 2024 |
| Dell          | Vostro 3350                 | Notebook    | [abe739e6c2](https://bsd-hardware.info/?probe=abe739e6c2) | Apr 13, 2024 |
| HP            | ProBook 645 G3              | Notebook    | [ea10ac1f83](https://bsd-hardware.info/?probe=ea10ac1f83) | Apr 12, 2024 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [15c55873cd](https://bsd-hardware.info/?probe=15c55873cd) | Apr 09, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a2cbe8253b](https://bsd-hardware.info/?probe=a2cbe8253b) | Apr 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a26013b913](https://bsd-hardware.info/?probe=a26013b913) | Apr 05, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3ccdd0084b](https://bsd-hardware.info/?probe=3ccdd0084b) | Apr 05, 2024 |
| Dell          | Latitude E5540              | Notebook    | [108e2acb98](https://bsd-hardware.info/?probe=108e2acb98) | Apr 01, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [56ea2c6719](https://bsd-hardware.info/?probe=56ea2c6719) | Apr 01, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [cfcf823cca](https://bsd-hardware.info/?probe=cfcf823cca) | Apr 01, 2024 |
| HUAWEI        | PUM-WDX9-PCB-B1 M1010       | Desktop     | [4a359f1f86](https://bsd-hardware.info/?probe=4a359f1f86) | Apr 01, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [0ae72ec0ff](https://bsd-hardware.info/?probe=0ae72ec0ff) | Mar 31, 2024 |
| Lenovo        | 3743 NOK                    | Desktop     | [fd5dc51da2](https://bsd-hardware.info/?probe=fd5dc51da2) | Mar 31, 2024 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [f4dde6ddf5](https://bsd-hardware.info/?probe=f4dde6ddf5) | Mar 22, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [db1d3cd098](https://bsd-hardware.info/?probe=db1d3cd098) | Mar 19, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [403a4f0ea9](https://bsd-hardware.info/?probe=403a4f0ea9) | Mar 17, 2024 |
| Google        | Cave                        | Notebook    | [d9df48c781](https://bsd-hardware.info/?probe=d9df48c781) | Mar 16, 2024 |
| ASUSTek       | H61M-K                      | Desktop     | [1f6840c3f3](https://bsd-hardware.info/?probe=1f6840c3f3) | Mar 12, 2024 |
| LG Electro... | R590-P.BE54P1               | Desktop     | [120ec3afe6](https://bsd-hardware.info/?probe=120ec3afe6) | Mar 09, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [7cc4588e07](https://bsd-hardware.info/?probe=7cc4588e07) | Mar 07, 2024 |
| HP            | Notebook                    | Notebook    | [15839305ee](https://bsd-hardware.info/?probe=15839305ee) | Mar 01, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [ac72a9a34a](https://bsd-hardware.info/?probe=ac72a9a34a) | Feb 23, 2024 |
| Dell          | Latitude E6540              | Notebook    | [92ba9b26e1](https://bsd-hardware.info/?probe=92ba9b26e1) | Feb 21, 2024 |
| Dell          | 0H634K A00                  | Desktop     | [5392dc85bb](https://bsd-hardware.info/?probe=5392dc85bb) | Feb 21, 2024 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [39e4fb5eba](https://bsd-hardware.info/?probe=39e4fb5eba) | Feb 20, 2024 |
| Dell          | 0H634K A00                  | Desktop     | [e933816d9f](https://bsd-hardware.info/?probe=e933816d9f) | Feb 19, 2024 |
| Biostar       | B450NH                      | Desktop     | [2db279db1d](https://bsd-hardware.info/?probe=2db279db1d) | Feb 16, 2024 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [fdeb2cee9d](https://bsd-hardware.info/?probe=fdeb2cee9d) | Feb 14, 2024 |
| Shenzhen M... | F6BFC                       | Desktop     | [ca7e1f0fae](https://bsd-hardware.info/?probe=ca7e1f0fae) | Feb 12, 2024 |
| Dell          | 0H634K A00                  | Desktop     | [a39d975ae9](https://bsd-hardware.info/?probe=a39d975ae9) | Feb 11, 2024 |
| Dell          | Latitude 7490               | Notebook    | [32828d5d84](https://bsd-hardware.info/?probe=32828d5d84) | Feb 10, 2024 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | Desktop     | [37d30255bc](https://bsd-hardware.info/?probe=37d30255bc) | Feb 06, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [0e644c21cc](https://bsd-hardware.info/?probe=0e644c21cc) | Feb 02, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [4768e0001d](https://bsd-hardware.info/?probe=4768e0001d) | Feb 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [e747b9066e](https://bsd-hardware.info/?probe=e747b9066e) | Jan 29, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [7e24e6c0f2](https://bsd-hardware.info/?probe=7e24e6c0f2) | Jan 29, 2024 |
| Dell          | 0GDJXY A00                  | All in one  | [c7f489add0](https://bsd-hardware.info/?probe=c7f489add0) | Jan 28, 2024 |
| ASUSTek       | X555LAB                     | Notebook    | [c396fcc8d9](https://bsd-hardware.info/?probe=c396fcc8d9) | Jan 22, 2024 |
| MSI           | Z370-A PRO                  | Desktop     | [2b442ae151](https://bsd-hardware.info/?probe=2b442ae151) | Jan 20, 2024 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ebd5d3e03f](https://bsd-hardware.info/?probe=ebd5d3e03f) | Jan 19, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [d08f6339ae](https://bsd-hardware.info/?probe=d08f6339ae) | Jan 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [2ab7b9d6b2](https://bsd-hardware.info/?probe=2ab7b9d6b2) | Jan 02, 2024 |
| Casper        | NIRVANA DESKTOP             | Desktop     | [926ae04d23](https://bsd-hardware.info/?probe=926ae04d23) | Dec 31, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [c915c03729](https://bsd-hardware.info/?probe=c915c03729) | Dec 30, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [fa4e90491b](https://bsd-hardware.info/?probe=fa4e90491b) | Dec 29, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [1c769a311c](https://bsd-hardware.info/?probe=1c769a311c) | Dec 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | Notebook    | [b6c3c05155](https://bsd-hardware.info/?probe=b6c3c05155) | Dec 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | Notebook    | [32c06c5669](https://bsd-hardware.info/?probe=32c06c5669) | Dec 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [851f118bd5](https://bsd-hardware.info/?probe=851f118bd5) | Dec 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [5281bb9e20](https://bsd-hardware.info/?probe=5281bb9e20) | Dec 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d81a233601](https://bsd-hardware.info/?probe=d81a233601) | Dec 12, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [09f5b25e72](https://bsd-hardware.info/?probe=09f5b25e72) | Dec 12, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [0fe56565dc](https://bsd-hardware.info/?probe=0fe56565dc) | Dec 09, 2023 |
| ASRock        | 990FX Extreme3              | Desktop     | [6ac792ecf6](https://bsd-hardware.info/?probe=6ac792ecf6) | Dec 05, 2023 |
| Dell          | Latitude E6330              | Notebook    | [7e0a01e9ad](https://bsd-hardware.info/?probe=7e0a01e9ad) | Dec 05, 2023 |
| Dell          | Inspiron 7558               | Notebook    | [b34a8742d5](https://bsd-hardware.info/?probe=b34a8742d5) | Nov 26, 2023 |
| Dell          | Inspiron 7558               | Notebook    | [aad8d359f3](https://bsd-hardware.info/?probe=aad8d359f3) | Nov 24, 2023 |
| Dell          | Latitude E5440              | Notebook    | [629fba28cc](https://bsd-hardware.info/?probe=629fba28cc) | Nov 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [19dfa9e36a](https://bsd-hardware.info/?probe=19dfa9e36a) | Nov 21, 2023 |
| Dell          | Precision 5520              | Notebook    | [45f5e399a4](https://bsd-hardware.info/?probe=45f5e399a4) | Nov 18, 2023 |
| HP            | Notebook                    | Notebook    | [c583c221c7](https://bsd-hardware.info/?probe=c583c221c7) | Nov 17, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [b34836b090](https://bsd-hardware.info/?probe=b34836b090) | Nov 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0fd2711a56](https://bsd-hardware.info/?probe=0fd2711a56) | Nov 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d87ea88953](https://bsd-hardware.info/?probe=d87ea88953) | Nov 09, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [05bf5fb9f4](https://bsd-hardware.info/?probe=05bf5fb9f4) | Nov 07, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [19514dd0bd](https://bsd-hardware.info/?probe=19514dd0bd) | Nov 03, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [965e71ac80](https://bsd-hardware.info/?probe=965e71ac80) | Oct 21, 2023 |
| Dell          | Latitude 5490               | Notebook    | [eeab525ffd](https://bsd-hardware.info/?probe=eeab525ffd) | Oct 20, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [f927cf5ba4](https://bsd-hardware.info/?probe=f927cf5ba4) | Oct 16, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [72a9b731f6](https://bsd-hardware.info/?probe=72a9b731f6) | Oct 14, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [36daf066ca](https://bsd-hardware.info/?probe=36daf066ca) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | Notebook    | [ac6742bd0f](https://bsd-hardware.info/?probe=ac6742bd0f) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | Notebook    | [3e15173331](https://bsd-hardware.info/?probe=3e15173331) | Oct 07, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [dffb96790c](https://bsd-hardware.info/?probe=dffb96790c) | Oct 06, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [39fbf2c8dc](https://bsd-hardware.info/?probe=39fbf2c8dc) | Oct 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [070c5dab4f](https://bsd-hardware.info/?probe=070c5dab4f) | Oct 02, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [6b58792f5e](https://bsd-hardware.info/?probe=6b58792f5e) | Oct 02, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [6427b9defc](https://bsd-hardware.info/?probe=6427b9defc) | Oct 02, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [dffc2e116d](https://bsd-hardware.info/?probe=dffc2e116d) | Sep 30, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [b0aca42c84](https://bsd-hardware.info/?probe=b0aca42c84) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [68b8b9f531](https://bsd-hardware.info/?probe=68b8b9f531) | Sep 29, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [b31f8c12f8](https://bsd-hardware.info/?probe=b31f8c12f8) | Sep 24, 2023 |
| ASRock        | H670M-ITX/ax                | Desktop     | [1b6996f127](https://bsd-hardware.info/?probe=1b6996f127) | Sep 17, 2023 |
| Lenovo        | ThinkPad T470 20HES0HU00    | Notebook    | [a64fe205a9](https://bsd-hardware.info/?probe=a64fe205a9) | Sep 17, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [0f92b89ffb](https://bsd-hardware.info/?probe=0f92b89ffb) | Sep 09, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [9e555f0b24](https://bsd-hardware.info/?probe=9e555f0b24) | Aug 24, 2023 |
| Dell          | Latitude 7490               | Notebook    | [0b05de2297](https://bsd-hardware.info/?probe=0b05de2297) | Aug 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [26995b5321](https://bsd-hardware.info/?probe=26995b5321) | Aug 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1bc7f67754](https://bsd-hardware.info/?probe=1bc7f67754) | Aug 18, 2023 |
| Mini PC       | Rev JSL5 DDR4               | Mini pc     | [af1a82a2d6](https://bsd-hardware.info/?probe=af1a82a2d6) | Aug 14, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [9d53e56e92](https://bsd-hardware.info/?probe=9d53e56e92) | Aug 13, 2023 |
| Samsung       | Q210                        | Notebook    | [2e25c6d2ec](https://bsd-hardware.info/?probe=2e25c6d2ec) | Aug 03, 2023 |
| Samsung       | Q210                        | Notebook    | [d3c5ab902d](https://bsd-hardware.info/?probe=d3c5ab902d) | Aug 03, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [9c0c41b663](https://bsd-hardware.info/?probe=9c0c41b663) | Jul 30, 2023 |
| Dell          | Inspiron 3180               | Notebook    | [e97b5d9219](https://bsd-hardware.info/?probe=e97b5d9219) | Jul 25, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [020e17c2f8](https://bsd-hardware.info/?probe=020e17c2f8) | Jul 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [efe49f9e5d](https://bsd-hardware.info/?probe=efe49f9e5d) | Jul 20, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [67080aeb1d](https://bsd-hardware.info/?probe=67080aeb1d) | Jul 20, 2023 |
| MSI           | Sword 17 A11UD              | Notebook    | [c9852c1ee3](https://bsd-hardware.info/?probe=c9852c1ee3) | Jul 19, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | Notebook    | [57b4bfc1bf](https://bsd-hardware.info/?probe=57b4bfc1bf) | Jul 17, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [826ba238d8](https://bsd-hardware.info/?probe=826ba238d8) | Jul 16, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [0273f2f271](https://bsd-hardware.info/?probe=0273f2f271) | Jul 16, 2023 |
| Intel         | HM570                       | Desktop     | [4e0fd42418](https://bsd-hardware.info/?probe=4e0fd42418) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [03e83e60ca](https://bsd-hardware.info/?probe=03e83e60ca) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [3096d8532a](https://bsd-hardware.info/?probe=3096d8532a) | Jul 07, 2023 |
| Dell          | G3 3579                     | Notebook    | [8d9b29f231](https://bsd-hardware.info/?probe=8d9b29f231) | Jul 05, 2023 |
| Dell          | G3 3579                     | Notebook    | [f6fc15b1f4](https://bsd-hardware.info/?probe=f6fc15b1f4) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e212a51c70](https://bsd-hardware.info/?probe=e212a51c70) | Jul 03, 2023 |
| HP            | 15                          | Notebook    | [4664b4c93f](https://bsd-hardware.info/?probe=4664b4c93f) | Jun 11, 2023 |
| Dell          | Inspiron 3180               | Notebook    | [cb769078b4](https://bsd-hardware.info/?probe=cb769078b4) | Jun 10, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [8bedc249ea](https://bsd-hardware.info/?probe=8bedc249ea) | Jun 10, 2023 |
| Dell          | Inspiron 7548               | Notebook    | [c80bb80e8f](https://bsd-hardware.info/?probe=c80bb80e8f) | Jun 10, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [fe5f99c4b0](https://bsd-hardware.info/?probe=fe5f99c4b0) | Jun 06, 2023 |
| Soyo          | SY-YL B550M                 | Desktop     | [1d1138e3c5](https://bsd-hardware.info/?probe=1d1138e3c5) | Jun 05, 2023 |
| Soyo          | SY-YL B550M                 | Desktop     | [79c6c2a177](https://bsd-hardware.info/?probe=79c6c2a177) | Jun 05, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [330c08c388](https://bsd-hardware.info/?probe=330c08c388) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [53cf3cea13](https://bsd-hardware.info/?probe=53cf3cea13) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [23cad3f06e](https://bsd-hardware.info/?probe=23cad3f06e) | May 28, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [c39ea00de5](https://bsd-hardware.info/?probe=c39ea00de5) | May 25, 2023 |
| Dell          | 0M9KCM A02                  | Desktop     | [932e96060f](https://bsd-hardware.info/?probe=932e96060f) | May 21, 2023 |
| HP            | ProBook 455 G3              | Notebook    | [b6a6c91115](https://bsd-hardware.info/?probe=b6a6c91115) | May 21, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0S300     | Notebook    | [44d30cfcf6](https://bsd-hardware.info/?probe=44d30cfcf6) | May 21, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [dca662fc41](https://bsd-hardware.info/?probe=dca662fc41) | May 16, 2023 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | Desktop     | [a3df9cd649](https://bsd-hardware.info/?probe=a3df9cd649) | May 14, 2023 |
| MSI           | GE62 6QC                    | Notebook    | [7c3fd3c9ca](https://bsd-hardware.info/?probe=7c3fd3c9ca) | May 08, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [95695f78c5](https://bsd-hardware.info/?probe=95695f78c5) | May 08, 2023 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [262110252b](https://bsd-hardware.info/?probe=262110252b) | Apr 17, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [773b28fbc7](https://bsd-hardware.info/?probe=773b28fbc7) | Apr 16, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [692b42afcd](https://bsd-hardware.info/?probe=692b42afcd) | Apr 08, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [4f4f6e06d7](https://bsd-hardware.info/?probe=4f4f6e06d7) | Mar 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [2a50573c9f](https://bsd-hardware.info/?probe=2a50573c9f) | Mar 29, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | Notebook    | [b960dc3bde](https://bsd-hardware.info/?probe=b960dc3bde) | Mar 25, 2023 |
| MouseCompu... | X5-aR5CEZAR-WA              | Notebook    | [4cd1097c65](https://bsd-hardware.info/?probe=4cd1097c65) | Mar 24, 2023 |
| MSI           | X299 PRO                    | Desktop     | [a26d096ecb](https://bsd-hardware.info/?probe=a26d096ecb) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [705ac0b37f](https://bsd-hardware.info/?probe=705ac0b37f) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [dcab531d1e](https://bsd-hardware.info/?probe=dcab531d1e) | Mar 18, 2023 |
| Lenovo        | SHARKBAY SDK0K17763 WIN ... | Desktop     | [c9279ce424](https://bsd-hardware.info/?probe=c9279ce424) | Mar 13, 2023 |
| Star Labs     | StarBook                    | Notebook    | [80f6445f54](https://bsd-hardware.info/?probe=80f6445f54) | Mar 10, 2023 |
| MSI           | X299 PRO                    | Desktop     | [0cebc094ca](https://bsd-hardware.info/?probe=0cebc094ca) | Mar 10, 2023 |
| Fujitsu       | FMVA532BSJ                  | Notebook    | [695e38d0ea](https://bsd-hardware.info/?probe=695e38d0ea) | Mar 10, 2023 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [37e1562772](https://bsd-hardware.info/?probe=37e1562772) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349S31       | Notebook    | [2b13f68cd6](https://bsd-hardware.info/?probe=2b13f68cd6) | Feb 28, 2023 |
| MSI           | X299 PRO                    | Desktop     | [3ca12f88d9](https://bsd-hardware.info/?probe=3ca12f88d9) | Feb 24, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [7d7fa2bbc9](https://bsd-hardware.info/?probe=7d7fa2bbc9) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS3320G    | Notebook    | [c85f94d574](https://bsd-hardware.info/?probe=c85f94d574) | Feb 19, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [9a0c17560f](https://bsd-hardware.info/?probe=9a0c17560f) | Feb 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [b42e3649a3](https://bsd-hardware.info/?probe=b42e3649a3) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a9928bd16e](https://bsd-hardware.info/?probe=a9928bd16e) | Feb 10, 2023 |
| HP            | 650                         | Notebook    | [48099613ec](https://bsd-hardware.info/?probe=48099613ec) | Feb 05, 2023 |
| Lenovo        | ThinkPad P50 20EN0008GE     | Notebook    | [8cb09e34ec](https://bsd-hardware.info/?probe=8cb09e34ec) | Feb 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e6ad419f5e](https://bsd-hardware.info/?probe=e6ad419f5e) | Jan 20, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [fa42e2faf7](https://bsd-hardware.info/?probe=fa42e2faf7) | Jan 20, 2023 |
| MSI           | X299 PRO                    | Desktop     | [a1f37f69d9](https://bsd-hardware.info/?probe=a1f37f69d9) | Jan 08, 2023 |
| HP            | 18E7                        | Desktop     | [0b962b9400](https://bsd-hardware.info/?probe=0b962b9400) | Dec 20, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [32207ea5d9](https://bsd-hardware.info/?probe=32207ea5d9) | Dec 19, 2022 |
| MSI           | X299 PRO                    | Desktop     | [beec8001a1](https://bsd-hardware.info/?probe=beec8001a1) | Dec 17, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [3a9623cfb4](https://bsd-hardware.info/?probe=3a9623cfb4) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [0314add226](https://bsd-hardware.info/?probe=0314add226) | Dec 16, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [9551c57fc3](https://bsd-hardware.info/?probe=9551c57fc3) | Dec 14, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d8d6af9e56](https://bsd-hardware.info/?probe=d8d6af9e56) | Dec 10, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [920a2fe2e9](https://bsd-hardware.info/?probe=920a2fe2e9) | Nov 30, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [9618eb0cbe](https://bsd-hardware.info/?probe=9618eb0cbe) | Nov 29, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [39ece5deaf](https://bsd-hardware.info/?probe=39ece5deaf) | Nov 27, 2022 |
| MSI           | X299 PRO                    | Desktop     | [d615157be7](https://bsd-hardware.info/?probe=d615157be7) | Nov 16, 2022 |
| Acer          | Aspire 5251                 | Notebook    | [c9eb0051ed](https://bsd-hardware.info/?probe=c9eb0051ed) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [45316a9769](https://bsd-hardware.info/?probe=45316a9769) | Nov 07, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Dell          | Latitude 5591               | Notebook    | [40957fa567](https://bsd-hardware.info/?probe=40957fa567) | Oct 31, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [51ec4ce710](https://bsd-hardware.info/?probe=51ec4ce710) | Oct 24, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [3d62c50607](https://bsd-hardware.info/?probe=3d62c50607) | Oct 20, 2022 |
| Dell          | Latitude 5591               | Notebook    | [04f53f51c8](https://bsd-hardware.info/?probe=04f53f51c8) | Oct 12, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [6674bbf7f3](https://bsd-hardware.info/?probe=6674bbf7f3) | Oct 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [a773a82ff4](https://bsd-hardware.info/?probe=a773a82ff4) | Oct 11, 2022 |
| Dell          | Latitude 5591               | Notebook    | [eda94b6c48](https://bsd-hardware.info/?probe=eda94b6c48) | Oct 11, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [8ad31cc470](https://bsd-hardware.info/?probe=8ad31cc470) | Sep 29, 2022 |
| Dell          | XPS M1330                   | Notebook    | [d84548dd9b](https://bsd-hardware.info/?probe=d84548dd9b) | Sep 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [4f31f81571](https://bsd-hardware.info/?probe=4f31f81571) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [fc259fcf3e](https://bsd-hardware.info/?probe=fc259fcf3e) | Aug 30, 2022 |
| HP            | Unknown                     | Notebook    | [7bd69ee984](https://bsd-hardware.info/?probe=7bd69ee984) | Aug 29, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0d7d7288c0](https://bsd-hardware.info/?probe=0d7d7288c0) | Aug 27, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0a90c3c566](https://bsd-hardware.info/?probe=0a90c3c566) | Aug 27, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [692e2f0837](https://bsd-hardware.info/?probe=692e2f0837) | Aug 20, 2022 |
| Lenovo        | ThinkPad 11e 4th Gen 20H... | Notebook    | [ba1ea734b1](https://bsd-hardware.info/?probe=ba1ea734b1) | Aug 19, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [c9bda4b49d](https://bsd-hardware.info/?probe=c9bda4b49d) | Aug 14, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [e1a29d8008](https://bsd-hardware.info/?probe=e1a29d8008) | Aug 14, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [cdc6bc6ef8](https://bsd-hardware.info/?probe=cdc6bc6ef8) | Aug 03, 2022 |
| Acer          | Aspire E5-521G              | Notebook    | [dcc5d3116f](https://bsd-hardware.info/?probe=dcc5d3116f) | Jul 29, 2022 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [3df3bd2f62](https://bsd-hardware.info/?probe=3df3bd2f62) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [52cc45aba9](https://bsd-hardware.info/?probe=52cc45aba9) | Jul 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [3182740b56](https://bsd-hardware.info/?probe=3182740b56) | Jul 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [15c5d9fdd9](https://bsd-hardware.info/?probe=15c5d9fdd9) | Jul 17, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [ead2595782](https://bsd-hardware.info/?probe=ead2595782) | Jul 17, 2022 |
| MSI           | B85M-E45                    | Desktop     | [80f2d74d1a](https://bsd-hardware.info/?probe=80f2d74d1a) | Jul 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9771cb16c0](https://bsd-hardware.info/?probe=9771cb16c0) | Jul 15, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3ee4c986b4](https://bsd-hardware.info/?probe=3ee4c986b4) | Jul 15, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [d9efb0425b](https://bsd-hardware.info/?probe=d9efb0425b) | Jul 15, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [6e85a064f0](https://bsd-hardware.info/?probe=6e85a064f0) | Jul 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1e8b0433e8](https://bsd-hardware.info/?probe=1e8b0433e8) | Jul 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [85a49cb7be](https://bsd-hardware.info/?probe=85a49cb7be) | Jul 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b09ba0c799](https://bsd-hardware.info/?probe=b09ba0c799) | Jul 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4c74cdfb76](https://bsd-hardware.info/?probe=4c74cdfb76) | Jul 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [6edc61f549](https://bsd-hardware.info/?probe=6edc61f549) | Jul 10, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0434c94fad](https://bsd-hardware.info/?probe=0434c94fad) | Jul 09, 2022 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [866724656a](https://bsd-hardware.info/?probe=866724656a) | Jul 06, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [5d668f86de](https://bsd-hardware.info/?probe=5d668f86de) | Jul 06, 2022 |
| Star Labs     | LabTop                      | Notebook    | [390c4c4d55](https://bsd-hardware.info/?probe=390c4c4d55) | Jul 03, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [3c2e2da462](https://bsd-hardware.info/?probe=3c2e2da462) | Jul 02, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [b870cd3698](https://bsd-hardware.info/?probe=b870cd3698) | Jul 01, 2022 |
| System76      | Gazelle                     | Notebook    | [7e2dbb0a5b](https://bsd-hardware.info/?probe=7e2dbb0a5b) | Jun 28, 2022 |
| System76      | Gazelle                     | Notebook    | [8cb2a30786](https://bsd-hardware.info/?probe=8cb2a30786) | Jun 28, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [bb3de13b1a](https://bsd-hardware.info/?probe=bb3de13b1a) | Jun 23, 2022 |
| ASUSTek       | X202E                       | Notebook    | [bdbe613858](https://bsd-hardware.info/?probe=bdbe613858) | Jun 22, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [a03ff6ad9e](https://bsd-hardware.info/?probe=a03ff6ad9e) | Jun 10, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [03cb6c6c7f](https://bsd-hardware.info/?probe=03cb6c6c7f) | Jun 09, 2022 |
| Dell          | Latitude 7490               | Notebook    | [22224f46f4](https://bsd-hardware.info/?probe=22224f46f4) | Jun 02, 2022 |
| Dell          | 0M3F6C A01                  | Desktop     | [21d45bc75d](https://bsd-hardware.info/?probe=21d45bc75d) | May 23, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e9524e612d](https://bsd-hardware.info/?probe=e9524e612d) | May 22, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [115de395dd](https://bsd-hardware.info/?probe=115de395dd) | May 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [d2334d7be3](https://bsd-hardware.info/?probe=d2334d7be3) | May 14, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [6dce802641](https://bsd-hardware.info/?probe=6dce802641) | May 10, 2022 |
| Gigabyte      | AX370-Gaming 3-CF           | Desktop     | [62ab2bc823](https://bsd-hardware.info/?probe=62ab2bc823) | May 07, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0d5b872ec1](https://bsd-hardware.info/?probe=0d5b872ec1) | May 02, 2022 |
| Dell          | Latitude 7490               | Notebook    | [03c97fe4d9](https://bsd-hardware.info/?probe=03c97fe4d9) | May 02, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [3f170bdee6](https://bsd-hardware.info/?probe=3f170bdee6) | May 01, 2022 |
| Dell          | Precision 7730              | Notebook    | [bdb3e3d4ce](https://bsd-hardware.info/?probe=bdb3e3d4ce) | Apr 30, 2022 |
| Dell          | Latitude 7490               | Notebook    | [1586880dd7](https://bsd-hardware.info/?probe=1586880dd7) | Apr 30, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [ece6d63cfb](https://bsd-hardware.info/?probe=ece6d63cfb) | Apr 25, 2022 |
| Dell          | Latitude E5450              | Notebook    | [ca5eb083f9](https://bsd-hardware.info/?probe=ca5eb083f9) | Apr 16, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [4023d86091](https://bsd-hardware.info/?probe=4023d86091) | Apr 15, 2022 |
| Dell          | 0Y56T3 A00                  | Desktop     | [d9d86d5bfd](https://bsd-hardware.info/?probe=d9d86d5bfd) | Apr 12, 2022 |
| Notebook      | N13xWU                      | Notebook    | [8986953acd](https://bsd-hardware.info/?probe=8986953acd) | Mar 22, 2022 |
| Notebook      | N7x0WU                      | Notebook    | [b80f84aef1](https://bsd-hardware.info/?probe=b80f84aef1) | Mar 22, 2022 |
| Notebook      | N8xEJEK                     | Notebook    | [9a62677ea8](https://bsd-hardware.info/?probe=9a62677ea8) | Mar 22, 2022 |
| Lenovo        | ThinkPad Yoga 460 20ELS1... | Convertible | [c216d655ae](https://bsd-hardware.info/?probe=c216d655ae) | Mar 22, 2022 |
| Dell          | Latitude E6500              | Notebook    | [5fad69bbf0](https://bsd-hardware.info/?probe=5fad69bbf0) | Mar 22, 2022 |
| Dell          | Latitude E6510              | Notebook    | [a040a1a04b](https://bsd-hardware.info/?probe=a040a1a04b) | Mar 22, 2022 |
| Dell          | Latitude E6530              | Notebook    | [9bc5fc70a7](https://bsd-hardware.info/?probe=9bc5fc70a7) | Mar 22, 2022 |
| MSI           | B250 PC MATE                | Desktop     | [612b0f0a34](https://bsd-hardware.info/?probe=612b0f0a34) | Mar 19, 2022 |
| Lenovo        | ThinkPad X201 32492EU       | Notebook    | [4a5ba4f3e4](https://bsd-hardware.info/?probe=4a5ba4f3e4) | Mar 13, 2022 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [8307275b2e](https://bsd-hardware.info/?probe=8307275b2e) | Mar 07, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [589f10057f](https://bsd-hardware.info/?probe=589f10057f) | Mar 01, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [e14fd85d4a](https://bsd-hardware.info/?probe=e14fd85d4a) | Feb 27, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | Notebook    | [bc2860431e](https://bsd-hardware.info/?probe=bc2860431e) | Feb 17, 2022 |
| Jumper        | EZbook                      | Notebook    | [35869ff0db](https://bsd-hardware.info/?probe=35869ff0db) | Feb 14, 2022 |
| Lenovo        | G500s 20245                 | Notebook    | [41f9f804ac](https://bsd-hardware.info/?probe=41f9f804ac) | Feb 04, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [0b290f2ac3](https://bsd-hardware.info/?probe=0b290f2ac3) | Feb 02, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [84d7fb3f1e](https://bsd-hardware.info/?probe=84d7fb3f1e) | Jan 30, 2022 |
| MSI           | GE75 Raider 10SFS           | Notebook    | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [5b9c617dc8](https://bsd-hardware.info/?probe=5b9c617dc8) | Jan 22, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [6d580e8270](https://bsd-hardware.info/?probe=6d580e8270) | Jan 21, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [52f4bdd7d0](https://bsd-hardware.info/?probe=52f4bdd7d0) | Jan 21, 2022 |
| Supermicro    | X10DRiB                     | Server      | [b4999ca89f](https://bsd-hardware.info/?probe=b4999ca89f) | Jan 21, 2022 |
| Dell          | 0NNNCT A01                  | Desktop     | [290f10c785](https://bsd-hardware.info/?probe=290f10c785) | Jan 21, 2022 |
| Dell          | Latitude E6540              | Notebook    | [f13972c935](https://bsd-hardware.info/?probe=f13972c935) | Jan 21, 2022 |
| Fujitsu       | CELSIUS H780                | Notebook    | [a173366c78](https://bsd-hardware.info/?probe=a173366c78) | Jan 21, 2022 |
| Jumper        | EZbook                      | Notebook    | [7d648bcdc7](https://bsd-hardware.info/?probe=7d648bcdc7) | Jan 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cf360a6098](https://bsd-hardware.info/?probe=cf360a6098) | Jan 16, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [d76873c5dd](https://bsd-hardware.info/?probe=d76873c5dd) | Jan 16, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [a6d7796cea](https://bsd-hardware.info/?probe=a6d7796cea) | Jan 13, 2022 |
| Dell          | Latitude 5510               | Notebook    | [a620d284cb](https://bsd-hardware.info/?probe=a620d284cb) | Jan 12, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [19be37f181](https://bsd-hardware.info/?probe=19be37f181) | Jan 09, 2022 |
| Dell          | Latitude E5450              | Notebook    | [c2ef231757](https://bsd-hardware.info/?probe=c2ef231757) | Jan 04, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [3ada7b4079](https://bsd-hardware.info/?probe=3ada7b4079) | Jan 03, 2022 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [259b5cc7b2](https://bsd-hardware.info/?probe=259b5cc7b2) | Dec 28, 2021 |
| Intel         | NUC7JYB J67970-400          | Mini pc     | [82c010f13c](https://bsd-hardware.info/?probe=82c010f13c) | Dec 09, 2021 |
| Alienware     | 01NYPT A00                  | Desktop     | [75aa0c00fb](https://bsd-hardware.info/?probe=75aa0c00fb) | Dec 06, 2021 |
| ASUSTek       | X202E                       | Notebook    | [7f4e6f4541](https://bsd-hardware.info/?probe=7f4e6f4541) | Dec 05, 2021 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [c501c5c75e](https://bsd-hardware.info/?probe=c501c5c75e) | Dec 04, 2021 |
| Samsung       | 530XBB                      | Notebook    | [41d5f95889](https://bsd-hardware.info/?probe=41d5f95889) | Dec 03, 2021 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [a2270b6f09](https://bsd-hardware.info/?probe=a2270b6f09) | Dec 02, 2021 |
| Alienware     | m15 R4                      | Notebook    | [a724a7d7c7](https://bsd-hardware.info/?probe=a724a7d7c7) | Nov 29, 2021 |
| Lenovo        | ThinkPad T520 4243E51       | Notebook    | [82f5612822](https://bsd-hardware.info/?probe=82f5612822) | Nov 29, 2021 |
| Sony          | SVP13225SCBI                | Notebook    | [03ef84679c](https://bsd-hardware.info/?probe=03ef84679c) | Nov 27, 2021 |
| Dell          | Latitude 5510               | Notebook    | [3da78c9445](https://bsd-hardware.info/?probe=3da78c9445) | Nov 24, 2021 |
| Acer          | TravelMate B117-M           | Notebook    | [4f02660d9c](https://bsd-hardware.info/?probe=4f02660d9c) | Nov 14, 2021 |
| Toshiba       | Satellite C855-1U4          | Notebook    | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Medion        | MS-7728                     | Desktop     | [5b5a847fdd](https://bsd-hardware.info/?probe=5b5a847fdd) | Nov 02, 2021 |
| Dell          | Latitude D630               | Notebook    | [7e3a92badc](https://bsd-hardware.info/?probe=7e3a92badc) | Nov 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [d23636abb2](https://bsd-hardware.info/?probe=d23636abb2) | Oct 31, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [69fe175fb8](https://bsd-hardware.info/?probe=69fe175fb8) | Oct 30, 2021 |
| HP            | Pavilion g6                 | Notebook    | [9754bc2e72](https://bsd-hardware.info/?probe=9754bc2e72) | Oct 27, 2021 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [9cf5948654](https://bsd-hardware.info/?probe=9cf5948654) | Oct 13, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [84838cd532](https://bsd-hardware.info/?probe=84838cd532) | Oct 07, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [db33045561](https://bsd-hardware.info/?probe=db33045561) | Oct 07, 2021 |
| Acer          | Aspire A315-56              | Notebook    | [03ca802f4b](https://bsd-hardware.info/?probe=03ca802f4b) | Oct 02, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [277d8118da](https://bsd-hardware.info/?probe=277d8118da) | Sep 30, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [76ea6529ac](https://bsd-hardware.info/?probe=76ea6529ac) | Sep 26, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [103ccaf452](https://bsd-hardware.info/?probe=103ccaf452) | Sep 25, 2021 |
| Lenovo        | ThinkPad X220 4290W42       | Notebook    | [8be5183e21](https://bsd-hardware.info/?probe=8be5183e21) | Sep 25, 2021 |
| Lenovo        | ThinkPad T500 2056Y2Z       | Notebook    | [88b86ecf8b](https://bsd-hardware.info/?probe=88b86ecf8b) | Sep 25, 2021 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [8f00f132de](https://bsd-hardware.info/?probe=8f00f132de) | Sep 23, 2021 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [bd5b726e52](https://bsd-hardware.info/?probe=bd5b726e52) | Sep 19, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [2a54a0c338](https://bsd-hardware.info/?probe=2a54a0c338) | Sep 14, 2021 |
| Lenovo        | ThinkPad T400 6474E18       | Notebook    | [2dd5b5869f](https://bsd-hardware.info/?probe=2dd5b5869f) | Sep 13, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [27f01061f2](https://bsd-hardware.info/?probe=27f01061f2) | Sep 12, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9dc50c0bcb](https://bsd-hardware.info/?probe=9dc50c0bcb) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | Notebook    | [ecd69774c0](https://bsd-hardware.info/?probe=ecd69774c0) | Sep 06, 2021 |
| System76      | Kudu                        | Notebook    | [c10fc12e40](https://bsd-hardware.info/?probe=c10fc12e40) | Sep 05, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [0ee3fe080c](https://bsd-hardware.info/?probe=0ee3fe080c) | Aug 30, 2021 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [d60f1bc575](https://bsd-hardware.info/?probe=d60f1bc575) | Aug 29, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [31b995146e](https://bsd-hardware.info/?probe=31b995146e) | Aug 25, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [2bc72bf29e](https://bsd-hardware.info/?probe=2bc72bf29e) | Aug 23, 2021 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [6f89733e13](https://bsd-hardware.info/?probe=6f89733e13) | Aug 16, 2021 |
| MSI           | H81M-P33                    | Desktop     | [6dcb3aa559](https://bsd-hardware.info/?probe=6dcb3aa559) | Aug 05, 2021 |
| Dell          | Latitude E5440              | Notebook    | [3f2e8586a7](https://bsd-hardware.info/?probe=3f2e8586a7) | Aug 05, 2021 |
| Dell          | Latitude E6430              | Notebook    | [4149fa5ec3](https://bsd-hardware.info/?probe=4149fa5ec3) | Aug 04, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [9fe86991b5](https://bsd-hardware.info/?probe=9fe86991b5) | Aug 04, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [011fb96fe0](https://bsd-hardware.info/?probe=011fb96fe0) | Aug 04, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [7364ae3b3d](https://bsd-hardware.info/?probe=7364ae3b3d) | Aug 04, 2021 |
| ASRock        | Z77 Extreme6                | Desktop     | [2521c70747](https://bsd-hardware.info/?probe=2521c70747) | Aug 02, 2021 |
| Lenovo        | ThinkPad L512 44444XG       | Notebook    | [a6c8fbcb20](https://bsd-hardware.info/?probe=a6c8fbcb20) | Aug 01, 2021 |
| GPU Compan... | GWTN156-5                   | Notebook    | [bc44d767cc](https://bsd-hardware.info/?probe=bc44d767cc) | Jul 22, 2021 |
| Dell          | Latitude E5520              | Notebook    | [e0dd26220f](https://bsd-hardware.info/?probe=e0dd26220f) | Jul 21, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [1e54d2fbdf](https://bsd-hardware.info/?probe=1e54d2fbdf) | Jul 05, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [f5d7a16498](https://bsd-hardware.info/?probe=f5d7a16498) | Jul 05, 2021 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [bde8057846](https://bsd-hardware.info/?probe=bde8057846) | Jun 29, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [668bf95221](https://bsd-hardware.info/?probe=668bf95221) | Jun 25, 2021 |
| Dell          | Latitude E6420              | Notebook    | [2e8b431cc6](https://bsd-hardware.info/?probe=2e8b431cc6) | Jun 25, 2021 |
| Lenovo        | ThinkPad T440 20B7S1860W    | Notebook    | [8552205176](https://bsd-hardware.info/?probe=8552205176) | Jun 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9f82e215c3](https://bsd-hardware.info/?probe=9f82e215c3) | Jun 22, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [a2deab0991](https://bsd-hardware.info/?probe=a2deab0991) | Jun 15, 2021 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [10d9e99990](https://bsd-hardware.info/?probe=10d9e99990) | May 31, 2021 |
| Sony          | SVP1322M1EBI                | Notebook    | [23316d0f2b](https://bsd-hardware.info/?probe=23316d0f2b) | May 29, 2021 |
| Lenovo        | Board                       | Desktop     | [428f39cbff](https://bsd-hardware.info/?probe=428f39cbff) | May 21, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [e27342ab94](https://bsd-hardware.info/?probe=e27342ab94) | May 13, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | Notebook    | [11fe52be5e](https://bsd-hardware.info/?probe=11fe52be5e) | May 13, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [7634d3b6ca](https://bsd-hardware.info/?probe=7634d3b6ca) | May 12, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [f2e42a5ca3](https://bsd-hardware.info/?probe=f2e42a5ca3) | May 10, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [0af6399c18](https://bsd-hardware.info/?probe=0af6399c18) | May 10, 2021 |
| Lenovo        | ThinkPad T430 2344C4U       | Notebook    | [0f001f65d2](https://bsd-hardware.info/?probe=0f001f65d2) | Apr 27, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [f8389b0546](https://bsd-hardware.info/?probe=f8389b0546) | Apr 24, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Dell          | 0TP412                      | Desktop     | [1bc05b5951](https://bsd-hardware.info/?probe=1bc05b5951) | Apr 04, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e4e3731289](https://bsd-hardware.info/?probe=e4e3731289) | Apr 01, 2021 |
| Acer          | Aspire E5-521G              | Notebook    | [e2b6dbfe40](https://bsd-hardware.info/?probe=e2b6dbfe40) | Apr 01, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [ec9e43382e](https://bsd-hardware.info/?probe=ec9e43382e) | Mar 25, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [3e500c12a3](https://bsd-hardware.info/?probe=3e500c12a3) | Mar 24, 2021 |
| HP            | 1850                        | Desktop     | [3055c06d45](https://bsd-hardware.info/?probe=3055c06d45) | Mar 22, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [a64a4e0792](https://bsd-hardware.info/?probe=a64a4e0792) | Mar 19, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | Notebook    | [196cd8a730](https://bsd-hardware.info/?probe=196cd8a730) | Mar 11, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [240171b234](https://bsd-hardware.info/?probe=240171b234) | Mar 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9ede3128c5](https://bsd-hardware.info/?probe=9ede3128c5) | Mar 07, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [39a46ce44e](https://bsd-hardware.info/?probe=39a46ce44e) | Mar 06, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b1ee3da46f](https://bsd-hardware.info/?probe=b1ee3da46f) | Mar 06, 2021 |
| Gigabyte      | EG43M-S2H                   | Desktop     | [f6eaa55ada](https://bsd-hardware.info/?probe=f6eaa55ada) | Mar 06, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [50ac436475](https://bsd-hardware.info/?probe=50ac436475) | Mar 06, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f27578615f](https://bsd-hardware.info/?probe=f27578615f) | Mar 05, 2021 |
| Acer          | Aspire XC-115               | Desktop     | [95f63df64d](https://bsd-hardware.info/?probe=95f63df64d) | Feb 21, 2021 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [c08ca084b0](https://bsd-hardware.info/?probe=c08ca084b0) | Feb 21, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [3680c4cd75](https://bsd-hardware.info/?probe=3680c4cd75) | Feb 20, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ade306695d](https://bsd-hardware.info/?probe=ade306695d) | Feb 20, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| Acer          | WG43M                       | Desktop     | [28a6795710](https://bsd-hardware.info/?probe=28a6795710) | Feb 15, 2021 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [e6fa5753b5](https://bsd-hardware.info/?probe=e6fa5753b5) | Feb 12, 2021 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [fd798dae01](https://bsd-hardware.info/?probe=fd798dae01) | Feb 12, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [23e7163f58](https://bsd-hardware.info/?probe=23e7163f58) | Feb 10, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [39c8cd6d0c](https://bsd-hardware.info/?probe=39c8cd6d0c) | Feb 08, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [5a0b61ac41](https://bsd-hardware.info/?probe=5a0b61ac41) | Feb 07, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [254e518190](https://bsd-hardware.info/?probe=254e518190) | Feb 03, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [cf41f72474](https://bsd-hardware.info/?probe=cf41f72474) | Jan 31, 2021 |
| Dell          | Latitude 5480               | Notebook    | [9b38a72dd4](https://bsd-hardware.info/?probe=9b38a72dd4) | Jan 26, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [fb318623f3](https://bsd-hardware.info/?probe=fb318623f3) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [97a89d4eb0](https://bsd-hardware.info/?probe=97a89d4eb0) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [806c954739](https://bsd-hardware.info/?probe=806c954739) | Jan 23, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [3d18f3f8a9](https://bsd-hardware.info/?probe=3d18f3f8a9) | Jan 23, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [f6df3820b5](https://bsd-hardware.info/?probe=f6df3820b5) | Jan 18, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [3c41c474ad](https://bsd-hardware.info/?probe=3c41c474ad) | Jan 16, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Notebook    | [9e58a182a8](https://bsd-hardware.info/?probe=9e58a182a8) | Jan 16, 2021 |
| MSI           | Z97 GAMING 5                | Desktop     | [9ef0da6093](https://bsd-hardware.info/?probe=9ef0da6093) | Jan 16, 2021 |
| HP            | OMEN by HP Laptop           | Notebook    | [14857eb6b7](https://bsd-hardware.info/?probe=14857eb6b7) | Jan 15, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [f7c32488e9](https://bsd-hardware.info/?probe=f7c32488e9) | Jan 15, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [06cbb5cd5f](https://bsd-hardware.info/?probe=06cbb5cd5f) | Jan 15, 2021 |
| Dell          | Latitude 5280               | Notebook    | [c9bfb73262](https://bsd-hardware.info/?probe=c9bfb73262) | Jan 15, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [a9228fa7c3](https://bsd-hardware.info/?probe=a9228fa7c3) | Jan 15, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [5af442bf61](https://bsd-hardware.info/?probe=5af442bf61) | Jan 15, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [a395c023bf](https://bsd-hardware.info/?probe=a395c023bf) | Jan 10, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [b4d2af272e](https://bsd-hardware.info/?probe=b4d2af272e) | Jan 05, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [5124b24d30](https://bsd-hardware.info/?probe=5124b24d30) | Jan 04, 2021 |
| Dell          | Inspiron 5758               | Notebook    | [c096e37be5](https://bsd-hardware.info/?probe=c096e37be5) | Jan 03, 2021 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | Desktop     | [2a0187ef7a](https://bsd-hardware.info/?probe=2a0187ef7a) | Jan 02, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [5cd8e23152](https://bsd-hardware.info/?probe=5cd8e23152) | Dec 26, 2020 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [fdbd71db5e](https://bsd-hardware.info/?probe=fdbd71db5e) | Dec 26, 2020 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [c51c202b8d](https://bsd-hardware.info/?probe=c51c202b8d) | Dec 25, 2020 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [4c24fe6fc4](https://bsd-hardware.info/?probe=4c24fe6fc4) | Dec 24, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [bf0d7fe4f1](https://bsd-hardware.info/?probe=bf0d7fe4f1) | Dec 22, 2020 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [a3a96da3fb](https://bsd-hardware.info/?probe=a3a96da3fb) | Dec 19, 2020 |
| Lenovo        | ThinkPad T450 20BV0064US    | Notebook    | [b397848c7e](https://bsd-hardware.info/?probe=b397848c7e) | Dec 16, 2020 |
| Toshiba       | Satellite C855              | Notebook    | [6bc78fc7fc](https://bsd-hardware.info/?probe=6bc78fc7fc) | Dec 16, 2020 |
| Panasonic     | CF-19AHNC8FN                | Notebook    | [04a42812bb](https://bsd-hardware.info/?probe=04a42812bb) | Dec 11, 2020 |
| Lenovo        | ThinkPad X220 42872VU       | Notebook    | [c843b5d271](https://bsd-hardware.info/?probe=c843b5d271) | Dec 10, 2020 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [464223cefe](https://bsd-hardware.info/?probe=464223cefe) | Dec 07, 2020 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Notebook    | [a6b923675d](https://bsd-hardware.info/?probe=a6b923675d) | Dec 07, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [d8a67b4a30](https://bsd-hardware.info/?probe=d8a67b4a30) | Dec 06, 2020 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [6c55fc2866](https://bsd-hardware.info/?probe=6c55fc2866) | Dec 05, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [53bf449015](https://bsd-hardware.info/?probe=53bf449015) | Dec 02, 2020 |
| Quanta        | 2AF5 011                    | Desktop     | [172f23efac](https://bsd-hardware.info/?probe=172f23efac) | Nov 29, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [8afa16fc20](https://bsd-hardware.info/?probe=8afa16fc20) | Nov 29, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [7fc23a57bb](https://bsd-hardware.info/?probe=7fc23a57bb) | Nov 25, 2020 |
| MSI           | B450 GAMING PLUS            | Desktop     | [4cf3dd682b](https://bsd-hardware.info/?probe=4cf3dd682b) | Nov 24, 2020 |
| MSI           | B450 GAMING PLUS            | Desktop     | [edee76372b](https://bsd-hardware.info/?probe=edee76372b) | Nov 21, 2020 |
| Acer          | Aspire 7540                 | Notebook    | [65d215a03b](https://bsd-hardware.info/?probe=65d215a03b) | Nov 17, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [cc075b3932](https://bsd-hardware.info/?probe=cc075b3932) | Nov 15, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [6a0c640524](https://bsd-hardware.info/?probe=6a0c640524) | Nov 12, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [6060033216](https://bsd-hardware.info/?probe=6060033216) | Nov 12, 2020 |
| Apple         | MacBook6,1                  | Notebook    | [64b1b1910c](https://bsd-hardware.info/?probe=64b1b1910c) | Nov 01, 2020 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [dc33c84287](https://bsd-hardware.info/?probe=dc33c84287) | Oct 22, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [1ac21e1660](https://bsd-hardware.info/?probe=1ac21e1660) | Oct 08, 2020 |
| Acer          | Aspire E1-532               | Notebook    | [10bff44534](https://bsd-hardware.info/?probe=10bff44534) | Oct 07, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7faf1699d6](https://bsd-hardware.info/?probe=7faf1699d6) | Oct 04, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [86e9866c03](https://bsd-hardware.info/?probe=86e9866c03) | Oct 02, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [3b8f8a2033](https://bsd-hardware.info/?probe=3b8f8a2033) | Oct 02, 2020 |
| Lenovo        | ThinkPad T590 20N40016CD    | Notebook    | [1d9786ac9f](https://bsd-hardware.info/?probe=1d9786ac9f) | Aug 31, 2020 |
| Lenovo        | ThinkPad T590 20N40016CD    | Notebook    | [e505894bee](https://bsd-hardware.info/?probe=e505894bee) | Aug 29, 2020 |
| System76      | Lemur Pro                   | Notebook    | [0163d0f084](https://bsd-hardware.info/?probe=0163d0f084) | Aug 29, 2020 |
| Lenovo        | ThinkPad T430s 23539JM      | Notebook    | [facf6fa0f8](https://bsd-hardware.info/?probe=facf6fa0f8) | Aug 27, 2020 |
| ASUSTek       | K53SD                       | Notebook    | [975e9ccbe2](https://bsd-hardware.info/?probe=975e9ccbe2) | Aug 27, 2020 |
| Lenovo        | ThinkPad T530 239242U       | Notebook    | [7c8087322d](https://bsd-hardware.info/?probe=7c8087322d) | Aug 27, 2020 |
| Sony          | VGN-SZ3VWP_X                | Notebook    | [ace534d784](https://bsd-hardware.info/?probe=ace534d784) | Aug 10, 2020 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [d508fb472b](https://bsd-hardware.info/?probe=d508fb472b) | Aug 10, 2020 |
| MSI           | H61M-P20                    | Desktop     | [fefac5637b](https://bsd-hardware.info/?probe=fefac5637b) | Aug 03, 2020 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [0073f8ff71](https://bsd-hardware.info/?probe=0073f8ff71) | Aug 02, 2020 |
| Gigabyte      | H67A-UD3H-B3                | Desktop     | [aa29eb9c75](https://bsd-hardware.info/?probe=aa29eb9c75) | Aug 01, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [b89da90904](https://bsd-hardware.info/?probe=b89da90904) | Aug 01, 2020 |
| ASUSTek       | G750JS                      | Notebook    | [8214170523](https://bsd-hardware.info/?probe=8214170523) | Aug 01, 2020 |
| ASUSTek       | G750JS                      | Notebook    | [60b904f003](https://bsd-hardware.info/?probe=60b904f003) | Aug 01, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [34bb81770b](https://bsd-hardware.info/?probe=34bb81770b) | Jul 22, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [4473708fd0](https://bsd-hardware.info/?probe=4473708fd0) | Jul 22, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [174569bf55](https://bsd-hardware.info/?probe=174569bf55) | Jul 21, 2020 |
| ASRock        | A300M-STX                   | Desktop     | [f62a2ace5a](https://bsd-hardware.info/?probe=f62a2ace5a) | Jul 16, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [db7146b868](https://bsd-hardware.info/?probe=db7146b868) | Jul 14, 2020 |
| Dell          | Latitude E6420              | Notebook    | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [f4e8ffb5dc](https://bsd-hardware.info/?probe=f4e8ffb5dc) | May 27, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [59c5b6d6b9](https://bsd-hardware.info/?probe=59c5b6d6b9) | May 27, 2020 |
| Dell          | Precision M4700             | Notebook    | [a7761ee829](https://bsd-hardware.info/?probe=a7761ee829) | May 25, 2020 |
| Gigabyte      | Z170X-UD5 TH-CF             | Desktop     | [2fc2952380](https://bsd-hardware.info/?probe=2fc2952380) | May 25, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [6a1b7867f0](https://bsd-hardware.info/?probe=6a1b7867f0) | May 16, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [25fd1154c0](https://bsd-hardware.info/?probe=25fd1154c0) | May 08, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [0370bc0522](https://bsd-hardware.info/?probe=0370bc0522) | May 02, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/GhostBSD/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| GhostBSD 20.04.02      | 109       | 20.26%  |
| GhostBSD 24.01.1       | 43        | 7.99%   |
| GhostBSD 21.08.27      | 40        | 7.43%   |
| GhostBSD 25.02-R14.3p2 | 39        | 7.25%   |
| GhostBSD 24.10.1       | 37        | 6.88%   |
| GhostBSD 23.10.1       | 30        | 5.58%   |
| GhostBSD 24.07.3       | 21        | 3.9%    |
| GhostBSD 25.01-R14.2p1 | 18        | 3.35%   |
| GhostBSD 22.01.12      | 18        | 3.35%   |
| GhostBSD 24.04.1       | 17        | 3.16%   |
| GhostBSD 23.06.01      | 15        | 2.79%   |
| GhostBSD 25.01-R14.2p3 | 14        | 2.6%    |
| GhostBSD 22.06.18      | 14        | 2.6%    |
| GhostBSD 25.01-R14.2p2 | 12        | 2.23%   |
| GhostBSD 23.02.02      | 10        | 1.86%   |
| GhostBSD 25.02-R14.3p4 | 8         | 1.49%   |
| GhostBSD 22.11.22      | 5         | 0.93%   |
| GhostBSD 24.07.1       | 4         | 0.74%   |
| GhostBSD 23.07.13      | 4         | 0.74%   |
| GhostBSD 22.07.16      | 4         | 0.74%   |
| GhostBSD 22.06.26      | 4         | 0.74%   |
| GhostBSD 23.09.06      | 3         | 0.56%   |
| GhostBSD 23.07.29      | 3         | 0.56%   |
| GhostBSD 23.06.05      | 3         | 0.56%   |
| GhostBSD 23.04.23      | 3         | 0.56%   |
| GhostBSD 23.03.17      | 3         | 0.56%   |
| GhostBSD 22.11.02      | 3         | 0.56%   |
| GhostBSD 22.09.16      | 3         | 0.56%   |
| GhostBSD 22.08.23      | 3         | 0.56%   |
| GhostBSD 22.04.06      | 3         | 0.56%   |
| GhostBSD 23.09.29      | 2         | 0.37%   |
| GhostBSD 23.09.16      | 2         | 0.37%   |
| GhostBSD 23.07.20      | 2         | 0.37%   |
| GhostBSD 23.06.22      | 2         | 0.37%   |
| GhostBSD 23.05.22      | 2         | 0.37%   |
| GhostBSD 23.05.18      | 2         | 0.37%   |
| GhostBSD 22.08.06      | 2         | 0.37%   |
| GhostBSD 22.07.13      | 2         | 0.37%   |
| GhostBSD 22.04.22      | 2         | 0.37%   |
| GhostBSD 24.07.2       | 1         | 0.19%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GhostBSD | 498       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 498       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| MATE             | 399       | 78.85%  |
| XFCE             | 72        | 14.23%  |
| KDE5             | 16        | 3.16%   |
| i3               | 3         | 0.59%   |
| Cinnamon         | 3         | 0.59%   |
| Metacity (Marco) | 2         | 0.4%    |
| KDE              | 2         | 0.4%    |
| GNOME            | 2         | 0.4%    |
| pekwm            | 1         | 0.2%    |
| openbox          | 1         | 0.2%    |
| LXQt             | 1         | 0.2%    |
| KDE6             | 1         | 0.2%    |
| helloDesktop     | 1         | 0.2%    |
| dwm              | 1         | 0.2%    |
| Console          | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 496       | 99.4%   |
| Wayland | 2         | 0.4%    |
| Console | 1         | 0.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 488       | 97.99%  |
| SDDM    | 8         | 1.61%   |
| Console | 2         | 0.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 232       | 45.4%   |
| C       | 144       | 28.18%  |
| de_DE   | 33        | 6.46%   |
| Unknown | 31        | 6.07%   |
| es_ES   | 16        | 3.13%   |
| ru_RU   | 11        | 2.15%   |
| pt_BR   | 8         | 1.57%   |
| pl_PL   | 7         | 1.37%   |
| en_GB   | 6         | 1.17%   |
| fr_FR   | 5         | 0.98%   |
| sk_SK   | 3         | 0.59%   |
| it_IT   | 3         | 0.59%   |
| pt_PT   | 2         | 0.39%   |
| nl_NL   | 2         | 0.39%   |
| en_AU   | 2         | 0.39%   |
| zh_CN   | 1         | 0.2%    |
| UTF-8   | 1         | 0.2%    |
| sv_SE   | 1         | 0.2%    |
| fr_CA   | 1         | 0.2%    |
| en_NZ   | 1         | 0.2%    |
| el_GR   | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 409       | 81.96%  |
| BIOS | 90        | 18.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 483       | 95.83%  |
| Ufs  | 21        | 4.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 485       | 97.19%  |
| MBR     | 9         | 1.8%    |
| Unknown | 5         | 1%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 118       | 23.69%  |
| Dell                                 | 80        | 16.06%  |
| ASUSTek Computer                     | 57        | 11.45%  |
| Hewlett-Packard                      | 55        | 11.04%  |
| MSI                                  | 27        | 5.42%   |
| Gigabyte Technology                  | 23        | 4.62%   |
| Apple                                | 20        | 4.02%   |
| Acer                                 | 20        | 4.02%   |
| ASRock                               | 17        | 3.41%   |
| Fujitsu                              | 8         | 1.61%   |
| Toshiba                              | 5         | 1%      |
| Notebook                             | 5         | 1%      |
| HUAWEI                               | 5         | 1%      |
| Sony                                 | 4         | 0.8%    |
| Samsung Electronics                  | 4         | 0.8%    |
| System76                             | 3         | 0.6%    |
| Supermicro                           | 3         | 0.6%    |
| Medion                               | 3         | 0.6%    |
| Biostar                              | 3         | 0.6%    |
| Alienware                            | 3         | 0.6%    |
| Unknown                              | 3         | 0.6%    |
| TUXEDO                               | 2         | 0.4%    |
| Star Labs                            | 2         | 0.4%    |
| Intel                                | 2         | 0.4%    |
| Huanan                               | 2         | 0.4%    |
| F-Plus Mobile                        | 2         | 0.4%    |
| AZW                                  | 2         | 0.4%    |
| XtReAmEr                             | 1         | 0.2%    |
| TongFang                             | 1         | 0.2%    |
| Soyo                                 | 1         | 0.2%    |
| Shenzhen Meigao Electronic Equipment | 1         | 0.2%    |
| Quanta                               | 1         | 0.2%    |
| Pegatron                             | 1         | 0.2%    |
| Panasonic                            | 1         | 0.2%    |
| OEM                                  | 1         | 0.2%    |
| MouseComputer                        | 1         | 0.2%    |
| Mini PC                              | 1         | 0.2%    |
| Microsoft                            | 1         | 0.2%    |
| Maibenben                            | 1         | 0.2%    |
| LG Electronics                       | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 6         | 1.2%    |
| MSI MS-7B86                        | 3         | 0.6%    |
| Dell XPS 13 9360                   | 3         | 0.6%    |
| Dell Latitude 7490                 | 3         | 0.6%    |
| Dell Inspiron 3542                 | 3         | 0.6%    |
| ASUS All Series                    | 3         | 0.6%    |
| MSI MS-7817                        | 2         | 0.4%    |
| MSI Modern 14 A10M                 | 2         | 0.4%    |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS | 2         | 0.4%    |
| Lenovo Yoga 900S-12ISK 80ML        | 2         | 0.4%    |
| Lenovo ThinkPad T430s 2352CTO      | 2         | 0.4%    |
| HP Notebook                        | 2         | 0.4%    |
| HP EliteBook Folio 9470m           | 2         | 0.4%    |
| F-Plus Mobile FLAPTOP r            | 2         | 0.4%    |
| Dell XPS 13 7390                   | 2         | 0.4%    |
| Dell OptiPlex 7050                 | 2         | 0.4%    |
| Dell Latitude E6540                | 2         | 0.4%    |
| Dell Latitude E6420                | 2         | 0.4%    |
| Dell Latitude E5440                | 2         | 0.4%    |
| Dell Latitude 5520                 | 2         | 0.4%    |
| Dell G3 3579                       | 2         | 0.4%    |
| ASUS ZenBook UX325UA_UM325UA       | 2         | 0.4%    |
| ASUS X202E                         | 2         | 0.4%    |
| ASUS SABERTOOTH X58                | 2         | 0.4%    |
| ASUS MINIPC PN50                   | 2         | 0.4%    |
| Apple iMac9,1                      | 2         | 0.4%    |
| TUXEDO InfinityBook13V3            | 1         | 0.2%    |
| TUXEDO Aura 15 Gen1                | 1         | 0.2%    |
| Toshiba Satellite L655             | 1         | 0.2%    |
| Toshiba Satellite L50-C            | 1         | 0.2%    |
| Toshiba Satellite C855-1U4         | 1         | 0.2%    |
| Toshiba Satellite C855             | 1         | 0.2%    |
| Toshiba Satellite C800D            | 1         | 0.2%    |
| TongFang GX4HRXL                   | 1         | 0.2%    |
| System76 Lemur Pro                 | 1         | 0.2%    |
| System76 Kudu                      | 1         | 0.2%    |
| System76 Gazelle                   | 1         | 0.2%    |
| Supermicro X10DRi                  | 1         | 0.2%    |
| Supermicro C7H170-M                | 1         | 0.2%    |
| Supermicro AS -3015A-I             | 1         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 80        | 16.06%  |
| Dell Latitude          | 29        | 5.82%   |
| Dell Inspiron          | 19        | 3.82%   |
| Acer Aspire            | 14        | 2.81%   |
| HP EliteBook           | 11        | 2.21%   |
| Dell OptiPlex          | 11        | 2.21%   |
| Lenovo IdeaPad         | 9         | 1.81%   |
| Dell XPS               | 8         | 1.61%   |
| ASUS PRIME             | 8         | 1.61%   |
| Lenovo Yoga            | 7         | 1.41%   |
| Dell Precision         | 7         | 1.41%   |
| Lenovo ThinkCentre     | 6         | 1.2%    |
| HP Laptop              | 6         | 1.2%    |
| Unknown                | 6         | 1.2%    |
| Toshiba Satellite      | 5         | 1%      |
| ASUS ROG               | 5         | 1%      |
| Lenovo Legion          | 4         | 0.8%    |
| HP Pavilion            | 4         | 0.8%    |
| ASUS VivoBook          | 4         | 0.8%    |
| ASUS TUF               | 4         | 0.8%    |
| MSI MS-7B86            | 3         | 0.6%    |
| Lenovo IdeaCentre      | 3         | 0.6%    |
| HP ProBook             | 3         | 0.6%    |
| HP OMEN                | 3         | 0.6%    |
| HP Compaq              | 3         | 0.6%    |
| Fujitsu LIFEBOOK       | 3         | 0.6%    |
| Dell Vostro            | 3         | 0.6%    |
| ASUS MINIPC            | 3         | 0.6%    |
| ASUS All               | 3         | 0.6%    |
| ASRock X570            | 3         | 0.6%    |
| ASRock B450            | 3         | 0.6%    |
| Acer TravelMate        | 3         | 0.6%    |
| MSI MS-7817            | 2         | 0.4%    |
| MSI Modern             | 2         | 0.4%    |
| HP ProLiant            | 2         | 0.4%    |
| HP ProDesk             | 2         | 0.4%    |
| HP Notebook            | 2         | 0.4%    |
| HP 255                 | 2         | 0.4%    |
| HP 250                 | 2         | 0.4%    |
| Gigabyte GA-78LMT-USB3 | 2         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 62        | 12.45%  |
| 2021 | 42        | 8.43%   |
| 2018 | 41        | 8.23%   |
| 2019 | 40        | 8.03%   |
| 2013 | 39        | 7.83%   |
| 2022 | 35        | 7.03%   |
| 2015 | 32        | 6.43%   |
| 2016 | 29        | 5.82%   |
| 2012 | 27        | 5.42%   |
| 2011 | 26        | 5.22%   |
| 2014 | 25        | 5.02%   |
| 2023 | 23        | 4.62%   |
| 2017 | 21        | 4.22%   |
| 2009 | 14        | 2.81%   |
| 2024 | 13        | 2.61%   |
| 2010 | 11        | 2.21%   |
| 2008 | 11        | 2.21%   |
| 2025 | 6         | 1.2%    |
| 2007 | 1         | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 307       | 61.65%  |
| Desktop     | 156       | 31.33%  |
| Mini pc     | 14        | 2.81%   |
| Convertible | 8         | 1.61%   |
| All in one  | 8         | 1.61%   |
| Server      | 4         | 0.8%    |
| Tablet      | 1         | 0.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 494       | 99.2%   |
| Yes  | 4         | 0.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 192       | 38.32%  |
| 16.01-24.0      | 167       | 33.33%  |
| 4.01-8.0        | 61        | 12.18%  |
| 32.01-64.0      | 50        | 9.98%   |
| 64.01-256.0     | 18        | 3.59%   |
| 24.01-32.0      | 11        | 2.2%    |
| More than 256.0 | 1         | 0.2%    |
| 2.01-3.0        | 1         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 210       | 41.67%  |
| 0.01-0.5   | 173       | 34.33%  |
| 1.01-2.0   | 75        | 14.88%  |
| 2.01-3.0   | 29        | 5.75%   |
| 4.01-8.0   | 9         | 1.79%   |
| 3.01-4.0   | 6         | 1.19%   |
| 24.01-32.0 | 1         | 0.2%    |
| 8.01-16.0  | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 283       | 55.38%  |
| 2      | 99        | 19.37%  |
| 0      | 85        | 16.63%  |
| 3      | 16        | 3.13%   |
| 4      | 13        | 2.54%   |
| 6      | 6         | 1.17%   |
| 5      | 6         | 1.17%   |
| 22     | 1         | 0.2%    |
| 8      | 1         | 0.2%    |
| 7      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 343       | 68.46%  |
| Yes       | 158       | 31.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 428       | 85.77%  |
| No        | 71        | 14.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 404       | 81.12%  |
| No        | 94        | 18.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 325       | 65.26%  |
| No        | 173       | 34.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 108       | 21.6%   |
| Germany      | 68        | 13.6%   |
| UK           | 28        | 5.6%    |
| Canada       | 27        | 5.4%    |
| France       | 22        | 4.4%    |
| Spain        | 20        | 4%      |
| Russia       | 19        | 3.8%    |
| Poland       | 15        | 3%      |
| Switzerland  | 10        | 2%      |
| Italy        | 9         | 1.8%    |
| Bulgaria     | 8         | 1.6%    |
| Brazil       | 8         | 1.6%    |
| Netherlands  | 7         | 1.4%    |
| Japan        | 7         | 1.4%    |
| Indonesia    | 7         | 1.4%    |
| India        | 7         | 1.4%    |
| Australia    | 7         | 1.4%    |
| Taiwan       | 6         | 1.2%    |
| Belgium      | 6         | 1.2%    |
| Austria      | 6         | 1.2%    |
| Portugal     | 5         | 1%      |
| Finland      | 5         | 1%      |
| China        | 5         | 1%      |
| Sweden       | 4         | 0.8%    |
| Philippines  | 4         | 0.8%    |
| Norway       | 4         | 0.8%    |
| New Zealand  | 4         | 0.8%    |
| Malaysia     | 4         | 0.8%    |
| Denmark      | 4         | 0.8%    |
| Argentina    | 4         | 0.8%    |
| Turkey       | 3         | 0.6%    |
| South Africa | 3         | 0.6%    |
| Slovenia     | 3         | 0.6%    |
| Slovakia     | 3         | 0.6%    |
| Paraguay     | 3         | 0.6%    |
| Mexico       | 3         | 0.6%    |
| Hungary      | 3         | 0.6%    |
| Hong Kong    | 3         | 0.6%    |
| Greece       | 3         | 0.6%    |
| Czechia      | 3         | 0.6%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Calgary       | 9         | 1.74%   |
| Zurich        | 7         | 1.35%   |
| Sofia         | 6         | 1.16%   |
| Paris         | 6         | 1.16%   |
| Edgware       | 6         | 1.16%   |
| Bonn          | 6         | 1.16%   |
| Bedburg       | 6         | 1.16%   |
| Berlin        | 5         | 0.97%   |
| Taichung      | 4         | 0.77%   |
| Sydney        | 4         | 0.77%   |
| Madrid        | 4         | 0.77%   |
| London        | 4         | 0.77%   |
| Jakarta       | 4         | 0.77%   |
| Indian Trail  | 4         | 0.77%   |
| Frederiksberg | 4         | 0.77%   |
| Denver        | 4         | 0.77%   |
| Cologne       | 4         | 0.77%   |
| Vienna        | 3         | 0.58%   |
| Victoria      | 3         | 0.58%   |
| Saratov       | 3         | 0.58%   |
| Rome          | 3         | 0.58%   |
| Oslo          | 3         | 0.58%   |
| New York      | 3         | 0.58%   |
| Moscow        | 3         | 0.58%   |
| Milan         | 3         | 0.58%   |
| Lisbon        | 3         | 0.58%   |
| Lebanon       | 3         | 0.58%   |
| Hamburg       | 3         | 0.58%   |
| Franconville  | 3         | 0.58%   |
| Cloppenburg   | 3         | 0.58%   |
| Chrusty       | 3         | 0.58%   |
| Bengaluru     | 3         | 0.58%   |
| Zdunska Wola  | 2         | 0.39%   |
| Zaragoza      | 2         | 0.39%   |
| Yokohama      | 2         | 0.39%   |
| Winnipeg      | 2         | 0.39%   |
| Whittier      | 2         | 0.39%   |
| Wezeren       | 2         | 0.39%   |
| Vancouver     | 2         | 0.39%   |
| Valencia      | 2         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 115       | 144    | 19.36%  |
| WDC                 | 88        | 112    | 14.81%  |
| Seagate             | 63        | 88     | 10.61%  |
| Crucial             | 46        | 60     | 7.74%   |
| Kingston            | 38        | 40     | 6.4%    |
| Toshiba             | 34        | 42     | 5.72%   |
| SanDisk             | 27        | 32     | 4.55%   |
| SK hynix            | 18        | 22     | 3.03%   |
| Intel               | 16        | 16     | 2.69%   |
| Hitachi             | 15        | 15     | 2.53%   |
| HGST                | 13        | 18     | 2.19%   |
| A-DATA Technology   | 13        | 14     | 2.19%   |
| Micron Technology   | 10        | 11     | 1.68%   |
| Phison              | 7         | 9      | 1.18%   |
| Apple               | 6         | 6      | 1.01%   |
| PNY                 | 5         | 7      | 0.84%   |
| Patriot             | 5         | 5      | 0.84%   |
| China               | 5         | 5      | 0.84%   |
| Transcend           | 4         | 4      | 0.67%   |
| Gigabyte Technology | 4         | 4      | 0.67%   |
| Plextor             | 3         | 3      | 0.51%   |
| LITEONIT            | 3         | 3      | 0.51%   |
| LITEON              | 3         | 3      | 0.51%   |
| Hikvision           | 3         | 6      | 0.51%   |
| Hewlett-Packard     | 3         | 9      | 0.51%   |
| GOODRAM             | 3         | 3      | 0.51%   |
| Team                | 2         | 2      | 0.34%   |
| Star Drive          | 2         | 2      | 0.34%   |
| SSSTC               | 2         | 2      | 0.34%   |
| SPCC                | 2         | 2      | 0.34%   |
| OCZ                 | 2         | 2      | 0.34%   |
| Maxtor              | 2         | 2      | 0.34%   |
| Lexar               | 2         | 3      | 0.34%   |
| KingSpec            | 2         | 2      | 0.34%   |
| Intenso             | 2         | 2      | 0.34%   |
| Fujitsu             | 2         | 2      | 0.34%   |
| Apacer              | 2         | 2      | 0.34%   |
| XUM                 | 1         | 1      | 0.17%   |
| XrayDisk            | 1         | 1      | 0.17%   |
| XPG                 | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Crucial CT1000MX500SSD1 1TB            | 10        | 1.56%   |
| WDC WDS500G2B0A-00SM50 500GB           | 7         | 1.1%    |
| Samsung SSD 850 EVO 250GB              | 7         | 1.1%    |
| Kingston SA400S37240G 240GB            | 7         | 1.1%    |
| Samsung SSD 870 EVO 500GB              | 6         | 0.94%   |
| Samsung SSD 860 QVO 1TB                | 6         | 0.94%   |
| Samsung SSD 850 EVO 500GB              | 6         | 0.94%   |
| Samsung SSD 860 EVO 500GB              | 5         | 0.78%   |
| Kingston SA400S37120G 120GB            | 5         | 0.78%   |
| Crucial CT240BX500SSD1 240GB           | 5         | 0.78%   |
| Toshiba DT01ACA050 500GB               | 4         | 0.63%   |
| Seagate ST500DM002-1BD142 500GB        | 4         | 0.63%   |
| Seagate ST2000DM001-1ER164 2TB         | 4         | 0.63%   |
| Samsung SSD 860 EVO 1TB                | 4         | 0.63%   |
| Kingston SV300S37A120G 120GB           | 4         | 0.63%   |
| Hitachi HTS541612J9SA00 120GB          | 4         | 0.63%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 3         | 0.47%   |
| WDC WD40EFRX-68N32N0 4TB               | 3         | 0.47%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 0.47%   |
| Toshiba MQ01ABD100 1TB                 | 3         | 0.47%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 3         | 0.47%   |
| SK hynix HFS256G39TND-N210A 256GB      | 3         | 0.47%   |
| Seagate ST2000LM003 HN-M201RAD 2TB     | 3         | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB         | 3         | 0.47%   |
| Seagate ST1000VM002-1SD102 1TB         | 3         | 0.47%   |
| Seagate ST1000LM049-2GH172 1TB         | 3         | 0.47%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 0.47%   |
| SanDisk SSD U100 16GB                  | 3         | 0.47%   |
| SanDisk SSD PLUS 1000GB                | 3         | 0.47%   |
| Samsung SSD 970 EVO Plus 1TB           | 3         | 0.47%   |
| Samsung HM320JI 320GB                  | 3         | 0.47%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.47%   |
| HGST HTS541010A9E680 1TB               | 3         | 0.47%   |
| Crucial CT500MX500SSD1 500GB           | 3         | 0.47%   |
| Crucial CT480BX500SSD1 480GB           | 3         | 0.47%   |
| Crucial CT250MX500SSD1 250GB           | 3         | 0.47%   |
| A-DATA SU650 120GB                     | 3         | 0.47%   |
| WDC WDS480G2G0A-00JH30 480GB           | 2         | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB           | 2         | 0.31%   |
| WDC WD2002FAEX-007BA0 2TB              | 2         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 86     | 32.98%  |
| WDC                 | 61        | 76     | 32.45%  |
| Toshiba             | 18        | 21     | 9.57%   |
| Hitachi             | 15        | 15     | 7.98%   |
| HGST                | 13        | 18     | 6.91%   |
| Samsung Electronics | 10        | 11     | 5.32%   |
| Maxtor              | 2         | 2      | 1.06%   |
| Fujitsu             | 2         | 2      | 1.06%   |
| Apple               | 2         | 2      | 1.06%   |
| WD MediaMax         | 1         | 1      | 0.53%   |
| HPT                 | 1         | 4      | 0.53%   |
| Hewlett-Packard     | 1         | 6      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 79        | 94     | 25.65%  |
| Crucial             | 41        | 50     | 13.31%  |
| Kingston            | 32        | 34     | 10.39%  |
| SanDisk             | 27        | 32     | 8.77%   |
| WDC                 | 18        | 21     | 5.84%   |
| SK hynix            | 10        | 10     | 3.25%   |
| Toshiba             | 8         | 10     | 2.6%    |
| A-DATA Technology   | 8         | 8      | 2.6%    |
| Micron Technology   | 7         | 8      | 2.27%   |
| Intel               | 7         | 7      | 2.27%   |
| PNY                 | 5         | 7      | 1.62%   |
| Patriot             | 5         | 5      | 1.62%   |
| China               | 5         | 5      | 1.62%   |
| Transcend           | 4         | 4      | 1.3%    |
| Apple               | 4         | 4      | 1.3%    |
| Plextor             | 3         | 3      | 0.97%   |
| LITEONIT            | 3         | 3      | 0.97%   |
| LITEON              | 3         | 3      | 0.97%   |
| Hikvision           | 3         | 6      | 0.97%   |
| GOODRAM             | 3         | 3      | 0.97%   |
| Team                | 2         | 2      | 0.65%   |
| SPCC                | 2         | 2      | 0.65%   |
| OCZ                 | 2         | 2      | 0.65%   |
| Lexar               | 2         | 3      | 0.65%   |
| KingSpec            | 2         | 2      | 0.65%   |
| Apacer              | 2         | 2      | 0.65%   |
| XUM                 | 1         | 1      | 0.32%   |
| XrayDisk            | 1         | 1      | 0.32%   |
| Verbatim            | 1         | 1      | 0.32%   |
| Vaseky              | 1         | 1      | 0.32%   |
| SSSTC               | 1         | 1      | 0.32%   |
| ShiJi               | 1         | 1      | 0.32%   |
| Seagate             | 1         | 1      | 0.32%   |
| SATADOM             | 1         | 2      | 0.32%   |
| Phison              | 1         | 1      | 0.32%   |
| Netac               | 1         | 1      | 0.32%   |
| Neo Forza           | 1         | 2      | 0.32%   |
| MidasForce          | 1         | 1      | 0.32%   |
| Intenso             | 1         | 1      | 0.32%   |
| Innodisk            | 1         | 1      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 256       | 356    | 50%     |
| HDD  | 159       | 244    | 31.05%  |
| NVMe | 97        | 133    | 18.95%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 361       | 600    | 78.82%  |
| NVMe | 97        | 133    | 21.18%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 264       | 348    | 59.46%  |
| 0.51-1.0   | 114       | 163    | 25.68%  |
| 1.01-2.0   | 44        | 56     | 9.91%   |
| 3.01-4.0   | 14        | 18     | 3.15%   |
| 4.01-10.0  | 5         | 11     | 1.13%   |
| 2.01-3.0   | 2         | 2      | 0.45%   |
| 10.01-20.0 | 1         | 2      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 134       | 25.97%  |
| 1-20           | 132       | 25.58%  |
| 251-500        | 97        | 18.8%   |
| 501-1000       | 54        | 10.47%  |
| 51-100         | 36        | 6.98%   |
| 21-50          | 29        | 5.62%   |
| Unknown        | 21        | 4.07%   |
| 1001-2000      | 11        | 2.13%   |
| More than 3000 | 2         | 0.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 447       | 86.96%  |
| 21-50   | 35        | 6.81%   |
| Unknown | 21        | 4.09%   |
| 51-100  | 6         | 1.17%   |
| 101-250 | 4         | 0.78%   |
| 251-500 | 1         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Hitachi HTS541612J9SA00 120GB         | 4         | 4      | 4.6%    |
| Samsung Electronics HM320JI 320GB     | 3         | 3      | 3.45%   |
| Toshiba MQ01ACF032 320GB              | 2         | 2      | 2.3%    |
| SK hynix HFS256G39TND-N210A 256GB     | 2         | 2      | 2.3%    |
| Seagate ST500LT012-9WS142 500GB       | 2         | 3      | 2.3%    |
| Seagate ST500LM021-1KJ152 500GB       | 2         | 2      | 2.3%    |
| Seagate ST500DM002-1BD142 500GB       | 2         | 3      | 2.3%    |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 2      | 2.3%    |
| Maxtor STM3320613AS 320GB             | 2         | 2      | 2.3%    |
| Kingston SA400S37240G 240GB           | 2         | 2      | 2.3%    |
| HGST HTS545050A7E380 500GB            | 2         | 2      | 2.3%    |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 2.3%    |
| WDC WDS480G2G0A-00JH30 480GB          | 1         | 2      | 1.15%   |
| WDC WD800AAJS-00TDA0 80GB             | 1         | 1      | 1.15%   |
| WDC WD6400BEVT-22A0RT0 640GB          | 1         | 1      | 1.15%   |
| WDC WD6400AAKS-40H2B0 640GB           | 1         | 1      | 1.15%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 2      | 1.15%   |
| WDC WD5000AAKS-60WWPA0 500GB          | 1         | 1      | 1.15%   |
| WDC WD5000AAKS-00UU3A0 500GB          | 1         | 1      | 1.15%   |
| WDC WD40EFRX-68N32N0 4TB              | 1         | 2      | 1.15%   |
| WDC WD3200LPVX-75V0TT0 320GB          | 1         | 1      | 1.15%   |
| WDC WD20EZRX-19D8PB0 2TB              | 1         | 1      | 1.15%   |
| WDC WD20EFRX-68EUZN0 1TB              | 1         | 1      | 1.15%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 1.15%   |
| WDC WD10EZEX-21M2NA0 1TB              | 1         | 1      | 1.15%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB  | 1         | 1      | 1.15%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB  | 1         | 1      | 1.15%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.15%   |
| Toshiba MK3263GSX 320GB               | 1         | 1      | 1.15%   |
| Toshiba MK1252GSX 120GB               | 1         | 1      | 1.15%   |
| Toshiba DT01ACA050 500GB              | 1         | 1      | 1.15%   |
| SK hynix HFS256G39MND-2300A 256GB     | 1         | 1      | 1.15%   |
| ShiJi SSD 512GB                       | 1         | 1      | 1.15%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 1.15%   |
| Seagate ST500LM000-1EJ162 500GB       | 1         | 2      | 1.15%   |
| Seagate ST500DM002-1BC142 500GB       | 1         | 1      | 1.15%   |
| Seagate ST4000DM004-2CV104 4TB        | 1         | 1      | 1.15%   |
| Seagate ST3250310AS 250GB             | 1         | 1      | 1.15%   |
| Seagate ST3160318AS 160GB             | 1         | 1      | 1.15%   |
| Seagate ST31500541AS 1.5TB            | 1         | 1      | 1.15%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 21     | 17.65%  |
| WDC                 | 13        | 16     | 15.29%  |
| Samsung Electronics | 10        | 11     | 11.76%  |
| Hitachi             | 9         | 9      | 10.59%  |
| Toshiba             | 8         | 8      | 9.41%   |
| HGST                | 5         | 5      | 5.88%   |
| Crucial             | 4         | 4      | 4.71%   |
| SK hynix            | 3         | 3      | 3.53%   |
| SanDisk             | 3         | 3      | 3.53%   |
| Micron Technology   | 2         | 2      | 2.35%   |
| Maxtor              | 2         | 2      | 2.35%   |
| Kingston            | 2         | 2      | 2.35%   |
| Intel               | 2         | 2      | 2.35%   |
| ShiJi               | 1         | 1      | 1.18%   |
| Plextor             | 1         | 1      | 1.18%   |
| Patriot             | 1         | 1      | 1.18%   |
| OCZ                 | 1         | 1      | 1.18%   |
| Fanxiang            | 1         | 2      | 1.18%   |
| Apple               | 1         | 1      | 1.18%   |
| A-DATA Technology   | 1         | 1      | 1.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 21     | 27.78%  |
| WDC                 | 12        | 14     | 22.22%  |
| Hitachi             | 9         | 9      | 16.67%  |
| Toshiba             | 6         | 6      | 11.11%  |
| HGST                | 5         | 5      | 9.26%   |
| Samsung Electronics | 4         | 5      | 7.41%   |
| Maxtor              | 2         | 2      | 3.7%    |
| Apple               | 1         | 1      | 1.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 50        | 63     | 61.73%  |
| SSD  | 30        | 32     | 37.04%  |
| NVMe | 1         | 1      | 1.23%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB         | 1         | 1      | 50%     |
| Intel SSDSCKKF512G8 SATA 512GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Intel   | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 375       | 623    | 81.34%  |
| Malfunc  | 78        | 96     | 16.92%  |
| Detected | 6         | 12     | 1.3%    |
| Failed   | 2         | 2      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 316       | 49.69%  |
| AMD                                     | 89        | 13.99%  |
| Samsung Electronics                     | 58        | 9.12%   |
| SanDisk                                 | 27        | 4.25%   |
| SK hynix                                | 19        | 2.99%   |
| Phison Electronics                      | 17        | 2.67%   |
| Micron/Crucial Technology               | 14        | 2.2%    |
| Kingston Technology Company             | 13        | 2.04%   |
| Nvidia                                  | 11        | 1.73%   |
| Micron Technology                       | 10        | 1.57%   |
| Toshiba                                 | 9         | 1.42%   |
| ASMedia Technology                      | 8         | 1.26%   |
| ADATA Technology                        | 8         | 1.26%   |
| JMicron Technology                      | 6         | 0.94%   |
| Silicon Motion                          | 5         | 0.79%   |
| MAXIO Technology (Hangzhou)             | 5         | 0.79%   |
| Shenzhen Longsys Electronics            | 3         | 0.47%   |
| Marvell Technology Group                | 3         | 0.47%   |
| KIOXIA                                  | 3         | 0.47%   |
| Solid State Storage Technology          | 1         | 0.16%   |
| Shenzhen Unionmemory Information System | 1         | 0.16%   |
| Shenzhen Techwinsemi Technology         | 1         | 0.16%   |
| Seagate Technology                      | 1         | 0.16%   |
| Realtek Semiconductor                   | 1         | 0.16%   |
| OCZ Technology Group                    | 1         | 0.16%   |
| Integrated Technology Express           | 1         | 0.16%   |
| HighPoint Technologies                  | 1         | 0.16%   |
| Hewlett-Packard                         | 1         | 0.16%   |
| Broadcom / LSI                          | 1         | 0.16%   |
| Biwin Storage Technology                | 1         | 0.16%   |
| Adaptec                                 | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 65        | 9.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 40        | 5.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 30        | 4.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 27        | 3.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 17        | 2.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 17        | 2.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 17        | 2.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16        | 2.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 15        | 2.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13        | 1.86%   |
| AMD 400 Series Chipset SATA Controller                                                  | 13        | 1.86%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 11        | 1.57%   |
| Intel SATA Controller [RAID Mode]                                                       | 11        | 1.57%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 9         | 1.29%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9         | 1.29%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 8         | 1.14%   |
| Nvidia MCP79 AHCI Controller                                                            | 8         | 1.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 8         | 1.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 8         | 1.14%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 8         | 1.14%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 7         | 1%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 1%      |
| Intel Comet Lake SATA AHCI Controller                                                   | 7         | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7         | 1%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7         | 1%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5         | 0.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5         | 0.72%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 5         | 0.72%   |
| Intel SSD 660P Series                                                                   | 5         | 0.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 0.72%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5         | 0.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5         | 0.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 0.72%   |
| Sandisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                            | 4         | 0.57%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 4         | 0.57%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                              | 4         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 368       | 58.51%  |
| NVMe | 186       | 29.57%  |
| RAID | 37        | 5.88%   |
| IDE  | 35        | 5.56%   |
| SCSI | 2         | 0.32%   |
| SAS  | 1         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 372       | 74.7%   |
| AMD    | 126       | 25.3%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz       | 9         | 1.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 7         | 1.41%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 6         | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 1.2%    |
| Intel Core 2 Duo                        | 6         | 1.2%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 5         | 1%      |
| Intel Core i7-10510U CPU @ 1.80GHz      | 5         | 1%      |
| Intel Core i5-8350U CPU @ 1.70GHz       | 5         | 1%      |
| Intel Core i5-5300U CPU @ 2.30GHz       | 5         | 1%      |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 0.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 0.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 4         | 0.8%    |
| Intel Core i7-5500U CPU @ 2.40GHz       | 4         | 0.8%    |
| Intel Core i7-3520M CPU @ 2.90GHz       | 4         | 0.8%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 4         | 0.8%    |
| Intel Core i5-4200U CPU @ 1.60GHz       | 4         | 0.8%    |
| Intel Core i5-3337U CPU @ 1.80GHz       | 4         | 0.8%    |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz    | 4         | 0.8%    |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz | 4         | 0.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 0.8%    |
| AMD Ryzen 7 5800H with Radeon Graphics  | 4         | 0.8%    |
| AMD Ryzen 7 5700U with Radeon Graphics  | 4         | 0.8%    |
| AMD Ryzen 5 4500U with Radeon Graphics  | 4         | 0.8%    |
| Intel CPU Version                       | 3         | 0.6%    |
| Intel Core i7-8565U CPU @ 1.80GHz       | 3         | 0.6%    |
| Intel Core i7-6600U CPU @ 2.60GHz       | 3         | 0.6%    |
| Intel Core i7-3770 CPU @ 3.40GHz        | 3         | 0.6%    |
| Intel Core i7-2620M CPU @ 2.70GHz       | 3         | 0.6%    |
| Intel Core i5-8365U CPU @ 1.60GHz       | 3         | 0.6%    |
| Intel Core i5-8300H CPU @ 2.30GHz       | 3         | 0.6%    |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 0.6%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 3         | 0.6%    |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 0.6%    |
| Intel Core i5-3230M CPU @ 2.60GHz       | 3         | 0.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 3         | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 0.6%    |
| Intel Core i3-5005U CPU @ 2.00GHz       | 3         | 0.6%    |
| Intel Core i3-3217U CPU @ 1.80GHz       | 3         | 0.6%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 3         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 133       | 26.71%  |
| Intel Core i7           | 100       | 20.08%  |
| Other                   | 38        | 7.63%   |
| AMD Ryzen 5             | 38        | 7.63%   |
| AMD Ryzen 7             | 32        | 6.43%   |
| Intel Core i3           | 29        | 5.82%   |
| Intel Core 2 Duo        | 20        | 4.02%   |
| Intel Xeon              | 12        | 2.41%   |
| Intel Pentium           | 11        | 2.21%   |
| Intel Celeron           | 11        | 2.21%   |
| AMD Ryzen 9             | 7         | 1.41%   |
| Intel Core i9           | 6         | 1.2%    |
| AMD Ryzen 3             | 6         | 1.2%    |
| AMD A6                  | 6         | 1.2%    |
| AMD Ryzen 7 PRO         | 5         | 1%      |
| AMD FX                  | 4         | 0.8%    |
| AMD E1                  | 4         | 0.8%    |
| Intel Core 2 Quad       | 3         | 0.6%    |
| AMD A10                 | 3         | 0.6%    |
| Intel Pentium Dual-Core | 2         | 0.4%    |
| Intel Core m7           | 2         | 0.4%    |
| AMD Ryzen 5 PRO         | 2         | 0.4%    |
| AMD Ryzen 3 PRO         | 2         | 0.4%    |
| AMD Athlon              | 2         | 0.4%    |
| AMD A8                  | 2         | 0.4%    |
| AMD A4                  | 2         | 0.4%    |
| Intel Xeon Platinum     | 1         | 0.2%    |
| Intel Xeon Gold         | 1         | 0.2%    |
| Intel Pentium Silver    | 1         | 0.2%    |
| Intel Genuine           | 1         | 0.2%    |
| Intel Core m3           | 1         | 0.2%    |
| Intel Core 2            | 1         | 0.2%    |
| Intel Celeron Dual-Core | 1         | 0.2%    |
| Intel Atom              | 1         | 0.2%    |
| AMD Ryzen Threadripper  | 1         | 0.2%    |
| AMD Ryzen Embedded      | 1         | 0.2%    |
| AMD PRO A10             | 1         | 0.2%    |
| AMD Phenom II X4        | 1         | 0.2%    |
| AMD GX                  | 1         | 0.2%    |
| AMD EPYC                | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 172       | 34.47%  |
| 4       | 165       | 33.07%  |
| 6       | 38        | 7.62%   |
| 8       | 35        | 7.01%   |
| 12      | 28        | 5.61%   |
| 16      | 27        | 5.41%   |
| Unknown | 18        | 3.61%   |
| 24      | 5         | 1%      |
| 10      | 4         | 0.8%    |
| 32      | 2         | 0.4%    |
| 1       | 2         | 0.4%    |
| 28      | 1         | 0.2%    |
| 20      | 1         | 0.2%    |
| 14      | 1         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 487       | 97.79%  |
| 2      | 11        | 2.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 304       | 60.92%  |
| 1       | 177       | 35.47%  |
| Unknown | 18        | 3.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 89        | 17.87%  |
| Haswell       | 45        | 9.04%   |
| Skylake       | 44        | 8.84%   |
| IvyBridge     | 43        | 8.63%   |
| Unknown       | 37        | 7.43%   |
| Zen 3         | 29        | 5.82%   |
| SandyBridge   | 28        | 5.62%   |
| Penryn        | 27        | 5.42%   |
| Zen 2         | 24        | 4.82%   |
| Zen+          | 22        | 4.42%   |
| Broadwell     | 19        | 3.82%   |
| TigerLake     | 13        | 2.61%   |
| Westmere      | 9         | 1.81%   |
| CometLake     | 8         | 1.61%   |
| Piledriver    | 7         | 1.41%   |
| Excavator     | 7         | 1.41%   |
| Zen           | 6         | 1.2%    |
| Nehalem       | 5         | 1%      |
| IceLake       | 5         | 1%      |
| Core          | 5         | 1%      |
| Silvermont    | 4         | 0.8%    |
| Jaguar        | 4         | 0.8%    |
| Puma          | 3         | 0.6%    |
| K10           | 3         | 0.6%    |
| Goldmont plus | 3         | 0.6%    |
| Goldmont      | 3         | 0.6%    |
| K10 Llano     | 2         | 0.4%    |
| Bobcat        | 2         | 0.4%    |
| Bulldozer     | 1         | 0.2%    |
| Bonnell       | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 294       | 51.67%  |
| Nvidia                     | 144       | 25.31%  |
| AMD                        | 127       | 22.32%  |
| Matrox Electronics Systems | 2         | 0.35%   |
| ASPEED Technology          | 2         | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 29        | 5.02%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                    | 23        | 3.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 23        | 3.98%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                       | 20        | 3.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 20        | 3.46%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                    | 17        | 2.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 15        | 2.6%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 14        | 2.42%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                     | 12        | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 12        | 2.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 11        | 1.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 11        | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10        | 1.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 10        | 1.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 8         | 1.38%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7         | 1.21%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 7         | 1.21%   |
| AMD Lucienne                                                                | 7         | 1.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7         | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 6         | 1.04%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                       | 6         | 1.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 6         | 1.04%   |
| Intel Core Processor Integrated Graphics Controller                         | 6         | 1.04%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5         | 0.87%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 5         | 0.87%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 5         | 0.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 0.87%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4         | 0.69%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 4         | 0.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 4         | 0.69%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 4         | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4         | 0.69%   |
| AMD Barcelo                                                                 | 4         | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3         | 0.52%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3         | 0.52%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3         | 0.52%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 3         | 0.52%   |
| Nvidia C79 [GeForce 9400]                                                   | 3         | 0.52%   |
| Nvidia C79 [GeForce 9400M]                                                  | 3         | 0.52%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 3         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 220       | 44.09%  |
| 1 x AMD              | 109       | 21.84%  |
| 1 x Nvidia           | 83        | 16.63%  |
| Intel + Nvidia       | 52        | 10.42%  |
| 2 x Intel            | 13        | 2.61%   |
| Intel + AMD          | 9         | 1.8%    |
| AMD + Nvidia         | 5         | 1%      |
| 2 x AMD              | 3         | 0.6%    |
| 2 x Nvidia           | 1         | 0.2%    |
| 2 x AMD + 1 x ASPEED | 1         | 0.2%    |
| Nvidia + Matrox      | 1         | 0.2%    |
| Nvidia + ASPEED      | 1         | 0.2%    |
| 1 x Matrox           | 1         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 423       | 84.43%  |
| Proprietary | 78        | 15.57%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 362       | 71.68%  |
| 0.01-0.5   | 35        | 6.93%   |
| 1.01-2.0   | 34        | 6.73%   |
| 0.51-1.0   | 25        | 4.95%   |
| 3.01-4.0   | 18        | 3.56%   |
| 7.01-8.0   | 15        | 2.97%   |
| 5.01-6.0   | 8         | 1.58%   |
| 8.01-16.0  | 5         | 0.99%   |
| 2.01-3.0   | 2         | 0.4%    |
| 16.01-24.0 | 1         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 62        | 12.53%  |
| Samsung Electronics     | 56        | 11.31%  |
| LG Display              | 52        | 10.51%  |
| Chimei Innolux          | 46        | 9.29%   |
| BOE                     | 45        | 9.09%   |
| Dell                    | 26        | 5.25%   |
| Goldstar                | 20        | 4.04%   |
| Hewlett-Packard         | 15        | 3.03%   |
| Lenovo                  | 14        | 2.83%   |
| BenQ                    | 13        | 2.63%   |
| Apple                   | 13        | 2.63%   |
| Ancor Communications    | 12        | 2.42%   |
| Acer                    | 10        | 2.02%   |
| ASUSTek Computer        | 9         | 1.82%   |
| Sharp                   | 8         | 1.62%   |
| Philips                 | 8         | 1.62%   |
| Iiyama                  | 8         | 1.62%   |
| InfoVision              | 7         | 1.41%   |
| AOC                     | 5         | 1.01%   |
| PANDA                   | 4         | 0.81%   |
| Panasonic               | 4         | 0.81%   |
| LG Electronics          | 4         | 0.81%   |
| CSO                     | 4         | 0.81%   |
| Chi Mei Optoelectronics | 4         | 0.81%   |
| ViewSonic               | 3         | 0.61%   |
| Fujitsu Siemens         | 3         | 0.61%   |
| Vizio                   | 2         | 0.4%    |
| Sony                    | 2         | 0.4%    |
| Mi                      | 2         | 0.4%    |
| Idek Iiyama             | 2         | 0.4%    |
| HKC                     | 2         | 0.4%    |
| HannStar                | 2         | 0.4%    |
| Unknown                 | 2         | 0.4%    |
| ___                     | 1         | 0.2%    |
| WYT                     | 1         | 0.2%    |
| Unknown (XXX)           | 1         | 0.2%    |
| Unknown                 | 1         | 0.2%    |
| Toshiba                 | 1         | 0.2%    |
| SANYO                   | 1         | 0.2%    |
| SANSUI                  | 1         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24C650 SAM09E9 1920x1080 520x290mm 23.4-inch     | 3         | 0.6%    |
| Panasonic LCD Monitor MEI96A2 2880x1620 340x190mm 15.3-inch           | 3         | 0.6%    |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch          | 3         | 0.6%    |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 3         | 0.6%    |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 3         | 0.6%    |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 3         | 0.6%    |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 290x160mm 13.0-inch        | 3         | 0.6%    |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 3         | 0.6%    |
| Sharp LCD Monitor SHP1481 1920x1080 290x170mm 13.2-inch               | 2         | 0.4%    |
| Sharp LCD Monitor SHP1457 2560x1440 280x160mm 12.7-inch               | 2         | 0.4%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 2         | 0.4%    |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch  | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4542 1366x768 300x170mm 13.6-inch  | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch | 2         | 0.4%    |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch              | 2         | 0.4%    |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 2         | 0.4%    |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch           | 2         | 0.4%    |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 2         | 0.4%    |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch          | 2         | 0.4%    |
| InfoVision LCD Monitor IVO0489 1366x768 260x140mm 11.6-inch           | 2         | 0.4%    |
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                 | 2         | 0.4%    |
| CSO LCD Monitor CSO1402 2880x1800 300x190mm 14.0-inch                 | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 340x190mm 15.3-inch      | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 340x190mm 15.3-inch       | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 310x170mm 13.9-inch       | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch       | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 2         | 0.4%    |
| BOE LCD Monitor BOE08D5 1920x1080 340x190mm 15.3-inch                 | 2         | 0.4%    |
| BenQ EX3203R BNQ7F66 2560x1440 700x390mm 31.5-inch                    | 2         | 0.4%    |
| BenQ BL2405 BNQ8016 1920x1080 530x300mm 24.0-inch                     | 2         | 0.4%    |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch        | 2         | 0.4%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch        | 2         | 0.4%    |
| AU Optronics LCD Monitor AUO35EC 1366x768 340x190mm 15.3-inch         | 2         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 237       | 48.97%  |
| 1366x768 (WXGA)    | 85        | 17.56%  |
| 2560x1440 (QHD)    | 32        | 6.61%   |
| 3840x2160 (4K)     | 24        | 4.96%   |
| 1600x900 (HD+)     | 23        | 4.75%   |
| 1920x1200 (WUXGA)  | 13        | 2.69%   |
| 1680x1050 (WSXGA+) | 11        | 2.27%   |
| 1280x1024 (SXGA)   | 9         | 1.86%   |
| 1440x900 (WXGA+)   | 7         | 1.45%   |
| 1280x800 (WXGA)    | 7         | 1.45%   |
| 2880x1800          | 6         | 1.24%   |
| Unknown            | 5         | 1.03%   |
| 2560x1080          | 4         | 0.83%   |
| 1360x768           | 3         | 0.62%   |
| 3840x1600          | 2         | 0.41%   |
| 3840x1080          | 2         | 0.41%   |
| 3440x1440          | 2         | 0.41%   |
| 2560x1600          | 2         | 0.41%   |
| 9600x2160          | 1         | 0.21%   |
| 5120x1440          | 1         | 0.21%   |
| 4640x1080          | 1         | 0.21%   |
| 3200x1800 (QHD+)   | 1         | 0.21%   |
| 3200x1080          | 1         | 0.21%   |
| 3000x2000          | 1         | 0.21%   |
| 2806x900           | 1         | 0.21%   |
| 2736x1824          | 1         | 0.21%   |
| 2240x1400          | 1         | 0.21%   |
| 1920x540           | 1         | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 121       | 24.59%  |
| 13      | 102       | 20.73%  |
| 27      | 45        | 9.15%   |
| 24      | 32        | 6.5%    |
| 21      | 28        | 5.69%   |
| 23      | 23        | 4.67%   |
| Unknown | 23        | 4.67%   |
| 19      | 17        | 3.46%   |
| 12      | 17        | 3.46%   |
| 17      | 16        | 3.25%   |
| 31      | 14        | 2.85%   |
| 14      | 12        | 2.44%   |
| 11      | 9         | 1.83%   |
| 22      | 6         | 1.22%   |
| 34      | 4         | 0.81%   |
| 54      | 3         | 0.61%   |
| 40      | 3         | 0.61%   |
| 16      | 3         | 0.61%   |
| 29      | 2         | 0.41%   |
| 65      | 1         | 0.2%    |
| 60      | 1         | 0.2%    |
| 57      | 1         | 0.2%    |
| 48      | 1         | 0.2%    |
| 46      | 1         | 0.2%    |
| 43      | 1         | 0.2%    |
| 39      | 1         | 0.2%    |
| 37      | 1         | 0.2%    |
| 32      | 1         | 0.2%    |
| 28      | 1         | 0.2%    |
| 25      | 1         | 0.2%    |
| 20      | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 196       | 40.33%  |
| 501-600     | 94        | 19.34%  |
| 201-300     | 68        | 13.99%  |
| 401-500     | 45        | 9.26%   |
| Unknown     | 23        | 4.73%   |
| 351-400     | 21        | 4.32%   |
| 601-700     | 20        | 4.12%   |
| 1001-1500   | 8         | 1.65%   |
| 801-900     | 5         | 1.03%   |
| 701-800     | 5         | 1.03%   |
| 901-1000    | 1         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 374       | 81.66%  |
| 16/10   | 44        | 9.61%   |
| Unknown | 17        | 3.71%   |
| 5/4     | 8         | 1.75%   |
| 21/9    | 6         | 1.31%   |
| 3/2     | 4         | 0.87%   |
| 4/3     | 2         | 0.44%   |
| 32/9    | 2         | 0.44%   |
| 6/5     | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 92        | 18.78%  |
| 81-90          | 90        | 18.37%  |
| 201-250        | 80        | 16.33%  |
| 301-350        | 46        | 9.39%   |
| 101-110        | 26        | 5.31%   |
| 71-80          | 25        | 5.1%    |
| Unknown        | 23        | 4.69%   |
| 351-500        | 21        | 4.29%   |
| 151-200        | 19        | 3.88%   |
| 61-70          | 16        | 3.27%   |
| 121-130        | 14        | 2.86%   |
| 51-60          | 9         | 1.84%   |
| 501-1000       | 8         | 1.63%   |
| 251-300        | 7         | 1.43%   |
| More than 1000 | 6         | 1.22%   |
| 111-120        | 5         | 1.02%   |
| 141-150        | 2         | 0.41%   |
| 131-140        | 1         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 159       | 32.65%  |
| 51-100        | 134       | 27.52%  |
| 101-120       | 107       | 21.97%  |
| 161-240       | 47        | 9.65%   |
| Unknown       | 23        | 4.72%   |
| More than 240 | 10        | 2.05%   |
| 1-50          | 7         | 1.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 410       | 80.87%  |
| 2     | 52        | 10.26%  |
| 0     | 44        | 8.68%   |
| 3     | 1         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 308       | 41.34%  |
| Realtek Semiconductor                  | 221       | 29.66%  |
| Qualcomm Atheros                       | 66        | 8.86%   |
| Broadcom                               | 49        | 6.58%   |
| TP-Link                                | 14        | 1.88%   |
| Ralink Technology                      | 9         | 1.21%   |
| Nvidia                                 | 8         | 1.07%   |
| Sierra Wireless                        | 7         | 0.94%   |
| Samsung Electronics                    | 6         | 0.81%   |
| Ericsson Business Mobile Networks      | 6         | 0.81%   |
| MediaTek                               | 5         | 0.67%   |
| Marvell Technology Group               | 5         | 0.67%   |
| Edimax Technology                      | 5         | 0.67%   |
| Qualcomm                               | 4         | 0.54%   |
| ASUSTek Computer                       | 3         | 0.4%    |
| Ralink                                 | 2         | 0.27%   |
| Qualcomm Technologies                  | 2         | 0.27%   |
| Qualcomm Atheros Communications        | 2         | 0.27%   |
| NetGear                                | 2         | 0.27%   |
| Hewlett-Packard                        | 2         | 0.27%   |
| Generic                                | 2         | 0.27%   |
| Fibocom                                | 2         | 0.27%   |
| Aquantia                               | 2         | 0.27%   |
| Apple                                  | 2         | 0.27%   |
| Xiaomi                                 | 1         | 0.13%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.13%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.13%   |
| Microchip Technology                   | 1         | 0.13%   |
| Mercucys                               | 1         | 0.13%   |
| Lenovo                                 | 1         | 0.13%   |
| Huawei Technologies                    | 1         | 0.13%   |
| Google                                 | 1         | 0.13%   |
| Dell                                   | 1         | 0.13%   |
| D-Link                                 | 1         | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 155       | 16.67%  |
| Intel Wireless 8265 / 8275                                             | 30        | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 30        | 3.23%   |
| Intel Wi-Fi 6 AX200                                                    | 29        | 3.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 25        | 2.69%   |
| Intel Wireless 7265                                                    | 23        | 2.47%   |
| Intel Ethernet Connection (4) I219-LM                                  | 18        | 1.94%   |
| Intel Wireless 8260                                                    | 17        | 1.83%   |
| Intel Wireless 7260                                                    | 17        | 1.83%   |
| Intel I211 Gigabit Network Connection                                  | 13        | 1.4%    |
| Intel Wi-Fi 6 AX201                                                    | 12        | 1.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 12        | 1.29%   |
| Intel Ethernet Connection I219-LM                                      | 11        | 1.18%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 10        | 1.08%   |
| Intel Wireless 3165                                                    | 10        | 1.08%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 10        | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 10        | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 9         | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 0.86%   |
| Intel Ethernet Connection (2) I219-V                                   | 8         | 0.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 8         | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 8         | 0.86%   |
| Nvidia MCP79 Ethernet                                                  | 7         | 0.75%   |
| Intel Ethernet Controller I225-V                                       | 7         | 0.75%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 6         | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6         | 0.65%   |
| Ralink RT5370 Wireless Adapter                                         | 6         | 0.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 0.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 6         | 0.65%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 0.65%   |
| Intel Centrino Ultimate-N 6300                                         | 6         | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 5         | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 5         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 5         | 0.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 250       | 55.8%   |
| Realtek Semiconductor                 | 62        | 13.84%  |
| Qualcomm Atheros                      | 50        | 11.16%  |
| Broadcom                              | 33        | 7.37%   |
| TP-Link                               | 14        | 3.13%   |
| Ralink Technology                     | 9         | 2.01%   |
| Sierra Wireless                       | 5         | 1.12%   |
| MediaTek                              | 5         | 1.12%   |
| Edimax Technology                     | 5         | 1.12%   |
| ASUSTek Computer                      | 3         | 0.67%   |
| Ralink                                | 2         | 0.45%   |
| Qualcomm Technologies                 | 2         | 0.45%   |
| Qualcomm Atheros Communications       | 2         | 0.45%   |
| NetGear                               | 2         | 0.45%   |
| Mercucys                              | 1         | 0.22%   |
| Marvell Technology Group              | 1         | 0.22%   |
| D-Link                                | 1         | 0.22%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 30        | 6.67%   |
| Intel Wi-Fi 6 AX200                                            | 29        | 6.44%   |
| Intel Wireless 7265                                            | 23        | 5.11%   |
| Intel Wireless 8260                                            | 17        | 3.78%   |
| Intel Wireless 7260                                            | 17        | 3.78%   |
| Intel Wi-Fi 6 AX201                                            | 12        | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 12        | 2.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 2.22%   |
| Intel Wireless 3165                                            | 10        | 2.22%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 10        | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 1.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 1.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8         | 1.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 6         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 1.33%   |
| Ralink RT5370 Wireless Adapter                                 | 6         | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 6         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                 | 6         | 1.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 5         | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 5         | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 1.11%   |
| Intel Wireless 3160                                            | 5         | 1.11%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 5         | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 1.11%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 5         | 1.11%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4         | 0.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 4         | 0.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.89%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 4         | 0.89%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 4         | 0.89%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 0.89%   |
| Sierra Wireless EM7455                                         | 3         | 0.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 192       | 42.86%  |
| Intel                                  | 178       | 39.73%  |
| Broadcom                               | 25        | 5.58%   |
| Qualcomm Atheros                       | 23        | 5.13%   |
| Nvidia                                 | 8         | 1.79%   |
| Samsung Electronics                    | 6         | 1.34%   |
| Qualcomm                               | 4         | 0.89%   |
| Marvell Technology Group               | 4         | 0.89%   |
| Aquantia                               | 2         | 0.45%   |
| Apple                                  | 2         | 0.45%   |
| Xiaomi                                 | 1         | 0.22%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.22%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.22%   |
| Lenovo                                 | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 155       | 33.77%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 30        | 6.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 25        | 5.45%   |
| Intel Ethernet Connection (4) I219-LM                                  | 18        | 3.92%   |
| Intel I211 Gigabit Network Connection                                  | 13        | 2.83%   |
| Intel Ethernet Connection I219-LM                                      | 11        | 2.4%    |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 1.74%   |
| Intel Ethernet Connection (2) I219-V                                   | 8         | 1.74%   |
| Nvidia MCP79 Ethernet                                                  | 7         | 1.53%   |
| Intel Ethernet Controller I225-V                                       | 7         | 1.53%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 1.53%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 1.53%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 1.31%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 1.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 1.09%   |
| Qualcomm FP3                                                           | 4         | 0.87%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.87%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 0.87%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 0.87%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 4         | 0.87%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.65%   |
| Intel I350 Gigabit Network Connection                                  | 3         | 0.65%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.65%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3         | 0.65%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 0.65%   |
| Intel Ethernet Connection (13) I219-LM                                 | 3         | 0.65%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.65%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 3         | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.65%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 0.44%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                          | 2         | 0.44%   |
| Intel Ethernet Controller I226-V                                       | 2         | 0.44%   |
| Intel Ethernet Connection X722 for 1GbE                                | 2         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 430       | 50.06%  |
| WiFi     | 408       | 47.5%   |
| Unknown  | 12        | 1.4%    |
| Modem    | 9         | 1.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 287       | 54.56%  |
| WiFi     | 236       | 44.87%  |
| Modem    | 3         | 0.57%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 305       | 61.24%  |
| 1     | 172       | 34.54%  |
| 3     | 15        | 3.01%   |
| 4     | 4         | 0.8%    |
| 5     | 1         | 0.2%    |
| 0     | 1         | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 494       | 99%     |
| Yes  | 5         | 1%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 204       | 62.01%  |
| Realtek Semiconductor           | 28        | 8.51%   |
| Apple                           | 18        | 5.47%   |
| Broadcom                        | 15        | 4.56%   |
| Qualcomm Atheros Communications | 13        | 3.95%   |
| Lite-On Technology              | 10        | 3.04%   |
| IMC Networks                    | 7         | 2.13%   |
| Dell                            | 6         | 1.82%   |
| Cambridge Silicon Radio         | 6         | 1.82%   |
| ASUSTek Computer                | 4         | 1.22%   |
| Foxconn / Hon Hai               | 3         | 0.91%   |
| USI                             | 2         | 0.61%   |
| Toshiba                         | 2         | 0.61%   |
| Skylight Digital                | 2         | 0.61%   |
| MediaTek                        | 2         | 0.61%   |
| Hewlett-Packard                 | 2         | 0.61%   |
| Alps Electric                   | 2         | 0.61%   |
| Qcom                            | 1         | 0.3%    |
| HTC (High Tech Computer)        | 1         | 0.3%    |
| Edimax Technology               | 1         | 0.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 96        | 29.18%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 27        | 8.21%   |
| Intel AX200 Bluetooth                                       | 26        | 7.9%    |
| Intel AX201 Bluetooth                                       | 24        | 7.29%   |
| Realtek Bluetooth Adapter                                   | 13        | 3.95%   |
| Intel AX210 Bluetooth                                       | 10        | 3.04%   |
| Apple Bluetooth Host Controller                             | 9         | 2.74%   |
| Intel AX211 Bluetooth                                       | 6         | 1.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 6         | 1.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 5         | 1.52%   |
| Intel Wireless-AC 3168 Bluetooth                            | 5         | 1.52%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 5         | 1.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 5         | 1.52%   |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 1.22%   |
| Realtek Bluetooth 4.2 Adapter                               | 4         | 1.22%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 4         | 1.22%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 4         | 1.22%   |
| Apple Broadcom Built-in Bluetooth                           | 4         | 1.22%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 3         | 0.91%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 0.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 0.91%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 0.91%   |
| USI Qualcomm WCN685x Bluetooth Adapter                      | 2         | 0.61%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 2         | 0.61%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 2         | 0.61%   |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 0.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 2         | 0.61%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 0.61%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 0.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 0.61%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 0.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2         | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 0.61%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 2         | 0.61%   |
| Realtek Wireless Bluetooth Adapter                          | 1         | 0.3%    |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.3%    |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.3%    |
| Realtek Bluetooth 5.1 Adapter                               | 1         | 0.3%    |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.3%    |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 355       | 53.87%  |
| AMD                    | 143       | 21.7%   |
| Nvidia                 | 100       | 15.17%  |
| C-Media Electronics    | 10        | 1.52%   |
| Logitech               | 7         | 1.06%   |
| Lenovo                 | 5         | 0.76%   |
| Focusrite-Novation     | 5         | 0.76%   |
| SteelSeries ApS        | 3         | 0.46%   |
| GN Netcom              | 3         | 0.46%   |
| VIA Technologies       | 2         | 0.3%    |
| RODE Microphones       | 2         | 0.3%    |
| Realtek Semiconductor  | 2         | 0.3%    |
| JMTek                  | 2         | 0.3%    |
| Creative Technology    | 2         | 0.3%    |
| Creative Labs          | 2         | 0.3%    |
| Corsair                | 2         | 0.3%    |
| Trust                  | 1         | 0.15%   |
| Texas Instruments      | 1         | 0.15%   |
| Tenx Technology        | 1         | 0.15%   |
| Samson Technologies    | 1         | 0.15%   |
| Razer USA              | 1         | 0.15%   |
| No brand               | 1         | 0.15%   |
| Nam Tai E&E Products   | 1         | 0.15%   |
| Microsoft              | 1         | 0.15%   |
| Kingston Technology    | 1         | 0.15%   |
| Generalplus Technology | 1         | 0.15%   |
| DSEA A/S               | 1         | 0.15%   |
| Cambridge Audio        | 1         | 0.15%   |
| Anlya.cn               | 1         | 0.15%   |
| Unknown                | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 69        | 8.47%   |
| Intel Sunrise Point-LP HD Audio                                            | 60        | 7.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 40        | 4.91%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 39        | 4.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 25        | 3.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 21        | 2.58%   |
| Intel Haswell-ULT HD Audio Controller                                      | 20        | 2.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20        | 2.45%   |
| Intel 8 Series HD Audio Controller                                         | 20        | 2.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 19        | 2.33%   |
| Intel Broadwell-U Audio Controller                                         | 19        | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 18        | 2.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16        | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 16        | 1.96%   |
| AMD Starship/Matisse HD Audio Controller                                   | 14        | 1.72%   |
| AMD FCH Azalia Controller                                                  | 14        | 1.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 13        | 1.6%    |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 1.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 12        | 1.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12        | 1.47%   |
| Nvidia GK107 HDMI Audio Controller                                         | 10        | 1.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 1.23%   |
| AMD Kabini HDMI/DP Audio                                                   | 10        | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.1%    |
| Nvidia GP104 High Definition Audio Controller                              | 9         | 1.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 1.1%    |
| Intel 200 Series PCH HD Audio                                              | 9         | 1.1%    |
| Nvidia MCP79 High Definition Audio                                         | 8         | 0.98%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 0.98%   |
| AMD Radeon High Definition Audio Controller                                | 8         | 0.98%   |
| Nvidia GP108 High Definition Audio Controller                              | 7         | 0.86%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 7         | 0.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 0.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6         | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 0.61%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 0.61%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.61%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 153       | 24.8%   |
| SK hynix                     | 125       | 20.26%  |
| Kingston                     | 65        | 10.53%  |
| Micron Technology            | 59        | 9.56%   |
| Crucial                      | 44        | 7.13%   |
| Unknown                      | 29        | 4.7%    |
| G.Skill                      | 25        | 4.05%   |
| Corsair                      | 18        | 2.92%   |
| Unknown                      | 16        | 2.59%   |
| Ramaxel Technology           | 15        | 2.43%   |
| Elpida                       | 12        | 1.94%   |
| A-DATA Technology            | 9         | 1.46%   |
| Team                         | 5         | 0.81%   |
| GOODRAM                      | 5         | 0.81%   |
| Nanya Technology             | 4         | 0.65%   |
| Unknown (ABCD)               | 3         | 0.49%   |
| Transcend                    | 3         | 0.49%   |
| Timetec                      | 2         | 0.32%   |
| Patriot                      | 2         | 0.32%   |
| CSX                          | 2         | 0.32%   |
| Apacer                       | 2         | 0.32%   |
| Wodposit                     | 1         | 0.16%   |
| Undefined-00BA               | 1         | 0.16%   |
| Tammuz                       | 1         | 0.16%   |
| SpecTek Incorporated         | 1         | 0.16%   |
| Smart Modular                | 1         | 0.16%   |
| Smart                        | 1         | 0.16%   |
| Silicon Power                | 1         | 0.16%   |
| Shenzhen Longsys             | 1         | 0.16%   |
| S                            | 1         | 0.16%   |
| Patriot Memory (PDP Systems) | 1         | 0.16%   |
| Neo Forza                    | 1         | 0.16%   |
| Kingmax                      | 1         | 0.16%   |
| Hewlett-Packard              | 1         | 0.16%   |
| GSkill                       | 1         | 0.16%   |
| GeIL                         | 1         | 0.16%   |
| Avant                        | 1         | 0.16%   |
| Atermiter                    | 1         | 0.16%   |
| AMD                          | 1         | 0.16%   |
| 09490000802C                 | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 16        | 2.49%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 12        | 1.87%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 9         | 1.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 1.25%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 1.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.25%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.09%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 1.09%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.93%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3200MT/s            | 5         | 0.78%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 5         | 0.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.78%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s            | 5         | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.62%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.62%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.62%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.62%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.62%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s              | 4         | 0.62%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 4         | 0.62%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 4         | 0.62%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 3         | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 3         | 0.47%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 3         | 0.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.47%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.47%   |
| Samsung RAM M471A2G44AM0-CWE 16GiB SODIMM DDR4 3200MT/s          | 3         | 0.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.47%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.47%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 0.47%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3                     | 3         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.31%   |
| Team RAM Elite-1333 8GB DIMM DDR3 1333MT/s                       | 2         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 242       | 48.11%  |
| DDR3    | 195       | 38.77%  |
| LPDDR3  | 14        | 2.78%   |
| DDR2    | 14        | 2.78%   |
| DDR5    | 11        | 2.19%   |
| Unknown | 10        | 1.99%   |
| LPDDR4  | 9         | 1.79%   |
| LPDDR5  | 4         | 0.8%    |
| SDRAM   | 2         | 0.4%    |
| DDR     | 2         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 334       | 66.14%  |
| DIMM         | 139       | 27.52%  |
| Row Of Chips | 27        | 5.35%   |
| Chip         | 4         | 0.79%   |
| Unknown      | 1         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 230       | 41.59%  |
| 4096  | 172       | 31.1%   |
| 16384 | 83        | 15.01%  |
| 2048  | 45        | 8.14%   |
| 32768 | 20        | 3.62%   |
| 49152 | 2         | 0.36%   |
| 1024  | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 130       | 23.68%  |
| 3200    | 104       | 18.94%  |
| 2400    | 64        | 11.66%  |
| 2667    | 59        | 10.75%  |
| 1333    | 44        | 8.01%   |
| 2133    | 34        | 6.19%   |
| 1334    | 15        | 2.73%   |
| 800     | 13        | 2.37%   |
| 1867    | 12        | 2.19%   |
| 1067    | 12        | 2.19%   |
| 667     | 8         | 1.46%   |
| 5600    | 6         | 1.09%   |
| 2666    | 6         | 1.09%   |
| 3600    | 5         | 0.91%   |
| 1066    | 5         | 0.91%   |
| Unknown | 5         | 0.91%   |
| 4800    | 4         | 0.73%   |
| 6400    | 3         | 0.55%   |
| 1866    | 3         | 0.55%   |
| 4267    | 2         | 0.36%   |
| 4266    | 2         | 0.36%   |
| 3000    | 2         | 0.36%   |
| 975     | 2         | 0.36%   |
| 7467    | 1         | 0.18%   |
| 6000    | 1         | 0.18%   |
| 3733    | 1         | 0.18%   |
| 3333    | 1         | 0.18%   |
| 3266    | 1         | 0.18%   |
| 3066    | 1         | 0.18%   |
| 2933    | 1         | 0.18%   |
| 1639    | 1         | 0.18%   |
| 1200    | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 66.67%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                            | Computers | Percent |
|--------------------------------------------------------------------------------------------------|-----------|---------|
| HP Laser 107a Printer                                                                            | 1         | 33.33%  |
| HP HP LaserJet MFP M232-M237 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer | 1         | 33.33%  |
| Brother MFC-J485DW                                                                               | 1         | 33.33%  |

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
| Chicony Electronics                    | 68        | 24.55%  |
| Microdia                               | 29        | 10.47%  |
| Bison Electronics                      | 28        | 10.11%  |
| IMC Networks                           | 27        | 9.75%   |
| Realtek Semiconductor                  | 23        | 8.3%    |
| Sunplus Innovation Technology          | 18        | 6.5%    |
| Logitech                               | 12        | 4.33%   |
| Quanta                                 | 10        | 3.61%   |
| Lite-On Technology                     | 10        | 3.61%   |
| Suyin                                  | 8         | 2.89%   |
| Luxvisions Innotech Limited            | 8         | 2.89%   |
| Syntek                                 | 7         | 2.53%   |
| Alcor Micro                            | 5         | 1.81%   |
| Silicon Motion                         | 3         | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.08%   |
| Apple                                  | 3         | 1.08%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.72%   |
| Ricoh                                  | 2         | 0.72%   |
| Lenovo                                 | 2         | 0.72%   |
| Xiongmai                               | 1         | 0.36%   |
| USB Camera                             | 1         | 0.36%   |
| Trust                                  | 1         | 0.36%   |
| OmniVision Technologies                | 1         | 0.36%   |
| Nam Tai E&E Products                   | 1         | 0.36%   |
| Jiangxi Shinetech Optical              | 1         | 0.36%   |
| Intel                                  | 1         | 0.36%   |
| Importek                               | 1         | 0.36%   |
| BSD                                    | 1         | 0.36%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 21        | 7.55%   |
| Bison Integrated Camera                              | 13        | 4.68%   |
| Sunplus Integrated_Webcam_HD                         | 11        | 3.96%   |
| Microdia Integrated_Webcam_HD                        | 11        | 3.96%   |
| IMC Networks Integrated Camera                       | 11        | 3.96%   |
| Microdia Integrated Webcam                           | 8         | 2.88%   |
| Logitech HD Pro Webcam C920                          | 5         | 1.8%    |
| Lite-On Integrated Camera                            | 5         | 1.8%    |
| Chicony HD WebCam                                    | 5         | 1.8%    |
| Syntek Integrated Camera                             | 4         | 1.44%   |
| Realtek USB 2.0 PC Camera                            | 4         | 1.44%   |
| Realtek Integrated_Webcam_HD                         | 4         | 1.44%   |
| Luxvisions Innotech Limited Integrated Camera        | 4         | 1.44%   |
| Chicony USB2.0 HD UVC WebCam                         | 4         | 1.44%   |
| Realtek Integrated Webcam HD                         | 3         | 1.08%   |
| Quanta HP TrueVision HD Camera                       | 3         | 1.08%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 3         | 1.08%   |
| Microdia Integrated Webcam HD                        | 3         | 1.08%   |
| IMC Networks Realtek PC Camera                       | 3         | 1.08%   |
| IMC Networks EasyCamera                              | 3         | 1.08%   |
| Chicony Integrated Camera (1280x720@30)              | 3         | 1.08%   |
| Chicony EasyCamera                                   | 3         | 1.08%   |
| Bison ThinkPad Integrated Camera                     | 3         | 1.08%   |
| Bison SunplusIT Integrated Camera                    | 3         | 1.08%   |
| Suyin Integrated_Webcam_HD                           | 2         | 0.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314]             | 2         | 0.72%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 2         | 0.72%   |
| Realtek Lenovo EasyCamera                            | 2         | 0.72%   |
| Realtek Front Camera                                 | 2         | 0.72%   |
| Quanta VGA WebCam                                    | 2         | 0.72%   |
| Microdia USB Camera                                  | 2         | 0.72%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.72%   |
| Logitech HD Webcam C525                              | 2         | 0.72%   |
| Lenovo Integrated Webcam [R5U877]                    | 2         | 0.72%   |
| IMC Networks USB 2.0 UVC HD Webcam                   | 2         | 0.72%   |
| IMC Networks Realtek DMFT RGB                        | 2         | 0.72%   |
| IMC Networks Lenovo EasyCamera                       | 2         | 0.72%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 0.72%   |
| Chicony thinkpad t430s camera                        | 2         | 0.72%   |
| Chicony Realtek DMFT RGB                             | 2         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 30.67%  |
| Synaptics                  | 21        | 28%     |
| Shenzhen Goodix Technology | 7         | 9.33%   |
| Elan Microelectronics      | 7         | 9.33%   |
| Upek                       | 4         | 5.33%   |
| FocalTech Systems          | 3         | 4%      |
| STMicroelectronics         | 2         | 2.67%   |
| LighTuning Technology      | 2         | 2.67%   |
| AuthenTec                  | 2         | 2.67%   |
| Samsung Electronics        | 1         | 1.33%   |
| Next Biometrics            | 1         | 1.33%   |
| Fingerprint Cards          | 1         | 1.33%   |
| Broadcom                   | 1         | 1.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 10        | 13.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 9         | 12%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 6         | 8%      |
| Elan Fingerprint Sensor                                                      | 6         | 8%      |
| Shenzhen Goodix Fingerprint Reader                                           | 5         | 6.67%   |
| Validity Sensors Synaptics WBDI                                              | 4         | 5.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 4%      |
| Synaptics WBDI                                                               | 3         | 4%      |
| FocalTech Systems Fingerprint Reader                                         | 3         | 4%      |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 2         | 2.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 2.67%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 2.67%   |
| Shenzhen Goodix  Fingerprint Device                                          | 2         | 2.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 2         | 2.67%   |
| Validity Sensors VFS491                                                      | 1         | 1.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 1.33%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 1.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 1.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 1         | 1.33%   |
| Synaptics Fingerprint reader [HP G6]                                         | 1         | 1.33%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 1.33%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 1.33%   |
| Fingerprint Cards FPC Fingerprint Reader                                     | 1         | 1.33%   |
| Elan WBF Fingerprint Sensor                                                  | 1         | 1.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 1.33%   |
| AuthenTec AES2810                                                            | 1         | 1.33%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 1.33%   |

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
| 1     | 159       | 31.18%  |
| 2     | 155       | 30.39%  |
| 3     | 81        | 15.88%  |
| 0     | 66        | 12.94%  |
| 4     | 36        | 7.06%   |
| 5     | 13        | 2.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 329       | 39.03%  |
| Bluetooth                | 201       | 23.84%  |
| Net/wireless             | 102       | 12.1%   |
| Fingerprint reader       | 73        | 8.66%   |
| Card reader              | 63        | 7.47%   |
| Firewire controller      | 31        | 3.68%   |
| Network                  | 17        | 2.02%   |
| Sound                    | 12        | 1.42%   |
| Net/ethernet             | 8         | 0.95%   |
| Storage                  | 5         | 0.59%   |
| Storage/raid             | 1         | 0.12%   |
| Modem                    | 1         | 0.12%   |

