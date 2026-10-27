# Student Performance Dashboard (Power BI)

An interactive **Power BI** dashboard exploring what affects secondary school students' mathematics grades, using the [UCI Student Performance dataset](https://archive.ics.uci.edu/dataset/320/student+performance).

## Dashboard pages
| Page | What it shows |
|---|---|
| **Home** | Key figures with cards and gauges, plus navigation buttons |
| **Performance** | Grade 3 maths result by study time and gender, failures vs grades, grade trend by period and plans for higher education |
| **Demographic** | Grades by gender, home address (urban/rural) and total parent education |
| **Support** | Grades by internet access and father's job |
| **Risks** | Grades by romantic relationship and going-out frequency |

Each page has slicers to filter the data, and a navigation bar to move between pages.

## Data preparation
- Raw data: `data/maths_raw.xlsx`, `data/portuguese_raw.xlsx`
- Cleaned in **Weka** (`data/maths_cleaned.arff`): renamed attributes to readable names (e.g. `Medu` → `MotherEducation`), relabelled codes (`U/R` → `Urban/Rural`, `A/T` → `Apart/Together`), removed unused columns, added a **Total Parent Education** feature and discretised grades into bins

## Open it
Download `student_performance_dashboard.pbix` and open it in **Power BI Desktop** (free).

## Tools
Power BI Desktop · Weka · Excel

> Coursework project, Bachelor of Information Systems (Hons.) Intelligent Systems Engineering, UiTM Shah Alam.
