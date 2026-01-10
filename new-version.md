```typescript
class Stefany {
  static readonly me = {
    location: 'Recife, Pernambuco, Brazil',
    languages: ['pt-BR', 'en-US'],
  }

  static readonly techStack = {
    area: 'frontend',
    languages: ['TypeScript', 'JavaScript', 'python'],
    tools: ['Everything in React ecosystem', 'Angular'],
  }

  static readonly education = {
    graduation: {
      degree: 'BSc in Information Systems',
      institution: 'UFRPE',
      finishYear: 2020,
    },
    posGrad: {
      status: 'searching right now',
      startYear: 2026,
    }
  }

  static readonly work = {
    experienceYears: 8,
    current: {
      company: 'Stone',
      role: 'Software Engineer',
      seniority: 'senior',
      focus: 'frontend',
    },
    previous: {
      company: 'FCxLabs',
      role: 'Systems Analyst',
      seniority: 'senior',
      focus: 'frontend',
    },
  }


  static getMyContact() {
    return {
      website: 'https://www.stefany-sa.com.br',
      linkedin: 'https://www.linkedin.com/in/stefanyvasconcelos',
      github: 'https://github.com/StefanyVasc',
      unsplash: 'https://unsplash.com/pt-br/@stevasc'
    }
  }
}

```
