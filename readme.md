markdown
# 🗃️ MongoDB Database Structures

![Database Diagrams Overview](diagrams/all_diagrams.png)

## 📄 Description - Exercise Statement

This repository contains MongoDB database structures for three different scenarios:

1. **Optical Shop Management System**  
   Design a database for "Cul d'Ampolla" optical shop to manage customers, glasses, suppliers, and sales.

2. **Food Delivery System**  
   Model a database for an online food delivery service handling orders, products, stores, and employees.

3. **Simplified YouTube Clone**  
   Create a database structure for a video sharing platform with users, videos, channels, and playlists.

## 💻 Technologies Used

- **MongoDB** - NoSQL database
- **MongoDB Compass** - GUI for MongoDB
- **Draw.io** - Database diagramming tool
- **JSON** - Data interchange format

## 📋 Requirements

- MongoDB Community Server v6.0+
- Basic understanding of NoSQL concepts
- JSON file viewer/editor (optional)

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/FlavioKde/S203dataStructure-MongoDB.git
Import JSON files to MongoDB:

bash
mongoimport --db database_name --collection collection_name --file path/to/file.json --jsonArray
📂 Repository Structure
mongoDB-estructura/
├── optical_shop/          # Optical shop database files
│   ├── customers.json
│   ├── glasses.json
│   ├── suppliers.json
│   └── sales.json
├── food_delivery/         # Food delivery system files
│   ├── customers.json
│   ├── orders.json
│   ├── products.json
│   └── stores.json
├── youtube_clone/         # YouTube clone files
│   ├── users.json
│   ├── videos.json
│   ├── comments.json
│   └── playlists.json
└── diagrams/              # Database diagrams (PNG)
    ├── glasses_store.png    # Optical shop structure
    ├── glasses.png         # Glasses details schema
    ├── food_store.png      # Food delivery model
    └── youtube_reduced.png # YouTube clone schema
🏗️ Database Diagrams
👓 Optical Shop System
Glasses Store Diagram
Complete optical shop database structure

Glasses Details
Glasses specification schema

� Food Delivery System
Food Store Diagram
Food delivery service data model

▶️ YouTube Clone
YouTube Structure
Simplified YouTube database schema

🤝 Contributions
Contributions are welcome! Please follow these steps:

Fork the repository

Create a new branch (git checkout -b feature/your-feature)

Commit your changes (git commit -am 'Add some feature')

Push to the branch (git push origin feature/your-feature)

Open a Pull Request

📝 License
This project is open-source and available under the MIT License.

*Developed as part of the MongoDB learning objectives - Duration: 4 days*


Key changes made:
1. Replaced `.drawio` references with your actual PNG files
2. Added image display sections for each diagram with descriptive captions
3. Maintained single-file format as requested
4. Kept all original functionality and structure
5. Added proper image paths in the repository structure section

To use this:
1. Save as `README.md` in your project root
2. Create a `diagrams/` folder
3. Place your 4 PNG images in that folder
4. The images will automatically display when viewed on GitHub

The markdown includes proper relative paths for the images and maintains all the professional formatting from the previous version while incorporating your specific diagram files.