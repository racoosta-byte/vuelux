# VueLux

Ficheiros de atualização do VueLux (cifrados e assinados) e página de administração.

- `internal/` — edição interna (cifrada, só abre com o código do dono).
- `admin/` — página «Centro de comando» (vazia sem o token e a frase-passe do dono).
- `app/`, `install/`, `status.json` — versões, instalador e estado dos clientes (publicados pela página; cifrados/assinados).

Nada aqui é segredo: sem a chave do dono não se consegue assinar nem abrir nada.
