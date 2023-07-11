### こんにちは 👋

const currentWorkplace:object = {
        company   : 'Dea Bakery',
        position  : 'Lead Software Engineer'
};

const generalKnowledge:object = {
        language    : ['Typescript','PHP','Python','Dart','SQL','Java'],
        using       : ['Svelte','Sveltekit','Bootstrap','DaisyUI','Laravel','Codeigniter','Android Studio','Flutter'],
        databases   : ['MySQL','SQLite','Supabase'],
        tools       : ['Figma','Photoshop','Premiere','Trello','Jira','Notion','Looker Studio']
};

function aboutMe(): object {
    return {
        name : 'okuruu',
        knowledge : generalKnowledge,
        workingAt : currentWorkplace,
        funFact : 'The 🦄 is the national animal of Scotland'
    };
}
