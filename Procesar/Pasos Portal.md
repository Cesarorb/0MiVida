```mermaid
flowchart TD
	A[(Trunk)]
	A-->|1| B[(WB00413)]
	A-->|2|C[(RFC)]
	B-->|3|D[Pruebas y errores]
	D-->|4|B
	B-->|5|E[PRE]
	D-->|6|C
	C-->|7|F[PRO]
	
```