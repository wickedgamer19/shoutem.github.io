---
layout: doc
permalink: /docs/ui-toolkit/components/dividers
title: Dividers
section: UI toolkit
---

# Dividers

Dividers are components used to add space or any other separator between other components.

## Divider
![Divider example]({{ site.baseurl }}/img/ui-toolkit/dividers/divider@2x.png "Divider"){:.docs-component-image}

#### JSX Declaration
```JSX
<Divider />
```

## Line divider
![Line divider example]({{ site.baseurl }}/img/ui-toolkit/dividers/line-divider@2x.png "Line divider"){:.docs-component-image}

#### JSX Declaration
```JSX
<Divider styleName="line" />
```

## Section divider  
Section dividers are usually used in lists to separate groups of similar list items, for example to group contacts by the first letter of their name. ListView will automatically style all dividers added to it.

![Section divider example]({{ site.baseurl }}/img/ui-toolkit/dividers/section-divider@2x.png "Section divider"){:.docs-component-image}

#### JSX Declaration
```JSX
<Divider styleName="section-header" />
```

## Section divider + Label
![Section divider + Label example]({{ site.baseurl }}/img/ui-toolkit/dividers/section-divider-label@2x.png "Section divider + Label"){:.docs-component-image}

#### JSX Declaration
```JSX
<Divider styleName="section-header">
  <Caption>INFORMATION</Caption>
</Divider>
```

## Section divider + Label + Caption
![Section divider + Label + Caption example]({{ site.baseurl }}/img/ui-toolkit/dividers/section-divider-lavel-caption@2x.png "Section divider + Label + Caption"){:.docs-component-image}

#### JSX Declaration
```JSX
<Divider styleName="section-header">
  <Caption>PRODUCT NAME</Caption>
  <Caption>PRICE</Caption>
</Divider>
```
