# ping-pong

PING PONG GAME

The code is a basic implementation of a two-player Ping-Pong game using the Python turtle module. The game consists of two paddles, one on each side of the screen, and a ball that bounces back and forth between them. The players use the keyboard to control their respective paddles and try to prevent the ball from going past them. The game keeps track of the score and updates it accordingly, and it also includes sound effects for when the ball hits a paddle or a wall. The game loop continues until it is manually stopped.

STEP 1 :For the implementation part of this game ,turtle and OS modules are used.

STEP 2 : For creation of window Screen() method is used and properties were set using various functions like title(), bgcolor(), setup(), and tracer().

STEP 3 : Two paddles (left and right)using the Turtle() were created and properties were set like shape(), color(), speed(), and goto().

STEP 4: Create a ball using the Turtle() method and set its properties like shape(), color(), speed(), penup(), and goto() and then a pen object to display the score using the Turtle() method and set its properties like speed(), penup(), and hideturtle()

STEP 5: four functions(paddle_left_up(),paddle_left_down(),paddle_right_up(), paddle_right_down()) were declared for controlling the paddles using keyboard.

STEP 6: Bind the arrow keys to the corresponding functions using the onkeypress() method and the listen() method.

STEP 7:Move the ball using setx() and sety() method

STEP 8: set up the border using xcor() and ycor() method

STEP 9: If the ball hits the borders, change the direction of the ball and play a sound using the os.system() method. Also, update the score for the player who scored using the player_a_score and player_b_score variables and display the updated score on the screen using the clear() and write() methods.

STEP 10:If the ball collides with the paddles, change the direction of the ball and play a sound using the os.system() method.

STEP 11:The while loop will keep running until the user closes the game window.
