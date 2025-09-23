<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Identidad de Marca</title>
    <!-- Enlace a la fuente Barlow de Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Barlow:wght@500&display=swap" rel="stylesheet">
    <!-- Enlace al CDN de Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Definir colores personalizados usando los códigos Pantone aproximados */
        :root {
            --pantone-286c: #00216B;
            --pantone-632c: #63c5da;
            --pantone-3125c: #00A3AD;
            --pantone-2757c: #1E1854;
            --pantone-311c: #00BDCE;
            --pantone-446c: #4E5254;
            --pantone-649c: #B8BCBD;
        }

        body {
            background-color: var(--pantone-286c);
            font-family: 'Barlow', sans-serif;
            color: #ffffff;
        }

        .text-pantone-286c {
            color: var(--pantone-286c);
        }

        .text-pantone-2757c {
            color: var(--pantone-2757c);
        }

        .text-pantone-3125c {
            color: var(--pantone-3125c);
        }

        .bg-pantone-632c {
            background-color: var(--pantone-632c);
        }

        .barlow-medium {
            font-family: 'Barlow', sans-serif;
            font-weight: 500;
        }
    </style>
</head>

<body class="p-6">
    <div class="max-w-4xl mx-auto space-y-12">
        <!-- Título principal -->
        <h1 class="text-4xl md:text-5xl lg:text-6xl text-center font-bold barlow-medium mt-8 mb-12">
            Identidad de marca
        </h1>

        <!-- Sección Logotipo -->
        <div class="bg-white p-8 rounded-xl shadow-lg text-black">
            <h2 class="text-3xl font-bold barlow-medium text-pantone-286c text-center mb-4">
                Logotipo
            </h2>
            <p class="text-base md:text-lg text-center leading-relaxed">
                La tipografía fue creada exclusivamente para la marca, sus terminaciones encuentran inspiración en las plumas del cóndor.
            </p>
            <div class="mt-8 flex justify-center">
                <!-- Espacio para una imagen -->
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Grupo_Sura_logo.svg/2560px-Grupo_Sura_logo.svg.png" class="w-full h-auto rounded-lg" />
            </div>
        </div>

        <!-- Sección Símbolo -->
        <div class="p-8 rounded-xl shadow-lg" style="background-color: var(--pantone-649c);">
            <h2 class="text-3xl font-bold barlow-medium text-pantone-286c text-center mb-4">
                Símbolo
            </h2>
            <p class="text-base md:text-lg text-center leading-relaxed text-black">
                El isotipo o símbolo de SURA, es la abstracción del cóndor, ave emblemática de la región donde opera la compañía. Éste, acompaña a la tipografía para juntos crear el logotipo.
            </p>
            <div class="mt-8 flex flex-col sm:flex-row justify-center items-center gap-6">
                <!-- Espacio para dos imágenes -->
                <img src="https://play-lh.googleusercontent.com/u6SbUHUFYzDa_WjhaexamUqW6-VdrG1aADgtF_3qkeHNSRTvoW4X9QzgJwUOo5wftQ" class="w-full sm:w-1/2 h-auto rounded-lg" />
                <img src="https://suseguro.co/wp-content/uploads/2025/03/logo-sura-movimiento.gif" class="w-full sm:w-1/2 h-auto rounded-lg" />
            </div>
        </div>

        <!-- Sección Colores -->
        <div class="bg-pantone-632c p-8 rounded-xl shadow-lg text-black">
            <h2 class="text-3xl font-bold barlow-medium text-pantone-2757c text-center mb-8">
                Colores
            </h2>
            <div class="flex flex-wrap justify-center gap-6">
                <!-- Azul Profundo -->
                <div class="flex flex-col items-center">
                    <div class="w-24 h-24 sm:w-28 sm:h-28 rounded-xl mb-2" style="background-color: var(--pantone-2757c);"></div>
                    <span class="text-center text-white">Azul profundo</span>
                    <span class="text-center text-white">PANTONE 2757 C</span>
                </div>
                <!-- Blanco -->
                <div class="flex flex-col items-center">
                    <div class="w-24 h-24 sm:w-28 sm:h-28 rounded-xl mb-2 bg-white border border-gray-300"></div>
                    <span class="text-center text-white">Blanco</span>
                </div>
                <!-- Aqua -->
                <div class="flex flex-col items-center">
                    <div class="w-24 h-24 sm:w-28 sm:h-28 rounded-xl mb-2" style="background-color: var(--pantone-311c);"></div>
                    <span class="text-center text-white">Aqua</span>
                    <span class="text-center text-white">PANTONE 311 C</span>
                </div>
                <!-- Gris Oscuro -->
                <div class="flex flex-col items-center">
                    <div class="w-24 h-24 sm:w-28 sm:h-28 rounded-xl mb-2" style="background-color: var(--pantone-446c);"></div>
                    <span class="text-center text-white">Gris oscuro</span>
                    <span class="text-center text-white">PANTONE 446 C</span>
                </div>
                <!-- Gris Claro -->
                <div class="flex flex-col items-center">
                    <div class="w-24 h-24 sm:w-28 sm:h-28 rounded-xl mb-2" style="background-color: var(--pantone-649c);"></div>
                    <span class="text-center text-white">Gris claro</span>
                    <span class="text-center text-white">PANTONE 649 C</span>
                </div>
            </div>
            <p class="mt-8 text-base md:text-lg text-center leading-relaxed">
                La paleta principal de Grupo SURA está compuesta por el Azul Profundo, el Blanco y el Aqua. A estos 3 colores se suman el Gris Oscuro y el Gris Claro como colores de apoyo. Estos 2 colores son para uso exclusivo en cuerpos de texto y para fondos con degradado.
            </p>
            <div class="mt-8 flex flex-col sm:flex-row justify-center items-center gap-6">
                <!-- Espacio para dos imágenes -->
                <img src="https://i.pinimg.com/736x/56/88/d1/5688d1a1bb1aa746310cd58efa088ddd.jpg" class="w-full sm:w-1/2 h-auto rounded-lg" />
                <img src="https://i.pinimg.com/736x/d1/19/ea/d119ea1e9749b50a3fee9217f81bb730.jpg" class="w-full sm:w-1/2 h-auto rounded-lg" />
            </div>
        </div>

        <!-- Sección Tipografía -->
        <div class="bg-pantone-632c p-8 rounded-xl shadow-lg text-black">
            <h2 class="text-3xl font-bold barlow-medium text-pantone-286c text-center mb-4">
                Tipografía
            </h2>
            <div class="text-center">
                <p class="text-base md:text-lg leading-relaxed">
                    SURA Sans fue diseñada exclusivamente para la marca, cuenta con una personalidad única que refleja los valores de la marca.
                </p>
                <div class="mt-4 text-left mx-auto max-w-xl space-y-4">
                    <p>
                        <span class="font-bold">1.</span> Es fundamental trabajar con titulares de gran tamaño (al menos el doble del tamaño del texto del párrafo; por ejemplo, si el párrafo está en un tamaño de 12 puntos, el título deberá tener al menos 24 puntos).
                    </p>
                    <p>
                        <span class="font-bold">2.</span> En los textos siempre es recomendable resaltar palabras o frases clave en <span class="font-bold">negrita (bold)</span> para destacar su importancia.
                    </p>
                </div>
            </div>
            <div class="mt-8 flex flex-col sm:flex-row justify-center items-center gap-6">
                <!-- Espacio para dos imágenes -->
                <img src="https://i.pinimg.com/736x/1d/2c/23/1d2c23e6652adfc865eebc5937975ea6.jpg" class="w-full sm:w-1/2 h-auto rounded-lg" />
                <img src="https://i.pinimg.com/736x/7f/46/5c/7f465c72aa036d081e0a94051dc4d77d.jpg" class="w-full sm:w-1/2 h-auto rounded-lg" />
            </div>
        </div>

    </div>
</body>

</html>
