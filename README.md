# 📚 Calculadora de Notas - Medicina

Uma aplicação em HTML, CSS e JavaScript para acompanhar o desempenho acadêmico em Medicina, simulando notas do 2º bimestre, médias finais e necessidades de recuperação.

## ✨ Funcionalidades

- ✅ Acompanhamento das disciplinas do período.
- ✅ Simulação das notas do 2º bimestre.
- ✅ Cálculo automático da média semestral.
- ✅ Cálculo da nota necessária para aprovação direta.
- ✅ Simulação da recuperação.
- ✅ Identificação automática do status:
  - Aprovado
  - Recuperação
  - Reprovado
- ✅ Disciplinas com separação entre eixo teórico e prático.
- ✅ Regra especial para Semiologia (70% prova teórica + 30% VHAB).
- ✅ Salvamento automático dos dados utilizando LocalStorage.
- ✅ Interface responsiva para computador e celular.

---

# 📖 Regras de Aprovação

## Aprovação Direta

A média mínima para aprovação é:

```
7,0 (70%)
```

Cálculo:

```
Média = (1º Bimestre + 2º Bimestre) ÷ 2
```

---

## Recuperação

Caso a média fique abaixo de 7,0:

```
(Média do eixo + Recuperação) ÷ 2 ≥ 6,0
```

Portanto:

```
Nota da Recuperação = 12 - Média do eixo
```

---

# 📚 Disciplinas

## Disciplinas exclusivamente teóricas

- Atenção Primária em Saúde I
- Biologia Celular
- Bioquímica
- Embriologia I
- Fisiologia I
- Projeto de Intervenção na Comunidade I

## Disciplinas com eixo teórico e prático

- Anatomia I
- Histologia I
- Semiologia I

---

# 🔬 Regra Especial de Semiologia

A nota do eixo teórico é composta por:

```
70% Prova Teórica
30% VHAB
```

Cálculo:

```
Nota Teórica = (Prova × 0,7) + (VHAB × 0,3)
```

---

# 💾 Persistência dos Dados

Os dados são armazenados automaticamente no navegador através do:

```javascript
localStorage
```

Chave utilizada:

```javascript
med_subjects_v6
```

Assim, as notas permanecem salvas mesmo após fechar a página.

---

# 🛠 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- LocalStorage

---

# 📱 Interface

A aplicação possui:

- Design responsivo;
- Cards individuais por disciplina;
- Indicadores coloridos de status;
- Simulação em tempo real;
- Separação entre teoria e prática;
- Média geral automática.

---

# 📂 Estrutura do Projeto

```
/
│
├── index.html
└── README.md
```

---

# 🚀 Como utilizar

1. Abra o arquivo:

```text
index.html
```

2. Digite suas notas do 1º bimestre.

3. Simule as notas do 2º bimestre.

4. Visualize automaticamente:

- Média do eixo;
- Nota necessária no 2º bimestre;
- Nota necessária na recuperação;
- Situação final da disciplina.

---

# 👨‍⚕️ Desenvolvedor

**Rafael Machado ∴**

Projeto desenvolvido para acompanhamento acadêmico de estudantes de Medicina.
