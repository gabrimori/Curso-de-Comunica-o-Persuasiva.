# Curso-de-Comunica-o-Persuasiva.<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PersuadeMaster - Learn Persuasive Communication</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        .lesson-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .progress-ring__circle {
            transition: stroke-dashoffset 0.5s;
            transform: rotate(-90deg);
            transform-origin: 50% 50%;
        }
        .typing-demo {
            width: 22ch;
            animation: typing 2s steps(22), blink .5s step-end infinite alternate;
            white-space: nowrap;
            overflow: hidden;
            border-right: 3px solid;
            font-family: monospace;
        }
        @keyframes typing {
            from { width: 0 }
        }
        @keyframes blink {
            50% { border-color: transparent }
        }
    </style>
</head>
<body class="bg-gray-50 font-sans">
    <!-- Navigation -->
    <nav class="gradient-bg text-white shadow-lg">
        <div class="container mx-auto px-6 py-3">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-4">
                    <i class="fas fa-comments fa-2x"></i>
                    <span class="text-xl font-bold">PersuadeMaster</span>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#" class="hover:text-gray-200">Home</a>
                    <a href="#courses" class="hover:text-gray-200">Courses</a>
                    <a href="#about" class="hover:text-gray-200">About</a>
                    <a href="#contact" class="hover:text-gray-200">Contact</a>
                </div>
                <div class="md:hidden">
                    <button class="mobile-menu-button p-2 focus:outline-none">
                        <i class="fas fa-bars fa-lg"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="gradient-bg text-white py-20">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h1 class="text-4xl md:text-6xl font-bold mb-6">Master the Art of <span class="typing-demo">Persuasion</span></h1>
                    <p class="text-xl mb-8">Unlock powerful communication skills to influence, inspire, and achieve your goals in any situation.</p>
                    <button class="bg-white text-purple-800 font-bold py-3 px-8 rounded-full hover:bg-gray-100 transition duration-300">
                        Start Learning Now
                    </button>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <img src="https://images.unsplash.com/photo-1580894732444-8ecded7900cd?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Persuasive Communication" class="rounded-lg shadow-2xl max-w-md w-full">
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-16 bg-white" id="courses">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Our Learning Approach</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-8 rounded-xl shadow-md hover:shadow-xl transition duration-300">
                    <div class="text-purple-600 mb-4">
                        <i class="fas fa-brain fa-3x"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Psychological Principles</h3>
                    <p class="text-gray-600">Learn the science behind persuasion including cognitive biases and social proof techniques.</p>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl shadow-md hover:shadow-xl transition duration-300">
                    <div class="text-purple-600 mb-4">
                        <i class="fas fa-hands-helping fa-3x"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Real-world Scenarios</h3>
                    <p class="text-gray-600">Practice with interactive simulations of business negotiations, sales pitches, and social situations.</p>
                </div>
                <div class="bg-gray-50 p-8 rounded-xl shadow-md hover:shadow-xl transition duration-300">
                    <div class="text-purple-600 mb-4">
                        <i class="fas fa-chart-line fa-3x"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Progress Tracking</h3>
                    <p class="text-gray-600">Monitor your improvement with detailed analytics and personalized feedback.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Courses Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Featured Courses</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Course 1 -->
                <div class="lesson-card bg-white rounded-xl overflow-hidden shadow-md transition duration-300">
                    <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Persuasion Fundamentals" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-2">
                            <span class="text-sm text-purple-600 font-semibold">BEGINNER</span>
                            <span class="text-sm text-gray-500">8 Lessons</span>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Persuasion Fundamentals</h3>
                        <p class="text-gray-600 mb-4">Master the core principles of persuasive communication and rhetoric.</p>
                        <div class="flex justify-between items-center">
                            <div class="flex items-center">
                                <i class="fas fa-star text-yellow-400 mr-1"></i>
                                <span class="text-gray-700">4.9</span>
                            </div>
                            <button class="text-purple-600 font-semibold hover:text-purple-800">Start Course</button>
                        </div>
                    </div>
                </div>
                
                <!-- Course 2 -->
                <div class="lesson-card bg-white rounded-xl overflow-hidden shadow-md transition duration-300">
                    <img src="https://images.unsplash.com/photo-1521791055366-0d553872125f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1469&q=80" alt="Business Negotiation" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-2">
                            <span class="text-sm text-purple-600 font-semibold">INTERMEDIATE</span>
                            <span class="text-sm text-gray-500">12 Lessons</span>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Business Negotiation</h3>
                        <p class="text-gray-600 mb-4">Win-win strategies and psychological tactics for business negotiations.</p>
                        <div class="flex justify-between items-center">
                            <div class="flex items-center">
                                <i class="fas fa-star text-yellow-400 mr-1"></i>
                                <span class="text-gray-700">4.8</span>
                            </div>
                            <button class="text-purple-600 font-semibold hover:text-purple-800">Start Course</button>
                        </div>
                    </div>
                </div>
                
                <!-- Course 3 -->
                <div class="lesson-card bg-white rounded-xl overflow-hidden shadow-md transition duration-300">
                    <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1471&q=80" alt="Social Influence" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-2">
                            <span class="text-sm text-purple-600 font-semibold">ADVANCED</span>
                            <span class="text-sm text-gray-500">10 Lessons</span>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Social Influence Mastery</h3>
                        <p class="text-gray-600 mb-4">Advanced techniques for leading groups and shaping opinions.</p>
                        <div class="flex justify-between items-center">
                            <div class="flex items-center">
                                <i class="fas fa-star text-yellow-400 mr-1"></i>
                                <span class="text-gray-700">4.7</span>
                            </div>
                            <button class="text-purple-600 font-semibold hover:text-purple-800">Start Course</button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <button class="bg-purple-600 text-white font-bold py-3 px-8 rounded-full hover:bg-purple-700 transition duration-300">
                    View All Courses
                </button>
            </div>
        </div>
    </section>

    <!-- Interactive Demo Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Try Our Interactive Demo</h2>
            
            <div class="max-w-4xl mx-auto bg-gray-50 rounded-xl shadow-md overflow-hidden">
                <div class="md:flex">
                    <div class="p-8 md:w-1/2">
                        <h3 class="text-xl font-bold mb-4">Persuasion Technique: Reciprocity</h3>
                        <p class="text-gray-600 mb-6">Reciprocity is the social norm of responding to a positive action with another positive action. Try this simulation to see how it works:</p>
                        
                        <div id="demo-container" class="space-y-4">
                            <div id="step1" class="demo-step">
                                <p class="font-semibold mb-2">Scenario: You're a salesperson trying to sell software to a client.</p>
                                <button onclick="nextStep(1)" class="bg-purple-600 text-white py-2 px-4 rounded hover:bg-purple-700 transition">
                                    Start Simulation
                                </button>
                            </div>
                            
                            <div id="step2" class="demo-step hidden">
                                <p class="font-semibold mb-2">Client: "I'm not sure we need this software right now."</p>
                                <p class="mb-4">Choose your response:</p>
                                <div class="space-y-2">
                                    <button onclick="selectOption(2, 'A')" class="w-full text-left bg-gray-100 hover:bg-gray-200 p-3 rounded transition">
                                        A. "That's fine, maybe another time."
                                    </button>
                                    <button onclick="selectOption(2, 'B')" class="w-full text-left bg-gray-100 hover:bg-gray-200 p-3 rounded transition">
                                        B. "I understand. Here's a free trial with premium features for 30 days."
                                    </button>
                                    <button onclick="selectOption(2, 'C')" class="w-full text-left bg-gray-100 hover:bg-gray-200 p-3 rounded transition">
                                        C. "You're making a big mistake by not buying now."
                                    </button>
                                </div>
                            </div>
                            
                            <div id="step3" class="demo-step hidden">
                                <p class="font-semibold mb-2">Client: "Well, with the free trial, I can see the value. Let's discuss pricing."</p>
                                <p class="mb-4 text-green-600">Success! By offering something first (the free trial), you triggered the reciprocity principle, making the client more likely to agree to your proposal.</p>
                                <button onclick="resetDemo()" class="bg-purple-600 text-white py-2 px-4 rounded hover:bg-purple-700 transition">
                                    Try Again
                                </button>
                            </div>
                            
                            <div id="feedback" class="hidden mt-4 p-4 bg-purple-100 rounded text-purple-800"></div>
                        </div>
                    </div>
                    
                    <div class="md:w-1/2 bg-purple-600 text-white p-8 flex items-center">
                        <div>
                            <h3 class="text-xl font-bold mb-4">Why This Works</h3>
                            <p class="mb-4">The reciprocity principle states that people feel obliged to return favors. By giving first (the free trial), you create a subconscious debt that makes the client more open to your request.</p>
                            <p>Key takeaways:</p>
                            <ul class="list-disc pl-5 mt-2 space-y-1">
                                <li>Give value before asking for something</li>
                                <li>Make your gift personalized and unexpected</li>
                                <li>The favor doesn't need to be large, just meaningful</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-16 bg-gray-50" id="about">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">What Our Students Say</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="flex-shrink-0">
                            <img class="h-12 w-12 rounded-full" src="https://randomuser.me/api/portraits/women/32.jpg" alt="Sarah Johnson">
                        </div>
                        <div class="ml-4">
                            <h4 class="text-lg font-semibold">Sarah Johnson</h4>
                            <p class="text-gray-600">Marketing Director</p>
                        </div>
                    </div>
                    <p class="text-gray-700">"The negotiation course transformed how I approach client meetings. I've closed 30% more deals since implementing these techniques."</p>
                    <div class="mt-4 flex">
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                    </div>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="flex-shrink-0">
                            <img class="h-12 w-12 rounded-full" src="https://randomuser.me/api/portraits/men/54.jpg" alt="Michael Chen">
                        </div>
                        <div class="ml-4">
                            <h4 class="text-lg font-semibold">Michael Chen</h4>
                            <p class="text-gray-600">Startup Founder</p>
                        </div>
                    </div>
                    <p class="text-gray-700">"The psychological principles module gave me insights that helped secure our Series A funding. The interactive exercises made complex concepts easy to apply."</p>
                    <div class="mt-4 flex">
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                    </div>
                </div>
                
                <div class="bg-white p-8 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="flex-shrink-0">
                            <img class="h-12 w-12 rounded-full" src="https://randomuser.me/api/portraits/women/68.jpg" alt="Emma Rodriguez">
                        </div>
                        <div class="ml-4">
                            <h4 class="text-lg font-semibold">Emma Rodriguez</h4>
                            <p class="text-gray-600">Nonprofit Director</p>
                        </div>
                    </div>
                    <p class="text-gray-700">"I used to struggle with fundraising. After completing the social influence course, we've doubled our donor contributions in six months."</p>
                    <div class="mt-4 flex">
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="gradient-bg text-white py-16">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-6">Ready to Transform Your Communication Skills?</h2>
            <p class="text-xl mb-8 max-w-2xl mx-auto">Join thousands of professionals who've mastered the art of persuasion with our proven methods.</p>
            <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-4">
                <button class="bg-white text-purple-800 font-bold py-3 px-8 rounded-full hover:bg-gray-100 transition duration-300">
                    Start Free Trial
                </button>
                <button class="border-2 border-white text-white font-bold py-3 px-8 rounded-full hover:bg-white hover:text-purple-800 transition duration-300">
                    Talk to an Expert
                </button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12" id="contact">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">PersuadeMaster</h3>
                    <p class="text-gray-400">Master the art of persuasive communication to achieve your personal and professional goals.</p>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Courses</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Persuasion Fundamentals</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Business Negotiation</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Social Influence</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Public Speaking</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Company</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">About Us</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Careers</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Blog</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Contact</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Connect</h4>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-white transition"><i class="fab fa-facebook-f fa-lg"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white transition"><i class="fab fa-twitter fa-lg"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white transition"><i class="fab fa-linkedin-in fa-lg"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white transition"><i class="fab fa-instagram fa-lg"></i></a>
                    </div>
                    <div class="mt-4">
                        <p class="text-gray-400">Subscribe to our newsletter</p>
                        <div class="flex mt-2">
                            <input type="email" placeholder="Your email" class="px-4 py-2 rounded-l text-gray-800 w-full">
                            <button class="bg-purple-600 px-4 rounded-r hover:bg-purple-700 transition">
                                <i class="fas fa-paper-plane"></i>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-400">
                <p>&copy; 2023 PersuadeMaster. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Mobile Menu (hidden by default) -->
    <div class="mobile-menu hidden md:hidden fixed inset-0 bg-gray-900 bg-opacity-90 z-50">
        <div class="flex items-center justify-center h-full">
            <div class="text-center">
                <button class="mobile-menu-close absolute top-4 right-4 text-white text-2xl">
                    <i class="fas fa-times"></i>
                </button>
                <a href="#" class="block text-white text-2xl py-4 hover:text-purple-300">Home</a>
                <a href="#courses" class="block text-white text-2xl py-4 hover:text-purple-300">Courses</a>
                <a href="#about" class="block text-white text-2xl py-4 hover:text-purple-300">About</a>
                <a href="#contact" class="block text-white text-2xl py-4 hover:text-purple-300">Contact</a>
                <button class="bg-purple-600 text-white font-bold py-3 px-8 rounded-full mt-6 hover:bg-purple-700 transition">
                    Sign In
                </button>
            </div>
        </div>
    </div>

    <script>
        // Mobile menu toggle
        const mobileMenuButton = document.querySelector('.mobile-menu-button');
        const mobileMenu = document.querySelector('.mobile-menu');
        const mobileMenuClose = document.querySelector('.mobile-menu-close');
        
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.remove('hidden');
        });
        
        mobileMenuClose.addEventListener('click', () => {
            mobileMenu.classList.add('hidden');
        });

        // Interactive demo functionality
        function nextStep(currentStep) {
            document.getElementById(`step${currentStep}`).classList.add('hidden');
            document.getElementById(`step${currentStep + 1}`).classList.remove('hidden');
        }
        
        function selectOption(step, option) {
            const feedback = document.getElementById('feedback');
            
            if (option === 'B') {
                nextStep(step);
            } else {
                feedback.classList.remove('hidden');
                if (option === 'A') {
                    feedback.textContent = "This is a missed opportunity. You didn't create any obligation for the client to respond to.";
                } else {
                    feedback.textContent = "Too aggressive! This approach will likely make the client defensive rather than cooperative.";
                }
            }
        }
        
        function resetDemo() {
            document.querySelectorAll('.demo-step').forEach(step => {
                step.classList.add('hidden');
            });
            document.getElementById('feedback').classList.add('hidden');
            document.getElementById('step1').classList.remove('hidden');
        }

        // Animated progress rings
        document.addEventListener('DOMContentLoaded', function() {
            const progressRings = document.querySelectorAll('.progress-ring');
            
            progressRings.forEach(ring => {
                const circle = ring.querySelector('.progress-ring__circle');
                const radius = circle.r.baseVal.value;
                const circumference = 2 * Math.PI * radius;
                const percent = parseInt(ring.dataset.percent);
                
                circle.style.strokeDasharray = `${circumference} ${circumference}`;
                circle.style.strokeDashoffset = circumference - (percent / 100) * circumference;
            });
        });
    </script>
</body>
</html>https://vscode.dev/?vscode-lang=pt-br
