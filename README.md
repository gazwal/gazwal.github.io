## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/gazwal/gazwal.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
```php
	if (!empty($node_116->field_image['und'][0]['uri'])) {
		$uri = $node_116->field_image['und'][0]['uri'];
		// sans style défini (= format original de l'upload)
		$bandeau_image = theme('image', array('path' => $uri));
		$variables['bandeau'] = $bandeau_image;
		// variable printée dans ../templates/node/node--article.tpl.php
	} else { $variables['bandeau'] = ''; }
	// texte du bandeau
	if (!empty($node_116->body['und'][0]['safe_value'])) {
		$bandeau_texte = $node_116->body['und'][0]['safe_value'];
		$variables['bandeau_textes'] = $bandeau_texte;
		// variable printée dans ../templates/node/node--article.tpl.php
	} else { $variables['bandeau_texte'] = ''; }
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/gazwal/gazwal.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
