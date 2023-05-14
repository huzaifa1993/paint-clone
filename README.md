# paint-clone
This project is a painting application that allows users to create artwork using various tools and features.<br>


Features:<br>
-Drawing tools: pencil, brush, eraser.<br>
-Color palette for selecting drawing colors.<br>
-Save buttons for saving drawings in .png format.<br>
-Save,load and clear from local storage.<br>

programing languages:<br>
-HTML<br>
-CSS<br>
-JAVASCRIPT<br>

Function:<br>
*displayBrushSize():<br>
-this function is called to display the current brush size to the user.<br>
-If the brush size is less than 10, it sets the text content of an element with an ID of   brushSize to the current brush size with a leading zero.<br>
-Otherwise, it sets the text content to the brush size without a leading zero.<br>
-it does not take parameter.<br>
-it returns void.<br>

*switchToBrush():<br>
-this function is called to switch the active drawing tool to a brush.<br>
-isEraser is set to false to indicate that the eraser is no longer the active tool.<br>
-The text content of an HTML element with an ID of activeToolEl is set to "Brush" to indicate that the brush is the new active tool.<br>
-The color of an HTML element with an ID of brushIcon is set to black to indicate that the brush icon is now selected.<br>
-The color of an HTML element with an ID of eraser is set to white to indicate that the eraser is no longer selected.<br>
-currentColor is set to the current brush color selected by the user using an HTML input element with an ID of brushColorBtn.<br>
-currentSize is set to 10 to indicate the default brush size.<br>
-The value of brushSlider is set to 10 to indicate the default brush size.<br>
-The displayBrushSize() function is called to update the UI and display the current brush size to the user.<br>

*createCanvas():<br>
-this function is called to create and initialize a new canvas element.<br>
-sets the width and height of the canvas element (canvas) to the width and height of the current browser window using window.innerWidth<br>
-set the window.innerHeight. The height is reduced by 50 to account for the height of other UI elements on the page.<br>
-sets the fill color of the canvas context (context) to bucketColor<br>
-fills the entire canvas with the bucket color using the fillRect() method.<br>
-The canvas element is appended to the body of the HTML document.<br>
-switchToBrush() function is called to switch to the brush tool and update the UI.<br>



