# RESUMO DE GIT E GIT HUB #



**GIT E GIT HUB**

1. Benefícios:

- Controle de Versão;

- Armazenamento em Nuvem;

- Trabalho em Equipe;

- Melhorar seu Código;

- Reconhecimento;

  

2. Alguns Comandos básicos

   **Cd, dir, mkdir, del, rmdir, rm –rf.**

 

**Tópicos Fundamentais para entender o funcionamento do GIT**

 **- SHA1:** É um conjunto de funções hash criptográficas projetadas pela NSA – A ENCRIPTAÇÃO gera conjunto de caracteres idenficador de 40 dígitos.

**- Objetos fundamentais:**

​        **Blobs:** contém metadados do arquivo que armazena, tipo do objetivo, tamanho stringer e tamanho do arquivo entre outros;

​        **Trees(arvores) :** Armazena blobs

​        **Commits:** é o objeto que vai ajuntar tudo. Tree, parente, autor.

**- Sistema distribuído:** imagina que vc tem seu código, seu software, e vamos supor que esse repositório tem varias pessoas contribuindo, os commits é difícil ser alterado. 

**- Segurança;**

 

**EXEMPLO DE COMO GERAR CHAVE SSH E TOKEN**

Gerar chave:

ssh-keygen -t ed25519 -C [Hudson.ebert@uol.com.br](mailto:Hudson.ebert@uol.com.br)

comando para executar agente ssh è eval $(ssh-agent -s)

passar a chave è ssh-add id_ed25519

 

**COMANDO PARA PASSAR USER E EMAIL**

git config --global user.email "hudson.ebert@uol.com.br"

git config --global user.name HudsonEbert



**COMANDO GITS**

1. GIT INIT – INICIAR  Além de criar a pasta inicializa o repositório 

2. GIT ADD - ADICIONAR
3. GIT COMMIT - COMMIT
4. Git status – comando para usar e ver o status do arquivo
5. Git add*
6. Git add.
7. git remote add origin https://github.com/hudsonebert/livro-receitas.git
8. git push origin master
9. git clone repositório/link
10. git commit –m “comentário” è importante para comentário.

 

Untracked è staged

Unmodified è

​        Arquivos que não soferam modificações

Modified è staged

Staged è Quando coloca arquivo no staged, ele transforma em commit è retornando para Unmodifed.

**Tudo que está no Repositório Local tem que estar commitado senão não vai para repositório remote.**