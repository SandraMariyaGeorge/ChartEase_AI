
# 📊 ChartEase - One Click AI Chart Generator

**ChartEase** is an AI-powered chart generation platform that transforms your raw Excel data into beautiful, insightful, and embeddable charts — automatically or manually. Just upload your data and get meaningful charts in seconds, powered by AI.

---

## 🚀 Features

- ⚡ **One-Click Chart Generation**  
  Upload Excel files and get smart, useful charts in a few clicks.

- ✍️ **Manual Chart Creation**  
  Build your own charts by selecting data columns and chart types manually.

- 🧠 **AI-Powered Suggestions**  
  Uses OpenAI’s API to intelligently suggest the best chart types — based **only on column names** and structure, not your actual data.

- 🔒 **Privacy-First Architecture**  
  Your data stays on your device/server — **only metadata** (like column names) are shared with OpenAI. No sensitive or user content leaves your system.

- 🌐 **Embeddable Charts**  
  Easily embed generated charts into your websites or apps with one line of code.

- 💾 **MongoDB Integration**  
  All user charts and related metadata are stored securely in a MongoDB database.

- 💼 **Modern Tech Stack**  
  Built with **FastAPI**, **React + Vite**, **TailwindCSS**, **MongoDB**, and **Recharts**.

---

## 🖼️ Screenshots


![Landing](https://github.com/vishnuhari17/ChartEase_AI/blob/main/frontend/public/ss1.png?raw=true)
![Creating chart](https://github.com/vishnuhari17/ChartEase_AI/blob/main/frontend/public/ss3.png?raw=true)
![Dashboard](https://github.com/vishnuhari17/ChartEase_AI/blob/main/frontend/public/ss4.png?raw=true)
![Generated charts](https://github.com/vishnuhari17/ChartEase_AI/blob/main/frontend/public/ss2.png?raw=true)

---

## 🧠 How It Works

1. **Upload Excel Sheet (.xlsx)**  
   User uploads their dataset through a drag-and-drop interface.

2. **Smart Chart Suggestions (Optional)**  
   The backend extracts column names and queries the OpenAI API for chart recommendations.

3. **Manual Chart Building (Optional)**  
   User can manually configure custom charts if desired.

4. **Chart Generation**  
   Charts are created using Recharts and shown in a clean, responsive dashboard.

5. **Embed Anywhere**  
   Users can embed charts in their websites using generated code snippets.

---

## 🛠️ Tech Stack

### Frontend
- **React + Vite**
- **TypeScript**
- **TailwindCSS**
- **Recharts**
- **Radix UI Components**

### Backend
- **FastAPI**
- **Python + Pandas**
- **MongoDB (via `motor` or `pymongo`)**
- **OpenAI API (only column names are sent)**

---

## 🗂️ Project Structure

```plaintext
ChartEase_AI/
├── backend/
│   ├── controller/
│   ├── models/
│   ├── utils/
│   ├── main.py
│   └── requirements.txt
├── frontend/
│   ├── public/
│   ├── src/
│   ├── App.tsx
│   ├── main.tsx
│   └── ...
├── screenshots/   # <-- Add your screenshots here
└── README.md
````

---

## 📦 Installation & Setup

### Backend

```bash
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
fastapi run main.py
```

> Make sure you have MongoDB running locally or in the cloud.

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🧪 Environment Variables

### Backend `.env`

```env
OPENAI_API_KEY=your_openai_api_key
MONGO_URI=mongodb://localhost:27017/chartease
```

### Frontend `.env.local`

```env
VITE_API_BASE_URL=http://localhost:8000
```

---

## 📈 Chart Types Supported

* Bar Chart
* Line Chart
* Pie Chart
* Area Chart
* Custom (based on column types)

---

## 💡 Use Cases

* Quickly visualize reports without manual effort
* Embed charts in internal dashboards
* Automate reporting in business workflows
* Create data presentations for meetings

---

## 🤝 Contributors

To all the contributors and supporters of this project, we want to express our sincerest thanks. Your time, effort, and expertise have been invaluable in making this project a success. Whether you contributed code, documentation, testing, or simply offered feedback and suggestions, your contributions are deeply appreciated.

<a href="https://github.com/vishnuhari17/ChartEase_AI/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=vishnuhari17/ChartEase_AI" />
</a>

---

## 📄 License

This project is licensed under the **MIT License**.
See the `LICENSE` file for details.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss your idea.

---

## 🌟 Star this repo if you like the project!

> Making chart generation a piece of cake 🍰

