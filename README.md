# IDCText: An Application for Conducting Text Input Research Studies in Indian Languages

### Abstract 
Some might argue that text-input-related HCI research in English is verging towards saturation. On the other hand, a lot more work remains to be done in Indian languages (and in fact, in several other languages around the world). Through this paper, we release in the public AQ1 domain IDCText, a web based tool that makes it easier for researchers to conduct text entry studies for Indian (and other) languages. This application is compatible with all contemporary web browsers and supports studies using any keyboard that can enter text in a web browser text field. The tool has many features that have been used in text input studies (including some special features that Indian language HCI researchers might need), and automatically calculates several metrics that text input studies report. To test our tool, and also to demonstrate its capabilities, we conducted an empirical within-subjects counterbalanced systematic longitudinal study (N = 10) to compare the performance of two experimental Marathi keyboards, namely Swarachakra and Swaravarna. We present the metrics that emerged from IDCText. We also reflect on the current capabilities of the tool and the future possibilities for improvement. The tool is hosted on a website and is accompanied by a video tutorial that shows how a HCI researcher can set up and conduct a new text input study. Through this paper, we also release IDCText code in the public domain in the open source, so that other researchers can continue to build on it.


--------------------------------------------------------------------------------------------------------------------------------
[**Publication Link**](https://link.springer.com/chapter/10.1007/978-3-031-80829-6_5)  

IDCText is an open-source, freely available web application developed using HTML5, CSS3, PHP and Javascript. IDCText allows HCI researchers to design studies in Indian languages, offering the flexibility to use custom phrases and configure various study parameters to meet their specific needs.

Visit [**IDCText**](http://idid.in/IDCtext/)  to see the hosted version of IDCText application


# Project Setup Guide 
## Prerequisites
Before you begin, ensure you have the following installed on your local machine:
- [**XAMPP**](https://www.apachefriends.org/index.html) (or any other local server like WAMP, MAMP, etc.)
- XAMPP is an open-source web server solution package. It is mainly used for web application testing on a local host webserver.
XAMPP stands for:
X = Cross-platform
A = Apache Server
M = MariaDB
P = PHP
P = Perl

On completing the download of the setup file, begin the installation process and, in the “Select Components” section, select all the required components.


<img src="https://github.com/user-attachments/assets/87332a04-5ae4-41b4-8cd8-62186ae80484" alt="Installation step 1" width="600" height="400">


Next, select the directory where you want the software to be installed. It is recommended that you keep the default directory “C:\xampp” and click on “next” to complete the installation

<img src="https://github.com/user-attachments/assets/65e66106-5c0b-40d5-816d-aace1fd0e099" alt="Installation step 1" width="600" height="400">


## Step-by-Step Instructions

### 1. Clone the Repository OR download the source code
First, download the source code or clone the repository using Git.

**To clone the repository:**
```bash
git clone https://github.com/IDCText/IDCText-app.git
```

### 2. Download the Source Code

- If you do not want to clone from github , you can download the source code as a ZIP file.
- Extract the ZIP file to your desired location (as explained below) .

### 3. Directory Structure


<img src="https://github.com/user-attachments/assets/2f778b1f-cdc2-40d0-9832-3ce68e71ceea" alt="Installation step 1" width="600" height="200">


  In the XAMPP directory, there exists a folder called “htdocs”. This is where all the programs for the web pages will be stored.
   Now, to run a PHP script:
   
   Go to “C:\xampp\htdocs” and inside it, either clone the repository here or move the downloaded source code here.

### Setup Instructions

### 4. Set Up the Database


<img src="https://github.com/user-attachments/assets/f4b66c0f-c490-4867-bfe9-bc95acbd32d7" alt="Installation step 1" width="600" height="400">


Before you run or start writing any program in PHP, you should start Apache and MYSQL in xampp as shown above.

- Open phpMyAdmin by navigating to `http://localhost/phpmyadmin` in your web browser.
     - Create a new database named **'textidc'** .


<img src="https://github.com/user-attachments/assets/61294ceb-846d-45b4-8c95-a3adf12548d8" alt="Installation step 1" width="600" height="400">


   - Import the SQL files provided in the databases folder into the textidc database:
      Click on the textidc database, go to the Import tab, and select the **'nusers.sql'** file from the databases folder. Click on 'import' to import the table in databaser.
   - Repeat the process by importing the **'studies.sql'** file into the same textidc database.


**Open your web browser and navigate to http://localhost/IDCText-app**.


--------------------------------------------------------------------------------------------------------------------------------

## Tutorial Video 

Tutorial video for creating a text input study on IDCText is available on [Youtube](https://www.youtube.com/watch?v=zjOIJ0RGGFE).


--------------------------------------------------------------------------------------------------------------------------------

## Cite our work 
@inproceedings{deshmukh2024idctext,
  title={IDCText: An Application for Conducting Text Input Research Studies in Indian Languages},
  author={Deshmukh, Vedant and Joshi, Anirudha},
  booktitle={Indian Conference on Human-Computer Interaction Design and Research},
  pages={104--124},
  year={2024},
  organization={Springer}
}


