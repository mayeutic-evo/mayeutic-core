DECISION TABLES v1
Mayeutic Core
________________________________________
🧠 TABLA CORE 1 — Intervenir o no (D1)
Repetición	Carga percibida	Impacto	Contexto	Decisión
baja	baja	bajo	estable	no intervenir
media	baja	medio	estable	esperar
media	media	medio	estable	intervenir
alta	media	alto	estable	intervenir
alta	alta	alto	inestable	intervenir
baja	alta	bajo	inestable	esperar
________________________________________
🧠 TABLA CORE 2 — Nivel de intervención (D2)
Estado	Ruido	Ambigüedad	Nivel
claro	bajo	baja	mínima
activo	medio	baja	media
cargado	alto	media	mínima
saturado	alto	alta	pedir validación
crítico	medio	baja	alta
Regla fija:
Más ruido ≠ más intervención.
________________________________________
🧠 TABLA CORE 3 — Prioridad (D3)
Urgencia	Impacto	Repetición	Prioridad
alta	alta	alta	inmediato
alta	media	media	próximo
media	media	baja	postergable
baja	baja	baja	descartable
________________________________________
🧠 TABLA CORE 4 — Agrupar vs Separar (D4)
Similitud	Distancia temporal	Fuente	Acción
alta	cercana	múltiple	agrupar
alta	lejana	múltiple	agrupar
baja	cercana	única	separar
baja	lejana	única	ignorar
________________________________________
🧠 TABLA CORE 5 — Escalar o Contener (D5)
Impacto	Afectados	Persistencia	Acción
bajo	individual	baja	contener
medio	individual	media	observar
medio	colectivo	alta	escalar
alto	colectivo	alta	escalar
alto	institucional	media	escalar
________________________________________
🧠 TABLA CORE 6 — Cierre de ciclo (D6)
Estado	Actividad reciente	Impacto	Acción
activo	sí	medio	mantener
activo	no	bajo	cerrar
crítico	no	bajo	cerrar
resuelto	no	bajo	archivar
________________________________________
🧠 TABLA CORE 7 — Validación humana (D7)
Ambigüedad	Riesgo	Confianza	Acción
baja	bajo	alta	ejecutar
media	medio	media	sugerir
alta	alta	baja	pedir validación
________________________________________
🧠 TABLA CORE 8 — Memoria (D8)
Frecuencia	Predictibilidad	Sensibilidad	Acción
alta	alta	baja	guardar automático
media	media	baja	resumir
baja	baja	media	pedir confirmación
baja	baja	alta	no guardar
________________________________________
🧠 TABLA CORE 9 — Dominios activos (D9)
Dominio	Responsabilidad declarada	Acción
hijos	sí	habilitar
hijos	no	ocultar
animales	sí	habilitar
animales	no	ocultar
vehículo	sí	habilitar
vehículo	no	ocultar
________________________________________
DECISION TABLES — BASYCO v1
________________________________________
🧍 TABLA B1 — Estado personal
Responsabilidades	Postergaciones	Ritmo	Estado
pocas	bajas	estable	claro
medias	medias	estable	cargado
muchas	altas	inestable	saturado
muchas	altas	crítico	desbordado
________________________________________
🧍 TABLA B2 — Intervención Basyco
Estado	Acción
claro	mostrar resumen
cargado	sugerir prioridad
saturado	reducir input
desbordado	alerta + validación
________________________________________
🧍 TABLA B3 — Automatización
Tipo	Repetición	Acción
mantenimiento	anual	automatizar
salud	periódica	automatizar
financiero	mensual	automatizar
sensible	irregular	confirmar
________________________________________
🧍 TABLA B4 — Resumen diario
Actividad	Estado	Acción
completadas	sí	reforzar
pendientes	pocas	reordenar
pendientes	muchas	reducir
ninguna	—	no intervenir
________________________________________
DECISION TABLES — NUKLEO v1
________________________________________
🏘️ TABLA N1 — Estado de problemática
Reportes	Intenciones	Persistencia	Estado
pocos	bajos	baja	latente
medios	medios	media	visible
altos	altos	media	sensible
altos	muy altos	alta	crítico
________________________________________
🏘️ TABLA N2 — Visibilidad
Estado	Acción
latente	baja visibilidad
visible	visibilidad media
sensible	visibilidad alta
crítico	máxima visibilidad
________________________________________
🏘️ TABLA N3 — Debate
Intenciones	Diversidad	Acción
bajas	baja	no abrir
medias	media	abrir
altas	alta	abrir
muy altas	alta	escalar
________________________________________
🏘️ TABLA N4 — Escalamiento institucional
Estado	Evidencia	Acción
sensible	baja	esperar
crítico	media	escalar
crítico	alta	escalar
________________________________________
🏘️ TABLA N5 — Archivo
Resolución	Actividad	Acción
lograda	baja	archivar
parcial	baja	archivar
no lograda	alta	mantener
________________________________________
🔒 ESTADO FINAL
Estas Decision Tables v1 son:
•	coherentes con el Core
•	ejecutables
•	auditables
•	versionables
•	suficientes para un MVP real
Desde ahora:
•	no se discuten
•	se implementan
•	se ajustan solo como v2
________________________________________

