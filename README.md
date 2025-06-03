# 🛠️ XML to Java, SQL, and MongoDB Parser

A Python-based tool to convert XML database schema definitions into:
- ✅ Java Class Files
- ✅ SQL Table Creation Scripts
- ✅ MongoDB Documents

This is especially useful for working with systems that export database definitions in custom XML formats—such as Sterling OMS, Oracle-based systems, or internal enterprise tools.

---

## 🚀 Features

- 🔁 **Recursive XML Parsing** for deeply nested structures
- 🔧 **Auto-generates Java POJOs** with fields and getters/setters
- 🏗️ **SQL DDL Generation** for easy database setup
- 🧩 **MongoDB Schema Insertion** including attributes, indices, and example data
- 📂 **Output to organized files and folders**
- ✅ Includes upsert logic to prevent MongoDB duplicates

---

## To Run

python xml_to_mongo.py sample.xml --mongo
