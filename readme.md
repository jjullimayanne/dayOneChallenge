
# 🎁 Desafio de Cálculo de Distância Absoluta 🎮

[🔗 Leia o desafio do Advent of Code 2024 Day 1 completo aqui](https://adventofcode.com/2024/day/1)

## 📚 O Desafio
Você está encarregado de resolver um problema matemático divertido e simples, envolvendo **listas de números**! Para participar, você precisa:

1. Ordenar duas listas de números.
2. Calcular a **distância absoluta** entre os números correspondentes das listas ordenadas.
3. Somar todas as distâncias absolutas.
4. **Explicar seu código com suas próprias palavras**, para que todos possam entender sua lógica.

Após completar o desafio, envie sua solução abrindo um Pull Request (PR) neste repositório com **seu nome como título do PR**.

⭐ **Quem participar estará concorrendo a um cupom do iFood no valor de R$50!**

## ⚡ Passo a Passo do Desafio

1. **Ordenar as listas**:
   - Você tem duas listas de números:
     ```javascript
     const leftList = [3, 4, 2, 1, 3, 3];
     const rightList = [4, 3, 5, 3, 9, 3];
     ```
   - Ordene cada lista em ordem crescente usando o método `sort`.

2. **Calcular distância absoluta**:
   - Para cada elemento correspondente nas duas listas ordenadas, calcule a distância absoluta:
     
     **Fórmula:**
     ```javascript
     Math.abs(leftList[i] - rightList[i])
     ```

3. **Somar as distâncias**:
   - Some todas as distâncias absolutas para obter o total.

4. **Explicar o código**:
   - Inclua uma explicação clara sobre como você implementou a solução, passo a passo, usando suas palavras.

5. **Adicionar comentários no código**:
   - Certifique-se de incluir comentários explicando cada parte do seu código, para que fique fácil de entender.

6. **Incluir prints do console no PR**:
   - No Pull Request, adicione capturas de tela ou logs do console mostrando o resultado do seu código funcionando.

7. **Envie sua solução**:
   - Abra um PR com sua solução no repositório.
   - Dê ao PR o título com **seu nome** para participar do sorteio.

## 🎉 Regras do Sorteio
- 📅 **O sorteio acontece no domingo, 12 de janeiro de 2025, às 16h,  
- Todos os participantes que abrirem um PR com uma solução válida estarão concorrendo.
- O vencedor receberá um cupom do iFood no valor de R$30!

## 🎮 Exemplo de Solução
Aqui está um exemplo de como sua função pode ser implementada:

```javascript
// Lista de números fornecida para o desafio
const leftList = [3, 4, 2, 1, 3, 3];
const rightList = [4, 3, 5, 3, 9, 3];

// Função para ordenar uma lista de números em ordem crescente
const sortedList = (list) => {
  return [...list].sort((a, b) => a - b); // Usando spread para criar uma cópia
};

// Função para calcular a distância absoluta entre dois números
const calculateDistance...

// Função para calcular a soma total das distâncias absolutas
const calculateTotalDistance = (leftList, rightList) => {

};

// Calculando a distância total
const totalDistance = calculateTotalDistance(leftList, rightList);
console.log(`A distância total é: ${totalDistance}`); // Resultado no console
```

## 🏆 Boa sorte e divirta-se! 🎮
