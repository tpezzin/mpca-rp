# Ifes - Instituto Federal do Espírito Santo --- Mestrado em Computação Aplicada

## Teoria da Computação --- 2022/2

**Autor:** Thadeu Pezzin Melo

### Problema 6

Utilizando uma linguagem de programação que tenha a construção lambda, i.e., definição de funções anônimas, implemente as funções dadas no Problema 5. Sua implementação deve ser o mais próxima do Cálculo 𝜆 que a linguagem em questão permitir.

(c\) APPEND — recebe duas listas e retorna a concatenação destas duas listas.

**Implementação**
###### Local do arquivo: ###### 
/trab1/src/probl6c/exercicio6append.clj


```python
(defn appendlst
  ([arglist1 arglist2]
   (println (concat arglist1 arglist2)))
  )
(appendlst [1 2 2] [3 3 4 5])
```

**Implementação**

Implementação em Clojure de uma função chamada appendlst que recebe duas listas e retorna a concatenação da primeira com a segunda. Utilizei a função concat para realizar a atividade, ela recebe como parâmetro a primeira e a segunda lista, concatenando a segunda na primeira. 

**Execução**

Para implementar e rodar a função eu utilizei o IntelliJ, que adiciona na primeira linha o namespace. Eu retirei esse namespace para enviar o arquivo "clj", pois sei que você provavelmente rodará o código no EMACS.