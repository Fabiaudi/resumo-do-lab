# 🗄️ Desafio de Laboratório – Banco de Dados no Microsoft Azure

Este documento faz parte do bootcamp de preparação para a **certificação AZ-900 (Microsoft Azure Fundamentals)** da [DIO](https://dio.me).  
O objetivo deste laboratório é praticar a configuração de uma instância de **Banco de Dados no Azure**, consolidando conceitos e documentando o processo para estudos futuros.

---

## 📖 Entendendo o Desafio

Este laboratório tem como objetivo:  

- Praticar o processo de **configuração de uma instância de Banco de Dados no Microsoft Azure**.  
- Documentar resumos, anotações e dicas para uso da Azure SQL, servindo como **material de apoio para estudos e futuras implementações**.  

🔗 Referência oficial: [Criar instância do Azure SQL Managed Instance (Portal do Azure)](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart?view=azuresql&tabs=azure-portal)

---

## 🎯 Objetivos de Aprendizagem

Ao concluir este desafio, fui capaz de:  

- ✅ Criar e configurar uma **instância de Banco de Dados (Azure SQL Managed Instance)** pelo Portal do Azure.  
- ✅ Entender conceitos como **camadas de serviço, redundância e escalabilidade**.  
- ✅ Praticar boas práticas de **segurança e gerenciamento de custos**.  
- ✅ Documentar dicas e pontos de atenção no uso do Azure SQL.  

---

## ⚙️ Resumo do Processo (Azure Portal)

1. **Acessar o Portal do Azure**  
   - Pesquisar por **SQL Managed Instance**.  
   - Clicar em **Criar**.  

2. **Configuração Básica**  
   - Selecionar **Assinatura** e **Grupo de Recursos**.  
   - Definir **Nome da instância**.  
   - Escolher **Região**.  
   - Selecionar **Camada de serviço** (General Purpose ou Business Critical).  

3. **Configuração de Rede**  
   - Definir **rede virtual (VNet)**.  
   - Ajustar parâmetros de segurança.  

4. **Ajustes de Performance e Armazenamento**  
   - Escolher número de **vCores**.  
   - Configurar espaço em disco.  
   - Definir redundância do armazenamento.  

5. **Revisar + Criar**  
   - Validar todas as opções.  
   - Clicar em **Criar** para provisionar a instância.  

---

## 💡 Dicas Importantes

- **Custos**: ajustar os recursos provisionados para evitar gastos desnecessários.  
- **Segurança**: configurar firewall e regras de rede para proteger a instância.  
- **Escalabilidade**: instâncias podem ser dimensionadas conforme a demanda.  
- **Backup automático**: o Azure SQL possui backup gerenciado, garantindo maior disponibilidade.  
- **SLA**: atenção às garantias de disponibilidade, que variam de acordo com a camada de serviço escolhida.  

---

## 📚 Conclusão

Este laboratório me permitiu:  

- Reforçar conceitos sobre **bancos de dados em nuvem**.  
- Entender a diferença entre ambientes locais e gerenciados.  
- Praticar a configuração do **Azure SQL Managed Instance**.  
- Criar uma base de resumos e dicas que servirá como apoio para **futuras implementações e para a prova AZ-900**.  

---

## 👩‍💻 Autor

**Fabiana Audi V. H. Lima**  
- Estudante de Análise e Desenvolvimento de Sistemas – UNIFAA  
- Desenvolvedora Fullstack em formação | Estagiária na GFT Brasil  
- Inglês avançado (C1 – MET)  
- Apaixonada por tecnologia, aprendizado contínuo e cloud computing  
- 📍 Rio de Janeiro, Brasil  

---

👉 Esse arquivo faz parte da entrega do **Desafio de Banco de Dados do Azure (Lab 3)** no bootcamp de preparação para a certificação **AZ-900**.
