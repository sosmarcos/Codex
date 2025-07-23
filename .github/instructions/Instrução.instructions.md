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