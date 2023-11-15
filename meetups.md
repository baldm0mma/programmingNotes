## Themes

### Non-technical

  - Dev Rel
  - Handlling async relationships
  - Imposter syndrom

## Talks

### The Global Playground: Navigating Diversity in a Remote World

#### Content Chunk 1: "The Global Playground: Navigating Diversity in a Remote World"

- Point 1: Embracing Cultural Diversity
  - Concepts
    - Start by discussing the diversity at Grafana Labs, with team members spanning different countries, cultures, and backgrounds.
    - Explain the value of this diversity in fostering innovation and creativity by bringing a wide range of perspectives to the table.
    - Share stories or examples of how the company has successfully harnessed this diversity to solve problems and develop unique solutions.
  - Intro
    - Grafana Labs is a remote only, global community of employees that spans almost every continent on the planet, and dozens of countries and 18 time zones around the world. With this expansiveness comes incredible opportunities, as well as genuine challenges.
    - Grafana Labs is a melting pot of talent, and with team members hailing from every corner of the globe, each contributing a unique set of experiences, perspectives, and cultural insights, this diversity isn't just a part of the company's identity; I would argue it's a driving force behind its success.
    - But, unlike many tech organizations, this diversity isn't merely a checkable box on a corporate checklist but a deliberate strategy that enhances collaboration and creativity. Cross-cultural collaboration is at the heart of Grafana Labs, with each team member bringing a unique cultural perspective and context to their work.
    - In todays tech-driven landscape, innovation is crucial for staying ahead. Grafana Labs recognizes that to innovate, it's essential to think differently and approach challenges from multiple angles. A diverse team naturally brings a wide range of problem-solving approaches to the table. The intersection of different viewpoints sparks creativity and encourages out-of-the-box thinking.
    - The value of diversity goes beyond the projects themselves. It's about building an inclusive culture where every team member feels heard, respected, valued for their unique contributions, and can bring their whole selves to work. This is the foundation for the strong team culture and a healthy work environment we have at Grafana Labs.
    - Story
      - Imagine a frigid, Colorado morning; vivid white snowfall blankets the ground and hangs heavily off tree branches. The sun isn't quite up yet, but has begun to reluctantly peek above the horizon. Jev Forsberg, this guy, is in his 3rd week at Grafana. He's been handed some smaller, but still important tasks, and has been fitting in well with his team. And for the most part, everything has gone incredibly smoothly.
        - Oh no... foreshadow_image
      - Suddenly, a ping on Slack. Someone named Torkel Ödegaard drops a message into our team's channel: "The latest update introduced a bug that's breaking Table, and it's affecting the majority part of our largest clients. They can access their dashboards, but they all error out. We need to fix this immediately."
      - Who is this?!?!?
        - Oh no... - torkel_odegaard_image
      - Our team springs into action. On the call, there's Victor from Romania, Oscar from Sweden, and Zoltan from Hungary, each contributing their unique perspectives:
        - Zoltan: his ability to think outside the box and come up with creative solutions.
        - Victor: his reputation for thoughtful analysis and meticulous problem-solving.
        - Oscar: his calm demeanor and exceptional understanding of the codebase.
      - Firstly, how was this bug introduced, and when?
        - Oh no... - jev_forsberg_github_image
      - Secondly, how do we fix it?
        - Together, we collaborate throughout the next few hours, despite being spread across different time zones and geographies, each of us bringing our unique expertise to the table. By EOD UTC, we've not only fixed the bug but have also added a small enhancement to the visualization, making it even more intuitive for the clients then it was before.
      - Now, could I have fixed this bug myself? Obviously not, I'm the dummy that introduced it. Just kidding, sure, of course, but it would have lacked the very gestalt-quality that makes Grafana great: bringing together a diverse group of people to solve problems in a way that is greater than the sum of its parts.
  

- Point 2: Challenges
  - Concepts
    - Address the challenges that come with cultural differences, including varying work styles, communication norms, and time zones.
    - Share strategies that Grafana Labs has implemented to overcome these challenges, such as using asynchronous communication tools and setting clear expectations for collaboration.
    - Highlight the importance of open and inclusive communication to bridge cultural gaps and build a strong team culture.
  - Content
    - Challenges
      - Working in a global, diverse, and asynchronous team does come with its set of challenges:
        - Varying Working Hours: The first challenge is managing different time zones. While it's a fantastic aspect of Grafana Labs that the sun never sets on its teams, coordinating meetings, collaborating on projects, and ensuring effective communication across time zones can be a logistical quagmire.
          - My team is split between the US, and Western/Central Europe. Around midnight MST, half my team clocks in, and only 6-9 hours later does the other half of my team even wake up and get online. This means that if I need to get ahold of someone, I need to be very intentional about when I do it. A quick glance at our teammates calendars shows an overlap of only about 90-120 minutes a day that is shared between all of us.
            - team-cal.png
        - Communication Styles: Cultural differences often lead to distinct communication styles and norms. This is our second challenge. What might be seen as assertive in one cultural context might be considered impolite in another. These differences can easily lead to misunderstandings, miscommunications, and at worst, team conflict.
          - For example, in the US, we tend to be very direct and to the point. We don't like to beat around the bush, and we don't like to waste time. We also tend to be very informal, and we don't like to use titles or honorifics. This can be a bit of a shock to someone from a culture that is more formal, or that values indirect communication. And it can be a bit of a shock to someone who is used to a more formal work environment.
        - Cultural Differences: Working with colleagues from diverse cultural backgrounds can sometimes lead to misunderstandings or clashes related to work practices, holidays, and expectations. These differences can affect team dynamics and workflow, and is our third challenge.
          - For example, when it comes to holiday/vacation: my European colleagues tend to take longer vacations during the summer months, while us Americans tend to take shorter vacations throughout the year. This can lead to some confusion and difficulties when it comes to planning out work and projects for the year.
          - At one point, 3 Europeans were out for the same 3 week period, and so knowing that in advance helped us plan our deliverables for that quarter accordingly. On the other hand, since us Americans tend to spread our vacation time out, we're often gone at what seems like random intervals with no rhyme or reason. A Friday here, and Monday there; and these days often fall on scheduled planning or review sessions.

