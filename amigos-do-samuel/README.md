# AMIGOS DO SAMUEL — Bíblia de Marca e Personagens

Documento de referência permanente da série. Todo roteiro de episódio (pasta `video-0XX-*/roteiro.md`) deve importar estas regras por referência, não copiá-las — evita divergência entre episódios.

Campanha: **Samuel Enfermeiro — 4001 — Deputado Federal**

---

## 1. Identidade visual oficial

| Elemento | Valor |
|---|---|
| Azul Samuel | `#0B2D6B` |
| Amarelo campanha | `#F7B603` |
| Branco | `#FFFFFF` |
| Laranja de apoio | `#F7941D` |
| Azul profundo | `#061B4F` |
| Proporção | 70% azul/amarelo · 20% branco · 10% laranja |

Não introduzir vermelho, verde/roxo como cor de identidade, degradês multicoloridos ou neon na assinatura, tipografia, grafismos e interfaces. **Roupas individuais dos personagens mantêm suas cores próprias aprovadas** (ex.: verde do André, roxo da Valentina) — a restrição de paleta vale para a identidade da campanha, não para o guarda-roupa.

**Logo 4001**: ativo protegido, arquivo oficial fornecido. Nunca redesenhar, redigitar, deformar ou recriar por IA. Amarelo com contorno azul. Assinatura eleitoral padrão:
```
4001
DEPUTADO FEDERAL
SAMUEL ENFERMEIRO
```

## 2. Personagens — status de referência

CHARACTER_ID fixo por personagem. Nunca alterar durante o projeto. Manter seed/reference image/style reference em toda ferramenta que suportar.

| CHARACTER_ID | Personagem | Referência visual | Status |
|---|---|---|---|
| `CHAR_SAMUEL_OFFICIAL_v01` | Samuel | `personagens/samuel-oficial.png` (fotografia real aprovada) | ✅ Aprovada |
| `CHAR_RAFAEL_v01` | Rafael | `personagens/rafael-ref.png` | ✅ Aprovada |
| `CHAR_ANDRE_v01` | André | `personagens/andre-ref.png` | ✅ Aprovada |
| `CHAR_VALENTINA_v01` | Valentina | `personagens/valentina-ref.png` (close-up) + `personagens/valentina-ref-corpo.png` (corpo inteiro) | ✅ Aprovada |
| `CHAR_THEO_v01` | Theo | `personagens/theo-ref.png` | ✅ Aprovada |
| `CHAR_LUCIA_v01` | Dona Lúcia | `personagens/lucia-ref.jpg` (close-up) + `personagens/lucia-ref-corpo.png` (corpo inteiro) | ✅ Aprovada |
| `CHAR_LUCAS_v01` | Lucas | `personagens/lucas-ref.png` (close-up) + `personagens/lucas-ref-corpo.png` (corpo inteiro) | ✅ Aprovada |
| `CHAR_MARIANA_v01` | Mariana | `personagens/mariana-ref.png` (close-up) + `personagens/mariana-ref-corpo.png` (corpo inteiro) | ✅ Aprovada |

> **GUARDIAN — nota de auditoria permanente:** Elenco completo — os 8 personagens (Samuel, Rafael, André, Valentina, Theo, Dona Lúcia, Lucas, Mariana) têm character reference aprovada com CHARACTER_ID fixo. Nenhum take do Vídeo 001 permanece `PENDENTE DE VERIFICAÇÃO` por falta de referência visual.

### Samuel — ativo protegido
Elo entre todos os personagens. Representa cuidado, escuta, experiência, representação, saúde, liderança pública. Personalidade: humano, próximo, seguro, acolhedor, positivo, não teatral. Preservar rosto, cabelo, sorriso, tom de pele, idade aparente, proporção facial. Pode melhorar iluminação/nitidez/animação/integração de cenário — nunca substituir identidade.

### Lucas — `personagens/lucas-ref.png` + `personagens/lucas-ref-corpo.png`
Jovem. Representa juventude, educação, oportunidades, primeiro emprego, futuro. Visual: cabelo castanho volumoso e ondulado, moletom verde-petróleo com cordão bege, mochila preta, calça jeans, tênis preto e branco, estética urbana jovem. Sorriso confiante e leve. Personalidade: curioso, inteligente, otimista, questionador.

