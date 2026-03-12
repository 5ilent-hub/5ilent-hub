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
      <!-- Slide 1 -->
      <div style="width: 50%; position: relative;">
        <img src="https://5ilent-hub.github.io/images/5ilent.png" alt="Tampilan Utama 5ilent-Mini" style="width: 100%; height: auto; display: block;"/>
        <div style="position: absolute; bottom: 0; left: 0; right: 0; background: linear-gradient(transparent, rgba(0,0,0,0.8)); color: white; padding: 20px; text-align: center;">
          <span style="background: #00F7F7; color: black; padding: 5px 15px; border-radius: 20px; font-weight: bold;">⚡ Tampilan Utama</span>
        </div>
      </div>
      
      <!-- Slide 2 - Gunakan gambar yang berbeda -->
      <div style="width: 50%; position: relative;">
        <img src="https://raw.githubusercontent.com/5ilent-hub/5ilent-mini/main/screenshot2.png" alt="Fitur Scanner 5ilent-Mini" style="width: 100%; height: auto; display: block;"/>
        <div style="position: absolute; bottom: 0; left: 0; right: 0; background: linear-gradient(transparent, rgba(0,0,0,0.8)); color: white; padding: 20px; text-align: center;">
          <span style="background: #00F7F7; color: black; padding: 5px 15px; border-radius: 20px; font-weight: bold;">⚡ Fitur Scanner</span>
        </div>
      </div>
    </div>
    
    <!-- Navigation Dots -->
    <div style="position: absolute; bottom: 20px; left: 50%; transform: translateX(-50%); display: flex; gap: 10px; z-index: 10;">
      <div style="width: 12px; height: 12px; background: #00F7F7; border-radius: 50%; cursor: pointer; box-shadow: 0 0 10px #00F7F7;" onclick="currentSlide(1)"></div>
      <div style="width: 12px; height: 12px; background: rgba(255,255,255,0.5); border-radius: 50%; cursor: pointer;" onclick="currentSlide(2)"></div>
    </div>
  </div>
  
  <p style="margin-top: 20px; color: #00F7F7; font-style: italic;">
    ✨ Geser otomatis setiap 5 detik | Klik dot untuk navigasi manual ✨
  </p>
</div>

<!-- Animasi CSS -->
<style>
@keyframes slide {
  0%, 40% { transform: translateX(0); }
  50%, 90% { transform: translateX(-50%); }
  100% { transform: translateX(0); }
}

.slider-container:hover .slider-wrapper {
  animation-play-state: paused;
}
</style>

<!-- JavaScript untuk kontrol manual -->
<script>
function currentSlide(n) {
  const slider = document.querySelector('div[style*="animation: slide"]');
  if (n === 1) {
    slider.style.transform = 'translateX(0)';
  } else {
    slider.style.transform = 'translateX(-50%)';
  }
}

// Pause animation saat mouse di atas dots
document.querySelectorAll('div[onclick]').forEach(dot => {
  dot.addEventListener('mouseenter', () => {
    document.querySelector('div[style*="animation: slide"]').style.animationPlayState = 'paused';
  });
  dot.addEventListener('mouseleave', () => {
    document.querySelector('div[style*="animation: slide"]').style.animationPlayState = 'running';
  });
});
</script>

---

## 🧐 **Fitur Unggulan**

<div align="center">
  <table>
    <tr>
      <td align="center" width="250" style="padding: 20px;">
        <img src="https://img.icons8.com/fluency/96/000000/scanner.png" width="50"/>
        <br />
        <b>📡 Scanner</b>
        <br />
        <sub>Scanning dengan presisi tinggi</sub>
      </td>
      <td align="center" width="250" style="padding: 20px;">
        <img src="https://img.icons8.com/fluency/96/000000/admin-settings-male.png" width="50"/>
        <br />
        <b>👑 Add Adminer</b>
        <br />
        <sub>Tambah admin dengan mudah</sub>
      </td>
      <td align="center" width="250" style="padding: 20px;">
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
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="nodejs"/>
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