- Point 3: Solutions: Building Cross-Cultural Understanding
  - Concepts
    - Discuss the benefits of investing in cross-cultural training and awareness programs.
    - Share how Grafana Labs promotes cross-cultural understanding through initiatives like diversity and inclusion workshops, language courses, or cultural exchange events.
    - Provide practical tips for attendees on how to interact effectively with colleagues from diverse cultural backgrounds and embrace the learning opportunities that come with it.
  - Content
    - Solutions
      - Despite these challenges, Grafana Labs has implemented a number of strategies to overcome them and build a strong, cohesive team culture:
        - Robust Asynchronous Communication Options and Training:
          - The first solution to our previous challenges is thoughtful and robust asynchronous communication. We use tools like Slack, GitHub, Google Meet, and email to communicate asynchronously, which allows us to work around different time zones and schedules. This also allows us to be more intentional about when we communicate, and how we communicate. We can be more thoughtful about what we say, and how we say it, and we can be more intentional about how we respond to others.
          - We also record and annotate all important meetings, so that anyone who wasn't able to attend can still get the information they need.
          - Documentation is also huge. We have a robust document store online - both in Google docs and Slack, as well as our internal documentation tooling, and we try to document absolutely everything.
          - Favorite Slack quick tip: Slack can sceduale messages to be sent at a later time. This is a great way to ensure that your message is sent at a time that is convenient for your recipient, and it also allows you to be more thoughtful about what you say, and how you say it.
        - Open and Inclusive Communication:
          - Our second solution is open and inclusive communication. We have a culture of open communication, where everyone is encouraged to speak up and share their ideas. We also have a culture of inclusion, where everyone is encouraged to participate in discussions and decision-making processes.
            - We have strong open-door policies. Not just team level managers, but also department level managers, and even C-level executives are open and available to talk to anyone at any time.
        - Emphasis on Team Building:
          - We have a number of initiatives in place to build strong team bonds, including online monthly connections where we simply get to know each other, team outings, and team retreats. These initiatives help us build trust and camaraderie, which is essential for effective collaboration.
          - We have bi-yearly hackathons, were anyone can pitch an idea, and anyone can participate. No one is told what to work on, and no one is told what not to work on. This allows us to be creative, and to think outside the box, and also allows us to work with people we might not normally work with.
          - Despite being a fully remote organization, Grafana understands how import in-person connections are. We have opportunities throughout the year to connect in person, share a meal, and get to know each other more deeply. We connect, we drink, we eat, we play. It's magical.





Content Chunk 2: "The Power of Flexibility: Balancing Work-Life Harmony in a Remote Work Environment" (15 minutes)

- Point 1: Remote Work and Flexibility
  - Concepts
    - Introduce the concept of remote work and asynchronous communication as the foundation for flexibility.
    - Explain how Grafana Labs allows employees to design their workdays to better suit their personal lives and how this aligns with the company's values.
    - Share statistics or stories that illustrate the positive impact of flexible work arrangements on employee satisfaction and productivity.
  - Content
    - Remote Work and Asynchronous Communication:
      - Remote work isn't just a trend; it's a fundamental shift in the way work is approached. Grafana Labs, like many forward-thinking organizations, has embraced remote work as a core element of its culture.
    - Aligning with Company Values:
      - Grafana Labs prioritizes flexibility as part of its core values. The company's leadership recognizes that the traditional 9-to-5 office model doesn't fit everyone's lifestyle or work style. As a result, the company encourages employees to design their workdays in a way that aligns with their personal lives and needs.
        - My schedule, for example, is built around my family. I have 2 young children, and so I start my work day early - around 5:50-6am. I work from 5:50-7:15, 8:15-noon, 1-3, 3:30-5. This allows me to be there for my kids in the morning, and to be there for them in the afternoon. It also allows me to be there for my wife, who is a acupunturist, and who has a very different schedule than I do.

- Point 2: Personal Well-Being and Self-Care
  - Concepts
    - Emphasize the importance of self-care and personal well-being in a remote work environment.
    - Discuss the mental and physical health benefits of flexible work and the ability to tailor one's schedule to accommodate personal needs.
    - Share resources and practices that Grafana Labs provides to help employees prioritize self-care and maintain their well-being while working remotely.
  - Content
    - Point 2: Personal Well-Being and Self-Care
      - Self-care isn't an indulgence; it's an essential aspect of maintaining a healthy and productive work life. Grafana Labs recognizes that employees who feel supported in their personal well-being are more likely to perform at their best professionally.
        - I feel lucky everyday that I landed at Grafana. My team is awesome, the product is awesome, and the company is awesome. I feel supported in my personal well-being, and I feel like I'm able to perform at my best professionally. I'm able to be there for my family, and I'm able to be there for my team. I'm able to be there for my wife, and I'm able to be there for my clients. I'm able to be there for myself, and I'm able to be there for my company.