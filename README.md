# **password-hacker: 4-Week Roadmap**

This roadmap is designed to guide interns through the development of a sophisticated password-cracking
simulation tool using Python and React. Over four weeks, interns will gain knowledge in cybersecurity fundamentals,
hash algorithms, brute-force and dictionary attacks, as well as full-stack development.
By the end of the program, they will have built an ethically-driven, real-world inspired password cracking system from scratch.

---

## **Week 1: Foundations of Ethical Hacking & Tool Setup**

**Day 1: Introduction to the Project and Ethical Hacking Concepts**
- Overview of the project and its goals.
- Introduction to cybersecurity and ethical hacking principles.
- Overview of brute-force, dictionary attack, rainbow table, and other cracking methods.

**Day 2: Python Environment Setup**
- Install essential tools (Python, VSCode, pip, virtualenv).
- Git and GitHub basics (repo creation, cloning, pushing/pulling).

**Day 3: React Frontend Setup**
- Initialize a React project (`create-react-app`).
- Define project folder structure and initial layout.
- Basic UI: input field for password hashes, buttons for launching attacks.

**Day 4: Introduction to Hashing in Python**
- Understand MD5, SHA-1, SHA-256 algorithms.
- Use Python’s `hashlib` module for hashing and verifying passwords.

**Day 5: Basic Brute-Force Attack Implementation**
- Learn the logic behind brute-force attacks.
- Write a simple brute-force cracker (for short, weak passwords).

**Day 6: Weekly Review and Mini Challenge**
- Review and debug code.
- Mini-task: crack a given hash using a brute-force script.

---

## **Week 2: Advanced Attack Techniques & API Integration**

**Day 7: Implementing Dictionary Attacks**
- What is a dictionary attack? How are wordlists made?
- Use common wordlists like `rockyou.txt` for hash cracking.

**Day 8: Front-End to Back-End Connection (FastAPI)**
- Set up FastAPI and create basic endpoints.
- Send requests from React to FastAPI using axios.

**Day 9: Automatic Hash Recognition**
- Recognize hash type based on format or use tools like `hashid`.
- Choose the appropriate cracking method based on detected hash type.

**Day 10: React UI Enhancements**
- Display cracked password results.
- Add hash input, algorithm selector, and attack type selector components.

**Day 11: Rainbow Table Concepts and Simulation**
- Understand how rainbow tables work.
- Build a small precomputed rainbow table and perform lookups.

**Day 12: Weekly Review – Capture The Flag Mini Challenge**
- Crack a set of provided hashes.
- Combine front-end, back-end, and attack logic into a cohesive flow.

---

## **Week 3: Real-World Scenarios & Advanced Features**

**Day 13: Multithreading for Speed Optimization**
- Learn Python’s `threading` and `concurrent.futures`.
- Improve brute-force performance with multithreading.

**Day 14: Hybrid Attacks and Wordlist Expansion**
- Add logic for prefix, suffix, case mutations.
- Combine brute-force and dictionary methods.

**Day 15: Frontend State Management**
- Use React Context to manage application state.
- Implement loading spinners and progress indicators.

**Day 16: Logging Cracked Passwords**
- Connect FastAPI to a database (MongoDB or SQLite).
- Store previously cracked hashes and results.

**Day 17: Realistic Hash Dumps**
- Simulate cracking hashes from real-world data dumps (anonymized and ethical).
- Try different attack methods based on hash complexity.

**Day 18: Weekly Review – Team Presentations**
- Teams work on different hashes and present their cracking strategies.
- Discuss challenges and insights.

---

## **Week 4: Final Touches, Security, and Deployment**

**Day 19: User Authentication with JWT**
- Implement user registration and login in FastAPI.
- Use JWT for session management.
- Build forms and protected pages in React.

**Day 20: Security Controls and Rate Limiting**
- Add API rate limiting to prevent abuse.
- Limit number of attack attempts or add cooldown timers.

**Day 21: Error Handling and Testing**
- Add backend error handling and validations.
- Write simple unit and integration tests.

**Day 22: Frontend Deployment (Vercel)**
- Deploy the React app to Vercel.
- Set environment variables and check static routing.

**Day 23: Backend Deployment (Render / Railway / Heroku)**
- Deploy FastAPI to a cloud provider.
- Ensure front-end and back-end are connected and working in production.

**Day 24: Demo Preparation and Final Presentation**
- Prepare a short demo and walkthrough of the tool.
- Highlight what was built, how it works, and what was learned.

**Day 25–30: Hack Week (Optional Bonus Week)**
- Interns build their own unique password cracking strategies.
- Creative ideas encouraged: SSH brute-force simulators, password guessing games, CAPTCHA solvers, etc.
