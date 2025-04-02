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
        👋 Hallo! Ich bin **Amirmahan Tajik**, Informatikstudent an der TU Clausthal mit einem besonderen Interesse an **Künstlicher Intelligenz**, **IT-Sicherheit** und **Softwareentwicklung**.

        In meiner Freizeit programmiere ich leidenschaftlich gerne, spiele Tischtennis, gehe spazieren und höre Musik. 🚀

        Auf dieser Seite findest du meine Projekte, Publikationen und mehr!
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

  - block: collection
    content:
      title: Selected Projects
      text: Hier findest du eine Auswahl meiner Projekte aus Studium und Freizeit.
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3

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
      title: Kontaktieren Sie mich!
      text: |
        Du hast eine Frage, ein Projekt oder möchtest einfach nur Hallo sagen?  
        Ich bin immer offen für spannende Gespräche rund um KI, Security und Coding!
      button:
        text: LinkedIn-Profil
        url: https://www.linkedin.com/in/amirmahan-tajik-5192a3288/
    design:
      card:
        css_class: "bg-primary-700"
---
