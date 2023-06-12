```js
class About extends Me {
  getProfile() {
    return `👋 Hi, I'm Tony! I'm a software engineer with a passion for learning 
      and over a decade of experience. I am driven by my desire to stay ahead 
      of the latest advancements, and I bring a wealth of technical expertise
      to each project I work on. I am a versatile and knowledgeable professional 
      in the field of technology and computing.`;
  }

  getCurrentProjects() {
    return {
      projects: [
        {
          name: 'Fragility',
          description: 'Issue Tracking System',
          website: 'https://fragility.ajdube.com/',
          technologies: ['Vue.js', 'Node.js', 'Express.js', 'MySQL', 'Vite',
            'Vuetify', 'Vue Router', 'Pinia', 'Inkscape']
        },
        {
          name: 'Tangle',
          description: 'Substitution Cipher Game',
          website: 'https://tangle.ajdube.com/',
          technologies: ['HTML', 'CSS', 'JavaScript']
        },
        {
          name: 'EggFlip',
          description: 'Breakfast Recipe App',
          website: 'https://eggflip.ajdube.com/',
          technologies: ['Python', 'Django', 'Django REST Framework', 'PostgreSQL',
            'Docker', 'Swagger', 'Github Actions']
        }
      ]
    };
  }

  getFutureGoal() {
    return 'To continue learning, collaborating, and building high-quality solutions.';
  }
}
```
