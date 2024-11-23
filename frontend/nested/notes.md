## components

nav-bar
![](<../../z/aharo24 2023-02-24 at 11.29.22 PM.png>)

profile
![](<../../z/aharo24 2023-02-24 at 11.29.44 PM.png>)

trends
![](<../../z/aharo24 2023-02-24 at 11.30.08 PM.png>)

feed
![](aharo24 2023-02-24 at 11.30.28 PM.png>)

feed:
	tweet component
	like component


### component code/implemntattion

```
class Tweet
{
	state= {};
	render(){
	}
}

```

![](<../../z/aharo24 2023-02-25 at 12.02.21 AM.png>)

### react
react is better because of something called DOM:
	it seems to be acsryconous 

reacts to state changes

#### its a library 

for that reason we need to work with an API 

### anguilar
**Framework** 

---
## npm

`install create-react-app`

> 	npm i -g [package_name]@



i       -->   install
-g   -->    global
@ --->    version

create-react-app --> is like a CLI 

create-react-app [app_name]   :
	will create a react app template on the pwd 


### steps:
--> create-react-app [app_name]  
cd into app_name
npm start


### older version in CLI
![](<../../z/aharo24 2023-02-25 at 2.21.45 AM.png>)




### span <>


In HTML, the `<span>` element is an inline container used to group and apply styles to a small piece of text or a part of a larger text. It is a generic container and doesn't have any semantic meaning, unlike other HTML elements such as `<h1>` (heading), `<p>` (paragraph), `<a>` (link), etc.

The `<span>` element can be used in various ways, for example:

-   To apply inline styles: You can apply CSS styles such as color, font-size, background-color, etc. to a `<span>` element and use it to highlight or emphasize specific text within a larger text block.
    
-   To group and target specific content: You can use the `class` or `id` attribute on a `<span>` element to group specific content together and apply styles or JavaScript functionality to them.



```  Js
<p>John loves <span style="color: blue;">blue</span>berries and <span style="color: red;">red</span> apples.</p>
```


![](<../../z/aharo24 2023-02-25 at 12.25.09 PM.png>)

In the code  provided, the outermost `<span>` element is used to group together a set of elements that need to be displayed as a single entity, likely for layout or styling purposes.

Within this `<span>` element, there is another nested `<span>` element, which is used to wrap the text "Let's Connect". This is probably done to apply some styling or interactivity to the text when the user interacts with it, such as a hover effect or a click event.





### const

![](<../../z/aharo24 2023-02-25 at 10.54.48 PM.png>)


![](<../../z/aharo24 2023-02-25 at 10.55.22 PM.png>)





```Js
const myObj = {name: 'Alice', age: 25};
myObj.age = 26; // This is allowed
```

```Js
const myObj = {name: 'Alice', age: 25};
myObj = {name: 'Bob', age: 30}; // This is not allowed

```



**const is like adding a 'state'**

in python
```python
user = {'name': 'Alice', 'age': 25, 'is_active': True}

# Update the user's age
user['age'] = 26

# Update the user's activity status
user['is_active'] = False

```
java
```java
public class User {
    private String name;
    private int age;
    private boolean isActive;

    public User(String name, int age, boolean isActive) {
        this.name = name;
        this.age = age;
        this.isActive = isActive;
    }

    // Getters and setters for the fields

    public void setAge(int age) {
        this.age = age;
    }

    public void setActive(boolean isActive) {
        this.isActive = isActive;
    }
}

// Example usage
User user = new User("Alice", 25, true);

// Update the user's age
user.setAge(26);

// Update the user's activity status
user.setActive(false);

```



---

### JSX

![](<../../z/aharo24 2023-02-26 at 1.00.46 AM.png>)


### bootstrap icons

``` brew
npm i bootstrap-icons
```

this one worked
``` brew
npm install react-bootstrap-icons --save   
```

### 'let'

```

```

![](<../../z/aharo24 2023-02-26 at 1.39.00 AM.png>)

### react-multi-carousel

``` brew
npm i react-multi-carousel
```

```brew
npm install react-multi-carousel --save
```

### animate.css
```brew
npm install animate.css --save  
```

### react-on-screen
```brew
npm i react-on-screen
```



### .css and .js  (hand to hand code)

![](<../../z/aharo24 2023-02-26 at 5.04.28 PM.png>)








### Email

1:17:00

I need to go to google settings to allow the third party to use my gmail.... I'll look into that later 
