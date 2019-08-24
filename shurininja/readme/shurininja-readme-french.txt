Profil du Shuri Ninja
_____________________


Version :    2.0.0
Auteur :     Twinblades2
Support :    Aalkaor et Gwendolyne
Langues :    anglais, français
Plateforme : Windows

Téléchargement : https://github.com/GwendolyneFreddy/Shuri-Ninja/releases/latest
Discussion: 



Présentation
============

Ce module ajoute un nouveau profil de voleur dans le jeu : le Shuri Ninja.
Créé il y a de nombreuses années par Twinblades2, il a été réécrit dans les standards modernes de code WeiDU et rendu compatible pour les jeux Enhanced par Aalkaor et Freddy_Gwendo.



Compatibilité
=============

Ce mod est conçu pour fonctionner sur les jeux Infinity Engine suivants : Enhanced Edition (BGEE), Baldur's Gate II: Enhanced Edition (BG2EE), le jeu original Baldur's Gate II (Les Ombres d'Amn : BG2-SoA) avec son extension Trône de Bhaal (Throne of Bhaal : ToB), les mods de conversion Baldur's Gate Trilogy (BGT) et Enhanced Edition Trilogy (EET), ainsi que l'extension de BGEE, Siege of Dragonspear (SoD).

Shuri Ninja est un mod WeiDU et devrait par conséquent être compatible avec n'importe quel mod WeiDU. Si vous faites face à des bugs, veuillez les signaler dans le forum, s'il vous plaît.
Bien que je m'efforce de le rendre compatible avec le plus grand nombre possible de mods, des incompatibilités risquent toujours de se produire. Voici la liste de celles recensées jusqu'à présent :

  - Shuri-Ninja n'est pas compatible avec Kit Revisions.


Si vous jouez avec BG2-ToB ou BGT, je vous recommande fortement d'installer la dernière version du BG2 Fixpack (http://www.gibberlings3.net/bg2fixpack/) avant d'installer ce mod.



Installation
============

1. Mise en garde

Si une ancienne version de ce mod est déjà installée, il est nécessaire de la désinstaller d'abord. Pour cela, lancez setup-shurininja.exe et désinstallez le composant principal précédemment installé. Une fois la désinstallation achevée, supprimez le répertoire shurininja et le fichier setup-shurininja.exe avant d'extraire la nouvelle version du mod.

Lorsque vous installez ou désinstallez, ne fermez pas la fenêtre DOS en cliquant sur le bouton X ! Au lieu de cela, appuyez sur la touche Entrée lorsque l'invite de commandes vous le demande.

Par précaution, désactivez les antivirus ou tout logiciel résidant en mémoire avant d'installer ce mod, ou tout autre mod. Certains (en particulier avast et Norton !) ont une fâcheuse tendance à déclarer les exécutables des mods comme des faux positifs, provoquant ainsi l'échec de la procédure d'installation.


2. Note spéciale pour Siege of Dragonspear fourni par Steam/GOG

Good Old Games (GOG) et Steam fournissent le contenu de Siege of Dragonspear dans un format que WeiDU, l'outil utilisé pour installer ce mod, ne peut pas reconnaitre. Vous devez donc lancer le programme Modmerge (https://forums.beamdog.com/discussion/50441/modmerge-merge-your-steam-gog-zip-based-dlc-into-something-weidu-nearinfinity-dltcep-can-use/p1 ) dans votre répertoire de SoD avant d'installer ce mod, ou tout autre mod utilisant WeiDU.


3. Note pour les jeux en Édition Améliorée (EE)

Les Éditions améliorées sont des jeux que le développeur fait encore évoluer, notamment par l'ajout de capacités supplémentaires destinées à la création de mods et par l'ajout de contenus. N'oubliez pas que chaque patch de mise à jour effacera les mods que vous avez installés ! Ce mod ne fera pas exception à la règle.

Si vous pouvez retarder la mise à jour du patch en plein milieu d'un partie moddée (si vous en avez la possibilité, notamment chez Beamdog et Good Old Games), n'oubliez pas que même après avoir réinstallé les mods sur un nouveau patch, vous ne pourrez peut-être pas continuer le jeu avec vos anciennes sauvegardes, en particulier à cause de noms de personnages, de lieux, etc. qui pourraient être incorrects. Pour y remédier, copiez tout le dossier du jeu dans un nouveau dossier dans lequel vous installerez vos mods, et qui ne sera pas modifié par les patches de mise à jour. Il est important que vous installiez le mod dans la version linguistique dans laquelle vous jouez. Sinon, les dialogues du mod ne s'afficheront pas et provoqueront des messages d'erreur.


4. Windows

Shuri-Ninja pour Windows est livré et installé avec WeiDU, et est diffusé sous forme d'archive.

Vous devez extraire les fichiers de l'archive dans votre répertoire de jeu (le dossier qui contient le fichier CHITIN.KEY) à l'aide de 7zip (http://www.7-zip.org/download.html ), de WinRAR (http://www.rarlab.com/download.htm ) ou de tout autre utilitaire de compression gérant les fichiers zip. Une fois l'archive extraite correctement, vous devriez trouver le répertoire shurininja et le fichier setup-shurininja.exe dans votre répertoire de jeu. Pour installer le mod, il suffit de double-cliquer sur setup-shurininja.exe et de suivre les instructions affichées à l'écran.

Vous pouvez lancer setup-shurininja.exe dans votre répertoire de jeu pour réinstaller, désinstaller, ou encore changer des composants.


5. Note pour effectuer une désinstallation complète

En plus des méthodes détaillées plus haut pour supprimer des composants, il est possible de désinstaller complètement le mod en tapant "setup-shurininja --uninstall" dans une ligne de commandes, ce qui supprimera tous les composants sans devoir ingurgiter tous les messages.



Composants
==========

Le programme d'installation comprend les composants suivants. Chacun possède un numéro distinct et pré-défini qui lui attribue une position déterminée (mot-clé DESIGNATED en langage WeiDU) ; ce qui permet aux autres composants de le détecter et aux utilitaires d'installation automatiques comme le BiG World Setup de préciser quels composants installer.

10. Profil de Shuri Ninja original

Description du profil :

Les shuri ninjas sont formés par le Shurikai, une organisation d'assassins ninjas qui opère dans tout le Kara-Tur. Ils se fondent dans les ombres, sont rapides, d'une redoutable efficacité au combat, et excellent dans le maniement des lames orientales, des armes de lancer et des arcs. Il est de notoriété publique qu'une cible désignée par le Shurikai ne passe pas la nuit. Leurs techniques de combat mortelles leur ont fait gagner le respect, mais aussi la haine farouche des samouraïs et des autres clans rivaux de ninjas. Rares sont en effet les combattants qui ont survécu après avoir croisé le fer avec un shuri ninja.

Beaucoup s'affranchissent du Shurikai pour suivre leur propre voie, même s'il doivent constamment surveiller leurs arrières pour ne pas être victimes de la lame de leurs anciens compagnons d'armes. S'ils parviennent à rejoindre sans encombre les contrées occidentales, ils savent que les guildes de voleurs locales apprécient et recherchent ardemment leurs services. Des guildes entières ayant été décimées par un seul shuri ninja, personne n'ose les trahir. Le Kara-Tur comptant très peu de demi-humains, seuls les humains sont autorisés à bénéficier des enseignements secrets du Shurikai Ninjutsu.

Avantages :
- +20 % en Furtivité.
- +2 à la Dextérité.
- Obtient les capacités spéciales du guerrier à haut niveau.
- Bonus de 1 au toucher et aux dégâts tous les 4 niveaux (à partir du niveau 4).
- Bonus de 1 à la CA tous les 5 niveaux (à partir du niveau 5).
- Peut se spécialiser (deux étoiles) dans le maniement du katana, du cimeterre, des dagues, des fléchettes et de l'arc court.
- Peut se spécialiser (deux étoiles) dans le style de combat d'arme à une main et allouer trois étoiles dans le style de combat à deux armes.

À mesure qu'il augmente de niveau, le shuri ninja acquiert de nouvelles techniques redoutables qui perfectionnent sa science martiale et ses talents d'assassin.
  * Au niveau 5 (ceinture bleue), il gagne la capacité Vision véritable deux fois par jour pour détecter les illusions.
  * Au niveau 10 (ceinture violette), il sait frapper les points vitaux de ses adversaires (Coup étourdissant deux fois par jour). Toutes ses attaques réussies au cours du round suivant obligent la victime à réussir un jet de sauvegarde contre les sorts sous peine d'être assommée
  * Au niveau 15 (ceinture rouge), il peut utiliser la capacité Frappe éclair une fois par jour, tous les 10 niveaux d'expérience. Pendant 10 secondes, toutes ses attaques infligent le maximum de dégâts.
  * Au niveau 20 (ceinture marron), une fois par jour, il peut utiliser la capacité Paume vibratoire du moine, dont le secret a été volé dans un monastère. Sa prochaine attaque réussie force sa victime à réussir un jet de sauvegarde contre les sorts ou mourir.
  * Au niveau 25 (ceinture noire), il peut enduire son arme de poison une fois par jour (capacité Arme empoisonnée).
  * Au niveau 30, il peut protéger son esprit de toute attaque mentale une fois par jour (capacité Ordres chaotiques) et il gagne 20 % supplémentaires en Furtivité.
  * Au niveau 35 (premier dan), il est encore plus fort au combat (bonus de 1 au TAC0) et gagne une utilisation supplémentaire de la capacité Arme empoisonnée.

ARME EMPOISONNÉE :
Chaque coup réussi au cours du prochain round empoisonnera la cible. Chaque cible ne peut être affectée qu'une fois par round. Le montant des dégâts de poison dépend du niveau du personnage :
1er : la cible subit 1 point de dégât de poison par seconde pendant 6 secondes (annulé par une sauvegarde contre la mort à +1)
5ème : la cible subit 1 point de dégât de poison par seconde pendant 12 secondes (annulé par une sauvegarde contre la mort) et subit immédiatement 2 points de dégâts de poison (sans sauvegarde)
9ème : la cible subit 1 point de dégât de poison par seconde pendant 18 secondes (annulé par une sauvegarde contre la mort à -1) et subit immédiatement 4 points de dégâts de poison (sans sauvegarde)
13ème : la cible subit 1 point de dégât de poison par seconde pendant 24 secondes (annulé par une sauvegarde contre la mort à -2) et subit immédiatement 6 points de dégâts de poison (sans sauvegarde)


Désavantages :
- Ne peut pas poser de pièges.
- Pénalité de 2 points à la Force, à la Constitution et au Charisme.
- Ne peut utiliser que les armes suivantes : katana, cimeterre, dague, fléchette et arc court.
- Ne peut pas être compétent dans les styles de combat armes à deux mains et épée et bouclier.
- Ne peut pas se jumeler.
- Doit être d'alignement chaotique.
- Doit être un humain.


Je pense que les deux composants suivants ne nécessitent pas de description...

20. Profil de Shuri Ninja limité aux armures de cuir (seulement pour EE)

30. Profil de Shuri Ninja sans armure (seulement pour EE)



Crédits et remerciements
========================

- Auteur : Twinblades2 (at twblds@hotmail.com)


- Remerciements

    - Aalkaor pour avoir déterré ce mod, l'avoir traduit en français, commencé le code WeiDU et initié l'idée de le rendre compatible avec les jeux EE.
    - Gwendolyne pour avoir terminé le code WeiDU, l'avoir rendu compatible avec les hjeux EE et avoir relu la traduction.


- Information sur les droits d'auteur

Shuri Ninja n'est pas développé, supporté ni approuvé par BioWare™ ou Interplay/Black Isle, Overhaul, Beamdog ou Wizards of the Coast. Il a été développé par Twinblades2, et est basé sur le jeu Baldur's Gate II et son extension.
Baldur's Gate II : Les Ombres d'Amn et Baldur's Gate II : Trône de Bhaal appartiennent à © TSR, Inc. Le moteur Infinity Engine appartient à © BioWare Corp. Toutes les autres marques et droits d'auteur appartiennent à leurs propriétaires respectifs.

Ce mod a été créé pour être librement apprécié par tous les joueurs de Baldur's Gate II. Cependant, il ne doit pas être vendu, publié, compilé ou redistribué sous une forme quelconque sans le consentement de son auteur.</br>



Historique des versions
=======================

Note du traducteur : l'historique n'est volontairement pas traduit afin de faciliter la mise à jour continue du mod.

Version 2.0.0 - nn septembre 2019

- tp2 split into components and commented for easier further updates.
- Reorganized components (DESIGNATED numbers).
- Added two sub-components (EE only): Shuri Ninja Kit may not wear heavier armor than leather and may not wear any armor.
- Added BG2EE compatibility (probably with EET, but not yet tested).
- No longer overwrites system files.
- Used HANDLE_CHARSETS function to add BG2EE compatibility for languages other than English.</li>
- Deleted unused files from mod folder.
- Updated readme (Shri-Ninja now supports translated readmes).
- Added French translation, including readme (Aalkaor and Gwendolyne).
- Traification.
- Updated installer <acronym title="Weimer Dialogue Utility">WeiDU</acronym> to v246.


Version 1 - February 10, 2004

- Initial release

