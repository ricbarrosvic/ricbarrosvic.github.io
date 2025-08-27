<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apresentação do Projeto SIOC</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            overflow: hidden;
            background-color: #f1f1f1; /* Fundo cinza claro */
            cursor: none; /* Esconde o cursor do mouse para uma apresentação mais limpa */
        }
        .slide {
            display: none;
            opacity: 0;
            transition: opacity 0.6s ease-in-out;
            height: 100vh;
            width: 100vw;
        }
        .slide.active {
            display: flex;
            opacity: 1;
        }
        .slide-content {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 2rem;
            width: 100%;
            height: 100%;
        }
        .dark-card {
            background-color: #1f2937; /* Cinza escuro */
            border-radius: 1rem;
            padding: 2rem;
            box-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
            transition: transform 0.3s;
            width: 100%;
            max-width: 320px;
            height: 290px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        .dark-card:hover {
            transform: translateY(-10px);
        }
        .geometric-background {
            background-color: #f3f4f6;
            background-image:
                linear-gradient(135deg, #c9a86b 1px, transparent 1px),
                linear-gradient(225deg, #c9a86b 1px, transparent 1px);
            background-size: 30px 30px;
        }
    </style>
</head>
<body>

    <!-- Slide 1: Título -->
    <div id="slide1" class="slide active">
        <div class="slide-content geometric-background">
            <div class="bg-gray-900 p-10 md:p-16 rounded-lg shadow-2xl">
                <h1 class="text-5xl md:text-6xl font-bold text-amber-400 mb-4">Projeto de Softwares para Clínica Odontológica</h1>
                <p class="text-xl text-slate-300 mt-8">Um projeto de Henrique Barros Vicente</p>
            </div>
        </div>
    </div>

    <!-- Slide 2: Objetivo -->
    <div id="slide2" class="slide">
        <div class="slide-content">
            <h2 class="text-4xl font-bold text-gray-800 mb-16">Objetivo do Projeto</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 w-full max-w-5xl">
                <div class="dark-card">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-20 w-20 text-amber-400 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z" /><path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" /></svg>
                    <h3 class="text-xl font-semibold text-slate-100">Otimizar Processos</h3>
                    <p class="text-slate-300 mt-2">Automatizar tarefas e centralizar a gestão da clínica.</p>
                </div>
                <div class="dark-card">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-20 w-20 text-amber-400 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M13 10V3L4 14h7v7l9-11h-7z" /></svg>
                    <h3 class="text-xl font-semibold text-slate-100">Aumentar a Eficiência</h3>
                    <p class="text-slate-300 mt-2">Reduzir tempo em tarefas administrativas e focar no atendimento.</p>
                </div>
                <div class="dark-card">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-20 w-20 text-amber-400 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M14.828 14.828a4 4 0 01-5.656 0M9 10h.01M15 10h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                    <h3 class="text-xl font-semibold text-slate-100">Melhorar a Experiência</h3>
                    <p class="text-slate-300 mt-2">Oferecer uma jornada digital, ágil e transparente para o paciente.</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Slide 3: Proposta Atual -->
    <div id="slide3" class="slide">
        <div class="slide-content">
            <h2 class="text-4xl font-bold text-gray-800 mb-16">Proposta Atual: A Clínica Conectada</h2>
            <div class="relative w-full max-w-4xl flex items-center justify-center" style="height: 400px;">
                <svg class="absolute w-full h-full top-0 left-0 z-0" width="100%" height="100%">
                    <line x1="50%" y1="50%" x2="25%" y2="18%" stroke="#c9a86b" stroke-width="2"></line>
                    <line x1="50%" y1="50%" x2="82%" y2="50%" stroke="#c9a86b" stroke-width="2"></line>
                    <line x1="50%" y1="50%" x2="25%" y2="82%" stroke="#c9a86b" stroke-width="2"></line>
                    <line x1="50%" y1="50%" x2="18%" y2="50%" stroke="#c9a86b" stroke-width="2"></line>
                </svg>
                <div class="bg-amber-400 text-gray-900 p-8 rounded-full shadow-lg z-10 flex flex-col items-center">
                     <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" /></svg>
                    <span class="font-bold mt-2 text-lg">SIOC</span>
                </div>
                <div class="absolute top-0 left-1/4 -translate-x-1/2 text-center z-10">
                    <div class="bg-gray-800 p-4 rounded-full shadow-md inline-block"><svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 text-amber-400" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" /></svg></div>
                    <p class="font-semibold mt-2 text-gray-800 bg-white/70 backdrop-blur-sm px-2 rounded">Agendamento Online</p>
                </div>
                <div class="absolute right-0 top-1/2 -translate-y-1/2 -mr-16 text-center z-10">
                    <div class="bg-gray-800 p-4 rounded-full shadow-md inline-block"><svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 text-amber-400" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" /></svg></div>
                    <p class="font-semibold mt-2 text-gray-800 bg-white/70 backdrop-blur-sm px-2 rounded">Prontuário Digital</p>
                </div>
                <div class="absolute bottom-0 left-1/4 -translate-x-1/2 text-center z-10">
                    <div class="bg-gray-800 p-4 rounded-full shadow-md inline-block"><svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 text-amber-400" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M17 9V7a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2m2 4h10a2 2 0 002-2v-6a2 2 0 00-2-2H9a2 2 0 00-2 2v6a2 2 0 002 2zm7-5a2 2 0 11-4 0 2 2 0 014 0z" /></svg></div>
                    <p class="font-semibold mt-2 text-gray-800 bg-white/70 backdrop-blur-sm px-2 rounded">Gestão Financeira</p>
                </div>
                <div class="absolute left-0 top-1/2 -translate-y-1/2 -ml-16 text-center z-10">
                    <div class="bg-gray-800 p-4 rounded-full shadow-md inline-block"><svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 text-amber-400" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" /></svg></div>
                    <p class="font-semibold mt-2 text-gray-800 bg-white/70 backdrop-blur-sm px-2 rounded">Relatórios</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Slide 4: Proposta Futura -->
    <div id="slide4" class="slide">
        <div class="slide-content">
            <h2 class="text-4xl font-bold text-gray-800 mb-16">Proposta Futura: A Evolução Inteligente</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 w-full max-w-5xl">
                <div class="dark-card">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-20 w-20 text-amber-400 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" /></svg>
                    <h3 class="text-xl font-semibold text-slate-100">Inteligência Artificial</h3>
                    <p class="text-slate-300 mt-2">Auxílio em pré-diagnósticos e análise de dados para gestão.</p>
                </div>
                <div class="dark-card">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-20 w-20 text-amber-400 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z" /></svg>
                    <h3 class="text-xl font-semibold text-slate-100">Aplicativo do Paciente</h3>
                    <p class="text-slate-300 mt-2">Acesso a histórico, agendamentos e comunicação direta.</p>
                </div>
                <div class="dark-card">
                     <svg xmlns="http://www.w3.org/2000/svg" class="h-20 w-20 text-amber-400 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M3 15a4 4 0 004 4h9a5 5 0 10-.1-9.999 5.002 5.002 0 10-9.78 2.096A4.001 4.001 0 003 15z" /></svg>
                    <h3 class="text-xl font-semibold text-slate-100">Expansão em Nuvem</h3>
                    <p class="text-slate-300 mt-2">Plataforma escalável para atender múltiplas unidades da clínica.</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Slide 5: Benefícios -->
    <div id="slide5" class="slide">
        <div class="slide-content">
            <h2 class="text-4xl font-bold text-gray-800 mb-16">Benefícios</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 w-full max-w-5xl">
                <div class="dark-card border-2 border-amber-400">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-20 w-20 text-amber-400 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6" /></svg>
                    <h3 class="text-xl font-semibold text-slate-100">Para a Clínica</h3>
                    <p class="text-slate-300 mt-2">Maior produtividade, rentabilidade e organização.</p>
                </div>
                <div class="dark-card border-2 border-amber-400">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-20 w-20 text-amber-400 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path d="M14.121 14.121L19 19m-7-7l7-7m-7 7l-2.879 2.879M12 12L9.121 9.121M12 12l2.879-2.879M12 12L9.121 14.879m2.879-2.879l2.879 2.879M3 12a9 9 0 1118 0 9 9 0 01-18 0z" /></svg>
                    <h3 class="text-xl font-semibold text-slate-100">Para o Profissional</h3>
                    <p class="text-slate-300 mt-2">Menos burocracia, mais tempo para focar no atendimento clínico.</p>
                </div>
                <div class="dark-card border-2 border-amber-400">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-20 w-20 text-amber-400 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" /></svg>
                    <h3 class="text-xl font-semibold text-slate-100">Para o Paciente</h3>
                    <p class="text-slate-300 mt-2">Atendimento ágil, transparente e uma experiência de cuidado superior.</p>
                </div>
            </div>
             <p class="text-xl text-gray-700 mt-16 font-semibold">SIOC: Construindo a clínica odontológica do futuro.</p>
        </div>
    </div>

    <script>
        let currentSlide = 1;
        const totalSlides = 5;
        const slides = document.querySelectorAll('.slide');

        function showSlide(n) {
            slides.forEach(slide => slide.classList.remove('active'));
            document.getElementById(`slide${n}`).classList.add('active');
        }

        function nextSlide() {
            if (currentSlide < totalSlides) {
                currentSlide++;
            } else {
                currentSlide = 1; // Opcional: volta para o primeiro slide no final
            }
            showSlide(currentSlide);
        }

        function prevSlide() {
            if (currentSlide > 1) {
                currentSlide--;
            } else {
                currentSlide = totalSlides; // Opcional: vai para o último slide se estiver no primeiro
            }
            showSlide(currentSlide);
        }

        // Navegação pelo teclado
        document.addEventListener('keydown', (e) => {
            if (e.key === 'ArrowRight' || e.key === ' ') { // Avança com seta direita ou espaço
                nextSlide();
            } else if (e.key === 'ArrowLeft') {
                prevSlide();
            }
        });

        // Inicia a apresentação
        showSlide(currentSlide);
    </script>

</body>
</html>
