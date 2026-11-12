<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Generador de Títulos y Preguntas de Investigación</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f1f5f9;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
            box-sizing: border-box;
        }
        .card {
            background-color: #ffffff;
            padding: 25px 30px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            max-width: 650px;
            width: 100%;
        }
        h2 {
            margin-top: 0;
            color: #0f172a;
            text-align: center;
        }
        p.subtitle {
            color: #64748b;
            font-size: 14px;
            text-align: center;
            margin-bottom: 20px;
        }
        .form-row {
            display: flex;
            gap: 15px;
            margin-bottom: 12px;
        }
        .form-group {
            flex: 1;
            margin-bottom: 12px;
        }
        label {
            display: block;
            margin-bottom: 4px;
            font-weight: bold;
            color: #334155;
            font-size: 13px;
        }
        input[type="text"], select {
            width: 100%;
            padding: 8px 10px;
            box-sizing: border-box;
            border: 1px solid #cbd5e1;
            border-radius: 6px;
            font-size: 14px;
        }
        .options-group {
            background-color: #f8fafc;
            border: 1px dashed #cbd5e1;
            padding: 12px;
            border-radius: 6px;
            margin: 15px 0;
        }
        .options-group legend {
            font-size: 13px;
            font-weight: bold;
            color: #334155;
            padding: 0 5px;
        }
        .checkbox-label {
            display: inline-flex;
            align-items: center;
            margin
