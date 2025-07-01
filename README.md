## My-WYAG (Write Your Own Git)

This is my personal project to rebuild the basic functionality of the popular version control system, Git, from scratch
using Python. The name "My-WYAG" is a nod to the wonderful and inspiring "Write Yourself a Git" tutorial.

### Project Motivation

The main goal of this project is to learn. I've always been fascinated by how Git works under the hood, and I believe
that the best way to truly understand a complex system is to try and build it yourself.

By undertaking this project, I aim to get a hands-on understanding of Git's core concepts, including:

- The structure of the .git directory.
- The fundamental object types: blob, tree, and commit.
- The mechanics of content-addressed storage and SHA-1 hashing.
- How the staging area (the index) works.
- The implementation of branches and tags.
- The process of merging and how histories are combined.

### Planned Features

I plan to implement a core set of Git commands. This serves as the project's roadmap.

- [ ] init: Initialize a new, empty repository.
- [ ] add: Add file changes from the working directory to the staging area.
- [ ] rm: Remove files from the working directory and the staging area.
- [ ] config: Get and set repository or global configuration variables.
- [ ] status: Show the status of the working directory and the staging area.
- [ ] log: Display the commit history reachable from HEAD.
- [ ] checkout: Switch branches or restore working tree files.
- [ ] tag: Create, list, or delete tag objects.
- [ ] merge: Join two or more development histories together.

Technology Stack
This project is being built entirely in Python. It was chosen for its readability and excellent standard library, which
is well-suited for file system operations, hashing, and data manipulation required for this task.

> This project is a learning journey, and I'm excited to see how far I can go in replicating the magic of Git.