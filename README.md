# posicion_sol
Programa para calcular la posición del sol
# Programa para el ca'lculo de la posici'on solar

Datos de entrada

* d'ia del año
* latitud, longitud
* hora (con tiempo est'andar) (vector): calcular para cada hora del dia
* zona horaria (verano s/n)

datos de salida

* declinaci'on
* duración del d'ia
* horas de amanecer y ocaso en tiempo estandar
* posici'on del sol: altura/elevaci'on, azimut, 'angulo cenital

Gr'aficas: 'angulos en funci'on de la hora

Trabajo en equipo 

validar con otros programas

ecs

declinaci´on

delta = 0.4093 * np.sin(2 * pi * (284 + N) / 365)

latitud 

phi = arg de una func

longitud local

L_loc = 

longitud de referencia 

L_zh

omega = 15 * (t_sol - 1)

t_sol = t_est + (L_loc - L_zh) / 15 + C_1 + E_t / 60

horario de verano C_1

E_t = 9.87 * np.sin(2 * B) - 7.53 * np.cos(B) - 1.5 * np.sin(B)

B = (N - 81) * 360 / 364

t_d = 24 * omega_o / pi

omega_o = arccos(-tan(delta)*tan(phi))

usuario

N =

phi =

L_loc =

L_ref = 

zona horario C_1

t_est =
