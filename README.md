<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Convertir XML a PDF - Ticket</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 flex items-center justify-center min-h-screen">

    <!-- Contenedor Principal -->
    <div class="w-full max-w-lg bg-white shadow-lg rounded-lg p-8">
        <!-- Título -->
        <div class="text-center mb-6">
            <h1 class="text-2xl font-extrabold text-teal-600">🎟 Convertidor XML a PDF</h1>
            <p class="text-gray-500 mt-2">Convierte tus comprobantes XML a un formato PDF listo para imprimir.</p>
        </div>

        <!-- Formulario -->
        <form action="#" method="POST" enctype="multipart/form-data" class="space-y-6">
            <!-- Tamaño del Ticket -->
            <div>
                <label for="size" class="block text-sm font-bold text-gray-700">Tamaño / Formato:</label>
                <select id="size" name="size" class="block w-full mt-1 border border-gray-300 rounded-md shadow-sm focus:ring-teal-500 focus:border-teal-500">
                    <option>80MM (3 Pulgadas)</option>
                    <option>58MM (2 Pulgadas)</option>
                </select>
            </div>

            <!-- Archivo XML -->
            <div>
                <label for="xml" class="block text-sm font-bold text-gray-700">Subir Archivo XML:</label>
                <input type="file" id="xml" name="xml" accept=".xml"
                    class="block w-full mt-2 text-sm text-gray-500 file:py-2 file:px-4 file:rounded file:border-0 file:text-sm file:font-semibold file:bg-teal-600 file:text-white hover:file:bg-teal-700">
                <p class="text-gray-400 text-xs mt-1">Solo se aceptan archivos con formato XML.</p>
            </div>

            <!-- Salida del archivo -->
            <div>
                <label for="output" class="block text-sm font-bold text-gray-700">Formato de Salida:</label>
                <select id="output" name="output" class="block w-full mt-1 border border-gray-300 rounded-md shadow-sm focus:ring-teal-500 focus:border-teal-500">
                    <option>PDF</option>
                </select>
            </div>

            <!-- Subir Logo -->
            <div>
                <label for="logo" class="block text-sm font-bold text-gray-700">Subir Logo (Opcional):</label>
                <input type="file" id="logo" name="logo" accept="image/*"
                    class="block w-full mt-2 text-sm text-gray-500 file:py-2 file:px-4 file:rounded file:border-0 file:text-sm file:font-semibold file:bg-teal-600 file:text-white hover:file:bg-teal-700">
                <p class="text-gray-400 text-xs mt-1">Archivos permitidos: PNG, JPG, SVG.</p>
            </div>

            <!-- Botón de Enviar -->
            <div>
                <button type="submit" class="w-full py-3 px-4 bg-teal-600 text-white font-bold rounded-md shadow-md hover:bg-teal-700">
                    Convertir Ahora
                </button>
            </div>
        </form>

        <!-- Instrucciones -->
        <div class="mt-8 text-sm text-gray-500">
            <h2 class="font-semibold text-gray-700">Instrucciones:</h2>
            <ul class="list-disc pl-5 mt-2 space-y-1">
                <li>Seleccione el tamaño del ticket que desea generar.</li>
                <li>Cargue el archivo XML correspondiente al comprobante.</li>
                <li>Suba su logo si desea personalizar el ticket.</li>
                <li>Presione el botón <strong>"Convertir Ahora"</strong> para generar el PDF.</li>
            </ul>
        </div>

        <!-- Footer -->
        <footer class="mt-10 text-center text-gray-400 text-xs">
            <p>© 2025 Negocio Ejemplo. Todos los derechos reservados.</p>
        </footer>
    </div>

</body>
</html>
