# install-proxmox-di-virtual-box

Proxmox VE adalah platform server sumber terbuka untuk virtualisasi perusahaan. Sebagai distribusi Linux berbasis Debian, Proxmox menggunakan kernel Ubuntu yang dimodifikasi untuk menjalankan beberapa mesin virtual dan wadah pada satu server. Sehingga dapat menerapkan dan mengelola lingkungan virtual dari konsol online atau baris perintah, memastikan ketersediaan yang mudah dan cepat. 


![Logo](https://www.researchgate.net/publication/348528986/figure/fig1/AS:980473941606402@1610774612842/Traditional-and-virtual-architecture-server-comparison.jpg)



## Prasyarat

- Perangkat lunak virtualisasi/vm
- Iso image Proxmox
- enable nested vt-x/amd-v virtualbox



## Setup vm di virtual box

```bash
  - version debian 64 bit
  - type linux
```

![Image](https://raw.githubusercontent.com/danimaulana/Cara-install-proxmox-di-vm/main/Image/createvirtualmachine-1.png)

```bash
  - memory 2gb

  - processors 1
```

![Image](https://raw.githubusercontent.com/danimaulana/Cara-install-proxmox-di-vm/main/Image/createvirtualmachine-2.png)

```bash
  - storage 20gb
```

![Image](https://raw.githubusercontent.com/danimaulana/Cara-install-proxmox-di-vm/main/Image/createvirtualmachine-3.png)

```bash
  - finish
```

![Image](https://raw.githubusercontent.com/danimaulana/Cara-install-proxmox-di-vm/main/Image/createvirtualmachine-4.png)

```bash
  - enable nested vt-x/amd-v virtualbox
```

![Image](https://raw.githubusercontent.com/danimaulana/Cara-install-proxmox-di-vm/main/Image/createvirtualmachine-5.png)

```bash
  - network bridge adapter
```

![Image](https://raw.githubusercontent.com/danimaulana/Cara-install-proxmox-di-vm/main/Image/createvirtualmachine-6.png)



## Setup proxmox

```bash
  - Masukkan ISO
```
![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install1.png)

```bash
  - Install proxmox ve {enter} untuk menginstal
```
![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install2.png)

```bash
  - {enter}
```
![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install3.png)

```bash
  - pilih target hardisk
```
![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install4.png)

```bash
  - Set {negara,time,keyboard} proxmox server
```
![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install5.png)

```bash
  - Masukkan password dan email
```
![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install6.png)

```bash
  - Masukkan hostname, ip addres, dan gateway. DNS 8.8.8.8
```
![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install7.png)

```bash
  - {enter}
```
![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install8.png)

```bash
  - Loading instalasi 
```
![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install9.png)

```bash
  - Instalasi berhasil
```
![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install10.png)

```bash
  - remove disk
```
![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install11.png)

```bash
  - matikan vm lalu nyalakan kembali vm
```
![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install12.png)


![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install13.png)


![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install14.png)


![Image](https://raw.githubusercontent.com/danimaulana/install-proxmox-di-virtual-box/main/Image/proxmox-install15.png)
