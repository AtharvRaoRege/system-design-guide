# System Design Metro 🚇

**Learn system design one station at a time.**

System Design Metro is a single-file, interactive learning guide for exploring system design concepts. It organizes topics into learning lines and stations, with explanations, examples, code snippets, calculations, interview questions, and knowledge checks.

## ✨ Features

- **156 system design topics** organized into learning lines and stations.
- Beginner-friendly explanations designed to make complex ideas easier to understand.
- Practical examples and code snippets that connect concepts to implementation.
- Worked calculations for understanding performance, capacity, and system behavior where applicable.
- Interview practice with questions and explanations.
- Interactive knowledge checks to test understanding.
- Topic navigation to explore related concepts.
- Learning progress and review markers to help organize study sessions.
- Responsive layout for desktop and mobile screens.
- Light and dark themes for comfortable reading.
- A single HTML file with no frontend build step required.

## 🚀 Getting Started

### Option 1: Open locally

1. Clone the repository:

   ```bash
   git clone <YOUR_REPOSITORY_URL>
   ```

2. Move into the project directory:

   ```bash
   cd <YOUR_REPOSITORY_DIRECTORY>
   ```

3. Open `index.html` in your browser.

You can also double-click `index.html` to open it directly.

### Option 2: Run a local web server

For a more reliable local browsing experience, serve the file over HTTP.

Using Python:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/index.html
```

Stop the server with `Ctrl+C`.

## 📚 How to Use

1. Open the home page and choose a learning line or topic.
2. Read the lesson from the core idea through the practical explanation.
3. Study the examples, code, calculations, and trade-offs available for that topic.
4. Try the interview questions and knowledge checks.
5. Mark topics as learned or save them for review, where those controls are available.
6. Follow related lessons to connect individual concepts into a broader system design mental model.

**Suggested study method:** focus on why a technique exists, how it works, when it is useful, and what trade-offs it introduces. Avoid memorizing definitions without understanding the underlying mechanism.

## 🧭 Topics

The guide covers system design concepts across areas such as:

- API and application design
- Databases and query performance
- Caching
- Reliability and fault tolerance
- Scaling and load distribution
- Messaging and asynchronous processing
- Distributed systems concepts
- Performance, monitoring, and debugging
- System design interview preparation

The exact topics and lesson content are defined in `index.html`.

## 🛠️ Technology

- HTML
- CSS
- Vanilla JavaScript

The project is designed to run as a standalone HTML page and does not require a package manager or compilation step. The page references web fonts, so an internet connection may be needed to load those fonts; fallback fonts can be used if they are unavailable.

## 📁 Project Structure

```text
.
└── index.html    # Main application: interface, styles, topic data, and interactions
```

If your repository uses a different filename, update the commands and structure above to match it.

## 🤝 Contributing

Contributions that improve clarity, technical accuracy, accessibility, or usability are welcome.

1. Fork the repository.
2. Create a branch for your change.
3. Make a focused update.
4. Test the page in a browser, including navigation and interactive elements.
5. Open a pull request describing the change and how it was tested.

When editing lesson content, prefer clear explanations and realistic, topic-specific examples over long lists of disconnected points. Preserve existing functionality unless a change is necessary.

## ⚠️ Notes

- This guide is an educational resource. Validate important architectural decisions against the requirements and constraints of your own system.
- Example values and calculations may be illustrative rather than performance guarantees.
- The project is a learning aid, not a substitute for testing, production monitoring, or technology-specific documentation.

## 📄 License

No license is specified here. Add a `LICENSE` file before presenting the project as open source, and choose a license that fits how you want others to use, modify, and distribute it.

---

**Happy learning, and enjoy the ride through system design! 🚇**
