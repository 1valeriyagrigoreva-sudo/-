<!DOCTYPE html>

<html class="light" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Lumina Indigo - Еженедельный план</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700;800&amp;family=Inter:wght@400;500;600&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "on-surface-variant": "#5f5e68",
                        "on-secondary": "#fbf7ff",
                        "surface-container-lowest": "#ffffff",
                        "tertiary": "#755478",
                        "error": "#a8364b",
                        "on-primary": "#fbf7ff",
                        "surface-container-high": "#eae6f1",
                        "background": "#fcf8fe",
                        "on-tertiary": "#fff7fa",
                        "on-error": "#fff7f7",
                        "secondary-container": "#e3e0f9",
                        "outline-variant": "#b3b0bc",
                        "primary": "#5b5a8b",
                        "on-secondary-container": "#505064",
                        "outline": "#7b7984",
                        "on-primary-fixed": "#232250",
                        "surface": "#fcf8fe",
                        "primary-dim": "#4e4e7f",
                        "on-primary-container": "#383766",
                        "error-dim": "#6b0221",
                        "on-error-container": "#6e0523",
                        "tertiary-container": "#fcd2fe",
                        "inverse-surface": "#0e0e12",
                        "tertiary-fixed-dim": "#eec4ef",
                        "tertiary-dim": "#68486c",
                        "secondary": "#5e5d72",
                        "on-surface": "#32313b",
                        "primary-fixed-dim": "#afaee5",
                        "on-secondary-fixed-variant": "#5a596f",
                        "surface-container-low": "#f6f2fa",
                        "on-primary-fixed-variant": "#414070",
                        "on-tertiary-fixed-variant": "#6f4e73",
                        "surface-variant": "#e4e1ed",
                        "inverse-primary": "#bdbcf4",
                        "tertiary-fixed": "#fcd2fe",
                        "on-background": "#32313b",
                        "secondary-fixed-dim": "#d4d2eb",
                        "on-tertiary-fixed": "#513355",
                        "on-secondary-fixed": "#3e3d51",
                        "surface-tint": "#5b5a8b",
                        "error-container": "#f97386",
                        "surface-bright": "#fcf8fe",
                        "on-tertiary-container": "#654568",
                        "primary-fixed": "#bdbcf4",
                        "surface-container-highest": "#e4e1ed",
                        "inverse-on-surface": "#9e9ca2",
                        "secondary-dim": "#525166",
                        "secondary-fixed": "#e3e0f9",
                        "surface-dim": "#dbd8e4",
                        "primary-container": "#bdbcf4",
                        "surface-container": "#f0ecf6"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "fontFamily": {
                        "headline": ["Manrope"],
                        "body": ["Inter"],
                        "label": ["Inter"]
                    }
                },
            },
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .tonal-shift {
            transition: background-color 0.3s ease;
        }
    </style>
