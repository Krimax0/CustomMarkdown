# Заголовки

```md
Lorem ipsum Пример

#### 4 Lorem ipsum Пример
### 3 Lorem ipsum Пример
## 2 Lorem ipsum Пример
# 1 Lorem ipsum Пример
```

<img src="https://i.imgur.com/6NBJRxN.png" />

# Разбивка на колонки

В GridBlocks можно поместить все что душе угодно, от изображений до других компонент описанных ниже
```jsx
<GridBlocks>
  <div>Правый блок</div>
  <div>Левый блок</div>
</GridBlocks>
```

<img src="https://i.imgur.com/R7tz8bX.png" />

## Можно изменить количество колонок

Количество указывается в фигурных скобках, по умолчанию 2 колонки
```jsx
<GridBlocks col={3}>
  <div>Первая колонка</div>
  <div>Вторая колонка</div>
  <div>Третья колонка</div>
</GridBlocks>
```
<img src="https://i.imgur.com/RfFQ4MU.png" />

## Блоки

```jsx
<BackBlock
  title="Заголовок"
>
  - Пример
  - Пример два
</BackBlock>
```
<img src="https://i.imgur.com/z7JuGzZ.png" />

### Применение BackBlock

```jsx

<GridBlocks>
  <BackBlock
    title="Заголовок"
  >
    - Пример
    - Пример два
  </BackBlock>
  <BackBlock
    title="Заголовок"
  >
    - Пример
    - Пример два
  </BackBlock>
</GridBlocks>
```

<img src="https://i.imgur.com/79ckIiO.png" />


# HastTag Навигация по странице
Работает только на wiki странице, не рекомендую использовать вне страниц для wiki

Пример тега
```jsx
<HashTag id="mb1" title = "What is MetaBrushes?" group="instrument" />
```
Входные параметры:
- Наличие id ОБЯЗАТЕЛЬНО- может быть как строчным значением так и числом(Число указывается в фигурных скобках{1})
- Title - Название данного тега, без него тег отображаться будет с невидимым именем
- Group - опциональный параметр, необходим для создании группы,
  - Будет работать только если сущесвует БОЛЬШЕ 1 тега с данной группой. Если в группе меньше 2 тегов, тег будет отображаться как обычно
  - 

![image](https://github.com/user-attachments/assets/12155f8e-de9d-4fcf-b938-540a4cdf1a28)
