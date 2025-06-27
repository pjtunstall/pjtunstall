I've been learning to code for the past two and a half years at 01Founders, a branch of the 01Edu family of coding bootcamps. We were introduced first to Go, then JavaScript, then Rust. This portfolio is a mixture of coursework and personal projects. An asterisk after the title denotes a 01Founders project.

(If you're viewing this on my GitHub [profile](https://github.com/pjtunstall), scroll down to pinned repos for a quick sample.)

## Rust

- [almondala](https://github.com/pjtunstall/almondala) Online Mandelbrot explorer, in Rust/Wasm and TypeScript.
- [0-shell](https://github.com/pjtunstall/0-shell)* A simple shell.
- [a-ray-tracer-darkly](https://github.com/pjtunstall/a-ray-tracer-darkly)* A ray tracer. My resonse to the 01Founders project called rt.
- [holocron](https://github.com/pjtunstall/holocron) A program to encrypt and decrypt messages with a hybrid cryptosystem, combining a conventional key-exchange mechanism with one of the proposed post-quantum algorithms.
- [filler](https://github.com/pjtunstall/filler)* A bot to compete against another bot at a game called filler. The bots take turns to receive a random Tetris-like piece and must place it on the playing area with certain constraints, trying to cut each other off and fill more of the space with their own tiles. The project is meant to run inside the Docker container created from the supplied Docker image.
- [smart-road](https://github.com/pjtunstall/smart-road)* A rudimentary simulation of traffic at an intersection. (First 01Founders Rust project.)

## JavaScript

- [overreact](https://github.com/pjtunstall/overreact)* A mini frontend framework and a [TodoMVC](https://todomvc.com/) web app built with it as a demo. (TodoMVC is a standard project to illustrate how different frameworks accomplish the same task.)
- [retro-raiders](https://github.com/pjtunstall/retro-raiders)* First JavaScript project for 01Founders. The brief: to make a classic arcade game using JS and no framework, canvas, or WebGL. This was a group project. I made the game and story, teammate Bilal refactored my chaotic code into something more sensibly modular--but I pressed on with this version, because I was impatient to keep working on new ideas. Bilal also whipped up the neat animation that happens when the aliens reach the ground. Thanks also to Daisy for the pixel art and Shane for the original scoreboard. (Full credits in game.)
- [react-tarot](https://github.com/pjtunstall/react-tarot) Personal project to introduce myself to React: a carousel of AI-generated tarot cards.
- [ziggurats](https://github.com/pjtunstall/ziggurats) An exercise to help me learn about Canvas animations and MVC architecture, which also turned into an exploration of performance.
- [spotify-scraper](https://github.com/pjtunstall/spotify-scraper) A program to scrape Spotify premium individual plan price data for all countries. Effective at least as far as early 2025. I'm not actively maintaining it or checking that it still works in case Spotify make changes to their website.
- [mad](https://github.com/pjtunstall/mad)* The Mad Bomber's Tea Party. The brief: recreate the 8-bit classic Bomberman as a multiplayer browser game, using WebSockets. I wrote the backend in Node. My code is naively structured and there are outstanding issues as detailed in the docs. But I still like the story and AI art + music. As in the single-player game project, Canvas and WebGL were forbidden. We weren't allowed to use any framework except one we each made in an earlier project, [overreact](https://github.com/pjtunstall/overreact). I adapted it from a single-player version by fellow students; see credits in game and in the README. Their work is most evident in the client-side code of the game itself.

## Go

- [penumbra](https://github.com/pjtunstall/penumbra) A task manager web app, written mostly in Go, using Go's HTML templates, with minimal JavaScript, and the DaisyUI CSS framework for styling.
- [lem-in](https://github.com/pjtunstall/lem-in)* First significant 01Founders project. We had to find an optimal way to send ants through a maze. It taught me some graph traversal algorithms and the concept of maximum flow. I kept thinking I had it, then realizing it went deeper. The breakthrough came when I found a paper by Schroeder, Guedes, and Duarte on how to adapt the Ford-Fulkerson technique to find a maximum flow in an undirected graph.
- [push-swap](https://github.com/pjtunstall/push-swap)* For us, at 01Founders, this was an optional project. The challenge is to sort a circular stack of numbers using one other circular stack, with as few instructions as possible. (Instructions include operations such as rotating a stack, swapping the two numbers at the top of the stack, or pushing a number from the top of one stack to the top of the other.) I got carried away comparing the performance of all the solutions I could find online from students at our sibling schools. My solution is not original, but a combination of the best I could find, switching techniques according to the size of the stack.
- [stock-exchange-sim](https://github.com/pjtunstall/stock-exchange-sim)* A playfully named, optional 01Founders project about task scheduling heuristics, introducing the idea of a process chain.
- [brainfuck](https://github.com/pjtunstall/brainfuck) An interpreter for the esoteric programming language Brainfuck.
