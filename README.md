<h1>ConceptWiki</h1>

<h2>User Stories</h2>
1. As a user, I can search Wikipedia entries and get a visual representation of the resulting Wikipedia entries.
2. As a user, I will be able to see a range of concepts that relate to my initial search and explore their relationship to each other.
3. As a user, I can click a button to generate a random Wikipedia entry.

<h2>Interesting  bits</h2>
1. Text is dynamically added to the correct Bootstrap carousel slide via a MutationObserver.
2. JS files are loaded asynchronously via promises.
3. Once Wikipedia generates a list of linked terms, the app searches Google to find an image that matches that term and displays it on the screen.
4. Concept visualization is done via Cytoscape, an open-source platform for visualizing networks. 

Designed of the front page was inspired by www.instactables.com .
