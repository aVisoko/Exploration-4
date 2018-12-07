# Exploration-4

## This is my last exploration for this class<br>for this exploration I decided to look into Twig<br>a template framework for php

Concise: The PHP language is verbose and becomes ridiculously verbose when it comes to output escaping:

<?php echo $var ?>
<?php echo htmlspecialchars($var, ENT_QUOTES, 'UTF-8') ?>
In comparison, Twig has a very concise syntax, which make templates more readable:

{{ var }}
{{ var|escape }}
{{ var|e }}         {# shortcut to escape a variable #}
Template oriented syntax: Twig has shortcuts for common patterns, like having a default text displayed when you iterate over an empty array:

{% for user in users %}
    * {{ user.name }}
{% else %}
    No users have been found.
{% endfor %}
Full Featured: Twig supports everything you need to build powerful templates with ease: multiple inheritance, blocks, automatic output-escaping, and much more:

{% extends "layout.html" %}

{% block content %}
    Content of the page...
{% endblock %}
Easy to learn: The syntax is easy to learn and has been optimized to allow web designers to get their job done fast without getting in their way.
