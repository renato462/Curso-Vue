<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA_Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="Basic to-do app with Vue.js 2.1">
    <meta name="author" content="https://styde.net">
    <link rel="icon" href="favicon.ico">
    <title>Lección 1 - Vue 2 - COMODER JR</title>

    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

</head>
<body>
<div id ="app" class="container">
    <div>
        <form >
            <h4>Registrate</h4>
            <div class="form-group">
                <label for="first_name">Nombre</label>
                <input type="text" id="first_name" class="form-control">
            </div>
            <div class="form-group">
                <label for="last_name">Apellido</label>
                <input type="text" id="last_name" class="form-control">
            </div>
            <button type="submit" class="btn btn-primary" disabled>Continuar</button>
        </form>
    </div>
    <div>
       <h4>Bienvenido, [Nombre Completo]</h4>
    </div>
    <footer class="footer">
        <p>&copy;2017 comoderjr.com.pe</p>
    </footer>
</div>
<script type="text/javascript" src="https://unpkg.com/vue@2.2.6"></script>
</body>
<script>
new Vue({
    el:"#app"
});
</script>
</html>