- 👋 Hi, I’m @lfarizav
- 👀 I’m a Kubestronaut interested in hybrid-cloud cloud-native RAN, orquestration and management. Working on a personal project migrating private cellular networks with SMS, IPTV, VoLTE, data from docker compose to Helm
- 🌱 I’m currently learning Kubernetes, Helm, CI/CD with FluxCD and Tekton
- 💞️ I’m looking to collaborate on Next Generation Cellular Networks and Open RAN
- 👀 I'm improving my AI skills to integrate them into infrastructure deployment for cellular networks
- 📫 How to reach me: my emails are lfarizav@unal.edu.co lfarizav@gmail.com

<!---
lfarizav/lfarizav is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
