---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate Research Assistant
          company: University of Central Florida
          company_url: 'https://www.ucf.edu/'
          location: Orlando, FL, USA
          date_start: '2022-08-01'
          date_end: ''
          description: |2-
              - Led team in kernel configuration research, achieving a 9% boost in coverage and a 15% increase in bug detection.
              - Engineered and deployed automation scripts in Python to speed up code integration and error identification.
              - Initiated configuration-aware fuzzing for Linux kernel security, identifying and reporting 41 bugs.
              - Authored a research paper detailing the project, incorporating graphs, diagrams, and algorithms for enhanced clarity.
        - title: Summer Intern
          company: Trail of Bits
          company_url: 'https://www.trailofbits.com/'
          location: New York City, NY, USA
          date_start: '2024-06-01'
          date_end: '2024-08-01'
          description: |2-
              - Contributed to the value generation logic of the open-source smart contract fuzzer Medusa by implementing a tracer to collect return values and values emitted via events during EVM execution, resulting in an 18% increase in bug discovery.
              - Utilized goroutines to extract event and return values from binary data and performed corpus collection to enhance the call sequence speed of the fuzzer, which contributed to around a 22% boost in performance.
              - Refactored tracing logic of Medusa by providing a larger abstraction for each tracer module, achieving clean and readable code.
        - title: Security Research Intern
          company: Margin Research
          company_url: 'https://www.margin.research/'
          location: New York City, NY, USA
          date_start: '2023-06-01'
          date_end: '2023-08-01'
          description: |2-
              - Developed tools for open-source repositories, automating and increasing vulnerability detection by 25%.
              - Integrated custom security tools into the Reagent platform, enhancing vulnerability detection and improving security performance by 30%.
              - Authored a guide on smart contract vulnerabilities, educating the industry on common security pitfalls.

  - block: skills
    id: skills
    content:
      title: Skills
      items:
        - name: Primary Skills
          description: Syzkaller, QEMU, Bash, Python, Go, C, Vim, Git, Docker, AWS

  - block: collection
    id: publications
    content:
      title: Publications
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
      items:
        - title: "Can You Fuzz Me Now? Overcoming Configuration Blind Spots via Configuration-aware Kernel Fuzzing"
          authors: "Sanan Hasanov, Stefan Nagy, Paul Gazzillo"
          date: "2023"
          publication: "Preprint"
          url_pdf: "https://drive.google.com/file/d/1KRtgWr6HkP1C8V0r4YawQyIGFTF5C70W/view?usp=sharing"
        - title: "A Little Goes a Long Way: Tuning Configuration Selection for Continuous Kernel Fuzzing"
          authors: "Sanan Hasanov, Stefan Nagy, Paul Gazzillo"
          date: "2025"
          publication: "47th IEEE/ACM International Conference on Software Engineering (ICSE)"
          url_pdf: "https://drive.google.com/file/d/1MuCOo7rLF7Ci4d-MaqqZHfOme8WjL9Mm/view?usp=sharing"

  - block: markdown
    id: service
    content:
      title: Service
      subtitle: ''
      text: |-
         - Student Volunteer at [PLDI'22](https://pldi22.sigplan.org/)
    design:
      columns: '1'
---
