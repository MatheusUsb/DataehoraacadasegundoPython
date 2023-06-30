# DataehoraacadasegundoPython
# Você pode executar este script em um ambiente Python para ver a impressão contínua da data e hora

import datetime
import time

def data_hora_extenso():
    while True:
        agora = datetime.datetime.now()
        data_extenso = agora.strftime("%d de %B de %Y")
        hora_extenso = agora.strftime("%H:%M:%S")
        print(f"Agora é {hora_extenso} do dia {data_extenso}")
        time.sleep(1)

data_hora_extenso()

