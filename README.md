<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ремонт стеклопластика в Краснодаре | Сэкономим до 90% стоимости новой емкости</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;800&display=swap');
        
        :root {
            scroll-behavior: smooth;
        }

        body { 
            font-family: 'Montserrat', sans-serif; 
        }

        .bg-accent { background-color: #f59e0b; }
        .text-accent { color: #f59e0b; }

        .hero-bg {
            background: linear-gradient(rgba(15, 23, 42, 0.85), rgba(15, 23, 42, 0.85)), 
                        url('https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?auto=format&fit=crop&w=1920&q=80');
            background-size: cover;
            background-position: center;
        }

        .floating {
            animation: floating 3s ease-in-out infinite;
        }

        @keyframes floating {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }

        .form-status-success {
            display: none;
            animation: fadeIn 0.5s ease forwards;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: scale(0.95); }
            to { opacity: 1; transform: scale(1); }
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900">

    <!-- Навигация -->
    <header class="fixed w-full z-50 bg-white/95 backdrop-blur-sm shadow-md transition-all duration-300" id="mainHeader">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <a href="#" class="flex items-center gap-2">
                <div class="bg-blue-600 p-2 rounded-lg">
                    <i class="fas fa-shield-virus text-white text-xl"></i>
                </div>
                <div class="leading-tight">
                    <span class="block font-extrabold text-xl uppercase tracking-tighter">Composite<span class="text-blue-600">Pro</span></span>
                    <span class="text-[10px] text-gray-500 font-bold uppercase tracking-widest italic">Работаем по ЮФО</span>
                </div>
            </a>
            
            <nav class="hidden lg:flex items-center gap-8 font-semibold text-sm uppercase tracking-wider">
                <a href="#services" class="hover:text-blue-600 transition">Услуги</a>
                <a href="#prices" class="hover:text-blue-600 transition">Цены</a>
                <a href="#gallery" class="hover:text-blue-600 transition">Работы</a>
                <a href="#contact" class="hover:text-blue-600 transition">Контакты</a>
            </nav>

            <div class="flex items-center gap-4">
                <div class="hidden sm:block text-right">
                    <a href="tel:+78610000000" class="block font-bold text-lg leading-none hover:text-blue-600 transition">+7 (861) 000-00-00</a>
                    <span class="text-[10px] text-green-600 font-bold uppercase tracking-widest">Перезвоним за 1 мин</span>
                </div>
                <button onclick="scrollToContact()" class="bg-blue-600 text-white px-5 py-2.5 rounded-xl font-bold hover:bg-blue-700 transition transform active:scale-95 shadow-lg shadow-blue-200">
                    Заказать выезд
                </button>
            </div>
        </div>
    </header>

    <!-- Главный экран -->
    <section class="hero-bg min-h-screen flex items-center pt-24 pb-12">
        <div class="container mx-auto px-4">
            <div class="flex flex-col lg:flex-row items-center gap-12">
                <div class="lg:w-7/12 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 bg-blue-600/30 border border-blue-400/30 text-blue-100 px-4 py-2 rounded-full mb-8">
                        <span class="relative flex h-3 w-3">
                            <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-blue-400 opacity-75"></span>
                            <span class="relative inline-flex rounded-full h-3 w-3 bg-blue-500"></span>
                        </span>
                        <span class="text-xs font-extrabold uppercase tracking-widest">Бригада в Краснодаре свободна</span>
                    </div>
                    
                    <h1 class="text-4xl md:text-6xl lg:text-7xl font-extrabold text-white mb-6 leading-[1.1]">
                        Ремонт емкостей <br><span class="text-blue-400 italic">с гарантией 3 года</span>
                    </h1>
                    
                    <p class="text-xl text-gray-300 mb-10 max-w-2xl leading-relaxed">
                        Профессиональное восстановление герметичности стеклопластиковых чаш бассейнов, баков КАС и септиков. Используем химстойкие смолы европейского качества.
                    </p>
                    
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-6 mb-12">
                        <div class="flex items-center gap-4 bg-white/5 p-4 rounded-2xl border border-white/10 backdrop-blur-sm">
                            <div class="text-accent text-3xl"><i class="fas fa-wallet"></i></div>
                            <div class="text-white text-sm font-semibold italic leading-snug">Дешевле замены <br>в 10 раз</div>
                        </div>
                        <div class="flex items-center gap-4 bg-white/5 p-4 rounded-2xl border border-white/10 backdrop-blur-sm">
                            <div class="text-accent text-3xl"><i class="fas fa-stopwatch"></i></div>
                            <div class="text-white text-sm font-semibold italic leading-snug">Ремонт на месте <br>за 1 рабочий день</div>
                        </div>
                    </div>
                </div>

                <!-- Форма -->
                <div class="lg:w-5/12 w-full max-w-md mx-auto">
                    <div class="bg-white p-8 rounded-[2rem] shadow-2xl relative overflow-hidden">
                        <div class="absolute -top-3 -right-3 bg-accent text-white font-black py-2 px-8 rounded-bl-2xl shadow-lg rotate-3">
                            АКЦИЯ: -15%
                        </div>
                        
                        <div id="heroFormContainer">
                            <h3 class="text-2xl font-bold mb-2 text-slate-900">Узнать стоимость</h3>
                            <p class="text-gray-500 text-sm mb-6 leading-snug">Заполните форму, и мастер рассчитает смету по фото в WhatsApp через 5-10 минут.</p>
                            
                            <form class="space-y-4" onsubmit="handleFormSubmit(event, 'heroFormContainer')">
                                <div>
                                    <input type="text" required placeholder="Ваше имя" class="w-full p-4 bg-gray-50 rounded-xl border border-gray-100 focus:border-blue-500 focus:ring-0 transition outline-none font-medium">
                                </div>
                                <div>
                                    <input type="tel" required placeholder="Ваш телефон" class="w-full p-4 bg-gray-50 rounded-xl border border-gray-100 focus:border-blue-500 focus:ring-0 transition outline-none font-medium">
                                </div>
                                <button type="submit" class="w-full bg-blue-600 text-white py-4 rounded-xl font-extrabold text-lg hover:bg-blue-700 transition shadow-xl shadow-blue-200 active:scale-95">
                                    Получить расчет бесплатно
                                </button>
                                <div class="flex items-center justify-center gap-2 text-[10px] text-gray-400 font-medium">
                                    <i class="fas fa-lock"></i> Данные под защитой
                                </div>
                            </form>
                        </div>

                        <div id="heroFormContainerSuccess" class="form-status-success py-10 text-center">
                            <div class="w-20 h-20 bg-green-100 text-green-600 rounded-full flex items-center justify-center mx-auto mb-6 text-4xl">
                                <i class="fas fa-check"></i>
                            </div>
                            <h3 class="text-2xl font-bold mb-2">Заявка принята!</h3>
                            <p class="text-gray-500">Мастер уже изучает ваш запрос и скоро свяжется с вами.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Услуги -->
    <section id="services" class="py-24 bg-white relative">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-end mb-16 gap-6">
                <div class="max-w-2xl">
                    <span class="text-blue-600 font-bold uppercase tracking-widest text-sm mb-2 block">С чем мы работаем</span>
                    <h2 class="text-4xl font-extrabold uppercase">Что мы восстанавливаем</h2>
                </div>
                <div class="text-gray-500 font-medium italic">Работаем с любыми изделиями <br>из стекловолокна и смол</div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Карта услуги 1 -->
                <div class="group p-1 bg-gradient-to-br from-blue-100 to-transparent rounded-[2.5rem] hover:from-blue-600 transition-all duration-500">
                    <div class="bg-white p-8 rounded-[2.4rem] h-full transition-all group-hover:shadow-2xl">
                        <div class="mb-6 overflow-hidden rounded-2xl h-48">
                            <img src="https://images.unsplash.com/photo-1576013551627-0cc20b96c2a7?auto=format&fit=crop&w=600&q=80" alt="Ремонт бассейнов" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                        </div>
                        <h3 class="text-2xl font-bold mb-4">Бассейны</h3>
                        <p class="text-gray-600 mb-6 leading-relaxed">Ремонт трещин, удаление осмотических пузырей, обновление защитного слоя (топкоута).</p>
                        <a href="#contact" class="inline-flex items-center gap-2 text-blue-600 font-bold hover:gap-4 transition-all">Подробнее <i class="fas fa-arrow-right"></i></a>
                    </div>
                </div>

                <!-- Карта услуги 2 -->
                <div class="group p-1 bg-gradient-to-br from-blue-100 to-transparent rounded-[2.5rem] hover:from-blue-600 transition-all duration-500">
                    <div class="bg-white p-8 rounded-[2.4rem] h-full transition-all group-hover:shadow-2xl">
                        <div class="mb-6 overflow-hidden rounded-2xl h-48">
                            <img src="https://images.unsplash.com/photo-1595113316349-9fa4ee24f884?auto=format&fit=crop&w=600&q=80" alt="Ремонт баков КАС" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                        </div>
                        <h3 class="text-2xl font-bold mb-4">Баки КАС</h3>
                        <p class="text-gray-600 mb-6 leading-relaxed">Восстановление химической стойкости емкостей для удобрений и агрохимии на выезде.</p>
                        <a href="#contact" class="inline-flex items-center gap-2 text-blue-600 font-bold hover:gap-4 transition-all">Подробнее <i class="fas fa-arrow-right"></i></a>
                    </div>
                </div>

                <!-- Карта услуги 3 -->
                <div class="group p-1 bg-gradient-to-br from-blue-100 to-transparent rounded-[2.5rem] hover:from-blue-600 transition-all duration-500">
                    <div class="bg-white p-8 rounded-[2.4rem] h-full transition-all group-hover:shadow-2xl">
                        <div class="mb-6 overflow-hidden rounded-2xl h-48">
                            <img src="https://images.unsplash.com/photo-1540962351504-03099e0a754b?auto=format&fit=crop&w=600&q=80" alt="Ремонт катеров" class="w-full h-full object-cover group-hover:scale-110 transition duration-500">
                        </div>
                        <h3 class="text-2xl font-bold mb-4">Катера и Лодки</h3>
                        <p class="text-gray-600 mb-6 leading-relaxed">Ремонт пробоин, трещин на корпусе, усиление транца и восстановление блеска гелькоута.</p>
                        <a href="#contact" class="inline-flex items-center gap-2 text-blue-600 font-bold hover:gap-4 transition-all">Подробнее <i class="fas fa-arrow-right"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Прайсы -->
    <section id="prices" class="py-24 bg-slate-900 text-white relative overflow-hidden">
        <div class="absolute top-0 right-0 w-1/2 h-full bg-blue-600/5 -skew-x-12 transform translate-x-1/2"></div>
        
        <div class="container mx-auto px-4 relative z-10">
            <div class="text-center mb-20">
                <h2 class="text-4xl font-extrabold mb-4 uppercase italic">Ориентировочная стоимость</h2>
                <p class="text-blue-200">Точный расчет возможен после оценки степени износа стеклопластика</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Пакет 1 -->
                <div class="bg-white/5 border border-white/10 p-10 rounded-[3rem] backdrop-blur-lg hover:bg-white/10 transition-all">
                    <h4 class="text-blue-400 font-bold uppercase tracking-widest text-sm mb-6">Локальный ремонт</h4>
                    <div class="text-5xl font-black mb-8 italic text-white">от 5 500 <span class="text-lg font-medium opacity-50 italic">₽</span></div>
                    <ul class="space-y-4 mb-12 text-gray-300">
                        <li class="flex items-center gap-3"><i class="fas fa-check-circle text-green-500"></i> Трещины до 30 см</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check-circle text-green-500"></i> Сколы гелькоута</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check-circle text-green-500"></i> Протечки фитингов</li>
                    </ul>
                    <button onclick="scrollToContact()" class="w-full py-4 border border-white/20 rounded-2xl font-bold hover:bg-white hover:text-black transition uppercase text-xs tracking-widest">Выбрать</button>
                </div>

                <!-- Пакет 2 (Хит) -->
                <div class="bg-blue-600 p-10 rounded-[3rem] shadow-2xl shadow-blue-500/20 transform scale-105 relative">
                    <div class="absolute -top-4 left-1/2 -translate-x-1/2 bg-accent text-white px-6 py-1 rounded-full text-[10px] font-black uppercase italic shadow-lg">Самый частый запрос</div>
                    <h4 class="text-blue-100 font-bold uppercase tracking-widest text-sm mb-6">Реставрация чаши</h4>
                    <div class="text-5xl font-black mb-8 italic text-white">от 14 000 <span class="text-lg font-medium opacity-50 italic">₽</span></div>
                    <ul class="space-y-4 mb-12">
                        <li class="flex items-center gap-3 text-white"><i class="fas fa-check-circle text-accent"></i> Удаление осмоса</li>
                        <li class="flex items-center gap-3 text-white"><i class="fas fa-check-circle text-accent"></i> Усиление углов</li>
                        <li class="flex items-center gap-3 text-white"><i class="fas fa-check-circle text-accent"></i> Полное покрытие</li>
                        <li class="flex items-center gap-3 text-white"><i class="fas fa-check-circle text-accent"></i> Гарантия 36 мес</li>
                    </ul>
                    <button onclick="scrollToContact()" class="w-full py-4 bg-white text-blue-600 rounded-2xl font-bold hover:bg-blue-50 transition uppercase text-xs tracking-widest shadow-xl">Заказать расчет</button>
                </div>

                <!-- Пакет 3 -->
                <div class="bg-white/5 border border-white/10 p-10 rounded-[3rem] backdrop-blur-lg hover:bg-white/10 transition-all">
                    <h4 class="text-blue-400 font-bold uppercase tracking-widest text-sm mb-6">Промышленный объект</h4>
                    <div class="text-5xl font-black mb-8 italic text-white">от 25 000 <span class="text-lg font-medium opacity-50 italic">₽</span></div>
                    <ul class="space-y-4 mb-12 text-gray-300">
                        <li class="flex items-center gap-3"><i class="fas fa-check-circle text-green-500"></i> Емкости от 20 куб.м</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check-circle text-green-500"></i> Химстойкий ровинг</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check-circle text-green-500"></i> Работа по безналу</li>
                    </ul>
                    <button onclick="scrollToContact()" class="w-full py-4 border border-white/20 rounded-2xl font-bold hover:bg-white hover:text-black transition uppercase text-xs tracking-widest">Подробнее</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Слайдер До/После (Упрощенный для стабильности) -->
    <section id="gallery" class="py-24 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-extrabold mb-4 uppercase tracking-tighter italic">Наши работы</h2>
                <p class="text-gray-500">Листайте фото, чтобы оценить качество восстановления структуры пластика</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl mx-auto">
                <!-- Работа 1 -->
                <div class="group cursor-pointer">
                    <div class="relative overflow-hidden rounded-[2.5rem] shadow-xl aspect-video">
                        <div class="absolute inset-0 flex">
                            <div class="w-1/2 h-full overflow-hidden border-r-4 border-white relative">
                                <img src="https://images.unsplash.com/photo-1562184552-997c461abbe6?auto=format&fit=crop&w=400&q=60" alt="До" class="h-full w-full object-cover grayscale">
                                <span class="absolute top-4 left-4 bg-red-600 text-white text-[10px] font-black px-2 py-0.5 rounded italic">ДО</span>
                            </div>
                            <div class="w-1/2 h-full overflow-hidden relative">
                                <img src="https://images.unsplash.com/photo-1576013551627-0cc20b96c2a7?auto=format&fit=crop&w=400&q=60" alt="После" class="h-full w-full object-cover">
                                <span class="absolute top-4 right-4 bg-green-600 text-white text-[10px] font-black px-2 py-0.5 rounded italic">ПОСЛЕ</span>
                            </div>
                        </div>
                        <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/80 to-transparent p-6 pt-12">
                            <p class="text-white font-bold italic">Восстановление чаши бассейна (6х4м), г. Краснодар</p>
                        </div>
                    </div>
                </div>

                <!-- Работа 2 -->
                <div class="group cursor-pointer">
                    <div class="relative overflow-hidden rounded-[2.5rem] shadow-xl aspect-video">
                        <div class="absolute inset-0 flex">
                            <div class="w-1/2 h-full overflow-hidden border-r-4 border-white relative">
                                <img src="https://images.unsplash.com/photo-1584622781564-1d9876a13d00?auto=format&fit=crop&w=400&q=60" alt="До" class="h-full w-full object-cover grayscale">
                                <span class="absolute top-4 left-4 bg-red-600 text-white text-[10px] font-black px-2 py-0.5 rounded italic">ДО</span>
                            </div>
                            <div class="w-1/2 h-full overflow-hidden relative">
                                <img src="https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?auto=format&fit=crop&w=400&q=60" alt="После" class="h-full w-full object-cover">
                                <span class="absolute top-4 right-4 bg-green-600 text-white text-[10px] font-black px-2 py-0.5 rounded italic">ПОСЛЕ</span>
                            </div>
                        </div>
                        <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/80 to-transparent p-6 pt-12">
                            <p class="text-white font-bold italic">Ремонт емкости для КАС (5000л), ст. Северская</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <button class="text-blue-600 font-bold hover:underline">Смотреть все работы в Telegram</button>
            </div>
        </div>
    </section>

    <!-- Лид-магнит -->
    <section class="py-16 bg-blue-600 text-white">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center justify-between gap-10">
            <div class="md:w-2/3">
                <h3 class="text-3xl font-extrabold mb-4 uppercase italic">Не знаете, можно ли починить вашу емкость?</h3>
                <p class="text-xl text-blue-100">Пришлите фото в WhatsApp. Наш мастер проведет аудит повреждения онлайн и скажет вердикт за 15 минут.</p>
            </div>
            <div class="md:w-1/3 text-center">
                <a href="https://wa.me/78610000000" class="inline-block bg-white text-blue-600 px-10 py-5 rounded-2xl font-black text-xl shadow-2xl hover:bg-green-50 transition transform hover:-translate-y-1 active:scale-95">
                    <i class="fab fa-whatsapp mr-2"></i> ОТПРАВИТЬ ФОТО
                </a>
            </div>
        </div>
    </section>

    <!-- Контакты -->
    <section id="contact" class="py-24 bg-slate-50">
        <div class="container mx-auto px-4">
            <div class="bg-white rounded-[3rem] shadow-2xl overflow-hidden flex flex-col lg:flex-row border border-gray-100">
                <div class="lg:w-1/2 p-12 lg:p-20">
                    <h2 class="text-4xl font-extrabold mb-8 uppercase italic leading-tight">Готовы <br><span class="text-blue-600">начать ремонт?</span></h2>
                    
                    <div id="footerFormContainer">
                        <form class="space-y-5" onsubmit="handleFormSubmit(event, 'footerFormContainer')">
                            <input type="text" required placeholder="Ваше имя" class="w-full px-6 py-4 bg-gray-50 border border-gray-100 rounded-2xl outline-none focus:border-blue-500 transition font-semibold">
                            <input type="tel" required placeholder="Контактный телефон" class="w-full px-6 py-4 bg-gray-50 border border-gray-100 rounded-2xl outline-none focus:border-blue-500 transition font-semibold">
                            <textarea placeholder="Опишите задачу (объем емкости, характер повреждения)" class="w-full px-6 py-4 bg-gray-50 border border-gray-100 rounded-2xl outline-none focus:border-blue-500 transition font-semibold h-32"></textarea>
                            <button class="w-full bg-blue-600 text-white py-5 rounded-2xl font-extrabold text-lg hover:bg-blue-700 transition shadow-xl shadow-blue-200 uppercase tracking-widest active:scale-95">
                                Вызвать мастера на замер
                            </button>
                        </form>
                    </div>

                    <div id="footerFormContainerSuccess" class="form-status-success py-10 text-center">
                        <div class="w-20 h-20 bg-blue-50 text-blue-600 rounded-full flex items-center justify-center mx-auto mb-6 text-4xl">
                            <i class="fas fa-paper-plane"></i>
                        </div>
                        <h3 class="text-2xl font-bold mb-2 uppercase italic">Заявка в очереди!</h3>
                        <p class="text-gray-500">Менеджер свяжется с вами в течение часа для уточнения деталей.</p>
                    </div>
                </div>

                <div class="lg:w-1/2 bg-slate-900 p-12 lg:p-20 text-white flex flex-col justify-between relative">
                    <div class="absolute top-0 right-0 p-10 opacity-5">
                        <i class="fas fa-tools text-[250px]"></i>
                    </div>
                    
                    <div class="relative z-10">
                        <h4 class="text-2xl font-bold mb-10 italic uppercase">Прямые контакты</h4>
                        <div class="space-y-10">
                            <div class="flex items-start gap-6">
                                <div class="w-12 h-12 bg-blue-600 rounded-xl flex items-center justify-center shrink-0">
                                    <i class="fas fa-phone-alt"></i>
                                </div>
                                <div>
                                    <p class="text-xs text-gray-400 font-bold uppercase tracking-widest mb-1">Горячая линия</p>
                                    <p class="text-2xl font-extrabold leading-none">+7 (861) 000-00-00</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-6">
                                <div class="w-12 h-12 bg-blue-600 rounded-xl flex items-center justify-center shrink-0">
                                    <i class="fas fa-map-marker-alt"></i>
                                </div>
                                <div>
                                    <p class="text-xs text-gray-400 font-bold uppercase tracking-widest mb-1">Где мы находимся</p>
                                    <p class="text-lg font-bold">Краснодар, Промзона (Уральская/Новороссийская)</p>
                                    <p class="text-blue-400 text-sm mt-1">Работаем с выездом по всему ЮФО</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-6">
                                <div class="w-12 h-12 bg-blue-600 rounded-xl flex items-center justify-center shrink-0">
                                    <i class="fas fa-clock"></i>
                                </div>
                                <div>
                                    <p class="text-xs text-gray-400 font-bold uppercase tracking-widest mb-1">Работаем</p>
                                    <p class="text-lg font-bold">Ежедневно: 08:00 – 21:00</p>
                                    <p class="text-green-400 text-sm mt-1 flex items-center gap-2"><span class="w-2 h-2 bg-green-400 rounded-full animate-pulse"></span> Сейчас открыто</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-16 pt-10 border-t border-white/10 relative z-10 flex gap-4">
                        <a href="#" class="w-12 h-12 rounded-xl bg-white/5 flex items-center justify-center hover:bg-blue-600 transition text-xl"><i class="fab fa-vk"></i></a>
                        <a href="#" class="w-12 h-12 rounded-xl bg-white/5 flex items-center justify-center hover:bg-blue-600 transition text-xl"><i class="fab fa-telegram-plane"></i></a>
                        <a href="#" class="w-12 h-12 rounded-xl bg-white/5 flex items-center justify-center hover:bg-blue-600 transition text-xl"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Подвал -->
    <footer class="bg-slate-950 py-12 text-gray-600">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center gap-8 border-b border-white/5 pb-12 mb-8">
                <div class="flex items-center gap-2">
                    <div class="bg-white/10 p-2 rounded-lg">
                        <i class="fas fa-shield-virus text-white text-xl"></i>
                    </div>
                    <span class="font-bold text-white tracking-tight uppercase">Composite<span class="text-blue-600">Pro</span></span>
                </div>
                <div class="text-center text-sm">
                    &copy; 2026 Профессиональный ремонт стеклопластика в Краснодаре. <br>ИП Иванов А.А. ОГРНИП 321234567890123
                </div>
                <div class="flex gap-8 text-xs font-bold uppercase tracking-widest">
                    <a href="#" class="hover:text-white transition">Политика</a>
                    <a href="#" class="hover:text-white transition">Гарантия</a>
                </div>
            </div>
            <p class="text-[10px] text-center text-gray-800 leading-relaxed uppercase tracking-widest font-bold">Материалы сайта носят информационный характер. <br>Не является публичной офертой.</p>
        </div>
    </footer>

    <!-- Скрипты -->
    <script>
        // Анимация хедера при скролле
        window.addEventListener('scroll', () => {
            const header = document.getElementById('mainHeader');
            if (window.scrollY > 50) {
                header.classList.add('py-1', 'shadow-xl', 'bg-white');
            } else {
                header.classList.remove('py-1', 'shadow-xl');
            }
        });

        // Функция скролла
        function scrollToContact() {
            document.getElementById('contact').scrollIntoView({ behavior: 'smooth' });
        }

        // Обработка форм
        function handleFormSubmit(event, containerId) {
            event.preventDefault();
            const container = document.getElementById(containerId);
            const successContainer = document.getElementById(containerId + 'Success');
            
            // Имитация отправки
            container.style.opacity = '0.5';
            container.style.pointerEvents = 'none';
            
            setTimeout(() => {
                container.style.display = 'none';
                successContainer.style.display = 'block';
            }, 1000);
        }

        // Параллакс эффект для фона (легкий)
        window.addEventListener('mousemove', (e) => {
            const moveX = (e.clientX - window.innerWidth / 2) * 0.01;
            const moveY = (e.clientY - window.innerHeight / 2) * 0.01;
            document.querySelector('.hero-bg').style.backgroundPosition = `calc(50% + ${moveX}px) calc(50% + ${moveY}px)`;
