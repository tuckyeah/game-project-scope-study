# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to these in this file via a pull request.

-   A wireframe of what your game project will look like.
  See drawings in 'wireframes' directory

-   The data structure you plan to use.

  USER:
    Attributes: name, password, list of games (current & past)
    Methods: change password, view all games, show games won, resume game
      sign in, sign out, change password

  GAME:
    Attributes: game board, number of moves played, number of moves left,
      array of x's, array of o's
    Methods: start new game, play a turn, display who won



-   How you will take the markup of the game board and represent it in JS

    The game board will itself be a div, and it will contain 9 divs, aligned in
    CSS in a grid, one for each of the cells. Those grid divs will be accessible
    either by ids, or by their index / relationship to the parent board div,
    depending on which seems easier.

    Although I am kind of curious if it would be easier to do the game board
    with tables (even though tables are the worst), if only because the board
    seems to be designed to be used with tables. I'll experiment with which is
    easier!


-   How you plan to approach this project.

   I plan to follow the given schedule pretty closely. I'm going to start with
   getting a really rough HTML page up and designing the basic core CSS for the
   game board, as well as making form/input fields for the sign up and sign in.
   Once I have this done and any huge design issues worked out, I'll start
   working on the JS for the gameplay functionality, then tackle the
   authentication. Once those guys are done, then I'll come back to the CSS and
   make it a little nicer looking, time permitting.


-   4-8 user stories for your game project.

  As a new user, I want to sign up so I can keep track of my games.

  As a returning user, I want to sign in quickly and resume a game.

  As a casual user, I'd like to be able to just start playing right away.

  As a returning user, I'd like to be able to view a record of all my games.

  As a new user, I'd like to be able to sign up / sign in without it losing track
  of where I am in my current game.


-   How you plan to keep your code modular.

  I'm going to follow the general flow we've been using thus far in our API
  trainings, by having seperate js files for the UI, events, api, and index. If
  it makes sense, I may also make seperate files for my game functionality and
  my user funcitonality, based on my model entities. The CSS for the pages, as
  well as any images will also be kept in their respective folders.

-   What creative spin will you add to your project.

  I'm really into the idea of using different symbols besides 'x' and 'o',
  and, time permitting, I'd like to be able to add an option for users to choose
  their symbols from say, a given three or four themed options.


-   How you will use version control to backup / track your project.

  I will set up a git repo for my overall project and make specific branches
  for each 'feature' (eg auth, game play, etc) to work on that I will merge into
  the master branch. This will also be good practice on working with Git!

-   Do you plan to attempt any of the bonuses.

  I'd like to do the customizable tokens (x's and o's), as well as definitely looking
  into localStorage options, so players can 'resume' a game. Time permitting, I'd
  love to tackle letting players from play from seperate devices too!
