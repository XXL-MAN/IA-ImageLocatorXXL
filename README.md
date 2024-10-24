# IA Image Locator XXL

Este repositorio contiene un script de una aplicación web interactiva desarrollada con Streamlit, que permite a los usuarios subir imágenes y obtener su ubicación geográfica aproximada. La aplicación utiliza un modelo de inteligencia artificial para predecir las coordenadas GPS (latitud y longitud) del lugar donde se tomó la imagen, y las visualiza en un mapa interactivo.

## Características

- **Subida de imágenes**: Los usuarios pueden subir hasta 3 imágenes en formato PNG, JPG o JPEG.
- **Visualización de imágenes**: Las imágenes subidas se muestran directamente en la interfaz de la aplicación.
- **Geolocalización automática**: El modelo de IA predice las coordenadas GPS de las imágenes subidas.
- **Mapa interactivo**: Se genera un mapa con Folium, donde se colocan marcadores en las ubicaciones estimadas.
- **Interfaz amigable**: La aplicación tiene una interfaz sencilla y fácil de usar gracias a Streamlit.

## Requisitos

Para ejecutar la aplicación necesitas tener instalado:

- `streamlit==1.26.0`
- `requests==2.31.0`
- `folium==0.14.0`
- `streamlit-folium==0.12.0`
- `numpy==1.23.5`
- `opencv-python==4.8.0.76`

## Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/tuusuario/ia-image-locator-xxl.git
    cd ia-image-locator-xxl
    ```

2. Crea y activa un entorno virtual:
    ```bash
    python -m venv env
    source env/bin/activate  # En Windows usa: env\Scripts\activate
    ```

3. Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

1. Asegúrate de que tienes tu clave de API correcta y reemplaza `PICARTA_API_TOKEN` en el código por tu clave.

2. Ejecuta la aplicación de Streamlit:
    ```bash
    streamlit run ImageProfileSeeker.py
    ```

3. Sube hasta 3 imágenes para obtener las predicciones de ubicación y verlas en el mapa interactivo.

## Captura de pantalla

![Interfaz de la aplicación](https://i.imgur.com/WTVCTci.png)

## Contribución

Las contribuciones son bienvenidas. Si encuentras un problema o tienes una mejora en mente, no dudes en abrir un `issue` o enviar un `pull request`.



