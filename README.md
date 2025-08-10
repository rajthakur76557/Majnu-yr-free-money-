<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>मेरा हिंदी ब्लॉग</title>
    <style>
        body {
            font-family: "Noto Sans", sans-serif;
            margin: 0;
            padding: 0;
            background: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #0077cc;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            max-width: 900px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        article {
            background: white;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
            border-radius: 6px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        article h2 {
            margin-top: 0;
            color: #0077cc;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background: #eee;
            color: #555;
            margin-top: 3rem;
        }
        .ad-space {
            background: #ffd;
            border: 1px dashed #ccaa00;
            padding: 0.5rem;
            margin: 1rem 0;
            text-align: center;
            color: #666;
        }
        @media(max-width: 600px) {
            body {
                padding: 0 1rem;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>मेरा हिंदी ब्लॉग</h1>
    <nav>
        <a href="#home">होम</a>
        <a href="#blog">ब्लॉग</a>
        <a href="#contact">संपर्क करें</a>
    </nav>
</header>

<main>
    <section id="home">
        <h2>स्वागत है!</h2>
        <p>यह मेरा हिंदी ब्लॉग है जहाँ मैं उपयोगी जानकारी और टिप्स शेयर करता हूँ। नए लेख नीचे देखिए।</p>
    </section>

    <section id="blog">
        <h2>नवीनतम ब्लॉग पोस्ट</h2>

        <article>
            <h3>ब्लॉगिंग से पैसे कैसे कमाएँ?</h3>
            <p>ब्लॉगिंग से पैसे कमाने के कई तरीके हैं। जैसे कि Google AdSense, affiliate marketing, sponsored posts आदि। ब्लॉग शुरू करने के लिए एक अच्छा विषय चुनना जरूरी है।</p>
            <div class="ad-space">यहाँ Google AdSense विज्ञापन दिख सकते हैं</div>
        </article>

        <article>
            <h3>SEO के आसान टिप्स</h3>
            <p>अपने ब्लॉग की विज़िबिलिटी बढ़ाने के लिए SEO महत्वपूर्ण है। सही keywords, अच्छी कंटेंट, तेज़ वेबसाइट स्पीड, और मोबाइल फ्रेंडली डिज़ाइन जरूरी हैं।</p>
            <div class="ad-space">यहाँ Google AdSense विज्ञापन दिख सकते हैं</div>
        </article>
    </section>

    <section id="contact">
        <h2>संपर्क करें</h2>
        <p>अगर आपके कोई सवाल हैं या सुझाव देना चाहते हैं तो नीचे अपना संदेश भेजें:</p>
        <form>
            <label>नाम:<br><input type="text" name="name" required></label><br><br>
            <label>ईमेल:<br><input type="email" name="email" required></label><br><br>
            <label>संदेश:<br><textarea name="message" rows="4" required></textarea></label><br><br>
            <button type="submit">भेजें</button>
        </form>
    </section>
</main>

<footer>
    &copy; 2025 मेरा हिंदी ब्लॉग. सभी अधिकार सुरक्षित।
</footer>

</body>
</html>
