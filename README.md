<h1 align="center">
  <b>Abel DB</b>
</h1>

👋 ¡Hola! Soy **Abel DB**, un apasionado por la **ciberseguridad, programación y Linux**, actualmente viviendo en **La Paz, Bolivia**.  
Comparto mi camino de aprendizaje en **Python, Linux, Tailwind y Laravel**, además de crear contenido en distintas plataformas.

---

## 🚀 Tecnologías que manejo
<div align="center">
  <img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=282828">
  <img src="https://img.shields.io/badge/-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black&labelColor=282828">
  <img src="https://img.shields.io/badge/-Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white&labelColor=282828">
  <img src="https://img.shields.io/badge/-Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white&labelColor=282828">
</div>

---

## 📊 Mis estadísticas de aprendizaje
<div align="center">
  <img src="https://img.shields.io/badge/Python-50%25-blue?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-50%25-black?style=for-the-badge&logo=linux&logoColor=white">
  <img src="https://img.shields.io/badge/Tailwind-75%25-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
  <img src="https://img.shields.io/badge/Laravel-75%25-FF2D20?style=for-the-badge&logo=laravel&logoColor=white">
</div>

---

## 🌎 Encuéntrame en
<div align="center">
  <a href="https://tiktok.com/@abeldb">
    <img src="https://img.shields.io/badge/TikTok-%23000000.svg?&style=for-the-badge&logo=tiktok&logoColor=white" />
  </a>
  <a href="https://youtube.com/@abeldb">
    <img src="https://img.shields.io/badge/YouTube-%23FF0000.svg?&style=for-the-badge&logo=youtube&logoColor=white" />
  </a>
  <a href="https://kick.com/abeldb">
    <img src="https://img.shields.io/badge/Kick-00FF00?style=for-the-badge&logo=kick&logoColor=black" />
  </a>
</div>

---

## 📊 Código de ejemplo en Python
```python
class AbelDB():
    
  def __init__(self):
    self.name = "Abel DB"
    self.username = "Abel-DB"
    self.location = "La Paz, Bolivia"
    self.skills = {
        "Python": "50%",
        "Linux": "50%",
        "Tailwind": "75%",
        "Laravel": "75%"
    }
  
  def show_info(self):
    print(f"👤 Nombre: {self.name}")
    print(f"🔗 GitHub: https://github.com/{self.username}")
    print(f"📍 Ubicación: {self.location}")
    print("⚡ Habilidades:")
    for skill, level in self.skills.items():
        print(f"   - {skill}: {level}")

if __name__ == '__main__':
    me = AbelDB()
    me.show_info()
