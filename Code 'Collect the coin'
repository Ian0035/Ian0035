import random
import turtle as t
t.bgcolor('grey')


man = t.Turtle()
man.shape('square')
man.color('blue')
man.speed(0)
man.penup()
man.hideturtle()

bullet = t.Turtle()
bullet.shape('square')
bullet.color('yellow')
bullet.speed(0)
bullet.penup()
bullet.hideturtle()



badman = t.Turtle()
badman.shape('square')
badman.color('red')
badman.speed(0)
badman.penup()
badman.hideturtle()

badman2 = t.Turtle()
badman2.shape('square')
badman2.color('red')
badman2.speed(0)
badman2.penup()
badman2.hideturtle()

badman3 = t.Turtle()
badman3.shape('square')
badman3.color('red')
badman3.speed(0)
badman3.penup()
badman3.hideturtle()

badman4 = t.Turtle()
badman4.shape('square')
badman4.color('red')
badman4.speed(0)
badman4.penup()
badman4.hideturtle()

badman5 = t.Turtle()
badman5.shape('square')
badman5.color('red')
badman5.speed(0)
badman5.penup()
badman5.hideturtle()

badman6 = t.Turtle()
badman6.shape('square')
badman6.color('red')
badman6.speed(0)
badman6.penup()
badman6.hideturtle()

badman7 = t.Turtle()
badman7.shape('square')
badman7.color('red')
badman7.speed(0)
badman7.penup()
badman7.hideturtle()

coin = t.Turtle()
coin.shape('circle')
coin.color('gold')
coin.penup()
coin.hideturtle()
coin.speed(0)



spel_gestart = False
tekst_turtle = t.Turtle()
tekst_turtle.write('Druk SPATIE om te beginnen', align='center',\
                   font=('Arial', 16, 'bold'))
tekst_turtle.hideturtle()

score_turtle = t.Turtle()
score_turtle.hideturtle()
score_turtle.speed(0)



def buiten_venster(man):
    muur_links = -t.window_width() / 2
    muur_rechts = t.window_width() / 2
    muur_boven = t.window_height() / 2
    muur_onder = -t.window_height() / 2
    (x, y) = man.pos()
    buiten = \
           x< muur_links or \
           x> muur_rechts or \
           y< muur_onder or \
           y> muur_boven
    return buiten
    
def game_over():
    man.color('red')
    coin.color('grey')
    t.penup()
    t.hideturtle()
    t.color('red')
    t.write('GAME OVER!', align='center', font=('Arial', 30, 'normal'))

def toon_score(huidige_score):
    score_turtle.clear()
    score_turtle.penup()
    x = (t.window_width() / 2) - 50
    y = (t.window_height() / 2) - 50
    score_turtle.setpos(x, y)
    score_turtle.write(str(huidige_score), align='right', \
                       font=('ARIAL', 40, 'bold'))
def plaats_coin():
    coin.ht()
    coin.setx(random.randint(-200, 200))
    coin.sety(random.randint(-200, 200))
    coin.st()

def plaats_badman():
    (man_x, man_y) = man.pos()
    badman.ht()
    proposed_x = random.randint(-200, 200)
    proposed_y = random.randint(-200, 200)
    while abs(proposed_x - man_x) < 40 and abs(proposed_y - man_y) < 40:
      proposed_x = random.randint(-200, 200)
      proposed_y = random.randint(-200, 200)
    badman.setx(proposed_x)
    badman.sety(proposed_y)
    badman.st()
    
def plaats_badman2():
    (man_x, man_y) = man.pos()
    badman2.ht()
    proposed_x = random.randint(-200, 200)
    proposed_y = random.randint(-200, 200)
    while abs(proposed_x - man_x) < 40 and abs(proposed_y - man_y) < 40:
      proposed_x = random.randint(-200, 200)
      proposed_y = random.randint(-200, 200)
    badman2.setx(proposed_x)
    badman2.sety(proposed_y)
    badman2.st()

def plaats_badman3():
    (man_x, man_y) = man.pos()
    badman3.ht()
    proposed_x = random.randint(-200, 200)
    proposed_y = random.randint(-200, 200)
    while abs(proposed_x - man_x) < 40 and abs(proposed_y - man_y) < 40:
      proposed_x = random.randint(-200, 200)
      proposed_y = random.randint(-200, 200)
    badman3.setx(proposed_x)
    badman3.sety(proposed_y)
    badman3.st()

def plaats_badman4():
    (man_x, man_y) = man.pos()
    badman4.ht()
    proposed_x = random.randint(-200, 200)
    proposed_y = random.randint(-200, 200)
    while abs(proposed_x - man_x) < 40 and abs(proposed_y - man_y) < 40:
      proposed_x = random.randint(-200, 200)
      proposed_y = random.randint(-200, 200)
    badman4.setx(proposed_x)
    badman4.sety(proposed_y)
    badman4.st()

