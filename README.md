# Foreign Per Diem Calculator for USA-Based Institutions

[![Link Check](https://github.com/hihipy/foreign-per-diem-calculator-for-usa-based-institutions/actions/workflows/links.yml/badge.svg)](https://github.com/hihipy/foreign-per-diem-calculator-for-usa-based-institutions/actions/workflows/links.yml)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**Built with**

[![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/microsoft-365/excel)

An Excel tool for calculating international travel expenses. It links to U.S. State Department resources for current M&IE (Meals and Incidental Expenses) rates and automates the deduction calculations for corporate, government, and academic organizations.

---

## Features

### Automated Data Handling

- **Date management:** Auto-populates travel dates and calculates total travel days
- **Daily totals:** Calculates expenses with meal deduction factors
- **Summary section:** Aggregates total foreign per diem and travel days

### Integration with U.S. State Department Resources

- [M&IE Rates](https://aoprals.state.gov/content.asp?content_id=184&menu_id=78): Direct link to current rates by location
- [Meal Deduction Table](https://aoprals.state.gov/content.asp?content_id=114&menu_id=75): Updates M&IE rate allocations

### Input

- **Checkbox deductions:** Mark travel days and provided meals
- **Optional notes:** A field for additional travel details

### Live Calculations

- **Dynamic fields:** Totals and deductions update as you type
- **Fewer errors:** Automated calculations cut down on manual mistakes

---

## How to Use

1. **Input travel dates**
   - Enter first and last travel days
   - Total travel days calculate automatically
2. **Enter location details**
   - Input city and country for each travel day
3. **Retrieve M&IE rates**
   - Use the State Department website link
   - Enter the applicable rates
4. **Mark travel days and meals**
   - Check boxes for travel days
   - Indicate provided meals
5. **Review results**
   - View daily totals with deductions
   - Check the summary section
6. **Add notes**
   - Document specific details or exceptions

---

## Technical Details

### Excel Formulas

```excel
Travel day calculation: =F2-F1
Daily totals: Sum(M&IE rate - deductions)
Summary totals: =SUM(H:H)
```

### Dynamic Features

- Auto-updating M&IE rate lookup
- Live meal deduction calculations

---

## Requirements

- Microsoft Excel 2016 or later
- Internet connection for current rates

---

## Best Practices

- Attach M&IE rate documentation
- Verify calculations before submission

---

## License

This project is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

You are free to:

- Use, share, and adapt this work
- Use it at your job

Under these terms:

- **Attribution:** Credit the original author
- **NonCommercial:** No selling or commercial products
- **ShareAlike:** Derivatives must use the same license
