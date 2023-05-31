# Passo a passo
---
1. Baixe e instale o [Git](https://git-scm.com/). Com ele, vem o terminal Git Bash junto, que será útil.
2. Após baixado (ou caso já possua), abra o terminal Git Bash nesta pasta. Se ele tiver habilitado e seu Sistema Operacional for Windows, é possível abrir ele na pasta atual apenas clicando com o botão direito em qualquer parte da janela do Windows Explorer, e depois em "Git Bash Here".
<img src="https://github.com/thalesAlves758/clone-multiple-repo/blob/main/img/exemplo.png?raw=true" style="width: 600px" />
3. Em seguida, execute o seguinte comando:
```bash
chmod +x script.sh
```
Esse comando dará permissão ao script para ser executado.
4. Copie e cole os links de todos os repositórios desejados no arquivo links.txt, da mesma maneira em que já está preenchido para exemplificar, um embaixo do outro.
5. Execute o seguinte comando para clonar os repositórios em lote:
```bash
xargs -n 1 git clone < links.txt
```
6. A mágica foi feita