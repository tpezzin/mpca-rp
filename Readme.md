# Ifes - Instituto Federal do Espírito Santo --- Mestrado em Computação Aplicada

## Teoria da Computação --- 2022/2

**Autor:** Thadeu Pezzin Melo

### Problema 1

Escreva um programa de computador 𝑃,&nbsp;não vazio, cuja saída seja ⟨𝑃 ⟩⟨𝑃 ⟩, &nbsp;ou seja, o próprio código fonte de 𝑃 &nbsp; impresso duas vezes em seguida. O programa 𝑃 &nbsp;pode ser implementado na sua linguagem de programação favorita, desde que ela seja livre e disponível para Ubuntu Linux nos repositórios oficiais.

**Resolução**

```python
def main():
    codigo = open(__file__).read()
    print(f"{codigo}\n" * 2)

if __name__ == "__main__":
    main()
```

**Implementação**

O código acima está contido no arquivo problema1.py, que ao ser executado chama a função "main" direcionando assim a execução do programa. A funcão "main" lê o arquivo indicado pela variável especial "\__file__", que foi utilizada, nesse caso, para retornar o caminho exato do próprio arquivo fonte. Com o conteúdo do programa atribuído à variável "codigo", a string é impressa duas vezes na linha posterior. 

**Execução**

Para rodar o programa basta executar o arquivo problema1.py através de uma IDE Python de desenvolvimento ou pela linha de comando de seu computador indicando, por exemplo, ao python3 sua localização sem a necessidade de passar parâmetros. O código abaixo será exibido:

```
def main():
    codigo = open(__file__).read()
    print(f"{codigo}\n" * 2)

if __name__ == "__main__":
    main()
def main():
    codigo = open(__file__).read()
    print(f"{codigo}\n" * 2)

if __name__ == "__main__":
    main()

```