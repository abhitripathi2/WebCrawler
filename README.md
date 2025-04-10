#  Java Web Crawler & Indexer

This is a simple web crawler and indexer built using **Java**, **JSoup**, and **MySQL**. It crawls web pages starting from a given URL, extracts important data (title, URL, text), and stores it in a database.

##  Features

- Recursively crawls web pages up to a configurable depth.
- Extracts:
  - Page title
  - Full page text
  - Hyperlinks (`<a href="">`)
- Avoids duplicate URLs.
- Saves data to a MySQL database.
- Uses JSoup for HTML parsing.

---

##  Technologies Used

- Java
- JSoup (HTML Parser)
- MySQL
- JDBC

---

##  Project Structure
ProjectSearchEngine/ │ ├── src/ │ └── main/ │ └── java/ │ └── org/ │ └── example/ │ ├── Crawler.java # Main crawler logic │ ├── Indexer.java # Extracts and stores data │ └── DatabaseConnection.java # Manages DB connection │ ├── lib/ # Place jsoup jar here if not using Maven ├── README.md └── ...


