<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mapa conceptual: Fases de un compilador</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .contenedor {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
        }
        .box {
            border: 1px solid #ccc;
            padding: 10px;
            margin: 10px;
            text-align: center;
            border-radius: 5px;
            background-color: #f5f5f5;
        }
        .linea {
            border-bottom: 1px dashed #ccc;
            width: 100%;
        }
        .etiqueta {
            font-size: 12px;
            font-style: italic;
            text-align: left;
            margin-left: 10px;
        }
    </style>
</head>
<body>
    <h1>Mapa conceptual: Fases de un compilador</h1>
    <div class="contenedor">
        <div class="box principal">
            <h2>Fases de un compilador</h2>
        </div>
        <div class="box secundario analisis">
            <h2>Análisis</h2>
            <ul>
                <li>Análisis léxico</li>
                <li>Análisis sintáctico</li>
                <li>Análisis semántico</li>
            </ul>
        </div>
        <div class="box secundario sintesis">
            <h2>Síntesis</h2>
            <ul>
                <li>Generación de código intermedio</li>
                <li>Optimización de código</li>
                <li>Generación de código final</li>
            </ul>
        </div>
        <div class="box secundario otros">
            <h2>Otras fases</h2>
            <ul>
                <li>Preprocesador</li>
                <li>Enlazador</li>
            </ul>
        </div>
        <div class="box secundario herramientas">
            <h2>Herramientas</h2>
            <ul>
                <li>Compilador</li>
                <li>Intérprete</li>
            </ul>
        </div>
        <div class="box secundario recursos">
            <h2>Recursos</h2>
            <ul>
                <li><a href="https://es.wikipedia.org/wiki/Compilador">Wikipedia: Compilador</a></li>
                <li>Fases de un compilador: [se quitó una URL no válida]</li>
                <li>Introducción a los compiladores: [se quitó una URL no válida]</li>
            </ul>
        </div>
        <div class="linea" style="width: 400px;"></div>
        <div class="linea" style="width: 200px;"></div>
        <div class="linea" style="width: 100px;"></div>
        <div class="linea" style="width: 200px;"></div>
        <div class="linea" style="width: 400px;"></div>
        <div class="etiqueta" style="width: 400px;">Análisis</div>
        <div class="etiqueta" style="width: 200px;">Síntesis</div>
        <div class="etiqueta" style="width: 100px;">Otros</div>
        <div class="etiqueta" style="width: 200px;">Herramientas</div>
        <div class="etiqueta" style="width: 400px;">Recursos</div>
    </div>
</body>
</html>
