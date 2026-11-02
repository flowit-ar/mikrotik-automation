# MikroTik Automation

Colección de scripts RouterOS y documentación orientados a tareas repetibles de operación y validación.

## Objetivo

Compartir automatizaciones reutilizables para inventario, backup, alertas y controles básicos, siempre con parámetros de ejemplo y sin datos de infraestructura real.

## Estructura sugerida

```text
mikrotik-automation/
├── scripts/
│   ├── export-sanitized.rsc
│   ├── backup-reminder.rsc
│   └── interface-health-check.rsc
├── docs/
│   ├── deployment.md
│   └── rollback.md
└── README.md
```

## Contenido previsto

- Exportaciones sanitizadas para documentación.
- Controles de disponibilidad de interfaces y enlaces.
- Recordatorios de revisión de backup.
- Ejemplos de logging y alertas sin endpoints reales.

## Seguridad

Antes de publicar un script RouterOS, revisar y eliminar:

- Direcciones IP, prefijos y gateways reales.
- Usuarios, contraseñas, certificados, claves y secretos.
- Dominios, DNS, SNMP communities y destinos de correo.
- Nombres de clientes, sitios, VLANs o enlaces identificables.
