<div style="display:flex;background-color:#f6f8fa;border:1px solid #f0f0f0;border-bottom:none;border-radius:10px 10px 0 0;padding:28px">
<img width="100px" style="display:inline-block;background:none" src="https://raw.githubusercontent.com/ngInit/Assets/refs/heads/main/cvA.png" alt="CV image">
<h2 style="display:inline-block;margin-top:36px;border:none;margin-left:24px">Aleksei Nikolaev</h2>
</div>
<div style="background-color:#f6f8fa;border:1px solid #f0f0f0;border-top:none;border-radius:0 0 10px 10px;padding: 0 28px 28px;">
<span style="color:steelblue">Tel:</span> <span>+36 (70) 555-17-69</span><br>
<span style="color:steelblue">Email:</span> <span>aleksey.nikolaev.eng@gmail.com</span><br>
<span style="color:steelblue">Discord:</span> Aleksei (@ngInit)<span></span><br>
<span style="color:steelblue">GitHub:</span> <a target="_blank" href="https://github.com/ngInit">Open Link</a><br>
</div>
<br>
<div style="background-color:#f6f8fa;border:1px solid #f0f0f0;border-radius:10px;padding:14px">
<span style="display:inline-block;margin:0 0 8px 14px;font-weight:700;color:steelblue">ABOUT ME</span>
<pre style="background:none;padding:0;margin:0 0 0 14px">
    I'm an engineer with 8 years’ experience in CNC programming industry. I decided to change my way and 
nowadays, I'm interested in frontend and full-stack development. I have some modern frontend development
skills and solid knowledge of common design patterns.
Moreover, my ability to self-education and self-organization allow me to work just as well on team projects 
as on my own.
</pre>
</div>
<br>
<div style="background-color:#f6f8fa;border:1px solid #f0f0f0;border-radius:10px;padding:14px">
<span style="display:inline-block;margin:0 0 8px 14px;font-weight:700;color:steelblue">SKILLS</span>
<pre style="background:none;padding:0;margin:0 0 0 28px">
• Angular    • React    • Bootstrap    • HTML   • CSS
• .NET       • Node.js  • JavaScript   • C#     • TypeScript       
• GitHub     • SOLID    • Clean Code   • Figma  • Photoshop
• Analytical skills     • Problem solving       • Agile & Waterfall
</pre>
</div>
<br>
<div style="background-color:#f6f8fa;border:1px solid #f0f0f0;border-radius:10px;padding:14px">
<span style="display:inline-block;margin:0 0 8px 14px;font-weight:700;color:steelblue">PROJECTS</span><br>
<span style="font-size:14px;padding:0;margin:0 0 0 28px">Currency Chart</span>
<pre style="background:none;padding:0;margin:0 0 0 28px">
<i>• Description:</i> A web-app with a chart for comparing currencies
<i>• Login:</i> Guest
<i>• Password:</i> My2007
<i>• <a target="_blank" href="https://currency-chart.vercel.app/Login">Open Project</a></i>
</pre>
<br>
<span style="font-size:14px;padding:0;margin:0 0 0 28px">CUE Sheet Audio</span>
<pre style="background:none;padding:0;margin:0 0 0 28px">
<i>• Description:</i> This VS Code extension was created to make it easier to create and edit CUE Sheets of Audio files
<i>• <a target="_blank" href="https://marketplace.visualstudio.com/items?itemName=QuantumPannonia.cue-sheet-audio">Open Project</a></i>
</pre>
</div>
<br>
<div style="background-color:#f6f8fa;border:1px solid #f0f0f0;border-bottom:none;border-radius:10px 10px 0 0;padding:14px">
<span style="display:inline-block;margin:0 0 0 14px;font-weight:700;color:steelblue">CODE EXAMPLE</span>
</div>

````js
    async function getArtists(artist) {
        await fetch(this.currentRequest, this.options)
            .then(artists => {
                if (artists.ok) {
                    console.log(artists.status);
                    return artists.clone().json();
                }
                else {
                    return 0;
                }
            })
            .then(list => {
                this.artists.count = list["count"];
                list.artists.map(item => {
                    let artist = Object.assign({}, this.newArtist);
                    artist.id = item["id"];
                    artist.name = item["name"];
                    artist.country = item["country"];
                    this.artists.list.push(artist);
                })
            });
        return this.artists;
    }
