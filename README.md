# biquadris
made by [Andrea Cen](https://github.com/an9rya), [Nicole Cui](https://github.com/nisu75) and [Sophia Yang](https://github.com/spiayang) for the final project of F2024 CS246 (Object-Oriented Software Development).

coded in C++, rendered using X11 Graphics.

## gameplay
unlike tetris, players take turns dropping their block with no time restriction. core gameplay is similar to the original game with the addition of special actions that apply for one turn after a 2+ line clear: 
- blind (which covers part of the opponent's board with question marks)
- force (which changes the opponent's next block)
- heavy (which makes the opponent's block fall faster)

players score points based on the number of lines they clear in a single turn, with more points awarded for clearing multiple lines and at higher levels.

as players increase their levels, the game becomes progressively harder and introduces new gameplay scenarios.

## display
both text-based and graphics-based displays are supported, with the text-based display in the terminal and graphics-based display rendered with the XWindows library. 

<picture>
  <img alt="biquadris demo" src="/images/display.png" width="1000">
</picture>

> ### due to [policy 71](https://uwaterloo.ca/secretariat/policies-procedures-guidelines/policy-71), the source code is only available upon request.
