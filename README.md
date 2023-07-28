### こんにちは 👋

```typescript
let currentWorkplace:object = {
        company   : 'Dea Bakery',
        position  : 'Lead Software Engineer'
};

let generalKnowledge:object = {
        language    : ['Typescript','PHP','Python','Dart','SQL','Java'],
        using       : [
            'Svelte','Sveltekit','Bootstrap','DaisyUI','NodeJS',
            'Laravel','Codeigniter','Android Studio','Flutter'
        ],
        databases   : ['MySQL','SQLite','Supabase','Firestore'],
        tools       : ['Figma','Photoshop','Premiere','Trello','Jira','Notion','Looker Studio','Pandas','Git']
};

function aboutMe():object {
    return {
        name        : 'okuruu',
        knowledge   : generalKnowledge,
        workingAt   : currentWorkplace,
        funFact     : 'The 🦄 is the national animal of Scotland'
    };
}
```
