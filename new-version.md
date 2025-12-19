```typescript
class Stefany {
  static readonly me = {
    location: 'Recife, Pernambuco, Brazil',
    languages: ['pt-BR', 'en-US'],
  }

  static readonly techStack = {
    area: 'frontend',
    languages: ['TypeScript', 'JavaScript'],
    tools: ['React', 'Zustand', 'SWR', 'Vitest'],
  }

  static readonly education = {
    graduation: {
      degree: 'BSc in Information Systems',
      institution: 'UFRPE',
      finishYear: 2020,
    },
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
      focus: 'frontend',
    },
  }

  static nowBuilding() {
    return {
      portfolio: 'https://github.com/StefanyVasc/portfolio',
    }
  }

  static learningFocus() {
    return [
      'react rendering internals',
      'performance optimization',
      'system design',
    ]
  }

  static contact() {
    return {
      website: 'https://www.stefany-sa.com.br',
      linkedin: 'https://www.linkedin.com/in/stefanyvasconcelos',
      github: 'https://github.com/StefanyVasc',
    }
  }
}

```