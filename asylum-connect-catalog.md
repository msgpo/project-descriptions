---
layout: project

summary:
    name: Asylum Connect Catalog
    tagline: A dynamic, online, centralized database of service providers useful to LGBTQ asylum seekers in the U.S.

team:
    - year: 2016
      semester: Fall
      pm:
      tl: Yoni Nachmany
      developers:
          - Hunter Lightman
          - Hana Pearlman
          - Veronica Wharton

client:
    - name: AsylumConnect
      description: >
          AsylumConnect is an incorporated nonprofit startup creating the first website and mobile app to feature an online,
          centralized database of service providers for LGBTQ asylum seekers in the U.S. The AsylumConnect catalog will help
          persecuted LGBTQ people find fundamental human needs resources upon their arrival in the U.S.
      website_url: http://www.asylumconnect.org/

project:
    problem: >
        AsylumConnect’s current resource verification model is a bottleneck, as volunteers must search for and independently
        verify resources for each city that the organization expands into. In addition, volunteers are not (all) members of
        our target community, and therefore not the best-equipped to verify whether or not a resource is LGBTQ-friendly,
        asylum seeker-friendly, etc. By allowing community members to tag, verify, endorse, and report resources, AsylumConnect
        will empower its niche and highly marginalized community while also keeping members as safe as possible.
    features:
        - Dynamic resource database with CRUD (create, read, update, delete) capabilities
        - Automated form for resource submission, editing & reporting that publishes publication requests to the admin console
        - Admin console for managing, editing, approving or rejecting resource submissions
        - Searching resources by location (e.g., Select a City like Philly / Seattle)
        - Basic data integrity & privacy (minimize collection of identifying user information)
        - Basic Google Analytics to track custom user actions
        - (Looking ahead) Better resource geospatial visualization such as geolocation, directions, Google Street View
        - (Looking ahead) Ability to endorse features
        - (Looking ahead) When submitting a resource, check if resource already exists (de-duping)
        - (Looking ahead) Being able to sort resources by proximity
    technologies:
        - Python
        - Flask (for web application microframework)
        - SQLAlchemy (for databases)
        - Bootstrap (for responsive, mobile first framework for HTML, CSS, and JS)
        - JQuery
    impact: >
        Upon arrival to the U.S. from countries where they are persecuted because of their sexual orientation or gender
        expression, LGBTQ asylum seekers often have nowhere to go, no social support, and no legal right to work - many end up
        homeless. AsylumConnect strives to rectify this situation by assisting asylum seekers in locating and obtaining
        lifesaving resources. This simple idea has the potential to benefit an estimated 300,000 LGBTQ asylum seekers.

code:
    github_repo_name: https://github.com/asylumconnect/asylum-connect-catalog
    live_url: http://asylumconnectcatalog.org/

keywords:
    social_impact_keywords:
        - LGBTQ
        - asylum
        - services
    tech_keywords:
        - crowdsourcing
        - open-source
        - privacy

media:
    screenshots:
        - screenshot_caption: Users can go to Seattle catalog
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/asylum-connect-catalog/ss1.png
        - screenshot_caption: Users can go to Philadelphia catalog
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/asylum-connect-catalog/ss2.png
        - screenshot_caption: Users can select categories, features, and requirements of resources
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/asylum-connect-catalog/ss3.png
        - screenshot_caption: Users can expand a resource from the map and view as a list
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/asylum-connect-catalog/ss4.png
        - screenshot_caption: Users can print resource list (part 1)
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/asylum-connect-catalog/ss5.png
        - screenshot_caption: Users can print resrouce list (part 2)
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/asylum-connect-catalog/ss6.png
        - screenshot_caption: Users can suggest changes to resources, to be reviewed by admins
          screenshot_url: https://raw.githubusercontent.com/hack4impact/project-screenshots/master/asylum-connect-catalog/ss7.png
    articles:
        - article_name: AsylumConnect Scales Catalog v3.0 to Philadelphia, PA
          article_url: http://www.asylumconnect.org/source-blog/2017/2/19/asylumconnect-scales-first-online-centralized-resource-database-for-lgbtq-asylum-seekers-to-philadelphia-pa
---
