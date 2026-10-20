# Coleta dos Reinos — Aventura da Vida

Jogo educativo de navegador para explorar a diversidade dos seres vivos e praticar sua classificação. Desenvolvido em HTML, CSS e JavaScript, sem bibliotecas externas nem servidor próprio.

**Jogue online:** quando o GitHub Pages estiver ativado, o endereço será  
https://lucksk-72.github.io/coleta-dos-reinos/

## O que há no jogo

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
2. Escolha o reino ou o desafio com todos os reinos e selecione um cenário.
3. Durante a rodada, selecione os organismos que correspondem ao reino escolhido.
4. Use a lupa quando precisar de ajuda e consulte o Catálogo Vivo para rever as descobertas.
5. No Modo Aula, gere um relatório resumido da atividade naquele navegador.

## Executar ou hospedar

Não é preciso instalar dependências. Para executar localmente, baixe o repositório e abra `index.html` em um navegador moderno.

### Ativar o GitHub Pages

1. Abra **Settings** neste repositório.
2. Entre em **Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch **main** e a pasta **/(root)** e clique em **Save**.
5. Aguarde o GitHub publicar o site. O endereço deverá ser:
   https://lucksk-72.github.io/coleta-dos-reinos/

Se o endereço não aparecer imediatamente, aguarde alguns minutos e atualize a página de Settings → Pages. Novos commits na branch `main` serão publicados automaticamente.

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
