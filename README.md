# Alecrim — Protótipo navegável

Protótipo web mobile-first, sem backend, com o fluxo solicitado:

1. **Boas-vindas em chat obrigatório** — coleta nome, região, produção e objetivo. O restante do app só é liberado ao final.
2. **Conversa** — assistente com entrada por texto e microfone.
3. **Oportunidades** — três caminhos iniciais com detalhes navegáveis.
4. **Perfil** — resumo das informações coletadas e simulação de avisos por WhatsApp.

## Paleta
- Verde principal `#3D5A40`
- Terracota `#C1652F`
- Dourado `#D4A017`
- Fundo areia `#F5EFE6`
- Texto `#2B2620`

## Testar
Abra `index.html` no navegador. Para o microfone, prefira Chrome/Edge servido via HTTP:

```bash
python3 -m http.server 8080
```

Depois acesse `http://localhost:8080`.

O cadastro inicial é salvo no `localStorage`; use **Refazer informações iniciais** em Perfil para reiniciar.


## Logo

Esta versão aplica a logo oficial do Alecrim fornecida pela equipe no cabeçalho do protótipo.
