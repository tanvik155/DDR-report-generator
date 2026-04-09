**⚡ DDR Report Generator**

**Overview**

DDR Report Generator is an AI-powered system that transforms inspection reports and thermal imaging PDFs into professional Detailed Diagnostic Reports (DDR) with intelligently matched thermal images—all in seconds.

No more manually hunting through hundreds of pages—get structured, actionable insights automatically.

**Features**

Extract text AND images from PDF documents with page context

Use Groq Llama 3.3 70B for structured data extraction

**Intelligent image-to-observation matching using 5 strategies:**

Area name recognition

Keyword correlation

Thermal pattern detection

Page proximity analysis

Confidence scoring (0–100%)

Generates 7-section professional reports

**Export in multiple formats: HTML, JSON, PDF**

Handles missing data or conflicts safely (marked as Not Available or noted in limitations)

**Who Can Use This**

Building inspectors & engineers – faster, accurate reporting

Construction & property management firms – actionable insights instantly

Insurance companies – verify claims efficiently

Facility managers & architects – track issues & repairs seamlessly


**Tech Stack**

Backend: Flask (Python)
LLM: Groq Llama 3.3 70B
PDF Processing: PyMuPDF (fitz)
Frontend: HTML/CSS with Markdown rendering

**Installation**


# Install dependencies

pip install -r requirements.txt

# Run the application

python app.py

**Why It Matters**

Transform 200+ page inspection reports into clear, actionable DDRs in seconds. Spend less time manually matching thermal images and more time making decisions.
