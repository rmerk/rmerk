![githubBanner](https://user-images.githubusercontent.com/4576425/123686375-595b4a80-d815-11eb-8ed5-a0934162e93d.jpg)

![Image for email](https://img.shields.io/badge/Email-ryan@ryanchoi.dev-orange?style=for-the-badge&logo=maildotru&link=mailto:ryan@ryanchoi.dev)
![Image for website](https://img.shields.io/badge/Personal%20Site-ryanchoi.dev-blue?style=for-the-badge&logo=curl&link=https://ryanchoi.dev)

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
                'position' => 'Senior Software Engineer',
                'years_employed' => 5
            ]
        ];
    }

    public function getLeveragedSkills(): array
    {
        return [
            'PHP',
            'PHPUnit',
            'JavaScript',
            'Vue.js',
            'Vuex',
            'Vue-Jest',
            'jQuery',
            'HTML5',
            'CSS3',
            'SASS',
            'Webpack'
        ];
    }

    public function getCurrentlyLearning(): string
    {
        return "I'm Currently learning React to build upon my known modern JavaScript frameworks.";
    }
}
```
