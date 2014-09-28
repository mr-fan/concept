# Concept/Gathering of ideas

* Target group: Developers, from beginner to advanced
* Difference to the forums: Stripping the discussion part, concentrating on the info; and if done properly: bypassing the mediocre forum search, better tagging
* Difference to the official tutorial section: Focusing on not creating a whole site, but modular parts of it. Single solutions. For example: [First child redirects](http://bigger-on-the-inside.net/2014/08/19/little-processwire-first-child-redirect-snippet/) (shameless plug, but this is the format of information pieces I'm having in mind)
* Difference to the API documentation: Situation-based ("I need this and that") instead of architecture-based
 
Laravel.io (forum), laravel.com (official, and doc) and laravel-recipies.com possibly prove that these type of sites can coexist in a framework ecosystem, so I guess a recipes site would not cannibalize the forums at http://processwire.com/talk nor the doc section.
 
A recipe site like this would live and die with its content, of course. I would be ready to share all the small pieces of information I encounter that would make a good "recipe". But that alone wouldn't be enough ;) so this project won't survive without contribution of the community.

===

# Potential recipes:

https://github.com/mr-fan/concept/blob/master/RECIPES.md


===

# Possible structure of processwire-recipes.com / snippets.pw

* Page type: Home page
	* Big ass search input
	* List of tags (topics)
	* Call to action: contribute to this directory! (links to form)
* Page type: Snippet/Recipe-Listing
	* Listing of Recipe/Snippet headlines, paginatable
	* Sortable by: Date added, alphabet, votes (a feature maybe added later)
* Page type: single Snippet/Recipe
	* Problem
	* Solution
	* Code example
	* Contributor
	* Discussion to that Recipe/Snippet (like comments below a blog post)
* Page type: generic content page
	* (Used for about page, Imprint,...)
* Page type: Form page
	* (Contribution form)
		* Recipe title
		* Recipe problem (prose)
		* Recipe solution (prose)
		* Recipe solution (code)
		* Contributor (link to GitHub and/or ProcessWire forums)
