# semana-15
# Crear un diccionario llamado informacion_personal
informacion_personal = {
    "nombre": "karen avigail quinonez",
    "edad": 18,
    "ciudad": "shushufindi",
    "profesion": "ingenieria en tecnologoa de la informacion"
}

# Acceder al valor asociado con la clave "ciudad" y modificarlo
informacion_personal["ciudad"] = "shushufindi"

# (La clave "profesion" ya fue agregada en la creación del diccionario,
# según las instrucciones originales. Si la intención era agregar otra profesión,
# se podría hacer así:)
# informacion_personal["otra_profesion"] = "Consultora de TI"

# Verificar si la clave "telefono" existe y agregarla si no
if "telefono" not in informacion_personal:
    informacion_personal["telefono"] = "0939863440"

# Eliminar la clave "edad"
if "edad" in informacion_personal:
    del informacion_personal["edad"]

# Imprimir el diccionario resultante
print(informacion_personal)
éxito
