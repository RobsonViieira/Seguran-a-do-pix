# Seguran-a-do-pix
Sistemas de transferências bancárias com Flask, SQlite  e controle de concorrência
# Segurança Financeira - Golpe do Pix Simultâneo

Este projeto visa identificar e prevenir golpes do tipo "Pix Simultâneo", utilizando técnicas de Inteligência Artificial para classificar transações financeiras suspeitas.

## Descrição

O objetivo é treinar um modelo de machine learning que seja capaz de analisar transações de pagamentos via Pix em tempo real e identificar padrões de fraude, como o golpe do "Pix Simultâneo", onde o criminoso tenta realizar transferências fraudulentas em vários dispositivos ao mesmo tempo.

## Funcionalidades

- **Análise de Transações:** O modelo avalia dados de transações financeiras (valor, horário, localização, etc.) para prever se uma transação é legítima ou fraudulenta.
- **Detecção de Golpes:** Identificação de tentativas de fraudes com múltiplas transações simultâneas.
- **Avaliação em Tempo Real:** O sistema pode ser implementado para avaliação em tempo real de transações.

## Tecnologias Usadas

- Python 3
- scikit-learn
- pandas
- numpy

## Como Executar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/seguranca-financeira-golpe-pix-simultaneo.git
    ```

2. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

3. Execute o script principal para treinar e avaliar o modelo:
    ```bash
    python main.py
    ```

## Exemplo de Uso

Você pode treinar o modelo com dados simulados ou reais de transações financeiras para verificar a eficácia da detecção de fraudes. Adapte o código conforme necessário.

## Licença

Este projeto está licenciado sob a Licença MIT.
