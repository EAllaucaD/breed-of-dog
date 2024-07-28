# USO DE LIBRERÍAS E INSTALACIÓN.
Esta sección es para ejecutar labelme.
## Instala la herramienta de etiquetado:
pip install labelme

## Si te pide actualizar pip:
python.exe -m pip install --upgrade pip

## Ejecuta labelme:
labelme

Después de ejecutar labelme, se etiquetaron las imágenes por razas.
_____________________________________

# CONVERTIR IMÁGENES DE JSON A YOLO

## Installa labelme2yolo para convertir Json a Yolo:
pip install labelme2yolo

## Convierte tus archivos Json a Yolo:
labelme2yolo --json_dir tu/direccion/sin/espacios
lA DIRECCIÓN DONDE SE VA A GUARDAR

____________________________________________

## Instala ultralytics:
pip install ultralytics


# USO DE LA RED NEURONAL
## Entrena tu red neuronal:
Se uso yolov8n por la capacidad del computador
yolo task=segment mode=train epochs=30 data=dataset.yaml model=yolov8n-seg.pt imgsz=640 batch=2

# EJECUTAR LA APLICACIÓN:

-Abrir alguno de los archivos .py

-Darle en ejecutar y necesidad de una cámara. Con esto mostrar una imagen a mostrar para identificación de raza.

![image](https://github.com/user-attachments/assets/b81f956b-5e3a-49bf-910e-3e658cac886c)
