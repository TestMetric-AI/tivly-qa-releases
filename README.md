# Tivly QA CLI

Distribuciones publicas del CLI de QA de TestMetric AI.

El codigo fuente se mantiene en un repositorio privado. Este repositorio contiene solamente los paquetes verificados y las notas de cada version.

## Requisitos

- Node.js 22 o posterior
- npm

## Instalar

Descarga e instala la version mas reciente publicada:

```powershell
npm install --global https://github.com/TestMetric-AI/tivly-qa-releases/releases/latest/download/tivly-qa.tgz
```

Comprueba la instalacion:

```powershell
tivly-qa --version
```

## Actualizar

Ejecuta nuevamente el mismo comando. npm reemplazara la version instalada:

```powershell
npm install --global https://github.com/TestMetric-AI/tivly-qa-releases/releases/latest/download/tivly-qa.tgz
```

La configuracion local del usuario se conserva durante la actualizacion.

## Version fija

Para instalar una version especifica, usa el artefacto versionado de su release. Por ejemplo:

```powershell
npm install --global https://github.com/TestMetric-AI/tivly-qa-releases/releases/download/v0.3.1/tivly-qa-0.3.1.tgz
```

Consulta [Releases](https://github.com/TestMetric-AI/tivly-qa-releases/releases) para ver las versiones y sus notas.

## Soporte

Este repositorio distribuye el ejecutable y no recibe cambios de codigo. Reporta problemas al equipo de TestMetric AI.
