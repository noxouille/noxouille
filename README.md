## Hi, I'm Ferdi! 👋

![](https://komarev.com/ghpvc/?username=noxouille)

Developer Consultant at [CGI](https://www.cgi.com/en)

### <img src="https://media.giphy.com/media/146gtxJUW6IR7W/giphy.gif" width=50> A little more about me... 

```javascript
const ferdi = {
  pronouns: "he" | "him",
  code: [Bash, PowerShell, Python, Scala, LaTeX],
  tools: [AzureDevOps, Terraform, Databricks, AzureML, Docker, Kubernetes]
}
```

Check out [my blog](https://ferdi.now.sh) for more details about me.

### <img src="https://i.imgur.com/uYxC2D8.png"> A little more about my keyboard... 

Check out the [build process](https://ferdi.now.sh/TFV2-silent-linear-build/) if you are interested or fellow enthusiast.

```hcl
resource "custom_keyboard" "silent_linear_build" {
    name          = "tfv2"
    color         = "e-white"
    mount         = "top"
    plate         = "brass"
    weight        = "brass"
    daughterboard = true
    foam {
      case        = true
      module      = true
    }
    pcb {
      name        = "dz60rgb-ansi-v2"
      layout      = "ansi"
      form_factor = "60%"
      hotswap     = true
      per_key_rgb = true
      backlight   = false
      bandaid_mod = true
      port {
        type      = "usb-c"
        position  = "left"
      }
    }
    switches {
      alphas {
        name      = "roselios"
        spring    = "67g"
        type      = "silent linear"
        lube      = "krytox 205-g0"
      }
      mods {
        name      = "sakurios"
        spring    = "62g"
        type      = "silent linear"
        lube      = "krytox 205-g0"
      }
    }
    stabs {
      name        = "zeal v2"
      spacebar_u  = "6.25"
      type        = "screw-in"
      lube        = "krytox 205-g0"
    }
    keycaps {
      name        = "dye-subbed keycaps kbdfans"
      material    = "PBT"
      type        = "dye-sublimated"
    }
}
```

<!--
**noxouille/noxouille** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
