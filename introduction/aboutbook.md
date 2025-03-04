Python Is a Full-Spectrum Language/
Both Scratch and C++ are decidedly not what I would call fullspectrum languages. 
In the Scratch level, it’s easy to start but you have to switch to a “real” language to build real applications.
Conversely, you can build real apps with C++, yet there is no gentle on-ramp. 
You dive head first into all the complexity of that language which exists to support these rich applications.
Python, on the other hand, is special. It is a full-spectrum language.
We often judge the simplicity of a language based on the “hello world” test. 
That is, what syntax and actions are necessary to get that language to output “hello world” to the user? In Python, it couldn’t be simpler:
```bash
print("Hello world")
```
Here’s the new test: 
What would it take to write a program that accesses an external website, downloads the content to your app in memory, then displays a subsection of that content to the user?
```bash
import requests
resp = requests.get("https://realpython.com")
html = resp.text
print(html[205:294])
```
Incredibly, that’s it. When run, the output is (something like):
```bash
<title>Python Tutorials – Real Python</title>
<meta name="author" content="Real Python">
```
This is the easy, getting started side of the spectrum of Python. 
A few trivial lines and incredible power is unleashed. 
Because Python has access to so many powerful but well-packaged libraries, such as requests, it is often described as having batteries included.

YouTube, the world’s most popular video streaming site, is written in Python and processes more than 1,000,000 requests per second. 
Instagram is another example of a Python application , we even have realpython.com

StackOverсow Trends.You can explore this chart and create similar charts to this one over at
insights.stackoverflow.com/trends.

Developers who are not developing with the language
or technology but have expressed interest in developing
with it 
