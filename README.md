# 🔐 Identificador de Bandeiras de Cartões de Crédito 💳

Olá! 👋  
Seja bem-vindo(a) ao meu projeto de detecção de bandeiras de cartões de crédito!

Este é um projeto simples, desenvolvido com o objetivo de criar uma aplicação em **Python** capaz de identificar a bandeira de um cartão de crédito com base em seu número.

Além disso, explorei o uso do **GitHub Copilot** como assistente de codificação — uma ferramenta que pode acelerar o desenvolvimento, sugerir trechos de código e aumentar a produtividade.

---

## 🧠 O que você vai encontrar aqui

- Um script que identifica a bandeira de um cartão a partir dos primeiros dígitos
- Um conjunto de testes automatizados para validar a aplicação
- Um código simples, limpo e fácil de entender

---

## 🚀 Tecnologias Utilizadas

- Python 3.13  
- Visual Studio Code  
- GitHub Copilot (IA para desenvolvimento)  
- Testes automatizados  
- Estrutura de diretórios clara  
- Muita vontade de aprender 😄

---

## 🎯 Funcionalidades

- **Entrada flexível**: aceita números de cartão como string, com ou sem espaços
- **Identificação automática da bandeira**: Visa, MasterCard e outras, com base nos prefixos
- **Validação básica**: verifica se o número inserido segue um padrão válido
- **Função reutilizável**: `get_card_brand` pode ser aplicada em outros projetos
- **Testes automatizados**: garantem o correto funcionamento da lógica
- **Exportação de resultados**: os resultados dos testes são registrados em `results/test_results.txt` para rastreabilidade
- **Organização clara**: código, testes, resultados e documentação separados em pastas específicas

---

## 🤖 Uso do GitHub Copilot

Durante o desenvolvimento deste projeto, o **GitHub Copilot** foi utilizado como assistente de codificação para:

- Criar a estrutura da função `get_card_brand`, responsável por identificar a bandeira do cartão;
- Sugerir e gerar rapidamente os primeiros casos de teste;
- Otimizar trechos de código, melhorando a legibilidade e organização;
- Criar a lógica dos testes automatizados com base nos cenários definidos;
- Acelerar o desenvolvimento, permitindo validar ideias de forma ágil e prática;
- Auxiliar na criação do código para exportar os resultados dos testes para o arquivo `.txt`.

Essa experiência demonstrou como a inteligência artificial pode ser uma aliada poderosa no processo de aprendizagem e desenvolvimento, sem substituir o raciocínio humano — apenas potencializando a produtividade e ajudando na escrita de um código mais limpo e eficiente.

---

## 🖼️ Imagens

Na pasta `images` você encontrará capturas de tela relacionadas à execução do projeto:

- [📷 Execução do código](images/execucao_codigo.png): mostra o processo de execução do código principal.
- [🧪 Execução dos testes](images/execucao_testes.png): exibe a execução dos testes automatizados.
- [📄 Resultado dos testes](images/resultado_testes.png): apresenta a saída e os resultados obtidos após a execução dos testes.

Essas imagens ajudam a visualizar o funcionamento do código e a validação dos testes.

---

## 📁 Estrutura do Projeto

card-flag-detector/
- src/ # Código-fonte da aplicação
  - main.py # Função principal que identifica a bandeira
    
- tests/ # Testes automatizados
  - test_main.py # Casos de teste
    
- results/ # Resultados de execução
  - test_results.txt # Arquivo de saída com resultados dos testes
      
- notes/ # Documentações adicionais
  - base.png # Tabela com prefixos (BIN/IIN) e quantidade de dígitos por bandeira
  - notas_importantes.md # Observações e anotações relevantes

- images/ # Capturas de tela da execução do código e testes
    
- README.md # Documentação principal do projeto

---
