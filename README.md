# ortopedia.daniellecruz
Pôster interativo de revisão para provas de ortopedia e TEOT, desenvolvido no estilo Atlas Mental Interativo com identidade visual cinematográfica. O material cobre o tema de lesões meniscais pediátricas com foco em:  cicatrização no paciente pediátrico  cirúrgica preferencial (sutura vs. meniscectomia) Diagnóstico clínico e por imagem Algoritmo 
# 🦴 Lesões Meniscais Pediátricas
### Infográfico Médico Cinematográfico · TEOT · Ortopedia Pediátrica

---

## 📋 Descrição

Pôster interativo de revisão para provas de ortopedia e TEOT, desenvolvido no estilo
**Atlas Mental Interativo** com identidade visual cinematográfica. O material cobre
o tema de lesões meniscais pediátricas com foco em:

- Potencial de cicatrização no paciente pediátrico
- Conduta cirúrgica preferencial (sutura vs. meniscectomia)
- Diagnóstico clínico e por imagem
- Algoritmo de decisão visual
- Pegadinhas de prova compiladas

> *"O menisco infantil é um tesouro vascular: preservar hoje é evitar artrose amanhã."*

---

## 👩‍⚕️ Autoria

**Dra. Danniele Cruz**
Ortopedista

---

## 🎯 Objetivo Pedagógico

Material de revisão rápida projetado para ser **absorvido em 30 segundos**, com
hierarquia visual que guia o olhar do título → conceito-chave → algoritmo → resumo.
Segue os princípios do **Método Rossanno de Memorização Médica (N1–N7)**:

| Nível | Técnica Aplicada |
|-------|-----------------|
| N1 | Ancoragem semântica via frase de impacto |
| N2 | Dual coding: SVG do menisco + texto estruturado |
| N4 | Pegadinhas de prova com feedback implícito |
| N5 | Interleaving: diferencial (sutura vs. meniscectomia) |
| N6 | Framing villain/hero (OA precoce como vilão) |

---

## 📁 Arquivo

```
lesoes-meniscais-pediatricas.html
```

- Arquivo único, autocontido
- Sem dependências externas de imagens
- Fontes via Google Fonts (requer conexão na 1ª abertura)
- SVGs gerados inline com CSS/HTML

---

## 🏗️ Estrutura do Conteúdo

```
HERO
├── Título principal
├── SVG: Menisco meia-lua com zona vascular/avascular
└── Frase de impacto

BLOCO 01 · Potencial de Cura
├── Barra visual de vascularização (≤10 anos = 100%)
├── Comparação criança vs. adulto
└── Pegadinha: criança ≠ adulto pequeno

BLOCO 02 · Maior Cicatrização
├── Taxa 50–90% (lesões longitudinais periféricas)
├── Explicação da zona vascular periférica
├── Algoritmo: Lesão → Zona → Sutura
└── Pegadinha: periferia = zona de ouro

BLOCO 03 · O Que Evitar
├── SVG: Joelho com osteoartrose (osteófitos simbólicos)
├── Meniscectomia como último recurso
└── Armadilha clínica: meniscectomia sem esgotar sutura

BLOCO 04 · Teste Clínico
├── McMurray Modificado Pediátrico
├── 40° de flexão (diferença do adulto)
├── Mnemônico: "McMurray dobra o joelho aos 40 graus"
└── Pegadinha: 40° ≠ McMurray clássico do adulto

BLOCO 05 · Exame de Imagem
├── RNM: exame de escolha ★
├── Radiografia: complementar (excluir diferenciais)
└── Pegadinha: RNM ≠ Rx como exame principal

REGRA DE OURO
└── Algoritmo visual: Criança → Menisco Vasc. → Preservar → Sutura → Evitar Meniscectomia → Evitar OA

PEGADINHAS COMPILADAS (4 cards)

RESUMO RÁPIDO (6 itens em grid)

FOOTER
└── Assinatura Dra. Danniele Cruz
```

---

## 🎨 Identidade Visual

| Elemento | Especificação |
|----------|--------------|
| Fundo | `#07090F` — preto profundo cinematográfico |
| Dourado | `#C9A84C` / `#F0D080` — destaque e títulos |
| Vermelho | `#B22222` / `#E63030` — perigo, zona vascular, OA |
| Verde | `#22C870` — proteção, preservação, sutura |
| Teal | `#1AB8A0` — decisões, imagem, testes |
| Display | Bebas Neue (títulos) |
| Corpo | Nunito (texto) |
| Mono | IBM Plex Mono (kickers, badges, dados) |
| Assinatura | Dancing Script |

---

## ⚡ Conteúdo Clínico — Referência Rápida

| Dado | Valor |
|------|-------|
| Vascularização em ≤10 anos | 100% |
| Taxa de cicatrização (periférica longitudinal) | 50–90% |
| Tipo de lesão com maior potencial | Longitudinal periférica |
| Conduta preferencial | Sutura meniscal |
| Meniscectomia | Último recurso absoluto |
| Consequência da meniscectomia precoce | Osteoartrose precoce |
| Teste clínico | McMurray Modificado (40°) |
| Exame de escolha | RNM |
| Radiografia | Complementar (excluir diferenciais + lesões ósseas) |

---

## 🚀 Como Usar

1. Abrir `lesoes-meniscais-pediatricas.html` em qualquer navegador moderno
2. Requer conexão com internet apenas para carregar as fontes (Google Fonts)
3. Responsivo para desktop e mobile
4. Pode ser impresso via `Ctrl+P` → "Salvar como PDF" para versão estática

---

## 📌 Observações Técnicas

- **Sem bibliotecas externas** — puro HTML5 + CSS3 + SVG inline
- **Sem JavaScript** — todo comportamento via CSS (hover, animações)
- **Responsivo** — grid colapsa para 1 coluna em telas < 768px
- **Shimmer animado** nas barras de vascularização (CSS `@keyframes`)
- **Grain overlay** fixo via SVG `feTurbulence` para textura cinematográfica
- **Vignette** radial para profundidade de pôster de cinema

---

*TEOT · Ortopedia Pediátrica · Material Educacional*
