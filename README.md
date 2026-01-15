# 🩺 Calculadora MELD 3.0

Calculadora clínica do **MELD 3.0 (Model for End-Stage Liver Disease)** desenvolvida em **HTML, CSS e JavaScript**, baseada na fórmula oficial utilizada para avaliação de gravidade da doença hepática em pacientes adultos.

O projeto foi criado com foco em **simplicidade, acessibilidade e fidelidade clínica**, podendo ser utilizado como **ferramenta de apoio educacional e clínico**.

---

## 📌 O que é o MELD 3.0

O **MELD 3.0** é uma atualização do escore MELD, incorporando:
- Sexo biológico
- Albumina sérica
- Ajustes refinados de sódio
- Melhor estratificação de risco

É amplamente utilizado em contextos de **transplante hepático** e avaliação de prognóstico em hepatologia.

---

## 🧮 Fórmula utilizada

A calculadora implementa exatamente a seguinte equação:
MELD 3.0 =
1,33 × (Feminino) +
4,56 × ln(Bilirrubina) +
0,82 × (137 − Sódio) −
0,24 × (137 − Sódio) × ln(Bilirrubina) +
9,09 × ln(INR) +
11,14 × ln(Creatinina) +
1,85 × (3,5 − Albumina) −
1,83 × (3,5 − Albumina) × ln(Creatinina) + 6

---

## ⚙️ Regras clínicas aplicadas

- Bilirrubina, INR e creatinina **< 1,0 → assumem 1,0**
- Creatinina **> 3,0 → fixada em 3,0**
- Creatinina = **3,0** se:
  - ≥ 2 sessões de diálise nos últimos 7 dias  
  - Hemodiálise venovenosa contínua (CVVHD)
- Sódio limitado entre **125 e 137 mEq/L**
- Albumina limitada entre **1,5 e 3,5 g/dL**
- Resultado final **arredondado para o inteiro mais próximo**
- Sexo feminino recebe peso adicional conforme fórmula

---

## 🖥️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- Google Fonts (Preston)

Sem dependências externas ou frameworks.

---

---

## ⚠️ Aviso importante (Disclaimer)

> **Esta calculadora é destinada exclusivamente para fins educacionais e de apoio clínico.**  
>  
> Ela **não substitui avaliação médica**, julgamento clínico ou protocolos institucionais.  
>  
> A decisão terapêutica final deve sempre ser tomada por um **profissional de saúde habilitado**, com base na avaliação completa do paciente.

---

## 👨‍💻 Autores

- Franklin R.
- Patrick R.

---

## 📜 Licença

Este projeto é disponibilizado sob licença **MIT**, permitindo uso, modificação e distribuição, desde que mantidos os créditos aos autores.

---

## 🤝 Contribuições

Sugestões, correções e melhorias são bem-vindas.  
Sinta-se à vontade para abrir uma **Issue** ou enviar um **Pull Request**.

---

