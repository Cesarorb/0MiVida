```mermaid
flowchart TD
	A["Entrega HU"]
	-->B["Analisis HU"]
	-->C["Actualización HU"]
	-->D["Descarga y despliegue</br>SVN, Bitbucket, Github"]
	-->E["Construcción"]
	-->F["MD - Manual de Despliegue</br>-Archivos estáticos</br>-Properties</br>DT - Diseño técnico</br>-Reglas de negocio"]
	-->G["Pruebas DEV</br>PU - Pruebas Unitarias</br>Evidencia de pruebas"]
	-->H["Pruebas Unitarias</br>Cobertura Min. 90%"]
	-->I["Portal</br>-Contexto</br>-Permiso"]
	
```
---
- [ ] Entrega HU
- [ ] Análisis HU
	- [ ] Actualización HU
- [ ] Descarga y despliegue
	- [ ]  SVN, Bitbucket, Github
- [ ]  Construcción
	- [ ]  MD - Manual de Despliegue
		- [ ]  Archivos estáticos
		- [ ] Properties
	- [ ]  DT - Diseño Técnico
		- [ ]  Reglas de negocio
- [ ]  Pruebas DEV
	- [ ]  PU - Pruebas Unitarias
		- [ ]  Evidencia de Pruebas
- [ ]  Pruebas JUnit
	- [ ]  Cobertura Min 90%
- [ ]  Portal
	- [ ]  Revisar Contexto
		- [ ]  Revertir si es necesario
	- [ ]  Solicitar Permiso
		- [ ]  Grupo Despliegues
- [ ]  Migración a PRE
- [ ]  Solicitud de Pruebas
	- [ ]  Pruebas UAT
- [ ]  Migración a Producción