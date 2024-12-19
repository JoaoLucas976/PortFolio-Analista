# **Cryptocurrency Dashboard**

Este repositório contém o código-fonte de um dashboard interativo para gerenciamento e monitoramento de **criptomoedas**. O objetivo principal é fornecer uma visão consolidada das suas moedas, destacando informações financeiras críticas e ajudando na tomada de decisões.

---

<img src="Dashboard_Cryptomoedas.png">

---

## **Funcionalidades do Dashboard**

1. **Valor de Compra**: Mostra o preço pelo qual a criptomoeda foi adquirida.  
2. **Quantidade**: Exibe a quantidade total da criptomoeda na carteira.  
3. **Valor Atual**: Obtém o preço atual da criptomoeda em tempo real, utilizando dados de APIs confiáveis.  
4. **Total na Carteira**: Calcula o valor total atual da carteira com base na quantidade e no valor atual da moeda.  
5. **Diferença**: Mostra a diferença percentual e absoluta entre o valor de compra e o valor atual, indicando lucro ou prejuízo.  
6. **Momento de Venda**: Identifica automaticamente se é um bom momento para vender, baseado em critérios personalizados como diferença percentual ou outros indicadores definidos pelo usuário.

---

## **Tecnologias Utilizadas**

- **Python**: Para coleta de dados, processamento e integração com APIs.  
- **APIs de Criptomoedas**: Utilização da [CoinGecko](https://www.coingecko.com/) para obter dados de preços em tempo real.  
- **Power BI**: Criação do dashboard interativo para visualização dos dados de forma clara e intuitiva.  
- **Pandas e NumPy**: Processamento e manipulação de dados financeiros.  

---

## **Instalação e Configuração**

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/cryptocurrency-dashboard.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure sua API Key (se necessário):
   - Para APIs que requerem autenticação, adicione sua chave ao arquivo `.env`:
     ```plaintext
     API_KEY=SUA_CHAVE_AQUI
     ```

4. Execute o script para carregar os dados no dashboard:
   ```bash
   python main.py
   ```

---

## **Como Usar o Dashboard**

1. **Importar os Dados**: Utilize o script Python para coletar dados em tempo real e gerar um arquivo consolidado (CSV ou JSON).  
2. **Atualizar o Dashboard no Power BI**: Carregue o arquivo consolidado no Power BI para atualizar as informações.  
3. **Analisar os Dados**:
   - Verifique a lucratividade de cada moeda.
   - Identifique rapidamente quais moedas estão no momento ideal para venda.

---

## **Contribuição**

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request com melhorias, correções ou novas funcionalidades.

---

## **Licença**

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais informações.
