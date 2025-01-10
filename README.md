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
![Code Time](http://img.shields.io/badge/Code%20Time-546%20hrs%2028%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-6.0%20million%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 📦 ? Used in GitHub's Storage 
 > 
> 🚫 Not Opted to Hire
 > 
> 📜 52 Public Repositories 
 > 
> 🔑 0 Private Repositories 
 > 
**I'm an Early 🐤** 

```text
🌞 Morning                302 commits         ████░░░░░░░░░░░░░░░░░░░░░   17.23 % 
🌆 Daytime                584 commits         ████████░░░░░░░░░░░░░░░░░   33.31 % 
🌃 Evening                382 commits         █████░░░░░░░░░░░░░░░░░░░░   21.79 % 
🌙 Night                  485 commits         ███████░░░░░░░░░░░░░░░░░░   27.67 % 
```
📅 **I'm Most Productive on Friday** 

```text
Monday                   258 commits         ████░░░░░░░░░░░░░░░░░░░░░   14.72 % 
Tuesday                  186 commits         ███░░░░░░░░░░░░░░░░░░░░░░   10.61 % 
Wednesday                263 commits         ████░░░░░░░░░░░░░░░░░░░░░   15.00 % 
Thursday                 289 commits         ████░░░░░░░░░░░░░░░░░░░░░   16.49 % 
Friday                   298 commits         ████░░░░░░░░░░░░░░░░░░░░░   17.00 % 
Saturday                 172 commits         ██░░░░░░░░░░░░░░░░░░░░░░░   09.81 % 
Sunday                   287 commits         ████░░░░░░░░░░░░░░░░░░░░░   16.37 % 
```


📊 **This Week I Spent My Time On** 

```text
🕑︎ Time Zone: Africa/Douala

💬 Programming Languages: 
Other                    3 hrs 4 mins        ███████████████░░░░░░░░░░   59.85 % 
Rust                     1 hr 12 mins        ██████░░░░░░░░░░░░░░░░░░░   23.60 % 
TOML                     16 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   05.22 % 
tmux                     11 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   03.83 % 
Bash                     11 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   03.69 % 

🔥 Editors: 
Chrome                   3 hrs 27 mins       █████████████████░░░░░░░░   67.16 % 
Sublime Text             1 hr 41 mins        ████████░░░░░░░░░░░░░░░░░   32.84 % 

🐱‍💻 Projects: 
PyExe-Forge              2 hrs 23 mins       ████████████░░░░░░░░░░░░░   46.47 % 
sbook_core               1 hr 31 mins        ███████░░░░░░░░░░░░░░░░░░   29.57 % 
rust_guess_game          52 mins             ████░░░░░░░░░░░░░░░░░░░░░   17.15 % 
Unknown Project          21 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   06.81 % 

💻 Operating System: 
Linux                    5 hrs 8 mins        █████████████████████████   100.00 % 
```

**I Mostly Code in Python** 

```text
Python                   22 repos            █████████████░░░░░░░░░░░░   53.66 % 
C                        2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   04.88 % 
CSS                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   04.88 % 
C++                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   04.88 % 
Rust                     1 repo              █░░░░░░░░░░░░░░░░░░░░░░░░   02.44 % 
```



**Timeline**

![Lines of Code chart](https://raw.githubusercontent.com/ken-morel/ken-morel/main/assets/bar_graph.png)


 Last Updated on 10/01/2025 18:45:22 UTC
<!--END_SECTION:waka-->
<!--### I call you number:
![Visitor Count](https://profile-counter.glitch.me/{ken-morel}/count.svg)
![](https://komarev.com/ghpvc/?username=ken-morel&color=553300&style=flat&label=views)
-->
> If we pull together and commit ourselves, then we can push through anything.
— Mona the Octocat :octocat:
