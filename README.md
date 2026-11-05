# NUVORA

**Plataforma web de gestión integral** para organizaciones sociales, fundaciones y centros de atención. Centraliza la información de pacientes o beneficiarios, profesionales, apoderados, fichas, sesiones y pagos. También contempla donaciones y procesos cooperativos para apoyar la gestión administrativa y financiera.

## Módulos del sistema

La estructura de aplicaciones prevista es:

```text
aplicaciones/
├── comun/            # Funciones y componentes compartidos
├── usuarios/         # Cuentas, roles y permisos
├── beneficiarios/    # Pacientes, apoderados y profesionales
├── atenciones/       # Fichas, asignaciones y sesiones
├── finanzas/         # Cobros, pagos y saldos
├── benefactores/     # Benefactores y donaciones
├── cooperativa/      # Socios y aportes cooperativos
├── prestamos/        # Solicitudes, préstamos y cuotas
├── reportes/         # Indicadores y seguimiento
└── notificaciones/   # Avisos y notificaciones
```

**Objetivo:** reunir en un solo sistema la atención de personas y el seguimiento institucional, con acceso según el rol de cada usuario.
