# Git e Github

 # Comandos

 - git int `inicia um repositório git na pasta onde foi inicializado`

 - git log `mostra o histórico de commits do projeto`

 - git status `mostra os status gerias do projeto, se existem modificações bem como os arquivos que foram modificados. Também mostra se está em estado staged`

 - git add . `Adiciona os arquivos no git e os deixa prontos para serem commitados`

 - git commit -m "message" `commita o projeto e pede uma mensagem para que seja o título do commit`
 
 - git restore --staged . `restaura o estado do projeto que já está em estado staged para o estado normal`

 -git reset -u soft `descommita o seu último commit`

# Github 

  # Comandos

  - git push -u origin main `cria um repositório no github com o projeto que foi iniciado`

  - git push `envia as alterações feitas no projeto para o repositório do github`

  - .gitignore `É um formato de arquivo que priva os arquivos especificados dentro dele, de serem enviados para o github`

  - git rm -r --cached . `comando que irá limpar o cache do git e isso irá permitir com que um arquivo seja adicionado no .gitignore e não apareça no github (EX: o arquivo foi mandado em um commit anterior mas agora eu quero que ele permaneça como gitignore e não apareça mais no meu github)`