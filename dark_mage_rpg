from dialogue import leftpath, entercave, nocandle, yescandle, usemace, spell1, spell2, flee, explorehut, sneakhut, \
    snoopsnoop, invisibletime, gunsakimbo, rightpath, intro, yeschug, nochug, escape, rosebushgo, aghthepain, \
    painisforwimps, hanselgretle, pitchforks, forest, castle, playalong, killfae, gardendate, helpfae, forbiddendate, \
    sleepin, flirt, cockblock, marry, dutycalls, mushroomland, temple, templeleft, templeright, touchlegold, \
    notouchgold, templemace, templespell, amulettrap, takeleamulet, vault, drawbridge, library, breaklamp, ignorelamp, \
    towertime, redbottle, purplebottle, vore, lampnogone, lalune, ignorelibrary, bigepicfight, reliquary


def kill():
    exit(-1)


def error():
    print("That is not a valid option.")


def par():
    print("")


def normalend():
    print("Congratulations " + name, "you have cleared the game!")
    print("Try replaying to see if you can get another route!")


def trueend():
    print('''When you returned from the litch's castle, you were paraded through the village's streets, and given a 
hefty amount of treasure to take back with you on your adventure, as well as the title of village hero. Although 
you would've liked to stay behind a bit longer, you knew that more adventures waited. And so, the next day before
dawn, you left the town to explore other unknown places, to wherever fate brings you.''')
    par()
    print("Congratulations " + name, "you have gotten the true ending of the game!")
    print("I hope you have enjoyed your journey through this land!")
    print("If this is the first ending you have gotten, please consider replaying to see what the other options give!")


print("Welcome to The Dark Mage, a text-based RPG written by Phosphiride.")
name = input("Please enter your name")
print("Hello, " + name)
intro()
par()


