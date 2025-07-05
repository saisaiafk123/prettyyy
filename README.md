<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Story of Jesus Christ</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
        
        .fade-in {
            animation: fadeIn 1s ease-out forwards;
        }
        
        .float {
            animation: float 3s ease-in-out infinite;
        }
        
        .parallax {
            background-attachment: fixed;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }
    </style>
</head>
<body class="font-poppins bg-gray-50">
    <!-- Header with Navigation -->
    <header class="sticky top-0 z-50 bg-white shadow-md">
        <nav class="container mx-auto px-6 py-3">
            <div class="flex justify-between items-center">
                <div class="text-2xl font-playfair font-bold text-indigo-800">JesusChrist.com</div>
                <div class="hidden md:flex space-x-8">
                    <a href="#about" class="hover:text-indigo-600 transition">About Jesus</a>
                    <a href="#birth" class="hover:text-indigo-600 transition">Birth</a>
                    <a href="#ministry" class="hover:text-indigo-600 transition">Ministry</a>
                    <a href="#miracles" class="hover:text-indigo-600 transition">Miracles</a>
                    <a href="#death" class="hover:text-indigo-600 transition">Death & Resurrection</a>
                </div>
                <button class="md:hidden focus:outline-none" id="menu-btn">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                </button>
            </div>
            <div class="md:hidden hidden py-4" id="mobile-menu">
                <a href="#about" class="block py-2 hover:text-indigo-600">About Jesus</a>
                <a href="#birth" class="block py-2 hover:text-indigo-600">Birth</a>
                <a href="#ministry" class="block py-2 hover:text-indigo-600">Ministry</a>
                <a href="#miracles" class="block py-2 hover:text-indigo-600">Miracles</a>
                <a href="#death" class="block py-2 hover:text-indigo-600">Death & Resurrection</a>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="h-screen flex items-center justify-center parallax relative overflow-hidden" style="background-image: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/7b74c793-df5e-40da-9748-ed4274f4378f.png');">
        <div class="text-center text-white px-4">
            <h1 class="text-4xl md:text-6xl font-playfair mb-6 fade-in">Jesus Christ</h1>
            <p class="text-xl md:text-2xl mb-8 fade-in" style="animation-delay: 0.3s">The Way, The Truth, and The Life</p>
            <a href="#about" class="bg-indigo-600 hover:bg-indigo-700 text-white px-6 py-3 rounded-full transition fade-in" style="animation-delay: 0.6s">Explore His Story</a>
        </div>
        <div class="absolute bottom-10 left-1/2 transform -translate-x-1/2 flex flex-col items-center">
            <span class="text-white mb-2">Scroll Down</span>
            <div class="w-6 h-10 border-2 border-white rounded-full flex justify-center">
                <div class="w-1 h-2 bg-white rounded-full mt-2 float"></div>
            </div>
        </div>
    </section>

    <!-- About Jesus Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-playfair text-center mb-16">Who is Jesus Christ?</h2>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <p class="text-gray-700 mb-6">Jesus Christ is the central figure of Christianity and the Son of God. According to the Bible, He is both fully God and fully man, who came to earth to save humanity from sin.</p>
                    <p class="text-gray-700 mb-6">"For God so loved the world that he gave his one and only Son, that whoever believes in him shall not perish but have eternal life." (John 3:16)</p>
                    <p class="text-gray-700">Jesus taught about love, forgiveness, and the kingdom of God, performing miracles that revealed His divine nature and authority over all creation.</p>
                </div>
                <div class="rounded-lg overflow-hidden shadow-xl transform hover:scale-105 transition duration-500">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/9d355a8c-1724-4d21-a3ee-0effc0fc70e7.png" alt="Jesus Christ standing on a hillside teaching a crowd with compassion in his eyes, wearing traditional robes, surrounded by green fields under blue skies" class="w-full h-auto">
                </div>
            </div>
        </div>
    </section>

    <!-- Nativity Story Section -->
    <section id="birth" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-playfair text-center mb-16">The Birth of Jesus</h2>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="order-2 md:order-1">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/4805cb75-56fc-4a2b-ace6-d5442d8cf3da.png" alt="Christmas nativity scene in Bethlehem with baby Jesus in a manger, Mary and Joseph looking lovingly at him, animals surrounding them, and a bright star shining above" class="w-full h-auto rounded-lg shadow-xl float" style="animation-delay: 0.3s">
                </div>
                <div class="order-1 md:order-2">
                    <h3 class="text-2xl font-playfair mb-4">The Christmas Story</h3>
                    <p class="text-gray-700 mb-6">Jesus was born in Bethlehem to the Virgin Mary, as foretold by prophets centuries before. His birth was announced by angels to shepherds who came to worship Him.</p>
                    <p class="text-gray-700 mb-6">"Today in the town of David a Savior has been born to you; he is the Messiah, the Lord. This will be a sign to you: You will find a baby wrapped in cloths and lying in a manger." (Luke 2:11-12)</p>
                    <p class="text-gray-700">Wise men from the East followed a star to bring gifts of gold, frankincense and myrrh, recognizing Jesus as the promised King.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Ministry Section -->
    <section id="ministry" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-playfair text-center mb-16">The Ministry of Jesus</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-6 rounded-lg shadow-md hover:shadow-xl transition">
                    <div class="text-indigo-600 text-4xl mb-4">30 A.D.</div>
                    <h3 class="text-xl font-playfair mb-3">Baptism</h3>
                    <p class="text-gray-700">Jesus was baptized by John the Baptist in the Jordan River, marking the beginning of His public ministry. The Holy Spirit descended on Him like a dove.</p>
                </div>
                <div class="bg-gray-50 p-6 rounded-lg shadow-md hover:shadow-xl transition">
                    <div class="text-indigo-600 text-4xl mb-4">32 A.D.</div>
                    <h3 class="text-xl font-playfair mb-3">Sermon on the Mount</h3>
                    <p class="text-gray-700">Jesus delivered His most famous sermon, teaching the Beatitudes and profound truths about God's kingdom, prayer, and righteous living.</p>
                </div>
                <div class="bg-gray-50 p-6 rounded-lg shadow-md hover:shadow-xl transition">
                    <div class="text-indigo-600 text-4xl mb-4">33 A.D.</div>
                    <h3 class="text-xl font-playfair mb-3">Last Supper</h3>
                    <p class="text-gray-700">Jesus shared the Passover meal with His disciples, instituting Communion and foretelling His betrayal by Judas Iscariot.</p>
                </div>
            </div>
            <div class="mt-12 bg-indigo-50 p-8 rounded-lg border-l-4 border-indigo-600">
                <h3 class="text-xl font-playfair mb-4">The Core Teachings of Jesus</h3>
                <p class="text-gray-700 mb-4"><span class="font-bold">Love:</span> "Love the Lord your God with all your heart...and love your neighbor as yourself." (Matthew 22:37-39)</p>
                <p class="text-gray-700 mb-4"><span class="font-bold">Forgiveness:</span> "If your brother or sister sins against you, forgive them." (Luke 17:3-4)</p>
                <p class="text-gray-700"><span class="font-bold">Salvation:</span> "I am the way and the truth and the life. No one comes to the Father except through me." (John 14:6)</p>
            </div>
        </div>
    </section>

    <!-- Miracles Section -->
    <section id="miracles" class="py-20 parallax text-white" style="background-image: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/d5d1b152-b2d2-4a42-a3bd-044754d7b899.png');">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-playfair text-center mb-16">Miracles of Jesus</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white bg-opacity-10 p-6 rounded-lg backdrop-blur-sm hover:scale-105 transition">
                    <h3 class="text-xl font-playfair mb-3">Turning Water to Wine</h3>
                    <p class="mb-4">At a wedding in Cana, Jesus transformed water into wine, His first public miracle showing divine power over creation.</p>
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/446b5a6a-aa03-4320-864c-1fe30ee9b808.png" alt="Wedding at Cana where Jesus turns water into wine, showing servants pouring from jars into cups with amazed guests watching" class="w-full rounded">
                </div>
                <div class="bg-white bg-opacity-10 p-6 rounded-lg backdrop-blur-sm hover:scale-105 transition">
                    <h3 class="text-xl font-playfair mb-3">Healing the Blind</h3>
                    <p class="mb-4">Jesus restored sight to the blind, including a man born blind, demonstrating His power to heal and bring spiritual light.</p>
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/1ae176bc-be39-4c70-af38-8090f59ae535.png" alt="Jesus gently touching a blind man's eyes as light shines on them, showing the moment of miraculous healing" class="w-full rounded">
                </div>
                <div class="bg-white bg-opacity-10 p-6 rounded-lg backdrop-blur-sm hover:scale-105 transition">
                    <h3 class="text-xl font-playfair mb-3">Raising Lazarus</h3>
                    <p class="mb-4">Jesus called Lazarus out from the tomb after four days dead, proving His authority over life and death itself.</p>
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/2b7cbf73-3aeb-404d-ac52-8ca3d43d68f0.png" alt="Jesus standing before the tomb of Lazarus as the resurrected man emerges still wrapped in burial cloths" class="w-full rounded">
                </div>
            </div>
            <div class="mt-12 bg-black bg-opacity-30 p-8 rounded-lg text-center backdrop-blur-sm">
                <h3 class="text-xl font-playfair mb-4">"The blind receive sight, the lame walk, those who have leprosy are cleansed, the deaf hear, the dead are raised, and the good news is proclaimed to the poor."</h3>
                <p class="text-lg">- Matthew 11:5</p>
            </div>
        </div>
    </section>

    <!-- Death & Resurrection Section -->
    <section id="death" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-playfair text-center mb-16">Death and Resurrection</h2>
            <div class="grid md:grid-cols-2 gap-12">
                <div class="bg-white p-8 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-playfair mb-4">The Crucifixion</h3>
                    <p class="text-gray-700 mb-6">Jesus was crucified on a cross at Calvary, willingly sacrificing Himself to bear the sins of humanity. As He died, He declared "It is finished," completing God's plan of redemption.</p>
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/e31df69a-e399-47db-8856-b3ea2770d1c0.png" alt="Jesus on the cross at Golgotha with a dark sky overhead, representing His sacrifice for humanity's sins" class="w-full rounded mb-6">
                    <p class="text-gray-700">"He was pierced for our transgressions, he was crushed for our iniquities; the punishment that brought us peace was on him, and by his wounds we are healed." (Isaiah 53:5)</p>
                </div>
                <div class="bg-white p-8 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-playfair mb-4">The Resurrection</h3>
                    <p class="text-gray-700 mb-6">On the third day, Jesus rose from the dead, conquering death and proving His victory over sin. He appeared to many witnesses before ascending to heaven.</p>
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/d8c71fde-d2e9-454f-9b95-51d653be6c48.png" alt="Empty tomb at dawn with the stone rolled away and angelic light shining from within, symbolizing Christ's victory over death" class="w-full rounded mb-6">
                    <p class="text-gray-700">"Don't be alarmed," he said. "You are looking for Jesus the Nazarene, who was crucified. He has risen! He is not here. See the place where they laid him." (Mark 16:6)</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action -->
    <section class="py-20 bg-indigo-800 text-white">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl md:text-4xl font-playfair mb-8">Would You Like to Know Jesus Personally?</h2>
            <p class="text-xl max-w-3xl mx-auto mb-10">Jesus offers forgiveness of sins and eternal life to all who believe in Him. Accepting Him means beginning a personal relationship with God.</p>
            <div class="max-w-2xl mx-auto bg-indigo-900 p-8 rounded-lg text-left">
                <h3 class="text-2xl font-playfair mb-4">How to Be Saved</h3>
                <ol class="list-decimal pl-5 space-y-4">
                    <li><span class="font-bold">Admit</span> you're a sinner in need of salvation (Romans 3:23)</li>
                    <li><span class="font-bold">Believe</span> Jesus died for your sins and rose again (Romans 10:9)</li>
                    <li><span class="font-bold">Confess</span> Jesus as Lord of your life (Romans 10:10)</li>
                    <li><span class="font-bold">Receive</span> His gift of eternal life (John 1:12)</li>
                </ol>
                <div class="mt-8 text-center">
                    <button id="prayer-btn" class="bg-white text-indigo-800 px-8 py-3 rounded-full font-bold hover:bg-gray-200 transition">Pray to Receive Christ</button>
                    <div id="prayer-text" class="mt-6 hidden bg-indigo-700 p-6 rounded-lg">
                        <p class="italic mb-4">"Dear Lord Jesus, I know I'm a sinner. I believe You died for my sins and rose again. I invite You into my life as my Lord and Savior. Forgive my sins and make me new. Thank You for saving me. Amen."</p>
                        <p>If you prayed this prayer, welcome to God's family! Find a Bible-believing church to help you grow in your new faith.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-300 py-12">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-xl font-playfair text-white mb-4">JesusChrist.com</h3>
                    <p>A resource to learn about Jesus Christ, His life, teachings, and the salvation He offers.</p>
                </div>
                <div>
                    <h3 class="text-xl text-white mb-4">Resources</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="hover:text-white transition">Bible Study Tools</a></li>
                        <li><a href="#" class="hover:text-white transition">Find a Church</a></li>
                        <li><a href="#" class="hover:text-white transition">Daily Devotions</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl text-white mb-4">Connect</h3>
                    <div class="flex space-x-4">
                        <a href="#" class="hover:text-white transition">About Us</a>
                        <a href="#" class="hover:text-white transition">Contact</a>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-8 pt-8 text-center">
                <p>© 2023 JesusChrist.com. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.getElementById('menu-btn').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Prayer button
        document.getElementById('prayer-btn').addEventListener('click', function() {
            const prayerText = document.getElementById('prayer-text');
            prayerText.classList.toggle('hidden');
        });

        // Animation on scroll
        const fadeElements = document.querySelectorAll('.fade-in');
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('fade-in');
                }
            });
        }, { threshold: 0.1 });

        fadeElements.forEach(el => {
            observer.observe(el);
        });
    </script>
</body>
</html>

