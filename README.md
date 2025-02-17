# Asset Management System

## Description
A web-based asset management system with Excel database integration, designed for tracking and managing organizational assets efficiently. The system provides real-time synchronization with Excel databases, making it ideal for organizations that need to maintain their asset records in Excel format while having a modern web interface for management.

## Repository
- GitHub: [https://github.com/moa-rw/assetmanagement](https://github.com/moa-rw/assetmanagement)

## Key Features
- 📊 Excel Database Integration
  - Seamless synchronization with Excel files
  - Support for both .xlsx and .csv formats
  - Auto-save functionality
  - Real-time data updates

- 🏢 Asset Management
  - Asset type registration and management
  - Brand registration and tracking
  - Individual asset addition with quantity tracking
  - Bulk import via Excel/CSV
  - Asset removal with quantity management

- 📈 Data Visualization
  - Interactive asset distribution charts
  - Brand-wise filtering
  - Real-time chart updates
  - Asset quantity tracking

## Tech Stack
- HTML5
- CSS3
- JavaScript (ES6+)
- Chart.js
- SheetJS (XLSX)

## Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, or Edge)
- Local development environment or web server

### Installation

1. Clone the repository
```bash
git clone https://github.com/moa-rw/assetmanagement.git
```

2. Navigate to project directory
```bash
cd assetmanagement
```

3. Open in your preferred web server or use local server:
   - Using Python:
     ```bash
     python -m http.server 8000
     ```
   - Using Node.js:
     ```bash
     npx http-server
     ```

4. Access the application:
   - Local server: Visit `http://localhost:8000`
   - Direct: Open `index.html` in browser

### Database Setup

1. Initial Database
   - Create Excel file with columns:
     - Asset Type
     - Brand
     - Quantity
   - Save as `.xlsx` format

2. Load Database
   - Click "Load Database" in application
   - Select your Excel file
   - Confirm successful load

## Usage Guide

### Asset Type Management
- Add new asset types
- Types automatically available in dropdowns
- View all asset types in summary

### Brand Management
- Register new brands
- Track assets by brand
- Filter views by brand

### Asset Operations
- Add assets individually
- Remove assets with quantity tracking
- Bulk import via Excel
- Auto-sync with database

### Data Views
- Table view with sorting
- Chart visualization
- Brand-wise filtering
- Real-time updates

```

## Contributing
1. Fork the repository
2. Create feature branch
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit changes
   ```bash
   git commit -m 'Add YourFeature'
   ```
4. Push to branch
   ```bash
   git push origin feature/YourFeature
   ```
5. Open Pull Request

## Issues
Report issues via GitHub issues page. Include:
- Clear description
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if applicable

## Future Enhancements
- [ ] User authentication
- [ ] Multiple database support
- [ ] Export reports
- [ ] Asset history tracking
- [ ] Maintenance scheduling
- [ ] Mobile app integration


## Support
Create an issue on GitHub for:
- Bug reports
- Feature requests
- General questions

## Acknowledgments
- Chart.js for visualization
- SheetJS for Excel operations
- Contributors and testers

## Author
- MOA
- GitHub: [moa-rw](https://github.com/moa-rw)

---
Made with ❤️ for better asset management
