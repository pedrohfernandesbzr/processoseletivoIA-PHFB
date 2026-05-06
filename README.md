## 📝 Relatório do Candidato - Desaifio IoT



### 👤 Identificação do Candidato

* **Nome completo: Pedro Henrique Fernandes Bezerra**
* **GitHub: https://github.com/pedrohfernandesbzr**

\---

## 1️. Visão Geral da Solução

**Introdução**

Os propósitos deste projeto são, de forma primária, ser um sistema auxiliar para labotórios de engenharia civil, e de forma secundária, servir de base para a criação de sistemas embarcados para o canteiro de obra, capazes de expandir as aplicações da metodologia BIM mais fielmente ao mundo real, seja antes, durante e até após a consolidação da edificação. Esta solução, em especial, servirá como instrumento de coleta de dados em processos de ensaios em corpos de prova de concreto, especificamente concretos compostos por aglomerantes quimicamente ativos do tipo hidráulicos, ou seja, compostos com misturas que solidificam reagindo com água, como cimento, areia e brita.

Através de sensores, poderá ser utilizado para monitorar e coletar informações sobre os processos de solidificação, endurecimento, cura e compressão do concreto, sendo a cura submersa ou não. Com o monitoramento ininterrúpto de variáveis físicas através de sensores, como temperatura e humidade, será possível observar e descrever fenômenos físicos do concreto de forma mais completa, presisa e detalhada.

Inicialmente, numa primeira versão, o sistema será focado em fenômenos internos causados pela temperatura, humidade e preessão. Com sensores, o sistema medirá as temperaturas, humidades e pressões internas e externas ao longo de cada processo e o expaço de tempo entre os processos de ensaio. Então os dados serão armazenados, sendo possível estração para análises mais detalhadas, como criação de séries temporais, análise em programas dedicados da área e cálculos mais complexos. Com isso, será possível compreender melhor como o concreto se comporta.

O projeto está sendo pensado para seguir as normas ABNT que regem esse tipo de ensaio, como as NBRs 5738 (sobre os procedimentos para moldagem e cura), 5739 (método de ensaio de compressão para determinar resistência), e a 7680 (extração, preparo e ensaio de testemunhos, que são os corpos de prova retirados da estrutura já pronta).



**Como utilizar o sistema**



1. **Cadastramento de Novo Ensaio**: o usuário deverá, primeiro, cadastrar um novo ensaio, informando dados de identificação, materiais, agregados, aditivos, tipos de aglomerantes, entre outros dados técnicos.



2. **Preparação da amostra:** após o cadastramento, o usuário deverá preparar a amostra de concreto e enformar. Imediatamente após, colocará o Sensor de Temperatura e Umidade DHT22 e o no interior da amostra.



3. **Solidificação**: com isso, o usuário deverá apertar o botão "Ensaio". Aqui, iniciará a coleta de dados do processo de solidificação.



4. **Endurecimento**: quando a pasta estiver solidificada (ainda com aspecto pastoso e deformável sobre pequena pressão, mas estável), aperte o botão P1. Com ele, a coleta de dados da solidificação será encerrada e registrada e registrada e iniciará a coleta de dados vinculada ao endurecimento.



5. **Cura**: quando o processo de cura iniciar, aperte o botão P2. Isso pausará a coleta de dados para o endurecimento e iniciará coleta da cura.



6. **Compressão**: clique no botão P3. A coleta de dados para a compressão iniciará.



7. **Fim do Ensaio**: ao clicar no botão "Ensaio", a coleta de dados irá parar e os dados ficarão prontos para serem exportados quando necessário.



*Em próximas versões, novos sensores e funções serão implementados.*



\---

## 2️. Arquitetura do Sistema Embarcado



* Fluxo principal do programa (`main.py`)



* Estrutura de estados, loops ou temporizações



* Como os componentes interagem entre si



Se desejar, utilize tópicos ou um pequeno diagrama em texto.

\---

## 3️.

Componentes Utilizados na Simulação

Liste os principais componentes definidos no `diagram.json`, por exemplo:

* Tipo de placa utilizada
* LEDs, botões, sensores, atuadores, etc.
* Função de cada componente no sistema

\---

## 4️⃣ Decisões Técnicas Relevantes

Explique brevemente decisões importantes tomadas durante o desenvolvimento, como:

* Organização do código
* Uso de funções, estados ou constantes
* Estratégias para temporização ou controle lógico

\---

## 5️⃣ Resultados Obtidos

Descreva o comportamento final do sistema:

* O que funciona corretamente
* Quais requisitos foram atendidos
* Resultado observado na simulação do Wokwi

\---

## 6️⃣ Comentários Adicionais (Opcional)

Utilize este espaço para comentar, se desejar:

* Dificuldades encontradas
* Limitações da solução
* Melhorias que você faria com mais tempo
* Principais aprendizados durante o desafio

\---

> ✅ Este relatório faz parte da avaliação técnica.  
> Clareza, objetividade e organização são tão importantes quanto o funcionamento do código.

