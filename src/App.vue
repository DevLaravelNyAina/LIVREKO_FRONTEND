<script>

</script>

<template>
    <header>
        <nav class="navbar">
            <div class="nav-left">
                <div class="logo">LIVREKO</div>
                <ul class="nav-links">
                    <li><a href="#">Find Jobs</a></li>
                    <li><a href="#">Post Route</a></li>
                    <li><a href="#">My Fleet</a></li>
                </ul>
            </div>
            <div class="nav-right">
                <span class="notification">🔔</span>
                <a href="#" class="btn-connexion">👤 CONNEXION</a>
            </div>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-container">
            <div class="hero-text">
                <span class="badge">LOGISTIQUE DE CONFIANCE</span>
                <h1>Connectez-vous pour livrer et recevoir <span class="highlight">en <br> toute confiance.</span></h1>
                <p>Livreko transforme le transport de marchandises en une expérience premium, fluide et sécurisée pour les professionnels et les particuliers.</p>
                
                <div class="hero-actions">
                    <button class="btn-blue">Trouver un job</button>
                    <button class="btn-outline">Publier un trajet</button>
                </div>

                <div class="search-bar">
                    <div class="input-group">
                        <span>📍</span>
                        <input type="text" placeholder="Ville de départ">
                    </div>
                    <div class="input-group">
                        <span>🚀</span>
                        <input type="text" placeholder="Destination">
                    </div>
                    <button class="search-btn">🔍</button>
                </div>
            </div>
            <div class="hero-image-container">
                <div class="hero-image">
                    <img src="https://images.unsplash.com/photo-1586528116311-ad8dd3c8310d?auto=format&fit=crop&w=800" alt="Warehouse" style="width: 200px;">
                    <div class="status-card">
                        <div class="status-icon">✔</div>
                        <div class="status-info">
                            <span class="status-label">STATUS EN DIRECT</span>
                            <span class="status-value">99.8% Livraisons Réussies</span>
                            <span class="status-desc">Confiance vérifiée par nos 15k transporteurs</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="features">
        <div class="section-header">
            <h2>L'orchestration de la logistique moderne</h2>
            <p>Plus qu'une plateforme, une infrastructure technologique au service de vos envois.</p>
        </div>

        <div class="features-grid">
            <div class="feature-card large-card dark-card">
                <div class="icon">🚀</div>
                <h3>Vitesse & Réactivité</h3>
                <p>Algorithmes de mise en relation instantanée pour vos trajets urgents. Trouvez un transporteur en moins de 15 minutes.</p>
                <div class="avatars">👤👤👤</div>
                <span class="card-number">01</span>
            </div>
            <div class="feature-right-column">
                <div class="feature-card dark-card row-card">
                    <div class="icon-square">💳</div>
                    <div>
                        <h3>Paiements Sécurisés</h3>
                        <p>Transactions bloquées et libérées uniquement après confirmation de livraison.</p>
                    </div>
                    <span class="card-number">02</span>
                </div>
                <div class="feature-sub-grid">
                    <div class="feature-card blue-card">
                        <div class="icon">🛡️</div>
                        <h3>Assurance Totale</h3>
                        <p>Couverture AXA incluse pour chaque trajet effectué via Livreko.</p>
                    </div>
                    <div class="feature-card green-card">
                        <div class="icon">🍃</div>
                        <h3>Zéro Carbone</h3>
                        <p>Optimisation des retours à vide pour une logistique durable.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="popular-routes">
        <div class="routes-header">
            <div>
                <h2>Trajets Populaires</h2>
                <p>Rejoignez le mouvement. Des centaines de transporteurs parcourent ces routes chaque jour.</p>
            </div>
            <a href="#" class="view-all">Voir tous les trajets →</a>
        </div>

        <div class="routes-grid">
            <div class="route-card">
                <div class="route-img">
                    <img src="https://images.unsplash.com/photo-1502602898657-3e91760cbb34?auto=format&fit=crop&w=400" alt="Paris">
                </div>
                <div class="route-content">
                    <div class="route-meta">
                        <span class="status-dot green">● ACTIF MAINTENANT</span>
                        <span class="price">€85.00</span>
                    </div>
                    <div class="route-details">
                        <p>⚪ Paris, FR</p>
                        <p class="distance">340 km • 4h 20m</p>
                        <p>📍 Lyon, FR</p>
                    </div>
                    <button class="btn-reserve">Réserver ce trajet</button>
                </div>
            </div>
            <div class="route-card">
                <div class="route-img">
                    <img src="https://images.unsplash.com/photo-1563910621483-200084042211?auto=format&fit=crop&w=400" alt="Bordeaux">
                </div>
                <div class="route-content">
                    <div class="route-meta">
                        <span class="status-dot orange">● 2 PLACES RESTANTES</span>
                        <span class="price">€120.00</span>
                    </div>
                    <div class="route-details">
                        <p>⚪ Bordeaux, FR</p>
                        <p class="distance">650 km • 6h 45m</p>
                        <p>📍 Marseille, FR</p>
                    </div>
                    <button class="btn-reserve">Réserver ce trajet</button>
                </div>
            </div>
            <div class="route-card">
                <div class="route-img">
                    <img src="https://images.unsplash.com/photo-1555881400-74d7acaacd8b?auto=format&fit=crop&w=400" alt="Lille">
                </div>
                <div class="route-content">
                    <div class="route-meta">
                        <span class="status-dot green">● EN LIGNE</span>
                        <span class="price">€45.00</span>
                    </div>
                    <div class="route-details">
                        <p>⚪ Lille, FR</p>
                        <p class="distance">220 km • 2h 30m</p>
                        <p>📍 Bruxelles, BE</p>
                    </div>
                    <button class="btn-reserve">Réserver ce trajet</button>
                </div>
            </div>
        </div>
    </section>

    <section class="cta">
        <div class="cta-box">
            <h2>Prêt à réinventer votre logistique ?</h2>
            <p>Rejoignez une communauté de transporteurs et d'expéditeurs qui font le choix de la confiance et de l'efficacité.</p>
            <div class="cta-btns">
                <button class="btn-white">Commencer Gratuitement</button>
                <button class="btn-outline-white">Voir les Tarifs</button>
            </div>
        </div>
    </section>

    <footer>
        <div class="footer-grid">
            <div class="footer-brand">
                <div class="logo">LIVREKO</div>
                <p>La plateforme de logistique collaborative leader en Europe. Sécurité, rapidité et durabilité au cœur de chaque livraison.</p>
                <div class="social-icons"><span>🌐</span> <span>🔗</span></div>
            </div>
            <div class="footer-links">
                <h4>PLATEFORME</h4>
                <a href="#">Find Jobs</a>
                <a href="#">Post Route</a>
                <a href="#">My Fleet</a>
                <a href="#">Calculateur de prix</a>
            </div>
            <div class="footer-links">
                <h4>SUPPORT</h4>
                <a href="#">Aide & FAQ</a>
                <a href="#">Assurance AXA</a>
                <a href="#">Sécurité</a>
                <a href="#">Contact</a>
            </div>
            <div class="footer-links">
                <h4>LÉGAL</h4>
                <a href="#">Confidentialité</a>
                <a href="#">CGU</a>
                <a href="#">Cookies</a>
            </div>
        </div>
        <div class="footer-bottom">
            <p>© 2024 LIVREKO Logistique. Tous droits réservés.</p>
            <div class="payment-icons">💳 💳 💳</div>
        </div>
    </footer>
</template>