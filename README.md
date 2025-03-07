## Framework
This system was designed with the intention to move towards a more standalone / generic structure so it can be integrated into any framework. As of now, it will work without any alterations if you are using the latest updates to [ox_core](https://github.com/overextended/ox_core), and [es_extended](https://github.com/esx-framework/esx-legacy).

[Small Preview Video](https://gyazo.com/9aec4a41a5d4b13798f8e8917dd20383)

## Dependencies
### [ox_lib](https://github.com/overextended/ox_lib) *(v2.5.2 or higher)*

Used for all UI elements (i.e. notifications, progress circle, input), cache, and state bag.

### [ox_inventory](https://github.com/overextended/ox_inventory)

Used for deducting money to receive treatment, and purchasing bandages.

## Features
- Treatment:
	- Simple system located at a hospital of your choice, to recover from *any* damages you may have.
	- Customizable options through *ox_lib* context to choose how you would like to receive "treatment".
	- Medicated effect upon finishing treatment, this is for a more "realistic" experience.
	- Toggle hospital treatment system on / off to allow / deny receiving treatment with a simple command.
	- Customizable NPC location / map blip for your desired hospital location.
	- Flexible customization for all treatment notifications, and treatment progress bar.

- Damages:
	- Damaged walk effect when player health reaches a certain point.
	- Once point is hit, health decreases with visual effects.
	- Knockout ragdoll effect when player health hits a certain point in hand-to-hand combat.
	- Flexible customization for all damage notifications.
	- Configurable anti-spam jump, if people choose to run away from combat. *(Why not?)* 😎

<br><div><h4 align='center'><a href='https://discord.gg/nTNup3teBT'>Discord Server</a></h4></div><br>
