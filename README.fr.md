<p align="center"><img src="docs/images/banner_fr.png" alt="DunenScope" width="100%"></p>

<p align="center"><a href="README.md">English</a> · <b>Français</b> · <a href="README.zh.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.it.md">Italiano</a> · <a href="README.pt.md">Português (BR)</a> · <a href="README.ru.md">Русский</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a></p>

<p align="center"><a href="https://github.com/simonlabrossedu71-tech/DunenScope/releases/latest"><img src="docs/images/download_fr.png" alt="Télécharger pour Windows" height="60"></a></p>
<p align="center"><sub>Windows 10 / 11 · 64 bits · mode découverte gratuit</sub></p>

## Logiciel de diagnostic et de mise en service des contrôleurs moteur Dunen / ELYX

DunenScope transforme un PC Windows et un adaptateur CAN en banc de test complet pour les contrôleurs Dunen / ELYX : voir ce que fait la machine, comprendre ce qui la limite, la régler et prouver qu'elle fonctionne — en quelques minutes, dans votre langue.

<p align="center"><img src="docs/images/fr/dashboard.png" alt="Tableau de bord" width="100%"></p>

## Ce que fait DunenScope

- **Tableau de bord en direct** — régime, couple, tension et courant batterie, levier, puissance, températures, état et défauts sur un seul écran ; débit de pompe ou vitesse du véhicule selon votre profil de machine.
- **« Pourquoi ça plafonne ? »** — montre quelle limite agit en ce moment (couple, courant batterie, régime, tension) et depuis combien de temps ; résistance interne et marges de la batterie ; contrôle du câblage de chaque entrée ; temps restant avant réduction thermique ; analyse du dernier défaut.
- **Courbes en temps réel** — six graphes synchronisés et une courbe libre de 4 variables au choix, enregistrement CSV.
- **Les 446 paramètres** — mêmes numéros de ligne que DunenConfiger, recherche, comparaison avec un fichier, export xlsx réimportable dans DunenConfiger, CSV.
- **Écriture sécurisée** — sauvegarde complète automatique avant chaque écriture, relecture, paramètres dangereux bloqués, moteur à l'arrêt obligatoire, enregistrement en mémoire permanente comme DunenConfiger.
- **Réglage du PI de vitesse** — mesure sur la machine, réglage manuel par échelons avec conseils, et réglage automatique.
- **Essais moteur** — régime ou couple imposé, auto-apprentissage de l'angle du codeur, boucle de courant ; STOP / Échap et arrêt automatique.
- **Outils d'atelier** — dossier support en un clic (.zip), assistant de calibration du levier, contrôle de fin de ligne avec rapport et journal de production.
- **Pensé pour le terrain** — 10 langues, adaptateurs PEAK PCAN-USB, Kvaser, IXXAT, Vector et SLCAN, profils d'application, et un mode simulation pour tout essayer sans matériel.

## Captures d'écran

<table>
<tr><td width="50%" align="center"><img src="docs/images/fr/diagnostic.png" alt="Diagnostic — ce qui limite la machine"><br><sub>Diagnostic — ce qui limite la machine</sub></td><td width="50%" align="center"><img src="docs/images/fr/realtime.png" alt="Courbes en temps réel et aide au réglage du PI"><br><sub>Courbes en temps réel et aide au réglage du PI</sub></td></tr>
<tr><td width="50%" align="center"><img src="docs/images/fr/parameters.png" alt="Paramètres — comparer, écrire, exporter"><br><sub>Paramètres — comparer, écrire, exporter</sub></td><td width="50%" align="center"><img src="docs/images/fr/licence.png" alt="Fenêtre Licence"><br><sub>Fenêtre Licence</sub></td></tr>
</table>

## Mode découverte gratuit ou version complète

| Fonction | Découverte (gratuit) | Version complète |
| --- | :---: | :---: |
| Connexion, lecture de tous les paramètres, tableau de bord, courbes | ✅ | ✅ |
| Diagnostic, historique des défauts, contrôle de fin de ligne, exports, dossier support | ✅ | ✅ |
| Mode simulation avec toutes les fonctions débloquées | ✅ | ✅ |
| Écriture des réglages dans un vrai contrôleur | — | ✅ |
| Essais moteur, réglage du PI, calibration du levier | — | ✅ |
| Mises à jour automatiques | — | ✅ |

### Version complète

**Licence à vie 50 €** · **abonnement annuel 20 €** · **abonnement trimestriel 7 €**. Une clé par PC, activée en quelques secondes depuis le bouton **Licence** (en haut à droite). Fonctionne sans internet une fois activée. L'achat en ligne ouvre bientôt.

<sub>Abonnements : une connexion à internet tous les 45 jours suffit.</sub>

## Démarrer

1. Téléchargez **DunenScope_Setup** dans [Releases](https://github.com/simonlabrossedu71-tech/DunenScope/releases/latest) et lancez-le. Si Windows affiche « Windows a protégé votre ordinateur », cliquez sur *Informations complémentaires* → *Exécuter quand même*.
2. Choisissez votre langue. L'installeur propose le pilote PEAK s'il manque.
3. Branchez l'adaptateur CAN sur le contrôleur et mettez la clé sur ON.
4. Choisissez l'adaptateur, 250 kbit/s, nœud 1 → **Connecter**. Pas encore de matériel ? Choisissez **Simulation**.
5. Version complète : bouton **Licence** → collez votre clé → **Activer**.

## Configuration requise

- Windows 10 ou 11, 64 bits.
- Un adaptateur CAN : PEAK PCAN-USB (conseillé), Kvaser, IXXAT, Vector ou SLCAN (CANable…).
- Un contrôleur Dunen / ELYX utilisant le protocole de DunenConfiger (Modbus sur CAN, 250 kbit/s par défaut).

## Notices

Notices complètes (PDF), aussi installées dans le menu Démarrer :

- [English (PDF)](docs/manuals/DunenScope_Manual_EN.pdf) · [Français (PDF)](docs/manuals/DunenScope_Notice_FR.pdf) · [中文 (PDF)](docs/manuals/DunenScope_Manual_ZH.pdf)

## Mises à jour et sécurité

- Chaque installateur est signé ; DunenScope vérifie la signature avant d'installer une mise à jour.
- Les nouvelles versions sont proposées au démarrage aux utilisateurs de la version complète ; réglages, profils et sauvegardes sont conservés.
- DunenScope ne contacte que le service de licence et le serveur de téléchargement. Aucune autre donnée ne quitte votre PC.

## Licence et précautions d'emploi

En installant DunenScope, vous acceptez le [contrat de licence utilisateur](docs/licence/EULA_FR.txt). DunenScope peut modifier les réglages d'un contrôleur et faire tourner un moteur : travaillez machine en sécurité et avec du personnel qualifié. Dunen et ELYX sont des marques de leurs propriétaires respectifs.
