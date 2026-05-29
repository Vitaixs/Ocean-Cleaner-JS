# 🌊 Ocean Cleaner - A Ocean Rogue-like

Um jogo arcade 2D desenvolvido em HTML5 Canvas e JavaScript puro. O jogador assume o papel de um mergulhador que explora as profundezas do oceano para coletar lixo marinho, evitar criaturas perigosas como tubarões e águas-vivas, e gerenciar seus recursos para comprar melhorias tecnológicas.

## 🚀 Funcionalidades do Jogo

* **Mecânica de Mergulho:** Controle o oxigênio e a capacidade do seu inventário enquanto desce a profundidades extremas.
* **Sistema de Ecossistema:** Peixes pacíficos dividem o espaço com águas-vivas estáticas e tubarões predadores que perseguem o jogador se ele se aproximar demais.
* **Loja de Upgrades Progressiva:** Economia baseada em pontuação e moedas para melhorar seus atributos:
    * **Pé de Pato (Boost):** Aumenta a velocidade de locomoção.
    * **Tanque de Oxigênio:** Permite passar mais tempo submerso.
    * **Inventário:** Aumenta a capacidade de carga para coletar mais lixo antes de voltar ao barco.
    * **Resistência (Vida):** Adiciona corações extras para aguentar ataques.
    * **Arpão Perfurante:** Permite se defender de tubarões, causando dano progressivo a cada upgrade.
* **Mudança de Bioma:** Ao comprar o upgrade do Barco Quebra-Gelo, o jogador reseta seus atributos básicos e desbloqueia um novo bioma ártico com blocos de gelo que servem como obstáculos colidíveis.

## 🎮 Como Jogar

### Controles
* **Teclas W, A, S, D:** Movimentam o mergulhador pelo oceano.
* **Barra de Espaço:** Ativa o *Boost* de velocidade (requer upgrade de Pé de Pato).
* **Movimento do Mouse:** Mira a direção do arpão.
* **Clique do Mouse:** Dispara o arpão para coletar lixo/peixes ou atacar tubarões.

### Objetivo
Desça para coletar os lixos. Quando o inventário estiver cheio, retorne à superfície e encoste no barco para descarregar o lixo. Cuidado com o oxigênio e com a vida! Se zerarem, é Fim de Jogo.

## 🛠️ Tecnologias Utilizadas

* **HTML5** (Estrutura e Canvas para renderização gráfica)
* **CSS3** (Estilização dos menus de interface, Game Over e Loja)
* **JavaScript (ES6+)** (Lógica do jogo, física de colisão, inteligência artificial simples dos inimigos e loop de renderização a 60 FPS estáveis)

## 📦 Como Executar o Projeto

Não há necessidade de instalar dependências complexas. Como o jogo foi feito em JavaScript puro, você só precisa de um navegador web.

