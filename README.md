# Приложение «Мобильный хоспис»
## Правила именования в проекте (*для разрабочиков*):
* Правила именования пакетов и классов:

Имена пакетов всегда в нижнем регистре и без подчеркивания. Использование многословных имен обычно не рекомендуется, но если действительно нужно использовать несколько слов, можно просто объединить их вместе или использовать camelCase.

  Пример:
  * `repository
  `
  * ` viewModel
  `


Имена классов и объектов начинаются с заглавной буквы и используют PascalCase:

  Пример:
  * `open class DeclarationProcessor { /*...*/ }
  `
  * `object EmptyDeclarationProcessor : DeclarationProcessor() { /*...*/ }
  `

Имена функций, свойств и локальных переменных начинаются со строчной буквы и используют camelCase без подчеркивания:
  Пример:
  * `fun processDeclarations() { /*...*/ }`
  * `var declarationCount = 1`


Для нейминга в xml *используется Snake Case*. Завершающим элементом в названии должен идти тип view (полностью).
  Больше ничего лишнего не добавляется:
  
  Пример:
    * `
          <ImageView
          android:id="@+id/line_divider_image_view"/>
    `
    * `
    <string name="date_not_set">Date not set</string>
    `
    * `
    <color name="light_grey">#F5F5F5</color>
    `
