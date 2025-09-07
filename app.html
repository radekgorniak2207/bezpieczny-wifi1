<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Analizator Bezpieczeństwa Wi-Fi</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 flex items-center justify-center min-h-screen p-4">

    <div id="app" class="bg-white p-8 rounded-2xl shadow-lg w-full max-w-md text-center transform transition-transform duration-300 hover:scale-105">
        <h1 class="text-3xl font-bold mb-4 text-gray-800">Analizator Bezpieczeństwa Wi-Fi</h1>
        <p class="text-gray-600 mb-6">Wprowadź nazwę sieci Wi-Fi, aby sprawdzić jej poziom bezpieczeństwa.</p>
        
        <input type="text" id="networkName" placeholder="Nazwa sieci Wi-Fi..." class="w-full p-3 mb-4 rounded-lg border-2 border-gray-300 focus:outline-none focus:border-blue-500 transition duration-200">
        
        <button id="checkButton" class="bg-blue-500 text-white font-bold py-3 px-6 rounded-full shadow-md hover:bg-blue-600 transition-colors duration-200 ease-in-out transform hover:scale-105">
            Sprawdź bezpieczeństwo
        </button>
        
        <div id="result" class="mt-8 p-6 rounded-xl border-4 transition-all duration-300">
            <p id="statusMessage" class="font-semibold text-lg"></p>
        </div>
    </div>

    <script>
        document.getElementById('checkButton').addEventListener('click', () => {
            const networkName = document.getElementById('networkName').value.trim();
            const resultDiv = document.getElementById('result');
            const statusMessage = document.getElementById('statusMessage');

            if (networkName === '') {
                statusMessage.textContent = 'Proszę wprowadzić nazwę sieci.';
                resultDiv.className = 'mt-8 p-6 rounded-xl border-4 border-gray-400 bg-gray-200 transition-all duration-300';
                return;
            }

            // Symulacja sprawdzania bezpieczeństwa
            resultDiv.className = 'mt-8 p-6 rounded-xl border-4 border-yellow-500 bg-yellow-100 transition-all duration-300 animate-pulse';
            statusMessage.textContent = `Analizuję sieć '${networkName}'...`;

            setTimeout(() => {
                const lowerCaseName = networkName.toLowerCase();
                if (lowerCaseName.includes("open") || lowerCaseName.includes("public") || lowerCaseName.includes("guest") || lowerCaseName.includes("niezabezpieczona")) {
                    statusMessage.innerHTML = `**Status sieci: NIEZABEZPIECZONA**<br><br>Ta sieć jest niezabezpieczona. Twoje dane mogą być narażone na ryzyko. Zalecamy natychmiastowe użycie VPN!`;
                    resultDiv.className = 'mt-8 p-6 rounded-xl border-4 border-red-500 bg-red-100 transition-all duration-300 shadow-md';
                } else {
                    statusMessage.innerHTML = `**Status sieci: BEZPIECZNA**<br><br>Ta sieć wydaje się być bezpieczna. Pamiętaj jednak o zasadach ostrożności w każdej publicznej sieci.`;
                    resultDiv.className = 'mt-8 p-6 rounded-xl border-4 border-green-500 bg-green-100 transition-all duration-300 shadow-md';
                }
            }, 2000);
        });
    </script>
</body>
</html>
