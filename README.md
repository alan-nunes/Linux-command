

## Verificar Memória 


1. `free`
O comando free exibe informações sobre a memória total, usada, livre, buffers/cache, etc. Você pode usar a opção **-h** para ver os valores em um formato mais legível (como MB ou GB).
free -h
 
Isso irá mostrar algo como:
             total        usado        livre      compartilhado   buffers   cache   disponível
Mem:           16G          5G           8G            1.2G       200M    3.5G        9.5G
Swap:           2G          0G           2G
 
• Mem: Mostra a memória RAM.
• Swap: Mostra a memória de swap (caso esteja configurada).
• Disponível: Indica a quantidade de memória livre, levando em consideração o cache que pode ser liberado quando necessário.


2. Comando top
O comando top exibe uma visão dinâmica e em tempo real do uso de memória e outros recursos do sistema. Para verificar a memória, observe a parte superior da tela, onde está a linha "Mem".
top
 
A linha "Mem" mostrará o total de memória, a memória usada, a memória livre, e o cache.


3. Comando htop
Se você tiver o htop instalado, ele oferece uma interface mais amigável do que o top, com gráficos e uma visão mais clara da utilização da memória e do processador.
htop
 


4. Comando vmstat
O comando vmstat mostra informações detalhadas sobre o sistema, incluindo o uso de memória.
vmstat -s

 
Isso fornecerá uma saída com várias métricas, incluindo a memória livre.


5. Comando cat /proc/meminfo
Esse comando exibe um relatório detalhado sobre a memória do sistema.
cat /proc/meminfo
 

A saída fornecerá uma lista de valores, incluindo a memória total, livre, buffers, cache, e swap.
