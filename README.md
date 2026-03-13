# ❤️ Heart Disease Interactive Dashboard

A professional, AI-powered interactive dashboard for analyzing heart disease data with real-time modifications through an integrated AI chatbot assistant.

## 🌟 Features

### 📊 Dashboard Components
- **Age Distribution** - Bar chart showing patient age groups
- **Disease vs Healthy** - Pie chart with disease prevalence
- **Cholesterol by Age** - Line chart tracking cholesterol trends
- **Age vs Cholesterol** - Scatter plot showing correlations

### 🎛️ Interactive Controls
- **Dual-mode Theme** - Toggle between dark and light modes
- **Age Range Filter** - Adjust patient age (20-77 years)
- **Cholesterol Filter** - Control cholesterol levels (100-600 mg/dL)
- **Real-time Updates** - Charts update instantly on filter changes

### 🤖 AI Chatbot Assistant
- Natural language commands to modify dashboard
- Filter data by age/cholesterol ranges
- Update dashboard title and configuration
- Toggle chart visibility
- Download Python code with current configuration

### 📈 Key Statistics
- Total Patients Count
- Disease Cases & Healthy Patients
- Disease Rate Percentage
- Average Age & Cholesterol Levels

## 🚀 Quick Start

### Installation
```bash
git clone https://github.com/yourusername/heart-disease-dashboard.git
cd heart-disease-dashboard
npm install
```

### Running the Dashboard
```bash
npm start
```
The dashboard will open at `http://localhost:3000`

## 💬 AI Assistant Commands

| Command | Example | Action |
|---------|---------|--------|
| Filter Age | "Filter age 40-60" | Updates age range |
| Filter Cholesterol | "Filter cholesterol 200-250" | Updates chol range |
| Change Title | "Change title to Cardiac Analysis" | Updates dashboard title |
| Show/Hide Charts | "Hide age distribution" | Toggle chart visibility |
| Get Help | "Help" | Display all commands |
| Download | "Download code" | Export Python configuration |

## 📦 Tech Stack

- **Frontend**: React with Hooks
- **Charts**: Recharts (Bar, Pie, Line, Scatter)
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **State Management**: React useState/useMemo
- **AI Chat**: Integrated chatbot with NLP processing

## 📊 Dataset Structure

### heart.csv (303 patients, 14 features)
```json
{
  "age": "Patient age (29-77)",
  "sex": "Gender (0/1)",
  "cp": "Chest pain type (0-3)",
  "trestbps": "Resting blood pressure",
  "chol": "Serum cholesterol (mg/dL)",
  "fbs": "Fasting blood sugar",
  "restecg": "Resting ECG results",
  "thalach": "Max heart rate achieved",
  "exang": "Exercise induced angina",
  "oldpeak": "ST depression",
  "slope": "ST segment slope",
  "ca": "Coronary arteries calcification",
  "thal": "Thalassemia type",
  "target": "Heart disease (0=healthy, 1=disease)"
}
```

## 🎨 Customization

### Dashboard Configuration
```javascript
dashboardConfig = {
  title: "❤️ Heart Disease Dashboard",
  chartColors: {
    primary: "#3b82f6",
    success: "#10b981",
    danger: "#ef4444",
    warning: "#f59e0b"
  },
  visibleCharts: ["age", "disease", "cholesterol", "scatter"]
}
```

### Modify Theme Colors
- Edit `dashboardConfig.chartColors` object
- Colors automatically sync across all charts
- Supports both dark and light modes

## 📥 Download Python Code

Click the "Code" button in the dashboard to download:
- Dashboard configuration in JSON format
- Python script template for data analysis
- Current filter settings

## 🔧 Available Scripts
```bash
npm start          # Start development server
npm run build      # Build for production
npm run deploy     # Deploy to hosting
```

## 📱 Responsive Design
- ✅ Mobile-friendly layout
- ✅ Tablet optimized
- ✅ Desktop full-width charts
- ✅ Touch-friendly controls

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

## 📄 License

This project is licensed under the MIT License - see LICENSE file for details

## 👨‍💻 Author

**Data Science Dashboard Developer**
- Dashboard Creation: January 2026
- AI Integration: January 2026
- Dataset: Heart Disease UCI ML Repository

## 📞 Support

For issues, questions, or suggestions:
- 📧 Email: support@heartdashboard.com
- 🐛 Issues: GitHub Issues
- 💬 Discussions: GitHub Discussions

## 🎯 Future Enhancements

- [ ] Real-time database integration
- [ ] User authentication & profiles
- [ ] Advanced ML model predictions
- [ ] Export to PDF reports
- [ ] Multi-language support
- [ ] Dark mode persistence
- [ ] Data upload functionality

---

## Project Structure
```
heart-disease-dashboard/
├── src/
│   ├── components/
│   │   ├── Dashboard.jsx
│   │   ├── ChatBot.jsx
│   │   └── Charts.jsx
│   ├── styles/
│   │   └── tailwind.css
│   └── App.jsx
├── public/
├── package.json
├── README.md
└── LICENSE
```

## 📊 Demo Screenshot
[Your dashboard screenshot here]

## 🏆 Key Achievements
✅ Interactive real-time filtering  
✅ AI-powered chatbot control  
✅ Professional data visualization  
✅ Dark/Light theme support  
✅ Responsive design  
✅ JSON configuration export  
✅ Python code generation  

---
## link :

https://claude.ai/chat/fec4fe05-1aa4-45da-af49-1bc72a351bf8?artifactId=heart_disease_dashboard


Made with ❤️ for data science enthusiasts
