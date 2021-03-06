# Homework Week 3

Base your week 3 homework on the result of week 2.

When you are done, update your PR from week 2.

## Outline

Extend your todo list app with the ability to add new todo items and remove existing ones.

Create an add button and a text input. When the add button is clicked a new todo item is created with the given
description. Create also a remove button, which when clicked it should remove the todo item from the list.

A mockup of the end result is the following:

```
Todo List

Enter description: [           ] [Add]

* [x] Get out of bed [remove]
* [ ] Brush teeth [remove]
* [ ] Eat breakfast [remove]
```

All the state should live in the `App` component. No state should be in the other components. Before you start draw
a mockup and identify the components with colours.

As a bonus, have the option to edit a todo item description. A mockup of the end result in this case should like
the following:

```
Todo List

Enter description: [           ] [Add]

* [x] Get out of bed [edit] [remove]
* [ ] Brush teeth [edit] [remove]
* [ ] Eat breakfast [edit] [remove]
```

And when edit is clicked in one of the components:

```
Todo List

Enter description: [           ] [Add]

* [x] [Get out of bed    ] [update] [cancel] [remove]
* [ ] Brush teeth [remove]
* [ ] Eat breakfast [remove]
```

## Scoring

You will be scored on:

- Correct functionality
- Code organisation
- Cleanliness of code
