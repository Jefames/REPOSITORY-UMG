# REPOSITORY-UMG

-------------- JIMMY YAQUE ------------------
given_file = open('Numeros.txt', 'r')

lines = given_file.readlines()

for line in lines:
    for c in line:
        if c.isdigit() == True:
            print('Numero encontrado : {}'.format(c))

given_file.close()
/n
------------ Oliver Ruiz--------------------
<html>
<head>
<title>Calculadora</title> 
<link rel="stylesheet" type="text/css" href="calculadora.css" />
<script type="text/javascript" src="calculadora.js"></script>
</head>
<body>
<div class="calculadora"
<form action="#" name="calculadora" id="calculadora">
<p id="textoPantalla">0</p>
<p>
-------------- JERRY CORDERO ------------------

class Cliente(Persona):
    nit = models.CharField('NIT', max_length=10, unique=True, null=True, blank=True, default='C/F')
    nombre_comercial = models.CharField('Nombre Comercial', max_length=100, null=True, blank=True)
    direccion = models.CharField('Dirección', max_length=150)

    class Meta():
        db_table = 'cliente'
        verbose_name = 'Cliente'
        verbose_name_plural = 'Clientes'
        unique_together = ['nombre', 'apellido']
    
    def __str__(self):
        return "%s - %s" % (self.nit, self.nombre_comercial)

    -------------- JOSE FELIPE ------------------
    <!DOCTYPE html>
<html>
   <head>
      <title>Título de mi página web</title>
   </head>
   <body>
      <header>
         <h1>Titular principal de la página</h1>
      </header>
      <main>
         <h2>Primer Subtítulo de la página</h2>
         <p>Primer párrafo</p>
      </main>
      <footer>
      </footer>
   </body>
</html>
    
    
    --------------OSCAR ESPINOZA-------------
    <HTML>
<HEAD>
<TITLE>Ejemplo 3</TITLE>
</HEAD>
<BODY>
Esto es texto simple: cada navegador lo visualizará según su configuración por defecto.
<FONT SIZE="1">Este texto es tamaño 1.</FONT>
<FONT SIZE="2">Este texto es tamaño 2.</FONT>
<FONT SIZE="4">Este texto es tamaño 4.</FONT>
<FONT SIZE="+1">Este texto es tamaño +1 (que es lo mismo que tamaño 4).</FONT>
<FONT FACE="Arial" SIZE="5" COLOR="FFFF00">Este texto posee varias especificaciones de formato.</FONT>
</BODY>
</HTML>
    
    
