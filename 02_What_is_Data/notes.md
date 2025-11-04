# Project 2 – What is Data?

## 📘 Key Points
- **Data** is a collection of facts — numbers, words, measurements, observations, or even images — that can be processed to gain insights.  
- In Data Science, understanding what type of data you’re working with is the first and most important step.  
- Data can be **structured**, **semi-structured**, or **unstructured**.  
- The quality, consistency, and format of data affect every later step of analysis.  
- Common data sources include:
  - Databases and spreadsheets  
  - APIs and web scraping  
  - Sensors / IoT devices  
  - User-generated content like text, images, and videos  

---

## 🧱 Structured Data
Structured data is highly organized — arranged in rows and columns (like in Excel or SQL tables).

**Example:**

| Name | Age | City |
|:------|:-----:|:------|
| Alice | 25 | New York |
| Bob | 30 | London |
| Charlie | 28 | Tokyo |

✅ Easy to store, query and analyze using pandas, SQL, or Excel.  
✅ Ideal for statistical and quantitative analysis.

---

## 🌀 Unstructured Data
Unstructured data has no predefined format or schema.

**Examples:**
- Social media posts, emails, documents, images, videos, and audio.  
- Requires techniques like Natural Language Processing (NLP) or Computer Vision (CV) to extract meaning.  

🔹 Harder to store and process but contains rich contextual information.

---

## 🌿 Semi-Structured Data
Semi-structured data sits between structured and unstructured formats. It has organizational elements like tags or keys but does not follow a strict table schema.

**Example (JSON):**
```json
{
  "name": "Alice",
  "age": 25,
  "skills": ["Python", "Data Analysis"]
}
