
# Comparativo: Databricks Cloud vs Databricks Free Edition

## 1. Limitações da Free Edition

- **Recursos de computação**:
  - Apenas **compute serverless**; sem suporte para configurações customizadas ou GPU.
  - Máquinas pequenas (ex: SQL Warehouse limitado a “2X-Small”).
  - Máximo de **5 jobs simultâneos** por conta.
  - Só 1 pipeline Lakeflow ativo por tipo.
  - Endpoints de model serving e vector search com muitas restrições (sem GPU, sem throughput provisionado, modelos limitados).
  - Apenas 1 app ativo por conta, que para automaticamente após até 24h.

- **Recursos não suportados**:
  - **R**, **Scala**, tabelas online, clean rooms, Agent Bricks, Lakebase, armazenamento customizado, e recursos legados.

- **Administração e segurança**:
  - Apenas 1 workspace e 1 metastore por conta.
  - Sem acesso ao console da conta, APIs de nível de conta, compliance, segurança personalizada ou redes privadas.
  - Autenticação limitada: apenas e-mail com OTP, Google e Microsoft. Sem SSO, SCIM.

- **Suporte e uso**:
  - Sem SLA, sem suporte oficial, uso não comercial (contas inativas podem ser deletadas).

- **Privacidade e conteúdo**:
  - Dados no Free Edition ficam em ambiente multi‑tenant e acessíveis pela equipe da Databricks.

---

## 2. Poder da Free Edition vs Databricks Cloud (pago)

- **Free Edition**:
  - Indicado para **estudantes, educadores, hobistas**; ideal para aprendizado, prototipagem e experimentação.
  - Permite: criar IA básica e agentes, colaborações com notebooks em tempo real, dashboards interativos (por Genie), pipelines com Lakeflow, e suporte do **Databricks Assistant**.
  - Oferece praticamente a mesma **plataforma base** do Databricks completo, dentro de limites calculados.
  - Parte do compromisso de educação da Databricks.

- **Databricks Cloud (pago)**:
  - Total liberdade de configuração: clusters customizáveis, GPU, rede privada, APIs, segurança empresarial, SSO, etc.
  - Suporte a **R, Scala**, tabelas online, clean rooms, Lakebase, e todos os recursos premium.
  - SLA garantido e suporte técnico (depende do plano).
  - Ideal para produção, pipelines MLOps, workloads empresariais, e escalabilidade real.

---

## 3. O que NÃO está disponível na Free Edition (mas está na Cloud paga)

- Recursos avançados:
  - R, Scala, APIs de conta, SSO, rede privada, clean rooms, Lakebase, custom compute, etc.

- Infraestrutura:
  - GPU, throughput provisionado em endpoints, custom clusters.

- Governança e segurança:
  - Não dá para configurar compliance, segurança personalizada ou redes privadas; sem SSO/SCIM.

- Suporte e confiabilidade:
  - Sem SLA, sem suporte, possibilidade de remoção da conta inativa.

---

## Resumo prático

| Recurso                  | Free Edition (grátis)       | Databricks Cloud (pago)          |
|---------------------------|-----------------------------|-----------------------------------|
| Computação                | Serverless, pequena         | Clusters customizáveis, GPU, escalável |
| Linguagens suportadas     | Python, SQL                 | Python, SQL, Scala, R             |
| Segurança e rede          | Básico, sem SSO             | Avançado, compliance, redes privadas |
| Admin/API                 | Limitado                    | Completo                          |
| Suporte / SLA             | Nenhum                      | Disponível dependendo do plano    |
| Produção / uso comercial  | Não permitido               | Permitido, ambiente de produção   |

---

**Conclusão:**  
Use a **Free Edition** se você quer aprender, prototipar ou testar. Se precisa de **poder, segurança, escalabilidade e suporte**, vá de **Databricks Cloud (pago)**.
