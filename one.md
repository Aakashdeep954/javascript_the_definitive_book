<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <link rel="stylesheet" href="style.css" />
        <title>My project</title>
    </head>
    <body>
        <div id="container">
            <div id="menu-container">
                <div id="menu">
                    <ul class="menu-content">
                        <li>
                            chapter 1: introduction to javascript
                            <ul>
                                <li>chapter 1: introduction to javascript</li>
                            </ul>
                        </li>
                    </ul>
                </div>
            </div>
            <div id="content-container">
                <div id="content">
                    <h5>8.2.1 Function invocation</h5>
                    <p>
                        Functions are invoked as functions or methods with an
                        invocation expression.An invocation expression consists
                        of function expression that evaluates to a function
                        object follwed by an open parenthesis, a comma seperated
                        zero or more arguments.
                    </p>
                    <h5>8.2.2 Method invocation</h5>
                    <p>
                        A method is nothing more than a function that is stored
                        in a property of an object.Method invocation differ from
                        regular function invocation in one important way that is
                        invocation context.
                    </p>
                    <h5>8.2.3 Constructor invocation</h5>
                    <p>
                        if a function or method invocation is preceded by
                        keyword new then it is contructor invocation.
                    </p>
                    <h5>8.2.4 Indirect invocation</h5>
                    <p>
                        javascript functions are objects like all javascript
                        objects they too have methods.Two of these methods
                        call() and apply() invoke the function indirectly this
                        means you can invoke any function as a method of any
                        object even it is not actually a method of that object.
                    </p>
                    <h5>8.3.1 Optional parameters and defaults</h5>
                    <p>
                        when a function is invoked with a fewer arguments than
                        declared parameters the additional parameters are set to
                        undefined. when desingning functions with optional
                        arguments you should be sure to put the optional ones at
                        the end of the argument list so they can be omitted.
                    </p>
                </div>
            </div>
        </div>

        <script src="app.js"></script>
    </body>

</html>
