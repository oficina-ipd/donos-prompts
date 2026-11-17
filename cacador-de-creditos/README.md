# Caçador de Créditos de IA

**Coloca a sua IA pra caçar crédito grátis de IA e nuvem no seu nome — e acompanhar até o crédito cair na conta.**

Me responde uma coisa: quanto você paga por mês de chave de IA? Agora outra: quantas vezes você parou pra procurar se a Anthropic, a OpenAI ou o Google estavam dando crédito pra alguém do seu tamanho?

Se a resposta da segunda foi "nunca", o problema não é falta de programa. É falta de tempo pra ler regra, preencher formulário e ficar de olho em prazo. Isso é exatamente o tipo de trabalho que um agente faz melhor que a gente.

## Por que isso importa pra quem usa a Oficina

Na Oficina, toda ferramenta usa **a sua chave de IA**. A gente não segura nem cobra uso. Na prática:

| Ferramenta | Chave que ela usa | Crédito que ajuda |
|---|---|---|
| [CRM do Dono](https://github.com/oficina-ipd/crm-do-dono-template) | Anthropic (Claude) | créditos da Anthropic |
| [DealMiner](https://github.com/oficina-ipd/dealminer) | OpenAI | créditos da OpenAI |

Crédito que paga a chave que você já usa vale mais que crédito bonito em serviço que você nunca vai abrir. O Caçador começa por aí.

## A real, antes de começar

- **Nem todo programa é pra você.** Muito programa grande é feito pra startup de tecnologia, às vezes só via aceleradora ou investidor. Uma clínica, uma loja ou uma padaria pode não se encaixar — e tudo bem. O Caçador verifica antes e **nunca declara nada que não é verdade** sobre você ou a sua empresa.
- **Crédito não é dinheiro.** Tem validade, vale pra certos produtos e às vezes pede cartão. O Caçador separa o que já está liberado do que está em análise ou condicionado.
- **Você continua no comando.** Ele cria contas e faz inscrições **gratuitas**. Não paga, não ativa cobrança, não assina contrato. Por padrão, mostra a lista de inscrições antes de enviar.

Alguém vai dizer que é mais rápido entrar no site e se inscrever na mão. Pra um programa, é. Pra oito provedores, com regra mudando todo mês e prazo vencendo calado, não é.

## Como usar

### Jeito recomendado: OpenBot

1. Abra um agente no OpenBot e mande:

   > Baixe este arquivo numa pasta `cacador-de-creditos` do seu espaço de trabalho, crie uma skill local com ela e use a skill para buscar créditos de IA pra mim: https://raw.githubusercontent.com/oficina-ipd/donos-prompts/main/cacador-de-creditos/SKILL.md

2. Responda as perguntas (são no máximo 5) e aprove a ficha da sua empresa.
3. Quando ele pedir, assuma o navegador pra digitar código de SMS ou resolver CAPTCHA. O resto ele faz.

O que o OpenBot faz diferente:

- Seus dados ficam no **Vault**, não colados no chat.
- Senha e código vão por **campo seguro**. Você nunca digita senha na conversa.
- As aprovações aparecem como **cartão de confirmação**: você clica, não precisa escrever.
- O registro fica numa **tabela** (`creditos_ia`) que você abre quando quiser.
- Uma **rotina** semanal acompanha os pedidos e te avisa de prazo.

### Outras IAs (Claude, ChatGPT, Codex e afins)

- **Com suporte a skills** (ex.: Claude Code): salve o [SKILL.md](SKILL.md) numa pasta `cacador-de-creditos` dentro da pasta de skills da sua IA.
- **Sem skills:** copie o [prompt pronto](PROMPT.md), preencha seus dados numa conversa privada e envie. A IA precisa ter acesso ao navegador.

## O que você recebe

- Uma tabela com cada programa: link oficial, se você é elegível e por quê, valor, validade, status, prova e próximo passo.
- As inscrições feitas, com print ou e-mail de confirmação.
- Um resumo: **liberado**, **em análise**, **condicionado**, **não elegível** — com valores separados por moeda.
- A lista do que depende de você, com o passo exato.
- Se o seu ambiente agenda tarefas, uma rotina de acompanhamento.

## Avisos

- **Seus dados são seus.** Use só em conversa privada. Não publique a tabela com CNPJ, e-mail ou telefone, nem cole isso num issue.
- **Programa muda o tempo todo.** Valor, regra e prazo podem ter mudado desde que este texto foi escrito. A página oficial do provedor é quem decide.
- **A inscrição sai no seu nome.** Leia a ficha da empresa antes de aprovar. Se a IA errou, você corrige uma vez e ela reusa a versão certa.
- Este repositório não tem nenhum vínculo com Anthropic, OpenAI, Google, Microsoft, AWS, xAI, NVIDIA ou Vercel. Os nomes aparecem só pra dizer onde procurar.

## Créditos

Ideia inspirada no prompt "Buscar créditos de IA" do guia [curso-vibecoding](https://github.com/soumatheusgomes/curso-vibecoding/blob/main/prompts/dicas/buscar-creditos-de-ia.md), de Matheus Gomes. Texto escrito do zero e adaptado para donos de pequeno negócio e para o OpenBot.

---

Achou um programa que o Caçador não pegou? Alguma parte ficou confusa? [Abra um issue](https://github.com/oficina-ipd/donos-prompts/issues/new?template=feedback.md). Se um leigo não entende, a gente reescreve.
