```javascript
const ME = {
  name: "Ahadu Chere",
  interests: { WebDevelopment: true, GraphicDesign: true },
  skills: {
    WebDevelopment: {
      Javascript: {
        level: "Beginner",
        frameworks: {
          VueJS: { status: "Learning" },
          ReactJS: { status: "Learning" }
        }
      },
      CSS: {
        level: "Beginner",
        frameworks: {
          TailwindCSS: { status: "Learning" },
          BootstrapCSS: { status: "Learning" }
        }
      }
    },
    GraphicDesign: {
      Adobe: {
        level: "Intermediate",
        software: {
          Photoshop: { status: "Previously Certified" },
          PremierePro: { status: "Previously Certified" }
        }
      }
    }
  },
  Projects: {
    Quickinit: {
      status: "Ongoing",
      description: "CLI tool for structuring my coding projects"
    }
  }
};
console.dir(ME, { depth: null });
