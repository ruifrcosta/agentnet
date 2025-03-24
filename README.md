# AgentNet Framework

Framework para construção de sistemas multi-agentes colaborativos.

## Recursos

- Criação de agentes especializados
- Memória compartilhada e privada
- Sistema de comunicação entre agentes
- Ferramentas integradas
- Fácil extensibilidade

## Instalação

```bash
pip install agentnet
```

## Uso Rápido

```python
from agentnet import Team, Agent, Memory

# Criar time de agentes
team = Team()
team.add_agent(Agent("researcher", model="gpt-4"))
team.add_agent(Agent("writer", model="claude-3"))
team.add_agent(Agent("reviewer", model="gemini-pro"))

# Adicionar memória compartilhada
team.set_memory(Memory.shared())

# Executar tarefa colaborativa
result = team.run("Pesquisar, escrever e revisar um artigo sobre IA generativa")
print(result)
```

## Documentação

Para documentação completa, visite [docs/README.md](docs/README.md).

## Licença

MIT
