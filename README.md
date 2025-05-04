<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Deutsche Literatur | Akademisches Portal</title>
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #3498db;
            --light: #ecf0f1;
            --dark: #1a252f;
            --accent: #e74c3c;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            margin: 0;
            padding: 0;
            background-color: var(--light);
        }
        
        header {
            background: var(--primary);
            color: white;
            padding: 1rem 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        nav {
            background: var(--dark);
            padding: 0.5rem;
        }
        
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            padding: 0;
            margin: 0;
        }
        
        nav li {
            margin: 0 1rem;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            transition: background 0.3s;
        }
        
        nav a:hover {
            background: var(--secondary);
        }
        
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        
        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1507842217343-583bb7270b66?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 4rem 1rem;
            text-align: center;
            margin-bottom: 2rem;
            border-radius: 8px;
        }
        
        .periods-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 1.5rem;
            margin: 2rem 0;
        }
        
        .period-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        
        .period-card:hover {
            transform: translateY(-5px);
        }
        
        .period-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        
        .period-card-content {
            padding: 1.5rem;
        }
        
        .period-card h3 {
            margin-top: 0;
            color: var(--primary);
        }
        
        .period-card .date {
            color: var(--secondary);
            font-weight: bold;
            margin-bottom: 0.5rem;
        }
        
        footer {
            background: var(--dark);
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }
        
        .timeline {
            position: relative;
            max-width: 1200px;
            margin: 2rem auto;
        }
        
        .timeline::after {
            content: '';
            position: absolute;
            width: 6px;
            background-color: var(--secondary);
            top: 0;
            bottom: 0;
            left: 50%;
            margin-left: -3px;
        }
        
        .timeline-item {
            padding: 10px 40px;
            position: relative;
            width: 50%;
            box-sizing: border-box;
        }
        
        .timeline-item::after {
            content: '';
            position: absolute;
            width: 25px;
            height: 25px;
            background-color: white;
            border: 4px solid var(--secondary);
            border-radius: 50%;
            top: 15px;
            z-index: 1;
        }
        
        .left {
            left: 0;
        }
        
        .right {
            left: 50%;
        }
        
        .left::after {
            right: -12px;
        }
        
        .right::after {
            left: -12px;
        }
        
        .timeline-content {
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        
        @media screen and (max-width: 768px) {
            .timeline::after {
                left: 31px;
            }
            
            .timeline-item {
                width: 100%;
                padding-left: 70px;
                padding-right: 25px;
            }
            
            .timeline-item::after {
                left: 18px;
            }
            
            .right {
                left: 0%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Deutsche Literatur</h1>
        <p>Ein akademisches Portal für Studierende der Portugiesisch-Deutsch-Philologie</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#home">Startseite</a></li>
            <li><a href="#perioden">Literaturperioden</a></li>
            <li><a href="#autoren">Hauptautoren</a></li>
            <li><a href="#ressourcen">Ressourcen</a></li>
            <li><a href="#ueber">Über</a></li>
        </ul>
    </nav>
    
    <div class="container">
        <section id="home">
            <div class="hero">
                <h2>Entdecken Sie den Reichtum der deutschen Literatur</h2>
                <p>Ein umfassender Leitfaden vom Mittelalter bis zur Gegenwartsliteratur</p>
                <a href="#perioden" style="display: inline-block; background: var(--accent); color: white; padding: 0.8rem 1.5rem; border-radius: 4px; text-decoration: none; margin-top: 1rem;">Starte deine Reise</a>
            </div>
            
            <h2>Warum deutsche Literatur studieren?</h2>
            <p>Die deutsche Literatur verfügt über eine reiche und vielfältige Tradition, die die westliche Kultur tiefgreifend beeinflusst hat. Von mittelalterlichen Epen bis zu modernistischen Experimenten haben deutsche Autoren universelle Themen mit philosophischer Tiefe und stilistischer Innovation erforscht.</p>
            <p>Für Studierende der Portugiesisch-Deutsch-Philologie ist das Verständnis dieser Tradition wesentlich für:</p>
            <ul>
                <li>Die Entwicklung der deutschen Sprache nachvollziehen</li>
                <li>Intertextuelle Beziehungen zwischen Literaturen analysieren</li>
                <li>Eine vergleichende Perspektive zwischen Literaturen entwickeln</li>
                <li>Kulturelles und kritisches Repertoire erweitern</li>
            </ul>
        </section>
        
        <section id="perioden">
            <h2>Literaturperioden</h2>
            <p>Entdecken Sie die wichtigsten Epochen der deutschen Literatur:</p>
            
            <div class="periods-grid">
                <!-- Mittelalter -->
                <div class="period-card">
                    <img src="https://images.unsplash.com/photo-1605000797499-95a51c5269ae?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Mittelalter">
                    <div class="period-card-content">
                        <h3>Mittelalter (750-1500)</h3>
                        <div class="date">8.-15. Jahrhundert</div>
                        <p>Die Anfänge der deutschen Literatur mit Heldenepen, Minnesang und geistlicher Dichtung.</p>
                        <a href="#mittelalter">Mehr erfahren →</a>
                    </div>
                </div>
                
                <!-- Humanismus und Reformation -->
                <div class="period-card">
                    <img src="https://images.unsplash.com/photo-1516550893923-42d28e5677af?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Humanismus">
                    <div class="period-card-content">
                        <h3>Humanismus und Reformation</h3>
                        <div class="date">15.-16. Jahrhundert</div>
                        <p>Der Mensch im Mittelpunkt - Martin Luthers Bibelübersetzung revolutioniert die deutsche Sprache.</p>
                        <a href="#humanismus">Mehr erfahren →</a>
                    </div>
                </div>
                
                <!-- Barock -->
                <div class="period-card">
                    <img src="https://images.unsplash.com/photo-1519327232521-1a2f3b4e5d5a?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Barock">
                    <div class="period-card-content">
                        <h3>Barock (1600-1720)</h3>
                        <div class="date">17. Jahrhundert</div>
                        <p>Vanitas-Motive, Gegensätze und die Vergänglichkeit des Lebens dominieren die Dichtung.</p>
                        <a href="#barock">Mehr erfahren →</a>
                    </div>
                </div>
                
                <!-- Aufklärung -->
                <div class="period-card">
                    <img src="https://images.unsplash.com/photo-1500382017468-9049fed747ef?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Aufklärung">
                    <div class="period-card-content">
                        <h3>Aufklärung (1720-1785)</h3>
                        <div class="date">18. Jahrhundert</div>
                        <p>Vernunft und Rationalität - Kants "Sapere aude!" wird zum Leitmotiv der Epoche.</p>
                        <a href="#aufklaerung">Mehr erfahren →</a>
                    </div>
                </div>
                
                <!-- Sturm und Drang -->
                <div class="period-card">
                    <img src="https://images.unsplash.com/photo-1519681393784-d120267933ba?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Sturm und Drang">
                    <div class="period-card-content">
                        <h3>Sturm und Drang (1767-1785)</h3>
                        <div class="date">Spätes 18. Jahrhundert</div>
                        <p>Jugendliche Rebellion gegen gesellschaftliche Normen - Geniekult und Gefühlsüberschwang.</p>
                        <a href="#sturm-und-drang">Mehr erfahren →</a>
                    </div>
                </div>
                
                <!-- Weimarer Klassik -->
                <div class="period-card">
                    <img src="https://images.unsplash.com/photo-1518895949257-7621c3c786d7?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Weimarer Klassik">
                    <div class="period-card-content">
                        <h3>Weimarer Klassik (1786-1805)</h3>
                        <div class="date">1786-1805</div>
                        <p>Harmonie und Humanität - Goethe und Schiller prägen das klassische Ideal.</p>
                        <a href="#weimarer-klassik">Mehr erfahren →</a>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="autoren">
            <h2>Hauptautoren der deutschen Literatur</h2>
            
            <div class="timeline">
                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>Walther von der Vogelweide</h3>
                        <p>(um 1170-1230)</p>
                        <p>Bedeutendster deutscher Lyriker des Mittelalters, bekannt für seinen Minnesang und politische Sprüche.</p>
                    </div>
                </div>
                
                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>Martin Luther</h3>
                        <p>(1483-1546)</p>
                        <p>Seine Bibelübersetzung schuf die Grundlage für die neuhochdeutsche Schriftsprache.</p>
                    </div>
                </div>
                
                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>Andreas Gryphius</h3>
                        <p>(1616-1664)</p>
                        <p>Wichtiger Barockdichter, bekannt für seine Sonette über Vergänglichkeit und Vanitas.</p>
                    </div>
                </div>
                
                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>Gotthold Ephraim Lessing</h3>
                        <p>(1729-1781)</p>
                        <p>Führender Vertreter der Aufklärung, Dramatiker ("Nathan der Weise") und Kritiker.</p>
                    </div>
                </div>
                
                <div class="timeline-item left">
                    <div class="timeline-content">
                        <h3>Johann Wolfgang von Goethe</h3>
                        <p>(1749-1832)</p>
                        <p>Universalgenie, prägte Sturm und Drang ("Die Leiden des jungen Werthers") und Weimarer Klassik ("Faust").</p>
                    </div>
                </div>
                
                <div class="timeline-item right">
                    <div class="timeline-content">
                        <h3>Friedrich Schiller</h3>
                        <p>(1759-1805)</p>
                        <p>Dramatiker ("Die Räuber", "Wilhelm Tell") und enger Freund Goethes in der Weimarer Klassik.</p>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="ressourcen">
            <h2>Lernressourcen</h2>
            
            <h3>Wichtige Primärtexte</h3>
            <ul>
                <li><strong>Nibelungenlied</strong> - Mittelalterliches Heldenepos</li>
                <li><strong>Martin Luther</strong> - Bibelübersetzung (1522-1534)</li>
                <li><strong>Andreas Gryphius</strong> - "Es ist alles eitel" (Barockgedicht)</li>
                <li><strong>Gotthold Ephraim Lessing</strong> - "Nathan der Weise" (1779)</li>
                <li><strong>Johann Wolfgang von Goethe</strong> - "Faust I" (1808)</li>
                <li><strong>Friedrich Schiller</strong> - "Wilhelm Tell" (1804)</li>
            </ul>
            
            <h3>Digitale Archive</h3>
            <ul>
                <li><a href="https://www.projekt-gutenberg.org/" target="_blank">Projekt Gutenberg-DE</a> - Kostenlose E-Books deutscher Literatur</li>
                <li><a href="https://www.deutschestextarchiv.de/" target="_blank">Deutsches Textarchiv</a> - Historische Texte digitalisiert</li>
                <li><a href="https://www.literaturportal-bayern.de/" target="_blank">Literaturportal Bayern</a> - Regionale Literaturgeschichte</li>
            </ul>
            
            <h3>Hilfreiche Tools</h3>
            <ul>
                <li><a href="https://www.duden.de/" target="_blank">Duden Online</a> - Deutsche Rechtschreibung und Grammatik</li>
                <li><a href="https://www.dwds.de/" target="_blank">Digitales Wörterbuch der deutschen Sprache</a> - Etymologie und Wortgeschichte</li>
                <li><a href="https://www.linguee.de/" target="_blank">Linguee</a> - Kontextuelle Übersetzungen</li>
            </ul>
        </section>
        
        <section id="ueber">
            <h2>Über dieses Projekt</h2>
            <p>Diese Website wurde als akademische Ressource für Studierende der Portugiesisch-Deutsch-Philologie entwickelt, die sich mit der deutschen Literaturgeschichte beschäftigen. Unser Ziel ist es, einen umfassenden Überblick über die wichtigsten Epochen, Autoren und Werke zu bieten.</p>
            <p>Die Inhalte werden regelmäßig aktualisiert und erweitert. Für Vorschläge oder Korrekturen kontaktieren Sie uns bitte über das Kontaktformular.</p>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2023 Deutsche Literatur - Ein akademisches Portal</p>
        <p>Entwickelt für Studierende der Portugiesisch-Deutsch-Philologie</p>
    </footer>
</body>
</html>
