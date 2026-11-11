# Nutrition-Calculator

Web App to perform calculations on the nutrition facts of various foods, to help with meal planning and comparing different food options. Initial plan is to start with a database of food items for a proof of concept, but plan to support reading nutrition facts with a phone camera so the math can be done on the fly in the grocery store.

---
## Calculator Page
<img width="1066" height="814" alt="Calculator drawio" src="https://github.com/user-attachments/assets/7cbe725a-bb93-44bd-bf57-89641c27d29d" />

- Header at the top of the page navigates between the calculator and the database page
- Expression is displayed offset to the right at the top of the page content
- Food saved to the database can be selected from the menu on the right, can be filtered with a text bar
- Calculator controls are beneath the expression display
- Nutrition information can be selected and inserted into the expression from the list under the expression
- Mathematical operations (addition, subtraction, multiplication, parentheses, etc) laid out as buttons on the right side of the calculator controls

## Databse Page
<img width="1064" height="814" alt="FoodDatabase drawio" src="https://github.com/user-attachments/assets/7e8980aa-ad1f-486a-8274-23bec5cf1b98" />

- Food database uses the same list of foods menu as the calculator page on the left of the page
- Additional item at the bottom of the page can be clicked to add a new item to the database
- Selecting a food item populates the nutrition fact table in the right side of the screen 
- Nutrition facts list split into two columns, fields and values
- Each field and value is a text field that can be edited when clicked, button at the bottom can be used to add a new nutrition fact field to the chosen food item
- Changing a field or value updates the food item in the database, and changes will be reflected when switching back to the calculator page

---

## Planned Features
- Database of food with nutrition facts to pull from
- Manual input of additional food items
- Editable formulas and a custom formula library 
  -  e.g. Protein/Calorie or Calories/Serving * Servings Per Container
- Apply formulas from formula library directly to food items in database
- Calculation history

### Aspirational Features
- Populate nutrition facts from phone camera images
- Recommend foods based on nutrition goals and what you've already purchased/eaten
