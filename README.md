# Aprendizaje No Supervisado - Segmentación de Clientes con RFM y k-Means

Este repositorio contiene un análisis de segmentación de clientes utilizando técnicas de **Aprendizaje No Supervisado**, específicamente el algoritmo **k-Means** junto con la metodología **RFM (Recency, Frequency, Monetary)**.

## Contenido del Proyecto

El notebook incluye los siguientes pasos:

1. **Definición de Indicadores RFM**  
   - **Recency**: Última fecha de compra del cliente.  
   - **Frequency**: Cantidad de compras realizadas.  
   - **Monetary**: Total gastado por el cliente.

2. **Aplicación del Algoritmo k-Means**  
   - Implementación del método del **codo (Elbow Method)** para determinar el número óptimo de clusters.
   - Aplicación de **k-Means** para segmentar a los clientes.

3. **Evaluación y Score de Segmentación**  
   - Creación de una métrica para evaluar la calidad del clustering.

4. **Conclusiones**  
   - Identificación de patrones de comportamiento en los clientes.  
   - Posibles estrategias de negocio basadas en la segmentación obtenida.

## Requisitos

Para ejecutar el notebook, se recomienda tener instalado lo siguiente:

- Python 3.x
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

Puedes instalar las dependencias con:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
Para su uso se necesita descargar el siguiente archivo https://mega.nz/file/d5VzibYD#YHa07N3SnqFLk8whMEel8KguFgLVfWpPouZf0-PfSV8

## Uso

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   ```
2. Navega al directorio del proyecto:
   ```bash
   cd tu_repositorio
   ```
3. Abre el notebook en Jupyter:
   ```bash
   jupyter notebook "Aprendizaje no Supervisado.ipynb"
   ```

## Contribución

Si deseas contribuir a este proyecto, puedes enviar un **pull request** o reportar problemas en la sección de **issues**.
