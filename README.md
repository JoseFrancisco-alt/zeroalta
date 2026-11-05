# Barbearia Zeroalta · protótipo

Protótipo do site da Barbearia Zeroalta (Boavista/Porto, Espinho e Lourosa, Portugal), feito para apresentar a proposta de redesign do site atual (WordPress).

**No ar:** https://josefrancisco-alt.github.io/zeroalta/

## O que tem
- Identidade da marca: preto, dourado do logo (`#dca54a`) e creme; slogan "Você aqui, você em alta."
- Serviços com preço, avaliações do Google em texto (faixa arrastável com setas), contadores e as 3 barbearias com "Marcar" e "Como chegar".
- Marcação única para as 3 lojas (`agendar.html`): barbearia → serviço → barbeiro → dia → hora → dados. A mensagem abre pronta no WhatsApp (+351 936 580 038). Links diretos por loja: `agendar.html?loja=boavista|espinho|lourosa`.
- Efeitos: abertura com navalha, cursor personalizado, botões magnéticos, texto palavra por palavra, faixa que entorta com a rolagem, letreiro no rodapé.
- Texto em português de Portugal (marcar, telemóvel).

## Editar
- Lojas, serviços, barbeiros, horários e WhatsApp: topo de `agenda.js`.
- Cores: variáveis no topo de `style.css` e `COLORS` em `script.js`.

## Pendências antes da versão final
- Preços que faltam e quais barbeiros atendem em cada loja (os nomes vieram das avaliações).
- Horários ocupados são de exemplo: a versão real precisa de banco de dados.

HTML, CSS e JS puros, sem build.
