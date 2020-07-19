<h1 align="center">Hi 👋, I'm Vitor</h1>

<h3 align="center">A passionate software developer from Portugal and currently living in Luxembourg</h3>

<p align="left">
    <img src="https://konpa.github.io/devicon/devicon.git/icons/php/php-original.svg" alt="php" width="20" height="20"/>
    <img src="https://konpa.github.io/devicon/devicon.git/icons/laravel/laravel-plain-wordmark.svg" alt="laravel" width="20" height="20"/> 
    <img src="https://konpa.github.io/devicon/devicon.git/icons/javascript/javascript-original.svg" alt="javascript" width="20" height="20"/> 
    <img src="https://konpa.github.io/devicon/devicon.git/icons/vuejs/vuejs-original-wordmark.svg" alt="vuejs" width="20" height="20"/>
    <img src="https://konpa.github.io/devicon/devicon.git/icons/docker/docker-original-wordmark.svg" alt="docker" width="20" height="20"/> 
    <img src="https://konpa.github.io/devicon/devicon.git/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="20" height="20"/> 
</p>

```php
<?php

namespace VitorArantes;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'eSST Luxembourg',
                'position' => 'Full Stack Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            VueJs::class,
            NuxtJs::class,
            Docker::class,
        ];
    }

    public function getAge()
    {
        return 24;
    }
}
```

<p align="left"> 
    <img src="https://komarev.com/ghpvc/?username=vitorarantes" alt="vitorarantes" />
</p>

<p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=vitorarantes&show_icons=true" alt="vitorarantes" />
</p>
