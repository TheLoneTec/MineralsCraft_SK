MineralsCraft\_SK: A rimworld mod for the [Hardcore SK project](https://github.com/skyarkhangel/Hardcore-SK)
------------------------------------------------------------------------------------------------------------

![](About/Preview.jpg)

This mod is an extension of
[Minerals\_SK](https://github.com/zachary-foster/Minerals_SK) and must
come after it in the load order. It adds way to use minerals for
crafting and adds a few new resource minerals.

New Resource minerals
---------------------

These are randomly spawned when a map is created and are never respawned
in a given map.

### Obsidian

A volcanic glass formed when lava cools quickly at the surface. Valued
by the tribal inhabitants of this rimworld for making knifes, handaxes,
and arrowheads. Razor-shape edges make this very difficult to climb
over.

**defName:** Obsidian

**Beauty:** 10

![](Textures/Things/Mineral/Obsidian/ObsidianA.png)
![](Textures/Things/Mineral/Obsidian/ObsidianB.png)
![](Textures/Things/Mineral/Obsidian/ObsidianC.png)
![](Textures/Things/Mineral/Obsidian/ObsidianD.png)

![](readme_images/Obsidian.jpg)

### Flint Nodule

Formations of microcrystalline silicon dioxide found in sedimentary
rocks. Valued by the tribal inhabitants of this rimworld for making
knifes, handaxes, and arrowheads.

**defName:** FlintNodule

**Beauty:** 1

![](Textures/Things/Mineral/FlintNodule/FlintNoduleA.png)
![](Textures/Things/Mineral/FlintNodule/FlintNoduleB.png)
![](Textures/Things/Mineral/FlintNodule/FlintNoduleC.png)
![](Textures/Things/Mineral/FlintNodule/FlintNoduleD.png)

### Adamant

Adamant is a mysterious and incredibly hard stone. Little is known about
the origins of this rare rock and the best glitterworld minerologists
have not found a way to explain its formation. Some speculate that the
nodes of adamant scattered around this solar system are the remnants of
planetary-scale alien structures that were destroyed around the time
this solar system begin forming. Adamant is difficult to mine and craft
with, but can be used to make very strong walls, beautiful floors, and
deadly arrows. However, it is also rare and valuable, so possession of
even a little adamant can attract significant interest.

Cutting gems
------------

Some gem-quality crystals can be found when mining some minerals. These
can be cut into gems to be used for some crafting recipes or sold to
traders. Gems are particularly light and valuable, making them excellent
for trading and attracting raiders.

Fire starting
-------------

Steel, kindling, fabirc, and a sharp stone like obsidian or flint can be
used to make a fire starting kit that can be used to start fires
anywhere.

Neolithic crafting
------------------

Flint and obsidian can be used to make "tribal" tools like knives and
handaxes. They have decent armor penetration, but are very brittle, so
tools will get destroyed often when used for self defense. Flint and
obsidian arrows are much better than standard stone arrows against
unarmored foes. Adamant can also be used to make arrows that have much
higher armor penetration.

![](readme_images/NeolithicCrafting.jpg)

Medieval crafting
-----------------

Precious metals and cut gems can be used to powerful royal weapons like
knives, swords, and battleaxes. These are stronger than their unjewled
analogs and provide a small social and mental break boost, but they are
heavy, expensive, and difficult to craft.

Installation
------------

You can download the current development version by clicking the green
"clone or download" button near the top of this page. You can also
download specific "stable" releases
[here](https://github.com/zachary-foster/MineralsCraft_SK/releases),
although they will probably not be updated too often. Once you have
downloaded the mod, uncompress the file and up the folder in the `Mods`
folder of you rimworld installation.

To xml modders and potential contributers:
------------------------------------------

This mod is set up so that new minerals, both static and dynamic, can be
added and configured using only XML changes. Adding:

    <ThingDef ParentName="StaticMineralBase">
            <defName>MyNewMineral</defName>
        ...
    </ThingDef>

or

    <ThingDef ParentName="DynamicMineralBase">
            <defName>MyNewMineral</defName>
        ...
    </ThingDef>

to an XML file in `Defs/ThingDefs_Minerals` will cause a new mineral to
be added to the game.

To add a mineral:

-   Copy the `ThingDef` for an existing mineral that is most similar to
    the one you want to make. Modify the XML how you want and add it to
    an XML file in `Defs/ThingDefs_Minerals`. Make sure to change the
    `defName`.
-   Create textures for the new mineral and add to them to
    `Textures/Things/Mineral` in the same format as the others there.
-   If you want to have you changes added to this mod for others to use,
    consider [forking](https://help.github.com/articles/fork-a-repo/)
    this repository and submitting a [pull
    request](https://help.github.com/articles/about-pull-requests/). I
    welcome contributions!

Image sources used
------------------

I based some of the textures off of images with licenses for
non-commercial reuse. Here are the list of images used:

-   Rob Lavinsky, iRocks.com – CC-BY-SA-3.0
    [link](https://commons.wikimedia.org/wiki/File:Elbaite-Quartz-Albite-164061.jpg)
-   Rob Lavinsky, iRocks.com – CC-BY-SA-3.0
    [link](https://commons.wikimedia.org/wiki/File:Elbaite-Lepidolite-Quartz-gem7-x1c.jpg)
-   Didier Descouens – GNU 1.2
    [link](https://commons.wikimedia.org/wiki/File:Selpologne.jpg)
-   Piotr Sosnowski – GNU 1.2
    [link](https://commons.wikimedia.org/wiki/File:Halite-crystals2.jpg)
-   Tjflex2 of flickr - CC-BY-SA-3.0
    [link](https://www.flickr.com/photos/tjflex/358359211)
-   <https://www.maxpixel.net/Crystal-Jewelry-Clear-Quartz-Value-2187139>
-   <https://www.flickr.com/photos/31856336@N03/3108675089>
-   <https://commons.wikimedia.org/wiki/File:Sapphire_Gem.jpg>
-   <https://commons.wikimedia.org/wiki/File:Cornflower_blue_Yogo_sapphire.jpg>
-   <https://commons.wikimedia.org/wiki/File:Black_obsidian.JPG>
-   <https://commons.wikimedia.org/wiki/File:Different_rocks_at_Panum_Crater.jpg>
-   <https://pixabay.com/en/obsidian-stone-volcanic-rocks-glass-505333/>
-   <https://www.flickr.com/photos/jsjgeology/36696371493>
-   <https://commons.wikimedia.org/wiki/File:Egyptian_flint_knives,_predynastic._Wellcome_M0016545EB.jpg>
-   <https://commons.wikimedia.org/wiki/File:Native_tribes_of_South-East_Australia_Fig_14_-_Stone_axe.jpg>
-   <https://github.com/Rikiki123456789/Rimworld/tree/ab7930661284c19e5dc4b9b01f2499bd88116378/CaveBiome/CaveBiome>
-   <https://commons.wikimedia.org/wiki/File:Pyrite-Tetrahedrite-Quartz-184642.jpg>
-   <https://commons.wikimedia.org/wiki/File:Pyrite-258273.jpg>
-   <https://commons.wikimedia.org/wiki/File:2780M-pyrite1.jpg>
-   <https://it.wikipedia.org/wiki/File:Una_mazza_Maquahuitl.jpg>
-   <https://commons.wikimedia.org/wiki/File:Elbaite-Lepidolite-Quartz-gem7-x1a.jpg>
-   <https://www.flickr.com/photos/jsjgeology/31997092221>
-   <https://commons.wikimedia.org/wiki/File:Schorl-181669.jpg>
-   <https://commons.wikimedia.org/wiki/File:Quartz-Schorl-k-142a.jpg>
-   <https://www.flickr.com/photos/orbitaljoe/5030069066>
-   <https://commons.wikimedia.org/wiki/File:Tourmaline-164039.jpg>
-   <https://commons.wikimedia.org/wiki/File:Tourmaline-34580.jpg>
-   <https://commons.wikimedia.org/wiki/File:Elbaite-Lepidolite-Quartz-gem7-x1a.jpg>
-   <https://commons.wikimedia.org/wiki/File:Sulfur-es67a.jpg>
-   <https://commons.wikimedia.org/wiki/File:Sulfur-20edd1ea.jpg>
-   <https://fr.m.wikipedia.org/wiki/Fichier:Sulfur_(16_S).jpg>
-   <https://www.flickr.com/photos/jsjgeology/17541066095>
-   <https://commons.wikimedia.org/wiki/File:Corundum-275089.jpg>
-   <https://commons.wikimedia.org/wiki/File:Corundum-215245.jpg>
-   <https://commons.wikimedia.org/wiki/File:Corundum-tmix07-151a.jpg>
-   <https://commons.wikimedia.org/wiki/File:Corundum-190228.jpg>
-   <https://commons.wikimedia.org/wiki/File:Corundum-119783.jpg>
-   <https://commons.wikimedia.org/wiki/File:Beryl-Quartz-Emerald-Zambia-85mm_0872.jpg>
-   <https://commons.wikimedia.org/wiki/File:Gachala_Emerald_3526711557_849c4c7367.jpg>
-   <https://commons.wikimedia.org/wiki/File:Diamant_sur_kimberlite_(R%C3%A9publique_d%27Afrique_du_Sud).JPG>
-   <https://commons.wikimedia.org/wiki/File:Diamond-21988.jpg>
-   <https://commons.wikimedia.org/wiki/File:Diamond-dimd5b.jpg>  
-   <https://www.flickr.com/photos/jsjgeology/17440851983>
-   <https://commons.wikimedia.org/wiki/File:Diamond-dimd5a.jpg>
-   <https://vi.wikipedia.org/wiki/T%E1%BA%ADp_tin:Pitchblende_schlema-alberoda.JPG>
-   <https://www.flickr.com/photos/jahansell/5379933134>
-   <http://www.geograph.ie/photo/4763916> © Copyright Eric Jones and
    licensed for reuse under this Creative Commons Licence.
-   <https://www.flickr.com/photos/jsjgeology/29921127566>
    CopyrightJames St. John
-   <https://www.flickr.com/photos/brewbooks/757551002/in/photostream/>
    Copyright brewbooks
-   <https://www.flickr.com/photos/98425334@N00/130957324/>
-   <https://commons.wikimedia.org/wiki/File:River_side_pebbles_and_rocks.jpg>
    Shashank ghosh
-   <https://commons.wikimedia.org/wiki/File:Box,_gift_(AM_1963.90-2).jpg>
