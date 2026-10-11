# aicore_density
Population management for aicore.

> 💬 **Need help or want to support Aicore?** Join our Discord: [https://discord.gg/xfQFcWjak](https://discord.gg/xfQFcWjak)


## Features
- Calm AI (adjusting npc/gang npc aggresiveness)
- Adjusting npc/vehicle/parked vehicle spawn rates
- Small collection of ymaps to disable car generators

## Installation
### Manual
- Download the script and put it in the `[aicore]` directory.
- Add the following code to your server.cfg/resouces.cfg
```
ensure aicore_density
```

## Configuration
- Adjust variables in `config/client.lua` for permanent changes
- Utilize `exports.aicore_density:SetDensity(type, value)` to adjust at runtime

> Rebranded from [Qbox-project/qbx_density](https://github.com/Qbox-project/qbx_density) under GPL-3.0. Original work © QBox Project contributors.
