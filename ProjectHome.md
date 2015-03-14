NXTurtle is a mashup of the [Python Turtle graphics for TK](http://docs.python.org/library/turtle.html) module and the LEGO Mindstorms driver [NXT-Python](http://code.google.com/p/nxt-python/).

It allows you to control a LEGO Mindstorms robot like the [turtle](http://en.wikipedia.org/wiki/Turtle_(robot)) known from the [Logo programming language](http://en.wikipedia.org/wiki/Logo_(programming_language)).




### Status ###
This is a hollyday project and barely tested.

Just to remind you
```
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

Having said that: Have fun!
Any feedback is welcome :-)


### Requirements  and installation ###

  1. This project builds on Python and [NXT-Python](http://code.google.com/p/nxt-python/).<br>Read the <a href='Installation.md'>installation instructions</a> for details.<br>
<ol><li>Build your LEGO Mindstorms turtle. The robot should meet some requirements.<br>Read the <a href='ConstructAndCalibrate.md'>build instructions</a> for details.<br>
</li><li>Calibrate your turtle (also described in the build instructions).</li></ol>

After this, you are ready to use it:<br>
<br>
<br>
<h3>Example</h3>

<pre><code>from nxturtle import NXTurtle
yertle = NXTurtle(connect=True)

# [... some initialization ...]

# standard turtle action
yertle.pendown()
yertle.forward(10)
yertle.left(90)
yertle.home()

# and some more bricky capabilities
yertle.play_tone(440, 500)
</code></pre>

Read the <a href='Tutorial.md'>tutorial</a> for more...<br>
<br>
<br>
<hr><br>
<br>
<br>
<a href='http://www.youtube.com/watch?feature=player_embedded&v=5xIK6iFTDzM' target='_blank'><img src='http://img.youtube.com/vi/5xIK6iFTDzM/0.jpg' width='425' height=344 /></a>