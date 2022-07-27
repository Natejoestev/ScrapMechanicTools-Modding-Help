---
sidebar_position: 5
title: Audio Events
hide_title: true
sidebar-label: 'Audio Events'
---

### Audio Events

Below is a JSON array that contains all available audio event paths, their parameters and min/max values.

These event paths can, for example, be used in an audio effect to play a sound in-game. <br></br>

A mod that makes use of these events can be found [here](https://steamcommunity.com/sharedfiles/filedetails/?id=2832061929). <br></br>
You can look through this mod's files to see how to use these event paths to play sounds.

```json
{
	"event:/amb/2D/amb_2D_cave": {
		"Parameters": {
			"distancetocave": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/2D/amb_2D_field_day_night": {
		"Parameters": {
			"amb_day_night": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"fadeoutambience": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"height": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"wind": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/2D/amb_2D_warehouse": {},
	"event:/amb/2D/amb_2D_water": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/2D/downedship_int": {
		"Parameters": {
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/2D/underwater": {},
	"event:/amb/3D/amb_3D_crashsitefire": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			},
			"fire_intensity": {
				"default": 1.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/amb_3D_crashsitefire_metalcreak": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"fire_intensity": {
				"default": 1.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/amb_3D_crashsitefire_small": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"fire_intensity": {
				"default": 1.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/amb_3D_elevator": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/amb_3D_tree": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/birds/amb_3D_birds_blackbird": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/birds/amb_3D_birds_raven": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/birds/amb_3D_birds_smallbird": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/bubbles": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/downedship_ext": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/electric_spark": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/electric_spark_randomloop": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/fire_extinguish": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/oilgeyser_loop": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/water_leak": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/3D/water_splash": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/birds": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 4": {
				"default": 0.0,
				"maximum": 150.0,
				"minimum": 0.0
			}
		}
	},
	"event:/amb/challenge": {},
	"event:/amb/field": {
		"Parameters": {
			"wind": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/consumtion/eat_generic": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/consumtion/eat_sandwich": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/consumtion/swallow": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/crouch": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/footstep": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/footstep_crouching": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/getup": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/health/burn": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"char": {
				"default": 1.0,
				"maximum": 10.0,
				"minimum": 0.0
			},
			"damage": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/health/death": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"char": {
				"default": 1.0,
				"maximum": 10.0,
				"minimum": 0.0
			},
			"damage": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/health/exhausted": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"char": {
				"default": 1.0,
				"maximum": 10.0,
				"minimum": 0.0
			},
			"damage": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/health/hurt_drown": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"char": {
				"default": 1.0,
				"maximum": 10.0,
				"minimum": 0.0
			},
			"damage": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/health/hurt_hunger": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"char": {
				"default": 1.0,
				"maximum": 10.0,
				"minimum": 0.0
			},
			"damage": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/health/impact": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"char": {
				"default": 1.0,
				"maximum": 10.0,
				"minimum": 0.0
			},
			"damage": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/health/ko": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/health/lowair": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"char": {
				"default": 1.0,
				"maximum": 10.0,
				"minimum": 0.0
			},
			"damage": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/health/lowfood": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"char": {
				"default": 1.0,
				"maximum": 10.0,
				"minimum": 0.0
			},
			"damage": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/health/poison": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"char": {
				"default": 1.0,
				"maximum": 10.0,
				"minimum": 0.0
			},
			"damage": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/health/shock": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"char": {
				"default": 1.0,
				"maximum": 10.0,
				"minimum": 0.0
			},
			"damage": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/jump": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/land": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/movement/water/swim_backwards": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/movement/water/swim_forwards": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/animals/glowgorp/eat": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/animals/glowgorp/footstep": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/animals/glowgorp/hit": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/animals/glowgorp/idle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/animals/glowgorp/jump": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/animals/glowgorp/pickup": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/confettibot": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_attack_02": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_attack_03": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_attack_04": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_explode": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_explode_buildup": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_ff_heavy": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_ff_light": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_ff_mid": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_move_body_alert_idle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_move_body_heavy": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_move_body_light": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_move_head": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_move_legs": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_move_scythe": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_noticeplayer": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_shoot": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_takedamage": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_voice_alert_idle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_voice_idle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_voice_roaming": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_voice_run": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/farmbot_voice_sprint": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/loops/farmbot_voice_alert_idle_loop": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/loops/farmbot_voice_idle_loop": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/loops/farmbot_voice_roaming_loop": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/farmbot/loops/farmbot_voice_sprint_loop": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_attack_01": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_attack_02": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_attack_03": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_attack_sprint": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_explode": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_ff": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_foley_forkimpact": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_foley_metal": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_foley_servo": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_idle_special_long": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_idle_special_short": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_noticeplayer": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_takedamage": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_walk_chaseplayer": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/haybot/haybot_walk_chaseplayer_loop": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/tapebot/tapebot_explode": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/tapebot/tapebot_ff": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			},
			"tapebot_ff_intensity": {
				"default": 0.0,
				"maximum": 3.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/tapebot/tapebot_foley_gunrattle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"tapebot_ff_intensity": {
				"default": 0.0,
				"maximum": 3.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/tapebot/tapebot_foley_scissor": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"tapebot_ff_intensity": {
				"default": 0.0,
				"maximum": 3.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/tapebot/tapebot_foley_servo": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"tapebot_ff_intensity": {
				"default": 0.0,
				"maximum": 3.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/tapebot/tapebot_noticeplayer": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/tapebot/tapebot_shoot": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/tapebot/tapebot_shoot_projectile": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/tapebot/tapebot_takedamage": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/tapebot/tapebot_walk_aggro": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/tapebot/tapebot_walk_chaseplayer": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/totebot/totebot_attack": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"totebot_color": {
				"default": 0.0,
				"maximum": 5.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/totebot/totebot_explode": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"totebot_color": {
				"default": 0.0,
				"maximum": 5.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/totebot/totebot_ff": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/totebot/totebot_foley_servo": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/totebot/totebot_noticeplayer": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"totebot_color": {
				"default": 0.0,
				"maximum": 5.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/totebot/totebot_takedamage": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"totebot_color": {
				"default": 0.0,
				"maximum": 5.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/totebot/totebot_walk_chaseplayer": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"totebot_color": {
				"default": 0.0,
				"maximum": 5.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/enemies/totebot/totebot_walk_chaseplayer_loop": {
		"Parameters": {
			"totebot_color": {
				"default": 0.0,
				"maximum": 5.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/observerbot_move": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/observerbot_write": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/cookbot/cob_craft": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"craftbot": {
				"default": 1.0,
				"maximum": 3.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/cookbot/cob_craft_finished": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/cookbot/cob_craft_start": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/cookbot/cob_craft_startloopfinished": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"craftbot": {
				"default": 1.0,
				"maximum": 3.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/cookbot/cob_idle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/cookbot/cob_idle_special01": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/cookbot/cob_idle_special02": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/cookbot/cob_unpack": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/craftinbot/cb_craft": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"craftbot": {
				"default": 1.0,
				"maximum": 3.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/craftinbot/cb_craft_finished": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/craftinbot/cb_craft_start": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/craftinbot/cb_craft_startloopfinished": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"craftbot": {
				"default": 1.0,
				"maximum": 3.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/craftinbot/cb_idle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/craftinbot/cb_idle_special01": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/craftinbot/cb_idle_special02": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/craftinbot/cb_small_craft": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/craftinbot/cb_small_idle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/craftinbot/cb_unpack": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/dressbot/db_craft": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"craftbot": {
				"default": 1.0,
				"maximum": 3.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/dressbot/db_craft_finished": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/dressbot/db_craft_start": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/dressbot/db_craft_startloopfinished": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"dressbot": {
				"default": 1.0,
				"maximum": 2.0,
				"minimum": 1.0
			}
		}
	},
	"event:/char/npc/bots/utility/dressbot/db_door_close": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/dressbot/db_door_open": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/dressbot/db_idle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/dressbot/db_unpack": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/refinery/refinery_unpack": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/refinery/refinery_use": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/refinery/refinery_use_end": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/bots/utility/refinery/refinery_use_start": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/human/farmer/farmer_male_old/bored": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/human/farmer/farmer_male_old/bye": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			}
		}
	},
	"event:/char/npc/human/farmer/farmer_male_old/cage_struggle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/human/farmer/farmer_male_old/greet": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			}
		}
	},
	"event:/char/npc/human/farmer/farmer_male_old/help": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/human/farmer/farmer_male_old/rolling": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"dummy": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/human/farmer/farmer_male_old/thanks": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/supervisor/monitor_bravo": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/supervisor/monitor_generic": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/supervisor/monitor_next": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/woc/woc_chewing": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/woc/woc_confetti": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/woc/woc_ff_run": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/woc/woc_ff_walk": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"surface": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/woc/woc_moo_idle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/woc/woc_moo_panic": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/npc/woc/woc_moo_ragdoll": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/char/wind": {
		"Parameters": {
			"velocity": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/collapse/beehive": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/collapse/clam": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/collapse/corn": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/collapse/fence": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/collapse/oilgeyser": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/collapse/plant": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/collapse/stone": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/collapse/tree_burnt": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/dust_rocket": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"ground_distance": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"material": {
				"default": 0.0,
				"maximum": 30.0,
				"minimum": 0.0
			},
			"power": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/impact_debris": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"material": {
				"default": 0.0,
				"maximum": 30.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/impact_multiple": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 4": {
				"default": 0.0,
				"maximum": 150.0,
				"minimum": 0.0
			},
			"material": {
				"default": 0.0,
				"maximum": 15.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/impact_rolling": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"material": {
				"default": 0.0,
				"maximum": 30.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/impact_single": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"material": {
				"default": 0.0,
				"maximum": 30.0,
				"minimum": 0.0
			},
			"phys_energy": {
				"default": 470.0,
				"maximum": 500.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/impact_sliding": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Distance 4": {
				"default": 0.0,
				"maximum": 150.0,
				"minimum": 0.0
			},
			"material": {
				"default": 1.0,
				"maximum": 20.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/impact_vehicle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Distance 4": {
				"default": 0.0,
				"maximum": 150.0,
				"minimum": 0.0
			},
			"material": {
				"default": 0.0,
				"maximum": 10.0,
				"minimum": 0.0
			},
			"parts": {
				"default": 0.0,
				"maximum": 20.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/impact_weapon": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"material": {
				"default": 0.0,
				"maximum": 30.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/coll/stress/stone": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/music/combat": {
		"Parameters": {
			"music": {
				"default": 0.0,
				"maximum": 10.0,
				"minimum": 0.0
			}
		}
	},
	"event:/music/creative": {},
	"event:/music/elevator": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			}
		}
	},
	"event:/music/environment": {
		"Parameters": {
			"music": {
				"default": 0.0,
				"maximum": 10.0,
				"minimum": 0.0
			}
		}
	},
	"event:/music/menu": {},
	"event:/music/robotheads/dance/dancebass": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			},
			"Event Orientation": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"pitch": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/music/robotheads/dance/dancedrum": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			},
			"Event Orientation": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"pitch": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/music/robotheads/dance/dancelead": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			},
			"Event Orientation": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"pitch": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/music/robotheads/dance/dancepad": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			},
			"Event Orientation": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"pitch": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/music/robotheads/piano": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			},
			"Event Orientation": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"pitch": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/music/robotheads/retrobass": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			},
			"Event Orientation": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"pitch": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/music/robotheads/retrodrum": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			},
			"Event Orientation": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"pitch": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/music/robotheads/retrofmblip": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			},
			"Event Orientation": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"pitch": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/music/robotheads/retrovoice": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			},
			"Event Orientation": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"pitch": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/music/robotheads/retrowildblip": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			},
			"Event Orientation": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"pitch": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/beehive": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/bot_unbox": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/bot_unbox_big": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/can_drink": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/can_open": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/challengeball_rolling": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/challengeball_slot": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/challengeball_spawn": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/challengecrowd_jump": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/downedship_poweron": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/elevator/elevator_button": {},
	"event:/props/installations/elevator/elevator_ding": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/elevator/elevator_keycard_use": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/elevator/elevator_move_outside": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/elevator/elevator_move_stereo": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			}
		}
	},
	"event:/props/installations/elevator/elevatordoor_close": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/elevator/elevatordoor_open": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/farmerhideout/hideout_close": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/farmerhideout/hideout_open": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/farmerhideout/hideout_vacuum": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/mechanicstation/ms_craft": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/mechanicstation/ms_open": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/packingstation/ps_load": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/packingstation/ps_pack": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/packingstation/ps_roller": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/packingstation/ps_throw": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/installations/powercore_insert": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/logs_appear": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/logs_smash": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/lootcrate_smash": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/mapinspector/mi_off": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/mapinspector/mi_on": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/plants/plant_finished": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/plants/plant_seed": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/sharktrophy": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/tree_creak": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"tree_creaking": {
				"default": 1.0,
				"maximum": 4.0,
				"minimum": 1.0
			}
		}
	},
	"event:/props/tree_fall": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"velocity_tree": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/tree_impact_ground": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/props/tree_impact_leafrattle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"velocity_max_50": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/alarmclock": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			},
			"alarm": {
				"default": 1.0,
				"maximum": 10.0,
				"minimum": 1.0
			}
		}
	},
	"event:/tools/builderguide/activate": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/builderguide/complete": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/builderguide/deactivate": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/builderguide/finish_section": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/builderguide/loop": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/connectiontool/connectiontool_direction": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/connectiontool/connectiontool_equip": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/connectiontool/connectiontool_fire": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/connectiontool/connectiontool_idle": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/connectiontool/connectiontool_putdown": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/connectiontool/connectiontool_rotate": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/crowbar": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/drill": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/fertilizer": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/glowstick/gs_bounce": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/glowstick/gs_flying": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/glowstick/gs_open": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/glowstick/gs_pool": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/glowstick/gs_throw": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/handbook/handbook_close": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/handbook/handbook_open": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/handbook/handbook_pickup": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/handbook/handbook_putdown": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/handbook/handbook_turnpage": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/lift_pickup": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/lift_place": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/lift_use": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"height": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"stretch": {
				"default": 1.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/logbook/close": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/logbook/open": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/multitool_refine": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"material": {
				"default": 0.0,
				"maximum": 30.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/painttool/pt_colourabort": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/painttool/pt_colourmenu": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/painttool/pt_colourpick": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/painttool/pt_equip": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/painttool/pt_erase": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/painttool/pt_paint": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/painttool/pt_putdown": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/painttool/pt_reload": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/radio": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/saw_material_old": {
		"Parameters": {
			"saw_material": {
				"default": 0.9999999403953552,
				"maximum": 16.0,
				"minimum": 0.0
			},
			"saw_material_off_on": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/sledgehammer_pickup": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/sledgehammer_putdown": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/sledgehammer_swing": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/vacuum/vacuum_blowout": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/vacuum/vacuum_suction": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/waterbucket_fill": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/waterbucket_throw": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/weldtool/wt_bearing": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"weld=1": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/weldtool/wt_equip": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/weldtool/wt_error": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/weldtool/wt_object": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"weld=1": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/weldtool/wt_putdown": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/weldtool/wt_sparks": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/tools/weldtool/wt_weld": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/attach": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/attach_default": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 3": {
				"default": 0.0,
				"maximum": 65.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/blueprint/bp_build": {},
	"event:/ui/blueprint/bp_camera": {
		"Parameters": {
			"Distance 3": {
				"default": 0.0,
				"maximum": 65.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/blueprint/bp_close": {},
	"event:/ui/blueprint/bp_delete": {},
	"event:/ui/blueprint/bp_open": {},
	"event:/ui/blueprint/bp_save": {},
	"event:/ui/blueprint/bp_share": {},
	"event:/ui/challenge/chall_activation": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/challenge/chall_fall": {
		"Parameters": {
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/challenge/chall_start": {
		"Parameters": {
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/challenge/complete": {},
	"event:/ui/challenge/complete_collect": {},
	"event:/ui/click": {},
	"event:/ui/detach_default": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 3": {
				"default": 0.0,
				"maximum": 65.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/drag": {},
	"event:/ui/drop": {},
	"event:/ui/enlarge": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 3": {
				"default": 0.0,
				"maximum": 65.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/equip_clothes": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/error": {},
	"event:/ui/garment_unbox": {},
	"event:/ui/health_restored": {},
	"event:/ui/highlight": {},
	"event:/ui/inventory_close_old": {},
	"event:/ui/inventory_select_old": {},
	"event:/ui/item_collect": {},
	"event:/ui/item_pickup": {},
	"event:/ui/item_projectile": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/item_spawn": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/logbook_entry": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/logbook_entryactivate": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/menu_change_screen": {},
	"event:/ui/menu_close": {},
	"event:/ui/menu_open": {},
	"event:/ui/notification": {},
	"event:/ui/openclose/backpack_close": {},
	"event:/ui/openclose/backpack_open": {},
	"event:/ui/openclose/chest_close": {},
	"event:/ui/openclose/chest_open": {},
	"event:/ui/paus": {},
	"event:/ui/reduce": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/rotate": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 3": {
				"default": 0.0,
				"maximum": 65.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/scroll": {
		"Parameters": {
			"height": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/steering_attach": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/steering_select": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/ui/upgrade_part": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/beacon": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/brake": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			},
			"strength": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/controller": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"level": {
				"default": 5.0,
				"maximum": 5.0,
				"minimum": 0.0
			},
			"load": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/drill": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"impact": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/elengines/elengine01": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"load": {
				"default": 0.5,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"rpm": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/elengines/elengine02": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"load": {
				"default": 0.5,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"rpm": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/elengines/elengine03": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"load": {
				"default": 0.5,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"rpm": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/elengines/elengine04": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"load": {
				"default": 0.5,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"rpm": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/elengines/elengine05": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"load": {
				"default": 0.5,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"rpm": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/fans/fan_arena": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/gasengines/gasengine01": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"gas": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"load": {
				"default": 0.5,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"rpm": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/gasengines/gasengine02": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"gas": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"load": {
				"default": 0.5,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"rpm": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/gasengines/gasengine03": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"gas": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"load": {
				"default": 0.5,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"rpm": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/gasengines/gasengine04": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"gas": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"load": {
				"default": 0.5,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"rpm": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/gasengines/gasengine05": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"gas": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"load": {
				"default": 0.5,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"rpm": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/gasengines/scrapengine": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"gas": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"load": {
				"default": 0.5,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"rpm": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/horns/clownhorn": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			},
			"Event Orientation": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"pitch": {
				"default": 0.5018050670623779,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/horns/phaserhorn": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"Event Cone Angle": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": 0.0
			},
			"pitch": {
				"default": 0.5250000357627869,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/piston": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"height": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"level": {
				"default": 5.0,
				"maximum": 5.0,
				"minimum": 0.0
			},
			"stretch": {
				"default": 1.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/resourcecollector_insert": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/resourcecollector_takeout": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/saw": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			},
			"impact": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/seats/default": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/seats/toilet": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/suspension": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"Distance 350": {
				"default": 0.0,
				"maximum": 350.0,
				"minimum": 0.0
			},
			"level": {
				"default": 5.0,
				"maximum": 5.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": -20.0,
				"maximum": 20.0,
				"minimum": -20.0
			}
		}
	},
	"event:/vehicle/thrusters/thruster01": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 450.0,
				"minimum": 0.0
			},
			"power": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": -1.0
			}
		}
	},
	"event:/vehicle/thrusters/thruster02": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 450.0,
				"minimum": 0.0
			},
			"power": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": -1.0
			}
		}
	},
	"event:/vehicle/thrusters/thruster03": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 450.0,
				"minimum": 0.0
			},
			"power": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": -1.0
			}
		}
	},
	"event:/vehicle/thrusters/thruster04": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 450.0,
				"minimum": 0.0
			},
			"power": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": -1.0
			}
		}
	},
	"event:/vehicle/thrusters/thruster05": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 450.0,
				"minimum": 0.0
			},
			"power": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": 0.0,
				"maximum": 50.0,
				"minimum": -1.0
			}
		}
	},
	"event:/vehicle/triggers/encryptor_off": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/triggers/encryptor_on": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/triggers/trigger_sensor_off": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"level": {
				"default": 5.0,
				"maximum": 5.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/triggers/trigger_sensor_on": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"level": {
				"default": 5.0,
				"maximum": 5.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/triggers/trigger_switch_off": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/triggers/trigger_switch_on": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/triggers/trigger_toggle_off": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vehicle/triggers/trigger_toggle_on": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/vo/straggler/vo_straggler_01": {},
	"event:/vo/straggler/vo_straggler_02": {},
	"event:/vo/straggler/vo_straggler_03": {},
	"event:/vo/straggler/vo_straggler_04": {},
	"event:/vo/straggler/vo_straggler_05": {},
	"event:/vo/straggler/vo_straggler_06": {},
	"event:/vo/straggler/vo_straggler_07": {},
	"event:/vo/straggler/vo_straggler_08": {},
	"event:/vo/straggler/vo_straggler_09": {},
	"event:/vo/straggler/vo_straggler_10": {},
	"event:/vo/straggler/vo_straggler_11": {},
	"event:/vo/straggler/vo_straggler_12": {},
	"event:/weapons/chemcannon/chem_cloud": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 200": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			}
		}
	},
	"event:/weapons/chemcannon/chem_explode": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/weapons/chemcannon/chem_flying": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/weapons/explosion_gas": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			},
			"size": {
				"default": 0.08000000566244125,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/weapons/explosion_gasleak": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"progress": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/weapons/spudgun/frier_fire": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			}
		}
	},
	"event:/weapons/spudgun/sg_fire": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			}
		}
	},
	"event:/weapons/spudgun/sg_noammo": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/weapons/spudgun/sg_reload": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"event:/weapons/spudgun/spinner_fire": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 250": {
				"default": 0.0,
				"maximum": 250.0,
				"minimum": 0.0
			}
		}
	},
	"event:/weapons/spudgun/spinner_spin": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance": {
				"default": 0.0,
				"maximum": 200.0,
				"minimum": 0.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			},
			"velocity": {
				"default": 0.0,
				"maximum": 1.0,
				"minimum": 0.0
			}
		}
	},
	"event:/weapons/watercannon_fire": {
		"Parameters": {
			"Direction": {
				"default": 0.0,
				"maximum": 180.0,
				"minimum": -180.0
			},
			"Distance 100": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	},
	"snapshot:/combat": {},
	"snapshot:/headphones": {},
	"snapshot:/loading": {},
	"snapshot:/nomusic": {},
	"snapshot:/paus": {},
	"snapshot:/reverb/arena": {},
	"snapshot:/reverb/field": {},
	"snapshot:/reverb/small room": {},
	"snapshot:/reverb/underwater": {},
	"snapshot:/reverb/underwater end": {},
	"snapshot:/reverb/warehouse": {},
	"snapshot:/sidechain": {
		"Parameters": {
			"Intensity": {
				"default": 0.0,
				"maximum": 100.0,
				"minimum": 0.0
			}
		}
	}
}
```