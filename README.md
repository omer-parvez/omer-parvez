<!-- Header banner: switches with the GitHub light/dark theme, same colours as the portfolio page -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&section=header&height=230&color=0:6aa8f0,100:f5a25b&text=Omer%20Parvez&fontColor=0f1729&fontSize=68&fontAlignY=38&desc=Machine%20learning%20%C2%B7%20Python%20back%20ends%20%C2%B7%20Developer%20tooling&descSize=18&descAlignY=60">
  <img width="100%" alt="Omer Parvez: machine learning, Python back ends and developer tooling" src="https://capsule-render.vercel.app/api?type=waving&section=header&height=230&color=0:2a78d6,100:e9832b&text=Omer%20Parvez&fontColor=ffffff&fontSize=68&fontAlignY=38&desc=Machine%20learning%20%C2%B7%20Python%20back%20ends%20%C2%B7%20Developer%20tooling&descSize=18&descAlignY=60">
</picture>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=19&pause=1400&color=6AA8F0&center=true&vCenter=true&width=700&lines=I+build+tools+that+make+complex+systems+easy+to+see;From+GAN+experiments+to+live+maps+of+AI+agents">
  <img alt="I build tools that make complex systems easy to see, from GAN experiments to live maps of AI agents." src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=19&pause=1400&color=2A78D6&center=true&vCenter=true&width=700&lines=I+build+tools+that+make+complex+systems+easy+to+see;From+GAN+experiments+to+live+maps+of+AI+agents">
</picture>

