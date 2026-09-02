# 💊 IA na Análise de Feedbacks: Insights para o Varejo Farmacêutico

<img width="1586" height="992" alt="ChatGPT Image 1 de set  de 2026, 22_41_08" src="https://github.com/user-attachments/assets/5aaf0296-a1e5-416a-a72e-e75c8e6d49dd" />


## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio criativo da **DIO**. Como trabalho na **Drogaria São Paulo** tive o objetivo de explorar o uso da **Inteligência Artificial para analisar feedbacks de clientes**.

O desafio consiste em construir um prompt estruturado capaz de transformar avaliações e comentários em insights úteis para a tomada de decisão.

Para tornar o projeto mais próximo de um cenário real de negócio, foi utilizado como contexto o **varejo farmacêutico**, analisando aspectos como atendimento, preços, disponibilidade de produtos, filas, entrega e experiência digital.

> ⚠️ **Os feedbacks utilizados neste projeto são fictícios e foram criados exclusivamente para fins educacionais. Nenhuma informação confidencial ou dado real de clientes foi utilizado.**

---

# 🎯 Objetivos

* Utilizar IA para analisar comentários de clientes;
* Identificar problemas e elogios recorrentes;
* Classificar feedbacks por tema e sentimento;
* Identificar possíveis situações prioritárias;
* Transformar dados não estruturados em insights;
* Sugerir ações para melhorar a experiência do cliente;
* Demonstrar a importância de prompts bem estruturados.

---

# 🧠 O Problema de Negócio

Empresas do varejo recebem diariamente centenas ou milhares de comentários através de diferentes canais.

Esses comentários podem conter informações importantes sobre:

* Qualidade do atendimento;
* Tempo de espera;
* Disponibilidade de medicamentos e produtos;
* Preços;
* Experiência no aplicativo;
* Entregas;
* Problemas no pagamento;
* Organização das lojas.

Porém, analisar manualmente todos esses comentários pode ser um processo lento e complexo.

Neste projeto, a **Inteligência Artificial** é utilizada para ajudar a transformar feedbacks não estruturados em informações organizadas e úteis para a tomada de decisão.

---

# 📊 Dados Analisados

A base de dados poderá conter informações como:

| Campo      | Descrição                           |
| ---------- | ----------------------------------- |
| ID         | Identificador fictício do feedback  |
| Data       | Data da avaliação                   |
| Canal      | Loja física, aplicativo ou delivery |
| Feedback   | Comentário do cliente               |
| Categoria  | Tema identificado                   |
| Sentimento | Positivo, negativo ou neutro        |
| Nota       | Avaliação de 1 a 5                  |
| Urgência   | Baixa, média ou alta                |

---

# 🤖 Construção do Prompt
## 🧱 Passo 1 — Definição da Intenção

O objetivo é utilizar uma IA para analisar feedbacks de clientes do varejo farmacêutico e identificar padrões que possam ajudar a melhorar a experiência do consumidor.

A análise será utilizada como apoio para equipes responsáveis por:

* Experiência do Cliente;
* Atendimento;
* Operações;
* Canais Digitais.

A entrega deverá apresentar insights claros, problemas recorrentes e possíveis ações de melhoria.



## 🧱 Passo 2 — Contexto e Restrições

A IA receberá feedbacks fictícios relacionados a diferentes pontos da jornada do cliente.

Os principais temas analisados serão:

* Atendimento;
* Filas;
* Preços;
* Estoque;
* Aplicativo;
* Delivery;
* Pagamento;
* Organização da loja.

A IA deverá seguir alguns cuidados:

* Utilizar apenas os dados fornecidos;
* Não inventar informações;
* Não criar estatísticas inexistentes;
* Não expor informações pessoais;
* Informar limitações dos dados;
* Basear os insights em evidências presentes nos feedbacks.

---

# 🔥 Prompt Final

