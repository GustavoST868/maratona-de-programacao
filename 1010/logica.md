# Etapas do Programa

## 1. Receber os parâmetros via terminal

Os valores serão passados como argumentos ao executar o programa.

---

## 2. Converter os valores necessários para calcular o valor total e calcular o valor total a pagar

```c
float float_argv3 = atof(argv[3]);
float float_argv4 = atof(argv[4]);
float float_argv5 = atof(argv[5]);
float float_argv6 = atof(argv[6]);

float valor_a_pagar = float_argv3 * float_argv5 + float_argv4 * float_argv6;
```
---
##3. Mostrar a mensagem


```c
printf("\n\nCódigo peça 1: %s\nCódigo peça 2: %s\nQuantidades de peças 1: %s\nQuantidades de peças 2: %s\nValor da peça 1: R$%s.00\nValor da peça 2: R$%s.00\nValor total R$%.2f\n\n\n",argv[1],argv[2],argv[3],argv[4],argv[5],argv[6], valor_a_pagar);
```

