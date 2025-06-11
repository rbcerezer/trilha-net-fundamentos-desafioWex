# 🚗 DIO - Bootcamp End to End Engineering - Sintaxes Basicas com .Net C#  
🔗 www.dio.me

## 🎯 Desafio de Projeto

Chegou a hora de colocar em prática tudo o que aprendi no modulo "Sintaxe Basica" do  **Bootcamp End to End Engineering** da [DIO](https://dio.me) + [Wex](https://www.wexinc.com/pt-br/) !  
Neste desafio, eu fui convidado a desenvolver um sistema de **estacionamento** – simples, direto e muito útil. 😄

---

## 🧩 O cenário

Imagine que fui contratado para criar um sistema capaz de gerenciar um estacionamento. O sistema precisa:

✅ Cadastrar veículos  
✅ Remover veículos (calculando o valor a ser pago 💰)  
✅ Listar todos os veículos estacionados

Legal, né? Então bora pra prática!

---

## 🛠️ O que eu vou construir

Vou desenvolver uma classe chamada **`Estacionamento`**, que será o cérebro do sistema.  
Olha só o que ela precisa conter:

![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)

### 🔐 Atributos da classe:

- **`precoInicial`**: do tipo `decimal`, representa o valor cobrado na entrada do estacionamento.  
- **`precoPorHora`**: também `decimal`, é o valor cobrado por hora de permanência.  
- **`veiculos`**: uma `List<string>` que guarda as placas dos veículos que estão estacionados.

---

### 🧪 Os métodos implementados:

🔸 **`AdicionarVeiculo`**  
Aqui, eu vou ler uma placa digitada e adicioná-la à lista de veículos.

🔸 **`RemoverVeiculo`**  
Esse método vai verificar se o veículo está no estacionamento.  
Se estiver, o sistema vai pedir a quantidade de horas que ele ficou, calcular o valor total com a fórmula:  
💸 `precoInicial + (precoPorHora * horas)`  
E depois, exibir o valor cobrado.

🔸 **`ListarVeiculos`**  
Se houver veículos estacionados, o sistema vai listar todos eles.  
Se não tiver nenhum, vou exibir a mensagem:  
🚫 “Não há veículos estacionados.”

---

## 🧭 O menu do sistema

Para deixar a interação mais amigável, vou criar um menu no console com as seguintes opções:

```
1️⃣ Cadastrar veículo  
2️⃣ Remover veículo  
3️⃣ Listar veículos  
4️⃣ Encerrar o programa
```

---

## 💡 Bora codar!

O código base já está parcialmente pronto. Agora, é comigo! 😎  
Vou procurar por `// TODO` no código e implementar tudo o que foi descrito aqui.

---

🚀 Vamos nessa!  
Mais um passo na minha jornada como dev .NET. 💻🔥  

---

🙏 Agradecimentos

Gostaria de agradecer à [DIO](https://www.dio.me) e à [Wex](https://www.wexinc.com) pela oportunidade incrível de aprendizado e desenvolvimento profissional. Essa jornada tem sido transformadora! 🚀💙
