* > **what is angular** - *angular is a component based frame work build using the java script by google.*
- *by using angular framework we can build our application using prebuilt function we don't need to write from scarch*

* > **what is spa** - *it is a single page application angular is a single page application. it will not reload a new page . *

* > **what is angular cli** - *it is a command line interface which is used to develop,scaffold,maintain directly from commad promt or terminal. by using angular we can create a component by using commands in our terminal.*

* > **what is compponent** - *component is a building blocks of an web application which contains html,css and ts .*
*we can create multiple components as we want*
- *for each components it contains  html,css and type script*
 - *we can create components manually and we can create a component by using angular cli*
- *when we create a component by using angular cli  by default angular creates a class and component decorator it will get register into app modules*
*when we creates manually we need to create a class and we need to export that class and we need to register into the app modules*
*when we register our component into app modules then only we need to use our coomponent*

* >**what is data binding** - *data binding is a technique where data stays in sync between component and veiw.*
- *there are two types of data bynding*
- *one-way binding*
-*two way binding*

* > **one way binding** - *in one way data binding data folws in one direction either component to veiw or veiw to component*
- *one way data binding can be classified into 3 types .*
- *interpolation*
- *property binding*
- *event binding*

* > **interpolation {{}}** - *by using interpolatin we can make the data dynamic in the template*

* > **property bindng []** - *property binding binding allows to bind html element property in property component. when ever the value of component changes automatically angular updates the element property  in the veiw* 
- *it is a one way binding from logic to veiw*
- *we can also set the properties such as class,href,text content etc*  
- *we can also set it for the custom components or directives*

* > **event binding ()** - *event binding allows to bind events such as click,ketstock,hover touch etc to a method in a component*
- *it is a one way binding from veiw to logic*
- *it helps to track the user events in the veiw and responce it in view and by clicking submit or somthing we can save the data in the backend server.*

* > **two-way data binding[()]** - *two way data binding is nothing but the combination of property binding and event binding to create two way binding*
- *angular uses the ngModel directive to achive two way binding*
- * for using ngModel dirctive  we need to import 'FormsModule' in our component which is in FORMS package.*

- > **@input Decorator** - *it is used for getting data from parent component to child component*
- *for that firstly we need to create a message inside the parent component after that we need to import inside the parent class after that we need to docoraete using @input() in this input we need to create a child message for getting data from parent component after that we need to bind this child message into the child component selector by using property binding.*

- > **@output decorator** - *it is used for getting data from child component to parent component while event occurs we can make use of event emmiter inside this component*

- *in output decorator we need to create a variable inside the child comonent for getting this child message inside the parent component we need do we need to import output and event emmiter inside the child component . after importing we need to decorate using @output() for that decorator we need to create a variable like "propertyName=new EventEmiter()" after that we need to create a function inside the child component and we need to bind this data into the child class selector which is in main template.*

- > **@veiwChild Decorator** - *it is used for getting data from child component to parent component by importing all the child component into the parent component  and we need to impoet veiwChild inside the parent class .*
- *firstly we need to create a variable inside the child class after that we need to get that child message inside the parent component by importing veiwChild inside the parent component.