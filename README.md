<a href="https://jekyll-themes.com">
<img src="https://img.shields.io/badge/featured%20on-JT-red.svg" height="20" alt="Jekyll Themes Shield" >
</a>

Other sections example:

``` yaml

projects:
    title: Projects
    intro: >
      You can list your side projects in this
      section. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      Vestibulum et ligula in nunc bibendum fringilla a eu lectus.
    assignments:
      - title: Velocity
        link: "#hook"
        tagline: "A responsive website template designed to help startups promote, market and sell their products."

      - title: DevStudio
        link: "#"
        tagline: "A responsive website template designed to help web developers/designers market their services."

      - title: Tempo
        link: "#"
        tagline: "A responsive website template designed to help startups promote their products or services and to attract users &amp; investors"

      - title: Atom
        link: "#"
        tagline: "A comprehensive website template solution for startups/developers to market their mobile apps."

      - title: Delta
        link: "#"
        tagline: "A responsive Bootstrap one page theme designed to help app developers promote their mobile apps"

oss:
    title: OSS Contributions
    intro: >
      You can list your open source software contributions in this
      section. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      Vestibulum et ligula in nunc bibendum fringilla a eu lectus.
    contributions:
      - title: Tempo
        link: "#"
        tagline: "A responsive website template designed to help startups promote their products or services and to attract users &amp; investors"

      - title: Atom
        link: "#"
        tagline: "A comprehensive website template solution for startups/developers to market their mobile apps."

      - title: Delta
        link: "#"
        tagline: "A responsive Bootstrap one page theme designed to help app developers promote their mobile apps"

publications:
    title: Publications
    intro: |
      You can list your publications in this section. Lorem ipsum dolor sit
      amet, consectetur adipiscing elit. Vestibulum et ligula in nunc
      bibendum fringilla a eu lectus.
    papers:
      - title: The Art of Computer Programming
        link: "#"
        authors: Donald E. Knuth
        conference: Addison-Wesley, 1968

      - title: "Genetic Programming III: Darwinian Invention &amp; Problem Solving"
        link: "#"
        authors: Koza, J.R., Andre, D., Bennett, F.H., Keane, M.A.
        conference: "Morgan Kaufmann Publishers Inc., San Francisco, CA, USA, 1st edn. (1999)"

      - title: A syntax directed compiler for Algol 60
        link: "#"
        authors: Edgar T. Irons
        conference: "Comm. ACM 4 (1961), 51–55"

certifications:
  title: cources & workshops
  list:
    - name: CV Builder
      start: 2020
      end: 2021
      organization: Microsoft
      credentialid: 111-222
      credentialurl: www.google.com
      credentialname: Google
      details: |
        Details about cert. Lorem ipsum dolor sit amet, consectetur
        adipiscing elit.
        Nullam eget orci purus. Nullam ultrices neque nibh.
        Aenean fermentum, felis vulputate suscipit accumsan,
        sem enim bibendum augue, sed convallis arcu lacus at dui.
        Pellentesque et nibh suscipit, vestibulum turpis eu, semper tortor.
        Praesent felis nibh, eleifend id eleifend id, dictum id enim.
        Praesent venenatis erat non augue suscipit consectetur.

        Second paragraph. Sed eleifend enim ante, vitae efficitur purus
        fringilla vel. Ut euismod, sem sed vulputate venenatis,
        justo diam viverra velit, sed rhoncus leo leo eu justo.
        Suspendisse placerat risus ante, sed porta nisi blandit at.
    - name: Git learning
      start: 2019
      end:
      organization: Microsoft
      credentialid: 111-222
      credentialurl: www.github.com
      credentialname: Github
      details: |
        Older certification. Lorem ipsum dolor sit amet, consectetur
        adipiscing elit.
        Nullam eget orci purus. Nullam ultrices neque nibh.
        Aenean fermentum, felis vulputate suscipit accumsan,
        sem enim bibendum augue, sed convallis arcu lacus at dui.
        Pellentesque et nibh suscipit, vestibulum turpis eu, semper tortor.
        Praesent felis nibh, eleifend id eleifend id, dictum id enim.
        Praesent venenatis erat non augue suscipit consectetur.
```

# Orbit
> This theme is designed by Xiaoying Riley at [3rd Wave Media](http://themes.3rdwavemedia.com/).
> Visit [her website](http://themes.3rdwavemedia.com/) for more themes.

I have made this into a Jekyll Theme. Checkout the live demo [here](https://online-cv.webjeda.com).

<table>
  <tr>
    <th>Desktop</th>
    <th>Mobile</th>
  </tr>
  <tr>
    <td>
        <img src="https://online-cv.webjeda.com/assets/images/desktop.png?raw=true" width="600"/>
    </td>
    <td>
        <img src="https://online-cv.webjeda.com/assets/images/mobile.png?raw=true" width="250"/>
    </td>
  </tr>
</table>

## Installation

* [Fork](https://github.com/sharu725/online-cv/fork) the repository;
* Go to settings and set master branch as Github Pages source;
* Your new site should be ready at `https://<username>.github.io/online-cv/`;
* Printable version of the site can be found at `https://<username>.github.io/online-cv/print`. Use a third party link https://pdflayer.com/, https://www.web2pdfconvert.com/ etc to get the printable PDF.

Change all the details from one place: `_data/data.yml`.

### To preview/edit locally with docker

```sh
docker-compose up
```

*docker-compose.yml* file is used to create a container that is reachable under <http://localhost:4000>.
Changes *_data/data.yml* will be visible after a while.

### Local machine

* Get the repo into your machine 

```bash
git clone https://github.com/sharu725/online-cv.git
```

* Install required ruby gems

```bash
bundle install
```

* Serve the site locally

```bash
bundle exec jekyll serve
```

* Navigate to `http://localhost:4000`


## Skins

There are 6 color schemes available:

| Blue | Turquoise | Green |
|---------|---------|---------|
| <img src="https://online-cv.webjeda.com/assets/images/blue.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/turquoise.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/green.jpg" width="300"/> |

| Berry | Orange | Ceramic |
|---------|---------|---------|
| <img src="https://online-cv.webjeda.com/assets/images/berry.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/orange.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/ceramic.jpg" width="300"/> |

## Credits

Thanks to [Nelson Estevão](https://github.com/nelsonmestevao) for all the [contributions](https://github.com/sharu725/online-cv/commits?author=nelsonmestevao).

Thanks to [t-h-e(sfrost)](https://github.com/t-h-e) for all the [contributions](https://github.com/sharu725/online-cv/commits?author=t-h-e).

Check out for more themes: [**Jekyll Themes**](http://jekyll-themes.com).

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=sharu725/online-cv&type=Date)](https://star-history.com/#sharu725/online-cv&Date)

