# install-proxmox-di-virtual-box

Proxmox VE adalah platform server sumber terbuka untuk virtualisasi perusahaan. Sebagai distribusi Linux berbasis Debian, Proxmox menggunakan kernel Ubuntu yang dimodifikasi untuk menjalankan beberapa mesin virtual dan wadah pada satu server. Sehingga dapat menerapkan dan mengelola lingkungan virtual dari konsol online atau baris perintah, memastikan ketersediaan yang mudah dan cepat. 


![Logo](https://raw.githubusercontent.com/danimaulana/Cara-install-proxmox-di-vm/main/Image/Traditional-and-virtual-architecture-server-comparison.jpg)



## Prasyarat

- Perangkat lunak virtualisasi/vm
- Iso image Proxmox
- enable nested vt-x/amd-v virtualbox



## Setup vm Virtual Box

- Setup vm di virtual box

```bash
  type linux
  version debian 64 bit
```

![Logo](https://raw.githubusercontent.com/danimaulana/Cara-install-proxmox-di-vm/main/Image/createvirtualmachine-1.png)

```bash
  memory 2gb
  processors 1
```

![Logo](https://raw.githubusercontent.com/danimaulana/Cara-install-proxmox-di-vm/main/Image/createvirtualmachine-2.png)

```bash
  storage 20gb
```

![Logo](https://raw.githubusercontent.com/danimaulana/Cara-install-proxmox-di-vm/main/Image/createvirtualmachine-3.png)

```bash
  finish
```

![Logo](https://raw.githubusercontent.com/danimaulana/Cara-install-proxmox-di-vm/main/Image/createvirtualmachine-4.png)
