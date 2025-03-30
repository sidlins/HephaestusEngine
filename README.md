# HephaestusEngine

HephaestusEngine é um framework modular voltado à análise estrutural com o **Método dos Elementos Finitos - MEF**. Desenvolvido para ensino, pesquisa e prototipagem, permite explorar, testar e modificar formulações numéricas sem depender de softwares comerciais fechados. Integra malhas de elementos finitos e utiliza solvers de bibliotecas Python, como NumPy e SciPy, sendo totalmente customizável para facilitar a validação e o desenvolvimento de novas abordagens computacionais.

Atualmente, o projeto está em construção, mas já conta com um módulo funcional e testável: o **3DTrussSolver**, voltado para a análise de treliças espaciais utilizando MEF e modelagem em grafos.

## 📌 Objetivos do Projeto

- Criar uma base open-source interpretável e didática para aplicações em MEF.
- Integrar com malhas geradas por softwares comerciais como Abaqus, GiD, Ansys e outros.
- Permitir que usuários modifiquem e implementem novas formulações numéricas.
- Fomentar o desenvolvimento científico e educacional em mecânica computacional.

## 🚧 Subprojetos do HephaestusEngine

- `3DTrussSolver` – Solver de treliças espaciais via MEF com modelagem em grafos (**em fase de validação**)
- `PAPPUSStructural` – Solver estrutural para problemas 2D/3D com suporte a importação de malhas (em desenvolvimento)
- `PAPUSThermal` – Solver para condução térmica estacionária com suporte a malhas comerciais (proposto)
- `Framework para Análise Estrutural` – Base computacional e conceitual para estudo e prototipagem de MEF

## ✅ Status Atual

- O módulo `3DTrussSolver` está finalizado e em fase de validação.
- A validação está sendo feita com exemplos de livros e artigos científicos.
- Os demais subprojetos estão em fase inicial de desenvolvimento e concepção.

## 📚 Tecnologias

- Python 3.x
- NumPy
- Matplotlib
- Estrutura modular orientada a objetos

## 🧪 Como Usar o 3DTrussSolver

> Em breve será disponibilizado um guia de instalação e exemplos de uso. Por enquanto, o uso está limitado ao ambiente de desenvolvimento local e exemplos específicos de teste.

## 📄 Licença

Este projeto será distribuído sob uma licença open-source (a ser definida em breve).

---

Desenvolvido por pesquisadores do grupo **IMACS – Identificação, Modelagem, Automação e Controle de Sistemas** da **Universidade Federal do Amazonas (UFAM)**.
