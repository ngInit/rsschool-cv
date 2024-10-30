<div style="display:flex;background-color:#f6f6f6;border:1px solid #f0f0f0;border-radius:10px;padding:14px">
<img width="100px" style="display:inline-block" src="https://raw.githubusercontent.com/ngInit/Assets/refs/heads/main/cvA.png" alt="CV image">
<h2 style="display: inline-block; margin-left: 24px">Aleksei Nikolaev</h2>
</div>
<br>
<div style="background-color:#f6f6f6;border:1px solid #f0f0f0;border-radius:10px;padding:14px">
<span style="color:#8900bd">Tel:</span> <span style="color:#2b87a7">+36 (70) 555-00-00</span><br>
<span style="color:#8900bd">Email:</span> <span style="color:#2b87a7">aleksey.nikolaev@gmail.com</span><br>
<span style="color:#8900bd">GitHub:</span> <a style="color:#2b87a7" href="https://github.com/ngInit">Open Link</a></div>
<br>
<div style="background-color:#f6f6f6;border:1px solid #f0f0f0;border-radius:10px;padding:14px">
<span style="display:inline-block;margin-left:14px;font-weight:700;color:steelblue">ABOUT ME</span>
<pre style="margin-left:14px">
I'm an engineer with 8 years’ experience in CNC programming industry. I decided to change my way and nowadays,
I'm interested in frontend and full-stack development. I have some modern frontend development skills and 
solid knowledge of common design patterns.
Moreover, my ability to self-education and self-organization allow me to work just as well on team projects 
as on my own.
</pre>
</div>
<br>
<div style="background-color:#f6f6f6;border:1px solid #f0f0f0;border-radius:10px;padding:14px">
<span style="display:inline-block;margin-left:14px;font-weight:700;color:steelblue">SKILLS</span>
<pre style="margin-left:14px">
• Angular    • React    • Bootstrap    • HTML   • CSS
• .NET       • Node.js  • JavaScript   • C#     • TypeScript       
• GitHub     • SOLID    • Clean Code   • Figma  • Photoshop
• Analytical skills     • Problem solving       • Agile & Waterfall
</pre>
</div>
<br>
<div style="background-color:#f6f6f6;border:1px solid #f0f0f0;border-radius:10px;padding:14px">
<span style="font-weight:700;margin:14px;color:steelblue">CODE EXAMPLE</span>
</div>

```javascript
async getArtists(artist) {

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
```
<br>
<div style="background-color:#f6f6f6;border:1px solid #f0f0f0;border-radius:10px;padding:14px">
<span style="display:inline-block;margin-bottom:8px;margin-left:14px;font-weight:700;color:steelblue">WORK EXPERIENCE</span><br>
<span style="font-size:14px;font-weight:700">CNC programmer (2014 - 2022)</span>
<pre style="margin-left:14px">
• Writing code for manufacturing machines
• Testing, analyzing and correcting existing code
• Supporting code at all stages of the life cycle
• Writing technical documentation
• Training & mentoring
</pre>
<span style="display:inline-block;margin-top:14px;font-size:14px;font-weight:700">Adjuster CNC machines (2012 - 2014)</span><br>
<pre style="margin-left:14px">
• Working with 3-Axis and 3+1-Axis CNC machines
• Setting up production equipment
• Debugging program projects
• Reading blueprints and technical documentation
• Writing documentation for the purchase of tools
</pre>
</div>
<br>
<div style="background-color:#f6f6f6;border:1px solid #f0f0f0;border-radius:10px;padding:14px">
<span style="display:inline-block;margin-bottom:8px;margin-left:14px;font-weight:700;color:steelblue">EDUCATION</span><br>
<span style="font-size:14px;font-weight:700">Postgraduate degree (PhD)</span>
<pre style="margin-left:14px">
ITMO University 2017 - 2021
GPA: 4.37 of 5.00
Field: Engineering (Faculty of Control Systems and Robotics)
</pre>
<span style="display:inline-block;margin-top:14px;font-size:14px;font-weight:700">Master's Degree</span>
<pre style="margin-left:14px">
ITMO University 2015 - 2017
GPA: 4.76 of 5.00
Field: Engineering (Device-making technologies)
</pre>
<span style="display:inline-block;margin-top:14px;font-size:14px;font-weight:700">Bachelor's degree</span>
<pre style="margin-left:14px">
ITMO University 2011 - 2015
GPA: 4.41 of 5.00
Field: Engineering
</pre>
<span style="display:inline-block;margin-top:14px;font-size:14px;font-weight:700">HTML, CSS, and Javascript for Web Developers</span><br>
<pre style="margin-left:14px">
The Johns Hopkins University
Issue date: February 2023
ID: V3RY4TFUDBM3
</pre>
<span style="display:inline-block;margin-top:14px;font-size:14px;font-weight:700">CSS (Basic)</span>
<pre style="margin-left:14px">
HackerRank
Issue date: November 2023
ID: B1B49D0C7BF3
</pre>
</div>
<br>
<div style="background-color:#f6f6f6;border:1px solid #f0f0f0;border-radius:10px;padding:14px">
<span style="display:inline-block;margin-bottom:8px;margin-left:14px;font-weight:700;color:steelblue">LANGUAGES</span><br>
<span style="display:inline-block;margin-left:14px">English language school HOP&SCOTCH: <span style="font-weight:700">Upper-Intermediate II (B2)</span></span><br>
<span style="display:inline-block;margin-left:14px">Russian: <span style="font-weight:700">Native</span></span><br>
<span style="display:inline-block;margin-left:14px">Ukrainian: <span style="font-weight:700">Native</span></span><br>
<span style="display:inline-block;margin-left:14px">Hungarian: <span style="font-weight:700">Beginner (A1)</span></span>
</div>