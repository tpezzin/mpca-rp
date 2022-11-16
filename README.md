# Ifes - Instituto Federal do Espírito Santo --- Mestrado em Computação Aplicada

## Teoria da Computação --- 2022/2

**Autor:** Thadeu Pezzin Melo

### Problema 6

Utilizando uma linguagem de programação que tenha a construção lambda, i.e., definição de funções anônimas, implemente as funções dadas no Problema 5. Sua implementação deve ser o mais próxima do Cálculo 𝜆 que a linguagem em questão permitir.

(b) MAX — recebe uma lista de números e retorna o maior deles.

**Implementação**
###### Local do arquivo: ###### 
/trab1/src/probl6b/exercicio6max.clj


```python
(defn maxlst
  ([arglist]
   (if (empty? (rest arglist))
     (println (first arglist))
     (maxlst (rest arglist) (first arglist))
     ))

  ([arglist m]
   (if (empty? arglist)
     (println m)
     (let [i (first arglist)]
       (if (< i m)
         (recur (rest arglist) m)
         (recur (rest arglist) i)
         )
       )
     )
   )
  )

(maxlst [10 20 6 9 5 ])
```

**Implementação**

Implementação em Clojure de uma fução chamada maxlst que recebe uma lista e retorna seu maior número por meio de uma recursão que valida se o primeiro elemento é maior do que o restante da lista. Sempre que um elemento maior é identificado, ele é passado por parâmetro para a recursão utiliza-lo como sendo o maior, e assim, compara-lo com os demais. 

**Execução**

Para implementar e rodar a função eu utilizei o IntelliJ, que adiciona na primeira linha o namespace. Eu retirei esse namespace para enviar o arquivo "clj", pois sei que você provavelmente rodará o código no EMACS.