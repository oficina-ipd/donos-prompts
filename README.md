<p align="center">
  <img src="https://raw.githubusercontent.com/oficina-ipd/.github/main/assets/logo.png" alt="Oficina IPD" width="120" />
</p>

# Donos Prompts

**Prompts e skills prontos pra colocar a sua IA pra trabalhar no negócio — não pra conversar.**

Todo mundo me pergunta qual IA usar. Quase ninguém me pergunta o que quer que ela execute. Este repositório é a segunda pergunta respondida: tarefas inteiras, escritas pra um agente fazer do começo ao fim, com limite claro do que ele pode e não pode fazer no seu nome.

Feito pela [Oficina IPD](https://github.com/oficina-ipd), o braço open-source da comunidade [IA para Donos](https://www.iaparadonos.com/comunidade).

## O que tem aqui

| Prompt / skill | O que faz | Status |
|---|---|---|
| [**Caçador de Créditos de IA**](cacador-de-creditos/) | Procura, pede e acompanha créditos gratuitos de IA e nuvem pra você ou sua empresa — só onde você é elegível de verdade | **Disponível (v0.1)** |

Cada pasta tem três coisas:

- `README.md` — o guia pra leigo: o que é, como usar, o que esperar, avisos.
- `SKILL.md` — a versão pra instalar no **OpenBot** (ou em qualquer IA que aceite skills).
- `PROMPT.md` — o bloco pra copiar e colar em qualquer IA com navegador.

## Como usar

**No OpenBot (recomendado):** peça pro seu agente baixar o `SKILL.md` da pasta numa pasta do espaço de trabalho dele e criar uma skill local com ela. Cada guia traz a frase exata. No OpenBot seus dados ficam no Vault, senha vai por campo seguro, aprovação é um clique e a rotina roda sozinha.

**Em outra IA:** abra o `PROMPT.md`, copie, preencha numa conversa privada e envie.

## O padrão destes prompts

- **Faz, não só sugere.** O agente executa a tarefa e prova o resultado.
- **Verdade acima de resultado.** Nada de inventar dado pra caber em formulário.
- **Nada pago sem você.** Nenhum prompt contrata, cobra ou assina no seu nome.
- **Seus dados ficam com você.** Conversa privada, registro privado, nada de senha no chat.
- **Português claro.** Se um leigo não entende, a gente reescreve.

## Contribuir

Não precisa ser programador. Testou um prompt? Conta o que funcionou e o que travou num [issue](https://github.com/oficina-ipd/donos-prompts/issues/new?template=feedback.md). Sem dado pessoal, sem CNPJ, sem print com e-mail. Veja o [CONTRIBUTING](CONTRIBUTING.md).

## Licença

[MIT](LICENSE). Use, adapte e espalhe.
