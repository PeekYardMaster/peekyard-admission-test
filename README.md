# Projeto Farol — versão 2 (homologação de admissão)

Este repositório contém uma landing page **fictícia, pública e sem backend** para testar a inscrição de projetos no [Peekyard](https://github.com/PeekYard/admissions).

A versão 2 foi deliberadamente modificada em relação ao snapshot da admissão anterior: removeu Google Fonts, o script JavaScript inline e recursos remotos de apresentação; adicionou explicação do fluxo de admissão e um bloco de privacidade. A aplicação ainda não está publicada na vitrine da Peekyard.

## Escopo do teste

- Formulário e triagem de nova inscrição, vinculada ao commit atual da branch padrão.
- Análise institucional consultiva por IA, sem dados de contato fornecidos ao modelo.
- Inspeção de metadados Git (WebSec de pré-admissão, sempre parcial) e consolidação de relatório privado.
- Revisão humana obrigatória antes de provisionamento, aprovação, merge ou publicação.

## Arquivos e dependências

- `index.html`: HTML sem scripts, CSS embutido, fontes de sistema; link externo apenas para o perfil público do responsável no GitHub.
- Nenhum pacote, build, API, formulário, rastreador, CDN ou recurso remoto embutido.

**Não executar o código de candidatos no runner de automações.** Este repositório é uma fonte de teste e não concede permissões operacionais. O snapshot anterior `PeekYard/admissions#4` e a reserva `PeekYard/operations#116` devem continuar preservados para auditoria. A nova inscrição só deverá ser aberta após o merge desta alteração na branch `main`.
