/* SUPPRESSION TOTALE ICÔNES BUGGÉES */
.md-icon,
svg.icon,
.md-nav__icon,
.md-header__button svg,
.md-tabs__icon svg,
.md-typeset a svg {
  display: none !important;
}

/* Liens avec texte seulement */
.md-nav__link::before,
.md-header-nav__button::before {
  content: none !important;
}

/* Images propres */
img { max-width: 95%; height: auto; }
.center { display: block; margin: 0 auto; }
