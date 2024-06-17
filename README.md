<h1 align="center">Configuração do Ubuntu Server Usando VirtualBox</h1>

<p align="center">
  <img src="https://github.com/joanacristinacs/Ubuntu-Server/assets/114433945/8d0b1b09-26b2-42d1-8869-4c7ac62252ac" alt="logo ubunto" />
</p>

Este repositório oferece um tutorial abrangente sobre como configurar um servidor Ubuntu Server 24.04 usando o VirtualBox para simular um ambiente de rede. Este projeto foi criado para servir como um guia prático na configuração e administração de servidores Linux em um ambiente virtual. <br>

🔍 Para mais detalhes, acesse a [Wiki]()
---

## Sumário

1. Introdução
2. Requisitos
3. Instalando o VirtualBox
4. Criando a Máquina Virtual
5. Instalando o Ubuntu Server 24.04
6. Configurando Serviços
7. Referências

## Requisitos

Antes de começar, assegure-se de ter os seguintes itens:

- Computador com virtualização ativada.
- VirtualBox instalado (recomenda-se a versão mais recente).
- Imagem ISO do Ubuntu Server 24.04.
- Conhecimentos básicos em redes e sistemas operacionais.

## Instalando o VirtualBox

1. Baixe a versão mais atual do VirtualBox no [site oficial](https://www.virtualbox.org/).
2. Siga as instruções fornecidas pelo instalador para completar a instalação.

## Criando a Máquina Virtual

1. Abra o VirtualBox e clique em "Novo" para iniciar a criação de uma nova VM.
2. Siga os passos do assistente, definindo o nome da máquina, tipo e versão do sistema operacional (Ubuntu Server 24.04).
3. Configure a memória RAM (mínimo recomendado: 2GB).
4. Crie um disco rígido virtual (mínimo recomendado: 50GB).
5. Finalize a criação da máquina virtual.

## Instalando o Ubuntu Server

1. Selecione a máquina virtual que você criou e clique em "Iniciar".
2. Selecione a imagem ISO do Ubuntu Server 24.04 como mídia de inicialização.
3. Siga as instruções do instalador do Ubuntu para concluir a instalação.

## Configurando Serviços

Após instalar o Ubuntu Server 24.04, siga os tutoriais específicos para configurar os seguintes serviços:

- Apache
- BIND9
- PROFTPD
- Samba
- ISC DHCP Server
- Squid

## Referências

- [Documentação do VirtualBox](https://www.virtualbox.org/wiki/Documentation)
- [Guia de Instalação do Ubuntu Server](https://ubuntu.com/server/docs/installation)
- [Documentação do Ubuntu Server](https://ubuntu.com/server/docs)

Este projeto foi elaborado como parte das atividades práticas da disciplina de Redes II, focando na configuração e administração de servidores Ubuntu em ambientes virtualizados.
