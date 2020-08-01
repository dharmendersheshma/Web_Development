# Netflix-Clone
***
[![N|Solid](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/70px-React-icon.svg.png)](https://reactjs.org/)[![N|Solid](https://img.icons8.com/color/48/000000/firebase.png)](https://firebase.google.com/) &nbsp; &nbsp;&nbsp; [![N|Solid](http://www.simpleimageresizer.com/_uploads/photos/84870d60/tmdb_50x50.png)](https://www.themoviedb.org/)
***
### [Website Link](https://netflix-995b1.web.app/)
**Netflix Clone** is a website developed using **React JS** and deployed on **Firebase**.

(Here I will use word 'Clone' to refer to the cloned Netflix website)

The UI of the website is just like the Netflix website, all the movie posters were taken from TMDBI website which is a free website which provides API for all the movie information available on orignial Netflix website.
**Note:** This clone does not provide you the original content or the full movies as it is just a clone and Netflix does not allow this without an account.
***
## Description

The clone is made by three building blocks:
1. The Nav bar.
2. The Banner
3. The rows.

#### 1. The Nav Bar
- This block contains original Netflix logo and an Avatar as original Netflix have.
- The bar becomes solid black when we scroll down which gives it a smooth transition effect and when we roll we scroll up back than the solid color fades away in a transition.
- The avatar in the right **does not** contain the clickable link, but this can be changed to give sign and other options.

#### 2. The Banner
- The Banner is the container which contains the big poster of a movie randomly choosen from the Netflix originals category.
- This is accompanied by two buttons with hover effects and a description text.
- Banner also have the same fading in the bottom of poster as the original site.

#### 3. The Rows
- This is the main continer for all the movies divided into their respective categories, which are: 
   * NETFLIX ORIGINALS
   * Trending now
   * Top Rated
   * Action Movies
   * Comedy Movies
   * Horror Movies
   * Romance Movies
   * Documentaries
- All these rows can be srolled in X-direction to extend the list.
- Each movie have an hover effect and when clicked it plays a YouTube trailer in a pop up.
***
#### TMDB API
The whole data of the movies is taken from **The Movie DataBase(TMDB)** using API provided by it in the form of JSON.
Link to the Website: [Click Here!](https://www.themoviedb.org/)
***
##### Note:
When poster of movie is cicked, sometimes the trailer played is not of the given movie. This is because the react-youtube library is used to search the trailer from youtube by using the name of movie taken from TMDB and there can be two movies with the same name.
***
##### This whole video tutorial for the clone is availabe on YouTube, link is given below: 
[**Video Tutorial**](https://www.youtube.com/watch?v=XtMThy8QKqU)
***
##### Disclaimer: This is an open source project and can be used as per requirement of the user.
****

### Happy Coding!! 🙂



