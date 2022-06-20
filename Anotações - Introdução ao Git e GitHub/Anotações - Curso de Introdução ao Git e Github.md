# Anotações - Curso de Introdução ao Git e Github :computer:



## Git 

O Git é um sistema de controle de versão utilizado principalmente para desenvolvimento de softwares. Criado em um projeto *open source*, a ferramenta permite manter o histórico de alterações de código em versões anteriores, bem como a colaboração simultânea em trabalhos de equipe, adicionando ou removendo o que seja necessário no código em questão.

As vantagens de se utilizar um sistema de controle de versão como o Git são:

- **Desempenho:** a partir do sistema distribuído, as operações foram criadas para ambientar o desenvolvedor a trabalhar de maneira mais prática e flexível. Ainda se destaca o fato de que não se necessita conexão à internet para utilizar a ferramenta, por se tratar de um sistema de servidor local.
- **Flexibilidade:** A adaptação do Git aos formatos de trabalho não lineares é essencial para que cada desenvolvedor e empresa possa trabalhar com um fluxo próprio, seja ele grande ou pequeno, sendo as alterações de código rastreadas por ramificações.
- **Segurança: **A proteção do código pelo sistema é realizada por meio do SHA1 (*Secure Hash Algorithm*), um algoritmo projetado pela Agência de Segurança Nacional dos Estados Unidos que objetiva uma função *hash* de criptografia. Assim, qualquer mínima alteração no código será rastreável, permitindo uma maior segurança para todos os que utilizam a ferramenta.



## Como é o funcionamento de um repositório local :question:

O **Working Directory**, também conhecido como *Working Tree*, é a área em que você está trabalhando. **Onde estão todos os seus arquivos**, onde você criará novos arquivos, deletará os velhos ou alterará os que já existem. Também é onde estão os arquivos *untracked.*

Após alterações nos arquivos, o próximo passo é adicionar essas alterações na **área de staging**. Também conhecida como *index,* é quando o Git passa a salvar aquele estado dos seus arquivos. É como se fosse uma **prévia do seu commit**. O interessante é que se você fizer uma alteração em um arquivo, adicionar ele na *staging area* e depois fizer uma nova alteração nesse mesmo arquivo, essa alteração estará no *working directory* novamente. E a alteração anterior continuará na *staging area*.

O próximo passo é pegar todas as alterações de *staging* e fazer um *commit* com elas. Quando você faz isso, esse commit vai para a *commit area* ou também conhecida como *local repository*. Aqui fica tudo do seu repositório. É por isso que você consegue trabalhar de maneira offline, podendo executar suas tarefas e fazer commits sem precisar se conectar a nenhum repositório remoto. 

## Links úteis para aprender mais :exclamation:

- [Instalar o Git no Windows](https://gitforwindows.org/)
- [Instalar o Git no Linux](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git)
- [Instalar o Git no MacOS](http://git-scm.com/download/mac)
- [Principais Comandos no Git e suas descrições](https://www.codigofonte.com.br/artigos/top-25-comandos-do-git)
- [Guia do Markdown](https://www.markdownguide.org/getting-started/)

## GitHub

Diferente do Git, o Github é uma ferramenta baseada em nuvem que hospeda um sistema de controle de versão, sendo essa a principal diferença entre o sistema do Git. Além disso, o GitHub pode ser usado como uma rede social para integrar colaboradores e pessoas desenvolvedoras e outros profissionais da tecnologia para contribuir com o *open source*. :crystal_ball:

Para começar a usar o GitHub e conhecer mais suas aplicações e ferramentas, basta criar uma conta no [site oficial](https://github.com/) e explorar suas funcionalidades.



