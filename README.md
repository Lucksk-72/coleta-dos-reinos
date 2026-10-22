# Coleta dos Reinos — Aventura da Vida

Jogo educativo de navegador para explorar a diversidade dos seres vivos e praticar sua classificação. Desenvolvido em HTML, CSS e JavaScript, sem bibliotecas externas nem servidor próprio.

**Jogue online:** https://lucksk-72.github.io/coleta-dos-reinos/  
**Modo Jovem — Corrida da Biodiversidade:** https://lucksk-72.github.io/coleta-dos-reinos/jovem.html

## Modos de jogo

- **Modo Infantil** (`index.html`): captura por toque/clique, agora com rodadas iniciais de 45 segundos e mais tempo para observar cada organismo.
- **Modo Jovem — Corrida da Biodiversidade** (`jovem.html`): campanha de cinco fases, com 3 minutos por fase (15 minutos de jogo), uma para cada reino didático. Inclui personagem correndo, saltos, obstáculos, coleta de organismos do reino-alvo, vidas, pontuação e revisão educativa ao final.
- No modo jovem, a campanha percorre os cinco reinos; é possível escolher por qual começar, e as outras fases seguem em sequência automática. Cada transição apresenta o novo objetivo. O cenário inicial é uma floresta, com controles por teclado ou toque. O recorde fica salvo localmente no navegador.

## O que há no modo infantil

- Seleção de reino biológico e de cenário: floresta, oceano, deserto, Ártico e mundo microscópico.
- Rodadas cronometradas, pontuação, combos e retorno imediato sobre acertos e erros.
- Recursos de ajuda, como lupa e pausa temporária.
- Sons opcionais gerados pelo navegador.
- Catálogo Vivo com organismos descobertos e curiosidades.
- XP, níveis e progresso armazenados localmente no navegador.
- Modo Aula que gera um relatório local para copiar ou baixar como TXT.
- Interface adaptável a computadores, tablets e celulares.

## Como jogar

1. Abra o jogo no navegador.
2. Na página inicial, escolha o Modo Infantil ou abra **Modo Jovem: Corrida**.
3. No modo infantil, selecione um reino e um cenário; durante a rodada, toque apenas nos organismos do reino-alvo.
4. No modo jovem, escolha o reino-alvo, mova o personagem, salte obstáculos e desvie dos organismos que não correspondem à missão.
5. Consulte o Catálogo Vivo (infantil) ou a revisão de descobertas ao final da corrida (jovem).
6. No Modo Aula, gere um relatório resumido da atividade naquele navegador.

## Executar ou hospedar

Não é preciso instalar dependências. Para executar localmente, baixe o repositório e abra `index.html` em um navegador moderno.

### Ativar o GitHub Pages

O repositório inclui um fluxo de publicação automática em `.github/workflows/pages.yml`. Para ativar o site:

1. Abra **Settings** neste repositório.
2. Entre em **Pages**.
3. Em **Build and deployment → Source**, selecione **GitHub Actions**.
4. Se solicitado, autorize as permissões de Pages para o fluxo.
5. Abra a aba **Actions** e acompanhe o fluxo **Deploy to GitHub Pages**. A primeira publicação pode levar alguns minutos.

Quando a implantação terminar, o endereço esperado é:
https://lucksk-72.github.io/coleta-dos-reinos/

Cada novo commit na branch `main` acionará uma nova publicação automaticamente. Se o site não aparecer, confira o resultado do fluxo em **Actions** e a configuração de **Settings → Pages**.

## Uso em sala de aula

O Modo Aula é um apoio simples para atividades coletivas. O relatório representa os dados disponíveis naquele navegador; não é um sistema de chamada, avaliação oficial ou acompanhamento individual de estudantes. O professor deve revisar as informações científicas e adequar a atividade à faixa etária e ao currículo.

## Precisão científica

O jogo adota uma classificação simplificada para tornar a atividade acessível. A divisão tradicional em cinco reinos é um modelo didático, não a única classificação científica atual. “Protistas” reúne organismos muito diversos e não corresponde a um único grupo evolutivo natural em todas as classificações. Alguns organismos podem ocupar mais de um ambiente, e os exemplos apresentados não substituem uma fonte de taxonomia especializada. Sugestões e correções científicas são bem-vindas por meio das Issues do repositório.

## Privacidade e limitações

- O jogo não envia deliberadamente os dados de progresso a um servidor; o progresso é salvo no armazenamento local (`localStorage`) do navegador.
- O progresso não sincroniza automaticamente entre navegadores ou dispositivos e pode ser perdido se os dados do site forem apagados.
- O relatório do Modo Aula é criado no dispositivo. Evite inserir dados pessoais ou sensíveis de estudantes.
- O protótipo não inclui contas, multiplayer, banco de dados remoto, sincronização em nuvem nem painel online para professores.
- O site hospedado pelo GitHub Pages está sujeito aos termos e à disponibilidade do GitHub.

## Acessibilidade e compatibilidade

O projeto busca uma interface responsiva, controles com foco visível e opção para desligar sons. Recomenda-se testar com os dispositivos, navegadores e tecnologias assistivas utilizados pela turma antes de uma aplicação formal.

## Como contribuir

1. Abra uma Issue descrevendo o problema, a correção científica ou a melhoria desejada.
2. Se souber programar, faça um fork, crie uma branch e envie um Pull Request.
3. Para correções científicas, inclua referências confiáveis (livros didáticos, artigos ou instituições científicas).

## Licença

Distribuído sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE).
