Эксперимент с уменьшением learning rate до 1e-4:  
<https://colab.research.google.com/drive/1vyu22yXuQDqL3OzRSwW7qLW2BRh3Cpxv?usp=sharing>  
Результат получился странный, не похожий ни на аналитическое решение, ни на константу. При этом условия уравнения выполняются со следующей точностью: MSE_f_u = 1.516322e-03; MSE_f_v = 1.827779e-03

<img src="https://github.com/mikhakuv/PINNs/blob/main/exp8_results_u.PNG" width="450" height="800"><img src="https://github.com/mikhakuv/PINNs/blob/main/exp8_results_v.PNG" width="450" height="800">  

Есть версия, что с таким низким learning rate оптимизатор просто не успел нормально подобрать веса и остановился на iter 50000