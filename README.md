# Desafio_Branching

Habilidades a evaluar

● Realiza operaciones de navegación de directorios, usando los comandos básicos del terminal, para crear y manipular archivos y directorios.

● Aplica las etapas del versionamiento de git, para mantener un repositorio de versiones.

## Requerimientos del Proyecto (10 puntos totales)

### 1. Configuración Inicial del Repositorio (5 puntos)

#### Preparación
1. Descargar proyecto base "Apoyo Desafío-Branching"
2. Inicializar repositorio Git:
   ```bash
   git init
   ```
3. Primer commit:
   ```bash
   git add .
   git commit -m "Commit inicial"
   ```

#### Nueva Funcionalidad
- **Rama**: development
- **Objetivo**: Implementar redirección a GitHub al hacer click en imagen

### 2. Manejo de Ramas (5 puntos)

#### Pasos a Seguir
1. Crear rama development:
   ```bash
   git checkout -b development
   ```
2. Modificar archivo index.html
3. Staging y commit de cambios:
   ```bash
   git add index.html
   git commit -m "Agregada funcionalidad de redirección"
   ```

#### Puntos de Verificación
- [ ] Confirmar inicialización del repositorio
- [ ] Verificar creación de rama development
- [ ] Comprobar funcionalidad de redirección
- [ ] Revisar diferencias entre ramas master y development
