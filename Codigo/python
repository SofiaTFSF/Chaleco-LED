# import usocket as socket
import socket
import machine, neopixel
import time
np = neopixel.NeoPixel(machine.Pin(27),60)

# Agregar nport de donde está el servidor TCP, en el ejemplo: 3000
serverAddressPort = socket.getaddrinfo('0.0.0.0', 3000)[0][-1]
# Cantidad de bytes a recibir
bufferSize  = 128

# Descomentar si el esp32 será una estación
# from wifiSTA import connectSTA as connect

# Descomentar si el esp32 estará en modo de acceso AP
from wifiAP import apConfig as connect

# poner acá el nombre de red ssid y password para conectarse
connect("ESP32LED", "87654321")

# Esta función es de ejemplo,
# Lo que se plantea acá es saber qué hacer con el dato recibido
# En el ejemplo solo se está imprimiendo por terminal
def exec(data):
    print(data)
    if data == b'A':
        # limpiar
        for i in range(60):
            np[i] = (0, 0, 0)
            np.write()
        time.sleep_ms(100)
        #SOS
        np[0]= (255,0,0)
        np[1]= (255,0,0)
        np[10]= (255,0,0)
        np[20]= (255,0,0)
        np[21]= (255,0,0)
        np[31]= (255,0,0)
        np[41]= (255,0,0)
        np[40]= (255,0,0)

        np[3]= (255,0,0)
        np[4]= (255,0,0)
        np[5]= (255,0,0)
        np[6]= (255,0,0)
        np[13]= (255,0,0)
        np[23]= (255,0,0)
        np[33]= (255,0,0)
        np[43]= (255,0,0)
        np[16]= (255,0,0)
        np[26]= (255,0,0)
        np[36]= (255,0,0)
        np[46]= (255,0,0)
        np[44]= (255,0,0)
        np[45]= (255,0,0)

        np[9]= (255,0,0)
        np[8]= (255,0,0)
        np[18]= (255,0,0)
        np[28]= (255,0,0)
        np[29]= (255,0,0)
        np[39]= (255,0,0)
        np[49]= (255,0,0)
        np[48]= (255,0,0)
        np.write()        
        print("ARRIBA")
    elif data == b'B':
        # limpiar
        for i in range(60):
            np[i] = (0, 0, 0)
            np.write()
        time.sleep_ms(100)
        for i in range(59):
            np[i]= (255,0,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (0,255,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (0,0,255)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (255,120,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (255,0,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (0,255,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (0,0,255)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (255,120,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (255,0,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (0,255,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (0,0,255)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (255,120,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (255,0,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (0,255,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (0,0,255)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (255,120,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (255,0,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (0,255,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (0,0,255)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (255,120,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (255,0,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (0,255,0)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (0,0,255)
            time.sleep_ms(5)
            np.write()
        for i in range(60):
            np[i]= (255,120,0)
            time.sleep_ms(5)
            np.write()
        np.write()
        print("Abajo")
    elif data == b'C':
        # limpiar
        for i in range(60):
            np[i] = (0, 0, 0)
            np.write()
        time.sleep_ms(100)
        # izquierda
        np[29]= (255,120,0)
        np[39]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[28]= (255,120,0)
        np[38]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[27]= (255,120,0)
        np[37]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[26]= (255,120,0)
        np[36]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[25]= (255,120,0)
        np[35]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[24]= (255,120,0)
        np[34]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[23]= (255,120,0)
        np[33]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[2]= (255,120,0)
        np[22]= (255,120,0)
        np[32]= (255,120,0)
        np[52]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[11]= (255,120,0)
        np[21]= (255,120,0)
        np[31]= (255,120,0)
        np[41]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[20]= (255,120,0)
        np[30]= (255,120,0)
        np.write()
        time.sleep_ms(200)
        # limpiar
        for i in range(60):
            np[i] = (0, 0, 0)
            np.write()
        time.sleep_ms(400)        
        print("Izquierda")
    elif data == b'D':
        # limpiar
        for i in range(60):
            np[i] = (0, 0, 0)
            np.write()
        time.sleep_ms(100)
        #derecha
        np[20]= (255,120,0)
        np[30]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[21]= (255,120,0)
        np[31]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[22]= (255,120,0)
        np[32]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[23]= (255,120,0)
        np[33]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[24]= (255,120,0)
        np[34]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[25]= (255,120,0)
        np[35]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[26]= (255,120,0)
        np[36]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[7]= (255,120,0)
        np[27]= (255,120,0)
        np[37]= (255,120,0)
        np[57]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[18]= (255,120,0)
        np[28]= (255,120,0)
        np[38]= (255,120,0)
        np[48]= (255,120,0)
        np.write()
        time.sleep_ms(100)
        np[29]= (255,120,0)
        np[39]= (255,120,0)
        np.write()
        time.sleep_ms(200)
        # limpiar
        for i in range(60):
            np[i] = (0, 0, 0)
            np.write()
        time.sleep_ms(400)
        print("Derecha")
    elif data == b'E':
        # limpiar
        for i in range(60):
            np[i] = (0, 0, 0)
            np.write()
        time.sleep_ms(100)
        np[3]=(255,0,0)
        np[4]=(255,0,0)
        np[5]=(255,0,0)
        np[6]=(255,0,0)
        np[12]=(255,0,0)
        np[16]=(255,0,0)
        np[17]=(255,0,0)
        np[21]=(255,0,0)
        np[25]=(255,0,0)
        np[28]=(255,0,0)
        np[31]=(255,0,0)
        np[34]=(255,0,0)
        np[38]=(255,0,0)
        np[42]=(255,0,0)
        np[43]=(255,0,0)
        np[47]=(255,0,0)
        np[53]=(255,0,0)
        np[54]=(255,0,0)
        np[55]=(255,0,0)
        np[56]=(255,0,0)
        np.write()
        print("Detener")
    else:
        print("Otra opcion")

sk = socket.socket()
sk.bind(serverAddressPort)
sk.listen(1)
print("Listening on: ", serverAddressPort)

while True:
    conn, addr = sk.accept()
    while True:
        data = conn.recv(bufferSize)
        # Si dato fue recibido, se decide que hacer con el.
        if data:
            exec(data)
            # Con la siguiente instruccion se pueden enviar datos al
            # dispositivo conectado
            conn.sendall("ok")
            # conn.send("ok")
    conn.close()
