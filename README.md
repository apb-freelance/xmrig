# 🧠 Guía de Minería en Linux: Aprender y Minar a Largo Plazo

# Para ver el README.md original ir a README.md.original

## 🌱 Fase 1: Aprender y Hacer Pruebas

### ✅ Requisitos:
- Cualquier PC con Linux (preferiblemente con GPU dedicada).
- Sistema: Ubuntu o derivadas, Arch, o distros ligeras.

### ⚙️ Instalación de `xmrig` para Monero (XMR):
```bash
sudo apt update && sudo apt install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev -y
git clone https://github.com/xmrig/xmrig.git
cd xmrig && mkdir build && cd build
cmake ..
make -j$(nproc)
```

### 🔗 Recursos:
- Pool: [supportxmr.com](https://supportxmr.com)
- Wallet: Feather Wallet o Monero GUI Wallet

### 🎯 Objetivos:
- Ejecutar `xmrig` y empezar a minar con CPU.
- Aprender a usar pools y wallets.
- Medir el hash rate.
- Familiarizarte con logs y monitoreo por terminal.

---

## 🔁 Fase 2: Minado con GPU

### ✅ Requisitos:
- GPU recomendadas:
  - AMD: RX 6600, RX 6700 XT
  - NVIDIA: RTX 3060 Ti, 3070
- Instalar drivers propietarios:
  - AMD: `amdgpu-pro`, `opencl-amdgpu`
  - NVIDIA: `nvidia-driver`, `nvidia-utils`, `cuda`

### 🧰 Software recomendado:
- `lolMiner`
- `teamredminer` (para AMD)
- `nbminer`

### 🎯 Monedas a considerar:
- Monero (XMR)
- Ergo (ERG)
- Kaspa (KAS)
- Ethereum Classic (ETC)

### 🔍 Utilidades:
- Herramientas de monitoreo: `minerstat`, `hiveos`, `mmpOS`
- Sitio de rentabilidad: [whattomine.com](https://whattomine.com)

---

## 🏗️ Fase 3: Montar Rig o Minar en Serio

### ✅ Hardware:
- Placa base con múltiples ranuras PCIe
- Fuente de alimentación potente (1000W+)
- Varias GPUs
- Chasis tipo open-air rig
- Ventiladores y control de temperatura

### ⚙️ Software:
- **HiveOS**: distro especializada gratuita hasta 4 GPUs
- Panel de control web + monitoreo remoto

### 📌 Tips:
- Overclock y undervolt para eficiencia
- Configuraciones por archivo JSON o panel web

---

## ⚠️ Consejos para Minar a Largo Plazo

- **Electricidad**: verifica si el coste del kWh te permite ser rentable (ideal < 0,10 €/kWh)
- **Fiscalidad**: infórmate sobre la situación legal en tu país
- **Seguridad**: usa wallets frías o hardware wallets si acumulas
- **Diversificación**: considera cambiar de moneda según dificultad/red

---

## 🧰 Recursos adicionales
- [whattomine.com](https://whattomine.com)
- [minerstat.com](https://minerstat.com)
- [xmrig GitHub](https://github.com/xmrig/xmrig)
- [HiveOS](https://hiveos.farm/)
- [Feather Wallet](https://featherwallet.org/)

---


