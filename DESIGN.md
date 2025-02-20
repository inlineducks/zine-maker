# software design document for zine maker

### **1. Introduction**

- **Project Name**: (Give your web app a name)
- **Purpose**: Why are you building this? (E.g., to create an easy-to-use zine design tool)
    - To practice our web dev skills and learn about collaborative workflows
    - There currently doesn’t seem to be any dedicated web-based app aimed at designing zines for print (there are desktop-based apps for print zines or web apps for digital zines though. there are also zine templates on canva maybe)
- **Scope**: What will this app do? What won’t it do?
- **Tech Stack**: List technologies (p5.js, JavaScript, HTML/CSS, etc.)
    - HTML, CSS, JavaScript
    - p5.js probably
- **Target Users**: Who will use it? (E.g., indie artists, hobbyists, ~~small publishers~~)
    - Indie artists, hobbyists, maybe educators, maybe activists/people who want to spread a message?

### **2. Features & Requirements**

- **Core Features**:
    - Canvas for designing pages
    - Ability to add images, text, and (maybe shapes?)
        - User can import/upload images, maybe we also provide a library of “sticker”-like images for them to add
    - Multi-page zine layout system
        - Design each page one at a time and then the app stitches them together in the proper format?
    - Export to a printable PDF format (correctly formatted for zines)
- **Nice-to-Have Features** (things you might add later):
    - Templates for different zine formats
    - Save work in progress and resume editing later
    - Upload a digital version to a public gallery
        - Ability to remix zines from the gallery?
    - Integrate a stock image search API
- **Technical Constraints**:
    - Runs in the browser
    - No backend

### **3. System Design & Architecture**

- **Frontend Architecture**:
    - How will you structure the code? (Separate UI logic from rendering logic, for example)
    - How does p5.js fit in?
- **Data Flow**:
    - How does user input translate into zine pages?
    - How will you store and retrieve design elements?
- **PDF Generation**:
    - How will you convert the canvas into a PDF? (E.g., use a library like jsPDF)

### **4. User Interface (UI) Design**

- Sketch or wireframes of the UI
- Navigation flow (e.g., how a user starts a new zine, edits, and exports)

### **5. Development Plan**

- **Milestones** (e.g., basic canvas working, text tools added, export feature completed)
- **Roles & Responsibilities** (who’s coding what?)
- **Collaboration Process** (e.g., using GitHub for version control)
    - GitHub - repo will belong to an organization where we all are members and can all push changes to
    - Suggestion: try a semi-professional workflow of pull requests and code reviews, if only for practice

### **6. Open Questions & Risks**

- Any parts of the project you’re unsure about? (e.g., best way to handle PDF generation)
- Potential challenges (e.g., performance with large zines)

### 7. Notes, research, helpful links

- [vance's p5.js notes on Notion](https://caesiumtea.notion.site/p5-js-19fd88f3aa31808fb493ff17fa27c941)

To look up:

- importing local files into p5.js
- drag and drop functionality in p5.js
- how to integrate p5.js with the rest of a web page
- does p5 use a regular HTML5 canvas element as its canvas?
- how to export canvas to PDF

[thanks chatgpt for outline](https://chatgpt.com/c/67b59359-2340-8000-ac76-75b58522bc53)
