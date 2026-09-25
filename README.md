# Landing page — Maria Luíza Viana Santos

Site estático em HTML, CSS e JavaScript, sem dependências de build. A página principal está em `dist/index.html`; o estilo está em `dist/styles.css` e as interações em `dist/script.js`.

## Editar o conteúdo

- **Nome, textos, serviços, endereço, CRP e telefone:** edite `dist/index.html`.
- **WhatsApp:** procure `5515998263434` em `dist/index.html` e substitua em todas as ocorrências pelo número confirmado, no formato `55` + DDD + número. Atualize também o telefone visível e o campo `telephone` dos dados estruturados no `<head>`.
- **Endereço:** altere a seção `#localizacao`, o rodapé, o link para rotas e o campo `address` dos dados estruturados.
- **Mapa do consultório:** a seção `#localizacao` usa um mapa incorporado do Google e mantém o botão de rota visível. Ao trocar o endereço, atualize também o parâmetro `q=` do `iframe`.
- **Fotos do espaço:** `dist/consultorio-ilustrativo.jpg` e `dist/recepcao-ilustrativa.jpg` são imagens geradas para a prévia e não retratam o consultório real. Antes de divulgar a página, substitua os arquivos por fotos autorizadas mantendo os nomes (ou altere os `src` no HTML) e atualize os textos `alt` em `dist/index.html`.
- **Foto principal:** a foto autorizada atual está em `dist/maria-luiza-hero.jpg`; a segunda foto está em `dist/maria-luiza-sobre.jpg`. Substitua os arquivos ou atualize o `src` correspondente em `dist/index.html`.
- **Logo:** `dist/maria-luiza-logo.png` é o arquivo original recebido. Ele aparece no cabeçalho e no rodapé; o ajuste de cor é feito pela classe `.brand-logo` em `dist/styles.css`, sem alterar a imagem original.
- **Cores e fontes:** as variáveis no início de `dist/styles.css` controlam a identidade visual.
- **Link do Google:** o link atual abre diretamente a área de avaliações a partir da URL fornecida. Confirme o destino final no navegador antes de divulgar.
- **Headline e serviços:** a abertura destaca avaliação neuropsicológica e os cards mantêm as quatro áreas já apresentadas no briefing. Confirme com Maria Luíza os serviços oferecidos atualmente antes de divulgar.
- **Tom de voz:** os textos visíveis são escritos como uma conversa de Maria Luíza com a pessoa visitante, em primeira pessoa. As mensagens preenchidas nos links do WhatsApp estão na voz de quem envia a mensagem.
- **Dúvidas frequentes:** valores e convênios são direcionados para consulta pelo WhatsApp; a página não afirma preços nem cobertura. Confirme o processo de avaliação, a participação dos responsáveis e os títulos acadêmicos antes da versão definitiva.

## Confirmar com Maria Luíza antes da publicação aberta

1. O número de WhatsApp, endereço e horários foram atualizados conforme as informações recebidas em 24/09/2026; reconfirme antes de uma publicação aberta.
2. Modalidades oferecidas atualmente e faixas etárias atendidas.
3. Nomes oficiais dos títulos acadêmicos e texto da apresentação em primeira pessoa.
4. Etapas específicas da avaliação e do atendimento.
5. As duas fotos pessoais recebidas foram incluídas; imagens reais do espaço ainda não foram fornecidas.
6. Revisão final do conteúdo clínico e autorização para divulgação.

A prévia está configurada como Site privado. Nenhum comentário de pacientes ou família foi copiado para a página.

## Uso local

Abra `dist/index.html` em um navegador. Os links internos e o menu responsivo funcionam sem servidor; as fontes externas e os links de WhatsApp, Google e Maps exigem conexão.

## Avaliações do Google

A página direciona o visitante às avaliações na própria plataforma. Depoimentos individuais de pacientes ou responsáveis não foram republicados: a orientação do CFP exige consentimento expresso por escrito e desaconselha o uso, especialmente quando há crianças e adolescentes envolvidos.
