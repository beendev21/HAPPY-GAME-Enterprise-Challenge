🎮 HAPPY-GAME-Enterprise-Challenge
Projeto desenvolvido para a Atividade 3 - Enterprise Challenge FIAP.

📌 Sobre o Projeto
Este repositório contém o OpenHorizon, um dashboard interativo que permite simular cenários de crescimento de usuários, receita e custos em um modelo de negócio digital.
A aplicação foi criada para auxiliar na análise de viabilidade financeira do projeto HAPPY GAME, permitindo avaliar ROI, payback e projeções mensais de forma visual e dinâmica.

⚙️ Funcionalidades
🔢 Modelagem Matemática: projeções baseadas em crescimento exponencial.
📈 Gráficos Dinâmicos (Chart.js): escolha entre visualizar usuários, receita ou custos ao longo do tempo.

🎛️ Simulador Interativo: ajuste parâmetros como:
Usuários iniciais (N₀)
Taxa de crescimento (%)
Receita média por usuário (ARPU)
Período de projeção (meses)

💰 Análise Financeira: cálculo de custos, lucro, ROI e payback estimado.
📊 Tabela Detalhada: acompanhamento mês a mês das projeções.
🌙 Design Futurista e Responsivo com TailwindCSS.

🧮 Fórmula Utilizada
O crescimento é modelado pela equação:
𝑁
(
𝑡
)
=
𝑁
0
×
𝑒
(
𝑟
×
𝑡
)
N(t)=N
0
	​

×e
(r×t)

Onde:
N(t) = valor projetado no tempo t (usuários, receita etc.)
N₀ = valor inicial
r = taxa de crescimento por período
t = tempo decorrido (meses)

🚀 Tecnologias
HTML5 / CSS3 (TailwindCSS)
JavaScript (ES6+)
Chart.js para visualização gráfica
Math.js para cálculos matemáticos

📂 Estrutura
index.html → dashboard principal
imagens/ → ícones e logo utilizados

👥 Equipe
Projeto desenvolvido por mim Breno da FIAP para o Enterprise Challenge.
