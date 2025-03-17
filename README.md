# 📱 Diagramação de Classes do iPhone

## 📋 Sobre o Projeto

Este repositório contém minha implementação do desafio de modelagem de software para representar as funcionalidades de um iPhone. O objetivo foi aplicar **princípios de Programação Orientada a Objetos (POO)** e técnicas de modelagem UML para estruturar um sistema que permite que um iPhone desempenhe três funções principais:

- 📀 **Reprodutor Musical**
- 📞 **Aparelho Telefônico**
- 🌍 **Navegador na Internet**

Ao longo do desenvolvimento, aprendi a importância da abstração, encapsulamento e interfaces na criação de sistemas modulares e bem estruturados.

---

## 📊 Diagrama UML
<p align="center">
  <img src="docs/iPhone-modelagem.png" alt="Diagrama de Classes">
</p>

Este diagrama representa as classes e interfaces que compõem o projeto. Cada uma tem um papel fundamental na organização e funcionamento do sistema.

### 🔹 **iPhone**
A classe `iPhone` é a principal e implementa três interfaces: `ReprodutorMusical`, `AparelhoTelefonico` e `NavegadorInternet`. Isso permite que o dispositivo tenha múltiplas funcionalidades.

### 🔹 **ReprodutorMusical**
Define métodos essenciais para tocar músicas:
- `tocar()`
- `pausar()`
- `selecionarMusica()`

### 🔹 **AparelhoTelefonico**
Define métodos para chamadas telefônicas:
- `ligar()`
- `atender()`
- `iniciarCorreioVoz()`

### 🔹 **NavegadorInternet**
Define métodos para navegação na web:
- `exibirPagina()`
- `adicionarNovaAba()`
- `atualizarPagina()`

Cada interface define um conjunto de funcionalidades que a classe `iPhone` deve implementar, tornando o código modular e reutilizável.

Para mais detalhes, veja o **diagrama completo** [clicando aqui](docs/iPhone-modelagem.pdf).

---

## 💡 Como Executar

1️⃣ **Clone o repositório**:
```sh
git clone https://github.com/SEU_USUARIO/iphone-poo.git
```

2️⃣ **Abra o projeto** na sua IDE Java preferida.

3️⃣ **Explore o código-fonte e o diagrama UML** para entender a estrutura e como cada funcionalidade foi implementada.

4️⃣ **Compile e execute os testes** para validar o funcionamento do sistema.

---

## 🎯 O que Aprendi

✔️ Aplicação de **interfaces** para definir contratos de funcionalidades.  
✔️ Uso de **herança e encapsulamento** para organizar melhor o código.  
✔️ Importância da **modelagem UML** na estruturação de sistemas complexos.  
✔️ Como representar múltiplas responsabilidades em uma única classe.  

Este desafio foi uma experiência valiosa para aprofundar meu conhecimento em **POO, design de sistemas e modelagem de software**. 🚀

---

## 📜 Licença

Projeto aberto para estudo e aprimoramento! Se achou útil, contribua dando uma ⭐ no repositório. 😊

