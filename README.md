# Muthukumar
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Senior System Administrator Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body class="bg-gray-100 text-gray-900">
    <header class="bg-blue-600 text-white p-4">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">John Doe</h1>
            <nav>
                <a href="#about" class="mx-2">About</a>
                <a href="#experience" class="mx-2">Experience</a>
                <a href="#skills" class="mx-2">Skills</a>
                <a href="#contact" class="mx-2">Contact</a>
            </nav>
        </div>
    </header>

    <main class="container mx-auto mt-8">
        <section id="about" class="my-8">
            <h2 class="text-3xl font-bold">About Me</h2>
            <p class="mt-4">I am a Senior System Administrator with 9 years of experience in managing and maintaining IT infrastructure. I specialize in ensuring system stability, optimizing performance, and implementing security measures.</p>
        </section>

        <section id="experience" class="my-8">
            <h2 class="text-3xl font-bold">Experience</h2>
            <ul class="mt-4">
                <li class="mb-4">
                    <h3 class="text-2xl font-semibold">Senior System Administrator at ABC Corp</h3>
                    <p class="text-gray-700">2017 - Present</p>
                    <p>Managed a team of system administrators, implemented automated system monitoring, and ensured 99.9% system uptime.</p>
                </li>
                <li class="mb-4">
                    <h3 class="text-2xl font-semibold">System Administrator at XYZ Ltd</h3>
                    <p class="text-gray-700">2013 - 2017</p>
                    <p>Configured and maintained servers, provided technical support, and developed disaster recovery plans.</p>
                </li>
            </ul>
        </section>

        <section id="skills" class="my-8">
            <h2 class="text-3xl font-bold">Skills</h2>
            <div class="flex flex-wrap mt-4">
                <span class="bg-blue-200 text-blue-800 px-4 py-2 m-2 rounded">Linux</span>
                <span class="bg-blue-200 text-blue-800 px-4 py-2 m-2 rounded">Windows Server</span>
                <span class="bg-blue-200 text-blue-800 px-4 py-2 m-2 rounded">VMware</span>
                <span class="bg-blue-200 text-blue-800 px-4 py-2 m-2 rounded">Docker</span>
                <span class="bg-blue-200 text-blue-800 px-4 py-2 m-2 rounded">AWS</span>
                <span class="bg-blue-200 text-blue-800 px-4 py-2 m-2 rounded">Python</span>
            </div>
        </section>

        <section id="contact" class="my-8">
            <h2 class="text-3xl font-bold">Contact</h2>
            <form id="contact-form" class="mt-4">
                <div class="mb-4">
                    <label for="name" class="block text-gray-700">Name</label>
                    <input type="text" id="name" class="w-full px-4 py-2 border rounded" required>
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-gray-700">Email</label>
                    <input type="email" id="email" class="w-full px-4 py-2 border rounded" required>
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-gray-700">Message</label>
                    <textarea id="message" class="w-full px-4 py-2 border rounded" required></textarea>
                </div>
                <button type="submit" class="bg-blue-600 text-white px-4 py-2 rounded">Send</button>
            </form>
        </section>
    </main>

    <footer class="bg-blue-600 text-white p-4 text-center">
        &copy; 2024 John Doe. All rights reserved.
    </footer>

    <script src="scripts.js"></script>
</body>
</html>

