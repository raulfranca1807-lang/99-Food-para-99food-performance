# 99Food Performance — versão 17

CRM comercial com identidade visual amarela 99Food.

## Novidades da versão 15
- Funil visual com quatro etapas: visitas, carrinhos, pedidos realizados e pedidos concluídos.
- Cálculo automático das taxas por etapa e da conversão geral (pedidos concluídos ÷ visitas à loja).
- Diagnóstico automático comparando os resultados com metas configuráveis pelo consultor.
- Metas editáveis para visita→carrinho, carrinho→pedido, pedido→concluído e conversão geral.
- Mantém formulário em blocos, respostas Sim/Não, status dos pilares, histórico, concorrência e relatórios.

## Arquivos
- `index.html`
- `app.js`

Os dados e parâmetros ficam armazenados localmente no navegador. Faça backup regularmente. As metas iniciais são apenas valores de partida ilustrativos e devem ser ajustadas pelo consultor; não são benchmarks oficiais da 99Food.


Correção v14: a conversão geral é recalculada ao digitar visitas e pedidos. Usa “Pedidos concluídos” quando preenchido; se esse campo estiver vazio, usa “Pedidos no período”.


**Versão 15:** reorganização da navegação principal para Formulário, Concorrência, Performance, Relatórios e Histórico, nessa ordem. Backup permanece como último botão.


Correção v15: cálculo de conversão reforçado com atualização durante digitação, alteração de campo e saída do campo. Aceita separador decimal com vírgula.


Correção v16: o campo de conversão geral agora é texto somente leitura para aceitar a formatação decimal brasileira (vírgula). O cálculo atualiza diretamente ao digitar, alterar ou sair dos campos de visitas e pedidos.


**Versão 17:** removido do formulário o bloco ‘3. Indicadores de performance’ e removido o botão ‘Performance’ da navegação principal, conforme solicitado. As demais abas permanecem disponíveis.
