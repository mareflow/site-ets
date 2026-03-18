<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Del Diagnóstico al Lucro | Turbo Masterclass</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&family=Orbitron:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        .font-brand {
            font-family: 'Orbitron', sans-serif;
        }
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0a0f1d;
        }
        ::-webkit-scrollbar-thumb {
            background: #1e293b;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #2563eb;
        }
    </style>
</head>
<body class="bg-[#0a0f1d] text-white selection:bg-blue-600 selection:text-white">

    <!-- Navbar -->
    <nav id="navbar" class="fixed top-0 left-0 right-0 z-50 transition-all duration-300 bg-transparent py-6">
        <div class="container mx-auto px-6 flex justify-between items-center">
            <div class="flex items-center gap-2">
                <div class="w-10 h-10 bg-blue-600 rounded-lg flex items-center justify-center font-bold text-xl rotate-12 shadow-lg shadow-blue-500/20">
                    <span class="text-white">E</span>
                </div>
                <span class="font-brand text-xl font-bold tracking-tighter text-white">ETS <span class="text-blue-500">EDUCACIÓN</span></span>
            </div>
            
            <div class="hidden md:flex items-center gap-8 text-sm font-medium">
                <a href="#metodo" class="text-slate-300 hover:text-white transition-colors">El Método</a>
                <a href="#modulos" class="text-slate-300 hover:text-white transition-colors">Contenido</a>
                <a href="#mentor" class="text-slate-300 hover:text-white transition-colors">Mentor</a>
                <a href="#inscripcion" class="bg-blue-500 hover:bg-blue-400 text-white px-6 py-2.5 rounded-full transition-all shadow-lg shadow-blue-500/40 font-bold uppercase tracking-wider text-xs">
                    ¡Inscribirme Ahora!
                </a>
            </div>
        </div>
    </nav>

    <main>
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 md:pt-48 md:pb-32 overflow-hidden bg-[#0a0f1d]">
            <div class="absolute top-0 left-1/2 -translate-x-1/2 w-full h-full -z-10 opacity-30">
                <div class="absolute top-[-10%] left-[-10%] w-[50%] h-[50%] bg-blue-900 blur-[140px] rounded-full"></div>
                <div class="absolute bottom-[-10%] right-[-10%] w-[40%] h-[40%] bg-blue-700 blur-[120px] rounded-full"></div>
                <div class="absolute top-[20%] right-[10%] w-[20%] h-[20%] bg-blue-400/10 blur-[100px] rounded-full"></div>
            </div>

            <div class="container mx-auto px-6 text-center">
                <div class="inline-block px-4 py-1.5 mb-6 rounded-full border border-blue-500/30 bg-blue-500/10 text-blue-400 text-sm font-bold tracking-widest uppercase">
                    Masterclass Internacional 2024
                </div>
                
                <h1 class="text-4xl md:text-7xl font-brand font-bold mb-8 leading-tight tracking-tight text-white uppercase">
                    Del Diagnóstico al <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-300 to-blue-600">LUCRO</span>
                </h1>
                
                <p class="text-lg md:text-2xl text-slate-400 max-w-4xl mx-auto mb-10 leading-relaxed">
                    Domina la nueva ola de vehículos turboalimentados. Deja de adivinar y conviértete en un <strong>técnico de referencia</strong> con resultados reales en tu taller.
                </p>

                <div class="flex flex-col md:flex-row gap-4 justify-center items-center">
                    <a href="#inscripcion" class="w-full md:w-auto px-10 py-5 bg-blue-500 hover:bg-blue-400 text-white rounded-xl font-bold text-lg transition-all transform hover:scale-105 shadow-2xl shadow-blue-500/40 border-b-4 border-blue-700">
                        QUIERO EMPEZAR AHORA
                    </a>
                    <a href="#metodo" class="w-full md:w-auto px-10 py-5 border border-slate-700 hover:bg-slate-800 text-slate-300 rounded-xl font-bold text-lg transition-all">
                        Ver el Método "Siga el Flujo"
                    </a>
                </div>

                <div class="mt-16 relative max-w-4xl mx-auto">
                    <div class="aspect-video bg-slate-900 rounded-3xl border border-blue-900/50 overflow-hidden shadow-2xl relative group">
                        <div class="absolute inset-0 bg-blue-950/40 z-10"></div>
                        <img 
                            src="https://images.unsplash.com/photo-1486006396113-ad7302ff172c?q=80&w=1200&auto=format&fit=crop" 
                            alt="Especialista en turbos" 
                            class="w-full h-full object-cover opacity-80 group-hover:scale-105 transition-transform duration-700"
                        />
                        <div class="absolute inset-0 flex items-center justify-center z-20">
                            <button class="w-20 h-20 bg-blue-600 rounded-full flex items-center justify-center shadow-xl hover:bg-blue-500 transition-colors animate-pulse border-4 border-white/10">
                                <svg class="w-10 h-10 text-white fill-current ml-1" viewBox="0 0 24 24">
                                    <path d="M8 5v14l11-7z" />
                                </svg>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Quality Markers -->
        <section class="py-12 bg-[#0d1526] border-y border-blue-900/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-blue-900 text-[10px] font-brand uppercase tracking-[0.5em] mb-10 font-bold">Tecnología y Precisión Internacional</p>
                <div class="flex flex-wrap justify-center gap-8 md:gap-20 items-center opacity-40 grayscale hover:grayscale-0 transition-all duration-700">
                    <span class="font-brand text-xl font-bold text-slate-400">GARRETT</span>
                    <span class="font-brand text-xl font-bold text-slate-400">BORGWARNER</span>
                    <span class="font-brand text-xl font-bold text-slate-400">HOLSET</span>
                    <span class="font-brand text-xl font-bold text-slate-400">IHI TURBO</span>
                    <span class="font-brand text-xl font-bold text-slate-400">MITSUBISHI</span>
                </div>
            </div>
        </section>

        <!-- Features Section -->
        <section id="metodo" class="py-24 bg-[#0a0f1d]">
            <div class="container mx-auto px-6">
                <div class="text-center mb-16">
                    <h2 class="text-3xl md:text-5xl font-brand font-bold mb-6 text-white">¿Por qué este es el <span class="text-blue-500">Último Curso</span> que necesitas?</h2>
                    <p class="text-slate-400 text-lg max-w-3xl mx-auto">
                        El mercado diesel ligero es la mayor oportunidad de negocio de los próximos años. Quien domine el turbo, domina el taller.
                    </p>
                </div>

                <div class="grid lg:grid-cols-3 gap-8">
                    <div class="p-10 rounded-[2rem] bg-slate-900/50 border border-blue-900/30 hover:border-blue-500/50 transition-all group">
                        <div class="w-14 h-14 bg-blue-600/10 rounded-2xl flex items-center justify-center text-blue-500 text-2xl mb-8 group-hover:bg-blue-600 group-hover:text-white transition-all">
                            🛠️
                        </div>
                        <h3 class="text-2xl font-bold mb-4 text-white font-brand leading-tight">Diagnósticos por Adivinanza</h3>
                        <p class="text-slate-400 leading-relaxed">Dejas de perder dinero cambiando piezas innecesarias esperando que el problema se solucione.</p>
                    </div>
                    <div class="p-10 rounded-[2rem] bg-slate-900/50 border border-blue-900/30 hover:border-blue-500/50 transition-all group">
                        <div class="w-14 h-14 bg-blue-600/10 rounded-2xl flex items-center justify-center text-blue-500 text-2xl mb-8 group-hover:bg-blue-600 group-hover:text-white transition-all">
                            📈
                        </div>
                        <h3 class="text-2xl font-bold mb-4 text-white font-brand leading-tight">El 'Miedo' al Biturbo</h3>
                        <p class="text-slate-400 leading-relaxed">Domina sistemas complejos que otros mecánicos rechazan, cobrando lo que realmente vale tu trabajo.</p>
                    </div>
                    <div class="p-10 rounded-[2rem] bg-slate-900/50 border border-blue-900/30 hover:border-blue-500/50 transition-all group">
                        <div class="w-14 h-14 bg-blue-600/10 rounded-2xl flex items-center justify-center text-blue-500 text-2xl mb-8 group-hover:bg-blue-600 group-hover:text-white transition-all">
                            ⚡
                        </div>
                        <h3 class="text-2xl font-bold mb-4 text-white font-brand leading-tight">Baja Facturación</h3>
                        <p class="text-slate-400 leading-relaxed">Pasa de ser un 'cambiapiezas' a un consultor técnico especializado en alta potencia.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Partnership Section -->
        <section class="py-24 bg-[#0d1526] border-y border-blue-900/10">
            <div class="container mx-auto px-6">
                <div class="flex flex-col lg:flex-row items-center gap-16">
                    <div class="lg:w-1/2">
                        <div class="inline-block px-4 py-1 bg-blue-600/20 text-blue-400 rounded-full text-xs font-bold mb-6 tracking-widest border border-blue-500/20 uppercase">
                            Alianza Internacional
                        </div>
                        <h2 class="text-4xl md:text-5xl font-brand font-bold mb-8 leading-tight text-white uppercase tracking-tighter">
                            Referencia en <span class="text-blue-500">Argentina</span>
                        </h2>
                        <p class="text-slate-400 text-xl mb-8 leading-relaxed">
                            Nos enorgullece nuestra alianza estratégica con <strong>Turbolager</strong>, el máximo referente en el mercado argentino de turbocompresores.
                        </p>
                        <div class="p-8 bg-blue-600/5 border border-blue-500/20 rounded-3xl backdrop-blur-sm">
                            <p class="text-white italic text-lg leading-relaxed">
                                "Turbolager no solo es un socio, sino que formó parte activa de nuestra <strong>Inmersión Técnica en Brasil</strong>."
                            </p>
                        </div>
                    </div>
                    <div class="lg:w-1/2 relative">
                        <div class="grid grid-cols-2 gap-4">
                            <div class="space-y-4 pt-8">
                                <img src="https://images.unsplash.com/photo-1581092160607-ee22621dd758?q=80&w=400&auto=format&fit=crop" class="rounded-2xl border border-blue-900/30 shadow-2xl" />
                                <img src="https://images.unsplash.com/photo-1504917595217-d4dc5ebe6122?q=80&w=400&auto=format&fit=crop" class="rounded-2xl border border-blue-900/30 shadow-2xl" />
                            </div>
                            <div class="space-y-4">
                                <img src="https://images.unsplash.com/photo-1619641782842-833be2dede65?q=80&w=400&auto=format&fit=crop" class="rounded-2xl border border-blue-900/30 shadow-2xl" />
                                <div class="bg-blue-600 aspect-square rounded-2xl flex flex-col items-center justify-center p-6 text-center shadow-xl shadow-blue-600/20">
                                    <span class="text-white font-brand font-bold text-4xl mb-2">ARG</span>
                                    <p class="text-blue-100 text-[10px] font-bold uppercase tracking-widest">Validado en Argentina y Uruguay</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Modules Section -->
        <section id="modulos" class="py-24 bg-[#0a0f1d] relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-16">
                    <h2 class="text-3xl md:text-5xl font-brand font-bold mb-6 text-white uppercase tracking-tighter">
                        Del Diagnóstico al <span class="text-blue-500">Lucro</span>
                    </h2>
                    <p class="text-slate-400 max-w-2xl mx-auto text-lg">
                        15 Clases de alto nivel con enfoque en el mercado rioplatense.
                    </p>
                </div>
                <div id="lessons-grid" class="grid md:grid-cols-2 lg:grid-cols-3 gap-6 max-w-7xl mx-auto">
                    <!-- Lessons injected by script -->
                </div>
            </div>
        </section>

        <!-- Mentor Section -->
        <section id="mentor" class="py-24 bg-[#0d1526] border-y border-blue-900/10">
            <div class="container mx-auto px-6">
                <div class="flex flex-col md:flex-row gap-16 items-center">
                    <div class="relative w-full max-w-md">
                        <img src="https://images.unsplash.com/photo-1590650153855-d9e808231d41?q=80&w=800&auto=format&fit=crop" class="rounded-[3rem] shadow-2xl relative z-10 border border-blue-900/50" />
                    </div>
                    <div class="max-w-xl">
                        <p class="text-blue-500 font-bold tracking-[0.3em] uppercase mb-4 text-xs">Director Técnico & Socio</p>
                        <h2 class="text-4xl md:text-5xl font-brand font-bold mb-8 text-white uppercase tracking-tighter">Marcus Einloft Pereira</h2>
                        <div class="space-y-6 text-slate-400 text-lg leading-relaxed">
                            <p>Director Técnico y socio de <strong>Turbo Sul</strong>, grupo líder con 39 años de trayectoria.</p>
                            <blockquote class="border-l-4 border-blue-600 pl-6 py-4 text-white italic font-medium bg-blue-600/5 rounded-r-2xl">
                                "Tras 50,000 diagnósticos, he refinado el método definitivo."
                            </blockquote>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Pricing Section -->
        <section id="inscripcion" class="py-24 bg-gradient-to-b from-[#0a0f1d] to-[#050810]">
            <div class="container mx-auto px-6">
                <div class="max-w-5xl mx-auto bg-[#0d1526] rounded-[3rem] border border-blue-900/50 overflow-hidden shadow-2xl">
                    <div class="grid lg:grid-cols-5">
                        <div class="lg:col-span-3 p-10 md:p-16">
                            <h2 class="text-3xl md:text-5xl font-brand font-bold mb-6 text-white uppercase tracking-tighter">Oferta de <span class="text-blue-500">Lanzamiento</span></h2>
                            <div class="space-y-6">
                                <div class="flex items-center gap-4"><div class="w-10 h-10 rounded-full bg-blue-600 flex items-center justify-center text-white font-bold">1</div><p class="text-white font-bold">9 Diagramas Exclusivos</p></div>
                                <div class="flex items-center gap-4"><div class="w-10 h-10 rounded-full bg-blue-600 flex items-center justify-center text-white font-bold">2</div><p class="text-white font-bold">Cuaderno de Actividades</p></div>
                                <div class="flex items-center gap-4"><div class="w-10 h-10 rounded-full bg-blue-600 flex items-center justify-center text-white font-bold">3</div><p class="text-white font-bold">Acceso VIP Aula Zoom</p></div>
                            </div>
                        </div>
                        <div class="lg:col-span-2 bg-[#141d31] p-10 md:p-16 flex flex-col justify-center items-center text-center">
                            <p class="text-slate-500 line-through text-xl mb-2 font-medium">$197 USD</p>
                            <div class="mb-8"><span class="text-6xl font-brand font-bold text-white tracking-tighter">$97</span><span class="text-xl font-bold text-blue-500 ml-2">USD</span></div>
                            <a href="#" class="w-full bg-blue-500 hover:bg-blue-400 text-white py-6 rounded-2xl font-brand font-bold text-xl transition-all shadow-2xl shadow-blue-500/40 transform hover:-translate-y-1 block">¡RESERVAR MI LUGAR!</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="py-20 bg-[#050810] border-t border-blue-900/20 text-center">
        <div class="container mx-auto px-6">
            <span class="font-brand text-xl font-bold tracking-tighter text-white">ETS <span class="text-blue-500">EDUCACIÓN</span></span>
            <p class="text-slate-700 text-[10px] mt-8 uppercase tracking-widest">© 2024 ETS Educación. Todos los derechos reservados.</p>
        </div>
    </footer>

    <script>
        // Navbar Scroll Effect
        const navbar = document.getElementById('navbar');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                navbar.classList.remove('bg-transparent', 'py-6');
                navbar.classList.add('bg-[#0a0f1d]/90', 'backdrop-blur-md', 'py-3', 'shadow-xl', 'border-b', 'border-blue-900/30');
            } else {
                navbar.classList.add('bg-transparent', 'py-6');
                navbar.classList.remove('bg-[#0a0f1d]/90', 'backdrop-blur-md', 'py-3', 'shadow-xl', 'border-b', 'border-blue-900/30');
            }
        });

        // Lessons Data
        const lessons = [
            { id: "01", title: "Diagnóstico de Potencia", hasPractice: false, topics: ["Downsizing", "Relación Motor-Turbo"] },
            { id: "02", title: "Medición de Presión", hasPractice: true, topics: ["Analógica x Digital", "Práctica: Test de Rodaje"] },
            { id: "03", title: "Componentes Principales", hasPractice: false, topics: ["Caracol Caliente", "Carcasa Compresora"] },
            { id: "04", title: "Flujos Térmicos", hasPractice: true, topics: ["Intercooler", "Práctica: Método SIGA EL FLUJO"] },
            { id: "05", title: "Flujo de Aire Maestro", hasPractice: false, topics: ["Fugas", "Flujo Inverso"] },
            { id: "06", title: "Turbos con Wastegate", hasPractice: true, topics: ["Vacío y Presión", "Práctica: Identificación"] },
            { id: "07", title: "Geometría Variable (VGT)", hasPractice: true, topics: ["Posición de Potencia", "Práctica: Accionamiento"] },
            { id: "08", title: "Sistemas Biturbo", hasPractice: true, topics: ["Secuenciales vs Paralelos", "Práctica: Diagnósticos"] },
            { id: "09", title: "Sistemas de Control", hasPractice: false, topics: ["MAP e MAF", "Integración de Señales"] },
            { id: "10", title: "Solenoides de Presión", hasPractice: true, topics: ["Overboost", "Práctica: Diagnóstico Real"] },
            { id: "11", title: "Solenoides de Vacío", hasPractice: true, topics: ["Medición Crítica", "Práctica: Test Vehículo"] },
            { id: "12", title: "Diagnósticos Maestros", hasPractice: false, topics: ["3 Cases reales", "Metodología Rapidez"] },
            { id: "13", title: "Actuadores Electrónicos", hasPractice: false, topics: ["Control Electrónico", "Sensores PVF"] },
            { id: "14", title: "Válvulas By-Pass", hasPractice: true, topics: ["Funcionamiento", "Práctica: Dicas de Oro"] },
            { id: "15", title: "Bono: Super Clase", hasPractice: false, topics: ["Esquemas Exclusivos", "Guía Técnica Final"] }
        ];

        const grid = document.getElementById('lessons-grid');
        lessons.forEach(lesson => {
            const card = document.createElement('div');
            card.className = 'group p-6 rounded-2xl bg-slate-900/40 border border-blue-900/20 hover:border-blue-500/40 transition-all duration-300 backdrop-blur-sm flex flex-col relative overflow-hidden';
            
            let practiceBadge = lesson.hasPractice ? `<div class="absolute top-0 right-0 bg-blue-600 text-white text-[8px] font-bold px-3 py-1 rounded-bl-xl uppercase tracking-widest">Incluye Práctica</div>` : '';

            const topicsHtml = lesson.topics.map(topic => `<li class="text-xs flex items-center gap-2 text-slate-500"><span class="w-1 h-1 rounded-full bg-blue-900"></span>${topic}</li>`).join('');

            card.innerHTML = `${practiceBadge}<span class="text-xs font-brand font-bold text-blue-500/50 mb-4">CLASE ${lesson.id}</span><h3 class="text-lg font-bold text-white mb-4 font-brand tracking-tight group-hover:text-blue-400 transition-colors">${lesson.title}</h3><ul class="space-y-2 mt-auto">${topicsHtml}</ul>`;
            grid.appendChild(card);
        });
    </script>
</body>
</html>