> ## Papel da IA
>
> Atue como um **Analista de Dados especializado em Experiência do Cliente (Customer Experience) no varejo farmacêutico**.
>
> Sua tarefa é analisar uma base de feedbacks de clientes para identificar padrões, problemas recorrentes, elogios e oportunidades de melhoria na experiência de compra.
>
> ---
>
> ## Contexto
>
> A análise será utilizada como apoio para equipes responsáveis por atendimento, operações e canais digitais.
>
> O objetivo é transformar comentários não estruturados de clientes em insights claros e acionáveis que possam apoiar a tomada de decisão.
>
> Os feedbacks podem estar relacionados a diferentes pontos da jornada do cliente, incluindo:
>
> * Atendimento em loja;
> * Tempo de espera e filas;
> * Disponibilidade de medicamentos e produtos;
> * Preços e promoções;
> * Aplicativo;
> * Compras online;
> * Delivery;
> * Pagamento;
> * Organização da loja.
>
> ---
>
> ## Dados Disponíveis
>
> A base poderá conter os seguintes campos:
>
> * ID do feedback;
> * Data;
> * Canal de atendimento;
> * Texto do comentário;
> * Nota de satisfação de 1 a 5.
>
> Caso algum campo não esteja disponível, realize a análise apenas com as informações fornecidas.
>
> ---
>
> ## Instruções de Análise
>
> 1. Classifique cada feedback de acordo com o tema principal.
>
> 2. Identifique o sentimento predominante:
>
>    * Positivo;
>    * Negativo;
>    * Neutro;
>    * Misto.
>
> 3. Avalie a urgência do problema:
>
>    * Baixa;
>    * Média;
>    * Alta.
>
> 4. Identifique padrões recorrentes nos comentários.
>
> 5. Destaque os principais:
>
>    * Problemas;
>    * Reclamações;
>    * Elogios;
>    * Oportunidades de melhoria.
>
> 6. Baseie todas as conclusões exclusivamente nos dados fornecidos.
>
> 7. Quando possível, utilize exemplos curtos dos comentários como evidência.
>
> 8. Sugira ações práticas para melhorar a experiência do cliente.
>
> ---
>
> ## Formato da Resposta
>
> Organize a resposta da seguinte forma:
>
> ### 1. Resumo Executivo
>
> Apresente os principais insights encontrados em até 5 tópicos.
>
> ### 2. Análise dos Principais Temas
>
> Crie uma tabela contendo:
>
> | Tema | Sentimento predominante | Problema ou insight identificado | Urgência | Ação sugerida |
> | ---- | ----------------------- | -------------------------------- | -------- | ------------- |
>
> ### 3. Padrões Identificados
>
> Liste os principais padrões encontrados nos feedbacks.
>
> ### 4. Pontos Positivos
>
> Apresente os principais elogios e aspectos positivos identificados.
>
> ### 5. Oportunidades de Melhoria
>
> Sugira ações práticas e priorizadas.
>
> ### 6. Prioridades
>
> Apresente as 3 principais prioridades utilizando os seguintes critérios:
>
> * Frequência do problema;
> * Impacto na experiência do cliente;
> * Nível de urgência.
>
> ---
>
> ## Restrições e Cuidados
>
> * Utilize apenas os dados fornecidos.
> * Não invente números, porcentagens ou estatísticas.
> * Não invente causas que não possam ser comprovadas pelos feedbacks.
> * Não exponha dados pessoais ou informações sensíveis.
> * Caso os dados sejam insuficientes, informe claramente a limitação.
> * Diferencie fatos observados de hipóteses.
> * Utilize linguagem clara, profissional e voltada para tomada de decisão.
>
> ---
>
> **O objetivo final é transformar feedbacks individuais em insights que possam ajudar a empresa a melhorar a experiência dos clientes.**

---

# 📈 Exemplo de Insights Esperados

A análise poderá identificar situações como:

## 🔴 Problemas Recorrentes

* Reclamações sobre demora no atendimento;
* Dificuldade para encontrar determinados produtos;
* Problemas no aplicativo;
* Atrasos em entregas.

## 🟢 Pontos Positivos

* Bom atendimento dos funcionários;
* Facilidade para encontrar produtos;
* Rapidez no pagamento;
* Boa experiência em compras online.

## 🟡 Oportunidades de Melhoria

* Otimização das filas;
* Melhoria na comunicação sobre estoque;
* Aperfeiçoamento do aplicativo;
* Melhor acompanhamento de pedidos.

---

# ⚠️ Cuidados com os Dados

Por se tratar de um cenário relacionado ao varejo farmacêutico, alguns cuidados são fundamentais.

A análise não deve:

* Expor nomes de clientes;
* Expor informações pessoais;
* Expor informações sensíveis;
* Utilizar dados confidenciais;
* Criar conclusões sem evidências.

> 🔒 **Todos os dados utilizados neste projeto são fictícios e utilizados exclusivamente para fins educacionais.**

---

# 🧩 Habilidades Demonstradas

Este projeto demonstra conhecimentos relacionados a:

* Prompt Engineering;
* Análise de Dados;
* Análise de Dados Não Estruturados;
* Inteligência Artificial;
* Customer Experience;
* Identificação de Padrões;
* Tomada de Decisão Baseada em Dados;
* Organização e Comunicação de Insights.

---

# 🚀 Tecnologias Utilizadas

* 🤖 Inteligência Artificial Generativa;
* 💬 ChatGPT;
* 🐙 GitHub;
* 📝 Markdown;
* 🎓 DIO.

---

# 🔮 Próximos Passos

Como evolução do projeto, os próximos passos podem incluir:

* [ ] Criação de uma base fictícia de feedbacks;
* [ ] Análise dos comentários utilizando IA;
* [ ] Estruturação dos resultados em formato tabular;
* [ ] Criação de gráficos;
* [ ] Desenvolvimento de um dashboard;
* [ ] Comparação entre análise manual e análise assistida por IA.

---

# 📝 Considerações Finais

Este projeto demonstra como **prompts bem estruturados** podem ajudar a transformar dados não estruturados em informações úteis para o negócio.

A qualidade da análise depende diretamente de fatores como:

* Clareza do objetivo;
* Contexto fornecido;
* Critérios de análise;
* Formato esperado da resposta;
* Restrições e cuidados definidos.

A Inteligência Artificial não substitui completamente a análise humana, mas pode acelerar a identificação de padrões e facilitar a transformação de grandes volumes de feedbacks em **insights acionáveis**.

---

## 👨‍💻 Autor

**Juan Vitor Pereira Amorim**

Apaixonado por tecnologia, análise de dados e soluções que transformam informações em decisões.
