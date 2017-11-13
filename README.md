# Les petits chefs

Une adaptation du jeu des Petits Chefs de Thiercelieu faite par l'équipe d'organisation de la conférence AgileFrance 2017, sur l'idée et l'impulsion de Frédéric André.


## Si vous connaissez les Petits Chefs de Thiercelieu

Les règles sont celles des Petits Chefs de Thiercelieu. Seul le vocabulaire est modifié, de la manière définie ci-dessous.

| Petits Chefs  | Petits chefs |
-------------------------------
| Village       | Projet |
| Nuit          | COPIL |
| Petits Chefs  | Petits chefs |
| Maître de jeu | Consultant |
| Équipiers    | Équipier |
| Voyante       | Coach Agile |
| Chasseur      | Manager |
| Capitaine     | Directrice |
| Sorcière      | Product Manager |
| Petite fille  | Secrétaire |
| Cupidon       | Software Craftsmanship Evangelist |
| Amoureux      | Binômes _(font du pair programming)_ |

## Règles

### Mise en place

On fait 3 ou 4 **projets** (de 15 à 20 joueurs) et on alterne des **itérations** / **COPILs** entre deux plats du dîner, chaque **projet** devra avoir un Consultant désigné ou tiré au sort.

Chaque joueur recevra une carte face cachée, qui lui indique son personnage et qui devra rester secrète.


### Personnages

#### Petits chefs

Opposants à l’agilité, ils ou elles se rassemblent en COPIL pour décider entre eux de congédier un ou une équipier·e. Lors des itérations, ils se font passer pour des équipier·e·s afin de ne pas être démasqués.

#### Équipiers

« Simple » équipier : membre de l’équipe, elle ou il n’a aucun super pouvoir particulier si ce n’est d’être convaincu par l’agilité, comme tous les joueurs ils se doivent d’être très attentifs. Lors de chaque COPIL, l’un·e d’entre eux est congédié par la, le ou les Petits chefs. Ce joueur est éliminé du jeu, et ne peut plus participer aux débats. Les équipiers survivants doivent, à la fin de chaque itération, faire quitter le projet à un·e ou un joueurs·e, dans l’espoir qu’il ou elle soit un Petit chef.

#### Coach agile

Lors de chaque COPIL, la ou le Coach Agile fait un test de personnalité d’un joueur de son choix et ainsi découvre sa véritable nature, la ou le Coach Agile doit aider les équipiers, sans être découvert·e par les Petits chefs.

#### Reviewer

Le Reviewer, s’il se fait congédier par les Petits chefs ou renvoyer de l’équipe par les joueurs, a le pouvoir de répliquer en lançant la commande (magique ?) « git blame » sur le ou la joueur·se de son choix avec pour conséquence de le ou la faire sortir immédiatement de l’équipe.

#### Directeur / Directrice

Cette carte est confiée à un des joueurs, en plus de sa carte personnage. La Directrice est élue par vote, à la majorité relative. On ne peut refuser l’honneur d’être Directrice. Dorénavant, les votes de ce joueur comptent pour 2 voix. Si ce joueur se fait éliminer, dans son dernier rapport il désigne son successeur.

#### Product Manager

Elle ou il peut utiliser 2 fois son influence sur l’équipe projet :

- Une fois lors d’un COPIL pour faire rester un joueur limogé par les Petits chefs.
- Une fois lors d’un COPIL pour éliminer un joueur, le faire sortir de l’équipe.

La ou le Product Manager ne peut utiliser son influence qu’une seule fois dans la partie pour chaque action. Elle peut se servir de ses 2 actions lors du même COPIL. Le début de l’itération suivant l’usage de cette influence, il pourra donc y avoir soit 0 départ, 1 départ ou 2 départs. La ou le Product Manager peut utiliser son influence à son profit, et donc se faire rester il ou elle-même (une seule fois).

#### Secrétaire

Elle ou il a le droit, lors d’un COPIL, au moment où les Petits chefs désignent leur victime, de les espionner (en entrouvrant les yeux, etc). S’il ou elle se fait surprendre par un des Petits chefs, il ou elle est limogé immédiatement (en silence), à la place de la victime désignée.

#### Software Craftsmanship Evangelist (et Binômes)

Lors du premier COPIL, il ou elle désigne 2 joueurs qui seront Binôme l’un de l’autre (pair programming). Si l’un d’eux sort de l’équipe, l’autre sort de l’équipe immédiatement par solidarité. Un Équipier et un Petit Chef peuvent être binôme l'un de l'autre. Ils jouent alors contre tous les autres. Si le Binôme survit au projet, alors ce sont eux qui gagnent. Le Software Craftsmanship Evangelist peut se désigner lui-même comme un des 2 membres du Binôme.


### Déroulé

1. Désigner ou tirer au sort un **Consultant**.
2. Le Consultant **distribue** à chacun·e des joueurs 1 carte personnage face cachée, et 1 carte de vote.

