<div align="center">

# Floating Accessory

[![Generic badge](https://img.shields.io/github/downloads/VRLabs/Floating-Accessory/total?label=Downloads)](https://github.com/VRLabs/Floating-Accessory/releases/latest)
[![Generic badge](https://img.shields.io/badge/License-MIT-informational.svg)](https://github.com/VRLabs/Floating-Accessory/blob/main/LICENSE)
[![Generic badge](https://img.shields.io/badge/Unity-2019.4.31f1-lightblue.svg)](https://unity3d.com/unity/whats-new/2019.4.31)
[![Generic badge](https://img.shields.io/badge/SDK-AvatarSDK3-lightblue.svg)](https://vrchat.com/home/download)

[![Generic badge](https://img.shields.io/discord/706913824607043605?color=%237289da&label=DISCORD&logo=Discord&style=for-the-badge)](https://discord.vrlabs.dev/)
[![Generic badge](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Dvrlabs%26type%3Dpatrons&style=for-the-badge)](https://patreon.vrlabs.dev/)

Give your object a floating effect

![Alt text]()

### ⬇️ [Download latest Unitypackage](https://github.com/VRLabs/Floating-Accessory/releases/latest)

<!-- 
### 📦 [Add to VRChat Creator Companion]() -->

</div>

---

## How it works

* Three physbones are used to make an object move smoothly witht the user.
* A sub animator then moves one physbone up and down to give it a floating effect.

## Install guide

* Drag & Drop the ``Floating Accessory`` prefab into the base of your Hierarchy.
* Right click and unpack the prefab, then drag & drop it onto your avatar.
* Expand the prefab hierarchy and find ``Floating Target``
* Move ``Floating Target`` outside of ``Floating Accessory`` and place it anywhere in your avatars hierarchy as needed.

## How to use

* Place the objects you want to float inside ``Container``.
  * Alternatively you can constrain the objects to ``Container``.

## Performance stats

```c++
Constraints:        6
Physbones:          3
Sub Animators:      1
```

## Hierarchy layout

```html
Floating Accessory
|-Container
|  |-Cube
|-Dynamics
|  |-PhysBones
|  |  |-Wobble
|  |  |  |-Wobble End
|  |  |-Float
|  |  |  |-Float End
|  |  |-Swing
|  |  |  |-Swing End
|  |-Constraints
|  |  |-Wobble
|  |  |-Float
|  |  |-Swing
|-Floating Target
```

## Contributors

* [hfcRed](https://github.com/hfcRed)  
* [Dreadrith](https://github.com/Dreadrith)

## License

Floating-Accessory is available as-is under MIT. For more information see [LICENSE](https://github.com/VRLabs/Floating-Accessory/blob/main/LICENSE).

​

<div align="center">

[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/VRLabs.png" width="50" height="50">](https://vrlabs.dev "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Discord.png" width="50" height="50">](https://discord.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Patreon.png" width="50" height="50">](https://patreon.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Twitter.png" width="50" height="50">](https://twitter.com/vrlabsdev "VRLabs")

</div>

---
