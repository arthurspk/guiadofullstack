# Como contribuir com o Guia de Full-stack

Obrigado por querer melhorar este guia! Ele faz parte da rede [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil) e segue o **Padrão de Qualidade GDB v2**. Toda contribuição passa por revisão.

## O que você pode sugerir

- **Novo recurso** (curso, livro, canal, ferramenta, comunidade, artigo): abra uma issue com o template *Sugestão de recurso* ou envie um pull request.
- **Link quebrado ou desatualizado:** abra uma issue com o template *Link quebrado*, de preferência já com um substituto.
- **Correção de texto** (ortografia, descrição imprecisa, categoria errada): pull request direto.

## Critérios de aceitação

Um recurso só entra no guia se cumprir **todos** os itens:

1. **Link funcionando** — resposta HTTP 200 no momento da revisão (verificamos com [lychee](https://github.com/lycheeverse/lychee)).
2. **Conteúdo legal** — apenas fontes oficiais ou legitimamente gratuitas. Nada de cursos pagos redistribuídos, PDFs de livros protegidos ou "drives" de terceiros.
3. **Descrição de 1 linha** dizendo o que é e por que vale o clique.
4. **Marcadores corretos:** 💰 pago · 🇺🇸 em inglês · 🆕 publicado/atualizado em 2024–2026.
5. **Ordem:** dentro de cada seção, recursos em português e gratuitos vêm primeiro.
6. **Curadoria, não acumulação:** preferimos poucos recursos excelentes a muitos duvidosos. Se o guia já cobre o assunto com algo melhor, a sugestão pode ser recusada.

Formato de cada item:

```markdown
- [Nome do recurso](https://url-verificada) — 1 linha objetiva do que é e por que vale. 🆕 💰 🇺🇸
```

## Fluxo de pull request

1. Faça um fork e crie uma branch a partir da `main` (ex.: `feat/novo-curso-nodejs`).
2. Edite o `README.md` **e** a tradução `translations/README.en.md` (veja abaixo).
3. Rode a verificação de links antes de abrir o PR:
   ```bash
   lychee --no-progress './**/*.md'
   ```
4. Abra o PR preenchendo o checklist do template. Descreva o que mudou e por quê.
5. Um mantenedor revisa; ajustes podem ser pedidos antes do merge.

## Política de tradução

- O `README.md` em **português é a fonte**. A versão em inglês (`translations/README.en.md`) é uma tradução fiel dele.
- Todo PR que altera o README principal deve alterar também a tradução, na mesma seção. Se não puder traduzir, diga isso no PR para que alguém complete.
- Nomes próprios de cursos, livros e canais permanecem no idioma original.

## Código de conduta

Ao participar, você concorda com o nosso [Código de Conduta](./CODE_OF_CONDUCT.md).
