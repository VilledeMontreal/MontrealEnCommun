
([English](#english-version))

<a id='french-version' class='anchor' aria-hidden='true'/>

# Principes directeurs d'architecture TI du programme Montréal en commun

## Objectif

Les différents systèmes du programme MeC ne sont pas construits par un seul réalisateur ni nécessairement même en collaboration entre les partenaires. Il est donc primordial de mettre en place des principes de base pour assurer leurs intégrations. Une architecture cible sommaire est publiée et rendue disponible comme référence aux contributeurs. Cette architecture illustre l’intégration des systèmes du MeC et permet aux partenaires de mettre en place une architecture détaillée de leurs sous-systèmes qui s’intègre bien dans l’écosystème MeC.<br />

Les principes visent surtout à orienter les architectures des contributions du programme MeC afin d’offrir des services personnalisés de haute valeur et ce d’une manière homogène, intégrée et efficace qui facilite l’accès à de l’information pertinente, opportune et de qualité.<br />
Ces principes sont issus principalement des meilleures pratiques de l’industrie avec une présentation et une priorisation qui s’aligne avec la vision présentée dans le défi des villes intelligentes.<br />

![Principes directeurs](Goal%20-%20Services%20Num%C3%A9riques.png)

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

## Objective

The different systems of the MeC program are not made by only one developer. They are also not necessarily developed in collaboration between the partners. It is thus primordial to put in place some basic guidelines to ensure their integrations. A target holistic architecture is published and made available as a reference and baseline. This architecture illustrates the integration of the MeC systems and allows the partners to put in place a detailed architecture of their sub-systems that integrate themselves well in the MeC ecosystem.<br />

The principles aim above all is to orient the architectures of the contributions of the MeC program to offer personalized services of high value and in a homogenous, integrated and efficient manner which facilitates access to relevant, timely and quality information.<br />
These principles are derived mainly from the best practices of the industry with a presentation and a prioritization that aligns itself with the vision that was in the Canadian Smart Cities Challenge.<br />

The goal of this document is to present the list of architecture principles of the MeC program.

### List of principles

1. **Primacy of architecture principles**, the architecture principles apply to all the solutions and all the projects in order to improve the synergies, replicability, adaptability and its scalability within Montréal en commun. Discrepancies should be justified and submitted for approval by the appropriate peers.
2. **Integrated, modular and reusable architecture**, plan for the integration of systems during the design phases, promote a highly decoupled modular approach, open-to-change connection interfaces, data isolation, and maximize the  reuse of developed application modules.
3. **Technological neutrality**, the services are designed so that the technologies are interchangeable; the architectures must provide alternatives or continuity plans and observe the aspects of migrability and portability.
4. **Open source software and hardware**, under the City of Montreal's free and open source policy, focus on the development and adoption of software and hardware under open source license, in order to reduce the risks of vendor lock-in and maximize the scalability of the developed solutions. All the projects developed within the framework of Montréal en Commun have a vocation to be replicable and to propose solutions that will become common and beneficial to the Montreal community and elsewhere.
5. **Data: a strategic asset to be protected and valued**, data is a valuable asset that the Montréal en Commun program aspires to make accessible through its open data initiative. The practice of this principle aims in particular to:
    - Optimize categorization and facilitate discovery and accessibility of data.
    - Maintain data quality, normalization, sanitization and aggregation.
    - Respect the principles of Montréal’s Digital Data Charter.


6. **Standardization**, adopt existing IT standards, particularly for APIs and data exchanges, and contribute to relevant standardization efforts. Also follow development methodologies that observe in particular development standards such as unit testing, code review and automated processes.

7. **Common digital identity**, ensure consistency in the identification logic, and favor single sign-on contexts to make the user experience fluid and simple.

8. **Security standards**, each service must manage its own security and ensure that the security breaches of a service does not jeopardize the other systems. Apply OWASP security principles and stay informed of vulnerability logs and adopt mitigation measures and best practices.

9. **Identification, assessment and mitigation of risks**, the deliverables must contain a clear documentation of the risks with the mitigation measures and residual risks.
11. **Accessibility and user-friendliness**, promote the adoption of market standards and access to Internet and mobile solutions. Systematize the use Web Content Accessibility Guidelines (WCAG) international standard: WCAG 2.0 - ISO/IEC 40500:2012 (AA or AAA level).

11. **Social acceptability and ethical and responsible use of data**, as part of the work with the CIRAIG research center, the City of Montreal has defined a series of guiding principles aimed at guaranteeing respect for the individual in the use of technologies . These principles will be followed and will be the subject of official policies and commitments, such as the Cities for digital rights declarations and the Montreal Declaration for the responsible development of artificial intelligence. <br />
Data contributes to improving urban living environments and informing collective and individual decision-making, but must be used wisely and in accordance with privacy protection guidelines.

12. **Legislative Compliance**, program projects must comply with established regulations, laws and policies.

13. **Digital inclusion**, the LIUM recognizes and works to bridge or reduce the digital divide. Montréal en commun projects must also recognize the digital divide because they are aimed at community organizations and disadvantaged people and encourage partners to apply an ADS+ approach, i.e. analysis differentiated according to gender and other factors to ensure that technological solutions do not create injustice.

14. **Eco-design of services and products**, The software and services of the Montréal en commun program respect the principles of sustainable development and environmental constraints from the first stages of functional, graphic, ergonomic, technical design, etc. Priority is given in particular to reducing the resources consumed throughout the life cycle of the services as well as to the underlying material infrastructure. The practice of the principle of eco-design materializes in:
    - A strategic vision, consistent with the vision of Montréal en commun, which governs the intention and the organizational aspect.
    - Operational integration during the design, production and consumption of services.

15. **Standards for the operational management of solutions**, Ensure the autonomy of partners in the operational management of components. Favor cloud computing platforms and respect non-functional constraints (continuity, performance, logging, etc.)

The source code of this project is distributed under the [MIT License](LICENSE).

### Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md#english-version).

### License and Intellectual Property

The source code for this project is released under the [MIT License](LICENSE).

### Code of Conduct

Participation in this poject is governed by the [Code of Conduct](CODE_OF_CONDUCT.md).
