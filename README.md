```typescript
const username: string = "albertozaranza";
const name: string = "Alberto Zaranza";
const languages: string = "JavaScript, TypeScript";
const frameworks: string = "React, React Native";

const linkedin: string = "https://www.linkedin.com/in/albertozaranza/";
const email: string = "albertozaranza@gmail.com";
const website: string = "https://albertozaranza.github.io/portfolio/";

type Project = {
    name: string;
    description: string;
}

const portfolio: Project = {
    name: "Portfolio",
    description: "Browse through my projects and discover my talent and experience in software development"
};

const moveIt: Project = {
    name: "MoveIt",
    description: "Help developers to do more exercises during the day"
};

const npmAutomation: Project = {
    name: "Npm Automation",
    description: "Create a new release of your package on NPM when you merge a release pull request"
};

type Contribution = {
    name: string;
    description: string;
}

const astroNative: Contribution = {
    name: "Astro Native",
    description: "Astro components for React Native"
};
```
