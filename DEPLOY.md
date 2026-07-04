# Deploy — SAL OCEANO Resorts

## Estrutura de pastas

```
sal-oceano-resorts/
├── index.html
├── imagens/
│   ├── img-hero.jpg        ← foto aérea do resort + piscina + praia
│   ├── img-lobby.jpg       ← lobby/recepção com plantas
│   ├── img-suites.jpg      ← suíte com vista do pôr do sol
│   ├── img-spa.jpg         ← sala de spa com produtos SAL OCEANO
│   ├── img-restaurante.jpg ← restaurante à beira-mar
│   └── img-coworking.jpg   ← espaço coworking com vista para o oceano
├── .gitignore
├── CNAME
├── DEPLOY.md
└── README.md
```

## Publicação via GitHub Pages

1. Crie um repositório no GitHub (ex: `sal-oceano-resorts`)
2. Faça upload de todos os arquivos desta pasta
3. Vá em **Settings → Pages → Source**: selecione `main` branch, pasta `/root`
4. O site ficará disponível em `https://seuusuario.github.io/sal-oceano-resorts`

### Com domínio customizado (resorts.saloceano.com.br)

1. O arquivo `CNAME` já contém `resorts.saloceano.com.br`
2. No seu provedor de DNS, adicione:
   - Tipo: `CNAME`
   - Nome: `resorts`
   - Valor: `seuusuario.github.io`
3. No GitHub Pages, ative **"Enforce HTTPS"**

## Formulário de contato (Formspree)

1. Acesse [formspree.io/new](https://formspree.io/new) e crie um formulário
2. Copie o ID gerado (ex: `xpzgabcd`)
3. Em `index.html`, substitua `YOUR_FORM_ID` pelo seu ID:
   ```html
   action="https://formspree.io/f/xpzgabcd"
   ```

## Imagens

Salve as fotos na pasta `imagens/` com os nomes exatos listados acima.
As fotos aparecem automaticamente no site.
