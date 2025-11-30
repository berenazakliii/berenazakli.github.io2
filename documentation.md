# Big idea notes
**COLLABRATİON**

*Computing innovation can be improved through collaboration. A computing innovation is the creation and application of novel ideas, technologies, and approaches within the field of computing, it includes a program as an integral part of its function. Effective collaboration results in a computing innovation that reflects the diversity and the unique perspectives of those who designed it, it also helps avoid bias in the development of computing innovations. While developing computing innovations, consultation and communication with users are important aspects of the development. Some common models of types of collaboration are pair programming, think-pair-share and etc… Collaboration can be supported by online tools such as github, repl it and shared doc/folder.*

**PROGRAM FUNCTİON AND PURPOSE**

*The purpose of computing innovations is to usually solve a problem or pursue an interest through creative expression. A program is a collection of program statements that run different tasks when it's run by a computer. A program works with lots of inputs and outputs that determine the behavior of a program. The behavior of a program is how a program functions during execution. Program inputs are data sent to a program, it can come from a user or other programs. Outputs are data sent from a program to a device, output is usually based on a program's input of prior state.*

**PROGRAM DESİGN AND DEVELOPMENT**

*Creators usually develop a program using a development process.A development process can be ordered and intentional, or exploratory in nature. The development process that is incremental breaks the problem into smaller pieces and makes sure each piece works before bringing them all together. While a development process that is iterative requires  revision based on feedback, testing, or reflection throughout the process. Investigation in a development process is important for understanding program constraints. İnvestigation can be performed as user testing, interview etc… The design phase outlines how to accomplish a given program specification, it can look like brainstorming ,planning and storyboarding. Documentation is also really important, program documentation helps in developing correct programs when working in programming environments.*


**IDENTİFYİNG AND CORRECTİNG ERRORS**

*There are lots of errors we can face while creating a program. A logic error is a mistake in the algorithm/program that causes the program to fail. Some of these errors are called syntax error, run-time error or an overflow error. Some effective ways to find and correct errors are test cases, hand tracing debuggers etc.. İn the development process testing uses defined input to make sure a program does not fail, defined inputs used to test a program should demonstrate the different expected outcomes. Program requirements are needed to find appropriate defined inputs for testing.*


# Big Idea 2 – Reflection Essays (2.1–2.4)

## 2.1 – Binary Numbers
Binary numbers are the foundation of all digital data. Everything—images, text, videos—is stored using bits. I learned how data is converted between binary and decimal. Overflow and round-off errors can happen. It was surprising how such simple 1s and 0s can create everything we see on a computer.

## 2.2 – Data Compression
Data compression helps reduce file size using algorithms like lossless and lossy compression. I found it interesting how we can save storage or increase speed by removing unnecessary data. JPEG images, for example, use lossy compression. It made me realize how much thought goes into optimizing media and files.

## 2.3 – Extracting Information from Data
This topic showed me how we use data to find patterns and make decisions, but also that we must be careful with interpretation. I learned the difference between correlation and causation. It made me think about how easily people can be misled by data without proper analysis.

## 2.4 – Using Programs with Data
Programs allow us to process and analyze huge amounts of data. I learned how algorithms can help us understand trends, like in recommendation systems. It was cool to see how computers help humans make smarter decisions. I’d like to explore how these systems are used in real-world apps.



# 🐸 Clock Game – Frog Escape Edition

## What was the hardest part of timing logic?
Handling the `Timer` properly — especially invalidating it to prevent overlap when restarting — was tricky. Making sure time resets and updates visually with animation was also a challenge.

## How did you use `if`, `for`, and `functions`?
- Used `if/else` in `initialTimeForLevel(level:)` to adjust time based on level.
- Used `for` loop in console testing (see below).
- Functions organized logic: `startGame()`, `checkCollision()`, `nextLevel()`.

## What happens when your clock overflows?
When time reaches 0 or player hits an obstacle, the clock resets and prints a message. Game state is reset, and timer stops until the player presses restart.

---


# 🍦 Ice Cream Overflow

This is a simple SwiftUI game where you stack scoops of ice cream. You can add up to 3 scoops. If you try to add more — it overflows!

---

##  Reflection

###  What is overflow in your app?
Overflow happens when you add more than 3 scoops. The app shows a message saying it’s too many scoops and stops you from adding more.

---

### How does the cone show abstraction?
The cone is a triangle shape. Instead of drawing every part, I used a simple `Triangle` shape. That’s abstraction — using one shape to stand for something more complex.

---

###  What did you learn about binary & compression?
I learned that computers use 1s and 0s (binary) to store things like colors and scoop positions.  
Compression means saving space — like reusing the same code instead of writing it again and again.

---


### ⏱️ Part A — Console Test:

## Reflection(LİST/ARRAY)

**Why did you choose this theme?**  
I chose this theme because I wanted to build a clean and functional book organizer that feels like a real app.

**What did you learn about lists?**  
I learned how lists can dynamically display data, update automatically when items change, and connect to navigation and detail views.

**What would change if your list had more items?**  
With more items, sorting, searching, and sectioning become more important to keep the list organized and easy to browse.


## Reflection NADİNS STORY

What inspired me most about Nadin’s story is how she started with a simple idea and focused on creating a meaningful, enjoyable experience rather than trying to build something overly complex. It showed me that passion and creativity matter just as much as technical skill. In the future, I’d like to explore an idea that connects my own interests with interactive learning and turns it into a playful, engaging Swift Playground.

# AP CSP Portfolio Review – Last 3 Projects

**Git Link:** *add your repo link here*

**Scores and Snippets – All Projects in One Block**

```swift
// ===== Project 1 – Pixel Painter =====
func changeColor() {
    if let n = Int(userInput), n >= 0 && n < 100 {
        cellColors[n] = .blue
    }
}

ForEach(0..<10) { row in
    ForEach(0..<10) { col in
        Rectangle().fill(cellColors[row*10+col])
    }
}

// Scores: Video:1, Program:1, WR1:1, Algorithm:1, Errors/Testing:1, Data/Procedure:1

// ===== Project 2 – Ice Cream / Moods =====
ForEach(0..<moods.count) { i in
    Text(moods[i])
    Text(colors[i])
}

// Scores: Video:1, Program:1, WR1:1, Algorithm:0, Errors/Testing:0, Data/Procedure:0
// Reason for 0: Only displays lists, no procedure, no selection, no input handling

// ===== Project 3 – Flags =====
ForEach(0..<cities.count) { i in
    Text(cities[i])
    Text(flags[i])
}

// Scores: Video:1, Program:1, WR1:1, Algorithm:0, Errors/Testing:0, Data/Procedure:0
// Reason for 0: Only displays lists, no algorithm or procedure


DOCUMENTATİON OF THE PROJECTS:

## [Swift video:](https://drive.google.com/file/d/1Sv3gThbgu-gjOIpwiryBfZp0z_RLUF9Y/view?usp=sharing)

## [Scratch video:](https://drive.google.com/file/d/1b4ZqT4OHX7jl7n36edUCt16QE3UP3bev/view?usp=sharing)

## [Scratch video2:](https://drive.google.com/file/d/1b4ZqT4OHX7jl7n36edUCt16QE3UP3bev/view?usp=sharing)

## [Scratch video3:](https://drive.google.com/file/d/1b4ZqT4OHX7jl7n36edUCt16QE3UP3bev/view?usp=sharing)



