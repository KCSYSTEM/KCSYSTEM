# KC System — Instruções para Claude Code

## Git: commit + push sempre juntos

Toda vez que uma alteração for commitada no KC System, o push para o GitHub deve ser feito imediatamente na mesma operação. Nunca deixar commit local sem subir.

```bash
git add index.html
git commit -m "mensagem"
git push
```

## Versionamento

- Incrementar patch: 7.52 → 7.53 → 7.54 ...
- Só ir para a próxima minor (7.x → 8.0) se o usuário pedir explicitamente
- Atualizar `<title>` e o badge na topbar

## Leitura do arquivo

- `C:\Lucas 2025\Piscicultura\KC system\Atual\index.html` pode ser lido sem pedir confirmação
