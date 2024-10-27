---
title: People
date: 2022-10-24

type: landing

sections:
  - block: about.biography
    id: current
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          # - Principal Investigators
          # - Researchers
          - Associate Professor
          - Postdoctoral Associates
          - PhD. Candidates
          - MS
          - Grad Students
          # - Administration
          # - Visitors
          # - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: people
    id: alumni
    content:
      title: Our Alumni
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          # - Principal Investigators
          # - Researchers
          # - Associate Professor
          # - Postdoctoral Associates
          # - PhD. Candidates
          # - MS
          # - Grad Students
          # - Administration
          # - Visitors
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
---