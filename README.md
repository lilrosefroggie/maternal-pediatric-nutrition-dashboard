# maternal-pediatric-nutrition-dashboard
# Maternal & Pediatric Nutrition Dashboard

A comprehensive, evidence-based nutrition dashboard designed for dietitians and healthcare professionals working with mothers and children. This interactive web application provides clinical guidelines, nutrient recommendations, and practical resources across seven critical life stages.

![Dashboard Preview](https://img.shields.io/badge/React-18.x-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## 🎯 Purpose

This dashboard serves as a clinical reference tool for dietitians, nutritionists, and healthcare providers to:
- Access evidence-based nutrition guidelines for maternal and child health
- Identify critical nutrient requirements and deficiency risks
- Recognize clinical red flags requiring intervention
- Provide culturally appropriate meal plans for families using SNAP/WIC benefits
- Support health equity by addressing disparities in maternal and child nutrition

## ✨ Key Features

### 📊 Seven Life Stages Covered
- **Preconception** - Preparing for pregnancy
- **Pregnancy** - Prenatal nutrition
- **Postpartum** - Recovery and lactation support
- **Infant (0-12 months)** - Early feeding guidelines
- **Toddler (1-3 years)** - Transition to family foods
- **Child (4-8 years)** - School-age nutrition
- **Adolescent (9-18 years)** - Pre-teen and teen health and development

### 🔍 Interactive Features
- **Smart Search**: Search across all stages for specific nutrients, guidelines, or conditions
- **Stage-Specific Content**: Detailed nutrient recommendations with evidence-based rationales
- **Clinical Red Flags**: Alert system for high-risk nutritional concerns
- **Health Equity Focus**: Highlights populations at increased risk for deficiencies

### 📋 Practical Resources
- **Sample Meal Plans**: SNAP and WIC-approved meal examples for each life stage
- **Supplement Guidelines**: Evidence-based supplementation protocols with dosing and timing
- **Food Safety Guide**: Stage-appropriate safety recommendations
- **Food Assistance Resources**: Direct links to SNAP, WIC, food banks, and community resources

## 🏥 Evidence-Based Guidelines

This dashboard integrates recommendations from:
- **ACOG** (American College of Obstetricians and Gynecologists)
- **AAP** (American Academy of Pediatrics)
- **DRI** (Dietary Reference Intakes)
- **Dietary Guidelines for Americans 2020-2025**
- **USDA Food and Nutrition Service**

## 🛠️ Technology Stack

- **Frontend Framework**: React 18.x
- **UI Components**: Lucide React icons
- **Styling**: Tailwind CSS (utility classes)
- **Build Tool**: Vite
- **Deployment**: GitHub Pages compatible

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

## 📱 Usage

### For Healthcare Providers

1. **Select a Life Stage**: Click on the appropriate stage button at the top of the dashboard
2. **Review Key Nutrients**: See critical nutrients with dosing and clinical rationales
3. **Check Red Flags**: Review warning signs that require immediate attention
4. **Access Resources**: Use the Quick Actions sidebar to view meal plans, supplements, and food safety guidelines
5. **Search Functionality**: Use the search bar to quickly find information across all stages

### For Patient Education

The dashboard includes downloadable patient handouts (feature in development) and links to free resources including:
- Food assistance program locators
- Budget-friendly recipe databases
- Breastfeeding support services
- Culturally diverse meal planning resources

## 🎨 Features Walkthrough

### Nutrient Priority System
- 🔴 **CRITICAL**: Red highlighting for life-critical nutrients (e.g., folic acid in pregnancy)
- ⚠️ **COMMON DEFICIENCY**: Yellow highlighting for frequently deficient nutrients
- Standard presentation for important but typically adequate nutrients

### Focus on Health Equity as a Dimension of Nutrition
It is critical to address nutrition insecurity alongside food insecurity. The dashboard specifically addresses:
- Population-specific deficiency risks 
- Socioeconomic barriers to nutrition
- Cultural food preferences and practices
- Access to affordable, nutritious foods

## 📖 Documentation

### Content Structure
```
stageContent = {
  [stageName]: {
    keyNutrients: [],    // Nutrient recommendations with amounts and rationales
    redFlags: [],        // Clinical warning signs
    focusAreas: []       // Priority counseling topics
  }
}
```

### Adding New Content
To add or modify nutritional guidelines:
1. Locate the `stageContent` object in `src/NutritionDashboard.jsx`
2. Add nutrients following the existing structure
3. Include evidence source (ACOG, AAP, DRI)
4. Mark priority level using 🔴 or ⚠️ emojis

## 🤝 Contributing

Contributions are welcome! This dashboard benefits from:
- Updated clinical guidelines
- Additional cultural meal plans
- Translation support
- User experience improvements

Please ensure all clinical content includes appropriate evidence sources.

**Last Updated**: December 2024 | **Version**: 1.0.0

*This dashboard is intended for use by qualified healthcare professionals. It does not replace individualized medical nutrition therapy or clinical judgment.*
