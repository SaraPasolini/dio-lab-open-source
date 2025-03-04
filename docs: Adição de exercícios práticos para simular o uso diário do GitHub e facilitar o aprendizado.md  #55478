
# Melhoria de aprendizado para iniciantes no GitHub






Essa solução foi desenvolvida com o objetivo de demonstrar, de forma clara e eficiente para iniciantes, como:

- Clonar repositórios diretamente do GitHub.

- Configurar e utilizar o GitHub no VSCode para uma experiência mais fluida e integrada.

- Aplicar comandos essenciais na prática, facilitando o entendimento dos conceitos fundamentais do versionamento de código.

Desta maneira, os usuários poderão aprender de maneira imersiva, enfrentando desafios reais e compreendendo melhor as particularidades da plataforma.

**Observações** : Todo o conteúdo aqui descrito será aplicado diretamente entre VS Code e no GitHub, sendo implementado nesses ambientes de desenvolvimento.





## Preparação do ambiente com as ferramentas e dependências necessárias.

Para darmos início a clonagem de repositórios e demais atividades é necessário ter em sua máquina as seguintes ferramentas:

- [Visual Studio Code](https://code.visualstudio.com/download) - Disponível para Windows, Linux e Mac.

- [GIT](https://git-scm.com/downloads) - Sistema de controle de versões distribuído, disponível para Windows, Linux e Mac.

- [GITUB](https://desktop.github.com/download/) - Plataforma que permite o desenvolvimento colaborativo de códigos.

**Observações** : Se você já possuí todas essas dependências instaladas em sua máquina, certifique-se de que estão na versão mais recente, ou seja, se estão devidamente atualizadas.


## Instalando e configurando o Visual Studio Code

**INSTALAÇÃO** 

**1**- Abra seu navegador e acesse o site oficial do VS Code: [Visual Studio Code](https://code.visualstudio.com/download).

**2**- Na página inicial, clique no botão **Download for** Windows, macOS ou Linux, conforme seu sistema operacional.

**3**- Após o download, **abra o instalador** (*.exe* no Windows, .*dmg* no macOS ou o *pacote correspondente* no Linux).

**4**- Marque a opção **"Aceito os termos do contrato"** e clique em **Avançar**.

**5**- Escolha a pasta onde deseja instalar o VS Code (ou deixe o padrão recomendado).

**6**- Na tela de opções adicionais, marque **"Adicionar ao PATH"** (opcional, mas recomendado para usar o VS Code no terminal).

**7**- Clique em Instalar e aguarde o processo ser concluído,ao finalizar, marque a opção **"Executar o Visual Studio Code"** e clique em *Concluir*.

**CONFIGURAÇÃO INICIAL** 

- Ao abrir o VS Code pela primeira vez, ele exibirá sugestões de extensões úteis, você pode personalizar o tema e instalar extensões conforme suas necessidades.

- Se tiver dúvidas sobre as extensões , consulte : [Gerenciar Extensões](https://learn.microsoft.com/pt-br/visualstudio/ide/finding-and-using-visual-studio-extensions?view=vs-2022).


**VERIFICAR A INSTALAÇÃO** 

- Para garantir que o VS Code foi instalado corretamente, abra o **terminal** (**Prompt de Comando**, **PowerShell** ou **Terminal do macOS/Linux**) e digite:

```bash
  code --version
```

- Se o número da versão for exibido, a instalação foi concluída corretamente.



## Instalando e configurando o Git

**INSTALAÇÃO - WINDOWS** 

**1**- Abra seu navegador e acesse o site oficial do [GIT](https://git-scm.com/downloads).

**2**- Clique em **Download for Windows** e baixe o instalador.

**3**- Execute o arquivo *.exe* baixado.

**4**- Durante a instalação, mantenha as opções padrão recomendadas e clique em **Next** até concluir.

**Observação:** Certifique-se que a opção **Git-Bash** esteja selecionada, leia todas as opções com atenção.

**5**- Após a instalação, reinicie o VS Code.


**INSTALAÇÃO - macOS (via Homebrew)** 

**1**- Abra o Terminal e digite: 

```bash
  brew install git
```

**2**- Aguarde a instalação e depois verifique com :

```bash
  git --version
```


**INSTALAÇÃO - Linux (Debian/Ubuntu)** 

**1**- Abra o Terminal e digite: 

```bash
  sudo apt update && sudo apt install git -y
```

**2**- Aguarde a instalação e depois verifique com :

```bash
  git --version
```

## Integrando o Git ao VS Code

- Após instalar o Git, abra o VS Code.

- No **menu lateral** , clique no ícone de *Controle de Código-Fonte* (parece um "ramo" com três pontos).

![Image](https://assets.digitalocean.com/articles/git-integration-in-visual-studio-code/6.png)

- Se aparecer a mensagem **"Nenhum repositório aberto"**, significa que o Git está pronto para uso.

![Image](https://code.visualstudio.com/assets/docs/sourcecontrol/github/git-clone-button.png)

- Agora, você pode clonar repositórios do GitHub, fazer commits e sincronizar seus projetos diretamente pelo VS Code.

- Se tiver dúvidas ou erros específicos , consulte : [Controle de Origem](https://code.visualstudio.com/docs/sourcecontrol/github#sourcecontrol-articles). 


## Configurar o Git com o GitHub

- Antes de começar a usar o GitHub no VS Code, é necessaário configurar *nome* e *e-mail*.

- Você pode utilizar o **Git-Bash** do próprio Git, ou utlizar o terminal do VS CODE.

- Como estamos utilizando o VS CODE , faremos pelo **terminal do VS CODE**.

**1**- No terminal digite :

```bash
  git config --global user.name "Seu Nome"
```


**2**- Depois, configure seu e-mail **(use o mesmo e-mail cadastrado no GitHub)**:

```bash
  git config --global user.email "seuemail@example.com"
```

**3**- Para verificar as configurações, use:

```bash
 git config --list
```

- Se as informações aparecerem corretamente, a configuração foi bem-sucedida.

## Conectar o GitHub ao VS Code

**1** - Gerar um Token de Acesso no GitHub :

- O VS Code não aceita login direto no GitHub por senha. É necessário gerar um **Token de Acesso Pessoal (PAT)**

- Acesse : [GITHUB TOKENS](https://github.com/settings/tokens).

- Clique em **Generate new token (classic)**.

- Marque as permissões básicas :

   - **repo** → Para acessar repositórios.
   - **workflow** → Para gerenciar ações no GitHub.
   - **admin:repo_hook** → Para configurar webhooks.

- Role para baixo, clique em *Generate Token* e **copie** o token.


**2** - Autenticar o GitHub no VS Code :

Agora, precisamos usar o token para conectar o GitHub ao VS Code.

- No VS Code, **clique em View** → Command Palette **(Ctrl + Shift + P)**.

- Digite **"Git: Clone"** e selecione a opção **"Git: Clone"**.

- **Cole a URL** do seu repositório GitHub (exemplo: https://github.com/seu-usuario/meu-repositorio.git).

- Escolha uma pasta onde deseja salvar o repositório.

- O VS Code pedirá as **credenciais do GitHub**. No campo **senha**, cole o **Token** de Acesso Pessoal gerado anteriormente.

- Se tudo estiver correto, o repositório **será clonado** e estará pronto para uso no VS Code.

**Aqui está uma outra sugestão de como clonar um repositório:**

- Entre no repositório que deseja clonar, aperte no botão **code** e copie o **link https://** . Como na imagem:

![IMG](https://analisemacro.com.br/wp-content/uploads/2021/11/url_git.png)

- Vá até o terminal do VS CODE e digite o seguinte comando:

```bash
 git clone <URL DO SEU REPOSITÓRIO> 
```

- Se der tudo certo, as pastass do repositório vão começar a aparecer no seu VS CODE.


## Usando o GitHub no VS Code

Agora que o GitHub está configurado, você pode **criar**, **versionar** e **enviar** arquivos diretamente pelo VS Code.

- Se quiser criar um novo repositório dentro do VS Code , abra o **terminal do VS CODE** e digite:

```bash
 git init 
```
Isso criará um repositório local.

- Adicione um arquivo (por exemplo, README.md) e salve. No terminal digite:

```bash
 git add README.md
```
Para adicionar todos os arquivos ao repositório.

- Agora, faça o primeiro commit:

```bash
git commit -m "Primeiro commit"
```

**Observações:** Faça todos esses comandos no **terminal do VS CODE**. Para abrir o terminal: (ctrl + ").

- Crie/Use um repositório no GitHub e copie a URL dele.

- Agora , conecte-se com o repositório remoto:


```bash
git remote add origin https://github.com/seu-usuario/seu-repositorio.git
```

- Por fim, envie os arquivos para o GitHub:

```bash
git push -u origin main
```

## Fazer Pull, Push e Commit diretamente pelo VS Code

Agora que o repositório está configurado, podemos gerenciar as alterações diretamente pelo VS Code.

- **Fazer Commit:**

    - No VS Code, clique no ícone de **Controle de Código-Fonte** (parece um ramo com três pontos).
    - Escreva uma mensagem de commit e clique em **Commit**.

![IMG](https://code.visualstudio.com/assets/docs/sourcecontrol/intro/scm-unstage-changes.png)


- Enviar alterações para o GitHub **(Push)**:

![IMG](https://sachinsf.com/wp-content/uploads/2021/02/pasted-image-0-16.png)

- Após fazer o commit, clique no botão **"Sincronizar mudanças"** ou digite no terminal: 

```bash
git push origin main
```

- Baixar atualizações do repositório **(Pull)**:

   - Para obter as últimas atualizações do repositório remoto, clique em **"Pull"** ou use o **terminal**:

```bash
git pull origin main
```

## Criar e Trocar de Branch no VS Code

Se estiver trabalhando com múltiplas **branches**, você pode **gerenciá-las no VS Code**.

- **Criar uma nova branch**:

```bash
git branch nova-branch
```

- **Mudar para a nova branch**: 

```bash
git checkout nova-branch
```

- **Criar e mudar para a nova branch ao mesmo tempo**:

```bash
git checkout -b nova-branch
```

- **Enviar a branch para o GitHub**:

```bash
git push -u origin nova-branch
```

Agora o GitHub está totalmente integrado ao VS Code, permitindo:

✅Clonar repositórios diretamente no VS Code.

✅ Realizar commits e push sem precisar usar o terminal.

✅ Gerenciar branches e sincronizar alterações facilmente.


## Links Úteis :

- Aqui estão links úteis para caso de dúvidas mais específicas ou aprofundamentos por parte do seu interesse: 

    🖇️[Documentação do VS CODE](https://code.visualstudio.com/docs).

    🖇️[Sobre GitHub e Git](https://docs.github.com/en/get-started/start-your-journey/about-github-and-git).

    🖇️[Documentação do GIT](https://git-scm.com/doc).

    🖇️[Clonagem de repositórios (possíveis dúvidas)](https://docs.github.com/pt/repositories/creating-and-managing-repositories/cloning-a-repository).


## Desafio Prático: Dominando o GitHub no VS Code


**Objetivo: Realizar tarefas reais dentro do GitHub e VS Code para reforçar o aprendizado**.


- *Tarefa 1: Clonando um Repositório*.

Passos:

- No GitHub, **crie um novo repositório chamado teste-clonagem**.
- **Copie a URL** do repositório.
- No VS Code, abra o Terminal e **clone** o repositório usando:

```bash
git clone <URL-do-repositório>
```

- Acesse a pasta do repositório:

```bash
cd teste-clonagem
```
**Desafio concluído se: Você conseguir visualizar a pasta do repositório no VS Code.**


- *Tarefa 2: Criar e Enviar um Arquivo para o GitHub*.

Passos:

- No VS Code, dentro da pasta do repositório clonado, **crie um arquivo chamado meu-arquivo.txt**.
- **Escrev**a qualquer coisa no arquivo e **salve**.
- No terminal, adicione o arquivo ao Git:

```bash
git add .
```

- Faça um **commit** com uma mensagem explicativa:

```bash
git commit -m "Adicionando meu primeiro arquivo"
```

- **Envie** para o GitHub:

```bash
git push origin main
```

**Desafio concluído se: Você ver o arquivo meu-arquivo.txt no seu repositório no GitHub.**

- *Tarefa 3: Atualizar um Arquivo e Fazer Push Novamente*.

Passos:

- No VS Code, **abra o arquivo meu-arquivo.txt** e **adicione** mais texto.
- **Salve** e faça um **novo commit**:

```bash
git add .
git commit -m "Atualizando o arquivo"
git push origin main
```

**Desafio concluído se: O arquivo no GitHub mostrar a nova atualização.**


## Considerações  Finais 

Desejo a todos vocês um bom estudo! Aqui venho eu tentar solucionar essa sugestão e espero ajudar a todos que estão com dificuldades.













