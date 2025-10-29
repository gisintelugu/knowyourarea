# 🗺️ Know Your Area - Local Information Portal

![Know Your Area](https://img.shields.io/badge/Know-Your%20Area-brightgreen)
![GitHub](https://img.shields.io/github/license/gisintelugu/knowyourarea)
![GitHub last commit](https://img.shields.io/github/last-commit/gisintelugu/knowyourarea)

A comprehensive web application that provides citizens with easy access to local ward information, public representatives, emergency services, and utility contacts for Hyderabad, Telangana.

## 🌟 Features

### 🔍 Smart Ward Search
- **Instant Search**: Type your ward number and get instant results
- **Auto-suggestions**: Smart dropdown with available ward numbers
- **Quick Access**: Enter key support for faster searching

### 👥 Public Representatives
- **MLA Details**: Complete information about your local MLA
- **Corporator Contacts**: Direct WhatsApp integration with corporator contact numbers
- **Address Information**: Official addresses of public representatives

### 🚨 Emergency Services
- **One-Touch Calling**: Direct dial for emergency numbers
- **Comprehensive List**: Police, Fire, Ambulance, Women & Child helplines
- **Quick Access**: Organized emergency contact grid

### 🏗️ Utility Services
- **Water Supply**: HMWSSB customer care and area officers
- **Electricity**: TSSPDCL complaint numbers and section offices
- **Animal Services**: GHMC street dog complaint contacts

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Icons**: Font Awesome 6.4.0
- **Data Source**: GitHub-hosted CSV (No CORS issues)
- **Design**: Responsive CSS Grid & Flexbox
- **Integration**: WhatsApp API for direct messaging

## 📊 Data Structure

The application uses a CSV file with the following key fields:
- `WardNo` - Ward identification number
- `NameoftheCorporator` - Corporator's full name
- `Contact Number1` & `Contact Number2` - Corporator contact numbers
- `NameoftheMLA` - MLA name and contact information
- Administrative details (Zone, Circle, District, etc.)

## 🚀 Quick Start

### Using the Application
1. Visit the deployed application
2. Enter your ward number in the search box
3. Click "Get Details" or press Enter
4. Browse through different tabs for comprehensive information

### For Developers
```bash
# Clone the repository
git clone https://github.com/gisintelugu/knowyourarea.git

# Open index.html in your browser
# No server setup required - works directly with GitHub raw CSV
```

## 📱 Responsive Design

The application is fully responsive and works seamlessly on:
- 📱 Mobile devices
- 💻 Tablets  
- 🖥️ Desktop computers
- 🖥️ Large screens

## 🔧 Key Features Explained

### Smart CSV Processing
- Handles quoted fields and commas within CSV values
- Dynamic field mapping for flexible data structure
- Real-time data loading from GitHub

### Contact Integration
- Automatic WhatsApp link generation
- International number formatting
- Multiple contact number support

### User Experience
- Loading states and error handling
- Smooth animations and transitions
- Tab-based information organization

## 📈 Project Impact

### For Citizens
- ✅ Easy access to local government information
- ✅ Direct communication with representatives
- ✅ Emergency services at fingertips
- ✅ No app installation required

### For Administrators
- ✅ Centralized data management via CSV
- ✅ Easy updates through GitHub
- ✅ No backend infrastructure needed
- ✅ Cost-effective deployment

## 🌐 Data Sources

- **GHMC**: Corporator and MLA information
- **TSSPDCL**: Electricity utility contacts  
- **HMWSSB**: Water supply information
- **Cyberabad Police**: Police station details

## 🤝 Contributing

We welcome contributions! Please feel free to:
- Report bugs and issues
- Suggest new features
- Improve documentation
- Add support for more cities

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🆘 Support

If you encounter any issues or have questions:
1. Check the [Issues](../../issues) page
2. Create a new issue with detailed description
3. Provide ward number and expected vs actual behavior

---

**Built with ❤️ for the people of Hyderabad**

*Making local governance information accessible to all citizens*
