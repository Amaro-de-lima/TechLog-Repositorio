# TechLog-Repositorio
O repositório TechLog-Repo foi criado para armazenar e disponibilizar todos os arquivos necessários para a implementação inicial da infraestrutura de servidor Linux.
# TechLog Server Setup

## 📌 Propósito do Repositório
O repositório **TechLog-Repo** contém todos os arquivos necessários para a configuração inicial da infraestrutura de servidor Linux (Ubuntu Server 22.04 LTS) da startup fictícia **TechLog**.

O objetivo é facilitar e padronizar a implantação do ambiente, garantindo segurança, organização e funcionalidade para as equipes de **desenvolvimento** e **operações**.

## 📂 Conteúdo
- **setup_infra.sh** → Script em Shell para automatizar:
  - Criação de usuários e grupos.
  - Configuração de permissões.
  - Instalação e configuração do servidor Apache.
  - Definição de cotas de disco.
  - Configuração de firewall e IP estático.
- **index.html** → Página HTML simples para ser servida pelo Apache.
- **README.md** → Documento explicando o propósito do projeto e como executá-lo.

## 🚀 Como Executar
1. Clone este repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```
2. Dê permissão de execução ao script:
   ```bash
   chmod +x setup_infra.sh
   ```
3. Execute o script:
   ```bash
   ./setup_infra.sh
   ```

## Requisitos

- Ubuntu Server 22.04 LTS
- Permissões de superusuário (sudo)

---
**Autor:** Equipe de Configuração TechLog
