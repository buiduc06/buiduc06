```
<?php

namespace BuiNgocDuc;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'VietName',
                'position' => 'Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Typescript::class,
            Laravel::class,
            Lumen::class,
            Vuejs::class,
            Angular::class,
            React::class,
            Nodejs::class,
            HtmlCss:class,
            Elasticsearch::class,
            Aws::class,
            BA::class
        ];
    }
    
    public function getFutureGoal(): string
    {
        return 'To become a professional Technical Project Manager.';
    }
}
```
