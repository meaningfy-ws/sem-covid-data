# Dataset description

Ireland was selected as a tryout member state country for which a COVID19 timeline shall be created similar to the EU action timeline. It was selected because it is the only member state country (UK having just left the U) that publishes official documents and press releases in English.

## EU action timeline dataset (ds_eu_timeline)
An investigation was conducted searching for a comparable timeline summary of Ireland actions on COVID19 and none was found. However, the official government website press corner, www.gov.ie, was identified as a good source of information.
gov.ie is a central portal for government services and information. It combines the websites of Irish government departments and is a trusted source that makes interactions with the government more user-focused.
We decided to use the search service of this website and search for the same set of EuroVoc concepts that was used to retrieve Covid relevant documents from Cellar. The search results are crawled and structured in a dataset using the set of data attributes listed in Table 7.
The preferred label of each EuroVoc concept is used as a search term. For each EuroVoc concept a new search is launched and only articles that are more recent than 1st of January 2020 are considered.

| Data attribute | Description
| -------------- | -----------
| Title          | The title of the press release article.
| Content        | The press release article in simple clean unstructured text.
| Published date | The date when the press release was published
| Update date    | The date when the article was updated.
| Content links  | A list of links available in the text.
| Campaigns links| A list of links to the organised Campaigns
| Department     | The government department authoring the article.
| Policies links | The list of links to the broad policy category under which the article is placed.
| Keywords       | A list of keywords assigned by the article authors.
| Page type      | The type of article is similar to the classification from the Resource Type authority table used for ds_eu_cellar dataset. The possible types are: press release, speech, news, policy information,  reports, etc.

Table 1: The attribute structure for ds_ireland_timeline


# Contributing

You are more than welcome to help expand and mature this project.

When contributing to this repository, please first discuss the change you wish
to make via issue, email, or any other method with the owners of this repository
before making a change.

Please note we adhere to Apache code of conduct, please follow it in all your
interactions with the project.

# License

The documents, such as reports and specifications, available in the /doc folder,
are licenced under a CC BY 4.0 licence.

The scripts (stylesheets) and other executables are licenced under GNU GPLv3
licence.
