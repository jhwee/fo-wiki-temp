# Player Classes
This page will provide descriptions for playable classes and some tips. The values shown here are defaults and may differ depending on the server's configuration.

**Some important things to remember**:
* Have `special` bound to a key to utilize the class special.
  * e.g. `bind mouse2 "special"` in console.
* If applicable, the class may have a menu for class-specific options. By default, pressing 5 (`impulse 5`) should bring it up. Alternatively, you may bind `menu` for that.
  * e.g. `bind z "menu"` in console.
* You can have custom configurations for each class and have them execute when you respawn.
  * Have class configs in the `/fortress/` directory named after each class, (e.g. `/fortress/soldier.cfg`)
  * Have the following entry in your `autoexec.cfg` file: `setinfo ec on`

## Scout
The Scout is an excellent light attack class due to his speed and maneuverability. Expose enemy spies by touching them and disarm detpacks by standing on top of them. Knock heavy weapon guys off their feet by tossing a concussion grenade towards them.

### Class Specialties
**special**: The Scout can perform a speed hop which can be used to initiate a bunnyhop at 540 speed. You can also use this to break a fall to avoid fall damage.

**class menu**: The scanner can be used to reveal the location of other players and the flag.

| Weapons | Slot | Ammo Type | Clip Size | Max |
| - | - | - | - | - |
| Nailgun | Primary | Nails | - | 200 |
| Shotgun | Secondary | Shells | 8 | 50  |
| Axe | Melee | - | - | - |

| Grenades | Slot | Max | Description |
| - | - | - | - |
| Flash | Primary | 2 | Temporarily blinds enemies within blast radius. |
| Concussion | Secondary | 4 | Concusses and knocks enemies off their feet. |

## Soldier
The Soldier is a medium attack class great to have on both offense and defense. Use cover to destroy a sentry gun with your rockets from a distance or toss a shock grenade at it. Rocket jump off surfaces for a bunny hopping boost.

### Class Specialties
None.

| Weapons | Slot | Ammo Type | Clip Size | Max |
| - | - | - | - | - |
| Rocket Launcher | Primary | Rockets | 4 | 50 |
| Super Shotgun | Secondary | Shells | 16 | 100 |
| Shotgun | Tertiary | Shells | 8 | 100 |
| Axe | Melee | - | - | - |

| Grenades | Slot | Max | Description |
| - | - | - | - |
| Grenade | Primary | 4 | Standard hand grenade. |
| Shock | Secondary | 1 | Releases a small continuous electric shock in a counter-clockwise pattern for 3 seconds. |

## Demoman
The Demoman is an important role for the defensive position. Lay up to 6 pipebombs on or around the flag. Detonate them using `special` before the enemy touches the flag. You can also use the detpack to clear obstacles on some maps.

### Class Specialties
**special**: Detonates the pipebombs (yellow).

**class menu**: The detpack can be used to clear out a large open room of enemies or remove obstacles on certain maps. Set detpacks from 5, 20, 50 to 255 seconds.

| Weapons | Slot | Ammo Type | Clip Size | Max |
| - | - | - | - | - |
| Grenade Launcher | Primary | Rockets | 6 (shared) | 50 |
| Pipebomb Launcher | Secondary | Rockets | 6 (shared) | 50 |
| Shotgun | Tertiary | Shells | 8 | 75 |
| Axe | Melee | - | - | - |

| Grenades | Slot | Max | Description |
| - | - | - | - |
| Grenade | Primary | 4 | Standard hand grenade. |
| MIRV | Secondary | 1 | Explodes into four smaller grenades for extra damage. |

## Medic
The Medic is a key class to have on offense. You can cure status effects on affected teammates, heal them and boost them with health before entering a battle. Use the blast grenade to give yourself a great speed boost for bunnyhopping or knock enemies off their feet.

### Class Specialties
**special**: A healing aura that automatically heals teammates around you.

| Weapons | Slot | Ammo Type | Clip Size | Max |
| - | - | - | - | - |
| Super Nailgun | Primary | Nails | - | 150 |
| Super Shotgun | Secondary | Shells | 16 | 75 |
| Shotgun | Tertiary | Shells | 8 | 75 |
| Bio Axe | Melee | Cells | - | 50 |

