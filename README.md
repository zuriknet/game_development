#This is our README template file

###Take a look at the README.md file to see the different things we can do with just a markdown file.

Installation
============

Here is where we drop our instructions.

We can even drop in HTML. See below...

####Sub-Instructions
Step 1...
Step 2...
Step 3...

Cheat Sheet
===========

The Basics
----------

<table>
    <tr>
        <th scope="col">Trigger</th>
        <th scope="col">Name</th>
        <th scope="col">Code</th>
    </tr>
    <tr>
        <td><kbd>tv + TAB</kbd></td>
        <td>template variable</td>
        <td><code>{{ ... }}</code></td>
    </tr>
    <tr>
        <td><kbd># + TAB</kbd></td>
        <td>inline comment</td>
        <td><code>{# ... #}</code></td>
    </tr>
    <tr>
        <td><kbd>tt + TAB</kbd></td>
        <td>custom template tag</td>
        <td><code>{% ... %}</code></td>
    </tr>
</table>

Default Django Template Tags
----------------------------

<table>
    <tr>
        <th scope="col">Trigger</th>
        <th scope="col">Name</th>
        <th scope="col">Code</th>
    </tr>
    <tr>
        <td><kbd>autoescape + TAB</kbd></td>
        <td>autoescape off</td>
        <td><code>{% autoescape off %} ... {% endautoescape %}</code></td>
    </tr>
    <tr>
        <td><kbd>comment + TAB</kbd></td>
        <td>multiline comment</td>
        <td><code>{% comment %} ... {% endcomment %}</code></td>
    </tr>
    <tr>
        <td><kbd>block + TAB</kbd></td>
        <td>block</td>
        <td><code>{% block <i>foo</i>￼ %} ... {% endblock %}</code></td>
    </tr>
    <tr>
        <td><kbd>cache + TAB</kbd></td>
        <td>cache</td>
        <td><code>{% cache ￼<i>foo</i> %} ... {% endcache %}</code></td>
    </tr>
    <tr>
        <td><kbd>csrf + TAB</kbd></td>
        <td>csrf token</td>
        <td><code>{% csrf_token %}</code></td>
    </tr>
    <tr>
        <td><kbd>cycle + TAB</kbd></td>
        <td>cycle</td>
        <td><code>{% cycle %}</code></td>
    </tr>
    <tr>
        <td><kbd>debug + TAB</kbd></td>
        <td>debug</td>
        <td><code>{% debug %}</code></td>
    </tr>
    <tr>
        <td><kbd>else + TAB</kbd></td>
        <td>else</td>
        <td><code>{% else %}</code></td>
    </tr>
    <tr>
        <td><kbd>empty + TAB</kbd></td>
        <td>empty</td>
        <td><code>{% empty %}</code></td>
    </tr>
    <tr>
        <td><kbd>endblock + TAB</kbd></td>
        <td>endblock</td>
        <td><code>{% endblock %}</code></td>
    </tr>
    <tr>
        <td><kbd>endfor + TAB</kbd></td>
        <td>endfor</td>
        <td><code>{% endfor %}</code></td>
    </tr>
    <tr>
        <td><kbd>endif + TAB</kbd></td>
        <td>endif</td>
        <td><code>{% endif %}</code></td>
    </tr>
    <tr>
        <td><kbd>extends + TAB</kbd></td>
        <td>extends</td>
        <td><code>{% extends "￼<i>foo</i>.html" %}</code></td>
    </tr>
    <tr>
        <td><kbd>filter + TAB</kbd></td>
        <td>filter</td>
        <td><code>{% filter <i>foo</i>￼ %} ... {% endfilter %}</code></td>
    </tr>
    <tr>
        <td><kbd>firstof + TAB</kbd></td>
        <td>firstof</td>
        <td><code>{% firstof ￼<i>foo</i>￼ %}</code></td>
    </tr>
    <tr>
        <td><kbd>for + TAB</kbd></td>
        <td>for</td>
        <td><code>{% for ￼<i>foo</i>￼ %} ... {% endfor %}</code></td>
    </tr>
    <tr>
        <td><kbd>forempty + TAB</kbd></td>
        <td>for ... empty</td>
        <td><code>{% for ￼<i>foo</i>￼ %} ... {% empty %} ... {% endfor %}</code></td>
    </tr>
    <tr>
        <td><kbd>if + TAB</kbd></td>
        <td>if</td>
        <td><code>{% if <i>foo</i>￼￼ %} ... {% endif %}</code></td>
    </tr>
    <tr>
        <td><kbd>ifelse + TAB</kbd></td>
        <td>if ... else</td>
        <td><code>{% if <i>foo</i>￼￼￼ %} ... {% else %} ... {% endif %}</code></td>
    </tr>
    <tr>
        <td><kbd>ifchanged + TAB</kbd></td>
        <td>ifchanged</td>
        <td><code>{% ifchanged %} ￼... {% endifchanged %}</code></td>
    </tr>
    <tr>
        <td><kbd>ifequal + TAB</kbd></td>
        <td>ifequal</td>
        <td><code>{% ifequal <i>foo</i>￼￼￼￼ %} ... {% endifequal %}</code></td>
    </tr>
    <tr>
        <td><kbd>ifnotequal + TAB</kbd></td>
        <td>ifnotequal</td>
        <td><code>{% ifnotequal <i>foo</i>￼ %} ... {% endifnotequal %}</code></td>
    </tr>
    <tr>
        <td><kbd>include + TAB</kbd></td>
        <td>include</td>
        <td><code>{% include "<i>foo</i>￼.html" %}</code></td>
    </tr>
    <tr>
        <td><kbd>load + TAB</kbd></td>
        <td>load</td>
        <td><code>{% load <i>foo</i>￼ %}</code></td>
    </tr>
    <tr>
        <td><kbd>now + TAB</kbd></td>
        <td>now</td>
        <td><code>{% now "r" %}</code></td>
    </tr>
    <tr>
        <td><kbd>regroup + TAB</kbd></td>
        <td>regroup</td>
        <td><code>{% regroup ￼<i>foo</i> %}</code></td>
    </tr>
    <tr>
        <td><kbd>spaceless + TAB</kbd></td>
        <td>spaceless</td>
        <td><code>{% spaceless %} ... {% endspaceless %}</code></td>
    </tr>
    <tr>
        <td><kbd>ssi + TAB</kbd></td>
        <td>ssi</td>
        <td><code>{% ssi <i>foo</i>￼ %}</code></td>
    </tr>
    <tr>
        <td><kbd>url + TAB</kbd></td>
        <td>url</td>
        <td><code>{% url <i>foo</i>￼ %}</code></td>
    </tr>
    <tr>
        <td><kbd>widthratio + TAB</kbd></td>
        <td>widthratio</td>
        <td><code>{% widthratio <i>foo</i>￼ %}</code></td>
    </tr>
    <tr>
        <td><kbd>with + TAB</kbd></td>
        <td>with</td>
        <td><code>{% with ￼<i>foo</i> %} ... {% endwith %}</code></td>
    </tr>
</table>