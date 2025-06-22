# HDMI-
JT 20
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Renda Extra com IA | Josmil</title>

    <script src="https://cdn.tailwindcss.com"></script>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap" rel="stylesheet">
    
    <style>
        /* --- CÓDIGO DO FUNDO ANIMADO ADICIONADO --- */
        @keyframes gradientAnimation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* Estilos e Animações Personalizadas */
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth; /* Mantido para rolagem suave */
            
            /* Animação de Fundo */
            color: white; /* Garante que o texto padrão seja branco */
            background: linear-gradient(-45deg, #000000, #0a0a0a, #033d20, #000000);
            background-size: 400% 400%;
            animation: gradientAnimation 20s ease infinite;
        }
        /* --- FIM DA SEÇÃO DO FUNDO ANIMADO --- */

        .header-bg {
            /* O fundo da página agora cobre tudo, então tornamos o header transparente */
            background-color: transparent;
            /* A vinheta radial foi mantida para o efeito de luz no topo */
            background-image: radial-gradient(circle at 50% 0%, rgba(0, 255, 136, 0.1) 0%, rgba(0, 0, 0, 0) 50%);
        }
        
        /* Efeitos de Animação */
        .cta-button {
            transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
        }
        .cta-button:hover {
            transform: translateY(-3px) scale(1.05);
            box-shadow: 0 6px 25px rgba(0, 255, 136, 0.25);
        }
        .testimonial-card, .benefit-card {
            border: 1px solid #27272a;
        }

        /* Animação de Pulsação de Texto */
        @keyframes pulse-glow {
            0%, 100% { text-shadow: 0 0 10px rgba(0, 255, 136, 0.5); }
            50% { text-shadow: 0 0 20px rgba(0, 255, 136, 0.7); }
        }

        /* Animação de Pulsação de Botão */
         @keyframes button-pulse-glow {
            0%, 100% { box-shadow: 0 0 20px rgba(0, 255, 136, 0.2); }
            50% { box-shadow: 0 0 35px rgba(0, 255, 136, 0.4); }
        }

        .text-glow-animated {
            animation: pulse-glow 3s infinite ease-in-out;
        }
        .button-glow-animated {
             animation: button-pulse-glow 2.5s infinite ease-in-out;
        }

        /* Animação de Surgimento ao Rolar (Scroll Reveal) */
        .reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 0.8s ease-out, transform 0.6s ease-out;
        }
        .reveal.visible {
            opacity: 1;
            transform: translateY(0);
        }
        
        /* Efeito de delay para os cards */
        .reveal.benefit-card:nth-child(1) { transition-delay: 0.1s; }
        .reveal.benefit-card:nth-child(2) { transition-delay: 0.2s; }
        .reveal.benefit-card:nth-child(3) { transition-delay: 0.3s; }
        .reveal.benefit-card:nth-child(4) { transition-delay: 0.4s; }
        .reveal.testimonial-card:nth-child(1) { transition-delay: 0.1s; }
        .reveal.testimonial-card:nth-child(2) { transition-delay: 0.2s; }
        .reveal.testimonial-card:nth-child(3) { transition-delay: 0.3s; }
        .reveal.testimonial-card:nth-child(4) { transition-delay: 0.4s; }
    </style>
