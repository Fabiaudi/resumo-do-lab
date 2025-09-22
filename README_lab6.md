# 🗄️ Desafio de Laboratório – Armazenamento no Microsoft Azure

Este documento faz parte do **Bootcamp AZ-900 (Microsoft Azure Fundamentals)** da [DIO](https://dio.me).  
O objetivo é consolidar os aprendizados sobre os **serviços de armazenamento do Azure**, suas camadas, redundância e ferramentas de gerenciamento.

---

## 📖 Entendendo o Desafio

Este desafio tem como propósito:  

- Documentar os aprendizados sobre **armazenamento no Azure**.  
- Explorar os tipos de serviços, camadas de armazenamento e opções de redundância.  
- Conhecer ferramentas de migração e gerenciamento de dados.  
- Reforçar a importância da organização em um **repositório GitHub** como parte do portfólio.  

---

## 📚 Resumo do Aprendizado

### 📦 Tipos de Serviços de Armazenamento
- **Blob Storage** – armazenamento de objetos (imagens, vídeos, documentos).  
- **File Storage** – compartilhamento de arquivos via SMB, similar a um file server.  
- **Queue Storage** – filas de mensagens para comunicação entre componentes de aplicações.  
- **Disk Storage** – discos para máquinas virtuais.  
- **Table Storage** – armazenamento de dados NoSQL, chave/valor.  
- **Data Lake Storage** – otimizado para análise de grandes volumes de dados.  

---

### 🏷️ Camadas de Armazenamento
- **Frequente (Hot)** – para dados acessados com frequência.  
- **Esporádico (Cool)** – para dados com acesso eventual, mas que precisam estar disponíveis.  
- **Frio (Cold)** – dados raramente acessados.  
- **Arquivo Morto (Archive)** – armazenamento de longo prazo, com custo baixo e acesso demorado.  

---

### 🌐 Padrão de Endereçamento
O acesso segue o padrão:  
https://meuarmazenamento.blob.core.windows.net


---

### 🛡️ Opções de Redundância
- **LRS (Locally Redundant Storage)** – cópias dentro de um único datacenter.  
- **ZRS (Zone Redundant Storage)** – cópias entre diferentes zonas de disponibilidade.  
- **GRS (Geo-Redundant Storage)** – cópias em regiões geográficas diferentes.  
- **GZRS (Geo-Zone Redundant Storage)** – combina redundância entre zonas e regiões.  

---

### ⚙️ Ferramentas de Migração e Gerenciamento
- **Azure Migrate** – ferramenta para migração de cargas de trabalho para a nuvem.  
- **Data Box** – dispositivo físico fornecido pela Microsoft para transferir grandes volumes de dados.  
- **AzCopy** – ferramenta de linha de comando para cópia de dados.  
- **Storage Explorer** – interface gráfica para gerenciar contas de armazenamento.  
- **File Sync** – sincronização entre servidores locais e Azure Files.  

---

### 📂 Contas e Formatos de Armazenamento
- **Storage Account** é o ponto central de gerenciamento dos serviços de armazenamento.  
- Suporte a diferentes **formatos de dados**: objetos, arquivos, tabelas e discos.  
- Permite organizar e aplicar **políticas de acesso e segurança**.  

---

## 🎯 Conclusão

Este módulo me permitiu:  

- Entender os diferentes **tipos de serviços de armazenamento** no Azure.  
- Diferenciar as **camadas de acesso e custo**.  
- Conhecer as **opções de redundância** e sua importância na disponibilidade dos dados.  
- Explorar **ferramentas práticas** para migração e gerenciamento de dados.  
- Consolidar a visão de como o armazenamento é essencial para **resiliência, segurança e performance** na nuvem.  

---

## 👩‍💻 Autor

**Fabiana Audi V. H. Lima**  
- Estudante de Análise e Desenvolvimento de Sistemas – UNIFAA  
- Desenvolvedora Fullstack em formação | Estagiária na GFT Brasil  
- Inglês avançado (C1 – MET)  
- Apaixonada por tecnologia, aprendizado contínuo e cloud computing  
- 📍 Rio de Janeiro, Brasil  

---

👉 Este arquivo (`README_lab6.md`) serve como **resumo consolidado** do módulo de **Armazenamento no Azure**, parte da preparação para a certificação **AZ-900**.

