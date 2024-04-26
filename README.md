# Kernel Level Anti-Cheat

## Cheating Overview

![Pacman](/Assets/pacman.png)

Cheating in video games started in the 1970's during the arcade gaming era in games like "Pac-Man" or "Space Invaders" with players discovering secret sequences of buttons presses or joystick movement to gain advantages in their games. 

![Cheat-Codes](/Assets/cheat-codes.jpg)

Cheating remained in the realm of single player games and therefore was not really problematic until the 2000's when online multiplayer games like Counter-Strike emerged. Cheaters started using more and more sophisticated cheats like ESP/Wallhacks, aimbots, etc ... 

![Counter-Strike](/Assets/counter-strike.jpg)

Today, the cheating problem became even more prevalent than before with gaming becoming mainstream and the fact that cheating created its own sub-economy. It has become lucrative for cheaters to cheat as they are able to sell their services like boosting, currency selling or even streaming their games. 

## Anti-Cheating Overview

### What does it mean to have kernel access ? 

In computing, a kernel is the core component of an operating system. It manages system resources, such as the CPU, memory, and peripheral devices, and provides essential services to higher-level software. It acts as a bridge between application software and the hardware of a computer.

![Kernel](/Assets/kernel.png)

![Ring Levels](/Assets/ring-level.png)

In computing, a kernel is the core component of an operating system. It manages system resources, such as the CPU, memory, and peripheral devices, and provides essential services to higher-level software. It acts as a bridge between application software and the hardware of a computer.

Kernel main purposes: 

- Provides the interfaces needed for users and applications to interact with the computer
- Launches and manage applications
- Manage the underlying system hardware devices

Kernel level access for anticheat purposes: 

- Monitor system level activities and processes
- Detection of unauthorized modifications, game files, code injection, ...
- Faster detection and and response to cheating behaviors

### Is it really a problem ? 

You don't need kernel access to steal data. Usually companies are not the problem, they use their anticheat in good faith.

![ESEA](/Assets/esea.png)

An ESEA employee was caught mining bitcoin on their customers' machines.

https://www.theverge.com/2013/5/2/4292672/esea-gaming-network-bitcoin-botnet

![Street Fighter 5](/Assets/street-fighter.png)

A Street Fighter 5 update installed an hidden rootkit that allowed any software to access the kernel.

https://www.theregister.com/2016/09/23/capcom_street_fighter_v/

### Who are those anti-cheat companies ?

#### Vanguard - Tencent - Chinese

![Vanguard](/Assets/vanguard.jpg)

![Easy](/Assets/easy.jpg)

#### Faceit - ESL - Saudi Arabia

![Faceit](/Assets/faceit.jpg)

![ESL](/Assets/esl.png)

#### Putin wants to make russian competitors for the Playstation and Xbox

![Putin](/Assets/putin.png)

https://kotaku.com/putin-russia-consoles-playstation-xbox-1851388516
### Are you okay with this ? 

Even with no ill intent, are you okay with companies potentially having such a deep access to your machine ? 
Most anti-cheats software even run when you are not playing your games.

## How do cheaters bypass kernel level anti-cheats ? 

![DMA](/Assets/dma.png)

- DMA Cheats
- Kernel Drivers
- EFI Cheating
- AHK Scripting / Pixel Bots
- Hardware pixel bots 

## Is AI anti-cheat the future of anti-cheats ? 

![Waldo](/Assets/waldo.png)

![Anybrain](/Assets/anybrain.png)

![Valve](/Assets/valve.jpg)

## Cool references 

https://waldo.vision/
https://anybrain.gg/
https://www.youtube.com/watch?v=RwzIq04vd0M
https://github.com/SamuelTulach/efi-memory
https://julienkinsi.medium.com/the-art-of-valorant-anti-cheating-6769165ae93f
https://www.leagueoflegends.com/en-us/news/dev/dev-vanguard-x-lol/