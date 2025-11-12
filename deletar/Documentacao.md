# 🗃️ Documentação

<br>
<p></p>

## 📦 Projeto: Personal Tech Icons

### 📝 Descrição
Este repositório contém **ícones personalizados em SVG** para uso em perfis GitHub, especialmente em arquivos `README.md`. O projeto nasceu da necessidade de incluir um ícone do Neo4j com melhor qualidade visual do que os disponíveis no DevIcons.

---

### 📁 Estrutura do Repositório

```
personal-tech-icons/
├── assets/                  # Imagens auxiliares e banner
├── icons/
│   └── svg/
│       └── neo4j/          # Ícones SVG personalizados do Neo4j
└── README.md               # Documentação do projeto
```

---

### 🛠️ Tecnologias Utilizadas

- **SVG**: formato vetorial para os ícones
- **Visual Studio Code**: editor usado para modificar os arquivos SVG
- **GitHub Pages / CDN (jsDelivr)**: para servir os ícones diretamente via URL

---

### 🎨 Como os ícones foram criados

1. Acessei o ícone original do Neo4j via DevIcons:  
   `https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/neo4j/neo4j-original-wordmark.svg`

2. Salvei o SVG localmente e editei no VSCode:
   - Ajustei o `viewBox` para centralizar verticalmente:  
     `viewBox="0 0 128 128"` → `viewBox="0 40 128 48"`
   - Modifiquei atributos `fill` para alterar cores.
   - Criei múltiplas versões com diferentes estilos.

3. Publiquei os ícones no GitHub e adaptei os links para uso via jsDelivr:
   - Exemplo:  
     `https://cdn.jsdelivr.net/gh/eddgh/personal-tech-icons/icons/svg/neo4j/neo4j-branco-azul.svg`

---

### 📌 Exemplos de Uso

```html
<img align="left" alt="Neo4j" title="Neo4j" width="70px"
     style="padding-right: 10px;"
     src="https://cdn.jsdelivr.net/gh/eddgh/personal-tech-icons/icons/svg/neo4j/neo4j-branco-azul.svg" />
```

---

### 📷 Visualizações

| Ícone Principal | Outras Versões |
|----------------|----------------|
| ![Neo4j Azul e Branco](https://cdn.jsdelivr.net/gh/eddgh/personal-tech-icons/icons/svg/neo4j/neo4j-branco-azul.svg) | ![](https://cdn.jsdelivr.net/gh/eddgh/personal-tech-icons/icons/svg/neo4j/neo4j-azul.svg), ![](https://cdn.jsdelivr.net/gh/eddgh/personal-tech-icons/icons/svg/neo4j/neo4j-branco.svg) |

---

