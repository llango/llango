<p align="center">
  <img src="banner.png" alt="Banner"/>
</p>

有关我的介绍如下:

```python
from dataclasses import dataclass
from typing import Sequence


@dataclass(frozen=True)
class Portfolio:
    en_name: str = 'Rontom'
    cn_name: 'Congliang Luo'
    location: str = 'Hunan·Changsha'
    profile: str = 'NLPer, Python Developer, Frontend Development'
    experience: str = '10+ years'
    website: str = 'http://www.llango.com'
    hobbies: Sequence[str] = 'Bike', 'Read', 'open source', 'and so on'


@dataclass(frozen=True)
class Skills:
    languages: Sequence[str] = 'Python', 'JavaScript', 'Shell'
    operation_systems: Sequence[str] = 'linux', 'Mac', 'Window'
    web_frameworks: Sequence[str] = 'flask', 'django', 'vue.js', 'react.js', 'bootstrap', 'and so on' 
    code_quality: Sequence[str] = 'flake8', 'mypy', 'pylint', 'black', 'pydocstyle'
    devops: Sequence[str] = 'jenkins', 'travis', 'docker'
    version_control: Sequence[str] = 'git', 'svn'
    ongoing: Sequence[str] = 'developing own web framework'


@dataclass(frozen=True)
class Social:
    wechat: str = 'rontomai'
    github: str = 'https://www.github.com/llango'
    portfolio: str = 'http://hackerlang.me'
    email: str = 'rontomai@gmail.com' 
 ````
