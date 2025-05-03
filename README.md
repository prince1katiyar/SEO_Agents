<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="description" content="An AI-powered YouTube SEO tool that automatically generates tags, descriptions, timestamps, titles, and thumbnails using LangChain, OpenAI, and more."/>
  <meta name="keywords" content="YouTube SEO, LangChain, Streamlit, OpenAI, Thumbnail Generator, Title Generator, Tags Generator, Python AI, YouTube Automation, GPT-4"/>
  <meta name="author" content="Your Name"/>
  <title>YouTube SEO Agent using LangChain + GPT-4</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; color: #333;">
  <h1>🎯 YouTube SEO Agent with LangChain + GPT-4</h1>
  
  <p><strong>Automate your YouTube SEO workflow</strong> using <code>LangChain</code>, <code>OpenAI</code>, and <code>Streamlit</code>. This tool extracts video content, analyzes it, and generates:</p>
  
  <ul>
    <li>🔥 35 Optimized Hashtags/Tags</li>
    <li>📝 400-500 Word SEO-Optimized Video Description</li>
    <li>⏱️ Timestamps with Labels (Minimum 5)</li>
    <li>🎯 5-7 Title Suggestions with Ranking</li>
    <li>🎨 3 High-CTR Thumbnail Concepts</li>
  </ul>

  <h2>🚀 Features</h2>
  <ul>
    <li>🎥 Extracts and summarizes video content</li>
    <li>🔍 Auto-generates all necessary SEO metadata</li>
    <li>🖼️ Thumbnail design recommendations with colors, text, and layout</li>
    <li>📌 Streamlit UI (optional)</li>
    <li>🌍 Multi-language support</li>
  </ul>

  <h2>🧰 Technologies Used</h2>
  <ul>
    <li><code>LangChain</code> >= 0.0.300</li>
    <li><code>OpenAI GPT-4</code> via <code>openai</code> >= 1.1.0</li>
    <li><code>Google Generative AI</code> >= 0.3.0</li>
    <li><code>Streamlit</code> >= 1.27.0</li>
    <li><code>Pytube</code>, <code>BeautifulSoup4</code>, <code>Requests</code>, <code>Pillow</code></li>
    <li><code>python-dotenv</code> for environment management</li>
  </ul>

  <h2>📦 Installation</h2>
  <pre>
git clone https://github.com/yourusername/youtube-seo-agent.git
cd youtube-seo-agent
pip install -r requirements.txt
  </pre>

  <h2>🔐 Environment Variables</h2>
  <p>Create a <code>.env</code> file in your root directory:</p>
  <pre>
OPENAI_API_KEY=your_openai_key
GOOGLE_API_KEY=your_generative_ai_key
  </pre>

  <h2>📈 How It Works</h2>
  <ol>
    <li>🎯 Input a YouTube video URL.</li>
    <li>📥 Pytube fetches metadata and title.</li>
    <li>🧠 LangChain + GPT-4 analyzes the content.</li>
    <li>📊 Generates tags, titles, descriptions, timestamps, and thumbnail ideas.</li>
    <li>🎨 Returns a complete SEO package ready to publish.</li>
  </ol>

  <h2>🧪 Run the SEO Engine</h2>
  <pre>
python main.py
  </pre>

  <h2>📺 Optional Streamlit Interface</h2>
  <pre>
streamlit run app.py
  </pre>

  <h2>📁 Example Output</h2>
  <ul>
    <li><strong>Tags:</strong> 35 trending YouTube tags</li>
    <li><strong>Description:</strong> Hook + Value + CTA + SEO Keywords</li>
    <li><strong>Timestamps:</strong> Evenly spaced labels for chapters</li>
    <li><strong>Titles:</strong> Ranked by SEO potential with justification</li>
    <li><strong>Thumbnails:</strong> Colors, overlays, layout, emotion</li>
  </ul>

  <h2>💡 Use Cases</h2>
  <ul>
    <li>YouTube creators and marketers</li>
    <li>Content teams looking for automation</li>
    <li>AI-powered thumbnail and title generation</li>
    <li>SEO optimization at scale</li>
  </ul>

  <h2>📜 License</h2>
  <p>MIT License</p>

  <h2>📬 Contact</h2>
  <p>Created with ❤️ by <strong>Prince katiyar</strong><br>
  🔗 <a href="https://github.com/prince1katiyar">GitHub</a> | 🌐 <a href="https://www.linkedin.com/in/katiyarprince/">LinkedIn</a></p>
</body>
</html>
