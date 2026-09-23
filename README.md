## Para ejecutar requerimientos.txt
py -m pip install -r requerimientos.txt

## Para actualización:
py -m pip install --upgrade pip
py -m pip install --upgrade mysql-connector-python

## En caso de ser necesario agregar manualmente los tipos de cliente
INSERT INTO tipo (id, nombre) VALUES
(1, 'Cliente Normal'),
(2, 'VIP'),
(3, 'Empresa');