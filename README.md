<h1 align="center">
  <b>Abel DB</b>
</h1>

👋 ¡Hola! Soy **Abel DB**, apasionado por **ciberseguridad, programación y Linux**, actualmente en **La Paz, Bolivia**.  
Comparto mi aprendizaje en **Python, Linux, Tailwind y Laravel**, y creo contenido educativo en distintas plataformas.

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

## My Skills Include

<h4> Languages & Technologies </h4>
<span> 
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white">
</span>

<h4> IDE / Tools </h4>
<span>
  <img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-Terminal-000000?style=for-the-badge&logo=gnu-bash&logoColor=white">
</span>

<h4> Other Tools </h4>
<span>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white">
</span>

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
