<h1 align=center>Script de Implantação de Aplicação Web</h1>

<p align="center">
<img src="https://img.shields.io/badge/status-concluido-purple?style=for-the-badge" />
<img src="https://img.shields.io/badge/Ubuntu-E95420.svg?style=for-the-badge&logo=Ubuntu&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624.svg?style=for-the-badge&logo=Linux&logoColor=black" />
<img src="https://img.shields.io/badge/Apache-D22128.svg?style=for-the-badge&logo=Apache&logoColor=white" />
</p>

##
## Descrição
Este projeto é um script Bash que automatiza o processo de preparação de um servidor Linux (Ubuntu) para hospedar uma aplicação web estática. Ele realiza a atualização do sistema, instala o servidor web Apache2 e baixa, descompacta e move os arquivos de uma aplicação web específica para o diretório padrão do Apache.

Este script é ideal para quem está começando a aprender sobre implantação e automação em ambientes Linux.
##
## Conteúdo

- [x] Atualização do Servidor: Atualiza os pacotes do sistema operacional.
- [x] Instalação de Pacotes Essenciais: Instala o servidor web Apache2 e a ferramenta unzip.
- [x] Download da Aplicação: Baixa o código-fonte da aplicação web do repositório linux-site-dio no GitHub.
- [x] Descompactação e Cópia: Descompacta os arquivos da aplicação e os move para o diretório /var/www/html, tornando-os acessíveis via web.

##
## Ferramentas Utilizadas
- Sistema Operacional: Linux

- Distribuição: Ubuntu Server

- Servidor Web: Apache2

- Outras Ferramentas: wget, unzip
##
## Como Rodar Localmente

1. Clone o repositório
```
git clone https://github.com/CahTarine/linux-projeto2-iac.git
```
2. Navegue até o diretório do projeto
```
cd linux-projeto2-iac
```
3. Dê permissão de execução ao script
```
chmod +x script-iac2.sh
```
4. Execute o script como superusuário
```
sudo ./script-iac2.sh
```
Após a execução, seu servidor Apache2 estará instalado e a aplicação web estará acessível. Você poderá testá-la navegando até o endereço IP do seu servidor em um navegador web.
##
## 👩🏻‍💻 Desenvolvedora

Feito com 💜 por Camille Tarine!
