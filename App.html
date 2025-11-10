<!DOCTYPE html>
<html lang="pt-BR" class="light">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Segurança Inteligente IF Goiano - Protótipo</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" xintegrity="sha512-SnH5WK+bZxgPHs44uWIX+LLMDJd/rB9gQ3/4E8wD/3c4I6WlC1w3r14pUvD/4e0V9bQ2bLh/5l4O6l4p9g==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <!-- Chart.js for Reports -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.3/dist/chart.umd.min.js"></script>
    <style>
        /* Estilos base e transições para o tema */
        :root {
            --color-ifg-primary: #006400; /* Verde Escuro */
            --color-ifg-accent: #00A000; /* Verde mais claro */
            --color-ifg-bg-light: #f8f9fa;
            --color-ifg-text-dark: #1f2937;
        }
        .light {
            --color-ifg-bg: var(--color-ifg-bg-light);
            --color-ifg-text: var(--color-ifg-text-dark);
            --color-ifg-card-bg: #ffffff;
        }
        .dark {
            --color-ifg-bg: #111827;
            --color-ifg-text: #f3f4f6;
            --color-ifg-card-bg: #1f2937;
        }
        body {
            background-color: var(--color-ifg-bg);
            color: var(--color-ifg-text);
            transition: background-color 0.3s, color 0.3s;
        }
        .card-bg {
            background-color: var(--color-ifg-card-bg);
            transition: background-color 0.3s;
        }
        /* Configuração de cores Tailwind via JS */
    </style>
