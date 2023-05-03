Download Link: https://assignmentchef.com/product/solved-cpt120-tutorial-8
<br>



<ol start="3">

 <li>Follow the materials under Canvas→ <a href="https://rmit.instructure.com/courses/56609/modules">Modules→We</a> <a href="https://rmit.instructure.com/courses/56609/modules">e</a><a href="https://rmit.instructure.com/courses/56609/modules">k</a> <a href="https://rmit.instructure.com/courses/56609/modules">8</a>…</li>

</ol>

<table width="771">

 <tbody>

  <tr>

   <td width="771">5.1. With the help of your group tutors via the Canvas→Discussion forums and by using good Object Oriented (OO) coding practices (also required for Assignment 3), convert the MusicLibraryW7.java (from IIE7 or your latest version) to an OO application as per the following description:<strong>Song.java: </strong>A <em>Song</em> object cannot be created without a <em>song title</em> and a String containing the <em>location</em> of the song in the computer (e.g. “<u>c:/song.mp3</u>”). It also has the relevant accessor (get) methods but no mutator (set) methods. A Song must not have any methods that will display messages. Only its constructor and the above two methods can be accessed by other classes. Write the code for this in a new class named <strong>Song.java</strong>.<strong>MusicLibrary.java</strong>: A <em>MusicLibrary </em>object cannot be created without a <em>maximum number of songs</em>. A <em>MusicLibrary </em>object also has an array of <em>Song </em>objects (the size of this array can be set to the <em>maximum number of songs specified</em>) and the <em>number of currently added songs</em>. It must not have the separate arrays songTitles and songLocations anymore. Move all of the code from the main method to the constructor first then refactor the code in to different methods so that you have at least one method per menu item. Aside from the methods, no other component of this class should be accessible by other classes. As it is the application class, the <em>MusicLibrary </em>has a main method and this method must contain only the following line (then the return statement):MusicLibrary ml=new MusicLibrary(100);In the above, the 100 refers to the maximum number of songs.<strong>Remember, when doing OO in Intro To Prog:</strong> Follow the guidelines given in Canvas→Assignments→Assignment 3 (guidelines). You must not create anything <em>static </em>other than<em> public static void main</em>. All object member variables must be <em>private </em>and they must only be initialised inside the constructor (including the creation of arrays). Any references to member variables from within methods should start with “this.”. There is no need for private methods. You will need to write a constructor for each class and you must prevent the creation of objects that are invalid (e.g. don’t create a second constructor that will allow you to create a <em>Song</em> object with no song title or location). Use only standard arrays in Java (e.g. avoid ArrayList, etc.). You must not use break, continue, System.exit(). Use only while loops for repetition. When possible, you must use concepts covered in standard class materials over others.</td>

  </tr>

  <tr>

   <td width="771">5.2. Add comments in the style required by Assignment 2/3. See rubric section in Assignment 2/3 PDF.</td>

  </tr>

 </tbody>

</table>