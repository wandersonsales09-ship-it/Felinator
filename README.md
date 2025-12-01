# 🐾 Felinator — Simulador de Genética Felina

O **Felinator** é um simulador educacional de genética de felinos criado para auxiliar
professores e estudantes no aprendizado de cruzamentos, probabilidades e herança
de fenótipos de pelagem.  
É totalmente interativo, lúdico e funciona direto no navegador.

## 🎮 Modos de Jogo

### 👨‍🎓 Modo Aluno
- O aluno escolhe dois fenótipos parentais.
- Recebe **quatro alternativas (A, B, C, D)** para o filhote.
- O sistema usa **probabilidades reais** para determinar o resultado.
- Feedback imediato com:
  - **"Muito bem!" / "Excelente!"** para acertos  
  - **"Não foi dessa vez." / "Quase lá."** com explicação para erros
- Conta acertos e mostra desempenho a cada sessão.

---

### 👩‍🏫 Modo Professor
Acesso restrito por e-mail (institucional ou pessoal) + código.

Inclui **painel didático completo**, com:

#### 🧮 Quadrado de Punnett Interativo
- Cruzamentos monohíbridos (AA, Aa, aa)
- Atualização automática dos genótipos
- Porcentagens e resumo automático

#### 📚 Painel de Conceitos
- Gene, alelo, dominância, recessividade…
- Explicações claras e prontas para aula

#### 📋 Tutoriais Interativos
- Passo a passo guiado de aula
- Cada etapa pode ser aberta/fechada

#### 📊 Gráficos (Canvas)
- Representação visual de proporções dominante/recessivo

#### 📝 Sistema de Exercícios
- Perguntas conceituais
- Botão “Mostrar resposta”

#### 🎲 Simulação Populacional
- Populações de 10 a 1000 filhotes
- Frequência do fenótipo gerada por Monte Carlo
- Discussão de flutuação x teoria

---

## 🧬 Probabilidade realista de fenótipos

O Felinator utiliza um sistema probabilístico **PROB_DISTR**, que considera:

- Dominância
- Manchas brancas (gene S)
- Tricolor (ligado ao X)
- Padrões Tabby
- Point
- Alto branco (Arlequim e Van)

Cada cruzamento retorna um fenótipo **baseado em probabilidade**, não só regra fixa.

---

## 🚀 Como executar
Basta abrir o arquivo **index.html** em qualquer navegador moderno.

Ou acessar a versão hospedada via GitHub Pages (link aparece aqui quando publicado).

---

## 📁 Estrutura do projeto
