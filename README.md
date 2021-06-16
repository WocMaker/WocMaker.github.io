## DnD text generation

In this page, you can write down whatever you are think about a fantasty character and his or her story as a staring ponint. Then, a GPT-2 generated biology would be created


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

  render () {
    return html`
    <div id="all">
    <div id="searchLine">
      <span id="inputSearchBar">
        <input id="searchBar" type="text" value=${this.text} @input=${e => {this.text = e.target.value}}/>
        <img src="assets/search.png" id="textSearch" @click=${e => { this.generate() }} />
        Backend url: <input type="text" value=${this.backendHost} @input=${e => {this.backendHost = e.target.value}}/>
        Model: <select @input=${e => {this.currentModel = e.target.value}}>${this.models.map(model => 
            html`<option value=${model} ?selected=${model === this.currentModel}>${model}</option>`)}</select>
      </span>
     
    </div>
    <div id="filter">
      Dalle Text to Image ! <br />
    </div>

    <div id="products">
    ${this.loading ? `loading, please wait ${this.loadingSeconds} seconds...` : ''}
    ${this.imagesDalle.map (image => this.renderImage(image))}
    </div>
    </div>
    `
  }
}

## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/WocMaker/WocMaker.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
