# Simulador de Empréstimo

## Visão Geral

**Simulador de Empréstimo** é uma aplicação web simples e intuitiva desenvolvida para ajudar os usuários a calcular planos de parcelamento com base no montante desejado, número de prestações e taxas de juros aplicadas. Ideal para gerenciar e simular cenários de financiamento, a aplicação apresenta os resultados de forma organizada e clara em uma tabela interativa.

## Funcionalidades

- **Cálculo Rápido:** Insira o valor do empréstimo e visualize instantaneamente os valores das parcelas para diferentes taxas e prazos.
- **Tabela Interativa:** Os resultados são exibidos em uma tabela estruturada com informações detalhadas sobre:
  - Taxas de juros
  - Número de parcelas
  - Valor de cada parcela
  - Valor total com juros
- **Interface Amigável:** Design simples e intuitivo para facilitar o uso.

## Tecnologias Utilizadas

- **HTML5:** Estrutura da página.
- **CSS3:** Estilos visuais.
- **JavaScript:** Lógica do cálculo e geração dinâmica da tabela.

## Estrutura do Projeto


loan_simulator/
├── index.html           # Página principal
├── styles.css           # Estilos CSS personalizados
├── script.js            # Script JavaScript para cálculos e manipulação de tabela
├── README.md            # Documentação do projeto


## Instalação

1. **Clone o Repositório**

   bash
   git clone https://github.com/dougdotcon/SimuladorParcelas.git
   

2. **Navegue até o Diretório do Projeto**

   bash
   cd SimuladorParcelas
   

3. **Abra o Arquivo `index.html` no Navegador**

   Você pode abrir o arquivo diretamente no seu navegador preferido clicando duas vezes sobre ele ou utilizando um servidor local.

   **Usando um Servidor Local com Python:**

   bash
   # Para Python 3.x
   python -m http.server 8000

   # Acesse http://localhost:8000 no seu navegador
   

## Uso

1. **Digite o Valor a Financiar**
   - Insira o valor no campo "Digite o valor a parcelar".

2. **Calcule as Parcelas**
   - Clique no botão **"Calcular"**.
   - Os valores das parcelas serão calculados com base em diferentes taxas e prazos.

3. **Visualize os Resultados**
   - A tabela exibirá:
     - Taxas de juros aplicadas
     - Número de parcelas
     - Valor de cada parcela
     - Valor total ao final do período

## Contribuição

Contribuições são bem-vindas! Se você deseja melhorar este projeto, siga os passos abaixo:

1. **Fork este Repositório**
2. **Crie uma Branch para sua Feature**

   bash
   git checkout -b feature/nova-feature
   

3. **Commit suas Alterações**

   bash
   git commit -m "Adiciona nova feature"
   

4. **Push para a Branch**

   bash
   git push origin feature/nova-feature
   

5. **Abra um Pull Request**

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## Contato

- **Autor:** Douglas H. Machado
- **Email:** [dougdotcon@gmail.com](mailto:dougdotcon@gmail.com)
- **LinkedIn:** [dougdoton](https://www.linkedin.com/in/dougdoton/)
- **GitHub:** [dougdotcon](https://github.com/dougdotcon)
