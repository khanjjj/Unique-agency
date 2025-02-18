# Unique-agency<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Creative Design Agency</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#4338ca',
                        secondary: '#f97316'
                    },
                    borderRadius: {
                        'none': '0px',
                        'sm': '4px',
                        DEFAULT: '8px',
                        'md': '12px',
                        'lg': '16px',
                        'xl': '20px',
                        '2xl': '24px',
                        '3xl': '32px',
                        'full': '9999px',
                        'button': '8px'
                    }
                }
            }
        }
    </script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/remixicon@4.5.0/fonts/remixicon.css" rel="stylesheet">
    <style>
        :where([class^="ri-"])::before { content: "\f3c2"; }
        .hover-up:hover { transform: translateY(-5px); }
    </style>
</head>
<body class="bg-white">
    <header class="fixed top-0 left-0 right-0 bg-white/95 backdrop-blur-sm z-50 border-b border-gray-100">
        <nav class="container mx-auto px-6 py-4 flex items-center justify-between">
            <a href="#" class="text-2xl font-['Pacifico'] text-primary">logo</a>
            <div class="hidden md:flex items-center space-x-8">
                <a href="#" class="text-gray-800 hover:text-primary">Home</a>
                <a href="#" class="text-gray-800 hover:text-primary">Services</a>
                <a href="#" class="text-gray-800 hover:text-primary">Portfolio</a>
                <a href="#" class="text-gray-800 hover:text-primary">About</a>
                <a href="#" class="text-gray-800 hover:text-primary">Contact</a>
            </div>
            <button class="bg-primary text-white px-6 py-2 !rounded-button hover:bg-primary/90 whitespace-nowrap">Get Started</button>
        </nav>
    </header>

    <main class="pt-20">
        <section class="relative min-h-[90vh] flex items-center" style="background-image: url('https://public.readdy.ai/ai/img_res/003c9a907233214bb8239c7e0bfd34a6.jpg'); background-size: cover; background-position: center;">
            <div class="absolute inset-0 bg-gradient-to-r from-white via-white/90 to-transparent"></div>
            <div class="container mx-auto px-6 relative">
                <div class="max-w-2xl">
                    <h1 class="text-6xl font-bold mb-6 leading-tight">Transforming Ideas into Visual Excellence</h1>
                    <p class="text-xl text-gray-600 mb-8">We craft stunning designs that elevate brands and create meaningful connections with your audience.</p>
                    <div class="flex gap-4">
                        <button class="bg-primary text-white px-8 py-3 !rounded-button hover:bg-primary/90 whitespace-nowrap">View Our Work</button>
                        <button class="border-2 border-primary text-primary px-8 py-3 !rounded-button hover:bg-primary/5 whitespace-nowrap">Let's Talk</button>
                    </div>
                </div>
            </div>
        </section>

        <section class="py-20 bg-gray-50">
            <div class="container mx-auto px-6">
                <div class="text-center mb-16">
                    <h2 class="text-4xl font-bold mb-4">Our Services</h2>
