# 📖 Quran_Dataset

A rich, structured, and annotated dataset of Quran pages, specially designed for computer vision, natural language processing (NLP), and Quranic research applications.  
This dataset includes various forms of the Quranic text and page formats with or without ayah markers, harakats, and backgrounds.

---

## 📂 Dataset Structure

Quran_Dataset/
│
├── Quran_pages_no_background/ # PNG images of Quran pages with backgrounds removed
├── Quran_pages_ayah_json/ # Ayah locations and metadata in JSON format
├── Quran_pages_ayah_marker/ # Pages with ayah markers overlaid
├── Quran_pages_ayah_marker_emlaey/ # Emlaey-style ayah markers
├── Quran_pages_ayahs_harakat/ # Pages with harakat (diacritical marks)
├── Quran_pages_data_json/ # Structured data in JSON format (e.g., coordinates)
├── Quran_pages_hafs_ayah_marker/ # Hafs-style ayah marker pages
├── Quran_pages_indexed_word/ # Pages with indexed words for mapping
├── Quran_pages_special_ayah_marker/ # Pages with special/alternate ayah markers
├── Quran_pages_txt_ayah_marker/ # Ayah markers in TXT format
├── Quran_pages_white_background/ # Pages with white background only
├── Quran_pages_word_per_line_count/ # Word-per-line metadata
├── finalized_quran_pages/ # Final cleaned version of pages
├── all_removed_ayah_markers.json # JSON log of removed ayah markers
├── Quran_Words_Per_Line_Per_Page.csv # Word-per-line stats for each page
├── Quran_pages_harakat.txt # Harakat data in text format
├── Quran_pages_line_word_counts.txt # Word count per line data
├── Quran_pages_lines_ayah_marker.txt # Line-wise ayah marker map
├── Quran_pages_no_harakat.txt # Pages without diacritics
├── Quran_pages_no_special_harakat.txt # Pages without special harakat


---

## 🔍 Features

- 🖼️ High-resolution Quranic pages
- 🧠 Annotated with ayah markers, harakats, and word indexing
- ⚙️ Multiple formats: PNG, JSON, TXT, and CSV
- 🎯 Suitable for:
  - Quran OCR training
  - NLP on Arabic text
  - Quran recitation alignment
  - Machine learning & AI-based research

---

## 📌 Use Cases

- ✅ **Quran Recitation Error Detection**
- ✅ **Visual Quran Browsers**
- ✅ **Arabic OCR Projects**
- ✅ **ML/DL for Text Localization**
- ✅ **Text-to-Speech (TTS) Training**
- ✅ **Educational Apps**

---

## 🚀 Getting Started

1. Clone the repo:

```bash
git clone https://github.com/AnasFahmy/Quran_Dataset.git


## 🙌 Acknowledgments

Built and curated by Anas Fahmy
Special thanks to the {} and {} open-source communities for inspiration and support.

---

### 📌 Tips for Best Effect:

- Add images or example pages by uploading them to the repo and embedding like this:
  
  ```markdown
  ![Example Quran Page](./Quran_pages_no_background/page001.png)
