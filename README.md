content = """# Ahoi Matei

![JavaScript](https://img.shields.io/badge/JavaScript-000000?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Node.js](https://img.shields.io/badge/Node.js-000000?style=for-the-badge&logo=node.js&logoColor=5FA04E)
![npm](https://img.shields.io/badge/npm-000000?style=for-the-badge&logo=npm&logoColor=CB3837)
![PHP](https://img.shields.io/badge/PHP-000000?style=for-the-badge&logo=php&logoColor=777BB4)
![HTML5](https://img.shields.io/badge/HTML5-000000?style=for-the-badge&logo=html5&logoColor=E34F26)
![CSS3](https://img.shields.io/badge/CSS3-000000?style=for-the-badge&logo=css3&logoColor=1572B6)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-000000?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4)
![MySQL](https://img.shields.io/badge/MySQL-000000?style=for-the-badge&logo=mysql&logoColor=4479A1)
![Git](https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=F05032)
![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=FFFFFF)
![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=FCC624)
![Ubuntu](https://img.shields.io/badge/Ubuntu-000000?style=for-the-badge&logo=ubuntu&logoColor=E95420)
![Docker](https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=2496ED)
![Cloudflare](https://img.shields.io/badge/Cloudflare-000000?style=for-the-badge&logo=cloudflare&logoColor=F38020)
![AWS](https://img.shields.io/badge/AWS-000000?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
"""
path = "/mnt/data/README.md"
with open(path, "w", encoding="utf-8") as f:
    f.write(content)
print(path)
