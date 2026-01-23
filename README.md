# Notbook-Playlink-PYPI-Package

**Notebook-Playlink** is a lightweight and powerful Python package designed to seamlessly render and display **YouTube videos** as well as **any browser-accessible web links** directly inside **Jupyter Notebook** and **Google Colab** environments.

With Notebook-Playlink, users can interactively view external content  **inline** , without leaving the notebook interface—making it ideal for  **education, research, tutorials, demonstrations, and data science workflows** .

---

## ✨ Key Features

* ▶️ Render **YouTube videos** directly inside notebooks
* 🌐 Display **any web page or browser-accessible link** inline
* 📓 Fully compatible with  **Jupyter Notebook** ,  **JupyterLab** , and **Google Colab**
* ⚡ Simple and minimal API
* 🧩 No external browser or tab switching required

---

## 📦 Installation

### Using pip (recommended)

<pre class="overflow-visible! px-0!" data-start="1135" data-end="1176"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(--spacing(9)+var(--header-height))] @w-xl/main:top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span>pip install notebook-playlink
</span></span></code></div></div></pre>

---

## 🛠️ Development Setup (Optional)

If you want to contribute or run the package locally:

### Create a Conda environment

<pre class="overflow-visible! px-0!" data-start="1307" data-end="1365"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(--spacing(9)+var(--header-height))] @w-xl/main:top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span>conda create -n NotebookPlaylink python=3.8 -y
</span></span></code></div></div></pre>

<pre class="overflow-visible! px-0!" data-start="1367" data-end="1410"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(--spacing(9)+var(--header-height))] @w-xl/main:top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span>conda activate NotebookPlaylink
</span></span></code></div></div></pre>

<pre class="overflow-visible! px-0!" data-start="1412" data-end="1459"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(--spacing(9)+var(--header-height))] @w-xl/main:top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span>pip install -r requirements_dev.txt
</span></span></code></div></div></pre>

---

## 🚀 Quick Start

### Render a YouTube video inline

<pre class="overflow-visible! px-0!" data-start="1520" data-end="1640"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(--spacing(9)+var(--header-height))] @w-xl/main:top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-python"><span><span>from</span><span> notebook_playlink </span><span>import</span><span> inline_playlink

inline_playlink(</span><span>"https://www.youtube.com/watch?v=VIDEO_ID"</span><span>)
</span></span></code></div></div></pre>

---

### Render any web page inline

<pre class="overflow-visible! px-0!" data-start="1679" data-end="1731"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(--spacing(9)+var(--header-height))] @w-xl/main:top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-python"><span><span>inline_playlink(</span><span>"https://example.com"</span><span>)
</span></span></code></div></div></pre>

The content will be displayed  **directly inside the notebook cell output** .

---

## 🧠 Use Cases

* 📚 Teaching & learning notebooks
* 🧪 Research demonstrations
* 🎓 Online courses and workshops
* 📊 Data science reports
* 📝 Interactive documentation

---

## 🌍 Supported Environments

* Google Colab
* Jupyter Notebook
* JupyterLab
* Any IPython-based notebook interface

---

## 👤 Author

**Bijoy Dewanjee**

* PyPI: [Bijoy07]()
* GitHub: [https://github.com/BijoyDewanjee](https://github.com/BijoyDewanjee)

---

## 📄 License

This project is licensed under the  **MIT License** .

Feel free to use, modify, and distribute it in your projects.

---

## 🤝 Contributing

Contributions are welcome!

If you find a bug or want to add a feature, feel free to open an issue or submit a pull request.

---

## ⭐ Acknowledgement

If Anyone find **Notebook-Playlink** useful, consider giving the repository a ⭐ on GitHub—it helps the project grow!
