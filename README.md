# Dentora | Odontologia Integrada & Estética Avançada

Site estático de uma página para clínica odontológica, desenvolvido com HTML + Tailwind CSS (via CDN).

## Estrutura

```
├── index.html          # Página principal
├── assets/
│   ├── css/            # Estilos customizados (se houver)
│   ├── js/             # Scripts customizados (se houver)
│   └── images/         # Imagens do site
├── DESIGN.md           # Especificações de design
├── vercel.json         # Configuração de deploy na Vercel
├── package.json        # Metadata do projeto
├── .gitignore          # Arquivos ignorados pelo Git
└── README.md           # Este arquivo
```

## Deploy

### Vercel (recomendado)
1. Conecte este repositório ao Vercel.
2. O deploy é automático a cada push na `main`.
3. Não há build step — o site é servido como arquivos estáticos.

### Hostinger / HostGator (cPanel / FTP)
1. Faça upload de todo o conteúdo desta pasta (exceto `.git/`, `node_modules/`, `skill site/`) para o `public_html/` via FTP ou Gerenciador de Arquivos do cPanel.
2. O `index.html` deve ficar na raiz do `public_html/`.

## Desenvolvimento

Rode localmente:

```bash
python -m http.server 5173
```

Acesse: http://localhost:5173

## Tecnologias

- HTML5
- Tailwind CSS (CDN)
- Google Fonts (Inter, Manrope, Material Symbols)