while True:

    a1 = input("Do you go [left] or [right]?")
    par()

    if a1 == "left":
        leftpath()
        par()

        while True:
            a2 = input("Do you go towards the [cave], or the [hut]?")
            par()

            if a2 == "cave":
                entercave()
                par()

                while True:
                    a3 = input("Do you light a candle?")
                    par()

                    if a3 == "no":
                        nocandle()
                        par()
                        print("You lay on the floor, becoming the creature's lunch. Better luck next time, " + name)
                        kill()

                    elif a3 == "yes":
                        yescandle()
                        par()

                        while True:

                            a4 = input("Do you [fight] or [flee]?")
                            par()

                            if a4 == "fight":
                                print("You prepare for battle. There is a mace hanging by your leg, and you also have "
                                      "a wide arsenal of spells at your disposal.")
                                par()

                                while True:

                                    a5 = input("Do you use the [mace], or cast a [spell]?")
                                    par()

                                    if a5 == "mace":
                                        usemace()
                                        print(name, "was hailed as a village hero for ridding them of the menace.")
                                        par()
                                        normalend()
                                        kill()

                                    elif a5 == "spell":
                                        spell1()
                                        par()

                                        speak1 = input("What do you reply with?")
                                        par()

                                        print('"' + speak1, '" you say as the person gets up. He clumsily dusts off '
                                                            'his pants, and nods at your words.')
                                        spell2()
                                        par()
                                        normalend()
                                        kill()

                                    else:
                                        error()

                            elif a4 == "flee":
                                flee()
                                par()
                                normalend()
                                kill()

                            else:
                                error()
            elif a2 == "hut":
                explorehut()
                par()

                while True:
                    b1 = input("Do you [go in], or [scout] around?")
                    par()

                    if b1 == "go in":
                        sneakhut()
                        par()

                        while True:
                            b2 = input("You have two options: [hide], or [attack]. What do you do?")
                            par()

                            if b2 == "attack":
                                gunsakimbo()
                                par()

                                while True:
                                    b3 = input("Do you drink the mysterious potion?")
                                    par()

                                    if b3 == "yes":
                                        yeschug()
                                        par()
                                        normalend()
                                        kill()

                                    elif b3 == "no":
                                        nochug()
                                        par()
                                        normalend()
                                        kill()

                                    else:
                                        error()

                            elif b2 == "hide":
                                invisibletime()
                                par()
                                gunsakimbo()
                                par()

                                while True:
                                    b3 = input("Do you drink the mysterious potion?")
                                    par()

                                    if b3 == "yes":
                                        yeschug()
                                        par()
                                        normalend()
                                        kill()

                                    elif b3 == "no":
                                        nochug()
                                        par()
                                        normalend()
                                        kill()

                            else:
                                error()

                    elif b1 == "scout":
                        snoopsnoop()
                        par()

                        while True:
                            b4 = input("Do you try to [escape], or do you [hide]?")
                            par()

                            if b4 == "escape":
                                escape()
                                par()
                                normalend()
                                kill()

                            elif b4 == "hide":
                                rosebushgo()
                                par()

                                while True:
                                    b5 = input("Either way, you can't take it anymore. Do you [scream], or attempt to "
                                               "[hold it in]?")
                                    par()

                                    if b5 == "scream":
                                        aghthepain()
                                        par()
                                        normalend()
                                        kill()

                                    elif b5 == "hold it in":
                                        painisforwimps()
                                        par()

                                        while True:
                                            b6 = input("You had to decide something. Do you [warn the town] of the "
                                                       "witch's plans, or do you [wait] for an opportunity?")
                                            par()

                                            if b6 == "wait":
                                                hanselgretle()
                                                par()
                                                normalend()
                                                kill()

                                            elif b6 == "warn the town":
                                                pitchforks()
                                                par()
                                                print(name + ", congratulations for starting a witch hunt that would "
                                                             "be remembered for centuries to come.")
                                                par()
                                                normalend()
                                                kill()

                                            else:
                                                error()

                                    else:
                                        error()

                            else:
                                error()

            else:
                error()

    elif a1 == "right":
        rightpath()
        par()

        while True:
            c1 = input("Do you follow the light into the [forest], or explore the [castle]?")
            par()

            if c1 == "forest":
                forest()
                par()

                while True:
                    c2 = input("Do you try to [kill] them, or [play along]?")
                    par()

                    if c2 == "play along":
                        playalong()
                        par()

                        while True:
                            c3 = input("Do you continue to the [garden], or do you accept the [quest]?")
                            par()

                            if c3 == "garden":
                                gardendate()
                                par()

                                while True:
                                    c4 = input("Do you [sneak out], or do you go back to [sleep]?")
                                    par()

                                    if c4 == "sneak out":
                                        forbiddendate()
                                        par()

                                        while True:
                                            c5 = input("Do you [accept] her advances, or [ignore] them??")
                                            par()

                                            if c5 == "accept":
                                                flirt()
                                                par()

                                                while True:
                                                    c6 = input("Do you undergo the procedure?")
                                                    par()

                                                    if c6 == "yes":
                                                        marry()
                                                        par()
                                                        normalend()
                                                        kill()

                                                    elif c6 == "no":
                                                        dutycalls()
                                                        par()
                                                        normalend()
                                                        kill()

                                                    else:
                                                        error()

                                            elif c5 == "ignore":
                                                cockblock()
                                                par()
                                                normalend()
                                                kill()

                                    elif c4 == "sleep":
                                        sleepin()
                                        par()
                                        helpfae()
                                        par()

                                        while True:
                                            d1 = input("Do you explore the [Mushroom Wilds], or the [Valley of Gods]?")
                                            par()

                                            if d1 == "Mushroom Wilds":
                                                mushroomland()
                                                par()
                                                normalend()
                                                kill()

                                            elif d1 == "Valley of Gods":
                                                temple()
                                                par()

                                                while True:
                                                    d2 = input("Do you take the [left] hallway or the [right]?")
                                                    par()

                                                    if d2 == "left":
                                                        templeleft()
                                                        par()

                                                        while True:
                                                            d3 = input("Do you start digging through the treasure?")
                                                            par()

                                                            if d3 == "yes":
                                                                touchlegold()
                                                                par()
                                                                normalend()
                                                                kill()

                                                            elif d3 == "no":
                                                                notouchgold()
                                                                par()
                                                                templeright()
                                                                par()

                                                                while True:
                                                                    d4 = input("Do you attack with your [mace],"
                                                                               "or use a [spell]?")
                                                                    par()

                                                                    if d4 == "mace":
                                                                        templemace()
                                                                        par()

                                                                        while True:
                                                                            d5 = input("Do you take the amulet?")
                                                                            par()

                                                                            if d5 == "yes":
                                                                                takeleamulet()
                                                                                par()
                                                                                normalend()
                                                                                kill()

                                                                            elif d5 == "no":
                                                                                amulettrap()
                                                                                par()
                                                                                normalend()
                                                                                kill()

                                                                            else:
                                                                                error()

                                                                    elif d4 == "spell":
                                                                        templespell()
                                                                        par()

                                                                        while True:
                                                                            d5 = input("Do you take the amulet?")
                                                                            par()

                                                                            if d5 == "yes":
                                                                                takeleamulet()
                                                                                par()
                                                                                normalend()
                                                                                kill()

                                                                            elif d5 == "no":
                                                                                amulettrap()
                                                                                par()
                                                                                normalend()
                                                                                kill()

                                                                            else:
                                                                                error()

                                                            else:
                                                                error()

                                                    elif d2 == "right":
                                                        templeright()
                                                        par()

                                                        while True:
                                                            d4 = input("Do you attack with your [mace], or use a"
                                                                       "[spell]?")
                                                            par()

                                                            if d4 == "mace":
                                                                templemace()
                                                                par()

                                                                while True:
                                                                    d5 = input("Do you take the amulet?")
                                                                    par()

                                                                    if d5 == "yes":
                                                                        takeleamulet()
                                                                        par()
                                                                        normalend()
                                                                        kill()

                                                                    elif d5 == "no":
                                                                        amulettrap()
                                                                        par()
                                                                        normalend()
                                                                        kill()

                                                                    else:
                                                                        error()

                                                            elif d4 == "spell":
                                                                templespell()
                                                                par()

                                                                while True:
                                                                    d5 = input("Do you take the amulet?")
                                                                    par()

                                                                    if d5 == "yes":
                                                                        takeleamulet()
                                                                        par()
                                                                        normalend()
                                                                        kill()

                                                                    elif d5 == "no":
                                                                        amulettrap()
                                                                        par()
                                                                        normalend()
                                                                        kill()

                                                                    else:
                                                                        error()

                                    else:
                                        error()

                            elif c3 == "quest":
                                helpfae()
                                par()

                                while True:
                                    d1 = input("Do you explore the [Mushroom Wilds], or the [Valley of Gods]?")
                                    par()

                                    if d1 == "Mushroom Wilds":
                                        mushroomland()
                                        par()
                                        normalend()
                                        kill()

                                    elif d1 == "Valley of Gods":
                                        temple()
                                        par()

                                        while True:
                                            d2 = input("Do you take the [left] hallway or the [right]?")
                                            par()

                                            if d2 == "left":
                                                templeleft()
                                                par()

                                                while True:
                                                    d3 = input("Do you start digging through the treasure?")
                                                    par()

                                                    if d3 == "yes":
                                                        touchlegold()
                                                        par()
                                                        normalend()
                                                        kill()

                                                    elif d3 == "no":
                                                        notouchgold()
                                                        par()
                                                        templeright()
                                                        par()

                                                        while True:
                                                            d4 = input("Do you attack with your [mace],"
                                                                       "or use a [spell]?")
                                                            par()

                                                            if d4 == "mace":
                                                                templemace()
                                                                par()

                                                                while True:
                                                                    d5 = input("Do you take the amulet?")
                                                                    par()

                                                                    if d5 == "yes":
                                                                        takeleamulet()
                                                                        par()
                                                                        normalend()
                                                                        kill()

                                                                    elif d5 == "no":
                                                                        amulettrap()
                                                                        par()
                                                                        normalend()
                                                                        kill()

                                                                    else:
                                                                        error()

                                                            elif d4 == "spell":
                                                                templespell()
                                                                par()

                                                                while True:
                                                                    d5 = input("Do you take the amulet?")
                                                                    par()

                                                                    if d5 == "yes":
                                                                        takeleamulet()
                                                                        par()
                                                                        normalend()
                                                                        kill()

                                                                    elif d5 == "no":
                                                                        amulettrap()
                                                                        par()
                                                                        normalend()
                                                                        kill()

                                                                    else:
                                                                        error()

                                                    else:
                                                        error()

                                            elif d2 == "right":
                                                templeright()
                                                par()

                                                while True:
                                                    d4 = input("Do you attack with your [mace], or use a [spell]?")
                                                    par()

                                                    if d4 == "mace":
                                                        templemace()
                                                        par()

                                                        while True:
                                                            d5 = input("Do you take the amulet?")
                                                            par()

                                                            if d5 == "yes":
                                                                takeleamulet()
                                                                par()
                                                                normalend()
                                                                kill()

                                                            elif d5 == "no":
                                                                amulettrap()
                                                                par()
                                                                normalend()
                                                                kill()

                                                            else:
                                                                error()

                                                    elif d4 == "spell":
                                                        templespell()
                                                        par()

                                                        while True:
                                                            d5 = input("Do you take the amulet?")
                                                            par()

                                                            if d5 == "yes":
                                                                takeleamulet()
                                                                par()
                                                                normalend()
                                                                kill()

                                                            elif d5 == "no":
                                                                amulettrap()
                                                                par()
                                                                normalend()
                                                                kill()

                                                            else:
                                                                error()

                                                    else:
                                                        error()

                                            else:
                                                error()

                                    else:
                                        error()

                            else:
                                error()

                    elif c2 == "kill":
                        killfae()
                        par()
                        normalend()
                        kill()

                    else:
                        error()

            elif c1 == "castle":
                castle()
                par()

                while True:
                    e1 = input("Do you try to [vault] over the moat, or look for the [mechanism]?")

                    if e1 == "vault":
                        vault()
                        par()
                        normalend()
                        kill()

                    elif e1 == "mechanism":
                        drawbridge()
                        par()

                        while True:
                            e2 = input("Do you enter the [library], or go into the [tower]?")

                            if e2 == "library":
                                library()
                                par()

                                while True:
                                    e3 = input("You could [destroy] the lamp, or [leave it alone]. What do you do?")

                                    if e3 == "destroy":
                                        breaklamp()
                                        par()
                                        towertime()
                                        par()

                                        while True:
                                            e4 = input("Do you drink the [red bottle], or the [purple bottle]?")

                                            if e4 == "red bottle":
                                                redbottle()
                                                par()
                                                normalend()
                                                kill()

                                            elif e4 == "purple bottle":
                                                purplebottle()
                                                par()

                                                while True:
                                                    e5 = input(
                                                        "Do you answer with the [sun], the [moon], or the [stars]?")
                                                    par()

                                                    if e5 == "sun" or e5 == "stars":
                                                        vore()
                                                        par()
                                                        normalend()
                                                        kill()

                                                    elif e5 == "moon":
                                                        lalune()
                                                        par()
                                                        print("Ah yes, " + name + ", I have been expecting you, "
                                                                                  "said the litch with a wicked grin.")
                                                        par()
                                                        bigepicfight()
                                                        reliquary()
                                                        par()
                                                        trueend()
                                                        kill()

                                                    else:
                                                        error()

                                    elif e3 == "leave it alone":
                                        ignorelamp()
                                        par()
                                        towertime()
                                        par()

                                        while True:
                                            e4 = input("Do you drink the [red bottle], or the [purple bottle]?")

                                            if e4 == "red bottle":
                                                redbottle()
                                                par()
                                                normalend()
                                                kill()

                                            elif e4 == "purple bottle":
                                                purplebottle()
                                                par()

                                                while True:
                                                    e5 = input(
                                                        "Do you answer with the [sun], the [moon], or the [stars]?")
                                                    par()

                                                    if e5 == "sun" or e5 == "stars":
                                                        vore()
                                                        par()
                                                        normalend()
                                                        kill()

                                                    elif e5 == "moon":
                                                        lalune()
                                                        par()
                                                        print("Ah yes, " + name + ", I have been expecting you, "
                                                                                  "said the litch with a wicked grin.")
                                                        par()
                                                        bigepicfight()
                                                        lampnogone()
                                                        par()
                                                        normalend()
                                                        kill()

                                                    else:
                                                        error()

                                    else:
                                        error()

                            elif e2 == "tower":
                                ignorelibrary()
                                towertime()
                                par()

                                while True:
                                    e4 = input("Do you drink the [red bottle], or the [purple bottle]?")

                                    if e4 == "red bottle":
                                        redbottle()
                                        par()
                                        normalend()
                                        kill()

                                    elif e4 == "purple bottle":
                                        purplebottle()
                                        par()

                                        while True:
                                            e5 = input("Do you answer with the [sun], the [moon], or the [stars]?")
                                            par()

                                            if e5 == "sun" or e5 == "stars":
                                                vore()
                                                par()
                                                normalend()
                                                kill()

                                            elif e5 == "moon":
                                                lalune()
                                                par()
                                                print("Ah yes, " + name + ", I have been expecting you, "
                                                                          "said the litch with a wicked grin.")
                                                par()
                                                bigepicfight()
                                                lampnogone()
                                                par()
                                                normalend()
                                                kill()

                                            else:
                                                error()

                                    else:
                                        error()

                            else:
                                error()

                    else:
                        error()

            else:
                error()

    else:
        error()
