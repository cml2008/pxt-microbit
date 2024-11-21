```blocks
basic.showString("ASK A QUESTION")
basic.showNumber(8)
input.onGesture(Gesture.Shake, () => {
    basic.clearScreen()
    let randomNumber = randint(0, 4)
    if (randomNumber == 3) {
        basic.showString("TRY AGAIN at another time")
    } else if (randomNumber == 2) {
        basic.showString("It will come true")
    } else if (randomNumber == 1) {
        basic.showString("NO")
    } else {
        basic.showString("I DON'T KNOW")
    }
    basic.showNumber(9)
})
