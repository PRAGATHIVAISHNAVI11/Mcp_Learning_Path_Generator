

🧠 Learning Path Generator with Model Context Protocol (MCP)

A **Streamlit-based AI web app** that builds **personalized learning paths** using Model Context Protocol (MCP). Integrates with **YouTube**, **Google Drive**, and **Notion** to provide a unified and interactive learning experience.

> 🚀 *“From goal to guidance — turn your ambition into action in seconds.”*


🔧 Features

* 🎯 **Goal-Based Learning**
  Generate custom learning plans based on your input goal and time frame.

* 🎥 **YouTube Integration**
  Auto-curated video content to match your path.

* 📁 **Google Drive or Notion Integration**
  Choose where your notes, documents, and tracking data are stored.

* 📝 **Smart Note-Taking**
  Automatically structured content suggestions for Notion pages.

* 📊 **Progress Tracking**
  Real-time progress feedback for your learning milestones.

* 🎨 **Clean Streamlit UI**
  Minimal, responsive, and easy to navigate.



## ⚙️ Prerequisites

* Python **3.10+**
* A **Google AI Studio API Key**
* **Pipedream URLs** for:

  * YouTube integration (required)
  * Google Drive *or* Notion (choose one)



## 🚀 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/learning-path-mcp.git
   cd learning-path-mcp
   ```

2. **Create and activate a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install the dependencies**

   ```bash
   pip install -r requirements.txt
   ```



## 🔧 Configuration

Before launching the app, prepare the following:

* ✅ A **Google AI Studio API Key**
* ✅ Pipedream Webhook URLs for:

  * YouTube (required)
  * Google Drive *or* Notion

You'll input these values in the Streamlit sidebar when using the app.

---

## 🧪 Running the Application

Start the Streamlit app with:

```bash
streamlit run app.py
```

Open your browser and visit:
👉 [http://localhost:8501](http://localhost:8501)


## 🧠 How to Use

1. Enter your **Google AI Studio API Key** and **Pipedream URLs** in the sidebar.
2. Choose between **Google Drive** or **Notion** as your secondary tool.
3. Enter a learning goal, such as:

   ```
   I want to learn Python basics in 3 days
   ```
4. Click **"Generate Learning Path"**
   The AI will create a personalized study plan with integrated resources.


## 📁 Project Structure

```plaintext
📦 learning-path-mcp
├── app.py             # Streamlit UI and main logic
├── utils.py           # Helper functions and integrations
├── prompt.py          # MCP prompt templates
├── requirements.txt   # Python dependencies
```

