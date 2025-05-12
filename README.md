# Criar conteúdo para o arquivo README.md do portfólio de Maria Rosa
readme_content = """
# Portfólio - Maria Rosa

Bem-vindo ao portfólio pessoal de **Maria Rosa**! 🌸

Este repositório contém uma página simples feita com HTML e Bootstrap, representando uma biografia profissional de forma elegante e acessível.

## 🔍 Sobre

O portfólio foi criado como um exercício de apresentação pessoal. A página inclui:

- Uma introdução com nome e imagem
- Um texto padrão de biografia
- Estilo responsivo com Bootstrap 5

## 🌐 Acesse o site publicado

Você pode visualizar o portfólio online aqui:  
➡️ [https://viviane1975M.github.io/portfolio-maria-rosa/](https://viviane1975M.github.io/portfolio-maria-rosa/)

## 🛠️ Tecnologias usadas

- HTML5
- Bootstrap 5
- GitHub Pages

## 📁 Arquivo principal

- `index.html` – página principal do portfólio

---

Feito com 💙 por Viviane
"""

# Salvar o README.md na mesma pasta do portfólio
from pathlib import Path
output_path = Path("/mnt/data/portfolio_maria_rosa")
readme_file = output_path / "README.md"
readme_file.write_text(readme_content.strip(), encoding="utf-8")

readme_file.as_posix()
