# Advocacia Previdenciaria Barkoski para Codex

Versao independente para o Codex da skill de Direito Previdenciario brasileiro criada por Lucas Barkoski. O projeto original para Claude permanece separado e nao e alterado por este repositorio.

## Principais controles

- rastreabilidade entre afirmacao, arquivo e pagina;
- separacao entre fato comprovado, alegacao, inferencia e conclusao juridica;
- tabela de provas e matriz requisito-prova-risco;
- analise adversarial e melhor tese provavel do INSS;
- protecao de dados e autorizacao antes de qualquer envio externo;
- pesquisa juridica em fontes oficiais;
- prazos e calculos com memoria reproduzivel;
- minutas sempre sujeitas a revisao integral do advogado.

## Instalacao no Codex

Copie a pasta `skills/advocacia-previdenciaria-barkoski-codex` para:

```text
C:\Users\SEU_USUARIO\.codex\skills\advocacia-previdenciaria-barkoski-codex
```

Reinicie o Codex ou inicie uma nova tarefa. A skill sera acionada em trabalhos com INSS, CNIS, PJe, processos e beneficios previdenciarios.

## Estrutura

```text
skills/advocacia-previdenciaria-barkoski-codex/
|- SKILL.md
|- agents/openai.yaml
`- references/
```

## Limites

A skill produz material de apoio e minutas para revisao profissional. Nao substitui o advogado, nao protocola automaticamente, nao promete resultado e nao transforma estimativa em calculo definitivo.

## Origem e licenca

Adaptacao autorizada da skill `advocacia-previdenciaria-barkoski`, mantida em repositorio separado. Licenca MIT.
