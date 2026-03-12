<h1 align="center" id="title">⚡ 5ilent-Mini ⚡</h1>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue?style=for-the-badge" alt="version"/>
  <img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge" alt="license"/>
  <img src="https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge" alt="build"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=25&duration=3000&pause=500&color=00F7F7&center=true&vCenter=true&width=435&lines=Selamat+datang!;Ini+adalah+proyek+keren!;Dibuat+dengan+❤️" alt="Typing SVG" />
</p>

---

## 📸 Screenshot / Demo

<div align="center">
  
  <!-- Container Slider -->
  <div style="position: relative; width: 100%; max-width: 600px; margin: 0 auto; overflow: hidden; border-radius: 15px; box-shadow: 0 20px 40px rgba(0,247,247,0.2);">
    
    <!-- Slide wrapper -->
    <div style="display: flex; width: 200%; animation: slide 10s infinite;">
      <!-- Slide 1 - Menggunakan gambar placeholder yang pasti muncul -->
      <div style="width: 50%; position: relative;">
        <img src="https://via.placeholder.com/600x400/00F7F7/000000?text=5ilent-Mini+Main+View" alt="Tampilan Utama 5ilent-Mini" style="width: 100%; height: auto; display: block; border-radius: 10px;"/>
        <div style="position: absolute; bottom: 0; left: 0; right: 0; background: linear-gradient(transparent, rgba(0,0,0,0.8)); color: white; padding: 20px; text-align: center; border-radius: 0 0 15px 15px;">
          <span style="background: #00F7F7; color: black; padding: 5px 15px; border-radius: 20px; font-weight: bold;">⚡ Tampilan Utama</span>
        </div>
      </div>
      
      <!-- Slide 2 - Menggunakan gambar placeholder yang pasti muncul -->
      <div style="width: 50%; position: relative;">
        <img src="https://via.placeholder.com/600x400/FF6B6B/000000?text=Scanner+Feature" alt="Fitur Scanner 5ilent-Mini" style="width: 100%; height: auto; display: block; border-radius: 10px;"/>
        <div style="position: absolute; bottom: 0; left: 0; right: 0; background: linear-gradient(transparent, rgba(0,0,0,0.8)); color: white; padding: 20px; text-align: center; border-radius: 0 0 15px 15px;">
          <span style="background: #00F7F7; color: black; padding: 5px 15px; border-radius: 20px; font-weight: bold;">⚡ Fitur Scanner</span>
        </div>
      </div>
    </div>
    
    <!-- Navigation Dots -->
    <div style="position: absolute; bottom: 20px; left: 50%; transform: translateX(-50%); display: flex; gap: 10px; z-index: 10;">
      <div style="width: 12px; height: 12px; background: #00F7F7; border-radius: 50%; cursor: pointer; box-shadow: 0 0 10px #00F7F7;"></div>
      <div style="width: 12px; height: 12px; background: rgba(255,255,255,0.5); border-radius: 50%; cursor: pointer;"></div>
    </div>
  </div>
  
  <p style="margin-top: 20px; color: #00F7F7; font-style: italic;">
    ✨ Geser otomatis setiap 5 detik ✨
  </p>
</div>

<!-- Animasi CSS -->
<style>
@keyframes slide {
  0%, 40% { transform: translateX(0); }
  50%, 90% { transform: translateX(-50%); }
  100% { transform: translateX(0); }
}

div[style*="animation: slide"]:hover {
  animation-play-state: paused;
}

/* Styling untuk gambar */
img {
  max-width: 100%;
  height: auto;
  display: block;
}
</style>

---

## 🧐 **Fitur Unggulan**

<div align="center">
  <table>
    <tr>
      <td align="center" width="250" style="padding: 15px; border: 1px solid #00F7F7; border-radius: 10px; margin: 5px;">
        <img src="https://img.icons8.com/fluency/96/000000/scanner.png" width="50"/>
        <br />
        <b>📡 Scanner</b>
        <br />
        <sub>Scanning dengan presisi tinggi</sub>
      </td>
      <td align="center" width="250" style="padding: 15px; border: 1px solid #00F7F7; border-radius: 10px; margin: 5px;">
        <img src="https://img.icons8.com/fluency/96/000000/admin-settings-male.png" width="50"/>
        <br />
        <b>👑 Add Adminer</b>
        <br />
        <sub>Tambah admin dengan mudah</sub>
      </td>
      <td align="center" width="250" style="padding: 15px; border: 1px solid #00F7F7; border-radius: 10px; margin: 5px;">
        <img src="https://img.icons8.com/fluency/96/000000/lightning-bolt.png" width="50"/>
        <br />
        <b>⚡ Performa Tinggi</b>
        <br />
        <sub>Ringan dan cepat</sub>
      </td>
    </tr>
  </table>
</div>

## 🛠️ **Tech Stack**

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="python"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="js"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="react"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="html5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="css3"/>
</p>

## 📦 **Instalasi**

```bash
# Clone repository
git clone https://github.com/5ilent-hub/5ilent-mini.git

# Masuk ke direktori
cd 5ilent-mini

# Install dependencies
pip install -r requirements.txt

# Jalankan
python main.py
