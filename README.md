# Clase de Git
## Comandos de Git
- (son para adelante)**git init** : Inicializar un repositorio.
- ````git add .```` : Guardar los cambios.
- ````git commit -m[mensaje]```` (descripcion o palabra de lo que hiciste) : actualiza el archivo en git (poner siempre el -m (mensaje) para que pueda mostrarse el mensaje en pantalla).
- ````git log```` : ver el historial de 'commit'.
- ````git show [file]```` : Muestra los commits que se a hecho.
- ````git branch```` : listar las ramas.(Solo te aparece la una rama una vez que hayas commit)
- ````git branch [rama]```` : crear una rama.
- ````git checkout [rama]```` : pasarme a una rama.
- ````git checkout -b(branch) [rama]```` : crear y pasarme a una rama.
  
 ## Comandos remotos 
- ````git remote -v```` : ver los repositorios que tengo remotos.
- ````git remote remove [name]```` : eliminar repositorios remotos.
- ````git remote rename [old name] [new name]```` : renombrar un repositorio remoto.
- ````git remote add [name of the remote] [link]```` : agregar un repositorio remoto.
- ````git clone [file]```` : clonar un repositorio.
- ````git diff [first link of a commit] [secondo link of a commit]```` : muestra la diferencia entre un commit y el otro.

# agregue otra cosa

```
<html><!-- asi se hace un comentario-->
  <head><!--la pestaña que sale en el buscador-->
    <title>mi_primer_programa</title>
    <style>
      body
      {
        background-color:#8C8684;
        color:#F2EDEC;
        font-family:Helvetica;
      }
      strong
      {
        background-color:#EE9F93;
      }
    </style>
  </head>
  <body>
    <p><strong>Ya se lo que hiciste ayer.</strong></p>
    <p><strong>Harry Poter.<strong></p>
    <p>Estoy detras de ti.</p>
    <p>Hola mundo, ya casi aprendo html.</p>
    <script type="text/javascript">
      alert("Esto es una pagina web para hacer una suma");
      var num_1=2;
      var num_2=2;
      num_1=parseInt(prompt("Digite el primer numero"));
      num_2=parseInt(prompt("Digite el segundo numero"));
      var resul=num_1+num_2;
      alert("El resultado de la suma es: " + resul);
      document.write("El resultado de la suma es: " + resul);
    </script>
  </body>
</html>
```