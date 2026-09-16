# Ontología del proyecto de titulación

## Tecnologías asistivas inteligentes basadas en fusión sensorial e inteligencia artificial

### Propósito

Esta ontología representa los conceptos y relaciones involucrados en el desarrollo de tecnologías asistivas inteligentes orientadas a la comunicación, percepción e interacción con el entorno.

El proyecto contempla dos sistemas principales:

- [[Guantes traductores]]
- [[Lentes asistivos]]

## Dominios principales

- [[Discapacidad y población]]
- [[Tecnología asistiva]]
- [[Inteligencia artificial]]
- [[Adquisición de información]]
- [[Comunicación humano-máquina]]
- [[Entorno inteligente]]
- [[Aplicación móvil]]

## Sistemas del proyecto

### Guantes traductores

Sistema basado en múltiples sensores para capturar información relacionada con la posición, movimiento y configuración de las manos. Los datos serán procesados mediante fusión sensorial y un modelo Sensor Fusion Transformer para reconocer señas y convertirlas en palabras, texto, audio o comandos.

### Lentes asistivos

Sistema basado en visión artificial para identificar obstáculos y reconocer denominaciones de billetes, proporcionando información al usuario mediante audio y vibración.

## Arquitectura conceptual

```text
                         USUARIO
                            │
                            ▼
                        NECESIDAD
                            │
                            ▼
                   TECNOLOGÍA ASISTIVA
                      │             │
                      ▼             ▼
                   GUANTES        LENTES
                      │             │
                      ▼             ▼
              FUSIÓN SENSORIAL   VISIÓN ARTIFICIAL
                      │             │
                      ▼             ▼
                    IA / MODELOS DE IA
                      │             │
                      └──────┬──────┘
                             ▼
                      INTERPRETACIÓN
                             │
                             ▼
                    COMUNICACIÓN / ACCIÓN
                       │       │       │
                       ▼       ▼       ▼
                     TEXTO    AUDIO  VIBRACIÓN
                             
                             │
                             ▼
                       ENTORNO DOMÓTICO
                             │
                             ▼
                         ACTUADORES