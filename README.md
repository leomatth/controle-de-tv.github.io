# Simulador de Televisor e Controle Remoto em Python

Este projeto é uma simulação simples de um televisor e um controle remoto, implementada em Python. Ele permite simular ações como aumentar/diminuir o volume, trocar e sintonizar canais em um televisor.

## Funcionalidades

- `Televisor`: Representa um televisor, mantendo informações como fabricante, modelo, volume atual, canal atual e lista de canais disponíveis.
- `ControleRemoto`: Permite a interação com o objeto `Televisor`, como aumentar e diminuir o volume, trocar e sintonizar canais.

## Como Usar

Para usar esta simulação, você precisará criar instâncias da classe `Televisor` e da classe `ControleRemoto`. 

Exemplo de uso:

```python
tv = Televisor("Samsung", "Modelo123")
controle = ControleRemoto(tv)

# Sintonizar um canal
controle.sintonizaCanal(5)

# Trocar para o canal sintonizado
controle.trocaCanal(5)

# Aumentar o volume
controle.aumentaVolume()

# Diminuir o volume
controle.diminuiVolume()
