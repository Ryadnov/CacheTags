Пример использование тегов

// Добавление записи с тегами teg1 и tag2
Yii::app()->cache->set($key, $value, 0, new ECacheTagsDependency('tag1', 'tag2'));

// Очистка кеша по тегу tag2
Yii::app()->cache->clear('tag2');


-----

Первоначальный код и идея: http://korzh.net/2011-04-tegirovanie-kesha-v-yii-framework-eto-ne-bolno.html
