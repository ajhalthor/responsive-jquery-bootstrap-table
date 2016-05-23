# jquery-bootstrap-table

A simple yet elegent assessment table, embellished with jquery and bootstrap functionality.

![Gif of Table](/gifs/normal.gif?raw=true "Normal view")

Its got Nice animations to captivate users 

![Validation Gif of Table](/gifs/validation.gif?raw=true "Normal view")

Oh Yeah! Its completely reponsive.

![Resize Gif of Table](/gifs/resize.gif?raw=true "Normal view")

##Features

- **Attractive.** Colored design makes the table more interactive for users.
- **Fully Equipped.** Comes with a basic page layout with a fixed sidebar and navigation bar .
- **Validation.** Uses jQuery for validation and clean transitions.
- **Completely responsive.** So, it looks good on all mobiles, tablets, laptops and desktops with any orientation.
- **Automatic Naming.** Each field is given a name depending on what you enter in the `fields` array (below). This name is formed by converting the field entry to lowercase and replacing space ' ' with hyphen '-'. Eg. A field "Command over Subject" will be automatically named as "command-over-subject". This can be used for furthur frontend or backend processing.

##Usage

index.html : The actual form that constitutes the core of this project.

Just modify the variables to configure what text appears on a desktop, tablet and mobile. Here is an example :

```
<script type="text/javascript">

		var heading ="Rate Professor X";

		var caption = "Professor X rating";

		//List of fields in your checklist
		var fields = ['Command On the Subject','Ability to Explain','Practical Exposure','Dress Code	','Disciplinary Insistence','Involvement in Project work','Social Attitudes','Rating As A Teacher','Language Capability','Ability To Create Interest','Punctuality','Availability for Students','Knowledge of recent Technological Advancement','My Amazing Field','Another Field'];

		//Heading of the fields
		var fields_heading = "Competency";

		/* an array of arrays in which each sub array has 3 fields:
			- Display on large devices ('Excellent','Very Good','Good','Fair','Poor')
			- Display on medium devices ('Ex','V.G','G','Avg','Poor')
			- Display on small devices ('5','4','3','2','1')
		*/
		var levels = [ ['Excellent','Ex','5'],['Very Good','V.G','4'],['Good','G','3'],['Fair','Avg','2'],['Poor','Poor','1'] ] ;

</script>

```
These are the only parameters you will need to modify in the entire project.You dont need to touch the rest of the project
		


![Screenshot of Table](/screenshots/desktop/normal.png?raw=true "Normal view")

Validation Will see if all fields are checked. if not, empty fields are highlighted.

![Screenshot of Table and Validation](/screenshots/desktop/validation.png?raw=true "Nice looks for Validation")

The design screenshots are also included in the project repository

##License
**jquery-bootstrap-table** is released under the MIT License. See the bundled LICENSE.md for details.
