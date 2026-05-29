## Objetivo
Este projeto tem como objetivo aprender, praticar e fixar o uso do
Git como ferramenta essencial no fluxo DevOps.

## Instalação

### Pre-requisitos
- Git instalado (verifique com: git --version)
- Conta no GitHub
- Editor de codigo (recomendado: VS Code)

### Passo a passo
1. Clone o repositorio:
   git clone https://github.com/USUARIO/roteiro-git-devops.git
2. Acesse a pasta do projeto:
   cd roteiro-git-devops
3. Abra no editor:
   code .
4. Configure sua identidade (se ainda não fez):
   git config --global user.name "Seu Nome"
   git config --global user.email "email@exemplo.com"

## Uso

### Ciclo basico do dia a dia
1. Atualize sua branch antes de comecar: git pull
2. Crie uma branch para sua tarefa: git switch -c feature/nome
3. Faca suas alteracoes nos arquivos
4. Adicione ao staging: git add .
5. Salve no historico: git commit -m "tipo: descricao"
6. Envie para o GitHub: git push

### Comandos uteis no dia a dia
- git status          -> ver estado atual dos arquivos
- git diff            -> ver o que foi alterado antes de commitar
- git log --oneline   -> ver historico resumido
- git restore arquivo -> desfazer alteracao nao commitada
- git config --global user.name "Seu Nome"  -> configurar identidade
- git config --global user.email "email"    -> configurar e-mail

## Exemplos de Comandos

- `git init` → inicializa um repositório
- `git status` → mostra o estado dos arquivos
- `git log --oneline` → mostra o histórico resumido

## Como Contribuir

1. Crie uma branch com o nome da sua tarefa
2. Faça suas alterações e commit
3. Abra um Pull Request descrevendo o que foi feito
4. Aguarde a revisão antes do merge
5. Para desfazer uma alteração não commitada:
- git restore "nome-do-arquivo"

> Projeto criado para praticar Git no fluxo DevOps.