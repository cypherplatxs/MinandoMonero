# MinandoMonero

## Monero 
 
![Logo xmrig](https://s2.coinmarketcap.com/static/img/coins/200x200/328.png) 

[Monero](https://www.getmonero.org/) es una crypto divisa que entre sus caracteristicas más resaltantes está su opacidad en las transferencias y su facil acceso para minar.

### Crear una wallet 

El primer paso para minar cualquier crypto es tener una wallet o billetera en la que puedas reclamar las recompensas de tu minero, existen varias wallets que reciben monero como son 
- [exodus](https://www.exodus.com/) 
- [freewallet](https://freewallet.org/) 
- [trust](https://trustwallet.com/es/) 

Después de crear nuestra wallet podemos tener acceso a nuestra dirección para recibir monero

### obtener direccion para recibir monero

![recive monero](https://github.com/cypherplatxs/MinandoMonero/blob/main/pics%20monero/moneroenlinux.png)



 Cómo minar monero  por cpu ?
 
 


Vamos a la web de [xmrig](https://xmrig.com/) que es el minero que vamos a usar

Descargamos la versión para la plataforma que vamos usamos en la parte de [descargas](https://xmrig.com/download)

Ejeplo de como instalar en linux

~~~
wget https://github.com/xmrig/xmrig/releases/download/v6.15.2/xmrig-6.15.2-linux-x64.tar.gz
~~~

~~~
tar -xvf xmrig-6.15.2-linux-x64.tar.gz
~~~


~~~
cd xmrig-6.15.2/
~~~


Generamos el script desde la webde xmrig → [wizard](https://xmrig.com/wizard)


Vamos a nueva configuración, elegimos la pool donde estamos en este caso es minexmr en backends elegimos solo cpu  en misc lo que quieras donar al pool y luego obtienes el resultado  


luego en la terminal donde descargamos el minero ejecutamos la linea que suelta el script 


el resultado para linux por ejemplo es 


~~~
sudo ./xmrig -o us-west.minexmr.com:443 -u MIIDDELAWALLET -k --tls --rig-id mineroDONALEX
~~~








