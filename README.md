# drawing_canvas
This program logic is mainly built around the below two main classes-
1) MyDrawingCanvas : this is the canvas object class under "console_object" package. It contains the actual implementation methods for drawing various shapes like a line(makeALine()), rectangle (makeARectangle()) or fill selected area with certain character(fillDrawing()).

2) Draw :  This class in the package "console_object" takes user inputs and creates the required object instance of the MyDrawingCanvas class. It then calls the corresponding shape methods of MyDrawingCanvas to output the desired shape in the user's canvas.



Running the app:
mvn compile exec:java -Dexec.mainClass="console_creator.Draw"

Running tests :
mvn -Dtest=console_object.DrawingTest test
