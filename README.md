# Lab-Using-Markdowns-in-Jupyter-Notebooks
Lab: Using Markdowns in Jupyter Notebooks

Jupyter Notebooks are composed of code and markdown cells. Markdown cells are used to present text, images, etc. and are useful to document and explain the contents of your notebook. In this lab, you will become familiar with writing markdown.

# Objectives
After completing this lab, you will be able to:

- Identify in which Kernel your Jupyter notebook is running
- Create headings, and add text in bold and italics in Markdown
- Insert links and images using Markdown
- Create Tables in Markdown
- Create ordered and unordered lists in Markdown
- Demonstrate your proficiency in using Markdown in Jupyter Notebooks


# Exercise 1
Kernels in Jupyter notebook
A notebook kernel is a computational engine that executes the code in a Notebook file.

When the Notebook is executed, the kernel performs the computation and produces the results.

On the top right corner you can see the kernel's name. For instance, in JupyterLite, the default kernel is Pyolite. Similarly, if you are working on JupyterLab, the kernel will be Python 3 or Python 2, depending on the version.

![image](https://github.com/user-attachments/assets/6e5bfeed-b699-4f2e-a7e4-fa75c3155018)

#### Try yourself:

* Click the running Kernel, For Example, **Pyolite**, to see which other kernels are available.<br/>

  > _Please don't switch the existing kernel._

the output looks like
![image](https://github.com/user-attachments/assets/55f70013-f77f-4f14-8041-3c0cd3dd689c)


* Check the state of the kernel by clicking on the circle next to it.
![image](https://github.com/user-attachments/assets/240476aa-2e70-4552-99d4-7934601e5b71)

# Exercise 2
Create headings, and add text in bold and italics in Markdown
Let us explore basic markdown elements such as:

- Headings
- Bold Text
- ItalicText


## Headings
* You can create headings by adding a # sign before a word or a phrase.

  - There are six levels of headings.
  - The number sign # indicate the level of heading for example # Hello corresponds to level 1,the highest level heading.
  - Display the following text using six different heading levels.
    
    1. H1: This is a level 1 Heading
    2. H2: This is a level 2 Heading
    3. H3: This is a level 3 Heading
    4. H4: This is a level 4 Heading
    5. H5: This is a level 5 Heading
    6. H6: This is a level 6 Heading
   
       ![image](https://github.com/user-attachments/assets/f7f3aaa6-b7fe-47af-84a0-3ef7adece768)


## Bold Text 
 * You can create bold text by adding two asterisks or underscores before and after a word, phrase, or a sentence.
 * Convert the cell below to markdown cell and execute it.

# Execute it as a markdown cell
**Bold Text using asterisks.**  
__Bold Text using underscores.__

Before Executing
![image](https://github.com/user-attachments/assets/9abc38fb-e2e7-423a-8ac2-1533a285721c)

After the Execution
![image](https://github.com/user-attachments/assets/623f93e3-9fc1-4438-bf20-f124ad6e0733)

## Italic Text
* You can display text in italics by adding a single asterisk or underscore before and after a word, phrase, or a sentence.

* Convert the cell below to markdown cell and execute it.

# Execute it as a markdown cell
*Text in italics using asterisk.*  
_Text in italics using underscore._

before execution
![image](https://github.com/user-attachments/assets/94331ec3-9b61-44c3-b49a-d52b3728306b)

after execution
![image](https://github.com/user-attachments/assets/0c93463b-5d24-4191-a0c1-0733df714aec)

### Bold and Italic text
* You can display text in both bold and italic style at the same time by adding a three asterisks or underscores before and after a word,phrase or a sentence.

* Convert the cell below to markdown cell and execute it.

before 
![image](https://github.com/user-attachments/assets/17fe21ec-2fa0-4af4-bd09-c6205b5dfabd)

and after
![image](https://github.com/user-attachments/assets/04b6f3b8-9b89-469d-a10f-9f36fbd95b29)

# Exercise 3
### Insert links and images using Markdown

* Hyperlinks
* Images

### Hyperlinks
You can create a **hyperlink** in the following format.

<img src="https://raw.githubusercontent.com/Lakshmiholla-2808/first/main/hyper1.png">

* **Name of the link** is the clickable link text
* **Link url** is the web address of the url which will be directed on clicking the link.
* To display a clickable link without a name, enclose the link in angle brackets.
&lt;https://skills.network/ &gt;


_Convert the code cell below to a markdown cell. Then create a hyperlink to the webpage **https://skills.network** with the **Name of the Link** as "Skills Network". Then execute the code._

![image](https://github.com/user-attachments/assets/76018ec4-65d4-477f-8cc0-976eac2e7009)


### Images

Images can be rendered in the following format.
     
<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Labs_V4/images/image.png">

Convert the cell below to markdown cell and execute it.
![image](https://github.com/user-attachments/assets/9082a435-1842-48e6-aefb-2a0a0a5c6b01)

output
![image](https://github.com/user-attachments/assets/1e05a5f7-1db4-4151-8953-09411edc953b)


# Exercise 4 

### Create Tables in Markdown

To create tables, use: 
* **hyphens** <code>(----)</code> for column headers 
* **pipes** <code>|</code> to separate each column
* **Text on a new line** to separate each row

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Labs_V4/images/tabledisp.png">


_Convert the code cell below to a markdown cell. Then recreate the example table above and execute the code._

## Execute as a markdown cell

| Country Name | Capital |
| -------------| ------ |
| United States | Washington DC |
| Australia | Canberra |
| India | New Delhi |

![image](https://github.com/user-attachments/assets/561f93c7-bac0-4dac-9585-048034ff6209)


output
![image](https://github.com/user-attachments/assets/6a65ef5f-7f7e-406d-ab14-f1b1e954a377)


# Exercise 4 

### Create ordered and unordered lists in Markdown

#### Unordered List

An unordered list is also referred to as a **bulleted list**.

You can create an unordered list by adding **dashes (-), asterisks (*), or plus signs (+)** in front of line items.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Labs_V4/images/unordered.png">

_Convert the code cell below to a markdown cell. Then recreate the unordered list displayed above using **dashes (-), asterisks (*),** and **plus signs (+).** Then execute the code._

![image](https://github.com/user-attachments/assets/c62207ef-3dd7-4fcf-8ebe-9fe8e4c87594)

# Execute as a markdown cell
- First item using dashes
- Second item using dashes
- Third item using dashes
- Fourth item using dashes

* First item using asterisks
* Second item using asterisks
* Third item using asterisks
* Fourth item using asterisks

+ First item using plus
+ Second item using plus
+ Third item using plus
+ Fourth item using plus


output 

![image](https://github.com/user-attachments/assets/f2076974-8ed0-4556-b001-eb69343457e4)



#### Ordered List

Create an ordered list by adding line items with **numbers** followed by **periods**.

 <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Labs_V4/images/list.png">

_Convert the code cell below to a markdown cell. Then recreate the ordered list displayed above and execute the code._

# Execute as a markdown cell
1. First item
2. Second item
3. Third item
4. Fourth item


output

![image](https://github.com/user-attachments/assets/cfe343e7-016a-4252-ae16-82031ecb6430)


# Practice Exercises

### Demonstrate your proficiency in using Markdown in Jupyter notebooks

#### Task 1: Create **H2 level heading** as **Welcome to Python programming** and add the image from the following **url** with alt text as **This is SN labs New Launcher**

_https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Labs_V4/images/Launcher.png_


answer - 
## Welcome to Python Programming   
![This is SN labs New Launcher](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Labs_V4/images/Launcher.png)

![image](https://github.com/user-attachments/assets/fd548d6b-d652-4456-978c-7c09b675b96a)


output - 

![image](https://github.com/user-attachments/assets/125248fe-f553-4b4d-8dbb-a6644297236f)


#### Task 2: Create a hyperlink to <code>https://www.coursera.org/learn/open-source-tools-for-data-science/home</code> with the **Name of the link** as "Tools For Data Science".

answer
<a href ="https://www.coursera.org/learn/open-source-tools-for-data-science/home/">Tools For Data Science</a> 

![image](https://github.com/user-attachments/assets/8ea0a173-df56-4de5-a913-8eafd495fc39)


output 

![image](https://github.com/user-attachments/assets/487a76f0-84ab-4050-8408-ea5a7af9117f)


#### Task 3: Create the following table:

 <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Labs_V4/images/table.png">

answer 

![image](https://github.com/user-attachments/assets/24332b6b-7ec8-44cd-b0c2-304b5d78bc37)


output

![image](https://github.com/user-attachments/assets/e24e0cd6-03a4-48f1-8ce5-8c9fdb795bb2)


#### Task 4: Create the following ordered list:

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Labs_V4/images/order1.png">

answer

![image](https://github.com/user-attachments/assets/4a8fa4b2-a034-43de-b926-a2795aca6b2a)

output

![image](https://github.com/user-attachments/assets/51ee3bfd-0af9-4bf9-a459-56d44e3b8ead)


## This is the end of Lab
##### CheatSheet - <https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet>