#### Première itération

1. C'est le COPIL, le Consultant demande à tous les joueurs de **fermer les yeux**.
2. **Pas encore traduit** _(Premier tour seulement)_ Le Consultant appelle le Voleur, qui se réveille et regarde discrètement les 2 cartes cachées du milieu, puis change éventuellement de personnage. Le Voleur ferme les yeux.
3. _(Premier tour seulement)_ Le Consultant **appelle le Software Craftsmanship Evangelist**, qui se réveille et désigne 2 joueurs (dont éventuellement lui-même). Le Consultant fait le tour de la table et touche discrètement le dos des 2 Binômes. Le Software Craftsmanship Evangelist ferme les yeux.
4. _(Premier tour seulement)_ Le Consultant **appelle les Binômes**, qui se réveillent, se reconnaissent, et referment les yeux.


#### Chaque itération se déroule de la manière suivante

1. Le Consultant **appelle le Coach Agile**, qui se réveille et désigne un joueur à sonder. Le Consultant montre à le Coach Agile la carte du joueur, ou lui mime son identité cachée. Le Coach Agile ferme les yeux.
2. Le Consultant **appelle les Petits Chefs**. Eux (et eux seulement) lèvent la tête, ouvrent les yeux, se concertent silencieusement et désignent une victime. Ils peuvent éventuellement ne pas ouvrir les yeux et ne pas désigner de victime pour réduire le risque de se faire espionner. Si un des Petits Chefs est désigné comme victime par les autres, tant pis pour lui, il quitte le projet !
  - Si aucun Petit Chef n'ouvre les yeux, ils perdent toute crédibilité, et les Équipiers ont donc gagné.
  - Durant ce tour, le **Secrétaire peut espionner** les Petits Chefs (en clignant des yeux, regardant entre ses doigts…), elle n'y est pas obligée, si elle se fait prendre elle est expulsée, à la place de la victime éventellement choisie.
  - Les Petits Chefs referment les yeux.
3. Le Consultant **appelle le Product Manager** et lui montre la victime des Petits Chefs. Il peut sauver l'équipier en le désignant avec le pouce tendu vers le haut, et/ou en expulser un·e autre avec le pouce tendu vers le bas. Le Product Manager n'est **pas obligé** d'user de son pouvoir à un tour spécifique. Le Consultant révélera son effet éventuel au début de l'itération.
4. **L'itération commence**, tout le monde lève la tête et ouvre les yeux. Le Consultant désigne le joueur qui a été victime des Petits Chefs durant la nuit. Ce joueur révèle sa carte et est éliminé du jeu. Quel que soit son personnage, il ne pourra **plus communiquer** avec les autres joueurs sous quelque forme que se soit.
  - Si la victime est le **Manager**, il a le droit de **répliquer** et expulse immédiatement un autre joueur de son choix.
  - Si la victime est un des 2 **Binômes**, l'autre** Binômes est également expulsé·e.
5. Les Équipiers tentent de démasquer un Petit Chef et de faire voter pour son élimination.
  - Les Petits Chefs doivent à force de bluff et mensonges, se faire passer pour des Équipiers.
  - Le Coach Agile ainsi que la Petite fille doivent aider les Équipiers, mais sans mettre trop tôt leur poste en danger en exposant leur identité.
  - Les Binômes doivent se protéger l'un l'autre.
  - En cas d'égalité, le vote de la **Directrice** désigne la victime. En son absence, les joueurs votent à nouveau (y compris les joueurs en cause) pour départager les ex-æquo.
6. Le joueur désigné par la majorité des voix est **expulsé**, il révèle sa carte et ne pourra plus communiquer avec les autres joueurs sous quelque forme que se soit. En cas d'égalité, les joueurs revotent pour départager les ex-æquo.
7. C'est le COPIL, tous les joueurs encore membres du Projet referment les yeux. (Les autres peuvent regarder mais se taisent.)

On recommence avec une nouvelle itération, jusqu'à ce que l'une des conditions de victoire soit remplie.

### Victoire

- Les Équipiers gagnent dès le dernier Petit Chef expulsé, ou si aucun des Petits Chefs n'ouvre les yeux lors du COPIL.
- Les Petits Chefs gagnent dès que l'avant-dernier Équipier est expulsé.
- Le Binôme gagne s'ils sont les seuls membres du projet.


# Licence

Ces instructions sont fournies sous une licence CC-BY-NC-SA « AgileFrance 2017 d'après les Loups-Garous de Thiercelieu », c'est-à-dire que vous avez le droit de les diffuser et de les modifier sous quelque forme que ce soit, dès lors que :

1. Vous en attribuez la source à « AgileFrance 2017 d'après les Loups-Garous de Thiercelieu ».
2. Vous ne monétisez pas cette diffusion.
3. Vous redistribuez vos améliorations à des conditions équivalentes à celles-ci.
