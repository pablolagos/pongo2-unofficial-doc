# pongo2-unofficial-doc
Pongo2 is a complete templating system but lacks sufficient documentation. This file contains unofficial documentation obtained from direct observation of the source code.

## Operators

Operator | Description
---------|-------------
and - &&   |
or - \|\|    |
! - not |
<=       |
\>=       |
== |
\>  |
<  |
!= - <\> |
in |

Operator | Description
---------|------------
\+ |
\- |
\* |
/ |
% |

## Tags

Tag | Description
----|------------
{% autoescape %} ...  {% endautoescape %} |
{% block NAME %} ... {% endblock %} |
{% comment %} ... {% endcomment %} |
{% cycle "test1" "test2"\|variable \[as NAME] %} | <a href="https://docs.djangoproject.com/en/3.2/ref/templates/builtins/#cycle" target="_blank" >Read in Django documentation</a>
{% extends FILENAME %} | 
{% filter FILTERS %}...{% endfilter %} | [Read in Django documentation](https://docs.djangoproject.com/en/3.2/ref/templates/builtins/#filter)
{% firstof LIST %} | [Read in Django documentation](https://docs.djangoproject.com/en/3.2/ref/templates/builtins/#firstof)
{% for \[key,] value in list \[reversed\|sorted] %}<br> ... <br>{% empty %}<br> ... <br>{% endfor %} | [Read in Django documentation](https://docs.djangoproject.com/en/3.2/ref/templates/builtins/#for)
