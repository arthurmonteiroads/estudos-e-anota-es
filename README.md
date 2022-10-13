 # **Git / GitHub** 

**Git – ferramenta de versionamento de código** 

**GitHub -** 

- **Controle de versão** 

- **Armazenamento em nuvem** 
- **Trabalho em equipe** 
- **Melhorar o seu código** 
- **Reconhecimento** 

 

 

**GUI** **(GRAPHIC USER INTERFACE)** **x CLI** **(COMMAND LINE INTERFACE)** 

**O que vamos aprender?** 

- Mudar de pastas 
- Listar as pastas 

- Criar as pastas/arquivos 
- Deletar pastas/arquivos 

| **Comando**                    | **Windows**     | **Linux**          |
| ------------------------------ | --------------- | ------------------ |
| **Mudar de pastas**            | **cd**          | **cd**             |
| **Listar as pastas**           | **dir**         | **ls**             |
| **Criar as pastas/arquivos**   | **mkdir**       | **mkdir**          |
| **Deletar as pastas/arquivos** | **del / rmdir** | **rm / rf**        |
| **Limpar a tela**              | **cls**         | **Clear / ctrl L** |
| **Autocompletar**              | **tab**         | **tab**            |
| **Retornar**                   | **cd ..**       | **cd ..**          |

 

**Como o git funciona por baixo dos panos** 

- **Sha1** 
- **Secure hash algorithm (algoritmo de hash seguro), é um conjunto de funções hash criptográficas projetadas pela NSA** 
- **A encriptação gera conjunto de caracteres identificador de 40 dígitos (único)** 

- **É uma forma curta de representar um arquivo cla** 
- **Objetos internos** 
- **Blobs** 
- Cria um sha com metadados do git (o tipo do objeto, o tamanho da string...) 
- **Trees** 

- Armazenam BLOBS (guarda o nome do arquivo) (também possuem o sha e metadados) 
- **Commits** 
- Aponta para uma árvore, aponta para um parente (ultimo commit realizado antes dele), aponta para um autor, aponta para uma mensagem, possuem timestamp (carimbo de tempo) 
- Também possui um sha1 
- **Sistema distribuído** 

- **Segurança** 

 

**Chaves SSH e Tokens** 

 

**Chave SSH** **(é** **uma forma de estabelecer uma conexão segura e encriptada entre duas máquinas)** 

- Uma é pública e outra privada 

 

**Iniciando o git e criando um commit** 

| Iniciar o git           | git init   |
| ----------------------- | ---------- |
| Iniciar o versionamento | git add    |
| Criar um commit         | git commit |

 

 

 

|                                                              | **TRACKED**                                                  |                                                     |            |
| ------------------------------------------------------------ | ------------------------------------------------------------ | --------------------------------------------------- | ---------- |
| **Untracked**                                                | **Unmodified**                                               | **Modified**                                        | **Staged** |
| **Adiciona o arquivo -------------------------------------------------------------------------------------------------->** |                                                              |                                                     |            |
|                                                              | **Edita o arquivo ----------------------------->**           |                                                     |            |
|                                                              |                                                              | **“stage” o arquivo ---------------------------->** |            |
| **<----------------------------------- Remove o arquivo**    |                                                              |                                                     |            |
|                                                              | **<----------------------------------------------------------------------------------------- Commit** |                                                     |            |

 

 

 