| Grenades | Slot | Max | Description |
| - | - | - | - |
| Grenade | Primary | 4 | Standard hand grenade. |
| Blast Grenade | Secondary | 2 | Blasts players away. |

## Heavy Weapons Guy
The Heavy Weapons Guy (hwguy) is great at slowing down and stopping fast enemies. While the assault cannon takes a while and costs 7 cells to spin up, use the class special to keep it spinning. Hold attack and use `special` to toggle between the firing and spinning modes.

### Class Specialties
**special**: Locks the firing mode of the assault cannon to avoid having to spin up again before firing.

| Weapons | Slot | Ammo Type | Clip Size | Max |
| - | - | - | - | - |
| Assault Cannon | Primary | Shells | 100 | 200 |
| Super Shotgun | Secondary | Shells | 16 | 75 |
| Shotgun | Tertiary | Shells | 8 | 75 |
| Axe | Melee | - | - | - |

| Grenades | Slot | Max | Description |
| - | - | - | - |
| Grenade | Primary | 4 | Standard hand grenade. |
| MIRV | Secondary | 1 | Explodes into four smaller grenades for extra damage. |

## Pyro
The Pyro is also another great class to have both on offense and defense. Use the flame thrower to set enemies on fire and knock them back. This will cause them to lose health over time. Use the class special to blast enemies and projectiles back. You can even use it to propel your napalm grenades further.

### Class Specialties
**special**: Releases a small burst of air that blasts enemies and projectiles back. 5 second cooldown.

| Weapons | Slot | Ammo Type | Clip Size | Max |
| - | - | - | - | - |
| Flame Thrower | Primary | Cells | 100 | 200 |
| Incendiary Cannon | Secondary | Rockets | - | 60 |
| Shotgun | Tertiary | Shells | 8 | 40 |
| Axe | Melee | - | - | - |

| Grenades | Slot | Max | Description |
| - | - | - | - |
| Grenade | Primary | 4 | Standard hand grenade. |
| Napalm | Secondary | 1 | Sets a small area on fire for a few seconds, igniting people who walk through it. |

## Spy
The Spy can infiltrate enemy bases while disgused to take out main defenses such as the sentry gun, heavy weapons guy and demoman. Be careful, using your weapon or picking up the flag will reveal your true identity. The tranquilizer will slow down your enemies. Knife your victims in the back for 3x damage.

### Class Specialties
**special**: Feigns death to fool  your enemies of your demise.
  * tip: bind `sfeign` for a silent feign.

**class menu**: Chooses what class to disguise as and setting options for manual color changes.
  
| Weapons | Slot | Ammo Type | Clip Size | Max |
| - | - | - | - | - |
| Tranquilizer | Primary | Shells | - | 40 |
| Super Shotgun | Secondary | Shells | 16 | 40 |
| Nailgun | Tertiary | Nails | - | 100 |
| Knife | Melee | - | - | - |

| Grenades | Slot | Max | Description |
| - | - | - | - |
| Grenade | Primary | 4 | Standard hand grenade. |
| Gas | Secondary | 1 | Causes affected enemies to hallucinate for a short period of time. |

## Engineer
The Engineer and their sentry gun is key to your team's success on defense. Upgrading the sentry gun to level 3 will allow it to fire rockets at enemies. You can only have one built at a time, so positioning is important. You can also build a dispenser which can be used by teammates to replenish ammo and armor. The dispenser also can be detonated (special) to cause fatal damage to those around it.

### Class Specialties
**special**: Detonates the dispenser. Rockets and cells will give the most blast damage from a detonated dispenser.

**class menu**: Brings up the build menu. Choose from Sentry gun (costs 130 cells) or Dispenser (costs 100 cells).
* Hitting the sentry gun with your spanner _after it is completely built_ will upgrade it and give you options to rotate it. Striking the gun _while it is building_ will cancel the build and refund cells.
* Hitting the dispenser wiith your spanner will allow you to deposit ammo or armor.

| Weapons | Slot | Ammo Type | Clip Size | Max |
| - | - | - | - | - |
| Railgun | Primary | Nails | - | 50 |
| Super Shotgun | Secondary | Shells | 16 | 50 |
| Spanner | Melee | - | - | - |

| Grenades | Slot | Max | Description |
| - | - | - | - |
| Grenade | Primary | 4 | Standard hand grenade. |
| EMP | Secondary | 2 | Detonates anything explosive around the blast radius. |