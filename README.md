# 99Food Performance — versão 6

Aplicativo local de apoio à consultoria comercial e às visitas em restaurantes.

## Como abrir
1. Extraia o arquivo ZIP para uma pasta.
2. Abra `index.html` no Google Chrome ou Microsoft Edge.
3. Os dados ficam salvos no armazenamento local do navegador usado.

## Módulos
- Formulário de visita consultiva com identificação, contrato Fixo/Flex, diagnóstico por pilares em blocos individuais, com perguntas, observações/evidências, status e progresso geral; indicadores, itens mais pedidos e plano de ação.
- Painel de performance com indicadores, funil de visitas à loja → carrinhos → pedidos, ranking de itens e distribuição de contratos.
- Inteligência competitiva com comparação manual dos preços 99Food, Keeta e iFood, além de campos para número de pedidos e faturamento de cada plataforma no mesmo período.
- Painel comparativo com barras de pedidos e faturamento por plataforma e ticket médio estimado no relatório PDF.
- Importação de gravações de tela e leitura OCR de quadros selecionados no próprio navegador. A leitura é preliminar e deve ser revisada manualmente.
- Diagnóstico automático de diferenças de preço: destaca itens em que o preço 99Food informado supera o menor preço informado entre Keeta e iFood.
- Relatório executivo imprimível / salvável em PDF pelo navegador.
- Backup e restauração em JSON.

## Limitações importantes
- Não há integração direta com as plataformas 99Food, Keeta ou iFood.
- O OCR é uma triagem de texto/preços, não uma IA que entende perfeitamente produtos, tamanhos, promoções ou adicionais. Confira equivalência e dados antes de recomendar alterações.
- Os dados são armazenados localmente neste navegador/dispositivo. Exporte o backup JSON para guardar ou transferir os registros.
- Para leitura OCR, o navegador precisa de internet para carregar a biblioteca Tesseract.js por CDN.
- O PDF é gerado pela função Imprimir do navegador: escolha “Salvar como PDF”.
