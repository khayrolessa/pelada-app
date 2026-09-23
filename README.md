# Pelada — Web App/PWA

Aplicação web para gestão completa da pelada, com Supabase como banco/autenticação e hospedagem compatível com Vercel.

## Backend
Projeto Supabase: `app-pelada`.

A aplicação começa zerada: nenhum jogador presente, nenhum pagamento, nenhuma partida e nenhuma estatística fictícia.

## Funcionalidades
- pelada do dia;
- cadastro, chegada e saída;
- pagamento pago/pendente/isento;
- caixa e despesas;
- fila individual por participação;
- formação e transição de times;
- vencedor permanece e perdedor sai;
- reaproveitamento quando não há time completo esperando;
- placar e cronômetro de 7 minutos;
- encerramento por 2 gols;
- nomes dos jogadores na tela do juiz;
- goleiros destacados;
- gol + assistência;
- defesas dos goleiros;
- troca de goleiro;
- desfazer evento;
- pênaltis com gol, defesa e fora/trave;
- histórico e ranking;
- acesso temporário do juiz por link;
- PWA e cache básico offline.

## Primeiro acesso
Use a opção “Primeiro acesso / criar administrador” na tela inicial e defina e-mail e senha do administrador. O username interno é `khayrolessa`.
