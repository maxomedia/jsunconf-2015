Responsive testing with Galen
===
Speaker: Martin Reinhardt  
GitHub: https://github.com/hypery2k  
Date of the talk: 2015-04-25

Galen (https://github.com/galenframework/galen) is a framework for layout and functional testing for websites. It's built with Java and comes with it's own, simple definition syntax. The syntax is white space sensitive and easy to learn, even for designers.

Apart from reading the beginners guide, here are some useful tips:
- Avoid testing against strict pixel values, as browsers tend to render things differently (who would have thought it)
- Define a global acceptance range (maybe 3%, see which value fits your case best)
- Do not test every last element of your page. Concentrate on the most important parts (header, footer, important modules)
- Use variables and import spec files across tests

