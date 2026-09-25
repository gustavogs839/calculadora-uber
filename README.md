# 🧮 Calculadora de Corridas Particulares

Uma calculadora web simples para motoristas calcularem o valor de suas corridas particulares.

![Preview da App](https://img.shields.io/badge/Interface-Mobile--First-ff85a1?style=for-the-badge)
![Tech](https://img.shields.io/badge/HTML5-CSS3-JS-pink?style=for-the-badge&logo=javascript)

## ✨ Funcionalidades

- **Corrida por quilômetro:** Usa `R$ 10,00` de valor inicial mais `R$ 2,50` por quilômetro rodado como padrão.
- **Corrida por hora:** Usa `R$ 10,00` de valor inicial mais `R$ 75,00` por hora como padrão, usando os horários de início e fim.
- **Valores editáveis:** O motorista pode alterar o valor inicial e a tarifa da modalidade antes de calcular.
- **Comprovante visual:** Resultado compacto e legível para capturar a tela e enviar ao cliente pelo WhatsApp.
- **Recibo para o cliente:** Botão que abre um recibo limpo com modalidade, medida, tarifas e valor total.
- **Design responsivo:** Interface otimizada para uso no celular.
- **Favicon Personalizado:** Ícone de calculadora diretamente na aba do navegador via SVG.

## 🧮 A lógica por trás do cálculo

Os valores abaixo são os padrões e podem ser alterados na tela.

Para corridas por quilômetro:

$$ValorCobrar = ValorInicial + (Quilômetros \times ValorPorKm)$$

Para corridas por hora, o tempo entre os horários é convertido em horas:

$$ValorCobrar = ValorInicial + (Horas \times ValorPorHora)$$

Isso garante que, quando a operadora retirar a percentagem dela sobre o total, o que sobra é exatamente o teu valor pretendido.

## 🚀 Tecnologias Utilizadas

* **HTML5:** Estrutura semântica.
* **CSS3:** Estilização com Variáveis, Flexbox e Animações `@keyframes`.
* **JavaScript (Vanilla):** Lógica de cálculo por km e por hora, com manipulação do DOM.
* **Google Fonts:** Fonte 'Poppins' para máxima legibilidade.
* **Heroicons:** Ícone SVG elegante.

## 🛠️ Como usar

1. Acede ao link do projeto (GitHub Pages).
2. Seleciona o tipo de corrida.
3. Informa os quilômetros ou os horários de início e fim.
4. Clica em **Calcular corrida**.
5. O sistema mostrará o valor a cobrar do cliente.

---
💡 *Projeto desenvolvido para facilitar o cálculo de corridas particulares.*
