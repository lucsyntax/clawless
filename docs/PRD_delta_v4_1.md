# Clawless PRD Delta v4.1

## Mudanças aprovadas

1. Provider inicial padrão deixa de ser Anthropic.
   - default_provider = "openai_compat"
   - default_model = definido por endpoint configurado
   - Anthropic continua suportado, mas não é caminho inicial

2. OpenFang é referência de dashboard e conceito de Claws.
   - Não usar stack Rust
   - Não perseguir paridade de produto no MVP

3. OpenClaw é referência de:
   - gateway local-first
   - bind local
   - auth obrigatória
   - WS tipado
   - separação entre tools e skills

4. nanobot continua como base obrigatória de leitura e migração,
   mas não será alterado em /reference/nanobot.