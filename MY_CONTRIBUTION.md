# My Contribution — SmartSaver

Forked from the original team repository: https://github.com/nouf-sudi/SmartSaver

**Team**
- Nouf Ibrahim Suwaydi — Team lead, Front-End
- Fooz Abdulelah Atta — Back-End
- Shumukh Faisal Alsaedi — Front-End, Design
- **Raghad Sultan Alharbi — Back-End** (me)

Course project, Umm Al-Qura University · Project owner: Abdulaziz Alshaer

---

## My role: Back-End & Database

- Designed the relational data model in MySQL — `Users`, `Salaries` and
  `Expenses` tables with their relationships (one user to many salary records,
  one user to many expense records) and the primary/foreign key structure.
- Implemented user registration and login, including password encryption and
  validation of duplicate email addresses.
- Built the financial calculation layer:
  - fixed savings percentage applied to the entered salary
  - total expenses aggregated across categories
  - remaining surplus = salary − savings − total commitments
- Wrote the input validation that rejects zero or invalid salary values before
  any calculation runs.
- Connected the stored records to the dashboard views: previous records,
  spending summary, and the expense breakdown by category.

## Tech stack

PHP · MySQL · HTML · CSS · JavaScript · Git/GitHub · Agile-Scrum
