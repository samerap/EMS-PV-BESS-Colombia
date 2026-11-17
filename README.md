# EMS-PV-BESS-Colombia
Código fuente del EMS para arbitraje energético en sistemas PV-BESS aplicado al SIN colombiano.

# EMS para arbitraje energético en sistemas PV-BESS

Repositorio asociado al trabajo de grado desarrollado para la
Maestría en Ingeniería Eléctrica de la Universidad Escuela Colombiana
de Ingeniería Julio Garavito.

El código implementa un Sistema de Gestión Energética (EMS) para un
sistema PV-BESS orientado al arbitraje energético en el Sistema
Interconectado Nacional colombiano.

## Componentes principales

- Procesamiento de datos del SIN.
- Pronóstico del precio de bolsa mediante Gradient Boosting.
- Pronóstico de irradiancia mediante CNN-LSTM.
- Conversión de irradiancia a potencia fotovoltaica.
- Optimización MILP del sistema PV-BESS.
- Operación mediante horizonte deslizante.
- Evaluación técnica y económica del EMS.

## Caso de estudio

Parque Solar El Paso, Cesar, Colombia.

- Sistema fotovoltaico: 99.5 MWdc / 67.92 MWac
- BESS: 30 MW / 60 MWh
- Horizonte de optimización: 24 h
- Resolución temporal: 1 h

## Autor

Santiago Alberto Mera Ponce

Maestría en Ingeniería Eléctrica  
Universidad Escuela Colombiana de Ingeniería Julio Garavito
