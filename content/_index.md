---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My work'
      subtitle: ''
      text: |-
        I am an Education Policy Researcher and Ph.D Candidate with over five years of international experience bridging research, policy, and practice. As a education specialist, my work focuses on utilizing diverse data sources to inform educational planning and strengthen education systems' use of evidence.

        My core research areas include: 
        
        - **School Choice & Urban Dynamics:** Examining school supply/demand, spatial accessibility, and socio-spatial segregation patterns using econometric and geospatial analyses.  
        
        - **Educational Equity & Dropout Prevention:** Utilizing administrative EMIS data to analyze school dropout patterns in secondary education and TVET systems.  
        
        - **System Scaling & Innovation:** Applying insights from behavioral, implementation, and scaling sciences to identify and replicate effective local school practices in education systems.

        **Let's Connect!** I am always looking to discuss with  researchers, policymakers, and organizations passionate about education policy research Please reach out to collaborate!
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
---