</head>
<body class="bg-surface font-body text-on-surface">
<!-- SideNavBar -->
<aside class="h-screen w-64 fixed left-0 top-0 border-r-0 bg-slate-50 dark:bg-slate-900 flex flex-col py-8 px-4 z-50">
<div class="mb-10 px-2 flex items-center gap-3">
<span class="text-xl font-bold text-[#5C59E8] dark:text-[#7C79FF] tracking-tighter font-headline">Lumina Indigo</span>
</div>
<nav class="flex-1 space-y-1">
<a class="flex items-center gap-3 px-4 py-3 text-slate-500 dark:text-slate-400 hover:text-[#5C59E8] dark:hover:text-[#7C79FF] transition-all duration-300 ease-in-out hover:bg-slate-100 dark:hover:bg-slate-800 font-manrope tracking-tight font-medium text-sm rounded-lg" href="#">
<span class="material-symbols-outlined" data-icon="dashboard">dashboard</span>
<span>Dashboard</span>
</a>
<a class="flex items-center gap-3 px-4 py-3 text-slate-500 dark:text-slate-400 hover:text-[#5C59E8] dark:hover:text-[#7C79FF] transition-all duration-300 ease-in-out hover:bg-slate-100 dark:hover:bg-slate-800 font-manrope tracking-tight font-medium text-sm rounded-lg" href="#">
<span class="material-symbols-outlined" data-icon="assignment">assignment</span>
<span>Tasks</span>
</a>
<a class="flex items-center gap-3 px-4 py-3 text-[#5C59E8] dark:text-[#7C79FF] font-semibold bg-white dark:bg-slate-800 rounded-r-full shadow-sm font-manrope tracking-tight text-sm translate-x-1 transition-transform" href="#">
<span class="material-symbols-outlined" data-icon="calendar_view_week">calendar_view_week</span>
<span>Weekly Plan</span>
</a>
<a class="flex items-center gap-3 px-4 py-3 text-slate-500 dark:text-slate-400 hover:text-[#5C59E8] dark:hover:text-[#7C79FF] transition-all duration-300 ease-in-out hover:bg-slate-100 dark:hover:bg-slate-800 font-manrope tracking-tight font-medium text-sm rounded-lg" href="#">
<span class="material-symbols-outlined" data-icon="insights">insights</span>
<span>Analytics</span>
</a>
<a class="flex items-center gap-3 px-4 py-3 text-slate-500 dark:text-slate-400 hover:text-[#5C59E8] dark:hover:text-[#7C79FF] transition-all duration-300 ease-in-out hover:bg-slate-100 dark:hover:bg-slate-800 font-manrope tracking-tight font-medium text-sm rounded-lg" href="#">
<span class="material-symbols-outlined" data-icon="settings">settings</span>
<span>Settings</span>
</a>
</nav>
<div class="mt-auto pt-6 px-2">
<button class="w-full py-3 px-4 bg-gradient-to-br from-primary to-primary-dim text-on-primary rounded-xl font-semibold shadow-[0px_12px_32px_rgba(91,90,139,0.06)] flex items-center justify-center gap-2 hover:opacity-90 transition-all active:scale-95">
<span class="material-symbols-outlined" data-icon="add">add</span>
                New Task
            </button>
