1. generate  a new IOC project using Ionic Command Line

For getting start, we am going to create a new ionic project under blank template
- ionic start ionic-expandable-listIOS blank

Once that has completed, you expect the working directory as belows: and jump to root of its
- cd ionic-expandable-listIOS

We will create a custom component called Expandable using
- ionic g component Expandable

This command will also automatically creat the component in the app.module.ts file, however, it also generate an expanble.module.ts

2. Building the expandable components
What we are aiming is to build a component that will look like as
<expandable [expandHeight] ="itemExpandHeight" [expended]="item.expanded">
 some content here
</expandable>

we could insert this whenever we would like to present a collapsible/ expandable component.

Modify ../components/expandable/expandable.html
???

modify ../components/expandable/expandable.scss like:
???

Modify ../components/expandable/expandable.ts like:
???

3. Using Component to create an Accordion List
The component is completed now, so all we need to is use it in project.




