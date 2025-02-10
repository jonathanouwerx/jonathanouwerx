# Jonathan Ouwerx

I'm a Mathematics and Computer Science student at Duke University interested in software engineering and entrepreneurship. I love working on coding projects—big or small—even if I spend 20 hours building a tool to save me 2 minutes per week. I am Belgian, Danish, and British, and I hope to work in the US!

---

## Languages and Tools

<p>
  <img alt="Python" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" />
  <img alt="Golang" width="40px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/go/go-original-wordmark.svg" />
  <img alt="React" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
  <img alt="Git" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
  <img alt="GitHub" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
  <img alt="JavaScript" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" />
  <img alt="Linux" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />
  <img alt="HTML" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain.svg" />
  <img alt="CSS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain.svg" />
  <img alt="Vim" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vim/vim-original.svg" />
</p>


## Projects

### WhatsApp Reaction Checker (2025)
A Chrome extension that identifies which users have reacted to a WhatsApp message and highlights those who haven't from a predefined list.

[![View Repo](https://img.shields.io/badge/View_Repo-blue?style=for-the-badge)](https://github.com/jonathanouwerx/whatsapp_extension)


<details>
<summary>More Details</summary> 
<br/>
  
#### Key Features
- **Toggle Extension**: Easily enable or disable the extension via a popup switch.  
- **Manage Name List**: Add, remove, and manage a list of names directly from the popup.  
- **Real-time Reaction Check**: Automatically scrolls through reactions and identifies missing names.  
- **Persistent State**: Saves and loads the extension state and name list across sessions.

#### Tech Stack
- **Languages**: JavaScript, HTML, CSS  
- **APIs**: Chrome Extensions API

#### Screenshots
<p>
    <img alt="WhatsApp Reaction Checker Screenshot Missing Names" height="400px" style="padding-right:10px;" src="./assets/missing_names.png" />
    <img alt="WhatsApp Reaction Checker Screenshot Popup" height="400px" style="padding-right:10px;" src="./assets/popup_thin.png" />
</p>

</details>

---

###  Jump CLI Tool (2024)
A command line application to jump to predetermined points in the terminal, making navigation faster and more efficient.

Demo: https://jump-demo-nine.vercel.app/

[![View Repo](https://img.shields.io/badge/View_Repo-blue?style=for-the-badge)](https://github.com/jonathanouwerx/jump)

<details>
<summary>More Details</summary>

#### Key Features
- **Add Destinations**: Easily add new destinations with the `jump add <name>` command.  
- **Navigate to Destinations**: Quickly navigate to preset directories using the `jump to <name>` command.  
- **List Destinations**: View all saved destinations with the `jump list` command.  
- **Remove Destinations**: Remove specific or all destinations using the `jump rm <name>` command.

#### Tech Stack
- **Language**: V  
- **Libraries**: cli, os, v.vmod

</details>

---

### Online Jump CLI Demo (2025)

A demo showcasing how the Jump CLI tool can manage and navigate project directories efficiently in a browser environment.

Demo: https://jump-demo-nine.vercel.app/

[![View Repo](https://img.shields.io/badge/View_Repo-blue?style=for-the-badge)](https://github.com/jonathanouwerx/jump-demo)

<details>
<summary>More Details</summary>

#### Key Features
- **List Jumps**: Display all available jump locations.  
- **Add Jumps**: Add new jump locations in the working directory.  
- **Navigate Jumps**: Open directories in VS Code using jump commands.  
- **Remove Jumps**: Delete existing jump locations.

#### Tech Stack
- **Languages**: TypeScript  
- **Frameworks**: React, Vite  
- **APIs**: Wouter (for routing), xterm.js (for terminal emulation)

</details>    
   
---

### EVNT Event Planning Platform (Work In Progress) (2024-)
A comprehensive platform for planning and managing small and large scale events.

<!-- [![View Repo](https://img.shields.io/badge/View_Repo-blue?style=for-the-badge)](https://github.com/jonathanouwerx/WhatsAppReactionChecker) -->

<details>
<summary>More Details</summary>

#### Key Features
- **Event Creation**: Create and customize events with details, dates, and locations.
- **Group Organization**: Users are organized by group to streamline event management.
- **Payment Processing**: Integrated payment processing for event tickets and merchandise.
- **Event Analytics**: Track event attendance, revenue, and other metrics for analysis.

#### Tech Stack
- **Frontend**: React, React Native, Expo, Styled-Components
- **Backend**: Node.js, Express
- **Database**: Prisma, PostgreSQL

#### Screenshots
<p>
    <img alt="EVNT Image 1" height="400px" style="padding-right:10px;" src="./assets/evnt1.png" />
    <img alt="EVNT Image 2" height="400px" style="padding-right:10px;" src="./assets/evnt2.png" />
    <img alt="EVNT Image 4" height="400px" style="padding-right:10px;" src="./assets/evnt4.png" />
</p>

</details>

## Research

### Theoretical and Practical Effectiveness of Greedy Algorithms for the Travelling Salesman Problem (2021)
This paper analyzes Brute Force, Nearest Neighbour, and Greedy algorithms for solving the Travelling Salesman Problem (TSP). A Python framework was developed to compare their efficiency using randomized node sets and TSPLIB datasets. Results show that Greedy algorithms produce shorter tours than Nearest Neighbour but are significantly slower. The study highlights the trade-off between computational speed and solution accuracy in real-world applications.

[![Read Paper](https://img.shields.io/badge/Read_Paper-blue?style=for-the-badge)](https://github.com/jonathanouwerx/travelling_salesman/blob/master/Travelling%20Salesman%20Problem%20-%20Jonathan%20Ouwerx.pdf)

### Automated Parliaments: Enhancing AI Decision-Making (2023)
This paper introduces Automated Parliaments (APs), a framework for reducing decision uncertainty and misalignment in language models (LMs). APs consist of AI delegates, each representing a moral or decision-making framework, which collaboratively modify and evaluate responses. The study demonstrates how Automated Moral Parliaments (AMPs) can improve AI alignment with human values by integrating deontology, utilitarianism, and virtue ethics. Experiments using few-shot prompting show a 57.3% improvement in moral decision consistency. This research highlights APs' potential applications, including AI ethics, legal compliance, and policy-making.

[![Read Paper](https://img.shields.io/badge/Read_Paper-blue?style=for-the-badge)](https://arxiv.org/abs/2311.10098 )
