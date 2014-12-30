#Yii2-universal-analytics

Forked from [TagPlanet/yii-analytics-ua](https://github.com/TagPlanet/yii-analytics-ua). Modified to work with Yii2 Framework.

##Installation
Install this extension via [composer](http://getcomposer.org/download). Add this line to your project’s composer.json

```php
“ethanfrogers/yii2-universal-analytics” : “dev-master”
```

##Setup

###Configuration

```php
//add this line in config/main-local.php for the appropriate application
$config[‘components’][] = [
    ‘googleAnalytics’ => [
        ‘class’ => ‘ethanfrogers\AnalyticsUA\UniversalAnalytics’
    ]
]
```

###Usage

```php
//Within your layout
Yii::$app->googleAnalytics->render();
```

For additional configuration options see [TagPlanet/yii-analytics-ua](https://github.com/TagPlanet/yii-analytics-ua).




