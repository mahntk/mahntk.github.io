---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-04-02
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: |
              👋 Hallo! Ich bin Amirmahan Tajik, Informatikstudent an der Technischen Universität Clausthal.
              Ich interessiere mich besonders für die spannenden und zukunftsweisenden Themen Künstliche Intelligenz, IT-Sicherheit und Softwareentwicklung. Mein Ziel ist es, durch kreative Ideen und technisches Know-how moderne, leistungsstarke und sichere Anwendungen zu entwickeln, die einen echten Mehrwert schaffen.

              💻 Schon während meines Studiums habe ich an verschiedenen Projekten gearbeitet – von kleinen Tools bis hin zu komplexeren Anwendungen. Dabei liebe ich es, neue Technologien zu entdecken, Probleme zu analysieren und elegante Lösungen zu entwerfen.

              🎯 Besonders fasziniert mich der Bereich der Künstlichen Intelligenz, da er das Potenzial hat, viele Aspekte unseres Lebens grundlegend zu verändern – von der Medizin bis zur Mobilität. Ebenso begeistert mich die IT-Sicherheit, denn in einer zunehmend vernetzten Welt ist Datenschutz wichtiger denn je.

              🌱 Neben dem Studium programmiere ich mit großer Leidenschaft in meiner Freizeit, lerne ständig Neues dazu und tausche mich gern mit Gleichgesinnten aus. Außerdem spiele ich Tischtennis, gehe gern spazieren und höre Musik, um den Kopf freizubekommen und neue Inspiration zu finden.

              🚀 Auf dieser Webseite findest du einen Einblick in meine Projekte, Publikationen und Interessen. Viel Spaß beim Stöbern!
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: '🧠 Aktuelles Projekt – Titanic KI-Modell'
      text: |
        In einem meiner letzten Projekte habe ich mit einem Team den berühmten Titanic-Datensatz analysiert und verschiedene **Machine-Learning-Algorithmen** wie **Naive Bayes**, **logistische Regression** und **KNN** implementiert.

        Ziel war es, die **Überlebenswahrscheinlichkeit von Passagieren vorherzusagen**. Besonderes Augenmerk lag auf Feature Engineering, Hyperparameter-Tuning und Modellauswahl.  
        
        👉 [Zum Projekt](projects/titanic-ml)
    design:
      columns: '1'

#  - block: collection
 #   content:
  #    title: Selected Projects
   #   text: Hier findest du eine Auswahl meiner Projekte aus Studium und Freizeit.
    #  filters:
     #   folders:
      #    - project
#    design:
#      view: article-grid
#      fill_image: false
#      columns: 3

  - block: collection
    content:
      title: Recent Posts
      text: ""
      filters:
        folders:
          - post
    design:
      view: date-title-summary

  - block: cta-card
    content:
      title: Kontakt
      text: | 
        Ich freue mich über jede Nachricht – egal ob per Mail oder auf LinkedIn.
        
        📧 **E-Mail:** [amirmahantajik991@gmail.com](mailto:amirmahantajik991@gmail.com)  
        🔗 **LinkedIn:** [Profil ansehen](https://www.linkedin.com/in/amirmahan-tajik-5192a3288/)
      button:
        text: Jetzt kontaktieren
        url: mailto:amirmahantajik991@gmail.com
    design:
      card:
        css_class: "bg-primary-700"
---