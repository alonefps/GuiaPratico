# Tutorial de Git e GitHub 🤙

## Introdução
E aí, gente! Bem-vindos ao tutorial mais descolado de todos os tempos sobre como usar o Git e o GitHub! 🎉 Se você tá perdido(a) com essas paradas de controle de versão e quer aprender a mexer de verdade, vem comigo que eu vou te mostrar o caminho das pedras! 😎

### O que é Git e GitHub?
Antes de começarmos, deixa eu te explicar o que é o Git e o GitHub, só pra não ficar viajando no tutorial sem entender o que tá acontecendo!

**Git** é uma ferramenta de controle de versão. Isso significa que ele permite que a gente rastreie as mudanças que fazemos em nossos arquivos ao longo do tempo. Imagine um superpoder que te permite voltar no tempo e ver o histórico das suas alterações! É tipo um "CTRL + Z" poderoso que funciona em qualquer arquivo, até em códigos!

**GitHub**, por sua vez, é uma plataforma online onde a galera compartilha seus projetos e colabora uns com os outros usando o Git. É tipo uma rede social para desenvolvedores, onde você pode mostrar o que anda codando e também colaborar com os projetos maneiros de outras pessoas.

### Configurando o Git
Antes de botar a mão na massa, você precisa configurar o Git com suas informações. É só abrir o terminal (ou Git Bash, pra quem tá no Windows) e digitar os seguintes comandos:

`git config --global user.name "Seu Nome Aqui"`

`git config --global user.email "seuemail@exemplo.com"`

## Comandos Básicos do Git
Agora vamos aprender os comandos básicos do Git para você começar a brilhar no controle de versão!

> `git init` Esse comando cria um repositório Git novo. É como se você estivesse dizendo ao Git: "Ei, aqui começa meu projeto, sacou?"

> `git add <nome_do_arquivo>` Com esse comando, você adiciona um arquivo específico para ser monitorado pelo Git. É como se você falasse: "Hey, Git, fica de olho nesse arquivo, beleza?"

> `git add .` Esse é o atalho da galera! Com esse comando, você adiciona TODOS os arquivos modificados de uma vez só! É pra economizar tempo e dedos! 😄

> `git commit -m "Mensagem do Commit"` Esse é o passo de salvar suas mudanças no histórico do Git. A mensagem é tipo um lembrete do que você fez, então seja descritivo e não abrevie demais, beleza?

> `git status` Esse é seu melhor amigo! Com ele, você fica sabendo o que tá acontecendo no seu repositório. Sempre use antes de um commit para ver o que vai ser salvo!

> `git log` Esse comando te mostra o histórico de commits que você fez. É legal para ver o que você aprontou nos seus arquivos!

## O Exercício Topzera!
Agora é hora de botar a mão na massa de verdade! Vamos fazer um exercício para você praticar os comandos que aprendeu.

Crie uma pasta chamada **"meu-projeto-git"**.

Entre na pasta que você acabou de criar:
```
cd meu-projeto-git
```
Inicie um repositório Git no diretório:
```
git init
```
Crie um arquivo chamado "index.html" com o conteúdo abaixo (ou qualquer conteúdo que quiser!):

```
<!DOCTYPE html>
<html>
<head>
    <title>Meu Projeto Git</title>
</head>
<body>
    <h1>Hello, Git!</h1>
</body>
</html>
```

## Adicione o arquivo ao Git:


```git add index.html```

Faça o primeiro commit das suas mudanças:

```git commit -m "Adicionar arquivo index.html"```

Agora, altere o conteúdo do arquivo "index.html" para algo diferente.

Use ```git status``` para ver as mudanças que você fez.

Adicione todas as mudanças:

```git add .```

Faça o segundo commit:

```git commit -m "Modificar conteúdo do index.html"```

### Pronto! Você fez seu primeiro exercício de Git! 🎉 Agora você já sabe como criar repositórios, adicionar arquivos e fazer commits!

## Enviando seu Repositório para o GitHub
Agora que você já sabe brilhar no Git, que tal mostrar seu talento pro mundo no GitHub? Vou te ensinar rapidinho como fazer isso!

Crie um repositório no GitHub com o nome **"meu-projeto-git"** (ou o nome que quiser!).

Na página do seu repositório, você vai ver uma URL parecida com **https://github.com/seu-usuario/meu-projeto-git.git.** Copie essa URL.

Volte para o terminal e adicione o repositório remoto do GitHub com o comando:

```git remote add origin URL_DO_REPOSITORIO```
Agora é só mandar suas mudanças para o GitHub com o comando:

```git push -u origin master```

### Eba! Seu projeto tá no GitHub! 🚀 Agora você pode compartilhar o link com a galera e receber elogios pelos seus códigos!

# Conclusão
Parabéns, você chegou até aqui e aprendeu o básico do Git e GitHub! 🎉 Agora é só continuar praticando e se aprofundando nesse universo incrível de controle de versão!

Lembre-se sempre de usar o git status para saber o que tá rolando, e faça commits com mensagens descritivas para não se perder no meio das mudanças!

Se tiver dúvidas, o Google e a comunidade do GitHub estão aí para te ajudar! 😉

Bons commits e até a próxima! 👋😄
