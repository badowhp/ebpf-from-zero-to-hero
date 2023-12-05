# eBPF for beginners: from zero to hero

Whether you're a DevOps enthusiast or a curious beginner, this meetup promises to equip you with the foundational knowledge and practical skills to navigate the world of eBPF. Join Hipolit Badowski on this exciting journey from zero to hero in the realm of Extended Berkeley Packet Filter technology.

# Marp CLI Slide Show Automation

This project provides a simple Rakefile to automate common tasks for creating and managing Marp CLI slide decks. [Marp CLI](https://marp-cli.netlify.app/) is a command-line interface for [Marp](https://marp.app/), a markdown presentation ecosystem.

## Prerequisites

- [Node.js](https://nodejs.org/) v16 and later installed on your machine.

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/badowhp/from-zero-to-hero.git
   cd from-zero-to-hero
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create your slide deck in the `slides` directory. You can use the [Marp syntax](https://marpit.marp.app/directives?id=markdown-syntax) for creating slides.

4. Run the default task to convert the slide deck into HTML:

   ```bash
   rake
   ```

   This will generate an HTML file in the `dist` directory.

## Available Tasks

- **Convert slide deck into HTML:**

  ```bash
  rake html
  ```

- **Convert slide deck into PDF:**

  ```bash
  rake pdf
  ```

- **Convert slide deck into PowerPoint document (PPTX):**

  ```bash
  rake pptx
  ```

- **Watch mode:**

  ```bash
  rake watch
  ```

- **Server mode (Pass directory to serve):**

  ```bash
  rake server
  ```

  This task starts a server to serve your slides. Open your browser and navigate to [http://localhost:8080](http://localhost:8080) to view the slides.

- **Convert slide deck into HTML, PDF, and PPTX:**

  ```bash
  rake all
  ```

  This task runs all conversion tasks (HTML, PDF, and PPTX) in one go.

## Customize

Feel free to customize the Rakefile to match your project structure or add additional tasks as needed.
```

