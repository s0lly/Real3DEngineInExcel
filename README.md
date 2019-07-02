# Real3DEngineInExcel
Real 3D Engine in Excel, following the logic presented in Chili's 3D Fundamentals YouTube series


Real 3D Engine in Excel


ReadMe

This excel file allows you to gain an intuitive understanding of how 3D rasterization works in the basic setting of an excel workbook.
This logic underpinning this model is based on a number of must-watch tutorials from the YouTuber Chili. The entire playlist to his 3D Fundamentals series is here:
https://youtu.be/uehGqieEbus
However, this model only implements a select number of concepts from the series, as oddly not everything is portable to our favourite application!
I hope this is of help for those trying to learn the basics of 3D Graphics!

Instructions:

First, you need to go to the sheet named "Screen"

The camera can be controlled manually by editing its location and rotation variables in cells GM116:GO117
The box / object can be moved / rotated via cells GM114:GO115
Note that the rotation variables are in radians, not degrees. The camera starts at lcoation (0,0,0), facing the positive Z direction (following the "left hand rule" with Y up, and Z "into" the screen).

Alternatively, you can press the "ANIMATE" button which will move the camera along a predetermined path. This path is listed in columns HF-HL on the 'Screen' tab.
This button changes the cell labelled "CurrentScene" to animate over the entire predetermined scene.
Please reset the model to the GitHub-sourced version to ensure that all formulae are present before attempting this, as it may otherwise not work.

PLEASE NOTE: The formulae "break down" when geomtry lies behind the camera. As such, try ensure that the geometry of interest lies in front of the camera's viewing plane. I haven't fixed this bug yet!!

The logic of the tabs follow the following order: "Objects" -> "Transforms" -> "Triangles" -> "Screen"
The logic used follows that taken by Chili in his series linked to above - I will avoid attempting to explain it as he does a much better job at it than I could!
I hope this helps you in your journey to learning 3D graphics!

by s0lly
https://www.youtube.com/c/s0lly
https://www.instagram.com/s0lly.gaming/
https://twitter.com/s0lly

THE MODEL IS PROVIDED WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE MODEL OR THE USE OR OTHER DEALINGS IN THE MODEL.
