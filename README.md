# cursos-de-las-tic
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reloj Completo Azul Mate</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="clock">
        <div id="time" class="time">00:00:00</div>
        <button id="startStop" class="button">Iniciar Cronómetro</button>
        <button id="reset" class="button">Resetear Cronómetro</button>
        <div id="stopwatch" class="stopwatch">00:00:00</div>
        
        <div class="alarm">
            <h3>Alarma</h3>
            <input type="time" id="alarmTime" />
            <button id="setAlarm" class="button">Configurar Alarma</button>
            <div id="alarmStatus" class="status">Alarma desactivada</div>
        </div>

        <div class="weather">
            <h3>Clima</h3>
            <div id="weatherInfo" class="weather-info">Cargando clima...</div>
        </div>

        <div class="timer">
            <h3>Temporizador</h3>
            <input type="number" id="timerMinutes" placeholder="Minutos" />
            <button id="startTimer" class="button">Iniciar Temporizador</button>
            <div id="timerDisplay" class="timer-display">00:00</div>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
