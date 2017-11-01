## Movie Library Manager (Implemented in Java & C++)

This project is a Java and C++ movie library browser/manager including video playback.

The Java program uses javax.swing components to present a view that includes
a JTree in the left panel and a panel for composing and displaying details of the
movie's description in the right pane.

The C++ program uses the library package FLTK (fast light toolkit).

#### The library includes the following functionality: 

-  Getting and setting the contents of text fields (JTextField), and text areas (JTextArea).

- Drop-down lists (actors and genre) are editable, which allows the user to add new values 
  into the displayed selection, as though they were a text-field. Hitting the return (enter)
  key when the user completes an edit causes the actionPerformed method to be called 
  (NewActor and NewGenre action commands).
  
- The clear buttons are also handled by the actionPerformed method with different action
  commands, each causing the respective combo box to be cleared. Hitting return in the
  actors combo box causes the new text to be added to the combo box, if its not already there.
  These actions will be useful setting up the actors and genre that would be done when adding
  a new movie to the library.
  
______________________________________________________________________________________________
 
![alt text](https://raw.githubusercontent.com/tdirusso/MovieLibrary/master/movieLib.png)
