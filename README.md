AI-Powered SEO Optimizer Agent

A clean, modern Streamlit application built with Python that leverages the Google Gemini API (google-genai SDK) to convert unoptimized text into SEO-optimized content complete with meta tags, keyword density analytics, and readability insights.

Features

Sidebar Configuration: Input your Gemini API key, target keywords, writing tone, and audience.

Gemini Integration: Uses gemini-2.5-flash for fast, accurate context-aware content rewriting.

Structured Outputs: Automatically parses Meta Titles, Meta Descriptions, structured Markdown content, and strategic SEO feedback.

Interactive Analytics: Calculates word count, primary keyword density, and renders interactive charts via Plotly.

Setup Instructions

Clone or Download this repository.

Install Dependencies:

pip install -r requirements.txt


Run the Streamlit App:

streamlit run app.py


Usage:

Enter your Google Gemini API key in the sidebar.

Enter your primary and secondary keywords.

Choose your tone and target audience.

Paste your draft into the input box and click Run SEO Optimization.
