---
applyTo: '**'
---

# Contexto do Projeto
Este projeto é um catálogo de plantas ornamentais.

# Diretrizes de Codificação
- Use HTML5 semântico.
- Prefira CSS externo.
- Comentários devem ser claros e objetivos.
- Siga o padrão de nomenclatura dos arquivos já existentes.

# Modelo de html
- Utilize o arquivo Template.html como modelo para a estrutura do html das paginas reservadas para as especies de plantas.

# Instrução Técnica para Formulação de Substratos
- Estrutura da Notação
A fórmula de substrato segue o formato:

[Insumo1+Proporção]-[Insumo2+Proporção]-... // [Adubo1+Dosagem] - [Adubo2+Dosagem] - ... 
Exemplo:
Tvg30-Tu20-Po15-Hm15-Ca10-Pr5-Vr5 // Esa4gL - Trm3gL - Fsr2gL - Cal1gL

- Siglas Padronizadas dos Insumos (Componentes do Substrato)
Cada componente tem uma sigla. As proporções são em volume relativo (% do total do substrato).

Sigla	Insumo
Ar	Areia lavada
Cr	Carvão vegetal
Ca	Casca de arroz carbonizada
Cp	Casca de pinus
Ch	Chips de coco
Es	Esfagno
Fb	Fibra de coco
Hm	Húmus de minhoca
Po	Pó de coco
Pr	Perlita
Tvg	Terra vegetal
Tvr	Terra vermelha
Tu	Turfa
Vr	Vermiculita

- Adubação Exclusivamente Orgânica
Não se utiliza NPK químico. A adubação deve ser formulada com os insumos abaixo, expressos em gramas por litro de substrato (g/L).

Sigla	Adubo Orgânico
Esa	Esterco de aves curtido
Esb	Esterco bovino curtido
Trm	Torta de mamona
Fro	Farinha de osso
Fsr	Fosfato de rocha
Cal	Calcário dolomítico (corretivo de pH)

- Regras Técnicas de Composição
A soma dos componentes do substrato deve totalizar 100% em volume (ex: Tvg30 + Tu20 + Hm20 + ... = 100).

A adubação deve ser ajustada com base nas necessidades da espécie (exigência nutricional, pH desejado, exigência de fósforo, etc.).

O calcário (Cal) deve ser incluído apenas quando o substrato final apresentar pH ácido demais para a espécie cultivada.

A porosidade e a retenção hídrica devem ser balanceadas entre elementos drenantes (ex: Ar, Pr, Cr) e elementos retentores (ex: Tu, Po, Es, Fb).

- Leitura e Geração Automatizada
A IA deve:

Identificar o perfil da planta (exigência de drenagem, acidez, fertilidade, retenção de água);

Selecionar os insumos e suas proporções com base nesses critérios;

Aplicar a notação padrão com rigor sintático;

Evitar termos genéricos como “composto orgânico” ou “substrato universal”.

# Instrução Técnica: Classificações de Exposição Solar e Tolerância à Maresia

## 1. Exposição Solar (Escala de 1 a 5)

Indica o grau de luminosidade ideal para o desenvolvimento da planta, em relação à radiação solar direta.

| Valor | Classificação         | Descrição resumida                            |
|-------|-----------------------|-----------------------------------------------|
| 1     | Sombra total          | Sem incidência direta de luz solar            |
| 2     | Sombra com claridade  | Luz solar difusa ou filtrada                  |
| 3     | Meia sombra           | Luz solar indireta em ambiente bem iluminado  |
| 4     | Sol Parcial           | Sol direto a maior parte do dia (>5 horas)    |
| 5     | Sol pleno             | Exposição solar intensa e contínua            |

**Aplicação prática:** A escolha do valor deve levar em conta a origem ecológica da espécie (sub-bosque, cerrado, deserto, restinga etc.) e seu comportamento fisiológico sob estresse térmico e luminoso.

---

## 2. Tolerância à Maresia (Escala de 1 a 3)

Define a capacidade da planta resistir ao ambiente litorâneo, salinidade atmosférica e ventos carregados de sais marinhos.

| Valor | Classificação           | Descrição resumida                               |
|-------|-------------------------|--------------------------------------------------|
| 1     | Não tolera              | Morre em condiçoes de exposição a maresia        |
| 2     | Moderadamente tolerante | Suporta maresia com graves impactos fisiológicos |
| 3     | Altamente tolerante     | Perfeitamente adaptada a ambientes de maresia    |

