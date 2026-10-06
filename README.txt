Marcos Carmona Cáceres
29

# Safe Zone - Proyecto de Desarrollo

## git initDescripción de la Aplicación
Safe Zone es una aplicación destinada al seguimiento y protección de sus usuarios durante las 24 horas del día, los 7 días de la semana[cite: 5]. El sistema integra funciones de comunicación como chats y llamadas, junto con mapas interactivos[cite: 5]. Todo ello se presenta bajo una interfaz totalmente configurable adaptada a los gustos del usuario[cite: 5].

## Objetivos
* El objetivo principal es conocer la ubicación y el estado del usuario en todo momento[cite: 5].
* Permite localizar al menor de manera instantánea, otorgando una ventaja crucial para actuar ante posibles conflictos o situaciones de peligro[cite: 5].
* Brinda seguridad y tranquilidad a los padres sobre el estado de sus hijos[cite: 5].

## Roles y Usuarios Principales
* **Padre (Usuario Administrador):** Posee control total sobre ambas partes de la aplicación[cite: 5]. Puede visualizar la ubicación de sus hijos y emplear todas las funcionalidades en cualquier momento[cite: 5].
* **Hijo (Usuario Receptor):** Es supervisado por el usuario administrador y cuenta con funciones limitadas según la configuración establecida por este último[cite: 5].
* **Otros usuarios potenciales:** La aplicación también puede ser utilizada por personas mayores con pérdida de memoria, personas con indicios de depresión o jóvenes que transitan zonas peligrosas[cite: 3].

## Plataformas Soportadas
* Dispositivos móviles (Android e iOS)[cite: 5].
* Tablets (Android e iPad)[cite: 5].
* Ordenadores portátiles y de sobremesa (Windows, Linux, MacOS)[cite: 5].
* Relojes inteligentes[cite: 5].
* Plataformas web[cite: 5].

## Requisitos del Sistema

### Requisitos Funcionales
* El producto se divide en dos aplicaciones distintas enfocadas a cada tipo de usuario (padres e hijos), donde la aplicación del padre ejerce el control total sobre la del hijo[cite: 6].
* Permite la visualización de la ubicación en tiempo real, integrando opciones para enviar avisos, realizar llamadas o chatear con el usuario[cite: 6].
* Ofrece la capacidad de rastrear la ubicación de más de un usuario de forma simultánea[cite: 6].
* Incluye un mapa interactivo para marcar destinos seguros y zonas de peligro, enviando alertas tanto al menor si se acerca a estas áreas, como a los padres si se adentran en ellas[cite: 6].
* Dispone de un botón de SOS, activable desde la interfaz o mediante una combinación de teclas, para alertar inmediatamente a los padres[cite: 6].
* Los administradores tienen acceso a la interfaz del menor siempre que lo deseen[cite: 4].

### Requisitos No Funcionales
* Cuenta con una interfaz limpia, de fácil manejo y configurable según las preferencias de los usuarios[cite: 6].
* La aplicación estará totalmente personalizada y detallada según las características propias y el sector al que pertenezca el usuario[cite: 6].
* Exige una integración multiplataforma para abarcar el mayor número de opciones posibles de visualización y control[cite: 6].
* Requiere que los datos estén totalmente encriptados para garantizar la privacidad absoluta de la información[cite: 7].
* Necesita un servidor confiable con una disponibilidad del 99,9% anual, asegurando la ausencia de retrasos en las alertas de SOS o en la actualización de las ubicaciones[cite: 7].

## Metodología de Desarrollo
El proyecto se desarrollará siguiendo el modelo ágil, concretamente bajo el marco de Scrum[cite: 3, 5]. Esta metodología resulta óptima para este caso debido a que permite estructurar el desarrollo en pequeñas fases, lo cual es ideal para facilitar su salida al mercado en un sector con poca competencia[cite: 3]. Además, el modelo ágil ayuda a comprender y adaptarse continuamente a las necesidades del usuario, reforzando las características críticas de seguridad y seguimiento continuo que promete la aplicación[cite: 3, 5].
