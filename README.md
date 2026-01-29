# Foreign Per Diem Calculator for USA-Based Institutions

An Excel tool for calculating international travel expenses. Integrates with U.S. State Department resources to provide accurate M&IE (Meals and Incidental Expenses) rates and automates deduction calculations for corporate, government, and academic organizations.

## Features

### Automated Data Handling
- **Date Management:** Auto-populates travel dates and calculates total travel days
- **Daily Totals:** Calculates expenses with meal deduction factors
- **Summary Section:** Aggregates total foreign per diem and travel days

### Integration with U.S. State Department Resources
- [M&IE Rates](https://aoprals.state.gov/content.asp?content_id=184&menu_id=78): Direct link to current rates by location
- [Meal Deduction Table](https://aoprals.state.gov/content.asp?content_id=114&menu_id=75): Auto-updates M&IE rate allocations

### User-Friendly Input
- **Checkbox Deduction System:** Mark travel days and provided meals
- **Optional Notes:** Additional context field for travel details

### Real-Time Calculations
- **Dynamic Fields:** Instant updates for totals and deductions
- **Error Reduction:** Automated calculations minimize manual errors

## How to Use

1. **Input Travel Dates**
   - Enter first and last travel days
   - Total travel days calculate automatically

2. **Enter Location Details**
   - Input city and country for each travel day

3. **Retrieve M&IE Rates**
   - Use the State Department website link
   - Enter applicable rates

4. **Mark Travel Days and Meals**
   - Check boxes for travel days
   - Indicate provided meals

5. **Review Results**
   - View daily totals with deductions
   - Check summary section

6. **Add Notes**
   - Document specific details or exceptions

## Technical Details

### Excel Formulas
```excel
Travel day calculation: =F2-F1
Daily totals: Sum(M&IE rate - deductions)
Summary totals: =SUM(H:H)
```

### Dynamic Features
- Auto-updating M&IE rate lookup
- Real-time meal deduction calculations

## Requirements

- Microsoft Excel 2016 or later
- Internet connection for real-time rates

## Best Practices

- Attach M&IE rate documentation
- Verify calculations before submission

## License

Foreign Per Diem Calculator for USA-Based Institutions © 2019 Philip Bachas-Daunert

Distributed under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/).
