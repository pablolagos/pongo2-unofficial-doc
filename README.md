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
