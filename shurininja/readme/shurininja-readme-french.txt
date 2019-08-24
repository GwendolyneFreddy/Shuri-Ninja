Profil du Shuri Ninja
_____________________


Version :    2.0.0
Auteur :     Twinblades2
Support :    Aalkaor et Gwendolyne
Langues :    anglais, fran�ais
Plateforme : Windows

T�l�chargement : https://github.com/GwendolyneFreddy/Shuri-Ninja/releases/latest
Discussion: 



Pr�sentation
============

Ce module ajoute un nouveau profil de voleur dans le jeu : le Shuri Ninja.
Cr�� il y a de nombreuses ann�es par Twinblades2, il a �t� r��crit dans les standards modernes de code WeiDU et rendu compatible pour les jeux Enhanced par Aalkaor et Freddy_Gwendo.



Compatibilit�
=============

Ce mod est con�u pour fonctionner sur les jeux Infinity Engine suivants : Enhanced Edition (BGEE), Baldur's Gate II: Enhanced Edition (BG2EE), le jeu original Baldur's Gate II (Les Ombres d'Amn : BG2-SoA) avec son extension Tr�ne de Bhaal (Throne of Bhaal : ToB), les mods de conversion Baldur's Gate Trilogy (BGT) et Enhanced Edition Trilogy (EET), ainsi que l'extension de BGEE, Siege of Dragonspear (SoD).

Shuri Ninja est un mod WeiDU et devrait par cons�quent �tre compatible avec n'importe quel mod WeiDU. Si vous faites face � des bugs, veuillez les signaler dans le forum, s'il vous pla�t.
Bien que je m'efforce de le rendre compatible avec le plus grand nombre possible de mods, des incompatibilit�s risquent toujours de se produire. Voici la liste de celles recens�es jusqu'� pr�sent :

  - Shuri-Ninja n'est pas compatible avec Kit Revisions.


Si vous jouez avec BG2-ToB ou BGT, je vous recommande fortement d'installer la derni�re version du BG2 Fixpack (http://www.gibberlings3.net/bg2fixpack/) avant d'installer ce mod.



Installation
============

1. Mise en garde

Si une ancienne version de ce mod est d�j� install�e, il est n�cessaire de la d�sinstaller d'abord. Pour cela, lancez setup-shurininja.exe et d�sinstallez le composant principal pr�c�demment install�. Une fois la d�sinstallation achev�e, supprimez le r�pertoire shurininja et le fichier setup-shurininja.exe avant d'extraire la nouvelle version du mod.

Lorsque vous installez ou d�sinstallez, ne fermez pas la fen�tre DOS en cliquant sur le bouton X ! Au lieu de cela, appuyez sur la touche Entr�e lorsque l'invite de commandes vous le demande.

Par pr�caution, d�sactivez les antivirus ou tout logiciel r�sidant en m�moire avant d'installer ce mod, ou tout autre mod. Certains (en particulier avast et Norton !) ont une f�cheuse tendance � d�clarer les ex�cutables des mods comme des faux positifs, provoquant ainsi l'�chec de la proc�dure d'installation.


2. Note sp�ciale pour Siege of Dragonspear fourni par Steam/GOG

Good Old Games (GOG) et Steam fournissent le contenu de Siege of Dragonspear dans un format que WeiDU, l'outil utilis� pour installer ce mod, ne peut pas reconnaitre. Vous devez donc lancer le programme Modmerge (https://forums.beamdog.com/discussion/50441/modmerge-merge-your-steam-gog-zip-based-dlc-into-something-weidu-nearinfinity-dltcep-can-use/p1 ) dans votre r�pertoire de SoD avant d'installer ce mod, ou tout autre mod utilisant WeiDU.


3. Note pour les jeux en �dition Am�lior�e (EE)

Les �ditions am�lior�es sont des jeux que le d�veloppeur fait encore �voluer, notamment par l'ajout de capacit�s suppl�mentaires destin�es � la cr�ation de mods et par l'ajout de contenus. N'oubliez pas que chaque patch de mise � jour effacera les mods que vous avez install�s ! Ce mod ne fera pas exception � la r�gle.

Si vous pouvez retarder la mise � jour du patch en plein milieu d'un partie modd�e (si vous en avez la possibilit�, notamment chez Beamdog et Good Old Games), n'oubliez pas que m�me apr�s avoir r�install� les mods sur un nouveau patch, vous ne pourrez peut-�tre pas continuer le jeu avec vos anciennes sauvegardes, en particulier � cause de noms de personnages, de lieux, etc. qui pourraient �tre incorrects. Pour y rem�dier, copiez tout le dossier du jeu dans un nouveau dossier dans lequel vous installerez vos mods, et qui ne sera pas modifi� par les patches de mise � jour. Il est important que vous installiez le mod dans la version linguistique dans laquelle vous jouez. Sinon, les dialogues du mod ne s'afficheront pas et provoqueront des messages d'erreur.


4. Windows

Shuri-Ninja pour Windows est livr� et install� avec WeiDU, et est diffus� sous forme d'archive.

Vous devez extraire les fichiers de l'archive dans votre r�pertoire de jeu (le dossier qui contient le fichier CHITIN.KEY) � l'aide de 7zip (http://www.7-zip.org/download.html ), de WinRAR (http://www.rarlab.com/download.htm ) ou de tout autre utilitaire de compression g�rant les fichiers zip. Une fois l'archive extraite correctement, vous devriez trouver le r�pertoire shurininja et le fichier setup-shurininja.exe dans votre r�pertoire de jeu. Pour installer le mod, il suffit de double-cliquer sur setup-shurininja.exe et de suivre les instructions affich�es � l'�cran.

Vous pouvez lancer setup-shurininja.exe dans votre r�pertoire de jeu pour r�installer, d�sinstaller, ou encore changer des composants.


5. Note pour effectuer une d�sinstallation compl�te

En plus des m�thodes d�taill�es plus haut pour supprimer des composants, il est possible de d�sinstaller compl�tement le mod en tapant "setup-shurininja --uninstall" dans une ligne de commandes, ce qui supprimera tous les composants sans devoir ingurgiter tous les messages.



Composants
==========

Le programme d'installation comprend les composants suivants. Chacun poss�de un num�ro distinct et pr�-d�fini qui lui attribue une position d�termin�e (mot-cl� DESIGNATED en langage WeiDU) ; ce qui permet aux autres composants de le d�tecter et aux utilitaires d'installation automatiques comme le BiG World Setup de pr�ciser quels composants installer.

10. Profil de Shuri Ninja original

Description du profil :

Les shuri ninjas sont form�s par le Shurikai, une organisation d'assassins ninjas qui op�re dans tout le Kara-Tur. Ils se fondent dans les ombres, sont rapides, d'une redoutable efficacit� au combat, et excellent dans le maniement des lames orientales, des armes de lancer et des arcs. Il est de notori�t� publique qu'une cible d�sign�e par le Shurikai ne passe pas la nuit. Leurs techniques de combat mortelles leur ont fait gagner le respect, mais aussi la haine farouche des samoura�s et des autres clans rivaux de ninjas. Rares sont en effet les combattants qui ont surv�cu apr�s avoir crois� le fer avec un shuri ninja.

Beaucoup s'affranchissent du Shurikai pour suivre leur propre voie, m�me s'il doivent constamment surveiller leurs arri�res pour ne pas �tre victimes de la lame de leurs anciens compagnons d'armes. S'ils parviennent � rejoindre sans encombre les contr�es occidentales, ils savent que les guildes de voleurs locales appr�cient et recherchent ardemment leurs services. Des guildes enti�res ayant �t� d�cim�es par un seul shuri ninja, personne n'ose les trahir. Le Kara-Tur comptant tr�s peu de demi-humains, seuls les humains sont autoris�s � b�n�ficier des enseignements secrets du Shurikai Ninjutsu.

Avantages :
- +20 % en Furtivit�.
- +2 � la Dext�rit�.
- Obtient les capacit�s sp�ciales du guerrier � haut niveau.
- Bonus de 1 au toucher et aux d�g�ts tous les 4 niveaux (� partir du niveau 4).
- Bonus de 1 � la CA tous les 5 niveaux (� partir du niveau 5).
- Peut se sp�cialiser (deux �toiles) dans le maniement du katana, du cimeterre, des dagues, des fl�chettes et de l'arc court.
- Peut se sp�cialiser (deux �toiles) dans le style de combat d'arme � une main et allouer trois �toiles dans le style de combat � deux armes.

� mesure qu'il augmente de niveau, le shuri ninja acquiert de nouvelles techniques redoutables qui perfectionnent sa science martiale et ses talents d'assassin.
  * Au niveau 5 (ceinture bleue), il gagne la capacit� Vision v�ritable deux fois par jour pour d�tecter les illusions.
  * Au niveau 10 (ceinture violette), il sait frapper les points vitaux de ses adversaires (Coup �tourdissant deux fois par jour). Toutes ses attaques r�ussies au cours du round suivant obligent la victime � r�ussir un jet de sauvegarde contre les sorts sous peine d'�tre assomm�e
  * Au niveau 15 (ceinture rouge), il peut utiliser la capacit� Frappe �clair une fois par jour, tous les 10 niveaux d'exp�rience. Pendant 10 secondes, toutes ses attaques infligent le maximum de d�g�ts.
  * Au niveau 20 (ceinture marron), une fois par jour, il peut utiliser la capacit� Paume vibratoire du moine, dont le secret a �t� vol� dans un monast�re. Sa prochaine attaque r�ussie force sa victime � r�ussir un jet de sauvegarde contre les sorts ou mourir.
  * Au niveau 25 (ceinture noire), il peut enduire son arme de poison une fois par jour (capacit� Arme empoisonn�e).
  * Au niveau 30, il peut prot�ger son esprit de toute attaque mentale une fois par jour (capacit� Ordres chaotiques) et il gagne 20 % suppl�mentaires en Furtivit�.
  * Au niveau 35 (premier dan), il est encore plus fort au combat (bonus de 1 au TAC0) et gagne une utilisation suppl�mentaire de la capacit� Arme empoisonn�e.

ARME EMPOISONN�E :
Chaque coup r�ussi au cours du prochain round empoisonnera la cible. Chaque cible ne peut �tre affect�e qu'une fois par round. Le montant des d�g�ts de poison d�pend du niveau du personnage :
1er : la cible subit 1 point de d�g�t de poison par seconde pendant 6 secondes (annul� par une sauvegarde contre la mort � +1)
5�me : la cible subit 1 point de d�g�t de poison par seconde pendant 12 secondes (annul� par une sauvegarde contre la mort) et subit imm�diatement 2 points de d�g�ts de poison (sans sauvegarde)
9�me : la cible subit 1 point de d�g�t de poison par seconde pendant 18 secondes (annul� par une sauvegarde contre la mort � -1) et subit imm�diatement 4 points de d�g�ts de poison (sans sauvegarde)
13�me : la cible subit 1 point de d�g�t de poison par seconde pendant 24 secondes (annul� par une sauvegarde contre la mort � -2) et subit imm�diatement 6 points de d�g�ts de poison (sans sauvegarde)


D�savantages :
- Ne peut pas poser de pi�ges.
- P�nalit� de 2 points � la Force, � la Constitution et au Charisme.
- Ne peut utiliser que les armes suivantes : katana, cimeterre, dague, fl�chette et arc court.
- Ne peut pas �tre comp�tent dans les styles de combat armes � deux mains et �p�e et bouclier.
- Ne peut pas se jumeler.
- Doit �tre d'alignement chaotique.
- Doit �tre un humain.


Je pense que les deux composants suivants ne n�cessitent pas de description...

20. Profil de Shuri Ninja limit� aux armures de cuir (seulement pour EE)

30. Profil de Shuri Ninja sans armure (seulement pour EE)



Cr�dits et remerciements
========================

- Auteur : Twinblades2 (at twblds@hotmail.com)


- Remerciements

    - Aalkaor pour avoir d�terr� ce mod, l'avoir traduit en fran�ais, commenc� le code WeiDU et initi� l'id�e de le rendre compatible avec les jeux EE.
    - Gwendolyne pour avoir termin� le code WeiDU, l'avoir rendu compatible avec les hjeux EE et avoir relu la traduction.


- Information sur les droits d'auteur

Shuri Ninja n'est pas d�velopp�, support� ni approuv� par BioWare� ou Interplay/Black Isle, Overhaul, Beamdog ou Wizards of the Coast. Il a �t� d�velopp� par Twinblades2, et est bas� sur le jeu Baldur's Gate II et son extension.
Baldur's Gate II : Les Ombres d'Amn et Baldur's Gate II : Tr�ne de Bhaal appartiennent � � TSR, Inc. Le moteur Infinity Engine appartient � � BioWare Corp. Toutes les autres marques et droits d'auteur appartiennent � leurs propri�taires respectifs.

Ce mod a �t� cr�� pour �tre librement appr�ci� par tous les joueurs de Baldur's Gate II. Cependant, il ne doit pas �tre vendu, publi�, compil� ou redistribu� sous une forme quelconque sans le consentement de son auteur.</br>



Historique des versions
=======================

Note du traducteur : l'historique n'est volontairement pas traduit afin de faciliter la mise � jour continue du mod.

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

