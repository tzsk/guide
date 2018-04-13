# Coding Standards & Best Practices

## PHP Code Sniffer

First of all I want to discuss about the code styling. By styling I don't mean patterns or rules or principals it's just visual styling. For that purpose only, I have mentioned `php cs fixer` as an Extension to install.

With the help of `PHP Code Sniffer` we can properly decorate the code for everybody to read. PHP CS Fixer is freely available as a composer library. Install that and configure with VSCode. Now on every save it will format your file with the proper styling guidelines.

## SOLID Principles

This is the one big rule of any programming language. But everyone not always able to follow it to the dot but I will encourage you to use it as much as possible.

The principles are:

1. `Single` Responsibility Principle.
2. `Open/Closed` Principle.
3. `Liskov` Substitution Principle.
4. `Interface` Seggragation Principle.
5. `Dependency` Inversion Principle.

I would highly recommend you to read about it. Watch tutorials in various platforms. If you require resources I will be happy to help.

## Various Rules

There are countless patterns one can use for programming. Most of them everybody uses withoug knowing that they are using them. I will list few of them here and will highly recommend to see [Clean Code PHP](https://github.com/jupeter/clean-code-php) on Github.

1. Use readable and self sefice naming conventions.
2. Avoid Nesting too deeply. Exit first.
3. Avoid redundant naming or unnecessary context.
4. Use no grater than 3 arguments in a function or method.
5. Avoid using flags as function arguments.
6. Try encapsulating conditionals.
7. Avoid Type Checking.
8. Clean unnecessary code.
9. If you want, you can use Fluent interface.
10. Use getters and setters more.

These are the few rules, if you want you can read the full list with proper examples in the above github link.


## Various Patterns

There are also a lot of programming patterns available. But few of them I really like are:

1. The Decorator Pattern.
2. Making use of Adapters.
3. Template Method Pattern.
5. The Stratagy Design Pattern.
6. Chain of Responsibility Pattern.
7. The Specification Pattern.
8. Observer Pattern.

Again, this is huge. I don't expect someone to code as per the rule book. But whenever you can you just keep these patterns in mind.


## Laravel Specific

There are some laravel specific things we can to quite easily and make our code much readable and manageable. Few of them are.

1. Consider `Form Objects`
2. Consider `Use Case Classes`
3. Consider `Laravel Events`
4. Use `Traits` & `Fragments`
5. Use `Value Objects`
6. Consider `Normalization`
7. Consider `View Models`
8. Make use of `7 Resourceful Methods`
9. Consider `Query Scopes` & `Query Objects`
10. Always have `Database Migrations` & `Seeds` in place.

There are also many others. But staying true to all of them is very hard and time consuming. But we should strive to get there.