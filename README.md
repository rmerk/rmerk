### Hi there 👋
https://img.shields.io/badge/Email-ryan@ryanchoi.dev-orange?style=for-the-badge&logo=maildotru&link=mailto:ryan@ryanchoi.dev 
<!--
**rmerk/rmerk** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

-->

```php
<?php

namespace RyanChoi;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Total Expert',
                'position' => 'Senior Software Engineer'        
            ]
        ];
    }

    public function getLeveragedSkills(): array
    {
        return [
            Php::class,
            PhpUnit::class,
            Javascript::class,
            Vuejs::class,
            Vuex::class,
            Jquery::class,
            Html::class,
            Css::class,
            Sass::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Currently learning React to build upon my known modern JavaScript frameworks.';
    }
}
```
