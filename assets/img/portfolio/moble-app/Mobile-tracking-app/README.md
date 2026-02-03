# FitTrack - Fitness Tracking Mobile App (HTML5 & CSS3)

A comprehensive fitness tracking mobile app converted to pure HTML5 and CSS3 with 14 complete screens.

## 📱 Features

### Design
- **Black background with white text** color scheme
- **iPhone-style status bars** and home indicators
- **Bottom navigation menu** on all main screens with 5 icon links:
  - 🏠 Home (Dashboard)
  - 🎯 Goals
  - ⚡ Activity (Center button - elevated)
  - 📊 Stats (Trends)
  - 👤 Profile
- **Mobile-first responsive design** (max-width: 390px for phone simulation)
- **Interactive elements** with hover effects

### Screens (14 Total)

1. **welcome.html** - Welcome/Onboarding screen
2. **register.html** - User registration
3. **login.html** - User login
4. **forgot-password.html** - Password recovery
5. **dashboard.html** - Main dashboard with daily statistics
6. **trends.html** - Weekly/monthly trends with charts
7. **activity-log.html** - Real-time activity tracking with pedometer
8. **goals.html** - Fitness goals overview
9. **goal-progress.html** - Detailed goal progress tracking
10. **history.html** - Activity history
11. **profile.html** - User profile and settings
12. **notifications.html** - Push notification settings
13. **integrations.html** - Wearable device integrations (Apple Watch, Fitbit, Garmin, etc.)
14. **health-sync.html** - Health app syncing (Apple Health, Google Fit, Samsung Health, Strava)

## 🎨 Styling

All styles are contained in `styles.css` with:
- Custom CSS3 variables
- Flexbox and Grid layouts
- SVG icons (inline)
- Smooth transitions and animations
- Bar charts and line charts using pure CSS/SVG
- Progress bars and circular progress indicators

## 🚀 Getting Started

### Option 1: Open Locally
1. Navigate to the `/public` folder
2. Open `dashboard.html` (or any screen) in your web browser
3. Use the dropdown selector at the top to navigate between screens

### Option 2: Use Bottom Navigation
- Click on the bottom navigation icons to navigate between main screens:
  - Home icon → Dashboard
  - Goals icon → Goals
  - Center Activity button → Activity Log
  - Stats icon → Trends
  - Profile icon → Profile

### Option 3: Direct Links
Open any HTML file directly:
- `welcome.html` - Start here for the welcome experience
- `dashboard.html` - Main app dashboard
- `login.html` - Login screen

## 📊 Charts and Visualizations

The app includes various data visualizations using pure CSS and SVG:

### Bar Charts
- Weekly activity statistics
- Multi-series data (workouts, minutes, calories)
- Animated on hover

### Line Charts
- Weight progress over time
- Monthly activity trends
- SVG-based with smooth curves

### Progress Circles
- Goal completion percentage
- Step counter visualization
- Calorie burn tracking

### Progress Bars
- Goal progress indicators
- Activity distribution
- Horizontal percentage bars

## 🎯 Interactive Elements

### Bottom Navigation
- 5 navigation items with icon links
- Active state highlighting (orange color)
- Center button with elevated design
- Hover effects on all buttons

### Toggle Switches
- Notification settings
- Sync preferences
- Click to toggle on/off
- Smooth animation

### Buttons
- Primary actions (orange background)
- Secondary actions (outlined)
- Hover and active states
- Smooth transitions

### Cards
- Activity cards
- Goal cards
- Integration cards
- Notification cards
- All with hover effects

## 🔗 Navigation Links

All screens are interconnected via:
1. **Screen Selector Dropdown** - At the top of each page
2. **Bottom Navigation Bar** - 5 main screens (Home, Goals, Activity, Stats, Profile)
3. **In-Page Links** - Back buttons, "View All" links, menu items
4. **Form Submissions** - Login/Register redirect to dashboard

## 🎨 Color Palette

- **Background**: `#000000` (Black)
- **Cards**: `#1a1a1a` (Dark gray)
- **Borders**: `#333333` (Medium gray)
- **Text Primary**: `#ffffff` (White)
- **Text Secondary**: `#999999` (Light gray)
- **Primary Color**: `#f97316` (Orange)
- **Success**: `#22c55e` (Green)
- **Error**: `#ef4444` (Red)

## 📱 Mobile Mockup

Each page includes a realistic iPhone mockup with:
- Notch at the top
- Status bar (time, signal, wifi, battery)
- Screen content area (390px × 844px)
- Home indicator bar at the bottom
- Phone frame with rounded corners

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox & Grid
- **SVG** - Icons and chart graphics
- **JavaScript** - Minimal (only for navigation and toggles)

## 📂 File Structure

```
/public/
├── index.html (defaults to dashboard.html)
├── dashboard.html
├── welcome.html
├── login.html
├── register.html
├── forgot-password.html
├── activity-log.html
├── goals.html
├── goal-progress.html
├── trends.html
├── history.html
├── profile.html
├── notifications.html
├── integrations.html
├── health-sync.html
├── styles.css
└── README.md
```

## 💡 Key Features

### Integrations
- **Apple Watch** - Connected
- **Fitbit** - Connected
- **Garmin Connect** - Available
- **Samsung Galaxy Watch** - Available
- **Whoop Strap** - Available
- **Polar Devices** - Available
- **Suunto Watch** - Available

### Health Apps
- **Apple Health** - Connected
- **Google Fit** - Available
- **Samsung Health** - Available
- **Strava** - Connected
- **MyFitnessPal** - Available

### Activity Types
- 🏃 Running
- 🚴 Cycling
- 💪 Strength Training
- 🏊 Swimming
- 🚶 Walking
- 🧘 Yoga

## 🎯 Goals Tracking
- Daily step goals
- Weekly workout targets
- Calorie burn goals
- Weight loss tracking
- Progress visualization
- Achievement badges

## 📈 Statistics
- Daily activity summary
- Weekly trends
- Monthly progress
- Activity distribution
- Calorie tracking
- Distance covered

## 🔔 Notifications
- Activity reminders
- Goal achievements
- Weekly summaries
- Workout suggestions
- Daily motivation
- Friend activity (optional)

## 📝 Notes

- All icons are created using inline SVG for better performance
- No external dependencies or libraries required
- Fully responsive for mobile devices
- All navigation links are functional
- Forms include basic validation
- Charts are static but styled for visual appeal

## 🚀 Browser Compatibility

Works in all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## 📄 License

This is a mockup/prototype for demonstration purposes.

---

**Created with ❤️ for FitTrack - Your Personal Fitness Companion**
