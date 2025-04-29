# cmsc203-lab-2-solved
**TO GET THIS SOLUTION VISIT:** [CMSC203 Lab 2 Solved](https://www.ankitcodinghub.com/product/cmsc203-gui-lab-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115016&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC203  Lab 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
Overview: In the Graphical User Interface (GUI) Lab we will construct a simple GUI step by step.

FXDriver: (Initial version provided to the student) The class called FXDriver is the starting point for the FX version of the GUI. FX is the framework we will use, and is available beginning with Java 8. There are many ways to organize the GUI, but one way is to hold the basic startup features in a single simple file, which calls an instance of the main panel.

In FX, the main method (as in any Java application) is the starting point. In FX it calls only the method launch(args), where args is the array of data passed in to the application, usually null. This launch method executes various setup code, hidden from the programmer, including creating a so-called “stage”, and calls the method start(Stage stage); Everything that the programmer wants to execute must be placed in start.

FXMainPane: (Initial version provided to the student) In this approach to GUI building, an instance of the class FXMainPane does all the programmer’s work of creating the GUI. The initial version is simply a stub with a constructor, so that FXDriver will compile and run.

Each task has a comment in the java files such as //student Task #n with a statement about what is to be accomplished.

Task #1

1) Create a java project in Eclipse. Load the files FXDriver.java, FXMainPane.java, and DataManager.java from Blackboard into this project.

2) In the FXDriver class, create an instance of FXMainPane and set it to a new instance of FXMainPane called root.

3) Using the parameter called stage (provided by Java FX when launch calls start), call the method stage.setScene(new Scene(root, [width],[height])); The parameters width and height specify the dimensions of the scene window in integer pixels.

Compile and run. Note that a window appears but does not have any content.

Take screenshots of run a program.

Task #2

Note that FXMainPane extends VBox, so the class is a VBox.

1) In the FXMainPane class, declare five buttons, a label, and a textfield. Declare two HBoxes that will hold the these components and go inside the VBox.

2) Instantiate the buttons with the arguments “Hello”, “Howdy”, “Chinese“, Clear”, and “Exit”.

3) Instantiate the label with the argument “Feedback:”.

4) Instantiate the textfield.

5) Instantiate the HBoxes.

6) Compile and run the FXDriver.

7) Take screenshots of run a program.

Note that even though the buttons and other components are instantiated, they do not appear in the window.

Task #3

To cause components to appear, they must be added to a containing component, which itself is added to its containing component, all the way up to the component that is added to Scene.

1) Add the buttons to one of the HBoxes using hBox.getChildren().addAll(button1, etc…)

2) Add the label and the textfield to the other HBox

3) Add the HBoxes to the FXMainPane (which is a VBox) using getChildren().addAll(…). Note that we have already added FXMainPane to the new Scene in FXDriver.

4) Compile and run the FXDriver.

5) Take screenshots of run a program.

Note two things: The buttons do not respond to mouse-clicks, and the components are not well-spread, but are all positioned in the upper left corner of the containing window.

Task #4

1) Declare an instance of DataManager at the FXMainPane class level so that its scope extends throughout the class. Instantiate it in the constructor.

2) To set the buttons to respond to mouse-clicks,

a) create an inner class at the class level (for example, called ButtonHandler) that implements EventHandler&lt;ActionEvent&gt;. For each button, use button.setOnAction(new ButtonHandler()).

b) This interface requires the method handle(ActionEvent event) to be implemented. The mouse event is provided to the handle method, and event.getTarget() returns the object that caused the event, allowing a selection to be made.

c) Implement an if-else-if structure that gets the target button that was selected and executes the appropriate block of code.

i) If the “Hello”, “Howdy” or “Chinese” buttons were selected, call the DataManager instance’s methods getHello, getHowdy, or getChinese and call the text field’s method setText with the response from the DataManager.

ii) If the “Clear” button was selected, call the text field’s method setText(“”); to clear out the text field.

iii) If the “Exit” button was selected, call Platform.exit(); and System.exit(0);

3) Position the components so they are generally centered and spaced apart.

a) To set margins for each component, call the static method on the containing component, e.g., HBox.setMargin(button1, inset); where inset is an instance of the class Inset.

b) To center each HBox, use hBox.setAlignment(Pos.CENTER); where Pos is an Enum that will need to be imported.

4) JUST FOR FUN (optional): create a sixth button that says “Hello” in another language. Add a method to the DataManager class to return the string.

5) Add the files to GitHub in a directory named CMSC203_Lab2

6) Compile and run FXDriver. Select each of the buttons to ensure they are working correctly.

7) Take screenshots of run the program.

Deliverables:

1) Submit the three java files to Blackboard.

2) Submit screenshots of run Program for each Task: Task#1, Task#2, Task#3, Task#4 to confirm all buttons work.
