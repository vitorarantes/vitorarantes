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
            NativeScript::class,
            TailwindCss::class,
            Docker::class,
        ];
    }

    public function getAge()
    {
        return 24;
    }
    
    public function getFutureGoal()
    {
        return 'Contribute to open source.';
    }
}
```
