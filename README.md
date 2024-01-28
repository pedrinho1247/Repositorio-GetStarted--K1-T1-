# Chave SSH no Git 

- Pode ser gerada por conta e não necessariamente por repositório
- Para gerar a chave:
-       ssh-keygen
- Navegue até o local: 
-        Local: ~/.ssh
- Por padrão o arquivo que contém a chave é: **Arquivo: id_rsa.pub**
- Após isso basta adicionar a chave ao ssh no GitHub

- Caso queira alterar o nome do arquivo da chave, quando existem várias chaves
- Abra o terminal e digite:
-       eval $(ssh-agent)
-       ssh-add <caminho _nova_ chave>
