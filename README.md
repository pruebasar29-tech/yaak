<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora IMC</title>
    <link rel="stylesheet" href="style.css"> 
</head>
<body>
    <div class="calculator-container">
        <h1>Calculadora de IMC</h1>

        <div class="input-group">
            <label for="peso">Peso (kg):</label>
            <input type="number" id="peso" step="0.1" required>
        </div>

        <div class="input-group">
            <label for="altura">Altura (cm):</label>
            <input type="number" id="altura" required>
        </div>

        <div class="input-group">
            <label for="sexo">Sexo:</label>
            <select id="sexo" required>
                <option value="default" disabled selected>Seleccione...</option>
                <option value="hombre">Hombre</option>
                <option value="mujer">Mujer</option>
            </select>
        </div>

        <button onclick="calcularIMC()">Calcular IMC</button>
        
        <div id="resultado-imc"></div>
        <div id="tip-imc"></div>
    </div>

    <script src="script.js"></script>
</body>
</html>

