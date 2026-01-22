# WinWidgets - GitHub Statistics Widgets

A collection of beautiful Windows widgets for displaying your GitHub statistics and activity directly on your desktop.

## Widgets Included

### 1. **GitHub Contributions** (`git_contributions.html`)
Displays your GitHub contribution heatmap in a compact, GitHub-style card format.

**Features:**
- Visual contribution heatmap
- Color-coded activity levels
- Clean, minimal design

### 2. **GitHub Activity Graph** (`git_graph.html`)
Shows your GitHub activity graph with commit patterns and contribution trends.

**Features:**
- Interactive activity graph
- Dark theme optimized
- Real-time updates

### 3. **GitHub Stats** (`git_stats.html`)
Comprehensive statistics widget showing your GitHub profile stats and contribution streak.

**Features:**
- Profile statistics (stars, commits, PRs, etc.)
- Contribution streak counter
- Customizable themes

##  Setup

1. **Replace Username**: 
   - Open each HTML file
   - Replace `YOUR_USERNAME` with your actual GitHub username
   - In `git_contributions.html`, replace `USERNAME` in the image URL

2. **Customize Themes** (Optional):
   - In `git_stats.html`, modify the `THEME` variable to change the color scheme
   - Available themes: `dark`, `date_night`, `github_dark`, and more

3. **Load in Windows Widgets**:
   - Open Windows Widgets
   - Add a custom widget
   - Select the HTML file you want to display

##  Customization

### Window Settings
Each widget includes meta tags for configuration:
- `windowSize`: Set widget dimensions
- `windowBorderRadius`: Adjust corner rounding
- `topMost`: Keep widget on top of other windows
- `windowLocation`: Set initial position

### Styling
All widgets use a dark GitHub-inspired theme (`#0d1117` background). You can modify the CSS in each file to match your preferences.

##  Files

- `git_contributions.html` - Contribution heatmap widget
- `git_graph.html` - Activity graph widget  
- `git_stats.html` - Statistics and streak widget

##  Requirements

- Windows 11 (Windows Widgets support)
- Active GitHub account
- Internet connection (widgets fetch data from GitHub APIs)

##  License

Free to use and modify for personal projects.

---

**Note**: Make sure to replace `YOUR_USERNAME` with your actual GitHub username in all files before using the widgets.