### Dona Lúcia — `personagens/lucia-ref.jpg` + `personagens/lucia-ref-corpo.png`
Pessoa idosa. Representa idosos, saúde, respeito, dignidade, envelhecimento com qualidade. Visual: cabelos grisalhos cacheados curtos, óculos de armação marrom, brincos e colar dourados discretos, cardigã bege sobre blusa creme, calça marrom, mocassim marrom. Sorriso largo e expressivo. Personalidade: carinhosa, sábia, bem-humorada, direta, afetiva.

### Mariana — `personagens/mariana-ref.png` + `personagens/mariana-ref-corpo.png`
Mãe do Theo. Representa famílias, maternidade, acolhimento, mães atípicas, rotina de cuidado. Visual: mulher adulta, cabelos longos castanho-escuros ondulados, camiseta verde-oliva gola V, calça jeans, sapatilha bege. Sorriso caloroso. Personalidade: forte, acolhedora, determinada, realista.

### Theo — `personagens/theo-ref.png`
Criança. Representa infância, autismo, inclusão, acolhimento. Visual: menino, cabelo cacheado, camiseta azul (estampa de peças de quebra-cabeça colorida). Autismo tratado com respeito: sem comportamento estereotipado, sem infantilização além da idade, sem uso do autismo como recurso dramático.

### Valentina — `personagens/valentina-ref.png`
Representa respeito, dignidade, inclusão, direito de existir e participar da sociedade. Visual: cabelos longos, blazer roxo/lilás, visual elegante. Personalidade: segura, carismática, elegante, assertiva.

### André — `personagens/andre-ref.png`
Pessoa com deficiência. Representa PCD, acessibilidade, autonomia, mobilidade, direitos. Visual: homem negro, camiseta verde, cadeira de rodas. A cadeira é parte da continuidade física — nunca some, muda de modelo ou é usada incorretamente. Personalidade: confiante, independente, bem-humorado, direto.

### Rafael — `personagens/rafael-ref.png`
Profissional de saúde. Representa enfermagem, profissionais da saúde, plantões, valorização de quem cuida. Visual: homem adulto, scrubs azul. Personalidade: profissional, companheiro, acolhedor, realista.

## 3. Tratamento da série

Cinematográfico, emocional, humano, moderno, popular, profissional, acolhedor, brasileiro, social, crível — **animação 3D premium + documentário humano + campanha contemporânea**. Nunca cartoon pastel, movimentos caricatos, saltos, danças, comédia involuntária. Sem emojis, stickers, ícones decorativos; palavras-conceito (CUIDAR, INCLUIR, TRANSFORMAR) só como tipografia, nunca com desenho.

## 4. Negative prompt global (aplicar em todo take)

```
no unwanted text, no logos generated by AI, no fake campaign logos, no random symbols,
no emojis, no stickers, no extra fingers, no deformed hands, no duplicated limbs,
no facial identity drift, no wardrobe changes, no age changes, no skin tone changes,
no hairstyle changes, no wheelchair deformation, no disappearing wheelchair,
no floating objects, no unnatural blinking, no exaggerated cartoon movement,
no childish acting, no plastic skin, no uncanny face, no extreme depth distortion,
no fisheye, no random background people looking at camera, no watermark,
no distorted typography
```

## 5. Regras jurídico/políticas (todos os episódios)

- Nunca inventar números, leis ou dados.
- Diferenciar sempre: pode propor / pode fiscalizar / pode destinar recursos / pode representar.
- Nunca afirmar vigência plena de uma lei quando houver ressalva jurídica.
- Dúvida factual → marcar `PENDENTE DE VERIFICAÇÃO`, nunca preencher com estimativa.

## 6. Episódios da série

| Episódio | Personagem | Tema |
|---|---|---|
| 001 | Todos (apresentação) | Abertura da série |
| 002 | Lucas | Juventude e primeiro emprego |
| 003 | Dona Lúcia | Saúde e dignidade na terceira idade |
| 004 | Mariana + Theo | Autismo, famílias e inclusão |
| 005 | André | Acessibilidade e autonomia |
| 006 | Valentina | Respeito e dignidade |
| 007 | Rafael | Valorização dos profissionais da saúde |

Cada episódio a partir do 002 deve fechar o arco: **história humana → problema → papel da política → o que um deputado federal pode fazer → continuação da série**.
