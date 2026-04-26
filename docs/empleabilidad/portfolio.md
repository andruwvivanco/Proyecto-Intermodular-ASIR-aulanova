# Portfolio de Evidencias Técnicas

En este apartado presento el avance real del proyecto "Aulanova" a fecha de finales de abril. Actualmente, el trabajo se centra en la **Fase de Diseño Físico y Distribución de Infraestructura**.

### 1. Diseño de la Topología Física (Cisco Packet Tracer)

A continuación, muestro la captura de pantalla del diseño físico realizado en Packet Tracer. He decidido empezar por esta vista para asegurar que el despliegue en el centro de formación sea realista y eficiente antes de pasar a la configuración lógica.

<img width="1919" height="1079" alt="captura avance de packet tracer" src="https://github.com/user-attachments/assets/acce34c3-ab95-4eb4-b41a-3201fa6621f7" />


### 2. Análisis del diseño actual
Como se puede observar en el plano, he distribuido el centro en cuatro áreas clave:
* **Aula Informática:** Diseñada para albergar los 20 puestos de alumnos, garantizando espacio suficiente para el cableado y la comodidad del aprendizaje.
* **Cuarto Técnico / Rack:** He ubicado el rack en una sala independiente para centralizar el switch, el router y los servidores, asegurando la climatización y seguridad del hardware crítico.
* **Recepción y Administración:** Puestos independientes para la gestión del centro.
* **Despacho de Dirección:** Conectado a la red principal para la supervisión del sistema.

### 3. Estado del proyecto y próximos pasos
Aunque en esta captura los equipos están ubicados físicamente, todavía no se ha procedido al cableado lógico ni a la asignación de direccionamiento IP. He preferido validar primero que la distribución física cumple con las necesidades de espacio y ergonomía del centro. Los próximos pasos serán:
1. Realizar el cableado estructurado entre el rack y las diferentes salas.
2. Definir las VLANs para segmentar el tráfico de alumnos y administración.
3. Configurar el direccionamiento IP estático para los servidores y dinámico (DHCP) para los puestos del aula.

### Aprendizaje técnico
Desarrollar este plano me ha enseñado que la administración de sistemas no solo ocurre dentro de la pantalla; la ubicación física de los equipos influye directamente en el rendimiento de la red y en la facilidad para realizar mantenimientos futuros.
