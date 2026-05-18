<div align="center">

# Fundamentos de Aprendizado de Máquina Científico para Mecânica dos Fluidos

**Curso completo · gratuito · em português**

[![Licença: CC BY 4.0](https://img.shields.io/badge/Licen%C3%A7a-CC%20BY%204.0-4fc3f7.svg)](https://creativecommons.org/licenses/by/4.0/deed.pt)
[![YouTube](https://img.shields.io/badge/YouTube-NeuroFluidos-e53935.svg)](https://www.youtube.com/@neurofluidos)
[![Material](https://img.shields.io/badge/Material-PDF%20%2B%20LaTeX-2d6a4f.svg)](#estrutura-do-reposit%C3%B3rio)

*Redes neurais encontram mecânica dos fluidos.*

</div>

---

## Sobre o curso

Este repositório reúne todo o material didático do curso **Fundamentos de Aprendizado de Máquina Científico para Mecânica dos Fluidos**, desenvolvido no âmbito do projeto PIBIC-FAPDF/IFB 2026–2027.

O curso aborda a fronteira entre o aprendizado de máquina e a mecânica dos fluidos computacional: como usar redes neurais, decomposições de dados e regressão esparsa para resolver equações diferenciais, descobrir leis físicas a partir de dados e construir modelos de escoamento.

Todo o conteúdo é **gratuito**, em **português**, e calibrado para estudantes de **graduação** em engenharia, física e matemática.

## Conteúdo programático

O curso tem **36 aulas** de 1h40 (≈60 horas), organizadas em 7 módulos:

| Módulo | Tema | Aulas |
|--------|------|:-----:|
| 1 | Fundamentos matemáticos e decomposições (SVD, PCA, POD) | 1–8 |
| 2 | Regressão, EDPs e DMD | 9–14 |
| 3 | Redes neurais artificiais | 15–20 |
| 4 | **PINNs: fundamentos** | 21–26 |
| 5 | **PINNs: aplicações** | 27–32 |
| 6 | SINDy e tópicos avançados | 33–35 |
| 7 | Workshop de consolidação | 36 |

Os tópicos centrais incluem:

- **SVD, PCA e POD** — decomposições para análise de dados de escoamento
- **DMD** — Dynamic Mode Decomposition e operador de Koopman
- **Redes neurais** — do perceptron ao backpropagation e otimizadores modernos
- **PINNs** — redes neurais informadas pela física para problemas diretos e inversos
- **SINDy** — descoberta de equações governantes a partir de dados
- **Neural Operators** — DeepONet, FNO e modelos substitutos

## Estrutura do repositório

```
.
├── planejamento/
│   └── planejamento_curso.pdf      # Ementa completa: 36 aulas, 7 módulos
├── aulas/
│   ├── aula01_aluno.pdf            # Panorama: IA e mecânica dos fluidos
│   ├── aula02_aluno.pdf            # Revisão de álgebra linear I
│   ├── aula03_aluno.pdf            # Revisão de álgebra linear II
│   ├── aula04_aluno.pdf            # SVD: definição e interpretação
│   ├── aula05_aluno.pdf            # SVD: truncamento e Eckart-Young
│   └── ...                         # (demais aulas em produção)
├── tutoriais/                      # Notebooks Python (em construção)
├── LICENSE
└── README.md
```

## Como usar este material

**Para estudo individual:** comece pelo `planejamento_curso.pdf` para ter a visão geral, depois siga as aulas em ordem. Cada nota de aula é autocontida e inclui exercícios propostos com gradação de dificuldade.

**Para acompanhar as videoaulas:** cada PDF corresponde a um vídeo no canal [NeuroFluidos](https://www.youtube.com/@neurofluidos). Recomenda-se ler a "leitura preparatória" indicada antes de assistir.

**Pré-requisitos:** álgebra linear básica, cálculo diferencial e integral, EDOs e programação introdutória em Python. Os conceitos avançados são construídos gradualmente ao longo do curso.

## Bibliografia principal

O curso é estruturado em torno de referências de acesso aberto sempre que possível. Os textos-base são:

- **Brunton & Kutz (2022)** — *Data-Driven Science and Engineering* ([PDF gratuito](https://databookuw.com/databookV2.pdf))
- **Goodfellow, Bengio & Courville (2016)** — *Deep Learning* ([online gratuito](https://www.deeplearningbook.org))
- **Strang (2019)** — *Linear Algebra and Learning from Data*

A lista completa de 11 referências está no documento de planejamento.

## Ferramentas

Todo o software utilizado é gratuito e de código aberto:

- **Python** + NumPy, SciPy, Matplotlib
- **PyTorch** — redes neurais e diferenciação automática
- **DeepXDE** — biblioteca de alto nível para PINNs
- **PySINDy** — descoberta de equações
- **Google Colab** — ambiente de execução com GPU gratuita

## Licença

O material didático (notas de aula, slides, PDFs, textos) está licenciado sob **[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.pt)**.

Você pode compartilhar e adaptar livremente, inclusive para fins comerciais, desde que atribua o crédito apropriado. Eventuais códigos-fonte são licenciados sob MIT. Veja o arquivo [LICENSE](LICENSE) para detalhes.

## Como citar

Se este material foi útil para você, cite-o como:

```
ABDO, R. F. Fundamentos de Aprendizado de Máquina Científico para
Mecânica dos Fluidos. Instituto Federal de Brasília, 2026.
Disponível em: https://github.com/neurofluidos
```

## Contato

Canal no YouTube: [**@neurofluidos**](https://www.youtube.com/@neurofluidos)

---

<div align="center">
<sub>Material desenvolvido no âmbito do projeto PIBIC-FAPDF/IFB 2026–2027.</sub>
</div>