</head>
<body class="min-h-screen">

    <!-- Configuração customizada do Tailwind para cores institucionais -->
    <script>
        tailwind.config = {
            darkMode: 'class', // Usar a classe 'dark' no <html>
            theme: {
                extend: {
                    colors: {
                        'ifg-primary': '#006400',
                        'ifg-accent': '#00A000',
                        'ifg-bg-light': '#f8f9fa',
                        'ifg-text-dark': '#1f2937',
                    },
                    spacing: {
                        '72': '18rem',
                        '84': '21rem',
                        '96': '24rem',
                    },
                },
            }
        }
    </script>

    <!-- 1. TELA DE LOGIN -->
    <div id="login-view" class="flex items-center justify-center min-h-screen p-4" style="background: linear-gradient(135deg, #006400 0%, #38b000 100%);">
        <div class="card-bg w-full max-w-md p-8 rounded-xl shadow-2xl">
            <div class="text-center mb-8">
                <!-- Logotipo Fictício -->
                <i class="fa-solid fa-shield-halved text-5xl text-ifg-primary mb-3"></i>
                <h1 class="text-3xl font-bold text-ifg-text-dark">Segurança Inteligente</h1>
                <p class="text-lg text-gray-500">IF Goiano</p>
            </div>
            <form id="login-form">
                <div class="mb-4">
                    <label for="username" class="block text-sm font-medium text-gray-700 mb-1">Usuário</label>
                    <input type="text" id="username" value="admin" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-ifg-primary focus:border-ifg-primary transition duration-150" placeholder="Digite seu usuário" required>
                </div>
                <div class="mb-6">
                    <label for="password" class="block text-sm font-medium text-gray-700 mb-1">Senha</label>
                    <input type="password" id="password" value="123" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-ifg-primary focus:border-ifg-primary transition duration-150" placeholder="Digite sua senha" required>
                </div>
                <button type="submit" class="w-full py-3 bg-ifg-primary text-white font-semibold rounded-lg shadow-md hover:bg-ifg-accent transition duration-300">
                    <i class="fa-solid fa-right-to-bracket mr-2"></i> Entrar no Sistema
                </button>
                <p id="login-error" class="text-red-500 mt-4 text-center hidden">Usuário ou senha inválidos. Tente 'admin'/'123'.</p>
            </form>
        </div>
    </div>

    <!-- 2. DASHBOARD PRINCIPAL -->
    <div id="dashboard-view" class="hidden min-h-screen flex">

        <!-- Sidebar Lateral (Menu) -->
        <aside id="sidebar" class="fixed top-0 left-0 h-full w-64 card-bg border-r border-gray-200 dark:border-gray-700 transition-all duration-300 transform -translate-x-full md:translate-x-0 z-30 flex flex-col">
            <div class="p-5 border-b border-gray-200 dark:border-gray-700">
                <h2 class="text-xl font-bold text-ifg-primary">IFG Segurança</h2>
                <span class="text-sm text-gray-500 dark:text-gray-400">Controle de Acesso</span>
            </div>
            <nav class="flex-grow p-4 space-y-2">
                <a href="#" data-view="dashboard" class="sidebar-link flex items-center p-3 rounded-lg text-gray-700 dark:text-gray-300 hover:bg-ifg-primary hover:text-white transition duration-200 bg-ifg-primary text-white">
                    <i class="fa-solid fa-chart-line w-6"></i>
                    <span class="ml-3">Dashboard</span>
                </a>
                <a href="#" data-view="visitantes" class="sidebar-link flex items-center p-3 rounded-lg text-gray-700 dark:text-gray-300 hover:bg-ifg-primary hover:text-white transition duration-200">
                    <i class="fa-solid fa-person-walking w-6"></i>
                    <span class="ml-3">Visitantes</span>
                </a>
                <a href="#" data-view="servidores" class="sidebar-link flex items-center p-3 rounded-lg text-gray-700 dark:text-gray-300 hover:bg-ifg-primary hover:text-white transition duration-200">
                    <i class="fa-solid fa-user-group w-6"></i>
                    <span class="ml-3">Alunos/Servidores</span>
                </a>
                <a href="#" data-view="ocorrencias" class="sidebar-link flex items-center p-3 rounded-lg text-gray-700 dark:text-gray-300 hover:bg-ifg-primary hover:text-white transition duration-200">
                    <i class="fa-solid fa-triangle-exclamation w-6"></i>
                    <span class="ml-3">Ocorrências</span>
                </a>
                <a href="#" data-view="veiculos" class="sidebar-link flex items-center p-3 rounded-lg text-gray-700 dark:text-gray-300 hover:bg-ifg-primary hover:text-white transition duration-200">
                    <i class="fa-solid fa-car w-6"></i>
                    <span class="ml-3">Veículos</span>
                </a>
                <a href="#" data-view="relatorios" class="sidebar-link flex items-center p-3 rounded-lg text-gray-700 dark:text-gray-300 hover:bg-ifg-primary hover:text-white transition duration-200">
                    <i class="fa-solid fa-file-pdf w-6"></i>
                    <span class="ml-3">Relatórios</span>
                </a>
            </nav>
            <div class="p-4 border-t border-gray-200 dark:border-gray-700 mt-auto">
                <a href="#" data-view="configuracoes" class="sidebar-link flex items-center p-3 rounded-lg text-gray-700 dark:text-gray-300 hover:bg-ifg-primary hover:text-white transition duration-200">
                    <i class="fa-solid fa-gear w-6"></i>
                    <span class="ml-3">Configurações</span>
                </a>
                <button onclick="logout()" class="w-full mt-2 flex items-center justify-center p-3 rounded-lg text-red-500 border border-red-500 hover:bg-red-500 hover:text-white transition duration-200">
                    <i class="fa-solid fa-right-from-bracket mr-2"></i> Sair
                </button>
            </div>
        </aside>

        <!-- Overlay para mobile -->
        <div id="sidebar-overlay" class="fixed inset-0 bg-black opacity-0 md:hidden z-20 pointer-events-none transition-opacity duration-300" onclick="toggleSidebar()"></div>

        <!-- Conteúdo Principal -->
        <main class="flex-1 md:ml-64 p-6 transition-all duration-300" id="main-content-area">
            
            <!-- Cabeçalho (Header) -->
            <header class="flex justify-between items-center mb-6">
                <button id="sidebar-toggle" class="md:hidden text-2xl text-gray-700 dark:text-gray-300" onclick="toggleSidebar()">
                    <i class="fa-solid fa-bars"></i>
                </button>
                <h1 id="page-title" class="text-3xl font-extrabold text-ifg-primary dark:text-ifg-accent">Dashboard</h1>
                <div class="flex items-center space-x-4">
                    <button id="theme-toggle" class="p-2 rounded-full hover:bg-gray-200 dark:hover:bg-gray-700 transition duration-200">
                        <i id="theme-icon" class="fa-solid fa-moon text-xl text-gray-700 dark:text-gray-300"></i>
                    </button>
                    <div class="flex items-center space-x-2">
                        <i class="fa-solid fa-circle-user text-2xl text-ifg-primary"></i>
                        <span class="font-medium">Admin</span>
                    </div>
                </div>
            </header>

            <!-- CONTEÚDO DINÂMICO -->

            <!-- 2.1. DASHBOARD HOME -->
            <section id="view-dashboard" class="content-view">
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 mb-8">
                    <div class="card-bg p-6 rounded-xl shadow-lg border-l-4 border-ifg-primary">
                        <p class="text-sm font-semibold text-gray-500">Visitantes Ativos</p>
                        <p id="stat-visitantes" class="text-3xl font-bold mt-1">12</p>
                        <p class="text-xs text-green-500 mt-2"><i class="fa-solid fa-arrow-up"></i> +1 Hoje</p>
                    </div>
                    <div class="card-bg p-6 rounded-xl shadow-lg border-l-4 border-blue-500">
                        <p class="text-sm font-semibold text-gray-500">Total de Entradas (Dia)</p>
                        <p id="stat-entradas" class="text-3xl font-bold mt-1">158</p>
                        <p class="text-xs text-gray-500 mt-2">Pico às 08:00</p>
                    </div>
                    <div class="card-bg p-6 rounded-xl shadow-lg border-l-4 border-red-500">
                        <p class="text-sm font-semibold text-gray-500">Ocorrências Registradas</p>
                        <p id="stat-ocorrencias" class="text-3xl font-bold mt-1">3</p>
                        <p class="text-xs text-red-500 mt-2"><i class="fa-solid fa-bell"></i> Alta Prioridade: 1</p>
                    </div>
                    <div class="card-bg p-6 rounded-xl shadow-lg border-l-4 border-yellow-500">
                        <p class="text-sm font-semibold text-gray-500">Veículos no Campus</p>
                        <p id="stat-veiculos" class="text-3xl font-bold mt-1">45</p>
                        <p class="text-xs text-gray-500 mt-2">6 Visitantes</p>
                    </div>
                </div>

                <!-- Painel de Ações Rápidas -->
                <div class="card-bg p-6 rounded-xl shadow-lg">
                    <h3 class="text-xl font-semibold mb-4 border-b pb-2">Feed de Atividade Recente</h3>
                    <ul class="space-y-3">
                        <li class="flex items-center text-sm">
                            <i class="fa-solid fa-circle-check text-green-500 mr-3"></i>
                            <span class="font-medium">ENTRADA:</span> João Silva (Visitante) - Destino: Pró-Reitoria (10:15)
                        </li>
                        <li class="flex items-center text-sm">
                            <i class="fa-solid fa-circle-exclamation text-yellow-500 mr-3"></i>
                            <span class="font-medium">OCORRÊNCIA:</span> Alarme de porta acionado - Bloco C (09:40)
                        </li>
                        <li class="flex items-center text-sm">
                            <i class="fa-solid fa-circle-check text-green-500 mr-3"></i>
                            <span class="font-medium">SAÍDA:</span> Maria Oliveira (Servidora) - Veículo: KJH-9I87 (09:30)
                        </li>
                    </ul>
                </div>
            </section>

            <!-- 2.2. SEÇÃO VISITANTES -->
            <section id="view-visitantes" class="content-view hidden">
                <div class="flex justify-between items-center mb-6">
                    <h2 class="text-2xl font-bold">Gestão de Visitantes</h2>
                    <div class="space-x-3">
                        <button id="btn-gerar-qr" class="px-4 py-2 bg-blue-500 text-white font-medium rounded-lg shadow-md hover:bg-blue-600 transition duration-300">
                            <i class="fa-solid fa-qrcode mr-2"></i> Gerar QR Code de Acesso
                        </button>
                        <button id="btn-novo-visitante" class="px-4 py-2 bg-ifg-primary text-white font-medium rounded-lg shadow-md hover:bg-ifg-accent transition duration-300">
                            <i class="fa-solid fa-plus mr-2"></i> Cadastrar Novo Visitante
                        </button>
                    </div>
                </div>

                <div class="card-bg p-4 rounded-xl shadow-lg overflow-x-auto">
                    <table class="min-w-full divide-y divide-gray-200 dark:divide-gray-700">
                        <thead class="bg-gray-50 dark:bg-gray-700">
                            <tr>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Nome</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">CPF</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Destino</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Entrada/Saída</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Status</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Ações</th>
                            </tr>
                        </thead>
                        <tbody id="tabela-visitantes" class="divide-y divide-gray-200 dark:divide-gray-700">
                            <!-- Dados de visitantes serão injetados aqui -->
                        </tbody>
                    </table>
                </div>
            </section>

            <!-- 2.3. SEÇÃO ALUNOS/SERVIDORES -->
            <section id="view-servidores" class="content-view hidden">
                <h2 class="text-2xl font-bold mb-4">Cadastro de Alunos e Servidores</h2>
                <div class="card-bg p-6 rounded-xl shadow-lg">
                    <p class="mb-4 text-gray-600 dark:text-gray-400">Esta seção simula a base de dados de usuários internos. A gestão completa estaria integrada ao sistema acadêmico.</p>
                    <table class="min-w-full divide-y divide-gray-200 dark:divide-gray-700">
                        <thead class="bg-gray-50 dark:bg-gray-700">
                            <tr>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Nome</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Matrícula</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Tipo</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Setor/Curso</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-gray-200 dark:divide-gray-700">
                            <tr class="hover:bg-gray-50 dark:hover:bg-gray-700">
                                <td class="px-6 py-4 whitespace-nowrap">Prof. Ana Costa</td>
                                <td class="px-6 py-4 whitespace-nowrap">SVR9021</td>
                                <td class="px-6 py-4 whitespace-nowrap"><span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-ifg-accent/20 text-ifg-primary">Servidor</span></td>
                                <td class="px-6 py-4 whitespace-nowrap">Departamento de TI</td>
                            </tr>
                            <tr class="hover:bg-gray-50 dark:hover:bg-gray-700">
                                <td class="px-6 py-4 whitespace-nowrap">Pedro Santos</td>
                                <td class="px-6 py-4 whitespace-nowrap">ALN5544</td>
                                <td class="px-6 py-4 whitespace-nowrap"><span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-blue-100 text-blue-800 dark:bg-blue-800/50 dark:text-blue-300">Aluno</span></td>
                                <td class="px-6 py-4 whitespace-nowrap">Agronomia</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </section>

            <!-- 2.4. SEÇÃO OCORRÊNCIAS -->
            <section id="view-ocorrencias" class="content-view hidden">
                <div class="flex justify-between items-center mb-6">
                    <h2 class="text-2xl font-bold">Registro de Ocorrências</h2>
                    <button id="btn-nova-ocorrencia" class="px-4 py-2 bg-red-500 text-white font-medium rounded-lg shadow-md hover:bg-red-600 transition duration-300">
                        <i class="fa-solid fa-plus mr-2"></i> Nova Ocorrência
                    </button>
                </div>

                <div class="card-bg p-4 rounded-xl shadow-lg overflow-x-auto">
                    <table class="min-w-full divide-y divide-gray-200 dark:divide-gray-700">
                        <thead class="bg-gray-50 dark:bg-gray-700">
                            <tr>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">ID</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Tipo</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Descrição</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Data/Hora</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Responsável</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Status</th>
                            </tr>
                        </thead>
                        <tbody id="tabela-ocorrencias" class="divide-y divide-gray-200 dark:divide-gray-700">
                            <!-- Dados de ocorrências serão injetados aqui -->
                        </tbody>
                    </table>
                </div>
            </section>

            <!-- 2.5. SEÇÃO VEÍCULOS -->
            <section id="view-veiculos" class="content-view hidden">
                <div class="flex justify-between items-center mb-6">
                    <h2 class="text-2xl font-bold">Controle de Veículos</h2>
                    <button id="btn-novo-veiculo" class="px-4 py-2 bg-yellow-600 text-white font-medium rounded-lg shadow-md hover:bg-yellow-700 transition duration-300">
                        <i class="fa-solid fa-car-on mr-2"></i> Cadastrar Novo Veículo
                    </button>
                </div>

                <div class="card-bg p-4 rounded-xl shadow-lg overflow-x-auto">
                    <table class="min-w-full divide-y divide-gray-200 dark:divide-gray-700">
                        <thead class="bg-gray-50 dark:bg-gray-700">
                            <tr>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Placa</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Modelo</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Responsável</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Status</th>
                                <th class="px-6 py-3 text-left text-xs font-medium text-gray-500 dark:text-gray-300 uppercase tracking-wider">Entrada</th>
                            </tr>
                        </thead>
                        <tbody id="tabela-veiculos" class="divide-y divide-gray-200 dark:divide-gray-700">
                            <!-- Dados de veículos serão injetados aqui -->
                        </tbody>
                    </table>
                </div>
            </section>

            <!-- 2.6. SEÇÃO RELATÓRIOS -->
            <section id="view-relatorios" class="content-view hidden">
                <h2 class="text-2xl font-bold mb-4">Análise de Dados e Relatórios</h2>
                <div class="card-bg p-6 rounded-xl shadow-lg mb-6">
                    <div class="flex flex-wrap gap-4 mb-4">
                        <input type="date" class="p-2 border rounded-lg dark:bg-gray-700 dark:border-gray-600" value="2025-11-01">
                        <select class="p-2 border rounded-lg dark:bg-gray-700 dark:border-gray-600">
                            <option>Tipo de Acesso: Todos</option>
                            <option>Visitante</option>
                            <option>Servidor</option>
                            <option>Aluno</option>
                        </select>
                        <select class="p-2 border rounded-lg dark:bg-gray-700 dark:border-gray-600">
                            <option>Usuário: Todos</option>
                            <option>Portaria A</option>
                            <option>Portaria B</option>
                        </select>
                        <button class="px-4 py-2 bg-ifg-accent text-white rounded-lg hover:bg-ifg-primary transition duration-300">
                            <i class="fa-solid fa-filter mr-2"></i> Aplicar Filtros
                        </button>
                    </div>

                    <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">
                        <div class="lg:col-span-2 card-bg p-4 rounded-xl shadow-inner">
                            <h3 class="text-lg font-semibold mb-3">Acessos por Dia (Últimos 7 dias)</h3>
                            <canvas id="acessosChart"></canvas>
                        </div>
                        <div class="lg:col-span-1 card-bg p-4 rounded-xl shadow-inner">
                            <h3 class="text-lg font-semibold mb-3">Visitantes Mais Frequentes (Destino)</h3>
                            <canvas id="destinosChart"></canvas>
                        </div>
                        <div class="lg:col-span-3 card-bg p-4 rounded-xl shadow-inner">
                            <h3 class="text-lg font-semibold mb-3">Horários de Pico de Entrada/Saída</h3>
                            <canvas id="picoChart"></canvas>
                        </div>
                    </div>
                </div>
            </section>

            <!-- 2.7. SEÇÃO CONFIGURAÇÕES -->
            <section id="view-configuracoes" class="content-view hidden">
                <h2 class="text-2xl font-bold mb-4">Configurações do Sistema</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div class="card-bg p-6 rounded-xl shadow-lg">
                        <h3 class="text-xl font-semibold mb-4 border-b pb-2">Opções Visuais</h3>
                        <div class="flex justify-between items-center">
                            <span class="text-gray-700 dark:text-gray-300">Tema Atual: <span id="current-theme" class="font-medium">Claro</span></span>
                            <button onclick="toggleTheme()" class="px-4 py-2 bg-gray-300 dark:bg-gray-700 text-gray-800 dark:text-gray-200 rounded-lg hover:bg-gray-400 dark:hover:bg-gray-600 transition duration-300">
                                <i class="fa-solid fa-circle-half-stroke mr-2"></i> Trocar Tema
                            </button>
                        </div>
                    </div>
                    <div class="card-bg p-6 rounded-xl shadow-lg">
                        <h3 class="text-xl font-semibold mb-4 border-b pb-2">Gerenciamento de Usuários (Fictício)</h3>
                        <ul class="space-y-2 text-sm">
                            <li class="flex justify-between items-center text-gray-700 dark:text-gray-300">Portaria A (Nível 3) <button class="text-blue-500 hover:text-blue-700"><i class="fa-solid fa-pen"></i></button></li>
                            <li class="flex justify-between items-center text-gray-700 dark:text-gray-300">Segurança C (Nível 2) <button class="text-blue-500 hover:text-blue-700"><i class="fa-solid fa-pen"></i></button></li>
                        </ul>
                    </div>
                </div>
            </section>

            <!-- FIM DO CONTEÚDO DINÂMICO -->

        </main>
    </div>

    <!-- MODAL - Cadastrar Novo Visitante -->
    <div id="modal-visitante" class="fixed inset-0 bg-black bg-opacity-50 hidden items-center justify-center z-50">
        <div class="card-bg w-full max-w-lg p-6 rounded-xl shadow-2xl">
            <h3 class="text-2xl font-bold mb-4 border-b pb-2">Cadastro de Visitante</h3>
            <form id="form-visitante" class="space-y-4">
                <div>
                    <label class="block text-sm font-medium mb-1">Nome Completo</label>
                    <input type="text" id="v-nome" class="w-full p-2 border rounded-lg dark:bg-gray-700 dark:border-gray-600" required>
                </div>
                <div>
                    <label class="block text-sm font-medium mb-1">CPF</label>
                    <input type="text" id="v-cpf" class="w-full p-2 border rounded-lg dark:bg-gray-700 dark:border-gray-600" required>
                </div>
                <div>
                    <label class="block text-sm font-medium mb-1">Destino / Pessoa Visitada</label>
                    <input type="text" id="v-destino" class="w-full p-2 border rounded-lg dark:bg-gray-700 dark:border-gray-600" required>
                </div>
                <div class="flex justify-end space-x-3 pt-2">
                    <button type="button" onclick="closeModal('modal-visitante')" class="px-4 py-2 border rounded-lg hover:bg-gray-100 dark:hover:bg-gray-700 transition duration-200">Cancelar</button>
                    <button type="submit" class="px-4 py-2 bg-ifg-primary text-white rounded-lg hover:bg-ifg-accent transition duration-300">
                        <i class="fa-solid fa-floppy-disk mr-2"></i> Registrar Entrada
                    </button>
                </div>
            </form>
        </div>
    </div>

    <!-- MODAL - Nova Ocorrência -->
    <div id="modal-ocorrencia" class="fixed inset-0 bg-black bg-opacity-50 hidden items-center justify-center z-50">
        <div class="card-bg w-full max-w-lg p-6 rounded-xl shadow-2xl">
            <h3 class="text-2xl font-bold mb-4 border-b pb-2">Novo Registro de Ocorrência</h3>
            <form id="form-ocorrencia" class="space-y-4">
                <div>
                    <label class="block text-sm font-medium mb-1">Tipo de Ocorrência</label>
                    <select id="o-tipo" class="w-full p-2 border rounded-lg dark:bg-gray-700 dark:border-gray-600" required>
                        <option value="Alarme">Alarme</option>
                        <option value="Vandalismo">Vandalismo</option>
                        <option value="Acesso Não Autorizado">Acesso Não Autorizado</option>
                        <option value="Perda/Roubo">Perda/Roubo</option>
                        <option value="Outro">Outro</option>
                    </select>
                </div>
                <div>
                    <label class="block text-sm font-medium mb-1">Descrição Detalhada</label>
                    <textarea id="o-descricao" rows="3" class="w-full p-2 border rounded-lg dark:bg-gray-700 dark:border-gray-600" required></textarea>
                </div>
                <div class="grid grid-cols-2 gap-4">
                    <div>
                        <label class="block text-sm font-medium mb-1">Data/Hora</label>
                        <input type="datetime-local" id="o-datahora" class="w-full p-2 border rounded-lg dark:bg-gray-700 dark:border-gray-600" required>
                    </div>
                    <div>
                        <label class="block text-sm font-medium mb-1">Responsável pelo Registro</label>
                        <input type="text" id="o-responsavel" value="Admin" class="w-full p-2 border rounded-lg dark:bg-gray-700 dark:border-gray-600" required>
                    </div>
                </div>
                <div class="flex justify-end space-x-3 pt-2">
                    <button type="button" onclick="closeModal('modal-ocorrencia')" class="px-4 py-2 border rounded-lg hover:bg-gray-100 dark:hover:bg-gray-700 transition duration-200">Cancelar</button>
                    <button type="submit" class="px-4 py-2 bg-red-500 text-white rounded-lg hover:bg-red-600 transition duration-300">
                        <i class="fa-solid fa-bullhorn mr-2"></i> Registrar Ocorrência
                    </button>
                </div>
            </form>
        </div>
    </div>

    <!-- MODAL - Cadastrar Novo Veículo -->
    <div id="modal-veiculo" class="fixed inset-0 bg-black bg-opacity-50 hidden items-center justify-center z-50">
        <div class="card-bg w-full max-w-lg p-6 rounded-xl shadow-2xl">
            <h3 class="text-2xl font-bold mb-4 border-b pb-2">Cadastro de Veículo</h3>
            <form id="form-veiculo" class="space-y-4">
                <div>
                    <label class="block text-sm font-medium mb-1">Placa</label>
                    <input type="text" id="v-placa" class="w-full p-2 border rounded-lg dark:bg-gray-700 dark:border-gray-600 uppercase" placeholder="ABC-1234" required>
                </div>
                <div>
                    <label class="block text-sm font-medium mb-1">Modelo / Cor</label>
                    <input type="text" id="v-modelo" class="w-full p-2 border rounded-lg dark:bg-gray-700 dark:border-gray-600" placeholder="VW Gol Prata" required>
                </div>
                <div>
                    <label class="block text-sm font-medium mb-1">Responsável (Nome ou Matrícula)</label>
                    <input type="text" id="v-responsavel" class="w-full p-2 border rounded-lg dark:bg-gray-700 dark:border-gray-600" required>
                </div>
                <div class="flex justify-end space-x-3 pt-2">
                    <button type="button" onclick="closeModal('modal-veiculo')" class="px-4 py-2 border rounded-lg hover:bg-gray-100 dark:hover:bg-gray-700 transition duration-200">Cancelar</button>
                    <button type="submit" class="px-4 py-2 bg-yellow-600 text-white rounded-lg hover:bg-yellow-700 transition duration-300">
                        <i class="fa-solid fa-circle-plus mr-2"></i> Cadastrar Veículo
                    </button>
                </div>
            </form>
        </div>
    </div>

    <!-- MODAL - Mensagem (Para QR Code, Saída, etc) -->
    <div id="modal-message" class="fixed inset-0 bg-black bg-opacity-50 hidden items-center justify-center z-50">
        <div class="card-bg w-full max-w-xs p-6 rounded-xl shadow-2xl text-center">
            <div id="message-icon" class="text-4xl mb-4 text-ifg-accent"><i class="fa-solid fa-qrcode"></i></div>
            <p id="message-content" class="text-lg font-medium">QR Code de Acesso gerado com sucesso para o visitante. Pronto para leitura!</p>
            <button onclick="closeModal('modal-message')" class="mt-5 w-full py-2 bg-ifg-primary text-white rounded-lg hover:bg-ifg-accent transition duration-300">Fechar</button>
        </div>
    </div>

    <script>
        // Variáveis de estado global
        let currentView = 'dashboard';
        let isSidebarOpen = false;
        let isDarkMode = false;
        
        // Dados simulados
        let visitantes = [
            { id: 1, nome: "João Silva", cpf: "123.456.789-00", destino: "Biblioteca", entrada: "10:15", saida: "-", status: "Dentro" },
            { id: 2, nome: "Maria Souza", cpf: "987.654.321-11", destino: "Depto. de TI", entrada: "08:30", saida: "11:45", status: "Fora" },
            { id: 3, nome: "Carlos Viana", cpf: "111.222.333-44", destino: "Pró-Reitoria", entrada: "14:00", saida: "-", status: "Dentro" },
        ];

        let ocorrencias = [
            { id: 1, tipo: "Alarme", descricao: "Alarme de porta acionado no Bloco C.", datahora: "07/11/2025 09:40", responsavel: "Admin", status: "Pendente" },
            { id: 2, tipo: "Vandalismo", descricao: "Pichação encontrada no muro lateral.", datahora: "06/11/2025 18:00", responsavel: "Segurança B", status: "Resolvido" },
        ];

        let veiculos = [
            { id: 1, placa: "PQR-1A23", modelo: "Fiat Uno Vermelho", responsavel: "Prof. Ana Costa", status: "Dentro", entrada: "07:45" },
            { id: 2, placa: "KJH-9I87", modelo: "Toyota Corolla Preto", responsavel: "Maria Souza (Visitante)", status: "Fora", entrada: "10:00" },
        ];

        // Charts instances
        let acessosChart, destinosChart, picoChart;

        // --- FUNÇÕES DE NAVEGAÇÃO E TEMA ---

        // Função para simular login
        function handleLogin(event) {
            event.preventDefault();
            const username = document.getElementById('username').value;
            const password = document.getElementById('password').value;
            const errorMsg = document.getElementById('login-error');

            if (username === 'admin' && password === '123') {
                document.getElementById('login-view').classList.add('hidden');
                document.getElementById('dashboard-view').classList.remove('hidden');
                navigateTo('dashboard');
            } else {
                errorMsg.classList.remove('hidden');
            }
        }

        // Função para simular logout
        function logout() {
            document.getElementById('dashboard-view').classList.add('hidden');
            document.getElementById('login-view').classList.remove('hidden');
            document.getElementById('login-form').reset();
            document.getElementById('login-error').classList.add('hidden');
        }

        // Função para trocar de seção
        function navigateTo(viewId) {
            currentView = viewId;
            // Oculta todas as seções de conteúdo
            document.querySelectorAll('.content-view').forEach(section => {
                section.classList.add('hidden');
            });
            // Mostra a seção desejada
            const target = document.getElementById(`view-${viewId}`);
            if (target) {
                target.classList.remove('hidden');
            }

            // Atualiza o título da página
            const titleMap = {
                'dashboard': 'Dashboard',
                'visitantes': 'Gestão de Visitantes',
                'servidores': 'Alunos e Servidores',
                'ocorrencias': 'Registro de Ocorrências',
                'veiculos': 'Controle de Veículos',
                'relatorios': 'Análise de Dados e Relatórios',
                'configuracoes': 'Configurações do Sistema'
            };
            document.getElementById('page-title').textContent = titleMap[viewId] || 'Segurança Inteligente';

            // Atualiza o estado da sidebar
            document.querySelectorAll('.sidebar-link').forEach(link => {
                if (link.dataset.view === viewId) {
                    link.classList.add('bg-ifg-primary', 'text-white');
                    link.classList.remove('text-gray-700', 'dark:text-gray-300');
                } else {
                    link.classList.remove('bg-ifg-primary', 'text-white');
                    link.classList.add('text-gray-700', 'dark:text-gray-300');
                }
            });

            // Fecha a sidebar em mobile
            if (isSidebarOpen) {
                toggleSidebar();
            }

            // Se for a seção de relatórios, desenha os gráficos
            if (viewId === 'relatorios') {
                drawCharts();
            }
        }

        // Função para alternar o tema (claro/escuro)
        function toggleTheme() {
            const html = document.documentElement;
            isDarkMode = html.classList.toggle('dark');
            document.getElementById('current-theme').textContent = isDarkMode ? 'Escuro' : 'Claro';
            document.getElementById('theme-icon').className = `fa-solid ${isDarkMode ? 'fa-sun' : 'fa-moon'} text-xl text-gray-700 dark:text-gray-300`;
            // Redesenha gráficos para atualizar cores (se a view Relatórios estiver ativa)
            if (currentView === 'relatorios') {
                drawCharts();
            }
        }

        // Função para abrir/fechar sidebar em mobile
        function toggleSidebar() {
            const sidebar = document.getElementById('sidebar');
            const overlay = document.getElementById('sidebar-overlay');
            
            if (isSidebarOpen) {
                sidebar.classList.add('-translate-x-full');
                overlay.classList.add('opacity-0', 'pointer-events-none');
            } else {
                sidebar.classList.remove('-translate-x-full');
                overlay.classList.remove('opacity-0', 'pointer-events-none');
                overlay.classList.add('opacity-50');
            }
            isSidebarOpen = !isSidebarOpen;
        }

        // --- FUNÇÕES DE MODAL ---

        function openModal(modalId) {
            document.getElementById(modalId).classList.add('flex');
            document.getElementById(modalId).classList.remove('hidden');
        }

        function closeModal(modalId) {
            document.getElementById(modalId).classList.add('hidden');
            document.getElementById(modalId).classList.remove('flex');
            // Reseta formulários ao fechar
            const form = document.getElementById(modalId).querySelector('form');
            if (form) form.reset();
        }

        // --- FUNÇÕES DE RENDERIZAÇÃO DE DADOS ---

        function renderVisitantes() {
            const tbody = document.getElementById('tabela-visitantes');
            tbody.innerHTML = visitantes.map(v => {
                const statusClass = v.status === "Dentro" 
                    ? 'bg-green-100 text-green-800 dark:bg-green-800/50 dark:text-green-300' 
                    : 'bg-red-100 text-red-800 dark:bg-red-800/50 dark:text-red-300';
                const statusButton = v.status === "Dentro" 
                    ? `<button data-id="${v.id}" class="btn-saida text-red-600 hover:text-red-800 ml-3 font-semibold text-sm">Registrar Saída</button>`
                    : '';
                
                return `
                    <tr class="hover:bg-gray-50 dark:hover:bg-gray-700">
                        <td class="px-6 py-4 whitespace-nowrap">${v.nome}</td>
                        <td class="px-6 py-4 whitespace-nowrap">${v.cpf}</td>
                        <td class="px-6 py-4 whitespace-nowrap">${v.destino}</td>
                        <td class="px-6 py-4 whitespace-nowrap">${v.entrada} / ${v.saida}</td>
                        <td class="px-6 py-4 whitespace-nowrap">
                            <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full ${statusClass}">
                                ${v.status}
                            </span>
                        </td>
                        <td class="px-6 py-4 whitespace-nowrap">
                            ${statusButton}
                        </td>
                    </tr>
                `;
            }).join('');
            
            // Adiciona listener para o botão de saída
            tbody.querySelectorAll('.btn-saida').forEach(btn => {
                btn.addEventListener('click', (e) => registrarSaida(e.target.dataset.id));
            });

            // Atualiza estatísticas do dashboard
            document.getElementById('stat-visitantes').textContent = visitantes.filter(v => v.status === "Dentro").length;
        }

        function renderOcorrencias() {
            const tbody = document.getElementById('tabela-ocorrencias');
            tbody.innerHTML = ocorrencias.map(o => {
                const status = o.status;
                let statusClass = 'bg-gray-100 text-gray-800 dark:bg-gray-700 dark:text-gray-300';
                if (status === 'Pendente') statusClass = 'bg-red-100 text-red-800 dark:bg-red-800/50 dark:text-red-300';
                if (status === 'Resolvido') statusClass = 'bg-green-100 text-green-800 dark:bg-green-800/50 dark:text-green-300';

                return `
                    <tr class="hover:bg-gray-50 dark:hover:bg-gray-700">
                        <td class="px-6 py-4 whitespace-nowrap font-medium">${o.id}</td>
                        <td class="px-6 py-4 whitespace-nowrap">${o.tipo}</td>
                        <td class="px-6 py-4 max-w-xs truncate">${o.descricao}</td>
                        <td class="px-6 py-4 whitespace-nowrap text-sm">${o.datahora}</td>
                        <td class="px-6 py-4 whitespace-nowrap">${o.responsavel}</td>
                        <td class="px-6 py-4 whitespace-nowrap">
                            <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full ${statusClass}">
                                ${status}
                            </span>
                        </td>
                    </tr>
                `;
            }).join('');
            document.getElementById('stat-ocorrencias').textContent = ocorrencias.filter(o => o.status === "Pendente").length;
        }

        function renderVeiculos() {
            const tbody = document.getElementById('tabela-veiculos');
            tbody.innerHTML = veiculos.map(v => {
                const statusClass = v.status === "Dentro" 
                    ? 'bg-ifg-accent/20 text-ifg-primary dark:bg-ifg-accent/50' 
                    : 'bg-gray-100 text-gray-800 dark:bg-gray-700 dark:text-gray-300';

                return `
                    <tr class="hover:bg-gray-50 dark:hover:bg-gray-700">
                        <td class="px-6 py-4 whitespace-nowrap font-semibold uppercase">${v.placa}</td>
                        <td class="px-6 py-4 whitespace-nowrap">${v.modelo}</td>
                        <td class="px-6 py-4 whitespace-nowrap">${v.responsavel}</td>
                        <td class="px-6 py-4 whitespace-nowrap">
                            <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full ${statusClass}">
                                ${v.status}
                            </span>
                        </td>
                        <td class="px-6 py-4 whitespace-nowrap text-sm">${v.entrada}</td>
                    </tr>
                `;
            }).join('');
             document.getElementById('stat-veiculos').textContent = veiculos.filter(v => v.status === "Dentro").length;
        }

        // --- FUNÇÕES DE CADASTRO (SIMULADO) ---

        function handleAddVisitante(event) {
            event.preventDefault();
            const nome = document.getElementById('v-nome').value;
            const cpf = document.getElementById('v-cpf').value;
            const destino = document.getElementById('v-destino').value;
            
            const novoVisitante = {
                id: visitantes.length + 1,
                nome: nome,
                cpf: cpf,
                destino: destino,
                entrada: new Date().toLocaleTimeString('pt-BR', {hour: '2-digit', minute:'2-digit'}),
                saida: "-",
                status: "Dentro"
            };
            visitantes.push(novoVisitante);
            renderVisitantes();
            closeModal('modal-visitante');
        }

        function registrarSaida(id) {
            const visitor = visitantes.find(v => v.id == id);
            if (visitor) {
                visitor.saida = new Date().toLocaleTimeString('pt-BR', {hour: '2-digit', minute:'2-digit'});
                visitor.status = "Fora";
                // Simular registro de saída de veículo se o visitante tiver um
                const veiculoIndex = veiculos.findIndex(v => v.responsavel.includes(visitor.nome) && v.status === "Dentro");
                if (veiculoIndex !== -1) {
                    veiculos[veiculoIndex].status = "Fora";
                    renderVeiculos();
                }

                renderVisitantes();
                // O ERRO ESTAVA NESTA LINHA: uso de ${} com aspas simples. Foi corrigido para backticks (`` ` ``) e a classe de cor ajustada.
                showMessage('Saída Registrada', `<i class="fa-solid fa-circle-check"></i>`, `O visitante **${visitor.nome}** registrou saída às ${visitor.saida}.`, 'text-green-500');
            }
        }

        function handleAddOcorrencia(event) {
            event.preventDefault();
            const tipo = document.getElementById('o-tipo').value;
            const descricao = document.getElementById('o-descricao').value;
            const datahoraInput = document.getElementById('o-datahora').value;
            const responsavel = document.getElementById('o-responsavel').value;

            const novoRegistro = {
                id: ocorrencias.length + 1,
                tipo: tipo,
                descricao: descricao,
                datahora: new Date(datahoraInput).toLocaleString('pt-BR', { day: '2-digit', month: '2-digit', year: 'numeric', hour: '2-digit', minute: '2-digit' }),
                responsavel: responsavel,
                status: "Pendente"
            };
            ocorrencias.unshift(novoRegistro); // Adiciona no início
            renderOcorrencias();
            closeModal('modal-ocorrencia');
        }

        function handleAddVeiculo(event) {
            event.preventDefault();
            const placa = document.getElementById('v-placa').value.toUpperCase();
            const modelo = document.getElementById('v-modelo').value;
            const responsavel = document.getElementById('v-responsavel').value;

            const novoVeiculo = {
                id: veiculos.length + 1,
                placa: placa,
                modelo: modelo,
                responsavel: responsavel,
                status: "Dentro",
                entrada: new Date().toLocaleTimeString('pt-BR', {hour: '2-digit', minute:'2-digit'})
            };
            veiculos.push(novoVeiculo);
            renderVeiculos();
            closeModal('modal-veiculo');
        }

        function showMessage(title, iconHtml, message, colorClass) {
            document.getElementById('message-icon').innerHTML = iconHtml;
            document.getElementById('message-icon').classList.remove('text-ifg-accent', 'text-red-500', 'text-blue-500', 'text-green-500'); // Garante a remoção correta
            document.getElementById('message-icon').classList.add(colorClass);

            // Substituir quebras de linha Markdown e renderizar em negrito
            const formattedMessage = message.replace(/\*\*(.*?)\*\*/g, '<strong>$1</strong>');
            
            document.getElementById('message-content').innerHTML = `<strong>${title}:</strong> ${formattedMessage}`;
            openModal('modal-message');
        }

        // --- FUNÇÕES DE GRÁFICOS (CHART.JS) ---

        function drawCharts() {
            // Destrói gráficos existentes para evitar duplicidade ou problemas de tema
            if (acessosChart) acessosChart.destroy();
            if (destinosChart) destinosChart.destroy();
            if (picoChart) picoChart.destroy();

            const isDark = document.documentElement.classList.contains('dark');
            const textColor = isDark ? '#f3f4f6' : '#1f2937';
            const gridColor = isDark ? 'rgba(255, 255, 255, 0.1)' : 'rgba(0, 0, 0, 0.1)';
            const primaryColor = isDark ? '#00A000' : '#006400';

            // Dados Fictícios
            const dataAcessos = [120, 150, 140, 180, 200, 160, 170];
            const labelsAcessos = ['Seg', 'Ter', 'Qua', 'Qui', 'Sex', 'Sáb', 'Dom'];

            const dataDestinos = [45, 30, 25, 15, 10];
            const labelsDestinos = ['Biblioteca', 'Depto. TI', 'Pró-Reitoria', 'Laboratório', 'Auditório'];

            const dataPicoEntrada = [20, 35, 45, 60, 40, 25, 10, 5];
            const dataPicoSaida = [5, 15, 20, 30, 55, 40, 20, 10];
            const labelsPico = ['07h', '08h', '09h', '10h', '11h', '12h', '13h', '14h'];


            // 1. Gráfico de Barras - Acessos por Dia
            acessosChart = new Chart(document.getElementById('acessosChart'), {
                type: 'bar',
                data: {
                    labels: labelsAcessos,
                    datasets: [{
                        label: 'Quantidade de Acessos',
                        data: dataAcessos,
                        backgroundColor: primaryColor,
                        borderRadius: 5
                    }]
                },
                options: {
                    responsive: true,
                    plugins: { legend: { display: false } },
                    scales: {
                        y: { beginAtZero: true, ticks: { color: textColor }, grid: { color: gridColor } },
                        x: { ticks: { color: textColor }, grid: { display: false } }
                    }
                }
            });

            // 2. Gráfico de Rosca - Visitantes Mais Frequentes (Destino)
            destinosChart = new Chart(document.getElementById('destinosChart'), {
                type: 'doughnut',
                data: {
                    labels: labelsDestinos,
                    datasets: [{
                        data: dataDestinos,
                        backgroundColor: ['#006400', '#00A000', '#38b000', '#83E879', '#D9FFD6'], // Tons de verde
                        hoverOffset: 4
                    }]
                },
                options: {
                    responsive: true,
                    plugins: {
                        legend: { position: 'right', labels: { color: textColor } },
                    }
                }
            });

            // 3. Gráfico de Linha - Horários de Pico
            picoChart = new Chart(document.getElementById('picoChart'), {
                type: 'line',
                data: {
                    labels: labelsPico,
                    datasets: [
                        {
                            label: 'Entrada',
                            data: dataPicoEntrada,
                            borderColor: primaryColor,
                            tension: 0.3,
                            fill: false
                        },
                        {
                            label: 'Saída',
                            data: dataPicoSaida,
                            borderColor: '#FFA500', // Laranja
                            tension: 0.3,
                            fill: false
                        }
                    ]
                },
                options: {
                    responsive: true,
                    plugins: { legend: { labels: { color: textColor } } },
                    scales: {
                        y: { beginAtZero: true, ticks: { color: textColor }, grid: { color: gridColor } },
                        x: { ticks: { color: textColor }, grid: { color: gridColor } }
                    }
                }
            });
        }

        // --- INICIALIZAÇÃO ---

        function initApp() {
            // 1. Configura listeners
            document.getElementById('login-form').addEventListener('submit', handleLogin);

            document.querySelectorAll('.sidebar-link').forEach(link => {
                link.addEventListener('click', (e) => {
                    e.preventDefault();
                    navigateTo(e.currentTarget.dataset.view);
                });
            });

            document.getElementById('theme-toggle').addEventListener('click', toggleTheme);

            // Modais e Botões de Ação
            document.getElementById('btn-novo-visitante').addEventListener('click', () => openModal('modal-visitante'));
            document.getElementById('form-visitante').addEventListener('submit', handleAddVisitante);
            document.getElementById('btn-gerar-qr').addEventListener('click', () => showMessage('QR Code', `<i class="fa-solid fa-qrcode"></i>`, 'QR Code de Acesso gerado com sucesso para o visitante. Pronto para leitura!', 'text-blue-500'));

            document.getElementById('btn-nova-ocorrencia').addEventListener('click', () => {
                document.getElementById('o-datahora').value = new Date(Date.now() - (new Date().getTimezoneOffset() * 60000)).toISOString().substring(0, 16);
                openModal('modal-ocorrencia');
            });
            document.getElementById('form-ocorrencia').addEventListener('submit', handleAddOcorrencia);

            document.getElementById('btn-novo-veiculo').addEventListener('click', () => openModal('modal-veiculo'));
            document.getElementById('form-veiculo').addEventListener('submit', handleAddVeiculo);

            // 2. Renderiza dados iniciais
            renderVisitantes();
            renderOcorrencias();
            renderVeiculos();
        }

        // Garante que o script roda após o carregamento do DOM
        window.onload = initApp;

    </script>
</body>
</html>

