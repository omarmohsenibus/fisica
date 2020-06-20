# Forza elastica: Pendolo

Il moto di un pendolo può essere ricondotto al moto causata da una forza elastica e quindi avere una relazione con la legge di Hooke.

Un pendolo è formato da un disco di massa m attaccato ad un'asta di massa trascurabile fissata all'estremo opposto al punto. Il disco viene posizionato ad un angolo $\theta$ rispetto alla verticale e poi lasciato libero di muoversi con attrito trascurabile

Abbiamo scelto il sistem di riferimento xz

!["pendolo"](/immagini/pendolo.png)

In assenza di attrito, l'unica forza che interagisce in questo sistema è la forza di gravità che mette in moto il corpo secondo una traiettoria semi circolare.

> $\vec F_p = -mg\vec k$


#### Caratteristiche pendolo:
- $l$: lunghezza dell'asta rigida e di massa trascurabile
- $z$: asse che rappresenta la verticale
- $\theta$: angolo che il corpo forma con l'asse verticale
- $m$: massa del corpo
- $\hat r$: versore che da la direzione dell'asta del pendolo
- $\vec F_\bot$: componente perpendicolare a $\hat r$
- $\vec F_\parallel$: componente parallela a $\hat r$ 
- $\vec F_p = \vec F_\bot + \vec F_\parallel$

> La componente parallela tenderebbe a allungare l'asta del pendolo poiche l'asta è rigida allora questa componente viene totalemente annulata dalla reazione vincolare dell'asta.

> La componente perpendicolare è punto per punto tangente alla circonferenza descritta dal pendolo avente raggio l'asta di lunghezza $l$ $(R)$ raggio

## Studio cinematico
### Calcoliamo il vettore posizone
Parametrizziamo il vettore posizione in funzione dell'angolo $\theta$

$\vec r = (lsin\theta, 0, -lcos\theta) = l\hat r $

dove $\hat r$ è il versore
$\hat r = sin\theta\hat i - cos\theta\hat k$

### Calcoliamo il vettore velocità istantanea

l'unica cosa che varia rispetto al tempo è l'angolo $\theta$

$\vec v = \frac {d\vec r}{dt} = lcos\theta\frac {d\theta}{dt}\hat i + l sin\theta \frac {d\theta}{dt}\hat k = l\frac {d\theta}{dt} \hat v$

dove $\hat v$ è il versore
$\hat v = (lsin\theta, 0, lcos\theta) = l\hat r $

### Calcoliamo il vettore accelerazione istantanea

$\vec a = \frac {d\vec v}{dt} = \frac {d^2\vec r}{dt^2}$

$\vec a = -lsin\theta(\frac {d\theta}{dt})^2 \hat i + lcos\theta \frac {d^2 \theta}{dt^2} \hat i+lcos\theta(\frac {d\theta}{dt})^2 \hat k + lsin\theta \frac {d^2 \theta}{dt^2} \hat k $

$\vec a = -l(\frac {d\theta}{dt})^2\hat r + l\frac {d^2 \theta}{dt^2}\hat v$

Il primo termine della somma è chiamata **accelerazione centripeta**
Il secondo termine è diverso da zero se vi è un effettivo cambiamento instantaneo della velocita del corpo.

$Se$ $\vec v = l\frac {d\theta}{dt}=l\omega = cost$
$Allora$ $\vec a = -l\omega^2\hat r = -\frac {v^2}{l}\hat r$

$\omega = \frac {d\theta}{dt}=\frac {1}{l}\frac {ds}{dt} = \frac {v}{l}$ $(velocità$ $angoloare)$

Per mantenersi lungo una traiettoria circolare di raggio $l$ un corpo di massa $m$ deve neccessariamente accelerare anche se la sua velocità $v = l\omega$ è **costante**.L'accelerazione necessaria per mantenersi su un 'orbita circolare si chiama ACCELERAZIONE CENTRIPETA ed è diretta lungo il vettore raggio posizione.

## Studio dinamico

La $\vec f_p = -mg\hat k$ è scomponibile in due componenti:
- la prima $\vec f_\bot =-mgcos\theta $ è quella che imprime il movimento al corpo.
- la seconda $\vec F_\parallel = -mgsin\theta$ è uguale a zero poichè viene annullata dalla reazione vincolare dell'asta poichè è rigida

Nella direzione $\hat v$ il sistema è invece completamente libero di muoversi sotto l'azione della componente perpendicolare della $\vec f_p$ secondo il secondo principio della dinamica.

$Ovvero: \vec F = m\vec a \Rightarrow \vec F_\bot = m\vec a_\bot$

$e$ $siccome$ $\vec a = \vec a_c + \vec a_t$
Quindi scriviamo l'equazione differenziale del secondo ordine :
$$ml(\frac {d\theta}{dt})^2\hat v = -mgsin\theta\hat v$$

$$l\frac {d^2 \theta}{dt^2}=-gsin\theta$$

**Bisogna trovare la soluzione all'equazione**
Supponiamo di lasciare liberare la massa $m$ a partire dall'angolo $\theta_0 << 1$