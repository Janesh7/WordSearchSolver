# WordSearchSolver

WordSearchSolver is a command-line tool that solves word search grids using the Trie data structure. It's a handy utility to quickly find words within a grid of letters. This README provides instructions on how to run the tool locally and offers an overview of its features.

## How to Run Locally

To run WordSearchSolver on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Janesh7/WordSearchSolver.git
   cd WordSearchSolver
   ```

2. Navigate to the Solver directory and install the required dependencies:

   ```bash
   cd Solver
   pip3 install -r requirements.txt
   ```

3. View the help manual to understand the command-line options:

   ```bash
   python3 solver.py -h
   ```

4. Solve a word search puzzle by providing the path to the grid file and word list file:

   ```bash
   python3 solver.py <path_to_grid_file> <path_to_wordlist>
   ```

5. Optionally, you can use the `-f` flag for faster processing with fewer animations (recommended for larger files):

   ```bash
   python3 solver.py <path_to_grid_file> <path_to_wordlist> -f
   ```

**Note:** Ensure that the required library dependencies are installed. You can install them manually or run `pip3 install -r requirements.txt` to check and install any missing dependencies. The `requirements.txt` file is included with the tool.

## Command-Line Usage

- `-h`: Display the help manual.
- `<path_to_grid_file>`: Specify the text file containing the grid (an n x n matrix of letters).
- `<path_to_wordlist>`: Specify the text file containing the list of words to search for (each word should have a length less than or equal to the grid size).
- `-f`: Use the fast mode for quicker results with reduced animations (recommended for larger files).

## Screenshots

- Help Manual:
  ![Help Manual](https://github.com/Janesh7/WordSearchSolver/blob/main/Screenshots/Screenshot1.png)

- Solving Process:
  ![Solving](https://github.com/Janesh7/WordSearchSolver/blob/main/Screenshots/Screenshot2.png)

- Solved Grid:
  ![Solved](https://github.com/Janesh7/WordSearchSolver/blob/main/Screenshots/Screenshot3.png)

- Fast Mode (No Animations):
  ![Fast Mode](https://github.com/Janesh7/WordSearchSolver/blob/main/Screenshots/Screenshot4.png)

**Note:** Make sure the grid file and word list file are located in the same directory as the tool, or provide their full paths as arguments.

Enjoy using WordSearchSolver to quickly and efficiently solve word search puzzles! If you encounter any issues or have suggestions for improvements, please feel free to contribute or raise an issue on the [GitHub repository](https://github.com/Janesh7/WordSearchSolver).

# Word Search Online Game

Welcome to the Word Search Online Game! This web-based game allows you to test your word-finding skills by locating words from a given list within a grid of characters. The game offers three exciting themes - Universe, Movies, and Animals - to choose from. Let's get started and have some word-searching fun!

## How to Play

1. Visit the game at [Word Search Online Game](https://orange-tofu.github.io).

2. Choose a theme from the dropdown menu. You can select from Universe, Movies, or Animals.

3. Click the "OK" button to confirm your theme selection.

4. Click the "Play Now" button to start the game.

## Game Rules

- You'll see a grid of characters, and a list of words to find on the right side of the screen.

- Words can be located in any of the eight directions: left-right, right-left, up-down, down-up, diagonal-right, or diagonal-left.

- To select a word, click and drag your cursor from one end of the word to the other.

- When you successfully locate a word, it will be struck out from the list.

- Your goal is to find all the words as quickly as possible.

## Themes

- **Universe**: Explore the cosmos and discover words related to space, stars, and galaxies.

- **Movies**: Dive into the world of cinema and find words associated with your favorite films and actors.

- **Animals**: Embark on an animal-themed adventure and search for words related to creatures from all around the world.

## Source Code

If you're interested in exploring the source code for this game, you can find it in the `/Webpage` directory of the [GitHub repository](https://github.com/orange-tofu/WordSearchOnlineGame).

Enjoy playing the Word Search Online Game, and may your word-searching skills shine as you uncover hidden words in the grid. Have fun, and happy gaming!