**Nota técnica:** A maresia é mais relevante para plantas cultivadas a menos de 5 km do litoral, especialmente em ambientes abertos e ventosos.

---

## Padronização para Registro

Sempre registrar a classificação com o **número e o significado correspondente** no título da seção (h2), e utilizar o parágrafo apenas para a descrição detalhada.

**Exemplo correto:**  
<h2>Exposição solar nível 4: Sol direto a maior parte do dia</h2>  
<p>Descrição detalhada sobre o comportamento da espécie sob essa condição.</p>

<h2>Tolerância à maresia nível 2: Moderadamente tolerante</h2>  
<p>Descrição detalhada sobre os impactos e recomendações para cultivo.</p>

# Instrução Técnica: Normas de Escrita em Grego e Latim para Catalogação Botânica

## 1. Escrita Latina: Nome Científico

### Regra Geral:
O nome científico das plantas deve seguir a nomenclatura binomial de *Linnaeus*, com formatação rigorosa:

**Formato:**
*Gênero espécie*, da família *Família*

### Regras tipográficas:
- O **nome científico** deve estar sempre em **itálico**.
- O **gênero** inicia com **letra maiúscula**.
- A **espécie** e a **família** são escritas com **letra minúscula**, mesmo que derivadas de nomes próprios.
- A **família** deve ser precedida por: `da família`
- O nome da família **não deve estar em itálico**.

### Exemplos:
- *Pachypodium lamerei*, da família *Apocynaceae*
- *Neoglaziovia variegata*, da família *Bromeliaceae*

---

## 2. Etimologia Grega: Uso do Grego Antigo

### Regra Geral:
Quando a etimologia envolver palavras gregas, estas devem ser grafadas utilizando **alfabeto helênico (grego clássico)**, não transliterações.

### Convenções de uso:
- Utilizar sempre o **alfabeto grego original**, mesmo em palavras compostas.
- Evitar a duplicação desnecessária de explicações. O grego aparece apenas como referência etimológica, não para tradução.

### Exemplo de aplicação:
> O nome *Pachypodium* deriva do grego παχύς (*pachýs*, “espesso”) e πόδι (*pódi*, “pé”), referindo-se à base engrossada do caule.

---

## 3. Ligaduras e Tipografia

###  Regras específicas:
- Empregar as **ligaduras tipográficas clássicas** nos dígrafos latinos:
  - *ae* → *æ*
  - *oe* → *œ*
- Não utilizar a ligadura visual “‿” em nenhuma circunstância.

### Exemplo:
- *Aechmea blanchetiana* → escrito como *Æchmea blanchetiana*
- *Coelogyne cristata* → escrito como *Cœlogyne cristata*

---

## 4. Exibição da Família no Index

Ao listar as espécies no arquivo index.html, sempre exibir o nome da família ao lado do nome científico, seguindo o padrão:

```html
<li><a href="Monstera_Adansonii.html"><em>Monstera adansonii</em>, da família Araceae</a></li>
```

- O nome científico deve estar em itálico.
- O nome da família deve aparecer após a expressão "da família", sem itálico.
- Seguir rigorosamente a tipografia e capitalização conforme instruções anteriores.

---

## 5. Referência ao Nome Popular na Etimologia

Ao iniciar a seção de etimologia de cada espécie, incluir a referência ao nome popular (quando houver), antes da explicação do nome científico.

**Exemplo:**
```html
<h2>Etimologia:</h2>
<p>
    Popularmente conhecida como jiboia, o nome <em>Epipremnum</em> deriva do grego ἐπί (*epí*, “sobre”) e πρέμνον (*prémnon*, “tronco”), referindo-se ao hábito de crescimento sobre troncos de árvores. O epíteto <em>aureum</em> vem do latim “áureus”, significando “dourado”, em alusão à coloração das folhas variegadas.
</p>
```

- O nome popular deve aparecer no início do parágrafo, em linguagem clara e objetiva.
- Manter o padrão nas demais espécies do catálogo sempre que houver nome popular

---

## Observações Finais

- Evitar traduções literais forçadas de nomes científicos.
- Toda etimologia deve ser concisa e respeitar a origem morfossintática das palavras gregas e latinas.
- O uso do grego deve ser **elegante e minimalista**, voltado à origem do nome, sem exageros filológicos.