[![Portfolio](https://img.shields.io/badge/Portfolio-omer--parvez.github.io-2a78d6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://omer-parvez.github.io/omer-parvez/)
[![Live demo](https://img.shields.io/badge/Agent%20Monitor-Live%20demo-e9832b?style=for-the-badge&logo=claude&logoColor=white)](https://omer-parvez.github.io/claude-agent-monitor/)
[![GitHub](https://img.shields.io/badge/GitHub-omer--parvez-15203a?style=for-the-badge&logo=github&logoColor=white)](https://github.com/omer-parvez)

</div>

> [!TIP]
> My [portfolio](https://omer-parvez.github.io/omer-parvez/) has a live map: move through it and click an orange node to open that project. Here is the same map:

```mermaid
graph LR
  me((Omer)):::me

  me --> monitor(["🛰️ Agent Monitor"]):::project
  me --> thesis(["🧬 Master's thesis"]):::project
  me --> blogs(["📝 Flask & Django blogs"]):::project
  me --> docs(["📚 Docs site"]):::project

  monitor --> js[JavaScript]:::skill
  monitor --> html[HTML5]:::skill
  monitor --> css[CSS3]:::skill
  monitor --> node[Node.js]:::skill

  thesis --> py[Python]:::skill
  thesis --> tf[TensorFlow]:::skill
  thesis --> keras[Keras]:::skill
  thesis --> np[NumPy]:::skill

  blogs --> django[Django]:::skill
  blogs --> flask[Flask]:::skill
  blogs -.-> py
  blogs -.-> html
  blogs -.-> css

  classDef me fill:#2a78d6,stroke:#15203a,color:#fff,stroke-width:2px
  classDef project fill:#e9832b,stroke:#15203a,color:#fff
  classDef skill fill:#edf0f5,stroke:#56617a,color:#15203a
```

---

## 🚀 Projects

Real screenshots and code from each repository. Click a screenshot to see it full size.

### 🛰️ [Agent Monitor for Claude Code](https://github.com/omer-parvez/claude-agent-monitor)

See what your Claude Code agents are doing: every session, prompt, subagent and swarm on a live map and timeline, with start and finish times and token counts.

Replay, search and export. Everything stays on your computer, with zero dependencies.

[**▶ Try the live demo**](https://omer-parvez.github.io/claude-agent-monitor/) · [Source](https://github.com/omer-parvez/claude-agent-monitor)

`JavaScript` `Node.js` `HTML/CSS` `Claude Code plugin`

<p align="center">
  <img src="https://raw.githubusercontent.com/omer-parvez/claude-agent-monitor/HEAD/docs/images/replay.gif" alt="A swarm of agents replaying: explorers start, work and hand over to measurers and fact-checkers" width="90%"><br>
  <sub><b>Replay:</b> a workflow swarm replaying, step by step.</sub>
</p>

<details>
<summary><b>📸 More screenshots:</b> map, timeline, prompt story, dark mode</summary>
<br>

<table>
  <tr>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/omer-parvez/claude-agent-monitor/HEAD/docs/images/swarm-map.png" alt="The map view: a prompt with explorer, measurer and fact-checker agents in lanes"><br>
      <sub><b>Map:</b> who started whom, and what each agent is doing now.</sub>
    </td>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/omer-parvez/claude-agent-monitor/HEAD/docs/images/timeline.png" alt="The timeline view: one bar per agent with start and finish times and tool-call ticks"><br>
      <sub><b>Timeline:</b> one bar per agent, a tick for every tool call.</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/omer-parvez/claude-agent-monitor/HEAD/docs/images/prompt-story.png" alt="The story of a prompt: what was asked and what each agent did"><br>
      <sub><b>Prompt story:</b> the story of one prompt, from question to answer.</sub>
    </td>
    <td width="50%" align="center">
      <img src="https://raw.githubusercontent.com/omer-parvez/claude-agent-monitor/HEAD/docs/images/dark-mode.png" alt="Agent Monitor in dark mode"><br>
      <sub><b>Dark mode:</b> the same views in dark mode.</sub>
    </td>
  </tr>
</table>

</details>

### 🧬 [Conditional data generation for prostate cancer diagnosis](https://github.com/omer-parvez/GAN)

My master's thesis: using generative adversarial networks (GANs) to generate extra training data, to improve diagnosis in prostate cancer.

Compare a collapsed training run, where every sample comes out the same, with a working DCGAN on Fashion-MNIST.

[Source](https://github.com/omer-parvez/GAN)

`Python` `TensorFlow` `Keras` `GANs` `Jupyter`

<table>
  <tr>
    <th width="50%">❌ Collapsed</th>
    <th width="50%">✅ Working</th>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/omer-parvez/GAN/HEAD/Figure%202021-03-07%20195836.png" alt="Collapsed run: a grid of identical grey samples"></td>
    <td><img src="https://raw.githubusercontent.com/omer-parvez/GAN/HEAD/Figure%202021-02-16%20182703.png" alt="Working run: a grid of generated clothing items such as shirts, shoes and bags"></td>
  </tr>
  <tr>
    <td colspan="2" align="center"><sub>Generated samples from two DCGAN training runs.</sub></td>
  </tr>
</table>

<details>
<summary><b>🖼️ Generated tissue</b></summary>
<br>
<p align="center">
  <img src="https://raw.githubusercontent.com/omer-parvez/GAN/HEAD/first.jpg" alt="Four generated greyscale tissue-like images" width="70%"><br>
  <sub>Samples from the generator, in greyscale.</sub>
</p>
</details>

<details>
<summary><b>🧠 Generator code</b> from <code>DCGAN.py</code></summary>

```python
def define_generator(latent_dim):
	model = Sequential()
	# foundation for 7x7 image
	n_nodes = 128 * 7 * 7
	model.add(Dense(n_nodes, input_dim=latent_dim))
	model.add(LeakyReLU(alpha=0.2))
	model.add(Reshape((7,7, 128)))
	# upsample to 14x14
	model.add(Conv2DTranspose(128, (4,4), strides=(2,2), padding='same'))
	model.add(LeakyReLU(alpha=0.2))
	# upsample to 28x28
	model.add(Conv2DTranspose(128, (4,4), strides=(2,2), padding='same'))
	model.add(LeakyReLU(alpha=0.2))
	# generate
	model.add(Conv2D(1, (7,7), activation='tanh', padding='same'))
	return model
```

The generator upsamples random noise into a 28×28 image.
</details>

### 📝 Blogs with Flask and Django

Two blogs built to learn Python web frameworks. The Flask version stores posts in SQLite and lets you create and edit them. The Django version uses the ORM and the built-in admin.

[flask-blog](https://github.com/omer-parvez/flask-blog) · [my-first-blog](https://github.com/omer-parvez/my-first-blog)

`Python` `Flask` `Django` `SQLite` `Jinja2`

<details>
<summary><b>🧪 Flask:</b> <code>app.py</code></summary>

```python
def get_post(post_id):
    conn = get_db_connection()
    post = conn.execute('SELECT * FROM posts WHERE id=?',
                        (post_id,)).fetchone()
    conn.close()
    if post is None:
        abort(404)
    return post

@app.route("/")
def index():
    conn = get_db_connection()
    posts = conn.execute('SELECT * FROM posts').fetchall()
    conn.close()
    return render_template("index.html", posts=posts)
```

Fetch one post, or show a 404 page if it doesn't exist.
</details>

<details>
<summary><b>🎸 Django:</b> <code>models.py</code></summary>

```python
class Post(models.Model):
    author = models.ForeignKey(settings.AUTH_USER_MODEL, on_delete=models.CASCADE)
    title = models.CharField(max_length=400)
    text = models.TextField()
    created_date = models.DateTimeField(default=timezone.now)
    published_date = models.DateTimeField(blank=True, null=True)

    def publish(self):
        self.published_date = timezone.now()
        self.save()

    def __str__(self):
        return self.title
```

A blog post that is saved as a draft until you publish it.
</details>

### 📚 [Documentation site](https://github.com/omer-parvez/docs)

A documentation site built with Mintlify and MDX.

---

## 🛠️ Skills

<!-- Same Devicon icons as the portfolio. Dark logos get a white version in dark mode. Hover an icon to see where I've used it. -->
<table>
  <tr>
    <th align="left">Languages</th>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" height="40" alt="Python" title="Python · used in Master's thesis, Flask & Django blogs"><br><sub>Python</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" height="40" alt="JavaScript" title="JavaScript · used in Agent Monitor"><br><sub>JavaScript</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="40" height="40" alt="C++" title="C++"><br><sub>C++</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" height="40" alt="HTML5" title="HTML5 · used in Agent Monitor, Flask & Django blogs"><br><sub>HTML5</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" height="40" alt="CSS3" title="CSS3 · used in Agent Monitor, Flask & Django blogs"><br><sub>CSS3</sub></td>
    <td align="center" width="76"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/gnubash/white"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" width="40" height="40" alt="Shell" title="Shell"></picture><br><sub>Shell</sub></td>
    <td align="center" width="76"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/latex/white"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/latex/latex-original.svg" width="40" height="40" alt="LaTeX" title="LaTeX"></picture><br><sub>LaTeX</sub></td>
  </tr>
  <tr>
    <th align="left">ML &amp; data</th>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="40" height="40" alt="PyTorch" title="PyTorch"><br><sub>PyTorch</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width="40" height="40" alt="TensorFlow" title="TensorFlow · used in Master's thesis"><br><sub>TensorFlow</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/keras/keras-original.svg" width="40" height="40" alt="Keras" title="Keras · used in Master's thesis"><br><sub>Keras</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" width="40" height="40" alt="scikit-learn" title="scikit-learn"><br><sub>scikit-learn</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="40" height="40" alt="NumPy" title="NumPy · used in Master's thesis"><br><sub>NumPy</sub></td>
    <td align="center" width="76"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/pandas/white"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="40" height="40" alt="Pandas" title="Pandas"></picture><br><sub>Pandas</sub></td>
    <td align="center" width="76"><img src="https://cdn.simpleicons.org/scipy" width="40" height="40" alt="SciPy" title="SciPy"><br><sub>SciPy</sub></td>
    <td align="center" width="76"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/plotly/white"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/plotly/plotly-original.svg" width="40" height="40" alt="Plotly" title="Plotly"></picture><br><sub>Plotly</sub></td>
  </tr>
  <tr>
    <th align="left">Web &amp; apps</th>
    <td align="center" width="76"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/django/white"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" width="40" height="40" alt="Django" title="Django · used in Flask & Django blogs"></picture><br><sub>Django</sub></td>
    <td align="center" width="76"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/flask/white"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" width="40" height="40" alt="Flask" title="Flask · used in Flask & Django blogs"></picture><br><sub>Flask</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40" height="40" alt="Node.js" title="Node.js · used in Agent Monitor"><br><sub>Node.js</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" height="40" alt="React" title="React"><br><sub>React</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/electron/electron-original.svg" width="40" height="40" alt="Electron" title="Electron"><br><sub>Electron</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/qt/qt-original.svg" width="40" height="40" alt="Qt" title="Qt"><br><sub>Qt</sub></td>
  </tr>
  <tr>
    <th align="left">Databases</th>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" width="40" height="40" alt="MongoDB" title="MongoDB"><br><sub>MongoDB</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="40" height="40" alt="MySQL" title="MySQL"><br><sub>MySQL</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/microsoftsqlserver/microsoftsqlserver-original.svg" width="40" height="40" alt="SQL Server" title="SQL Server"><br><sub>SQL Server</sub></td>
  </tr>
  <tr>
    <th align="left">Cloud &amp; DevOps</th>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" width="40" height="40" alt="Azure" title="Azure"><br><sub>Azure</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" width="40" height="40" alt="Google Cloud" title="Google Cloud"><br><sub>Google Cloud</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="40" height="40" alt="Docker" title="Docker"><br><sub>Docker</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="40" height="40" alt="Linux" title="Linux"><br><sub>Linux</sub></td>
    <td align="center" width="76"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg" width="40" height="40" alt="Arduino" title="Arduino"><br><sub>Arduino</sub></td>
  </tr>
</table>

<details>
<summary><b>🔁 Where I've used each skill</b> (the back of the flip tiles on my portfolio)</summary>
<br>

| Skill | Used in |
| --- | --- |
| Python | [Master's thesis](#-conditional-data-generation-for-prostate-cancer-diagnosis), [Flask & Django blogs](#-blogs-with-flask-and-django) |
| JavaScript | [Agent Monitor](#️-agent-monitor-for-claude-code) |
| HTML5 | [Agent Monitor](#️-agent-monitor-for-claude-code), [Flask & Django blogs](#-blogs-with-flask-and-django) |
| CSS3 | [Agent Monitor](#️-agent-monitor-for-claude-code), [Flask & Django blogs](#-blogs-with-flask-and-django) |
| TensorFlow | [Master's thesis](#-conditional-data-generation-for-prostate-cancer-diagnosis) |
| Keras | [Master's thesis](#-conditional-data-generation-for-prostate-cancer-diagnosis) |
| NumPy | [Master's thesis](#-conditional-data-generation-for-prostate-cancer-diagnosis) |
| Django | [Flask & Django blogs](#-blogs-with-flask-and-django) |
| Flask | [Flask & Django blogs](#-blogs-with-flask-and-django) |
| Node.js | [Agent Monitor](#️-agent-monitor-for-claude-code) |

</details>

---

## 📊 GitHub stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=omer-parvez&count_private=true&show_icons=true&hide_border=true&bg_color=0f1729&title_color=6aa8f0&icon_color=f5a25b&text_color=e7ecf6">
  <img height="170" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=omer-parvez&count_private=true&show_icons=true&hide_border=true&bg_color=edf0f5&title_color=2a78d6&icon_color=e9832b&text_color=15203a">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=omer-parvez&layout=compact&hide_border=true&bg_color=0f1729&title_color=6aa8f0&text_color=e7ecf6">
  <img height="170" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=omer-parvez&layout=compact&hide_border=true&bg_color=edf0f5&title_color=2a78d6&text_color=15203a">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=omer-parvez&hide_border=true&background=0f1729&ring=f5a25b&fire=f5a25b&currStreakLabel=6aa8f0&sideLabels=e7ecf6&currStreakNum=e7ecf6&sideNums=e7ecf6&dates=9aa6bf&stroke=2a3756">
  <img alt="GitHub streak" src="https://streak-stats.demolab.com/?user=omer-parvez&hide_border=true&background=edf0f5&ring=e9832b&fire=e9832b&currStreakLabel=2a78d6&sideLabels=15203a&currStreakNum=15203a&sideNums=15203a&dates=56617a&stroke=d6dce7">
</picture>

</div>

---

<div align="center">
<sub>© Omer Parvez. Code on <a href="https://github.com/omer-parvez">github.com/omer-parvez</a></sub>
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&section=footer&height=120&color=0:6aa8f0,100:f5a25b">
  <img width="100%" alt="" src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=120&color=0:2a78d6,100:e9832b">
</picture>
