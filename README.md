# GS PYTHON
Projeto de sustentabilidade desenvolvido na disciplina de Python para Global Solution da FIAP.

## Integrantes
- Estefany Caetano de Jesus RM: 560181
- Gabrielly Cândido Camargo da Silva RM: 560916
- Luiza Saraçol Ribeiro RM: 560200

## Sobre o Projeto
Este projeto simula o consumo de energia de uma comunidade e a geração de energia renovável (solar e eólica). Ele ajuda a analisar a autossuficiência energética e os impactos econômicos, além de fornecer dicas para reduzir o consumo.
 
## Como Funciona
O programa coleta informações do usuário, como número de casas, consumo médio e capacidade de geração de energia. A partir desses dados, ele calcula:  
1. O consumo total de energia da comunidade em determinado período.  
2. A energia gerada pelas fontes renováveis (solar e eólica).  
3. O valor estimado da conta de luz com base no consumo e no custo por kWh.  
4. O excedente ou déficit de energia comparando consumo e geração.  
5. A **economia gerada** em comparação ao consumo antes de adotar energia renovável.

---

## Modo de Uso
1. Execute o programa em um ambiente Python.  
2. Insira os dados solicitados:  
   - Capacidade de geração solar e eólica (em kWh/dia).  
   - Número de casas e o consumo médio por casa (em kWh/dia).  
   - Período de simulação (em dias).  
   - Custo do kWh, valor da conta de água e consumo mensal anterior.  
3. O programa calculará automaticamente os resultados e exibirá:  
   - Consumo total da comunidade.  
   - Energia renovável gerada.  
   - Valor estimado da conta de luz.  
   - Análise de autossuficiência energética.  
   - Comparação e economia com energia renovável.  
   - Dicas de economia de energia.  

---

## O que o Código Faz
### Configuração Inicial
O código coleta os dados necessários do usuário, como consumo, capacidade de geração e custo médio por kWh.  

### Funções
1. `calcular_consumo_total`: Calcula o consumo total da comunidade em um período com base no número de casas e consumo médio diário.  
2. `calcular_geracao_total`: Calcula a energia gerada somando a capacidade solar e eólica durante o período.  
3. `calcular_valor_conta`: Estima o custo da conta de luz com base no consumo total e no custo por kWh.  

### Análises e Resultados
- Consumo vs. Geração: Determina se a comunidade é autossuficiente ou tem déficit de energia.  
- Economia: Compara o consumo atual com o anterior e calcula a economia na conta de luz.  
- Dicas: Sugere formas de reduzir o consumo caso ele esteja alto.  

## Requisitos
- Python instalado.  
- Nenhuma dependência externa necessária.  


## Exemplos de Entrada e Saída
### Entrada
- Capacidade de geração solar: `50` kWh/dia  
- Capacidade de geração eólica: `30` kWh/dia  
- Número de casas: `10`  
- Consumo médio por casa: `5` kWh/dia  
- Período de simulação: `30` dias  
- Custo do kWh: `0.8` R$  
- Consumo mensal anterior: `2000` kWh  

### Saída
- Consumo total da comunidade: `1500 kWh`  
- Energia gerada: `2400 kWh`  
- Valor estimado da conta de luz: `R$ 1200.00`  
- Excedente: `900 kWh`  
- Economia: `R$ 400.00`  
