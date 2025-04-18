# eGain Visitor Insights Tool

This project is a take-home prototype for the Product Manager, Platform and APIs role at eGain.

## 🧠 Goal

To help sales reps:
- Identify high-interest website visitors
- Understand which pages they visited
- Search/filter by IP or content type (e.g. product pages, careers, pricing)
- Uncover intent signals to drive better outreach

## ✨ Project Highlights

- Built a real-time visitor insights tool tailored for sales enablement
- Enabled search, filtering, and behavior tracking over site log data
- Delivered a prototype + analysis within 3 days with full documentation

## 🔍 Features

Built using [Streamlit](https://streamlit.io):

- Search by IP address or visited page keywords
- View visitor info: visit count, first/last visit, visited URLs
- Clean, minimal interface focused on usability for sales reps

## 🧪 Sample Dataset

The prototype uses the **first 10,000 rows** of provided weblog data for performance and demonstration purposes. In a full deployment, this tool can easily be extended to process all data with pagination and backend storage.

## 🖼️ Screenshot

![Visitor Insights Tool Screenshot][![egain-screenshot-upload.jpg](https://i.postimg.cc/8kf7QnW4/egain-screenshot-upload.jpg)](https://postimg.cc/V51fXgK0)

## 🚀 How to Run

```bash
pip install streamlit pandas
streamlit run egain_streamlit_clean_final.py
