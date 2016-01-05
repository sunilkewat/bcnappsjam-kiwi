Objetivo

La aplicación de este proyecto tiene el objetivo de que las personas que tienen que permanecer en un cola para acceder a un trámite administrativo, servicio público, institución cultural, atracción turística, etc, en espera de su turno, puedan aprovechar ese tiempo para realizar otro actividad.
Implantación del sistema

La aplicación está pensada para funcionar con el sistema, “análogico”, actual de colas, es decir que podría implantarse en estos momentos y los usuarios con posesión de un smartphone podrían hacer utilización de la aplicación y disfrutar de su servicio, en el caso que el usuario no tuviese un smartphone seguiría realizando la cola, obtención de un ticket impreso, tal y como se realiza actualmente, así que la tecnología no excluye a ningún ciudadano.

La aplicación requiere una comunicación con el servidor de gestión de la cola; aunque esto implica que el usuario tiene que tener una acceso a un conexión a Internet, no consideramos que esto sea un impedimento porque casi todos los usuario de un smartphone tiene contratada una tarifa de datos con uno de los operadores móviles, además de cada vez más núcleos de población ofrecen conexiones Wifi gratuitas.
Tecnología

Obtención de ticket

La aplicación ofrece dos posibilidades para la obtención del “ticket virtual”, de dos maneras:

**NFC**. Se condiera que el funcionamiento con esta tecnología sería el caso ideal, pero debido a que la gama de smartphones que incluyen está tecnología es muy reducida y poco accesible por cualquier usuario, se ha considera añadir la opción mencionada a continuación.

**Códigos QR**. Esta tecnología, es muy utilizada para la captura de datos desde los smartphone; podriamos decir que es una tecnología implementada en la mayoría de smartphones y que está al alcance de casi cualquier ciudadano en posesión de un smartphone.


Idenpendientemente de la tecnología utilizada para la obtención del ticket, el objetivo es que el ticket ya no se obtiene físicamente, ya que al estar registrado en el dispositivo y ser accesible al número que se ha asignado, entonces no es necesario.

Obtención de información

La aplicación necesita la obtención de información del servidor que gestiona la cola a la que se va a poner a la espera.

Necesita obtener inicialmente:
El turno que le corresponde al usuario.
El turno actual.
El tiempo estimado hasta su turno.


Cuando el usuario obtiene su turno, la aplicación registra el dispositivo para posteriormente mantenerle informado mediante notificaciones _push_ del turno actual y el del tiempo estimado (se considera que el servidor es capaz de dar estimaciones más precisas que las que puede realizar el propio dispositivo).

Situaciones identificadas donde la aplicación sería de gran utilidad

Ciudadano que debe realizar un trámite con algún órgano administrativo.

Durante el tiempo que transcurre su turno podría realizar otras actividades que le permitiesen optimizar el tiempo en vez de tener que estar esperando en la propia sede administrativa su turno; las activades podrían ser muy diversas, por ejemplo, realizar otro trámite administrativo, realizar actividades profesionales, etc.
Ciudadano o turista que va a visitar institución cultural, atracción turística u servicio público de ocio.

Las personas que van a realizar este tipo de actividades tendrán la sensación de disfrutar mucho más el tiempo de ocio que están pasando porque estaría disfrutando ese tiempo de espera dando una vuelta por los alrededores, tomando un refrigerio, etc; además debido a que el tiempo de espera las personas no tiene que estar físicamente en la cola, es un tiempo que potenciaría el consumo en los negocios cercanos y así favorecer la actividad económica de la zona.

Ganancias de la aplicación sobre el sistema actual

Libera al usuario de tener que permanecer físicamente en la cola.
Evita la pérdida del ticket que identifica su turno.
Avisa al usuario cuando quedan, un número de turnos configurable, antes del suyo, disminuyendo las posibilidades de que se le pase.


NOTA: Este texto también lo puedes encontrar en un documento público, en: https://docs.google.com/document/d/1YI5teqaUPXozTN3ZaAd443zgua-c-aarIDwEs4Im08w/edit