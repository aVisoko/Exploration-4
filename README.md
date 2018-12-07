# Exploration-4

## This is my last exploration for this class<br>for this exploration I decided to look into Twig<br>a template framework for php

Twig's main website can be found [here](https://twig.symfony.com)

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
   
## Job Posting

Veterans United is seeking a Web Developer in our Marketing department to build websites, use web analytics and work closely with the Creative team. This position will not be originating loans.

Responsibilities:
Build interactive websites using Javascript, PHP, Twig, and MySQL.
Act as a technical resource for the creative marketing team.
Use regular expressions to help manage our multivariate testing systems(a/b testing).
Utilize and implement various web analytics tools to provide useful statistics and insights into how our websites work.
Pair with designers and other developers to learn and grow.
Necessary Skills:
Excellent troubleshooting capabilities.
Aptitude to learn new technology.
Strong interpersonal communication skills (written and verbal).
Excel in fast-paced, results-oriented environment.
Job Requirements:
3+ years of experience in web development or similar software development roles.
Proficient in jQuery or other javascript framework.
Proficient in PHP.
Familiarity with LAMP stack.
Experience with Jenkins, Perforce, Git, and other version control, continuous integration and delivery tools.
Veterans United is proud to be an EOE/ADA and Military Friendly employer 

To apply to this job, click Apply Now


Link to the posting is [here](https://www.glassdoor.com/Job/jobs.htm?suggestCount=0&suggestChosen=true&clickSource=searchBtn&typedKeyword=web+&sc.keyword=Front+End+Web+Developer&locT=C&locId=1130886&jobType=)