<div class="mt-8 flex items-center gap-3">
<img class="w-10 h-10 rounded-full object-cover border-2 border-primary-container" data-alt="close-up portrait of a professional woman with a calm and focused expression in a modern office setting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAWqp6Ec2FjvKCtnBQ6UCMZfDOqxFrHk8PtRwoiR1U_XFn09paCsKuHY2Uk29AgZ979-2URXrWyZKIHUhBKbxWIPRcfn_I727WEeoYVYwfLb5VKDWpwqAqzMjrDsKD30C-6IVO9ouR28rpz2EgFSt2gYulWVruMTQWPhJYoMbvGPOK1Wpsu6Ki8UnVKpzOd-5yJOyZzS9fckluvPNjnIdCntkm_3Tf3hukPrSik1zGBYWJ6leHTA-BezPI7pD_DkJTJ-8Gsd2swmTmH"/>
<div>
<p class="text-sm font-bold text-on-surface">Lumina Indigo</p>
<p class="text-xs text-on-surface-variant">Task Curator</p>
</div>
</div>
</div>
</aside>
<!-- Main Content Area -->
<main class="ml-64 min-h-screen bg-surface">
<!-- TopNavBar -->
<header class="fixed top-0 right-0 w-[calc(100%-16rem)] z-40 bg-white/70 dark:bg-slate-950/70 backdrop-blur-xl flex justify-between items-center px-8 h-16 shadow-[0px_12px_32px_rgba(91,90,139,0.06)]">
<div class="flex items-center bg-surface-container-low px-4 py-2 rounded-full w-96">
<span class="material-symbols-outlined text-outline text-sm" data-icon="search">search</span>
<input class="bg-transparent border-none focus:ring-0 text-sm font-body ml-2 w-full placeholder:text-outline-variant" placeholder="Поиск задач..." type="text"/>
</div>
<div class="flex items-center gap-6">
<button class="relative text-on-surface-variant hover:text-primary transition-colors">
<span class="material-symbols-outlined" data-icon="notifications">notifications</span>
<span class="absolute top-0 right-0 w-2 h-2 bg-error rounded-full"></span>
</button>
<div class="h-8 w-[1px] bg-outline-variant/30"></div>
<div class="flex items-center gap-2">
<span class="text-sm font-medium font-manrope">Александр В.</span>
<span class="material-symbols-outlined text-primary" data-icon="account_circle">account_circle</span>
</div>
</div>
</header>
<!-- Page Content -->
<div class="pt-24 pb-12 px-10">
<!-- Weekly Priority Banner -->
<section class="mb-10">
<div class="relative overflow-hidden bg-gradient-to-r from-primary to-primary-dim rounded-[2rem] p-8 text-on-primary shadow-lg group">
<div class="relative z-10 flex flex-col md:flex-row justify-between items-center gap-6">
<div class="max-w-xl">
<span class="text-[10px] font-bold tracking-[0.2em] text-primary-fixed-dim uppercase mb-2 block">ПРИОРИТЕТ НЕДЕЛИ</span>
<h1 class="text-3xl font-extrabold font-headline leading-tight mb-3">Запуск проекта "Ethereal" &amp; Оптимизация UX</h1>
<p class="text-primary-container text-sm font-body max-w-lg opacity-90">Фокус на завершении ключевых модулей интерфейса и проведении финального тестирования с командой разработки.</p>
</div>
<div class="flex -space-x-3">
<img class="w-12 h-12 rounded-full border-4 border-primary ring-2 ring-primary-container object-cover" data-alt="professional man in a grey suit smiling" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDrpvJZBCRSyItPPPUo26iJOcdauJ3xjuKIdzzRF4SFe6dW3xrc1Y3581nBQKn6Yoeu9p2vtO5JQxYXJgri2MTzO3XklQQKwR8mE2IV8MYYFELeISrx4wI7zXXEdDd6EDqsMPSx9g_VjcOpH9OSI_Q3CXPoqxh9ZjBMuNYqHQdkrjZloS_0755ghT5PrGhu5g4Luav6kxv8TWJTDUewyxGWe8TVHwcw2I68FzG7iNXKry0AmH7cZ60VsCK3RlK4wtYH1vO2Ir8clfsC"/>
<img class="w-12 h-12 rounded-full border-4 border-primary ring-2 ring-primary-container object-cover" data-alt="smiling woman with glasses in a creative studio" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDqDwPgecScOEB6OpLv_es9WHEZnuBzRu0Fl4cv0a8uoUzSLEo8i80TVG2H1cjbpVX0ryj35mmxfTUMBEx640uDGQeZqjcEdPczlg5LJDbQ6YQhpHuGxRyvy-3gUTTmt0c78hUqwiI1zws7EDLqCVA_HEgKo2AgT6NIJB__dT7Kmi_OWpyRiwFhD9THD7V4niMHmhvB-HrLwU_LGiG5p0VRV-CToL_28qxKNGAi_pYsfsuedd9XK-JQmuXe5ynJql63BupVd3rcBYs-"/>
<img class="w-12 h-12 rounded-full border-4 border-primary ring-2 ring-primary-container object-cover" data-alt="professional woman leading a meeting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCvgUUxsmRz5EPNjtSDrnq0cAUVq4oNLwJiDhMthn4ub-ou4w-LhuakQTV5vYVBJV4kcE9OM6IJsx6ZmBfCXAWN2hCPZCEhKwpB5evpvLoZ2zV_gytqXkJGNFIAnciGq5plZiGBTQiYuSf5ka4J0Gsz1Wp0gDPNVMsYA9I9EyxIUm7mMGfl3j-9zAbLrhUrOwDlG0z6Swr1nVdXxHHUjARsllfSRmEWsjYUbwDDgKgauNHtmG7QjDioFu9YXpURKxG63Y5SwCKw0Vvw"/>
<div class="w-12 h-12 rounded-full border-4 border-primary ring-2 ring-primary-container bg-primary-container flex items-center justify-center text-on-primary-container text-xs font-bold">+5</div>
</div>
</div>
<!-- Decorative background glow -->
<div class="absolute -right-20 -top-20 w-80 h-80 bg-white/10 rounded-full blur-[80px]"></div>
<div class="absolute -left-10 -bottom-10 w-40 h-40 bg-tertiary-container/20 rounded-full blur-[50px]"></div>
</div>
</section>
<!-- Weekly Grid -->
<div class="grid grid-cols-1 lg:grid-cols-7 gap-6">
<!-- Monday -->
<div class="space-y-4">
<div class="flex flex-col mb-4">
<span class="text-on-surface-variant text-[11px] font-bold tracking-widest uppercase">Понедельник</span>
<span class="text-2xl font-extrabold font-headline text-on-surface">12</span>
</div>
<div class="bg-surface-container-lowest p-5 rounded-xl shadow-[0px_4px_12px_rgba(91,90,139,0.03)] hover:shadow-[0px_12px_32px_rgba(91,90,139,0.06)] transition-all group border-l-4 border-primary">
<div class="flex justify-between items-start mb-3">
<span class="text-[10px] font-bold bg-primary-container text-on-primary-container px-2 py-1 rounded-full">WORK</span>
<span class="text-[10px] font-medium text-on-surface-variant">09:00</span>
</div>
<h3 class="text-sm font-bold font-headline mb-1 leading-snug">Синхронизация команды</h3>
<p class="text-xs text-on-surface-variant line-clamp-2">Обсуждение планов на неделю и блокирующих факторов.</p>
<div class="mt-4 flex items-center gap-2">
<span class="material-symbols-outlined text-[16px] text-primary" data-icon="check_circle" style="font-variation-settings: 'FILL' 1;">check_circle</span>
<span class="text-[10px] font-semibold text-primary">Завершено</span>
</div>
</div>
<div class="bg-surface-container-lowest p-5 rounded-xl shadow-[0px_4px_12px_rgba(91,90,139,0.03)] hover:shadow-[0px_12px_32px_rgba(91,90,139,0.06)] transition-all border-l-4 border-tertiary-dim">
<div class="flex justify-between items-start mb-3">
<span class="text-[10px] font-bold bg-tertiary-container text-on-tertiary-container px-2 py-1 rounded-full">DESIGN</span>
<span class="text-[10px] font-medium text-on-surface-variant">14:30</span>
</div>
<h3 class="text-sm font-bold font-headline mb-1 leading-snug">Ревью макетов Dash</h3>
<p class="text-xs text-on-surface-variant line-clamp-2">Проверка новой цветовой палитры и шрифтов.</p>
<div class="mt-4 flex items-center gap-2">
<span class="material-symbols-outlined text-[16px] text-outline" data-icon="radio_button_unchecked">radio_button_unchecked</span>
<span class="text-[10px] font-semibold text-on-surface-variant">В процессе</span>
</div>
</div>
</div>
<!-- Tuesday -->
<div class="space-y-4">
<div class="flex flex-col mb-4">
<span class="text-on-surface-variant text-[11px] font-bold tracking-widest uppercase">Вторник</span>
<span class="text-2xl font-extrabold font-headline text-on-surface">13</span>
</div>
<div class="bg-surface-container-lowest p-5 rounded-xl shadow-[0px_4px_12px_rgba(91,90,139,0.03)] hover:shadow-[0px_12px_32px_rgba(91,90,139,0.06)] transition-all border-l-4 border-error">
<div class="flex justify-between items-start mb-3">
<span class="text-[10px] font-bold bg-error-container text-on-error-container px-2 py-1 rounded-full">URGENT</span>
<span class="text-[10px] font-medium text-on-surface-variant">11:00</span>
</div>
<h3 class="text-sm font-bold font-headline mb-1 leading-snug">Интервью с клиентом</h3>
<p class="text-xs text-on-surface-variant line-clamp-2">Сбор обратной связи по прототипу Lumina.</p>
</div>
<div class="bg-surface-container-low border border-dashed border-outline-variant p-5 rounded-xl flex items-center justify-center group cursor-pointer hover:bg-surface-container-high transition-colors">
<div class="text-center">
<span class="material-symbols-outlined text-outline group-hover:text-primary transition-colors" data-icon="add">add</span>
<p class="text-[10px] font-bold text-outline-variant group-hover:text-primary mt-1">ДОБАВИТЬ</p>
</div>
</div>
</div>
<!-- Wednesday -->
<div class="space-y-4">
<div class="flex flex-col mb-4">
<span class="text-on-surface-variant text-[11px] font-bold tracking-widest uppercase text-primary">Среда</span>
<div class="flex items-center gap-2">
<span class="text-2xl font-extrabold font-headline text-primary">14</span>
<div class="w-1.5 h-1.5 bg-primary rounded-full"></div>
</div>
</div>
<div class="relative bg-surface-container-lowest p-5 rounded-xl shadow-[0px_12px_32px_rgba(91,90,139,0.08)] border-l-4 border-primary overflow-hidden">
<div class="absolute right-0 top-0 w-24 h-24 bg-primary/5 rounded-full -translate-y-12 translate-x-12 blur-2xl"></div>
<div class="flex justify-between items-start mb-3">
<span class="text-[10px] font-bold bg-primary-container text-on-primary-container px-2 py-1 rounded-full">DEEP WORK</span>
<span class="text-[10px] font-medium text-on-surface-variant">10:00 - 13:00</span>
</div>
<h3 class="text-sm font-bold font-headline mb-1 leading-snug">Архитектура базы данных</h3>
<p class="text-xs text-on-surface-variant line-clamp-2">Проектирование связей для модуля уведомлений.</p>
<div class="mt-4 flex items-center -space-x-1">
<img class="w-6 h-6 rounded-full border-2 border-white object-cover" data-alt="headshot of a man with a beard in a modern setting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDCNQbcfyN1dlWFSTTH4RBSsZaXCCPcu7xEau7XDl3lHCgWy18W442mF_W6egWWe5NvmkAtVn34Vvn56q_AIJq4LxR_8FNs1hsocZZs-JwUpahzNMF7HyJON8kx_-eSBe5OPE5_9wHGSDAkhon-CSHCmyRk37bK5_ETuXVLXPIzXNKpKVuEAkZMF5VlbYmOMJc4UPYeIOTvRNrNAMLOqK1FAuueJqHOwbEQHqR1HjP8bP_c9bKepJyQpXxZmNbEDWE9Q1mBZyELCyZy"/>
<img class="w-6 h-6 rounded-full border-2 border-white object-cover" data-alt="professional woman with tied back hair" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBHCmHC0ir-FsAJsy-U-Dn6q3NgICM0gRnMkhW8teszg-abXp6DoOSXQ1k9NF8QPID2bOJzZ3wEwCmQSmbbUe8hCjVdVZdeL8HS1Ap-MgmUIZtcpurgVXBNA2WcrBsHRWLzOsRmZ-kv3pI3JHPl8f083fvWaaLEVNMPtTpXsLFIC-ELBKMs3akJemJ20-9exPBu_Zmxfc1N_dGfh3wZcQBZK_G5_XlaL0zZsWXUdqNCDG1ohE0iWkMfTRsMMlqbIODpIKaDO3oLArzS"/>
</div>
</div>
<div class="bg-surface-container-lowest p-5 rounded-xl shadow-[0px_4px_12px_rgba(91,90,139,0.03)] border-l-4 border-outline">
<div class="flex justify-between items-start mb-3">
<span class="text-[10px] font-bold bg-surface-container-high text-on-surface-variant px-2 py-1 rounded-full">PERSONAL</span>
<span class="text-[10px] font-medium text-on-surface-variant">18:30</span>
</div>
<h3 class="text-sm font-bold font-headline mb-1 leading-snug">Йога &amp; Медитация</h3>
<p class="text-xs text-on-surface-variant">Восстановление энергии после рабочего дня.</p>
</div>
</div>
<!-- Thursday -->
<div class="space-y-4">
<div class="flex flex-col mb-4">
<span class="text-on-surface-variant text-[11px] font-bold tracking-widest uppercase">Четверг</span>
<span class="text-2xl font-extrabold font-headline text-on-surface">15</span>
</div>
<div class="bg-surface-container-lowest p-5 rounded-xl shadow-[0px_4px_12px_rgba(91,90,139,0.03)] border-l-4 border-tertiary">
<div class="flex justify-between items-start mb-3">
<span class="text-[10px] font-bold bg-tertiary-container text-on-tertiary-container px-2 py-1 rounded-full">MARKETING</span>
<span class="text-[10px] font-medium text-on-surface-variant">15:00</span>
</div>
<h3 class="text-sm font-bold font-headline mb-1 leading-snug">Стратегия запуска</h3>
<p class="text-xs text-on-surface-variant line-clamp-2">Подготовка контента для социальных сетей и рассылок.</p>
</div>
</div>
<!-- Friday -->
<div class="space-y-4">
<div class="flex flex-col mb-4">
<span class="text-on-surface-variant text-[11px] font-bold tracking-widest uppercase">Пятница</span>
<span class="text-2xl font-extrabold font-headline text-on-surface">16</span>
</div>
<div class="bg-surface-container-lowest p-5 rounded-xl shadow-[0px_4px_12px_rgba(91,90,139,0.03)] border-l-4 border-primary-dim">
<div class="flex justify-between items-start mb-3">
<span class="text-[10px] font-bold bg-primary-container text-on-primary-container px-2 py-1 rounded-full">WORK</span>
<span class="text-[10px] font-medium text-on-surface-variant">12:00</span>
</div>
<h3 class="text-sm font-bold font-headline mb-1 leading-snug">Демонстрация недели</h3>
<p class="text-xs text-on-surface-variant line-clamp-2">Презентация достигнутых результатов стейкхолдерам.</p>
</div>
<div class="bg-surface-container-lowest p-5 rounded-xl shadow-[0px_4px_12px_rgba(91,90,139,0.03)] border-l-4 border-secondary">
<div class="flex justify-between items-start mb-3">
<span class="text-[10px] font-bold bg-secondary-container text-on-secondary-container px-2 py-1 rounded-full">PLANNING</span>
<span class="text-[10px] font-medium text-on-surface-variant">17:00</span>
</div>
<h3 class="text-sm font-bold font-headline mb-1 leading-snug">Ретроспектива</h3>
<p class="text-xs text-on-surface-variant line-clamp-2">Анализ эффективности и планирование следующей недели.</p>
</div>
</div>
<!-- Saturday -->
<div class="space-y-4">
<div class="flex flex-col mb-4">
<span class="text-on-surface-variant text-[11px] font-bold tracking-widest uppercase">Суббота</span>
<span class="text-2xl font-extrabold font-headline text-on-surface">17</span>
</div>
<div class="bg-surface-container-low/50 border border-dashed border-outline-variant h-32 rounded-xl flex items-center justify-center italic text-xs text-outline-variant">
                        Свободный день
                    </div>
