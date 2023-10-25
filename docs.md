# StrongMind UI/UX Pizza Designer Excercize
**Project Details:**
https://github.com/StrongMind/culture/blob/main/recruit/ux-engineer.md#user-stories

**Link to userflow:**
https://www.figma.com/file/qnnWpo9yxHfWsTPYa5pcTG/Pizza_UserFlow?type=whiteboard&node-id=0%3A1&t=5ULZAR8Nx4rgKNQC-1

**Link to wireframe:**
https://www.figma.com/proto/JAWZ5Dd7HaKYabuultZS6i/Pizza_Wireframes1-(Copy)?type=design&node-id=1-2&t=tDHHPU4q2Z6dNk7I-1&scaling=min-zoom&page-id=0%3A1&mode=design

**Link to Design/Prototype:**
https://www.figma.com/proto/RjqR1FPnCMNt8JpMdYbjQE/Pizza_Design?type=design&t=vasPnKH6QIE18BRV-1&scaling=min-zoom&page-id=0%3A1&node-id=1-2&mode=design

**Link to developed page:**
http://dallincox.com/ux_exercise/src/

## Documentation:
**Target devices:** Desktop, Tablet, Mobile

**Assumptions:**
Happy route on database submissions - ie no problems saving configurations

### Pizza Store Owner (Manage toppings UI)
Pizza owner wants a simple and easy to use interface that allows them to add or edit toppings as well as add new toppings. Any errors made from user should be easily identifiable and validated.<br/>
-visually appealing dashboard to manage toppings<br/>
--Easily Identify each topping through visual or name<br/>
--Adding updating or deleting a topping should be intuitive<br/>
--clear feedback when i try to add duplicate toppings<br/>

**screens:** 
toppings list, 
    modal - edit topping, 
    modal - add topping modal, 
    modal - topping photo uploading
    modal - delete topping modal
    prompt on page - successful save/delete


### Pizza Chef
Pizza Chef wants a clear UI that Identifies all aspects of pizza creation for simplicity. Pizzas should be easy to identify as well as all details such as crust, sauce, cheese, and toppings.<br/>
-creation space where i can visualize pizza<br/>
--design should help differentiate between various pizza and their toppings<br/>
--Adding, updating, or deleting a pizza, or its toppings, should be a straightforward process.<br/>
--Ensure that the UI provides feedback when duplicate pizza names are entered.

**screens:** <br/>
pizza list, <br/>
    modal - delete pizza,<br/>
    prompt on page - successfly save/delete<br/>
pizza add/edit, <br/>
    Error message for existing pizza name<br/>
    prompt on page - successfly save/delete<br/>

### Design Decisions: 
-Editing or adding a new pizza is a form submission. Standard form validation should suffice for informing user of duplicate name entry.
<br/>
-Editing or adding a new topping is a form submission. Standard form validation should suffice for informing user of duplicate name entry
    

**Deliverables:**<br/>
-Documentation (docs.md)<br/>
-Wireframes<br/>
-User Flows<br/>
-Prototype that demonstrates interactions<br/>
-Basic responsive front-end for one page