---
title: Home
layout: layout.html
order: 0
---
# Machine Learning Hardware Reading Group

We meet every other {{ site.day }} in {{ site.location }} at {{ site.time }}.

The schedule for this semester (Spring 2017):

<ul>
{{#each schedule}}
    <li>
      <time>{{date day 'MMMM D'}}</time>: <strong>{{title}}</strong><br>
      led by {{who}}
      {{#if details}}<div>{{{ markdown details }}}</div>{{/if}}
    </li>
{{/each}}
</ul>

You can [edit the schedule][edit] on GitHub.

[edit]: https://github.com/cucapra/cslrg/edit/master/src/schedule.yaml
