# O que é
 - Relógio digital atualizado em tempo real com base na hora do sistema do usuário


## Como Usar
 - Só iniciar a aplicação e já estará funcionando

## Como funciona
 - A aplicação pega a hora do sistema do usuário, e exibe na tela com : Horas : Minutos : Segundos : AM/PM
 - Não é necessário que o usuário faça algo

### Nota do desenvolvedor 
 Você, para desenvolver esse projeto, não vai precisar da instalação de nenhuma dependência. Porém, eu decidi iniciar a aplicação com `serve` para ter o arquivo hospedado em um serivdor local para a minha máquina e para dispositivos conectados na mesma rede. Caso você queira fazer o mesmo, segue abaixo as etapas.
 
 Antes de tudo, você vai precisar ter o `NodeJS` instalado. Você pode fazer o download por [aqui](nodejs.org).
 
 ``` sh

  Após a instalação, abra o terminal de sua preferência e siga as etapas à seguir:
  cd # (aqui após o 'cd', você coloca o caminho do arquivo. Exemplo: `cd Documents/Projetos/Clock`)
  npm init -y # para inicializar o package.json
  npm install serve -D # para instalar o serve como dependência de desenvolvimento
  npx serve . # para rodar o servidor node
 ```
 
