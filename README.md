# <p align="center"> CantoneseChatbot_v2 </p>

<b>
<div align="center">
City University of Hong Kong
<br>
</div>  
Dataset <br>
|-- <a href="https://drive.google.com/file/d/1-0zxvtzvwp48dGzRISR0KCGXSrRDftF1/view?usp=sharing"> Social <br></a>
|-- <a href="https://drive.google.com/file/d/1STpqOOza1wmS-rOww5nwSHWQ2RLb6fTy/view?usp=sharing"> Historical Dialogs <br></a>
|-- <a href="https://drive.google.com/file/d/1gpuj981sSxqwdZOrNeW-khCcFUaVmxzS/view?usp=sharing"> Students <br></a>
|-- <a href="https://drive.google.com/file/d/1oH9G13-j0TNGeY32cTBV3iIrQukm-AHm/view?usp=sharing"> Efaqa <br></a>
|-- <a href="https://drive.google.com/file/d/1JtntdoZM-uZZ3TpH479jQ9Tgok4xb91B/view?usp=sharing"> Undergraduate <br></a>
|-- <a href="https://drive.google.com/file/d/1xQKNEazEK5djWmZsMM0MCce1uJzRd8ec/view?usp=sharing"> Counsellor-Evaluated Dialogs <br></a>


<a href="https://colab.research.google.com/drive/1y_l6ZMyopxIaFeX9K3UBeGwTT0cxrXs6?authuser=6"> Demo On Google Colab <br></a>
</b>


<div align="center"></br><img src="images/example-1.png" width="900"/></div>

## How to use
1.   Click "Demo On Google Colab" in above.
2. When you are directed to Google Colab, please click "Runtime" > "Run all" in the menu bar.
   * The configuration steps may take a few minutes to run
3.   When the configuration is completed, scroll to the bottom of the webpage. Enjoy the chatting :)

## Customization

#### Prerequisite
* Any text editor that can be used to edit the CSV file (e.g., Excel, Visual Studio Code, Notebook and etc) 
<h1 align="center">
<b>Customization</b>
</h1>

<h2 align="center">
<b>Opener/ Username Identification/ Initial Greeting</b>
</h2>

1. Go to "Opener" section
2. Insert/ Delete the content in the Input Field.

> <h4><b>INSERT EXAMPLE</b></h4>        

>> **ORIGINAL👇**

>>>        初次見面，點稱呼呀？ | Hello，點稱呼呀？

>> **INSERT "Halo!!!"👇**

>>>        初次見面，點稱呼呀？ | Hello，點稱呼呀？| Halo!!!

</br>

> <h4><b>DELETE EXAMPLE</b></h4>

>> **ORIGINAL👇**

>>>        初次見面，點稱呼呀？ | Hello，點稱呼呀？| 你好呀，你叫咩名？

>> **DELETE "你好呀，你叫咩名？"👇**

>>>        初次見面，點稱呼呀？ | Hello，點稱呼呀？

3. Click "Update Opener"/ "Update Username Identification"/ "Update Initial Greeting"
4. If you wanna reset the candidates, click "Reset Opener"/ "Reset Username Identification"/ "Reset Initial Greeting"

<h2 align="center">
<b>Keyword</b>
</h2>

1. Go to "Keyword Customization" section
2. Click "Download Keywords' List"
3. Unzipping the file and you can customize the keyword file that you want to modifiy.
4. When you finished the customization, save and upload it by dragging the file to the "Files" section at the left side of Colab. 


<h2 align="center">
<b>Candidates Pool</b>
</h2>

1. Go to the "Candidates Pool Customization" Section
2. Click "Download Candidates Pool" button to get the "candidates.csv" file.
3. Please refer to the same process at Keywords customization
4. When the upload is finished, please click the "Update Candidates" button to update the candidates pool.