def plaats_badman5():
    (man_x, man_y) = man.pos()
    badman5.ht()
    proposed_x = random.randint(-200, 200)
    proposed_y = random.randint(-200, 200)
    while abs(proposed_x - man_x) < 40 and abs(proposed_y - man_y) < 40:
      proposed_x = random.randint(-200, 200)
      proposed_y = random.randint(-200, 200)
    badman5.setx(proposed_x)
    badman5.sety(proposed_y)
    badman5.st()

def plaats_badman6():
    (man_x, man_y) = man.pos()
    badman6.ht()
    proposed_x = random.randint(-200, 200)
    proposed_y = random.randint(-200, 200)
    while abs(proposed_x - man_x) < 40 and abs(proposed_y - man_y) < 40:
      proposed_x = random.randint(-200, 200)
      proposed_y = random.randint(-200, 200)
    badman6.setx(proposed_x)
    badman6.sety(proposed_y)
    badman6.st()

def plaats_badman7():
    (man_x, man_y) = man.pos()
    badman7.ht()
    proposed_x = random.randint(-200, 200)
    proposed_y = random.randint(-200, 200)
    while abs(proposed_x - man_x) < 40 and abs(proposed_y - man_y) < 40:
      proposed_x = random.randint(-200, 200)
      proposed_y = random.randint(-200, 200)
    badman7.setx(proposed_x)
    badman7.sety(proposed_y)
    badman7.st()

def schiet():
    schiet = True
    (x, y) = man.pos()
    bullet.ht()
    bullet.setx(x)
    bullet.sety(y)
    bullet.st()
    
    bullet_snelheid = 50
    bullet.lenght = 1.5
    bullet.showturtle()
    
            
    while True:
        if man.heading() == 0:
            bullet.setheading(0)
    
        if man.heading() == 90:
            bullet.setheading(90)
            
        if man.heading() == 180:
            bullet.setheading(180)
        
        if man.heading() == 270:
            bullet.setheading(270)
            
        bullet.forward(bullet_snelheid)
        man.forward(0)

        if bullet.distance(badman) < 30 :
            plaats_badman()
            

        if bullet.distance(badman2) < 30 and score > 40  :
            plaats_badman2()

        if bullet.distance(badman3) < 30 and score > 90  :
            plaats_badman3()

        if bullet.distance(badman4) < 30 and score > 140  :
            plaats_badman4()

        if bullet.distance(badman5) < 30 and score > 190  :
            plaats_badman5()

        if bullet.distance(badman6) < 30 and score > 240  :
            plaats_badman6()

        if bullet.distance(badman7) < 30 and score > 290  :
            plaats_badman7()
            
        if buiten_venster(bullet):
            return
    

    
def start_spel():
    global spel_gestart
    global score
    if spel_gestart:
        return
    spel_gestart = True
    score = 0   
    tekst_turtle.clear()

    man_snelheid = 2
    man_lengte = 2
    man.shapesize(2, man_lengte, 2)
    man.showturtle()
    toon_score(score)
    plaats_coin()
    plaats_badman()
    
    
    while True:
        man.forward(man_snelheid)
        if man.distance(coin) < 20 :
            plaats_coin()
            score = score + 10
            toon_score(score)
            plaats_badman()
            if score > 40 :
                plaats_badman2()
            if score > 90 :
                plaats_badman3()
            if score > 140 :
                plaats_badman4()
            if score > 190 :
                plaats_badman5()
            if score > 240 :
                plaats_badman6()
            if score > 290 :
                plaats_badman7()
            
        if buiten_venster(man):
            game_over()
            break
        if man.distance(badman) < 30 :
            game_over()
            break
        if man.distance(badman2) < 30 and score > 40 :
            game_over()
            break
        if man.distance(badman3) < 30 and score > 90 :
            game_over()
            break
        if man.distance(badman4) < 30 and score > 140 :
            game_over()
            break
        if man.distance(badman5) < 30 and score > 190 :
            game_over()
            break
        if man.distance(badman6) < 30 and score > 240 :
            game_over()
            break
        if man.distance(badman7) < 30 and score > 290 :
            game_over()
            break

def naar_boven():
    if man.heading() == 0 or man.heading() == 180:
        man.setheading(90)

def naar_onder():
    if man.heading() == 0 or man.heading() == 180:
        man.setheading(270)

def naar_links():
    if man.heading() == 90 or man.heading() == 270:
        man.setheading(180)

def naar_rechts():
    if man.heading() == 90 or man.heading() == 270:
        man.setheading(0)
        
t.onkey(start_spel, 'space')
t.onkey(naar_boven, 'Up')
t.onkey(naar_rechts, 'Right')
t.onkey(naar_onder, 'Down')
t.onkey(naar_links, 'Left')
t.onkey(schiet, 's')

t.listen()
t.mainloop()
