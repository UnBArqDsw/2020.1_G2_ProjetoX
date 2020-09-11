# Cost estimate

The calculation of the cost estimate considers three factors acquisition, personal and tool.

## 1.1 Acquisition cost

|           Equipment|           Amount|                           Goal|       Unit value|            Price|
|--------------------|-----------------|-------------------------------|-----------------|-----------------|
|           Notebooks|           5 unit|       Development and planning|         R$ 4.000|     R$ 20.000,00|
|  Broadband internet|         4 months|       Development and planning|      R$100/month|       R$ 2000,00|

## 1.2 Personal cost

|                                            Role|     Amount| Salary/month (160h total)| Salary/hour|      Total|
|------------------------------------------------|-----------|--------------------------|------------|-----------|
|                                Middle developer|          5|                  R$ 4.000|     R$25,00| R$ 22.500¹|
|   Software architect, DevOps, Scrum Master e PO|          5|                  R$ 6.500|     R$40,63| R$ 36.567¹|

¹ price for 5 members working 12h/week for 15 sprints week-long.

## 1.3 Tool cost

|          Tool name|                                  Goal| Total price|
|-------------------|--------------------------------------|------------|
|       Google Drive|                            File share|        R$ 0|
|        Text editor|           Creating documents and code|        R$ 0|
|             GitHub| Source code management and repository|        R$ 0|
|     GitHub Actions|                        Pipeline CI/CD|       R$ 0¹|
|     Google domains|      Domain name registration service|    R$ 50,00|
|             Docker|                        Container apps|        R$ 0|
|         Amazon EC2|                    Host cloud service|       R$ 0²|
|         Amazon RDS|                Database cloud service|       R$ 0³|
|         Amazon SES|                   Email cloud service|       R$ 0⁴|
|      Amazon Lambda|         Lambda function cloud service|       R$ 0⁵|
|           RabbitMq|                        Message broker|        R$ 0|
|           Telegram|                  Members comunication|        R$ 0|

¹ price valid for 2000 minutes/month, after that will cost US$ 0.008 per minute.

² price valid for 750 hours/year, after that will cost US$ 0,0116 per hour on demand.

³ price valid for 750 hours/year, after that will cost US$ 0,017 per hour on demand.

⁴ price valid for 62000 emails sents, after that will cost US$ 0,10 for every 1000 emails sents.

⁵ price valid if have applications in ec2 and the limit is 1 million request or 400.000 gb/s in compution time, 
after that will cost US$0,20 at every 1 million request and US$ 0,0000166667 for every gb/s


## 1.4 Total cost

|        Cost| Total value|
|------------|------------|
| Acquisition|   R$ 22.000|
|    Personal|   R$ 59.067|
|       Tools|       R$ 50|

The total value for estimated cost is R$ 81.117,00
Considering the risks, will increase 10% of total project value, **the final value for estimated cost is R$89.228,7**.

---
## References
---
Meller, Maristela Corrêa. Modelos Para Estimar Custos De Software: Estudo Comparativo Com Softwares De Pequeno Porte. 2002. Disponível em: https://repositorio.ufsc.br/xmlui/handle/123456789/82351



## Document Versioning

---
|    Date    | Author(s) |             Description             |    Version    |
|------------|---------|-------------------------------------|-------------|
|  09/05/2020| Ygor Galeno |                    Document creation| 0.1 |
|  09/06/2020| Ygor Galeno |                    Finish document|  0.2 |
