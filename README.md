# Como usar o básico de Git
Primeiramente instale o git de acordo com o seu sistema operacional na sua máquina, usando o seguinte link:
> https://git-scm.com/downloads

Clique no link que representa o seu sistema operacional e siga os passos.

# Iniciando um repositório
Crie uma pasta para o seu projeto e depois inicie o central de comando do seu sistema operacional.

>Caso Windows: tecla windows + R

No terminal do Windows use o comando (dir) para abrir uma listagem dos arquivos e ver se a pasta que criamos está de fato aparecendo, em seguida digite (cd "nome da pasta") para entrar dentro da pasta, em seguida digite o comando (git init) para definir essa pasta como um repositório.

>Caso Linux (ubuntu): control + alt + T

No terminal do Linux use o comando (ls) para abrir uma listagem de todo os arquivos no pc e ver se a pasta que criamos está aparecendo, em seguida digite (cd "nome da pasta") para entrar dentro da pasta e em seguida digite o comando (git init) para definir essa pasta como um repostório.

Na pasta que você definiu como um repositório crie um arquivo que vai ser usado como um projeto, por exemplo: teste.py. Para adcionar esse projeto no git basta seguir os seguintes passos:

>git add "nome do projeto" <br>
- Exemplo: git add teste.py

>git commit "mensagem qualquer" <br>
- Exemplo: git commit "Meu primeiro commit"

>git push

E pronto! O seu projeto já está salvo no git.