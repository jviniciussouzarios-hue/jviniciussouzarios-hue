# Revisão e instalação

Esta é a primeira versão para revisão. Nenhum arquivo foi publicado no GitHub.

## Arquivos

- `README.md`: conteúdo do perfil.
- `assets/hero.svg`: banner local na paleta solicitada.
- `assets/typing.svg`: animação local em SVG, sem JavaScript.
- `.github/workflows/snake.yml`: geração diária da contribution snake, ainda não executada.

## Antes de publicar

1. Confira o usuário `jviniciussouzarios-hue`, extraído do endereço de portfólio informado na conversa.
2. Revise as descrições dos cinco projetos. Não foram atribuídos resultados quantitativos nem links de repositórios não confirmados. “Fleet Intelligence” é um título editorial para o case de BI/Frota.
3. LinkedIn e e-mail foram incluídos conforme informados nesta conversa. O portfólio usa o endereço já fornecido; sua disponibilidade não pôde ser verificada nesta sessão.
4. A formação FAM não declara conclusão ou data, pois esse status não foi informado. Os cursos Google não são apresentados como o certificado profissional completo.

## Instalar no perfil

Copie `README.md`, a pasta `assets` e `.github/workflows/snake.yml` para a raiz do repositório público `jviniciussouzarios-hue/jviniciussouzarios-hue`. Preserve a estrutura das pastas. Este guia não precisa ser publicado.

O README usa Markdown e HTML simples. O GitHub controla o fundo da página; a identidade dark se aplica ao hero, à animação e ao card de analytics. As seções continuam legíveis nos temas claro e escuro.

## Ativar a snake

1. Na aba Actions, habilite os workflows se necessário.
2. Execute `Generate contribution snake` usando `Run workflow`.
3. Aguarde a criação da branch `output` e do arquivo `github-snake.svg`.
4. No README, remova o comentário externo do bloco `CONTRIBUTION SNAKE`, deixando o título e a imagem visíveis.

O workflow usa `GITHUB_TOKEN`, sem token pessoal. Ele precisa de permissão de escrita de conteúdo para publicar o SVG na branch `output`. Não use uma branch `output` que contenha outros arquivos importantes, pois ela será administrada pela action de publicação. A agenda roda diariamente às 09:17 UTC, sujeita ao agendamento do GitHub.

## Recursos e limitações

- O hero e a animação ficam no próprio repositório. A frase animada também está no texto alternativo.
- O card de analytics consulta um serviço externo e pode ter cache, limites ou indisponibilidade. O link para o GitHub permanece utilizável mesmo se a imagem falhar. Não foram simuladas estatísticas.
- A snake só aparece depois da ativação; não há gráfico de contribuições fictício nesta versão.
- O README oferece navegação, conteúdo expansível e animação; não executa scripts nem um jogo interativo.

Referências técnicas: [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats), [Platane/snk](https://github.com/Platane/snk) e [action de publicação](https://github.com/crazy-max/ghaction-github-pages).
