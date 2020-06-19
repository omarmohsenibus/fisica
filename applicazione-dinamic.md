# Applicazione dei principi della dinamica

## Forza nulla: moto rettilineo uniforme

Supponiamo che un corpo di massa m non sia soggetto a forze, oppure che la risultante della forza
a cui è sottoposto sia nulla, vogliamo determinare la sua velocità e la sua posizione nel tempo.

Applico il secondo principio della dinamica

> $\vec F = m\vec a$

siccome la forza è nulla

> $m\vec a = 0$

per definizione di accelerazione istantanea vettoriale

> $\vec a = \frac {d\vec v}{dt}$

Quindi:

> $m\frac {d\vec v}{dt} = 0$

Nelle varie componenti cartesiane

> $m(\frac {dv_x}{dt}, \frac {dv_y}{dt}, \frac {dv_z}{dt}) = (0, 0, 0)$


$\frac{dv_x}{dt} = 0 \to v_x = cost$$\Rightarrow$ $v_x = v_x(t_0)$

$\frac{dv_x}{dt} = 0 \to v_y = cost$$\Rightarrow$ $v_y = v_y(t_0)$

$\frac{dv_x}{dt} = 0 \to v_z = cost$$\Rightarrow$ $v_z = v_z(t_0)$

Queste sono tre equazioni differenziali di primo grado per
essere risolte devono essere completato da una condizione al 
contorno.

In questo caso bisogna conosce la componenti della velocità al 
tempo $t_0$

### Ricaviamo la legge oraria

Sfruttiamo la relazione tra la velocità vettoriale e il vettore posizone

Siccome

> $\vec v = \frac {d\vec r}{dt}$

allora le sue componenti cartesiane:

$v_x = v_x(t_0) \Rightarrow \frac {dx}{dt} = v_x(t_0) $

$v_y = v_y(t_0) \Rightarrow \frac {dy}{dt} = v_y(t_0) $

$v_z = v_z(t_0) \Rightarrow \frac {dz}{dt} = v_z(t_0) $

Dunque risolviamo le equazioni differenziali:

$x(t) = v_x(t_0)t + x(t_1)$
$y(t) = v_y(t_0)t + y(t_1)$
$z(t) = v_z(t_0)t + z(t_1)$

con in generale $t_0 \neq t_1 $

Sono funzioni lineari nel tempo, quindi sono rette

### Grafici del moto rettilineo uniforme

da fare

## Forza costante: moto uniformemente accelerato

Supponiamo che un corpo di massa m sia soggetto ad una forza costante,
vogliamo determinare la sua velocità e la sua posizone nel tempo

Applico il secondo principio della dinamica

> $\vec F = m\vec a$

siccome la forza è costante

> $m\vec a = \vec C$

per definizione di accelerazione istantanea vettoriale

> $\vec a = \frac {d\vec v}{dt}$

Quindi:

> $m\frac {d\vec v}{dt} = \vec C$

Nelle varie componenti cartesiane

> $m(\frac {dv_x}{dt}, \frac {dv_y}{dt}, \frac {dv_z}{dt}) = (C_x, C_y, C_z)$


$\frac{dv_x}{dt} = \frac{C_x}{m} \to v_x = cost$ $\Rightarrow$ $v_x = \frac{C_x}{m} + v_x(t_0)$

$\frac{dv_x}{dt} = \frac{C_y}{m} \to v_y = cost$ $\Rightarrow$ $v_y = \frac{C_x}{m} + v_y(t_0)$

$\frac{dv_x}{dt} = \frac{C_z}{m} \to v_z = cost$ $\Rightarrow$ $v_z = \frac{C_x}{m} + v_z(t_0)$


Queste sono tre equazioni differenziali di primo grado per
essere risolte devono essere completato da una condizione al 
contorno.

Condizione al contorno (velocità vettoriale all'istante $t_0$)
> $\vec v(t_0) = (v_x(t_0), v_y(t_0), v_z(t_0))$


La velocità di un corpo di massa m soggetto ad una forza costante aumenta linearmente con il tempo

### Ricaviamo la legge oraria

Sfruttiamo la relazione tra la velocità vettoriale e il vettore posizone

Siccome

> $\vec v = \frac {d\vec r}{dt}$

allora le sue componenti cartesiane:

$v_x = \frac{C_x}{m}t + v_x(t_0) \Rightarrow \frac {dx}{dt} = \frac{C_x}{m}t + v_x(t_0) $

$v_y = \frac{C_y}{m}t + v_y(t_0) \Rightarrow \frac {dy}{dt} = \frac{C_x}{m}t + v_y(t_0) $

$v_z = \frac{C_z}{m}t + v_z(t_0) \Rightarrow \frac {dz}{dt} = \frac{C_x}{m}t + v_z(t_0) $

Dunque risolviamo le equazioni differenziali:

$x(t) = \frac {1}{2} \frac{C_x}{m}t^2 + v_x(t_0)t + x(t_1)$

$y(t) = \frac {1}{2} \frac{C_x}{m}t^2 + v_y(t_0)t + y(t_1)$

$z(t) = \frac {1}{2} \frac{C_x}{m}t^2 + v_z(t_0)t + z(t_1)$

con in generale $t_0 \neq t_1 $

Lo spazio percorso dal corpo di massa m soggetto ad una forza costante aumenta quadraticamente con il tempo

### Esempio: caduta di un grave

Supponiamo di lasciare cadere da fermo un corpo di massa m da un'altezza h, vogliamo determinare il tempo di caduta in assenza di attrito.

![caduta grave](/immagini/caduta-grave.png)

La forza di gravità supponiamo agisca su l'asse z:

$\vec F = \vec C$ dove $\vec C = -mg\vec k = (0, 0, mg)$

Le condizioni al contorn del problemo sono:

> $\vec r(t_0) = (0, 0, h)$

Allora riscriviamo la legge oraria del moto:

$x(t) = \frac {1}{2} \frac{C_x}{m}t^2 + v_x(t_0)t + x(t_0)$ $\Rightarrow x = x(t_0)$

$y(t) = \frac {1}{2} \frac{C_x}{m}t^2 + v_y(t_0)t + y(t_0)$ $\Rightarrow y = y(t_0)$

$z(t) = \frac {1}{2} \frac{C_x}{m}t^2 + v_z(t_0)t + z(t_0)$ $\Rightarrow z = -\frac{g}{2}t^2 + h$

Il corpo di massa m raggiungerà il suolo quando sarà nella posizone $\vec r(t) = (0, 0, 0) $


0 = $-\frac{g}{2}t^2 + h$ $\rightarrow$ $ t = \sqrt{\frac {2h}{g}} $

In condizione di attrito trascurabile, il tempo di caduta di un corpo non dipende dalla sua massa.
