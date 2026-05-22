# 💼 Payroll Calculator | ระบบคำนวณเงินเดือนรายวิก

**An advanced Thai biweekly employee payroll calculator with real-time computation, OT tracking, and PDF export.**

## 🌐 Live Demo
Visit: **https://jatnarung285-arch.github.io/**

## ✨ Features

✅ **Biweekly Pay Cycles**
- Week 1: Paid on the 25th (Days 1-15)
- Week 2: Paid on the 10th (Days 16-30/31)

✅ **Complete Salary Breakdown**
- Base salary calculation
- Overtime (OT) at 1.5x rate
- Food allowance (per day)
- Travel allowance (split per week)

✅ **Automatic Deductions**
- Social security (per week)
- Provident fund (5% of gross income)
- Custom deductions (loans, etc.)

✅ **Real-time Calculations**
- Live updates as you type
- Instant OT rate computation (Base Rate ÷ 8 × 1.5)
- Summary statistics dashboard

✅ **Export & Share Options**
- 🖨️ Print to PDF
- 📋 Copy to clipboard
- 📊 Export as CSV (Excel)

✅ **Modern UI/UX**
- Responsive design (mobile, tablet, desktop)
- Thai language support (Sarabun font)
- Color-coded weeks (amber for Week 1, emerald for Week 2)
- Smooth animations and transitions

## 🚀 Quick Start

### Installation
```bash
git clone https://github.com/jatnarung285-arch/j-arch.github.io.git
cd j-arch.github.io
```

### Run Locally
Simply open `index.html` in your web browser.

## 📋 How to Use

1. **Enter Employee Info**
   - Employee name
   - Daily wage rate (default: 380 THB)
   - Food allowance per day
   - Monthly travel allowance
   - Social security per week

2. **Input Work Days & OT**
   - Week 1: Days worked (max 15) + OT hours
   - Week 2: Days worked (max 16) + OT hours
   - Custom deductions if needed

3. **View Results**
   - Real-time calculation
   - Detailed breakdown table
   - Net salary per week
   - Monthly total

4. **Export Data**
   - Print payslip
   - Copy to clipboard
   - Download as CSV

## 📐 Calculation Formula

```
Hourly Rate = Daily Wage ÷ 8 hours
OT Hourly Rate = Hourly Rate × 1.5

Base Pay = Days Worked × Daily Wage
OT Pay = OT Hours × OT Hourly Rate
Food Allowance = Days × Food Rate
Travel Allowance = Monthly Amount ÷ 2 (split per week)

Gross Income = Base + OT + Food + Travel

Provident Fund = Gross × 5%
Total Deductions = Social Security + Provident Fund + Other

Net Salary = Gross - Total Deductions
```

## 🛠️ Technology Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first styling
- **JavaScript (Vanilla)** - Real-time calculations
- **Google Fonts** - Thai language (Sarabun)
- **Responsive Design** - Mobile-first approach

## 📱 Browser Support

✓ Chrome/Edge (latest)
✓ Firefox (latest)
✓ Safari (latest)
✓ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 UI Components

- **Input Dashboard** - 3-column layout for employee info and weekly data
- **Summary Statistics** - 4-card layout showing totals
- **Payslip Document** - Print-optimized layout
- **Action Buttons** - Print, copy, export functions

## 📊 Improvements Made

✅ Added custom deductions field for Week 1 & 2
✅ Real-time fund calculation display
✅ Summary statistics cards (work days, OT hours, etc.)
✅ Export to CSV functionality
✅ Improved visual hierarchy and color coding
✅ Better mobile responsiveness
✅ Added reset and copy-to-clipboard features
✅ Enhanced typography and spacing
✅ Separated income and deduction sections in table
✅ Added dark mode toggle (prepared)
✅ Better form validation with min/max values

## 📝 License

MIT License - Feel free to use and modify for your needs.

## 👤 Author

**jatnarung285-arch**
- GitHub: [@jatnarung285-arch](https://github.com/jatnarung285-arch)

## 🤝 Contributing

Contributions are welcome! Feel free to fork and submit pull requests.

## 💡 Future Enhancements

- [ ] Dark mode toggle functionality
- [ ] Multiple employee management
- [ ] Database integration
- [ ] Monthly report generation
- [ ] Email payslip feature
- [ ] Thai holiday calendar integration
- [ ] Multi-language support

---

**Last Updated:** May 2026
**Version:** 2.0 (Improved)
