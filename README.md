# RSA-Encryption

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [AVL Tree](#avl-tree)
  * [Why AVL Trees?](#why-avl-trees)
* [Usage](#usage)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)

## About The Project

This project is the implementation of one of the data structures "AVL Tree".  
If you are someone who is interested in data structures, trees, one of the first structures that come to your mind, are very important to us. For this reason, I implemented AVL trees in order to learn these structures better and to improve myself and I am sharing them with you.  
**In addition to other AVL Tree implementation, it also stores the movement of nodes in the stack.**

### Built With

This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [C++](https://isocpp.org)
* [Makefile](https://www.gnu.org/software/make/manual/make.html)

## Getting Started

Before examining the project, we need to know about AVL trees.

### AVL Tree

In computer science, an AVL tree (named after inventors Adelson-Velsky and Landis) is a self-balancing binary search tree.  
It was the first such data structure to be invented. In an AVL tree, the heights of the two child subtrees of any node differ by at most one; if at any time they differ by more than one, rebalancing is done to restore this property. Lookup, insertion, and deletion all take O(log n) time in both the average and worst cases, where n is the number of nodes in the tree prior to the operation. Insertions and deletions may require the tree to be rebalanced by one or more tree rotations.

### Why AVL Trees?

Most of the BST operations (e.g., search, max, min, insert, delete.. etc) take O(h) time where h is the height of the BST. The cost of these operations may become O(n) for a skewed Binary tree. If we make sure that height of the tree remains O(Logn) after every insertion and deletion, then we can guarantee an upper bound of O(Logn) for all these operations. The height of an AVL tree is always O(Logn) where n is the number of nodes in the tree (See this video lecture for proof).

## Usage

1. Get a MinGW at [HERE](http://www.mingw.org/) and Install
2. Open file folder from command line
```sh
cd desktop/AVL-Tree-Data-Structures
```
3. Run Makefile for compile process
```sh
mingw32-make
```
4. Open bin folder from command line or file explorer
```
cd.. / for move back folder
cd bin
program.exe
```

## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.

## Contact

Twitter: [twitter.com/fehmiisener](https://twitter.com/fehmiisener)  
Mail: fehmiisener@gmail.com  
Project Link: [RSA-Encryption](https://github.com/fehmiisener/RSA-Encryption)

[contributors-shield]: https://img.shields.io/github/contributors/fehmiisener/RSA-Encryption.svg?style=flat-square
[contributors-url]: https://github.com/fehmiisener/RSA-Encryption/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/fehmiisener/RSA-Encryption?style=flat-square
[forks-url]: https://github.com/fehmiisener/RSA-Encryption/network/members
[stars-shield]: https://img.shields.io/github/stars/fehmiisener/RSA-Encryption?style=flat-square
[stars-url]: https://github.com/fehmiisener/RSA-Encryption/stargazers
[issues-shield]: https://img.shields.io/github/issues/fehmiisener/RSA-Encryption?style=flat-square
[issues-url]: https://github.com/fehmiisener/RSA-Encryption/issues
[license-shield]: https://img.shields.io/github/license/fehmiisener/RSA-Encryption?style=flat-square
[license-url]: https://github.com/fehmiisener/RSA-Encryption/blob/master/LICENSE
[product-screenshot]: images/screenshot.png