</div>
<!-- Sunday -->
<div class="space-y-4">
<div class="flex flex-col mb-4">
<span class="text-on-surface-variant text-[11px] font-bold tracking-widest uppercase">Воскресенье</span>
<span class="text-2xl font-extrabold font-headline text-on-surface">18</span>
</div>
<div class="bg-surface-container-low/50 border border-dashed border-outline-variant h-32 rounded-xl flex items-center justify-center italic text-xs text-outline-variant">
                        Свободный день
                    </div>
</div>
</div>
<!-- Stats & Insights Footer Bento -->
<section class="mt-12 grid grid-cols-1 md:grid-cols-3 gap-6">
<div class="bg-surface-container-low p-6 rounded-2xl flex items-center gap-4">
<div class="w-12 h-12 rounded-full bg-primary-container flex items-center justify-center text-primary">
<span class="material-symbols-outlined" data-icon="task_alt">task_alt</span>
</div>
<div>
<p class="text-2xl font-extrabold font-headline text-on-surface">24/30</p>
<p class="text-xs font-medium text-on-surface-variant uppercase tracking-wider">Задач выполнено</p>
</div>
</div>
<div class="bg-surface-container-low p-6 rounded-2xl flex items-center gap-4">
<div class="w-12 h-12 rounded-full bg-tertiary-container flex items-center justify-center text-tertiary">
<span class="material-symbols-outlined" data-icon="schedule">schedule</span>
</div>
<div>
<p class="text-2xl font-extrabold font-headline text-on-surface">42ч</p>
<p class="text-xs font-medium text-on-surface-variant uppercase tracking-wider">Рабочее время</p>
</div>
</div>
<div class="bg-surface-container-low p-6 rounded-2xl flex items-center gap-4">
<div class="w-12 h-12 rounded-full bg-secondary-container flex items-center justify-center text-secondary">
<span class="material-symbols-outlined" data-icon="auto_awesome">auto_awesome</span>
</div>
<div>
<p class="text-2xl font-extrabold font-headline text-on-surface">85%</p>
<p class="text-xs font-medium text-on-surface-variant uppercase tracking-wider">Продуктивность</p>
</div>
</div>
</section>
</div>
</main>
<!-- Contextual FAB -->
<button class="fixed bottom-8 right-8 w-16 h-16 rounded-full bg-gradient-to-br from-primary to-primary-dim text-on-primary shadow-[0px_12px_32px_rgba(91,90,139,0.3)] flex items-center justify-center hover:scale-105 active:scale-95 transition-all z-50">
<span class="material-symbols-outlined text-2xl" data-icon="add">add</span>
</button>
</body></html>