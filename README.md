### This is a new account made on 9/22/2025!

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

![Static Badge](https://img.shields.io/badge/Roblox%20TS-darkred?style=flat-square)
![Static Badge](https://img.shields.io/badge/HTML-grey?style=flat-square)
![Static Badge](https://img.shields.io/badge/Python-orange?style=flat-square)
![Static Badge](https://img.shields.io/badge/LuaU-f?style=flat-square&color=cyan)
![Static Badge](https://img.shields.io/badge/Rust-darkblue?style=flat-square&color=darkblue)

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

# 🚧 Tools

### <ind>Databases</ind>

![Static Badge](https://img.shields.io/badge/MySQL-Data?style=flat-square&color=darkgreen&link=https%3A%2F%2Fwww.mysql.com%2F)
![Static Badge](https://img.shields.io/badge/Microsoft%20SQL-Data?style=flat-square&color=darkorange&link=https%3A%2F%2Fwww.microsoft.com%2Fen-us%2Fsql-server)
![Static Badge](https://img.shields.io/badge/Oracle-Data?style=flat-square&color=blue&link=https%3A%2F%2Fwww.oracle.com%2F)

### <ind>Roblox Frameworks</ind>

![Static Badge](https://img.shields.io/badge/Knit-Framework?style=flat-square&color=violet&link=https%3A%2F%2Fsleitnick.github.io%2FKnit%2F)
![Static Badge](https://img.shields.io/badge/Nevermore%20Engine-Framework?style=flat-square&color=grey&link=https%3A%2F%2Fquenty.github.io%2FNevermoreEngine%2F)
![Static Badge](https://img.shields.io/badge/Custom%20Frameworks-Framework?style=flat-square&color=darkblue)

# ⛽ Top Repositories

[![Public](https://github-readme-stats.vercel.app/api/pin/?username=syncronicc&repo=Pubsdlic)](https://github.com/syncronicc/Pubic)
[![Private](https://github-readme-stats.vercel.app/api/pin/?username=syncronicc&repo=Privfate)](https://github.com/syncronicc/Prvate)

# 🏆GitHub Trophies [ Github + Roblox trophy stack ]
![](https://github-trophies.vercel.app/?username=kts&theme=radical&no-frame=false&no-bg=false&margin-w=4)

---
[![](https://visitcount.itsvg.in/api?id=kts&icon=0&color=0)](https://visitcount.itsvg.in)
