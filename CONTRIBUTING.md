# Contributing

[한국어](CONTRIBUTING_KR.md)

Thank you for your interest in contributing to the NPB Historical Database!

## Ways to Contribute

### 1. Submit Issues (Easy)

Use GitHub Issues for:
- **Nickname** - Player nickname submissions
- **Pitch Repertoire** - Pitcher pitch type submissions
- **Stat Correction** - Report incorrect stats
- **Missing Player** - Report missing players
- **Feature Request** - Suggest improvements

No coding required! Just fill out the issue template.

### 2. Pull Requests (For Files)

For contributing files like logos, uniforms, ballparks, etc.

#### Option A: Web Upload (No Git Required)

1. Click "Fork" at the top right of the repository page
2. In your fork, navigate to the folder you want to add files to
3. Click "Add file" → "Upload files"
4. Drag and drop your files
5. Click "Commit changes"
6. Click "Contribute" → "Open pull request"
7. Submit your pull request

#### Option B: Using Git

##### Step 1: Fork the Repository

Click the "Fork" button at the top right of the repository page.

##### Step 2: Clone Your Fork

```bash
git clone https://github.com/YOUR_USERNAME/OOTP_NPB_Historical.git
cd OOTP_NPB_Historical
```

##### Step 3: Add Your Files

Add your files to the appropriate folder:

| Content | Folder | Format |
|---------|--------|--------|
| Team Logos | `logos/` | PNG 150x150 |
| Jerseys | `uniforms/jerseys/` | PNG |
| Pants | `uniforms/pants/` | PNG |
| Ballcaps | `uniforms/ballcap/` | PNG |
| Socks | `uniforms/socks/` | PNG |
| Ballparks | `ballparks/` | - |
| Schedules | `schedules/` | - |
| Facegen | `fg_files/` | - |

##### Step 4: Commit and Push

```bash
git add .
git commit -m "Add [description of your contribution]"
git push
```

##### Step 5: Create Pull Request

1. Go to your fork on GitHub
2. Click "Contribute" → "Open pull request"
3. Add a description of your changes
4. Submit the pull request

## File Naming Conventions

Use the OOTP registered team name (not the real corporate name).

### Logos
```
teamname_startyear-endyear_hex1_hex2.png
```
Examples:
- `tokyo_giants_1961-1974_F97709_000000.png`
- `tokyo_giants_1975-1992_F97709_000000.png`
- `osaka_tigers_1961-1999_FFE100_000000.png`

### Uniforms
```
type_teamname_startyear-endyear.png (home)
type_teamname_away_startyear-endyear.png (away)
type_teamname_alt_startyear-endyear.png (alternate)
```
Types: `jerseys`, `pants`, `caps`, `socks`

Examples:
- `jerseys_Tokyo_Giants_1975-1992.png`
- `jerseys_Tokyo_Giants_away_1975-1992.png`
- `pants_Tokyo_Giants_1975-1992.png`
- `caps_Tokyo_Giants_away_1975-1992.png`

## Questions?

Open an issue with the **Feature Request** template if you have questions.