````
<div style="background-color:#f6f8fa;border:1px solid #f0f0f0;border-radius:10px;padding:14px;margin-top: 36px">
<span style="display:inline-block;margin:0 0 8px 14px;font-weight:700;color:steelblue">WORK EXPERIENCE</span><br>
<span style="font-size:14px;font-weight:700;padding:0;margin:0 0 0 28px">CNC programmer (2014 - 2022)</span>
<pre style="background:none;padding:0;margin:0 0 0 28px">
• Writing code for manufacturing machines
• Testing, analyzing and correcting existing code
• Supporting code at all stages of the life cycle
• Writing technical documentation
• Training & mentoring
</pre>
<br>
<span style="font-size:14px;font-weight:700;padding:0;margin:0 0 0 28px">Adjuster CNC machines (2012 - 2014)</span><br>
<pre style="background:none;padding:0;margin:0 0 0 28px">
• Working with 3-Axis and 3+1-Axis CNC machines
• Setting up production equipment
• Debugging program projects
• Reading blueprints and technical documentation
• Writing documentation for the purchase of tools
</pre>
</div>
<br>
<div style="background-color:#f6f8fa;border:1px solid #f0f0f0;border-radius:10px;padding:14px">
<span style="display:inline-block;margin:0 0 8px 14px;font-weight:700;color:steelblue">EDUCATION</span><br>
<span style="font-size:14px;font-weight:700;padding:0;margin:0 0 0 28px">Postgraduate degree (PhD)</span>
<pre style="background:none;padding:0;margin:0 0 0 28px">
ITMO University (2017 - 2021)
GPA: 4.37 of 5.00
Field: Engineering (Faculty of Control Systems and Robotics)
</pre>
<br>
<span style="font-size:14px;font-weight:700;padding:0;margin:0 0 0 28px">Master's Degree</span>
<pre style="background:none;padding:0;margin:0 0 0 28px">
ITMO University (2015 - 2017)
GPA: 4.76 of 5.00
Field: Engineering (Device-making technologies)
</pre>
<br>
<span style="font-size:14px;font-weight:700;padding:0;margin:0 0 0 28px">Bachelor's degree</span>
<pre style="background:none;padding:0;margin:0 0 0 28px">
ITMO University (2011 - 2015)
GPA: 4.41 of 5.00
Field: Engineering
</pre>
<br>
<span style="font-size:14px;font-weight:700;padding:0;margin:0 0 0 28px">HTML, CSS, and Javascript for Web Developers</span><br>
<pre style="background:none;padding:0;margin:0 0 0 28px">
The Johns Hopkins University
Issue date: February 2023
ID: V3RY4TFUDBM3
<a target="_blank" href="https://www.coursera.org/account/accomplishments/verify/V3RY4TFUDBM3">Open Certificate</a>
</pre>
<br>
<span style="font-size:14px;font-weight:700;padding:0;margin:0 0 0 28px">CSS (Basic)</span>
<pre style="background:none;padding:0;margin:0 0 0 28px">
HackerRank
Issue date: November 2023
ID: B1B49D0C7BF3
<a target="_blank" href="https://www.hackerrank.com/certificates/b1b49d0c7bf3">Open Certificate</a>
</pre>
</div>
<br>
<div style="background-color:#f6f8fa;border:1px solid #f0f0f0;border-radius:10px;padding:14px">
<span style="display:inline-block;margin:0 0 8px 14px;font-weight:700;color:steelblue">LANGUAGES</span><br>
<span style="font-size:14px;padding:0;margin:0 0 0 28px">English language school HOP&SCOTCH: <span style="font-weight:700">Upper-Intermediate II (B2)</span></span><br>
<span style="font-size:14px;padding:0;margin:0 0 0 28px">Russian: <span style="font-weight:700">Native</span></span><br>
<span style="font-size:14px;padding:0;margin:0 0 0 28px">Ukrainian: <span style="font-weight:700">Native</span></span><br>
<span style="font-size:14px;padding:0;margin:0 0 0 28px">Hungarian: <span style="font-weight:700">Beginner (A1)</span></span>
</div>