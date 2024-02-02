# CocktailApp
## Status: In Progress

### The Idea
To create an app where users can search for cocktail recipes and save these as a PDF document.

<img width="361" alt="Screenshot 2024-02-01 at 19 20 03" src="https://github.com/kkd01/CocktailApp/assets/156792296/3fd8dd8c-b761-4db1-8b55-6a3a1b2f55ea">


<img width="420" alt="Screenshot 2024-02-01 at 19 26 23" src="https://github.com/kkd01/CocktailApp/assets/156792296/0891d795-1af0-48a2-8e5e-27db814a4e2a">


<img width="1329" alt="Screenshot 2024-02-02 at 09 10 30" src="https://github.com/kkd01/CocktailApp/assets/156792296/60733892-4841-492e-97de-bb55c0119509">

### Current Stage
The app can currently search for cocktails based on the most searched ingredients.

The ingredients are stored in a SQLite table where only the new values are added on each API call, the ingredients dropdown is then populated with this data. 

When a user selects an ingredient to search, the ingredient name is passed to another API to retrieve all the cocktails that contain this ingredient, this data is then presented in a treeview.

The treeview will need to show basic information for the cocktail (name, ingredients, glass type, alcoholic / non alcoholic), this is yet to be implemented and is not reflected in the images above.

### Python Libraries
* pandas<br />
* sqlite3<br />
* requests<br />
* json<br />
* tkinter<br />
* IPython<br />
* PIL<br />
