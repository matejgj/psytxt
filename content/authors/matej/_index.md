---
# Display name
name: Matej Gjurković

# Username (this should match the folder name)
authors:
- matej

# Is this the primary user of the site?
superuser: true

# Role/position
role: Mess generator
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
- icon: linkedin
  icon_pack: fab
  link: https://www.linkedin.com/in/matejgjurkovic/
- icon: twitter
  icon_pack: fab
  link: https://twitter.com/matgju
- icon: google-scholar
  icon_pack: ai
  link: https://scholar.google.com/citations?user=TMbUXMMAAAAJ
- icon: researchgate
  icon_pack: ai
  link: https://www.researchgate.net/profile/Matej_Gjurkovic
- icon: orcid
  icon_pack: ai
  link: https://orcid.org/0000-0002-8345-2138
- icon: arxiv
  icon_pack: ai
  link: http://arxiv.org/a/gjurkovic_m_1
- icon: mendeley
  icon_pack: ai
  link: https://www.mendeley.com/profiles/matej-gjurkovic/
- icon: osf
  icon_pack: ai
  link: osf.io/cfyw3
- icon: semantic-scholar
  icon_pack: ai
  link: https://www.semanticscholar.org/author/Matej-Gjurkovic/51130892


  
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

I am the "what if" type who raises a lot more questions than he can answer. That's also the main reason I enrolled in a PhD program after working as a software engineer for years.

I have always been interested in psychology, but only as a hobby. That changed when I started reading up on ML and NLP in particular and came up with the idea of combining these fields with psychology.

I am currently focusing on developing resources that can help overcome the challenge of automatically recognizing personality traits from text.

In my spare time, I enjoy conducting psychological experiments on myself and stepping out of my comfort zone. I enjoy ultra trail running, rock and alpine climbing, and mountaineering. 
My most notable experiences include completing a 173km trail running race and climbing a 7000m mountain.


<body>
	<div id='radar'><!-- Plotly chart will be drawn inside this DIV --></div>

<script>

data = [{
  type: 'scatterpolar',
  r: [47, 83, 90, 49, 39, 27, 87, 9, 88, 87, 81, 1, 32],
  theta: ['Agreeableness', 'Openness', 'Imagination', 'Conscientiousness', 'Extraversion',
       'Neuroticism','Adventurousness','Gregariousness','Intellect','Progressivism','Cooperation','Orderliness','Emotionality'],
  fill: 'toself'
}]

layout = {
  polar: {
    radialaxis: {
      visible: true,
      range: [0, 100]
    }
  },
  showlegend: false
}

Plotly.newPlot("radar", data, layout)


</script>

</body>