</head>
<body class="text-white"> <header class="header-bg text-center py-20 md:py-32 px-6">
        <div class="max-w-4xl mx-auto">
            <h1 class="text-4xl md:text-6xl font-black uppercase text-glow-animated" style="color: #00ff88;">
                10 Formas Infalíveis de Lucrar com IA
            </h1>
            <p class="mt-6 text-lg md:text-xl max-w-2xl mx-auto text-zinc-300 reveal">
                Descubra os 10 métodos validados para criar uma nova fonte de renda online ainda hoje — mesmo que você seja iniciante.
            </p>
            <a href="https://pay.cakto.com.br/3ahen5v_438406" class="cta-button button-glow-animated inline-block mt-10 bg-[#00ff88] text-black font-bold text-lg px-10 py-4 rounded-lg uppercase tracking-wider reveal">
                Quero Acesso Imediato
            </a>
        </div>
    </header>

    <main>
        <section class="py-20 px-6">
            <div class="max-w-6xl mx-auto">
                <div class="text-center md:text-left reveal">
                    <h2 class="text-3xl md:text-4xl font-black"><span class="text-[#00ff88]">BENEFÍCIOS DO E-BOOK</span></h2>
                </div>
                <div class="mt-12 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                    <div class="benefit-card bg-zinc-800 p-8 rounded-xl text-center reveal">
                        <div class="text-[#00ff88] mb-4 w-10 h-10 mx-auto"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="m3.75 13.5 10.5-11.25L12 10.5h8.25L9.75 21.75 12 13.5H3.75Z" /></svg></div>
                        <h3 class="text-xl font-bold mb-2 text-white">Resultados Rápidos</h3>
                        <p class="text-zinc-400">Veja o impacto positivo no seu negócio em tempo recorde com nossas estratégias otimizadas.</p>
                    </div>
                    <div class="benefit-card bg-zinc-800 p-8 rounded-xl text-center reveal">
                        <div class="text-[#00ff88] mb-4 w-10 h-10 mx-auto"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M15.042 21.672 13.684 16.6m0 0-2.51 2.225.569-9.47 5.227 7.917-3.286-.672ZM12 2.25V4.5m5.832.168-1.591 1.591M21.75 12h-2.25m-1.668 5.832-1.591-1.591M5.25 12H3m1.668-5.832L6.168 7.832m7.414 0-1.591 1.591M4.5 5.25l1.668 1.591" /></svg></div>
                        <h3 class="text-xl font-bold mb-2 text-white">Precisão Estratégica</h3>
                        <p class="text-zinc-400">Alcançamos seu público-alvo com precisão cirúrgica, maximizando o retorno.</p>
                    </div>
                    <div class="benefit-card bg-zinc-800 p-8 rounded-xl text-center reveal">
                        <div class="text-[#00ff88] mb-4 w-10 h-10 mx-auto"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M18 18.72a9.094 9.094 0 0 0 3.741-.479 3 3 0 0 0-4.682-2.72m-7.5-2.952a4.5 4.5 0 1 1 9 0 4.5 4.5 0 0 1-9 0Zm10.293 4.643a6 6 0 1 1-11.586 0 6 6 0 0 1 11.586 0Z" /></svg></div>
                        <h3 class="text-xl font-bold mb-2 text-white">Suporte Dedicado</h3>
                        <p class="text-zinc-400">Nossa equipe está sempre disponível para tirar dúvidas e ajudar você a alcançar seus objetivos.</p>
                    </div>
                    <div class="benefit-card bg-zinc-800 p-8 rounded-xl text-center reveal">
                        <div class="text-[#00ff88] mb-4 w-10 h-10 mx-auto"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 18 9 11.25l4.306 4.306a11.95 11.95 0 0 1 5.814-5.518l2.74-1.22m0 0-5.94-2.281m5.94 2.28-2.28 5.941" /></svg></div>
                        <h3 class="text-xl font-bold mb-2 text-white">Crescimento Escalável</h3>
                        <p class="text-zinc-400">Oferecemos soluções que crescem junto com a sua empresa, garantindo sucesso a longo prazo.</p>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="comprar" class="py-20 px-6">
            <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div class="reveal">
                    <img src='https://i.postimg.cc/DwKWmw4w/Chat-GPT-Image-13-de-jun-de-2025-21-21-25.png' alt='Capa do e-book Renda Extra com IA' class="rounded-lg shadow-2xl mx-auto">
                </div>
                <div class="text-center md:text-left reveal">
                    <h2 class="text-3xl md:text-4xl font-black">Garanta seu acesso ao<br><span class="text-[#00ff88]">Renda Extra com IA</span></h2>
                    <p class="mt-4 text-lg text-zinc-300 max-w-md mx-auto md:mx-0">As 10 estratégias que você precisa para lucrar online, de forma prática e direta ao ponto.</p>
                    <div class="mt-8 bg-zinc-900 border border-zinc-800 rounded-xl p-8 max-w-md mx-auto md:mx-0">
                        <p class="text-zinc-400 text-lg">De <span class="line-through">R$147</span> por apenas:</p>
                        <p class="text-5xl font-black my-2 text-white">12x de <span class="text-[#00ff88]">R$3,80</span></p>
                        <p class="text-zinc-400">ou R$38 à vista</p>
                        <a href="https://pay.cakto.com.br/3ahen5v_438406" class="cta-button button-glow-animated block w-full mt-6 bg-[#00ff88] text-black font-bold text-lg text-center py-4 rounded-lg uppercase tracking-wider">Comprar Agora</a>
                        <p class="text-xs text-zinc-500 mt-4">✔ Acesso vitalício + Bônus exclusivos</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="bg-zinc-900 py-20 px-6">
            <div class="max-w-4xl mx-auto text-center reveal">
                <h2 class="text-3xl md:text-4xl font-black"><span class="text-[#00ff88]">O QUE VOCÊ TÁ ESPERANDO?</span></h2>
                <p class="text-zinc-400 mt-4 mb-8 max-w-3xl mx-auto">Não espere mais. Junte-se a centenas de pessoas que já estão aplicando nosso método e construindo uma nova realidade financeira.</p>
                <a href="https://pay.cakto.com.br/3ahen5v_438406" class="cta-button button-glow-animated inline-block bg-[#00ff88] text-black font-bold text-lg px-10 py-4 rounded-lg uppercase tracking-wider">
                    Garantir Minha Vaga
                </a>
            </div>
        </section>

        <section class="py-20 px-6">
            <div class="max-w-5xl mx-auto">
                <div class="text-center md:text-left reveal mb-12">
                    <h2 class="text-3xl md:text-4xl font-black"><span class="text-[#00ff88]">O QUE NOSSOS CLIENTES DIZEM</span></h2>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 text-left">
                    <div class="testimonial-card bg-zinc-800 rounded-xl p-8 flex flex-col reveal">
                        <p class="text-zinc-300 italic mb-6 flex-grow">"A parceria transformou nosso negócio. Os resultados apareceram muito mais rápido do que esperávamos. Recomendo!"</p>
                        <div class="flex items-center mt-auto">
                            <img src="https://i.pravatar.cc/80?img=1" alt="Foto do Cliente 1" class="w-14 h-14 rounded-full mr-4 border-2 border-[#00ff88]">
                            <div><h4 class="text-lg font-bold text-[#00ff88]">Ana Clara Souza</h4><span class="text-sm text-zinc-500">Diretora de Marketing</span></div>
                        </div>
                    </div>
                    <div class="testimonial-card bg-zinc-800 rounded-xl p-8 flex flex-col reveal">
                        <p class="text-zinc-300 italic mb-6 flex-grow">"O suporte é incrível e as estratégias são muito eficazes. Finalmente encontramos um serviço que entende nossas necessidades."</p>
                        <div class="flex items-center mt-auto">
                            <img src="https://i.pravatar.cc/80?img=2" alt="Foto do Cliente 2" class="w-14 h-14 rounded-full mr-4 border-2 border-[#00ff88]">
                            <div><h4 class="text-lg font-bold text-[#00ff88]">Bruno Mendes</h4><span class="text-sm text-zinc-500">CEO da StartUp Inova</span></div>
                        </div>
                    </div>
                    <div class="testimonial-card bg-zinc-800 rounded-xl p-8 flex flex-col reveal">
                        <p class="text-zinc-300 italic mb-6 flex-grow">"Profissionalismo e precisão em cada detalhe. O crescimento que tivemos no último trimestre foi espetacular."</p>
                        <div class="flex items-center mt-auto">
                            <img src="https://i.pravatar.cc/80?img=3" alt="Foto do Cliente 3" class="w-14 h-14 rounded-full mr-4 border-2 border-[#00ff88]">
                            <div><h4 class="text-lg font-bold text-[#00ff88]">Juliana Ferreira</h4><span class="text-sm text-zinc-500">Gerente de Vendas</span></div>
                        </div>
                    </div>
                    <div class="testimonial-card bg-zinc-800 rounded-xl p-8 flex flex-col reveal">
                        <p class="text-zinc-300 italic mb-6 flex-grow">"Estávamos perdidos sem saber como escalar. A equipe nos deu o caminho e as ferramentas certas. Gratidão!"</p>
                        <div class="flex items-center mt-auto">
                            <img src="https://i.pravatar.cc/80?img=4" alt="Foto do Cliente 4" class="w-14 h-14 rounded-full mr-4 border-2 border-[#00ff88]">
                            <div><h4 class="text-lg font-bold text-[#00ff88]">Ricardo Almeida</h4><span class="text-sm text-zinc-500">Fundador da Tech Solutions</span></div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <section class="bg-zinc-900 py-20 px-6">
            <div class="max-w-4xl mx-auto text-center reveal">
                <div class="text-center md:text-left">
                    <h2 class="text-3xl md:text-4xl font-black"><span class="text-[#00ff88]">CURSO FACEBOOK ADS PREMIUM</span></h2>
                    <p class="text-zinc-400 mt-4 mb-12 max-w-2xl">Oferta prêmio: curso completo de tráfego pago. Aprenda a criar anúncios que vendem todos os dias.</p>
                </div>
                <div class="max-w-md mx-auto bg-black rounded-lg shadow-xl overflow-hidden transform transition-transform hover:scale-105 reveal">
                    <img src="https://postimg.pro/images/2025/06/17/7K858z.png" alt="Capa do curso Facebook Ads na Prática" border="0">
                    <div class="p-8 text-left">
                        <h3 class="text-3xl font-black text-[#00ff88]">Facebook Ads na Prática</h3>
                        <p class="text-zinc-300 mt-2 mb-6">Aprenda a vender com anúncios em 12 aulas direto ao ponto.</p>
                        <div class="space-y-3 text-zinc-300 mb-6">
                            <p class="flex items-center"><span class="text-[#00ff88] mr-3">✔</span>Mais de 5.000 alunos</p>
                            <p class="flex items-center"><span class="text-[#00ff88] mr-3">✔</span>Resultados comprovados</p>
                            <p class="flex items-center"><span class="text-[#00ff88] mr-3">✔</span>Alta taxa de satisfação</p>
                        </div>
                        <div class="mt-8 bg-zinc-900 border border-zinc-800 rounded-xl p-8">
                            <p class="text-zinc-400 text-lg">De <span class="line-through">R$120</span> por apenas:</p>
                            <p class="text-5xl font-black my-2 text-white">12x de <span class="text-[#00ff88]">R$10</span></p>
                            <p class="text-zinc-400">ou R$120 à vista</p>
                            <a href="https://pay.cakto.com.br/dyukn2b_438435" class="cta-button button-glow-animated block w-full mt-6 bg-[#00ff88] text-black font-bold text-lg text-center py-4 rounded-lg uppercase tracking-wider">Comprar Agora</a>
                            <p class="text-xs text-zinc-500 mt-4">✔ Acesso vitalício + 12 aulas completas</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-black border-t border-zinc-900 text-center py-8 px-6">
        <p class="text-zinc-500 text-sm">© 2025 Josmil Digital. Todos os direitos reservados.</p>
        <div class="mt-2">
            <a href="#" class="text-zinc-600 hover:text-white text-sm mx-2">Termos de Uso</a>
            <span class="text-zinc-600">•</span>
            <a href="#" class="text-zinc-600 hover:text-white text-sm mx-2">Política de Privacidade</a>
        </div>
    </footer>

    <script>
        // Script de Animação de Scroll
        document.addEventListener("DOMContentLoaded", function() {
            const revealElements = document.querySelectorAll('.reveal');
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');
                    }
                });
            }, {
                threshold: 0.1 
            });
            revealElements.forEach(element => {
                observer.observe(element);
            });
        });
    </script>
</body>
</html>
![Chat-GPT-Image-13-de-jun-de-2025-21-21-25](https://github.com/user-attachments/assets/ad912b61-e735-4592-bbee-edfe5745b6d9)
