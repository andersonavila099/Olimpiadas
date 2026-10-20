# 🏅 Projeto Olimpíadas — Análise de Clean Code
> Trabalho da disciplina de **Engenharia de Software II** (UniSenac)

* **Autor:** Anderson Tavares Avila

---

## 📋 Resumo da Análise

### 1. Visão Geral do Projeto
O sistema **Olimpíadas** gerencia o quadro de medalhas, atletas e pontuações de delegações em eventos esportivos.

### 2. Pontos de Melhoria (Código Sujo / Refatoração)
* **Nomenclatura ruim:** Variáveis genéricas (`p`, `o`, `pr`, `b`) foram substituídas por nomes descritivos (`medalhasOuro`, `nomePais`).
* **Números Mágicos:** Os pesos das medalhas (`3`, `2`, `1`) foram isolados em constantes nomeadas (`PONTOS_OURO`, etc.).
* **Guard Clauses:** Remoção de blocos `else` desnecessários através de retornos antecipados.

### 3. Pontos de Destaque (Código Limpo)
* Funções focadas em uma única responsabilidade (SRP), como a função de ordenação do quadro de medalhas seguindo o critério oficial olímpico.