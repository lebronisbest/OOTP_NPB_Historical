# NPB Historical Database for OOTP

[한국어](README_KR.md)

The most comprehensive Nippon Professional Baseball (NPB) historical database for Out of the Park Baseball.

## Features

| Category | Count |
|----------|-------|
| Players | 8,165 |
| Batting Records | 54,266 |
| Pitching Records | 24,951 |
| Pitchers with Repertoire | 349 |
| Team-Seasons | 1,032 |
| Years Covered | 1936-2025 |

### What's Included

- **Complete Statistics**: Batting, Pitching, Fielding for all NPB players since 1936
- **Advanced Metrics**: DRS (Defensive Runs Saved), park factors, era adjustments
- **Pitch Repertoires**: 349 pitchers with accurate pitch type data
- **Postseason Data**: Japan Series, Climax Series, All-Star games
- **Hall of Fame**: Complete voting records
- **Awards**: MVP, Best Nine, Golden Glove, Sawamura Award, Rookie of the Year
- **Minor League**: Ni-Gun (Farm) league data (2008-2025)
- **Visual Assets**: 100+ team logos, uniforms, ballpark files

## Installation

### Download

Click **Code → Download ZIP** or clone the repository.

### OOTP 26

1. Extract the zip file anywhere
2. Start OOTP 26 → New Game → Historical
3. Click **"Select Database"** and navigate to the extracted folder
4. Select the NPB database

### OOTP 25 and earlier

1. **Backup your original files first!** (MLB historical will be overwritten)
2. Extract and overwrite files to:
   - Steam: `C:\Program Files (x86)\Steam\steamapps\common\Out of the Park Baseball 25\data\database\`
   - Standalone: `C:\Program Files (x86)\Out of the Park Developments\OOTP Baseball 25\data\database\`
3. Start OOTP → New Game → Historical

> **IMPORTANT**: When setting up your historical game, set the league name to **"Japanese Probaseball League"** for proper functionality.
>
> **WARNING**: For OOTP 25 and earlier, this will replace your MLB historical database. Make sure to backup the original `data\database` folder if you want to play MLB historical later.

### Pre-1950 Single League Era

Before 1950, NPB was a single league. If you start a game in this era (1936-1949), you **MUST delete the National League** in league setup. Playing with two leagues during the single-league era will cause issues.

## File Structure

```
dist/
├── stats/
│   ├── historical_database.odb      # Main player database
│   ├── historical_lineups.odb       # Game lineups
│   ├── historical_minor_database.odb # Farm league data
│   ├── historical_transactions.odb  # Transactions
│   ├── Master.csv                   # Player master data
│   ├── Batting.csv                  # Batting statistics
│   ├── Pitching.csv                 # Pitching statistics
│   ├── Fielding.csv                 # Fielding statistics
│   └── ...                          # Additional CSV files
├── logos/                           # Team logos (100+)
├── ballparks/                       # Ballpark configurations
├── uniforms/                        # Team uniforms
├── schedules/                       # Season schedules (LSDL format)
└── fg_files/                        # FaceGen files
```

## Teams

### Central League
- Yomiuri Giants (1936-)
- Hanshin Tigers (1936-)
- Chunichi Dragons (1936-)
- Yokohama DeNA BayStars (1950-)
- Hiroshima Toyo Carp (1950-)
- Tokyo Yakult Swallows (1950-)

### Pacific League
- Orix Buffaloes (1936-)
- Fukuoka SoftBank Hawks (1938-)
- Saitama Seibu Lions (1950-)
- Chiba Lotte Marines (1950-)
- Hokkaido Nippon-Ham Fighters (1946-)
- Tohoku Rakuten Golden Eagles (2005-)

*Includes all historical franchises and name changes*

## Data Sources

- NPB Official Records
- Japanese Baseball Hall of Fame
- Various Japanese baseball statistics databases

## Known Limitations

- Some pre-war (1936-1945) records may be incomplete
- Pitch repertoire data is available for ~350 notable pitchers
- Minor league data starts from 2008

## Contributing

Found an error? Want to contribute?

- **Issues**: Use the Issues tab to report problems
- **Pitch Repertoire**: Submit pitcher's pitch types
- **Stat Corrections**: Report incorrect statistics
- **Missing Players**: Report players not in the database

## Changelog

### v1.0.0 (2025-01-11)
- Initial public release
- 8,165 players with complete statistics
- 349 pitchers with pitch repertoire data
- Full postseason and All-Star data
- Team logos and uniforms
- Minor league (Ni-Gun) data

## License

This project is for personal, non-commercial use with OOTP Baseball.

## Credits

Created with dedication to preserving NPB history for baseball simulation fans.

---

*If you enjoy this mod, consider starring the repository!*
