# DIO - Trilha .NET - Explorando a linguagem C# / DIO - .NET Trail - Exploring the C# Language

www.dio.me

---

## Desafio de Projeto / Project Challenge

Para este desafio, voce precisara usar seus conhecimentos adquiridos no modulo de explorando a linguagem C#, da trilha .NET da DIO.

For this challenge, you will need to use the knowledge acquired in the Exploring the C# Language module of the DIO .NET trail.

---

## Contexto / Context

Voce foi contratado para construir um sistema de hospedagem, que sera usado para realizar uma reserva em um hotel. Voce precisara usar a classe Pessoa, que representa o hospede, a classe Suite, e a classe Reserva, que fara um relacionamento entre ambos.

You have been hired to build a hosting system that will be used to make a hotel reservation. You will need to use the Person class representing the guest, the Suite class, and the Reservation class that will create a relationship between them.

O seu programa devera calcular corretamente os valores dos metodos da classe Reserva, que precisara trazer a quantidade de hospedes e o valor da diaria, concedendo um desconto de 10% para caso a reserva seja para um periodo maior que 10 dias.

Your program should correctly calculate the values of the Reservation class methods, which need to return the number of guests and the daily rate value, granting a 10% discount if the reservation is for a period longer than 10 days.

---

## Regras e Validacoes / Rules and Validations

1. Nao deve ser possivel realizar uma reserva de uma suite com capacidade menor do que a quantidade de hospedes. Exemplo: Se e uma suite capaz de hospedar 2 pessoas, entao ao passar 3 hospedes devera retornar uma exception.
   It should not be possible to make a reservation for a suite with a capacity smaller than the number of guests. Example: If it is a suite that can host 2 people, then passing 3 guests should return an exception.

2. O metodo ObterQuantidadeHospedes da classe Reserva devera retornar a quantidade total de hospedes, enquanto que o metodo CalcularValorDiaria devera retornar o valor da diaria (Dias reservados x valor da diaria).
   The ObterQuantidadeHospedes method of the Reservation class should return the total number of guests, while the CalcularValorDiaria method should return the daily rate value (Reserved days x daily rate value).

3. Caso seja feita uma reserva igual ou maior que 10 dias, devera ser concedido um desconto de 10% no valor da diaria.
   If a reservation is made for 10 days or more, a 10% discount on the daily rate value should be granted.

---

## Diagrama / Diagram

![Diagrama de classe estacionamento / Parking class diagram](diagrama_classe_hotel.png)

---

## Solucao / Solution

O codigo esta pela metade, e voce devera dar continuidade obedecendo as regras descritas acima, para que no final, tenhamos um programa funcional. Procure pela palavra comentada "TODO" no codigo, em seguida, implemente conforme as regras acima.

The code is halfway done, and you should continue following the rules described above, so that in the end we have a functional program. Look for the commented word "TODO" in the code, then implement according to the rules above.

---

## Tecnologias / Technologies

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

## Autor / Author

Marcus Lafaiete - [@marcuslaf](https://github.com/marcuslaf)
