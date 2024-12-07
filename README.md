# modern-arquitecture
Arquitetura moderna, Evento Dev-Pira 

Critérios para Aplicações Modernas

1. Cloud Native
--> Saber sobre as ferramentas GERAIS sobre as tecnologias, exemplo: Oq é o Bucket tanto para AWS quanto para CloudFlare

2. Alta Disponibilidade
--> RTO + RPO + Tempo de Recuperação dos Dados (Redundancia e Balanceamento, instnacias!!!)

3. Escalavel
--> Escalabilidade Horizontal: Adiciona mais instancia de servidores
--> Escalabilidade Vertical: Incrementa capacidade de recursos, como CPU, RAM ou Armazenamento
--> Fazer testes de stress!!!

4. Desacoplamento (Api First)
--> Ecossitema Plugável: APIs tornam o sistema moduklar e expansivel permitindo conexão de novos serviços
--> Autoatendimento: APOs publicas e bem documnetadas oferecem autonomia aos devs, acelerando integrações

5. DevSecOps
--> Microserviços e Microfrontends, Intfra as Code, CI/CD, COntinuous Deployment

6. Segura por Padrão
--> Estudar brechas de seguranças, testes de intruzão, Scans de Segurança, Fortify, SonarQube, MFA, Cripto de Dados

7. tolerante a Falhas
--> Prever e lidar com falhas, redundancia e recuperação automatica
--> Erros Possiveis: Hardware, Infraestrutura, Dependencias e Internas

8. Observabilidade
--> DATADOG! Logs, metricas, traces, MONITORAR APLICAÇÃO
--> Ver sobre dados, como lugares q o usuário mais clica e etc

9. Projetado para Evoluir
--> Flexibilidade e mudanças continuas, reduzindo a entropia

10. Data
--> "Data is the new Oil" -- Clive Humby
--> dados no Centro, Cliente no Centro, Metricas de Sucesso (NPS), tempo de resposta, taxa de erro, satisfação do cliente e a eficiencia operacional
--> Achar formas de tornar publico, dados para servir pessoas
--> Something like DATALAKES

11. Finops
--> Alocação de Custos por Equipes, Dimensionamento de Recursos, Economia com Resarvas e Descontos, Monitoramento e Otimização Continua