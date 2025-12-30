# 🎓 RTU CGPA Calculator

**Official Rajasthan Technical University Grade Point Calculator**

Calculate your CGPA/SGPA accurately according to RTU grading standards. Enter your marks or grades manually for instant calculation.

---

## ✨ Key Features

### 📊 Calculation Methods
- **✍️ Manual Entry** - Enter marks or grades directly
- **📊 Individual Grades** - Enter course-wise grades and credits

### 🎯 RTU Grading System (Official)
Follows the exact RTU grading scale:

| Marks Range | Grade | Grade Points |
|-------------|-------|--------------|
| ≥ 90        | A++   | 10.0         |
| 85-89       | A+    | 9.0          |
| 80-84       | A     | 8.5          |
| 75-79       | B+    | 8.0          |
| 70-74       | B     | 7.5          |
| 65-69       | C+    | 7.0          |
| 60-64       | C     | 6.5          |
| 55-59       | D+    | 6.0          |
| 50-54       | D     | 5.5          |
| 45-49       | E+    | 5.0          |
| 40-44       | E     | 4.0          |
| < 40        | F     | 0.0          |

### 📈 Division Classification
- **CGPA ≥ 7.0** → I Division with Distinction
- **6.0 ≤ CGPA < 7.0** → I Division
- **5.0 ≤ CGPA < 6.0** → II Division
- **4.0 ≤ CGPA < 5.0** → Pass

### 🧮 Calculation Formula
```
SGPA = Σ(Credits × Grade Points) / Σ(Credits)
CGPA = Σ(SGPA × Credits) / Σ(Credits)
Percentage = CGPA × 10
```

---

## 🚀 Quick Start

### Method 1: Enter Marks Manually
1. Go to **CGPA Calculator** tab
2. Fill in:
   - Student Name (optional)
   - Roll Number (optional)
   - Semester
   - Number of Subjects
   - Total Obtained Marks
   - Total Marks
3. Click **"Calculate CGPA"**
4. ✅ **Get your CGPA with grade and division!**

### Method 2: Enter Individual Grades
1. Scroll to course entry section
2. Click **"Add Course"**
3. Enter:
   - Course Name
   - Grade (A++, A+, A, B+, etc.)
   - Credits
4. Repeat for all courses
5. ✅ **Automatic SGPA calculation!**

---


## 🎯 Example Calculation

### Example 1: SGPA Calculation
```
Mathematics:    A++  (10.0 points) × 4 credits = 40.0
Physics:        B+   (8.0 points)  × 3 credits = 24.0
Chemistry:      A    (8.5 points)  × 3 credits = 25.5
Programming:    A+   (9.0 points)  × 4 credits = 36.0
─────────────────────────────────────────────────────
Total:                             14 credits   125.5

SGPA = 125.5 / 14 = 8.96 ✅
Percentage = 8.96 × 10 = 89.6%
Division: I Division with Distinction
```

### Example 2: CGPA Calculation
```
Semester 1: SGPA 8.5 × 22 credits = 187.0
Semester 2: SGPA 9.0 × 24 credits = 216.0
Semester 3: SGPA 8.7 × 26 credits = 226.2
────────────────────────────────────────
Total:              72 credits    629.2

CGPA = 629.2 / 72 = 8.74 ✅
Percentage = 8.74 × 10 = 87.4%
Division: I Division with Distinction
```

---

## 🔧 Technical Details

### Built With
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **UI Framework**: Bootstrap 5.3
- **Icons**: Font Awesome 6.4

### Browser Support
- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

### Features
- 📱 Fully Responsive - Works on all devices
- 🌙 Dark Mode - Comfortable for eyes
- 💾 Offline Support - No internet needed after loading
- 🔒 100% Privacy - All data stored locally
- ⚡ Fast & Accurate - Instant calculations

---

## 🎨 Additional Study Tools

Bonus features included:
- **Subject Tracker** - Manage multiple subjects
- **Topic Planner** - Organize study topics with priorities
- **Pomodoro Timer** - 25-minute focus sessions
- **Flashcards** - Create and review flashcards
- **Notes** - Save subject-specific notes
- **Goals Tracker** - Set and achieve study goals
- **Study Streak** - Track consecutive study days

---

## 🆘 Troubleshooting

### Wrong Calculation?
- Verify grade points match RTU scale
- Check if credits are entered correctly
- Ensure all courses are included
- Manual verification recommended

### Calculator Not Loading?
- Clear browser cache and refresh
- Check if JavaScript is enabled
- Try different browser
- Ensure internet connection for first load

---

## 📱 How to Use

### Running Locally
1. **Download** or clone this repository
2. **Open** `index.html` in your browser
3. **Start calculating!**

### Using Local Server (Optional)
```bash
# Python
python -m http.server 8080

# Then visit: http://localhost:8080
```

---

## 🔐 Privacy & Security

- ✅ **100% Local Storage** - All data stays in your browser
- ✅ **No Server** - No data sent anywhere
- ✅ **No Tracking** - Zero analytics or tracking
- ✅ **No Login** - No account required
- ✅ **Your Control** - Export/delete anytime

---

## 📝 Formula Reference

### SGPA (Semester Grade Point Average)
```
SGPA = Σ(ci × gi) / Σci

Where:
  ci = Credits of course i
  gi = Grade points of course i
```

### CGPA (Cumulative Grade Point Average)
```
CGPA = Σ(Si × Ci) / ΣCi

Where:
  Si = SGPA of semester i
  Ci = Credits of semester i
```

### Percentage Conversion
```
Percentage = CGPA × 10
```

---

## 🎓 Perfect For

- ✅ RTU B.Tech Students
- ✅ RTU B.Sc Students
- ✅ RTU Diploma Students
- ✅ Any RTU Affiliated College Students
- ✅ Academic Planning & Tracking

---

## 📞 Support

For issues or questions:
1. Check the **Troubleshooting** section above
2. Open browser console (F12) to see error details
3. Verify your input data matches RTU format

---

## 📄 License

Free to use for educational purposes. No warranty provided.

---

**Made with ❤️ for RTU Students**

*Calculate Smart, Study Hard! 📚✨*
