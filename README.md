# Ifes - Instituto Federal do Espírito Santo --- Mestrado em Computação Aplicada

## Teoria da Computação --- 2022/2

**Autor:** Thadeu Pezzin Melo

### Problema 6

Utilizando uma linguagem de programação que tenha a construção lambda, i.e., definição de funções anônimas, implemente as funções dadas no Problema 5. Sua implementação deve ser o mais próxima do Cálculo 𝜆 que a linguagem em questão permitir.

(d) REVERSE — recebe uma lista e retorna a lista invertida.

**Implementação**
###### Local do arquivo: ###### 
/trab1/src/probl6c/exercicio6reverse.clj


```python
(defn reverselst
  ([arglist]
   (println (reverse arglist)))
  )

(reverselst [1 2 3 4 5])
```

**Implementação**

Implementação em Clojure de uma função chamada reverselst que recebe uma lista e retorna os valores na ordem inversa que recebeu. Utilizei a função reverse para realizar a atividade. 

**Execução**

Para implementar e rodar a função eu utilizei o IntelliJ, que adiciona na primeira linha o namespace. Eu retirei esse namespace para enviar o arquivo "clj", pois sei que você provavelmente rodará o código no EMACS.