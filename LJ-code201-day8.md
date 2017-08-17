I had a lot of trouble during the lab today getting my JS to interface with the
correct elements in my HTML file. The TA's were mostly busy, so I got some help
from a 301 student, who actually kind of led me astray. A 401 student swooped in later
and helped me find the answer. What I was missing is that in order to pull
the user input from my text box elements, I had to use the name attribute I had
given them earlier. Like this:

event.target.THENAMEGOESHERE.value;

I had been trying OBJECT.target.['THENAMEGOESHERE'].value;

After I got to the bottom of that issue, everything flowed pretty naturally,
but I was pretty frustrated for most of the lab time.
