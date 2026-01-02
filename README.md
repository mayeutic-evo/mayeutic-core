# Mayeutic Core v1

Mayeutic Core es el sistema central de decisión que gobierna todos los productos de Mayeutic.

No es una app.
No es una interfaz.
No es un chatbot.
No es una IA que improvisa.

Es un motor de criterio que observa contextos humanos complejos, evalúa estados, consulta tablas de decisión y recomienda acciones con el objetivo de reducir fricción cognitiva, organizacional y social.

## Qué hace

- Decide si intervenir o no
- Decide cuándo intervenir
- Define nivel de intervención
- Prioriza
- Agrupa
- Escala
- Cierra ciclos
- Gestiona memoria
- Pide validación humana cuando hay ambigüedad

## Qué NO hace

- No ejecuta acciones finales
- No toma decisiones irreversibles
- No opina
- No juzga
- No reemplaza humanos ni instituciones

## Principio rector

Si la IA decide, está mal.  
Si la UI decide, está peor.  
Si el Core decide, todo fluye.

## Estructura

- El Core vive en reglas y decision tables
- Los productos (Basyco, Nukleo) son configuraciones del Core
- La IA es ejecutora, no cerebro
- Las interfaces solo capturan y muestran

## Documentación

- docs/core-v1.md → definición completa del sistema
- docs/decision-tables-v1.md → reglas ejecutables v1

Este repositorio define la verdad operativa del sistema.
Todo diseño, código o IA debe colgar de acá.

## Documentos fuente (verdad del sistema)

Este repositorio se rige exclusivamente por los siguientes documentos:

- docs/core-v1.md  
  Define el propósito, alcance, decisiones fundacionales, estados y acciones permitidas del Mayeutic Core v1.

- docs/decision-tables-v1.md  
  Contiene las Decision Tables ejecutables (Core, Basyco y Nukleo).  
  Estas tablas gobiernan el comportamiento del sistema y son la única fuente de decisión.

Regla:
Si algo no está definido en estos documentos, no existe para el sistema.

