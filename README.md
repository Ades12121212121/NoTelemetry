# No Telemetrie v1.0

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.7%2B-blue?logo=python">
  <img src="https://img.shields.io/badge/Platform-Windows-green">
  <img src="https://img.shields.io/github/v/release/Ades12121212121/NoTelemetry">
  <img src="https://img.shields.io/github/license/Ades12121212121/NoTelemetry">
</p>

## 🛡️ Anti-Telemetry Tool

Una herramienta avanzada para eliminar y modificar datos de telemetría en aplicaciones populares de desarrollo como VS Code, Cursor, Kiro AI y más.

## 🚀 Características

- **Eliminación de Telemetría**: Cambia IDs únicos de máquina y dispositivos
- **Spoofing de HWID**: Modifica identificadores de hardware con backup automático
- **Cambio de MAC**: Actualiza direcciones MAC en archivos de configuración
- **Sistema de Perfiles**: Guarda y carga configuraciones personalizadas
- **Detector Automático**: Identifica aplicaciones instaladas automáticamente
- **Interfaz Gráfica**: Modo GUI opcional para usuarios no técnicos
- **Sistema de Logs**: Registro completo de todas las actividades
- **Exportación de Reportes**: Genera informes detallados en formato JSON

## 📋 Aplicaciones Soportadas

- Kiro AI
- CodeLLM
- Cursor
- Visual Studio Code
- Trae
- Windsurf

## 💻 Instalación

### Opción 1: Ejecutable (Recomendado)
Descarga el archivo `.exe` de la sección de [Releases](https://github.com/Ades12121212121/NoTelemetry/releases)

### Opción 2: Versión Python
```bash
# Clonar el repositorio
git clone https://github.com/Ades12121212121/NoTelemetry.git
cd NoTelemetry

# Instalar dependencias
pip install -r requirements.txt

# Ejecutar
python notelemetrie.py
```

## 🛠️ Comandos Disponibles

| Comando | Descripción |
|---------|-------------|
| `help` | Mostrar ayuda |
| `reset` | Cambiar telemetría en todas las apps |
| `mac` | Cambiar direcciones MAC |
| `spoof` | Cambiar HWID y crear backup |
| `time` | Cambiar configuración de hora/región |
| `detect` | Detectar aplicaciones instaladas |
| `profiles` | Listar perfiles guardados |
| `save-profile <nombre>` | Guardar perfil actual |
| `load-profile <nombre>` | Cargar perfil |
| `config` | Mostrar configuración |
| `set-config <key> <value>` | Establecer configuración |
| `stats` | Mostrar estadísticas |
| `report` | Exportar informe |
| `update` | Verificar actualizaciones |
| `gui` | Abrir interfaz gráfica |
| `clear` | Limpiar pantalla |
| `exit` | Salir |

## 📁 Estructura de Archivos Generada

```
NoTelemetry/
├── backups/           # Backups de archivos originales
├── profiles/          # Perfiles guardados
├── reports/           # Informes exportados
├── telemetry_log.txt  # Registro de actividades
├── usage_stats.json   # Estadísticas de uso
├── config.json        # Configuración del usuario
└── NoTelemetrie.exe   # Ejecutable (después de compilar)
```

## ⚠️ Advertencias Importantes

- **Solo para uso personal**: Esta herramienta debe usarse únicamente en tus propios sistemas
- **Backup recomendado**: Siempre se recomienda crear backups antes de usar
- **Responsabilidad**: El autor no se hace responsable del mal uso de esta herramienta
- **Legalidad**: Asegúrate de cumplir con los términos de servicio de las aplicaciones

## 📋 Requisitos

- Windows 7/8/10/11
- Python 3.7+ (solo para versión source)
- Permisos de escritura en AppData\Roaming
- 50MB de espacio libre

## 📦 Dependencias

```txt
colorama>=0.4.6
requests>=2.31.0
```

## 🔄 Actualizaciones

El programa verifica automáticamente actualizaciones al iniciar. También puedes usar:
```
update
```

## 📊 Estadísticas

La herramienta mantiene estadísticas de uso en `usage_stats.json`:
- Total de resets realizados
- Total de spoofing ejecutados
- Perfiles creados
- Última fecha de uso

## 📝 Licencia

Este proyecto está licenciado bajo MIT License - ver el archivo [LICENSE](LICENSE) para detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Haz un fork del proyecto
2. Crea tu rama de características (`git checkout -b feature/CaracteristicaIncreible`)
3. Haz commit de tus cambios (`git commit -m 'Añadir CaracteristicaIncreible'`)
4. Haz push a la rama (`git push origin feature/CaracteristicaIncreible`)
5. Abre un Pull Request

## 📧 Contacto

**Ades12121212121** - [@Ades12121212121](https://github.com/Ades12121212121)

Link del proyecto: [https://github.com/Ades12121212121/NoTelemetry](https://github.com/Ades12121212121/NoTelemetry)

## 🙏 Agradecimientos

- A la comunidad de desarrollo por las herramientas que inspiraron este proyecto
- A todos los usuarios que reportan bugs y sugieren mejoras

---

<p align="center">
  <strong>🛡️ Protege tu privacidad con No Telemetrie 🛡️</strong>
</p>
