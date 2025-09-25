# Cross-Cutting Data Interoperability & Harmonization Innovation Summit 2025 — Group 18


<p style="text-align: right;"><a href="https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/edit/main/docs/index.md" title="Edit this page">✏️</a></p>


---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ESIIL Group 18: From Data Chaos to Community Standards</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            min-height: 100vh;
        }
        
        .hero {
            background: linear-gradient(135deg, #2c5282 0%, #2d3748 100%);
            color: white;
            padding: 60px 40px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><circle cx="50" cy="50" r="2" fill="rgba(255,255,255,0.1)"/><circle cx="20" cy="20" r="1.5" fill="rgba(255,255,255,0.1)"/><circle cx="80" cy="30" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="30" cy="80" r="1.5" fill="rgba(255,255,255,0.1)"/></svg>') repeat;
            animation: float 20s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }
        
        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            font-weight: 700;
            position: relative;
            z-index: 1;
        }
        
        .hero-subtitle {
            font-size: 1.4rem;
            margin-bottom: 30px;
            opacity: 0.9;
            position: relative;
            z-index: 1;
        }
        
        .hero-tagline {
            font-size: 1.1rem;
            font-style: italic;
            position: relative;
            z-index: 1;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .content {
            padding: 0 40px;
        }
        
        .section {
            margin: 60px 0;
        }
        
        .section h2 {
            font-size: 2.5rem;
            margin-bottom: 30px;
            color: #2d3748;
            text-align: center;
            position: relative;
        }
        
        .section h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 60px;
            height: 3px;
            background: linear-gradient(90deg, #667eea, #764ba2);
            border-radius: 2px;
        }
        
        .journey-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .journey-card {
            background: #f8fafc;
            padding: 30px;
            border-radius: 15px;
            border-left: 5px solid #667eea;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .journey-card::before {
            content: '';
            position: absolute;
            top: 0;
            right: 0;
            width: 100px;
            height: 100px;
            background: linear-gradient(45deg, rgba(102, 126, 234, 0.1), transparent);
            border-radius: 0 15px 0 100%;
        }
        
        .journey-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
        }
        
        .journey-card h3 {
            color: #2d3748;
            margin-bottom: 15px;
            font-size: 1.3rem;
        }
        
        .process-visual {
            background: linear-gradient(135deg, #f1f5f9 0%, #e2e8f0 100%);
            padding: 40px;
            border-radius: 20px;
            margin: 40px 0;
            text-align: center;
        }
        
        .process-steps {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;
            margin: 30px 0;
        }
        
        .process-step {
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            flex: 1;
            min-width: 200px;
            position: relative;
        }
        
        .process-step::after {
            content: '→';
            position: absolute;
            right: -25px;
            top: 50%;
            transform: translateY(-50%);
            font-size: 1.5rem;
            color: #667eea;
            font-weight: bold;
        }
        
        .process-step:last-child::after {
            display: none;
        }
        
        .process-step h4 {
            color: #2d3748;
            margin-bottom: 10px;
            font-size: 1.1rem;
        }
        
        .highlight-quote {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 40px;
            border-radius: 20px;
            margin: 50px 0;
            text-align: center;
            font-size: 1.4rem;
            font-style: italic;
            position: relative;
        }
        
        .highlight-quote::before, .highlight-quote::after {
            content: '"';
            font-size: 4rem;
            font-weight: bold;
            opacity: 0.3;
            position: absolute;
        }
        
        .highlight-quote::before {
            top: 10px;
            left: 20px;
        }
        
        .highlight-quote::after {
            bottom: 10px;
            right: 20px;
        }
        
        .solutions-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }
        
        .solution-card {
            background: white;
            padding: 25px;
            border-radius: 12px;
            border: 1px solid #e2e8f0;
            transition: all 0.3s ease;
            position: relative;
        }
        
        .solution-card:hover {
            border-color: #667eea;
            box-shadow: 0 8px 25px rgba(102, 126, 234, 0.15);
        }
        
        .solution-card h4 {
            color: #2d3748;
            margin-bottom: 15px;
            font-size: 1.2rem;
        }
        
        .solution-card .status {
            display: inline-block;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: bold;
            margin-top: 15px;
        }
        
        .status.active {
            background: #c6f6d5;
            color: #22543d;
        }
        
        .status.planned {
            background: #fed7d7;
            color: #742a2a;
        }
        
        .team-values {
            background: #f8fafc;
            padding: 40px;
            border-radius: 20px;
            margin: 40px 0;
        }
        
        .values-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .value-item {
            text-align: center;
            padding: 20px;
            background: white;
            border-radius: 10px;
        }
        
        .value-icon {
            font-size: 2rem;
            margin-bottom: 10px;
            display: block;
        }
        
        .cta-section {
            background: linear-gradient(135deg, #2d3748 0%, #2c5282 100%);
            color: white;
            padding: 60px 40px;
            text-align: center;
            margin: 60px -40px 0 -40px;
        }
        
        .cta-section h2 {
            color: white;
            margin-bottom: 20px;
        }
        
        .cta-section h2::after {
            background: white;
        }
        
        .cta-button {
            display: inline-block;
            background: #667eea;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            margin: 10px;
            transition: all 0.3s ease;
        }
        
        .cta-button:hover {
            background: #5a67d8;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .hero-subtitle {
                font-size: 1.2rem;
            }
            
            .content {
                padding: 0 20px;
            }
            
            .process-steps {
                flex-direction: column;
            }
            
            .process-step::after {
                content: '↓';
                right: 50%;
                bottom: -25px;
                top: auto;
                transform: translateX(50%);
            }
            
            .cta-section {
                margin: 60px -20px 0 -20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="hero">
            <h1>From Data Chaos to Community Standards</h1>
            <p class="hero-subtitle">ESIIL Group 18's Journey Through the Metadata Maze</p>
            <p class="hero-tagline">"Data usefulness goes down with time while costs go up — where's the sweet spot? We're finding out."</p>
        </header>
        
        <main class="content">
            <section class="section">
                <h2>Our Journey: Navigating the Groan Zone</h2>
                <p style="text-align: center; font-size: 1.1rem; margin-bottom: 30px; color: #4a5568;">
                    Two intensive days, 9 environmental scientists, one big challenge: making data work better for everyone.
                </p>
                
                <div class="journey-container">
                    <div class="journey-card">
                        <h3>🎯 Day 1: The Big Picture Problem</h3>
                        <p>We started with grand ambitions—tackle all the data interoperability challenges in environmental science! But reality hit: we couldn't write a meaningful paper without understanding what researchers actually do with their data.</p>
                    </div>
                    
                    <div class="journey-card">
                        <h3>🤔 The Realization</h3>
                        <p>Hurricane path data scattered across federal sources. Agricultural sampling methods buried in cryptic metadata. eDNA methods changing faster than we could keep up. The problem wasn't abstract—it was personal.</p>
                    </div>
                    
                    <div class="journey-card">
                        <h3>💡 Day 2: The Strategic Pivot</h3>
                        <p>Instead of assuming solutions, we decided to ask the right questions first. What do researchers actually need? How do they currently handle metadata? What are the real barriers?</p>
                    </div>
                    
                    <div class="journey-card">
                        <h3>🛠️ Evidence-Based Solutions</h3>
                        <p>Now we're building tools informed by real researcher needs: live polling at this summit, comprehensive post-event surveys, and practical guidelines for OASIS that actually work in the field. This evidence gathering is directly informing our perspectives paper for Environmental Data Science.</p>
                    </div>
                </div>
            </section>
            
            <div class="process-visual">
                <h3 style="color: #2d3748; margin-bottom: 20px; font-size: 1.8rem;">From Divergent Thinking to Convergent Action</h3>
                <p style="margin-bottom: 30px; color: #4a5568;">We embraced the "Groan Zone" — that uncomfortable but creative space between brainstorming and decision-making.</p>
                
                <div class="process-steps">
                    <div class="process-step">
                        <h4>Divergent Ideas</h4>
                        <p>Best practices, training materials, repository audits, improving current repositories, creating ESIIL-Zenodo communities, developing data cube standards, AI tools for metadata generation — we explored everything</p>
                    </div>
                    <div class="process-step">
                        <h4>Groan Zone</h4>
                        <p>Frustration led to breakthrough: we need data before prescribing solutions, we need to study the weaknesses of current initiatives, we can actually work on a solution to OASIS</p>
                    </div>
                    <div class="process-step">
                        <h4>Convergent Action</h4>
                        <p>Tools to gather information, write a perspective paper, create resources for researchers</p>
                    </div>
                </div>
            </div>
            
            <div class="highlight-quote">
                "Data on its own is not inherently useful — you need metadata and context. There's no problem that's not interdisciplinary, so it would be better if it wasn't so hard and time-intensive to collaborate."
                <div style="margin-top: 20px; font-size: 1rem; opacity: 0.8; font-style: normal;">
                    — heard in our discussion sessions
                </div>
            </div>
            
            <section class="section">
                <h2>What We're Building</h2>
                <div class="solutions-grid">
                    <div class="solution-card">
                        <h4>📊 Live Community Polling</h4>
                        <p>Right here at the summit — understanding how you identify datasets, what barriers you face, and where the biggest pain points lie in data discoverability.</p>
                        <span class="status active">Active Now</span>
                    </div>
                    
                    <div class="solution-card">
                        <h4>📝 Comprehensive Post-Survey</h4>
                        <p>Detailed follow-up exploring metadata practices, repository usage, interoperability challenges, and time spent on data preparation across disciplines.</p>
                        <span class="status planned">Coming Soon</span>
                    </div>
                    
                    <div class="solution-card">
                        <h4>📑 Call-to-Action Paper</h4>
                        <p>Evidence-based recommendations for Environmental Data Science journal, targeting spring 2026 publication with concrete, actionable standards.</p>
                        <span class="status planned">Spring 2026</span>
                    </div>
                    
                    <div class="solution-card">
                        <h4>🔧 OASIS Integration</h4>
                        <p>Practical metadata guidelines and tools integrated into ESIIL's Open Analysis and Synthesis Infrastructure, making standards accessible where researchers actually work.</p>
                        <span class="status planned">In Development</span>
                    </div>
                </div>
            </section>
            
            <section class="section">
                <h2>Why This Matters</h2>
                <div class="journey-container">
                    <div class="journey-card">
                        <h3>🔍 The Hidden Time Sink</h3>
                        <p>Researchers spend hours, days, even weeks hunting for datasets and preparing them for analysis. Imagine if that time could be spent on actual discovery instead.</p>
                    </div>
                    
                    <div class="journey-card">
                        <h3>🌐 The Interdisciplinary Imperative</h3>
                        <p>Climate change doesn't respect disciplinary boundaries. Hurricane impacts involve meteorology, ecology, sociology, economics, and more. Our data should connect as easily as the problems do.</p>
                    </div>
                    
                    <div class="journey-card">
                        <h3>🚀 Future-Proofing Science</h3>
                        <p>We can't predict what our data will be useful for in the future, but we can ensure it's equipped to be discovered, understood, and reused by the next generation of researchers.</p>
                    </div>
                </div>
            </section>
            
            <div class="team-values">
                <h3 style="text-align: center; margin-bottom: 20px; color: #2d3748; font-size: 1.8rem;">Our Team Values in Action</h3>
                <div class="values-grid">
                    <div class="value-item">
                        <span class="value-icon">🎤</span>
                        <h4>All Voices Welcome</h4>
                        <p>We invite perspectives from every discipline</p>
                    </div>
                    <div class="value-item">
                        <span class="value-icon">🤝</span>
                        <h4>Consensus-Building</h4>
                        <p>We strive for solutions everyone can support</p>
                    </div>
                    <div class="value-item">
                        <span class="value-icon">👂</span>
                        <h4>Active Listening</h4>
                        <p>Every perspective leads with curiosity</p>
                    </div>
                    <div class="value-item">
                        <span class="value-icon">🔍</span>
                        <h4>Evidence-Based</h4>
                        <p>We check our assumptions with real data</p>
                    </div>
                    <div class="value-item">
                        <span class="value-icon">🤖</span>
                        <h4>AI-Transparent</h4>
                        <p>We're open about how we use AI tools</p>
                    </div>
                    <div class="value-item">
                        <span class="value-icon">⚖️</span>
                        <h4>Dependable</h4>
                        <p>We deliver on our commitments</p>
                    </div>
                </div>
            </div>
            
            <section class="section">
                <h2>Our Unique Approach</h2>
                <p style="font-size: 1.1rem; color: #4a5568; margin-bottom: 30px;">
                    While most FAIR data initiatives create complex standards that are "challenging for typical researchers to understand and implement," we're taking a different path:
                </p>
                
                <div class="journey-container">
                    <div class="journey-card">
                        <h3>🏥 Learning from Success Stories</h3>
                        <p><strong>ESS-DIVE shows what's possible:</strong> high-quality standards, clear templates, rigorous quality control. We're studying what makes them successful and how to apply those lessons elsewhere.</p>
                    </div>
                    
                    <div class="journey-card">
                        <h3>👥 Community-Centric Design</h3>
                        <p><strong>Researchers first, standards second:</strong> Instead of top-down mandates, we're building from the ground up, understanding actual workflows and pain points.</p>
                    </div>
                    
                    <div class="journey-card">
                        <h3>🔬 Evidence-Based Development</h3>
                        <p><strong>Data about data practices:</strong> Our surveys and polls aren't just consultation — they're research that will inform practical, adoptable solutions.</p>
                    </div>
                    
                    <div class="journey-card">
                        <h3>🛠️ Implementation-Ready Tools</h3>
                        <p><strong>From theory to practice:</strong> Our OASIS integration ensures recommendations become accessible tools in researchers' actual workflows.</p>
                    </div>
                </div>
            </section>
        </main>
        
        <section class="cta-section">
            <h2>Join the Conversation</h2>
            <p style="font-size: 1.2rem; margin-bottom: 30px;">
                Your experience matters. Help us understand the real challenges and build better solutions.
            </p>
            <a href="#" class="cta-button">Take Our Live Poll</a>
            <a href="#" class="cta-button">Join the Follow-up Survey</a>
            <p style="margin-top: 30px; opacity: 0.9;">
                Together, we're not just managing data — we're accelerating discovery.
            </p>
        </section>
    </div>
</body>
</html>

---

## Day 1 — Define & Explore
*Focus: questions, hypotheses, context; add at least one visual (photo of whiteboard/notes).*

### Our product 📣
-A call to action for broader community change/standards
- a paper for standards in metadata to future-proof data to ensure future utility. We can't imagine what our data can be useful for in the future. How can we generalize across our disciplines? Maybe special issue Environmental Data Science, ideas by Nov 2025, full article by spring 2026
- an open source tool that translates the academic paper

### Our question(s) 📣
- Can we use AI/LLMs for identifying if datasets are fit for use?
- Can we do a review of the metadata standards that exist for FAIR data principles or siloed projects (coping with FAIR Maricela)
- We have to behave differently before we can even get to FAIR

### Hypotheses / intentions
- usefulness of data goes down and cost goes up
- museum/library/archival perspective on data accessibility over time versus data scientist view on data is "useful/accessible" for 5 years max


### Why this matters (the “upshot”) 📣
- in order to operationalize FAIR we have to have community standards that everyone adheres to (DARE?)
- for such a data centric group
- data isn't "useful" broadly to the community
- standardizing the standards
- there's no problem that's not interdisciplinary, it might be better if we have broader community standards

### Inspirations (papers, datasets, tools)
- Publication: [The FAIR Guiding Principles](https://www.nature.com/articles/sdata201618)
- Dataset portal: [EPA Environmental Dataset Gateway](https://edg.epa.gov/)
- Tool/tech: [Pangeo Forge](https://pangeo-forge.org/)

### Field notes / visuals
<!-- EDIT: Replace with a real smartphone photo or sketch; keep filename simple. -->
![Our norms](assets/our_norms.png)
[Raw photo location: assets/our_norms.png](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/blob/main/docs/assets/our_norms.png)
*Caption: Mapping current interoperability pain points, user stories, and priority partners for Group 18.*

> **Different perspectives:** Briefly capture disagreements or alternate framings. These can unlock innovation.

---

## Day 2 — Data & Methods
*Focus: what we’re testing and building; show a first visual (plot/map/screenshot/GIF).*

### Data sources we’re exploring 📣
<!-- EDIT: Link each source; add size/notes if relevant. -->
- **Source A**

- **NOAA Climate Data Online (CDO)** — hourly precipitation and temperature summaries that we will harmonize with partner-held observations.

  ![Pattern revealed during exploration](assets/explore_data_plot.png)
  [Raw photo location: explore_data_plot.png](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/blob/main/docs/assets/explore_data_plot.png)
  *Snapshot highlighting how CDO variables vary across pilot watersheds.*

- **USGS Water Services API** — near real-time streamflow indicators to pair with ecological and community datasets for interoperability testing.

### Methods / technologies we’re testing 📣
- Approach 1 (e.g., time-series break detection)
- Approach 2 (e.g., random forest on features)
- Visualization (e.g., map tiles, small multiples)

### Challenges identified
- Data gaps / quality issues
- Method limitations / compute constraints
- Open questions we need to decide on

### Visuals
<!-- EDIT: Swap examples; keep file sizes modest. -->
#### Static figure
![Early pattern we’re seeing](assets/figure1.png)
[Raw photo location: figure1.png](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/blob/main/docs/assets/figure1.png)
*Figure 1.* One line on what this suggests.

#### Animated change (GIF)
![Seasonal/temporal change animation](assets/change.gif)
[Raw photo location: change.gif](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/blob/main/docs/assets/change.gif)
*Figure 2.* One line on what changes across time.

#### Interactive map (iframe)
<iframe
  title="Interoperability pilot area (OpenStreetMap)"
  src="https://www.openstreetmap.org/export/embed.html?bbox=-105.35%2C39.90%2C-105.10%2C40.10&layer=mapnik&marker=40.000%2C-105.225"
  width="100%" height="360" frameborder="0"></iframe>
<p><a href="https://www.openstreetmap.org/?mlat=40.000&mlon=-105.225#map=12/40.0000/-105.2250">Open full map</a></p>

> If an embed doesn’t load, put the normal link directly under it.

---

## Final Share Out — Insights & Sharing 
*Focus: synthesis; highlight 2–3 visuals that tell the story; keep text crisp. Practice a 2-minute walkthrough of the homepage 📣: Why → Questions → Data/Methods → Findings → Next.*

![Team photo at start of Day 3](assets/team_photo.jpg)
[Raw photo location: team_photo.jpg](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/blob/main/docs/assets/team_photo.jpg)

### Findings at a glance 📣
<!-- EDIT: 2–4 bullets, each a headline in plain language with a number if possible. -->
- Headline 1 — what, where, how much
- Headline 2 — change/trend/contrast
- Headline 3 — implication for practice or policy

### Visuals that tell the story 📣
<!-- EDIT: Swap visuals; prioritize clarity. -->
![Lead interoperability graphic](assets/fire_hull.png)
[Raw photo location: fire_hull.png](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/blob/main/docs/assets/fire_hull.png)
*Visual 1.* Swap in the primary graphic that clearly communicates your core takeaway.

![Supporting panels for key insights](assets/hull_panels.png)
[Raw photo location: hull_panels.png](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/blob/main/docs/assets/hull_panels.png)
*Visual 2.* Use a complementary panel, collage, or set of snapshots that reinforces supporting evidence.

![Complementary result figure placeholder](assets/main_result.png)
[Raw photo location: main_result.png](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/blob/main/docs/assets/main_result.png)
*Visual 3.* Highlight an additional visual that captures a secondary insight or next step.

<iframe
  title="Short explainer video (optional)"
  width="100%" height="360"
  src="https://www.youtube.com/embed/ASTGFZ0d6Ps"
  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen></iframe>

### What’s next? 📣
- Immediate follow-ups
- What we would do with one more week/month
- Who should see this next

---

## Featured links (image buttons)
<!-- EDIT: Replace images/links; keep alt text meaningful and motion subtle. -->
<table>
<tr>
<td align="center" width="33%">
  <a href="assets/Seven%20ways%20to%20measure%20fire%20polygon%20velocity-4.pdfa"><img src="assets/button_brief.gif" alt="Upload your summit brief" width="240"><br><strong>Read the brief</strong></a>
</td>
<td align="center" width="33%">
  <a href="https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/blob/main/code/single_hull_demo.py"><img src="assets/button_code.gif" alt="Browse shared code" width="240"><br><strong>View code</strong></a>
</td>
<td align="center" width="33%">
  <a href="https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/blob/main/code/prism_quicklook.py"><img src="assets/button_data.gif" alt="Explore shared datasets" width="240"><br><strong>Explore data</strong></a>
</td>
</tr>
</table>

---


## Team
| Name | Role | Contact | GitHub |
|------|------|---------|--------|
| Jane Doe | Lead | jane.doe@example.org | @janedoe |
| John Smith | Analyst | john.smith@example.org | @jsmith |

---



## Storage

Code
Keep shared scripts, notebooks, and utilities in the [`code/`](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/tree/main/code) directory. Document how to run them in a README or within the files so teammates and visitors can reproduce your workflow.

Documentation
Use the [`docs/`](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/tree/main/docs) folder to publish project updates on this site. Longer internal notes can live in [`documentation/`](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/tree/main/documentation); summarize key takeaways here so the public story stays current.

---

## Cite & reuse
If you use these materials, please cite:

> ESIIL Innovation Summit Team 18. (2025). *Cross-Cutting Data Interoperability & Harmonization Innovation Summit 2025 — Group 18*. https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18

License: CC-BY-4.0 unless noted. See dataset licenses on the **[Data](data.md)** page.

---

<!-- EDIT HINTS
- Upload images to docs/assets/ and reference as assets/filename.png
- Keep images ~1200 px wide; avoid >5–8 MB per file.
- Use short, active sentences; this is a scrolling “slide deck.”
- Update this page at least once per day during the sprint.
-->
