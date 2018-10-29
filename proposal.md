# X-Team 41 Project Proposal - "Monday Movie Madness"

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

# Problem Description

HBO wants to create a movie marathon to take place all day each Monday. They have hired X-Team 41 to create a program to select and schedule the movies that will play during the marathon. The goal of the program is to select movies that will drive up interest in the movie marathon and appeal to a wide audience. They have a fixed budget so selecting all new blockbuster type movies is not an option as the price to attain their licenses is higher than older or less popular movies.




# Questions to answer for Exercise #2

1. Name: Monday Movie Madness 




2. Output: The output of our program would provide a 24 hr schedule of movies based off of our restrictions and preferences. 
    #### Output sample
    | Time slots    | Movie                      | 
    | ------------- |:-------------------------: |
    | 7:00PM        | Avengers Infinity War      | 
    | 7:30PM        | Avengers Infinity War      |  
    | 8:00PM        | Avengers Infinity War      | 
    | 8:30PM        | Avengers 4: the squeakquel |
    | 9:00PM        | Avengers 4: the squeakquel |


3. Input: The input to the program would be a list of movies, these movies will be checked    against the database of movies already used to check movie details
    #### Input sample
    | Movie                      | 
    |:-------------------------: |
    | Avengers Infinity War      | 
    | Avengers 4: the squeakquel |
    | Venom      |  
    | Halloween |


4. User Interface: There is a box to enter a movie into, with a link underneath to import a list of movies as a text file. A schedule that updates as movies are added into the list. A sidebar where you can click and list all movies by overall rank (which includes details for each movie)



5. Types List: Our program will read in information of movies such as Rotten Tomatoes score, and box office numbers, length of the movie, genre and advisory rating. The program will create a weighted score for each movie. Rank movies in order from best to worst (highest weighted score best, lowest weighted score worst).  We will then create an array of priority queues depending on genre and restrictions due to time slot and box office success and other information provided to decide what movies to show at various time slots. 

    #### Most popular time slots to least popular time slots:
    * 7pm - 12am (Prime Time)
    * 3pm - 7pm (Early Fringe)
    * 10am - 3pm (Daytime TV)
    * 6am - 10am (Early Morning)
    * 12am - 6am (Graveyard)

    #### Details Required for Each Individual Movie:
    * Rotten Tomatoes Score
    * Box Office success
    * Genre
    * Advisory Rating
    * Length of the Movie (rounded to closest 30)



#### Name each interface or class and briefly describe its function or purpose.
* A movie class. Hold information for each individual movie
* A priorityQueue class. Orders movies from best to worst by weighted score. 
* A scheduler class. Chooses items from a certain priorityQueue and places into schedule array. Does this until schedule is full.
* UI class. Creates user interface for Monday Movie Madness.


## Edit and Submit this file and any figures referenced by this document.

