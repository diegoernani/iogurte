# Iogurte — referência visual histórica (2008–2009)

## Fonte de design

Pacote de 100 quadros fornecidos pelo usuário, derivado de vídeo tutorial do Orkut. Quadros 001–062 contêm telas e transições; quadros 063–100 apresentam essencialmente repetição do logotipo. Os arquivos de referência não são redistribuídos neste repositório.

Complemento de pesquisa histórica: https://orkutdeveloper.blogspot.com/2009/11/new-orkut-more-for-apps.html

## Mapeamento

| Quadros | Padrão observado | Implementação |
|---|---|---|
| 008–014 | Criação de conta vinculada à Conta Google, formulários de cadastro com rótulos à esquerda | `/cadastro`: protótipo visual em três etapas, **sem senha ou autenticação real** |
| 015–018 | Tela de boas-vindas, links compactos, coluna lateral e blocos | `/`: home com caixas, recados e sorte de hoje |
| 020–022 | Listas compactas de amigos/membros, miniaturas | `/friends`: grade de amigos |
| 025–032 | Perfil de terceiro e diálogo de adicionar amigo/grupos | `/profile/[id]` demonstrativo; solicitações de amizade ainda não implementadas |
| 033–041 | Recados, painel de perfil, indicadores social e pessoal | `/scraps`, `/profile/me` |
| 043–052 | Busca de comunidades, categorias, seleção | `/communities`: busca e criação demonstrativas |
| 053–060 | Página da comunidade, fórum tabular, contadores e categorias | `/communities/[id]`, `/communities/[id]/topic/[id]` |
| 063–100 | Vinheta e logo repetidos | Não reproduzir literalmente o logotipo; manter marca própria |

## Regras de fidelidade

- Tamanho-base 12px Verdana, links azuis e fundo #d9e5f3.
- Três colunas desktop: 160px, conteúdo central e 230px.
- Menus e caixas com cabeçalho azul muito claro, pouca sombra.
- Perfis tabulados: social, profissional e pessoal.
- Fóruns em formato tabela com nome do tópico, autor e quantidade de respostas.
- Dados de demonstração nunca devem ser apresentados como contas reais.
- Não reutilizar logotipo/marca oficial do Orkut em produção.

## Trabalho pendente para produção

1. Supabase Auth (não coletar senha em protótipo local).
2. Modelo relacional de usuários, amizade, comunidades, tópicos e mensagens.
3. Convites, permissões de moderação, solicitações de amizade e aprovação de depoimentos.
4. Upload seguro de imagens e álbuns.
5. Privacidade, consentimento, bloqueios, denúncias e anti-spam.
6. Testes e migrações versionadas.
