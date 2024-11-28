#H1 Expanding Cards Project!
###A little project of some expanding cards, with HTML, CSS and some JavaScript

In the HTML file, I made one div with a container class and a panel class.

The CSS I styled for each panel, it has a rounded radius, separated by a flex box.

JavaScript was the "Hardest" part, because I'm still studying how to use modify
HTML and give functions. I've made 2 main functions:

Adding the "active" class:
```
panels.forEach(panel => {
    panel.addEventListener('click', () => {
        removeActiveClasses();
        panel.classList.add('active');
    });
});
```

Remove function:
```
function removeActiveClasses() {
    panels.forEach(panel => {
        panel.classList.remove('active');
    });
}
```

This is a little project for studying WebDevelopment
