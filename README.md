<html lang="es">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>
   Comprobante XML a PDF Ticket
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
 </head>
 <body class="bg-white text-gray-800">
  <header class="flex justify-between items-center p-4">
   <div class="flex items-center">
    <img alt="Factdin logo" class="h-12" height="50" src="https://storage.googleapis.com/a1aa/image/P3JKfqZm1QXdKKfzWVkjNaqnuAPzfXlPnGNLkkLMTUgegjcQB.jpg" width="50"/>
    <span class="text-4xl font-bold ml-2">
     Factdin
    </span>
   </div>
   <nav class="flex space-x-4">
    <a class="text-gray-800 hover:text-gray-600" href="#">
     Tienda
    </a>
    <a class="text-gray-800 hover:text-gray-600" href="#">
     PosDin
    </a>
    <a class="text-gray-800 hover:text-gray-600" href="#">
     Aplicaciones
    </a>
   </nav>
  </header>
  <main class="flex flex-col items-center mt-10">
   <h1 class="text-3xl font-bold mb-6">
    Comprobante XML a PDF Ticket
   </h1>
   <form class="w-full max-w-md">
    <div class="mb-4">
     <label class="block text-gray-700" for="size">
      Tamaño:
     </label>
     <select class="w-full p-2 border border-gray-300 rounded" id="size">
      <option>
       58MM (2 Pulgadas)
      </option>
     </select>
    </div>
    <div class="mb-4">
     <label class="block text-gray-700" for="xml">
      XML:
     </label>
     <input class="w-full p-2 border border-gray-300 rounded" id="xml" type="file"/>
     <span class="text-gray-600">
      Sin archivos seleccionados
     </span>
    </div>
    <div class="mb-4">
     <label class="block text-gray-700" for="output">
      Salida:
     </label>
     <select class="w-full p-2 border border-gray-300 rounded" id="output">
      <option>
       PDF
      </option>
     </select>
    </div>
    <button class="w-full bg-gray-700 text-white p-2 rounded" type="submit">
     Enviar
    </button>
   </form>
  </main>
 </body>
</html>
