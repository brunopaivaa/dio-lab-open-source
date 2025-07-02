<h1>
    <a href="https://www.dio.me/">
     <img alinhar="centro" largura="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <vão> Guia de Contribuição</vão>
</h1>

[![Estrela](https://img.shields.io/github/stars/digitalinnovationone/dio-lab-open-source?style=social)](https://github.com/digitalinnovationone/dio-lab-open-source/stargazers)
[![Garfos](https://img.shields.io/github/forks/digitalinnovationone/dio-lab-open-source?style=social)](https://github.com/digitalinnovationone/dio-lab-open-source/forks)
[![Problemas do GitHub](https://img.shields.io/github/issues/digitalinnovationone/dio-lab-open-source?style=social)](https://github.com/digitalinnovationone/dio-lab-open-source/issues/)

 Este é um projeto feito para uma comunidade, então sinta-se livre para contribuir. Algumas formas de contribuição além de seu exemplo de perfil README, é inserir outros utilitários na massa [`utilitários`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/utils), ou melhor, uma página de pesquisa dos READMEs fazendo modificações nos arquivos da massa [`documentos`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/docs). <br>
 Além disso, você também pode contribuir:
 
 ?? ️ Resolvendo, respondendo ou indicando **questões**

⭐ Adicionando aos favoritos (**estrela**) 

## Contribuindo no diretório "Comunidade" 
 A contribuição no diretório "Comunidade" é uma das formas de completar o Desafio do lab "**Contribuindo em um Projeto Open Source no GitHub**"da [Inovação Digital Um](https://www.dio.me/). . . Você pode colaborar criando um perfil README contendo informações sobre você que deseje compartilhar com uma comunidade. <br>
 Para isso, você pode inserir: distintivos indicando suas habilidades; cartões com suas estatísticas no GitHub e projetos que criou, colaboraram ou que desejaram que outras pessoas colaborem. Além disso, você pode inserir ligações para seus projetos de projeto e artigos na plataforma da [Inovação Digital Um](https://www.dio.me/). <br>
 Inspire-se consultando os exemplares na massa [`comunidade`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/community), confira alguns utilitários na massa [`utilitários`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/utils) e use sua criatividade para criar o seu 😊💙.

### 1) Faça um **Garfo** deste Repositório
Acesse a pagina principal do repositório e clique no botão "Fork" no canto superior direito da pagina.
> [!NOTA]  
> Um "garfo" não GitHub é uma cidade de um repositório que pode ser criada por um usuário qualificado. <br>
> Para mais detalhes, reveja a aula ou acesse a documentação do GitHub: [Criar fork de um repositório](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).

### 2) Clone localização
Abra o seu Git Bash e digite o comando `clone git` segundo da URL do seu fork para clonar o seu repositório localmente. Por exemplo:
`bash
clone Git https://github.com/SEU_USERNAME/dio-lab-open-source.git
`
Pressione enter, e uma culpa do seu fork no GitHub será criada localmente.

### 3) Crie uma nova **filial** 
Utilize o comando `checkout git - b` para criar e alternar para uma nova filial e nomeie-a como `façanha/comunidade/SEU_USERNAME`
> Exemplo: `git checkout - b feat/comunidade/falvojr`

### 4) Crie o seu Perfil README
 Dentro da massa [`comunidade`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/community), crie um arquivo em Markdown (extensão `. .md`) e nomeie com o mesmo nome do seu usuário no GitHub:

> Exemplo: `comunidade/falvojr.md`

#### 4.1) Desenvolvimento o seu Perfil README
Para isso, você pode se inspirar nos exemplos não diretos [`comunidade`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/community) e adicionar alguns dos utilitários apresenta na massa [`utilitários`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/utils)

### 5) Adicione suas alterações à "área de preparação" 
Utilize o comando `git adicionar comunidade/SEU_USERNAME.md` para adicionar sua alteração (nesse caso o arquivo markdown criado) à "área de preparação" no Git.

### 6) Crie um Commit
Crie um commit e adicione a mensagem indicando uma adição do seu perfil:
`bash
git commit - m "feat: add SEU_USERNAME profile"
`
>[!IMPORTANTE]
> Verifique a [`Convocação de Commits`](https://github.com/digitalinnovationone/dio-lab-open-source/blob/main/CONTRIBUTING.md#conven%C3%A7%C3%A3o-de-commits) para escrever a mensagem do seu commit de forma clara e padronizada.

### 7) Envie as Alterações para o seu Repositório Remoto
Envie as alterações realizadas no seu repositório local para uma filial `façanha/comunidade/SEU_USERNAME` no seu repositório remoto com o comando:
`bash
git push origem feat/comunidade/SEU_USERNAME
`
>[!AVISO]
> Caso você tenha criado seu arquivo direto no repositório remoto no GitHub, esse processo não será necessário.

### 8) Crie hum **Solicitação Puxar**.

Atente-se para a seguir as orientações para a contribuição, princípio:
- Seu PR deve modificar apenas o arquivo community/SEU_USERNAME.md (dê uma olhadinha na aba "Arquivos alterados");
- O nome desse arquivo deve ser exatamente igual ao nome de usuário no GitHub (nossa validação é case-sensitive).

>[!NOTA]
> Caso não saiba como criar uma solicitação de pull, reveja o lab ou acesse a documentação do GitHub: [Como criar uma solicitação de pull
](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

Após criar o seu Pull Request, nossa automation irá validar a sua submissão. Caso esteja tudo certo, será retornada uma mensagem indicada que seu PR foi aprovado. Do contrário, leia atentamente como orientações e verifique os arquivos modificados para saber se atende como instruções para contribuição.
    
    
## Convocação de Commits 

| Tipo de Compromisso |Descrição | Exemplo
| ---------------|-----------------------------------------------------------
| `façanha` | Adiciona uma nova funcionalidade ao projeto. | `façanha: adicionar perfil USENAME.md`
| `corrigir` | Corrige um bug ou problema sem projeto. | `correção: correção de problema fixo#IssueNumber`
| `documentos` | Altera a documentação do projeto.| `docs: atualizar README.md`
| `estilo` | Realiza mudanças na aparência, sem alterar a funcionalidade. | `estilo: adicionar EFFECTNAME ao COMPONENTE`
| `refator` | Realiza mudanças no côdigo que não alteram uma funcionalidade. | `refator: refator em CLASSNAME`
| `teste` | Adiciona ou modifica testes sem projeto. | `teste: adicione teste de unidade para UserService`


## Referências
- [ANGULAR. Contribuindo para Angular](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md)
- [COMISSÕES CONVENCIONAIS. Resumo](https://www.conventionalcommits.org/en/v1.0.0/)
- [GITHUB. Configurar diretrizes para os contribuidores do repositório](https://docs.github.com/pt/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)
