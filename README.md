# 🐉 The Greedy Dragon

**The Greedy Dragon** é um jogo de estilo *Boss Rush* e *Bullet Hell* desenvolvido como projeto final para a disciplina de **Introdução à Engenharia da Computação (ECO101B)** da **Universidade Federal de Itajubá (UNIFEI)**.

O projeto foi totalmente implementado utilizando a plataforma **MakeCode Arcade** em TypeScript, aplicando conceitos estruturados de desenvolvimento de software e programação concorrente não-bloqueante para lidar com a alta densidade de elementos gráficos e projéteis simultâneos.

---

## 📖 História do Jogo

Após os 5 anos mais sombrios de sua história, após incontáveis desafios, longas e excruciantes horas de sofrimento, você finalmente tem seu tão ansiado **DIPLOMA DE ENSINO SUPERIOR**.

*“Nada pode me parar!!!”* — Diz você.

Até que você se lembra do seu **EMPRÉSTIMO ESTUDANTIL**. Foram 5 anos sem preocupação, mas agora seu pior pesadelo se tornou realidade: os juros transformaram um simples empréstimo em uma fortuna que ninguém no mundo poderia pagar.

No bar, afundando as mágoas com seu ex-colega que já fundou uma empresa e é CEO, vocês conversam:
* *"É impossível! Simplesmente Impossível!"* — Você diz.
* *"Nem eu tenho todo esse dinheiro. Talvez só um dragão daquelas histórias de criança tem dinheiro nesse nível em seu ninho"* — Falou seu amigo.

Enquanto seu amigo ria da piada, sua cabeça já cheia de problemas forma uma ideia genial. *“O que tenho a perder?”* — Pensa. Então, com uma ideia na cabeça e equipamento roubado, você parte para o suposto ninho do dragão para enfrentar perigos e Slimes até chegar ao grande tesouro que limpará seu nome de vez!

---

## 🎮 Mecânicas e Arquitetura Técnica

O motor lógico do jogo foi projetado cirurgicamente para respeitar as limitações de concorrência do MakeCode Arcade, utilizando:
* **Máquina de Estados de IA:** Padrões dinâmicos e imprevisíveis para os ataques de cada chefe.
* **Lógica Não-Bloqueante:** Uso estrito de timers paralelos (`setTimeout` e `runInParallel`) em vez de laços de espera bloqueantes, garantindo que a taxa de quadros (FPS) se mantenha estável mesmo com dezenas de projéteis na tela.
* **Processamento de Imagens Dinâmico:** Algoritmos customizados de varredura de pixels para gerar contornos e transparências em tempo de execução (`outlineAndTransparent`).

---

## 👥 Equipe e Créditos

* **Trabalho de Introdução à Engenharia da Computação – ECO101B**
* **Integrante mais Importante:** Ícaro Victor Ferreira
* **Integrante mais Criativo:** Marcos Vinícius Santos de Carvalho Macedo
* **Integrante mais Bonito:** Thiago Mendes Ramos
* **Luiz Guilherme:** Contrucci Vinhais

**THE GREEDY DRAGON**

---

## 🚀 Como Executar

1. Copie o link deste repositório.
2. Acesse o [MakeCode Arcade](https://arcade.makecode.com/).
3. Clique em **Import** (Importar) e selecione **Import URL**.
4. Cole o link para rodar ou modificar o projeto diretamente no simulador!
