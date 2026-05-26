---
title: Kshitij Durge
type: landing

design:
  spacing: '4rem'

sections:
  - block: resume-biography
    id: about
    content:
      username: me

  - block: resume-experience
    id: experience
    content:
      username: me
      title: Experience & Education
    design:
      columns: 1

  - block: collection
    id: publications
    content:
      title: Publications & Thesis
      text: ""
      filters:
        folders:
          - publications
    design:
      view: citation

  - block: markdown
    id: skills
    content:
      title: Technical Expertise
      text: |
        I have executed most of my simulations in PennyLane, occasionally utilizing Qiskit. I am experienced in Quantum Machine Learning (QML) and Quantum Information Theory. I am proficient in Python and have a basic knowledge of C and C++. My research experience also includes scientific writing and LaTeX.
    design:
      columns: 1

  - block: collection
    id: research
    content:
      title: Research Projects
      text: ""
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2
      fill_image: false
      show_date: false
      show_read_time: false

  - block: markdown
    id: contact
    content:
      title: Contact
      text: |
        📧 **Email**: [kshitijdurgekd@gmail.com](mailto:kshitijdurgekd@gmail.com)

        🏛️ **Address**: QuCIS lab, Department of Electrical Engineering and Computer Science, IISER Bhopal, 462066, Bhopal, Madhya Pradesh, India

        Feel free to reach out if you are interested in collaborating on quantum computing research.
    design:
      columns: 1
---