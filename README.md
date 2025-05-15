# Pilhas.py
Training Stack 
def inverter_pilha(pilha_original):
  """Inverte a ordem dos elementos de uma pilha.

  Args:
      pilha_original: A pilha a ser invertida (lista em Python).

  Returns:
      Uma nova pilha com os elementos invertidos.
  """
  pilha_invertida = []
  while pilha_original:
      pilha_invertida.append(pilha_original.pop())
  return pilha_invertida

# Exemplo de uso:
pilha = [1, 2, 3, 4, 5]
pilha_invertida = inverter_pilha(pilha)
print(pilha_invertida)
