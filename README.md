<h1>A simple calculator</h1>
This is a simple calculator application used to perform addition, subtraction, multiplication and division. 
As I am a learning bud in python and its frameworks, I just liked to create a basic application thats why I used Flask framework to run the application.
<h2>Requirements</h2>
Installation and python and flask is required for this project. Use the following to install those.<br>
<code>pip install python </code><br>
<code>pip install flask</code>
<h2>Description</h2>
In this program i created three files namely<br>
<b>Calculator.html</b> to create a calculator template which acts as the front end.<br>
<b>main.css</b> to style the calculator buttons and the input types.<br>
<b>app.py</b> to run the application using flask.
<h2>Explanation</h2>
First I created the app.py python file using the basic template.
<pre>app = Flask(__name__)
@app.route('/')
def index():
    return render_template('calculator.html')
if __name__ == '__main__':
    app.run(debug=True)
    </pre>
Then I created the required HTML page with all the necessary input buttons for the calculator from 0 to 9 and the symbols for calculator and a clear button to clear the result field. Then I moved onto the css file to decorate the page with borders, colors, shape and many more..<br>
A very simple javascript is added to the end of the body block to perform the functions of the calculation involved in the application. Keyboard lsitener is added to make sure the user can also enter the input from the keyboard.
<h3>Conclusion</h3>
This is all for the basic simple calculator application. Since I am a newbie I didnt added many feautures but it will be updated one by one.<br>
<h2>Thanks for your time to read about my application :)
