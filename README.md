<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Alternance - Vital Plajoe | Assistant Comptable</title>
    <meta name="description" content="Portfolio de Vital Plajoe, étudiant en BTS Comptabilité et Gestion à la recherche d'une alternance assistant comptable pour septembre 2025.">
    <meta property="og:title" content="Portfolio Alternance - Vital Plajoe, Assistant Comptable">
    <meta property="og:description" content="Étudiant rigoureux et organisé en Comptabilité et Gestion, à la recherche d'une alternance pour septembre 2025.">
    <meta property="og:image" content="[VOTRE_LIEN_VERS_LA_PHOTO_PROFESSIONNELLE]">
    <meta property="og:url" content="[VOTRE_URL_DU_SITE]">

    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .smooth-scroll {
            scroll-behavior: smooth;
        }
        .animate-fade-in {
            animation: fadeIn 1s ease-in-out;
        }
        .hover-scale {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .hover-scale:hover {
            transform: scale(1.03); /* Légèrement réduit pour un effet plus subtil */
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }
        /* Ajustement pour mobile */
        @media (max-width: 768px) {
            .navbar-menu {
                display: none;
            }
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-900 smooth-scroll">

    <nav class="bg-white shadow-lg fixed w-full z-20">
        <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
            <h1 class="text-2xl font-extrabold text-teal-600 tracking-wider">Vital Plajoe</h1>
            <ul class="hidden md:flex space-x-6">
                <li><a href="#accueil" class="hover:text-teal-600 font-medium transition">Accueil</a></li>
                <li><a href="#a-propos" class="hover:text-teal-600 font-medium transition">À propos</a></li>
                <li><a href="#competences" class="hover:text-teal-600 font-medium transition">Compétences</a></li>
                <li><a href="#experiences" class="hover:text-teal-600 font-medium transition">Expériences</a></li>
                <li><a href="#formation" class="hover:text-teal-600 font-medium transition">Formation</a></li>
                <li><a href="#contact" class="hover:text-teal-600 font-medium transition">Contact</a></li>
            </ul>
        </div>
    </nav>

    <section id="accueil" class="min-h-screen flex items-center pt-20 bg-gradient-to-br from-teal-600 to-cyan-700 text-white">
        <div class="max-w-7xl mx-auto px-4 text-center animate-fade-in">
            <img src="[LIEN_DE_VOTRE_PHOTO_PROFESSIONNELLE]" alt="Vital Plajoe Photo Professionnelle" class="w-40 h-40 md:w-52 md:h-52 rounded-full mx-auto mb-6 object-cover shadow-2xl border-4 border-white">
            
            <h2 class="text-4xl md:text-6xl font-extrabold mb-4 leading-tight">Vital PLAJOE</h2>
            <p class="text-xl md:text-2xl font-light mb-8 max-w-4xl mx-auto">
                Étudiant en Comptabilité et Gestion à la recherche d'une alternance en tant qu’<span class="font-semibold">Assistant Comptable</span> pour septembre 2025.
            </p>
            <a href="#contact" class="bg-white text-teal-700 px-8 py-4 rounded-full text-lg font-bold shadow-xl hover:bg-gray-100 transition duration-300 hover-scale">
                Contacter pour l'Alternance
            </a>
        </div>
    </section>

    <section id="a-propos" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 animate-fade-in">
            <h2 class="text-4xl font-bold text-center mb-12 text-teal-600">À propos de moi</h2>
            <div class="flex flex-col items-center">
                <p class="text-lg text-gray-700 max-w-4xl leading-relaxed">
                    Je suis **Vital Plajoe**, étudiant en **BTS Comptabilité et Gestion** à ESG-Finance Paris. Âgé de 22 ans, je suis à la recherche d’une alternance en tant qu’assistant comptable pour septembre 2025. Rigoureux, organisé et doté d’un esprit **analytique**, je souhaite mettre mes compétences solides en comptabilité, gestion et analyse financière au service de projets concrets. Mon parcours montre une forte capacité d'adaptation et une volonté d'apprentissage continu dans le domaine de la gestion d'entreprise.
                </p>
            </div>
        </div>
    </section>

    <section id="competences" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 animate-fade-in">
            <h2 class="text-4xl font-bold text-center mb-12 text-teal-600">Mes Compétences Techniques et Humaines</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-xl shadow-lg hover-scale border-t-4 border-teal-600">
                    <h3 class="text-2xl font-semibold mb-3 text-teal-700">Comptabilité & Finance</h3>
                    <p class="text-gray-700">Saisie et comptabilisation de factures, **gestion de paie**, lettrage, pointage, **rapprochement bancaire**, comptabilisation de la TVA, Opérations Diverses (OD).</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-lg hover-scale border-t-4 border-teal-600">
                    <h3 class="text-2xl font-semibold mb-3 text-teal-700">Outils & Logiciels</h3>
                    <p class="text-gray-700">Maîtrise de **Microsoft Office (Excel avancé)**, Word, PowerPoint. Expérience des **Progiciels de Gestion Intégrée (PGI)**, notamment **Cegid**.</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-lg hover-scale border-t-4 border-teal-600">
                    <h3 class="text-2xl font-semibold mb-3 text-teal-700">Qualités Personnelles (Soft Skills)</h3>
                    <p class="text-gray-700">**Rigueur** et **Organisation**, forte capacité de **collaboration** et cohésion d’équipe. Gestion efficace du temps et des priorités, **adaptabilité** rapide.</p>
                </div>
            </div>
            <div class="mt-12 text-center">
                <h3 class="text-2xl font-semibold mb-3 text-teal-700">Langues</h3>
                <p class="text-lg text-gray-700">**Anglais :** Niveau B1 (Intermédiaire)</p>
            </div>
        </div>
    </section>

    <section id="experiences" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 animate-fade-in">
            <h2 class="text-4xl font-bold text-center mb-12 text-teal-600">Parcours Professionnel</h2>
            <div class="space-y-10">
                <div class="bg-gray-50 p-8 rounded-xl shadow-lg hover-scale">
                    <h3 class="text-2xl font-bold text-teal-700">Assistant comptable - S.P.L EXPERTISE, Évry-Courcouronnes</h3>
                    <p class="text-gray-600 italic mt-1 mb-3">Juin 2025 - Juillet 2025 (Stage)</p>
                    <ul class="list-disc list-inside space-y-1 text-gray-700 ml-4">
                        <li>Saisie et comptabilisation de factures **clients et fournisseurs**.</li>
                        <li>Saisie et comptabilisation de banque, gestion des **rapprochements bancaires**.</li>
                        <li>**Lettrage** des comptes et gestion de la **TVA, OD**.</li>
                    </ul>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl shadow-lg hover-scale">
                    <h3 class="text-2xl font-bold text-teal-700">Stagiaire comptable - Cabinet ACEF, Lomé, Togo</h3>
                    <p class="text-gray-600 italic mt-1 mb-3">Juin 2023 - Juin 2024 (Stage long)</p>
                    <ul class="list-disc list-inside space-y-1 text-gray-700 ml-4">
                        <li>Assistance dans la **gestion de paie** et le traitement des salaires.</li>
                        <li>Création et gestion des comptes **fournisseurs et clients**.</li>
                        <li>Gestion proactive des **relances clients** et traitement des litiges.</li>
                    </ul>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl shadow-lg hover-scale">
                    <h3 class="text-2xl font-bold text-teal-700">Caissier - Oriental Fast-Food, Lomé, Togo</h3>
                    <p class="text-gray-600 italic mt-1 mb-3">Janvier 2022 - Mars 2023</p>
                    <ul class="list-disc list-inside space-y-1 text-gray-700 ml-4">
                        <li>Gestion quotidienne des transactions en espèces et par carte de crédit.</li>
                        <li>Accueil client et assistance pour garantir un service de qualité.</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section id="formation" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 animate-fade-in">
            <h2 class="text-4xl font-bold text-center mb-12 text-teal-600">Formation Académique</h2>
            <div class="space-y-10 max-w-4xl mx-auto">
                <div class="bg-white p-8 rounded-xl shadow-lg hover-scale border-l-4 border-teal-600">
                    <h3 class="text-2xl font-bold text-teal-700">BTS Comptabilité et Gestion</h3>
                    <p class="text-gray-700 font-medium">Depuis septembre 2024</p>
                    <p class="text-gray-600">**ESG-Finance**, Paris</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-lg hover-scale border-l-4 border-teal-600">
                    <h3 class="text-2xl font-bold text-teal-700">Baccalauréat Techniques Quantitatives d’Économie et de Gestion</h3>
                    <p class="text-gray-700 font-medium">Novembre 2022 - Juin 2023</p>
                    <p class="text-gray-600">Institut Technique d’Enseignement Commercial KOUVAHEY, Lomé, Togo</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="interets" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 animate-fade-in">
            <h2 class="text-4xl font-bold text-center mb-12 text-teal-600">Centres d’Intérêt</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-8 rounded-xl shadow-lg text-center hover-scale">
                    <h3 class="text-2xl font-semibold mb-3 text-teal-700">Sport - Football</h3>
                    <p class="text-gray-700">Le football favorise l'esprit d'équipe et la discipline, des qualités essentielles dans le monde professionnel.</p>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl shadow-lg text-center hover-scale">
                    <h3 class="text-2xl font-semibold mb-3 text-teal-700">Voyages</h3>
                    <p class="text-gray-700">Découverte de nouvelles cultures et destinations, renforçant l'ouverture d'esprit et l'adaptabilité.</p>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl shadow-lg text-center hover-scale">
                    <h3 class="text-2xl font-semibold mb-3 text-teal-700">Bénévolat</h3>
                    <p class="text-gray-700">Engagement dans des causes sociales, démontrant mon sens des responsabilités et de l'initiative.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-20 bg-gray-900 text-white">
        <div class="max-w-7xl mx-auto px-4 animate-fade-in">
            <h2 class="text-4xl font-bold text-center mb-12 text-teal-400">Prêt à échanger ? Contactez-moi !</h2>
            <div class="max-w-lg mx-auto bg-gray-800 p-10 rounded-xl shadow-2xl">
                <div class="text-center mb-8 space-y-2">
                    <p class="text-xl">
                        <strong class="text-teal-400">Email :</strong> 
                        <a href="mailto:plajoevital@gmail.com" class="hover:text-teal-400 transition underline">plajoevital@gmail.com</a>
                    </p>
                    <p class="text-xl">
                        <strong class="text-teal-400">Téléphone :</strong> 
                        <a href="tel:+33745042320" class="hover:text-teal-400 transition underline">+33 7 45 04 23 20</a>
                    </p>
                    <p class="text-xl">
                        <strong class="text-teal-400">LinkedIn :</strong> 
                        <a href="https://www.linkedin.com/in/vital-plajoe-40b0b4350" class="hover:text-teal-400 transition underline">Mon Profil LinkedIn</a>
                    </p>
                    <p class="text-md mt-6 text-gray-400">
                        20 av. Léon Blum, Épinay-sur-Seine 93800
                    </p>
                </div>
                
                <form action="[VOTRE_ENDPOINT_FORMSPREE_ICI]" method="POST" class="space-y-4">
                    <input type="text" name="name" placeholder="Votre nom" required class="w-full p-4 border border-gray-600 rounded-lg bg-gray-700 text-white focus:outline-none focus:ring-2 focus:ring-teal-400">
                    <input type="email" name="_replyto" placeholder="Votre email" required class="w-full p-4 border border-gray-600 rounded-lg bg-gray-700 text-white focus:outline-none focus:ring-2 focus:ring-teal-400">
                    <textarea name="message" placeholder="Votre message" rows="6" required class="w-full p-4 border border-gray-600 rounded-lg bg-gray-700 text-white focus:outline-none focus:ring-2 focus:ring-teal-400"></textarea>
                    <button type="submit" class="w-full bg-teal-600 text-white p-4 rounded-lg font-bold text-lg hover:bg-teal-700 transition hover-scale">
                        Envoyer le message
                    </button>
                </form>
            </div>
        </div>
    </section>

    <footer class="bg-gray-900 text-gray-400 py-6 border-t border-gray-700">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <p>© 2025 Vital Plajoe. Tous droits réservés.</p>
        </div>
    </footer>

</body>
</html>
