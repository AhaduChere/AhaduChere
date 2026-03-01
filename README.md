```javascript
const My = {
  name: "Ahadu Chere",
  age: 23,
  tools: {
    editor: "Neovim",
    os: "Linux Mint",
  },
  projects: {
    Odyssey: {
      description: "Calendar WebApp",
      framework: "NuxtJS"
    },
    Ember: {
      description: "Local File Music Player",
      framework: "Electron"
    }
  },
 info() {
    console.log(`My name is ${this.name} and I'm ${this.age}`);
    console.log(`I code in ${this.tools.editor} on ${this.tools.os}`);
    let projectList = "My Projects are: \n";
    for (const project in this.projects) {
      const { description, framework } = this.projects[project];
      projectList += `${project}: A ${description} built with ${framework}\n`;
    }
    console.log(projectList);
  }
};

My.info();
```
