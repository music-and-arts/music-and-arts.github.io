---
layout: default
title: "Music and Arts - Musica, Arte e Pensiero"
description: "Uno spazio raffinato dedicato alla musica, arte, scrittura e creatività. Esplora contenuti unici e riflessioni profonde."
---

<section class="hero">
    <div class="hero-content">
        <h1 class="hero-title">Musica e Altro</h1>
        <p class="hero-subtitle">Uno spazio per condividere passioni, idee e riflessioni</p>
    </div>
</section>

<section class="content-section">
    <div class="text-block">
        <h2>Benvenuto nel mio angolo di creatività</h2>
        <p>Questo sito nasce dalla necessità di dare forma concreta a pensieri, emozioni e connessioni che la musica e l'arte suscitano in me. Non troverai recensioni tecniche o analisi accademiche, ma piuttosto impressioni personali, suggestioni e forse qualche intuizione che risuoni con la tua esperienza.</p>
        
        <p>La musica per me non è solo suono organizzato, ma un linguaggio in grado di attraversare dimensioni diverse della percezione. È colore, è immagine, è memoria, è corpo. In queste pagine esploreremo insieme queste connessioni.</p>
    </div>

    <div class="features-grid">
        <div class="feature-card">
            <h3>I Colori della Musica</h3>
            <p>Esplorazione delle connessioni tra musica e percezione visiva. Come i suoni si traducono in palette cromatiche e visioni interiori.</p>
            <a href="{{ '/i-colori-della-musica' | relative_url }}" class="feature-link">Esplora →</a>
        </div>

        <div class="feature-card">
            <h3>Un Regalo per Voi</h3>
            <p>Risorse musicali e contenuti speciali condivisi con la comunità. Piccoli doni per chi apprezza la profondità artistica.</p>
            <a href="{{ '/un-regalo-per-voi' | relative_url }}" class="feature-link">Scopri →</a>
        </div>

        <div class="feature-card">
            <h3>Tre Albums Esagerati</h3>
            <p>Album che hanno superato i confini della normalità musicale. Opere che hanno segnato traiettorie artistiche uniche.</p>
            <a href="{{ '/tre-albums-esagerati' | relative_url }}" class="feature-link">Ascolta →</a>
        </div>

        <div class="feature-card">
            <h3>Immagini e Musica</h3>
            <p>Il dialogo costante tra visione e ascolto nell'esperienza artistica. Come le immagini influenzano la percezione musicale.</p>
            <a href="{{ '/immagini-e-musica' | relative_url }}" class="feature-link">Vedi →</a>
        </div>
    </div>

    <div class="quotes-section">
        <h2>Pensieri in nota</h2>
        <div class="quotes-grid">
            <div class="quote-card">
                <blockquote>
                    "La musica è la letteratura del cuore; essa comincia dove finisce la parola."
                    <cite>— Alphonse de Lamartine</cite>
                </blockquote>
            </div>
            <div class="quote-card">
                <blockquote>
                    "La musica può dare nome all'innominabile e comunicare l'inconoscibile."
                    <cite>— Leonard Bernstein</cite>
                </blockquote>
            </div>
            <div class="quote-card">
                <blockquote>
                    "Dove le parole falliscono, la musica parla."
                    <cite>— Hans Christian Andersen</cite>
                </blockquote>
            </div>
        </div>
    </div>
</section>

<style>
.hero {
    padding: 5rem 0;
    text-align: center;
    background: var(--gradient);
    color: white;
    border-radius: 16px;
    margin-bottom: 4rem;
    position: relative;
    overflow: hidden;
}

.hero::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" opacity="0.1"><circle cx="50" cy="50" r="2" fill="white"/></svg>') repeat;
}

.hero-title {
    font-family: 'Playfair Display', serif;
    font-size: 3.5rem;
    font-weight: 500;
    margin-bottom: 1rem;
    position: relative;
}

.hero-subtitle {
    font-size: 1.4rem;
    opacity: 0.9;
    font-weight: 300;
    position: relative;
}

.content-section {
    padding: 2rem 0;
}

.text-block {
    max-width: 800px;
    margin: 0 auto 4rem;
    text-align: center;
}

.text-block h2 {
    font-family: 'Playfair Display', serif;
    font-size: 2.2rem;
    margin-bottom: 2rem;
    font-weight: 500;
    color: var(--primary-color);
}

.text-block p {
    font-size: 1.1rem;
    margin-bottom: 1.5rem;
    color: var(--text-color);
    line-height: 1.8;
}

.features-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin-bottom: 5rem;
}

.feature-card {
    background: white;
    padding: 2.5rem;
    border-radius: 12px;
    box-shadow: var(--shadow);
    transition: all 0.3s ease;
    border: 1px solid var(--border-color);
    position: relative;
}

.feature-card::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 4px;
    background: var(--gradient);
    border-radius: 12px 12px 0 0;
}

.feature-card:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-hover);
}

.feature-card h3 {
    font-family: 'Playfair Display', serif;
    font-size: 1.4rem;
    margin-bottom: 1rem;
    color: var(--primary-color);
}

.feature-card p {
    color: var(--text-light);
    margin-bottom: 1.5rem;
    line-height: 1.6;
}

.feature-link {
    color: var(--primary-color);
    text-decoration: none;
    font-weight: 500;
    transition: all 0.3s ease;
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
}

.feature-link:hover {
    color: var(--secondary-color);
    gap: 1rem;
}

.quotes-section {
    max-width: 1000px;
    margin: 0 auto;
}

.quotes-section h2 {
    font-family: 'Playfair Display', serif;
    font-size: 2rem;
    text-align: center;
    margin-bottom: 3rem;
    color: var(--primary-color);
}

.quotes-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.quote-card {
    background: white;
    padding: 2rem;
    border-radius: 12px;
    box-shadow: var(--shadow);
    border-left: 4px solid var(--primary-color);
}

.quote-card blockquote {
    font-family: 'Playfair Display', serif;
    font-size: 1.1rem;
    font-style: italic;
    color: var(--text-color);
    line-height: 1.6;
    margin-bottom: 1rem;
}

.quote-card cite {
    color: var(--text-light);
    font-size: 0.9rem;
    font-style: normal;
}

@media (max-width: 768px) {
    .hero-title {
        font-size: 2.5rem;
    }
    
    .hero-subtitle {
        font-size: 1.2rem;
    }
    
    .features-grid {
        grid-template-columns: 1fr;
    }
    
    .quotes-grid {
        grid-template-columns: 1fr;
    }
    
    .feature-card {
        padding: 2rem;
    }
}
</style>
