# 🛡️ Requisitos Não Funcionais

## O que são?

Os **requisitos não funcionais (RNF)** descrevem características de qualidade, condições de funcionamento ou restrições que o sistema deve atender.

Enquanto um requisito funcional explica **o que o sistema faz**, um requisito não funcional costuma indicar **como o sistema deve funcionar** ou quais condições precisa respeitar.

## Categorias comuns

- **Desempenho:** tempo de resposta e capacidade de processamento.
- **Segurança:** proteção de dados e controle de acesso.
- **Usabilidade:** facilidade de uso e compreensão da interface.
- **Compatibilidade:** funcionamento em dispositivos, navegadores ou ambientes definidos.
- **Disponibilidade:** período em que o sistema precisa estar acessível.
- **Manutenibilidade:** facilidade para corrigir e evoluir o software.

## Exemplos

Em um sistema de delivery:

- **RNF01 — Desempenho:** nas condições de teste definidas, a página inicial deve carregar em até 2 segundos.
- **RNF02 — Segurança:** as senhas dos usuários devem ser armazenadas usando um mecanismo seguro de hash apropriado.
- **RNF03 — Compatibilidade:** a interface deve funcionar nas versões de navegadores e nos dispositivos definidos pelo projeto.
- **RNF04 — Usabilidade:** os textos de erro devem explicar o problema e orientar o usuário sobre como prosseguir.
- **RNF05 — Disponibilidade:** o serviço deve atingir a meta de disponibilidade acordada para o período de medição.

Os exemplos são ilustrativos. Em projetos reais, limites, ferramentas, versões e metas devem ser definidos com as partes interessadas.

## Como escrever um requisito não funcional?

Evite expressões vagas como “rápido”, “seguro” ou “fácil de usar” sem explicar como isso será avaliado.

**Vago:**

> RNF01 — O sistema deve ser rápido.

**Mais verificável:**

> RNF01 — Nas condições de teste acordadas, 95% das consultas ao cardápio devem ser respondidas em até 2 segundos.

## Boas práticas

- Especifique condições e critérios de medição quando possível.
- Evite termos subjetivos sem definição.
- Verifique se o requisito pode ser testado ou avaliado.
- Registre as metas com as pessoas responsáveis pelo projeto.

## Checklist

- [ ] O requisito descreve qualidade, condição ou restrição?
- [ ] Está claro como avaliar seu cumprimento?
- [ ] As metas e condições estão definidas?
- [ ] O requisito é relevante para o sistema?
