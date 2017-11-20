Learn JSDoc
===========

Use JSDoc and a few carefully crafted comments to document your JavaScript! 

![Undocumented Code](http://i.imgur.com/YYcMply.png "Undocumented")

> "Good code is its own best documentation. <br />
> As you're about to add a comment, ask yourself, <br />
> 'How can I improve the code so that this comment isn't needed?' <br />
> Improve the code and then document it to make it even clearer."
> ~ Steve McConnell (Code Complete)

> "Always code as if the guy who ends up maintaining your code <br />
> will be a violent psychopath who knows where you live."
> ~ Martin Golding

### Installation 

Once you have [Node.js](http://nodejs.org/) installed in your terminal run:

```
npm install jsdoc
```

or if you have an existing node project, add **jsdoc** to **devDependencies** in 
[package.json](http://docs.nodejitsu.com/articles/getting-started/npm/what-is-the-file-package-json)

### Baby Steps

Create a javascript file and add the following comments/code

```javascript
/**
 * Hello "Name"
 *
 * @param {string} name person/thing you want to say hello to.
 * @returns {string} Hello + name 
 */
function hello(name) {
  return "Hello "+name +"!";
}
```

Now run jsdoc in your command line: `jsdoc`

This will create the **out** directory which contains the mini-documentation 
for the simple hello function. Open the out/**index.html** file in your browser

![JSDoc Hello World Example](http://i.imgur.com/A4POXNA.png "JSDoc Hello World Example")


The *vast* majority of JSDoc tags are useless.
For a full list of tags see: http://usejsdoc.org/#JSDoc3_Tag_Dictionary

I will update this tutorial as and when I use a new tag.
For now I'm only using **@param**, **@returns** and **@example**


### FAQ

Q: Do I need Java to run JSDoc? <br />
A: No. [Java](http://www.securelist.com/en/analysis/204792310/Kaspersky_Lab_Report_Java_under_attack_the_evolution_of_exploits_in_2012_2013) is ***not*** *required*. :-)



### Useful Links

- JSDoc GitHub Repo https://github.com/jsdoc3/jsdoc
- Documentation: http://usejsdoc.org/
- Wiki: https://code.google.com/p/jsdoc-toolkit/w/list
- Examples: https://code.google.com/p/jsdoc-toolkit/wiki/DocExamples
- Tag Reference: https://code.google.com/p/jsdoc-toolkit/wiki/TagReference

### Tutorials


- Bit old but still relevant: http://www.2ality.com/2011/08/jsdoc-intro.html
- DailyJS (Dox): http://dailyjs.com/2011/01/20/framework-part-47/
- DZone Intro: http://css.dzone.com/articles/introduction-jsdoc

#### Investigate

- Dox: https://github.com/visionmedia/dox
- Docco: http://jashkenas.github.io/docco/ + https://github.com/jashkenas/docco



### *Useless* But *Interesting* Programming Quotes
- http://quotes.cat-v.org/programming/
- http://www.linfo.org/q_programming.html
- http://www.goodreads.com/quotes/tag/programming
- http://www.javacodegeeks.com/2012/11/20-kick-ass-programming-quotes.html
- http://www.marcofolio.net/tips/27_inspiring_top_notch_programming_quotes.html
- http://web.archive.org/web/20100818203850/http://stackoverflow.com/questions/58640/great-programming-quotes

### Package.json

> @todo Move this to main node.js tutorial

- What is package.json: http://docs.nodejitsu.com/articles/getting-started/npm/what-is-the-file-package-json
- Interactive Guid: http://package.json.nodejitsu.com/