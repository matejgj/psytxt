---
# Display name
name: Matej Gjurković

# Username (this should match the folder name)
authors:
- matej

# Is this the primary user of the site?
superuser: true

# Role/position
role: Idea generator
# Organizations/Affiliations
organizations:
- name: TakeLab, FER
  url: ""

# Short bio (displayed in user profile at end of posts)
bio:

#interests:
#- Artificial Intelligence
#- Computational Linguistics
#- Information Retrieval

# education:
#   courses:
#   - course: PhD in Artificial Intelligence
#     institution: Stanford University
#     year: 2012
#   - course: MEng in Artificial Intelligence
#     institution: Massachusetts Institute of Technology
#     year: 2009
#   - course: BSc in Artificial Intelligence
#     institution: Massachusetts Institute of Technology
#     year: 2008

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: "mailto:matej.gjurkovic@fer.hr"
- icon: twitter
  icon_pack: fab
  link: https://twitter.com/matgju
- icon: google-scholar
  icon_pack: ai
  link: https://scholar.google.com/citations?user=TMbUXMMAAAAJ
#- icon: github
#  icon_pack: fab
#  link: https://github.com/jsnajder
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ""

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
- Researchers
#- Visitors
---

I am that "what if" guy that generates much more questions than they can be answered which is also a primary reason why I enrolled in a PhD program after years of working as a software engineer. 

I have always had an interest in psychology, but only as a hobby. This changed when I started learning about ML and in particular NLP and got an idea to combine those fields with psychology.

I am currently focused on the development of resources that can help to tackle the challenge of automating personality traits recognition based on the text.

In my free time, I like to do psychological experiments on myself and push out of the comfort zone. I am into long distance trail running, rock and alpine climbing, as well as mountaineering. The most notable experiences include finishing a 173 km long trail running race and summiting a 7000 m high mountain.


<body>
	<div id='myDiv'><!-- Plotly chart will be drawn inside this DIV --></div>

<script>

data = [{
  type: 'scatterpolar',
  r: [39, 28, 8, 7, 28, 39],
  theta: ['A','B','C', 'D', 'E', 'A'],
  fill: 'toself'
}]

layout = {
  polar: {
    radialaxis: {
      visible: true,
      range: [0, 50]
    }
  },
  showlegend: false
}

Plotly.newPlot("myDiv", data, layout)


</script>

</body>