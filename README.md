<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FAQ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #1a1a1a; /* Colore nero al 90% */
            color: #fff; /* Testo bianco per contrasto */
        }
        h1 {
            color: #fff;
        }
        .faq-section {
            margin-bottom: 20px;
        }
        .faq-question {
            cursor: pointer;
            margin: 5px 0;
            padding: 10px;
            background-color: #333;
            border: 1px solid #ccc;
            color: #fff;
        }
        .faq-answer {
            display: none;
            padding: 10px;
            border-left: 3px solid #fff;
            background-color: #444;
            color: #fff;
        }
    </style>
</head>

<body>
    <h1>Domande Frequenti</h1>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(0)">1 Q.: Dove posso trovare delle liste IPTV?</div>
        <div class="faq-answer" id="answer-0">Liste IPTV stabili sono difficili da trovare, ma ti possiamo consigliare un paio di anno che fanno al caso tuo, digita !addons sul canale telegram e leggi i nostri consigli.</div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(1)">2 Q.: Non trovo addons che trattano sport, avete da suggermene qualcuna?</div>
        <div class="faq-answer" id="answer-1">Basta vedere quelli che trattano eventi sportivi o eventi live.</div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(2)">3 Q.: Hai problemi con un determinato addon?</div>
        <div class="faq-answer" id="answer-2">Prima di cercare qui, prova a chiedere nel gruppo di supporto (scrivi nel gruppo Kodiitalia !addons). Se nella guida non trovi l'addon non è detto che qualcuno nel gruppo possa esservi di aiuto.</div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(3)">4 Q.: Hai problemi con un addon, ma hai installato una mod o un pack?</div>
        <div class="faq-answer" id="answer-3">Disinstalla tutto e ricomincia da capo seguendo i nostri consigli. Tutto questo perche mod e pack molte volte e a lungo andare compromettono il funzionamento di kodi.</div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(4)">5 Q.: Installando un addon, ti mostra impossibile installare, dipendenza di phyton 2.0 non soddisfatta? </div>
        <div class="faq-answer" id="answer-4">Hai ancora kodi 18.x installa l'ultima versione di kodi dal sito kodi.tv.</div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(5)">6 Q.: Vuoi installare l'ultima versione di kodi? </div>
        <div class="faq-answer" id="answer-5">Al momento l'unica alternativa è di installarlo dal sito ufficiale kodi.tv/download. Purtroppo al momento gli standard di Google sono fissati al target api 30 ovvero Android 11 mentre APK di Kodi ha ancora il target api 29 di Android 10, non superando questo requisito non può essere caricato/approvato nello store.</div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(6)">7 Q.: Come si installa kodi su iOS? </div>
        <div class="faq-answer" id="answer-6">Per iPhone hai tre opzioni:
          - jailbreak
          - paghi
          - metodo alt store</div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(7)">8 Q.: Ho appena acquistato un box e c'è l'app Kodi preinstallata, va bene? </div>
        <div class="faq-answer" id="answer-7">In linea di massima, consigliamo di installare sempre una versione ufficiale, quelle preinstallate dalla casa madre sono sempre app modificate e questo non consente a noi di escludere che in futuro possiate avere problemi.</div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(8)">9 Q.: Ho installato e avviato per la prima volta kodi sul mio dispositivo, ma lo schermo è nero, come mai? </div>
        <div class="faq-answer" id="answer-8">Se hai un dispositivo android devi settare il refresh del tuo schermo a 60 mHz.x</div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(9)"></div>
        <div class="faq-answer" id="answer-9"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(10)"></div>
        <div class="faq-answer" id="answer-10"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(11)"></div>
        <div class="faq-answer" id="answer-11"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(12)"></div>
        <div class="faq-answer" id="answer-12"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(13)"></div>
        <div class="faq-answer" id="answer-13"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(14)"></div>
        <div class="faq-answer" id="answer-14"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(15)"></div>
        <div class="faq-answer" id="answer-15"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(16)"></div>
        <div class="faq-answer" id="answer-16"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(17)"></div>
        <div class="faq-answer" id="answer-17"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(18)"></div>
        <div class="faq-answer" id="answer-18"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(19)"></div>
        <div class="faq-answer" id="answer-19"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(20)"></div>
        <div class="faq-answer" id="answer-20"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(21)"></div>
        <div class="faq-answer" id="answer-21"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(22)"></div>
        <div class="faq-answer" id="answer-22"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(23)"></div>
        <div class="faq-answer" id="answer-23"></div>
    </div>
    
    <div class="faq-section">
        <div class="faq-question" onclick="toggleAnswer(24)"></div>
        <div class="faq-answer" id="answer-24"></div>
    </div>
    
    <script>
        function toggleAnswer(index) {
            var answer = document.getElementById('answer-' + index);
            if (answer.style.display === 'none' || answer.style.display === '') {
                answer.style.display = 'block';
            } else {
                answer.style.display = 'none';
            }
        }
    </script>
</body>
</html>
