# Especificação Técnica do Protocolo Flux (v1.0)

Este documento estabelece os critérios técnicos, tabelas de referência e normas de medição para a unidade de medida **Flux (Fx)**.

---

## 1. Tabela de Estados de Intensidade (Escala Fx)

A intensidade de Flux é dividida em quatro zonas de engajamento cognitivo:

| Nível (Fx) | Estado                          | Descrição Técnica                                                                 |
|-----------|----------------------------------|-----------------------------------------------------------------------------------|
| 0.0 – 1.0 | Inércia / Entropia               | Ausência de objetivo claro. Múltiplas trocas de contexto.                          |
| 1.1 – 4.0 | Engajamento Ativo                | Fase de aquecimento. Esforço consciente para manter o foco.                        |
| 4.1 – 8.0 | Zona de Fluxo (Flow)             | Perda da autoconsciência. Alta produtividade e distorção temporal.                |
| 8.1 – 10.0| Fluxo Pleno / Hiperfoco          | Fusão total entre ação e consciência. Imunidade a estímulos externos.              |

---

## 2. Parâmetros de Ascensão (O "Aquecimento")

O ganho de Flux não é instantâneo e segue uma taxa de progressão definida:

- **Taxa Padrão:**  
  +1.0 Fx a cada 10 minutos de foco ininterrupto em uma única tarefa.

- **Saturação:**  
  A progressão torna-se **logarítmica** após o nível **7.0 Fx**, exigindo maior consistência para atingir o limite máximo de **10.0 Fx**.

---

## 3. Critérios de Penalidade e Atrito (O "Decaimento")

A quebra do estado de Flux é quantificada conforme a gravidade da interrupção.

### 3.1. Troca de Contexto Leve (Micro-distração)

- **Ação:**  
  Alternar para uma aba ou aplicativo diferente por menos de 10 segundos.

- **Penalidade:**  
  Redução imediata de **15%** do Fx atual.

### 3.2. Quebra de Fluxo Grave (Reset)

- **Ação:**  
  Abertura de redes sociais, vídeos não relacionados ou ócio por mais de 5 minutos.

- **Penalidade:**  
  Redução imediata de **80%** do Fx atual, retornando ao estado de **Inércia**.

---

## 4. Unidade de Desempenho: Fx-h (Flux-hora)

O desempenho total (**Fx-h**) representa o volume de foco acumulado ao longo do tempo.

### Algoritmo de Cálculo

- O software deve registrar a intensidade **Fx** a cada minuto.
- O resultado final corresponde à **média aritmética** dessas intensidades em relação ao tempo total em horas.

**Exemplo:**  
> 1 hora mantendo média de **5.0 Fx** resulta em exatamente **5.0 Fx-h**.

---

## 5. Requisitos para Softwares de Medição

Para que um software seja considerado um **"Medidor Oficial de Flux"**, ele deve atender aos seguintes critérios:

- **Monitoramento de Atividade:**  
  Capturar sinais de interação e visibilidade de tela.

- **Privacidade:**  
  Medir a intensidade sem processar ou armazenar o conteúdo privado do usuário.

- **Auditabilidade:**  
  Permitir a exportação de logs para fins de comprovação acadêmica.

---

### Nota do Autor

Esta especificação será refinada conforme novos dados de **telemetria comportamental** forem coletados em **2026**.
