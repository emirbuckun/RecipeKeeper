# RecipeKeeper

This is a recipe app. With this application, new recipes can be added, 
liked recipes can be added to favorites and users can comment on each other's recipes.

## Versioning
| GitHub Release | .NET Core Version | Node Version | Vite Version |
|----------------|-------------------|--------------|--------------|
| master | 7.0.101 | v20.2.0 | 4.4.5 |

## Project Structure
```
├── .vscode
├── Core
│   └── RecipeKepeer.App
│   └── RecipeKepeer.DataAccess
│   └── RecipeKepeer.Entity
├── Infrastructure
│   └── RecipeKepeer.DataAccess.MsSql
│   └── RecipeKepeer.DataAccess.InMemory
├── Presentation
│   └── RecipeKepeer.Api
│   └── RecipeKepeer.WebUI
├── .gitignore
├── README.md
├── RecipeKeeper.sln
```

- `.vscode` contains workspace settings as well as configurations.
- `Core` is core layer of the solution. It contains app, data access and entity projects.
- `Infrastructure` is infrastructure layer of the solution. It contains data access projects.
- `Presentation` is presentation layer of the solution. It contains Web API and Web UI projects.
- `RecipeKepeer.Entity` is used to store entity classes.
- `RecipeKepeer.DataAccess` contains repositories.
- `RecipeKepeer.App` contains handlers.
- `RecipeKepeer.DataAccess.MsSql` is a data access layer for MSSQL database.
- `RecipeKepeer.DataAccess.InMemory` is a data access layer for in memory storage.
- `RecipeKepeer.Api` is a Web API used by Web UI.
- `RecipeKepeer.WebUI` is a Vite project with React template.
- `.gitignore` specifies intentionally untracked files that Git should ignore.
- `RecipeKeeper.sln` is a structure for organizing projects.

## Setting Up

To setup this project, you need to clone the git repo.

```sh
$ git clone https://github.com/emirbuckun/RecipeKeeper.git
$ cd RecipeKeeper
```

followed by

```sh
$ dotnet restore
```
