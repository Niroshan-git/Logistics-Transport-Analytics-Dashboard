# Logistics & Transport Analytics Dashboard

![Home Page](https://github.com/user-attachments/assets/3f843175-7ea6-42bc-bf5a-46bce7e8c73c)


## 📊 Project Overview

This interactive Power BI dashboard was developed for the ZoomCharts Challenge, focusing on logistics and transportation analytics. The dashboard provides comprehensive insights into customer booking patterns, delivery performance, and supply chain efficiency. With intuitive navigation and advanced filtering capabilities, it enables stakeholders to make data-driven decisions to optimize logistics operations.

## 🚚 Dashboard Features

### Navigation System
- **Three main sections**: Home, Overview, and Details
- **Left sidebar navigation**: Quick access to Customer, Driver, Supplier, and Details views
- **Interactive elements**: Tooltips, info buttons, and filter controls throughout the interface

### Overview Page
![Overview](https://github.com/user-attachments/assets/826d8062-c1d4-4ac8-9d04-8cf6990e46b5)


The Overview page serves as the command center, displaying:

- **Key Performance Metrics**:
  - On-Time Delivery Rate: 39%
  - Total Bookings: 3,582
  - Delayed Deliveries: 2,201
  - Materials Shipped: 712

- **Resource Utilization**:
  - Total Customers: 34
  - Active Drivers: 1,429
  - Suppliers: 193

- **Booking Trends**: 
  - Visual representation of booking patterns from 2019-2020
  - Peak booking period identified in August 2020 (1,429 bookings)
  - Monthly booking distribution chart

- **Supplier Performance**:
  - Leading supplier: Ekta Transport Company (7.07% of total deliveries)

### Customer Insights Page


Detailed customer analytics including:

- **Booking Details**:
  - Top customer: Larsen & Toubro Limited (977 bookings)
  - Customer engagement frequency chart
  - Booking trends visualization from April 2019 to October 2020

- **Delivery Performance**:
  - On-Time Delivery percentage: 39%
  - Delivered shipments: 1,381 
  - Geographical distribution of shipments with interactive map
  - Most frequently ordered materials (Auto Parts leading)

- **Delay Analysis**:
  - Delayed deliveries count: 2,201
  - Customer destination breakdown
  - Delay hotspots identification

- **Customer Satisfaction**:
  - Star rating system for customer feedback
  - Most Valuable Customer identification

### Details Page
![Details](https://github.com/user-attachments/assets/1dab4295-09bf-4607-b545-1e0582d073a0)


Granular view of logistics operations:

- **Comprehensive Booking Log**:
  - Booking ID tracking
  - Delivery status indicators (On Time, Slightly Late, Extremely Late)
  - Distance metrics (KM)
  - Materials shipped details
  - Supplier attribution

- **Advanced Filtering Options**:
  - Search by Booking ID
  - Search by Customer Name
  - Search by Supplier Name
  - Delivery Status filter
  - Year and Month selectors

- **Route Visualization**:
  - Interactive map showing specific routes (e.g., Madurai → Ludhiana)
  - Distance markers and logistics hubs
  - Month-wise delivery status chart

    ![Info-Overvie Page](https://github.com/user-attachments/assets/7373b5f3-95e8-4f6a-94e9-7052edc8c670)


## 🛠️ Technical Implementation

### Data Model
- **Entities**: Customers, Drivers, Suppliers, Bookings, Materials, Routes
- **Relationships**: Complex many-to-many relationships between logistics components
- **Time Intelligence**: Month and year analysis with trend visualization

### Advanced Power BI Features Used
- **Custom Navigation System**: Tab-based interface with contextual filtering
- **Interactive Maps**: OpenStreetMap integration for geographic insights
- **Dynamic Tooltips**: Hover functionality for additional context
- **Cross-Filtering**: Synchronized filtering across all dashboard elements
- **Visual Hierarchy**: Logical organization of metrics based on importance
- **Custom Icons and Indicators**: Visual representations of delivery status

### Dashboard Design Elements
- **Color Scheme**: Professional blue palette with accent colors for status indicators
- **Info Buttons**: Contextual help and guidance throughout the interface
- **Search Filters**: Multiple search options for different data dimensions
- **Visual Consistency**: Uniform design language across all pages
- **Mobile-Responsive Layout**: Adaptable for different screen sizes

## 📈 Key Insights

Analysis of the data reveals several important findings:

1. **On-Time Delivery Challenge**: Only 39% of deliveries are made on time, indicating significant room for improvement in delivery performance
2. **Customer Concentration**: Larsen & Toubro Limited represents the highest booking volume (977), suggesting a potential risk if this customer relationship were to change
3. **Product Demand Patterns**: Auto Parts are the most frequently shipped items, indicating potential for inventory optimization
4. **Seasonal Trends**: Booking volume peaked in mid-2020 after steady growth throughout 2019
5. **Supplier Performance**: Several carriers like Sunita Carriers Private Limited show a high rate of "Extremely Late" deliveries
6. **Geographic Insights**: Shipping volume concentration in specific regions suggests opportunities for distribution center optimization

## 🚀 How To Use This Dashboard

1. **Navigation**: Use the top menu to switch between Home, Overview, and Details pages
2. **Filtering**: Apply filters using the search boxes and dropdown menus to focus on specific time periods, customers, or suppliers
3. **Tooltips**: Hover over charts and data points to see additional information
4. **Map Interaction**: Zoom and pan on the maps to explore geographic distribution
5. **Drill-Down**: Click on specific elements to see more detailed information
6. **Clear Filters**: Use the clear filters button to reset your view

## 💻 Technical Requirements

- **Power BI Desktop**: Version 2.92 or higher
- **ZoomCharts Visual**: Required for enhanced interactive visuals
- **Data Refresh**: Recommended daily for operational dashboards

## 🔮 Future Enhancements

- Integration of predictive analytics for delivery time estimation
- Driver performance metrics and optimization
- Cost analysis by route and material type
- Weather impact analysis on delivery performance
- Customer satisfaction correlation with delivery timeliness

## 📝 ZoomCharts Challenge Context

This project was developed as an entry for the ZoomCharts Challenge, which tasked participants with creating an insightful and visually engaging dashboard to analyze logistics and transportation data. The challenge focused on demonstrating both analytical capabilities and interactive design excellence while working with complex supply chain data.

## 🔗 Connect With Me

- [LinkedIn](https://linkedin.com/in/yourusername)
- [Portfolio](https://yourportfolio.com)
- [GitHub](https://github.com/yourusername)

---

## 📋 How to Use This Repository

1. Clone this repository
2. Download the PBIX file from the main directory
3. Open with Power BI Desktop
4. Ensure you have the ZoomCharts custom visual installed
5. Explore the interactive dashboard

---

## 🙏 Acknowledgements

- [ZoomCharts](https://zoomcharts.com/) for hosting the challenge
- Data sources: Logistics and transportation dataset provided for the challenge
- OpenStreetMap contributors for map visualization components

---

*This project is for educational and portfolio purposes only.*
