# resource-pack-galith

## Installation

- Télécharger les fichiers au format .zip
- Installer le [Datapack Racks](https://www.planetminecraft.com/data-pack/tool-rack-hang-your-tools-and-weapons/) pour une meilleur expérience

## Blocs

### Fût de bière

![fut de bière](./assets/minecraft/textures/block/barrel_side.png)

Remplace le tonneau

### Orge

![orge](./assets/minecraft/textures/block/beetroots_stage3.png)

Remplace les betteraves

### Stand d'alchimie

Remplace le skin de l'alambic

## items

⚠️**With EssentialX**, il faut préfixer la commande de give de la manière suivante : 

```
/minecraft:give ...
```

### Pièce d'or

![po](./assets/minecraft/textures/item/po.png)

```
/give @s minecraft:raw_gold{CustomModelData:7500,display:{Name:"{\"text\":\"Pièce d'or\",\"italic\":\"false\"}"}}
```

### Pièce d'argent

![pa](./assets/minecraft/textures/item/pa.png)

```
/give @s minecraft:raw_iron{CustomModelData:7501,display:{Name:"{\"text\":\"Pièce d'argent\",\"italic\":\"false\"}"}}
```

### Pièce de bronze

![pb](./assets/minecraft/textures/item/pb.png)

```
/give @s minecraft:raw_copper{CustomModelData:7502,display:{Name:"{\"text\":\"Pièce de bronze\",\"italic\":\"false\"}"}}
```

### Bière

![bière](./assets/minecraft/textures/item/honey_bottle.png)

```
/give @s minecraft:honey_bottle{CustomModelData:7503,display:{Name:"{\"text\":\"Bière\",\"italic\":\"false\"}"}}
```

### Rack

⚠️ Les racks proviennent du [Datapack Racks](https://www.planetminecraft.com/data-pack/tool-rack-hang-your-tools-and-weapons/) 

```
/function pk_racks:cmd/give/oak
```