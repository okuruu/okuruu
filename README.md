### こんにちは 👋

```typescript
let currentWorkplace:object = {
        company   : 'Dea Bakery',
        position  : 'Lead Software Engineer'
};

let generalKnowledge:object = {
        language    : ['Typescript','PHP','Rust','Python','Dart','SQL','Java'],
        using       : [
            'Sveltekit','Tauri','Bootstrap','DaisyUI','NodeJS',
            'Laravel','Codeigniter','Android Studio','Flutter'
        ],
        databases   : ['MySQL','SQLite','Supabase','Firestore'],
        tools       : ['Figma','Photoshop','Premiere','Trello','Jira','Notion','Looker Studio','Pandas','Git']
};

function aboutMe() {
    return {
        name        : 'okuruu',
        knowledge   : generalKnowledge,
        workingAt   : currentWorkplace,
        funFact     : 'The 🦄 is the national animal of Scotland'
    };
}
```
