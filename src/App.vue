<script setup>
import IconAvatar from './components/icon/IconAvatar.vue';
import IconDestination from './components/icon/IconDestination.vue';
import IconMap from './components/icon/IconMap.vue';
import IconNotification from './components/icon/IconNotification.vue';
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
                <span class="notification"> 
                    <IconNotification/>
                </span>
                <a href="#" class="btn-connexion"> 
                    <IconAvatar/>
                    <p>CONNEXION</p>
                </a>
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
                        <div class="input-group_icon">
                            <IconMap/>
                        </div>
                        <input type="text" placeholder="Ville de départ">
                    </div>
                    <div class="input-group">
                        <IconDestination/>
                        <input type="text" placeholder="Destination">
                    </div>
                    <button class="search-btn">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none">
                            <path d="M11.5 21C16.7467 21 21 16.7467 21 11.5C21 6.25329 16.7467 2 11.5 2C6.25329 2 2 6.25329 2 11.5C2 16.7467 6.25329 21 11.5 21Z" stroke="#030303" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M22 22L20 20" stroke="#030303" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                    </button>
                </div>
            </div>
            <div class="hero-image-container">
                <div class="hero-image">
                    <img src="https://images.unsplash.com/photo-1586528116311-ad8dd3c8310d?auto=format&fit=crop&w=800" alt="Warehouse">
                    <div class="status-card">
                        <div class="status-icon">
                            <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" fill="#60b837">
                                <g clip-path="url(#clip0_4418_4964)">
                                    <path opacity="0.4" d="M10.7499 2.45031C11.4399 1.86031 12.5699 1.86031 13.2699 2.45031L14.8499 3.81031C15.1499 4.07031 15.7099 4.28031 16.1099 4.28031H17.8099C18.8699 4.28031 19.7399 5.15031 19.7399 6.21031V7.91031C19.7399 8.30031 19.9499 8.87031 20.2099 9.17031L21.5699 10.7503C22.1599 11.4403 22.1599 12.5703 21.5699 13.2703L20.2099 14.8503C19.9499 15.1503 19.7399 15.7103 19.7399 16.1103V17.8103C19.7399 18.8703 18.8699 19.7403 17.8099 19.7403H16.1099C15.7199 19.7403 15.1499 19.9503 14.8499 20.2103L13.2699 21.5703C12.5799 22.1603 11.4499 22.1603 10.7499 21.5703L9.16988 20.2103C8.86988 19.9503 8.30988 19.7403 7.90988 19.7403H6.17988C5.11988 19.7403 4.24988 18.8703 4.24988 17.8103V16.1003C4.24988 15.7103 4.03988 15.1503 3.78988 14.8503L2.43988 13.2603C1.85988 12.5703 1.85988 11.4503 2.43988 10.7603L3.78988 9.17031C4.03988 8.87031 4.24988 8.31031 4.24988 7.92031V6.20031C4.24988 5.14031 5.11988 4.27031 6.17988 4.27031H7.90988C8.29988 4.27031 8.86988 4.06031 9.16988 3.80031L10.7499 2.45031Z" fill="white" style="fill: var(--fillg);"/>
                                    <path d="M10.7901 15.1693C10.5901 15.1693 10.4001 15.0893 10.2601 14.9493L7.84006 12.5293C7.55006 12.2393 7.55006 11.7593 7.84006 11.4693C8.13006 11.1793 8.61006 11.1793 8.90006 11.4693L10.7901 13.3593L15.0901 9.0593C15.3801 8.7693 15.8601 8.7693 16.1501 9.0593C16.4401 9.3493 16.4401 9.8293 16.1501 10.1193L11.3201 14.9493C11.1801 15.0893 10.9901 15.1693 10.7901 15.1693Z" fill="white" style="fill: var(--fillg);"/>
                                </g>
                                <defs>
                                    <clipPath id="clip0_4418_4964">
                                        <rect width="30" height="30" fill="white"/>
                                    </clipPath>
                                </defs>
                            </svg>
                        </div>
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
            <div class="feature-card_large-card_dark-card">
                <div class="icon">🚀</div>
                <h3>Vitesse & Réactivité</h3>
                <p>Algorithmes de mise en relation instantanée pour vos trajets urgents. Trouvez un transporteur en moins de 15 minutes.</p>
                <div class="">
                    <div class="avatars">👤👤👤</div>
                    <span class="card-number">01</span>
                </div>
            </div>
            <div class="feature-right-column">
                <div class="feature-card_dark-card_row-card">
                    <div class="feature-card_dark-card_row-card_status">
                        <div class="icon-square">💳</div>
                        <h3>Paiements Sécurisés</h3>
                        <p>Transactions bloquées et libérées uniquement après confirmation de livraison.</p>
                        <span class="card-number">02</span>
                    </div>
                </div>
                <div class="feature-sub-grid">
                    <div class="feature-card_blue-card">
                        <div class="icon">🛡️</div>
                        <h3>Assurance Totale</h3>
                        <p>Couverture AXA incluse pour chaque trajet effectué via Livreko.</p>
                    </div>
                    <div class="feature-card_green-card">
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