
# Notas de aula referentes ao módulo 1 do curso do git e github


 ## Instalação do git
### Após a instalação no site:

*No Prompt de comando:* 

git config --global user.name "detomiatti" #vincular a conta github
git config --global user.email "detomiatti@gmail.com"

git config --list #conferir se deu certo


## Versionamento
*É o controle de versões definido através de “numerações” de históricos diferentes*

- Permite acessar quando e como foram realizadas as alterações

## Repositório
*Pasta onde os projetos são armazenados*

- **Formato:** .git para que o git entenda a alteração
- Podem se dividir em módulos, em várias subpastas
- **Issues**: O que está sendo trabalhado e para relatar problemas

## Commit
*Um conjunto de alterações do código*

- “Commitar” é salvar as mudanças

<aside>
💡 Git entende como alteração:

1. Criação, renomeação ou exclusão de arquivos
2. Inserção ou exclusão de uma linha → **linha modificada é inserção ou exclusão**

</aside>

- É possível adicionar mensagem do que foi alterado

## Branch
*Separações de código para que as pessoas atuem em um mesmo projeto de forma independente*
- Dessa forma, os códigos não entram e conflito

### Na prática:

**Develop**: ambiente para o desenvolvimento.
- Depois de testar na própria máquina, o código é disponibilizado aqui

**Homolog**: Onde são testados e validados

- Reporta em forma de bug para correção

**Master**: A principal. Os códigos que vão para produção.

## Merge
*União dos commits dentro da branch*

- Para juntar alterações de duas branchs em que duas pessoas estavam atuando simultaneamente
- É realizado no “Pull request”

## Clone
*Transferir o repositório do GitHub para a máquina*
- Depois é possível colocar novamente no git

## Pull
*Para atualizar o repositório local com o remoto*

- É realizado um merge com o repositório online e o da máquina

## Push
*Enviar as alterações commitadas localmente para a ORIGEM remota*
- As pessoas que forem clonar, já terão o arquivo com as suas alterações

## Fork
*Para contribuir com o repositório de outra pessoa*

- Semelhante ao clone, mas é realizado na interface do github
- O repositório não é baixado para a máquina, mas para o clone
- Depois de “forkar” o repositório de outra pessoa, é possível fazer **pull-requests** para contribuir com o repositório principal

## Pull Request
*Ação depois de “forkar” e resolver issues, assim as soluções são enviadas e adicionando novos conteúdos*

- Dono do repositório vai avaliar o pull e então ser mergeada
 

 
 