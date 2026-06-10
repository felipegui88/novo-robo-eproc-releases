# Robo Eproc IA — Releases

Repositório público de distribuição (apenas instaladores + manifesto; o
código-fonte fica em repo privado).

-  — controla versão, atualização e bloqueio remoto.
- Releases — instaladores (.exe Windows, .dmg macOS) + assets da IA local.

## Bloquear o uso (kill switch)
Edite `manifest.json` → `"bloqueado": true` e `"mensagem_bloqueio"`.

## Lançar nova versão
1. Build (`build_release.py`) → `gh release create vX.Y.Z <instalador>`
2. Atualize `versao_atual` + `url_instalador` no manifest.

Desenvolvido por Felipe Guinsani.
