### This is a new account made on 9/22/2025, the old one is [this!](https://github.com/KTSGod)

# 🌍 About me

### <ins>Biography</ins>

- **I have contributed to 200m+ visits across many genres;**

- **I am 17 [ 2008, 18 september ];**

- **I work only ' remotely ', so I wont meet anyone else besides employer unless he is located in another country.**

<sub>[ EU -> Romania ]</sub>

### <ins>Background</ins>

- **As of right now im free to commision, I have a lot of technical expertise in frontend but I can be full-stack.**

- **I am just getting started into vehicle mechanics so I wont be taking anything related to them as I am not that experienced in this area of developing.**

- **I have contributed to a total of ~200m+ visits within the past years.**

![Static Badge](https://img.shields.io/badge/Code-LuaU-Code?style=for-the-badge&color=cyan)
![Static Badge](https://img.shields.io/badge/Code-Python-Code?style=for-the-badge&color=orange)
![Static Badge](https://img.shields.io/badge/Code-Roblox%E2%A0%80TS-Code?style=for-the-badge&color=darkred)

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ktsgod&theme=vue&show_icons=true&hide_border=false&layout=compact" alt="ktsgod's GitHub Stats" />

# 📋 Snippets

### <ins>LuaU Sample</ins>
``` LuaU
function service.new(player:Player,access)
    promise.defer(function()
        return(CreateUI(player.Character or player.CharacterAdded:Wait(),access.Level))
    end)

    return setmetatable({Player=player,self.connection=player.CharacterAdded:Connect(function(char)
        CreateUI(player.Character,access.Level)
    end)},{
      __call=function(self,...)
          if not self.connection then
              return
          end
          
          self.connection:Disconnect()
          self.connection=nil
      end,
    })
end
```

### <ins>Roblox-TS Sample</ins>
``` TypeScript
export class AboutMe {
    name: string;
    role: string = "LuaU Programmer";
    lang: string[] = ["ro_RO", "en_US"];
    exp: string;
    skills: string[];

    constructor(
        name: string = "KTS_God",
        exp: string = "5+",
        skills: string[] = ["Scripting", "Game Design", "Optimization"]
    ) {
        this.name = name;
        this.exp = exp;
        this.skills = skills;
    }

    intro() {
        print(`Hey there! I'm ${this.name}, working as a ${this.role}.`);
        print(`I've been doing this for about ${this.exp} years now, mostly in ${this.lang.join(" and ")}.`);
        print(`Some of the things I enjoy doing: ${this.skills.join(", ")}.`);
    }
}

const newKTS = new AboutMe();
newKTS.intro();
```

# 🏆GitHub Trophies [ Keep in mind the main account was not originally made by me ]
![](https://github-trophies.vercel.app/?username=kts&theme=radical&no-frame=false&no-bg=false&margin-w=4)

---
[![](https://visitcount.itsvg.in/api?id=kts&icon=0&color=0)](https://visitcount.itsvg.in)
