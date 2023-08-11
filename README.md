# **Atividades Dadosfera**

## Case 1:
Coletaria dados como o tempo médio de resposta da equipe de suporte, o número de tickets abertos e fechados, o tempo médio de resolução de problemas e o número de avaliações positivas e negativas dos clientes. Com esses dados, você pode identificar os pontos fortes e fracos da equipe de suporte e melhorar continuamente o suporte ao produto. 

## Case 2:
A gestão de mudanças é o processo de preparar-se para qualquer nova mudança organizacional e levá-la a bom termo. É geralmente durante o processo de gestão de mudanças que se prepara a transição para uma nova mudança, se obtém apoio organizacional para o que quer que a mudança exija e se implementa a mudança cuidadosamente com o passar do tempo.

## Case 3:
- Criar usuários individuais.
- Requerer senhas fortes.
- Usar múltiplos fatores de autenticação.
- Revisar regularmente os usuários criados.

## Case 4:
  Os chatbots podem melhorar a satisfação e o envolvimento do cliente de várias maneiras. Eles podem oferecer suporte ao cliente baseado em chatbot, experiências de usuário personalizadas, auxiliar os clientes na tomada de decisões, reduzir custos e otimizar recursos, coletar dados e fornecer insights diferenciados de dados de clientes.

## Case 5
```SQL
SELECT id, name AS "Nome", email AS "Email", dt_criacao AS "Data de Criação"
FROM user_emails
WHERE dt_criacao >= DATEADD(day, -30, GETDATE());
```
<br>
<br>
 Esta consulta seleciona todos os usuários da tabela “user_emails” que se cadastraram nos últimos 30 dias. A função “DATEADD” é usada para subtrair 30 dias da data atual (GETDATE) e a cláusula “WHERE” é usada para selecionar apenas os usuários que foram criados após essa data.
    
### Relatório de usuários cadastrados nos últimos 30 dias
---

| ID | Nome | Email | Data de Criação |
|----|------|-------|----------------|
| 1  | João Silva | joao.silva@example.com | 2023-08-01 |
| 2  | Maria Souza | maria.souza@example.com | 2023-08-05 |
| 3  | José Santos | jose.santos@example.com | 2023-08-10 |
| 4  | Ana Oliveira | ana.oliveira@example.com | 2023-08-15 |
---
