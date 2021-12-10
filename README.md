# Issue of Web Technology

## Architectural issue of Web Technology
------------------------------------------
The web layer is also referred to as the UI layer. The web layer is primarily concerned with presenting the user interface and the behavior of the application (handling user interactions/events). While the web layer can also contain logic, core application logic is usually located in the services layer. The three Layers within the Web Layer are:

* ``HTML(The Content Layer)``: The content layer is where you store all the content that your customers want to read or look at. This includes text and images as well as multimedia. It's also important to make sure that every aspect of your site is represented in the content layer. That way, your customers who have JavaScript turned off or can't view CSS will still have access to the entire site, if not all the functionality.

* ``CSS(the Styles Layer)``: Store all your styles for your Web site in an external style sheet. This defines the way the pages should look, and you can have separate style sheets for various media types. Store your CSS in an external style sheet so that you can get the benefits of the style layer across the site.

* ``JavaScript(the Behavior Layer)``: JavaScript is the most commonly used language for writing the behavior layer; ASP, CGI and PHP can also generate Web page behaviors. However, when most developers refer to the behavior layer, they mean that layer that is activated directly in the Web browser - so JavaScript is nearly always the language of choice. You use this layer to interact directly with the DOM or Document Object Model.

Benefits of separating the layers are:

* Shared resources
* Faster downloads
* Multi-person teams
* Accessibility
* Backwards compatibility

## Tier Technology
----------------------------

Software Architecture consists of One Tier, Two Tier, Three Tier, and N-Tier architectures.

A ``tier`` can also be referred to as a ``layer``.

Three layers are involved in the application namely ``Presentation Layer``, ``Business Layer``, and ``Data Layer``. Let’s see each layer in detail:

#### **``Presentation Layer :``**
It is also known as the Client layer. The top most layer of an application. This is the layer we see when we use the software. By using this layer we can access the web pages. The main function of this layer is to communicate with the Application layer. This layer passes the information which is given by the user in terms of keyboard actions, mouse clicks to the Application Layer.
For example, the login page of Gmail where an end-user could see text boxes and buttons to enter user id, password, and to click on sign-in.

In simple words, it is to view the application.

#### **``Application Layer :``**

It is also known as Business Logic Layer which is also known as the logical layer. As per the Gmail login page example, once the user clicks on the login button, the Application layer interacts with the Database layer and sends required information to the Presentation layer. It controls an application’s functionality by performing detailed processing. This layer acts as a mediator between the Presentation and the Database layer. Complete business logic will be written in this layer.

In simple words, it is to perform operations on the application.

#### **``Data Layer :``**

The data is stored in this layer. The application layer communicates with the Database layer to retrieve the data. It contains methods that connect the database and performs required action e.g.: insert, update, delete, etc.

### **One Tier Technology :**

One Tier application AKA Standalone application. One-tier architecture has all the layers such as Presentation, Business, Data Access layers in a single software package. Applications that handle all the three tiers such as MP3 player, MS Office come under the one-tier application. The data is stored in the local system or a shared drive.

### **Two Tier Technology :**
Two Tier application AKA Client-Server application. The Two-tier architecture is divided into two parts:

* ``Client Application`` (Client Tier)
* ``Database`` (Data Tier)

The client system handles both Presentation and Application layers and the Server system handles the Database layer. It is also known as a client-server application. The communication takes place between the Client and the Server. The client system sends the request to the server system and the Server system processes the request and sends back the data to the Client System.

### **Three Tier Technology :**
Three Tier application AKA Web Based application. The Three-tier architecture is divided into three parts:

* ``Presentation layer`` (Client Tier)
* ``Application layer`` (Business Tier)
* ``Database layer`` (Data Tier)

The client system handles the Presentation layer, the Application server handles the Application layer, and the Server system handles the Database layer.

### **N-Tier Technology :**

Another layer is the N-Tier application. N-Tier application AKA Distributed application. It is similar to the three-tier architecture but the number of application servers is increased and represented in individual tiers in order to distribute the business logic so that the logic will be distributed.

**_Advantages of Tier Technology_** 

* ``Maintainability`` - Because each tier is independent of the other tiers, updates or changes can be carried out without affecting the application as a whole.
* ``Scalability`` - Because tiers are based on the deployment of layers, scaling out an application is reasonably straightforward.
* ``Flexibility`` - Because each tier can be managed or scaled independently, flexibility is increased.
* ``Availability`` - Applications can exploit the modular architecture of enabling systems using easily scalable components, which increases availability.
* ``Reusability`` - Components are reusable
* ``Faster development`` - Because of division of work web designer does presentation, software engineer does logic, DB admin does data model.
