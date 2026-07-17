# Gracefully-Coloring-Tesseract
College research project exploring the graceful chromatic number of the tesseract (4D hypercube) using graph theory, programming, and a pigeonhole principle-based proof.

Work required 2 separate skills and 1 instance of knowledge of the subject along with guidance from my instructor and research about work from other people in the field - 
Graph Theory
Iterative Programming
General Mathematical Principles

The start of the project was me trying out possibilities randomly starting with at a vertex with color 1 and trying to color the edges around first and then coloring more connected vertices... while maintaining gracefulness. On seeing the number of possibilities, it soon turned out to be an ineffective strategy.
Then i looked at other graphs in the family and observed a simple pattern i.e. opposite vertices had the same color. This drastically reduced the number of possiblilities but still would be ineffective trying out all the possible combinations. I did try out a few of them but soon started thinking of better approaches. To be noted that i had no idea if this par=ttern would still persist in the currect graph.
Replicating the process in a computer program took a few attempts and a little bit of debugging, but successful run of the program showed 8 as the graceful chromatic number, along with the colors for each vertex and neighbouring vertices. Testing out the result showed that the program's output was correct and now the part remaining was the proof for the same.
This was the most random stumble of this project because i was laying on my bed thinking about ways to do this and i fell upon the thought about each number occuring twice and not more. That turned out to be the logic and gave a new observation in the process - a cube cannot have more than 2 instances of the same color in  graceful coloring.
A little more time into this helped me frame the proof better with pigeonhole principle and that was where the result was solidified.

The observation was also correct and its implementation in the program turned out to be crucial as it reduced the time complexity of the run from BIG_O(15) to BIG_O(7), reducing 8 iterations of unviable possibilities.

One important lesson learnt is that its generally a good practice to have fresh and simples chains of thought rather than complex branching chains. Logic doesnt usually require a lot of ifs and buts, just a few simple rules that are easier to figure out with better approaches.
