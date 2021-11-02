Hello, 大家好，我是一个Python工程师， 主要写写Python代码，不时写写前端代码。
<p align="center">
  <img src="banner.png" alt="Banner"/>
</p>

```python
from dataclasses import dataclass
from typing import Sequence


@dataclass(frozen=True)
class Portfolio:
    en_name: str = 'Rontom'
    cn_name: '罗从良'
    location: str = '湖南·长沙'
    profile: str = 'NLPer, Python Developer, Frontend Development'
    experience: str = '10+ years'
    website: str = 'http://www.llango.com'
    hobbies: Sequence[str] = 'Bike', 'Read', 'open source', 'and so on'


@dataclass(frozen=True)
class Skills:
    languages: Sequence[str] = 'Python', 'JavaScript', 'Shell'
    operation_systems: Sequence[str] = 'linux', 'Mac', 'Window'
    web_frameworks: Sequence[str] = 'flask', 'django','django rest-framework', 'vue.js', 'react.js', 'bootstrap', 'and so on' 
    code_quality: Sequence[str] = 'flake8', 'mypy', 'pylint', 'black', 'pydocstyle'
    devops: Sequence[str] = 'jenkins', 'travis', 'docker'
    version_control: Sequence[str] = 'git', 'svn'
    ongoing: Sequence[str] = 'developing own web framework'


@dataclass(frozen=True)
class Social:
    wechat: str = 'rontomai'
    github: str = 'https://www.github.com/llango'
    portfolio: str = 'http://hackerlang.me'
    email: str = 'labankiplagat81@gmail.com' 
 ````
