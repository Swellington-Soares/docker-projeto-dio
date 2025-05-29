# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 28/05/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Swellington Soares

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Swellington Soares. O objetivo do projeto foi *elencar 3 serviços AWS com a finalidade de realizar diminuição de custos imediatos*.

A Abstergo Industries, como empresa do setor farmacêutico, possui demandas específicas de armazenamento seguro de dados clínicos, processamento de grandes volumes de informação científica e conformidade com normas regulatórias. A adoção de soluções em nuvem visa atender essas demandas com escalabilidade e controle de custos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

---

### Etapa 1
- **Nome da ferramenta:** AWS Lambda  
- **Foco da ferramenta:** Execução de código sob demanda, sem provisionamento de servidores  
- **Descrição de caso de uso:** Scripts de análise de dados laboratoriais e automações de workflows internos estavam sendo executados em servidores dedicados com baixa utilização. Com a adoção do AWS Lambda, essas tarefas passaram a ser executadas sob demanda, acionadas por eventos como uploads no Amazon S3 (por exemplo, resultados de testes clínicos). Isso reduziu o custo com infraestrutura ociosa e aumentou a eficiência dos processos automatizados.

---

### Etapa 2
- **Nome da ferramenta:** Amazon S3  
- **Foco da ferramenta:** Armazenamento seguro, escalável e com baixo custo  
- **Descrição de caso de uso:** Dados de ensaios clínicos, imagens médicas, documentos regulatórios e arquivos históricos foram migrados para o Amazon S3. Utilizando políticas de versionamento, criptografia (AES-256) e ciclo de vida (migração para o Glacier após 90 dias), foi possível garantir segurança, conformidade com regulamentações como a HIPAA e redução de custos operacionais com armazenamento local.

---

### Etapa 3
- **Nome da ferramenta:** AWS Cost Explorer  
- **Foco da ferramenta:** Monitoramento e otimização de gastos com recursos AWS  
- **Descrição de caso de uso:** Para controlar os investimentos em tecnologia e garantir sustentabilidade financeira do ambiente em nuvem, foi implementado o AWS Cost Explorer. A ferramenta permitiu mapear recursos subutilizados — como instâncias EC2 superdimensionadas utilizadas em simulações farmacológicas — e readequar seus tamanhos. Alertas orçamentários e relatórios por centro de custo foram configurados, proporcionando visibilidade e controle financeiro mais assertivo.

---

## Conclusão

A implementação de ferramentas na empresa *Abstergo Industries* tem como esperado *a redução de custos operacionais, aumento da escalabilidade, automação de tarefas críticas e conformidade com regulamentações do setor farmacêutico*, o que aumentará a eficiência e a produtividade da empresa.  
Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos.

## Anexos

- [Documentação do AWS Lambda](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)  
- [Documentação do Amazon S3](https://docs.aws.amazon.com/s3/index.html)  
- [Documentação do AWS Cost Explorer](https://docs.aws.amazon.com/cost-management/latest/userguide/cost-explorer-what-is.html)

---
