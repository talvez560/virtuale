# 🖥️ Windows 11 Lite VM (Docker)

Este repositório contém a configuração para rodar uma máquina virtual do Windows 11 extremamente leve e otimizada (Tiny11) utilizando Docker. Ideal para testes rápidos sem pesar no sistema.

## 🚀 Requisitos

*   [Docker](https://docker.com) instalado na máquina.
*   Docker Compose ativo.

## 🛠️ Como Instalar e Rodar

1. Baixe o arquivo `docker-compose.yml` deste repositório.
2. Abra o seu terminal na pasta do arquivo.
3. Execute o comando abaixo para iniciar a máquina virtual:

```bash
docker compose up -d
```

4. Aguarde o Docker baixar e configurar o sistema automaticamente.

## 🌐 Como Acessar

Após a inicialização, você pode acessar a interface visual do Windows 11 de duas formas:

*   **Pelo Navegador**: Acesse `http://localhost:8006`
*   **Via RDP (Área de Trabalho Remota)**: Conecte em `localhost:3389`

## ⚙️ Configurações Padrão

*   **Versão**: Tiny11 (Windows 11 ultra-leve sem bloatware)
*   **Memória RAM**: 2 GB
*   **Processador**: 2 Núcleos de CPU
*   **Armazenamento**: 20 GB (Expandível)
