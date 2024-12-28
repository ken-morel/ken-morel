![My logo](ama.svg)

Hi I am @ken-morel a pythonista looking for collaborators, prices and project.
I like coding, as tells my [wakatime](https://wakatime.com/@kenmorel), but I also like being able to help
other developers or users with self made or team made tools.

I currently work on efus. Something I aim to help better markup UI components(at least better than XML) with builtin reactivity just for you to extend.
currently looks like...
**Page.efus**
```julia
using taktk.components:Window, Frame
using tkinter.constants

Window
    Frame padding=10px pos:pack=true
        Label  text=&label_text pos:pack=true
        Button command=(click)  pos:pack=true
```
... and python code...
```python
from efus import Comp2nent

class Page(Comp2nent):
    label_text = "label "
    def click(self):
        self['label_text'] += ">"
        self.namespace.update()

component = Page.make()
root = component.render()
root.mainloop()
# or Page.make().render().mainloop()
```

... Still bulky, working on it, tomorrow.

## tools and languages 📦

![](https://skillicons.dev/icons?i=py,sublime,ubuntu,regex,svg,c,sass,html,js,discord,git,arduino,github,githubactions,gmail,stackoverflow,svelte,md,bash,powershell,mongodb,nodejs,npm&perline=3)

## stack overflow

I sometimes browse stack overflow questions, and try editing or answerring what I can

[![](https://stackoverflow.com/users/flair/22719308.png?theme=dark&cache=300#gh-dark-mode-only)](https://stackoverflow.com/users/22719308/ken-morel#gh-dark-mode-only)
[![](https://stackoverflow.com/users/flair/22719308.png?theme=light&cache=300#gh-light-mode-only)](https://stackoverflow.com/users/22719308/ken-morel#gh-light-mode-only)
<!--## gists
[![Gist Card-Dark](https://ken-morel-stats.vercel.app/api/gist?id=aa1e2aab3af5162a7fc10540d4c6b014&theme=nord&bg_color=00114455&hide_border=true&border_radius=20#gh-dark-mode-only)](https://gist.github.com/ken-morel/aa1e2aab3af5162a7fc10540d4c6b014#gh-dark-mode-only)
[![Gist Card-Light](https://ken-morel-stats.vercel.app/api/gist?id=aa1e2aab3af5162a7fc10540d4c6b014&theme=view&bg_color=aabbff33&hide_border=true&border_radius=20#gh-light-mode-only)](https://gist.github.com/ken-morel/aa1e2aab3af5162a7fc10540d4c6b014#gh-light-mode-only)
-->

[![Readme Card-Dark](https://github-readme-stats.vercel.app/api/pin/?username=ken-morel&repo=gama&theme=nord&bg_color=55114455&hide_border=true&border_radius=20#gh-dark-mode-only)](https://github.com/ken-morel/pyoload#gh-dark-mode-only)
[![Readme Card-Light](https://github-readme-stats.vercel.app/api/pin/?username=ken-morel&repo=gama&theme=view&bg_color=ffaaee33&hide_border=true&border_radius=20#gh-light-mode-only)](https://github.com/ken-morel/pyoload#gh-light-mode-only)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=ken-morel&theme=monokai&bg_color=00554455&column=3&margin-w=10&no-frame=true)

### 🔝 Best meal
My best meal could be...

> An ubuntu flavoured beautifull python soup as that composed by wayland cooks.

Yeah, not good, workin' on it!

<!--![](https://github-contributor-stats.vercel.app/api?username=ken-morel&limit=5&theme=nord&combine_all_yearly_contributions=true&border_radius=20&bg_color=22441155&border_radius=20&hide_border=true)
<div align="center">
    <a href="https://github.com/ken-morel">
        <img src="https://github-readme-activity-graph.vercel.app/graph?username=ken-morel&theme=react-dark&hide_border=true&hide_title=false&area=true&custom_title=Total%20contribution%20graph%20in%20all%20repo" width="96%" alt="activity graph">
    </a>
</div>-->



## Coding
I code mostly in python and javascript and a little go.

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-544%20hrs%2026%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-12-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-6.0%20million%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 📦 ? Used in GitHub's Storage 
 > 
> 🚫 Not Opted to Hire
 > 
> 📜 49 Public Repositories 
 > 
> 🔑 0 Private Repositories 
 > 
**I'm an Early 🐤** 

```text
🌞 Morning                302 commits         ████░░░░░░░░░░░░░░░░░░░░░   17.27 % 
🌆 Daytime                583 commits         ████████░░░░░░░░░░░░░░░░░   33.33 % 
🌃 Evening                380 commits         █████░░░░░░░░░░░░░░░░░░░░   21.73 % 
🌙 Night                  484 commits         ███████░░░░░░░░░░░░░░░░░░   27.67 % 
```
📅 **I'm Most Productive on Friday** 

```text
Monday                   258 commits         ████░░░░░░░░░░░░░░░░░░░░░   14.75 % 
Tuesday                  186 commits         ███░░░░░░░░░░░░░░░░░░░░░░   10.63 % 
Wednesday                262 commits         ████░░░░░░░░░░░░░░░░░░░░░   14.98 % 
Thursday                 288 commits         ████░░░░░░░░░░░░░░░░░░░░░   16.47 % 
Friday                   298 commits         ████░░░░░░░░░░░░░░░░░░░░░   17.04 % 
Saturday                 172 commits         ██░░░░░░░░░░░░░░░░░░░░░░░   09.83 % 
Sunday                   285 commits         ████░░░░░░░░░░░░░░░░░░░░░   16.30 % 
```


📊 **This Week I Spent My Time On** 

```text
🕑︎ Time Zone: Africa/Douala

💬 Programming Languages: 
Other                    9 hrs 30 mins       ██████████░░░░░░░░░░░░░░░   41.88 % 
JavaScript               3 hrs 35 mins       ████░░░░░░░░░░░░░░░░░░░░░   15.82 % 
Svelte                   3 hrs 26 mins       ████░░░░░░░░░░░░░░░░░░░░░   15.13 % 
Sass                     2 hrs 56 mins       ███░░░░░░░░░░░░░░░░░░░░░░   12.96 % 
Python                   1 hr 42 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   07.54 % 

🔥 Editors: 
Sublime Text             11 hrs 41 mins      █████████████░░░░░░░░░░░░   51.52 % 
Chrome                   11 hrs              ████████████░░░░░░░░░░░░░   48.48 % 

🐱‍💻 Projects: 
svghai                   13 hrs 25 mins      ███████████████░░░░░░░░░░   59.13 % 
Efus                     4 hrs 37 mins       █████░░░░░░░░░░░░░░░░░░░░   20.35 % 
waybar                   1 hr 4 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   04.76 % 
ken-morel                43 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   03.22 % 
Sbook                    37 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   02.77 % 

💻 Operating System: 
Linux                    22 hrs 42 mins      █████████████████████████   100.00 % 
```

**I Mostly Code in Python** 

```text
Python                   21 repos            ██████████████░░░░░░░░░░░   55.26 % 
HTML                     5 repos             ███░░░░░░░░░░░░░░░░░░░░░░   13.16 % 
Go                       3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   07.89 % 
CSS                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   05.26 % 
C++                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   05.26 % 
```



**Timeline**

![Lines of Code chart](https://raw.githubusercontent.com/ken-morel/ken-morel/main/assets/bar_graph.png)


 Last Updated on 28/12/2024 18:42:11 UTC
<!--END_SECTION:waka-->
<!--### I call you number:
![Visitor Count](https://profile-counter.glitch.me/{ken-morel}/count.svg)
![](https://komarev.com/ghpvc/?username=ken-morel&color=553300&style=flat&label=views)
-->
> If we pull together and commit ourselves, then we can push through anything.
— Mona the Octocat :octocat:
