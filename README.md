``` TypeScript
export class AboutMe {
    name: string;
    role: string = "LuaU Technical Engineer";
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
