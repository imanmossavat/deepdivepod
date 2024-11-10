<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Deep Dive Podcast</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            gap: 20px;
            background-image: url('https://raw.githubusercontent.com/mossavatFontys/deepdivepod/cee119a959cabe2964621bd1f26778f29ffca0ba/assets/background.jpg');
            background-size: cover;
            background-position: center;
            height: 100vh;
        }
        .content {
            max-width: 800px;
            position: relative;
            z-index: 2;
            background-color: rgba(255, 255, 255, 0.8); /* Add a white background with opacity to ensure content visibility */
            padding: 20px;
            border-radius: 8px;
        }

        h1 {
            color: #000000;
            text-align: center;
            font-size: 3em;
            margin: 20px 0;
        }

        .subtitle {
            font-size: 1.1em;
            text-align: center;
            color: #000000;
        }

        .subsubtitle {
            font-size: 1em;
            text-align: center;
            color: #383737;  /* Lighter color for the subsub title */
        }

        .episode {
            background-color: #ffffff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            margin-bottom: 20px;
            text-align: left;
        }
        .episode h2 {
            color: #2d2d7d;
        }
        iframe {
            width: 100%;
            height: 80px;
            border-radius: 8px;
        }
        .description {
            font-size: 1em;
            margin-top: 10px;
            color: #666;
            text-align: left;
        }
        a {
            color: #2d2d7d;
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            text-decoration: underline;
        }
        .contact-btn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            font-size: 0.9em;  /* Smaller font size */
            color: #666;  /* Milder color */
            font-weight: normal;  /* Remove bold */
            text-decoration: none;  /* No underline */
            background-color: rgba(255, 255, 255, 0.7);  /* Light background */
            padding: 10px;
            border-radius: 5px;
        }
        .contact-link:hover {
            color: #2d2d7d;  /* Darker color on hover */
            background-color: rgba(255, 255, 255, 0.9);
        }
        .radio-logo {
            display: block;
            margin: 20px auto;
            width: 200px;
            height: auto;
        }

    </style>
</head>
<body>

    <div class="content">
        <h1>Deep Dive Podcast</h1>
        <p class="subtitle">Conversations on humans and algorithms</p>
        <p class="subsubtitle">In collaboration with <a href="https://www.radio4brainport.org/" target="_blank">Radio4Brainport</a></p>

        <!-- Episode 5 -->
        <div class="episode">
            <h2>Episode 5: Evolutionary Science and AI with Indre Žliobaitė</h2>
            <iframe src="https://open.spotify.com/embed/episode/2BzPwHFPBRxmUoMjAaIiYI?utm_source=generator" frameborder="0" allowfullscreen="" loading="lazy"></iframe>
            <p class="description">Professor <a href="https://www.zliobaite.com/" target="_blank">Indre Žliobaitė</a> explores parallels between evolutionary science and AI, discussing adaptive models, concept drift, and more. She explains how principles of evolution can inform AI, providing insights into dynamics like competition and adaptation.</p>
        </div>

        <!-- Episode 4 -->
        <div class="episode">
            <h2>Episode 4: Legal Challenges of AI with Colette Cuijpers</h2>
            <iframe src="https://open.spotify.com/embed/episode/1oe9HWEoT6XJvPTrrGNZk3?utm_source=generator" frameborder="0" allowfullscreen="" loading="lazy"></iframe>
            <p class="description"><a href="https://research.tilburguniversity.edu/en/persons/colette-cuijpers" target="_blank">Colette Cuijpers</a>, Associate Professor at Tilburg Law School, discusses the urgent legal and ethical challenges AI presents, from accountability to bias. This episode highlights the balance between innovation and regulation in a rapidly evolving field.</p>
        </div>

        <!-- Episode 3 -->
        <div class="episode">
            <h2>Episode 3: Causal AI and Intelligent Systems with Alexander Molak</h2>
            <iframe src="https://open.spotify.com/embed/episode/0xghHS4lo0aW22sI5VVH11?utm_source=generator" frameborder="0" allowfullscreen="" loading="lazy"></iframe>
            <p class="description"><a href="https://alxndr.io/" target="_blank">Alexander Molak</a>, machine learning researcher, explains why Generative AI lacks true causal understanding. He discusses Causal AI and its potential to improve intelligent systems by moving beyond mere correlation to deeper cause-and-effect insights.</p>
        </div>

        <!-- Episode 2 -->
        <div class="episode">
            <h2>Episode 2: Systems Engineering and AI with Gerrit Muller</h2>
            <iframe src="https://open.spotify.com/embed/episode/0C0GGgkFuwFlFmZvmqulm4?utm_source=generator" frameborder="0" allowfullscreen="" loading="lazy"></iframe>
            <p class="description">Gerrit Muller, a systems engineer and professor, discusses the integration of systems engineering and AI, exploring the importance of a balanced approach. He examines common challenges, such as data quality and interpretability, and the complementary role of Model-Based Systems Engineering.</p>
        </div>

        <!-- Episode 1 -->
        <div class="episode">
            <h2>Episode 1: Understanding Power Dynamics in AI with Mahault Albarracin</h2>
            <iframe src="https://open.spotify.com/embed/episode/3uHMBoorJXPnIZoYvdMrla?utm_source=generator" frameborder="0" allowfullscreen="" loading="lazy"></iframe>
            <p class="description">Mahault Albarracin, Director of Applied Research and PhD candidate in Computing, discusses how AI often prioritizes objectives set by powerful stakeholders, affecting societal power structures. This episode explores the intersection of technology, ethics, and power in AI design.</p>
        </div>

        <!-- Radio4Brainport Logo -->
        <img src="https://www.radio4brainport.org/assets/logo.png" alt="Radio4Brainport Logo" class="radio-logo">

    </div>

    <a href="contact.html" class="contact-btn">Contact Us</a>

</body>
</html>