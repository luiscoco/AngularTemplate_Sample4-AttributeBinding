# Attribute Binding

https://angular.io/guide/attribute-binding

In Angular, attribute binding is a way to dynamically bind values from component properties to HTML attributes. It allows you to set values for HTML attributes based on the state or data within your Angular component.

Attribute binding is denoted by square brackets ([]) and can be used with any standard HTML attribute. It enables you to dynamically update attribute values based on changes in your component's properties.

Here's a simple example to illustrate attribute binding in Angular:

Let's say you have a component called AppComponent with a property called title that holds the title text for your application. You want to bind this property to the title attribute of an HTML element, such as an h1 tag.

In your component's template (HTML file), you can use attribute binding as follows:
  
```typescript
<h1 [title]="title">My Angular App</h1>
```

In this example, the value of the title property in your AppComponent will be bound to the title attribute of the h1 tag. So, whenever the title property changes in your component, the title attribute in the HTML will be updated accordingly.

You can also perform attribute binding with other attributes. For instance, if you want to bind the src attribute of an img tag to a component property called imageUrl, you can do it like this:
  
```typescript
<img [src]="imageUrl" alt="Image">
```

Again, whenever the value of imageUrl changes in your component, the src attribute of the <img> tag will be updated accordingly.

Attribute binding is a powerful feature in Angular that allows you to create dynamic and interactive applications by synchronizing component data with HTML attributes.
