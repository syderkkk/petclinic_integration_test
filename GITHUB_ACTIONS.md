# Implementación con GitHub Actions

Este proyecto implementa CI/CD usando GitHub Actions en lugar de Jenkins.

## Archivo de configuración
- `.github/workflows/ci.yml`

## Características implementadas
- ✅ Compilación automática con Maven
- ✅ Ejecución de pruebas unitarias
- ✅ Ejecución programada cada 2 horas
- ✅ Activación en cada push y pull request

## Ventajas sobre Jenkins
- No requiere servidor EC2 en AWS
- Configuración más simple (YAML vs Groovy)
- Gratis para repositorios públicos
- Integración nativa con GitHub
