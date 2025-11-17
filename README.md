# Simple-Statistics-App
Stats App for BukSU-Talakag

Stat-Ease Analyst: Statistical Test Selector
This is a single-file, fully functional interactive web application designed to help students and researchers easily select the correct statistical test (parametric vs. non-parametric, one-sample vs. two-sample, t-test vs. z-test) based on a series of guided questions.
The application also includes calculators for the following tests:
One-Sample Tests: t-Test, Z-Test, Proportion Z-Test, Sign Test (Non-parametric)
Two-Sample Tests: Independent t-Test (Welch's), Independent Z-Test, Paired t-Test, Two-Sample Proportion Z-Test
Non-Parametric Two-Sample Tests: Mann-Whitney U Test (Wilcoxon Rank Sum), Wilcoxon Signed-Rank Test (Paired)
Results display calculated statistics, hypotheses formulated in LaTeX (rendered via MathJax), and a graphical representation of the rejection region for Z and t-tests.
🚀 Deployment Instructions (for Students)
Since this project is contained within a single HTML file (stat_ease_analyst.html), deploying it as a functional website is extremely easy using GitHub Pages.
Create a New Repository: Create a new public repository on GitHub (e.g., stat-ease-analyst).
Upload the File: Upload the file named stat_ease_analyst.html to the root directory of this new repository.
Enable GitHub Pages:
Go to your repository's Settings tab.
Navigate to Pages in the sidebar.
Under "Build and deployment," choose Deploy from a branch.
Select your main branch (usually main or master) and set the folder to / (root).
Click Save.
Access the Live Tool: GitHub will provide a URL (e.g., https://[YourUsername].github.io/stat-ease-analyst/) where the tool will be live and usable within a minute or two.
🛠️ Technology Stack
HTML: Structure
Tailwind CSS (via CDN): Styling and responsiveness
JavaScript: Core logic and calculations
jStat: Advanced statistical function library
MathJax: Rendering of mathematical notation (Latex)
