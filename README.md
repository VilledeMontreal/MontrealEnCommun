
([English](#english-version))

<a id='french-version' class='anchor' aria-hidden='true'/>

# Principes directeurs d'architecture TI du programme Montréal en commun

## Objectif

Les différents systèmes du programme MeC ne sont pas construits par un seul réalisateur ni nécessairement même en collaboration entre les partenaires. Il est donc primordial de mettre en place des principes de base pour assurer leurs intégrations. Une architecture cible sommaire est publiée et rendue disponible comme référence aux contributeurs. Cette architecture illustre l’intégration des systèmes du MeC et permet aux partenaires de mettre en place une architecture détaillée de leurs sous-systèmes qui s’intègre bien dans l’écosystème MeC. <br />

Les principes visent surtout à orienter les architectures des contributions du programme MeC afin d’offrir des services personnalisés de haute valeur et ce d’une manière homogène, intégrée et efficace qui facilite l’accès à de l’information pertinente, opportune et de qualité.<br />
Ces principes sont issus principalement des meilleures pratiques de l’industrie avec une présentation et une priorisation qui s’aligne avec la vision présentée dans le défi des villes intelligentes.<br />

Le but de ce document est de présenter la liste des principes directeurs de des architectures des contributions aux programme MeC.


### Liste des principes

1. **Primauté des principes d’architecture**, les principes d'architecture s’appliquent à toutes les solutions et tous les projets, afin d’améliorer les synergies, la réplicabilité, l'adaptabilité   et son évolutivité, au sein de Montréal en commun et dans d’autres communautés. Les divergences devront être justifiées et soumises à l’approbation des pairs  appropriés.
2. **Architecture intégrée, modulaire et réutilisable**, prévoir l’intégration de systèmes lors des phases de conception, et favoriser une approche modulaire fortement découplée soutenue par des interfaces de connexion évolutives permettant d’isoler les données, tout en favorisant la réutilisation des modules applicatifs développés.
3. **Neutralité technologique**, les services sont conçus pour que les technologies soient interchangeables ; les architectures doivent prévoir des plans de sortie ou de continuité et observer les aspects de migrabilité et de portabilité.
4. **Logiciels et matériels libres**, en vertu de la politique de logiciels libres de la Ville de Montréal, miser sur le développement et l’adoption de logiciels et de matériels sous licence ouverte, afin de limiter les risques de menottage technologique et maximiser la capacité d’évolution des solutions développées. Tous les projets développés dans le cadre de Montréal en Commun ont une vocation à être réplicables et proposer des solutions appelées à devenir  des communs, au service de la communauté montréalaise et ailleurs.

5. **Les données : un actif stratégique à protéger et valoriser**, les données sont un bien qui a de la valeur que le programme Montréal en Commun aspire à rendre accessible dans son initiative de données ouvertes. La pratique de ce principe vise en particulier à :
    - Optimiser la catégorisation et faciliter la découverte et l’accessibilité aux données.
    - Maintenir la qualité des données, normalisation, sanitization et agrégation.
    - Respecter les principes de la Charte des données.

6. **Standardisation**, adopter les standards métiers existants, notamment pour les APIs et les échanges de données, et contribuer aux efforts de standardisation pertinents. Suivre aussi des méthodologies de développement qui observent en particulier les standards métiers comme les essais unitaires, révision du code et processus automatisés.

7. **Identité numérique commune**, assurer une cohérence dans la logique d’identification, et privilégier l’authentification unique (SSO pour Single sign-on) pour rendre l’expérience utilisateur fluide et simple.

8. **Standards de sécurité**, chaque service doit gérer sa propre sécurité et s’assurer que la défectuosité d’un service ne mette pas en péril les autres systèmes. Appliquer les principes de sécurité de l’OWASP et rester informé des registres de vulnérabilités et adopter les meilleures pratiques de mitigation.

9. **Identification, évaluation et atténuation des risques**, les livrables doivent contenir une documentation claire des risques avec les mesures de mitigation et risques résiduelles.

10. **Accessibilité et convivialité**, favoriser l’adoption des standards du marché et l’accès des solutions Internet et mobiles. Systématiser l’utilisation des normes d’accès universel: WCAG 2.0 - ISO/IEC 40500:2012 (niveau AA ou AAA).

11. **Acceptabilité sociale et utilisation des données éthique et responsable**, dans le cadre des travaux avec le centre de recherche CIRAIG, la Ville de Montréal a défini une série de principes directeurs visant à garantir le respect de la personne dans les usages des technologies. Ces principes seront suivis et feront l'objet de politiques officielles et d’engagements, tels que les déclarations Cities for digital rights et la Déclaration de Montréal pour un développement responsable de l’intelligence artificielle. <br />
La donnée contribue à améliorer les milieux de vie urbains et à éclairer les prises de décisions collectives et individuelles mais doit être utilisée à bon escient en prenant en compte les paramètres de protection de la vie privée

12. **Conformité législative**, les projets du programme doivent être conformes aux règlements, lois et politiques établies.

13. **Inclusion numérique**, le LIUM reconnaît et travaille à diminuer la fracture numérique. Les projets de Montréal en commun doivent aussi reconnaître la fracture numérique car ils s’adressent à des organismes communautaires et des personnes défavorisées et encourage les partenaires à appliquer une démarche ADS+, soit l’analyse différenciée selon les sexes et autres facteurs pour s’assurer que les solutions technologiques ne créent pas d’injustice.

14. **Écoconception des services et produits**, Les logiciels et services du programme Montréal en commun respectent les principes de développement durable et les contraintes environnementales dès les premières étapes de conception fonctionnelle, graphique, ergonomique, technique, etc. Une priorité est donnée en particulier à la réduction des ressources consommées tout au long du cycle de vie des services ainsi qu’à l’infrastructure matérielle sous-jacente. La pratique du principe de l’écoconception se matérialise en :  
    - Une vision stratégique, conforme à la vision de Montréal en commun qui gouverne l'intention et l'aspect organisationnel.
    - Une intégration opérationnelle au cours de la conception, réalisation et consommation des services.

15. **Standards de gestion opérationnelle des solutions**, Assurer l’autonomie des partenaires dans la gestion opérationnelle des composants. Favoriser les plateformes infonuagiques et respecter les contraintes non-fonctionnelles (continuité, performance, journalisation, ..)


### Contribuer

Voir [CONTRIBUTING.md](CONTRIBUTING.md#french-version)

### Licence et propriété intellectuelle

Le code source de ce projet est libéré sous la licence [MIT License](LICENSE).

### Code de Conduite

La participation à ce projet est réglementée part le [Code de Conduite](CODE_OF_CONDUCT.md#french-version)

______________________

([Français](#french-version))

<a id='english-version' class='anchor' aria-hidden='true'/>

# Architecture Principles of Montréal en commun

## Template for README.md

- Project description

### Details

- How does it work?
- Who will use this project?

### Build

### Installation

### Testing

### License

The source code of this project is distributed under the [MIT License](LICENSE).

### Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md#english-version).

### Code of Conduct

Participation in this poject is governed by the [Code of Conduct](CODE_OF_CONDUCT.md).

