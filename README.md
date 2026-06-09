<div align="center">

# DiceMind

**RPG solo com narrativa guiada por IA e regras inspiradas em AD&D 2ª edição.**

[![Google Play](https://img.shields.io/badge/Google_Play-Baixar_o_jogo-34A853?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.bilbo.bilbomobile&hl=pt_BR)
[![Versão](https://img.shields.io/badge/versão-0.1.0-blue?style=for-the-badge)](https://github.com/rafaelcavalheri/dicemind/releases)
[![Licença](https://img.shields.io/badge/licença-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## O que é o DiceMind?

DiceMind é um RPG solo onde uma IA assume o papel de Mestre, conduzindo aventuras com narrativa dinâmica e regras inspiradas em AD&D 2ª edição. O jogador toma decisões reais, rola dados com impacto mecânico genuíno e progride em campanhas persistentes — sem precisar de um grupo ou de um mestre humano.

## Pilares do Projeto

| Pilar | Descrição |
|---|---|
| **Narrativa por IA** | O Mestre gera a história de forma dinâmica, adaptando-se às escolhas do jogador |
| **Regras clássicas** | Sistema de combate, atributos e progressão inspirados em AD&D 2ª edição |
| **Interação real** | Rolagens de dados e decisões do jogador têm impacto direto no jogo |
| **Persistência** | Progresso salvo, permitindo retomar a aventura a qualquer momento |

## Estado Atual

| Módulo | Status | Observação |
|---|---|---|
| Sistema de combate | Implementado | Base funcional com rolagens e modificadores |
| Rolagem de dados | Implementado | Integrada ao fluxo de jogo |
| Persistência de progresso | Implementado | Salva estado da aventura |
| Criação de personagem | Implementado | Atributos, raça e classe |
| Regras do Mestre (`master.md`) | Ajustável | Configurável pelo usuário |
| Magia e habilidades especiais | Planejado | — |
| Sistema de inventário | Planejado | — |

## Como Jogar

1. Baixe o app na [Google Play](https://play.google.com/store/apps/details?id=com.bilbo.bilbomobile&hl=pt_BR).
2. Crie sua conta.
3. Crie seu personagem (escolha raça, classe e distribua atributos).
4. Insira sua [API key](https://platform.openai.com/account/api-keys) nas configurações.
5. Inicie a aventura.

> **Nota:** O DiceMind utiliza a API da OpenAI para gerar a narrativa. Você precisa de uma chave de API válida para jogar.

## Personalização do Mestre

O comportamento do Mestre pode ser ajustado editando o arquivo [`master.md`](master.md). Ele contém as instruções base que guiam o tom narrativo, nível de dificuldade e regras específicas da campanha.

Veja o arquivo para entender as opções disponíveis.

## Contribuindo

Contribuições são bem-vindas. Leia o [guia de contribuição](CONTRIBUTING.md) para saber como começar.

## Licença

Distribuído sob a licença MIT. Veja [LICENSE](LICENSE) para detalhes.
